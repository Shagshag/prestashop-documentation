ConfigurationCore
===============

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
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $id_shop_group

    public mixed $id_shop_group





* Visibility: **public**


### $id_shop

    public mixed $id_shop





* Visibility: **public**


### $value

    public string $value





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'configuration', 'primary' => 'id_configuration', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isConfigName', 'required' => true, 'size' => 254), 'id_shop_group' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'value' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $_cache

    protected array $_cache = array()





* Visibility: **protected**
* This property is **static**.


### $types

    protected array $types = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('value' => array()))





* Visibility: **protected**


Methods
-------


### getFieldsLang

    boolean|array ConfigurationCore::getFieldsLang()





* Visibility: **public**




### getIdByName

    integer ConfigurationCore::getIdByName(string $key, integer $id_shop_group, integer $id_shop)

Return ID a configuration key



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string**
* $id_shop_group **integer**
* $id_shop **integer**



### configurationIsLoaded

    mixed ConfigurationCore::configurationIsLoaded()





* Visibility: **public**
* This method is **static**.




### clearConfigurationCacheForTesting

    mixed ConfigurationCore::clearConfigurationCacheForTesting()

WARNING: For testing only. Do NOT rely on this method, it may be removed at any time.



* Visibility: **public**
* This method is **static**.




### loadConfiguration

    mixed ConfigurationCore::loadConfiguration()

Load all configuration data



* Visibility: **public**
* This method is **static**.




### get

    string ConfigurationCore::get(string $key, integer $id_lang, $id_shop_group, $id_shop)

Get a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string** - &lt;p&gt;Key wanted&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $id_shop_group **mixed**
* $id_shop **mixed**



### getGlobalValue

    mixed ConfigurationCore::getGlobalValue($key, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### getInt

    array ConfigurationCore::getInt(string $key, integer $id_shop_group, integer $id_shop)

Get a single configuration value (in multiple languages)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string** - &lt;p&gt;Key wanted&lt;/p&gt;
* $id_shop_group **integer**
* $id_shop **integer**



### getMultiShopValues

    array ConfigurationCore::getMultiShopValues(string $key, integer $id_lang)

Get a single configuration value for all shops



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string** - &lt;p&gt;Key wanted&lt;/p&gt;
* $id_lang **integer**



### getMultiple

    array ConfigurationCore::getMultiple(array $keys, integer $id_lang, integer $id_shop_group, integer $id_shop)

Get several configuration values (in one language only)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $keys **array** - &lt;p&gt;Keys wanted&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $id_shop_group **integer**
* $id_shop **integer**



### hasKey

    boolean ConfigurationCore::hasKey(string $key, integer $id_lang, integer $id_shop_group, integer $id_shop)

Check if key exists in configuration



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string**
* $id_lang **integer**
* $id_shop_group **integer**
* $id_shop **integer**



### set

    mixed ConfigurationCore::set(string $key, mixed $values, integer $id_shop_group, integer $id_shop)

Set TEMPORARY a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string** - &lt;p&gt;Key wanted&lt;/p&gt;
* $values **mixed** - &lt;p&gt;$values is an array if the configuration is multilingual, a single string else.&lt;/p&gt;
* $id_shop_group **integer**
* $id_shop **integer**



### updateGlobalValue

    boolean ConfigurationCore::updateGlobalValue(string $key, mixed $values, boolean $html)

Update configuration key for global context only



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string**
* $values **mixed**
* $html **boolean**



### updateValue

    boolean ConfigurationCore::updateValue(string $key, mixed $values, boolean $html, integer $id_shop_group, integer $id_shop)

Update configuration key and value into database (automatically insert if key does not exist)

Values are inserted/updated directly using SQL, because using (Configuration) ObjectModel
may not insert values correctly (for example, HTML is escaped, when it should not be).

* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string** - &lt;p&gt;Key&lt;/p&gt;
* $values **mixed** - &lt;p&gt;$values is an array if the configuration is multilingual, a single string else.&lt;/p&gt;
* $html **boolean** - &lt;p&gt;Specify if html is authorized in value&lt;/p&gt;
* $id_shop_group **integer**
* $id_shop **integer**



### deleteByName

    boolean ConfigurationCore::deleteByName(string $key)

Delete a configuration key in database (with or without language management)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string** - &lt;p&gt;Key to delete&lt;/p&gt;



### deleteFromContext

    mixed ConfigurationCore::deleteFromContext(string $key)

Delete configuration key from current context.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string**



### hasContext

    mixed ConfigurationCore::hasContext(string $key, integer $id_lang, integer $context)

Check if configuration var is defined in given context



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string**
* $id_lang **integer**
* $context **integer**



### isOverridenByCurrentContext

    mixed ConfigurationCore::isOverridenByCurrentContext($key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**



### isLangKey

    boolean ConfigurationCore::isLangKey(string $key)

Check if a key was loaded as multi lang



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string**



### sqlRestriction

    string ConfigurationCore::sqlRestriction(integer $id_shop_group, integer $id_shop)

Add SQL restriction on shops for configuration table



* Visibility: **protected**
* This method is **static**.


#### Arguments
* $id_shop_group **integer**
* $id_shop **integer**



### getWebserviceObjectList

    array ConfigurationCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)

This method is override to allow TranslatedConfiguration entity



* Visibility: **public**


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**


