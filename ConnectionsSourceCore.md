ConnectionsSourceCore
===============






* Class name: ConnectionsSourceCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/ConnectionsSource.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L27)





Properties
----------

* [$id_connections](#property-$id_connections)
* [$http_referer](#property-$http_referer)
* [$request_uri](#property-$request_uri)
* [$keywords](#property-$keywords)
* [$date_add](#property-$date_add)
* [$uri_max_size](#property-$uri_max_size)
* [$definition](#property-$definition)

Methods
-------
* [add](#method-add)
* [logHttpReferer](#method-logHttpReferer)
* [getOrderSources](#method-getOrderSources)




Properties
----------


### <a name="property-$id_connections"></a>$id_connections

    public mixed $id_connections





* Visibility: **public**
* This property is defined in [classes/ConnectionsSource.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L29)


### <a name="property-$http_referer"></a>$http_referer

    public mixed $http_referer





* Visibility: **public**
* This property is defined in [classes/ConnectionsSource.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L30)


### <a name="property-$request_uri"></a>$request_uri

    public mixed $request_uri





* Visibility: **public**
* This property is defined in [classes/ConnectionsSource.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L31)


### <a name="property-$keywords"></a>$keywords

    public mixed $keywords





* Visibility: **public**
* This property is defined in [classes/ConnectionsSource.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L32)


### <a name="property-$date_add"></a>$date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in [classes/ConnectionsSource.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L33)


### <a name="property-$uri_max_size"></a>$uri_max_size

    public mixed $uri_max_size = 255





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/ConnectionsSource.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L34)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'connections_source', 'primary' => 'id_connections_source', 'fields' => array('id_connections' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'request_uri' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'keywords' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/ConnectionsSource.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L39)


Methods
-------


### <a name="method-add"></a>add

    mixed ConnectionsSourceCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/ConnectionsSource.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L51)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-logHttpReferer"></a>logHttpReferer

    mixed ConnectionsSourceCore::logHttpReferer(\Cookie $cookie)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConnectionsSource.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L59)


#### Arguments
* $cookie **[Cookie](CookieCore)**



### <a name="method-getOrderSources"></a>getOrderSources

    mixed ConnectionsSourceCore::getOrderSources($id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConnectionsSource.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConnectionsSource.php#L108)


#### Arguments
* $id_order **mixed**


