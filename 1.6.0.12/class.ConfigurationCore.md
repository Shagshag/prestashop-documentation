Class ConfigurationCore
=====================





* Class name: ConfigurationCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Configuration.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L27)


Contents
--------


### Properties

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

### Methods

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

```php
protected array $_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Configuration.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L64).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Configuration.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L41).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Configuration.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L44).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'configuration', 'primary' => 'id_configuration', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isConfigName', 'required' => true, 'size' => 254), 'id_shop_group' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'value' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Configuration.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L49).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Configuration.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L29).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Configuration.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L35).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* Source: [classes/Configuration.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L34).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Configuration.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L32).


### <a name="property-$types"></a>$types

```php
protected array $types = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Configuration.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L67).


### <a name="property-$value"></a>$value

```php
public string $value
```





* Visibility: **public**
* Source: [classes/Configuration.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L38).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('value' => array()))
```





* Visibility: **protected**
* Source: [classes/Configuration.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L69).


Methods
-------


### <a name="method-configurationIsLoaded"></a>configurationIsLoaded

```php
mixed ConfigurationCore::configurationIsLoaded()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L107)




### <a name="method-deleteByName"></a>deleteByName

```php
boolean ConfigurationCore::deleteByName(string $key)
```

Delete a configuration key in database (with or without language management)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L423)


#### Arguments
* $key **string** - Key to delete



### <a name="method-deleteFromContext"></a>deleteFromContext

```php
mixed ConfigurationCore::deleteFromContext(string $key)
```

Delete configuration key from current context.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L450)


#### Arguments
* $key **string**



### <a name="method-get"></a>get

```php
string ConfigurationCore::get(string $key, integer $id_lang, $id_shop_group, $id_shop)
```

Get a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L162)


#### Arguments
* $key **string** - Key wanted
* $id_lang **integer** - Language ID
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ConfigurationCore::getFieldsLang()
```





* Visibility: **public**
* Source: [classes/Configuration.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L79)




### <a name="method-getGlobalValue"></a>getGlobalValue

```php
mixed ConfigurationCore::getGlobalValue($key, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L192)


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
mixed ConfigurationCore::getIdByName(string $key, integer $id_shop_group, integer $id_shop)
```

Return ID a configuration key



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L93)


#### Arguments
* $key **string**
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-getInt"></a>getInt

```php
array ConfigurationCore::getInt(string $key, integer $id_shop_group, integer $id_shop)
```

Get a single configuration value (in multiple languages)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L205)


#### Arguments
* $key **string** - Key wanted
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-getMultiShopValues"></a>getMultiShopValues

```php
array ConfigurationCore::getMultiShopValues(string $key, integer $id_lang)
```

Get a single configuration value for all shops



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L221)


#### Arguments
* $key **string** - Key wanted
* $id_lang **integer**



### <a name="method-getMultiple"></a>getMultiple

```php
array ConfigurationCore::getMultiple(array $keys, integer $id_lang, $id_shop_group, $id_shop)
```

Get several configuration values (in one language only)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L238)


#### Arguments
* $keys **array** - Keys wanted
* $id_lang **integer** - Language ID
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
array ConfigurationCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```

This method is override to allow TranslatedConfiguration entity



* Visibility: **public**
* Source: [classes/Configuration.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L558)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-hasContext"></a>hasContext

```php
mixed ConfigurationCore::hasContext(string $key, integer $id_lang, integer $context)
```

Check if configuration var is defined in given context



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L478)


#### Arguments
* $key **string**
* $id_lang **integer**
* $context **integer**



### <a name="method-hasKey"></a>hasKey

```php
boolean ConfigurationCore::hasKey(string $key, integer $id_lang, integer $id_shop_group, integer $id_shop)
```

Check if key exists in configuration



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L264)


#### Arguments
* $key **string**
* $id_lang **integer**
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-isLangKey"></a>isLangKey

```php
boolean ConfigurationCore::isLangKey(string $key)
```

Check if a key was loaded as multi lang



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L527)


#### Arguments
* $key **string**



### <a name="method-isOverridenByCurrentContext"></a>isOverridenByCurrentContext

```php
mixed ConfigurationCore::isOverridenByCurrentContext($key)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L502)


#### Arguments
* $key **mixed**



### <a name="method-loadConfiguration"></a>loadConfiguration

```php
mixed ConfigurationCore::loadConfiguration()
```

Load all configuration data



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L126)




### <a name="method-set"></a>set

```php
mixed ConfigurationCore::set(string $key, mixed $values, integer $id_shop_group, integer $id_shop)
```

Set TEMPORARY a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L284)


#### Arguments
* $key **string** - Key wanted
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-sqlRestriction"></a>sqlRestriction

```php
string ConfigurationCore::sqlRestriction(integer $id_shop_group, integer $id_shop)
```

Add SQL restriction on shops for configuration table



* Visibility: **protected**
* This method is **static**.
* Source: [classes/Configuration.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L539)


#### Arguments
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-updateGlobalValue"></a>updateGlobalValue

```php
boolean ConfigurationCore::updateGlobalValue(string $key, mixed $values, boolean $html)
```

Update configuration key for global context only



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L316)


#### Arguments
* $key **string**
* $values **mixed**
* $html **boolean**



### <a name="method-updateValue"></a>updateValue

```php
boolean ConfigurationCore::updateValue(string $key, mixed $values, boolean $html, integer $id_shop_group, integer $id_shop)
```

Update configuration key and value into database (automatically insert if key does not exist)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Configuration.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Configuration.php#L331)


#### Arguments
* $key **string** - Key
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $html **boolean** - Specify if html is authorized in value
* $id_shop_group **integer**
* $id_shop **integer**


