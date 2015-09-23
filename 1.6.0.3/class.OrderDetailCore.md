Class OrderDetailCore
=====================





* Class name: OrderDetailCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderDetail.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L27)


Contents
--------


### Properties

* [$context](#property-$context)
* [$customer](#property-$customer)
* [$definition](#property-$definition)
* [$discount_quantity_applied](#property-$discount_quantity_applied)
* [$download_deadline](#property-$download_deadline)
* [$download_hash](#property-$download_hash)
* [$download_nb](#property-$download_nb)
* [$ecotax](#property-$ecotax)
* [$ecotax_tax_rate](#property-$ecotax_tax_rate)
* [$group_reduction](#property-$group_reduction)
* [$id_order](#property-$id_order)
* [$id_order_detail](#property-$id_order_detail)
* [$id_order_invoice](#property-$id_order_invoice)
* [$id_shop](#property-$id_shop)
* [$id_warehouse](#property-$id_warehouse)
* [$original_product_price](#property-$original_product_price)
* [$outOfStock](#property-$outOfStock)
* [$product_attribute_id](#property-$product_attribute_id)
* [$product_ean13](#property-$product_ean13)
* [$product_id](#property-$product_id)
* [$product_name](#property-$product_name)
* [$product_price](#property-$product_price)
* [$product_quantity](#property-$product_quantity)
* [$product_quantity_discount](#property-$product_quantity_discount)
* [$product_quantity_in_stock](#property-$product_quantity_in_stock)
* [$product_quantity_refunded](#property-$product_quantity_refunded)
* [$product_quantity_reinjected](#property-$product_quantity_reinjected)
* [$product_quantity_return](#property-$product_quantity_return)
* [$product_reference](#property-$product_reference)
* [$product_supplier_reference](#property-$product_supplier_reference)
* [$product_upc](#property-$product_upc)
* [$product_weight](#property-$product_weight)
* [$purchase_supplier_price](#property-$purchase_supplier_price)
* [$reduction_amount](#property-$reduction_amount)
* [$reduction_amount_tax_excl](#property-$reduction_amount_tax_excl)
* [$reduction_amount_tax_incl](#property-$reduction_amount_tax_incl)
* [$reduction_percent](#property-$reduction_percent)
* [$specificPrice](#property-$specificPrice)
* [$tax_calculator](#property-$tax_calculator)
* [$tax_computation_method](#property-$tax_computation_method)
* [$tax_name](#property-$tax_name)
* [$tax_rate](#property-$tax_rate)
* [$total_price_tax_excl](#property-$total_price_tax_excl)
* [$total_price_tax_incl](#property-$total_price_tax_incl)
* [$total_shipping_price_tax_excl](#property-$total_shipping_price_tax_excl)
* [$total_shipping_price_tax_incl](#property-$total_shipping_price_tax_incl)
* [$unit_price_tax_excl](#property-$unit_price_tax_excl)
* [$unit_price_tax_incl](#property-$unit_price_tax_incl)
* [$vat_address](#property-$vat_address)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [checkProductStock](#method-checkProductStock)
* [create](#method-create)
* [createList](#method-createList)
* [delete](#method-delete)
* [getCrossSells](#method-getCrossSells)
* [getDownloadFromHash](#method-getDownloadFromHash)
* [getList](#method-getList)
* [getStockState](#method-getStockState)
* [getTaxCalculator](#method-getTaxCalculator)
* [getTaxCalculatorStatic](#method-getTaxCalculatorStatic)
* [getWsTaxes](#method-getWsTaxes)
* [incrementDownload](#method-incrementDownload)
* [saveTaxCalculator](#method-saveTaxCalculator)
* [setContext](#method-setContext)
* [setDetailProductPrice](#method-setDetailProductPrice)
* [setProductTax](#method-setProductTax)
* [setShippingCost](#method-setShippingCost)
* [setSpecificPrice](#method-setSpecificPrice)
* [setVirtualProductInformation](#method-setVirtualProductInformation)
* [updateTaxAmount](#method-updateTaxAmount)




Properties
----------


### <a name="property-$context"></a>$context

```php
protected \Context $context = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L238).


### <a name="property-$customer"></a>$customer

```php
protected \Customer $customer = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L235).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_detail', 'primary' => 'id_order_detail', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'product_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_attribute_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'product_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'product_quantity_in_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'product_quantity_return' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_reinjected' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'group_reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_quantity_discount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'product_upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'product_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tax_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tax_computation_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'ecotax_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'discount_quantity_applied' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_hash' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'download_nb' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_deadline' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'unit_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'unit_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'purchase_supplier_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'original_product_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderDetail.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L158).


### <a name="property-$discount_quantity_applied"></a>$discount_quantity_applied

```php
public integer $discount_quantity_applied
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L123).


### <a name="property-$download_deadline"></a>$download_deadline

```php
public \date $download_deadline
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L132).


### <a name="property-$download_hash"></a>$download_hash

```php
public string $download_hash
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L126).


### <a name="property-$download_nb"></a>$download_nb

```php
public integer $download_nb
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L129).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L117).


### <a name="property-$ecotax_tax_rate"></a>$ecotax_tax_rate

```php
public float $ecotax_tax_rate
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L120).


### <a name="property-$group_reduction"></a>$group_reduction

```php
public float $group_reduction
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L96).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L33).


### <a name="property-$id_order_detail"></a>$id_order_detail

```php
public integer $id_order_detail
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L30).


### <a name="property-$id_order_invoice"></a>$id_order_invoice

```php
public integer $id_order_invoice
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L36).


### <a name="property-$id_shop"></a>$id_shop

```php
public integer $id_shop
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L42).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L144).


### <a name="property-$original_product_price"></a>$original_product_price

```php
public float $original_product_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L69).


### <a name="property-$outOfStock"></a>$outOfStock

```php
protected boolean $outOfStock = false
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L223).


### <a name="property-$product_attribute_id"></a>$product_attribute_id

```php
public integer $product_attribute_id
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L45).


### <a name="property-$product_ean13"></a>$product_ean13

```php
public string $product_ean13
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L102).


### <a name="property-$product_id"></a>$product_id

```php
public integer $product_id
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L39).


### <a name="property-$product_name"></a>$product_name

```php
public string $product_name
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L48).


### <a name="property-$product_price"></a>$product_price

```php
public float $product_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L66).


### <a name="property-$product_quantity"></a>$product_quantity

```php
public integer $product_quantity
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L51).


### <a name="property-$product_quantity_discount"></a>$product_quantity_discount

```php
public float $product_quantity_discount
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L99).


### <a name="property-$product_quantity_in_stock"></a>$product_quantity_in_stock

```php
public integer $product_quantity_in_stock
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L54).


### <a name="property-$product_quantity_refunded"></a>$product_quantity_refunded

```php
public integer $product_quantity_refunded
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L60).


### <a name="property-$product_quantity_reinjected"></a>$product_quantity_reinjected

```php
public integer $product_quantity_reinjected
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L63).


### <a name="property-$product_quantity_return"></a>$product_quantity_return

```php
public integer $product_quantity_return
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L57).


### <a name="property-$product_reference"></a>$product_reference

```php
public string $product_reference
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L108).


### <a name="property-$product_supplier_reference"></a>$product_supplier_reference

```php
public string $product_supplier_reference
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L111).


### <a name="property-$product_upc"></a>$product_upc

```php
public string $product_upc
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L105).


### <a name="property-$product_weight"></a>$product_weight

```php
public float $product_weight
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L114).


### <a name="property-$purchase_supplier_price"></a>$purchase_supplier_price

```php
public float $purchase_supplier_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L153).


### <a name="property-$reduction_amount"></a>$reduction_amount

```php
public float $reduction_amount
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L87).


### <a name="property-$reduction_amount_tax_excl"></a>$reduction_amount_tax_excl

```php
public float $reduction_amount_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L90).


### <a name="property-$reduction_amount_tax_incl"></a>$reduction_amount_tax_incl

```php
public float $reduction_amount_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L93).


### <a name="property-$reduction_percent"></a>$reduction_percent

```php
public float $reduction_percent
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L84).


### <a name="property-$specificPrice"></a>$specificPrice

```php
protected \Address $specificPrice = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L232).


### <a name="property-$tax_calculator"></a>$tax_calculator

```php
protected \TaxCalculator $tax_calculator = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L226).


### <a name="property-$tax_computation_method"></a>$tax_computation_method

```php
public float $tax_computation_method
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L141).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L135).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public float $tax_rate
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L138).


### <a name="property-$total_price_tax_excl"></a>$total_price_tax_excl

```php
public float $total_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L81).


### <a name="property-$total_price_tax_incl"></a>$total_price_tax_incl

```php
public float $total_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L78).


### <a name="property-$total_shipping_price_tax_excl"></a>$total_shipping_price_tax_excl

```php
public float $total_shipping_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L147).


### <a name="property-$total_shipping_price_tax_incl"></a>$total_shipping_price_tax_incl

```php
public float $total_shipping_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L150).


### <a name="property-$unit_price_tax_excl"></a>$unit_price_tax_excl

```php
public float $unit_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L75).


### <a name="property-$unit_price_tax_incl"></a>$unit_price_tax_incl

```php
public float $unit_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L72).


### <a name="property-$vat_address"></a>$vat_address

```php
protected \Address $vat_address = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L229).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders'), 'product_id' => array('xlink_resource' => 'products'), 'product_attribute_id' => array('xlink_resource' => 'combinations'), 'product_quantity_reinjected' => array(), 'group_reduction' => array(), 'discount_quantity_applied' => array(), 'download_hash' => array(), 'download_deadline' => array()), 'hidden_fields' => array('tax_rate', 'tax_name'), 'associations' => array('taxes' => array('resource' => 'tax', 'getter' => 'getWsTaxes', 'setter' => false, 'fields' => array('id' => array()))))
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L204).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed OrderDetailCore::__construct($id, $id_lang, $context)
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L240)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $context **mixed**



### <a name="method-checkProductStock"></a>checkProductStock

```php
mixed OrderDetailCore::checkProductStock(array $product, integer $id_order_state)
```

Check the order state



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L412)


#### Arguments
* $product **array**
* $id_order_state **integer**



### <a name="method-create"></a>create

```php
mixed OrderDetailCore::create(object $order, object $cart, array $product, $id_order_state, integer $id_order_invoice, boolean $use_taxes, $id_warehouse)
```

Create an order detail liable to an id_order



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L549)


#### Arguments
* $order **object**
* $cart **object**
* $product **array**
* $id_order_state **mixed**
* $id_order_invoice **integer**
* $use_taxes **boolean** - set to false if you don&#039;t want to use taxes
* $id_warehouse **mixed**



### <a name="method-createList"></a>createList

```php
mixed OrderDetailCore::createList(object $order, object $cart, $id_order_state, $product_list, integer $id_order_invoice, boolean $use_taxes, $id_warehouse)
```

Create a list of order detail for a specified id_order using cart



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L604)


#### Arguments
* $order **object**
* $cart **object**
* $id_order_state **mixed**
* $product_list **mixed**
* $id_order_invoice **integer**
* $use_taxes **boolean** - set to false if you don&#039;t want to use taxes
* $id_warehouse **mixed**



### <a name="method-delete"></a>delete

```php
mixed OrderDetailCore::delete()
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L253)




### <a name="method-getCrossSells"></a>getCrossSells

```php
mixed OrderDetailCore::getCrossSells($id_product, $id_lang, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L658)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $limit **mixed**



### <a name="method-getDownloadFromHash"></a>getDownloadFromHash

```php
mixed OrderDetailCore::getDownloadFromHash($hash)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L269)


#### Arguments
* $hash **mixed**



### <a name="method-getList"></a>getList

```php
array OrderDetailCore::getList(integer $id_order)
```

Get a detailed order list of an id_order



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L382)


#### Arguments
* $id_order **integer**



### <a name="method-getStockState"></a>getStockState

```php
array OrderDetailCore::getStockState()
```

Get the state of the current stock product



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L624)




### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
\TaxCalculator OrderDetailCore::getTaxCalculator()
```

Returns the tax calculator associated to this order detail.



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L294)




### <a name="method-getTaxCalculatorStatic"></a>getTaxCalculatorStatic

```php
\TaxCalculator OrderDetailCore::getTaxCalculatorStatic(integer $id_order_detail)
```

Return the tax calculator associated to this order_detail



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L305)


#### Arguments
* $id_order_detail **integer**



### <a name="method-getWsTaxes"></a>getWsTaxes

```php
mixed OrderDetailCore::getWsTaxes()
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 648](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L648)




### <a name="method-incrementDownload"></a>incrementDownload

```php
mixed OrderDetailCore::incrementDownload($id_order_detail, $increment)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L280)


#### Arguments
* $id_order_detail **mixed**
* $increment **mixed**



### <a name="method-saveTaxCalculator"></a>saveTaxCalculator

```php
boolean OrderDetailCore::saveTaxCalculator(\Order $order, $replace)
```

Save the tax calculator



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L330)


#### Arguments
* $order **[Order](class.OrderCore.md)**
* $replace **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed OrderDetailCore::setContext($id_shop)
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L263)


#### Arguments
* $id_shop **mixed**



### <a name="method-setDetailProductPrice"></a>setDetailProductPrice

```php
mixed OrderDetailCore::setDetailProductPrice(object $order, object $cart, array $product)
```

Set detailed product price to the order detail



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 496](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L496)


#### Arguments
* $order **object**
* $cart **object**
* $product **array**



### <a name="method-setProductTax"></a>setProductTax

```php
mixed OrderDetailCore::setProductTax(object $order, array $product)
```

Apply tax to the product



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L434)


#### Arguments
* $order **object**
* $product **array**



### <a name="method-setShippingCost"></a>setShippingCost

```php
mixed OrderDetailCore::setShippingCost(\Order $order, $product)
```

Set the additional shipping information



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 635](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L635)


#### Arguments
* $order **[Order](class.OrderCore.md)**
* $product **mixed**



### <a name="method-setSpecificPrice"></a>setSpecificPrice

```php
mixed OrderDetailCore::setSpecificPrice(object $order, $product)
```

Set specific price of the product



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L460)


#### Arguments
* $order **object**
* $product **mixed**



### <a name="method-setVirtualProductInformation"></a>setVirtualProductInformation

```php
mixed OrderDetailCore::setVirtualProductInformation($product)
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L391)


#### Arguments
* $product **mixed**



### <a name="method-updateTaxAmount"></a>updateTaxAmount

```php
mixed OrderDetailCore::updateTaxAmount($order)
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderDetail.php#L367)


#### Arguments
* $order **mixed**


