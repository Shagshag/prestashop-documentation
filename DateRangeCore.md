DateRangeCore
===============






* Class name: DateRangeCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $time_start

    public mixed $time_start





* Visibility: **public**


### $time_end

    public mixed $time_end





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'date_range', 'primary' => 'id_date_range', 'fields' => array('time_start' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'time_end' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getCurrentRange

    mixed DateRangeCore::getCurrentRange()





* Visibility: **public**
* This method is **static**.



