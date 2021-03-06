Class ImageCore
=====================





* Class name: ImageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Image.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L27)


Contents
--------


### Properties

* [$_cacheGetSize](#property-$_cacheGetSize)
* [$access_rights](#property-$access_rights)
* [$cover](#property-$cover)
* [$definition](#property-$definition)
* [$existing_path](#property-$existing_path)
* [$folder](#property-$folder)
* [$id](#property-$id)
* [$id_image](#property-$id_image)
* [$id_product](#property-$id_product)
* [$image_format](#property-$image_format)
* [$position](#property-$position)
* [$source_index](#property-$source_index)
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
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [clearCache](#method-clearCache)
* [clearTmpDir](#method-clearTmpDir)
* [createImgFolder](#method-createImgFolder)
* [delete](#method-delete)
* [deleteAllImages](#method-deleteAllImages)
* [deleteCover](#method-deleteCover)
* [deleteImage](#method-deleteImage)
* [deleteProductAttributeImage](#method-deleteProductAttributeImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateAttributeImageAssociations](#method-duplicateAttributeImageAssociations)
* [duplicateObject](#method-duplicateObject)
* [duplicateProductImages](#method-duplicateProductImages)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAllImages](#method-getAllImages)
* [getAssociatedShops](#method-getAssociatedShops)
* [getCover](#method-getCover)
* [getDefinition](#method-getDefinition)
* [getExistingImgPath](#method-getExistingImgPath)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getHeight](#method-getHeight)
* [getHighestPosition](#method-getHighestPosition)
* [getImages](#method-getImages)
* [getImagesTotal](#method-getImagesTotal)
* [getImgFolder](#method-getImgFolder)
* [getImgFolderStatic](#method-getImgFolderStatic)
* [getImgPath](#method-getImgPath)
* [getPathForCreation](#method-getPathForCreation)
* [getSize](#method-getSize)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWidth](#method-getWidth)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [moveToNewFileSystem](#method-moveToNewFileSystem)
* [positionImage](#method-positionImage)
* [replaceAttributeImageAssociationId](#method-replaceAttributeImageAssociationId)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [testFileSystem](#method-testFileSystem)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [updatePosition](#method-updatePosition)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$_cacheGetSize"></a>$_cacheGetSize

```php
protected mixed $_cacheGetSize = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L72).


### <a name="property-$access_rights"></a>$access_rights

```php
protected integer $access_rights = 509
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L56).


### <a name="property-$cover"></a>$cover

```php
public boolean $cover
```





* Visibility: **public**
* Source: [classes/Image.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L41).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'image', 'primary' => 'id_image', 'multilang' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'cover' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'shop' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Image.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L61).


### <a name="property-$existing_path"></a>$existing_path

```php
protected string $existing_path
```





* Visibility: **protected**
* Source: [classes/Image.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L53).


### <a name="property-$folder"></a>$folder

```php
protected string $folder
```





* Visibility: **protected**
* Source: [classes/Image.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L50).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Image.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L29).


### <a name="property-$id_image"></a>$id_image

```php
public integer $id_image
```





* Visibility: **public**
* Source: [classes/Image.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L32).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/Image.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L35).


### <a name="property-$image_format"></a>$image_format

```php
public string $image_format = 'jpg'
```





* Visibility: **public**
* Source: [classes/Image.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L44).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Image.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L38).


### <a name="property-$source_index"></a>$source_index

```php
public string $source_index
```





* Visibility: **public**
* Source: [classes/Image.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L47).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L130).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L80).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L65).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L95).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L85).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L90).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L105).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L63).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L57).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L59).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L61).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L75).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L116).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L70).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L110).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L135).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L113).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ImageCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Image.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L74)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed ImageCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Image.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L81)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1182](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1182)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1229](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1229)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1169](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1169)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1196](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1196)


#### Arguments
* $all **mixed**



### <a name="method-clearTmpDir"></a>clearTmpDir

```php
mixed ImageCore::clearTmpDir()
```

Clear all images in tmp dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L392)




### <a name="method-createImgFolder"></a>createImgFolder

```php
boolean ImageCore::createImgFolder()
```

Create parent folders for the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L545)




### <a name="method-delete"></a>delete

```php
mixed ImageCore::delete()
```





* Visibility: **public**
* Source: [classes/Image.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L89)




### <a name="method-deleteAllImages"></a>deleteAllImages

```php
boolean ImageCore::deleteAllImages(string $path, string $format)
```

Recursively deletes all product images in the given folder tree and removes empty folders.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L468)


#### Arguments
* $path **string** - folder containing the product images to delete
* $format **string** - image format



### <a name="method-deleteCover"></a>deleteCover

```php
boolean ImageCore::deleteCover(integer $id_product)
```

Delete product cover



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L190)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-deleteImage"></a>deleteImage

```php
mixed ImageCore::deleteImage($force_delete)
```

Delete the product image from disk and remove the containing folder if empty
Handles both legacy and new image filesystems



* Visibility: **public**
* Source: [classes/Image.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L414)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteProductAttributeImage"></a>deleteProductAttributeImage

```php
mixed ImageCore::deleteProductAttributeImage()
```

Delete Image - Product attribute associations for this image



* Visibility: **public**
* Source: [classes/Image.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L401)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 734](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L734)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L958)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateAttributeImageAssociations"></a>duplicateAttributeImageAssociations

```php
boolean ImageCore::duplicateAttributeImageAssociations($combination_images)
```

Duplicate product attribute image associations



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L289)


#### Arguments
* $combination_images **mixed**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\new ObjectModelCore::duplicateObject()
```

Duplicate current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L518)




### <a name="method-duplicateProductImages"></a>duplicateProductImages

```php
mixed ImageCore::duplicateProductImages(integer $id_product_old, boolean $id_product_new, $combination_images)
```

Copy images from a product to another



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L231)


#### Arguments
* $id_product_old **integer** - Source product ID
* $id_product_new **boolean** - Destination product ID
* $combination_images **mixed**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1273](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1273)


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
* Source: [classes/ObjectModel.php line 1397](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1397)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L325)


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
* Source: [classes/ObjectModel.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L371)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAllImages"></a>getAllImages

```php
array ImageCore::getAllImages()
```

Return Images



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L146)




### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1258](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1258)




### <a name="method-getCover"></a>getCover

```php
boolean ImageCore::getCover(integer $id_product)
```

Get product cover



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L216)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1503](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1503)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getExistingImgPath"></a>getExistingImgPath

```php
mixed ImageCore::getExistingImgPath()
```

Returns image path in the old or in the new filesystem

@ returns string image path

* Visibility: **public**
* Source: [classes/Image.php line 508](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L508)




### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1610](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1610)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L253)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L290)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1161](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1161)


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
* Source: [classes/ObjectModel.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L276)




### <a name="method-getHeight"></a>getHeight

```php
mixed ImageCore::getHeight($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L383)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-getHighestPosition"></a>getHighestPosition

```php
integer ImageCore::getHighestPosition(integer $id_product)
```

Return highest position of images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L175)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImages"></a>getImages

