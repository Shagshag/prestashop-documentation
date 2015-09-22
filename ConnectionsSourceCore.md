ConnectionsSourceCore
===============






* Class name: ConnectionsSourceCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\ConnectionsSource.php line 27





Properties
----------


### $id_connections

    public mixed $id_connections





* Visibility: **public**
* This property is defined in classes\ConnectionsSource.php line 29


### $http_referer

    public mixed $http_referer





* Visibility: **public**
* This property is defined in classes\ConnectionsSource.php line 30


### $request_uri

    public mixed $request_uri





* Visibility: **public**
* This property is defined in classes\ConnectionsSource.php line 31


### $keywords

    public mixed $keywords





* Visibility: **public**
* This property is defined in classes\ConnectionsSource.php line 32


### $date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in classes\ConnectionsSource.php line 33


### $uri_max_size

    public mixed $uri_max_size = 255





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\ConnectionsSource.php line 34


### $definition

    public mixed $definition = array('table' => 'connections_source', 'primary' => 'id_connections_source', 'fields' => array('id_connections' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'request_uri' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'keywords' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\ConnectionsSource.php line 39


Methods
-------


### add

    mixed ConnectionsSourceCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in classes\ConnectionsSource.php line 51


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### logHttpReferer

    mixed ConnectionsSourceCore::logHttpReferer(\Cookie $cookie)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConnectionsSource.php line 59


#### Arguments
* $cookie **[Cookie](CookieCore)**



### getOrderSources

    mixed ConnectionsSourceCore::getOrderSources($id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConnectionsSource.php line 108


#### Arguments
* $id_order **mixed**


