OrderHistoryCore
===============






* Class name: OrderHistoryCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_order

    public integer $id_order





* Visibility: **public**


### $id_order_state

    public integer $id_order_state





* Visibility: **public**


### $id_employee

    public integer $id_employee





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_history', 'primary' => 'id_order_history', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'order_histories', 'fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_order_state' => array('required' => true, 'xlink_resource' => 'order_states'), 'id_order' => array('xlink_resource' => 'orders')), 'objectMethods' => array('add' => 'addWs'))





* Visibility: **protected**


Methods
-------


### changeIdOrderState

    mixed OrderHistoryCore::changeIdOrderState(integer $new_order_state, \int/object $id_order, boolean $use_existing_payment)

Sets the new state of the given order



* Visibility: **public**


#### Arguments
* $new_order_state **integer**
* $id_order **int/object**
* $use_existing_payment **boolean**



### getLastOrderState

    \OrderState|boolean OrderHistoryCore::getLastOrderState(integer $id_order)

Returns the last order status



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **integer**



### addWithemail

    boolean OrderHistoryCore::addWithemail(boolean $autodate, array $template_vars, \Context $context)





* Visibility: **public**


#### Arguments
* $autodate **boolean** - &lt;p&gt;Optional&lt;/p&gt;
* $template_vars **array** - &lt;p&gt;Optional&lt;/p&gt;
* $context **Context** - &lt;p&gt;Deprecated&lt;/p&gt;



### sendEmail

    mixed OrderHistoryCore::sendEmail($order, $template_vars)





* Visibility: **public**


#### Arguments
* $order **mixed**
* $template_vars **mixed**



### add

    mixed OrderHistoryCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### isValidated

    integer OrderHistoryCore::isValidated()





* Visibility: **public**




### addWs

    boolean OrderHistoryCore::addWs()

Add method for webservice create resource Order History
If sendemail=1 GET parameter is present sends email to customer otherwise does not



* Visibility: **public**



