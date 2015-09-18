OrderInvoiceCore
===============






* Class name: OrderInvoiceCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### TAX_EXCL

    const TAX_EXCL = 0





### TAX_INCL

    const TAX_INCL = 1





### DETAIL

    const DETAIL = 2





Properties
----------


### $id_order

    public integer $id_order





* Visibility: **public**


### $number

    public integer $number





* Visibility: **public**


### $delivery_number

    public integer $delivery_number





* Visibility: **public**


### $delivery_date

    public integer $delivery_date = '0000-00-00 00:00:00'





* Visibility: **public**


### $total_discount_tax_excl

    public float $total_discount_tax_excl





* Visibility: **public**


### $total_discount_tax_incl

    public float $total_discount_tax_incl





* Visibility: **public**


### $total_paid_tax_excl

    public float $total_paid_tax_excl





* Visibility: **public**


### $total_paid_tax_incl

    public float $total_paid_tax_incl





* Visibility: **public**


### $total_products

    public float $total_products





* Visibility: **public**


### $total_products_wt

    public float $total_products_wt





* Visibility: **public**


### $total_shipping_tax_excl

    public float $total_shipping_tax_excl





* Visibility: **public**


### $total_shipping_tax_incl

    public float $total_shipping_tax_incl





* Visibility: **public**


### $shipping_tax_computation_method

    public integer $shipping_tax_computation_method





* Visibility: **public**


### $total_wrapping_tax_excl

    public float $total_wrapping_tax_excl





* Visibility: **public**


### $total_wrapping_tax_incl

    public float $total_wrapping_tax_incl





* Visibility: **public**


### $shop_address

    public string $shop_address





* Visibility: **public**


### $invoice_address

    public string $invoice_address





* Visibility: **public**


### $delivery_address

    public string $delivery_address





* Visibility: **public**


### $note

    public string $note





* Visibility: **public**


### $date_add

    public integer $date_add





* Visibility: **public**


### $_total_paid_cache

    protected array $_total_paid_cache = array()





* Visibility: **protected**
* This property is **static**.


### $order

    private \Order $order





* Visibility: **private**


### $definition

    public mixed $definition = array('table' => 'order_invoice', 'primary' => 'id_order_invoice', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'number' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'delivery_number' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'delivery_date' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'total_discount_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_discount_tax_incl' => array('type' => self::TYPE_FLOAT), 'total_paid_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_paid_tax_incl' => array('type' => self::TYPE_FLOAT), 'total_products' => array('type' => self::TYPE_FLOAT), 'total_products_wt' => array('type' => self::TYPE_FLOAT), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT), 'shipping_tax_computation_method' => array('type' => self::TYPE_INT), 'total_wrapping_tax_excl' => array('type' => self::TYPE_FLOAT), 'total_wrapping_tax_incl' => array('type' => self::TYPE_FLOAT), 'shop_address' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 1000), 'invoice_address' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 1000), 'delivery_address' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 1000), 'note' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65000), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### add

    mixed OrderInvoiceCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getProductsDetail

    mixed OrderInvoiceCore::getProductsDetail()





* Visibility: **public**




### getInvoiceByNumber

    mixed OrderInvoiceCore::getInvoiceByNumber($id_invoice)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_invoice **mixed**



### getProducts

    array OrderInvoiceCore::getProducts($products, $selected_products, $selected_qty)

Get order products



* Visibility: **public**


#### Arguments
* $products **mixed**
* $selected_products **mixed**
* $selected_qty **mixed**



### setProductCustomizedDatas

    mixed OrderInvoiceCore::setProductCustomizedDatas($product, $customized_datas)





* Visibility: **protected**


#### Arguments
* $product **mixed**
* $customized_datas **mixed**



### setProductCurrentStock

    mixed OrderInvoiceCore::setProductCurrentStock($product)

This method allow to add stock information on a product detail



* Visibility: **protected**


#### Arguments
* $product **mixed**



### setProductImageInformations

    mixed OrderInvoiceCore::setProductImageInformations($product)

This method allow to add image information on a product detail



* Visibility: **protected**


#### Arguments
* $product **mixed**



### useOneAfterAnotherTaxComputationMethod

    boolean OrderInvoiceCore::useOneAfterAnotherTaxComputationMethod()

This method returns true if at least one order details uses the
One After Another tax computation method.



* Visibility: **public**




