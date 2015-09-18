StateCore
===============






* Class name: StateCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_country

    public integer $id_country





* Visibility: **public**


### $id_zone

    public integer $id_zone





* Visibility: **public**


### $iso_code

    public string $iso_code





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'state', 'primary' => 'id_state', 'fields' => array('id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_zone' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isStateIsoCode', 'required' => true, 'size' => 7), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_zone' => array('xlink_resource' => 'zones'), 'id_country' => array('xlink_resource' => 'countries')))





* Visibility: **protected**


Methods
-------


### getStates

    mixed StateCore::getStates($id_lang, $active)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $active **mixed**



### getNameById

    string StateCore::getNameById(integer $id_state)

Get a state name with its ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_state **integer** - &lt;p&gt;Country ID&lt;/p&gt;



### getIdByName

    integer StateCore::getIdByName($state)

Get a state id with its name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $state **mixed**



### getIdByIso

    integer StateCore::getIdByIso(string $iso_code, $id_country)

Get a state id with its iso code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **string** - &lt;p&gt;Iso code&lt;/p&gt;
* $id_country **mixed**



### delete

    boolean StateCore::delete()

Delete a state only if is not in use



* Visibility: **public**




### isUsed

    boolean StateCore::isUsed()

Check if a state is used



* Visibility: **public**




### countUsed

    integer StateCore::countUsed()

Returns the number of utilisation of a state



* Visibility: **public**




### getStatesByIdCountry

    mixed StateCore::getStatesByIdCountry($id_country)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **mixed**



### hasCounties

    mixed StateCore::hasCounties($id_state)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_state **mixed**



### getIdZone

    mixed StateCore::getIdZone($id_state)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_state **mixed**



### affectZoneToSelection

    boolean StateCore::affectZoneToSelection($ids_states, $id_zone)





* Visibility: **public**


#### Arguments
* $ids_states **mixed**
* $id_zone **mixed**


