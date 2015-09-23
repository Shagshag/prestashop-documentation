Class TranslatedConfigurationCore
=====================





* Class name: TranslatedConfigurationCore
* Parent class: [Configuration](class.ConfigurationCore.md)
* Source: [classes/TranslatedConfiguration.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/TranslatedConfiguration.php#L28)


Contents
--------


### Properties

* [$webserviceParameters](#property-$webserviceParameters)
* [$_CONF](#property-$_CONF)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_group_shop](#property-$id_group_shop)
* [$id_shop](#property-$id_shop)
* [$name](#property-$name)
* [$types](#property-$types)
* [$value](#property-$value)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id_lang](#property-$id_lang)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteByName](#method-deleteByName)
* [deleteFromContext](#method-deleteFromContext)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [get](#method-get)
* [getDefinition](#method-getDefinition)
* [getEntity](#method-getEntity)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getGlobalValue](#method-getGlobalValue)
* [getIdByName](#method-getIdByName)
* [getInt](#method-getInt)
* [getMultiple](#method-getMultiple)
* [getShopFromContext](#method-getShopFromContext)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasContext](#method-hasContext)
* [hasKey](#method-hasKey)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangKey](#method-isLangKey)
* [isLangMultishop](#method-isLangMultishop)
* [isOverridenByCurrentContext](#method-isOverridenByCurrentContext)
* [loadConfiguration](#method-loadConfiguration)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [set](#method-set)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [sqlRestriction](#method-sqlRestriction)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateGlobalValue](#method-updateGlobalValue)
* [updateValue](#method-updateValue)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'translated_configuration', 'objectsNodeName' => 'translated_configurations', 'fields' => array('value' => array('i18n' => true), 'date_add' => array('i18n' => true), 'date_upd' => array('i18n' => true)))
```





* Visibility: **protected**
* Source: [classes/TranslatedConfiguration.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/TranslatedConfiguration.php#L30).


### <a name="property-$_CONF"></a>$_CONF

```php
protected array $_CONF
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L65).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L42).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L45).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'configuration', 'primary' => 'id_configuration', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isConfigName', 'required' => true, 'size' => 32), 'id_group_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'value' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L50).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L30).


### <a name="property-$id_group_shop"></a>$id_group_shop

```php
public mixed $id_group_shop
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L35).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L36).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L33).


### <a name="property-$types"></a>$types

```php
protected array $types = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L68).


### <a name="property-$value"></a>$value

```php
public string $value
```





* Visibility: **public**
* This property is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L39).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L97).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L51).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TranslatedConfigurationCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/TranslatedConfiguration.php#L40)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed TranslatedConfigurationCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/TranslatedConfiguration.php#L58)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L961)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1009)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L975)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 517](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L517)




### <a name="method-deleteByName"></a>deleteByName

```php
boolean ConfigurationCore::deleteByName(string $key)
```

Delete a configuration key in database (with or without language management)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L354)


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
* Source: [classes/Configuration.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L378)


#### Arguments
* $key **string**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1079)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L553)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L740)


#### Arguments
* $field **mixed**
* $className **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1049)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1113)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L272)


#### Arguments
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-get"></a>get

```php
string ConfigurationCore::get(string $key, $langID, $shopGroupID, $shopID)
```

Get a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L139)


#### Arguments
* $key **string** - Key wanted
* $langID **mixed**
* $shopGroupID **mixed**
* $shopID **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
mixed ObjectModelCore::getDefinition($class, $field)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1209)


#### Arguments
* $class **mixed**
* $field **mixed**



### <a name="method-getEntity"></a>getEntity

```php
mixed ObjectModelCore::getEntity($entity)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1269)


#### Arguments
* $entity **mixed**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ConfigurationCore::getFieldsLang()
```





* Visibility: **public**
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L80)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L953)


#### Arguments
* $all **mixed**



### <a name="method-getGlobalValue"></a>getGlobalValue

```php
mixed ConfigurationCore::getGlobalValue($key, $langID)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L159)


#### Arguments
* $key **mixed**
* $langID **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
mixed ConfigurationCore::getIdByName(string $key, integer $shopGroupID, integer $shopID)
```

