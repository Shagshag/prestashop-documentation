Class WarehouseCore
=====================

Holds Stock



* Class name: WarehouseCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/Warehouse.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L32)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$id](#property-$id)
* [$id_address](#property-$id_address)
* [$id_currency](#property-$id_currency)
* [$id_employee](#property-$id_employee)
* [$management_type](#property-$management_type)
* [$name](#property-$name)
* [$reference](#property-$reference)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [exists](#method-exists)
* [getCarriers](#method-getCarriers)
* [getNumberOfProducts](#method-getNumberOfProducts)
* [getPackWarehouses](#method-getPackWarehouses)
* [getProductLocation](#method-getProductLocation)
* [getProductWarehouseList](#method-getProductWarehouseList)
* [getQuantitiesOfProducts](#method-getQuantitiesOfProducts)
* [getShops](#method-getShops)
* [getStockValue](#method-getStockValue)
* [getWarehouseNameById](#method-getWarehouseNameById)
* [getWarehouses](#method-getWarehouses)
* [getWarehousesByEmployee](#method-getWarehousesByEmployee)
* [getWarehousesByProductId](#method-getWarehousesByProductId)
* [getWarehousesGroupedByShops](#method-getWarehousesGroupedByShops)
* [getWsCarriers](#method-getWsCarriers)
* [getWsShops](#method-getWsShops)
* [getWsStockValue](#method-getWsStockValue)
* [getWsStocks](#method-getWsStocks)
* [isEmpty](#method-isEmpty)
* [removeCarrier](#method-removeCarrier)
* [resetProductsLocations](#method-resetProductsLocations)
* [resetStockAvailable](#method-resetStockAvailable)
* [setCarriers](#method-setCarriers)
* [setProductLocation](#method-setProductLocation)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'warehouse', 'primary' => 'id_warehouse', 'fields' => array('id_address' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'management_type' => array('type' => self::TYPE_STRING, 'validate' => 'isStockManagement', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'deleted' => array('type' => self::TYPE_BOOL)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/Warehouse.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L65).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L53).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L35).


### <a name="property-$id_address"></a>$id_address

```php
public integer $id_address
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L38).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L50).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L47).


### <a name="property-$management_type"></a>$management_type

```php
public string $management_type
```

Describes the way a Warehouse is managed



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L60).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L44).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L41).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_address' => array('xlink_resource' => 'addresses'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_currency' => array('xlink_resource' => 'currencies'), 'valuation' => array('getter' => 'getWsStockValue', 'setter' => false), 'deleted' => array()), 'associations' => array('stocks' => array('resource' => 'stock', 'fields' => array('id' => array())), 'carriers' => array('resource' => 'carrier', 'fields' => array('id' => array())), 'shops' => array('resource' => 'shop', 'fields' => array('id' => array(), 'name' => array()))))
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L82).


Methods
-------


### <a name="method-exists"></a>exists

```php
boolean WarehouseCore::exists(integer $id_warehouse)
```

Checks if the given warehouse exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L217)


#### Arguments
* $id_warehouse **integer**



### <a name="method-getCarriers"></a>getCarriers

```php
array WarehouseCore::getCarriers($return_reference)
```

Gets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L135)


#### Arguments
* $return_reference **mixed**



### <a name="method-getNumberOfProducts"></a>getNumberOfProducts

```php
integer WarehouseCore::getNumberOfProducts()
```

Gets the number of products in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L382)




### <a name="method-getPackWarehouses"></a>getPackWarehouses

```php
array|boolean WarehouseCore::getPackWarehouses(integer $id_product, $id_shop)
```

For a given pack, returns the warehouse it can be shipped from



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 491](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L491)


#### Arguments
* $id_product **integer**
* $id_shop **mixed**



### <a name="method-getProductLocation"></a>getProductLocation

```php
string WarehouseCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)
```

For a given {product, product attribute} gets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L273)


#### Arguments
* $id_product **integer** - ID of the product
* $id_product_attribute **integer** - Use 0 if this product does not have attributes
* $id_warehouse **integer** - ID of the warehouse



### <a name="method-getProductWarehouseList"></a>getProductWarehouseList

```php
array WarehouseCore::getProductWarehouseList(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given {product, product attribute} gets warehouse list



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L293)


#### Arguments
* $id_product **integer** - ID of the product
* $id_product_attribute **integer** - Optional, uses 0 if this product does not have attributes
* $id_shop **integer** - Optional, ID of the shop. Uses the context shop id (@see Context::shop)



### <a name="method-getQuantitiesOfProducts"></a>getQuantitiesOfProducts

```php
integer WarehouseCore::getQuantitiesOfProducts()
```

Gets the number of quantities - for all products - in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L402)




### <a name="method-getShops"></a>getShops

```php
array WarehouseCore::getShops()
```

Gets the shops associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L118)




### <a name="method-getStockValue"></a>getStockValue

```php
integer WarehouseCore::getStockValue()
```

Gets the value of the stock in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L419)




### <a name="method-getWarehouseNameById"></a>getWarehouseNameById

```php
string WarehouseCore::getWarehouseNameById(integer $id_warehouse)
```

For a given $id_warehouse, returns its name



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L476)


#### Arguments
* $id_warehouse **integer** - Warehouse Id



### <a name="method-getWarehouses"></a>getWarehouses

```php
array WarehouseCore::getWarehouses(boolean $ignore_shop, integer $id_shop)
```

Gets available warehouses
It is possible via ignore_shop and id_shop to filter the list with shop id



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L340)


#### Arguments
* $ignore_shop **boolean** - Optional, false by default - Allows to get only the warehouses that are associated to one/some shops (@see $id_shop)
* $id_shop **integer** - Optional, Context::shop::Id by default - Allows to define a specific shop to filter.



### <a name="method-getWarehousesByEmployee"></a>getWarehousesByEmployee

```php
array WarehouseCore::getWarehousesByEmployee(integer $id_employee)
```

For a given employee, gets the warehouse(s) he/she manages



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L435)


#### Arguments
* $id_employee **integer** - Manager ID



### <a name="method-getWarehousesByProductId"></a>getWarehousesByProductId

```php
array WarehouseCore::getWarehousesByProductId(integer $id_product, integer $id_product_attribute)
```

For a given product, returns the warehouses it is stored in



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L452)


#### Arguments
* $id_product **integer** - Product Id
* $id_product_attribute **integer** - Optional, Product Attribute Id - 0 by default (no attribues)



### <a name="method-getWarehousesGroupedByShops"></a>getWarehousesGroupedByShops

```php
array WarehouseCore::getWarehousesGroupedByShops()
```

Gets warehouses grouped by shops



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L362)




### <a name="method-getWsCarriers"></a>getWsCarriers

```php
array WarehouseCore::getWsCarriers()
```

Webservice : gets the ids carriers associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 591](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L591)




### <a name="method-getWsShops"></a>getWsShops

```php
array WarehouseCore::getWsShops()
```

Webservice : gets the ids shops associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L575)




### <a name="method-getWsStockValue"></a>getWsStockValue

```php
integer WarehouseCore::getWsStockValue()
```

Webservice : gets the value of the warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L552)




### <a name="method-getWsStocks"></a>getWsStocks

```php
array WarehouseCore::getWsStocks()
```

Webservice : gets the ids stock associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L561)




### <a name="method-isEmpty"></a>isEmpty

```php
boolean WarehouseCore::isEmpty()
```

Checks if a warehouse is empty - i.e. has no stock



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L202)




### <a name="method-removeCarrier"></a>removeCarrier

```php
mixed WarehouseCore::removeCarrier(integer $id_carrier, integer $id_warehouse)
```

For a given carrier, removes it from the warehouse/carrier association
If $id_warehouse is set, it only removes the carrier for this warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L189)


#### Arguments
* $id_carrier **integer** - Id of the carrier to remove
* $id_warehouse **integer** - optional Id of the warehouse to filter



### <a name="method-resetProductsLocations"></a>resetProductsLocations

```php
mixed WarehouseCore::resetProductsLocations()
```

Resets all product locations for this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L258)




### <a name="method-resetStockAvailable"></a>resetStockAvailable

```php
mixed WarehouseCore::resetStockAvailable()
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L535)




### <a name="method-setCarriers"></a>setCarriers

```php
mixed WarehouseCore::setCarriers(array $ids_carriers)
```

Sets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L165)


#### Arguments
* $ids_carriers **array**



### <a name="method-setProductLocation"></a>setProductLocation

```php
boolean WarehouseCore::setProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse, string $location)
```

For a given {product, product attribute} sets its location in the given warehouse
First, for the given parameters, it cleans the database before updating



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/stock/Warehouse.php#L237)


#### Arguments
* $id_product **integer** - ID of the product
* $id_product_attribute **integer** - Use 0 if this product does not have attributes
* $id_warehouse **integer** - ID of the warehouse
* $location **string** - Describes the location (no lang id required)


