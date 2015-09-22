Class OrderInvoiceCore
=====================





* Class name: OrderInvoiceCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderInvoice.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L27)


Contents
--------

### Constants

* [DETAIL](#constant-DETAIL)
* [TAX_EXCL](#constant-TAX_EXCL)
* [TAX_INCL](#constant-TAX_INCL)

### Properties

* [$_total_paid_cache](#property-$_total_paid_cache)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$delivery_date](#property-$delivery_date)
* [$delivery_number](#property-$delivery_number)
* [$id_order](#property-$id_order)
* [$note](#property-$note)
* [$number](#property-$number)
* [$shipping_tax_computation_method](#property-$shipping_tax_computation_method)
* [$total_discount_tax_excl](#property-$total_discount_tax_excl)
* [$total_discount_tax_incl](#property-$total_discount_tax_incl)
* [$total_paid_tax_excl](#property-$total_paid_tax_excl)
* [$total_paid_tax_incl](#property-$total_paid_tax_incl)
* [$total_products](#property-$total_products)
* [$total_products_wt](#property-$total_products_wt)
* [$total_shipping_tax_excl](#property-$total_shipping_tax_excl)
* [$total_shipping_tax_incl](#property-$total_shipping_tax_incl)
* [$total_wrapping_tax_excl](#property-$total_wrapping_tax_excl)
* [$total_wrapping_tax_incl](#property-$total_wrapping_tax_incl)

### Methods

* [getByDateInterval](#method-getByDateInterval)
* [getByDeliveryDateInterval](#method-getByDeliveryDateInterval)
* [getByStatus](#method-getByStatus)
* [getCarrier](#method-getCarrier)
* [getCarrierId](#method-getCarrierId)
* [getEcoTaxTaxesBreakdown](#method-getEcoTaxTaxesBreakdown)
* [getGlobalRestPaid](#method-getGlobalRestPaid)
* [getInvoiceByNumber](#method-getInvoiceByNumber)
* [getInvoiceNumberFormatted](#method-getInvoiceNumberFormatted)
* [getOrderPaymentCollection](#method-getOrderPaymentCollection)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getProducts](#method-getProducts)
* [getProductsDetail](#method-getProductsDetail)
* [getRestPaid](#method-getRestPaid)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getSibling](#method-getSibling)
* [getSiblingTotal](#method-getSiblingTotal)
* [getTotalPaid](#method-getTotalPaid)
* [getWrappingTaxesBreakdown](#method-getWrappingTaxesBreakdown)
* [isPaid](#method-isPaid)
* [retrieveOneById](#method-retrieveOneById)
* [saveCarrierTaxCalculator](#method-saveCarrierTaxCalculator)
* [setProductCurrentStock](#method-setProductCurrentStock)
* [setProductCustomizedDatas](#method-setProductCustomizedDatas)
* [setProductImageInformations](#method-setProductImageInformations)
* [useOneAfterAnotherTaxComputationMethod](#method-useOneAfterAnotherTaxComputationMethod)


Constants
----------


### <a name="constant-DETAIL"></a>DETAIL

```php
const DETAIL = 2
```





* Source: [classes/order/OrderInvoice.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L31).


### <a name="constant-TAX_EXCL"></a>TAX_EXCL

```php
const TAX_EXCL = 0
```





* Source: [classes/order/OrderInvoice.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L29).


### <a name="constant-TAX_INCL"></a>TAX_INCL

```php
const TAX_INCL = 1
```





* Source: [classes/order/OrderInvoice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L30).


Properties
----------


### <a name="property-$_total_paid_cache"></a>$_total_paid_cache

```php
protected array $_total_paid_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/order/OrderInvoice.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L85).


### <a name="property-$date_add"></a>$date_add

```php
public \intger $date_add
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L82).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_invoice', 'primary' => 'id_order_invoice', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'number' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'delivery_number' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'delivery_date' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'total_discount_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_discount_tax_incl' => array('type' => self::TYPE_FLOAT), 'total_paid_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_paid_tax_incl' => array('type' => self::TYPE_FLOAT), 'total_products' => array('type' => self::TYPE_FLOAT), 'total_products_wt' => array('type' => self::TYPE_FLOAT), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT), 'shipping_tax_computation_method' => array('type' => self::TYPE_INT), 'total_wrapping_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_wrapping_tax_incl' => array('type' => self::TYPE_FLOAT), 'note' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65000), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderInvoice.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L90).


### <a name="property-$delivery_date"></a>$delivery_date

```php
public integer $delivery_date = '0000-00-00 00:00:00'
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L43).


### <a name="property-$delivery_number"></a>$delivery_number

```php
public integer $delivery_number
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L40).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L34).


### <a name="property-$note"></a>$note

```php
public string $note
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L79).


### <a name="property-$number"></a>$number

```php
public integer $number
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L37).


### <a name="property-$shipping_tax_computation_method"></a>$shipping_tax_computation_method

```php
public integer $shipping_tax_computation_method
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L70).


### <a name="property-$total_discount_tax_excl"></a>$total_discount_tax_excl

```php
public float $total_discount_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L46).


### <a name="property-$total_discount_tax_incl"></a>$total_discount_tax_incl

```php
public float $total_discount_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L49).


### <a name="property-$total_paid_tax_excl"></a>$total_paid_tax_excl

```php
public float $total_paid_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L52).


### <a name="property-$total_paid_tax_incl"></a>$total_paid_tax_incl

```php
public float $total_paid_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L55).


### <a name="property-$total_products"></a>$total_products

```php
public float $total_products
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L58).


### <a name="property-$total_products_wt"></a>$total_products_wt

```php
public float $total_products_wt
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L61).


### <a name="property-$total_shipping_tax_excl"></a>$total_shipping_tax_excl

```php
public float $total_shipping_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L64).


### <a name="property-$total_shipping_tax_incl"></a>$total_shipping_tax_incl

```php
public float $total_shipping_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L67).


### <a name="property-$total_wrapping_tax_excl"></a>$total_wrapping_tax_excl

```php
public float $total_wrapping_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L73).


### <a name="property-$total_wrapping_tax_incl"></a>$total_wrapping_tax_incl

```php
public float $total_wrapping_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L76).


Methods
-------


### <a name="method-getByDateInterval"></a>getByDateInterval

```php
array OrderInvoiceCore::getByDateInterval($date_from, $date_to)
```

Returns all the order invoice that match the date interval



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L424)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**



### <a name="method-getByDeliveryDateInterval"></a>getByDeliveryDateInterval

```php
array OrderInvoiceCore::getByDeliveryDateInterval($date_from, $date_to)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L468)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**



### <a name="method-getByStatus"></a>getByStatus

```php
array OrderInvoiceCore::getByStatus($id_order_state)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L446)


#### Arguments
* $id_order_state **mixed**



### <a name="method-getCarrier"></a>getCarrier

```php
mixed OrderInvoiceCore::getCarrier($id_order_invoice)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L488)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-getCarrierId"></a>getCarrierId

```php
mixed OrderInvoiceCore::getCarrierId($id_order_invoice)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L502)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-getEcoTaxTaxesBreakdown"></a>getEcoTaxTaxesBreakdown

```php
array OrderInvoiceCore::getEcoTaxTaxesBreakdown()
```

Returns the ecotax taxes breakdown



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L395)




### <a name="method-getGlobalRestPaid"></a>getGlobalRestPaid

```php
mixed OrderInvoiceCore::getGlobalRestPaid()
```

Get global rest to paid
   This method will return something different of the method getRestPaid if
   there is an other invoice linked to the payments of the current invoice



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L621)




### <a name="method-getInvoiceByNumber"></a>getInvoiceByNumber

```php
mixed OrderInvoiceCore::getInvoiceByNumber($id_invoice)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L126)


#### Arguments
* $id_invoice **mixed**



### <a name="method-getInvoiceNumberFormatted"></a>getInvoiceNumberFormatted

```php
string OrderInvoiceCore::getInvoiceNumberFormatted(integer $id_lang, $id_shop)
```

Get the formatted number of invoice



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L672)


#### Arguments
* $id_lang **integer** - for invoice_prefix
* $id_shop **mixed**



### <a name="method-getOrderPaymentCollection"></a>getOrderPaymentCollection

```php
\PrestaShopCollection OrderInvoiceCore::getOrderPaymentCollection()
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L661)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

```php
array OrderInvoiceCore::getProductTaxesBreakdown($order)
```

Returns the correct product taxes breakdown.



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L277)


#### Arguments
* $order **mixed**



### <a name="method-getProducts"></a>getProducts

```php
array OrderInvoiceCore::getProducts($products, $selectedProducts, $selectedQty)
```

Get order products



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L153)


#### Arguments
* $products **mixed**
* $selectedProducts **mixed**
* $selectedQty **mixed**



### <a name="method-getProductsDetail"></a>getProductsDetail

```php
mixed OrderInvoiceCore::getProductsDetail()
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L114)




### <a name="method-getRestPaid"></a>getRestPaid

```php
float OrderInvoiceCore::getRestPaid()
```

Rest Paid



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L548)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

```php
array OrderInvoiceCore::getShippingTaxesBreakdown($order)
```

Returns the shipping taxes breakdown



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L355)


#### Arguments
* $order **mixed**



### <a name="method-getSibling"></a>getSibling

```php
\PrestaShopCollection|array OrderInvoiceCore::getSibling()
```

Return collection of order invoice object linked to the payments of the current order invoice object



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L560)




### <a name="method-getSiblingTotal"></a>getSiblingTotal

```php
mixed OrderInvoiceCore::getSiblingTotal(integer $mod)
```

Return total to paid of sibling invoices



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 591](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L591)


#### Arguments
* $mod **integer** - TAX_EXCL, TAX_INCL, DETAIL



### <a name="method-getTotalPaid"></a>getTotalPaid

```php
float OrderInvoiceCore::getTotalPaid()
```

Amounts of payments



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L529)




### <a name="method-getWrappingTaxesBreakdown"></a>getWrappingTaxesBreakdown

```php
array OrderInvoiceCore::getWrappingTaxesBreakdown()
```

Returns the wrapping taxes breakdown



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L383)




### <a name="method-isPaid"></a>isPaid

```php
boolean OrderInvoiceCore::isPaid()
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L652)




### <a name="method-retrieveOneById"></a>retrieveOneById

```php
\OrderInvoice OrderInvoiceCore::retrieveOneById($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L516)


#### Arguments
* $id **mixed**



### <a name="method-saveCarrierTaxCalculator"></a>saveCarrierTaxCalculator

```php
mixed OrderInvoiceCore::saveCarrierTaxCalculator(array $taxes_amount)
```





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 677](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L677)


#### Arguments
* $taxes_amount **array**



### <a name="method-setProductCurrentStock"></a>setProductCurrentStock

```php
mixed OrderInvoiceCore::setProductCurrentStock($product)
```

This method allow to add stock information on a product detail



* Visibility: **protected**
* Source: [classes/order/OrderInvoice.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L213)


#### Arguments
* $product **mixed**



### <a name="method-setProductCustomizedDatas"></a>setProductCustomizedDatas

```php
mixed OrderInvoiceCore::setProductCustomizedDatas($product, $customized_datas)
```





* Visibility: **protected**
* Source: [classes/order/OrderInvoice.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L199)


#### Arguments
* $product **mixed**
* $customized_datas **mixed**



### <a name="method-setProductImageInformations"></a>setProductImageInformations

```php
mixed OrderInvoiceCore::setProductImageInformations($product)
```

This method allow to add image information on a product detail



* Visibility: **protected**
* Source: [classes/order/OrderInvoice.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L228)


#### Arguments
* $product **mixed**



### <a name="method-useOneAfterAnotherTaxComputationMethod"></a>useOneAfterAnotherTaxComputationMethod

```php
boolean OrderInvoiceCore::useOneAfterAnotherTaxComputationMethod()
```

This method returns true if at least one order details uses the
One After Another tax computation method.



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/order/OrderInvoice.php#L258)



