Class CountryCore
=====================





* Class name: CountryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Country.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L27)


Contents
--------


### Properties

* [$_idZones](#property-$_idZones)
* [$active](#property-$active)
* [$cache_iso_by_id](#property-$cache_iso_by_id)
* [$call_prefix](#property-$call_prefix)
* [$contains_states](#property-$contains_states)
* [$definition](#property-$definition)
* [$display_tax_label](#property-$display_tax_label)
* [$id](#property-$id)
* [$id_currency](#property-$id_currency)
* [$id_zone](#property-$id_zone)
* [$iso_code](#property-$iso_code)
* [$name](#property-$name)
* [$need_identification_number](#property-$need_identification_number)
* [$need_zip_code](#property-$need_zip_code)
* [$webserviceParameters](#property-$webserviceParameters)
* [$zip_code_format](#property-$zip_code_format)

### Methods

* [add](#method-add)
* [addModuleRestrictions](#method-addModuleRestrictions)
* [affectZoneToSelection](#method-affectZoneToSelection)
* [checkZipCode](#method-checkZipCode)
* [containsStates](#method-containsStates)
* [delete](#method-delete)
* [getByIso](#method-getByIso)
* [getCountries](#method-getCountries)
* [getCountriesByIdShop](#method-getCountriesByIdShop)
* [getCountriesByZoneId](#method-getCountriesByZoneId)
* [getDefaultCountryId](#method-getDefaultCountryId)
* [getIdByName](#method-getIdByName)
* [getIdZone](#method-getIdZone)
* [getIsoById](#method-getIsoById)
* [getNameById](#method-getNameById)
* [getNeedZipCode](#method-getNeedZipCode)
* [getZipCodeFormat](#method-getZipCodeFormat)
* [isNeedDni](#method-isNeedDni)
* [isNeedDniByCountryId](#method-isNeedDniByCountryId)




Properties
----------


### <a name="property-$_idZones"></a>$_idZones

```php
protected mixed $_idZones = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Country.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L64).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Country.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L62).


### <a name="property-$cache_iso_by_id"></a>$cache_iso_by_id

```php
protected mixed $cache_iso_by_id = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Country.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L94).


### <a name="property-$call_prefix"></a>$call_prefix

```php
public integer $call_prefix
```





* Visibility: **public**
* Source: [classes/Country.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L41).


### <a name="property-$contains_states"></a>$contains_states

```php
public boolean $contains_states
```





* Visibility: **public**
* Source: [classes/Country.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L47).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'country', 'primary' => 'id_country', 'multilang' => true, 'fields' => array('id_zone' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'call_prefix' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'contains_states' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'need_identification_number' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'need_zip_code' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'zip_code_format' => array('type' => self::TYPE_STRING, 'validate' => 'isZipCodeFormat'), 'display_tax_label' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)), 'associations' => array('zone' => array('type' => self::HAS_ONE), 'currency' => array('type' => self::HAS_ONE)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Country.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L69).


### <a name="property-$display_tax_label"></a>$display_tax_label

```php
public boolean $display_tax_label = true
```





* Visibility: **public**
* Source: [classes/Country.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L59).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Country.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L29).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/Country.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L35).


### <a name="property-$id_zone"></a>$id_zone

```php
public integer $id_zone
```





* Visibility: **public**
* Source: [classes/Country.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L32).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/Country.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L38).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Country.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L44).


### <a name="property-$need_identification_number"></a>$need_identification_number

```php
public boolean $need_identification_number
```





* Visibility: **public**
* Source: [classes/Country.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L50).


### <a name="property-$need_zip_code"></a>$need_zip_code

```php
public boolean $need_zip_code
```





* Visibility: **public**
* Source: [classes/Country.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L53).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'countries', 'fields' => array('id_zone' => array('xlink_resource' => 'zones'), 'id_currency' => array('xlink_resource' => 'currencies')))
```





* Visibility: **protected**
* Source: [classes/Country.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L96).


### <a name="property-$zip_code_format"></a>$zip_code_format

```php
public string $zip_code_format
```





* Visibility: **public**
* Source: [classes/Country.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L56).


Methods
-------


### <a name="method-add"></a>add

```php
mixed CountryCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Country.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L377)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addModuleRestrictions"></a>addModuleRestrictions

```php
mixed CountryCore::addModuleRestrictions(array $shops, array $countries, array $modules)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L351)


#### Arguments
* $shops **array**
* $countries **array**
* $modules **array**



### <a name="method-affectZoneToSelection"></a>affectZoneToSelection

```php
boolean CountryCore::affectZoneToSelection($ids_countries, $id_zone)
```





* Visibility: **public**
* Source: [classes/Country.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L325)


#### Arguments
* $ids_countries **mixed**
* $id_zone **mixed**



### <a name="method-checkZipCode"></a>checkZipCode

```php
\(bool) CountryCore::checkZipCode($zip_code)
```

Replace letters of zip code format And check this format on the zip code



* Visibility: **public**
* Source: [classes/Country.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L339)


#### Arguments
* $zip_code **mixed**



### <a name="method-containsStates"></a>containsStates

```php
mixed CountryCore::containsStates($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L312)


#### Arguments
* $id_country **mixed**



### <a name="method-delete"></a>delete

```php
mixed CountryCore::delete()
```





* Visibility: **public**
* Source: [classes/Country.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L104)




### <a name="method-getByIso"></a>getByIso

```php
integer CountryCore::getByIso(string $iso_code)
```

Get a country ID with its iso code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L160)


#### Arguments
* $iso_code **string** - Country iso code



### <a name="method-getCountries"></a>getCountries

```php
Array CountryCore::getCountries(integer $id_lang, boolean $active, boolean $contain_states, boolean $list_states)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L121)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active coutries
* $contain_states **boolean** - return only country with states
* $list_states **boolean** - Include the states list with the returned list



### <a name="method-getCountriesByIdShop"></a>getCountriesByIdShop

```php
mixed CountryCore::getCountriesByIdShop($id_shop, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L144)


#### Arguments
* $id_shop **mixed**
* $id_lang **mixed**



### <a name="method-getCountriesByZoneId"></a>getCountriesByZoneId

```php
mixed CountryCore::getCountriesByZoneId($id_zone, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L284)


#### Arguments
* $id_zone **mixed**
* $id_lang **mixed**



### <a name="method-getDefaultCountryId"></a>getDefaultCountryId

```php
integer CountryCore::getDefaultCountryId()
```

Returns the default country Id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L278)




### <a name="method-getIdByName"></a>getIdByName

```php
\intval CountryCore::getIdByName(integer $id_lang, string $country)
```

Get a country id with its name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L236)


#### Arguments
* $id_lang **integer** - Language ID
* $country **string** - Country Name



### <a name="method-getIdZone"></a>getIdZone

```php
mixed CountryCore::getIdZone($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L172)


#### Arguments
* $id_country **mixed**



### <a name="method-getIsoById"></a>getIsoById

```php
string CountryCore::getIsoById(integer $id_country)
```

Get a country iso with its ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L216)


#### Arguments
* $id_country **integer** - Country ID



### <a name="method-getNameById"></a>getNameById

```php
string CountryCore::getNameById(integer $id_lang, integer $id_country)
```

Get a country name with its ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L196)


#### Arguments
* $id_lang **integer** - Language ID
* $id_country **integer** - Country ID



### <a name="method-getNeedZipCode"></a>getNeedZipCode

```php
mixed CountryCore::getNeedZipCode($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L250)


#### Arguments
* $id_country **mixed**



### <a name="method-getZipCodeFormat"></a>getZipCodeFormat

```php
mixed CountryCore::getZipCodeFormat($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L261)


#### Arguments
* $id_country **mixed**



### <a name="method-isNeedDni"></a>isNeedDni

```php
mixed CountryCore::isNeedDni()
```





* Visibility: **public**
* Source: [classes/Country.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L299)




### <a name="method-isNeedDniByCountryId"></a>isNeedDniByCountryId

```php
mixed CountryCore::isNeedDniByCountryId($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Country.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Country.php#L304)


#### Arguments
* $id_country **mixed**


