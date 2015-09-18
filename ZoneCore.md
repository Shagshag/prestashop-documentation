ZoneCore
===============






* Class name: ZoneCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'zone', 'primary' => 'id_zone', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array()





* Visibility: **protected**


Methods
-------


### getZones

    array ZoneCore::getZones(boolean $active)

Get all available geographical zones



* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **boolean**



### getIdByName

    integer ZoneCore::getIdByName(string $name)

Get a zone ID from its default language name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string**



### delete

    boolean ZoneCore::delete()

Delete a zone



* Visibility: **public**



