RangePriceCore
===============






* Class name: RangePriceCore
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

    public mixed $definition = array('table' => 'range_price', 'primary' => 'id_range_price', 'fields' => array('id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'delimiter1' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true), 'delimiter2' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'price_ranges', 'objectNodeName' => 'price_range', 'fields' => array('id_carrier' => array('xlink_resource' => 'carriers')))





* Visibility: **protected**


Methods
-------


### add

    boolean RangePriceCore::add(boolean $autodate, boolean $null_values)

Override add to create delivery value for all zones



* Visibility: **public**


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### getRanges

    array RangePriceCore::getRanges($id_carrier)

Get all available price ranges



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**



### rangeExist

    mixed RangePriceCore::rangeExist($id_carrier, $delimiter1, $delimiter2)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**



### isOverlapping

    mixed RangePriceCore::isOverlapping($id_carrier, $delimiter1, $delimiter2, $id_rang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**
* $id_rang **mixed**


