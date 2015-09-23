Class SupplyOrderCore
=====================





* Class name: SupplyOrderCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/SupplyOrder.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L31)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$date_delivery_expected](#property-$date_delivery_expected)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$discount_rate](#property-$discount_rate)
* [$discount_value_te](#property-$discount_value_te)
* [$id_currency](#property-$id_currency)
* [$id_lang](#property-$id_lang)
* [$id_ref_currency](#property-$id_ref_currency)
* [$id_supplier](#property-$id_supplier)
* [$id_supply_order_state](#property-$id_supply_order_state)
* [$id_warehouse](#property-$id_warehouse)
* [$is_template](#property-$is_template)
* [$reference](#property-$reference)
* [$supplier_name](#property-$supplier_name)
* [$total_tax](#property-$total_tax)
* [$total_te](#property-$total_te)
* [$total_ti](#property-$total_ti)
* [$total_with_discount_te](#property-$total_with_discount_te)
* [$webserviceParameters](#property-$webserviceParameters)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
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
* [addHistory](#method-addHistory)
* [associateTo](#method-associateTo)
* [calculatePrices](#method-calculatePrices)
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
* [getDefinition](#method-getDefinition)
* [getEntries](#method-getEntries)
* [getEntriesCollection](#method-getEntriesCollection)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getReferenceById](#method-getReferenceById)
* [getSupplyOrderByReference](#method-getSupplyOrderByReference)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsSupplyOrderDetails](#method-getWsSupplyOrderDetails)
* [hasEntries](#method-hasEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isDeliveryNoteAvailable](#method-isDeliveryNoteAvailable)
* [isEditable](#method-isEditable)
* [isInReceiptState](#method-isInReceiptState)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [resetProducts](#method-resetProducts)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [supplierHasPendingOrders](#method-supplierHasPendingOrders)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [warehouseHasPendingOrders](#method-warehouseHasPendingOrders)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L76).


### <a name="property-$date_delivery_expected"></a>$date_delivery_expected

```php
public string $date_delivery_expected
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L86).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L81).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supply_order', 'primary' => 'id_supply_order', 'fields' => array('id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'supplier_name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_ref_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'date_delivery_expected' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'total_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_with_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_ti' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_tax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'discount_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => false), 'discount_value_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'is_template' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/SupplyOrder.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L126).


### <a name="property-$discount_rate"></a>$discount_rate

```php
public float $discount_rate
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L111).


### <a name="property-$discount_value_te"></a>$discount_value_te

```php
public float $discount_value_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L116).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L61).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L46).


### <a name="property-$id_ref_currency"></a>$id_ref_currency

```php
public integer $id_ref_currency
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L66).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L36).


### <a name="property-$id_supply_order_state"></a>$id_supply_order_state

```php
public integer $id_supply_order_state
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L56).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L51).


### <a name="property-$is_template"></a>$is_template

```php
public integer $is_template
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L121).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L71).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L41).


### <a name="property-$total_tax"></a>$total_tax

```php
public float $total_tax
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L106).


### <a name="property-$total_te"></a>$total_te

```php
public float $total_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L91).


### <a name="property-$total_ti"></a>$total_ti

```php
public float $total_ti
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L101).


### <a name="property-$total_with_discount_te"></a>$total_with_discount_te

```php
public float $total_with_discount_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L96).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_supplier' => array('xlink_resource' => 'suppliers'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states'), 'id_currency' => array('xlink_resource' => 'currencies')), 'hidden_fields' => array('id_ref_currency'), 'associations' => array('supply_order_details' => array('resource' => 'supply_order_detail', 'fields' => array('id' => array(), 'id_product' => array(), 'id_product_attribute' => array(), 'supplier_reference' => array(), 'product_name' => array()))))
```





* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L154).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L48).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L150)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed SupplyOrderCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L197)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L925)


#### Arguments
* $fields **mixed**



### <a name="method-addHistory"></a>addHistory

```php
mixed SupplyOrderCore::addHistory()
```

Historizes the order : its id, its state, and the employee responsible for the current action



* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L358)




### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L973)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-calculatePrices"></a>calculatePrices

```php
mixed SupplyOrderCore::calculatePrices()
```

Checks all products in this order and calculate prices
Applies the global discount if necessary



* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L213)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L939)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L521)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1047](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1047)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L559)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L757)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1017)


#### Arguments
* $id **mixed**



### <a name="method-exists"></a>exists

```php
integer SupplyOrderCore::exists(integer|string $match)
```

For a given id or reference, tells if the supply order exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L432)


#### Arguments
* $match **integer|string** - Either the reference of the order, or the Id of the order



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1081)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L272)


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
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1184)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getEntries"></a>getEntries

```php
array SupplyOrderCore::getEntries(integer $id_lang)
```

Retrieves the product entries for the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L251)


#### Arguments
* $id_lang **integer** - Optional Id Lang - Uses Context::language::id by default



### <a name="method-getEntriesCollection"></a>getEntriesCollection

```php
\Collection SupplyOrderCore::getEntriesCollection()
```

Retrieves the details entries (i.e. products) collection for the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L287)




### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1261)


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
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L917)


#### Arguments
* $all **mixed**



### <a name="method-getReferenceById"></a>getReferenceById

```php
boolean|string SupplyOrderCore::getReferenceById(integer $id_supply_order)
```

Gets the reference of a given order



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 497](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L497)


#### Arguments
* $id_supply_order **integer**



### <a name="method-getSupplyOrderByReference"></a>getSupplyOrderByReference

```php
boolean|\SupplyOrder SupplyOrderCore::getSupplyOrderByReference(string $reference)
```

For a given reference, returns the corresponding supply order



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L452)


#### Arguments
* $reference **string** - Reference of the order



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L595)


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
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L130)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L890)


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
* Source: [classes/ObjectModel.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L816)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWsSupplyOrderDetails"></a>getWsSupplyOrderDetails

```php
array SupplyOrderCore::getWsSupplyOrderDetails()
```

Webservice : gets the ids supply_order_detail associated to this order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L522)




### <a name="method-hasEntries"></a>hasEntries

```php
boolean SupplyOrderCore::hasEntries()
```

Check if the order has entries



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L300)




### <a name="method-hydrate"></a>hydrate

```php
mixed SupplyOrderCore::hydrate(array $data, $id_lang)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L472)


#### Arguments
* $data **array**
* $id_lang **mixed**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1135)


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
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1003)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L954)


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
* Source: [classes/ObjectModel.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1099)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isDeliveryNoteAvailable"></a>isDeliveryNoteAvailable

```php
boolean SupplyOrderCore::isDeliveryNoteAvailable()
```

Checks if the current state allows to generate a delivery note for this order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L330)




### <a name="method-isEditable"></a>isEditable

```php
boolean SupplyOrderCore::isEditable()
```

Check if the current state allows to edit the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L315)




### <a name="method-isInReceiptState"></a>isInReceiptState

```php
boolean SupplyOrderCore::isInReceiptState()
```

Checks if the current state allows to add products in stock



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L345)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1037)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L611)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-resetProducts"></a>resetProducts

```php
mixed SupplyOrderCore::resetProducts()
```

Removes all products from the order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L374)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L360)


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
* Source: [classes/ObjectModel.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1207)




### <a name="method-supplierHasPendingOrders"></a>supplierHasPendingOrders

```php
boolean SupplyOrderCore::supplierHasPendingOrders(integer $id_supplier)
```

For a given $id_supplier, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L410)


#### Arguments
* $id_supplier **integer** - Id Supplier



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L575)




### <a name="method-update"></a>update

```php
mixed SupplyOrderCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L182)


#### Arguments
* $null_values **mixed**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L772)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L778)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L710)


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
* Source: [classes/ObjectModel.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L649)


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
* Source: [classes/ObjectModel.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L675)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-warehouseHasPendingOrders"></a>warehouseHasPendingOrders

```php
boolean SupplyOrderCore::warehouseHasPendingOrders(integer $id_warehouse)
```

For a given $id_warehouse, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 388](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/stock/SupplyOrder.php#L388)


#### Arguments
* $id_warehouse **integer**


