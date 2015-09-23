Class CountyCore
=====================





* Class name: CountyCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* Source: [classes/County.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L31)


Contents
--------

### Constants

* [USE_BOTH_TAX](#constant-USE_BOTH_TAX)
* [USE_COUNTY_TAX](#constant-USE_COUNTY_TAX)
* [USE_STATE_TAX](#constant-USE_STATE_TAX)

### Properties

* [$_cache_county_zipcode](#property-$_cache_county_zipcode)
* [$_cache_get_counties](#property-$_cache_get_counties)
* [$active](#property-$active)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_state](#property-$id_state)
* [$name](#property-$name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [addZipCodes](#method-addZipCodes)
* [breakDownZipCode](#method-breakDownZipCode)
* [delete](#method-delete)
* [deleteZipCodeByIdCounty](#method-deleteZipCodeByIdCounty)
* [getCounties](#method-getCounties)
* [getIdCountyByNameAndIdState](#method-getIdCountyByNameAndIdState)
* [getIdCountyByZipCode](#method-getIdCountyByZipCode)
* [getZipCodes](#method-getZipCodes)
* [isZipCodePresent](#method-isZipCodePresent)
* [isZipCodeRangePresent](#method-isZipCodeRangePresent)
* [removeZipCodes](#method-removeZipCodes)


Constants
----------


### <a name="constant-USE_BOTH_TAX"></a>USE_BOTH_TAX

```php
const USE_BOTH_TAX = 0
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/County.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L54).


### <a name="constant-USE_COUNTY_TAX"></a>USE_COUNTY_TAX

```php
const USE_COUNTY_TAX = 1
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/County.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L55).


### <a name="constant-USE_STATE_TAX"></a>USE_STATE_TAX

```php
const USE_STATE_TAX = 2
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/County.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L56).


Properties
----------


### <a name="property-$_cache_county_zipcode"></a>$_cache_county_zipcode

```php
protected mixed $_cache_county_zipcode = array()
```





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* Source: [classes/County.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L52).


### <a name="property-$_cache_get_counties"></a>$_cache_get_counties

```php
protected mixed $_cache_get_counties = array()
```





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* Source: [classes/County.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L51).


### <a name="property-$active"></a>$active

```php
public mixed $active
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/County.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L36).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'county', 'primary' => 'id_county', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* Source: [classes/County.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L41).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/County.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L33).


### <a name="property-$id_state"></a>$id_state

```php
public mixed $id_state
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/County.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L35).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/County.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L34).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_state' => array('xlink_resource' => 'states')))
```





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/County.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L58).


Methods
-------


### <a name="method-addZipCodes"></a>addZipCodes

```php
mixed CountyCore::addZipCodes($zip_codes)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L90)


#### Arguments
* $zip_codes **mixed**



### <a name="method-breakDownZipCode"></a>breakDownZipCode

```php
mixed CountyCore::breakDownZipCode($zip_codes)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L108)


#### Arguments
* $zip_codes **mixed**



### <a name="method-delete"></a>delete

```php
mixed CountyCore::delete()
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L64)




### <a name="method-deleteZipCodeByIdCounty"></a>deleteZipCodeByIdCounty

```php
mixed CountyCore::deleteZipCodeByIdCounty($id_county)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L144)


#### Arguments
* $id_county **mixed**



### <a name="method-getCounties"></a>getCounties

```php
mixed CountyCore::getCounties($id_state)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L72)


#### Arguments
* $id_state **mixed**



### <a name="method-getIdCountyByNameAndIdState"></a>getIdCountyByNameAndIdState

```php
mixed CountyCore::getIdCountyByNameAndIdState($name, $id_state)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L153)


#### Arguments
* $name **mixed**
* $id_state **mixed**



### <a name="method-getIdCountyByZipCode"></a>getIdCountyByZipCode

```php
mixed CountyCore::getIdCountyByZipCode($id_state, $zip_code)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L117)


#### Arguments
* $id_state **mixed**
* $zip_code **mixed**



### <a name="method-getZipCodes"></a>getZipCodes

```php
mixed CountyCore::getZipCodes()
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L81)




### <a name="method-isZipCodePresent"></a>isZipCodePresent

```php
mixed CountyCore::isZipCodePresent($zip_code)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L135)


#### Arguments
* $zip_code **mixed**



### <a name="method-isZipCodeRangePresent"></a>isZipCodeRangePresent

```php
mixed CountyCore::isZipCodeRangePresent($zip_codes)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L126)


#### Arguments
* $zip_codes **mixed**



### <a name="method-removeZipCodes"></a>removeZipCodes

```php
mixed CountyCore::removeZipCodes($zip_codes)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/County.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/County.php#L99)


#### Arguments
* $zip_codes **mixed**


