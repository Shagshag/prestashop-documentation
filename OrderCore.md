OrderCore
===============






* Class name: OrderCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### ROUND_ITEM

    const ROUND_ITEM = 1





### ROUND_LINE

    const ROUND_LINE = 2





### ROUND_TOTAL

    const ROUND_TOTAL = 3





Properties
----------


### $id_address_delivery

    public integer $id_address_delivery





* Visibility: **public**


### $id_address_invoice

    public integer $id_address_invoice





* Visibility: **public**


### $id_shop_group

    public mixed $id_shop_group





* Visibility: **public**


### $id_shop

    public mixed $id_shop





* Visibility: **public**


### $id_cart

    public integer $id_cart





* Visibility: **public**


### $id_currency

    public integer $id_currency





* Visibility: **public**


### $id_lang

    public integer $id_lang





* Visibility: **public**


### $id_customer

    public integer $id_customer





* Visibility: **public**


### $id_carrier

    public integer $id_carrier





* Visibility: **public**


### $current_state

    public integer $current_state





* Visibility: **public**


### $secure_key

    public string $secure_key





* Visibility: **public**


### $payment

    public string $payment





* Visibility: **public**


### $module

    public string $module





* Visibility: **public**


### $conversion_rate

    public float $conversion_rate





* Visibility: **public**


### $recyclable

    public boolean $recyclable = 1





* Visibility: **public**


### $gift

    public boolean $gift





* Visibility: **public**


### $gift_message

    public string $gift_message





* Visibility: **public**


### $mobile_theme

    public boolean $mobile_theme





* Visibility: **public**


### $shipping_number

    public string $shipping_number





* Visibility: **public**


### $total_discounts

    public float $total_discounts





* Visibility: **public**


### $total_discounts_tax_incl

    public mixed $total_discounts_tax_incl





* Visibility: **public**


### $total_discounts_tax_excl

    public mixed $total_discounts_tax_excl





* Visibility: **public**


### $total_paid

    public float $total_paid





* Visibility: **public**


### $total_paid_tax_incl

    public float $total_paid_tax_incl





* Visibility: **public**


### $total_paid_tax_excl

    public float $total_paid_tax_excl





* Visibility: **public**


### $total_paid_real

    public float $total_paid_real





* Visibility: **public**


### $total_products

    public float $total_products





* Visibility: **public**


### $total_products_wt

    public float $total_products_wt





* Visibility: **public**


### $total_shipping

    public float $total_shipping





* Visibility: **public**


### $total_shipping_tax_incl

    public float $total_shipping_tax_incl





* Visibility: **public**


### $total_shipping_tax_excl

    public float $total_shipping_tax_excl





* Visibility: **public**


### $carrier_tax_rate

    public float $carrier_tax_rate





* Visibility: **public**


### $total_wrapping

    public float $total_wrapping





* Visibility: **public**


### $total_wrapping_tax_incl

    public float $total_wrapping_tax_incl





* Visibility: **public**


### $total_wrapping_tax_excl

    public float $total_wrapping_tax_excl





* Visibility: **public**


### $invoice_number

    public integer $invoice_number





* Visibility: **public**


### $delivery_number

    public integer $delivery_number





* Visibility: **public**


### $invoice_date

    public string $invoice_date





* Visibility: **public**


### $delivery_date

    public string $delivery_date





* Visibility: **public**


### $valid

    public boolean $valid





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $reference

    public string $reference





* Visibility: **public**


### $round_mode

    public integer $round_mode





* Visibility: **public**


### $round_type

    public integer $round_type





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'orders', 'primary' => 'id_order', 'fields' => array('id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'current_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5'), 'payment' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true), 'recyclable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift_message' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'total_discounts' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_paid_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_real' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products_wt' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_shipping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'carrier_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'total_wrapping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'round_mode' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'round_type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'shipping_number' => array('type' => self::TYPE_STRING, 'validate' => 'isTrackingNumber'), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'invoice_number' => array('type' => self::TYPE_INT), 'delivery_number' => array('type' => self::TYPE_INT), 'invoice_date' => array('type' => self::TYPE_DATE), 'delivery_date' => array('type' => self::TYPE_DATE), 'valid' => array('type' => self::TYPE_BOOL), 'reference' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs'), 'objectNodeName' => 'order', 'objectsNodeName' => 'orders', 'fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_cart' => array('xlink_resource' => 'carts'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_carrier' => array('xlink_resource' => 'carriers'), 'current_state' => array('xlink_resource' => 'order_states', 'setter' => 'setWsCurrentState'), 'module' => array('required' => true), 'invoice_number' => array(), 'invoice_date' => array(), 'delivery_number' => array(), 'delivery_date' => array(), 'valid' => array(), 'date_add' => array(), 'date_upd' => array(), 'shipping_number' => array('getter' => 'getWsShippingNumber', 'setter' => 'setWsShippingNumber')), 'associations' => array('order_rows' => array('resource' => 'order_row', 'setter' => false, 'virtual_entity' => true, 'fields' => array('id' => array(), 'product_id' => array('required' => true), 'product_attribute_id' => array('required' => true), 'product_quantity' => array('required' => true), 'product_name' => array('setter' => false), 'product_reference' => array('setter' => false), 'product_ean13' => array('setter' => false), 'product_upc' => array('setter' => false), 'product_price' => array('setter' => false), 'unit_price_tax_incl' => array('setter' => false), 'unit_price_tax_excl' => array('setter' => false)))))





