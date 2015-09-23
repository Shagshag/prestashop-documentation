Class ImageCore
=====================





* Class name: ImageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Image.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L27)


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
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [duplicateAttributeImageAssociations](#method-duplicateAttributeImageAssociations)
* [duplicateObject](#method-duplicateObject)
* [duplicateProductImages](#method-duplicateProductImages)
* [duplicateShops](#method-duplicateShops)
* [enableCache](#method-enableCache)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAllImages](#method-getAllImages)
* [getAssociatedShops](#method-getAssociatedShops)
* [getBestImageAttribute](#method-getBestImageAttribute)
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
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getSize](#method-getSize)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWidth](#method-getWidth)
* [hasImages](#method-hasImages)
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
* Source: [classes/Image.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L76).


### <a name="property-$access_rights"></a>$access_rights

```php
protected integer $access_rights = 509
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L59).


### <a name="property-$cover"></a>$cover

```php
public boolean $cover
```





* Visibility: **public**
* Source: [classes/Image.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L41).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'image', 'primary' => 'id_image', 'multilang' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'shop' => 'both', 'validate' => 'isUnsignedId', 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'cover' => array('type' => self::TYPE_BOOL, 'allow_null' => true, 'validate' => 'isBool', 'shop' => true), 'legend' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Image.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L64).


### <a name="property-$existing_path"></a>$existing_path

```php
protected string $existing_path
```





* Visibility: **protected**
* Source: [classes/Image.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L56).


### <a name="property-$folder"></a>$folder

```php
protected string $folder
```





* Visibility: **protected**
* Source: [classes/Image.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L53).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Image.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L29).


### <a name="property-$id_image"></a>$id_image

```php
public integer $id_image
```





* Visibility: **public**
* Source: [classes/Image.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L32).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/Image.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L35).


### <a name="property-$image_format"></a>$image_format

```php
public string $image_format = 'jpg'
```





* Visibility: **public**
* Source: [classes/Image.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L47).


### <a name="property-$legend"></a>$legend

```php
public string $legend
```





* Visibility: **public**
* Source: [classes/Image.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L44).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Image.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L38).


### <a name="property-$source_index"></a>$source_index

```php
public string $source_index
```





* Visibility: **public**
* Source: [classes/Image.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L50).


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L164).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L150).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected array $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L88).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected array $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L70).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L106).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L94).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L112).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected array $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L118).


### <a name="property-$force_id"></a>$force_id

```php
public boolean $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L159).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected boolean $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L67).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected integer $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L61).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public array $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L64).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L82).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L130).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected array $loaded_classes = array()
```

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L147).


### <a name="property-$table"></a>$table

```php
protected string $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L76).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L124).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L153).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L127).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ImageCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Image.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L78)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed ImageCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Image.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L85)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)
```

Sets required field for this class in the database.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1340)


#### Arguments
* $fields **array**



### <a name="method-associateTo"></a>associateTo

```php
boolean|void ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1408)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)
```

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1319)


#### Arguments
* $all **boolean** - If true, caches required fields of all object classes.



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache(boolean $all)
```

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1360)


#### Arguments
* $all **boolean** - If true, clears cache for all objects



### <a name="method-clearTmpDir"></a>clearTmpDir

```php
mixed ImageCore::clearTmpDir()
```

Clear all images in tmp dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L460)




### <a name="method-createImgFolder"></a>createImgFolder

```php
boolean ImageCore::createImgFolder()
```

Create parent folders for the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L617)




### <a name="method-delete"></a>delete

```php
mixed ImageCore::delete()
```





* Visibility: **public**
* Source: [classes/Image.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L109)




### <a name="method-deleteAllImages"></a>deleteAllImages

```php
boolean ImageCore::deleteAllImages(string $path, string $format)
```

Recursively deletes all product images in the given folder tree and removes empty folders.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L540)


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
* Source: [classes/Image.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L255)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-deleteImage"></a>deleteImage

```php
mixed ImageCore::deleteImage($force_delete)
```

Delete the product image from disk and remove the containing folder if empty
Handles both legacy and new image filesystems



* Visibility: **public**
* Source: [classes/Image.php line 482](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L482)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteProductAttributeImage"></a>deleteProductAttributeImage

