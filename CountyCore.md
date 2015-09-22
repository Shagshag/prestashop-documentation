CountyCore
===============






* Class name: CountyCore
* Parent class: [ObjectModel](ObjectModelCore)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* This class is defined in [classes/County.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L31)



Constants
----------

* [USE_BOTH_TAX](#constant-USE_BOTH_TAX)
* [USE_COUNTY_TAX](#constant-USE_COUNTY_TAX)
* [USE_STATE_TAX](#constant-USE_STATE_TAX)

Properties
----------

* [$id](#property-$id)
* [$name](#property-$name)
* [$id_state](#property-$id_state)
* [$active](#property-$active)
* [$definition](#property-$definition)
* [$_cache_get_counties](#property-$_cache_get_counties)
* [$_cache_county_zipcode](#property-$_cache_county_zipcode)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [delete](#method-delete)
* [getCounties](#method-getCounties)
* [getZipCodes](#method-getZipCodes)
* [addZipCodes](#method-addZipCodes)
* [removeZipCodes](#method-removeZipCodes)
* [breakDownZipCode](#method-breakDownZipCode)
* [getIdCountyByZipCode](#method-getIdCountyByZipCode)
* [isZipCodeRangePresent](#method-isZipCodeRangePresent)
* [isZipCodePresent](#method-isZipCodePresent)
* [deleteZipCodeByIdCounty](#method-deleteZipCodeByIdCounty)
* [getIdCountyByNameAndIdState](#method-getIdCountyByNameAndIdState)


Constants
----------


### <a name="constant-USE_BOTH_TAX"></a>USE_BOTH_TAX

    const USE_BOTH_TAX = 0



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/County.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L54)


### <a name="constant-USE_COUNTY_TAX"></a>USE_COUNTY_TAX

    const USE_COUNTY_TAX = 1



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/County.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L55)


### <a name="constant-USE_STATE_TAX"></a>USE_STATE_TAX

    const USE_STATE_TAX = 2



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/County.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L56)


Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L33)


### <a name="property-$name"></a>$name

    public mixed $name





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L34)


### <a name="property-$id_state"></a>$id_state

    public mixed $id_state





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L35)


### <a name="property-$active"></a>$active

    public mixed $active





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L36)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'county', 'primary' => 'id_county', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/County.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L41)


### <a name="property-$_cache_get_counties"></a>$_cache_get_counties

    protected mixed $_cache_get_counties = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/County.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L51)


### <a name="property-$_cache_county_zipcode"></a>$_cache_county_zipcode

    protected mixed $_cache_county_zipcode = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/County.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L52)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_state' => array('xlink_resource' => 'states')))





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L58)


Methods
-------


### <a name="method-delete"></a>delete

    mixed CountyCore::delete()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L64)




### <a name="method-getCounties"></a>getCounties

    mixed CountyCore::getCounties($id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L72)


#### Arguments
* $id_state **mixed**



### <a name="method-getZipCodes"></a>getZipCodes

    mixed CountyCore::getZipCodes()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L81)




### <a name="method-addZipCodes"></a>addZipCodes

    mixed CountyCore::addZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L90)


#### Arguments
* $zip_codes **mixed**



### <a name="method-removeZipCodes"></a>removeZipCodes

    mixed CountyCore::removeZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L99)


#### Arguments
* $zip_codes **mixed**



### <a name="method-breakDownZipCode"></a>breakDownZipCode

    mixed CountyCore::breakDownZipCode($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L108)


#### Arguments
* $zip_codes **mixed**



### <a name="method-getIdCountyByZipCode"></a>getIdCountyByZipCode

    mixed CountyCore::getIdCountyByZipCode($id_state, $zip_code)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L117)


#### Arguments
* $id_state **mixed**
* $zip_code **mixed**



### <a name="method-isZipCodeRangePresent"></a>isZipCodeRangePresent

    mixed CountyCore::isZipCodeRangePresent($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L126)


#### Arguments
* $zip_codes **mixed**



### <a name="method-isZipCodePresent"></a>isZipCodePresent

    mixed CountyCore::isZipCodePresent($zip_code)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L135)


#### Arguments
* $zip_code **mixed**



### <a name="method-deleteZipCodeByIdCounty"></a>deleteZipCodeByIdCounty

    mixed CountyCore::deleteZipCodeByIdCounty($id_county)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L144)


#### Arguments
* $id_county **mixed**



### <a name="method-getIdCountyByNameAndIdState"></a>getIdCountyByNameAndIdState

    mixed CountyCore::getIdCountyByNameAndIdState($name, $id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L153)


#### Arguments
* $name **mixed**
* $id_state **mixed**


