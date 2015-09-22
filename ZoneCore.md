ZoneCore
===============






* Class name: ZoneCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Zone.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#L27)





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Zone.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#30)


### $active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Zone.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#33)


### $definition

    public mixed $definition = array('table' => 'zone', 'primary' => 'id_zone', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Zone.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#38)


### $webserviceParameters

    protected mixed $webserviceParameters = array()





* Visibility: **protected**
* This property is defined in [classes/Zone.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#47)


Methods
-------


### getZones

    array ZoneCore::getZones(boolean $active)

Get all available geographical zones



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Zone.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#55)


#### Arguments
* $active **boolean**



### getIdByName

    integer ZoneCore::getIdByName(string $name)

Get a zone ID from its default language name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Zone.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#77)


#### Arguments
* $name **string**



### delete

    boolean ZoneCore::delete()

Delete a zone



* Visibility: **public**
* This method is defined in [classes/Zone.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Zone.php#91)



