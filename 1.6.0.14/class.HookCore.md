Class HookCore
=====================





* Class name: HookCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Hook.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L27)


Contents
--------


### Properties

* [$_hook_modules_cache](#property-$_hook_modules_cache)
* [$_hook_modules_cache_exec](#property-$_hook_modules_cache_exec)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$executed_hooks](#property-$executed_hooks)
* [$live_edit](#property-$live_edit)
* [$name](#property-$name)
* [$native_module](#property-$native_module)
* [$position](#property-$position)
* [$title](#property-$title)
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
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$loaded_classes](#property-$loaded_classes)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [PDFInvoice](#method-PDFInvoice)
* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addProduct](#method-addProduct)
* [associateTo](#method-associateTo)
* [backBeforePayment](#method-backBeforePayment)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteProduct](#method-deleteProduct)
* [deleteSelection](#method-deleteSelection)
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [enableCache](#method-enableCache)
* [exec](#method-exec)
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
* [getHookAliasList](#method-getHookAliasList)
* [getHookModuleExecList](#method-getHookModuleExecList)
* [getHookModuleList](#method-getHookModuleList)
* [getHooks](#method-getHooks)
* [getIdByName](#method-getIdByName)
* [getLiveEditById](#method-getLiveEditById)
* [getModulesFromHook](#method-getModulesFromHook)
* [getNameById](#method-getNameById)
* [getRetroHookName](#method-getRetroHookName)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [newOrder](#method-newOrder)
* [orderConfirmation](#method-orderConfirmation)
* [paymentReturn](#method-paymentReturn)
* [postUpdateOrderStatus](#method-postUpdateOrderStatus)
* [preloadHookModulesCache](#method-preloadHookModulesCache)
* [productFooter](#method-productFooter)
* [productOutOfStock](#method-productOutOfStock)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateCarrier](#method-updateCarrier)
* [updateMultishopTable](#method-updateMultishopTable)
* [updateOrderStatus](#method-updateOrderStatus)
* [updateProduct](#method-updateProduct)
* [updateProductAttribute](#method-updateProductAttribute)
* [updateQuantity](#method-updateQuantity)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)
* [wrapLiveEdit](#method-wrapLiveEdit)




Properties
----------


### <a name="property-$_hook_modules_cache"></a>$_hook_modules_cache

```php
protected mixed $_hook_modules_cache = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Hook.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L79).


### <a name="property-$_hook_modules_cache_exec"></a>$_hook_modules_cache_exec

```php
protected mixed $_hook_modules_cache_exec = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Hook.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L84).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'hook', 'primary' => 'id_hook', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isHookName', 'required' => true, 'size' => 64), 'title' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'description' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml'), 'position' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'live_edit' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L64).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Hook.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L42).


### <a name="property-$executed_hooks"></a>$executed_hooks

```php
public array $executed_hooks = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L57).


### <a name="property-$live_edit"></a>$live_edit

```php
public boolean $live_edit = false
```





* Visibility: **public**
* Source: [classes/Hook.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L52).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Hook.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L32).


### <a name="property-$native_module"></a>$native_module

```php
public mixed $native_module
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L59).


### <a name="property-$position"></a>$position

```php
public boolean $position = false
```





* Visibility: **public**
* Source: [classes/Hook.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L47).


### <a name="property-$title"></a>$title

```php
public string $title
```





* Visibility: **public**
* Source: [classes/Hook.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L37).


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L153).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L143).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L133).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L106).


### <a name="property-$force_id"></a>$force_id

```php
public \boolean, $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L148).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L64).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L55).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L60).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L117).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L120).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected mixed $loaded_classes = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L128).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L138).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L114).


Methods
-------


### <a name="method-PDFInvoice"></a>PDFInvoice

```php
mixed HookCore::PDFInvoice($pdf, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L636)


#### Arguments
* $pdf **mixed**
* $id_order **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L181)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed HookCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Hook.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L86)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1244)


#### Arguments
* $fields **mixed**



### <a name="method-addProduct"></a>addProduct

```php
mixed HookCore::addProduct($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 751](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L751)


#### Arguments
* $product **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1302](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1302)


#### Arguments
* $id_shops **integer|array**



### <a name="method-backBeforePayment"></a>backBeforePayment

```php
mixed HookCore::backBeforePayment($module)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L647)


#### Arguments
* $module **mixed**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1231)


#### Arguments
* $all **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1258)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L723)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1433)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteProduct"></a>deleteProduct

```php
mixed HookCore::deleteProduct($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L769)


#### Arguments
* $product **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L769)


#### Arguments
* $selection **array**



### <a name="method-disableCache"></a>disableCache

```php
mixed ObjectModelCore::disableCache()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1719](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1719)




### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1014](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1014)


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
* Source: [classes/ObjectModel.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L549)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1346](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1346)


#### Arguments
* $id **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ObjectModelCore::enableCache()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1714](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1714)




### <a name="method-exec"></a>exec

```php
string HookCore::exec(string $hook_name, array $hook_args, integer $id_module, $array_return, $check_exceptions, $use_push, $id_shop)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L401)


#### Arguments
* $hook_name **string** - Hook Name
* $hook_args **array** - Parameters for the functions
* $id_module **integer** - Execute hook for this module only
* $array_return **mixed**
* $check_exceptions **mixed**
* $use_push **mixed**
* $id_shop **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1470)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L348)


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
* Source: [classes/ObjectModel.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L395)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**
* $purify **mixed**



### <a name="method-get"></a>get

```php
integer HookCore::get(string $hookName)
```

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L690)


#### Arguments
* $hookName **string** - Hook name



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1331](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1331)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1576)


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
* Source: [classes/ObjectModel.php line 1683](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1683)


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
* Source: [classes/ObjectModel.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L276)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L313)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1223)


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
* Source: [classes/ObjectModel.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L299)




### <a name="method-getHookAliasList"></a>getHookAliasList

```php
array HookCore::getHookAliasList()
```

Get list of hook alias



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L178)




### <a name="method-getHookModuleExecList"></a>getHookModuleExecList

```php
array HookCore::getHookModuleExecList(string $hook_name)
```

Get list of modules we can execute per hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L281)


#### Arguments
* $hook_name **string** - Get list of modules for this hook if given



### <a name="method-getHookModuleList"></a>getHookModuleList

```php
array HookCore::getHookModuleList()
```

Get list of all registered hooks with modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L218)




### <a name="method-getHooks"></a>getHooks

```php
array HookCore::getHooks(boolean $position)
```

Return Hooks List



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L98)


#### Arguments
* $position **boolean**



### <a name="method-getIdByName"></a>getIdByName

```php
integer HookCore::getIdByName(string $hook_name)
```

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L113)


#### Arguments
* $hook_name **string** - Hook name



### <a name="method-getLiveEditById"></a>getLiveEditById

```php
mixed HookCore::getLiveEditById($hook_id)
```

Return hook live edit bool from ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L160)


#### Arguments
* $hook_id **mixed**



### <a name="method-getModulesFromHook"></a>getModulesFromHook

```php
array HookCore::getModulesFromHook(integer $id_hook, integer $id_module)
```

Return Hooks List



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L264)


#### Arguments
* $id_hook **integer**
* $id_module **integer**



### <a name="method-getNameById"></a>getNameById

```php
mixed HookCore::getNameById($hook_id)
```

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L145)


#### Arguments
* $hook_id **mixed**



### <a name="method-getRetroHookName"></a>getRetroHookName

```php
integer HookCore::getRetroHookName(string $hook_name)
```

Return retrocompatible hook name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L200)


#### Arguments
* $hook_name **string** - Hook name



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 804](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L804)


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
* Source: [classes/ObjectModel.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L161)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1164)


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
* Source: [classes/ObjectModel.php line 1086](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1086)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1371)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1508](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1508)


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
* Source: [classes/ObjectModel.php line 1527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1527)


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
* Source: [classes/ObjectModel.php line 1273](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1273)


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
* Source: [classes/ObjectModel.php line 1488](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1488)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1388](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1388)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
mixed ObjectModelCore::isMultiShopField($field)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1383](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1383)


#### Arguments
* $field **mixed**



### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1378](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1378)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L820)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-newOrder"></a>newOrder

```php
mixed HookCore::newOrder($cart, $order, $customer, $currency, $orderStatus)
```

Called when quantity of a product is updated.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L710)


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
* Source: [classes/Hook.php line 584](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L584)


#### Arguments
* $id_order **mixed**



### <a name="method-paymentReturn"></a>paymentReturn

```php
mixed HookCore::paymentReturn($id_order, $id_module)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L610)


#### Arguments
* $id_order **mixed**
* $id_module **mixed**



### <a name="method-postUpdateOrderStatus"></a>postUpdateOrderStatus

```php
mixed HookCore::postUpdateOrderStatus($newOrderStatusId, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L572)


#### Arguments
* $newOrderStatusId **mixed**
* $id_order **mixed**



### <a name="method-preloadHookModulesCache"></a>preloadHookModulesCache

```php
boolean HookCore::preloadHookModulesCache()
```

Preload hook modules cache



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L671)




### <a name="method-productFooter"></a>productFooter

```php
mixed HookCore::productFooter($product, $category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L733)


#### Arguments
* $product **mixed**
* $category **mixed**



### <a name="method-productOutOfStock"></a>productOutOfStock

```php
mixed HookCore::productOutOfStock($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 742](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L742)


#### Arguments
* $product **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L446)


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
* Source: [classes/ObjectModel.php line 1614](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1614)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1709](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1709)


#### Arguments
* $fields **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L785)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L605)


#### Arguments
* $null_values **boolean**



### <a name="method-updateCarrier"></a>updateCarrier

```php
mixed HookCore::updateCarrier($id_carrier, $carrier)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L657)


#### Arguments
* $id_carrier **mixed**
* $carrier **mixed**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1403)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-updateOrderStatus"></a>updateOrderStatus

```php
mixed HookCore::updateOrderStatus($newOrderStatusId, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L558)


#### Arguments
* $newOrderStatusId **mixed**
* $id_order **mixed**



### <a name="method-updateProduct"></a>updateProduct

```php
mixed HookCore::updateProduct($product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 760](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L760)


#### Arguments
* $product **mixed**



### <a name="method-updateProductAttribute"></a>updateProductAttribute

```php
mixed HookCore::updateProductAttribute($id_product_attribute)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L778)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed HookCore::updateQuantity($product, $order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 724](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L724)


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
* Source: [classes/ObjectModel.php line 1032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1032)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1038](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1038)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang, $skip, $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 931](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L931)


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
* Source: [classes/ObjectModel.php line 858](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L858)


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
* Source: [classes/ObjectModel.php line 887](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L887)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/ObjectModel.php#L1200)


#### Arguments
* $htmlentities **mixed**



### <a name="method-wrapLiveEdit"></a>wrapLiveEdit

```php
mixed HookCore::wrapLiveEdit($display, $moduleInstance, $id_hook)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Hook.php#L539)


#### Arguments
* $display **mixed**
* $moduleInstance **mixed**
* $id_hook **mixed**


