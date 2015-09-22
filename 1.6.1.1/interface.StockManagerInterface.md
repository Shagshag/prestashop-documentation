Interface StockManagerInterface
=========================

StockManagerInterface : defines a way to manage stock



* Interface name: StockManagerInterface
* This is an **interface**
* Source: [classes/stock/StockManagerInterface.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L31)





Methods
-------
* [addProduct](#method-addProduct)
* [getProductCoverage](#method-getProductCoverage)
* [getProductPhysicalQuantities](#method-getProductPhysicalQuantities)
* [getProductRealQuantities](#method-getProductRealQuantities)
* [isAvailable](#method-isAvailable)
* [removeProduct](#method-removeProduct)
* [transferBetweenWarehouses](#method-transferBetweenWarehouses)






Methods
-------


### <a name="method-addProduct"></a>addProduct

    boolean StockManagerInterface::addProduct(integer $id_product, integer $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_movement_reason, float $price_te, boolean $is_usable, integer $id_supply_order)

For a given product, adds a given quantity



* Visibility: **public**
* Source: [classes/stock/StockManagerInterface.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L53)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $warehouse **[Warehouse](class.WarehouseCore)**
* $quantity **integer**
* $id_stock_movement_reason **integer**
* $price_te **float**
* $is_usable **boolean**
* $id_supply_order **integer** - optionnal



### <a name="method-getProductCoverage"></a>getProductCoverage

    integer StockManagerInterface::getProductCoverage(integer $id_product, integer $id_product_attribute, integer $coverage, integer $id_warehouse)

For a given product, returns the time left before being out of stock.

By default, for the given product, it will use sum(quantities removed in all warehouses)

* Visibility: **public**
* Source: [classes/stock/StockManagerInterface.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L122)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**
* $id_warehouse **integer** - Optional



### <a name="method-getProductPhysicalQuantities"></a>getProductPhysicalQuantities

    integer StockManagerInterface::getProductPhysicalQuantities(integer $id_product, integer $id_product_attribute, array|integer $ids_warehouse, boolean $usable)

For a given product, returns its physical quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations



* Visibility: **public**
* Source: [classes/stock/StockManagerInterface.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L79)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $ids_warehouse **array|integer** - optional
* $usable **boolean** - false default - in this case we retrieve all physical quantities, otherwise we retrieve physical quantities flagged as usable



### <a name="method-getProductRealQuantities"></a>getProductRealQuantities

    integer StockManagerInterface::getProductRealQuantities(integer $id_product, integer $id_product_attribute, array|integer $ids_warehouse, boolean $usable)

For a given product, returns its real quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations
Real quantity : (physical_qty + supply_orders_qty - client_orders_qty)
If $usable is defined, real quantity: usable_qty + supply_orders_qty - client_orders_qty



* Visibility: **public**
* Source: [classes/stock/StockManagerInterface.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L93)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $ids_warehouse **array|integer** - optional
* $usable **boolean** - false by default



### <a name="method-isAvailable"></a>isAvailable

    \StockManagerInterface StockManagerInterface::isAvailable()

Checks if the StockManager is available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockManagerInterface.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L38)




### <a name="method-removeProduct"></a>removeProduct

    array StockManagerInterface::removeProduct(integer $id_product, integer $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_movement_reason, boolean $is_usable, integer $id_order)

For a given product, removes a given quantity



* Visibility: **public**
* Source: [classes/stock/StockManagerInterface.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L67)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $warehouse **[Warehouse](class.WarehouseCore)**
* $quantity **integer**
* $id_stock_movement_reason **integer**
* $is_usable **boolean**
* $id_order **integer** - Optionnal



### <a name="method-transferBetweenWarehouses"></a>transferBetweenWarehouses

    boolean StockManagerInterface::transferBetweenWarehouses(integer $id_product, integer $id_product_attribute, integer $quantity, integer $warehouse_from, integer $warehouse_to, boolean $usable_from, boolean $usable_to)

For a given product, transfers quantities between two warehouses
By default, it manages usable quantities
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 2
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 1



* Visibility: **public**
* Source: [classes/stock/StockManagerInterface.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerInterface.php#L110)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $quantity **integer**
* $warehouse_from **integer**
* $warehouse_to **integer**
* $usable_from **boolean** - Optional, true by default
* $usable_to **boolean** - Optional, true by default

