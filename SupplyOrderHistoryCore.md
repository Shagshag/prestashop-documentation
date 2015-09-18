SupplyOrderHistoryCore
===============






* Class name: SupplyOrderHistoryCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_supply_order

    public integer $id_supply_order





* Visibility: **public**


### $id_employee

    public integer $id_employee





* Visibility: **public**


### $employee_firstname

    public string $employee_firstname





* Visibility: **public**


### $employee_lastname

    public string $employee_lastname





* Visibility: **public**


### $id_state

    public integer $id_state





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'supply_order_history', 'primary' => 'id_supply_order_history', 'fields' => array('id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_histories', 'objectNodeName' => 'supply_order_history', 'fields' => array('id_supply_order' => array('xlink_resource' => 'supply_orders'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_state' => array('xlink_resource' => 'supply_order_states')))





* Visibility: **protected**



