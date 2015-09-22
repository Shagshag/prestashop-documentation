OrderCore
===============






* Class name: OrderCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/order/Order.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#27)



Constants
----------


### ROUND_ITEM

    const ROUND_ITEM = 1



* This constant is defined in [classes/order/Order.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#29)


### ROUND_LINE

    const ROUND_LINE = 2



* This constant is defined in [classes/order/Order.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#30)


### ROUND_TOTAL

    const ROUND_TOTAL = 3



* This constant is defined in [classes/order/Order.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#31)


Properties
----------


### $id_address_delivery

    public integer $id_address_delivery





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#35)


### $id_address_invoice

    public integer $id_address_invoice





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#38)


### $id_shop_group

    public mixed $id_shop_group





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#40)


### $id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#42)


### $id_cart

    public integer $id_cart





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#45)


### $id_currency

    public integer $id_currency





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#48)


### $id_lang

    public integer $id_lang





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#51)


### $id_customer

    public integer $id_customer





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#54)


### $id_carrier

    public integer $id_carrier





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#57)


### $current_state

    public integer $current_state





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#60)


### $secure_key

    public string $secure_key





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#63)


### $payment

    public string $payment





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#66)


### $module

    public string $module





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#69)


### $conversion_rate

    public float $conversion_rate





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#72)


### $recyclable

    public boolean $recyclable = 1





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#75)


### $gift

    public boolean $gift





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#78)


### $gift_message

    public string $gift_message





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#81)


### $mobile_theme

    public boolean $mobile_theme





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#84)


### $shipping_number

    public string $shipping_number





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#91)


### $total_discounts

    public float $total_discounts





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#94)


### $total_discounts_tax_incl

    public mixed $total_discounts_tax_incl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#96)


### $total_discounts_tax_excl

    public mixed $total_discounts_tax_excl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#97)


### $total_paid

    public float $total_paid





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#100)


### $total_paid_tax_incl

    public float $total_paid_tax_incl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#103)


### $total_paid_tax_excl

    public float $total_paid_tax_excl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#106)


### $total_paid_real

    public float $total_paid_real





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#109)


### $total_products

    public float $total_products





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#112)


### $total_products_wt

    public float $total_products_wt





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#115)


### $total_shipping

    public float $total_shipping





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#118)


### $total_shipping_tax_incl

    public float $total_shipping_tax_incl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#121)


### $total_shipping_tax_excl

    public float $total_shipping_tax_excl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#124)


### $carrier_tax_rate

    public float $carrier_tax_rate





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#127)


### $total_wrapping

    public float $total_wrapping





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#130)


### $total_wrapping_tax_incl

    public float $total_wrapping_tax_incl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#133)


### $total_wrapping_tax_excl

    public float $total_wrapping_tax_excl





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#136)


### $invoice_number

    public integer $invoice_number





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#139)


### $delivery_number

    public integer $delivery_number





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#142)


### $invoice_date

    public string $invoice_date





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#145)


### $delivery_date

    public string $delivery_date





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#148)


### $valid

    public boolean $valid





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#151)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#154)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#157)


### $reference

    public string $reference





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#162)


### $round_mode

    public integer $round_mode





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#167)


### $round_type

    public integer $round_type





* Visibility: **public**
* This property is defined in [classes/order/Order.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#172)


### $definition

    public mixed $definition = array('table' => 'orders', 'primary' => 'id_order', 'fields' => array('id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'current_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5'), 'payment' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true), 'recyclable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift_message' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'total_discounts' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_paid_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_real' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products_wt' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_shipping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'carrier_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'total_wrapping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'round_mode' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'round_type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'shipping_number' => array('type' => self::TYPE_STRING, 'validate' => 'isTrackingNumber'), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'invoice_number' => array('type' => self::TYPE_INT), 'delivery_number' => array('type' => self::TYPE_INT), 'invoice_date' => array('type' => self::TYPE_DATE), 'delivery_date' => array('type' => self::TYPE_DATE), 'valid' => array('type' => self::TYPE_BOOL), 'reference' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/order/Order.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#177)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs'), 'objectNodeName' => 'order', 'objectsNodeName' => 'orders', 'fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_cart' => array('xlink_resource' => 'carts'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_carrier' => array('xlink_resource' => 'carriers'), 'current_state' => array('xlink_resource' => 'order_states', 'setter' => 'setWsCurrentState'), 'module' => array('required' => true), 'invoice_number' => array(), 'invoice_date' => array(), 'delivery_number' => array(), 'delivery_date' => array(), 'valid' => array(), 'date_add' => array(), 'date_upd' => array(), 'shipping_number' => array('getter' => 'getWsShippingNumber', 'setter' => 'setWsShippingNumber')), 'associations' => array('order_rows' => array('resource' => 'order_row', 'setter' => false, 'virtual_entity' => true, 'fields' => array('id' => array(), 'product_id' => array('required' => true), 'product_attribute_id' => array('required' => true), 'product_quantity' => array('required' => true), 'product_name' => array('setter' => false), 'product_reference' => array('setter' => false), 'product_ean13' => array('setter' => false), 'product_upc' => array('setter' => false), 'product_price' => array('setter' => false), 'unit_price_tax_incl' => array('setter' => false), 'unit_price_tax_excl' => array('setter' => false)))))





* Visibility: **protected**
* This property is defined in [classes/order/Order.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#229)


### $_taxCalculationMethod

    protected mixed $_taxCalculationMethod = PS_TAX_EXC





* Visibility: **protected**
* This property is defined in [classes/order/Order.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#277)


### $_historyCache

    protected mixed $_historyCache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/order/Order.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#279)


### $cacheCustomer

    protected mixed $cacheCustomer = null

used to cache order customer



* Visibility: **protected**
* This property is defined in [classes/order/Order.php line 1048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1048)


Methods
-------


### __construct

    mixed OrderCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#281)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### getFields

    array OrderCore::getFields()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#298)




### add

    mixed OrderCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#307)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getTaxCalculationMethod

    mixed OrderCore::getTaxCalculationMethod()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#315)




### deleteProduct

    boolean OrderCore::deleteProduct($order, \OrderDetail $order_detail, integer $quantity)

Does NOT delete a product but "cancel" it (which means return/refund/delete it depending of the case)



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#329)


#### Arguments
* $order **mixed**
* $order_detail **[OrderDetail](OrderDetailCore)**
* $quantity **integer**



### getCartProducts

    array OrderCore::getCartProducts()

This function return products of the orders
It's similar to Order::getProducts but with similar outputs of Cart::getProducts



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#354)




### _deleteProduct

    boolean OrderCore::_deleteProduct(\OrderDetail $order_detail, integer $quantity)

DOES delete the product



* Visibility: **protected**
* This method is defined in [classes/order/Order.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#390)


#### Arguments
* $order_detail **[OrderDetail](OrderDetailCore)**
* $quantity **integer**



### deleteCustomization

    mixed OrderCore::deleteCustomization($id_customization, $quantity, $order_detail)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#461)


#### Arguments
* $id_customization **mixed**
* $quantity **mixed**
* $order_detail **mixed**



### getHistory

    array OrderCore::getHistory(integer $id_lang, integer $id_order_state, integer $no_hidden, integer $filters)

Get order history



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 491](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#491)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_order_state **integer** - &lt;p&gt;Filter a specific order status&lt;/p&gt;
* $no_hidden **integer** - &lt;p&gt;Filter no hidden status&lt;/p&gt;
* $filters **integer** - &lt;p&gt;Flag to use specific field filter&lt;/p&gt;



### getProductsDetail

    mixed OrderCore::getProductsDetail()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#544)




### getFirstMessage

    mixed OrderCore::getFirstMessage()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#554)




### setProductPrices

    mixed OrderCore::setProductPrices($row)

Marked as deprecated but should not throw any "deprecated" message
This function is used in order to keep front office backward compatibility 14 -> 1.5
(Order History)



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#571)


#### Arguments
* $row **mixed**



### getProducts

    array OrderCore::getProducts($products, $selected_products, $selected_qty)

Get order products



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#597)


#### Arguments
* $products **mixed**
* $selected_products **mixed**
* $selected_qty **mixed**



### getIdOrderProduct

    mixed OrderCore::getIdOrderProduct($id_customer, $id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 648](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#648)


#### Arguments
* $id_customer **mixed**
* $id_product **mixed**



### setProductCustomizedDatas

    mixed OrderCore::setProductCustomizedDatas($product, $customized_datas)





* Visibility: **protected**
* This method is defined in [classes/order/Order.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#661)


#### Arguments
* $product **mixed**
* $customized_datas **mixed**



### setProductCurrentStock

    mixed OrderCore::setProductCurrentStock($product)

This method allow to add stock information on a product detail

If advanced stock management is active, get physical stock of this product in the warehouse associated to the ptoduct for the current order
Else get the available quantity of the product in fucntion of the shop associated to the order

* Visibility: **protected**
* This method is defined in [classes/order/Order.php line 680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#680)


#### Arguments
* $product **mixed**



### setProductImageInformations

    mixed OrderCore::setProductImageInformations($product)

This method allow to add image information on a product detail



* Visibility: **protected**
* This method is defined in [classes/order/Order.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#696)


#### Arguments
* $product **mixed**



### getTaxesAverageUsed

    mixed OrderCore::getTaxesAverageUsed()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 724](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#724)




### getVirtualProducts

    integer OrderCore::getVirtualProducts()

Count virtual products in order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 734](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#734)




### isVirtual

    boolean OrderCore::isVirtual(boolean $strict)

Check if order contains (only) virtual products



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#751)


#### Arguments
* $strict **boolean** - &lt;p&gt;If false return true if there are at least one product virtual&lt;/p&gt;



### getDiscounts

    mixed OrderCore::getDiscounts($details)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#774)


#### Arguments
* $details **mixed**



### getCartRules

    mixed OrderCore::getCartRules()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#780)




### getDiscountsCustomer

    mixed OrderCore::getDiscountsCustomer($id_customer, $id_cart_rule)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#788)


#### Arguments
* $id_customer **mixed**
* $id_cart_rule **mixed**



### getCurrentState

    integer OrderCore::getCurrentState()

Get current order status (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**
* This method is defined in [classes/order/Order.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#808)




### getCurrentStateFull

    array OrderCore::getCurrentStateFull($id_lang)

Get current order status name (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**
* This method is defined in [classes/order/Order.php line 818](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#818)


#### Arguments
* $id_lang **mixed**



### hasBeenDelivered

    mixed OrderCore::hasBeenDelivered()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#827)




### hasProductReturned

    mixed OrderCore::hasProductReturned()

Has products returned by the merchant or by the customer?



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#835)




### hasBeenPaid

    mixed OrderCore::hasBeenPaid()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 847](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#847)




### hasBeenShipped

    mixed OrderCore::hasBeenShipped()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#852)




### isInPreparation

    mixed OrderCore::isInPreparation()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#857)




### isPaidAndShipped

    boolean OrderCore::isPaidAndShipped()

Checks if the current order status is paid and shipped



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 867](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#867)




### getCustomerOrders

    array OrderCore::getCustomerOrders(integer $id_customer, boolean $show_hidden_status, \Context $context)

Get customer orders



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#883)


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer id&lt;/p&gt;
* $show_hidden_status **boolean** - &lt;p&gt;Display or not hidden order statuses&lt;/p&gt;
* $context **[Context](ContextCore)**



### getOrdersIdByDate

    mixed OrderCore::getOrdersIdByDate($date_from, $date_to, $id_customer, $type)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 916](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#916)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### getOrdersWithInformations

    mixed OrderCore::getOrdersWithInformations($limit, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#933)


#### Arguments
* $limit **mixed**
* $context **[Context](ContextCore)**



### getOrdersIdInvoiceByDate

    array OrderCore::getOrdersIdInvoiceByDate($date_from, $date_to, $id_customer, $type)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 965](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#965)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### getOrderIdsByStatus

    array OrderCore::getOrderIdsByStatus($id_order_state)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#990)


#### Arguments
* $id_order_state **mixed**



### getTotalProductsWithoutTaxes

    \Product OrderCore::getTotalProductsWithoutTaxes($products)

Get product total without taxes



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1012](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1012)


#### Arguments
* $products **mixed**



### getTotalProductsWithTaxes

    \Product OrderCore::getTotalProductsWithTaxes($products)

Get product total with taxes



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1022](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1022)


#### Arguments
* $products **mixed**



### getCustomer

    \Customer OrderCore::getCustomer()

Get order customer



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1055](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1055)




### getCustomerNbOrders

    array OrderCore::getCustomerNbOrders(integer $id_customer)

Get customer orders number



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1070](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1070)


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer id&lt;/p&gt;



### getOrderByCartId

    array OrderCore::getOrderByCartId(integer $id_cart)

Get an order by its cart id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1087](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1087)


#### Arguments
* $id_cart **integer** - &lt;p&gt;Cart id&lt;/p&gt;



### addDiscount

    boolean OrderCore::addDiscount(integer $id_cart_rule, string $name, float $value)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1106)


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $value **float**



### addCartRule

    boolean OrderCore::addCartRule(integer $id_cart_rule, string $name, array $values, integer $id_order_invoice, $free_shipping)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1120)


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $values **array**
* $id_order_invoice **integer**
* $free_shipping **mixed**



### getNumberOfDays

    mixed OrderCore::getNumberOfDays()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1137)




### isReturnable

    boolean OrderCore::isReturnable()

Can this order be returned by the client?



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1157)




### getLastInvoiceNumber

    mixed OrderCore::getLastInvoiceNumber()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1166)




### setLastInvoiceNumber

    mixed OrderCore::setLastInvoiceNumber($order_invoice_id, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1174)


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### getInvoiceNumber

    mixed OrderCore::getInvoiceNumber($order_invoice_id)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1200)


#### Arguments
* $order_invoice_id **mixed**



### setInvoice

    mixed OrderCore::setInvoice($use_existing_payment)

This method allows to generate first invoice of the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1216)


#### Arguments
* $use_existing_payment **mixed**



### setInvoiceDetails

    mixed OrderCore::setInvoiceDetails($order_invoice)

This method allows to fulfill the object order_invoice with sales figures



* Visibility: **protected**
* This method is defined in [classes/order/Order.php line 1312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1312)


#### Arguments
* $order_invoice **mixed**



### setDeliverySlip

    mixed OrderCore::setDeliverySlip()

This method allows to generate first delivery slip of the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1362)




### setDeliveryNumber

    mixed OrderCore::setDeliveryNumber($order_invoice_id, $id_shop)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1375)


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### getDeliveryNumber

    mixed OrderCore::getDeliveryNumber($order_invoice_id)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1403)


#### Arguments
* $order_invoice_id **mixed**



### setDelivery

    mixed OrderCore::setDelivery()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1416)




### getByDelivery

    mixed OrderCore::getByDelivery($id_delivery)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1442)


#### Arguments
* $id_delivery **mixed**



### getByReference

    \PrestaShopCollection OrderCore::getByReference(string $reference)

Get a collection of orders using reference



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1460)


