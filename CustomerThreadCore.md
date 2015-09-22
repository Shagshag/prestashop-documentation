CustomerThreadCore
===============






* Class name: CustomerThreadCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\CustomerThread.php line 27





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 29


### $id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 30


### $id_lang

    public mixed $id_lang





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 31


### $id_contact

    public mixed $id_contact





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 32


### $id_customer

    public mixed $id_customer





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 33


### $id_order

    public mixed $id_order





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 34


### $id_product

    public mixed $id_product





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 35


### $status

    public mixed $status





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 36


### $email

    public mixed $email





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 37


### $token

    public mixed $token





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 38


### $date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 39


### $date_upd

    public mixed $date_upd





* Visibility: **public**
* This property is defined in classes\CustomerThread.php line 40


### $definition

    public mixed $definition = array('table' => 'customer_thread', 'primary' => 'id_customer_thread', 'fields' => array('id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_contact' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 254), 'token' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'status' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\CustomerThread.php line 45


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_order' => array('xlink_resource' => 'orders'), 'id_product' => array('xlink_resource' => 'products')), 'associations' => array('customer_messages' => array('resource' => 'customer_message', 'id' => array('required' => true))))





* Visibility: **protected**
* This property is defined in classes\CustomerThread.php line 63


Methods
-------


### getWsCustomerMessages

    mixed CustomerThreadCore::getWsCustomerMessages()





* Visibility: **public**
* This method is defined in classes\CustomerThread.php line 88




### delete

    mixed CustomerThreadCore::delete()





* Visibility: **public**
* This method is defined in classes\CustomerThread.php line 96




### getCustomerMessages

    mixed CustomerThreadCore::getCustomerMessages($id_customer, $read, $id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CustomerThread.php line 123


#### Arguments
* $id_customer **mixed**
* $read **mixed**
* $id_order **mixed**



### getIdCustomerThreadByEmailAndIdOrder

    mixed CustomerThreadCore::getIdCustomerThreadByEmailAndIdOrder($email, $id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CustomerThread.php line 141


#### Arguments
* $email **mixed**
* $id_order **mixed**



### getContacts

    mixed CustomerThreadCore::getContacts()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CustomerThread.php line 152




### getTotalCustomerThreads

    mixed CustomerThreadCore::getTotalCustomerThreads($where)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CustomerThread.php line 174


#### Arguments
* $where **mixed**



### getMessageCustomerThreads

    mixed CustomerThreadCore::getMessageCustomerThreads($id_customer_thread)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CustomerThread.php line 191


#### Arguments
* $id_customer_thread **mixed**



### getNextThread

    mixed CustomerThreadCore::getNextThread($id_customer_thread)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CustomerThread.php line 210


#### Arguments
* $id_customer_thread **mixed**


