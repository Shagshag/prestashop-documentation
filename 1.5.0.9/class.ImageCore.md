Class ImageCore
=====================





* Class name: ImageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Image.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L28)


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
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
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
* [duplicateProductImages](#method-duplicateProductImages)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAllImages](#method-getAllImages)
* [getCover](#method-getCover)
* [getDefinition](#method-getDefinition)
* [getExistingImgPath](#method-getExistingImgPath)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
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
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [moveToNewFileSystem](#method-moveToNewFileSystem)
* [positionImage](#method-positionImage)
* [replaceAttributeImageAssociationId](#method-replaceAttributeImageAssociationId)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [testFileSystem](#method-testFileSystem)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updatePosition](#method-updatePosition)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_cacheGetSize"></a>$_cacheGetSize

```php
protected mixed $_cacheGetSize = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L73).


### <a name="property-$access_rights"></a>$access_rights

```php
protected integer $access_rights = 509
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L57).


### <a name="property-$cover"></a>$cover

```php
public boolean $cover
```





* Visibility: **public**
* Source: [classes/Image.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L42).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'image', 'primary' => 'id_image', 'multilang' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'cover' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Image.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L62).


### <a name="property-$existing_path"></a>$existing_path

```php
protected string $existing_path
```





* Visibility: **protected**
* Source: [classes/Image.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L54).


### <a name="property-$folder"></a>$folder

```php
protected string $folder
```





* Visibility: **protected**
* Source: [classes/Image.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L51).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Image.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L30).


### <a name="property-$id_image"></a>$id_image

```php
public integer $id_image
```





* Visibility: **public**
* Source: [classes/Image.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L33).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/Image.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L36).


### <a name="property-$image_format"></a>$image_format

```php
public string $image_format = 'jpg'
```





* Visibility: **public**
* Source: [classes/Image.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L45).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Image.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L39).


### <a name="property-$source_index"></a>$source_index

```php
public string $source_index
```





* Visibility: **public**
* Source: [classes/Image.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L48).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L97).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L108).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L102).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L105).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ImageCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Image.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L75)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed ImageCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Image.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L82)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L925)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L973)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L939)


#### Arguments
* $all **mixed**



### <a name="method-clearTmpDir"></a>clearTmpDir

```php
mixed ImageCore::clearTmpDir()
```

Clear all images in tmp dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L361)




### <a name="method-createImgFolder"></a>createImgFolder

```php
boolean ImageCore::createImgFolder()
```

Create parent folders for the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 515](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L515)




### <a name="method-delete"></a>delete

```php
mixed ImageCore::delete()
```





* Visibility: **public**
* Source: [classes/Image.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L90)




### <a name="method-deleteAllImages"></a>deleteAllImages

```php
boolean ImageCore::deleteAllImages(string $path, string $format)
```

Recursively deletes all product images in the given folder tree and removes empty folders.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L438)


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
* Source: [classes/Image.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L181)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-deleteImage"></a>deleteImage

```php
mixed ImageCore::deleteImage()
```

Delete the product image from disk and remove the containing folder if empty
Handles both legacy and new image filesystems



* Visibility: **public**
* Source: [classes/Image.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L383)




### <a name="method-deleteProductAttributeImage"></a>deleteProductAttributeImage

```php
mixed ImageCore::deleteProductAttributeImage()
```

Delete Image - Product attribute associations for this image



* Visibility: **public**
* Source: [classes/Image.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L370)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L559)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L757)


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
* Source: [classes/Image.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L270)


#### Arguments
* $combination_images **mixed**



### <a name="method-duplicateProductImages"></a>duplicateProductImages

```php
mixed ImageCore::duplicateProductImages(integer $id_product_old, boolean $id_product_new, $combination_images)
```

Copy images from a product to another



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L217)


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
* Source: [classes/ObjectModel.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1017)


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
* Source: [classes/ObjectModel.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1081)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L272)


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
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L319)


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
* Source: [classes/Image.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L137)




### <a name="method-getCover"></a>getCover

```php
boolean ImageCore::getCover(integer $id_product)
```

Get product cover



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L202)


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
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1184)


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
* Source: [classes/Image.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L478)




### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1261)


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
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L917)


#### Arguments
* $all **mixed**



### <a name="method-getHighestPosition"></a>getHighestPosition

```php
integer ImageCore::getHighestPosition(integer $id_product)
```

Return highest position of images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L166)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImages"></a>getImages

```php
array ImageCore::getImages(integer $id_lang, integer $id_product)
```

Return available images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L122)


#### Arguments
* $id_lang **integer** - Language ID
* $id_product **integer** - Product ID



### <a name="method-getImagesTotal"></a>getImagesTotal

```php
integer ImageCore::getImagesTotal(integer $id_product)
```

Return number of images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L151)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImgFolder"></a>getImgFolder

```php
string ImageCore::getImgFolder()
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 499](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L499)




### <a name="method-getImgFolderStatic"></a>getImgFolderStatic

```php
string ImageCore::getImgFolderStatic(mixed $id_image)
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L555)


#### Arguments
* $id_image **mixed**



### <a name="method-getImgPath"></a>getImgPath

```php
string ImageCore::getImgPath()
```

Returns the path to the image without file extension



* Visibility: **public**
* Source: [classes/Image.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L540)




### <a name="method-getPathForCreation"></a>getPathForCreation

```php
string ImageCore::getPathForCreation()
```

Returns the path where a product image should be created (without file format)



* Visibility: **public**
* Source: [classes/Image.php line 653](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L653)




### <a name="method-getSize"></a>getSize

```php
mixed ImageCore::getSize($type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L347)


#### Arguments
* $type **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L595)


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
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L130)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L890)


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
* Source: [classes/ObjectModel.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L816)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1116)


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
* Source: [classes/ObjectModel.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1135)


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
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1003)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L954)


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
* Source: [classes/ObjectModel.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1099)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1037)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L611)


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
* Source: [classes/Image.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L571)


#### Arguments
* $max_execution_time **mixed**



### <a name="method-positionImage"></a>positionImage

```php
mixed ImageCore::positionImage(integer $position, boolean $direction)
```

Reposition image



* Visibility: **public**
* Source: [classes/Image.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L289)


#### Arguments
* $position **integer** - Position
* $direction **boolean** - Direction



### <a name="method-replaceAttributeImageAssociationId"></a>replaceAttributeImageAssociationId

```php
mixed ImageCore::replaceAttributeImageAssociationId($combination_images, $saved_id, $id_image)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Image.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L255)


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
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L360)


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
* Source: [classes/ObjectModel.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1207)




### <a name="method-testFileSystem"></a>testFileSystem

```php
boolean ImageCore::testFileSystem()
```

Try to create and delete some folders to check if moving images to new file system will be possible



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L621)




### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L575)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L446)


#### Arguments
* $null_values **boolean**



### <a name="method-updatePosition"></a>updatePosition

```php
integer ImageCore::updatePosition(integer $way, integer $position)
```

Change an image position and update relative positions



* Visibility: **public**
* Source: [classes/Image.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Image.php#L324)


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
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L772)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L778)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L710)


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
* Source: [classes/ObjectModel.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L649)


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
* Source: [classes/ObjectModel.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L675)


#### Arguments
* $die **boolean**
* $error_return **boolean**


