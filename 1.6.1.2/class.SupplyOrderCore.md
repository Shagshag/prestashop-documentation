Class SupplyOrderCore
=====================





* Class name: SupplyOrderCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/SupplyOrder.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L30)


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
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$loaded_classes](#property-$loaded_classes)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addHistory](#method-addHistory)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [calculatePrices](#method-calculatePrices)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [enableCache](#method-enableCache)
* [exists](#method-exists)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAllExpectedQuantity](#method-getAllExpectedQuantity)
* [getAllPendingQuantity](#method-getAllPendingQuantity)
* [getAllReceivedQuantity](#method-getAllReceivedQuantity)
* [getAssociatedShops](#method-getAssociatedShops)
* [getDefinition](#method-getDefinition)
* [getEntries](#method-getEntries)
* [getEntriesCollection](#method-getEntriesCollection)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getReferenceById](#method-getReferenceById)
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getSupplyOrderByReference](#method-getSupplyOrderByReference)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsSupplyOrderDetails](#method-getWsSupplyOrderDetails)
* [hasEntries](#method-hasEntries)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isDeliveryNoteAvailable](#method-isDeliveryNoteAvailable)
* [isEditable](#method-isEditable)
* [isInReceiptState](#method-isInReceiptState)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [resetProducts](#method-resetProducts)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [supplierHasPendingOrders](#method-supplierHasPendingOrders)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)
* [warehouseHasPendingOrders](#method-warehouseHasPendingOrders)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L75).


### <a name="property-$date_delivery_expected"></a>$date_delivery_expected

```php
public string $date_delivery_expected
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L85).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L80).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supply_order', 'primary' => 'id_supply_order', 'fields' => array('id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'supplier_name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_ref_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'date_delivery_expected' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'total_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_with_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_ti' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_tax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'discount_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => false), 'discount_value_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'is_template' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/SupplyOrder.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L125).


### <a name="property-$discount_rate"></a>$discount_rate

```php
public float $discount_rate
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L110).


### <a name="property-$discount_value_te"></a>$discount_value_te

```php
public float $discount_value_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L115).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L60).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L45).


### <a name="property-$id_ref_currency"></a>$id_ref_currency

```php
public integer $id_ref_currency
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L65).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L35).


### <a name="property-$id_supply_order_state"></a>$id_supply_order_state

```php
public integer $id_supply_order_state
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L55).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L50).


### <a name="property-$is_template"></a>$is_template

```php
public integer $is_template
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L120).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L70).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L40).


### <a name="property-$total_tax"></a>$total_tax

```php
public float $total_tax
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L105).


### <a name="property-$total_te"></a>$total_te

```php
public float $total_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L90).


### <a name="property-$total_ti"></a>$total_ti

```php
public float $total_ti
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L100).


### <a name="property-$total_with_discount_te"></a>$total_with_discount_te

```php
public float $total_with_discount_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L95).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_supplier' => array('xlink_resource' => 'suppliers'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states'), 'id_currency' => array('xlink_resource' => 'currencies')), 'hidden_fields' => array('id_ref_currency'), 'associations' => array('supply_order_details' => array('resource' => 'supply_order_detail', 'fields' => array('id' => array(), 'id_product' => array(), 'id_product_attribute' => array(), 'supplier_reference' => array(), 'product_name' => array()))))
```





* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L153).


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L164).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L150).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected array $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L88).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected array $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L70).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L106).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L94).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L112).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected array $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L118).


### <a name="property-$force_id"></a>$force_id

```php
public boolean $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L159).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected boolean $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L67).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L55).


### <a name="property-$id_shop"></a>$id_shop

