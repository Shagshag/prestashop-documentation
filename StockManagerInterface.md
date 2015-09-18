StockManagerInterface
===============

StockManagerInterface : defines a way to manage stock




* Interface name: StockManagerInterface
* Namespace: 
* This is an **interface**






Methods
-------


### isAvailable

    \StockManagerInterface StockManagerInterface::isAvailable()

Checks if the StockManager is available



* Visibility: **public**
* This method is **static**.




### addProduct

    boolean StockManagerInterface::addProduct(integer $id_product, integer $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_movement_reason, float $price_te, boolean $is_usable, integer $id_supply_order)

For a given product, adds a given quantity



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $warehouse **Warehouse**
* $quantity **integer**
* $id_stock_movement_reason **integer**
* $price_te **float**
* $is_usable **boolean**
* $id_supply_order **integer** - &lt;p&gt;optionnal&lt;/p&gt;



### removeProduct

    array StockManagerInterface::removeProduct(integer $id_product, integer $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_movement_reason, boolean $is_usable, integer $id_order)

For a given product, removes a given quantity



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $warehouse **Warehouse**
* $quantity **integer**
* $id_stock_movement_reason **integer**
* $is_usable **boolean**
* $id_order **integer** - &lt;p&gt;Optionnal&lt;/p&gt;



### getProductPhysicalQuantities

    integer StockManagerInterface::getProductPhysicalQuantities(integer $id_product, integer $id_product_attribute, array|integer $ids_warehouse, boolean $usable)

For a given product, returns its physical quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $ids_warehouse **array|integer** - &lt;p&gt;optional&lt;/p&gt;
* $usable **boolean** - &lt;p&gt;false default - in this case we retrieve all physical quantities, otherwise we retrieve physical quantities flagged as usable&lt;/p&gt;



### getProductRealQuantities

    integer StockManagerInterface::getProductRealQuantities(integer $id_product, integer $id_product_attribute, array|integer $ids_warehouse, boolean $usable)

For a given product, returns its real quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations
Real quantity : (physical_qty + supply_orders_qty - client_orders_qty)
If $usable is defined, real quantity: usable_qty + supply_orders_qty - client_orders_qty



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $ids_warehouse **array|integer** - &lt;p&gt;optional&lt;/p&gt;
* $usable **boolean** - &lt;p&gt;false by default&lt;/p&gt;



### transferBetweenWarehouses

    boolean StockManagerInterface::transferBetweenWarehouses(integer $id_product, integer $id_product_attribute, integer $quantity, integer $warehouse_from, integer $warehouse_to, boolean $usable_from, boolean $usable_to)

For a given product, transfers quantities between two warehouses
By default, it manages usable quantities
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 2
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 1



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $quantity **integer**
* $warehouse_from **integer**
* $warehouse_to **integer**
* $usable_from **boolean** - &lt;p&gt;Optional, true by default&lt;/p&gt;
* $usable_to **boolean** - &lt;p&gt;Optional, true by default&lt;/p&gt;



### getProductCoverage

    integer StockManagerInterface::getProductCoverage(integer $id_product, integer $id_product_attribute, integer $coverage, integer $id_warehouse)

For a given product, returns the time left before being out of stock.

By default, for the given product, it will use sum(quantities removed in all warehouses)

* Visibility: **public**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**
* $id_warehouse **integer** - &lt;p&gt;Optional&lt;/p&gt;


