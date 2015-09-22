Class DateRangeCore
=====================





* Class name: DateRangeCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/DateRange.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L27)



Properties
----------

* [$definition](#property-$definition)
* [$time_end](#property-$time_end)
* [$time_start](#property-$time_start)

Methods
-------
* [getCurrentRange](#method-getCurrentRange)




Properties
----------


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'date_range', 'primary' => 'id_date_range', 'fields' => array('time_start' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'time_end' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/DateRange.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L35)


### <a name="property-$time_end"></a>$time_end

    public mixed $time_end





* Visibility: **public**
* Source: [classes/DateRange.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L30)


### <a name="property-$time_start"></a>$time_start

    public mixed $time_start





* Visibility: **public**
* Source: [classes/DateRange.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L29)


Methods
-------


### <a name="method-getCurrentRange"></a>getCurrentRange

    mixed DateRangeCore::getCurrentRange()





* Visibility: **public**
* This method is **static**.
* Source: [classes/DateRange.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L44)



