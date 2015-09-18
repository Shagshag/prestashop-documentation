OrderStateCore
===============






* Class name: OrderStateCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### FLAG_NO_HIDDEN

    const FLAG_NO_HIDDEN = 1





### FLAG_LOGABLE

    const FLAG_LOGABLE = 2





### FLAG_DELIVERY

    const FLAG_DELIVERY = 4





### FLAG_SHIPPED

    const FLAG_SHIPPED = 8





### FLAG_PAID

    const FLAG_PAID = 16





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $template

    public string $template





* Visibility: **public**


### $send_email

    public boolean $send_email





* Visibility: **public**


### $module_name

    public mixed $module_name





* Visibility: **public**


### $invoice

    public boolean $invoice





* Visibility: **public**


### $color

    public string $color





* Visibility: **public**


### $unremovable

    public mixed $unremovable





* Visibility: **public**


### $logable

    public boolean $logable





* Visibility: **public**


### $delivery

    public boolean $delivery





* Visibility: **public**


### $hidden

    public boolean $hidden





* Visibility: **public**


### $shipped

    public boolean $shipped





* Visibility: **public**


### $paid

    public boolean $paid





* Visibility: **public**


### $pdf_invoice

    public boolean $pdf_invoice





* Visibility: **public**


### $pdf_delivery

    public boolean $pdf_delivery





* Visibility: **public**


### $deleted

    public boolean $deleted





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_state', 'primary' => 'id_order_state', 'multilang' => true, 'fields' => array('send_email' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'module_name' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName'), 'invoice' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'logable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipped' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'unremovable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delivery' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'hidden' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'paid' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pdf_delivery' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pdf_invoice' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'template' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isTplName', 'size' => 64)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('unremovable' => array(), 'delivery' => array(), 'hidden' => array()))





* Visibility: **protected**


Methods
-------


### getOrderStates

    array OrderStateCore::getOrderStates(integer $id_lang)

Get all available order statuses



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id for status name&lt;/p&gt;



### invoiceAvailable

    boolean OrderStateCore::invoiceAvailable(integer $id_order_state)

Check if we can make a invoice when order is in this state



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_state **integer** - &lt;p&gt;State ID&lt;/p&gt;



### isRemovable

    mixed OrderStateCore::isRemovable()





* Visibility: **public**



