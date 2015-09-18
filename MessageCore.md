MessageCore
===============






* Class name: MessageCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $message

    public string $message





* Visibility: **public**


### $id_cart

    public integer $id_cart





* Visibility: **public**


### $id_order

    public integer $id_order





* Visibility: **public**


### $id_customer

    public integer $id_customer





* Visibility: **public**


### $id_employee

    public integer $id_employee





* Visibility: **public**


### $private

    public boolean $private





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'message', 'primary' => 'id_message', 'fields' => array('message' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 1600), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'private' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getMessageByCartId

    array MessageCore::getMessageByCartId(integer $id_cart)

Return the last message from cart



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **integer** - &lt;p&gt;Cart ID&lt;/p&gt;



### getMessagesByOrderId

    array MessageCore::getMessagesByOrderId(integer $id_order, boolean $private, \Context $context)

Return messages from Order ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **integer** - &lt;p&gt;Order ID&lt;/p&gt;
* $private **boolean** - &lt;p&gt;return WITH private messages&lt;/p&gt;
* $context **Context**



### getMessagesByCartId

    array MessageCore::getMessagesByCartId($id_cart, boolean $private, \Context $context)

Return messages from Cart ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **mixed**
* $private **boolean** - &lt;p&gt;return WITH private messages&lt;/p&gt;
* $context **Context**



### markAsReaded

    mixed MessageCore::markAsReaded(integer $id_message, $id_employee)

Registered a message 'readed'



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_message **integer** - &lt;p&gt;Message ID&lt;/p&gt;
* $id_employee **mixed**


