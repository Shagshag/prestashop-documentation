ConnectionCore
===============






* Class name: ConnectionCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Connection.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#27)





Properties
----------


### $id_guest

    public integer $id_guest





* Visibility: **public**
* This property is defined in [classes/Connection.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#30)


### $id_page

    public integer $id_page





* Visibility: **public**
* This property is defined in [classes/Connection.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#33)


### $ip_address

    public string $ip_address





* Visibility: **public**
* This property is defined in [classes/Connection.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#36)


### $http_referer

    public string $http_referer





* Visibility: **public**
* This property is defined in [classes/Connection.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#39)


### $id_shop

    public integer $id_shop





* Visibility: **public**
* This property is defined in [classes/Connection.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#42)


### $id_shop_group

    public integer $id_shop_group





* Visibility: **public**
* This property is defined in [classes/Connection.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#45)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Connection.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#48)


### $definition

    public mixed $definition = array('table' => 'connections', 'primary' => 'id_connections', 'fields' => array('id_guest' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_page' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'ip_address' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Connection.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#53)


Methods
-------


### getFields

    array ConnectionCore::getFields()





* Visibility: **public**
* This method is defined in [classes/Connection.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#71)




### setPageConnection

    mixed ConnectionCore::setPageConnection($cookie, $full)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#81)


#### Arguments
* $cookie **mixed**
* $full **mixed**



### setNewConnection

    mixed ConnectionCore::setNewConnection($cookie)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#115)


#### Arguments
* $cookie **mixed**



### setPageTime

    mixed ConnectionCore::setPageTime($id_connections, $id_page, $time_start, $time)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#164)


#### Arguments
* $id_connections **mixed**
* $id_page **mixed**
* $time_start **mixed**
* $time **mixed**



### cleanConnectionsPages

    mixed ConnectionCore::cleanConnectionsPages()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#184)



