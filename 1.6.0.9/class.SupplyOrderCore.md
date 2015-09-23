Class SupplyOrderCore
=====================





* Class name: SupplyOrderCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/SupplyOrder.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L30)


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

### Methods

* [add](#method-add)
* [addHistory](#method-addHistory)
* [calculatePrices](#method-calculatePrices)
* [exists](#method-exists)
* [getAllExpectedQuantity](#method-getAllExpectedQuantity)
* [getAllPendingQuantity](#method-getAllPendingQuantity)
* [getAllReceivedQuantity](#method-getAllReceivedQuantity)
* [getEntries](#method-getEntries)
* [getEntriesCollection](#method-getEntriesCollection)
* [getReferenceById](#method-getReferenceById)
* [getSupplyOrderByReference](#method-getSupplyOrderByReference)
* [getWsSupplyOrderDetails](#method-getWsSupplyOrderDetails)
* [hasEntries](#method-hasEntries)
* [hydrate](#method-hydrate)
* [isDeliveryNoteAvailable](#method-isDeliveryNoteAvailable)
* [isEditable](#method-isEditable)
* [isInReceiptState](#method-isInReceiptState)
* [resetProducts](#method-resetProducts)
* [supplierHasPendingOrders](#method-supplierHasPendingOrders)
* [update](#method-update)
* [warehouseHasPendingOrders](#method-warehouseHasPendingOrders)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L75).


### <a name="property-$date_delivery_expected"></a>$date_delivery_expected

```php
public string $date_delivery_expected
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L85).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L80).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supply_order', 'primary' => 'id_supply_order', 'fields' => array('id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'supplier_name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_ref_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'date_delivery_expected' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'total_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_with_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_ti' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_tax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'discount_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => false), 'discount_value_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'is_template' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/SupplyOrder.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L125).


### <a name="property-$discount_rate"></a>$discount_rate

```php
public float $discount_rate
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L110).


### <a name="property-$discount_value_te"></a>$discount_value_te

```php
public float $discount_value_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L115).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L60).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L45).


### <a name="property-$id_ref_currency"></a>$id_ref_currency

```php
public integer $id_ref_currency
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L65).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L35).


### <a name="property-$id_supply_order_state"></a>$id_supply_order_state

```php
public integer $id_supply_order_state
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L55).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L50).


### <a name="property-$is_template"></a>$is_template

```php
public integer $is_template
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L120).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L70).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L40).


### <a name="property-$total_tax"></a>$total_tax

```php
public float $total_tax
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L105).


### <a name="property-$total_te"></a>$total_te

```php
public float $total_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L90).


### <a name="property-$total_ti"></a>$total_ti

```php
public float $total_ti
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L100).


### <a name="property-$total_with_discount_te"></a>$total_with_discount_te

```php
public float $total_with_discount_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L95).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_supplier' => array('xlink_resource' => 'suppliers'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states'), 'id_currency' => array('xlink_resource' => 'currencies')), 'hidden_fields' => array('id_ref_currency'), 'associations' => array('supply_order_details' => array('resource' => 'supply_order_details', 'fields' => array('id' => array(), 'id_product' => array(), 'id_product_attribute' => array(), 'supplier_reference' => array(), 'product_name' => array()))))
```





* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L153).


Methods
-------


### <a name="method-add"></a>add

```php
mixed SupplyOrderCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L196)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addHistory"></a>addHistory

```php
mixed SupplyOrderCore::addHistory()
```

Historizes the order : its id, its state, and the employee responsible for the current action



* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L355)




### <a name="method-calculatePrices"></a>calculatePrices

```php
mixed SupplyOrderCore::calculatePrices()
```

Checks all products in this order and calculate prices
Applies the global discount if necessary



* Visibility: **protected**
* Source: [classes/stock/SupplyOrder.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L212)




### <a name="method-exists"></a>exists

```php
integer SupplyOrderCore::exists(integer|string $match)
```

For a given id or reference, tells if the supply order exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L429)


#### Arguments
* $match **integer|string** - Either the reference of the order, or the Id of the order



### <a name="method-getAllExpectedQuantity"></a>getAllExpectedQuantity

```php
mixed SupplyOrderCore::getAllExpectedQuantity()
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L509)




### <a name="method-getAllPendingQuantity"></a>getAllPendingQuantity

```php
mixed SupplyOrderCore::getAllPendingQuantity()
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L527)




### <a name="method-getAllReceivedQuantity"></a>getAllReceivedQuantity

```php
mixed SupplyOrderCore::getAllReceivedQuantity()
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L518)




### <a name="method-getEntries"></a>getEntries

```php
array SupplyOrderCore::getEntries(integer $id_lang)
```

Retrieves the product entries for the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L250)


#### Arguments
* $id_lang **integer** - Optional Id Lang - Uses Context::language::id by default



### <a name="method-getEntriesCollection"></a>getEntriesCollection

```php
\PrestaShopCollection SupplyOrderCore::getEntriesCollection()
```

Retrieves the details entries (i.e. products) collection for the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L284)




### <a name="method-getReferenceById"></a>getReferenceById

```php
boolean|string SupplyOrderCore::getReferenceById(integer $id_supply_order)
```

Gets the reference of a given order



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L495)


#### Arguments
* $id_supply_order **integer**



### <a name="method-getSupplyOrderByReference"></a>getSupplyOrderByReference

```php
boolean|\SupplyOrder SupplyOrderCore::getSupplyOrderByReference(string $reference)
```

For a given reference, returns the corresponding supply order



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L449)


#### Arguments
* $reference **string** - Reference of the order



### <a name="method-getWsSupplyOrderDetails"></a>getWsSupplyOrderDetails

```php
array SupplyOrderCore::getWsSupplyOrderDetails()
```

Webservice : gets the ids supply_order_detail associated to this order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 547](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L547)




### <a name="method-hasEntries"></a>hasEntries

```php
boolean SupplyOrderCore::hasEntries()
```

Check if the order has entries



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L297)




### <a name="method-hydrate"></a>hydrate

```php
mixed SupplyOrderCore::hydrate(array $data, $id_lang)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L470)


#### Arguments
* $data **array**
* $id_lang **mixed**



### <a name="method-isDeliveryNoteAvailable"></a>isDeliveryNoteAvailable

```php
boolean SupplyOrderCore::isDeliveryNoteAvailable()
```

Checks if the current state allows to generate a delivery note for this order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L327)




### <a name="method-isEditable"></a>isEditable

```php
boolean SupplyOrderCore::isEditable()
```

Check if the current state allows to edit the current order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L312)




### <a name="method-isInReceiptState"></a>isInReceiptState

```php
boolean SupplyOrderCore::isInReceiptState()
```

Checks if the current state allows to add products in stock



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L342)




### <a name="method-resetProducts"></a>resetProducts

```php
mixed SupplyOrderCore::resetProducts()
```

Removes all products from the order



* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L371)




### <a name="method-supplierHasPendingOrders"></a>supplierHasPendingOrders

```php
boolean SupplyOrderCore::supplierHasPendingOrders(integer $id_supplier)
```

For a given $id_supplier, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L407)


#### Arguments
* $id_supplier **integer** - Id Supplier



### <a name="method-update"></a>update

```php
mixed SupplyOrderCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrder.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L181)


#### Arguments
* $null_values **mixed**



### <a name="method-warehouseHasPendingOrders"></a>warehouseHasPendingOrders

```php
boolean SupplyOrderCore::warehouseHasPendingOrders(integer $id_warehouse)
```

For a given $id_warehouse, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrder.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/SupplyOrder.php#L385)


#### Arguments
* $id_warehouse **integer**


