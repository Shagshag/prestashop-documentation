Class OrderReturnCore
=====================





* Class name: OrderReturnCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderReturn.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L27)



Properties
----------

* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_customer](#property-$id_customer)
* [$id_order](#property-$id_order)
* [$question](#property-$question)
* [$state](#property-$state)

Methods
-------
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

    public string $date_add





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L45).


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L48).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'order_return', 'primary' => 'id_order_return', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'question' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml'), 'state' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderReturn.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L53).


### <a name="property-$id"></a>$id

    public integer $id





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L30).


### <a name="property-$id_customer"></a>$id_customer

    public integer $id_customer





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L33).


### <a name="property-$id_order"></a>$id_order

    public integer $id_order





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L36).


### <a name="property-$question"></a>$question

    public string $question





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L42).


### <a name="property-$state"></a>$state

    public integer $state





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L39).


Methods
-------


### <a name="method-addReturnDetail"></a>addReturnDetail

    mixed OrderReturnCore::addReturnDetail($order_detail_list, $product_qty_list, $customization_ids, $customization_qty_input)





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L66)


#### Arguments
* $order_detail_list **mixed**
* $product_qty_list **mixed**
* $customization_ids **mixed**
* $customization_qty_input **mixed**



### <a name="method-addReturnedQuantity"></a>addReturnedQuantity

    mixed OrderReturnCore::addReturnedQuantity(array $products, integer $id_order)

Add returned quantity to products list



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L246)


#### Arguments
* $products **array**
* $id_order **integer**



### <a name="method-checkEnoughProduct"></a>checkEnoughProduct

    mixed OrderReturnCore::checkEnoughProduct($order_detail_list, $product_qty_list, $customization_ids, $customization_qty_input)





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L88)


#### Arguments
* $order_detail_list **mixed**
* $product_qty_list **mixed**
* $customization_ids **mixed**
* $customization_qty_input **mixed**



### <a name="method-countProduct"></a>countProduct

    mixed OrderReturnCore::countProduct()





* Visibility: **public**
* Source: [classes/order/OrderReturn.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L132)




### <a name="method-deleteOrderReturnDetail"></a>deleteOrderReturnDetail

    mixed OrderReturnCore::deleteOrderReturnDetail($id_order_return, $id_order_detail, $id_customization)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L218)


#### Arguments
* $id_order_return **mixed**
* $id_order_detail **mixed**
* $id_customization **mixed**



### <a name="method-getOrdersReturn"></a>getOrdersReturn

    mixed OrderReturnCore::getOrdersReturn($customer_id, $order_id, $no_denied, \Context $context)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L143)


#### Arguments
* $customer_id **mixed**
* $order_id **mixed**
* $no_denied **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getOrdersReturnDetail"></a>getOrdersReturnDetail

    mixed OrderReturnCore::getOrdersReturnDetail($id_order_return)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L166)


#### Arguments
* $id_order_return **mixed**



### <a name="method-getOrdersReturnProducts"></a>getOrdersReturnProducts

    array OrderReturnCore::getOrdersReturnProducts(integer $order_return_id, \Order $order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L179)


#### Arguments
* $order_return_id **integer**
* $order **[Order](class.OrderCore.md)**



### <a name="method-getProductReturnDetail"></a>getProductReturnDetail

    mixed OrderReturnCore::getProductReturnDetail($id_order_detail)

Get return details for one product line



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L228)


#### Arguments
* $id_order_detail **mixed**



### <a name="method-getReturnedCustomizedProducts"></a>getReturnedCustomizedProducts

    mixed OrderReturnCore::getReturnedCustomizedProducts($id_order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturn.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderReturn.php#L199)


#### Arguments
* $id_order **mixed**


