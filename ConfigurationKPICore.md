ConfigurationKPICore
===============






* Class name: ConfigurationKPICore
* Namespace: 
* Parent class: [Configuration](ConfigurationCore)

* This class is defined in [classes/ConfigurationKPI.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#27)





Properties
----------


### $definition_backup

    public mixed $definition_backup





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/ConfigurationKPI.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#29)


Methods
-------


### setKpiDefinition

    mixed ConfigurationKPICore::setKpiDefinition()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#31)




### unsetKpiDefinition

    mixed ConfigurationKPICore::unsetKpiDefinition()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#38)




### getIdByName

    mixed ConfigurationKPICore::getIdByName($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#43)


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### loadConfiguration

    mixed ConfigurationKPICore::loadConfiguration()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#51)




### get

    mixed ConfigurationKPICore::get($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#59)


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### getGlobalValue

    mixed ConfigurationKPICore::getGlobalValue($key, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#67)


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### getInt

    mixed ConfigurationKPICore::getInt($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#75)


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### getMultiple

    mixed ConfigurationKPICore::getMultiple($keys, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#83)


#### Arguments
* $keys **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### hasKey

    mixed ConfigurationKPICore::hasKey($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#91)


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### set

    mixed ConfigurationKPICore::set($key, $values, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#99)


#### Arguments
* $key **mixed**
* $values **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### updateGlobalValue

    mixed ConfigurationKPICore::updateGlobalValue($key, $values, $html)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#107)


#### Arguments
* $key **mixed**
* $values **mixed**
* $html **mixed**



### updateValue

    mixed ConfigurationKPICore::updateValue($key, $values, $html, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#115)


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
* This method is defined in [classes/ConfigurationKPI.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#123)


#### Arguments
* $key **mixed**



### deleteFromContext

    mixed ConfigurationKPICore::deleteFromContext($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#131)


#### Arguments
* $key **mixed**



### hasContext

    mixed ConfigurationKPICore::hasContext($key, $id_lang, $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#139)


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $context **mixed**



### isOverridenByCurrentContext

    mixed ConfigurationKPICore::isOverridenByCurrentContext($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#147)


#### Arguments
* $key **mixed**



### isLangKey

    mixed ConfigurationKPICore::isLangKey($key)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#155)


#### Arguments
* $key **mixed**



### sqlRestriction

    mixed ConfigurationKPICore::sqlRestriction($id_shop_group, $id_shop)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/ConfigurationKPI.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#163)


#### Arguments
* $id_shop_group **mixed**
* $id_shop **mixed**


