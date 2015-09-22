SupplyOrderReceiptHistoryCore
===============

History of receipts




* Class name: SupplyOrderReceiptHistoryCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/stock/SupplyOrderReceiptHistory.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#31)





Properties
----------


### $id_supply_order_detail

    public integer $id_supply_order_detail





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#36)


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#41)


### $employee_firstname

    public string $employee_firstname





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#46)


### $employee_lastname

    public string $employee_lastname





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#51)


### $id_supply_order_state

    public integer $id_supply_order_state





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#56)


### $quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#61)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#66)


### $definition

    public mixed $definition = array('table' => 'supply_order_receipt_history', 'primary' => 'id_supply_order_receipt_history', 'fields' => array('id_supply_order_detail' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#71)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_receipt_histories', 'objectNodeName' => 'supply_order_receipt_history', 'fields' => array('id_supply_order_detail' => array('xlink_resource' => 'supply_order_details'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states')))





* Visibility: **protected**
* This property is defined in [classes/stock/SupplyOrderReceiptHistory.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderReceiptHistory.php#88)



