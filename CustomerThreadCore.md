CustomerThreadCore
===============






* Class name: CustomerThreadCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/CustomerThread.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L27)





Properties
----------

* [$id](#property-$id)
* [$id_shop](#property-$id_shop)
* [$id_lang](#property-$id_lang)
* [$id_contact](#property-$id_contact)
* [$id_customer](#property-$id_customer)
* [$id_order](#property-$id_order)
* [$id_product](#property-$id_product)
* [$status](#property-$status)
* [$email](#property-$email)
* [$token](#property-$token)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [getWsCustomerMessages](#method-getWsCustomerMessages)
* [delete](#method-delete)
* [getCustomerMessages](#method-getCustomerMessages)
* [getIdCustomerThreadByEmailAndIdOrder](#method-getIdCustomerThreadByEmailAndIdOrder)
* [getContacts](#method-getContacts)
* [getTotalCustomerThreads](#method-getTotalCustomerThreads)
* [getMessageCustomerThreads](#method-getMessageCustomerThreads)
* [getNextThread](#method-getNextThread)




Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L29)


### <a name="property-$id_shop"></a>$id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L30)


### <a name="property-$id_lang"></a>$id_lang

    public mixed $id_lang





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L31)


### <a name="property-$id_contact"></a>$id_contact

    public mixed $id_contact





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L32)


### <a name="property-$id_customer"></a>$id_customer

    public mixed $id_customer





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L33)


### <a name="property-$id_order"></a>$id_order

    public mixed $id_order





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L34)


### <a name="property-$id_product"></a>$id_product

    public mixed $id_product





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L35)


### <a name="property-$status"></a>$status

    public mixed $status





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L36)


### <a name="property-$email"></a>$email

    public mixed $email





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L37)


### <a name="property-$token"></a>$token

    public mixed $token





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L38)


### <a name="property-$date_add"></a>$date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L39)


### <a name="property-$date_upd"></a>$date_upd

    public mixed $date_upd





* Visibility: **public**
* This property is defined in [classes/CustomerThread.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L40)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'customer_thread', 'primary' => 'id_customer_thread', 'fields' => array('id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_contact' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 254), 'token' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'status' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/CustomerThread.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L45)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_order' => array('xlink_resource' => 'orders'), 'id_product' => array('xlink_resource' => 'products')), 'associations' => array('customer_messages' => array('resource' => 'customer_message', 'id' => array('required' => true))))





* Visibility: **protected**
* This property is defined in [classes/CustomerThread.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L63)


Methods
-------


### <a name="method-getWsCustomerMessages"></a>getWsCustomerMessages

    mixed CustomerThreadCore::getWsCustomerMessages()





* Visibility: **public**
* This method is defined in [classes/CustomerThread.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L88)




### <a name="method-delete"></a>delete

    mixed CustomerThreadCore::delete()





* Visibility: **public**
* This method is defined in [classes/CustomerThread.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L96)




### <a name="method-getCustomerMessages"></a>getCustomerMessages

    mixed CustomerThreadCore::getCustomerMessages($id_customer, $read, $id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerThread.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L123)


#### Arguments
* $id_customer **mixed**
* $read **mixed**
* $id_order **mixed**



### <a name="method-getIdCustomerThreadByEmailAndIdOrder"></a>getIdCustomerThreadByEmailAndIdOrder

    mixed CustomerThreadCore::getIdCustomerThreadByEmailAndIdOrder($email, $id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerThread.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L141)


#### Arguments
* $email **mixed**
* $id_order **mixed**



### <a name="method-getContacts"></a>getContacts

    mixed CustomerThreadCore::getContacts()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerThread.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L152)




### <a name="method-getTotalCustomerThreads"></a>getTotalCustomerThreads

    mixed CustomerThreadCore::getTotalCustomerThreads($where)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerThread.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L174)


#### Arguments
* $where **mixed**



### <a name="method-getMessageCustomerThreads"></a>getMessageCustomerThreads

    mixed CustomerThreadCore::getMessageCustomerThreads($id_customer_thread)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerThread.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L191)


#### Arguments
* $id_customer_thread **mixed**



### <a name="method-getNextThread"></a>getNextThread

    mixed CustomerThreadCore::getNextThread($id_customer_thread)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerThread.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerThread.php#L210)


#### Arguments
* $id_customer_thread **mixed**


