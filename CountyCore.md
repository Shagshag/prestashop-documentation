CountyCore
===============






* Class name: CountyCore
* Parent class: [ObjectModel](ObjectModelCore)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* This class is defined in [classes/County.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#L31)



Constants
----------


### USE_BOTH_TAX

    const USE_BOTH_TAX = 0



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/County.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#54)


### USE_COUNTY_TAX

    const USE_COUNTY_TAX = 1



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/County.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#55)


### USE_STATE_TAX

    const USE_STATE_TAX = 2



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/County.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#56)


Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#33)


### $name

    public mixed $name





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#34)


### $id_state

    public mixed $id_state





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#35)


### $active

    public mixed $active





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#36)


### $definition

    public mixed $definition = array('table' => 'county', 'primary' => 'id_county', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/County.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#41)


### $_cache_get_counties

    protected mixed $_cache_get_counties = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/County.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#51)


### $_cache_county_zipcode

    protected mixed $_cache_county_zipcode = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/County.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#52)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_state' => array('xlink_resource' => 'states')))





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/County.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#58)


Methods
-------


### delete

    mixed CountyCore::delete()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#64)




### getCounties

    mixed CountyCore::getCounties($id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#72)


#### Arguments
* $id_state **mixed**



### getZipCodes

    mixed CountyCore::getZipCodes()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#81)




### addZipCodes

    mixed CountyCore::addZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#90)


#### Arguments
* $zip_codes **mixed**



### removeZipCodes

    mixed CountyCore::removeZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#99)


#### Arguments
* $zip_codes **mixed**



### breakDownZipCode

    mixed CountyCore::breakDownZipCode($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#108)


#### Arguments
* $zip_codes **mixed**



### getIdCountyByZipCode

    mixed CountyCore::getIdCountyByZipCode($id_state, $zip_code)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#117)


#### Arguments
* $id_state **mixed**
* $zip_code **mixed**



### isZipCodeRangePresent

    mixed CountyCore::isZipCodeRangePresent($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#126)


#### Arguments
* $zip_codes **mixed**



### isZipCodePresent

    mixed CountyCore::isZipCodePresent($zip_code)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#135)


#### Arguments
* $zip_code **mixed**



### deleteZipCodeByIdCounty

    mixed CountyCore::deleteZipCodeByIdCounty($id_county)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#144)


#### Arguments
* $id_county **mixed**



### getIdCountyByNameAndIdState

    mixed CountyCore::getIdCountyByNameAndIdState($name, $id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/County.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/County.php#153)


#### Arguments
* $name **mixed**
* $id_state **mixed**


