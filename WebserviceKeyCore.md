WebserviceKeyCore
===============






* Class name: WebserviceKeyCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $key

    public string $key





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $description

    public string $description





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'webservice_account', 'primary' => 'id_webservice_account', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'key' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### add

    mixed WebserviceKeyCore::add($autodate, $nullValues)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### keyExists

    mixed WebserviceKeyCore::keyExists($key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**



### delete

    mixed WebserviceKeyCore::delete()





* Visibility: **public**




### deleteAssociations

    mixed WebserviceKeyCore::deleteAssociations()





* Visibility: **public**




### getPermissionForAccount

    mixed WebserviceKeyCore::getPermissionForAccount($auth_key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $auth_key **mixed**



### isKeyActive

    mixed WebserviceKeyCore::isKeyActive($auth_key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $auth_key **mixed**



### getClassFromKey

    mixed WebserviceKeyCore::getClassFromKey($auth_key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $auth_key **mixed**



### setPermissionForAccount

    mixed WebserviceKeyCore::setPermissionForAccount($id_account, $permissions_to_set)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_account **mixed**
* $permissions_to_set **mixed**


