Class ManufacturerCore
=====================





* Class name: ManufacturerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Manufacturer.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L28)


Contents
--------


### Properties

* [$active](#property-$active)
* [$cacheName](#property-$cacheName)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$description](#property-$description)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_address](#property-$id_address)
* [$id_manufacturer](#property-$id_manufacturer)
* [$identifier](#property-$identifier)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$name](#property-$name)
* [$short_description](#property-$short_description)
* [$table](#property-$table)
* [$webserviceParameters](#property-$webserviceParameters)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getAddresses](#method-getAddresses)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getIdByName](#method-getIdByName)
* [getIdentifier](#method-getIdentifier)
* [getLink](#method-getLink)
* [getManufacturerAddress](#method-getManufacturerAddress)
* [getManufacturers](#method-getManufacturers)
* [getNameById](#method-getNameById)
* [getProducts](#method-getProducts)
* [getProductsLite](#method-getProductsLite)
* [getTranslationsFields](#method-getTranslationsFields)
* [getTranslationsFieldsChild](#method-getTranslationsFieldsChild)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsAddresses](#method-getWsAddresses)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [manufacturerExists](#method-manufacturerExists)
* [save](#method-save)
* [setWsAddresses](#method-setWsAddresses)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L66).


### <a name="property-$cacheName"></a>$cacheName

```php
protected mixed $cacheName = array()
```

Return name from id



* Visibility: **protected**
* This property is **static**.
* Source: [classes/Manufacturer.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L233).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L48).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L51).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L39).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('name')
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L68).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('name' => 64)
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L69).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array('short_description' => 254, 'meta_title' => 128, 'meta_description' => 255, 'meta_description' => 255)
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L72).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('name' => 'isCatalogName')
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L70).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array('description' => 'isString', 'short_description' => 'isString', 'meta_title' => 'isGenericName', 'meta_description' => 'isGenericName', 'meta_keywords' => 'isGenericName')
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L73).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L30).


### <a name="property-$id_address"></a>$id_address

```php
public integer $id_address
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L45).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L33).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_manufacturer'
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L82).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L54).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L63).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L60).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L57).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L36).


### <a name="property-$short_description"></a>$short_description

```php
public string $short_description
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L42).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'manufacturer'
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L81).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('active' => array(), 'link_rewrite' => array('getter' => 'getLink', 'setter' => false)), 'associations' => array('addresses' => array('resource' => 'address', 'setter' => false, 'fields' => array('id' => array('xlink_resource' => 'addresses')))))
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L84).


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


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L59).


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


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ManufacturerCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L96)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed ObjectModelCore::add($autodate, $nullValues)
```

Add current object to database

return boolean Insertion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L202)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L780)


#### Arguments
* $fields **mixed**



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
mixed ManufacturerCore::delete()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L130)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L898)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ManufacturerCore::deleteSelection($selection)
```

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/Manufacturer.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L144)


#### Arguments
* $selection **mixed**



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



### <a name="method-getAddresses"></a>getAddresses

```php
mixed ManufacturerCore::getAddresses($id_lang)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L375)


#### Arguments
* $id_lang **mixed**



### <a name="method-getFields"></a>getFields

```php
mixed ManufacturerCore::getFields()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L106)




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




### <a name="method-getIdByName"></a>getIdByName

```php
mixed ManufacturerCore::getIdByName($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L246)


#### Arguments
* $name **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getLink"></a>getLink

```php
mixed ManufacturerCore::getLink()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L257)




### <a name="method-getManufacturerAddress"></a>getManufacturerAddress

```php
mixed ManufacturerCore::getManufacturerAddress()
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L158)




### <a name="method-getManufacturers"></a>getManufacturers

```php
array ManufacturerCore::getManufacturers(boolean $get_nb_products, $id_lang, $active, $p, $n, $all_group, $id_group_shop)
```

Return manufacturers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L178)


#### Arguments
* $get_nb_products **boolean** - [optional] return products numbers for each
* $id_lang **mixed**
* $active **mixed**
* $p **mixed**
* $n **mixed**
* $all_group **mixed**
* $id_group_shop **mixed**



### <a name="method-getNameById"></a>getNameById

```php
mixed ManufacturerCore::getNameById($id_manufacturer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L234)


#### Arguments
* $id_manufacturer **mixed**



### <a name="method-getProducts"></a>getProducts

```php
mixed ManufacturerCore::getProducts($id_manufacturer, $id_lang, $p, $n, $order_by, $order_way, $get_total, $active, $active_category, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L262)


#### Arguments
* $id_manufacturer **mixed**
* $id_lang **mixed**
* $p **mixed**
* $n **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $get_total **mixed**
* $active **mixed**
* $active_category **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductsLite"></a>getProductsLite

```php
mixed ManufacturerCore::getProductsLite($id_lang)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L350)


#### Arguments
* $id_lang **mixed**



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
mixed ManufacturerCore::getTranslationsFieldsChild()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L118)




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



### <a name="method-getWsAddresses"></a>getWsAddresses

```php
mixed ManufacturerCore::getWsAddresses()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L386)




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



### <a name="method-manufacturerExists"></a>manufacturerExists

```php
mixed ManufacturerCore::manufacturerExists($id_manufacturer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L365)


#### Arguments
* $id_manufacturer **mixed**



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



### <a name="method-setWsAddresses"></a>setWsAddresses

```php
mixed ManufacturerCore::setWsAddresses($id_addresses)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Manufacturer.php#L395)


#### Arguments
* $id_addresses **mixed**



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
boolean ObjectModelCore::update($nullValues)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L274)


#### Arguments
* $nullValues **mixed**



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


