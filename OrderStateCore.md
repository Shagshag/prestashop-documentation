OrderStateCore
===============






* Class name: OrderStateCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/order/OrderState.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L27)



Constants
----------


### FLAG_NO_HIDDEN

    const FLAG_NO_HIDDEN = 1



* This constant is defined in [classes/order/OrderState.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#108)


### FLAG_LOGABLE

    const FLAG_LOGABLE = 2



* This constant is defined in [classes/order/OrderState.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#109)


### FLAG_DELIVERY

    const FLAG_DELIVERY = 4



* This constant is defined in [classes/order/OrderState.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#110)


### FLAG_SHIPPED

    const FLAG_SHIPPED = 8



* This constant is defined in [classes/order/OrderState.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#111)


### FLAG_PAID

    const FLAG_PAID = 16



* This constant is defined in [classes/order/OrderState.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#112)


Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#30)


### $template

    public string $template





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#33)


### $send_email

    public boolean $send_email





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#36)


### $module_name

    public mixed $module_name





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#38)


### $invoice

    public boolean $invoice





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#41)


### $color

    public string $color





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#44)


### $unremovable

    public mixed $unremovable





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#46)


### $logable

    public boolean $logable





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#49)


### $delivery

    public boolean $delivery





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#52)


### $hidden

    public boolean $hidden





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#55)


### $shipped

    public boolean $shipped





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#58)


### $paid

    public boolean $paid





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#61)


### $pdf_invoice

    public boolean $pdf_invoice





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#64)


### $pdf_delivery

    public boolean $pdf_delivery





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#67)


### $deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in [classes/order/OrderState.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#70)


### $definition

    public mixed $definition = array('table' => 'order_state', 'primary' => 'id_order_state', 'multilang' => true, 'fields' => array('send_email' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'module_name' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName'), 'invoice' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'logable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipped' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'unremovable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delivery' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'hidden' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'paid' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pdf_delivery' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pdf_invoice' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'template' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isTplName', 'size' => 64)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/order/OrderState.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#75)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('unremovable' => array(), 'delivery' => array(), 'hidden' => array()))





* Visibility: **protected**
* This property is defined in [classes/order/OrderState.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#100)


Methods
-------


### getOrderStates

    array OrderStateCore::getOrderStates(integer $id_lang)

Get all available order statuses



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/OrderState.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#120)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id for status name&lt;/p&gt;



### invoiceAvailable

    boolean OrderStateCore::invoiceAvailable(integer $id_order_state)

Check if we can make a invoice when order is in this state



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/OrderState.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#142)


#### Arguments
* $id_order_state **integer** - &lt;p&gt;State ID&lt;/p&gt;



### isRemovable

    mixed OrderStateCore::isRemovable()





* Visibility: **public**
* This method is defined in [classes/order/OrderState.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#154)



