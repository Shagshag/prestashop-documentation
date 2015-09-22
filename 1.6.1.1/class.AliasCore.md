Class AliasCore
=====================





* Class name: AliasCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/Alias.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L27)



Properties
----------

* [$active](#property-$active)
* [$alias](#property-$alias)
* [$definition](#property-$definition)
* [$search](#property-$search)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [aliasExists](#method-aliasExists)
* [delete](#method-delete)
* [getAliases](#method-getAliases)
* [isFeatureActive](#method-isFeatureActive)




Properties
----------


### <a name="property-$active"></a>$active

    public mixed $active = true





* Visibility: **public**
* Source: [classes/Alias.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L31)


### <a name="property-$alias"></a>$alias

    public mixed $alias





* Visibility: **public**
* Source: [classes/Alias.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L29)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'alias', 'primary' => 'id_alias', 'fields' => array('search' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'alias' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Alias.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L36)


### <a name="property-$search"></a>$search

    public mixed $search





* Visibility: **public**
* Source: [classes/Alias.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AliasCore::__construct($id, $alias, $search, $id_lang)





* Visibility: **public**
* Source: [classes/Alias.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L46)


#### Arguments
* $id **mixed**
* $alias **mixed**
* $search **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

    mixed AliasCore::add($autodate, $nullValues)





* Visibility: **public**
* Source: [classes/Alias.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L76)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-aliasExists"></a>aliasExists

    boolean AliasCore::aliasExists($id_alias)

This method is allow to know if a alias exist for AdminImportController



* Visibility: **public**
* This method is **static**.
* Source: [classes/Alias.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L129)


#### Arguments
* $id_alias **mixed**



### <a name="method-delete"></a>delete

    mixed AliasCore::delete()





* Visibility: **public**
* Source: [classes/Alias.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L89)




### <a name="method-getAliases"></a>getAliases

    mixed AliasCore::getAliases()





* Visibility: **public**
* Source: [classes/Alias.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L99)




### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean AliasCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Alias.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Alias.php#L119)