```php
protected integer $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L61).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public array $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L64).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L82).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L130).


### <a name="property-$image_format"></a>$image_format

```php
protected String $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L133).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected array $loaded_classes = array()
```

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L147).


### <a name="property-$table"></a>$table

```php
protected string $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L76).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L124).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L153).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer|null $id, integer|null $id_lang, integer|null $id_shop)
```

Builds the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L201)


#### Arguments
* $id **integer|null** - If specified, loads and existing object from DB (optional).
* $id_lang **integer|null** - Required if object is multilingual (optional).
* $id_shop **integer|null** - ID shop for objects with multishop tables.



### <a name="method-add"></a>add

```php
mixed SupplyOrderCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L197)


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
* Source: [classes/ObjectModel.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1390)


#### Arguments
* $fields **array**



### <a name="method-addHistory"></a>addHistory

```php
mixed SupplyOrderCore::addHistory()
```

Historizes the order : its id, its state, and the employee responsible for the current action



* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L361)




### <a name="method-associateTo"></a>associateTo

```php
boolean|void ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1464)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)
```

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1368)


#### Arguments
* $all **boolean** - If true, caches required fields of all object classes.



### <a name="method-calculatePrices"></a>calculatePrices

```php
mixed SupplyOrderCore::calculatePrices()
```

Checks all products in this order and calculate prices
Applies the global discount if necessary



* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L214)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache(boolean $all)
```

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1414)


#### Arguments
* $all **boolean** - If true, clears cache for all objects



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Deletes current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L743)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage(boolean $force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1643)


#### Arguments
* $force_delete **boolean**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $ids)
```

Deletes multiple objects from the database at once



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L790)


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
* Source: [classes/ObjectModel.php line 1969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1969)




### <a name="method-displayFieldName"></a>displayFieldName

```php
string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)
```

Returns field name translation



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1083)


#### Arguments
* $field **string** - Field name
* $class **string** - ObjectModel class name
* $htmlentities **boolean** - If true, applies htmlentities() to result string
* $context **[Context](class.ContextCore.md)|null** - Context object



### <a name="method-duplicateObject"></a>duplicateObject

```php
\ObjectModel|false ObjectModelCore::duplicateObject()
```

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L549)




### <a name="method-duplicateShops"></a>duplicateShops

```php
boolean|void ObjectModelCore::duplicateShops($id)
```

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1523)


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
* Source: [classes/ObjectModel.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1961)




### <a name="method-exists"></a>exists

```php
integer SupplyOrderCore::exists(integer|string $match)
```

For a given id or reference, tells if the supply order exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L438)


#### Arguments
* $match **integer|string** - Either the reference of the order, or the Id of the order



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1686)


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
* Source: [classes/ObjectModel.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L327)


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
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### <a name="method-getAllExpectedQuantity"></a>getAllExpectedQuantity

```php
mixed SupplyOrderCore::getAllExpectedQuantity()
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L522)




### <a name="method-getAllPendingQuantity"></a>getAllPendingQuantity

```php
mixed SupplyOrderCore::getAllPendingQuantity()
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L540)




### <a name="method-getAllReceivedQuantity"></a>getAllReceivedQuantity

```php
mixed SupplyOrderCore::getAllReceivedQuantity()
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 531](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L531)




### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1499)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string|null $field)
```

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1809)


#### Arguments
* $class **string** - Name of object
* $field **string|null** - Name of field if we want the definition of one field only



### <a name="method-getEntries"></a>getEntries

```php
array SupplyOrderCore::getEntries(integer $id_lang)
```

Retrieves the product entries for the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L255)


#### Arguments
* $id_lang **integer** - Optional Id Lang - Uses Context::language::id by default



### <a name="method-getEntriesCollection"></a>getEntriesCollection

```php
\PrestaShopCollection SupplyOrderCore::getEntriesCollection()
```

Retrieves the details entries (i.e. products) collection for the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L290)




### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)
```

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1927)


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
* Source: [classes/ObjectModel.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L244)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L288)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)
```

Returns an array of required fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1355)


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
* Source: [classes/ObjectModel.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L270)




### <a name="method-getReferenceById"></a>getReferenceById

```php
boolean|string SupplyOrderCore::getReferenceById(integer $id_supply_order)
```

Gets the reference of a given order



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L507)


#### Arguments
* $id_supply_order **integer**



### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