#### Arguments
* $reference **string**



### getTotalWeight

    mixed OrderCore::getTotalWeight()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1467](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1467)




### getInvoice

    mixed OrderCore::getInvoice(integer $id_invoice)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1481)


#### Arguments
* $id_invoice **integer**



### isAssociatedAtGuest

    mixed OrderCore::isAssociatedAtGuest($email)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1490)


#### Arguments
* $email **mixed**



### getCartIdStatic

    integer OrderCore::getCartIdStatic(integer $id_order, integer $id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1510](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1510)


#### Arguments
* $id_order **integer**
* $id_customer **integer** - &lt;p&gt;optionnal&lt;/p&gt;



### getWsOrderRows

    mixed OrderCore::getWsOrderRows()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1519](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1519)




### setCurrentState

    mixed OrderCore::setCurrentState(integer $id_order_state, integer $id_employee)

Set current order status



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1545](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1545)


#### Arguments
* $id_order_state **integer**
* $id_employee **integer** - &lt;p&gt;(/!\ not optional except for Webservice.&lt;/p&gt;



### addWs

    mixed OrderCore::addWs($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1567](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1567)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### deleteAssociations

    mixed OrderCore::deleteAssociations()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1577)




### getPreviousOrderId

    integer OrderCore::getPreviousOrderId()

