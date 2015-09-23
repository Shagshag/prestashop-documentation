Class OrderHistoryCore
=====================





* Class name: OrderHistoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderHistory.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id_employee](#property-$id_employee)
* [$id_order](#property-$id_order)
* [$id_order_state](#property-$id_order_state)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [addWithemail](#method-addWithemail)
* [addWs](#method-addWs)
* [changeIdOrderState](#method-changeIdOrderState)
* [getLastOrderState](#method-getLastOrderState)
* [isValidated](#method-isValidated)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L39).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L42).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_history', 'primary' => 'id_order_history', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderHistory.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L47).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L36).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L30).


### <a name="property-$id_order_state"></a>$id_order_state

```php
public integer $id_order_state
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L33).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'order_histories', 'fields' => array('id_order_state' => array('required' => true, 'xlink_resource' => 'order_states'), 'id_order' => array('xlink_resource' => 'orders')), 'objectMethods' => array('add' => 'addWs'))
```





* Visibility: **protected**
* Source: [classes/order/OrderHistory.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L61).


Methods
-------


### <a name="method-add"></a>add

```php
mixed OrderHistoryCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L433)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addWithemail"></a>addWithemail

```php
boolean OrderHistoryCore::addWithemail(boolean $autodate, array $template_vars, \Context $context)
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L368)


#### Arguments
* $autodate **boolean** - Optional
* $template_vars **array** - Optional
* $context **[Context](class.ContextCore.md)** - Optional



### <a name="method-addWs"></a>addWs

```php
boolean OrderHistoryCore::addWs()
```

Add method for webservice create resource Order History
If sendemail=1 GET parameter is present sends email to customer otherwise does not



* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 466](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L466)




### <a name="method-changeIdOrderState"></a>changeIdOrderState

```php
mixed OrderHistoryCore::changeIdOrderState(integer $new_order_state, \int/object $id_order, boolean $use_existing_payment)
```

Sets the new state of the given order



* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L79)


#### Arguments
* $new_order_state **integer**
* $id_order **int/object**
* $use_existing_payment **boolean**



### <a name="method-getLastOrderState"></a>getLastOrderState

```php
\OrderState|boolean OrderHistoryCore::getLastOrderState(integer $id_order)
```

Returns the last order status



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderHistory.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L345)


#### Arguments
* $id_order **integer**



### <a name="method-isValidated"></a>isValidated

```php
integer OrderHistoryCore::isValidated()
```





* Visibility: **public**
* Source: [classes/order/OrderHistory.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderHistory.php#L451)



