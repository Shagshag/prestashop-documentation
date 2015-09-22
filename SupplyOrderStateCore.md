SupplyOrderStateCore
===============






* Class name: SupplyOrderStateCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/stock/SupplyOrderState.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#30)





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#35)


### $delivery_note

    public boolean $delivery_note





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#40)


### $editable

    public boolean $editable





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#45)


### $receipt_state

    public boolean $receipt_state





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#50)


### $pending_receipt

    public boolean $pending_receipt





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#55)


### $enclosed

    public boolean $enclosed





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#60)


### $color

    public string $color





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#65)


### $definition

    public mixed $definition = array('table' => 'supply_order_state', 'primary' => 'id_supply_order_state', 'multilang' => true, 'fields' => array('delivery_note' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'editable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'receipt_state' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pending_receipt' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'enclosed' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/SupplyOrderState.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#70)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_states', 'objectNodeName' => 'supply_order_state', 'fields' => array())





* Visibility: **protected**
* This property is defined in [classes/stock/SupplyOrderState.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#88)


Methods
-------


### getSupplyOrderStates

    array SupplyOrderStateCore::getSupplyOrderStates(integer $id_state_referrer, integer $id_lang)

Gets the list of supply order statuses



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/SupplyOrderState.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#102)


#### Arguments
* $id_state_referrer **integer** - &lt;p&gt;Optional, used to know what state is available after this one&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional Id Language&lt;/p&gt;



### getStates

    array SupplyOrderStateCore::getStates(array $ids, integer $id_lang)

Gets the list of supply order statuses



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/SupplyOrderState.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#154)


#### Arguments
* $ids **array** - &lt;p&gt;Optional Do not include these ids in the result&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional&lt;/p&gt;


