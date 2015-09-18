SupplyOrderStateCore
===============






* Class name: SupplyOrderStateCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $delivery_note

    public boolean $delivery_note





* Visibility: **public**


### $editable

    public boolean $editable





* Visibility: **public**


### $receipt_state

    public boolean $receipt_state





* Visibility: **public**


### $pending_receipt

    public boolean $pending_receipt





* Visibility: **public**


### $enclosed

    public boolean $enclosed





* Visibility: **public**


### $color

    public string $color





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'supply_order_state', 'primary' => 'id_supply_order_state', 'multilang' => true, 'fields' => array('delivery_note' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'editable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'receipt_state' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pending_receipt' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'enclosed' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_states', 'objectNodeName' => 'supply_order_state', 'fields' => array())





* Visibility: **protected**


Methods
-------


### getSupplyOrderStates

    array SupplyOrderStateCore::getSupplyOrderStates(integer $id_state_referrer, integer $id_lang)

Gets the list of supply order statuses



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_state_referrer **integer** - &lt;p&gt;Optional, used to know what state is available after this one&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional Id Language&lt;/p&gt;



### getStates

    array SupplyOrderStateCore::getStates(array $ids, integer $id_lang)

Gets the list of supply order statuses



* Visibility: **public**
* This method is **static**.


#### Arguments
* $ids **array** - &lt;p&gt;Optional Do not include these ids in the result&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional&lt;/p&gt;


