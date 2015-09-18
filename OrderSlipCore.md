OrderSlipCore
===============






* Class name: OrderSlipCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public integer $id





* Visibility: **public**


### $id_customer

    public integer $id_customer





* Visibility: **public**


### $id_order

    public integer $id_order





* Visibility: **public**


### $conversion_rate

    public float $conversion_rate





* Visibility: **public**


### $total_products_tax_excl

    public float $total_products_tax_excl





* Visibility: **public**


### $total_products_tax_incl

    public float $total_products_tax_incl





* Visibility: **public**


### $total_shipping_tax_excl

    public float $total_shipping_tax_excl





* Visibility: **public**


### $total_shipping_tax_incl

    public float $total_shipping_tax_incl





* Visibility: **public**


### $amount

    public integer $amount





* Visibility: **public**


### $shipping_cost

    public integer $shipping_cost





* Visibility: **public**


### $shipping_cost_amount

    public integer $shipping_cost_amount





* Visibility: **public**


### $partial

    public integer $partial





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $order_slip_type

    public integer $order_slip_type





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_slip', 'primary' => 'id_order_slip', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_products_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_products_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'shipping_cost' => array('type' => self::TYPE_INT), 'shipping_cost_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'partial' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'order_slip_type' => array('type' => self::TYPE_INT, 'validate' => 'isInt')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'order_slip', 'objectsNodeName' => 'order_slips', 'fields' => array('id_customer' => array('xlink_resource' => 'customers'), 'id_order' => array('xlink_resource' => 'orders')), 'associations' => array('order_slip_details' => array('resource' => 'order_slip_detail', 'setter' => false, 'virtual_entity' => true, 'fields' => array('id' => array(), 'id_order_detail' => array('required' => true), 'product_quantity' => array('required' => true), 'amount_tax_excl' => array('required' => true), 'amount_tax_incl' => array('required' => true)))))





* Visibility: **protected**


Methods
-------


### addSlipDetail

    mixed OrderSlipCore::addSlipDetail($orderDetailList, $productQtyList)





* Visibility: **public**


#### Arguments
* $orderDetailList **mixed**
* $productQtyList **mixed**



### getOrdersSlip

    mixed OrderSlipCore::getOrdersSlip($customer_id, $order_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $customer_id **mixed**
* $order_id **mixed**



### getOrdersSlipDetail

    mixed OrderSlipCore::getOrdersSlipDetail($id_order_slip, $id_order_detail)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_slip **mixed**
* $id_order_detail **mixed**



### getOrdersSlipProducts

    array OrderSlipCore::getOrdersSlipProducts(integer $orderSlipId, \Order $order)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $orderSlipId **integer**
* $order **Order**



### getProductSlipResume

    mixed OrderSlipCore::getProductSlipResume($id_order_detail)

Get resume of all refund for one product line



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_detail **mixed**



### getProductSlipDetail

    mixed OrderSlipCore::getProductSlipDetail($id_order_detail)

Get refund details for one product line



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_detail **mixed**



### getProducts

    mixed OrderSlipCore::getProducts()





* Visibility: **public**




### getSlipsIdByDate

    mixed OrderSlipCore::getSlipsIdByDate($dateFrom, $dateTo)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dateFrom **mixed**
* $dateTo **mixed**



### createOrderSlip

    mixed OrderSlipCore::createOrderSlip($order, $productList, $qtyList, $shipping_cost)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $order **mixed**
* $productList **mixed**
* $qtyList **mixed**
* $shipping_cost **mixed**



### create

    mixed OrderSlipCore::create(\Order $order, $product_list, $shipping_cost, $amount, $amount_choosen, $add_tax)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $order **Order**
* $product_list **mixed**
* $shipping_cost **mixed**
* $amount **mixed**
* $amount_choosen **mixed**
* $add_tax **mixed**



### addProductOrderSlip

    mixed OrderSlipCore::addProductOrderSlip($product)





* Visibility: **protected**


#### Arguments
* $product **mixed**



### createPartialOrderSlip

    mixed OrderSlipCore::createPartialOrderSlip($order, $amount, $shipping_cost_amount, $order_detail_list)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $order **mixed**
* $amount **mixed**
* $shipping_cost_amount **mixed**
* $order_detail_list **mixed**



### addPartialSlipDetail

    mixed OrderSlipCore::addPartialSlipDetail($order_detail_list)





* Visibility: **public**


#### Arguments
* $order_detail_list **mixed**



### getEcoTaxTaxesBreakdown

    mixed OrderSlipCore::getEcoTaxTaxesBreakdown()





* Visibility: **public**




### getWsOrderSlipDetails

    mixed OrderSlipCore::getWsOrderSlipDetails()





* Visibility: **public**




### setWsOrderSlipDetails

    mixed OrderSlipCore::setWsOrderSlipDetails($values)





* Visibility: **public**


#### Arguments
* $values **mixed**


