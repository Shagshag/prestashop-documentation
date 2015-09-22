OrderHistoryCore
===============






* Class name: OrderHistoryCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/order/OrderHistory.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L27)





Properties
----------

* [$id_order](#property-$id_order)
* [$id_order_state](#property-$id_order_state)
* [$id_employee](#property-$id_employee)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [changeIdOrderState](#method-changeIdOrderState)
* [getLastOrderState](#method-getLastOrderState)
* [addWithemail](#method-addWithemail)
* [sendEmail](#method-sendEmail)
* [add](#method-add)
* [isValidated](#method-isValidated)
* [addWs](#method-addWs)




Properties
----------


### <a name="property-$id_order"></a>$id_order

    public integer $id_order





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L30)


### <a name="property-$id_order_state"></a>$id_order_state

    public integer $id_order_state





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L33)


### <a name="property-$id_employee"></a>$id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L36)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L39)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L42)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'order_history', 'primary' => 'id_order_history', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/order/OrderHistory.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L47)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'order_histories', 'fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_order_state' => array('required' => true, 'xlink_resource' => 'order_states'), 'id_order' => array('xlink_resource' => 'orders')), 'objectMethods' => array('add' => 'addWs'))





* Visibility: **protected**
* This property is defined in [classes/order/OrderHistory.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L61)


Methods
-------


### <a name="method-changeIdOrderState"></a>changeIdOrderState

    mixed OrderHistoryCore::changeIdOrderState(integer $new_order_state, \int/object $id_order, boolean $use_existing_payment)

Sets the new state of the given order



* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L80)


#### Arguments
* $new_order_state **integer**
* $id_order **int/object**
* $use_existing_payment **boolean**



### <a name="method-getLastOrderState"></a>getLastOrderState

    \OrderState|boolean OrderHistoryCore::getLastOrderState(integer $id_order)

Returns the last order status



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/OrderHistory.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L371)


#### Arguments
* $id_order **integer**



### <a name="method-addWithemail"></a>addWithemail

    boolean OrderHistoryCore::addWithemail(boolean $autodate, array $template_vars, \Context $context)





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L395)


#### Arguments
* $autodate **boolean** - &lt;p&gt;Optional&lt;/p&gt;
* $template_vars **array** - &lt;p&gt;Optional&lt;/p&gt;
* $context **[Context](ContextCore)** - &lt;p&gt;Deprecated&lt;/p&gt;



### <a name="method-sendEmail"></a>sendEmail

    mixed OrderHistoryCore::sendEmail($order, $template_vars)





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L410)


#### Arguments
* $order **mixed**
* $template_vars **mixed**



### <a name="method-add"></a>add

    mixed OrderHistoryCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L480)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-isValidated"></a>isValidated

    integer OrderHistoryCore::isValidated()





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L499)




### <a name="method-addWs"></a>addWs

    boolean OrderHistoryCore::addWs()

Add method for webservice create resource Order History
If sendemail=1 GET parameter is present sends email to customer otherwise does not



* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L514)



