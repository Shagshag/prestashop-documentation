OrderHistoryCore
===============






* Class name: OrderHistoryCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/order/OrderHistory.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#L27)





Properties
----------


### $id_order

    public integer $id_order





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#30)


### $id_order_state

    public integer $id_order_state





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#33)


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#36)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#39)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/order/OrderHistory.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#42)


### $definition

    public mixed $definition = array('table' => 'order_history', 'primary' => 'id_order_history', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/order/OrderHistory.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#47)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'order_histories', 'fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_order_state' => array('required' => true, 'xlink_resource' => 'order_states'), 'id_order' => array('xlink_resource' => 'orders')), 'objectMethods' => array('add' => 'addWs'))





* Visibility: **protected**
* This property is defined in [classes/order/OrderHistory.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#61)


Methods
-------


### changeIdOrderState

    mixed OrderHistoryCore::changeIdOrderState(integer $new_order_state, \int/object $id_order, boolean $use_existing_payment)

Sets the new state of the given order



* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#80)


#### Arguments
* $new_order_state **integer**
* $id_order **int/object**
* $use_existing_payment **boolean**



### getLastOrderState

    \OrderState|boolean OrderHistoryCore::getLastOrderState(integer $id_order)

Returns the last order status



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/OrderHistory.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#371)


#### Arguments
* $id_order **integer**



### addWithemail

    boolean OrderHistoryCore::addWithemail(boolean $autodate, array $template_vars, \Context $context)





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#395)


#### Arguments
* $autodate **boolean** - &lt;p&gt;Optional&lt;/p&gt;
* $template_vars **array** - &lt;p&gt;Optional&lt;/p&gt;
* $context **[Context](ContextCore)** - &lt;p&gt;Deprecated&lt;/p&gt;



### sendEmail

    mixed OrderHistoryCore::sendEmail($order, $template_vars)





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#410)


#### Arguments
* $order **mixed**
* $template_vars **mixed**



### add

    mixed OrderHistoryCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#480)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### isValidated

    integer OrderHistoryCore::isValidated()





* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#499)




### addWs

    boolean OrderHistoryCore::addWs()

Add method for webservice create resource Order History
If sendemail=1 GET parameter is present sends email to customer otherwise does not



* Visibility: **public**
* This method is defined in [classes/order/OrderHistory.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderHistory.php#514)



