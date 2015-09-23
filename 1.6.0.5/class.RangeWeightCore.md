Class RangeWeightCore
=====================





* Class name: RangeWeightCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/range/RangeWeight.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$delimiter1](#property-$delimiter1)
* [$delimiter2](#property-$delimiter2)
* [$id_carrier](#property-$id_carrier)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [getRanges](#method-getRanges)
* [isOverlapping](#method-isOverlapping)
* [rangeExist](#method-rangeExist)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'range_weight', 'primary' => 'id_range_weight', 'fields' => array('id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'delimiter1' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true), 'delimiter2' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/range/RangeWeight.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L36).


### <a name="property-$delimiter1"></a>$delimiter1

```php
public mixed $delimiter1
```





* Visibility: **public**
* Source: [classes/range/RangeWeight.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L30).


### <a name="property-$delimiter2"></a>$delimiter2

```php
public mixed $delimiter2
```





* Visibility: **public**
* Source: [classes/range/RangeWeight.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L31).


### <a name="property-$id_carrier"></a>$id_carrier

```php
public mixed $id_carrier
```





* Visibility: **public**
* Source: [classes/range/RangeWeight.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L29).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'weight_range', 'objectsNodeName' => 'weight_ranges', 'fields' => array('id_carrier' => array('xlink_resource' => 'carriers')))
```





* Visibility: **protected**
* Source: [classes/range/RangeWeight.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L46).


Methods
-------


### <a name="method-add"></a>add

```php
boolean RangeWeightCore::add(boolean $autodate, boolean $null_values)
```

Override add to create delivery value for all zones



* Visibility: **public**
* Source: [classes/range/RangeWeight.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L62)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-getRanges"></a>getRanges

```php
array RangeWeightCore::getRanges($id_carrier)
```

Get all available price ranges



* Visibility: **public**
* This method is **static**.
* Source: [classes/range/RangeWeight.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L87)


#### Arguments
* $id_carrier **mixed**



### <a name="method-isOverlapping"></a>isOverlapping

```php
mixed RangeWeightCore::isOverlapping($id_carrier, $delimiter1, $delimiter2, $id_rang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/range/RangeWeight.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L105)


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**
* $id_rang **mixed**



### <a name="method-rangeExist"></a>rangeExist

```php
mixed RangeWeightCore::rangeExist($id_carrier, $delimiter1, $delimiter2)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/range/RangeWeight.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/range/RangeWeight.php#L96)


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**


