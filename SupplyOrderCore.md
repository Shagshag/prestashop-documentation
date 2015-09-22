SupplyOrderCore
===============






* Class name: SupplyOrderCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\stock\SupplyOrder.php line 30





Properties
----------


### $id_supplier

    public integer $id_supplier





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 35


### $supplier_name

    public string $supplier_name





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 40


### $id_lang

    public integer $id_lang





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 45


### $id_warehouse

    public integer $id_warehouse





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 50


### $id_supply_order_state

    public integer $id_supply_order_state





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 55


### $id_currency

    public integer $id_currency





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 60


### $id_ref_currency

    public integer $id_ref_currency





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 65


### $reference

    public string $reference





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 70


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 75


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 80


### $date_delivery_expected

    public string $date_delivery_expected





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 85


### $total_te

    public float $total_te





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 90


### $total_with_discount_te

    public float $total_with_discount_te





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 95


### $total_ti

    public float $total_ti





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 100


### $total_tax

    public float $total_tax





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 105


### $discount_rate

    public float $discount_rate





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 110


### $discount_value_te

    public float $discount_value_te





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 115


### $is_template

    public integer $is_template





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrder.php line 120


### $definition

    public mixed $definition = array('table' => 'supply_order', 'primary' => 'id_supply_order', 'fields' => array('id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'supplier_name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_ref_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'date_delivery_expected' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'total_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_with_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_ti' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_tax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'discount_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => false), 'discount_value_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'is_template' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\stock\SupplyOrder.php line 125


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_supplier' => array('xlink_resource' => 'suppliers'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states'), 'id_currency' => array('xlink_resource' => 'currencies')), 'hidden_fields' => array('id_ref_currency'), 'associations' => array('supply_order_details' => array('resource' => 'supply_order_detail', 'fields' => array('id' => array(), 'id_product' => array(), 'id_product_attribute' => array(), 'supplier_reference' => array(), 'product_name' => array()))))





* Visibility: **protected**
* This property is defined in classes\stock\SupplyOrder.php line 153


Methods
-------


### update

    mixed SupplyOrderCore::update($null_values)





* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 181


#### Arguments
* $null_values **mixed**



### add

    mixed SupplyOrderCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 197


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### calculatePrices

    mixed SupplyOrderCore::calculatePrices()

Checks all products in this order and calculate prices
Applies the global discount if necessary



* Visibility: **protected**
* This method is defined in classes\stock\SupplyOrder.php line 214




### getEntries

    array SupplyOrderCore::getEntries(integer $id_lang)

Retrieves the product entries for the current order



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 255


#### Arguments
* $id_lang **integer** - &lt;p&gt;Optional Id Lang - Uses Context::language::id by default&lt;/p&gt;



### getEntriesCollection

    \PrestaShopCollection SupplyOrderCore::getEntriesCollection()

Retrieves the details entries (i.e. products) collection for the current order



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 290




### hasEntries

    boolean SupplyOrderCore::hasEntries()

Check if the order has entries



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 303




### isEditable

    boolean SupplyOrderCore::isEditable()

Check if the current state allows to edit the current order



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 318




### isDeliveryNoteAvailable

    boolean SupplyOrderCore::isDeliveryNoteAvailable()

Checks if the current state allows to generate a delivery note for this order



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 333




### isInReceiptState

    boolean SupplyOrderCore::isInReceiptState()

Checks if the current state allows to add products in stock



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 348




### addHistory

    mixed SupplyOrderCore::addHistory()

Historizes the order : its id, its state, and the employee responsible for the current action



* Visibility: **protected**
* This method is defined in classes\stock\SupplyOrder.php line 361




### resetProducts

    mixed SupplyOrderCore::resetProducts()

Removes all products from the order



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 377




### warehouseHasPendingOrders

    boolean SupplyOrderCore::warehouseHasPendingOrders(integer $id_warehouse)

For a given $id_warehouse, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\SupplyOrder.php line 392


#### Arguments
* $id_warehouse **integer**



### supplierHasPendingOrders

    boolean SupplyOrderCore::supplierHasPendingOrders(integer $id_supplier)

For a given $id_supplier, tells if it has pending supply orders



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\SupplyOrder.php line 415


#### Arguments
* $id_supplier **integer** - &lt;p&gt;Id Supplier&lt;/p&gt;



### exists

    integer SupplyOrderCore::exists(integer|string $match)

For a given id or reference, tells if the supply order exists



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\SupplyOrder.php line 438


#### Arguments
* $match **integer|string** - &lt;p&gt;Either the reference of the order, or the Id of the order&lt;/p&gt;



### getSupplyOrderByReference

    boolean|\SupplyOrder SupplyOrderCore::getSupplyOrderByReference(string $reference)

For a given reference, returns the corresponding supply order



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\SupplyOrder.php line 459


#### Arguments
* $reference **string** - &lt;p&gt;Reference of the order&lt;/p&gt;



### hydrate

    mixed SupplyOrderCore::hydrate(array $data, $id_lang)





* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 482


#### Arguments
* $data **array**
* $id_lang **mixed**



### getReferenceById

    boolean|string SupplyOrderCore::getReferenceById(integer $id_supply_order)

Gets the reference of a given order



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\SupplyOrder.php line 507


#### Arguments
* $id_supply_order **integer**



### getAllExpectedQuantity

    mixed SupplyOrderCore::getAllExpectedQuantity()





* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 522




### getAllReceivedQuantity

    mixed SupplyOrderCore::getAllReceivedQuantity()





* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 531




### getAllPendingQuantity

    mixed SupplyOrderCore::getAllPendingQuantity()





* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 540




### getWsSupplyOrderDetails

    array SupplyOrderCore::getWsSupplyOrderDetails()

Webservice : gets the ids supply_order_detail associated to this order



* Visibility: **public**
* This method is defined in classes\stock\SupplyOrder.php line 560



