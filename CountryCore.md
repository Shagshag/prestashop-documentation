CountryCore
===============






* Class name: CountryCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_zone

    public integer $id_zone





* Visibility: **public**


### $id_currency

    public integer $id_currency





* Visibility: **public**


### $iso_code

    public string $iso_code





* Visibility: **public**


### $call_prefix

    public integer $call_prefix





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $contains_states

    public boolean $contains_states





* Visibility: **public**


### $need_identification_number

    public boolean $need_identification_number





* Visibility: **public**


### $need_zip_code

    public boolean $need_zip_code





* Visibility: **public**


### $zip_code_format

    public string $zip_code_format





* Visibility: **public**


### $display_tax_label

    public boolean $display_tax_label = true





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $_idZones

    protected mixed $_idZones = array()





* Visibility: **protected**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'country', 'primary' => 'id_country', 'multilang' => true, 'fields' => array('id_zone' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'call_prefix' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'contains_states' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'need_identification_number' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'need_zip_code' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'zip_code_format' => array('type' => self::TYPE_STRING, 'validate' => 'isZipCodeFormat'), 'display_tax_label' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)), 'associations' => array('zone' => array('type' => self::HAS_ONE), 'currency' => array('type' => self::HAS_ONE)))





* Visibility: **public**
* This property is **static**.


### $cache_iso_by_id

    protected mixed $cache_iso_by_id = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'countries', 'fields' => array('id_zone' => array('xlink_resource' => 'zones'), 'id_currency' => array('xlink_resource' => 'currencies')))





* Visibility: **protected**


Methods
-------


### delete

    mixed CountryCore::delete()





* Visibility: **public**




### getCountries

    Array CountryCore::getCountries(integer $id_lang, boolean $active, boolean $contain_states, boolean $list_states)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active coutries&lt;/p&gt;
* $contain_states **boolean** - &lt;p&gt;return only country with states&lt;/p&gt;
* $list_states **boolean** - &lt;p&gt;Include the states list with the returned list&lt;/p&gt;



### getCountriesByIdShop

    mixed CountryCore::getCountriesByIdShop($id_shop, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**
* $id_lang **mixed**



### getByIso

    integer CountryCore::getByIso(string $iso_code, boolean $active)

Get a country ID with its iso code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **string** - &lt;p&gt;Country iso code&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active coutries&lt;/p&gt;



### getIdZone

    mixed CountryCore::getIdZone($id_country)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **mixed**



### getNameById

    string CountryCore::getNameById(integer $id_lang, integer $id_country)

Get a country name with its ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $id_country **integer** - &lt;p&gt;Country ID&lt;/p&gt;



### getIsoById

    string CountryCore::getIsoById(integer $id_country)

Get a country iso with its ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **integer** - &lt;p&gt;Country ID&lt;/p&gt;



### getIdByName

    integer CountryCore::getIdByName(integer $id_lang, string $country)

Get a country id with its name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $country **string** - &lt;p&gt;Country Name&lt;/p&gt;



### getNeedZipCode

    mixed CountryCore::getNeedZipCode($id_country)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **mixed**



### getZipCodeFormat

    mixed CountryCore::getZipCodeFormat($id_country)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **mixed**



### getDefaultCountryId

    integer CountryCore::getDefaultCountryId()

Returns the default country Id



* Visibility: **public**
* This method is **static**.




### getCountriesByZoneId

    mixed CountryCore::getCountriesByZoneId($id_zone, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_zone **mixed**
* $id_lang **mixed**



### isNeedDni

    mixed CountryCore::isNeedDni()





* Visibility: **public**




### isNeedDniByCountryId

    mixed CountryCore::isNeedDniByCountryId($id_country)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **mixed**



### containsStates

    mixed CountryCore::containsStates($id_country)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **mixed**



### affectZoneToSelection

    boolean CountryCore::affectZoneToSelection($ids_countries, $id_zone)





* Visibility: **public**


#### Arguments
* $ids_countries **mixed**
* $id_zone **mixed**



### checkZipCode

    \(bool) CountryCore::checkZipCode($zip_code)

Replace letters of zip code format And check this format on the zip code



* Visibility: **public**


#### Arguments
* $zip_code **mixed**



### addModuleRestrictions

    mixed CountryCore::addModuleRestrictions(array $shops, array $countries, array $modules)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $shops **array**
* $countries **array**
* $modules **array**



### add

    mixed CountryCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**


