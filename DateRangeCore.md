DateRangeCore
===============






* Class name: DateRangeCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/DateRange.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L27)





Properties
----------

* [$time_start](#property-$time_start)
* [$time_end](#property-$time_end)
* [$definition](#property-$definition)

Methods
-------
* [getCurrentRange](#method-getCurrentRange)




Properties
----------


### <a name="property-$time_start"></a>$time_start

    public mixed $time_start





* Visibility: **public**
* This property is defined in [classes/DateRange.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L29)


### <a name="property-$time_end"></a>$time_end

    public mixed $time_end





* Visibility: **public**
* This property is defined in [classes/DateRange.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L30)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'date_range', 'primary' => 'id_date_range', 'fields' => array('time_start' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'time_end' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/DateRange.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L35)


Methods
-------


### <a name="method-getCurrentRange"></a>getCurrentRange

    mixed DateRangeCore::getCurrentRange()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/DateRange.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/DateRange.php#L44)



