StockManagerCore
===============

StockManager : implementation of StockManagerInterface




* Class name: StockManagerCore
* This class is defined in [classes/stock/StockManager.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L31)
* This class implements: [StockManagerInterface](StockManagerInterface)






Methods
-------
* [isAvailable](#method-isAvailable)
* [addProduct](#method-addProduct)
* [removeProduct](#method-removeProduct)
* [getProductPhysicalQuantities](#method-getProductPhysicalQuantities)
* [getProductRealQuantities](#method-getProductRealQuantities)
* [transferBetweenWarehouses](#method-transferBetweenWarehouses)
* [getProductCoverage](#method-getProductCoverage)
* [calculateWA](#method-calculateWA)
* [getStockCollection](#method-getStockCollection)
* [getStockByCarrier](#method-getStockByCarrier)






Methods
-------


### <a name="method-isAvailable"></a>isAvailable

    \StockManagerInterface StockManagerInterface::isAvailable()

Checks if the StockManager is available



* Visibility: **public**
* This method is **static**.
* This method is defined by [StockManagerInterface](StockManagerInterface)
* This method is defined in [classes/stock/StockManager.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L38)




### <a name="method-addProduct"></a>addProduct

    boolean StockManagerInterface::addProduct(integer $id_product, integer $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_movement_reason, float $price_te, boolean $is_usable, integer $id_supply_order)

For a given product, adds a given quantity



* Visibility: **public**
* This method is defined by [StockManagerInterface](StockManagerInterface)
* This method is defined in [classes/stock/StockManager.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L53)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $warehouse **[Warehouse](WarehouseCore)**
* $quantity **integer**
* $id_stock_movement_reason **integer**
* $price_te **float**
* $is_usable **boolean**
* $id_supply_order **integer** - &lt;p&gt;optionnal&lt;/p&gt;



### <a name="method-removeProduct"></a>removeProduct

    array StockManagerInterface::removeProduct(integer $id_product, integer $id_product_attribute, \Warehouse $warehouse, integer $quantity, integer $id_stock_movement_reason, boolean $is_usable, integer $id_order)

For a given product, removes a given quantity



* Visibility: **public**
* This method is defined by [StockManagerInterface](StockManagerInterface)
* This method is defined in [classes/stock/StockManager.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L67)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $warehouse **[Warehouse](WarehouseCore)**
* $quantity **integer**
* $id_stock_movement_reason **integer**
* $is_usable **boolean**
* $id_order **integer** - &lt;p&gt;Optionnal&lt;/p&gt;



### <a name="method-getProductPhysicalQuantities"></a>getProductPhysicalQuantities

    integer StockManagerInterface::getProductPhysicalQuantities(integer $id_product, integer $id_product_attribute, array|integer $ids_warehouse, boolean $usable)

For a given product, returns its physical quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations



* Visibility: **public**
* This method is defined by [StockManagerInterface](StockManagerInterface)
* This method is defined in [classes/stock/StockManager.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L79)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $ids_warehouse **array|integer** - &lt;p&gt;optional&lt;/p&gt;
* $usable **boolean** - &lt;p&gt;false default - in this case we retrieve all physical quantities, otherwise we retrieve physical quantities flagged as usable&lt;/p&gt;



### <a name="method-getProductRealQuantities"></a>getProductRealQuantities

    integer StockManagerInterface::getProductRealQuantities(integer $id_product, integer $id_product_attribute, array|integer $ids_warehouse, boolean $usable)

For a given product, returns its real quantity
If the given product has combinations and $id_product_attribute is null, returns the sum for all combinations
Real quantity : (physical_qty + supply_orders_qty - client_orders_qty)
If $usable is defined, real quantity: usable_qty + supply_orders_qty - client_orders_qty



* Visibility: **public**
* This method is defined by [StockManagerInterface](StockManagerInterface)
* This method is defined in [classes/stock/StockManager.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L93)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $ids_warehouse **array|integer** - &lt;p&gt;optional&lt;/p&gt;
* $usable **boolean** - &lt;p&gt;false by default&lt;/p&gt;



### <a name="method-transferBetweenWarehouses"></a>transferBetweenWarehouses

    boolean StockManagerInterface::transferBetweenWarehouses(integer $id_product, integer $id_product_attribute, integer $quantity, integer $warehouse_from, integer $warehouse_to, boolean $usable_from, boolean $usable_to)

For a given product, transfers quantities between two warehouses
By default, it manages usable quantities
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 2
It is also possible to transfer a usable quantity from warehouse 1 in an unusable quantity to warehouse 1



* Visibility: **public**
* This method is defined by [StockManagerInterface](StockManagerInterface)
* This method is defined in [classes/stock/StockManager.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L110)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $quantity **integer**
* $warehouse_from **integer**
* $warehouse_to **integer**
* $usable_from **boolean** - &lt;p&gt;Optional, true by default&lt;/p&gt;
* $usable_to **boolean** - &lt;p&gt;Optional, true by default&lt;/p&gt;



### <a name="method-getProductCoverage"></a>getProductCoverage

    integer StockManagerInterface::getProductCoverage(integer $id_product, integer $id_product_attribute, integer $coverage, integer $id_warehouse)

For a given product, returns the time left before being out of stock.

By default, for the given product, it will use sum(quantities removed in all warehouses)

* Visibility: **public**
* This method is defined by [StockManagerInterface](StockManagerInterface)
* This method is defined in [classes/stock/StockManager.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L122)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**
* $id_warehouse **integer** - &lt;p&gt;Optional&lt;/p&gt;



### <a name="method-calculateWA"></a>calculateWA

    integer StockManagerCore::calculateWA(\Stock|\PrestaShopCollection $stock, integer $quantity, float $price_te)

For a given stock, calculates its new WA(Weighted Average) price based on the new quantities and price
Formula : (physicalStock * lastCump + quantityToAdd * unitPrice) / (physicalStock + quantityToAdd)



* Visibility: **protected**
* This method is defined in [classes/stock/StockManager.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L778)


#### Arguments
* $stock **[Stock](StockCore)|[Stock](PrestaShopCollectionCore)**
* $quantity **integer**
* $price_te **float**



### <a name="method-getStockCollection"></a>getStockCollection

    \PrestaShopCollection StockManagerCore::getStockCollection(integer $id_product, integer $id_product_attribute, integer $id_warehouse, integer $price_te)

For a given product, retrieves the stock collection



* Visibility: **protected**
* This method is defined in [classes/stock/StockManager.php line 792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L792)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $price_te **integer** - &lt;p&gt;Optional&lt;/p&gt;



### <a name="method-getStockByCarrier"></a>getStockByCarrier

    integer StockManagerCore::getStockByCarrier(integer $id_product, integer $id_product_attribute, array $delivery_option)

For a given product, retrieves the stock in function of the delivery option



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockManager.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManager.php#L815)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;optional&lt;/p&gt;
* $delivery_option **array**


