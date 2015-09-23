Class SupplyOrderHistoryCore
=====================





* Class name: SupplyOrderHistoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/SupplyOrderHistory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L30)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$employee_firstname](#property-$employee_firstname)
* [$employee_lastname](#property-$employee_lastname)
* [$id_employee](#property-$id_employee)
* [$id_state](#property-$id_state)
* [$id_supply_order](#property-$id_supply_order)
* [$webserviceParameters](#property-$webserviceParameters)





Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderHistory.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L60).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supply_order_history', 'primary' => 'id_supply_order_history', 'fields' => array('id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/SupplyOrderHistory.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L65).


### <a name="property-$employee_firstname"></a>$employee_firstname

```php
public string $employee_firstname
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderHistory.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L45).


### <a name="property-$employee_lastname"></a>$employee_lastname

```php
public string $employee_lastname
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderHistory.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L50).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderHistory.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L40).


### <a name="property-$id_state"></a>$id_state

```php
public integer $id_state
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderHistory.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L55).


### <a name="property-$id_supply_order"></a>$id_supply_order

```php
public integer $id_supply_order
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderHistory.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L35).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_histories', 'objectNodeName' => 'supply_order_history', 'fields' => array('id_supply_order' => array('xlink_resource' => 'supply_orders'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_state' => array('xlink_resource' => 'supply_order_states')))
```





* Visibility: **protected**
* Source: [classes/stock/SupplyOrderHistory.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/SupplyOrderHistory.php#L81).



