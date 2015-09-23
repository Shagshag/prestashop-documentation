Class OrderReturnStateCore
=====================





* Class name: OrderReturnStateCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderReturnState.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/order/OrderReturnState.php#L27)


Contents
--------


### Properties

* [$color](#property-$color)
* [$definition](#property-$definition)
* [$name](#property-$name)

### Methods

* [getOrderReturnStates](#method-getOrderReturnStates)




Properties
----------


### <a name="property-$color"></a>$color

```php
public string $color
```





* Visibility: **public**
* Source: [classes/order/OrderReturnState.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/order/OrderReturnState.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_return_state', 'primary' => 'id_order_return_state', 'multilang' => true, 'fields' => array('color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderReturnState.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/order/OrderReturnState.php#L38).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/order/OrderReturnState.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/order/OrderReturnState.php#L30).


Methods
-------


### <a name="method-getOrderReturnStates"></a>getOrderReturnStates

```php
array OrderReturnStateCore::getOrderReturnStates(integer $id_lang)
```

Get all available order statuses



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderReturnState.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/order/OrderReturnState.php#L56)


#### Arguments
* $id_lang **integer** - Language id for status name


