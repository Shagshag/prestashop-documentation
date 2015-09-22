Class OrderStateCore
=====================





* Class name: OrderStateCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderState.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L27)


Contents
--------

### Constants

* [FLAG_DELIVERY](#constant-FLAG_DELIVERY)
* [FLAG_LOGABLE](#constant-FLAG_LOGABLE)
* [FLAG_NO_HIDDEN](#constant-FLAG_NO_HIDDEN)
* [FLAG_PAID](#constant-FLAG_PAID)
* [FLAG_SHIPPED](#constant-FLAG_SHIPPED)

### Properties

* [$color](#property-$color)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$delivery](#property-$delivery)
* [$hidden](#property-$hidden)
* [$invoice](#property-$invoice)
* [$logable](#property-$logable)
* [$module_name](#property-$module_name)
* [$name](#property-$name)
* [$paid](#property-$paid)
* [$pdf_delivery](#property-$pdf_delivery)
* [$pdf_invoice](#property-$pdf_invoice)
* [$send_email](#property-$send_email)
* [$shipped](#property-$shipped)
* [$template](#property-$template)
* [$unremovable](#property-$unremovable)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [getOrderStates](#method-getOrderStates)
* [invoiceAvailable](#method-invoiceAvailable)
* [isRemovable](#method-isRemovable)


Constants
----------


### <a name="constant-FLAG_DELIVERY"></a>FLAG_DELIVERY

```php
const FLAG_DELIVERY = 4
```





* Source: [classes/order/OrderState.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L110).


### <a name="constant-FLAG_LOGABLE"></a>FLAG_LOGABLE

```php
const FLAG_LOGABLE = 2
```





* Source: [classes/order/OrderState.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L109).


### <a name="constant-FLAG_NO_HIDDEN"></a>FLAG_NO_HIDDEN

```php
const FLAG_NO_HIDDEN = 1
```





* Source: [classes/order/OrderState.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L108).


### <a name="constant-FLAG_PAID"></a>FLAG_PAID

```php
const FLAG_PAID = 16
```





* Source: [classes/order/OrderState.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L112).


### <a name="constant-FLAG_SHIPPED"></a>FLAG_SHIPPED

```php
const FLAG_SHIPPED = 8
```





* Source: [classes/order/OrderState.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L111).


Properties
----------


### <a name="property-$color"></a>$color

```php
public string $color
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L44).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_state', 'primary' => 'id_order_state', 'multilang' => true, 'fields' => array('send_email' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'module_name' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName'), 'invoice' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'logable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipped' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'unremovable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delivery' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'hidden' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'paid' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pdf_delivery' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pdf_invoice' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'template' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isTplName', 'size' => 64)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderState.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L75).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L70).


### <a name="property-$delivery"></a>$delivery

```php
public boolean $delivery
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L52).


### <a name="property-$hidden"></a>$hidden

```php
public boolean $hidden
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L55).


### <a name="property-$invoice"></a>$invoice

```php
public boolean $invoice
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L41).


### <a name="property-$logable"></a>$logable

```php
public boolean $logable
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L49).


### <a name="property-$module_name"></a>$module_name

```php
public mixed $module_name
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L38).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L30).


### <a name="property-$paid"></a>$paid

```php
public boolean $paid
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L61).


### <a name="property-$pdf_delivery"></a>$pdf_delivery

```php
public boolean $pdf_delivery
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L67).


### <a name="property-$pdf_invoice"></a>$pdf_invoice

```php
public boolean $pdf_invoice
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L64).


### <a name="property-$send_email"></a>$send_email

```php
public boolean $send_email
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L36).


### <a name="property-$shipped"></a>$shipped

```php
public boolean $shipped
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L58).


### <a name="property-$template"></a>$template

```php
public string $template
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L33).


### <a name="property-$unremovable"></a>$unremovable

```php
public mixed $unremovable
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L46).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('unremovable' => array(), 'delivery' => array(), 'hidden' => array()))
```





* Visibility: **protected**
* Source: [classes/order/OrderState.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L100).


Methods
-------


### <a name="method-getOrderStates"></a>getOrderStates

```php
array OrderStateCore::getOrderStates(integer $id_lang)
```

Get all available order statuses



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderState.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L120)


#### Arguments
* $id_lang **integer** - Language id for status name



### <a name="method-invoiceAvailable"></a>invoiceAvailable

```php
boolean OrderStateCore::invoiceAvailable(integer $id_order_state)
```

Check if we can make a invoice when order is in this state



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderState.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L142)


#### Arguments
* $id_order_state **integer** - State ID



### <a name="method-isRemovable"></a>isRemovable

```php
mixed OrderStateCore::isRemovable()
```





* Visibility: **public**
* Source: [classes/order/OrderState.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderState.php#L154)



