Class StateCore
=====================





* Class name: StateCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/State.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$definition](#property-$definition)
* [$id_country](#property-$id_country)
* [$id_zone](#property-$id_zone)
* [$iso_code](#property-$iso_code)
* [$name](#property-$name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [affectZoneToSelection](#method-affectZoneToSelection)
* [countUsed](#method-countUsed)
* [delete](#method-delete)
* [getIdByIso](#method-getIdByIso)
* [getIdByName](#method-getIdByName)
* [getIdZone](#method-getIdZone)
* [getNameById](#method-getNameById)
* [getStates](#method-getStates)
* [getStatesByIdCountry](#method-getStatesByIdCountry)
* [hasCounties](#method-hasCounties)
* [isUsed](#method-isUsed)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/State.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L42).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'state', 'primary' => 'id_state', 'fields' => array('id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_zone' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isStateIsoCode', 'required' => true, 'size' => 7), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/State.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L47).


### <a name="property-$id_country"></a>$id_country

```php
public integer $id_country
```





* Visibility: **public**
* Source: [classes/State.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L30).


### <a name="property-$id_zone"></a>$id_zone

```php
public integer $id_zone
```





* Visibility: **public**
* Source: [classes/State.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L33).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/State.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L36).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/State.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L39).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_zone' => array('xlink_resource' => 'zones'), 'id_country' => array('xlink_resource' => 'countries')))
```





* Visibility: **protected**
* Source: [classes/State.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L59).


Methods
-------


### <a name="method-affectZoneToSelection"></a>affectZoneToSelection

```php
boolean StateCore::affectZoneToSelection($ids_states, $id_zone)
```





* Visibility: **public**
* Source: [classes/State.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L218)


#### Arguments
* $ids_states **mixed**
* $id_zone **mixed**



### <a name="method-countUsed"></a>countUsed

```php
integer StateCore::countUsed()
```

Returns the number of utilisation of a state



* Visibility: **public**
* Source: [classes/State.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L174)




### <a name="method-delete"></a>delete

```php
boolean StateCore::delete()
```

Delete a state only if is not in use



* Visibility: **public**
* Source: [classes/State.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L141)




### <a name="method-getIdByIso"></a>getIdByIso

```php
integer StateCore::getIdByIso(string $iso_code, $id_country)
```

Get a state id with its iso code



* Visibility: **public**
* This method is **static**.
* Source: [classes/State.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L127)


#### Arguments
* $iso_code **string** - Iso code
* $id_country **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer StateCore::getIdByName($state)
```

Get a state id with its name



* Visibility: **public**
* This method is **static**.
* Source: [classes/State.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L104)


#### Arguments
* $state **mixed**



### <a name="method-getIdZone"></a>getIdZone

```php
mixed StateCore::getIdZone($id_state)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/State.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L201)


#### Arguments
* $id_state **mixed**



### <a name="method-getNameById"></a>getNameById

```php
string StateCore::getNameById(integer $id_state)
```

Get a state name with its ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/State.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L81)


#### Arguments
* $id_state **integer** - Country ID



### <a name="method-getStates"></a>getStates

```php
mixed StateCore::getStates($id_lang, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/State.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L66)


#### Arguments
* $id_lang **mixed**
* $active **mixed**



### <a name="method-getStatesByIdCountry"></a>getStatesByIdCountry

```php
mixed StateCore::getStatesByIdCountry($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/State.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L184)


#### Arguments
* $id_country **mixed**



### <a name="method-hasCounties"></a>hasCounties

```php
mixed StateCore::hasCounties($id_state)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/State.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L196)


#### Arguments
* $id_state **mixed**



### <a name="method-isUsed"></a>isUsed

```php
boolean StateCore::isUsed()
```

Check if a state is used



* Visibility: **public**
* Source: [classes/State.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/State.php#L164)



