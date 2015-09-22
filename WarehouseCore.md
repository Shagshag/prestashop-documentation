WarehouseCore
===============

Holds Stock




* Class name: WarehouseCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/stock/Warehouse.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L32)





Properties
----------

* [$id](#property-$id)
* [$id_address](#property-$id_address)
* [$reference](#property-$reference)
* [$name](#property-$name)
* [$id_employee](#property-$id_employee)
* [$id_currency](#property-$id_currency)
* [$deleted](#property-$deleted)
* [$management_type](#property-$management_type)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [getShops](#method-getShops)
* [getCarriers](#method-getCarriers)
* [setCarriers](#method-setCarriers)
* [removeCarrier](#method-removeCarrier)
* [isEmpty](#method-isEmpty)
* [exists](#method-exists)
* [setProductLocation](#method-setProductLocation)
* [resetProductsLocations](#method-resetProductsLocations)
* [getProductLocation](#method-getProductLocation)
* [getProductWarehouseList](#method-getProductWarehouseList)
* [getWarehouses](#method-getWarehouses)
* [getWarehousesGroupedByShops](#method-getWarehousesGroupedByShops)
* [getNumberOfProducts](#method-getNumberOfProducts)
* [getQuantitiesOfProducts](#method-getQuantitiesOfProducts)
* [getStockValue](#method-getStockValue)
* [getWarehousesByEmployee](#method-getWarehousesByEmployee)
* [getWarehousesByProductId](#method-getWarehousesByProductId)
* [getWarehouseNameById](#method-getWarehouseNameById)
* [getPackWarehouses](#method-getPackWarehouses)
* [resetStockAvailable](#method-resetStockAvailable)
* [getWsStockValue](#method-getWsStockValue)
* [getWsStocks](#method-getWsStocks)
* [getWsShops](#method-getWsShops)
* [getWsCarriers](#method-getWsCarriers)




Properties
----------


### <a name="property-$id"></a>$id

    public integer $id





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L35)


### <a name="property-$id_address"></a>$id_address

    public integer $id_address





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L38)


### <a name="property-$reference"></a>$reference

    public string $reference





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L41)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L44)


### <a name="property-$id_employee"></a>$id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L47)


### <a name="property-$id_currency"></a>$id_currency

    public integer $id_currency





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L50)


### <a name="property-$deleted"></a>$deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L53)


### <a name="property-$management_type"></a>$management_type

    public string $management_type

Describes the way a Warehouse is managed



* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L60)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'warehouse', 'primary' => 'id_warehouse', 'fields' => array('id_address' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'management_type' => array('type' => self::TYPE_STRING, 'validate' => 'isStockManagement', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'deleted' => array('type' => self::TYPE_BOOL)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/Warehouse.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L65)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_address' => array('xlink_resource' => 'addresses'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_currency' => array('xlink_resource' => 'currencies'), 'valuation' => array('getter' => 'getWsStockValue', 'setter' => false), 'deleted' => array()), 'associations' => array('stocks' => array('resource' => 'stock', 'fields' => array('id' => array())), 'carriers' => array('resource' => 'carrier', 'fields' => array('id' => array())), 'shops' => array('resource' => 'shop', 'fields' => array('id' => array(), 'name' => array()))))





* Visibility: **protected**
* This property is defined in [classes/stock/Warehouse.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L82)


Methods
-------


### <a name="method-getShops"></a>getShops

    array WarehouseCore::getShops()

Gets the shops associated to the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L118)




### <a name="method-getCarriers"></a>getCarriers

    array WarehouseCore::getCarriers($return_reference)

Gets the carriers associated to the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L135)


#### Arguments
* $return_reference **mixed**



### <a name="method-setCarriers"></a>setCarriers

    mixed WarehouseCore::setCarriers(array $ids_carriers)

Sets the carriers associated to the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L169)


#### Arguments
* $ids_carriers **array**



### <a name="method-removeCarrier"></a>removeCarrier

    mixed WarehouseCore::removeCarrier(integer $id_carrier, integer $id_warehouse)

For a given carrier, removes it from the warehouse/carrier association
If $id_warehouse is set, it only removes the carrier for this warehouse



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L196)


#### Arguments
* $id_carrier **integer** - &lt;p&gt;Id of the carrier to remove&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;optional Id of the warehouse to filter&lt;/p&gt;



### <a name="method-isEmpty"></a>isEmpty

    boolean WarehouseCore::isEmpty()

Checks if a warehouse is empty - i.e. has no stock



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L209)




### <a name="method-exists"></a>exists

    boolean WarehouseCore::exists(integer $id_warehouse)

Checks if the given warehouse exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L224)


#### Arguments
* $id_warehouse **integer**



### <a name="method-setProductLocation"></a>setProductLocation

    boolean WarehouseCore::setProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse, string $location)

For a given {product, product attribute} sets its location in the given warehouse
First, for the given parameters, it cleans the database before updating



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L244)


#### Arguments
* $id_product **integer** - &lt;p&gt;ID of the product&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Use 0 if this product does not have attributes&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;ID of the warehouse&lt;/p&gt;
* $location **string** - &lt;p&gt;Describes the location (no lang id required)&lt;/p&gt;



### <a name="method-resetProductsLocations"></a>resetProductsLocations

    mixed WarehouseCore::resetProductsLocations()

Resets all product locations for this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L265)




### <a name="method-getProductLocation"></a>getProductLocation

    string WarehouseCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)

For a given {product, product attribute} gets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L280)


#### Arguments
* $id_product **integer** - &lt;p&gt;ID of the product&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Use 0 if this product does not have attributes&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;ID of the warehouse&lt;/p&gt;



### <a name="method-getProductWarehouseList"></a>getProductWarehouseList

    array WarehouseCore::getProductWarehouseList(integer $id_product, integer $id_product_attribute, integer $id_shop)

For a given {product, product attribute} gets warehouse list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L300)


#### Arguments
* $id_product **integer** - &lt;p&gt;ID of the product&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Optional, uses 0 if this product does not have attributes&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional, ID of the shop. Uses the context shop id (@see Context::shop)&lt;/p&gt;



### <a name="method-getWarehouses"></a>getWarehouses

    array WarehouseCore::getWarehouses(boolean $ignore_shop, integer $id_shop)

Gets available warehouses
It is possible via ignore_shop and id_shop to filter the list with shop id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L344)


#### Arguments
* $ignore_shop **boolean** - &lt;p&gt;Optional, false by default - Allows to get only the warehouses that are associated to one/some shops (@see $id_shop)&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional, Context::shop::Id by default - Allows to define a specific shop to filter.&lt;/p&gt;



### <a name="method-getWarehousesGroupedByShops"></a>getWarehousesGroupedByShops

    array WarehouseCore::getWarehousesGroupedByShops()

Gets warehouses grouped by shops



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L369)




### <a name="method-getNumberOfProducts"></a>getNumberOfProducts

    integer WarehouseCore::getNumberOfProducts()

Gets the number of products in the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L390)




### <a name="method-getQuantitiesOfProducts"></a>getQuantitiesOfProducts

    integer WarehouseCore::getQuantitiesOfProducts()

Gets the number of quantities - for all products - in the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L410)




### <a name="method-getStockValue"></a>getStockValue

    integer WarehouseCore::getStockValue()

Gets the value of the stock in the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L427)




### <a name="method-getWarehousesByEmployee"></a>getWarehousesByEmployee

    array WarehouseCore::getWarehousesByEmployee(integer $id_employee)

For a given employee, gets the warehouse(s) he/she manages



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L443)


#### Arguments
* $id_employee **integer** - &lt;p&gt;Manager ID&lt;/p&gt;



### <a name="method-getWarehousesByProductId"></a>getWarehousesByProductId

    array WarehouseCore::getWarehousesByProductId(integer $id_product, integer $id_product_attribute)

For a given product, returns the warehouses it is stored in



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L460)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product Id&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Optional, Product Attribute Id - 0 by default (no attribues)&lt;/p&gt;



### <a name="method-getWarehouseNameById"></a>getWarehouseNameById

    string WarehouseCore::getWarehouseNameById(integer $id_warehouse)

For a given $id_warehouse, returns its name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L487)


#### Arguments
* $id_warehouse **integer** - &lt;p&gt;Warehouse Id&lt;/p&gt;



### <a name="method-getPackWarehouses"></a>getPackWarehouses

    array|boolean WarehouseCore::getPackWarehouses(integer $id_product, $id_shop)

For a given pack, returns the warehouse it can be shipped from



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L502)


#### Arguments
* $id_product **integer**
* $id_shop **mixed**



### <a name="method-resetStockAvailable"></a>resetStockAvailable

    mixed WarehouseCore::resetStockAvailable()





* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 547](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L547)




### <a name="method-getWsStockValue"></a>getWsStockValue

    integer WarehouseCore::getWsStockValue()

Webservice : gets the value of the warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L565)




### <a name="method-getWsStocks"></a>getWsStocks

    array WarehouseCore::getWsStocks()

Webservice : gets the ids stock associated to this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L574)




### <a name="method-getWsShops"></a>getWsShops

    array WarehouseCore::getWsShops()

Webservice : gets the ids shops associated to this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L588)




### <a name="method-getWsCarriers"></a>getWsCarriers

    array WarehouseCore::getWsCarriers()

Webservice : gets the ids carriers associated to this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#L604)



