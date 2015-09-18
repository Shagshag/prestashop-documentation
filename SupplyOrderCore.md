SupplyOrderCore
===============






* Class name: SupplyOrderCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_supplier

    public integer $id_supplier





* Visibility: **public**


### $supplier_name

    public string $supplier_name





* Visibility: **public**


### $id_lang

    public integer $id_lang





* Visibility: **public**


### $id_warehouse

    public integer $id_warehouse





* Visibility: **public**


### $id_supply_order_state

    public integer $id_supply_order_state





* Visibility: **public**


### $id_currency

    public integer $id_currency





* Visibility: **public**


### $id_ref_currency

    public integer $id_ref_currency





* Visibility: **public**


### $reference

    public string $reference





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $date_delivery_expected

    public string $date_delivery_expected





* Visibility: **public**


### $total_te

    public float $total_te





* Visibility: **public**


### $total_with_discount_te

    public float $total_with_discount_te





* Visibility: **public**


### $total_ti

    public float $total_ti





* Visibility: **public**


### $total_tax

    public float $total_tax





* Visibility: **public**


### $discount_rate

    public float $discount_rate





* Visibility: **public**


### $discount_value_te

    public float $discount_value_te





* Visibility: **public**


### $is_template

    public integer $is_template





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'supply_order', 'primary' => 'id_supply_order', 'fields' => array('id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'supplier_name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_ref_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'date_delivery_expected' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'total_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_with_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_ti' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_tax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'discount_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => false), 'discount_value_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'is_template' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_supplier' => array('xlink_resource' => 'suppliers'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states'), 'id_currency' => array('xlink_resource' => 'currencies')), 'hidden_fields' => array('id_ref_currency'), 'associations' => array('supply_order_details' => array('resource' => 'supply_order_detail', 'fields' => array('id' => array(), 'id_product' => array(), 'id_product_attribute' => array(), 'supplier_reference' => array(), 'product_name' => array()))))





* Visibility: **protected**


Methods
-------


### update

    mixed SupplyOrderCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### add

    mixed SupplyOrderCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### calculatePrices

    mixed SupplyOrderCore::calculatePrices()

Checks all products in this order and calculate prices
Applies the global discount if necessary



* Visibility: **protected**




### getEntries

    array SupplyOrderCore::getEntries(integer $id_lang)

Retrieves the product entries for the current order



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Optional Id Lang - Uses Context::language::id by default&lt;/p&gt;



### getEntriesCollection

    \PrestaShopCollection SupplyOrderCore::getEntriesCollection()

Retrieves the details entries (i.e. products) collection for the current order



* Visibility: **public**




### hasEntries

    boolean SupplyOrderCore::hasEntries()

Check if the order has entries



* Visibility: **public**




### isEditable

    boolean SupplyOrderCore::isEditable()

Check if the current state allows to edit the current order



* Visibility: **public**




### isDeliveryNoteAvailable

    boolean SupplyOrderCore::isDeliveryNoteAvailable()

Checks if the current state allows to generate a delivery note for this order



* Visibility: **public**




### isInReceiptState

    boolean SupplyOrderCore::isInReceiptState()

Checks if the current state allows to add products in stock



* Visibility: **public**




### addHistory

    mixed SupplyOrderCore::addHistory()

Historizes the order : its id, its state, and the employee responsible for the current action



* Visibility: **protected**




### resetProducts

    mixed SupplyOrderCore::resetProducts()

Removes all products from the order



* Visibility: **public**




### warehouseHasPendingOrders

    boolean SupplyOrderCore::warehouseHasPendingOrders(integer $id_warehouse)

For a given $id_warehouse, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_warehouse **integer**



### supplierHasPendingOrders

    boolean SupplyOrderCore::supplierHasPendingOrders(integer $id_supplier)

For a given $id_supplier, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supplier **integer** - &lt;p&gt;Id Supplier&lt;/p&gt;



### exists

    integer SupplyOrderCore::exists(integer|string $match)

For a given id or reference, tells if the supply order exists



* Visibility: **public**
* This method is **static**.


#### Arguments
* $match **integer|string** - &lt;p&gt;Either the reference of the order, or the Id of the order&lt;/p&gt;



### getSupplyOrderByReference

    boolean|\SupplyOrder SupplyOrderCore::getSupplyOrderByReference(string $reference)

For a given reference, returns the corresponding supply order



* Visibility: **public**
* This method is **static**.


#### Arguments
* $reference **string** - &lt;p&gt;Reference of the order&lt;/p&gt;



### hydrate

    mixed SupplyOrderCore::hydrate(array $data, $id_lang)





* Visibility: **public**


#### Arguments
* $data **array**
* $id_lang **mixed**



### getReferenceById

    boolean|string SupplyOrderCore::getReferenceById(integer $id_supply_order)

Gets the reference of a given order



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supply_order **integer**



### getAllExpectedQuantity

    mixed SupplyOrderCore::getAllExpectedQuantity()





* Visibility: **public**




### getAllReceivedQuantity

    mixed SupplyOrderCore::getAllReceivedQuantity()





* Visibility: **public**




### getAllPendingQuantity

    mixed SupplyOrderCore::getAllPendingQuantity()





* Visibility: **public**




### getWsSupplyOrderDetails

    array SupplyOrderCore::getWsSupplyOrderDetails()

Webservice : gets the ids supply_order_detail associated to this order



* Visibility: **public**



