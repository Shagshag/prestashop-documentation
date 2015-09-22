Class OrderInvoiceCore
=====================





* Class name: OrderInvoiceCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderInvoice.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L27)

Constants
----------

* [DETAIL](#constant-DETAIL)
* [TAX_EXCL](#constant-TAX_EXCL)
* [TAX_INCL](#constant-TAX_INCL)

Properties
----------

* [$_total_paid_cache](#property-$_total_paid_cache)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$delivery_address](#property-$delivery_address)
* [$delivery_date](#property-$delivery_date)
* [$delivery_number](#property-$delivery_number)
* [$id_order](#property-$id_order)
* [$invoice_address](#property-$invoice_address)
* [$note](#property-$note)
* [$number](#property-$number)
* [$order](#property-$order)
* [$shipping_tax_computation_method](#property-$shipping_tax_computation_method)
* [$shop_address](#property-$shop_address)
* [$total_discount_tax_excl](#property-$total_discount_tax_excl)
* [$total_discount_tax_incl](#property-$total_discount_tax_incl)
* [$total_paid_tax_excl](#property-$total_paid_tax_excl)
* [$total_paid_tax_incl](#property-$total_paid_tax_incl)
* [$total_products](#property-$total_products)
* [$total_products_wt](#property-$total_products_wt)
* [$total_shipping_tax_excl](#property-$total_shipping_tax_excl)
* [$total_shipping_tax_incl](#property-$total_shipping_tax_incl)
* [$total_wrapping_tax_excl](#property-$total_wrapping_tax_excl)
* [$total_wrapping_tax_incl](#property-$total_wrapping_tax_incl)

Methods
-------
* [add](#method-add)
* [displayTaxBasesInProductTaxesBreakdown](#method-displayTaxBasesInProductTaxesBreakdown)
* [fixAllShopAddresses](#method-fixAllShopAddresses)
* [getByDateInterval](#method-getByDateInterval)
* [getByDeliveryDateInterval](#method-getByDeliveryDateInterval)
* [getByStatus](#method-getByStatus)
* [getCarrier](#method-getCarrier)
* [getCarrierId](#method-getCarrierId)
* [getCurrentFormattedShopAddress](#method-getCurrentFormattedShopAddress)
* [getEcoTaxTaxesBreakdown](#method-getEcoTaxTaxesBreakdown)
* [getGlobalRestPaid](#method-getGlobalRestPaid)
* [getInvoiceByNumber](#method-getInvoiceByNumber)
* [getInvoiceNumberFormatted](#method-getInvoiceNumberFormatted)
* [getOrder](#method-getOrder)
* [getOrderPaymentCollection](#method-getOrderPaymentCollection)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getProducts](#method-getProducts)
* [getProductsDetail](#method-getProductsDetail)
* [getRestPaid](#method-getRestPaid)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getSibling](#method-getSibling)
* [getSiblingTotal](#method-getSiblingTotal)
* [getTotalPaid](#method-getTotalPaid)
* [getWrappingTaxesBreakdown](#method-getWrappingTaxesBreakdown)
* [isPaid](#method-isPaid)
* [retrieveOneById](#method-retrieveOneById)
* [saveCarrierTaxCalculator](#method-saveCarrierTaxCalculator)
* [saveWrappingTaxCalculator](#method-saveWrappingTaxCalculator)
* [setProductCurrentStock](#method-setProductCurrentStock)
* [setProductCustomizedDatas](#method-setProductCustomizedDatas)
* [setProductImageInformations](#method-setProductImageInformations)
* [useOneAfterAnotherTaxComputationMethod](#method-useOneAfterAnotherTaxComputationMethod)


Constants
----------


### <a name="constant-DETAIL"></a>DETAIL

    const DETAIL = 2





* Source: [classes/order/OrderInvoice.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L31).


### <a name="constant-TAX_EXCL"></a>TAX_EXCL

    const TAX_EXCL = 0





* Source: [classes/order/OrderInvoice.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L29).


### <a name="constant-TAX_INCL"></a>TAX_INCL

    const TAX_INCL = 1





* Source: [classes/order/OrderInvoice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L30).


Properties
----------


### <a name="property-$_total_paid_cache"></a>$_total_paid_cache

    protected array $_total_paid_cache = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/order/OrderInvoice.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L94).


### <a name="property-$date_add"></a>$date_add

    public integer $date_add





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L91).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'order_invoice', 'primary' => 'id_order_invoice', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'number' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'delivery_number' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'delivery_date' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'total_discount_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_discount_tax_incl' => array('type' => self::TYPE_FLOAT), 'total_paid_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_paid_tax_incl' => array('type' => self::TYPE_FLOAT), 'total_products' => array('type' => self::TYPE_FLOAT), 'total_products_wt' => array('type' => self::TYPE_FLOAT), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT), 'shipping_tax_computation_method' => array('type' => self::TYPE_INT), 'total_wrapping_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_wrapping_tax_incl' => array('type' => self::TYPE_FLOAT), 'shop_address' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 1000), 'invoice_address' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 1000), 'delivery_address' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 1000), 'note' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65000), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderInvoice.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L102).


### <a name="property-$delivery_address"></a>$delivery_address

    public string $delivery_address





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L85).


### <a name="property-$delivery_date"></a>$delivery_date

    public integer $delivery_date = '0000-00-00 00:00:00'





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L43).


### <a name="property-$delivery_number"></a>$delivery_number

    public integer $delivery_number





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L40).


### <a name="property-$id_order"></a>$id_order

    public integer $id_order





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L34).


### <a name="property-$invoice_address"></a>$invoice_address

    public string $invoice_address





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L82).


### <a name="property-$note"></a>$note

    public string $note





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L88).


### <a name="property-$number"></a>$number

    public integer $number





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L37).


### <a name="property-$order"></a>$order

    private \Order $order





* Visibility: **private**
* Source: [classes/order/OrderInvoice.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L97).


### <a name="property-$shipping_tax_computation_method"></a>$shipping_tax_computation_method

    public integer $shipping_tax_computation_method





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L70).


### <a name="property-$shop_address"></a>$shop_address

    public string $shop_address





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L79).


### <a name="property-$total_discount_tax_excl"></a>$total_discount_tax_excl

    public float $total_discount_tax_excl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L46).


### <a name="property-$total_discount_tax_incl"></a>$total_discount_tax_incl

    public float $total_discount_tax_incl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L49).


### <a name="property-$total_paid_tax_excl"></a>$total_paid_tax_excl

    public float $total_paid_tax_excl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L52).


### <a name="property-$total_paid_tax_incl"></a>$total_paid_tax_incl

    public float $total_paid_tax_incl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L55).


### <a name="property-$total_products"></a>$total_products

    public float $total_products





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L58).


### <a name="property-$total_products_wt"></a>$total_products_wt

    public float $total_products_wt





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L61).


### <a name="property-$total_shipping_tax_excl"></a>$total_shipping_tax_excl

    public float $total_shipping_tax_excl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L64).


### <a name="property-$total_shipping_tax_incl"></a>$total_shipping_tax_incl

    public float $total_shipping_tax_incl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L67).


### <a name="property-$total_wrapping_tax_excl"></a>$total_wrapping_tax_excl

    public float $total_wrapping_tax_excl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L73).


### <a name="property-$total_wrapping_tax_incl"></a>$total_wrapping_tax_incl

    public float $total_wrapping_tax_incl





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L76).


Methods
-------


### <a name="method-add"></a>add

    mixed OrderInvoiceCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L129)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-displayTaxBasesInProductTaxesBreakdown"></a>displayTaxBasesInProductTaxesBreakdown

    mixed OrderInvoiceCore::displayTaxBasesInProductTaxesBreakdown()





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L344)




### <a name="method-fixAllShopAddresses"></a>fixAllShopAddresses

    mixed OrderInvoiceCore::fixAllShopAddresses()

This method is used to fix shop addresses that cannot be fixed during upgrade process
(because uses the whole environnement of PS classes that is not available during upgrade).

This method should execute once on an upgraded PrestaShop to fix all OrderInvoices in one shot.
This method is triggered once during a (non bulk) creation of a PDF from an OrderInvoice that is not fixed yet.

* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L895)




### <a name="method-getByDateInterval"></a>getByDateInterval

    array OrderInvoiceCore::getByDateInterval($date_from, $date_to)

Returns all the order invoice that match the date interval



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L585)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**



### <a name="method-getByDeliveryDateInterval"></a>getByDeliveryDateInterval

    array OrderInvoiceCore::getByDeliveryDateInterval($date_from, $date_to)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L627)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**



### <a name="method-getByStatus"></a>getByStatus

    array OrderInvoiceCore::getByStatus($id_order_state)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L606)


#### Arguments
* $id_order_state **mixed**



### <a name="method-getCarrier"></a>getCarrier

    mixed OrderInvoiceCore::getCarrier($id_order_invoice)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 646](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L646)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-getCarrierId"></a>getCarrierId

    mixed OrderInvoiceCore::getCarrierId($id_order_invoice)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 660](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L660)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-getCurrentFormattedShopAddress"></a>getCurrentFormattedShopAddress

    mixed OrderInvoiceCore::getCurrentFormattedShopAddress($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 874](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L874)


#### Arguments
* $id_shop **mixed**



### <a name="method-getEcoTaxTaxesBreakdown"></a>getEcoTaxTaxesBreakdown

    array OrderInvoiceCore::getEcoTaxTaxesBreakdown()

Returns the ecotax taxes breakdown



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L557)




### <a name="method-getGlobalRestPaid"></a>getGlobalRestPaid

    mixed OrderInvoiceCore::getGlobalRestPaid()

Get global rest to paid
   This method will return something different of the method getRestPaid if
   there is an other invoice linked to the payments of the current invoice



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 782](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L782)




### <a name="method-getInvoiceByNumber"></a>getInvoiceByNumber

    mixed OrderInvoiceCore::getInvoiceByNumber($id_invoice)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L158)


#### Arguments
* $id_invoice **mixed**



### <a name="method-getInvoiceNumberFormatted"></a>getInvoiceNumberFormatted

    string OrderInvoiceCore::getInvoiceNumberFormatted(integer $id_lang, $id_shop)

Get the formatted number of invoice



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 832](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L832)


#### Arguments
* $id_lang **integer** - for invoice_prefix
* $id_shop **mixed**



### <a name="method-getOrder"></a>getOrder

    mixed OrderInvoiceCore::getOrder()





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L349)




### <a name="method-getOrderPaymentCollection"></a>getOrderPaymentCollection

    \PrestaShopCollection OrderInvoiceCore::getOrderPaymentCollection()





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 821](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L821)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

    mixed OrderInvoiceCore::getProductTaxesBreakdown($order)





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L358)


#### Arguments
* $order **mixed**



### <a name="method-getProducts"></a>getProducts

    array OrderInvoiceCore::getProducts($products, $selected_products, $selected_qty)

Get order products



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L186)


#### Arguments
* $products **mixed**
* $selected_products **mixed**
* $selected_qty **mixed**



### <a name="method-getProductsDetail"></a>getProductsDetail

    mixed OrderInvoiceCore::getProductsDetail()





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L146)




### <a name="method-getRestPaid"></a>getRestPaid

    float OrderInvoiceCore::getRestPaid()

Rest Paid



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 709](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L709)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

    array OrderInvoiceCore::getShippingTaxesBreakdown(\Order $order)

Returns the shipping taxes breakdown



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L425)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-getSibling"></a>getSibling

    \PrestaShopCollection|array OrderInvoiceCore::getSibling()

Return collection of order invoice object linked to the payments of the current order invoice object



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 720](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L720)




### <a name="method-getSiblingTotal"></a>getSiblingTotal

    mixed OrderInvoiceCore::getSiblingTotal(integer $mod)

Return total to paid of sibling invoices



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L753)


#### Arguments
* $mod **integer** - TAX_EXCL, TAX_INCL, DETAIL



### <a name="method-getTotalPaid"></a>getTotalPaid

    float OrderInvoiceCore::getTotalPaid()

Amounts of payments



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L688)




### <a name="method-getWrappingTaxesBreakdown"></a>getWrappingTaxesBreakdown

    array OrderInvoiceCore::getWrappingTaxesBreakdown()

Returns the wrapping taxes breakdown



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L494)




### <a name="method-isPaid"></a>isPaid

    boolean OrderInvoiceCore::isPaid()





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L812)