This method return the ID of the previous order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1589](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1589)




### getNextOrderId

    integer OrderCore::getNextOrderId()

This method return the ID of the next order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1604](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1604)




### getOrderDetailList

    array OrderCore::getOrderDetailList()

Get the an order detail list of the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1618)




### generateReference

    String OrderCore::generateReference()

Gennerate a unique reference for orders generated with the same cart id
This references, is usefull for check payment



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 1629](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1629)




### orderContainProduct

    mixed OrderCore::orderContainProduct($id_product)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1634)


#### Arguments
* $id_product **mixed**



### useOneAfterAnotherTaxComputationMethod

    boolean OrderCore::useOneAfterAnotherTaxComputationMethod()

This method returns true if at least one order details uses the
One After Another tax computation method.



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1651)




### getOrderPaymentCollection

    \PrestaShopCollection OrderCore::getOrderPaymentCollection()

This method allows to get all Order Payment for the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1668](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1668)




### addOrderPayment

    boolean OrderCore::addOrderPayment(float $amount_paid, string $payment_method, string $payment_transaction_id, \Currency $currency, string $date, \OrderInvoice $order_invoice)

This method allows to add a payment to the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1687](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1687)


#### Arguments
* $amount_paid **float**
* $payment_method **string**
* $payment_transaction_id **string**
* $currency **[Currency](CurrencyCore)**
* $date **string**
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**