* Visibility: **protected**


### $_taxCalculationMethod

    protected mixed $_taxCalculationMethod = PS_TAX_EXC





* Visibility: **protected**


### $_historyCache

    protected mixed $_historyCache = array()





* Visibility: **protected**
* This property is **static**.


### $cacheCustomer

    protected mixed $cacheCustomer = null

used to cache order customer



* Visibility: **protected**


Methods
-------


### __construct

    mixed OrderCore::__construct($id, $id_lang)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### getFields

    array OrderCore::getFields()





* Visibility: **public**




### add

    mixed OrderCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getTaxCalculationMethod

    mixed OrderCore::getTaxCalculationMethod()





* Visibility: **public**




### deleteProduct

    boolean OrderCore::deleteProduct($order, \OrderDetail $order_detail, integer $quantity)

Does NOT delete a product but "cancel" it (which means return/refund/delete it depending of the case)



* Visibility: **public**


#### Arguments
* $order **mixed**
* $order_detail **OrderDetail**
* $quantity **integer**



### getCartProducts

    array OrderCore::getCartProducts()

This function return products of the orders
It's similar to Order::getProducts but with similar outputs of Cart::getProducts



* Visibility: **public**




### _deleteProduct

    boolean OrderCore::_deleteProduct(\OrderDetail $order_detail, integer $quantity)

DOES delete the product



* Visibility: **protected**


#### Arguments
* $order_detail **OrderDetail**
* $quantity **integer**



### deleteCustomization

    mixed OrderCore::deleteCustomization($id_customization, $quantity, $order_detail)





* Visibility: **public**


#### Arguments
* $id_customization **mixed**
* $quantity **mixed**
* $order_detail **mixed**



### getHistory

    array OrderCore::getHistory(integer $id_lang, integer $id_order_state, integer $no_hidden, integer $filters)

Get order history



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_order_state **integer** - &lt;p&gt;Filter a specific order status&lt;/p&gt;
* $no_hidden **integer** - &lt;p&gt;Filter no hidden status&lt;/p&gt;
* $filters **integer** - &lt;p&gt;Flag to use specific field filter&lt;/p&gt;



### getProductsDetail

    mixed OrderCore::getProductsDetail()





* Visibility: **public**




### getFirstMessage

    mixed OrderCore::getFirstMessage()





* Visibility: **public**




### setProductPrices

    mixed OrderCore::setProductPrices($row)

Marked as deprecated but should not throw any "deprecated" message
This function is used in order to keep front office backward compatibility 14 -> 1.5
(Order History)



* Visibility: **public**


#### Arguments
* $row **mixed**



### getProducts

    array OrderCore::getProducts($products, $selected_products, $selected_qty)

Get order products



* Visibility: **public**


#### Arguments
* $products **mixed**
* $selected_products **mixed**
* $selected_qty **mixed**



