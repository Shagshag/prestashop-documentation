CountyCore
===============






* Class name: CountyCore
* Namespace: 
* Parent class: ObjectModel
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.



Constants
----------


### USE_BOTH_TAX

    const USE_BOTH_TAX = 0



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.


### USE_COUNTY_TAX

    const USE_COUNTY_TAX = 1



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.


### USE_STATE_TAX

    const USE_STATE_TAX = 2



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.


Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $name

    public mixed $name





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $id_state

    public mixed $id_state





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $active

    public mixed $active





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $definition

    public mixed $definition = array('table' => 'county', 'primary' => 'id_county', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.


### $_cache_get_counties

    protected mixed $_cache_get_counties = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.


### $_cache_county_zipcode

    protected mixed $_cache_county_zipcode = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_state' => array('xlink_resource' => 'states')))





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


Methods
-------


### delete

    mixed CountyCore::delete()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.




### getCounties

    mixed CountyCore::getCounties($id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $id_state **mixed**



### getZipCodes

    mixed CountyCore::getZipCodes()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.




### addZipCodes

    mixed CountyCore::addZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $zip_codes **mixed**



### removeZipCodes

    mixed CountyCore::removeZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $zip_codes **mixed**



### breakDownZipCode

    mixed CountyCore::breakDownZipCode($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $zip_codes **mixed**



### getIdCountyByZipCode

    mixed CountyCore::getIdCountyByZipCode($id_state, $zip_code)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $id_state **mixed**
* $zip_code **mixed**



### isZipCodeRangePresent

    mixed CountyCore::isZipCodeRangePresent($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $zip_codes **mixed**



### isZipCodePresent

    mixed CountyCore::isZipCodePresent($zip_code)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $zip_code **mixed**



### deleteZipCodeByIdCounty

    mixed CountyCore::deleteZipCodeByIdCounty($id_county)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $id_county **mixed**



### getIdCountyByNameAndIdState

    mixed CountyCore::getIdCountyByNameAndIdState($name, $id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $name **mixed**
* $id_state **mixed**