```php
mixed ImageCore::deleteProductAttributeImage()
```

Delete Image - Product attribute associations for this image



* Visibility: **public**
* Source: [classes/Image.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L469)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $ids)
```

Deletes multiple objects from the database at once



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 765](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L765)


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
* Source: [classes/ObjectModel.php line 1892](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1892)




### <a name="method-displayFieldName"></a>displayFieldName

```php
string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)
```

Returns field name translation



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1051](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1051)


#### Arguments
* $field **string** - Field name
* $class **string** - ObjectModel class name
* $htmlentities **boolean** - If true, applies htmlentities() to result string
* $context **[Context](class.ContextCore.md)|null** - Context object



### <a name="method-duplicateAttributeImageAssociations"></a>duplicateAttributeImageAssociations

```php
boolean ImageCore::duplicateAttributeImageAssociations($combination_images)
```

Duplicate product attribute image associations



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L357)


#### Arguments
* $combination_images **mixed**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\ObjectModel|false ObjectModelCore::duplicateObject()
```

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L534)




### <a name="method-duplicateProductImages"></a>duplicateProductImages

```php
mixed ImageCore::duplicateProductImages(integer $id_product_old, boolean $id_product_new, $combination_images)
```

Copy images from a product to another



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L296)


#### Arguments
* $id_product_old **integer** - Source product ID
* $id_product_new **boolean** - Destination product ID
* $combination_images **mixed**



### <a name="method-duplicateShops"></a>duplicateShops

```php
boolean|void ObjectModelCore::duplicateShops($id)
```

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1462)


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
* Source: [classes/ObjectModel.php line 1884](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1884)




### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1624](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1624)


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
* Source: [classes/ObjectModel.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L322)


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
* Source: [classes/ObjectModel.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L373)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### <a name="method-getAllImages"></a>getAllImages

```php
array ImageCore::getAllImages()
```

Return Images



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L211)




### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1440)




### <a name="method-getBestImageAttribute"></a>getBestImageAttribute

```php
array ImageCore::getBestImageAttribute(integer $id_shop, integer $id_lang, integer $id_product, integer $id_product_attribute)
```

Return first image (by position) associated with a product attribute



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L137)


#### Arguments
* $id_shop **integer** - Shop ID
* $id_lang **integer** - Language ID
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Product Attribute ID



### <a name="method-getCover"></a>getCover

```php
boolean ImageCore::getCover(integer $id_product)
```

Get product cover



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L281)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string|null $field)
```

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1740](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1740)


#### Arguments
* $class **string** - Name of object
* $field **string|null** - Name of field if we want the definition of one field only



### <a name="method-getExistingImgPath"></a>getExistingImgPath

```php
mixed ImageCore::getExistingImgPath()
```

Returns image path in the old or in the new filesystem

@ returns string image path

* Visibility: **public**
* Source: [classes/Image.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L580)




### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)
```

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1849](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1849)


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
* Source: [classes/ObjectModel.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L243)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L284)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)
```

Returns an array of required fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1306)


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
* Source: [classes/ObjectModel.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L267)




### <a name="method-getHeight"></a>getHeight

```php
mixed ImageCore::getHeight($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L451)


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
* Source: [classes/Image.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L240)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImages"></a>getImages

```php
array ImageCore::getImages(integer $id_lang, integer $id_product, integer $id_product_attribute)
```

Return available images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L169)


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
* Source: [classes/Image.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L225)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImgFolder"></a>getImgFolder

```php
string ImageCore::getImgFolder()
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 601](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L601)




### <a name="method-getImgFolderStatic"></a>getImgFolderStatic

```php
string ImageCore::getImgFolderStatic(mixed $id_image)
```

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L657)


#### Arguments
* $id_image **mixed**



### <a name="method-getImgPath"></a>getImgPath

```php
string ImageCore::getImgPath()
```

Returns the path to the image without file extension



* Visibility: **public**
* Source: [classes/Image.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L642)




### <a name="method-getPathForCreation"></a>getPathForCreation

```php
string ImageCore::getPathForCreation()
```

Returns the path where a product image should be created (without file format)



* Visibility: **public**
* Source: [classes/Image.php line 755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L755)




### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

```php
mixed ObjectModelCore::getRepositoryClassName()
```

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L166)




### <a name="method-getSize"></a>getSize

```php
mixed ImageCore::getSize($type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L434)