Return ID a configuration key



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L94)


#### Arguments
* $key **string**
* $shopGroupID **integer**
* $shopID **integer**



### <a name="method-getInt"></a>getInt

```php
array ConfigurationCore::getInt(string $key, $id_group_shop, $id_shop)
```

Get a single configuration value (in multiple languages)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L172)


#### Arguments
* $key **string** - Key wanted
* $id_group_shop **mixed**
* $id_shop **mixed**



### <a name="method-getMultiple"></a>getMultiple

```php
array ConfigurationCore::getMultiple(array $keys, $langID, $shopGroupID, $shopID)
```

Get several configuration values (in one language only)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L188)


#### Arguments
* $keys **array** - Keys wanted
* $langID **mixed**
* $shopGroupID **mixed**
* $shopID **mixed**



### <a name="method-getShopFromContext"></a>getShopFromContext

```php
mixed ConfigurationCore::getShopFromContext(integer $id_group_shop, integer $id_shop)
```

Fill $id_group_shop and $id_shop vars from correct context



* Visibility: **protected**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L449)


#### Arguments
* $id_group_shop **integer**
* $id_shop **integer**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fieldsArray)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L589)


#### Arguments
* $fieldsArray **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L130)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed TranslatedConfigurationCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/TranslatedConfiguration.php#L86)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($wsParamsAttributeName)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L799)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-hasContext"></a>hasContext

```php
mixed ConfigurationCore::hasContext(string $key, integer $langID, integer $context)
```

Check if configuration var is defined in given context



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L401)


#### Arguments
* $key **string**
* $langID **integer**
* $context **integer**



### <a name="method-hasKey"></a>hasKey

```php
boolean ConfigurationCore::hasKey(string $key, $langID, integer $shopGroupID, integer $shopID)
```

Check if key exists in configuration



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L211)


#### Arguments
* $key **string**
* $langID **mixed**
* $shopGroupID **integer**
* $shopID **integer**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1148)


#### Arguments
* $data **array**
* $id_lang **integer**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1167)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1035)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L990)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1131)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangKey"></a>isLangKey

```php
boolean ConfigurationCore::isLangKey(string $key)
```

Check if a key was loaded as multi lang



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L438)


#### Arguments
* $key **string**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1069)




### <a name="method-isOverridenByCurrentContext"></a>isOverridenByCurrentContext

```php
mixed ConfigurationCore::isOverridenByCurrentContext($key)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L413)


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
* Source: [classes/Configuration.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L107)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L605)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-set"></a>set

```php
mixed ConfigurationCore::set(string $key, mixed $values, $id_group_shop, $id_shop)
```

Set TEMPORARY a single configuration value (in one language only)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L229)


#### Arguments
* $key **string** - Key wanted
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $id_group_shop **mixed**
* $id_shop **mixed**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1224)




### <a name="method-sqlRestriction"></a>sqlRestriction

```php
string ConfigurationCore::sqlRestriction(integer $shopGroupID, integer $shopID)
```

Add SQL restriction on shops for configuration table



* Visibility: **protected**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L468)


#### Arguments
* $shopGroupID **integer**
* $shopID **integer**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L569)




### <a name="method-update"></a>update

```php
mixed TranslatedConfigurationCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/TranslatedConfiguration.php#L63)


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
* Source: [classes/Configuration.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L257)


#### Arguments
* $key **string**
* $values **mixed**
* $html **boolean**



### <a name="method-updateValue"></a>updateValue

```php
boolean ConfigurationCore::updateValue(string $key, mixed $values, boolean $html, integer $shopGroupID, integer $shopID)
```

Update configuration key and value into database (automatically insert if key does not exist)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ConfigurationCore](class.ConfigurationCore.md).
* Source: [classes/Configuration.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Configuration.php#L272)


#### Arguments
* $key **string** - Key
* $values **mixed** - $values is an array if the configuration is multilingual, a single string else.
* $html **boolean** - Specify if html is authorized in value
* $shopGroupID **integer**
* $shopID **integer**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L753)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L759)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L704)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L643)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L669)


#### Arguments
* $die **boolean**
* $error_return **boolean**


