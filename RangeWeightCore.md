RangeWeightCore
===============






* Class name: RangeWeightCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_carrier

    public mixed $id_carrier





* Visibility: **public**


### $delimiter1

    public mixed $delimiter1





* Visibility: **public**


### $delimiter2

    public mixed $delimiter2





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'range_weight', 'primary' => 'id_range_weight', 'fields' => array('id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'delimiter1' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true), 'delimiter2' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'weight_range', 'objectsNodeName' => 'weight_ranges', 'fields' => array('id_carrier' => array('xlink_resource' => 'carriers')))





* Visibility: **protected**


Methods
-------


### add

    boolean RangeWeightCore::add(boolean $autodate, boolean $null_values)

Override add to create delivery value for all zones



* Visibility: **public**


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### getRanges

    array RangeWeightCore::getRanges($id_carrier)

Get all available price ranges



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**



### rangeExist

    mixed RangeWeightCore::rangeExist($id_carrier, $delimiter1, $delimiter2)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**



### isOverlapping

    mixed RangeWeightCore::isOverlapping($id_carrier, $delimiter1, $delimiter2, $id_rang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**
* $id_rang **mixed**


