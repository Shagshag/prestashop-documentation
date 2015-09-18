WarehouseProductLocationCore
===============






* Class name: WarehouseProductLocationCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**


### $id_warehouse

    public integer $id_warehouse





* Visibility: **public**


### $location

    public string $location





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'warehouse_product_location', 'primary' => 'id_warehouse_product_location', 'fields' => array('location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_warehouse' => array('xlink_resource' => 'warehouses')), 'hidden_fields' => array())





* Visibility: **protected**


Methods
-------


### getProductLocation

    string WarehouseProductLocationCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)

For a given product and warehouse, gets the location



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;product attribute ID&lt;/p&gt;
* $id_warehouse **integer** - &lt;p&gt;warehouse ID&lt;/p&gt;



### getIdByProductAndWarehouse

    integer WarehouseProductLocationCore::getIdByProductAndWarehouse(integer $id_product, integer $id_product_attribute, $id_warehouse)

For a given product and warehouse, gets the WarehouseProductLocation corresponding ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **mixed**



### getCollection

    \PrestaShopCollection WarehouseProductLocationCore::getCollection(integer $id_product)

For a given product, gets its warehouses



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**



### getProducts

    mixed WarehouseProductLocationCore::getProducts($id_warehouse)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_warehouse **mixed**


