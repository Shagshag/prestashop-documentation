Class ImageCore
=====================





* Class name: ImageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Image.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L27)


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
* [$legend](#property-$legend)
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
* [$force_id](#property-$force_id)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$loaded_classes](#property-$loaded_classes)
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
* Source: [classes/Image.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L76).


### <a name="property-$access_rights"></a>$access_rights

```php
protected integer $access_rights = 509
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L59).


### <a name="property-$cover"></a>$cover

```php
public boolean $cover
```





* Visibility: **public**
* Source: [classes/Image.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L41).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'image', 'primary' => 'id_image', 'multilang' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'cover' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'shop' => true), 'legend' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Image.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L64).


### <a name="property-$existing_path"></a>$existing_path

```php
protected string $existing_path
```





* Visibility: **protected**
* Source: [classes/Image.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L56).


### <a name="property-$folder"></a>$folder

```php
protected string $folder
```





* Visibility: **protected**
* Source: [classes/Image.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L53).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Image.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L29).


### <a name="property-$id_image"></a>$id_image

```php
public integer $id_image
```





* Visibility: **public**
* Source: [classes/Image.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L32).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/Image.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L35).


### <a name="property-$image_format"></a>$image_format

```php
public string $image_format = 'jpg'
```





* Visibility: **public**
* Source: [classes/Image.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L47).


### <a name="property-$legend"></a>$legend

```php
public string $legend
```





* Visibility: **public**
* Source: [classes/Image.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L44).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Image.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L38).


### <a name="property-$source_index"></a>$source_index

```php
public string $source_index
```





* Visibility: **public**
* Source: [classes/Image.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L50).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L143).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L133).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L106).


### <a name="property-$force_id"></a>$force_id

```php
public \boolean, $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L148).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L64).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L60).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L117).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected mixed $loaded_classes = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L128).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L138).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L114).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ImageCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Image.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L78)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed ImageCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Image.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L85)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1238)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1290](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1290)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1225)


#### Arguments
* $all **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1252)


#### Arguments
* $all **mixed**



### <a name="method-clearTmpDir"></a>clearTmpDir

```php
mixed ImageCore::clearTmpDir()
```

Clear all images in tmp dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L396)




### <a name="method-createImgFolder"></a>createImgFolder

```php
boolean ImageCore::createImgFolder()
```

Create parent folders for the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L549)




### <a name="method-delete"></a>delete

```php
mixed ImageCore::delete()
```





* Visibility: **public**
* Source: [classes/Image.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L93)




### <a name="method-deleteAllImages"></a>deleteAllImages

```php
boolean ImageCore::deleteAllImages(string $path, string $format)
```

Recursively deletes all product images in the given folder tree and removes empty folders.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L472)


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
* Source: [classes/Image.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L194)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-deleteImage"></a>deleteImage

```php
mixed ImageCore::deleteImage($force_delete)
```

Delete the product image from disk and remove the containing folder if empty
Handles both legacy and new image filesystems



* Visibility: **public**
* Source: [classes/Image.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L418)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteProductAttributeImage"></a>deleteProductAttributeImage

```php
mixed ImageCore::deleteProductAttributeImage()
```

Delete Image - Product attribute associations for this image



* Visibility: **public**
* Source: [classes/Image.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L405)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 763](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L763)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1008](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1008)


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
* Source: [classes/Image.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L293)


