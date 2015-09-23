Class WarehouseCore
=====================

Holds Stock



* Class name: WarehouseCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/Warehouse.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L33)


Contents
--------


### Properties

* [$deleted](#property-$deleted)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$id](#property-$id)
* [$id_address](#property-$id_address)
* [$id_currency](#property-$id_currency)
* [$id_employee](#property-$id_employee)
* [$identifier](#property-$identifier)
* [$management_type](#property-$management_type)
* [$name](#property-$name)
* [$reference](#property-$reference)
* [$table](#property-$table)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
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
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [exists](#method-exists)
* [existsInDatabase](#method-existsInDatabase)
* [getCarriers](#method-getCarriers)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getIdentifier](#method-getIdentifier)
* [getNumberOfProducts](#method-getNumberOfProducts)
* [getProductLocation](#method-getProductLocation)
* [getProductWarehouseList](#method-getProductWarehouseList)
* [getQuantitiesOfProducts](#method-getQuantitiesOfProducts)
* [getShops](#method-getShops)
* [getStockValue](#method-getStockValue)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWarehouses](#method-getWarehouses)
* [getWarehousesByEmployee](#method-getWarehousesByEmployee)
* [getWarehousesByProductId](#method-getWarehousesByProductId)
* [getWarehousesGroupedByShops](#method-getWarehousesGroupedByShops)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isEmpty](#method-isEmpty)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [removeCarrier](#method-removeCarrier)
* [save](#method-save)
* [setCarriers](#method-setCarriers)
* [setProductLocation](#method-setProductLocation)
* [setShops](#method-setShops)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L54).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('id_address', 'reference', 'name', 'id_employee', 'management_type', 'id_currency')
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L62).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('stock_management' => 32, 'reference' => 45, 'name' => 45)
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L71).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('id_address' => 'isUnsignedId', 'reference' => 'isString', 'name' => 'isName', 'id_employee' => 'isUnsignedId', 'management_type' => 'isStockManagement', 'id_currency' => 'isUnsignedId')
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L77).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L36).


### <a name="property-$id_address"></a>$id_address

```php
public integer $id_address
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L39).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L51).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L48).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_warehouse'
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L87).


### <a name="property-$management_type"></a>$management_type

```php
public \enum $management_type
```

Describes the way a Warehouse is managed



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L60).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L45).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L42).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'warehouse'
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L86).


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



### <a name="method-exists"></a>exists

```php
boolean WarehouseCore::exists(integer $id_warehouse)
```

Checks if the given warehouse exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L214)


#### Arguments
* $id_warehouse **integer**



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



### <a name="method-getCarriers"></a>getCarriers

```php
array WarehouseCore::getCarriers()
```

Gets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L143)




### <a name="method-getFields"></a>getFields

```php
mixed WarehouseCore::getFields()
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L89)




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




### <a name="method-getNumberOfProducts"></a>getNumberOfProducts

```php
integer WarehouseCore::getNumberOfProducts()
```

Gets the number of products in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L345)




### <a name="method-getProductLocation"></a>getProductLocation

```php
string WarehouseCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)
```

For a given {product, product attribute} gets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L259)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**



### <a name="method-getProductWarehouseList"></a>getProductWarehouseList

```php
string WarehouseCore::getProductWarehouseList(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given {product, product attribute} gets warehouse list



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L279)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_shop **integer**



### <a name="method-getQuantitiesOfProducts"></a>getQuantitiesOfProducts

```php
integer WarehouseCore::getQuantitiesOfProducts()
```

Gets the number of quantities - for all products - in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L365)




### <a name="method-getShops"></a>getShops

```php
array WarehouseCore::getShops()
```

Gets the shops (id and name) associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L108)




### <a name="method-getStockValue"></a>getStockValue

```php
integer WarehouseCore::getStockValue()
```

Gets the value of the stock in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L382)




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



### <a name="method-getWarehouses"></a>getWarehouses

```php
array WarehouseCore::getWarehouses(boolean $ignore_shop, integer $id_shop)
```

Gets available warehouses
It is possible via ignore_shop and id_shop to filter the list with shop id



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L303)


#### Arguments
* $ignore_shop **boolean** - false by default
* $id_shop **integer** - null by default



### <a name="method-getWarehousesByEmployee"></a>getWarehousesByEmployee

```php
array WarehouseCore::getWarehousesByEmployee(integer $id_employee)
```

For a given employee, gets the warehouse(s) he manages



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L398)


#### Arguments
* $id_employee **integer**



### <a name="method-getWarehousesByProductId"></a>getWarehousesByProductId

```php
array WarehouseCore::getWarehousesByProductId(integer $id_product, integer $id_product_attribute)
```

For a given product, returns the warehouses it is stored in



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L415)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**



### <a name="method-getWarehousesGroupedByShops"></a>getWarehousesGroupedByShops

```php
array WarehouseCore::getWarehousesGroupedByShops()
```

Gets ids of warehouses, grouped by ids of shops



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L325)




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



### <a name="method-isEmpty"></a>isEmpty

```php
boolean WarehouseCore::isEmpty()
```

Checks if a warehouse is empty - i.e. holds no stock



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L199)




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



### <a name="method-removeCarrier"></a>removeCarrier

```php
mixed WarehouseCore::removeCarrier(integer $id_carrier, integer $id_warehouse)
```

For a given carrier, removes it from the warehouse/carrier association
If $id_warehouse is set, it only removes the carrier for this warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L186)


#### Arguments
* $id_carrier **integer**
* $id_warehouse **integer** - optional



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



### <a name="method-setCarriers"></a>setCarriers

```php
mixed WarehouseCore::setCarriers(array $ids_carriers)
```

Sets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L166)


#### Arguments
* $ids_carriers **array**



### <a name="method-setProductLocation"></a>setProductLocation

```php
boolean WarehouseCore::setProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse, string $location)
```

For a given {product, product attribute} sets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L233)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**
* $location **string**



### <a name="method-setShops"></a>setShops

```php
mixed WarehouseCore::setShops(array $ids_shop)
```

Sets the shops associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/Warehouse.php#L125)


#### Arguments
* $ids_shop **array**



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


