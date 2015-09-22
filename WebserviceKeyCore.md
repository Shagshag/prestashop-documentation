WebserviceKeyCore
===============






* Class name: WebserviceKeyCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/webservice/WebserviceKey.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#L27)





Properties
----------


### $key

    public string $key





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceKey.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#30)


### $active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceKey.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#33)


### $description

    public string $description





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceKey.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#36)


### $definition

    public mixed $definition = array('table' => 'webservice_account', 'primary' => 'id_webservice_account', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'key' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/webservice/WebserviceKey.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#41)


Methods
-------


### add

    mixed WebserviceKeyCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceKey.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#51)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### keyExists

    mixed WebserviceKeyCore::keyExists($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/webservice/WebserviceKey.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#59)


#### Arguments
* $key **mixed**



### delete

    mixed WebserviceKeyCore::delete()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceKey.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#67)




### deleteAssociations

    mixed WebserviceKeyCore::deleteAssociations()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceKey.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#72)




### getPermissionForAccount

    mixed WebserviceKeyCore::getPermissionForAccount($auth_key)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/webservice/WebserviceKey.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#77)


#### Arguments
* $auth_key **mixed**



### isKeyActive

    mixed WebserviceKeyCore::isKeyActive($auth_key)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/webservice/WebserviceKey.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#94)


#### Arguments
* $auth_key **mixed**



### getClassFromKey

    mixed WebserviceKeyCore::getClassFromKey($auth_key)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/webservice/WebserviceKey.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#102)


#### Arguments
* $auth_key **mixed**



### setPermissionForAccount

    mixed WebserviceKeyCore::setPermissionForAccount($id_account, $permissions_to_set)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/webservice/WebserviceKey.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceKey.php#110)


#### Arguments
* $id_account **mixed**
* $permissions_to_set **mixed**


