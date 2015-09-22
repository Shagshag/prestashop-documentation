WarehouseProductLocationCore
===============






* Class name: WarehouseProductLocationCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/stock/WarehouseProductLocation.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#29)





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#34)


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#39)


### $id_warehouse

    public integer $id_warehouse





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#44)


### $location

    public string $location





* Visibility: **public**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#49)


### $definition

    public mixed $definition = array('table' => 'warehouse_product_location', 'primary' => 'id_warehouse_product_location', 'fields' => array('location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/WarehouseProductLocation.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#54)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_warehouse' => array('xlink_resource' => 'warehouses')), 'hidden_fields' => array())





* Visibility: **protected**
* This property is defined in [classes/stock/WarehouseProductLocation.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#68)


Methods
-------


### getProductLocation

    string WarehouseProductLocationCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)

For a given product and warehouse, gets the location



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#86)


#### Arguments
* $id_product **integer** - &lt;p&gt;product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;product attribute ID&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;warehouse ID&lt;/p&gt;



### getIdByProductAndWarehouse

    integer WarehouseProductLocationCore::getIdByProductAndWarehouse(integer $id_product, integer $id_product_attribute, $id_warehouse)

For a given product and warehouse, gets the WarehouseProductLocation corresponding ID



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#108)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **mixed**



### getCollection

    \PrestaShopCollection WarehouseProductLocationCore::getCollection(integer $id_product)

For a given product, gets its warehouses



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#128)


#### Arguments
* $id_product **integer**



### getProducts

    mixed WarehouseProductLocationCore::getProducts($id_warehouse)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/WarehouseProductLocation.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/WarehouseProductLocation.php#135)


#### Arguments
* $id_warehouse **mixed**


