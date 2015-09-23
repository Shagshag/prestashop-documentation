Class StockCore
=====================

Represents the products kept in warehouses



* Class name: StockCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/Stock.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L32)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$ean13](#property-$ean13)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_warehouse](#property-$id_warehouse)
* [$physical_quantity](#property-$physical_quantity)
* [$price_te](#property-$price_te)
* [$reference](#property-$reference)
* [$upc](#property-$upc)
* [$usable_quantity](#property-$usable_quantity)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [getProductInformations](#method-getProductInformations)
* [getWsRealQuantity](#method-getWsRealQuantity)
* [update](#method-update)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'stock', 'primary' => 'id_stock', 'fields' => array('id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'physical_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'usable_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/Stock.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L64).


### <a name="property-$ean13"></a>$ean13

```php
public integer $ean13
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L47).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L38).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L41).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L35).


### <a name="property-$physical_quantity"></a>$physical_quantity

```php
public integer $physical_quantity
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L53).


### <a name="property-$price_te"></a>$price_te

```php
public integer $price_te
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L59).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L44).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L50).


### <a name="property-$usable_quantity"></a>$usable_quantity

```php
public integer $usable_quantity
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L56).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'real_quantity' => array('getter' => 'getWsRealQuantity', 'setter' => false)), 'hidden_fields' => array())
```





* Visibility: **protected**
* Source: [classes/stock/Stock.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L83).


Methods
-------


### <a name="method-add"></a>add

```php
mixed StockCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L107)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-getProductInformations"></a>getProductInformations

```php
mixed StockCore::getProductInformations()
```

Gets reference, ean13 and upc of the current product
Stores it in stock for stock_mvt integrity and history purposes



* Visibility: **protected**
* Source: [classes/stock/Stock.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L118)




### <a name="method-getWsRealQuantity"></a>getWsRealQuantity

```php
mixed StockCore::getWsRealQuantity()
```

Webservice : used to get the real quantity of a product



* Visibility: **public**
* Source: [classes/stock/Stock.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L155)




### <a name="method-update"></a>update

```php
mixed StockCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/stock/Stock.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/stock/Stock.php#L97)


#### Arguments
* $null_values **mixed**