### getIdOrderProduct

    mixed OrderCore::getIdOrderProduct($id_customer, $id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $id_product **mixed**



### setProductCustomizedDatas

    mixed OrderCore::setProductCustomizedDatas($product, $customized_datas)





* Visibility: **protected**


#### Arguments
* $product **mixed**
* $customized_datas **mixed**



### setProductCurrentStock

    mixed OrderCore::setProductCurrentStock($product)

This method allow to add stock information on a product detail

If advanced stock management is active, get physical stock of this product in the warehouse associated to the ptoduct for the current order
Else get the available quantity of the product in fucntion of the shop associated to the order

* Visibility: **protected**


#### Arguments
* $product **mixed**



### setProductImageInformations

    mixed OrderCore::setProductImageInformations($product)

This method allow to add image information on a product detail



* Visibility: **protected**


#### Arguments
* $product **mixed**



### getTaxesAverageUsed

    mixed OrderCore::getTaxesAverageUsed()





* Visibility: **public**




### getVirtualProducts

    integer OrderCore::getVirtualProducts()

Count virtual products in order



* Visibility: **public**




### isVirtual

    boolean OrderCore::isVirtual(boolean $strict)

Check if order contains (only) virtual products



* Visibility: **public**


#### Arguments
* $strict **boolean** - &lt;p&gt;If false return true if there are at least one product virtual&lt;/p&gt;



### getDiscounts

    mixed OrderCore::getDiscounts($details)





* Visibility: **public**


#### Arguments
* $details **mixed**



### getCartRules

    mixed OrderCore::getCartRules()





* Visibility: **public**




### getDiscountsCustomer

    mixed OrderCore::getDiscountsCustomer($id_customer, $id_cart_rule)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $id_cart_rule **mixed**



### getCurrentState

    integer OrderCore::getCurrentState()

Get current order status (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**




### getCurrentStateFull

    array OrderCore::getCurrentStateFull($id_lang)

Get current order status name (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### hasBeenDelivered

    mixed OrderCore::hasBeenDelivered()





* Visibility: **public**




### hasProductReturned

    mixed OrderCore::hasProductReturned()

Has products returned by the merchant or by the customer?



* Visibility: **public**




### hasBeenPaid

    mixed OrderCore::hasBeenPaid()





* Visibility: **public**




### hasBeenShipped

    mixed OrderCore::hasBeenShipped()





* Visibility: **public**




### isInPreparation

    mixed OrderCore::isInPreparation()





* Visibility: **public**




### isPaidAndShipped

    boolean OrderCore::isPaidAndShipped()

Checks if the current order status is paid and shipped



* Visibility: **public**




### getCustomerOrders

    array OrderCore::getCustomerOrders(integer $id_customer, boolean $show_hidden_status, \Context $context)

Get customer orders



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer id&lt;/p&gt;
* $show_hidden_status **boolean** - &lt;p&gt;Display or not hidden order statuses&lt;/p&gt;
* $context **Context**



### getOrdersIdByDate

    mixed OrderCore::getOrdersIdByDate($date_from, $date_to, $id_customer, $type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### getOrdersWithInformations

    mixed OrderCore::getOrdersWithInformations($limit, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $limit **mixed**
* $context **Context**



### getOrdersIdInvoiceByDate

    array OrderCore::getOrdersIdInvoiceByDate($date_from, $date_to, $id_customer, $type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### getOrderIdsByStatus

    array OrderCore::getOrderIdsByStatus($id_order_state)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_state **mixed**



### getTotalProductsWithoutTaxes

    \Product OrderCore::getTotalProductsWithoutTaxes($products)

Get product total without taxes



* Visibility: **public**


#### Arguments
* $products **mixed**



### getTotalProductsWithTaxes

    \Product OrderCore::getTotalProductsWithTaxes($products)

Get product total with taxes



* Visibility: **public**


#### Arguments
* $products **mixed**



### getCustomer

    \Customer OrderCore::getCustomer()

Get order customer



* Visibility: **public**




### getCustomerNbOrders

    array OrderCore::getCustomerNbOrders(integer $id_customer)

Get customer orders number



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer id&lt;/p&gt;



### getOrderByCartId

    array OrderCore::getOrderByCartId(integer $id_cart)

Get an order by its cart id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **integer** - &lt;p&gt;Cart id&lt;/p&gt;



### addDiscount

    boolean OrderCore::addDiscount(integer $id_cart_rule, string $name, float $value)





* Visibility: **public**


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $value **float**



### addCartRule

    boolean OrderCore::addCartRule(integer $id_cart_rule, string $name, array $values, integer $id_order_invoice, $free_shipping)





* Visibility: **public**


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $values **array**
* $id_order_invoice **integer**
* $free_shipping **mixed**



### getNumberOfDays

    mixed OrderCore::getNumberOfDays()





* Visibility: **public**




### isReturnable

    boolean OrderCore::isReturnable()

Can this order be returned by the client?



* Visibility: **public**




### getLastInvoiceNumber

    mixed OrderCore::getLastInvoiceNumber()





* Visibility: **public**
* This method is **static**.




### setLastInvoiceNumber

    mixed OrderCore::setLastInvoiceNumber($order_invoice_id, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### getInvoiceNumber

    mixed OrderCore::getInvoiceNumber($order_invoice_id)





* Visibility: **public**


#### Arguments
* $order_invoice_id **mixed**



### setInvoice

    mixed OrderCore::setInvoice($use_existing_payment)

This method allows to generate first invoice of the current order



* Visibility: **public**


#### Arguments
* $use_existing_payment **mixed**



### setInvoiceDetails

    mixed OrderCore::setInvoiceDetails($order_invoice)

This method allows to fulfill the object order_invoice with sales figures



* Visibility: **protected**


#### Arguments
* $order_invoice **mixed**



### setDeliverySlip

    mixed OrderCore::setDeliverySlip()

This method allows to generate first delivery slip of the current order



* Visibility: **public**




### setDeliveryNumber

    mixed OrderCore::setDeliveryNumber($order_invoice_id, $id_shop)





* Visibility: **public**


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### getDeliveryNumber

    mixed OrderCore::getDeliveryNumber($order_invoice_id)





* Visibility: **public**


#### Arguments
* $order_invoice_id **mixed**



### setDelivery

    mixed OrderCore::setDelivery()





* Visibility: **public**




### getByDelivery

    mixed OrderCore::getByDelivery($id_delivery)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_delivery **mixed**



### getByReference

    \PrestaShopCollection OrderCore::getByReference(string $reference)

Get a collection of orders using reference



* Visibility: **public**
* This method is **static**.


#### Arguments
* $reference **string**



### getTotalWeight

    mixed OrderCore::getTotalWeight()





* Visibility: **public**




### getInvoice

    mixed OrderCore::getInvoice(integer $id_invoice)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_invoice **integer**



### isAssociatedAtGuest

    mixed OrderCore::isAssociatedAtGuest($email)





* Visibility: **public**


#### Arguments
* $email **mixed**



### getCartIdStatic

    integer OrderCore::getCartIdStatic(integer $id_order, integer $id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **integer**
* $id_customer **integer** - &lt;p&gt;optionnal&lt;/p&gt;



### getWsOrderRows

    mixed OrderCore::getWsOrderRows()





* Visibility: **public**




### setCurrentState

    mixed OrderCore::setCurrentState(integer $id_order_state, integer $id_employee)

Set current order status



* Visibility: **public**


#### Arguments
* $id_order_state **integer**
* $id_employee **integer** - &lt;p&gt;(/!\ not optional except for Webservice.&lt;/p&gt;



### addWs

    mixed OrderCore::addWs($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### deleteAssociations

    mixed OrderCore::deleteAssociations()





* Visibility: **public**




### getPreviousOrderId

    integer OrderCore::getPreviousOrderId()

This method return the ID of the previous order



* Visibility: **public**




### getNextOrderId

    integer OrderCore::getNextOrderId()

This method return the ID of the next order



* Visibility: **public**




### getOrderDetailList

    array OrderCore::getOrderDetailList()

Get the an order detail list of the current order



* Visibility: **public**




### generateReference

    String OrderCore::generateReference()

Gennerate a unique reference for orders generated with the same cart id
This references, is usefull for check payment



* Visibility: **public**
* This method is **static**.




### orderContainProduct

    mixed OrderCore::orderContainProduct($id_product)





* Visibility: **public**


#### Arguments
* $id_product **mixed**



### useOneAfterAnotherTaxComputationMethod

    boolean OrderCore::useOneAfterAnotherTaxComputationMethod()

This method returns true if at least one order details uses the
One After Another tax computation method.



* Visibility: **public**




### getOrderPaymentCollection

    \PrestaShopCollection OrderCore::getOrderPaymentCollection()

This method allows to get all Order Payment for the current order



* Visibility: **public**




### addOrderPayment

    boolean OrderCore::addOrderPayment(float $amount_paid, string $payment_method, string $payment_transaction_id, \Currency $currency, string $date, \OrderInvoice $order_invoice)

This method allows to add a payment to the current order



* Visibility: **public**


#### Arguments
* $amount_paid **float**
* $payment_method **string**
* $payment_transaction_id **string**
* $currency **Currency**
* $date **string**
* $order_invoice **OrderInvoice**



### getDocuments

    array OrderCore::getDocuments()

Returns the correct product taxes breakdown.

Get all documents linked to the current order

* Visibility: **public**




### getReturn

    mixed OrderCore::getReturn()





* Visibility: **public**




### getShipping

    array OrderCore::getShipping()





* Visibility: **public**




### getOrderSlipsCollection

    \PrestaShopCollection OrderCore::getOrderSlipsCollection()

Get all order_slips for the current order



* Visibility: **public**




### getInvoicesCollection

    \PrestaShopCollection OrderCore::getInvoicesCollection()

Get all invoices for the current order



* Visibility: **public**




### getDeliverySlipsCollection

    \PrestaShopCollection OrderCore::getDeliverySlipsCollection()

Get all delivery slips for the current order



* Visibility: **public**




### getNotPaidInvoicesCollection

    \PrestaShopCollection OrderCore::getNotPaidInvoicesCollection()

Get all not paid invoices for the current order



* Visibility: **public**




### getTotalPaid

    float OrderCore::getTotalPaid(\Currency $currency)

Get total paid



* Visibility: **public**


#### Arguments
* $currency **Currency** - &lt;p&gt;currency used for the total paid of the current order&lt;/p&gt;



### getOrdersTotalPaid

    float OrderCore::getOrdersTotalPaid()

Get the sum of total_paid_tax_incl of the orders with similar reference



* Visibility: **public**




### updateShippingCost

    boolean OrderCore::updateShippingCost(float $amount)

This method allows to change the shipping cost of the current order



* Visibility: **public**


#### Arguments
* $amount **float**



### getProductTaxesBreakdown

    array OrderCore::getProductTaxesBreakdown()

Returns the correct product taxes breakdown.



* Visibility: **public**




### getShippingTaxesBreakdown

    array OrderCore::getShippingTaxesBreakdown()

Returns the shipping taxes breakdown



* Visibility: **public**




### getWrappingTaxesBreakdown

    array OrderCore::getWrappingTaxesBreakdown()

Returns the wrapping taxes breakdown



* Visibility: **public**




### getEcoTaxTaxesBreakdown

    array OrderCore::getEcoTaxTaxesBreakdown()

Returns the ecotax taxes breakdown



* Visibility: **public**




### hasInvoice

    boolean OrderCore::hasInvoice()

Has invoice return true if this order has already an invoice



* Visibility: **public**




### hasDelivery

    boolean OrderCore::hasDelivery()

Has Delivery return true if this order has already a delivery slip



* Visibility: **public**




### getWarehouseList

    mixed OrderCore::getWarehouseList()

Get warehouse associated to the order

return array List of warehouse

* Visibility: **public**




### getCurrentOrderState

    \OrderState OrderCore::getCurrentOrderState()





* Visibility: **public**




### getWebserviceObjectList

    mixed OrderCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### getBrother

    mixed OrderCore::getBrother()

Get all other orders with the same reference



* Visibility: **public**




### getOrderPayments

    mixed OrderCore::getOrderPayments()

Get a collection of order payments



* Visibility: **public**




### getUniqReference

    mixed OrderCore::getUniqReference()

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**




### getUniqReferenceOf

    mixed OrderCore::getUniqReferenceOf($id_order)

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **mixed**



### getIdOrderCarrier

    mixed OrderCore::getIdOrderCarrier()

Return id of carrier

Get id of the carrier used in order

* Visibility: **public**




### sortDocuments

    mixed OrderCore::sortDocuments($a, $b)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $a **mixed**
* $b **mixed**



### getWsShippingNumber

    mixed OrderCore::getWsShippingNumber()





* Visibility: **public**




### setWsShippingNumber

    mixed OrderCore::setWsShippingNumber($shipping_number)





* Visibility: **public**


#### Arguments
* $shipping_number **mixed**



### getWsCurrentState

    mixed OrderCore::getWsCurrentState()





* Visibility: **public**




### setWsCurrentState

    mixed OrderCore::setWsCurrentState($state)





* Visibility: **public**


#### Arguments
* $state **mixed**



### getProductTaxesDetails

    array OrderCore::getProductTaxesDetails($limitToOrderDetails)

By default this function was made for invoice, to compute tax amounts and balance delta (because of computation made on round values).

If you provide $limitToOrderDetails, only these item will be taken into account. This option is usefull for order slip for example,
where only sublist of the order is refunded.

* Visibility: **public**


#### Arguments
* $limitToOrderDetails **mixed** - &lt;p&gt;Optional array of OrderDetails to take into account. False by default to take all OrderDetails from the current Order.&lt;/p&gt;



### updateOrderDetailTax

    mixed OrderCore::updateOrderDetailTax()

The primary purpose of this method is to be
called at the end of the generation of each order
in PaymentModule::validateOrder, to fill in
the order_detail_tax table with taxes
that will add up in such a way that
the sum of the tax amounts in the product tax breakdown
is equal to the difference between products with tax and
products without tax.



* Visibility: **public**




### getOrderDetailTaxes

    mixed OrderCore::getOrderDetailTaxes()





* Visibility: **public**



