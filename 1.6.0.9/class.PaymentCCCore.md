Class PaymentCCCore
=====================





* Class name: PaymentCCCore
* Parent class: [OrderPayment](class.OrderPaymentCore.md)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L33)


Contents
--------


### Properties

* [$amount](#property-$amount)
* [$card_brand](#property-$card_brand)
* [$card_expiration](#property-$card_expiration)
* [$card_holder](#property-$card_holder)
* [$card_number](#property-$card_number)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$id_currency](#property-$id_currency)
* [$id_order](#property-$id_order)
* [$transaction_id](#property-$transaction_id)

### Methods

* [add](#method-add)
* [getByOrderId](#method-getByOrderId)




Properties
----------


### <a name="property-$amount"></a>$amount

```php
public mixed $amount
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L37).


### <a name="property-$card_brand"></a>$card_brand

```php
public mixed $card_brand
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L40).


### <a name="property-$card_expiration"></a>$card_expiration

```php
public mixed $card_expiration
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L41).


### <a name="property-$card_holder"></a>$card_holder

```php
public mixed $card_holder
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L42).


### <a name="property-$card_number"></a>$card_number

```php
public mixed $card_number
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L39).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L43).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'payment_cc', 'primary' => 'id_payment_cc')
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* Source: [classes/PaymentCC.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L51).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('id_currency', 'amount')
```





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L45).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('transaction_id' => 254, 'card_number' => 254, 'card_brand' => 254, 'card_expiration' => 254, 'card_holder' => 254)
```





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L46).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('id_order' => 'isUnsignedId', 'id_currency' => 'isUnsignedId', 'amount' => 'isPrice', 'transaction_id' => 'isAnything', 'card_number' => 'isAnything', 'card_brand' => 'isAnything', 'card_expiration' => 'isAnything', 'card_holder' => 'isAnything')
```





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L47).


### <a name="property-$id_currency"></a>$id_currency

```php
public mixed $id_currency
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L36).


### <a name="property-$id_order"></a>$id_order

```php
public mixed $id_order
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L35).


### <a name="property-$transaction_id"></a>$transaction_id

```php
public mixed $transaction_id
```





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L38).


Methods
-------


### <a name="method-add"></a>add

```php
mixed PaymentCCCore::add($autodate, $nullValues)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L61)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-getByOrderId"></a>getByOrderId

```php
array PaymentCCCore::getByOrderId(integer $id_order)
```

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/PaymentCC.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/PaymentCC.php#L74)


#### Arguments
* $id_order **integer**