### displayTaxBasesInProductTaxesBreakdown

    mixed OrderInvoiceCore::displayTaxBasesInProductTaxesBreakdown()





* Visibility: **public**




### getOrder

    mixed OrderInvoiceCore::getOrder()





* Visibility: **public**




### getProductTaxesBreakdown

    mixed OrderInvoiceCore::getProductTaxesBreakdown($order)





* Visibility: **public**


#### Arguments
* $order **mixed**



### getShippingTaxesBreakdown

    array OrderInvoiceCore::getShippingTaxesBreakdown(\Order $order)

Returns the shipping taxes breakdown



* Visibility: **public**


#### Arguments
* $order **Order**



### getWrappingTaxesBreakdown

    array OrderInvoiceCore::getWrappingTaxesBreakdown()

Returns the wrapping taxes breakdown



* Visibility: **public**




### getEcoTaxTaxesBreakdown

    array OrderInvoiceCore::getEcoTaxTaxesBreakdown()

Returns the ecotax taxes breakdown



* Visibility: **public**




### getByDateInterval

    array OrderInvoiceCore::getByDateInterval($date_from, $date_to)

Returns all the order invoice that match the date interval



* Visibility: **public**
* This method is **static**.


#### Arguments
* $date_from **mixed**
* $date_to **mixed**



### getByStatus

    array OrderInvoiceCore::getByStatus($id_order_state)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_state **mixed**



### getByDeliveryDateInterval

    array OrderInvoiceCore::getByDeliveryDateInterval($date_from, $date_to)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $date_from **mixed**
* $date_to **mixed**



### getCarrier

    mixed OrderInvoiceCore::getCarrier($id_order_invoice)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_invoice **mixed**



### getCarrierId

    mixed OrderInvoiceCore::getCarrierId($id_order_invoice)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_invoice **mixed**



### retrieveOneById

    \OrderInvoice OrderInvoiceCore::retrieveOneById(integer $id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **integer**



### getTotalPaid

    float OrderInvoiceCore::getTotalPaid()

Amounts of payments



* Visibility: **public**




### getRestPaid

    float OrderInvoiceCore::getRestPaid()

Rest Paid



* Visibility: **public**




### getSibling

    \PrestaShopCollection|array OrderInvoiceCore::getSibling()

Return collection of order invoice object linked to the payments of the current order invoice object



* Visibility: **public**




### getSiblingTotal

    mixed OrderInvoiceCore::getSiblingTotal(integer $mod)

Return total to paid of sibling invoices



* Visibility: **public**


#### Arguments
* $mod **integer** - &lt;p&gt;TAX_EXCL, TAX_INCL, DETAIL&lt;/p&gt;



### getGlobalRestPaid

    mixed OrderInvoiceCore::getGlobalRestPaid()

Get global rest to paid
   This method will return something different of the method getRestPaid if
   there is an other invoice linked to the payments of the current invoice



* Visibility: **public**




### isPaid

    boolean OrderInvoiceCore::isPaid()





* Visibility: **public**




### getOrderPaymentCollection

    \PrestaShopCollection OrderInvoiceCore::getOrderPaymentCollection()





* Visibility: **public**




### getInvoiceNumberFormatted

    string OrderInvoiceCore::getInvoiceNumberFormatted(integer $id_lang, $id_shop)

Get the formatted number of invoice



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;for invoice_prefix&lt;/p&gt;
* $id_shop **mixed**



### saveCarrierTaxCalculator

    mixed OrderInvoiceCore::saveCarrierTaxCalculator(array $taxes_amount)





* Visibility: **public**


#### Arguments
* $taxes_amount **array**



### saveWrappingTaxCalculator

    mixed OrderInvoiceCore::saveWrappingTaxCalculator(array $taxes_amount)





* Visibility: **public**


#### Arguments
* $taxes_amount **array**



### getCurrentFormattedShopAddress

    mixed OrderInvoiceCore::getCurrentFormattedShopAddress($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**



### fixAllShopAddresses

    mixed OrderInvoiceCore::fixAllShopAddresses()

This method is used to fix shop addresses that cannot be fixed during upgrade process
(because uses the whole environnement of PS classes that is not available during upgrade).

This method should execute once on an upgraded PrestaShop to fix all OrderInvoices in one shot.
This method is triggered once during a (non bulk) creation of a PDF from an OrderInvoice that is not fixed yet.

* Visibility: **public**
* This method is **static**.