#### Arguments
* $combination_images **mixed**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\new ObjectModelCore::duplicateObject()
```

Duplicate current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 543](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L543)




### <a name="method-duplicateProductImages"></a>duplicateProductImages

```php
mixed ImageCore::duplicateProductImages(integer $id_product_old, boolean $id_product_new, $combination_images)
```

Copy images from a product to another



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L235)


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
* Source: [classes/ObjectModel.php line 1334](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1334)


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
* Source: [classes/ObjectModel.php line 1458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1458)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L342)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes, $purify)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L389)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**
* $purify **mixed**



### <a name="method-getAllImages"></a>getAllImages

```php
array ImageCore::getAllImages()
```

Return Images



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L150)




### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1319)




### <a name="method-getCover"></a>getCover

```php
boolean ImageCore::getCover(integer $id_product)
```

Get product cover



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L220)


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
* Source: [classes/ObjectModel.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1564)


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
* Source: [classes/Image.php line 512](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L512)




### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1671)


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
* Source: [classes/ObjectModel.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L270)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L307)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1217)


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
* Source: [classes/ObjectModel.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L293)




### <a name="method-getHeight"></a>getHeight

```php
mixed ImageCore::getHeight($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L387)


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
* Source: [classes/Image.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L179)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImages"></a>getImages

```php
array ImageCore::getImages(integer $id_lang, integer $id_product, integer $id_product_attribute)
```

Return available images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L130)


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
* Source: [classes/Image.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L164)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImgFolder"></a>getImgFolder

```php
string ImageCore::getImgFolder()
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L533)




### <a name="method-getImgFolderStatic"></a>getImgFolderStatic

```php
string ImageCore::getImgFolderStatic(mixed $id_image)
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L589)


#### Arguments
* $id_image **mixed**



### <a name="method-getImgPath"></a>getImgPath

```php
string ImageCore::getImgPath()
```

Returns the path to the image without file extension



* Visibility: **public**
* Source: [classes/Image.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L574)




### <a name="method-getPathForCreation"></a>getPathForCreation

```php
string ImageCore::getPathForCreation()
```

Returns the path where a product image should be created (without file format)



* Visibility: **public**
* Source: [classes/Image.php line 687](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L687)




### <a name="method-getSize"></a>getSize

```php
mixed ImageCore::getSize($type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L370)


#### Arguments
* $type **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 798](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L798)


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
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L156)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1158)


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
* Source: [classes/ObjectModel.php line 1080](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1080)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWidth"></a>getWidth

```php
mixed ImageCore::getWidth($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L381)


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
* Source: [classes/ObjectModel.php line 1359](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1359)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1496](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1496)


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
* Source: [classes/ObjectModel.php line 1515](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1515)


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
* Source: [classes/ObjectModel.php line 1267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1267)


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
* Source: [classes/ObjectModel.php line 1476](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1476)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1376](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1376)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
mixed ObjectModelCore::isMultiShopField($field)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1371)


#### Arguments
* $field **mixed**



### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1366](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1366)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 814](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L814)


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
* Source: [classes/Image.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L605)


#### Arguments
* $max_execution_time **mixed**



### <a name="method-positionImage"></a>positionImage

```php
mixed ImageCore::positionImage(integer $position, boolean $direction)
```

Reposition image



* Visibility: **public**
* Source: [classes/Image.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L312)


#### Arguments
* $position **integer** - Position
* $direction **boolean** - Direction



### <a name="method-replaceAttributeImageAssociationId"></a>replaceAttributeImageAssociationId

```php
mixed ImageCore::replaceAttributeImageAssociationId($combination_images, $saved_id, $id_image)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Image.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L278)


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
* Source: [classes/ObjectModel.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L440)


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
* Source: [classes/ObjectModel.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1602)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1697)


#### Arguments
* $fields **array**



### <a name="method-testFileSystem"></a>testFileSystem

```php
boolean ImageCore::testFileSystem()
```

Try to create and delete some folders to check if moving images to new file system will be possible



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 655](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L655)




### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L779)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 599](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L599)


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
* Source: [classes/ObjectModel.php line 1391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1391)


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
* Source: [classes/Image.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Image.php#L347)


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
* Source: [classes/ObjectModel.php line 1026](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1026)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1032)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang, $skip, $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L925)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**
* $skip **mixed**
* $human_errors **mixed**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L852)


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
* Source: [classes/ObjectModel.php line 881](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L881)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1194)


#### Arguments
* $htmlentities **mixed**


