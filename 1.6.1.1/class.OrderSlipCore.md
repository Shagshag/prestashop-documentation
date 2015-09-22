Class OrderSlipCore
=====================





* Class name: OrderSlipCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/order/OrderSlip.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L27)



Properties
----------

* [$amount](#property-$amount)
* [$conversion_rate](#property-$conversion_rate)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_customer](#property-$id_customer)
* [$id_order](#property-$id_order)
* [$order_slip_type](#property-$order_slip_type)
* [$partial](#property-$partial)
* [$shipping_cost](#property-$shipping_cost)
* [$shipping_cost_amount](#property-$shipping_cost_amount)
* [$total_products_tax_excl](#property-$total_products_tax_excl)
* [$total_products_tax_incl](#property-$total_products_tax_incl)
* [$total_shipping_tax_excl](#property-$total_shipping_tax_excl)
* [$total_shipping_tax_incl](#property-$total_shipping_tax_incl)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [addPartialSlipDetail](#method-addPartialSlipDetail)
* [addProductOrderSlip](#method-addProductOrderSlip)
* [addSlipDetail](#method-addSlipDetail)
* [create](#method-create)
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

    public integer $amount





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L54)


### <a name="property-$conversion_rate"></a>$conversion_rate

    public float $conversion_rate





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L39)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L66)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L69)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'order_slip', 'primary' => 'id_order_slip', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_products_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_products_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'shipping_cost' => array('type' => self::TYPE_INT), 'shipping_cost_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'partial' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'order_slip_type' => array('type' => self::TYPE_INT, 'validate' => 'isInt')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderSlip.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L77)


### <a name="property-$id"></a>$id

    public integer $id





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L30)


### <a name="property-$id_customer"></a>$id_customer

    public integer $id_customer





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L33)


### <a name="property-$id_order"></a>$id_order

    public integer $id_order





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L36)


### <a name="property-$order_slip_type"></a>$order_slip_type

    public integer $order_slip_type





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L72)


### <a name="property-$partial"></a>$partial

    public integer $partial





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L63)


### <a name="property-$shipping_cost"></a>$shipping_cost

    public integer $shipping_cost





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L57)


### <a name="property-$shipping_cost_amount"></a>$shipping_cost_amount

    public integer $shipping_cost_amount





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L60)


### <a name="property-$total_products_tax_excl"></a>$total_products_tax_excl

    public float $total_products_tax_excl





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L42)


### <a name="property-$total_products_tax_incl"></a>$total_products_tax_incl

    public float $total_products_tax_incl





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L45)


### <a name="property-$total_shipping_tax_excl"></a>$total_shipping_tax_excl

    public float $total_shipping_tax_excl





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L48)


### <a name="property-$total_shipping_tax_incl"></a>$total_shipping_tax_incl

    public float $total_shipping_tax_incl





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L51)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'order_slip', 'objectsNodeName' => 'order_slips', 'fields' => array('id_customer' => array('xlink_resource' => 'customers'), 'id_order' => array('xlink_resource' => 'orders')), 'associations' => array('order_slip_details' => array('resource' => 'order_slip_detail', 'setter' => false, 'virtual_entity' => true, 'fields' => array('id' => array(), 'id_order_detail' => array('required' => true), 'product_quantity' => array('required' => true), 'amount_tax_excl' => array('required' => true), 'amount_tax_incl' => array('required' => true)))))





* Visibility: **protected**
* Source: [classes/order/OrderSlip.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L98)


Methods
-------


### <a name="method-addPartialSlipDetail"></a>addPartialSlipDetail

    mixed OrderSlipCore::addPartialSlipDetail($order_detail_list)





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L440)


#### Arguments
* $order_detail_list **mixed**



### <a name="method-addProductOrderSlip"></a>addProductOrderSlip

    mixed OrderSlipCore::addProductOrderSlip($product)





* Visibility: **protected**
* Source: [classes/order/OrderSlip.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L406)


#### Arguments
* $product **mixed**



### <a name="method-addSlipDetail"></a>addSlipDetail

    mixed OrderSlipCore::addSlipDetail($orderDetailList, $productQtyList)





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L117)


#### Arguments
* $orderDetailList **mixed**
* $productQtyList **mixed**



### <a name="method-create"></a>create

    mixed OrderSlipCore::create(\Order $order, $product_list, $shipping_cost, $amount, $amount_choosen, $add_tax)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L267)


#### Arguments
* $order **[Order](class.OrderCore)**
* $product_list **mixed**
* $shipping_cost **mixed**
* $amount **mixed**
* $amount_choosen **mixed**
* $add_tax **mixed**



### <a name="method-createOrderSlip"></a>createOrderSlip

    mixed OrderSlipCore::createOrderSlip($order, $productList, $qtyList, $shipping_cost)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L247)


#### Arguments
* $order **mixed**
* $productList **mixed**
* $qtyList **mixed**
* $shipping_cost **mixed**



### <a name="method-createPartialOrderSlip"></a>createPartialOrderSlip

    mixed OrderSlipCore::createPartialOrderSlip($order, $amount, $shipping_cost_amount, $order_detail_list)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L421)


#### Arguments
* $order **mixed**
* $amount **mixed**
* $shipping_cost_amount **mixed**
* $order_detail_list **mixed**



### <a name="method-getEcoTaxTaxesBreakdown"></a>getEcoTaxTaxesBreakdown

    mixed OrderSlipCore::getEcoTaxTaxesBreakdown()





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 496](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L496)




### <a name="method-getOrdersSlip"></a>getOrdersSlip

    mixed OrderSlipCore::getOrdersSlip($customer_id, $order_id)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L136)


#### Arguments
* $customer_id **mixed**
* $order_id **mixed**



### <a name="method-getOrdersSlipDetail"></a>getOrdersSlipDetail

    mixed OrderSlipCore::getOrdersSlipDetail($id_order_slip, $id_order_detail)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L146)


#### Arguments
* $id_order_slip **mixed**
* $id_order_detail **mixed**



### <a name="method-getOrdersSlipProducts"></a>getOrdersSlipProducts

    array OrderSlipCore::getOrdersSlipProducts(integer $orderSlipId, \Order $order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L160)


#### Arguments
* $orderSlipId **integer**
* $order **[Order](class.OrderCore)**



### <a name="method-getProductSlipDetail"></a>getProductSlipDetail

    mixed OrderSlipCore::getProductSlipDetail($id_order_detail)

Get refund details for one product line



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L199)


#### Arguments
* $id_order_detail **mixed**



### <a name="method-getProductSlipResume"></a>getProductSlipResume

    mixed OrderSlipCore::getProductSlipResume($id_order_detail)

Get resume of all refund for one product line



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L186)


#### Arguments
* $id_order_detail **mixed**



### <a name="method-getProducts"></a>getProducts

    mixed OrderSlipCore::getProducts()





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L209)




### <a name="method-getSlipsIdByDate"></a>getSlipsIdByDate

    mixed OrderSlipCore::getSlipsIdByDate($dateFrom, $dateTo)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderSlip.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L226)


#### Arguments
* $dateFrom **mixed**
* $dateTo **mixed**



### <a name="method-getWsOrderSlipDetails"></a>getWsOrderSlipDetails

    mixed OrderSlipCore::getWsOrderSlipDetails()





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 517](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L517)




### <a name="method-setWsOrderSlipDetails"></a>setWsOrderSlipDetails

    mixed OrderSlipCore::setWsOrderSlipDetails($values)





* Visibility: **public**
* Source: [classes/order/OrderSlip.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderSlip.php#L526)


#### Arguments
* $values **mixed**


