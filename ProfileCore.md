ProfileCore
===============






* Class name: ProfileCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'profile', 'primary' => 'id_profile', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.


### $_cache_accesses

    protected mixed $_cache_accesses = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### getProfiles

    array ProfileCore::getProfiles($id_lang)

Get all available profiles



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**



### getProfile

    string ProfileCore::getProfile($id_profile, $id_lang)

Get the current profile name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_profile **mixed**
* $id_lang **mixed**



### add

    mixed ProfileCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### delete

    mixed ProfileCore::delete()





* Visibility: **public**




### getProfileAccess

    mixed ProfileCore::getProfileAccess($id_profile, $id_tab)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_profile **mixed**
* $id_tab **mixed**



### getProfileAccesses

    mixed ProfileCore::getProfileAccesses($id_profile, $type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_profile **mixed**
* $type **mixed**


