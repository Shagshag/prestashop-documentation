OrderReturnStateCore
===============






* Class name: OrderReturnStateCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $color

    public string $color





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_return_state', 'primary' => 'id_order_return_state', 'multilang' => true, 'fields' => array('color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getOrderReturnStates

    array OrderReturnStateCore::getOrderReturnStates(integer $id_lang)

Get all available order statuses



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id for status name&lt;/p&gt;


