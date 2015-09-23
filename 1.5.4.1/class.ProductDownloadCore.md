Class ProductDownloadCore
=====================





* Class name: ProductDownloadCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/ProductDownload.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L27)


Contents
--------


### Properties

* [$_productIds](#property-$_productIds)
* [$active](#property-$active)
* [$date_add](#property-$date_add)
* [$date_expiration](#property-$date_expiration)
* [$definition](#property-$definition)
* [$display_filename](#property-$display_filename)
* [$filename](#property-$filename)
* [$id_product](#property-$id_product)
* [$is_shareable](#property-$is_shareable)
* [$nb_days_accessible](#property-$nb_days_accessible)
* [$nb_downloadable](#property-$nb_downloadable)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [checkFile](#method-checkFile)
* [checkWritableDir](#method-checkWritableDir)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteFile](#method-deleteFile)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getDeadline](#method-getDeadline)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getFilenameFromFilename](#method-getFilenameFromFilename)
* [getFilenameFromIdProduct](#method-getFilenameFromIdProduct)
* [getHash](#method-getHash)
* [getHtmlLink](#method-getHtmlLink)
* [getIdFromFilename](#method-getIdFromFilename)
* [getIdFromIdProduct](#method-getIdFromIdProduct)
* [getNewFilename](#method-getNewFilename)
* [getTextLink](#method-getTextLink)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [isLangMultishop](#method-isLangMultishop)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$_productIds"></a>$_productIds

```php
protected mixed $_productIds = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/ProductDownload.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L56).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L51).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L39).


### <a name="property-$date_expiration"></a>$date_expiration

```php
public string $date_expiration
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L42).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product_download', 'primary' => 'id_product_download', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'display_filename' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 255), 'filename' => array('type' => self::TYPE_STRING, 'validate' => 'isSha1', 'size' => 255), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_expiration' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'nb_days_accessible' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'nb_downloadable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_shareable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/ProductDownload.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L61).


### <a name="property-$display_filename"></a>$display_filename

```php
public string $display_filename
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L33).


### <a name="property-$filename"></a>$filename

```php
public string $filename
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L36).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L30).


### <a name="property-$is_shareable"></a>$is_shareable

```php
public boolean $is_shareable
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L54).


### <a name="property-$nb_days_accessible"></a>$nb_days_accessible

```php
public string $nb_days_accessible
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L45).


### <a name="property-$nb_downloadable"></a>$nb_downloadable

```php
public string $nb_downloadable
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L48).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L130).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L80).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L65).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L95).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L85).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L90).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L105).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L63).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L54).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L57).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L59).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L61).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L75).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L116).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L119).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L70).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L110).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L135).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L113).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ProductDownloadCore::__construct(integer $id_product_download)
```

Build a virtual product



* Visibility: **public**
* Source: [classes/ProductDownload.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L82)


#### Arguments
* $id_product_download **integer** - Existing productDownload id in order to load object (optional)



### <a name="method-add"></a>add

```php
mixed ProductDownloadCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L101)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1146](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1146)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1193](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1193)


#### Arguments
* $id_shops **integer|array**



### <a name="method-checkFile"></a>checkFile

```php
boolean ProductDownloadCore::checkFile()
```

Check if file exists



* Visibility: **public**
* Source: [classes/ProductDownload.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L152)




### <a name="method-checkWritableDir"></a>checkWritableDir

```php
boolean ProductDownloadCore::checkWritableDir()
```

Check if download repository is writable



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L163)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1160](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1160)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed ProductDownloadCore::delete($delete)
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L124)


#### Arguments
* $delete **mixed**



### <a name="method-deleteFile"></a>deleteFile

```php
boolean ProductDownloadCore::deleteFile(integer $id_product_download)
```

Delete the file



* Visibility: **public**
* Source: [classes/ProductDownload.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L138)


#### Arguments
* $id_product_download **integer** - : if we need to delete a specific product attribute file



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1319](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1319)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 737](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L737)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L939)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\new ObjectModelCore::duplicateObject()
```

Duplicate current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L528)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1237](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1237)


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
* Source: [classes/ObjectModel.php line 1356](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1356)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L335)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1222](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1222)




### <a name="method-getDeadline"></a>getDeadline

```php
string ProductDownloadCore::getDeadline()
```

Return a deadline



* Visibility: **public**
* Source: [classes/ProductDownload.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L276)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1462)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1569](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1569)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ProductDownloadCore::getFields()
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L92)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L300)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1138](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1138)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ObjectModelCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we considere they are already validated in getFields() method, this
not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L286)




### <a name="method-getFilenameFromFilename"></a>getFilenameFromFilename

```php
string ProductDownloadCore::getFilenameFromFilename(string $filename)
```

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L229)


#### Arguments
* $filename **string** - Filename physically



### <a name="method-getFilenameFromIdProduct"></a>getFilenameFromIdProduct

```php
string ProductDownloadCore::getFilenameFromIdProduct(integer $id_product)
```

Return the filename from an id_product



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L213)


#### Arguments
* $id_product **integer** - Product the id



### <a name="method-getHash"></a>getHash

```php
string ProductDownloadCore::getHash()
```

Return a hash for control download access



* Visibility: **public**
* Source: [classes/ProductDownload.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L289)




### <a name="method-getHtmlLink"></a>getHtmlLink

```php
string ProductDownloadCore::getHtmlLink(string $class, boolean $admin, boolean $hash)
```

Return html link



* Visibility: **public**
* Source: [classes/ProductDownload.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L261)


#### Arguments
* $class **string** - CSS selector
* $admin **boolean** - specific to backend
* $hash **boolean** - hash code in table order detail



### <a name="method-getIdFromFilename"></a>getIdFromFilename

```php
integer ProductDownloadCore::getIdFromFilename(string $filename)
```

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L199)


#### Arguments
* $filename **string** - Filename physically



### <a name="method-getIdFromIdProduct"></a>getIdFromIdProduct

```php
integer ProductDownloadCore::getIdFromIdProduct(integer $id_product)
```

Return the id_product_download from an id_product



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L174)


#### Arguments
* $id_product **integer** - Product the id



### <a name="method-getNewFilename"></a>getNewFilename

```php
string ProductDownloadCore::getNewFilename()
```

Return a sha1 filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L300)




### <a name="method-getTextLink"></a>getTextLink

```php
string ProductDownloadCore::getTextLink(boolean $admin, string $hash)
```

Return html link



* Visibility: **public**
* Source: [classes/ProductDownload.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L245)


#### Arguments
* $admin **boolean** - specific to backend (optionnal)
* $hash **string** - hash code in table order detail (optionnal)



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L769)


#### Arguments
* $fields_array **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L148)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1080](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1080)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($ws_params_attribute_name)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1006)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1262](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1262)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1394](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1394)


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
* Source: [classes/ObjectModel.php line 1413](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1413)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1175](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1175)


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
* Source: [classes/ObjectModel.php line 1374](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1374)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean ProductDownloadCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L313)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1274](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1274)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1269)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L785)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L425)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1500](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1500)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1595](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1595)


#### Arguments
* $fields **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L753)




### <a name="method-update"></a>update

```php
mixed ProductDownloadCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ProductDownload.php#L113)


#### Arguments
* $null_values **mixed**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1289](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1289)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L954)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 960](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L960)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 892](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L892)


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
* Source: [classes/ObjectModel.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L823)


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
* Source: [classes/ObjectModel.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L852)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1116)


#### Arguments
* $htmlentities **mixed**


