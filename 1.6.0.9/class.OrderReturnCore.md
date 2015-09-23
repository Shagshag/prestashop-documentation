Class OrderReturnCore
=====================





* Class name: OrderReturnCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderReturn.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_customer](#property-$id_customer)
* [$id_order](#property-$id_order)
* [$question](#property-$question)
* [$state](#property-$state)

### Methods

* [addReturnDetail](#method-addReturnDetail)
* [addReturnedQuantity](#method-addReturnedQuantity)
* [checkEnoughProduct](#method-checkEnoughProduct)
* [countProduct](#method-countProduct)
* [deleteOrderReturnDetail](#method-deleteOrderReturnDetail)
* [getOrdersReturn](#method-getOrdersReturn)
* [getOrdersReturnDetail](#method-getOrdersReturnDetail)
* [getOrdersReturnProducts](#method-getOrdersReturnProducts)
* [getProductReturnDetail](#method-getProductReturnDetail)
* [getReturnedCustomizedProducts](#method-getReturnedCustomizedProducts)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L45).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L48).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_return', 'primary' => 'id_order_return', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'question' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml'), 'state' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderReturn.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L53).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L30).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L33).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L36).


### <a name="property-$question"></a>$question

```php
public string $question
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L42).


### <a name="property-$state"></a>$state

```php
public integer $state
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L39).


Methods
-------


### <a name="method-addReturnDetail"></a>addReturnDetail

```php
mixed OrderReturnCore::addReturnDetail($orderDetailList, $productQtyList, $customizationIds, $customizationQtyInput)
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L66)


#### Arguments
* $orderDetailList **mixed**
* $productQtyList **mixed**
* $customizationIds **mixed**
* $customizationQtyInput **mixed**



### <a name="method-addReturnedQuantity"></a>addReturnedQuantity

```php
mixed OrderReturnCore::addReturnedQuantity(array $products, integer $id_order)
```

Add returned quantity to products list



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L228)


#### Arguments
* $products **array**
* $id_order **integer**



### <a name="method-checkEnoughProduct"></a>checkEnoughProduct

```php
mixed OrderReturnCore::checkEnoughProduct($orderDetailList, $productQtyList, $customizationIds, $customizationQtyInput)
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L81)


#### Arguments
* $orderDetailList **mixed**
* $productQtyList **mixed**
* $customizationIds **mixed**
* $customizationQtyInput **mixed**



### <a name="method-countProduct"></a>countProduct

```php
mixed OrderReturnCore::countProduct()
```





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L119)




### <a name="method-deleteOrderReturnDetail"></a>deleteOrderReturnDetail

```php
mixed OrderReturnCore::deleteOrderReturnDetail($id_order_return, $id_order_detail, $id_customization)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L200)


#### Arguments
* $id_order_return **mixed**
* $id_order_detail **mixed**
* $id_customization **mixed**



### <a name="method-getOrdersReturn"></a>getOrdersReturn

```php
mixed OrderReturnCore::getOrdersReturn($customer_id, $order_id, $no_denied, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L129)


#### Arguments
* $customer_id **mixed**
* $order_id **mixed**
* $no_denied **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getOrdersReturnDetail"></a>getOrdersReturnDetail

```php
mixed OrderReturnCore::getOrdersReturnDetail($id_order_return)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L152)


#### Arguments
* $id_order_return **mixed**



### <a name="method-getOrdersReturnProducts"></a>getOrdersReturnProducts

```php
mixed OrderReturnCore::getOrdersReturnProducts($orderReturnId, $order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L160)


#### Arguments
* $orderReturnId **mixed**
* $order **mixed**



### <a name="method-getProductReturnDetail"></a>getProductReturnDetail

```php
mixed OrderReturnCore::getProductReturnDetail($id_order_detail)
```

Get return details for one product line



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L210)


#### Arguments
* $id_order_detail **mixed**



### <a name="method-getReturnedCustomizedProducts"></a>getReturnedCustomizedProducts

```php
mixed OrderReturnCore::getReturnedCustomizedProducts($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/order/OrderReturn.php#L181)


#### Arguments
* $id_order **mixed**


