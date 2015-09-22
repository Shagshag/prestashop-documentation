CustomerMessageCore
===============






* Class name: CustomerMessageCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/CustomerMessage.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#L27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#29)


### $id_customer_thread

    public mixed $id_customer_thread





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#30)


### $id_employee

    public mixed $id_employee





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#31)


### $message

    public mixed $message





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#32)


### $file_name

    public mixed $file_name





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#33)


### $ip_address

    public mixed $ip_address





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#34)


### $user_agent

    public mixed $user_agent





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#35)


### $private

    public mixed $private





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#36)


### $date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#37)


### $date_upd

    public mixed $date_upd





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#38)


### $read

    public mixed $read





* Visibility: **public**
* This property is defined in [classes/CustomerMessage.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#39)


### $definition

    public mixed $definition = array('table' => 'customer_message', 'primary' => 'id_customer_message', 'fields' => array('id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer_thread' => array('type' => self::TYPE_INT), 'ip_address' => array('type' => self::TYPE_STRING, 'validate' => 'isIp2Long', 'size' => 15), 'message' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 16777216), 'file_name' => array('type' => self::TYPE_STRING), 'user_agent' => array('type' => self::TYPE_STRING), 'private' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'read' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/CustomerMessage.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#44)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_customer_thread' => array('xlink_resource' => 'customer_threads')))





* Visibility: **protected**
* This property is defined in [classes/CustomerMessage.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#61)


Methods
-------


### getMessagesByOrderId

    mixed CustomerMessageCore::getMessagesByOrderId($id_order, $private)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerMessage.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#72)


#### Arguments
* $id_order **mixed**
* $private **mixed**



### getTotalCustomerMessages

    mixed CustomerMessageCore::getTotalCustomerMessages($where)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CustomerMessage.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#95)


#### Arguments
* $where **mixed**



### delete

    mixed CustomerMessageCore::delete()





* Visibility: **public**
* This method is defined in [classes/CustomerMessage.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomerMessage.php#114)