### getDocuments

    array OrderCore::getDocuments()

Returns the correct product taxes breakdown.

Get all documents linked to the current order

* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1739](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1739)




### getReturn

    mixed OrderCore::getReturn()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1764](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1764)




### getShipping

    array OrderCore::getShipping()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1773)




### getOrderSlipsCollection

    \PrestaShopCollection OrderCore::getOrderSlipsCollection()

Get all order_slips for the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1797)




### getInvoicesCollection

    \PrestaShopCollection OrderCore::getInvoicesCollection()

Get all invoices for the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1810](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1810)




### getDeliverySlipsCollection

    \PrestaShopCollection OrderCore::getDeliverySlipsCollection()

Get all delivery slips for the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1823](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1823)




### getNotPaidInvoicesCollection

    \PrestaShopCollection OrderCore::getNotPaidInvoicesCollection()

Get all not paid invoices for the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1836](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1836)




### getTotalPaid

    float OrderCore::getTotalPaid(\Currency $currency)

Get total paid



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1856](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1856)


#### Arguments
* $currency **[Currency](CurrencyCore)** - &lt;p&gt;currency used for the total paid of the current order&lt;/p&gt;



### getOrdersTotalPaid

    float OrderCore::getOrdersTotalPaid()

Get the sum of total_paid_tax_incl of the orders with similar reference



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1888](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1888)