### <a name="method-retrieveOneById"></a>retrieveOneById

    \OrderInvoice OrderInvoiceCore::retrieveOneById(integer $id)





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderInvoice.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L674)


#### Arguments
* $id **integer**



### <a name="method-saveCarrierTaxCalculator"></a>saveCarrierTaxCalculator

    mixed OrderInvoiceCore::saveCarrierTaxCalculator(array $taxes_amount)





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 848](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L848)


#### Arguments
* $taxes_amount **array**



### <a name="method-saveWrappingTaxCalculator"></a>saveWrappingTaxCalculator

    mixed OrderInvoiceCore::saveWrappingTaxCalculator(array $taxes_amount)





* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 861](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L861)


#### Arguments
* $taxes_amount **array**



### <a name="method-setProductCurrentStock"></a>setProductCurrentStock

    mixed OrderInvoiceCore::setProductCurrentStock($product)

This method allow to add stock information on a product detail



* Visibility: **protected**
* Source: [classes/order/OrderInvoice.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L282)


#### Arguments
* $product **mixed**



### <a name="method-setProductCustomizedDatas"></a>setProductCustomizedDatas

    mixed OrderInvoiceCore::setProductCustomizedDatas($product, $customized_datas)





* Visibility: **protected**
* Source: [classes/order/OrderInvoice.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L267)


#### Arguments
* $product **mixed**
* $customized_datas **mixed**



### <a name="method-setProductImageInformations"></a>setProductImageInformations

    mixed OrderInvoiceCore::setProductImageInformations($product)

This method allow to add image information on a product detail



* Visibility: **protected**
* Source: [classes/order/OrderInvoice.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L298)


#### Arguments
* $product **mixed**



### <a name="method-useOneAfterAnotherTaxComputationMethod"></a>useOneAfterAnotherTaxComputationMethod

    boolean OrderInvoiceCore::useOneAfterAnotherTaxComputationMethod()

This method returns true if at least one order details uses the
One After Another tax computation method.



* Visibility: **public**
* Source: [classes/order/OrderInvoice.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderInvoice.php#L331)