#### Arguments
* $type **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array ObjectModelCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L806)


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
* Source: [classes/ObjectModel.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L178)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)
```

Returns webservice object list.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1230)


#### Arguments
* $sql_join **string**
* $sql_filter **string**
* $sql_sort **string**
* $sql_limit **string**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
array ObjectModelCore::getWebserviceParameters(string|null $ws_params_attribute_name)
```

Returns webservice parameters of this object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1140)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-getWidth"></a>getWidth

```php
mixed ImageCore::getWidth($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L445)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-hasImages"></a>hasImages

```php
boolean ImageCore::hasImages(integer $id_lang, integer $id_product, integer $id_product_attribute)
```

Check if a product has an image available



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L192)


#### Arguments
* $id_lang **integer** - Language ID
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Product Attribute ID



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1488)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer|null $id_lang)
```

Fill an object with given data. Data must be an array with this syntax:
array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1666](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1666)


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
* Source: [classes/ObjectModel.php line 1688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1688)


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
* Source: [classes/ObjectModel.php line 1375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1375)


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
* Source: [classes/ObjectModel.php line 1644](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1644)


#### Arguments
* $table **string|null** - Name of table linked to entity
* $has_active_column **boolean** - True if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
boolean ObjectModelCore::isLangMultishop()
```

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1523)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
boolean ObjectModelCore::isMultiShopField(string $field)
```

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1513](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1513)


#### Arguments
* $field **string**



### <a name="method-isMultishop"></a>isMultishop

```php
boolean ObjectModelCore::isMultishop()
```

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1501)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L827)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-moveToNewFileSystem"></a>moveToNewFileSystem

```php
mixed ImageCore::moveToNewFileSystem(integer $max_execution_time)
```

Move all legacy product image files from the image folder root to their subfolder in the new filesystem.

If max_execution_time is provided, stops before timeout and returns string "timeout".
If any image cannot be moved, stops and returns "false"

* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 673](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L673)


#### Arguments
* $max_execution_time **integer**



### <a name="method-positionImage"></a>positionImage

```php
mixed ImageCore::positionImage(integer $position, boolean $direction)
```

Reposition image



* Visibility: **public**
* Source: [classes/Image.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L376)


#### Arguments
* $position **integer** - Position
* $direction **boolean** - Direction



### <a name="method-replaceAttributeImageAssociationId"></a>replaceAttributeImageAssociationId

```php
mixed ImageCore::replaceAttributeImageAssociationId($combination_images, $saved_id, $id_image)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Image.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L342)


#### Arguments
* $combination_images **mixed**
* $saved_id **mixed**
* $id_image **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $auto_date)
```

Saves current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L429)


#### Arguments
* $null_values **boolean**
* $auto_date **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1778)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1876)


#### Arguments
* $fields **array**



### <a name="method-testFileSystem"></a>testFileSystem

```php
boolean ImageCore::testFileSystem()
```

Try to create and delete some folders to check if moving images to new file system will be possible



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L723)




### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggles object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L783)




### <a name="method-update"></a>update

```php
mixed ImageCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Image.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L98)


#### Arguments
* $null_values **mixed**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1539](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1539)


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
* Source: [classes/Image.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Image.php#L411)


#### Arguments
* $way **integer** - position is moved up if 0, moved down if 1
* $position **integer** - new position of the moved image



### <a name="method-validateControler"></a>validateControler

```php
array ObjectModelCore::validateControler(boolean $htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1071](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1071)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

```php
array ObjectModelCore::validateController(boolean $htmlentities)
```

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1084](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1084)


#### Arguments
* $htmlentities **boolean** - If true, uses htmlentities() for field name translations in errors.



### <a name="method-validateField"></a>validateField

```php
true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L946)


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
* Source: [classes/ObjectModel.php line 867](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L867)


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
* Source: [classes/ObjectModel.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L898)


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
* Source: [classes/ObjectModel.php line 1275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1275)


#### Arguments
* $htmlentities **boolean**


