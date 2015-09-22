Class ConfigurationKPICore
=====================





* Class name: ConfigurationKPICore
* Parent class: [Configuration](class.ConfigurationCore)
* Source: [classes/ConfigurationKPI.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L27)



Properties
----------

* [$definition_backup](#property-$definition_backup)

Methods
-------
* [deleteByName](#method-deleteByName)
* [deleteFromContext](#method-deleteFromContext)
* [get](#method-get)
* [getGlobalValue](#method-getGlobalValue)
* [getIdByName](#method-getIdByName)
* [getInt](#method-getInt)
* [getMultiple](#method-getMultiple)
* [hasContext](#method-hasContext)
* [hasKey](#method-hasKey)
* [isLangKey](#method-isLangKey)
* [isOverridenByCurrentContext](#method-isOverridenByCurrentContext)
* [loadConfiguration](#method-loadConfiguration)
* [set](#method-set)
* [setKpiDefinition](#method-setKpiDefinition)
* [sqlRestriction](#method-sqlRestriction)
* [unsetKpiDefinition](#method-unsetKpiDefinition)
* [updateGlobalValue](#method-updateGlobalValue)
* [updateValue](#method-updateValue)




Properties
----------


### <a name="property-$definition_backup"></a>$definition_backup

    public mixed $definition_backup





* Visibility: **public**
* This property is **static**.
* Source: [classes/ConfigurationKPI.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L29)


Methods
-------


### <a name="method-deleteByName"></a>deleteByName

    mixed ConfigurationKPICore::deleteByName($key)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L123)


#### Arguments
* $key **mixed**



### <a name="method-deleteFromContext"></a>deleteFromContext

    mixed ConfigurationKPICore::deleteFromContext($key)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L131)


#### Arguments
* $key **mixed**



### <a name="method-get"></a>get

    mixed ConfigurationKPICore::get($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L59)


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-getGlobalValue"></a>getGlobalValue

    mixed ConfigurationKPICore::getGlobalValue($key, $id_lang)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L67)


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### <a name="method-getIdByName"></a>getIdByName

    mixed ConfigurationKPICore::getIdByName($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L43)


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-getInt"></a>getInt

    mixed ConfigurationKPICore::getInt($key, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L75)


#### Arguments
* $key **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-getMultiple"></a>getMultiple

    mixed ConfigurationKPICore::getMultiple($keys, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L83)


#### Arguments
* $keys **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-hasContext"></a>hasContext

    mixed ConfigurationKPICore::hasContext($key, $id_lang, $context)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L139)


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $context **mixed**



### <a name="method-hasKey"></a>hasKey

    mixed ConfigurationKPICore::hasKey($key, $id_lang, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L91)


#### Arguments
* $key **mixed**
* $id_lang **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-isLangKey"></a>isLangKey

    mixed ConfigurationKPICore::isLangKey($key)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L155)


#### Arguments
* $key **mixed**



### <a name="method-isOverridenByCurrentContext"></a>isOverridenByCurrentContext

    mixed ConfigurationKPICore::isOverridenByCurrentContext($key)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L147)


#### Arguments
* $key **mixed**



### <a name="method-loadConfiguration"></a>loadConfiguration

    mixed ConfigurationKPICore::loadConfiguration()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L51)




### <a name="method-set"></a>set

    mixed ConfigurationKPICore::set($key, $values, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L99)


#### Arguments
* $key **mixed**
* $values **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-setKpiDefinition"></a>setKpiDefinition

    mixed ConfigurationKPICore::setKpiDefinition()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L31)




### <a name="method-sqlRestriction"></a>sqlRestriction

    mixed ConfigurationKPICore::sqlRestriction($id_shop_group, $id_shop)





* Visibility: **protected**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L163)


#### Arguments
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-unsetKpiDefinition"></a>unsetKpiDefinition

    mixed ConfigurationKPICore::unsetKpiDefinition()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L38)




### <a name="method-updateGlobalValue"></a>updateGlobalValue

    mixed ConfigurationKPICore::updateGlobalValue($key, $values, $html)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L107)


#### Arguments
* $key **mixed**
* $values **mixed**
* $html **mixed**



### <a name="method-updateValue"></a>updateValue

    mixed ConfigurationKPICore::updateValue($key, $values, $html, $id_shop_group, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationKPI.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationKPI.php#L115)


#### Arguments
* $key **mixed**
* $values **mixed**
* $html **mixed**
* $id_shop_group **mixed**
* $id_shop **mixed**


