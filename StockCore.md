StockCore
===============

Represents the products kept in warehouses




* Class name: StockCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_warehouse

    public integer $id_warehouse





* Visibility: **public**


### $id_product

    public integer $id_product





* Visibility: **public**


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**


### $reference

    public string $reference





* Visibility: **public**


### $ean13

    public integer $ean13





* Visibility: **public**


### $upc

    public string $upc





* Visibility: **public**


### $physical_quantity

    public integer $physical_quantity





* Visibility: **public**


### $usable_quantity

    public integer $usable_quantity





* Visibility: **public**


### $price_te

    public integer $price_te





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'stock', 'primary' => 'id_stock', 'fields' => array('id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'physical_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'usable_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'real_quantity' => array('getter' => 'getWsRealQuantity', 'setter' => false)), 'hidden_fields' => array())





* Visibility: **protected**


Methods
-------


### update

    mixed StockCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### add

    mixed StockCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getProductInformations

    mixed StockCore::getProductInformations()

Gets reference, ean13 and upc of the current product
Stores it in stock for stock_mvt integrity and history purposes



* Visibility: **protected**




### getWsRealQuantity

    mixed StockCore::getWsRealQuantity()

Webservice : used to get the real quantity of a product



* Visibility: **public**




### deleteStockByIds

    mixed StockCore::deleteStockByIds($id_product, $id_product_attribute)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**



### productIsPresentInStock

    mixed StockCore::productIsPresentInStock($id_product, $id_product_attribute, $id_warehouse)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_warehouse **mixed**


