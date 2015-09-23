Class SupplyOrderReceiptHistoryCore
=====================

History of receipts



* Class name: SupplyOrderReceiptHistoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L31)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$employee_firstname](#property-$employee_firstname)
* [$employee_lastname](#property-$employee_lastname)
* [$id_employee](#property-$id_employee)
* [$id_supply_order_detail](#property-$id_supply_order_detail)
* [$id_supply_order_state](#property-$id_supply_order_state)
* [$quantity](#property-$quantity)
* [$webserviceParameters](#property-$webserviceParameters)





Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L66).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supply_order_receipt_history', 'primary' => 'id_supply_order_receipt_history', 'fields' => array('id_supply_order_detail' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supply_order_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L71).


### <a name="property-$employee_firstname"></a>$employee_firstname

```php
public string $employee_firstname
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L46).


### <a name="property-$employee_lastname"></a>$employee_lastname

```php
public string $employee_lastname
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L51).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L41).


### <a name="property-$id_supply_order_detail"></a>$id_supply_order_detail

```php
public integer $id_supply_order_detail
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L36).


### <a name="property-$id_supply_order_state"></a>$id_supply_order_state

```php
public integer $id_supply_order_state
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L56).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L61).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_receipt_histories', 'objectNodeName' => 'supply_order_receipt_history', 'fields' => array('id_supply_order_detail' => array('xlink_resource' => 'supply_order_details'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_supply_order_state' => array('xlink_resource' => 'supply_order_states')))
```





* Visibility: **protected**
* Source: [classes/stock/SupplyOrderReceiptHistory.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/stock/SupplyOrderReceiptHistory.php#L88).



