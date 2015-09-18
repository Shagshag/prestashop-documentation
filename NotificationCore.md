NotificationCore
===============






* Class name: NotificationCore
* Namespace: 





Properties
----------


### $types

    public mixed $types





* Visibility: **public**


Methods
-------


### __construct

    mixed NotificationCore::__construct()





* Visibility: **public**




### getLastElements

    array NotificationCore::getLastElements()

getLastElements return all the notifications (new order, new customer registration, and new customer message)
Get all the notifications



* Visibility: **public**




### getLastElementsIdsByType

    array NotificationCore::getLastElementsIdsByType(string $type, integer $id_last_element)

getLastElementsIdsByType return all the element ids to show (order, customer registration, and customer message)
Get all the element ids



* Visibility: **public**
* This method is **static**.


#### Arguments
* $type **string** - &lt;p&gt;contains the field name of the Employee table&lt;/p&gt;
* $id_last_element **integer** - &lt;p&gt;contains the id of the last seen element&lt;/p&gt;



### updateEmployeeLastElement

    boolean NotificationCore::updateEmployeeLastElement(string $type)

updateEmployeeLastElement return 0 if the field doesn't exists in Employee table.

Updates the last seen element by the employee

* Visibility: **public**


#### Arguments
* $type **string** - &lt;p&gt;contains the field name of the Employee table&lt;/p&gt;


