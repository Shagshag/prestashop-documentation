CustomerThreadCore
===============






* Class name: CustomerThreadCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_shop

    public mixed $id_shop





* Visibility: **public**


### $id_lang

    public mixed $id_lang





* Visibility: **public**


### $id_contact

    public mixed $id_contact





* Visibility: **public**


### $id_customer

    public mixed $id_customer





* Visibility: **public**


### $id_order

    public mixed $id_order





* Visibility: **public**


### $id_product

    public mixed $id_product





* Visibility: **public**


### $status

    public mixed $status





* Visibility: **public**


### $email

    public mixed $email





* Visibility: **public**


### $token

    public mixed $token





* Visibility: **public**


### $date_add

    public mixed $date_add





* Visibility: **public**


### $date_upd

    public mixed $date_upd





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'customer_thread', 'primary' => 'id_customer_thread', 'fields' => array('id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_contact' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 254), 'token' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'status' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_order' => array('xlink_resource' => 'orders'), 'id_product' => array('xlink_resource' => 'products')), 'associations' => array('customer_messages' => array('resource' => 'customer_message', 'id' => array('required' => true))))





* Visibility: **protected**


Methods
-------


### getWsCustomerMessages

    mixed CustomerThreadCore::getWsCustomerMessages()





* Visibility: **public**




### delete

    mixed CustomerThreadCore::delete()





* Visibility: **public**




### getCustomerMessages

    mixed CustomerThreadCore::getCustomerMessages($id_customer, $read, $id_order)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $read **mixed**
* $id_order **mixed**



### getIdCustomerThreadByEmailAndIdOrder

    mixed CustomerThreadCore::getIdCustomerThreadByEmailAndIdOrder($email, $id_order)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $email **mixed**
* $id_order **mixed**



### getContacts

    mixed CustomerThreadCore::getContacts()





* Visibility: **public**
* This method is **static**.




### getTotalCustomerThreads

    mixed CustomerThreadCore::getTotalCustomerThreads($where)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $where **mixed**



### getMessageCustomerThreads

    mixed CustomerThreadCore::getMessageCustomerThreads($id_customer_thread)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer_thread **mixed**



### getNextThread

    mixed CustomerThreadCore::getNextThread($id_customer_thread)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer_thread **mixed**


