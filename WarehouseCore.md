WarehouseCore
===============

Holds Stock




* Class name: WarehouseCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/stock/Warehouse.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#32)





Properties
----------


### $id

    public integer $id





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#35)


### $id_address

    public integer $id_address





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#38)


### $reference

    public string $reference





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#41)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#44)


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#47)


### $id_currency

    public integer $id_currency





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#50)


### $deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#53)


### $management_type

    public string $management_type

Describes the way a Warehouse is managed



* Visibility: **public**
* This property is defined in [classes/stock/Warehouse.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#60)


### $definition

    public mixed $definition = array('table' => 'warehouse', 'primary' => 'id_warehouse', 'fields' => array('id_address' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'management_type' => array('type' => self::TYPE_STRING, 'validate' => 'isStockManagement', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'deleted' => array('type' => self::TYPE_BOOL)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/Warehouse.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#65)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_address' => array('xlink_resource' => 'addresses'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_currency' => array('xlink_resource' => 'currencies'), 'valuation' => array('getter' => 'getWsStockValue', 'setter' => false), 'deleted' => array()), 'associations' => array('stocks' => array('resource' => 'stock', 'fields' => array('id' => array())), 'carriers' => array('resource' => 'carrier', 'fields' => array('id' => array())), 'shops' => array('resource' => 'shop', 'fields' => array('id' => array(), 'name' => array()))))





* Visibility: **protected**
* This property is defined in [classes/stock/Warehouse.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#82)


Methods
-------


### getShops

    array WarehouseCore::getShops()

Gets the shops associated to the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#118)




### getCarriers

    array WarehouseCore::getCarriers($return_reference)

Gets the carriers associated to the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#135)


#### Arguments
* $return_reference **mixed**



### setCarriers

    mixed WarehouseCore::setCarriers(array $ids_carriers)

Sets the carriers associated to the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#169)


#### Arguments
* $ids_carriers **array**



### removeCarrier

    mixed WarehouseCore::removeCarrier(integer $id_carrier, integer $id_warehouse)

For a given carrier, removes it from the warehouse/carrier association
If $id_warehouse is set, it only removes the carrier for this warehouse



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#196)


#### Arguments
* $id_carrier **integer** - &lt;p&gt;Id of the carrier to remove&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;optional Id of the warehouse to filter&lt;/p&gt;



### isEmpty

    boolean WarehouseCore::isEmpty()

Checks if a warehouse is empty - i.e. has no stock



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#209)




### exists

    boolean WarehouseCore::exists(integer $id_warehouse)

Checks if the given warehouse exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#224)


#### Arguments
* $id_warehouse **integer**



### setProductLocation

    boolean WarehouseCore::setProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse, string $location)

For a given {product, product attribute} sets its location in the given warehouse
First, for the given parameters, it cleans the database before updating



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#244)


#### Arguments
* $id_product **integer** - &lt;p&gt;ID of the product&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Use 0 if this product does not have attributes&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;ID of the warehouse&lt;/p&gt;
* $location **string** - &lt;p&gt;Describes the location (no lang id required)&lt;/p&gt;



### resetProductsLocations

    mixed WarehouseCore::resetProductsLocations()

Resets all product locations for this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#265)




### getProductLocation

    string WarehouseCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)

For a given {product, product attribute} gets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#280)


#### Arguments
* $id_product **integer** - &lt;p&gt;ID of the product&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Use 0 if this product does not have attributes&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;ID of the warehouse&lt;/p&gt;



### getProductWarehouseList

    array WarehouseCore::getProductWarehouseList(integer $id_product, integer $id_product_attribute, integer $id_shop)

For a given {product, product attribute} gets warehouse list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#300)


#### Arguments
* $id_product **integer** - &lt;p&gt;ID of the product&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Optional, uses 0 if this product does not have attributes&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional, ID of the shop. Uses the context shop id (@see Context::shop)&lt;/p&gt;



### getWarehouses

    array WarehouseCore::getWarehouses(boolean $ignore_shop, integer $id_shop)

Gets available warehouses
It is possible via ignore_shop and id_shop to filter the list with shop id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#344)


#### Arguments
* $ignore_shop **boolean** - &lt;p&gt;Optional, false by default - Allows to get only the warehouses that are associated to one/some shops (@see $id_shop)&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional, Context::shop::Id by default - Allows to define a specific shop to filter.&lt;/p&gt;



### getWarehousesGroupedByShops

    array WarehouseCore::getWarehousesGroupedByShops()

Gets warehouses grouped by shops



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#369)




### getNumberOfProducts

    integer WarehouseCore::getNumberOfProducts()

Gets the number of products in the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#390)




### getQuantitiesOfProducts

    integer WarehouseCore::getQuantitiesOfProducts()

Gets the number of quantities - for all products - in the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#410)




### getStockValue

    integer WarehouseCore::getStockValue()

Gets the value of the stock in the current warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#427)




### getWarehousesByEmployee

    array WarehouseCore::getWarehousesByEmployee(integer $id_employee)

For a given employee, gets the warehouse(s) he/she manages



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#443)


#### Arguments
* $id_employee **integer** - &lt;p&gt;Manager ID&lt;/p&gt;



### getWarehousesByProductId

    array WarehouseCore::getWarehousesByProductId(integer $id_product, integer $id_product_attribute)

For a given product, returns the warehouses it is stored in



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#460)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product Id&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Optional, Product Attribute Id - 0 by default (no attribues)&lt;/p&gt;



### getWarehouseNameById

    string WarehouseCore::getWarehouseNameById(integer $id_warehouse)

For a given $id_warehouse, returns its name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#487)


#### Arguments
* $id_warehouse **integer** - &lt;p&gt;Warehouse Id&lt;/p&gt;



### getPackWarehouses

    array|boolean WarehouseCore::getPackWarehouses(integer $id_product, $id_shop)

For a given pack, returns the warehouse it can be shipped from



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Warehouse.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#502)


#### Arguments
* $id_product **integer**
* $id_shop **mixed**



### resetStockAvailable

    mixed WarehouseCore::resetStockAvailable()





* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 547](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#547)




### getWsStockValue

    integer WarehouseCore::getWsStockValue()

Webservice : gets the value of the warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#565)




### getWsStocks

    array WarehouseCore::getWsStocks()

Webservice : gets the ids stock associated to this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#574)




### getWsShops

    array WarehouseCore::getWsShops()

Webservice : gets the ids shops associated to this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#588)




### getWsCarriers

    array WarehouseCore::getWsCarriers()

Webservice : gets the ids carriers associated to this warehouse



* Visibility: **public**
* This method is defined in [classes/stock/Warehouse.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Warehouse.php#604)



