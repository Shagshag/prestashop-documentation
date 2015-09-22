WarehouseProductLocationCore
===============






* Class name: WarehouseProductLocationCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/stock/WarehouseProductLocation.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L29)





Properties
----------

* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_warehouse](#property-$id_warehouse)
* [$location](#property-$location)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [getProductLocation](#method-getProductLocation)
* [getIdByProductAndWarehouse](#method-getIdByProductAndWarehouse)
* [getCollection](#method-getCollection)
* [getProducts](#method-getProducts)




Properties
----------


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L34)


### <a name="property-$id_product_attribute"></a>$id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L39)


### <a name="property-$id_warehouse"></a>$id_warehouse

    public integer $id_warehouse





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L44)


### <a name="property-$location"></a>$location

    public string $location





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L49)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'warehouse_product_location', 'primary' => 'id_warehouse_product_location', 'fields' => array('location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/WarehouseProductLocation.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L54)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_warehouse' => array('xlink_resource' => 'warehouses')), 'hidden_fields' => array())





* Visibility: **protected**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L68)


Methods
-------


### <a name="method-getProductLocation"></a>getProductLocation

    string WarehouseProductLocationCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)

For a given product and warehouse, gets the location



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L86)


#### Arguments
* $id_product **integer** - &lt;p&gt;product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;product attribute ID&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;warehouse ID&lt;/p&gt;



### <a name="method-getIdByProductAndWarehouse"></a>getIdByProductAndWarehouse

    integer WarehouseProductLocationCore::getIdByProductAndWarehouse(integer $id_product, integer $id_product_attribute, $id_warehouse)

For a given product and warehouse, gets the WarehouseProductLocation corresponding ID



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L108)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **mixed**



### <a name="method-getCollection"></a>getCollection

    \PrestaShopCollection WarehouseProductLocationCore::getCollection(integer $id_product)

For a given product, gets its warehouses



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L128)


#### Arguments
* $id_product **integer**



### <a name="method-getProducts"></a>getProducts

    mixed WarehouseProductLocationCore::getProducts($id_warehouse)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#L135)


#### Arguments
* $id_warehouse **mixed**