```php
array ImageCore::getImages(integer $id_lang, integer $id_product, integer $id_product_attribute)
```

Return available images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L126)


#### Arguments
* $id_lang **integer** - Language ID
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Product Attribute ID



### <a name="method-getImagesTotal"></a>getImagesTotal

```php
integer ImageCore::getImagesTotal(integer $id_product)
```

Return number of images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L160)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImgFolder"></a>getImgFolder

```php
string ImageCore::getImgFolder()
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L529)




### <a name="method-getImgFolderStatic"></a>getImgFolderStatic

```php
string ImageCore::getImgFolderStatic(mixed $id_image)
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 585](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L585)


#### Arguments
* $id_image **mixed**



### <a name="method-getImgPath"></a>getImgPath

```php
string ImageCore::getImgPath()
```

Returns the path to the image without file extension



* Visibility: **public**
* Source: [classes/Image.php line 570](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L570)




### <a name="method-getPathForCreation"></a>getPathForCreation

```php
string ImageCore::getPathForCreation()
```

Returns the path where a product image should be created (without file format)



* Visibility: **public**
* Source: [classes/Image.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L683)




### <a name="method-getSize"></a>getSize

```php
mixed ImageCore::getSize($type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L366)


#### Arguments
* $type **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L769)


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
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L148)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1102](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1102)


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
* Source: [classes/ObjectModel.php line 1027](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1027)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWidth"></a>getWidth

```php
mixed ImageCore::getWidth($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L377)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1298](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1298)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1435](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1435)


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
* Source: [classes/ObjectModel.php line 1454](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1454)


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
* Source: [classes/ObjectModel.php line 1211](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1211)


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
* Source: [classes/ObjectModel.php line 1415](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1415)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1315](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1315)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
mixed ObjectModelCore::isMultiShopField($field)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1310](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1310)


#### Arguments
* $field **mixed**



### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1305](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1305)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L785)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-moveToNewFileSystem"></a>moveToNewFileSystem

```php
mixed ImageCore::moveToNewFileSystem($max_execution_time)
```

Move all legacy product image files from the image folder root to their subfolder in the new filesystem.

If max_execution_time is provided, stops before timeout and returns string "timeout".
If any image cannot be moved, stops and returns "false"

* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 601](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L601)


#### Arguments
* $max_execution_time **mixed**



### <a name="method-positionImage"></a>positionImage

```php
mixed ImageCore::positionImage(integer $position, boolean $direction)
```

Reposition image



* Visibility: **public**
* Source: [classes/Image.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L308)


#### Arguments
* $position **integer** - Position
* $direction **boolean** - Direction



### <a name="method-replaceAttributeImageAssociationId"></a>replaceAttributeImageAssociationId

```php
mixed ImageCore::replaceAttributeImageAssociationId($combination_images, $saved_id, $id_image)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Image.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L274)


#### Arguments
* $combination_images **mixed**
* $saved_id **mixed**
* $id_image **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L415)


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
* Source: [classes/ObjectModel.php line 1541](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1541)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1636](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1636)


#### Arguments
* $fields **array**



### <a name="method-testFileSystem"></a>testFileSystem

```php
boolean ImageCore::testFileSystem()
```

Try to create and delete some folders to check if moving images to new file system will be possible



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 651](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L651)




### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 750](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L750)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L574)


#### Arguments
* $null_values **boolean**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1330](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1330)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-updatePosition"></a>updatePosition

```php
integer ImageCore::updatePosition(integer $way, integer $position)
```

Change an image position and update relative positions



* Visibility: **public**
* Source: [classes/Image.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Image.php#L343)


#### Arguments
* $way **integer** - position is moved up if 0, moved down if 1
* $position **integer** - new position of the moved image



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L973)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 979](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L979)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 896](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L896)


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
* Source: [classes/ObjectModel.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L823)


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
* Source: [classes/ObjectModel.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L852)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1138](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ObjectModel.php#L1138)


#### Arguments
* $htmlentities **mixed**


