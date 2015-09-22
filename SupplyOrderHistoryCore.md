SupplyOrderHistoryCore
===============






* Class name: SupplyOrderHistoryCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\stock\SupplyOrderHistory.php line 30





Properties
----------


### $id_supply_order

    public integer $id_supply_order





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrderHistory.php line 35


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrderHistory.php line 40


### $employee_firstname

    public string $employee_firstname





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrderHistory.php line 45


### $employee_lastname

    public string $employee_lastname





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrderHistory.php line 50


### $id_state

    public integer $id_state





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrderHistory.php line 55


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in classes\stock\SupplyOrderHistory.php line 60


### $definition

    public mixed $definition = array('table' => 'supply_order_history', 'primary' => 'id_supply_order_history', 'fields' => array('id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\stock\SupplyOrderHistory.php line 65


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_histories', 'objectNodeName' => 'supply_order_history', 'fields' => array('id_supply_order' => array('xlink_resource' => 'supply_orders'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_state' => array('xlink_resource' => 'supply_order_states')))





* Visibility: **protected**
* This property is defined in classes\stock\SupplyOrderHistory.php line 81



