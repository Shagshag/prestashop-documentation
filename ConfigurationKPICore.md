ConfigurationKPICore
===============






* Class name: ConfigurationKPICore
* Namespace: 
* Parent class: Configuration





Properties
----------


### $definition_backup

    public mixed $definition_backup





* Visibility: **public**
* This property is **static**.


Methods
-------


### setKpiDefinition

    mixed ConfigurationKPICore::setKpiDefinition()





* Visibility: **public**
* This method is **static**.




### unsetKpiDefinition

    mixed ConfigurationKPICore::unsetKpiDefinition()





* Visibility: **public**
* This method is **static**.




### getIdByName

    mixed ConfigurationKPICore::getIdByName($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### loadConfiguration

    mixed ConfigurationKPICore::loadConfiguration()





* Visibility: **public**
* This method is **static**.




### get

    mixed ConfigurationKPICore::get($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### getGlobalValue

    mixed ConfigurationKPICore::getGlobalValue($key, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### getInt

    mixed ConfigurationKPICore::getInt($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### getMultiple

    mixed ConfigurationKPICore::getMultiple($keys, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $keys **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### hasKey

    mixed ConfigurationKPICore::hasKey($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### set

    mixed ConfigurationKPICore::set($key, $values, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $values **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### updateGlobalValue

    mixed ConfigurationKPICore::updateGlobalValue($key, $values, $html)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $values **mixed**
* $html **mixed**



### updateValue

    mixed ConfigurationKPICore::updateValue($key, $values, $html, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $key **mixed**



### deleteFromContext

    mixed ConfigurationKPICore::deleteFromContext($key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**



### hasContext

    mixed ConfigurationKPICore::hasContext($key, $id_lang, $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $context **mixed**



### isOverridenByCurrentContext

    mixed ConfigurationKPICore::isOverridenByCurrentContext($key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**



### isLangKey

    mixed ConfigurationKPICore::isLangKey($key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**



### sqlRestriction

    mixed ConfigurationKPICore::sqlRestriction($id_shop_group, $id_shop)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $id_shop_group **mixed**
* $id_shop **mixed**


