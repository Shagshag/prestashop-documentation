Class OrderSlipCore
=====================





* Class name: OrderSlipCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderSlip.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L27)


Contents
--------


### Properties

* [$amount](#property-$amount)
* [$conversion_rate](#property-$conversion_rate)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_customer](#property-$id_customer)
* [$id_order](#property-$id_order)
* [$partial](#property-$partial)
* [$shipping_cost](#property-$shipping_cost)
* [$shipping_cost_amount](#property-$shipping_cost_amount)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [addPartialSlipDetail](#method-addPartialSlipDetail)
* [addSlipDetail](#method-addSlipDetail)
* [createOrderSlip](#method-createOrderSlip)
* [createPartialOrderSlip](#method-createPartialOrderSlip)
* [getEcoTaxTaxesBreakdown](#method-getEcoTaxTaxesBreakdown)
* [getOrdersSlip](#method-getOrdersSlip)
* [getOrdersSlipDetail](#method-getOrdersSlipDetail)
* [getOrdersSlipProducts](#method-getOrdersSlipProducts)
* [getProductSlipDetail](#method-getProductSlipDetail)
* [getProductSlipResume](#method-getProductSlipResume)
* [getProducts](#method-getProducts)
* [getSlipsIdByDate](#method-getSlipsIdByDate)
* [getWsOrderSlipDetails](#method-getWsOrderSlipDetails)
* [setWsOrderSlipDetails](#method-setWsOrderSlipDetails)




Properties
----------


### <a name="property-$amount"></a>$amount

```php
public integer $amount
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L42).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public float $conversion_rate
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L39).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L54).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L57).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_slip', 'primary' => 'id_order_slip', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'shipping_cost' => array('type' => self::TYPE_INT), 'shipping_cost_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'partial' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderSlip.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L62).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L30).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L33).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L36).


### <a name="property-$partial"></a>$partial

```php
public integer $partial
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L51).


### <a name="property-$shipping_cost"></a>$shipping_cost

```php
public integer $shipping_cost
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L45).


### <a name="property-$shipping_cost_amount"></a>$shipping_cost_amount

```php
public integer $shipping_cost_amount
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L48).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'order_slip', 'objectsNodeName' => 'order_slips', 'fields' => array('id_customer' => array('xlink_resource' => 'customers'), 'id_order' => array('xlink_resource' => 'orders')), 'associations' => array('order_slip_details' => array('resource' => 'order_slip_detail', 'setter' => false, 'virtual_entity' => true, 'fields' => array('id' => array(), 'id_order_detail' => array('required' => true), 'product_quantity' => array('required' => true), 'amount_tax_excl' => array('required' => true), 'amount_tax_incl' => array('required' => true)))))
```





* Visibility: **protected**
* Source: [classes/order/OrderSlip.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L78).


Methods
-------


### <a name="method-addPartialSlipDetail"></a>addPartialSlipDetail

```php
mixed OrderSlipCore::addPartialSlipDetail($order_detail_list)
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L259)


#### Arguments
* $order_detail_list **mixed**



### <a name="method-addSlipDetail"></a>addSlipDetail

```php
mixed OrderSlipCore::addSlipDetail($orderDetailList, $productQtyList)
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L97)


#### Arguments
* $orderDetailList **mixed**
* $productQtyList **mixed**



### <a name="method-createOrderSlip"></a>createOrderSlip

```php
mixed OrderSlipCore::createOrderSlip($order, $productList, $qtyList, $shipping_cost)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L215)


#### Arguments
* $order **mixed**
* $productList **mixed**
* $qtyList **mixed**
* $shipping_cost **mixed**



### <a name="method-createPartialOrderSlip"></a>createPartialOrderSlip

```php
mixed OrderSlipCore::createPartialOrderSlip($order, $amount, $shipping_cost_amount, $order_detail_list)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L241)


#### Arguments
* $order **mixed**
* $amount **mixed**
* $shipping_cost_amount **mixed**
* $order_detail_list **mixed**



### <a name="method-getEcoTaxTaxesBreakdown"></a>getEcoTaxTaxesBreakdown

```php
mixed OrderSlipCore::getEcoTaxTaxesBreakdown()
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L305)




### <a name="method-getOrdersSlip"></a>getOrdersSlip

```php
mixed OrderSlipCore::getOrdersSlip($customer_id, $order_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L117)


#### Arguments
* $customer_id **mixed**
* $order_id **mixed**



### <a name="method-getOrdersSlipDetail"></a>getOrdersSlipDetail

```php
mixed OrderSlipCore::getOrdersSlipDetail($id_order_slip, $id_order_detail)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L127)


#### Arguments
* $id_order_slip **mixed**
* $id_order_detail **mixed**



### <a name="method-getOrdersSlipProducts"></a>getOrdersSlipProducts

```php
mixed OrderSlipCore::getOrdersSlipProducts($orderSlipId, $order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L136)


#### Arguments
* $orderSlipId **mixed**
* $order **mixed**



### <a name="method-getProductSlipDetail"></a>getProductSlipDetail

```php
mixed OrderSlipCore::getProductSlipDetail($id_order_detail)
```

Get refund details for one product line



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L173)


#### Arguments
* $id_order_detail **mixed**



### <a name="method-getProductSlipResume"></a>getProductSlipResume

```php
mixed OrderSlipCore::getProductSlipResume($id_order_detail)
```

Get resume of all refund for one product line



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L160)


#### Arguments
* $id_order_detail **mixed**



### <a name="method-getProducts"></a>getProducts

```php
mixed OrderSlipCore::getProducts()
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L183)




### <a name="method-getSlipsIdByDate"></a>getSlipsIdByDate

```php
mixed OrderSlipCore::getSlipsIdByDate($dateFrom, $dateTo)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L201)


#### Arguments
* $dateFrom **mixed**
* $dateTo **mixed**



### <a name="method-getWsOrderSlipDetails"></a>getWsOrderSlipDetails

```php
mixed OrderSlipCore::getWsOrderSlipDetails()
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L326)




### <a name="method-setWsOrderSlipDetails"></a>setWsOrderSlipDetails

```php
mixed OrderSlipCore::setWsOrderSlipDetails($values)
```





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/order/OrderSlip.php#L335)


#### Arguments
* $values **mixed**