### updateShippingCost

    boolean OrderCore::updateShippingCost(float $amount)

This method allows to change the shipping cost of the current order



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1905](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1905)


#### Arguments
* $amount **float**



### getProductTaxesBreakdown

    array OrderCore::getProductTaxesBreakdown()

Returns the correct product taxes breakdown.



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1928](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1928)




### getShippingTaxesBreakdown

    array OrderCore::getShippingTaxesBreakdown()

Returns the shipping taxes breakdown



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 1983](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#1983)




### getWrappingTaxesBreakdown

    array OrderCore::getWrappingTaxesBreakdown()

Returns the wrapping taxes breakdown



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2006](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2006)




### getEcoTaxTaxesBreakdown

    array OrderCore::getEcoTaxTaxesBreakdown()

Returns the ecotax taxes breakdown



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2018](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2018)




### hasInvoice

    boolean OrderCore::hasInvoice()

Has invoice return true if this order has already an invoice



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2032](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2032)




### hasDelivery

    boolean OrderCore::hasDelivery()

Has Delivery return true if this order has already a delivery slip



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2047](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2047)




### getWarehouseList

    mixed OrderCore::getWarehouseList()

Get warehouse associated to the order

return array List of warehouse

* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2062](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2062)




### getCurrentOrderState

    \OrderState OrderCore::getCurrentOrderState()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2085](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2085)




### getWebserviceObjectList

    mixed OrderCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2096](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2096)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### getBrother

    mixed OrderCore::getBrother()

Get all other orders with the same reference



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2107)




### getOrderPayments

    mixed OrderCore::getOrderPayments()

Get a collection of order payments



* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2120)




### getUniqReference

    mixed OrderCore::getUniqReference()

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2133)




### getUniqReferenceOf

    mixed OrderCore::getUniqReferenceOf($id_order)

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 2157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2157)


#### Arguments
* $id_order **mixed**



### getIdOrderCarrier

    mixed OrderCore::getIdOrderCarrier()

Return id of carrier

Get id of the carrier used in order

* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2170)




### sortDocuments

    mixed OrderCore::sortDocuments($a, $b)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/Order.php line 2178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2178)


#### Arguments
* $a **mixed**
* $b **mixed**



### getWsShippingNumber

    mixed OrderCore::getWsShippingNumber()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2186)




### setWsShippingNumber

    mixed OrderCore::setWsShippingNumber($shipping_number)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2199)


#### Arguments
* $shipping_number **mixed**



### getWsCurrentState

    mixed OrderCore::getWsCurrentState()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2218)




### setWsCurrentState

    mixed OrderCore::setWsCurrentState($state)





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2223)


#### Arguments
* $state **mixed**



### getProductTaxesDetails

    array OrderCore::getProductTaxesDetails($limitToOrderDetails)

By default this function was made for invoice, to compute tax amounts and balance delta (because of computation made on round values).

If you provide $limitToOrderDetails, only these item will be taken into account. This option is usefull for order slip for example,
where only sublist of the order is refunded.

* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2240)


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
* This method is defined in [classes/order/Order.php line 2393](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2393)




### getOrderDetailTaxes

    mixed OrderCore::getOrderDetailTaxes()





* Visibility: **public**
* This method is defined in [classes/order/Order.php line 2419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/Order.php#2419)



