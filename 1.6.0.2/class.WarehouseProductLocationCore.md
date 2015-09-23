Class WarehouseProductLocationCore
=====================





* Class name: WarehouseProductLocationCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/WarehouseProductLocation.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L29)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_warehouse](#property-$id_warehouse)
* [$location](#property-$location)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [getCollection](#method-getCollection)
* [getIdByProductAndWarehouse](#method-getIdByProductAndWarehouse)
* [getProductLocation](#method-getProductLocation)
* [getProducts](#method-getProducts)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'warehouse_product_location', 'primary' => 'id_warehouse_product_location', 'fields' => array('location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/WarehouseProductLocation.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L54).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/stock/WarehouseProductLocation.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L34).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/stock/WarehouseProductLocation.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L39).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/stock/WarehouseProductLocation.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L44).


### <a name="property-$location"></a>$location

```php
public string $location
```





* Visibility: **public**
* Source: [classes/stock/WarehouseProductLocation.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L49).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_warehouse' => array('xlink_resource' => 'warehouses')), 'hidden_fields' => array())
```





* Visibility: **protected**
* Source: [classes/stock/WarehouseProductLocation.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L68).


Methods
-------


### <a name="method-getCollection"></a>getCollection

```php
\Collection WarehouseProductLocationCore::getCollection(integer $id_product)
```

For a given product, gets its warehouses



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/WarehouseProductLocation.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L128)


#### Arguments
* $id_product **integer**



### <a name="method-getIdByProductAndWarehouse"></a>getIdByProductAndWarehouse

```php
integer WarehouseProductLocationCore::getIdByProductAndWarehouse(integer $id_product, integer $id_product_attribute, $id_warehouse)
```

For a given product and warehouse, gets the WarehouseProductLocation corresponding ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/WarehouseProductLocation.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L108)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **mixed**



### <a name="method-getProductLocation"></a>getProductLocation

```php
string WarehouseProductLocationCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)
```

For a given product and warehouse, gets the location



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/WarehouseProductLocation.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L86)


#### Arguments
* $id_product **integer** - product ID
* $id_product_attribute **integer** - product attribute ID
* $id_warehouse **integer** - warehouse ID



### <a name="method-getProducts"></a>getProducts

```php
mixed WarehouseProductLocationCore::getProducts($id_warehouse)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/WarehouseProductLocation.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/stock/WarehouseProductLocation.php#L135)


#### Arguments
* $id_warehouse **mixed**


