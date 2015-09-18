OrderDetailCore
===============






* Class name: OrderDetailCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_order_detail

    public integer $id_order_detail





* Visibility: **public**


### $id_order

    public integer $id_order





* Visibility: **public**


### $id_order_invoice

    public integer $id_order_invoice





* Visibility: **public**


### $product_id

    public integer $product_id





* Visibility: **public**


### $id_shop

    public integer $id_shop





* Visibility: **public**


### $product_attribute_id

    public integer $product_attribute_id





* Visibility: **public**


### $product_name

    public string $product_name





* Visibility: **public**


### $product_quantity

    public integer $product_quantity





* Visibility: **public**


### $product_quantity_in_stock

    public integer $product_quantity_in_stock





* Visibility: **public**


### $product_quantity_return

    public integer $product_quantity_return





* Visibility: **public**


### $product_quantity_refunded

    public integer $product_quantity_refunded





* Visibility: **public**


### $product_quantity_reinjected

    public integer $product_quantity_reinjected





* Visibility: **public**


### $product_price

    public float $product_price





* Visibility: **public**


### $original_product_price

    public float $original_product_price





* Visibility: **public**


### $unit_price_tax_incl

    public float $unit_price_tax_incl





* Visibility: **public**


### $unit_price_tax_excl

    public float $unit_price_tax_excl





* Visibility: **public**


### $total_price_tax_incl

    public float $total_price_tax_incl





* Visibility: **public**


### $total_price_tax_excl

    public float $total_price_tax_excl





* Visibility: **public**


### $reduction_percent

    public float $reduction_percent





* Visibility: **public**


### $reduction_amount

    public float $reduction_amount





* Visibility: **public**


### $reduction_amount_tax_excl

    public float $reduction_amount_tax_excl





* Visibility: **public**


### $reduction_amount_tax_incl

    public float $reduction_amount_tax_incl





* Visibility: **public**


### $group_reduction

    public float $group_reduction





* Visibility: **public**


### $product_quantity_discount

    public float $product_quantity_discount





* Visibility: **public**


### $product_ean13

    public string $product_ean13





* Visibility: **public**


### $product_upc

    public string $product_upc





* Visibility: **public**


### $product_reference

    public string $product_reference





* Visibility: **public**


### $product_supplier_reference

    public string $product_supplier_reference





* Visibility: **public**


### $product_weight

    public float $product_weight





* Visibility: **public**


### $ecotax

    public float $ecotax





* Visibility: **public**


### $ecotax_tax_rate

    public float $ecotax_tax_rate





* Visibility: **public**


### $discount_quantity_applied

    public integer $discount_quantity_applied





* Visibility: **public**


### $download_hash

    public string $download_hash





* Visibility: **public**


### $download_nb

    public integer $download_nb





* Visibility: **public**


### $download_deadline

    public \datetime $download_deadline





* Visibility: **public**


### $tax_name

    public string $tax_name





* Visibility: **public**


### $tax_rate

    public float $tax_rate





* Visibility: **public**


### $tax_computation_method

    public float $tax_computation_method





* Visibility: **public**


### $id_tax_rules_group

    public integer $id_tax_rules_group





* Visibility: **public**


### $id_warehouse

    public integer $id_warehouse





* Visibility: **public**


### $total_shipping_price_tax_excl

    public float $total_shipping_price_tax_excl





* Visibility: **public**


### $total_shipping_price_tax_incl

    public float $total_shipping_price_tax_incl





* Visibility: **public**


### $purchase_supplier_price

    public float $purchase_supplier_price





* Visibility: **public**


### $original_wholesale_price

    public float $original_wholesale_price





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_detail', 'primary' => 'id_order_detail', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'product_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_attribute_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'product_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'product_quantity_in_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'product_quantity_return' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_reinjected' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'group_reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_quantity_discount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'product_upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'product_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tax_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tax_computation_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'ecotax_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'discount_quantity_applied' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_hash' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'download_nb' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_deadline' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'unit_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'unit_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'purchase_supplier_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'original_product_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'original_wholesale_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders'), 'product_id' => array('xlink_resource' => 'products'), 'product_attribute_id' => array('xlink_resource' => 'combinations'), 'product_quantity_reinjected' => array(), 'group_reduction' => array(), 'discount_quantity_applied' => array(), 'download_hash' => array(), 'download_deadline' => array()), 'hidden_fields' => array('tax_rate', 'tax_name'), 'associations' => array('taxes' => array('resource' => 'tax', 'getter' => 'getWsTaxes', 'setter' => false, 'fields' => array('id' => array()))))





* Visibility: **protected**


### $outOfStock

    protected boolean $outOfStock = false





* Visibility: **protected**


### $tax_calculator

    protected \TaxCalculator $tax_calculator = null





* Visibility: **protected**


