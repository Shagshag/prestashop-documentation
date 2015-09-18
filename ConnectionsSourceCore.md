ConnectionsSourceCore
===============






* Class name: ConnectionsSourceCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_connections

    public mixed $id_connections





* Visibility: **public**


### $http_referer

    public mixed $http_referer





* Visibility: **public**


### $request_uri

    public mixed $request_uri





* Visibility: **public**


### $keywords

    public mixed $keywords





* Visibility: **public**


### $date_add

    public mixed $date_add





* Visibility: **public**


### $uri_max_size

    public mixed $uri_max_size = 255





* Visibility: **public**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'connections_source', 'primary' => 'id_connections_source', 'fields' => array('id_connections' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'request_uri' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'keywords' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### add

    mixed ConnectionsSourceCore::add($autodate, $nullValues)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### logHttpReferer

    mixed ConnectionsSourceCore::logHttpReferer(\Cookie $cookie)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cookie **Cookie**



### getOrderSources

    mixed ConnectionsSourceCore::getOrderSources($id_order)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **mixed**


