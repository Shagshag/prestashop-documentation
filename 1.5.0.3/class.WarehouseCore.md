Class WarehouseCore
=====================

Holds Stock



* Class name: WarehouseCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/Warehouse.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L33)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$id](#property-$id)
* [$id_address](#property-$id_address)
* [$id_currency](#property-$id_currency)
* [$id_employee](#property-$id_employee)
* [$management_type](#property-$management_type)
* [$name](#property-$name)
* [$reference](#property-$reference)
* [$webserviceParameters](#property-$webserviceParameters)
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
* [$image_format](#property-$image_format)
* [$table](#property-$table)
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
* [exists](#method-exists)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getCarriers](#method-getCarriers)
* [getDefinition](#method-getDefinition)
* [getEntity](#method-getEntity)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getNumberOfProducts](#method-getNumberOfProducts)
* [getProductLocation](#method-getProductLocation)
* [getProductWarehouseList](#method-getProductWarehouseList)
* [getQuantitiesOfProducts](#method-getQuantitiesOfProducts)
* [getShops](#method-getShops)
* [getStockValue](#method-getStockValue)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWarehouseNameById](#method-getWarehouseNameById)
* [getWarehouses](#method-getWarehouses)
* [getWarehousesByEmployee](#method-getWarehousesByEmployee)
* [getWarehousesByProductId](#method-getWarehousesByProductId)
* [getWarehousesGroupedByShops](#method-getWarehousesGroupedByShops)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsCarriers](#method-getWsCarriers)
* [getWsShops](#method-getWsShops)
* [getWsStockValue](#method-getWsStockValue)
* [getWsStocks](#method-getWsStocks)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isEmpty](#method-isEmpty)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [removeCarrier](#method-removeCarrier)
* [resetProductsLocations](#method-resetProductsLocations)
* [save](#method-save)
* [setCarriers](#method-setCarriers)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setProductLocation](#method-setProductLocation)
* [setShops](#method-setShops)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'warehouse', 'primary' => 'id_warehouse', 'fields' => array('id_address' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 45), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'management_type' => array('type' => self::TYPE_STRING, 'validate' => 'isStockManagement', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'deleted' => array('type' => self::TYPE_BOOL)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/Warehouse.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L65).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L54).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L36).


### <a name="property-$id_address"></a>$id_address

```php
public integer $id_address
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L39).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L51).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L48).


### <a name="property-$management_type"></a>$management_type

```php
public \enum $management_type
```

Describes the way a Warehouse is managed



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L60).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L45).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L42).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_address' => array('xlink_resource' => 'addresses'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_currency' => array('xlink_resource' => 'currencies'), 'valuation' => array('getter' => 'getWsStockValue', 'setter' => false), 'deleted' => array()), 'associations' => array('stocks' => array('resource' => 'stock', 'fields' => array('id' => array())), 'carriers' => array('resource' => 'carrier', 'fields' => array('id' => array())), 'shops' => array('resource' => 'shop', 'fields' => array('id' => array(), 'name' => array()))))
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L82).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L97).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L150)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
boolean ObjectModelCore::add(boolean $autodate, boolean $null_values)
```

Add current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L372)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L961)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1009)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L975)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 517](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L517)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1079)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L553)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L740)


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
* Source: [classes/ObjectModel.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1049)


#### Arguments
* $id **mixed**



### <a name="method-exists"></a>exists

```php
boolean WarehouseCore::exists(integer $id_warehouse)
```

Checks if the given warehouse exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L231)


#### Arguments
* $id_warehouse **integer**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1113)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L272)


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
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getCarriers"></a>getCarriers

```php
array WarehouseCore::getCarriers()
```

Gets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L156)




### <a name="method-getDefinition"></a>getDefinition

```php
mixed ObjectModelCore::getDefinition($class, $field)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1209)


#### Arguments
* $class **mixed**
* $field **mixed**



### <a name="method-getEntity"></a>getEntity

```php
mixed ObjectModelCore::getEntity($entity)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1269)


#### Arguments
* $entity **mixed**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L953)


#### Arguments
* $all **mixed**



### <a name="method-getNumberOfProducts"></a>getNumberOfProducts

```php
integer WarehouseCore::getNumberOfProducts()
```

Gets the number of products in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L374)




### <a name="method-getProductLocation"></a>getProductLocation

```php
string WarehouseCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)
```

For a given {product, product attribute} gets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L286)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**



### <a name="method-getProductWarehouseList"></a>getProductWarehouseList

```php
array WarehouseCore::getProductWarehouseList(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given {product, product attribute} gets warehouse list



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L306)


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
* Source: [classes/stock/Warehouse.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L394)




### <a name="method-getShops"></a>getShops

```php
array WarehouseCore::getShops()
```

Gets the shops (id and name) associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L118)




### <a name="method-getStockValue"></a>getStockValue

```php
integer WarehouseCore::getStockValue()
```

Gets the value of the stock in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L411)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fieldsArray)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L589)


#### Arguments
* $fieldsArray **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L130)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWarehouseNameById"></a>getWarehouseNameById

```php
string WarehouseCore::getWarehouseNameById(integer $id_warehouse)
```

For a given $id_warehouse, returns its name



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 467](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L467)


#### Arguments
* $id_warehouse **integer**



### <a name="method-getWarehouses"></a>getWarehouses

```php
array WarehouseCore::getWarehouses(boolean $ignore_shop, integer $id_shop)
```

Gets available warehouses
It is possible via ignore_shop and id_shop to filter the list with shop id



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 332](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L332)


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
* Source: [classes/stock/Warehouse.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L427)


#### Arguments
* $id_employee **integer**



### <a name="method-getWarehousesByProductId"></a>getWarehousesByProductId

```php
array WarehouseCore::getWarehousesByProductId(integer $id_product, integer $id_product_attribute)
```

For a given product, returns the warehouses it is stored in



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L444)


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
* Source: [classes/stock/Warehouse.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L354)




### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L929)


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
* Source: [classes/ObjectModel.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L799)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-getWsCarriers"></a>getWsCarriers

```php
array WarehouseCore::getWsCarriers()
```

Webservice : gets the ids carriers associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L519)




### <a name="method-getWsShops"></a>getWsShops

```php
array WarehouseCore::getWsShops()
```

Webservice : gets the ids shops associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 503](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L503)




### <a name="method-getWsStockValue"></a>getWsStockValue

```php
integer WarehouseCore::getWsStockValue()
```

Webservice : gets the value of the warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L480)




### <a name="method-getWsStocks"></a>getWsStocks

```php
array WarehouseCore::getWsStocks()
```

Webservice : gets the ids stock associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 489](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L489)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1148)


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
* Source: [classes/ObjectModel.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1167)


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
* Source: [classes/ObjectModel.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1035)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L990)


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
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1131)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isEmpty"></a>isEmpty

```php
boolean WarehouseCore::isEmpty()
```

Checks if a warehouse is empty - i.e. holds no stock



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L216)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1069)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L605)


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
* Source: [classes/stock/Warehouse.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L203)


#### Arguments
* $id_carrier **integer**
* $id_warehouse **integer** - optional



### <a name="method-resetProductsLocations"></a>resetProductsLocations

```php
mixed WarehouseCore::resetProductsLocations()
```

Reset all product locations for this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L271)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setCarriers"></a>setCarriers

```php
mixed WarehouseCore::setCarriers(array $ids_carriers)
```

Sets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L179)


#### Arguments
* $ids_carriers **array**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1224)




### <a name="method-setProductLocation"></a>setProductLocation

```php
boolean WarehouseCore::setProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse, string $location)
```

For a given {product, product attribute} sets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L250)


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
* Source: [classes/stock/Warehouse.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/stock/Warehouse.php#L135)


#### Arguments
* $ids_shop **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L569)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L444)


#### Arguments
* $null_values **boolean**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L753)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L759)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L704)


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
* Source: [classes/ObjectModel.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L643)


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
* Source: [classes/ObjectModel.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L669)


#### Arguments
* $die **boolean**
* $error_return **boolean**


