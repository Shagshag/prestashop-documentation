MessageCore
===============






* Class name: MessageCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Message.php line 27





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in classes\Message.php line 29


### $message

    public string $message





* Visibility: **public**
* This property is defined in classes\Message.php line 32


### $id_cart

    public integer $id_cart





* Visibility: **public**
* This property is defined in classes\Message.php line 35


### $id_order

    public integer $id_order





* Visibility: **public**
* This property is defined in classes\Message.php line 38


### $id_customer

    public integer $id_customer





* Visibility: **public**
* This property is defined in classes\Message.php line 41


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in classes\Message.php line 44


### $private

    public boolean $private





* Visibility: **public**
* This property is defined in classes\Message.php line 47


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in classes\Message.php line 50


### $definition

    public mixed $definition = array('table' => 'message', 'primary' => 'id_message', 'fields' => array('message' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 1600), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'private' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Message.php line 55


Methods
-------


### getMessageByCartId

    array MessageCore::getMessageByCartId(integer $id_cart)

Return the last message from cart



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Message.php line 75


#### Arguments
* $id_cart **integer** - &lt;p&gt;Cart ID&lt;/p&gt;



### getMessagesByOrderId

    array MessageCore::getMessagesByOrderId(integer $id_order, boolean $private, \Context $context)

Return messages from Order ID



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Message.php line 91


#### Arguments
* $id_order **integer** - &lt;p&gt;Order ID&lt;/p&gt;
* $private **boolean** - &lt;p&gt;return WITH private messages&lt;/p&gt;
* $context **[Context](ContextCore)**



### getMessagesByCartId

    array MessageCore::getMessagesByCartId($id_cart, boolean $private, \Context $context)

Return messages from Cart ID



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Message.php line 124


#### Arguments
* $id_cart **mixed**
* $private **boolean** - &lt;p&gt;return WITH private messages&lt;/p&gt;
* $context **[Context](ContextCore)**



### markAsReaded

    mixed MessageCore::markAsReaded(integer $id_message, $id_employee)

Registered a message 'readed'



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Message.php line 154


#### Arguments
* $id_message **integer** - &lt;p&gt;Message ID&lt;/p&gt;
* $id_employee **mixed**


