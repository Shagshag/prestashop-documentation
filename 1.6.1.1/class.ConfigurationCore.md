Class ConfigurationCore
=====================

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.

* Class name: ConfigurationCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/Configuration.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L27)



Properties
----------

* [$_cache](#property-$_cache)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$name](#property-$name)
* [$types](#property-$types)
* [$value](#property-$value)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [clearConfigurationCacheForTesting](#method-clearConfigurationCacheForTesting)
* [configurationIsLoaded](#method-configurationIsLoaded)
* [deleteByName](#method-deleteByName)
* [deleteFromContext](#method-deleteFromContext)
* [get](#method-get)
* [getFieldsLang](#method-getFieldsLang)
* [getGlobalValue](#method-getGlobalValue)
* [getIdByName](#method-getIdByName)
* [getInt](#method-getInt)
* [getMultiShopValues](#method-getMultiShopValues)
* [getMultiple](#method-getMultiple)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [hasContext](#method-hasContext)
* [hasKey](#method-hasKey)
* [isLangKey](#method-isLangKey)
* [isOverridenByCurrentContext](#method-isOverridenByCurrentContext)
* [loadConfiguration](#method-loadConfiguration)
* [set](#method-set)
* [sqlRestriction](#method-sqlRestriction)
* [updateGlobalValue](#method-updateGlobalValue)
* [updateValue](#method-updateValue)




Properties
----------


### <a name="property-$_cache"></a>$_cache

    protected array $_cache = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Configuration.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L64)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* Source: [classes/Configuration.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L41)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* Source: [classes/Configuration.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L44)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'configuration', 'primary' => 'id_configuration', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isConfigName', 'required' => true, 'size' => 254), 'id_shop_group' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'value' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Configuration.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L49)


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* Source: [classes/Configuration.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L29)


### <a name="property-$id_shop"></a>$id_shop

    public mixed $id_shop





* Visibility: **public**
* Source: [classes/Configuration.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L35)


### <a name="property-$id_shop_group"></a>$id_shop_group

    public mixed $id_shop_group





* Visibility: **public**
* Source: [classes/Configuration.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L34)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Configuration.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L32)


### <a name="property-$types"></a>$types

    protected array $types = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Configuration.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L67)


### <a name="property-$value"></a>$value

    public string $value





* Visibility: **public**
* Source: [classes/Configuration.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L38)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('value' => array()))





* Visibility: **protected**
* Source: [classes/Configuration.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L69)


Methods
-------


### <a name="method-clearConfigurationCacheForTesting"></a>clearConfigurationCacheForTesting

    mixed ConfigurationCore::clearConfigurationCacheForTesting()

WARNING: For testing only. Do NOT rely on this method, it may be removed at any time.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L132)




### <a name="method-configurationIsLoaded"></a>configurationIsLoaded

    mixed ConfigurationCore::configurationIsLoaded()





* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L111)




### <a name="method-deleteByName"></a>deleteByName

    boolean ConfigurationCore::deleteByName(string $key)

Delete a configuration key in database (with or without language management)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L472)


#### Arguments
* $key **string** - Key to delete



### <a name="method-deleteFromContext"></a>deleteFromContext

    mixed ConfigurationCore::deleteFromContext(string $key)

Delete configuration key from current context.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L500)


#### Arguments
* $key **string**



### <a name="method-get"></a>get

    string ConfigurationCore::get(string $key, integer $id_lang, $id_shop_group, $id_shop)

Get a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L177)


#### Arguments
* $key **string** - Key wanted
* $id_lang **integer** - Language ID
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-getFieldsLang"></a>getFieldsLang

    boolean|array ConfigurationCore::getFieldsLang()





* Visibility: **public**
* Source: [classes/Configuration.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L79)




### <a name="method-getGlobalValue"></a>getGlobalValue

    mixed ConfigurationCore::getGlobalValue($key, $id_lang)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L212)


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### <a name="method-getIdByName"></a>getIdByName

    integer ConfigurationCore::getIdByName(string $key, integer $id_shop_group, integer $id_shop)

Return ID a configuration key



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L95)


#### Arguments
* $key **string**
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-getInt"></a>getInt

    array ConfigurationCore::getInt(string $key, integer $id_shop_group, integer $id_shop)

Get a single configuration value (in multiple languages)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L225)


#### Arguments
* $key **string** - Key wanted
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-getMultiShopValues"></a>getMultiShopValues

    array ConfigurationCore::getMultiShopValues(string $key, integer $id_lang)

Get a single configuration value for all shops



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L242)


#### Arguments
* $key **string** - Key wanted
* $id_lang **integer**



### <a name="method-getMultiple"></a>getMultiple

    array ConfigurationCore::getMultiple(array $keys, integer $id_lang, integer $id_shop_group, integer $id_shop)

Get several configuration values (in one language only)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L263)


#### Arguments
* $keys **array** - Keys wanted
* $id_lang **integer** - Language ID
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

    array ConfigurationCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)

This method is override to allow TranslatedConfiguration entity



* Visibility: **public**
* Source: [classes/Configuration.php line 608](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L608)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-hasContext"></a>hasContext

    mixed ConfigurationCore::hasContext(string $key, integer $id_lang, integer $context)

Check if configuration var is defined in given context



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L530)


#### Arguments
* $key **string**
* $id_lang **integer**
* $context **integer**



### <a name="method-hasKey"></a>hasKey

    boolean ConfigurationCore::hasKey(string $key, integer $id_lang, integer $id_shop_group, integer $id_shop)

Check if key exists in configuration



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L293)


#### Arguments
* $key **string**
* $id_lang **integer**
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-isLangKey"></a>isLangKey

    boolean ConfigurationCore::isLangKey(string $key)

Check if a key was loaded as multi lang



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L576)


#### Arguments
* $key **string**



### <a name="method-isOverridenByCurrentContext"></a>isOverridenByCurrentContext

    mixed ConfigurationCore::isOverridenByCurrentContext($key)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L552)


#### Arguments
* $key **mixed**



### <a name="method-loadConfiguration"></a>loadConfiguration

    mixed ConfigurationCore::loadConfiguration()

Load all configuration data



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L140)




### <a name="method-set"></a>set

    mixed ConfigurationCore::set(string $key, mixed $values, integer $id_shop_group, integer $id_shop)

Set TEMPORARY a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L324)


#### Arguments
* $key **string** - Key wanted
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-sqlRestriction"></a>sqlRestriction

    string ConfigurationCore::sqlRestriction(integer $id_shop_group, integer $id_shop)

Add SQL restriction on shops for configuration table



* Visibility: **protected**
* This method is **static**.
* Source: [classes/Configuration.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L588)


#### Arguments
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-updateGlobalValue"></a>updateGlobalValue

    boolean ConfigurationCore::updateGlobalValue(string $key, mixed $values, boolean $html)

Update configuration key for global context only



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L360)


#### Arguments
* $key **string**
* $values **mixed**
* $html **boolean**



### <a name="method-updateValue"></a>updateValue

    boolean ConfigurationCore::updateValue(string $key, mixed $values, boolean $html, integer $id_shop_group, integer $id_shop)

Update configuration key and value into database (automatically insert if key does not exist)

Values are inserted/updated directly using SQL, because using (Configuration) ObjectModel
may not insert values correctly (for example, HTML is escaped, when it should not be).

* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Configuration.php#L379)


#### Arguments
* $key **string** - Key
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $html **boolean** - Specify if html is authorized in value
* $id_shop_group **integer**
* $id_shop **integer**


