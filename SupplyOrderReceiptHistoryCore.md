SupplyOrderReceiptHistoryCore
===============

History of receipts




* Class name: SupplyOrderReceiptHistoryCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/stock/SupplyOrderReceiptHistory.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L31)





Properties
----------

* [$id_supply_order_detail](#property-$id_supply_order_detail)
* [$id_employee](#property-$id_employee)
* [$employee_firstname](#property-$employee_firstname)
* [$employee_lastname](#property-$employee_lastname)
* [$id_supply_order_state](#property-$id_supply_order_state)
* [$quantity](#property-$quantity)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)





Properties
----------


### <a name="property-$id_supply_order_detail"></a>$id_supply_order_detail

    public integer $id_supply_order_detail





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L36)


### <a name="property-$id_employee"></a>$id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L41)


### <a name="property-$employee_firstname"></a>$employee_firstname

    public string $employee_firstname





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L46)


### <a name="property-$employee_lastname"></a>$employee_lastname

    public string $employee_lastname





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L51)


### <a name="property-$id_supply_order_state"></a>$id_supply_order_state

    public integer $id_supply_order_state





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L56)


### <a name="property-$quantity"></a>$quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L61)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L66)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'supply_order_receipt_history', 'primary' => 'id_supply_order_receipt_history', 'fields' => array('id_supply_order_detail' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L71)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_receipt_histories', 'objectNodeName' => 'supply_order_receipt_history', 'fields' => array('id_supply_order_detail' => array('xlink_resource' => 'supply_order_details'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states')))





* Visibility: **protected**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#L88)



