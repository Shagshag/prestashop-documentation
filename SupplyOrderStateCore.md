SupplyOrderStateCore
===============






* Class name: SupplyOrderStateCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/stock/SupplyOrderState.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L30)





Properties
----------

* [$name](#property-$name)
* [$delivery_note](#property-$delivery_note)
* [$editable](#property-$editable)
* [$receipt_state](#property-$receipt_state)
* [$pending_receipt](#property-$pending_receipt)
* [$enclosed](#property-$enclosed)
* [$color](#property-$color)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [getSupplyOrderStates](#method-getSupplyOrderStates)
* [getStates](#method-getStates)




Properties
----------


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L35)


### <a name="property-$delivery_note"></a>$delivery_note

    public boolean $delivery_note





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L40)


### <a name="property-$editable"></a>$editable

    public boolean $editable





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L45)


### <a name="property-$receipt_state"></a>$receipt_state

    public boolean $receipt_state





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L50)


### <a name="property-$pending_receipt"></a>$pending_receipt

    public boolean $pending_receipt





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L55)


### <a name="property-$enclosed"></a>$enclosed

    public boolean $enclosed





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L60)


### <a name="property-$color"></a>$color

    public string $color





* Visibility: **public**
* This property is defined in [classes/stock/SupplyOrderState.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L65)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'supply_order_state', 'primary' => 'id_supply_order_state', 'multilang' => true, 'fields' => array('delivery_note' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'editable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'receipt_state' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pending_receipt' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'enclosed' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/SupplyOrderState.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L70)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_states', 'objectNodeName' => 'supply_order_state', 'fields' => array())





* Visibility: **protected**
* This property is defined in [classes/stock/SupplyOrderState.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L88)


Methods
-------


### <a name="method-getSupplyOrderStates"></a>getSupplyOrderStates

    array SupplyOrderStateCore::getSupplyOrderStates(integer $id_state_referrer, integer $id_lang)

Gets the list of supply order statuses



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/SupplyOrderState.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L102)


#### Arguments
* $id_state_referrer **integer** - &lt;p&gt;Optional, used to know what state is available after this one&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional Id Language&lt;/p&gt;



### <a name="method-getStates"></a>getStates

    array SupplyOrderStateCore::getStates(array $ids, integer $id_lang)

Gets the list of supply order statuses



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/SupplyOrderState.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/SupplyOrderState.php#L154)


#### Arguments
* $ids **array** - &lt;p&gt;Optional Do not include these ids in the result&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional&lt;/p&gt;


