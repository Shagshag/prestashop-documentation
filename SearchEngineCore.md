SearchEngineCore
===============






* Class name: SearchEngineCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/SearchEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#L27)





Properties
----------

* [$server](#property-$server)
* [$getvar](#property-$getvar)
* [$definition](#property-$definition)

Methods
-------
* [getKeywords](#method-getKeywords)




Properties
----------


### <a name="property-$server"></a>$server

    public mixed $server





* Visibility: **public**
* This property is defined in [classes/SearchEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#L29)


### <a name="property-$getvar"></a>$getvar

    public mixed $getvar





* Visibility: **public**
* This property is defined in [classes/SearchEngine.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#L30)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'search_engine', 'primary' => 'id_search_engine', 'fields' => array('server' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl', 'required' => true), 'getvar' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/SearchEngine.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#L35)


Methods
-------


### <a name="method-getKeywords"></a>getKeywords

    mixed SearchEngineCore::getKeywords($url)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SearchEngine.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SearchEngine.php#L44)


#### Arguments
* $url **mixed**


