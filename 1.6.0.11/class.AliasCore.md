Class AliasCore
=====================





* Class name: AliasCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Alias.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$alias](#property-$alias)
* [$definition](#property-$definition)
* [$search](#property-$search)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [aliasExists](#method-aliasExists)
* [delete](#method-delete)
* [getAliases](#method-getAliases)
* [isFeatureActive](#method-isFeatureActive)




Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active = true
```





* Visibility: **public**
* Source: [classes/Alias.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L31).


### <a name="property-$alias"></a>$alias

```php
public mixed $alias
```





* Visibility: **public**
* Source: [classes/Alias.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L29).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'alias', 'primary' => 'id_alias', 'fields' => array('search' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'alias' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Alias.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L36).


### <a name="property-$search"></a>$search

```php
public mixed $search
```





* Visibility: **public**
* Source: [classes/Alias.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AliasCore::__construct($id, $alias, $search, $id_lang)
```





* Visibility: **public**
* Source: [classes/Alias.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L46)


#### Arguments
* $id **mixed**
* $alias **mixed**
* $search **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed AliasCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/Alias.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L82)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-aliasExists"></a>aliasExists

```php
boolean AliasCore::aliasExists($id_alias)
```

This method is allow to know if a alias exist for AdminImportController



* Visibility: **public**
* This method is **static**.
* Source: [classes/Alias.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L133)


#### Arguments
* $id_alias **mixed**



### <a name="method-delete"></a>delete

```php
mixed AliasCore::delete()
```





* Visibility: **public**
* Source: [classes/Alias.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L93)




### <a name="method-getAliases"></a>getAliases

```php
mixed AliasCore::getAliases()
```





* Visibility: **public**
* Source: [classes/Alias.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L104)




### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean AliasCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Alias.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Alias.php#L123)