### $vat_address

    protected \Address $vat_address = null





* Visibility: **protected**


### $specificPrice

    protected \Address $specificPrice = null





* Visibility: **protected**


### $customer

    protected \Customer $customer = null





* Visibility: **protected**


### $context

    protected \Context $context = null





* Visibility: **protected**


Methods
-------


### __construct

    mixed OrderDetailCore::__construct($id, $id_lang, $context)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $context **mixed**



### delete

    mixed OrderDetailCore::delete()





* Visibility: **public**




### setContext

    mixed OrderDetailCore::setContext($id_shop)





* Visibility: **protected**


#### Arguments
* $id_shop **mixed**



### getDownloadFromHash

    mixed OrderDetailCore::getDownloadFromHash($hash)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $hash **mixed**



### incrementDownload

    mixed OrderDetailCore::incrementDownload($id_order_detail, $increment)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_detail **mixed**
* $increment **mixed**



### getTaxCalculator

    \TaxCalculator OrderDetailCore::getTaxCalculator()

Returns the tax calculator associated to this order detail.



* Visibility: **public**




### getTaxCalculatorStatic

    \TaxCalculator OrderDetailCore::getTaxCalculatorStatic(integer $id_order_detail)

Return the tax calculator associated to this order_detail



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_detail **integer**



### saveTaxCalculator

    boolean OrderDetailCore::saveTaxCalculator(\Order $order, $replace)

Save the tax calculator



* Visibility: **public**


#### Arguments
* $order **Order**
* $replace **mixed**



### updateTaxAmount

    mixed OrderDetailCore::updateTaxAmount($order)





* Visibility: **public**


#### Arguments
* $order **mixed**



### getList

    array OrderDetailCore::getList(integer $id_order)

Get a detailed order list of an id_order



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **integer**



### getTaxList

    mixed OrderDetailCore::getTaxList()





* Visibility: **public**




### getTaxListStatic

    mixed OrderDetailCore::getTaxListStatic($id_order_detail)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order_detail **mixed**



### setVirtualProductInformation

    mixed OrderDetailCore::setVirtualProductInformation($product)





* Visibility: **protected**


#### Arguments
* $product **mixed**



### checkProductStock

    mixed OrderDetailCore::checkProductStock(array $product, integer $id_order_state)

Check the order status



* Visibility: **protected**


#### Arguments
* $product **array**
* $id_order_state **integer**



### setProductTax

    mixed OrderDetailCore::setProductTax(object $order, array $product)

Apply tax to the product



* Visibility: **protected**


#### Arguments
* $order **object**
* $product **array**



### setSpecificPrice

    mixed OrderDetailCore::setSpecificPrice(object $order, $product)

Set specific price of the product



* Visibility: **protected**


#### Arguments
* $order **object**
* $product **mixed**



### setDetailProductPrice

    mixed OrderDetailCore::setDetailProductPrice(object $order, object $cart, array $product)

Set detailed product price to the order detail



* Visibility: **protected**


#### Arguments
* $order **object**
* $cart **object**
* $product **array**



### create

    mixed OrderDetailCore::create(object $order, object $cart, array $product, $id_order_state, integer $id_order_invoice, boolean $use_taxes, $id_warehouse)

Create an order detail liable to an id_order



* Visibility: **protected**


#### Arguments
* $order **object**
* $cart **object**
* $product **array**
* $id_order_state **mixed**
* $id_order_invoice **integer**
* $use_taxes **boolean** - &lt;p&gt;set to false if you don&#039;t want to use taxes&lt;/p&gt;
* $id_warehouse **mixed**



### createList

    mixed OrderDetailCore::createList(object $order, object $cart, $id_order_state, $product_list, integer $id_order_invoice, boolean $use_taxes, $id_warehouse)

Create a list of order detail for a specified id_order using cart



* Visibility: **public**


#### Arguments
* $order **object**
* $cart **object**
* $id_order_state **mixed**
* $product_list **mixed**
* $id_order_invoice **integer**
* $use_taxes **boolean** - &lt;p&gt;set to false if you don&#039;t want to use taxes&lt;/p&gt;
* $id_warehouse **mixed**



### getStockState

    array OrderDetailCore::getStockState()

Get the state of the current stock product



* Visibility: **public**




### setShippingCost

    mixed OrderDetailCore::setShippingCost(\Order $order, $product)

Set the additional shipping information



* Visibility: **public**


#### Arguments
* $order **Order**
* $product **mixed**



### getWsTaxes

    mixed OrderDetailCore::getWsTaxes()





* Visibility: **public**




### getCrossSells

    mixed OrderDetailCore::getCrossSells($id_product, $id_lang, $limit)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $limit **mixed**



### add

    mixed OrderDetailCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getWholeSalePrice

    mixed OrderDetailCore::getWholeSalePrice()





* Visibility: **public**