```php
mixed ObjectModelCore::getRepositoryClassName()
```

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L166)




### <a name="method-getSupplyOrderByReference"></a>getSupplyOrderByReference

```php
boolean|\SupplyOrder SupplyOrderCore::getSupplyOrderByReference(string $reference)
```

For a given reference, returns the corresponding supply order



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L459)


#### Arguments
* $reference **string** - Reference of the order



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array ObjectModelCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L831)


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
* Source: [classes/ObjectModel.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L178)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)
```

Returns webservice object list.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1279)


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
* Source: [classes/ObjectModel.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1176)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-getWsSupplyOrderDetails"></a>getWsSupplyOrderDetails

```php
array SupplyOrderCore::getWsSupplyOrderDetails()
```

Webservice : gets the ids supply_order_detail associated to this order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L560)




### <a name="method-hasEntries"></a>hasEntries

```php
boolean SupplyOrderCore::hasEntries()
```

Check if the order has entries



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L303)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1550)




### <a name="method-hydrate"></a>hydrate

```php
mixed SupplyOrderCore::hydrate(array $data, $id_lang)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 482](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L482)


#### Arguments
* $data **array**
* $id_lang **mixed**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1755)


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
* Source: [classes/ObjectModel.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1430)


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
* Source: [classes/ObjectModel.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1706)


#### Arguments
* $table **string|null** - Name of table linked to entity
* $has_active_column **boolean** - True if the table has an active column



### <a name="method-isDeliveryNoteAvailable"></a>isDeliveryNoteAvailable

```php
boolean SupplyOrderCore::isDeliveryNoteAvailable()
```

Checks if the current state allows to generate a delivery note for this order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L333)




### <a name="method-isEditable"></a>isEditable

```php
boolean SupplyOrderCore::isEditable()
```

Check if the current state allows to edit the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L318)




### <a name="method-isInReceiptState"></a>isInReceiptState

```php
boolean SupplyOrderCore::isInReceiptState()
```

Checks if the current state allows to add products in stock



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L348)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
boolean ObjectModelCore::isLangMultishop()
```

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1586)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
boolean ObjectModelCore::isMultiShopField(string $field)
```

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1576)


#### Arguments
* $field **string**



### <a name="method-isMultishop"></a>isMultishop

```php
boolean ObjectModelCore::isMultishop()
```

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1564)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L854)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-resetProducts"></a>resetProducts

```php
mixed SupplyOrderCore::resetProducts()
```

Removes all products from the order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L377)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $auto_date)
```

Saves current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L443)


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
* Source: [classes/ObjectModel.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1855)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1953](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1953)


#### Arguments
* $fields **array**



### <a name="method-supplierHasPendingOrders"></a>supplierHasPendingOrders

```php
boolean SupplyOrderCore::supplierHasPendingOrders(integer $id_supplier)
```

For a given $id_supplier, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L415)


#### Arguments
* $id_supplier **integer** - Id Supplier



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggles object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L807)




### <a name="method-update"></a>update

```php
mixed SupplyOrderCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L181)


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
* Source: [classes/ObjectModel.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1602)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-validateControler"></a>validateControler

```php
array ObjectModelCore::validateControler(boolean $htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1105)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

```php
array ObjectModelCore::validateController(boolean $htmlentities)
```

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1118)


#### Arguments
* $htmlentities **boolean** - If true, uses htmlentities() for field name translations in errors.



### <a name="method-validateField"></a>validateField

```php
true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L977)


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
* Source: [classes/ObjectModel.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L895)


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
* Source: [classes/ObjectModel.php line 927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L927)


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
* Source: [classes/ObjectModel.php line 1322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1322)


#### Arguments
* $htmlentities **boolean**



### <a name="method-warehouseHasPendingOrders"></a>warehouseHasPendingOrders

```php
boolean SupplyOrderCore::warehouseHasPendingOrders(integer $id_warehouse)
```

For a given $id_warehouse, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/SupplyOrder.php#L392)


#### Arguments
* $id_warehouse **integer**


