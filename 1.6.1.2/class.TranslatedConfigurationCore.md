Class TranslatedConfigurationCore
=====================





* Class name: TranslatedConfigurationCore
* Parent class: [Configuration](class.ConfigurationCore.md)
* Source: [classes/TranslatedConfiguration.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/TranslatedConfiguration.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)
* [$_cache](#property-$_cache)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$id](#property-$id)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$name](#property-$name)
* [$types](#property-$types)
* [$value](#property-$value)
* [$cache_objects](#property-$cache_objects)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$force_id](#property-$force_id)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id_lang](#property-$id_lang)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$loaded_classes](#property-$loaded_classes)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [clearCache](#method-clearCache)
* [clearConfigurationCacheForTesting](#method-clearConfigurationCacheForTesting)
* [configurationIsLoaded](#method-configurationIsLoaded)
* [delete](#method-delete)
* [deleteByName](#method-deleteByName)
* [deleteFromContext](#method-deleteFromContext)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [enableCache](#method-enableCache)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [get](#method-get)
* [getAssociatedShops](#method-getAssociatedShops)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getGlobalValue](#method-getGlobalValue)
* [getIdByName](#method-getIdByName)
* [getInt](#method-getInt)
* [getMultiShopValues](#method-getMultiShopValues)
* [getMultiple](#method-getMultiple)
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasContext](#method-hasContext)
* [hasKey](#method-hasKey)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangKey](#method-isLangKey)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [isOverridenByCurrentContext](#method-isOverridenByCurrentContext)
* [loadConfiguration](#method-loadConfiguration)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [set](#method-set)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [sqlRestriction](#method-sqlRestriction)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateGlobalValue](#method-updateGlobalValue)
* [updateMultishopTable](#method-updateMultishopTable)
* [updateValue](#method-updateValue)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'configuration', 'primary' => 'id_configuration', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isConfigName', 'required' => true, 'size' => 32), 'id_shop_group' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'value' => array('type' => self::TYPE_STRING, 'lang' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/TranslatedConfiguration.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/TranslatedConfiguration.php#L39).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'translated_configuration', 'objectsNodeName' => 'translated_configurations', 'fields' => array('value' => array(), 'date_add' => array(), 'date_upd' => array()))
```





* Visibility: **protected**
* Source: [classes/TranslatedConfiguration.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/TranslatedConfiguration.php#L29).


### <a name="property-$_cache"></a>$_cache

```php
protected array $_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L64).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L41).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L44).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L29).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L35).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L34).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L32).


### <a name="property-$types"></a>$types

```php
protected array $types = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L67).


### <a name="property-$value"></a>$value

```php
public string $value
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L38).


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L164).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L150).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected array $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L88).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected array $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L70).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L106).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L94).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L112).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected array $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L118).


### <a name="property-$force_id"></a>$force_id

```php
public boolean $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L159).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected boolean $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L67).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L58).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public array $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L64).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L82).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L130).


### <a name="property-$image_format"></a>$image_format

```php
protected String $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L133).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected array $loaded_classes = array()
```

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L147).


### <a name="property-$table"></a>$table

```php
protected string $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L76).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L124).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L153).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TranslatedConfigurationCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/TranslatedConfiguration.php#L53)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed TranslatedConfigurationCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/TranslatedConfiguration.php#L71)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)
```

Sets required field for this class in the database.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1390)


#### Arguments
* $fields **array**



### <a name="method-associateTo"></a>associateTo

```php
boolean|void ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1464)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)
```

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1368)


#### Arguments
* $all **boolean** - If true, caches required fields of all object classes.



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache(boolean $all)
```

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1414)


#### Arguments
* $all **boolean** - If true, clears cache for all objects



### <a name="method-clearConfigurationCacheForTesting"></a>clearConfigurationCacheForTesting

```php
mixed ConfigurationCore::clearConfigurationCacheForTesting()
```

WARNING: For testing only. Do NOT rely on this method, it may be removed at any time.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L132)




### <a name="method-configurationIsLoaded"></a>configurationIsLoaded

