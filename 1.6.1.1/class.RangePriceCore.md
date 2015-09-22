Class RangePriceCore
=====================





* Class name: RangePriceCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/range/RangePrice.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L27)



Properties
----------

* [$definition](#property-$definition)
* [$delimiter1](#property-$delimiter1)
* [$delimiter2](#property-$delimiter2)
* [$id_carrier](#property-$id_carrier)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [add](#method-add)
* [getRanges](#method-getRanges)
* [isOverlapping](#method-isOverlapping)
* [rangeExist](#method-rangeExist)




Properties
----------


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'range_price', 'primary' => 'id_range_price', 'fields' => array('id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'delimiter1' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true), 'delimiter2' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/range/RangePrice.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L36)


### <a name="property-$delimiter1"></a>$delimiter1

    public mixed $delimiter1





* Visibility: **public**
* Source: [classes/range/RangePrice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L30)


### <a name="property-$delimiter2"></a>$delimiter2

    public mixed $delimiter2





* Visibility: **public**
* Source: [classes/range/RangePrice.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L31)


### <a name="property-$id_carrier"></a>$id_carrier

    public mixed $id_carrier





* Visibility: **public**
* Source: [classes/range/RangePrice.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L29)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'price_ranges', 'objectNodeName' => 'price_range', 'fields' => array('id_carrier' => array('xlink_resource' => 'carriers')))





* Visibility: **protected**
* Source: [classes/range/RangePrice.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L46)


Methods
-------


### <a name="method-add"></a>add

    boolean RangePriceCore::add(boolean $autodate, boolean $null_values)

Override add to create delivery value for all zones



* Visibility: **public**
* Source: [classes/range/RangePrice.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L62)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-getRanges"></a>getRanges

    array RangePriceCore::getRanges($id_carrier)

Get all available price ranges



* Visibility: **public**
* This method is **static**.
* Source: [classes/range/RangePrice.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L89)


#### Arguments
* $id_carrier **mixed**



### <a name="method-isOverlapping"></a>isOverlapping

    mixed RangePriceCore::isOverlapping($id_carrier, $delimiter1, $delimiter2, $id_rang)





* Visibility: **public**
* This method is **static**.
* Source: [classes/range/RangePrice.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L107)


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**
* $id_rang **mixed**



### <a name="method-rangeExist"></a>rangeExist

    mixed RangePriceCore::rangeExist($id_carrier, $delimiter1, $delimiter2)





* Visibility: **public**
* This method is **static**.
* Source: [classes/range/RangePrice.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/range/RangePrice.php#L98)


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**


