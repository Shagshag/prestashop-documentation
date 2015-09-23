Class SupplyOrderDetailCore
=====================

Represents one product ordered



* Class name: SupplyOrderDetailCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/SupplyOrderDetail.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L31)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$discount_rate](#property-$discount_rate)
* [$discount_value_te](#property-$discount_value_te)
* [$ean13](#property-$ean13)
* [$exchange_rate](#property-$exchange_rate)
* [$id_currency](#property-$id_currency)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_supply_order](#property-$id_supply_order)
* [$name](#property-$name)
* [$price_te](#property-$price_te)
* [$price_ti](#property-$price_ti)
* [$price_with_discount_te](#property-$price_with_discount_te)
* [$price_with_order_discount_te](#property-$price_with_order_discount_te)
* [$quantity_expected](#property-$quantity_expected)
* [$quantity_received](#property-$quantity_received)
* [$reference](#property-$reference)
* [$supplier_reference](#property-$supplier_reference)
* [$tax_rate](#property-$tax_rate)
* [$tax_value](#property-$tax_value)
* [$tax_value_with_order_discount](#property-$tax_value_with_order_discount)
* [$unit_price_te](#property-$unit_price_te)
* [$upc](#property-$upc)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [applyGlobalDiscount](#method-applyGlobalDiscount)
* [calculatePrices](#method-calculatePrices)
* [hydrate](#method-hydrate)
* [update](#method-update)
* [validateController](#method-validateController)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supply_order_detail', 'primary' => 'id_supply_order_detail', 'fields' => array('id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'exchange_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'unit_price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'quantity_expected' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'quantity_received' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'discount_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'discount_value_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'price_with_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'tax_value' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'price_ti' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'tax_value_with_order_discount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'price_with_order_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/SupplyOrderDetail.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L148).


### <a name="property-$discount_rate"></a>$discount_rate

```php
public float $discount_rate
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L107).


### <a name="property-$discount_value_te"></a>$discount_value_te

```php
public float $discount_value_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L112).


### <a name="property-$ean13"></a>$ean13

```php
public integer $ean13
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L66).


### <a name="property-$exchange_rate"></a>$exchange_rate

```php
public float $exchange_rate
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L81).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L76).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L41).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L46).


### <a name="property-$id_supply_order"></a>$id_supply_order

```php
public integer $id_supply_order
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L36).


### <a name="property-$name"></a>$name

```php
public integer $name
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L61).


### <a name="property-$price_te"></a>$price_te

```php
public float $price_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L102).


### <a name="property-$price_ti"></a>$price_ti

```php
public float $price_ti
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L132).


### <a name="property-$price_with_discount_te"></a>$price_with_discount_te

```php
public float $price_with_discount_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L117).


### <a name="property-$price_with_order_discount_te"></a>$price_with_order_discount_te

```php
public float $price_with_order_discount_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L143).


### <a name="property-$quantity_expected"></a>$quantity_expected

```php
public integer $quantity_expected
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L91).


### <a name="property-$quantity_received"></a>$quantity_received

```php
public integer $quantity_received
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L96).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L51).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public string $supplier_reference
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L56).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public integer $tax_rate
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L122).


### <a name="property-$tax_value"></a>$tax_value

```php
public float $tax_value
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L127).


### <a name="property-$tax_value_with_order_discount"></a>$tax_value_with_order_discount

```php
public float $tax_value_with_order_discount
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L137).


### <a name="property-$unit_price_te"></a>$unit_price_te

```php
public float $unit_price_te
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L86).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L71).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_details', 'objectNodeName' => 'supply_order_detail', 'fields' => array('id_supply_order' => array('xlink_resource' => 'supply_orders'), 'id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations')), 'hidden_fields' => array('id_currency'))
```





* Visibility: **protected**
* Source: [classes/stock/SupplyOrderDetail.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L180).


Methods
-------


### <a name="method-add"></a>add

```php
mixed SupplyOrderDetailCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L206)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-applyGlobalDiscount"></a>applyGlobalDiscount

```php
mixed SupplyOrderDetailCore::applyGlobalDiscount($discount_rate)
```

Applies a global order discount rate, for the current product (i.e detail)
Calls ObjectModel::update()



* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L245)


#### Arguments
* $discount_rate **mixed** - The discount rate in percent (Ex. 5 for 5 percents)



### <a name="method-calculatePrices"></a>calculatePrices

```php
mixed SupplyOrderDetailCore::calculatePrices()
```

Calculates all prices for this product based on its quantity and unit price
Applies discount if necessary
Calculates tax value, function of tax rate



* Visibility: **protected**
* Source: [classes/stock/SupplyOrderDetail.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L218)




### <a name="method-hydrate"></a>hydrate

```php
mixed SupplyOrderDetailCore::hydrate(array $data, $id_lang)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L322)


#### Arguments
* $data **array**
* $id_lang **mixed**



### <a name="method-update"></a>update

```php
mixed SupplyOrderDetailCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L196)


#### Arguments
* $null_values **mixed**



### <a name="method-validateController"></a>validateController

```php
\$errors SupplyOrderDetailCore::validateController($htmlentities)
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderDetail.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/stock/SupplyOrderDetail.php#L267)


#### Arguments
* $htmlentities **mixed** - Optional


