Class ZoneCore
=====================





* Class name: ZoneCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Zone.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$definition](#property-$definition)
* [$name](#property-$name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [delete](#method-delete)
* [getIdByName](#method-getIdByName)
* [getZones](#method-getZones)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Zone.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'zone', 'primary' => 'id_zone', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Zone.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L38).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Zone.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L30).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array()
```





* Visibility: **protected**
* Source: [classes/Zone.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L47).


Methods
-------


### <a name="method-delete"></a>delete

```php
boolean ZoneCore::delete()
```

Delete a zone



* Visibility: **public**
* Source: [classes/Zone.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L91)




### <a name="method-getIdByName"></a>getIdByName

```php
integer ZoneCore::getIdByName(string $name)
```

Get a zone ID from its default language name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Zone.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L77)


#### Arguments
* $name **string**



### <a name="method-getZones"></a>getZones

```php
array ZoneCore::getZones(boolean $active)
```

Get all available geographical zones



* Visibility: **public**
* This method is **static**.
* Source: [classes/Zone.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Zone.php#L55)


#### Arguments
* $active **boolean**