```php
mixed ConfigurationCore::configurationIsLoaded()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L111)




### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Deletes current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L743)




### <a name="method-deleteByName"></a>deleteByName

```php
boolean ConfigurationCore::deleteByName(string $key)
```

Delete a configuration key in database (with or without language management)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L472)


#### Arguments
* $key **string** - Key to delete



### <a name="method-deleteFromContext"></a>deleteFromContext

```php
mixed ConfigurationCore::deleteFromContext(string $key)
```

Delete configuration key from current context.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L500)


#### Arguments
* $key **string**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage(boolean $force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1643)


#### Arguments
* $force_delete **boolean**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $ids)
```

Deletes multiple objects from the database at once



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L790)


#### Arguments
* $ids **array** - Array of objects IDs.



### <a name="method-disableCache"></a>disableCache

```php
mixed ObjectModelCore::disableCache()
```

Disables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1969)




### <a name="method-displayFieldName"></a>displayFieldName

```php
string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)
```

Returns field name translation



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1083)


#### Arguments
* $field **string** - Field name
* $class **string** - ObjectModel class name
* $htmlentities **boolean** - If true, applies htmlentities() to result string
* $context **[Context](class.ContextCore.md)|null** - Context object



### <a name="method-duplicateObject"></a>duplicateObject

```php
\ObjectModel|false ObjectModelCore::duplicateObject()
```

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L549)




### <a name="method-duplicateShops"></a>duplicateShops

```php
boolean|void ObjectModelCore::duplicateShops($id)
```

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1523)


#### Arguments
* $id **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ObjectModelCore::enableCache()
```

Enables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1961)




### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1686)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```

Formats values of each fields.



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L327)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, boolean $with_quotes, boolean $purify, boolean $allow_null)
```

Formats a value



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### <a name="method-get"></a>get

```php
string ConfigurationCore::get(string $key, integer $id_lang, $id_shop_group, $id_shop)
```

Get a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L177)


#### Arguments
* $key **string** - Key wanted
* $id_lang **integer** - Language ID
* $id_shop_group **mixed**
* $id_shop **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1499)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string|null $field)
```

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1809)


#### Arguments
* $class **string** - Name of object
* $field **string|null** - Name of field if we want the definition of one field only



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)
```

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1927)


#### Arguments
* $field_name **string**
* $id_lang **integer|null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval, .

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L244)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
boolean|array ConfigurationCore::getFieldsLang()
```





* Visibility: **public**
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L79)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)
```

Returns an array of required fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1355)


#### Arguments
* $all **boolean** - If true, returns required fields of all object classes.



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ObjectModelCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we consider they are already validated in getFields() method,
this is not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L270)




### <a name="method-getGlobalValue"></a>getGlobalValue

```php
mixed ConfigurationCore::getGlobalValue($key, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L212)


#### Arguments
* $key **mixed**
* $id_lang **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer ConfigurationCore::getIdByName(string $key, integer $id_shop_group, integer $id_shop)
```

Return ID a configuration key



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L95)


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
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L225)


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
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L242)


#### Arguments
* $key **string** - Key wanted
* $id_lang **integer**



### <a name="method-getMultiple"></a>getMultiple

```php
array ConfigurationCore::getMultiple(array $keys, integer $id_lang, integer $id_shop_group, integer $id_shop)
```

Get several configuration values (in one language only)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L263)


#### Arguments
* $keys **array** - Keys wanted
* $id_lang **integer** - Language ID
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

```php
mixed ObjectModelCore::getRepositoryClassName()
```

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L166)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array ObjectModelCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L831)


#### Arguments
* $fields_array **array**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L178)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed TranslatedConfigurationCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/TranslatedConfiguration.php#L98)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
array ObjectModelCore::getWebserviceParameters(string|null $ws_params_attribute_name)
```

Returns webservice parameters of this object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1176)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-hasContext"></a>hasContext

```php
mixed ConfigurationCore::hasContext(string $key, integer $id_lang, integer $context)
```

