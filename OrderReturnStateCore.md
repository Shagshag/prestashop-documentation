OrderReturnStateCore
===============






* Class name: OrderReturnStateCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\order\OrderReturnState.php line 27





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\order\OrderReturnState.php line 30


### $color

    public string $color





* Visibility: **public**
* This property is defined in classes\order\OrderReturnState.php line 33


### $definition

    public mixed $definition = array('table' => 'order_return_state', 'primary' => 'id_order_return_state', 'multilang' => true, 'fields' => array('color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\order\OrderReturnState.php line 38


Methods
-------


### getOrderReturnStates

    array OrderReturnStateCore::getOrderReturnStates(integer $id_lang)

Get all available order statuses



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\order\OrderReturnState.php line 56


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id for status name&lt;/p&gt;


