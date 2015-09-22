SearchEngineCore
===============






* Class name: SearchEngineCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/SearchEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#27)





Properties
----------


### $server

    public mixed $server





* Visibility: **public**
* This property is defined in [classes/SearchEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#29)


### $getvar

    public mixed $getvar





* Visibility: **public**
* This property is defined in [classes/SearchEngine.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#30)


### $definition

    public mixed $definition = array('table' => 'search_engine', 'primary' => 'id_search_engine', 'fields' => array('server' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl', 'required' => true), 'getvar' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/SearchEngine.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#35)


Methods
-------


### getKeywords

    mixed SearchEngineCore::getKeywords($url)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SearchEngine.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#44)


#### Arguments
* $url **mixed**


