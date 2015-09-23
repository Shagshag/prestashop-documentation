Class SceneCore
=====================





* Class name: SceneCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Scene.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L28)


Contents
--------


### Properties

* [$active](#property-$active)
* [$categories](#property-$categories)
* [$feature_active](#property-$feature_active)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$identifier](#property-$identifier)
* [$name](#property-$name)
* [$products](#property-$products)
* [$table](#property-$table)
* [$zones](#property-$zones)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsSize](#property-$fieldsSize)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addCategories](#method-addCategories)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addZoneProducts](#method-addZoneProducts)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteCategories](#method-deleteCategories)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [deleteZoneProducts](#method-deleteZoneProducts)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getIdentifier](#method-getIdentifier)
* [getIndexedCategories](#method-getIndexedCategories)
* [getProducts](#method-getProducts)
* [getScenes](#method-getScenes)
* [getTranslationsFields](#method-getTranslationsFields)
* [getTranslationsFieldsChild](#method-getTranslationsFieldsChild)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hideScenePosition](#method-hideScenePosition)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateCategories](#method-updateCategories)
* [updateZoneProducts](#method-updateZoneProducts)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Scene.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L34).


### <a name="property-$categories"></a>$categories

```php
public array $categories = array()
```





* Visibility: **public**
* Source: [classes/Scene.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L40).


### <a name="property-$feature_active"></a>$feature_active

```php
protected mixed $feature_active = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Scene.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L54).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('active')
```





* Visibility: **protected**
* Source: [classes/Scene.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L48).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array('name')
```





* Visibility: **protected**
* Source: [classes/Scene.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L50).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array('name' => 100)
```





* Visibility: **protected**
* Source: [classes/Scene.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L51).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('active' => 'isBool', 'zones' => 'isSceneZones', 'categories' => 'isArrayWithIds')
```





* Visibility: **protected**
* Source: [classes/Scene.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L49).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array('name' => 'isGenericName')
```





* Visibility: **protected**
* Source: [classes/Scene.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L52).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_scene'
```





* Visibility: **protected**
* Source: [classes/Scene.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L46).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Scene.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L31).


### <a name="property-$products"></a>$products

```php
public array $products
```





* Visibility: **public**
* Source: [classes/Scene.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L43).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'scene'
```





* Visibility: **protected**
* Source: [classes/Scene.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L45).


### <a name="property-$zones"></a>$zones

```php
public array $zones = array()
```





* Visibility: **public**
* Source: [classes/Scene.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L37).


### <a name="property-$_cache"></a>$_cache

```php
protected mixed $_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L75).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected \fieldsRequiredDatabase $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L50).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L53).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L31).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L34).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L36).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L78).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L81).


### <a name="property-$langMultiShop"></a>$langMultiShop

```php
protected mixed $langMultiShop = false
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L67).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L70).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed SceneCore::__construct($id, $id_lang, $liteResult, $hideScenePosition)
```





* Visibility: **public**
* Source: [classes/Scene.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L56)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $liteResult **mixed**
* $hideScenePosition **mixed**



### <a name="method-add"></a>add

```php
mixed SceneCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/Scene.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L102)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addCategories"></a>addCategories

```php
mixed SceneCore::addCategories($categories)
```





* Visibility: **public**
* Source: [classes/Scene.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L144)


#### Arguments
* $categories **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L780)


#### Arguments
* $fields **mixed**



### <a name="method-addZoneProducts"></a>addZoneProducts

```php
mixed SceneCore::addZoneProducts($zones)
```





* Visibility: **public**
* Source: [classes/Scene.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L171)


#### Arguments
* $zones **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 828](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L828)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L794)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed SceneCore::delete()
```





* Visibility: **public**
* Source: [classes/Scene.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L119)




### <a name="method-deleteCategories"></a>deleteCategories

```php
mixed SceneCore::deleteCategories()
```





* Visibility: **public**
* Source: [classes/Scene.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L155)




### <a name="method-deleteImage"></a>deleteImage

```php
mixed SceneCore::deleteImage()
```





* Visibility: **public**
* Source: [classes/Scene.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L131)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ObjectModelCore::deleteSelection($selection)
```

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L387)


#### Arguments
* $selection **mixed**



### <a name="method-deleteZoneProducts"></a>deleteZoneProducts

```php
mixed SceneCore::deleteZoneProducts()
```





* Visibility: **public**
* Source: [classes/Scene.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L185)




### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L558)


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
* Source: [classes/ObjectModel.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L868)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase($id_entity, $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 931](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L931)


#### Arguments
* $id_entity **mixed** - entity id
* $table **mixed**



### <a name="method-getFields"></a>getFields

```php
mixed SceneCore::getFields()
```





* Visibility: **public**
* Source: [classes/Scene.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L67)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L772)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsValidateLang"></a>getFieldsValidateLang

```php
array ObjectModelCore::getFieldsValidateLang()
```

Get list of fields related to language to validate



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L975)




### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getIndexedCategories"></a>getIndexedCategories

```php
array SceneCore::getIndexedCategories(integer $id_scene)
```

Get categories where scene is indexed



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L270)


#### Arguments
* $id_scene **integer** - Scene id



### <a name="method-getProducts"></a>getProducts

```php
array SceneCore::getProducts($onlyActive, $id_lang, $liteResult, \Context $context)
```

Get all products of this scene



* Visibility: **public**
* Source: [classes/Scene.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L237)


#### Arguments
* $onlyActive **mixed**
* $id_lang **mixed**
* $liteResult **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getScenes"></a>getScenes

```php
array SceneCore::getScenes($id_category, $id_lang, $onlyActive, $liteResult, $hideScenePosition, \Context $context)
```

Get all scenes of a category



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L206)


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**
* $onlyActive **mixed**
* $liteResult **mixed**
* $hideScenePosition **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields(array $fieldsArray)
```

Prepare multilingual fields for database insertion



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L430)


#### Arguments
* $fieldsArray **array** - Multilingual fields to prepare
return array Prepared fields for database insertion



### <a name="method-getTranslationsFieldsChild"></a>getTranslationsFieldsChild

```php
array SceneCore::getTranslationsFieldsChild()
```

Check then return multilingual fields for database interaction



* Visibility: **public**
* Source: [classes/Scene.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L79)




### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L89)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L747)


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
* Source: [classes/ObjectModel.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L617)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-hideScenePosition"></a>hideScenePosition

```php
string SceneCore::hideScenePosition(string $name)
```

Hide scene prefix used for position



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L284)


#### Arguments
* $name **string** - Scene name



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L987)


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
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L1006)


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
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L854)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L809)


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
* Source: [classes/ObjectModel.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L948)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean SceneCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L294)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L888)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L447)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
mixed ObjectModelCore::save($nullValues, $autodate)
```

Save current object to database (add or update)

return boolean Insertion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L192)


#### Arguments
* $nullValues **mixed**
* $autodate **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed ObjectModelCore::toggleStatus()
```

Toggle object status in database

return boolean Update result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L405)




### <a name="method-update"></a>update

```php
mixed SceneCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Scene.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L85)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateCategories"></a>updateCategories

```php
mixed SceneCore::updateCategories()
```





* Visibility: **public**
* Source: [classes/Scene.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L162)




### <a name="method-updateZoneProducts"></a>updateZoneProducts

```php
mixed SceneCore::updateZoneProducts()
```





* Visibility: **public**
* Source: [classes/Scene.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Scene.php#L192)




### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L571)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L577)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateFields"></a>validateFields

```php
mixed ObjectModelCore::validateFields($die, $errorReturn)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L481)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
mixed ObjectModelCore::validateFieldsLang($die, $errorReturn)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L514)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**


