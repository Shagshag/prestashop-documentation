ProfileCore
===============






* Class name: ProfileCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Profile.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#L27)





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Profile.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#30)


### $definition

    public mixed $definition = array('table' => 'profile', 'primary' => 'id_profile', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Profile.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#35)


### $_cache_accesses

    protected mixed $_cache_accesses = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Profile.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#45)


Methods
-------


### getProfiles

    array ProfileCore::getProfiles($id_lang)

Get all available profiles



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Profile.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#52)


#### Arguments
* $id_lang **mixed**



### getProfile

    string ProfileCore::getProfile($id_profile, $id_lang)

Get the current profile name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Profile.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#66)


#### Arguments
* $id_profile **mixed**
* $id_lang **mixed**



### add

    mixed ProfileCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Profile.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#81)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### delete

    mixed ProfileCore::delete()





* Visibility: **public**
* This method is defined in [classes/Profile.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#95)




### getProfileAccess

    mixed ProfileCore::getProfileAccess($id_profile, $id_tab)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Profile.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#106)


#### Arguments
* $id_profile **mixed**
* $id_tab **mixed**



### getProfileAccesses

    mixed ProfileCore::getProfileAccesses($id_profile, $type)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Profile.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Profile.php#113)


#### Arguments
* $id_profile **mixed**
* $type **mixed**