Check if configuration var is defined in given context



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L530)


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
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L293)


#### Arguments
* $key **string**
* $id_lang **integer**
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1550)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer|null $id_lang)
```

Fill an object with given data. Data must be an array with this syntax:
array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1730)


#### Arguments
* $data **array**
* $id_lang **integer|null**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1755)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer|null**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)
```

Checks if current object is associated to a shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1430)


#### Arguments
* $id_shop **integer|null**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)
```

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1706)


#### Arguments
* $table **string|null** - Name of table linked to entity
* $has_active_column **boolean** - True if the table has an active column



### <a name="method-isLangKey"></a>isLangKey

```php
boolean ConfigurationCore::isLangKey(string $key)
```

Check if a key was loaded as multi lang



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L576)


#### Arguments
* $key **string**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
boolean ObjectModelCore::isLangMultishop()
```

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1586)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
boolean ObjectModelCore::isMultiShopField(string $field)
```

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1576)


#### Arguments
* $field **string**



### <a name="method-isMultishop"></a>isMultishop

```php
boolean ObjectModelCore::isMultishop()
```

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1564)




### <a name="method-isOverridenByCurrentContext"></a>isOverridenByCurrentContext

```php
mixed ConfigurationCore::isOverridenByCurrentContext($key)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L552)


#### Arguments
* $key **mixed**



### <a name="method-loadConfiguration"></a>loadConfiguration

```php
mixed ConfigurationCore::loadConfiguration()
```

Load all configuration data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L140)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L854)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $auto_date)
```

Saves current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L443)


#### Arguments
* $null_values **boolean**
* $auto_date **boolean**



### <a name="method-set"></a>set

```php
mixed ConfigurationCore::set(string $key, mixed $values, integer $id_shop_group, integer $id_shop)
```

Set TEMPORARY a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L324)


#### Arguments
* $key **string** - Key wanted
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1855)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1953](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1953)


#### Arguments
* $fields **array**



### <a name="method-sqlRestriction"></a>sqlRestriction

```php
string ConfigurationCore::sqlRestriction(integer $id_shop_group, integer $id_shop)
```

Add SQL restriction on shops for configuration table



* Visibility: **protected**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L588)


#### Arguments
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggles object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L807)




### <a name="method-update"></a>update

```php
mixed TranslatedConfigurationCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/TranslatedConfiguration.php#L76)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateGlobalValue"></a>updateGlobalValue

```php
boolean ConfigurationCore::updateGlobalValue(string $key, mixed $values, boolean $html)
```

Update configuration key for global context only



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L360)


#### Arguments
* $key **string**
* $values **mixed**
* $html **boolean**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1602)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-updateValue"></a>updateValue

```php
boolean ConfigurationCore::updateValue(string $key, mixed $values, boolean $html, integer $id_shop_group, integer $id_shop)
```

Update configuration key and value into database (automatically insert if key does not exist)

Values are inserted/updated directly using SQL, because using (Configuration) ObjectModel
may not insert values correctly (for example, HTML is escaped, when it should not be).

* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Configuration.php#L379)


#### Arguments
* $key **string** - Key
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $html **boolean** - Specify if html is authorized in value
* $id_shop_group **integer**
* $id_shop **integer**



### <a name="method-validateControler"></a>validateControler

```php
array ObjectModelCore::validateControler(boolean $htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1105)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

```php
array ObjectModelCore::validateController(boolean $htmlentities)
```

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1118)


#### Arguments
* $htmlentities **boolean** - If true, uses htmlentities() for field name translations in errors.



### <a name="method-validateField"></a>validateField

```php
true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L977)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer|null** - Language ID
* $skip **array** - Array of fields to skip.
* $human_errors **boolean** - If true, uses more descriptive, translatable error strings.



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Checks if object field values are valid before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L895)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Checks if multilingual object field values are valid before database interaction.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L927)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
array ObjectModelCore::validateFieldsRequiredDatabase(boolean $htmlentities)
```

Validate required fields.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1322)


#### Arguments
* $htmlentities **boolean**


