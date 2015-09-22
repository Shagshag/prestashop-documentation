AliasCore
===============






* Class name: AliasCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Alias.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#27)





Properties
----------


### $alias

    public mixed $alias





* Visibility: **public**
* This property is defined in [classes/Alias.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#29)


### $search

    public mixed $search





* Visibility: **public**
* This property is defined in [classes/Alias.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#30)


### $active

    public mixed $active = true





* Visibility: **public**
* This property is defined in [classes/Alias.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#31)


### $definition

    public mixed $definition = array('table' => 'alias', 'primary' => 'id_alias', 'fields' => array('search' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'alias' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Alias.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#36)


Methods
-------


### __construct

    mixed AliasCore::__construct($id, $alias, $search, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Alias.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#46)


#### Arguments
* $id **mixed**
* $alias **mixed**
* $search **mixed**
* $id_lang **mixed**



### add

    mixed AliasCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/Alias.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#76)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### delete

    mixed AliasCore::delete()





* Visibility: **public**
* This method is defined in [classes/Alias.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#89)




### getAliases

    mixed AliasCore::getAliases()





* Visibility: **public**
* This method is defined in [classes/Alias.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#99)




### isFeatureActive

    boolean AliasCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Alias.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#119)




### aliasExists

    boolean AliasCore::aliasExists($id_alias)

This method is allow to know if a alias exist for AdminImportController



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Alias.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#129)


#### Arguments
* $id_alias **mixed**


