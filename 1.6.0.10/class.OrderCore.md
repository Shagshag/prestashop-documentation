Class OrderCore
=====================





* Class name: OrderCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/Order.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L27)


Contents
--------

### Constants

* [ROUND_ITEM](#constant-ROUND_ITEM)
* [ROUND_LINE](#constant-ROUND_LINE)
* [ROUND_TOTAL](#constant-ROUND_TOTAL)

### Properties

* [$_historyCache](#property-$_historyCache)
* [$_taxCalculationMethod](#property-$_taxCalculationMethod)
* [$carrier_tax_rate](#property-$carrier_tax_rate)
* [$conversion_rate](#property-$conversion_rate)
* [$current_state](#property-$current_state)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$delivery_date](#property-$delivery_date)
* [$delivery_number](#property-$delivery_number)
* [$gift](#property-$gift)
* [$gift_message](#property-$gift_message)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_address_invoice](#property-$id_address_invoice)
* [$id_carrier](#property-$id_carrier)
* [$id_cart](#property-$id_cart)
* [$id_currency](#property-$id_currency)
* [$id_customer](#property-$id_customer)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$invoice_date](#property-$invoice_date)
* [$invoice_number](#property-$invoice_number)
* [$mobile_theme](#property-$mobile_theme)
* [$module](#property-$module)
* [$payment](#property-$payment)
* [$recyclable](#property-$recyclable)
* [$reference](#property-$reference)
* [$secure_key](#property-$secure_key)
* [$shipping_number](#property-$shipping_number)
* [$total_discounts](#property-$total_discounts)
* [$total_discounts_tax_excl](#property-$total_discounts_tax_excl)
* [$total_discounts_tax_incl](#property-$total_discounts_tax_incl)
* [$total_paid](#property-$total_paid)
* [$total_paid_real](#property-$total_paid_real)
* [$total_paid_tax_excl](#property-$total_paid_tax_excl)
* [$total_paid_tax_incl](#property-$total_paid_tax_incl)
* [$total_products](#property-$total_products)
* [$total_products_wt](#property-$total_products_wt)
* [$total_shipping](#property-$total_shipping)
* [$total_shipping_tax_excl](#property-$total_shipping_tax_excl)
* [$total_shipping_tax_incl](#property-$total_shipping_tax_incl)
* [$total_wrapping](#property-$total_wrapping)
* [$total_wrapping_tax_excl](#property-$total_wrapping_tax_excl)
* [$total_wrapping_tax_incl](#property-$total_wrapping_tax_incl)
* [$valid](#property-$valid)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [_deleteProduct](#method-_deleteProduct)
* [add](#method-add)
* [addCartRule](#method-addCartRule)
* [addDiscount](#method-addDiscount)
* [addOrderPayment](#method-addOrderPayment)
* [addWs](#method-addWs)
* [deleteAssociations](#method-deleteAssociations)
* [deleteCustomization](#method-deleteCustomization)
* [deleteProduct](#method-deleteProduct)
* [generateReference](#method-generateReference)
* [getBrother](#method-getBrother)
* [getByDelivery](#method-getByDelivery)
* [getByReference](#method-getByReference)
* [getCartIdStatic](#method-getCartIdStatic)
* [getCartProducts](#method-getCartProducts)
* [getCartRules](#method-getCartRules)
* [getCurrentOrderState](#method-getCurrentOrderState)
* [getCurrentState](#method-getCurrentState)
* [getCurrentStateFull](#method-getCurrentStateFull)
* [getCustomer](#method-getCustomer)
* [getCustomerNbOrders](#method-getCustomerNbOrders)
* [getCustomerOrders](#method-getCustomerOrders)
* [getDeliveryNumber](#method-getDeliveryNumber)
* [getDeliverySlipsCollection](#method-getDeliverySlipsCollection)
* [getDiscounts](#method-getDiscounts)
* [getDiscountsCustomer](#method-getDiscountsCustomer)
* [getDocuments](#method-getDocuments)
* [getEcoTaxTaxesBreakdown](#method-getEcoTaxTaxesBreakdown)
* [getFields](#method-getFields)
* [getFirstMessage](#method-getFirstMessage)
* [getHistory](#method-getHistory)
* [getIdOrderCarrier](#method-getIdOrderCarrier)
* [getIdOrderProduct](#method-getIdOrderProduct)
* [getInvoice](#method-getInvoice)
* [getInvoiceNumber](#method-getInvoiceNumber)
* [getInvoicesCollection](#method-getInvoicesCollection)
* [getLastInvoiceNumber](#method-getLastInvoiceNumber)
* [getNextOrderId](#method-getNextOrderId)
* [getNotPaidInvoicesCollection](#method-getNotPaidInvoicesCollection)
* [getNumberOfDays](#method-getNumberOfDays)
* [getOrderByCartId](#method-getOrderByCartId)
* [getOrderDetailList](#method-getOrderDetailList)
* [getOrderIdsByStatus](#method-getOrderIdsByStatus)
* [getOrderPaymentCollection](#method-getOrderPaymentCollection)
* [getOrderPayments](#method-getOrderPayments)
* [getOrderSlipsCollection](#method-getOrderSlipsCollection)
* [getOrdersIdByDate](#method-getOrdersIdByDate)
* [getOrdersIdInvoiceByDate](#method-getOrdersIdInvoiceByDate)
* [getOrdersTotalPaid](#method-getOrdersTotalPaid)
* [getOrdersWithInformations](#method-getOrdersWithInformations)
* [getPreviousOrderId](#method-getPreviousOrderId)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getProducts](#method-getProducts)
* [getProductsDetail](#method-getProductsDetail)
* [getReturn](#method-getReturn)
* [getShipping](#method-getShipping)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getTaxCalculationMethod](#method-getTaxCalculationMethod)
* [getTaxesAverageUsed](#method-getTaxesAverageUsed)
* [getTotalPaid](#method-getTotalPaid)
* [getTotalProductsWithTaxes](#method-getTotalProductsWithTaxes)
* [getTotalProductsWithoutTaxes](#method-getTotalProductsWithoutTaxes)
* [getTotalWeight](#method-getTotalWeight)
* [getUniqReference](#method-getUniqReference)
* [getUniqReferenceOf](#method-getUniqReferenceOf)
* [getVirtualProducts](#method-getVirtualProducts)
* [getWarehouseList](#method-getWarehouseList)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWrappingTaxesBreakdown](#method-getWrappingTaxesBreakdown)
* [getWsCurrentState](#method-getWsCurrentState)
* [getWsOrderRows](#method-getWsOrderRows)
* [getWsShippingNumber](#method-getWsShippingNumber)
* [hasBeenDelivered](#method-hasBeenDelivered)
* [hasBeenPaid](#method-hasBeenPaid)
* [hasBeenShipped](#method-hasBeenShipped)
* [hasDelivery](#method-hasDelivery)
* [hasInvoice](#method-hasInvoice)
* [hasProductReturned](#method-hasProductReturned)
* [isAssociatedAtGuest](#method-isAssociatedAtGuest)
* [isInPreparation](#method-isInPreparation)
* [isPaidAndShipped](#method-isPaidAndShipped)
* [isReturnable](#method-isReturnable)
* [isVirtual](#method-isVirtual)
* [orderContainProduct](#method-orderContainProduct)
* [setCurrentState](#method-setCurrentState)
* [setDelivery](#method-setDelivery)
* [setDeliveryNumber](#method-setDeliveryNumber)
* [setDeliverySlip](#method-setDeliverySlip)
* [setInvoice](#method-setInvoice)
* [setLastInvoiceNumber](#method-setLastInvoiceNumber)
* [setProductCurrentStock](#method-setProductCurrentStock)
* [setProductCustomizedDatas](#method-setProductCustomizedDatas)
* [setProductImageInformations](#method-setProductImageInformations)
* [setProductPrices](#method-setProductPrices)
* [setWsCurrentState](#method-setWsCurrentState)
* [setWsShippingNumber](#method-setWsShippingNumber)
* [sortDocuments](#method-sortDocuments)
* [updateShippingCost](#method-updateShippingCost)
* [useOneAfterAnotherTaxComputationMethod](#method-useOneAfterAnotherTaxComputationMethod)


Constants
----------


### <a name="constant-ROUND_ITEM"></a>ROUND_ITEM

```php
const ROUND_ITEM = 1
```





* Source: [classes/order/Order.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L29).


### <a name="constant-ROUND_LINE"></a>ROUND_LINE

```php
const ROUND_LINE = 2
```





* Source: [classes/order/Order.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L30).


### <a name="constant-ROUND_TOTAL"></a>ROUND_TOTAL

```php
const ROUND_TOTAL = 3
```





* Source: [classes/order/Order.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L31).


Properties
----------


### <a name="property-$_historyCache"></a>$_historyCache

```php
protected mixed $_historyCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/order/Order.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L268).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
protected mixed $_taxCalculationMethod = PS_TAX_EXC
```





* Visibility: **protected**
* Source: [classes/order/Order.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L266).


### <a name="property-$carrier_tax_rate"></a>$carrier_tax_rate

```php
public float $carrier_tax_rate
```





* Visibility: **public**
* Source: [classes/order/Order.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L127).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public float $conversion_rate
```





* Visibility: **public**
* Source: [classes/order/Order.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L72).


### <a name="property-$current_state"></a>$current_state

```php
public integer $current_state
```





* Visibility: **public**
* Source: [classes/order/Order.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L60).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/order/Order.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L154).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/order/Order.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L157).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'orders', 'primary' => 'id_order', 'fields' => array('id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'current_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5'), 'payment' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true), 'recyclable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift_message' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'total_discounts' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_paid_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_real' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products_wt' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_shipping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'carrier_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'total_wrapping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'shipping_number' => array('type' => self::TYPE_STRING, 'validate' => 'isTrackingNumber'), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'invoice_number' => array('type' => self::TYPE_INT), 'delivery_number' => array('type' => self::TYPE_INT), 'invoice_date' => array('type' => self::TYPE_DATE), 'delivery_date' => array('type' => self::TYPE_DATE), 'valid' => array('type' => self::TYPE_BOOL), 'reference' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/Order.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L167).


### <a name="property-$delivery_date"></a>$delivery_date

```php
public string $delivery_date
```





* Visibility: **public**
* Source: [classes/order/Order.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L148).


### <a name="property-$delivery_number"></a>$delivery_number

```php
public integer $delivery_number
```





* Visibility: **public**
* Source: [classes/order/Order.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L142).


### <a name="property-$gift"></a>$gift

```php
public boolean $gift
```





* Visibility: **public**
* Source: [classes/order/Order.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L78).


### <a name="property-$gift_message"></a>$gift_message

```php
public string $gift_message
```





* Visibility: **public**
* Source: [classes/order/Order.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L81).


### <a name="property-$id_address_delivery"></a>$id_address_delivery

```php
public integer $id_address_delivery
```





* Visibility: **public**
* Source: [classes/order/Order.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L35).


### <a name="property-$id_address_invoice"></a>$id_address_invoice

```php
public integer $id_address_invoice
```





* Visibility: **public**
* Source: [classes/order/Order.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L38).


### <a name="property-$id_carrier"></a>$id_carrier

```php
public integer $id_carrier
```





* Visibility: **public**
* Source: [classes/order/Order.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L57).


### <a name="property-$id_cart"></a>$id_cart

```php
public integer $id_cart
```





* Visibility: **public**
* Source: [classes/order/Order.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L45).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/order/Order.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L48).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer
```





* Visibility: **public**
* Source: [classes/order/Order.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L54).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/order/Order.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/order/Order.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L42).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* Source: [classes/order/Order.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L40).


### <a name="property-$invoice_date"></a>$invoice_date

```php
public string $invoice_date
```





* Visibility: **public**
* Source: [classes/order/Order.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L145).


### <a name="property-$invoice_number"></a>$invoice_number

```php
public integer $invoice_number
```





* Visibility: **public**
* Source: [classes/order/Order.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L139).


### <a name="property-$mobile_theme"></a>$mobile_theme

```php
public boolean $mobile_theme
```





* Visibility: **public**
* Source: [classes/order/Order.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L84).


### <a name="property-$module"></a>$module

```php
public string $module
```





* Visibility: **public**
* Source: [classes/order/Order.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L69).


### <a name="property-$payment"></a>$payment

```php
public string $payment
```





* Visibility: **public**
* Source: [classes/order/Order.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L66).


### <a name="property-$recyclable"></a>$recyclable

```php
public boolean $recyclable = 1
```





* Visibility: **public**
* Source: [classes/order/Order.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L75).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/order/Order.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L162).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/order/Order.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L63).


### <a name="property-$shipping_number"></a>$shipping_number

```php
public string $shipping_number
```





* Visibility: **public**
* Source: [classes/order/Order.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L91).


### <a name="property-$total_discounts"></a>$total_discounts

```php
public float $total_discounts
```





* Visibility: **public**
* Source: [classes/order/Order.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L94).


### <a name="property-$total_discounts_tax_excl"></a>$total_discounts_tax_excl

```php
public mixed $total_discounts_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L97).


### <a name="property-$total_discounts_tax_incl"></a>$total_discounts_tax_incl

```php
public mixed $total_discounts_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L96).


### <a name="property-$total_paid"></a>$total_paid

```php
public float $total_paid
```





* Visibility: **public**
* Source: [classes/order/Order.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L100).


### <a name="property-$total_paid_real"></a>$total_paid_real

```php
public float $total_paid_real
```





* Visibility: **public**
* Source: [classes/order/Order.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L109).


### <a name="property-$total_paid_tax_excl"></a>$total_paid_tax_excl

```php
public float $total_paid_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L106).


### <a name="property-$total_paid_tax_incl"></a>$total_paid_tax_incl

```php
public float $total_paid_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L103).


### <a name="property-$total_products"></a>$total_products

```php
public float $total_products
```





* Visibility: **public**
* Source: [classes/order/Order.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L112).


### <a name="property-$total_products_wt"></a>$total_products_wt

```php
public float $total_products_wt
```





* Visibility: **public**
* Source: [classes/order/Order.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L115).


### <a name="property-$total_shipping"></a>$total_shipping

```php
public float $total_shipping
```





* Visibility: **public**
* Source: [classes/order/Order.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L118).


### <a name="property-$total_shipping_tax_excl"></a>$total_shipping_tax_excl

```php
public float $total_shipping_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L124).


### <a name="property-$total_shipping_tax_incl"></a>$total_shipping_tax_incl

```php
public float $total_shipping_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L121).


### <a name="property-$total_wrapping"></a>$total_wrapping

```php
public float $total_wrapping
```





* Visibility: **public**
* Source: [classes/order/Order.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L130).


### <a name="property-$total_wrapping_tax_excl"></a>$total_wrapping_tax_excl

```php
public float $total_wrapping_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L136).


### <a name="property-$total_wrapping_tax_incl"></a>$total_wrapping_tax_incl

```php
public float $total_wrapping_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L133).


### <a name="property-$valid"></a>$valid

```php
public boolean $valid
```





* Visibility: **public**
* Source: [classes/order/Order.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L151).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs'), 'objectNodeName' => 'order', 'objectsNodeName' => 'orders', 'fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_cart' => array('xlink_resource' => 'carts'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_carrier' => array('xlink_resource' => 'carriers'), 'current_state' => array('xlink_resource' => 'order_states', 'getter' => 'getWsCurrentState', 'setter' => 'setWsCurrentState'), 'module' => array('required' => true), 'invoice_number' => array(), 'invoice_date' => array(), 'delivery_number' => array(), 'delivery_date' => array(), 'valid' => array(), 'date_add' => array(), 'date_upd' => array(), 'shipping_number' => array('getter' => 'getWsShippingNumber', 'setter' => 'setWsShippingNumber')), 'associations' => array('order_rows' => array('resource' => 'order_row', 'setter' => false, 'virtual_entity' => true, 'fields' => array('id' => array(), 'product_id' => array('required' => true), 'product_attribute_id' => array('required' => true), 'product_quantity' => array('required' => true), 'product_name' => array('setter' => false), 'product_reference' => array('setter' => false), 'product_ean13' => array('setter' => false), 'product_upc' => array('setter' => false), 'product_price' => array('setter' => false), 'unit_price_tax_incl' => array('setter' => false), 'unit_price_tax_excl' => array('setter' => false)))))
```





* Visibility: **protected**
* Source: [classes/order/Order.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L217).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed OrderCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L270)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-_deleteProduct"></a>_deleteProduct

```php
mixed OrderCore::_deleteProduct($orderDetail, $quantity)
```





* Visibility: **protected**
* Source: [classes/order/Order.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L365)


#### Arguments
* $orderDetail **mixed**
* $quantity **mixed**



### <a name="method-add"></a>add

```php
mixed OrderCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L296)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addCartRule"></a>addCartRule

```php
boolean OrderCore::addCartRule(integer $id_cart_rule, string $name, array $values, integer $id_order_invoice, $free_shipping)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1065](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1065)


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $values **array**
* $id_order_invoice **integer**
* $free_shipping **mixed**



### <a name="method-addDiscount"></a>addDiscount

```php
boolean OrderCore::addDiscount(integer $id_cart_rule, string $name, float $value)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1051](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1051)


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $value **float**



### <a name="method-addOrderPayment"></a>addOrderPayment

```php
boolean OrderCore::addOrderPayment(float $amount_paid, string $payment_method, string $payment_transaction_id, \Currency $currency, string $date, \OrderInvoice $order_invoice)
```

This method allows to add a payment to the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1562](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1562)


#### Arguments
* $amount_paid **float**
* $payment_method **string**
* $payment_transaction_id **string**
* $currency **[Currency](class.CurrencyCore.md)**
* $date **string**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**



### <a name="method-addWs"></a>addWs

```php
mixed OrderCore::addWs($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1447)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-deleteAssociations"></a>deleteAssociations

```php
mixed OrderCore::deleteAssociations()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1456](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1456)




### <a name="method-deleteCustomization"></a>deleteCustomization

```php
mixed OrderCore::deleteCustomization($id_customization, $quantity, $orderDetail)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L435)


#### Arguments
* $id_customization **mixed**
* $quantity **mixed**
* $orderDetail **mixed**



### <a name="method-deleteProduct"></a>deleteProduct

```php
mixed OrderCore::deleteProduct($order, $orderDetail, $quantity)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L309)


#### Arguments
* $order **mixed**
* $orderDetail **mixed**
* $quantity **mixed**



### <a name="method-generateReference"></a>generateReference

```php
String OrderCore::generateReference()
```

Gennerate a unique reference for orders generated with the same cart id
This references, is usefull for check payment



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1506](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1506)




### <a name="method-getBrother"></a>getBrother

```php
mixed OrderCore::getBrother()
```

Get all other orders with the same reference



* Visibility: **public**
* Source: [classes/order/Order.php line 1970](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1970)




### <a name="method-getByDelivery"></a>getByDelivery

```php
mixed OrderCore::getByDelivery($id_delivery)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1324](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1324)


#### Arguments
* $id_delivery **mixed**



### <a name="method-getByReference"></a>getByReference

```php
\PrestaShopCollection OrderCore::getByReference(string $reference)
```

Get a collection of orders using reference



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1342)


#### Arguments
* $reference **string**



### <a name="method-getCartIdStatic"></a>getCartIdStatic

```php
integer OrderCore::getCartIdStatic(integer $id_order, integer $id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1391)


#### Arguments
* $id_order **integer**
* $id_customer **integer** - optionnal



### <a name="method-getCartProducts"></a>getCartProducts

```php
array OrderCore::getCartProducts()
```

This function return products of the orders
It's similar to Order::getProducts but witrh similar outputs of Cart::getProducts



* Visibility: **public**
* Source: [classes/order/Order.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L335)




### <a name="method-getCartRules"></a>getCartRules

```php
mixed OrderCore::getCartRules()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 736](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L736)




### <a name="method-getCurrentOrderState"></a>getCurrentOrderState

```php
\OrderState OrderCore::getCurrentOrderState()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1949](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1949)




### <a name="method-getCurrentState"></a>getCurrentState

```php
integer OrderCore::getCurrentState()
```

Get current order status (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**
* Source: [classes/order/Order.php line 764](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L764)




### <a name="method-getCurrentStateFull"></a>getCurrentStateFull

```php
array OrderCore::getCurrentStateFull($id_lang)
```

Get current order status name (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**
* Source: [classes/order/Order.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L774)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCustomer"></a>getCustomer

```php
\Customer OrderCore::getCustomer()
```

Get order customer



* Visibility: **public**
* Source: [classes/order/Order.php line 1000](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1000)




### <a name="method-getCustomerNbOrders"></a>getCustomerNbOrders

```php
array OrderCore::getCustomerNbOrders(integer $id_customer)
```

Get customer orders number



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1015](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1015)


#### Arguments
* $id_customer **integer** - Customer id



### <a name="method-getCustomerOrders"></a>getCustomerOrders

```php
array OrderCore::getCustomerOrders(integer $id_customer, boolean $showHiddenStatus, \Context $context)
```

Get customer orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L838)


#### Arguments
* $id_customer **integer** - Customer id
* $showHiddenStatus **boolean** - Display or not hidden order statuses
* $context **[Context](class.ContextCore.md)**



### <a name="method-getDeliveryNumber"></a>getDeliveryNumber

```php
mixed OrderCore::getDeliveryNumber($order_invoice_id)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1287)


#### Arguments
* $order_invoice_id **mixed**



### <a name="method-getDeliverySlipsCollection"></a>getDeliverySlipsCollection

```php
\PrestaShopCollection OrderCore::getDeliverySlipsCollection()
```

Get all delivery slips for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1690](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1690)




### <a name="method-getDiscounts"></a>getDiscounts

```php
mixed OrderCore::getDiscounts($details)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 730](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L730)


#### Arguments
* $details **mixed**



### <a name="method-getDiscountsCustomer"></a>getDiscountsCustomer

```php
mixed OrderCore::getDiscountsCustomer($id_customer, $id_cart_rule)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 744](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L744)


#### Arguments
* $id_customer **mixed**
* $id_cart_rule **mixed**



### <a name="method-getDocuments"></a>getDocuments

```php
array OrderCore::getDocuments()
```

Returns the correct product taxes breakdown.

Get all documents linked to the current order

* Visibility: **public**
* Source: [classes/order/Order.php line 1608](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1608)




### <a name="method-getEcoTaxTaxesBreakdown"></a>getEcoTaxTaxesBreakdown

```php
array OrderCore::getEcoTaxTaxesBreakdown()
```

Returns the ecotax taxes breakdown



* Visibility: **public**
* Source: [classes/order/Order.php line 1882](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1882)




### <a name="method-getFields"></a>getFields

```php
array OrderCore::getFields()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L288)




### <a name="method-getFirstMessage"></a>getFirstMessage

```php
mixed OrderCore::getFirstMessage()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L519)




### <a name="method-getHistory"></a>getHistory

```php
array OrderCore::getHistory(integer $id_lang, integer $id_order_state, integer $no_hidden, integer $filters)
```

Get order history



* Visibility: **public**
* Source: [classes/order/Order.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L461)


#### Arguments
* $id_lang **integer** - Language id
* $id_order_state **integer** - Filter a specific order status
* $no_hidden **integer** - Filter no hidden status
* $filters **integer** - Flag to use specific field filter



### <a name="method-getIdOrderCarrier"></a>getIdOrderCarrier

```php
mixed OrderCore::getIdOrderCarrier()
```

Return id of carrier

Get id of the carrier used in order

* Visibility: **public**
* Source: [classes/order/Order.php line 2032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L2032)




### <a name="method-getIdOrderProduct"></a>getIdOrderProduct

```php
mixed OrderCore::getIdOrderProduct($id_customer, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L610)


#### Arguments
* $id_customer **mixed**
* $id_product **mixed**



### <a name="method-getInvoice"></a>getInvoice

```php
mixed OrderCore::getInvoice(integer $id_invoice)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1363](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1363)


#### Arguments
* $id_invoice **integer**



### <a name="method-getInvoiceNumber"></a>getInvoiceNumber

```php
mixed OrderCore::getInvoiceNumber($order_invoice_id)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1140)


#### Arguments
* $order_invoice_id **mixed**



### <a name="method-getInvoicesCollection"></a>getInvoicesCollection

```php
\PrestaShopCollection OrderCore::getInvoicesCollection()
```

Get all invoices for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1677](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1677)




### <a name="method-getLastInvoiceNumber"></a>getLastInvoiceNumber

```php
mixed OrderCore::getLastInvoiceNumber()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1109)




### <a name="method-getNextOrderId"></a>getNextOrderId

```php
integer OrderCore::getNextOrderId()
```

This method return the ID of the next order



* Visibility: **public**
* Source: [classes/order/Order.php line 1482](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1482)




### <a name="method-getNotPaidInvoicesCollection"></a>getNotPaidInvoicesCollection

```php
\PrestaShopCollection OrderCore::getNotPaidInvoicesCollection()
```

Get all not paid invoices for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1703](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1703)




### <a name="method-getNumberOfDays"></a>getNumberOfDays

```php
mixed OrderCore::getNumberOfDays()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1083)




### <a name="method-getOrderByCartId"></a>getOrderByCartId

```php
array OrderCore::getOrderByCartId(integer $id_cart)
```

Get an order by its cart id



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1032)


#### Arguments
* $id_cart **integer** - Cart id



### <a name="method-getOrderDetailList"></a>getOrderDetailList

```php
array OrderCore::getOrderDetailList()
```

Get the an order detail list of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1495)




### <a name="method-getOrderIdsByStatus"></a>getOrderIdsByStatus

```php
array OrderCore::getOrderIdsByStatus($id_order_state)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 943](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L943)


#### Arguments
* $id_order_state **mixed**



### <a name="method-getOrderPaymentCollection"></a>getOrderPaymentCollection

```php
\PrestaShopCollection OrderCore::getOrderPaymentCollection()
```

This method allows to get all Order Payment for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1543](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1543)




### <a name="method-getOrderPayments"></a>getOrderPayments

```php
mixed OrderCore::getOrderPayments()
```

Get a collection of order payments



* Visibility: **public**
* Source: [classes/order/Order.php line 1983](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1983)




### <a name="method-getOrderSlipsCollection"></a>getOrderSlipsCollection

```php
\PrestaShopCollection OrderCore::getOrderSlipsCollection()
```

Get all order_slips for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1664](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1664)




### <a name="method-getOrdersIdByDate"></a>getOrdersIdByDate

```php
mixed OrderCore::getOrdersIdByDate($date_from, $date_to, $id_customer, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L870)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### <a name="method-getOrdersIdInvoiceByDate"></a>getOrdersIdInvoiceByDate

```php
array OrderCore::getOrdersIdInvoiceByDate($date_from, $date_to, $id_customer, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 918](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L918)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### <a name="method-getOrdersTotalPaid"></a>getOrdersTotalPaid

```php
float OrderCore::getOrdersTotalPaid()
```

Get the sum of total_paid_tax_incl of the orders with similar reference



* Visibility: **public**
* Source: [classes/order/Order.php line 1750](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1750)




### <a name="method-getOrdersWithInformations"></a>getOrdersWithInformations

```php
mixed OrderCore::getOrdersWithInformations($limit, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 886](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L886)


#### Arguments
* $limit **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getPreviousOrderId"></a>getPreviousOrderId

```php
integer OrderCore::getPreviousOrderId()
```

This method return the ID of the previous order



* Visibility: **public**
* Source: [classes/order/Order.php line 1468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1468)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

```php
array OrderCore::getProductTaxesBreakdown()
```

Returns the correct product taxes breakdown.



* Visibility: **public**
* Source: [classes/order/Order.php line 1789](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1789)




### <a name="method-getProducts"></a>getProducts

```php
array OrderCore::getProducts($products, $selectedProducts, $selectedQty)
```

Get order products



* Visibility: **public**
* Source: [classes/order/Order.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L561)


#### Arguments
* $products **mixed**
* $selectedProducts **mixed**
* $selectedQty **mixed**



### <a name="method-getProductsDetail"></a>getProductsDetail

```php
mixed OrderCore::getProductsDetail()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L509)




### <a name="method-getReturn"></a>getReturn

```php
mixed OrderCore::getReturn()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1631](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1631)




### <a name="method-getShipping"></a>getShipping

```php
array OrderCore::getShipping()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1640](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1640)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

```php
array OrderCore::getShippingTaxesBreakdown()
```

Returns the shipping taxes breakdown



* Visibility: **public**
* Source: [classes/order/Order.php line 1848](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1848)




### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

```php
mixed OrderCore::getTaxCalculationMethod()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L303)




### <a name="method-getTaxesAverageUsed"></a>getTaxesAverageUsed

```php
mixed OrderCore::getTaxesAverageUsed()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 680](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L680)




### <a name="method-getTotalPaid"></a>getTotalPaid

```php
float OrderCore::getTotalPaid(\Currency $currency)
```

Get total paid



* Visibility: **public**
* Source: [classes/order/Order.php line 1719](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1719)


#### Arguments
* $currency **[Currency](class.CurrencyCore.md)** - currency used for the total paid of the current order



### <a name="method-getTotalProductsWithTaxes"></a>getTotalProductsWithTaxes

```php
\Product OrderCore::getTotalProductsWithTaxes($products)
```

Get product total with taxes



* Visibility: **public**
* Source: [classes/order/Order.php line 974](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L974)


#### Arguments
* $products **mixed**



### <a name="method-getTotalProductsWithoutTaxes"></a>getTotalProductsWithoutTaxes

```php
\Product OrderCore::getTotalProductsWithoutTaxes($products)
```

Get product total without taxes



* Visibility: **public**
* Source: [classes/order/Order.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L964)


#### Arguments
* $products **mixed**



### <a name="method-getTotalWeight"></a>getTotalWeight

```php
mixed OrderCore::getTotalWeight()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1349)




### <a name="method-getUniqReference"></a>getUniqReference

```php
mixed OrderCore::getUniqReference()
```

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**
* Source: [classes/order/Order.php line 1996](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1996)




### <a name="method-getUniqReferenceOf"></a>getUniqReferenceOf

```php
mixed OrderCore::getUniqReferenceOf($id_order)
```

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 2019](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L2019)


#### Arguments
* $id_order **mixed**



### <a name="method-getVirtualProducts"></a>getVirtualProducts

```php
integer OrderCore::getVirtualProducts()
```

Count virtual products in order



* Visibility: **public**
* Source: [classes/order/Order.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L690)




### <a name="method-getWarehouseList"></a>getWarehouseList

```php
mixed OrderCore::getWarehouseList()
```

Get warehouse associated to the order

return array List of warehouse

* Visibility: **public**
* Source: [classes/order/Order.php line 1928](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1928)




### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed OrderCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1959](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1959)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWrappingTaxesBreakdown"></a>getWrappingTaxesBreakdown

```php
array OrderCore::getWrappingTaxesBreakdown()
```

Returns the wrapping taxes breakdown



* Visibility: **public**
* Source: [classes/order/Order.php line 1870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1870)




### <a name="method-getWsCurrentState"></a>getWsCurrentState

```php
mixed OrderCore::getWsCurrentState($state)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2078](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L2078)


#### Arguments
* $state **mixed**



### <a name="method-getWsOrderRows"></a>getWsOrderRows

```php
mixed OrderCore::getWsOrderRows()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1400](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1400)




### <a name="method-getWsShippingNumber"></a>getWsShippingNumber

```php
mixed OrderCore::getWsShippingNumber()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2047](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L2047)




### <a name="method-hasBeenDelivered"></a>hasBeenDelivered

```php
mixed OrderCore::hasBeenDelivered()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 783](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L783)




### <a name="method-hasBeenPaid"></a>hasBeenPaid

```php
mixed OrderCore::hasBeenPaid()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 803](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L803)




### <a name="method-hasBeenShipped"></a>hasBeenShipped

```php
mixed OrderCore::hasBeenShipped()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L808)




### <a name="method-hasDelivery"></a>hasDelivery

```php
boolean OrderCore::hasDelivery()
```

Has Delivery return true if this order has already a delivery slip



* Visibility: **public**
* Source: [classes/order/Order.php line 1912](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1912)




### <a name="method-hasInvoice"></a>hasInvoice

```php
boolean OrderCore::hasInvoice()
```

Has invoice return true if this order has already an invoice



* Visibility: **public**
* Source: [classes/order/Order.php line 1896](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1896)




### <a name="method-hasProductReturned"></a>hasProductReturned

```php
mixed OrderCore::hasProductReturned()
```

Has products returned by the merchant or by the customer?



* Visibility: **public**
* Source: [classes/order/Order.php line 791](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L791)




### <a name="method-isAssociatedAtGuest"></a>isAssociatedAtGuest

```php
mixed OrderCore::isAssociatedAtGuest($email)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1372](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1372)


#### Arguments
* $email **mixed**



### <a name="method-isInPreparation"></a>isInPreparation

```php
mixed OrderCore::isInPreparation()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 813](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L813)




### <a name="method-isPaidAndShipped"></a>isPaidAndShipped

```php
boolean OrderCore::isPaidAndShipped()
```

Checks if the current order status is paid and shipped



* Visibility: **public**
* Source: [classes/order/Order.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L823)




### <a name="method-isReturnable"></a>isReturnable

```php
boolean OrderCore::isReturnable()
```

Can this order be returned by the client?



* Visibility: **public**
* Source: [classes/order/Order.php line 1101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1101)




### <a name="method-isVirtual"></a>isVirtual

```php
boolean OrderCore::isVirtual(boolean $strict)
```

Check if order contains (only) virtual products



* Visibility: **public**
* Source: [classes/order/Order.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L707)


#### Arguments
* $strict **boolean** - If false return true if there are at least one product virtual



### <a name="method-orderContainProduct"></a>orderContainProduct

```php
mixed OrderCore::orderContainProduct($id_product)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1511](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1511)


#### Arguments
* $id_product **mixed**



### <a name="method-setCurrentState"></a>setCurrentState

```php
mixed OrderCore::setCurrentState(integer $id_order_state, integer $id_employee)
```

Set current order status



* Visibility: **public**
* Source: [classes/order/Order.php line 1426](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1426)


#### Arguments
* $id_order_state **integer**
* $id_employee **integer** - (/!\ not optional except for Webservice.



### <a name="method-setDelivery"></a>setDelivery

```php
mixed OrderCore::setDelivery()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1299](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1299)




### <a name="method-setDeliveryNumber"></a>setDeliveryNumber

```php
mixed OrderCore::setDeliveryNumber($order_invoice_id, $id_shop)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1262](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1262)


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### <a name="method-setDeliverySlip"></a>setDeliverySlip

```php
mixed OrderCore::setDeliverySlip()
```

This method allows to generate first delivery slip of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1248](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1248)




### <a name="method-setInvoice"></a>setInvoice

```php
mixed OrderCore::setInvoice($use_existing_payment)
```

This method allows to generate first invoice of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1155)


#### Arguments
* $use_existing_payment **mixed**



### <a name="method-setLastInvoiceNumber"></a>setLastInvoiceNumber

```php
mixed OrderCore::setLastInvoiceNumber($order_invoice_id, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1117)


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### <a name="method-setProductCurrentStock"></a>setProductCurrentStock

```php
mixed OrderCore::setProductCurrentStock($product)
```

This method allow to add stock information on a product detail

If advanced stock management is active, get physical stock of this product in the warehouse associated to the ptoduct for the current order
Else get the available quantity of the product in fucntion of the shop associated to the order

* Visibility: **protected**
* Source: [classes/order/Order.php line 641](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L641)


#### Arguments
* $product **mixed**



### <a name="method-setProductCustomizedDatas"></a>setProductCustomizedDatas

```php
mixed OrderCore::setProductCustomizedDatas($product, $customized_datas)
```





* Visibility: **protected**
* Source: [classes/order/Order.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L623)


#### Arguments
* $product **mixed**
* $customized_datas **mixed**



### <a name="method-setProductImageInformations"></a>setProductImageInformations

```php
mixed OrderCore::setProductImageInformations($product)
```

This method allow to add image information on a product detail



* Visibility: **protected**
* Source: [classes/order/Order.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L656)


#### Arguments
* $product **mixed**



### <a name="method-setProductPrices"></a>setProductPrices

```php
mixed OrderCore::setProductPrices($row)
```

Marked as deprecated but should not throw any "deprecated" message
This function is used in order to keep front office backward compatibility 14 -> 1.5
(Order History)



* Visibility: **public**
* Source: [classes/order/Order.php line 536](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L536)


#### Arguments
* $row **mixed**



### <a name="method-setWsCurrentState"></a>setWsCurrentState

```php
mixed OrderCore::setWsCurrentState($state)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2083](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L2083)


#### Arguments
* $state **mixed**



### <a name="method-setWsShippingNumber"></a>setWsShippingNumber

```php
mixed OrderCore::setWsShippingNumber($shipping_number)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2061](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L2061)


#### Arguments
* $shipping_number **mixed**



### <a name="method-sortDocuments"></a>sortDocuments

```php
mixed OrderCore::sortDocuments($a, $b)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 2040](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L2040)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-updateShippingCost"></a>updateShippingCost

```php
boolean OrderCore::updateShippingCost(float $amount)
```

This method allows to change the shipping cost of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1767)


#### Arguments
* $amount **float**



### <a name="method-useOneAfterAnotherTaxComputationMethod"></a>useOneAfterAnotherTaxComputationMethod

```php
boolean OrderCore::useOneAfterAnotherTaxComputationMethod()
```

This method returns true if at least one order details uses the
One After Another tax computation method.



* Visibility: **public**
* Source: [classes/order/Order.php line 1526](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/order/Order.php#L1526)



