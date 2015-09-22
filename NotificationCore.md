NotificationCore
===============






* Class name: NotificationCore
* Namespace: 

* This class is defined in [classes/Notification.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Notification.php#27)





Properties
----------


### $types

    public mixed $types





* Visibility: **public**
* This property is defined in [classes/Notification.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Notification.php#29)


Methods
-------


### __construct

    mixed NotificationCore::__construct()





* Visibility: **public**
* This method is defined in [classes/Notification.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Notification.php#31)




### getLastElements

    array NotificationCore::getLastElements()

getLastElements return all the notifications (new order, new customer registration, and new customer message)
Get all the notifications



* Visibility: **public**
* This method is defined in [classes/Notification.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Notification.php#42)




### getLastElementsIdsByType

    array NotificationCore::getLastElementsIdsByType(string $type, integer $id_last_element)

getLastElementsIdsByType return all the element ids to show (order, customer registration, and customer message)
Get all the element ids



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Notification.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Notification.php#67)


#### Arguments
* $type **string** - &lt;p&gt;contains the field name of the Employee table&lt;/p&gt;
* $id_last_element **integer** - &lt;p&gt;contains the id of the last seen element&lt;/p&gt;



### updateEmployeeLastElement

    boolean NotificationCore::updateEmployeeLastElement(string $type)

updateEmployeeLastElement return 0 if the field doesn't exists in Employee table.

Updates the last seen element by the employee

* Visibility: **public**
* This method is defined in [classes/Notification.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Notification.php#136)


#### Arguments
* $type **string** - &lt;p&gt;contains the field name of the Employee table&lt;/p&gt;


