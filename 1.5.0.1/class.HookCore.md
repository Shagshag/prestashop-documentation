Class HookCore
=====================





* Class name: HookCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Hook.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L28)


Contents
--------


### Properties

* [$_hookModulesCache](#property-$_hookModulesCache)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$identifier](#property-$identifier)
* [$name](#property-$name)
* [$preloadHookAlias](#property-$preloadHookAlias)
* [$preloadModulesFromHooks](#property-$preloadModulesFromHooks)
* [$table](#property-$table)
* [$title](#property-$title)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [PDFInvoice](#method-PDFInvoice)
* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addProduct](#method-addProduct)
* [associateTo](#method-associateTo)
* [backBeforePayment](#method-backBeforePayment)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteProduct](#method-deleteProduct)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [exec](#method-exec)
* [existsInDatabase](#method-existsInDatabase)
* [get](#method-get)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getHooks](#method-getHooks)
* [getIdByName](#method-getIdByName)
* [getIdentifier](#method-getIdentifier)
* [getModulesFromHook](#method-getModulesFromHook)
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
* [newOrder](#method-newOrder)
* [orderConfirmation](#method-orderConfirmation)
* [paymentReturn](#method-paymentReturn)
* [postUpdateOrderStatus](#method-postUpdateOrderStatus)
* [preloadHookAlias](#method-preloadHookAlias)
* [preloadModulesFromHooks](#method-preloadModulesFromHooks)
* [productFooter](#method-productFooter)
* [productOutOfStock](#method-productOutOfStock)
* [save](#method-save)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateCarrier](#method-updateCarrier)
* [updateOrderStatus](#method-updateOrderStatus)
* [updateProduct](#method-updateProduct)
* [updateProductAttribute](#method-updateProductAttribute)
* [updateQuantity](#method-updateQuantity)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_hookModulesCache"></a>$_hookModulesCache

```php
protected mixed $_hookModulesCache
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Hook.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L41).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('name')
```





* Visibility: **protected**
* Source: [classes/Hook.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L34).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('name' => 32)
```





* Visibility: **protected**
* Source: [classes/Hook.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L35).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('name' => 'isHookName')
```





* Visibility: **protected**
* Source: [classes/Hook.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L36).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_hook'
```





* Visibility: **protected**
* Source: [classes/Hook.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L39).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Hook.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L31).


### <a name="property-$preloadHookAlias"></a>$preloadHookAlias

```php
public mixed $preloadHookAlias = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L44).


### <a name="property-$preloadModulesFromHooks"></a>$preloadModulesFromHooks

```php
public mixed $preloadModulesFromHooks = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L43).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'hook'
```





* Visibility: **protected**
* Source: [classes/Hook.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L38).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* Source: [classes/Hook.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L32).


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


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L62).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L65).


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


### <a name="method-PDFInvoice"></a>PDFInvoice

```php
mixed HookCore::PDFInvoice($pdf, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L411)


#### Arguments
* $pdf **mixed**
* $id_order **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L115)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **mixed**



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



### <a name="method-addProduct"></a>addProduct

```php
mixed HookCore::addProduct($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L343)


#### Arguments
* $product **mixed**



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



### <a name="method-backBeforePayment"></a>backBeforePayment

```php
mixed HookCore::backBeforePayment($module)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L418)


#### Arguments
* $module **mixed**



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
mixed ObjectModelCore::delete()
```

Delete current object from database

return boolean Deletion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L349)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L898)




### <a name="method-deleteProduct"></a>deleteProduct

```php
mixed HookCore::deleteProduct($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L355)


#### Arguments
* $product **mixed**



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



### <a name="method-exec"></a>exec

```php
string HookCore::exec(string $hook_name, array $hookArgs, $id_module)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L170)


#### Arguments
* $hook_name **string** - Hook Name
* $hookArgs **array** - Parameters for the functions
* $id_module **mixed**



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



### <a name="method-get"></a>get

```php
integer HookCore::get(string $hookName)
```

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L62)


#### Arguments
* $hookName **string** - Hook name



### <a name="method-getFields"></a>getFields

```php
mixed HookCore::getFields()
```





* Visibility: **public**
* Source: [classes/Hook.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L46)




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




### <a name="method-getHooks"></a>getHooks

```php
mixed HookCore::getHooks($position)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L99)


#### Arguments
* $position **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer HookCore::getIdByName(string $hook_name)
```

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L82)


#### Arguments
* $hook_name **string** - Hook name



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getModulesFromHook"></a>getModulesFromHook

```php
mixed HookCore::getModulesFromHook($hookID, $moduleID)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L149)


#### Arguments
* $hookID **mixed**
* $moduleID **mixed**



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



### <a name="method-newOrder"></a>newOrder

```php
mixed HookCore::newOrder($cart, $order, $customer, $currency, $orderStatus)
```

Called when quantity of a product is updated.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L314)


#### Arguments
* $cart **mixed**
* $order **mixed**
* $customer **mixed**
* $currency **mixed**
* $orderStatus **mixed**



### <a name="method-orderConfirmation"></a>orderConfirmation

```php
mixed HookCore::orderConfirmation($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L367)


#### Arguments
* $id_order **mixed**



### <a name="method-paymentReturn"></a>paymentReturn

```php
mixed HookCore::paymentReturn($id_order, $id_module)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L389)


#### Arguments
* $id_order **mixed**
* $id_module **mixed**



### <a name="method-postUpdateOrderStatus"></a>postUpdateOrderStatus

```php
mixed HookCore::postUpdateOrderStatus($newOrderStatusId, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L300)


#### Arguments
* $newOrderStatusId **mixed**
* $id_order **mixed**



### <a name="method-preloadHookAlias"></a>preloadHookAlias

```php
mixed HookCore::preloadHookAlias()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L107)




### <a name="method-preloadModulesFromHooks"></a>preloadModulesFromHooks

```php
mixed HookCore::preloadModulesFromHooks()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L116)




### <a name="method-productFooter"></a>productFooter

```php
mixed HookCore::productFooter($product, $category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L331)


#### Arguments
* $product **mixed**
* $category **mixed**



### <a name="method-productOutOfStock"></a>productOutOfStock

```php
mixed HookCore::productOutOfStock($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L337)


#### Arguments
* $product **mixed**



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
boolean ObjectModelCore::update($nullValues)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L274)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateCarrier"></a>updateCarrier

```php
mixed HookCore::updateCarrier($id_carrier, $carrier)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L426)


#### Arguments
* $id_carrier **mixed**
* $carrier **mixed**



### <a name="method-updateOrderStatus"></a>updateOrderStatus

```php
mixed HookCore::updateOrderStatus($newOrderStatusId, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L290)


#### Arguments
* $newOrderStatusId **mixed**
* $id_order **mixed**



### <a name="method-updateProduct"></a>updateProduct

```php
mixed HookCore::updateProduct($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L349)


#### Arguments
* $product **mixed**



### <a name="method-updateProductAttribute"></a>updateProductAttribute

```php
mixed HookCore::updateProductAttribute($id_product_attribute)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L361)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed HookCore::updateQuantity($product, $order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Hook.php#L325)


#### Arguments
* $product **mixed**
* $order **mixed**



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


