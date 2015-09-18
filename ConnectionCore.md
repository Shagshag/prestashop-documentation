ConnectionCore
===============






* Class name: ConnectionCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_guest

    public integer $id_guest





* Visibility: **public**


### $id_page

    public integer $id_page





* Visibility: **public**


### $ip_address

    public string $ip_address





* Visibility: **public**


### $http_referer

    public string $http_referer





* Visibility: **public**


### $id_shop

    public integer $id_shop





* Visibility: **public**


### $id_shop_group

    public integer $id_shop_group





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'connections', 'primary' => 'id_connections', 'fields' => array('id_guest' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_page' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'ip_address' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getFields

    array ConnectionCore::getFields()





* Visibility: **public**




### setPageConnection

    mixed ConnectionCore::setPageConnection($cookie, $full)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cookie **mixed**
* $full **mixed**



### setNewConnection

    mixed ConnectionCore::setNewConnection($cookie)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cookie **mixed**



### setPageTime

    mixed ConnectionCore::setPageTime($id_connections, $id_page, $time_start, $time)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_connections **mixed**
* $id_page **mixed**
* $time_start **mixed**
* $time **mixed**



### cleanConnectionsPages

    mixed ConnectionCore::cleanConnectionsPages()





* Visibility: **public**
* This method is **static**.



