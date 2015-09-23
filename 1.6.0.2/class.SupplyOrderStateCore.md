Class SupplyOrderStateCore
=====================





* Class name: SupplyOrderStateCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/SupplyOrderState.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L30)


Contents
--------


### Properties

* [$color](#property-$color)
* [$definition](#property-$definition)
* [$delivery_note](#property-$delivery_note)
* [$editable](#property-$editable)
* [$enclosed](#property-$enclosed)
* [$name](#property-$name)
* [$pending_receipt](#property-$pending_receipt)
* [$receipt_state](#property-$receipt_state)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [getStates](#method-getStates)
* [getSupplyOrderStates](#method-getSupplyOrderStates)




Properties
----------


### <a name="property-$color"></a>$color

```php
public string $color
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderState.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L65).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supply_order_state', 'primary' => 'id_supply_order_state', 'multilang' => true, 'fields' => array('delivery_note' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'editable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'receipt_state' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'pending_receipt' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'enclosed' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/SupplyOrderState.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L70).


### <a name="property-$delivery_note"></a>$delivery_note

```php
public boolean $delivery_note
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderState.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L40).


### <a name="property-$editable"></a>$editable

```php
public boolean $editable
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderState.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L45).


### <a name="property-$enclosed"></a>$enclosed

```php
public boolean $enclosed
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderState.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L60).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderState.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L35).


### <a name="property-$pending_receipt"></a>$pending_receipt

```php
public boolean $pending_receipt
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderState.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L55).


### <a name="property-$receipt_state"></a>$receipt_state

```php
public boolean $receipt_state
```





* Visibility: **public**
* Source: [classes/stock/SupplyOrderState.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L50).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_states', 'objectNodeName' => 'supply_order_state', 'fields' => array())
```





* Visibility: **protected**
* Source: [classes/stock/SupplyOrderState.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L88).


Methods
-------


### <a name="method-getStates"></a>getStates

```php
array SupplyOrderStateCore::getStates(array $ids, integer $id_lang)
```

Gets the list of supply order states



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrderState.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L152)


#### Arguments
* $ids **array** - Optional Do not include these ids in the result
* $id_lang **integer** - Optional



### <a name="method-getSupplyOrderStates"></a>getSupplyOrderStates

```php
array SupplyOrderStateCore::getSupplyOrderStates(integer $id_state_referrer, integer $id_lang)
```

Gets the list of supply order states



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/SupplyOrderState.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/SupplyOrderState.php#L102)


#### Arguments
* $id_state_referrer **integer** - Optional, used to know what state is available after this one
* $id_lang **integer** - Optional Id Language


