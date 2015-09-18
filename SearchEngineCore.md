SearchEngineCore
===============






* Class name: SearchEngineCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $server

    public mixed $server





* Visibility: **public**


### $getvar

    public mixed $getvar





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'search_engine', 'primary' => 'id_search_engine', 'fields' => array('server' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl', 'required' => true), 'getvar' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getKeywords

    mixed SearchEngineCore::getKeywords($url)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **mixed**


