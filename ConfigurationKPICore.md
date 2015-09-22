ConfigurationKPICore
===============






* Class name: ConfigurationKPICore
* Namespace: 
* Parent class: [Configuration](ConfigurationCore)
* This class is defined in classes\ConfigurationKPI.php line 27





Properties
----------


### $definition_backup

    public mixed $definition_backup





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\ConfigurationKPI.php line 29


Methods
-------


### setKpiDefinition

    mixed ConfigurationKPICore::setKpiDefinition()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 31




### unsetKpiDefinition

    mixed ConfigurationKPICore::unsetKpiDefinition()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 38




### getIdByName

    mixed ConfigurationKPICore::getIdByName($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 43


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### loadConfiguration

    mixed ConfigurationKPICore::loadConfiguration()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 51




### get

    mixed ConfigurationKPICore::get($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 59


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### getGlobalValue

    mixed ConfigurationKPICore::getGlobalValue($key, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 67


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### getInt

    mixed ConfigurationKPICore::getInt($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 75


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### getMultiple

    mixed ConfigurationKPICore::getMultiple($keys, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 83


#### Arguments
* $keys **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### hasKey

    mixed ConfigurationKPICore::hasKey($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 91


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### set

    mixed ConfigurationKPICore::set($key, $values, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 99


#### Arguments
* $key **mixed**
* $values **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### updateGlobalValue

    mixed ConfigurationKPICore::updateGlobalValue($key, $values, $html)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 107


#### Arguments
* $key **mixed**
* $values **mixed**
* $html **mixed**



### updateValue

    mixed ConfigurationKPICore::updateValue($key, $values, $html, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 115


#### Arguments
* $key **mixed**
* $values **mixed**
* $html **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### deleteByName

    mixed ConfigurationKPICore::deleteByName($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 123


#### Arguments
* $key **mixed**



### deleteFromContext

    mixed ConfigurationKPICore::deleteFromContext($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 131


#### Arguments
* $key **mixed**



### hasContext

    mixed ConfigurationKPICore::hasContext($key, $id_lang, $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 139


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $context **mixed**



### isOverridenByCurrentContext

    mixed ConfigurationKPICore::isOverridenByCurrentContext($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 147


#### Arguments
* $key **mixed**



### isLangKey

    mixed ConfigurationKPICore::isLangKey($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 155


#### Arguments
* $key **mixed**



### sqlRestriction

    mixed ConfigurationKPICore::sqlRestriction($id_shop_group, $id_shop)





* Visibility: **protected**
* This method is **static**.
* This method is defined in classes\ConfigurationKPI.php line 163


#### Arguments
* $id_shop_group **mixed**
* $id_shop **mixed**


