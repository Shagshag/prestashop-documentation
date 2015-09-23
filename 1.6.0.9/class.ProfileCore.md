Class ProfileCore
=====================





* Class name: ProfileCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Profile.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L27)


Contents
--------


### Properties

* [$_cache_accesses](#property-$_cache_accesses)
* [$definition](#property-$definition)
* [$name](#property-$name)

### Methods

* [add](#method-add)
* [delete](#method-delete)
* [getProfile](#method-getProfile)
* [getProfileAccess](#method-getProfileAccess)
* [getProfileAccesses](#method-getProfileAccesses)
* [getProfiles](#method-getProfiles)




Properties
----------


### <a name="property-$_cache_accesses"></a>$_cache_accesses

```php
protected mixed $_cache_accesses = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Profile.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L45).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'profile', 'primary' => 'id_profile', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Profile.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L35).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Profile.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L30).


Methods
-------


### <a name="method-add"></a>add

```php
mixed ProfileCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Profile.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L80)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-delete"></a>delete

```php
mixed ProfileCore::delete()
```





* Visibility: **public**
* Source: [classes/Profile.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L95)




### <a name="method-getProfile"></a>getProfile

```php
string ProfileCore::getProfile($id_profile, $id_lang)
```

Get the current profile name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Profile.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L66)


#### Arguments
* $id_profile **mixed**
* $id_lang **mixed**



### <a name="method-getProfileAccess"></a>getProfileAccess

```php
mixed ProfileCore::getProfileAccess($id_profile, $id_tab)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Profile.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L105)


#### Arguments
* $id_profile **mixed**
* $id_tab **mixed**



### <a name="method-getProfileAccesses"></a>getProfileAccesses

```php
mixed ProfileCore::getProfileAccesses($id_profile, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Profile.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L112)


#### Arguments
* $id_profile **mixed**
* $type **mixed**



### <a name="method-getProfiles"></a>getProfiles

```php
array ProfileCore::getProfiles($id_lang)
```

Get all available profiles



* Visibility: **public**
* This method is **static**.
* Source: [classes/Profile.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Profile.php#L52)


#### Arguments
* $id_lang **mixed**


