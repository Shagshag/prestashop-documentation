StateCore
===============






* Class name: StateCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\State.php line 27





Properties
----------


### $id_country

    public integer $id_country





* Visibility: **public**
* This property is defined in classes\State.php line 30


### $id_zone

    public integer $id_zone





* Visibility: **public**
* This property is defined in classes\State.php line 33


### $iso_code

    public string $iso_code





* Visibility: **public**
* This property is defined in classes\State.php line 36


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\State.php line 39


### $active

    public boolean $active = true





* Visibility: **public**
* This property is defined in classes\State.php line 42


### $definition

    public mixed $definition = array('table' => 'state', 'primary' => 'id_state', 'fields' => array('id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_zone' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isStateIsoCode', 'required' => true, 'size' => 7), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\State.php line 47


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_zone' => array('xlink_resource' => 'zones'), 'id_country' => array('xlink_resource' => 'countries')))





* Visibility: **protected**
* This property is defined in classes\State.php line 59


Methods
-------


### getStates

    mixed StateCore::getStates($id_lang, $active)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\State.php line 66


#### Arguments
* $id_lang **mixed**
* $active **mixed**



### getNameById

    string StateCore::getNameById(integer $id_state)

Get a state name with its ID



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\State.php line 81


#### Arguments
* $id_state **integer** - &lt;p&gt;Country ID&lt;/p&gt;



### getIdByName

    integer StateCore::getIdByName($state)

Get a state id with its name



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\State.php line 105


#### Arguments
* $state **mixed**



### getIdByIso

    integer StateCore::getIdByIso(string $iso_code, $id_country)

Get a state id with its iso code



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\State.php line 129


#### Arguments
* $iso_code **string** - &lt;p&gt;Iso code&lt;/p&gt;
* $id_country **mixed**



### delete

    boolean StateCore::delete()

Delete a state only if is not in use



* Visibility: **public**
* This method is defined in classes\State.php line 143




### isUsed

    boolean StateCore::isUsed()

Check if a state is used



* Visibility: **public**
* This method is defined in classes\State.php line 167




### countUsed

    integer StateCore::countUsed()

Returns the number of utilisation of a state



* Visibility: **public**
* This method is defined in classes\State.php line 177




### getStatesByIdCountry

    mixed StateCore::getStatesByIdCountry($id_country)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\State.php line 187


#### Arguments
* $id_country **mixed**



### hasCounties

    mixed StateCore::hasCounties($id_state)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\State.php line 200


#### Arguments
* $id_state **mixed**



### getIdZone

    mixed StateCore::getIdZone($id_state)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\State.php line 205


#### Arguments
* $id_state **mixed**



### affectZoneToSelection

    boolean StateCore::affectZoneToSelection($ids_states, $id_zone)





* Visibility: **public**
* This method is defined in classes\State.php line 223


#### Arguments
* $ids_states **mixed**
* $id_zone **mixed**


