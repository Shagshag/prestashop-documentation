Class DeliveryCore
=====================





* Class name: DeliveryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Delivery.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_carrier](#property-$id_carrier)
* [$id_delivery](#property-$id_delivery)
* [$id_range_price](#property-$id_range_price)
* [$id_range_weight](#property-$id_range_weight)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$id_zone](#property-$id_zone)
* [$price](#property-$price)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [getFields](#method-getFields)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'delivery', 'primary' => 'id_delivery', 'fields' => array('id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_range_price' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_range_weight' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_zone' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT), 'id_shop_group' => array('type' => self::TYPE_INT), 'price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Delivery.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L56).


### <a name="property-$id_carrier"></a>$id_carrier

```php
public integer $id_carrier
```





* Visibility: **public**
* Source: [classes/Delivery.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L39).


### <a name="property-$id_delivery"></a>$id_delivery

```php
public integer $id_delivery
```





* Visibility: **public**
* Source: [classes/Delivery.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L30).


### <a name="property-$id_range_price"></a>$id_range_price

```php
public integer $id_range_price
```





* Visibility: **public**
* Source: [classes/Delivery.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L42).


### <a name="property-$id_range_weight"></a>$id_range_weight

```php
public integer $id_range_weight
```





* Visibility: **public**
* Source: [classes/Delivery.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L45).


### <a name="property-$id_shop"></a>$id_shop

```php
public integer $id_shop
```





* Visibility: **public**
* Source: [classes/Delivery.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L33).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public integer $id_shop_group
```





* Visibility: **public**
* Source: [classes/Delivery.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L36).


### <a name="property-$id_zone"></a>$id_zone

```php
public integer $id_zone
```





* Visibility: **public**
* Source: [classes/Delivery.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L48).


### <a name="property-$price"></a>$price

```php
public float $price
```





* Visibility: **public**
* Source: [classes/Delivery.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L51).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'deliveries', 'fields' => array('id_carrier' => array('xlink_resource' => 'carriers'), 'id_range_price' => array('xlink_resource' => 'price_ranges'), 'id_range_weight' => array('xlink_resource' => 'weight_ranges'), 'id_zone' => array('xlink_resource' => 'zones')))
```





* Visibility: **protected**
* Source: [classes/Delivery.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L70).


Methods
-------


### <a name="method-getFields"></a>getFields

```php
mixed DeliveryCore::getFields()
```





* Visibility: **public**
* Source: [classes/Delivery.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Delivery.php#L80)



