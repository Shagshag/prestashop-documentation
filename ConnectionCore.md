ConnectionCore
===============






* Class name: ConnectionCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Connection.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L27)





Properties
----------

* [$id_guest](#property-$id_guest)
* [$id_page](#property-$id_page)
* [$ip_address](#property-$ip_address)
* [$http_referer](#property-$http_referer)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)

Methods
-------
* [getFields](#method-getFields)
* [setPageConnection](#method-setPageConnection)
* [setNewConnection](#method-setNewConnection)
* [setPageTime](#method-setPageTime)
* [cleanConnectionsPages](#method-cleanConnectionsPages)




Properties
----------


### <a name="property-$id_guest"></a>$id_guest

    public integer $id_guest





* Visibility: **public**
* This property is defined in [classes/Connection.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L30)


### <a name="property-$id_page"></a>$id_page

    public integer $id_page





* Visibility: **public**
* This property is defined in [classes/Connection.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L33)


### <a name="property-$ip_address"></a>$ip_address

    public string $ip_address





* Visibility: **public**
* This property is defined in [classes/Connection.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L36)


### <a name="property-$http_referer"></a>$http_referer

    public string $http_referer





* Visibility: **public**
* This property is defined in [classes/Connection.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L39)


### <a name="property-$id_shop"></a>$id_shop

    public integer $id_shop





* Visibility: **public**
* This property is defined in [classes/Connection.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L42)


### <a name="property-$id_shop_group"></a>$id_shop_group

    public integer $id_shop_group





* Visibility: **public**
* This property is defined in [classes/Connection.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L45)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Connection.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L48)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'connections', 'primary' => 'id_connections', 'fields' => array('id_guest' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_page' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'ip_address' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Connection.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L53)


Methods
-------


### <a name="method-getFields"></a>getFields

    array ConnectionCore::getFields()





* Visibility: **public**
* This method is defined in [classes/Connection.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L71)




### <a name="method-setPageConnection"></a>setPageConnection

    mixed ConnectionCore::setPageConnection($cookie, $full)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L81)


#### Arguments
* $cookie **mixed**
* $full **mixed**



### <a name="method-setNewConnection"></a>setNewConnection

    mixed ConnectionCore::setNewConnection($cookie)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L115)


#### Arguments
* $cookie **mixed**



### <a name="method-setPageTime"></a>setPageTime

    mixed ConnectionCore::setPageTime($id_connections, $id_page, $time_start, $time)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L164)


#### Arguments
* $id_connections **mixed**
* $id_page **mixed**
* $time_start **mixed**
* $time **mixed**



### <a name="method-cleanConnectionsPages"></a>cleanConnectionsPages

    mixed ConnectionCore::cleanConnectionsPages()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Connection.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Connection.php#L184)



