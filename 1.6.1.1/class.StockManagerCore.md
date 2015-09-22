Class StockManagerCore
=====================

StockManager : implementation of StockManagerInterface



* Class name: StockManagerCore
* Source: [classes/stock/StockManager.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L31)
* This class implements: [StockManagerInterface](interface.StockManagerInterface.md)

Contents
--------



### Methods

* [addProduct](#method-addProduct)
* [calculateWA](#method-calculateWA)
* [getProductCoverage](#method-getProductCoverage)
* [getProductPhysicalQuantities](#method-getProductPhysicalQuantities)
* [getProductRealQuantities](#method-getProductRealQuantities)
* [getStockByCarrier](#method-getStockByCarrier)
* [getStockCollection](#method-getStockCollection)
* [isAvailable](#method-isAvailable)
* [removeProduct](#method-removeProduct)
* [transferBetweenWarehouses](#method-transferBetweenWarehouses)






Methods
-------


### <a name="method-addProduct"></a>addProduct

```php
boolean StockManagerCore::addProduct(integer $id_product, integer $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_mvt_reason, float $price_te, boolean $is_usable, integer|null $id_supply_order, \Employee|null $employee)
```

For a given product, adds a given quantity



* Visibility: **public**
* Source: [classes/stock/StockManager.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L58)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $warehouse **[Warehouse](class.WarehouseCore.md)**
* $quantity **integer**
* $id_stock_mvt_reason **integer**
* $price_te **float**
* $is_usable **boolean**
* $id_supply_order **integer|null**
* $employee **[Employee](class.EmployeeCore.md)|null**



### <a name="method-calculateWA"></a>calculateWA

```php
integer StockManagerCore::calculateWA(\Stock|\PrestaShopCollection $stock, integer $quantity, float $price_te)
```

For a given stock, calculates its new WA(Weighted Average) price based on the new quantities and price
Formula : (physicalStock * lastCump + quantityToAdd * unitPrice) / (physicalStock + quantityToAdd)



* Visibility: **protected**
* Source: [classes/stock/StockManager.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L778)


#### Arguments
* $stock **[Stock](class.StockCore.md)|[Stock](class.PrestaShopCollectionCore.md)**
* $quantity **integer**
* $price_te **float**



### <a name="method-getProductCoverage"></a>getProductCoverage

```php
integer StockManagerCore::getProductCoverage($id_product, $id_product_attribute, $coverage, $id_warehouse)
```

For a given product, returns the time left before being out of stock.

By default, for the given product, it will use sum(quantities removed in all warehouses)

* Visibility: **public**
* Source: [classes/stock/StockManager.php line 724](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L724)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $coverage **mixed**
* $id_warehouse **mixed**



### <a name="method-getProductPhysicalQuantities"></a>getProductPhysicalQuantities

```php
mixed StockManagerCore::getProductPhysicalQuantities($id_product, $id_product_attribute, $ids_warehouse, $usable)
```

For a given product, returns its physical quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations



* Visibility: **public**
* Source: [classes/stock/StockManager.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L514)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $ids_warehouse **mixed**
* $usable **mixed**



### <a name="method-getProductRealQuantities"></a>getProductRealQuantities

```php
mixed StockManagerCore::getProductRealQuantities($id_product, $id_product_attribute, $ids_warehouse, $usable)
```

For a given product, returns its real quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations
Real quantity : (physical_qty + supply_orders_qty - client_orders_qty)
If $usable is defined, real quantity: usable_qty + supply_orders_qty - client_orders_qty



* Visibility: **public**
* Source: [classes/stock/StockManager.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L549)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $ids_warehouse **mixed**
* $usable **mixed**



### <a name="method-getStockByCarrier"></a>getStockByCarrier

```php
integer StockManagerCore::getStockByCarrier(integer $id_product, integer $id_product_attribute, array $delivery_option)
```

For a given product, retrieves the stock in function of the delivery option



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockManager.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L815)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - optional
* $delivery_option **array**



### <a name="method-getStockCollection"></a>getStockCollection

```php
\PrestaShopCollection StockManagerCore::getStockCollection(integer $id_product, integer $id_product_attribute, integer $id_warehouse, integer $price_te)
```

For a given product, retrieves the stock collection



* Visibility: **protected**
* Source: [classes/stock/StockManager.php line 792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L792)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer** - Optional
* $price_te **integer** - Optional



### <a name="method-isAvailable"></a>isAvailable

```php
mixed StockManagerCore::isAvailable()
```

Checks if the StockManager is available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockManager.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L36)




### <a name="method-removeProduct"></a>removeProduct

```php
array StockManagerCore::removeProduct(integer $id_product, integer|null $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_mvt_reason, boolean $is_usable, integer|null $id_order, integer $ignore_pack, \Employee|null $employee)
```

For a given product, removes a given quantity



* Visibility: **public**
* Source: [classes/stock/StockManager.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L215)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer|null**
* $warehouse **[Warehouse](class.WarehouseCore.md)**
* $quantity **integer**
* $id_stock_mvt_reason **integer**
* $is_usable **boolean**
* $id_order **integer|null**
* $ignore_pack **integer**
* $employee **[Employee](class.EmployeeCore.md)|null**



### <a name="method-transferBetweenWarehouses"></a>transferBetweenWarehouses

```php
mixed StockManagerCore::transferBetweenWarehouses($id_product, $id_product_attribute, $quantity, $id_warehouse_from, $id_warehouse_to, $usable_from, $usable_to)
```

For a given product, transfers quantities between two warehouses
By default, it manages usable quantities
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 2
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 1



* Visibility: **public**
* Source: [classes/stock/StockManager.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L657)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $quantity **mixed**
* $id_warehouse_from **mixed**
* $id_warehouse_to **mixed**
* $usable_from **mixed**
* $usable_to **mixed**


