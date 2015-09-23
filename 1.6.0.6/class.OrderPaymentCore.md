Class OrderPaymentCore
=====================





* Class name: OrderPaymentCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderPayment.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L27)


Contents
--------


### Properties

* [$amount](#property-$amount)
* [$card_brand](#property-$card_brand)
* [$card_expiration](#property-$card_expiration)
* [$card_holder](#property-$card_holder)
* [$card_number](#property-$card_number)
* [$conversion_rate](#property-$conversion_rate)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$id_currency](#property-$id_currency)
* [$order_reference](#property-$order_reference)
* [$payment_method](#property-$payment_method)
* [$transaction_id](#property-$transaction_id)

### Methods

* [add](#method-add)
* [getByInvoiceId](#method-getByInvoiceId)
* [getByOrderId](#method-getByOrderId)
* [getByOrderReference](#method-getByOrderReference)
* [getOrderInvoice](#method-getOrderInvoice)




Properties
----------


### <a name="property-$amount"></a>$amount

```php
public mixed $amount
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L31).


### <a name="property-$card_brand"></a>$card_brand

```php
public mixed $card_brand
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L36).


### <a name="property-$card_expiration"></a>$card_expiration

```php
public mixed $card_expiration
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L37).


### <a name="property-$card_holder"></a>$card_holder

```php
public mixed $card_holder
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L38).


### <a name="property-$card_number"></a>$card_number

```php
public mixed $card_number
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L35).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public mixed $conversion_rate
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L33).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L39).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_payment', 'primary' => 'id_order_payment', 'fields' => array('order_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 9), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isNegativePrice', 'required' => true), 'payment_method' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'transaction_id' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_number' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_brand' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_expiration' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_holder' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderPayment.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L44).


### <a name="property-$id_currency"></a>$id_currency

```php
public mixed $id_currency
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L30).


### <a name="property-$order_reference"></a>$order_reference

```php
public mixed $order_reference
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L29).


### <a name="property-$payment_method"></a>$payment_method

```php
public mixed $payment_method
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L32).


### <a name="property-$transaction_id"></a>$transaction_id

```php
public mixed $transaction_id
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L34).


Methods
-------


### <a name="method-add"></a>add

```php
mixed OrderPaymentCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L62)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-getByInvoiceId"></a>getByInvoiceId

```php
\PrestaShopCollection OrderPaymentCore::getByInvoiceId(integer $id_invoice)
```

Get Order Payments By Invoice ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderPayment.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L106)


#### Arguments
* $id_invoice **integer** - Invoice ID



### <a name="method-getByOrderId"></a>getByOrderId

```php
array OrderPaymentCore::getByOrderId(integer $id_order)
```

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderPayment.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L77)


#### Arguments
* $id_order **integer**



### <a name="method-getByOrderReference"></a>getByOrderReference

```php
array OrderPaymentCore::getByOrderReference(integer $order_reference)
```

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderPayment.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L90)


#### Arguments
* $order_reference **integer**



### <a name="method-getOrderInvoice"></a>getOrderInvoice

```php
mixed OrderPaymentCore::getOrderInvoice(integer $id_order)
```

Return order invoice object linked to the payment



* Visibility: **public**
* Source: [classes/order/OrderPayment.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/order/OrderPayment.php#L128)


#### Arguments
* $id_order **integer** - Order Id


