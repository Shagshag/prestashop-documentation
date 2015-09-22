CountyCore
===============






* Class name: CountyCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* This class is defined in classes\County.php line 31



Constants
----------


### USE_BOTH_TAX

    const USE_BOTH_TAX = 0



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in classes\County.php line 54


### USE_COUNTY_TAX

    const USE_COUNTY_TAX = 1



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in classes\County.php line 55


### USE_STATE_TAX

    const USE_STATE_TAX = 2



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in classes\County.php line 56


Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in classes\County.php line 33


### $name

    public mixed $name





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in classes\County.php line 34


### $id_state

    public mixed $id_state





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in classes\County.php line 35


### $active

    public mixed $active





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in classes\County.php line 36


### $definition

    public mixed $definition = array('table' => 'county', 'primary' => 'id_county', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in classes\County.php line 41


### $_cache_get_counties

    protected mixed $_cache_get_counties = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in classes\County.php line 51


### $_cache_county_zipcode

    protected mixed $_cache_county_zipcode = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in classes\County.php line 52


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_state' => array('xlink_resource' => 'states')))





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in classes\County.php line 58


Methods
-------


### delete

    mixed CountyCore::delete()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 64




### getCounties

    mixed CountyCore::getCounties($id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 72


#### Arguments
* $id_state **mixed**



### getZipCodes

    mixed CountyCore::getZipCodes()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 81




### addZipCodes

    mixed CountyCore::addZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 90


#### Arguments
* $zip_codes **mixed**



### removeZipCodes

    mixed CountyCore::removeZipCodes($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 99


#### Arguments
* $zip_codes **mixed**



### breakDownZipCode

    mixed CountyCore::breakDownZipCode($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 108


#### Arguments
* $zip_codes **mixed**



### getIdCountyByZipCode

    mixed CountyCore::getIdCountyByZipCode($id_state, $zip_code)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 117


#### Arguments
* $id_state **mixed**
* $zip_code **mixed**



### isZipCodeRangePresent

    mixed CountyCore::isZipCodeRangePresent($zip_codes)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 126


#### Arguments
* $zip_codes **mixed**



### isZipCodePresent

    mixed CountyCore::isZipCodePresent($zip_code)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 135


#### Arguments
* $zip_code **mixed**



### deleteZipCodeByIdCounty

    mixed CountyCore::deleteZipCodeByIdCounty($id_county)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 144


#### Arguments
* $id_county **mixed**



### getIdCountyByNameAndIdState

    mixed CountyCore::getIdCountyByNameAndIdState($name, $id_state)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in classes\County.php line 153


#### Arguments
* $name **mixed**
* $id_state **mixed**


