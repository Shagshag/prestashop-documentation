Class NotificationCore
=====================





* Class name: NotificationCore
* Source: [classes/Notification.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Notification.php#L28)


Contents
--------


### Properties

* [$types](#property-$types)

### Methods

* [__construct](#method-__construct)
* [getLastElements](#method-getLastElements)
* [getLastElementsIdsByType](#method-getLastElementsIdsByType)
* [installDb](#method-installDb)
* [updateEmployeeLastElement](#method-updateEmployeeLastElement)




Properties
----------


### <a name="property-$types"></a>$types

```php
public mixed $types
```





* Visibility: **public**
* Source: [classes/Notification.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Notification.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed NotificationCore::__construct()
```





* Visibility: **public**
* Source: [classes/Notification.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Notification.php#L32)




### <a name="method-getLastElements"></a>getLastElements

```php
array NotificationCore::getLastElements()
```

getLastElements return all the notifications (new order, new customer registration, and new customer message)
Get all the notifications



* Visibility: **public**
* Source: [classes/Notification.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Notification.php#L43)




### <a name="method-getLastElementsIdsByType"></a>getLastElementsIdsByType

```php
array NotificationCore::getLastElementsIdsByType(string $type, integer $id_last_element)
```

getLastElementsIdsByType return all the element ids to show (order, customer registration, and customer message)
Get all the element ids



* Visibility: **public**
* This method is **static**.
* Source: [classes/Notification.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Notification.php#L75)


#### Arguments
* $type **string** - contains the field name of the Employee table
* $id_last_element **integer** - contains the id of the last seen element



### <a name="method-installDb"></a>installDb

```php
mixed NotificationCore::installDb()
```





* Visibility: **public**
* Source: [classes/Notification.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Notification.php#L59)




### <a name="method-updateEmployeeLastElement"></a>updateEmployeeLastElement

```php
boolean NotificationCore::updateEmployeeLastElement(string $type)
```

updateEmployeeLastElement return 0 if the field doesn't exists in Employee table.

Updates the last seen element by the employee

* Visibility: **public**
* Source: [classes/Notification.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Notification.php#L143)


#### Arguments
* $type **string** - contains the field name of the Employee table


