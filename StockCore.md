StockCore
===============

Represents the products kept in warehouses




* Class name: StockCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/stock/Stock.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L32)





Properties
----------

* [$id_warehouse](#property-$id_warehouse)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$reference](#property-$reference)
* [$ean13](#property-$ean13)
* [$upc](#property-$upc)
* [$physical_quantity](#property-$physical_quantity)
* [$usable_quantity](#property-$usable_quantity)
* [$price_te](#property-$price_te)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [update](#method-update)
* [add](#method-add)
* [getProductInformations](#method-getProductInformations)
* [getWsRealQuantity](#method-getWsRealQuantity)
* [deleteStockByIds](#method-deleteStockByIds)
* [productIsPresentInStock](#method-productIsPresentInStock)




Properties
----------


### <a name="property-$id_warehouse"></a>$id_warehouse

    public integer $id_warehouse





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L35)


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L38)


### <a name="property-$id_product_attribute"></a>$id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L41)


### <a name="property-$reference"></a>$reference

    public string $reference





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L44)


### <a name="property-$ean13"></a>$ean13

    public integer $ean13





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L47)


### <a name="property-$upc"></a>$upc

    public string $upc





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L50)


### <a name="property-$physical_quantity"></a>$physical_quantity

    public integer $physical_quantity





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L53)


### <a name="property-$usable_quantity"></a>$usable_quantity

    public integer $usable_quantity





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L56)


### <a name="property-$price_te"></a>$price_te

    public integer $price_te





* Visibility: **public**
* This property is defined in [classes/stock/Stock.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L59)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'stock', 'primary' => 'id_stock', 'fields' => array('id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'physical_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'usable_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/Stock.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L64)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_warehouse' => array('xlink_resource' => 'warehouses'), 'id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'real_quantity' => array('getter' => 'getWsRealQuantity', 'setter' => false)), 'hidden_fields' => array())





* Visibility: **protected**
* This property is defined in [classes/stock/Stock.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L83)


Methods
-------


### <a name="method-update"></a>update

    mixed StockCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/stock/Stock.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L97)


#### Arguments
* $null_values **mixed**



### <a name="method-add"></a>add

    mixed StockCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/stock/Stock.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L107)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-getProductInformations"></a>getProductInformations

    mixed StockCore::getProductInformations()

Gets reference, ean13 and upc of the current product
Stores it in stock for stock_mvt integrity and history purposes



* Visibility: **protected**
* This method is defined in [classes/stock/Stock.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L118)




### <a name="method-getWsRealQuantity"></a>getWsRealQuantity

    mixed StockCore::getWsRealQuantity()

Webservice : used to get the real quantity of a product



* Visibility: **public**
* This method is defined in [classes/stock/Stock.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L153)




### <a name="method-deleteStockByIds"></a>deleteStockByIds

    mixed StockCore::deleteStockByIds($id_product, $id_product_attribute)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Stock.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L160)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**



### <a name="method-productIsPresentInStock"></a>productIsPresentInStock

    mixed StockCore::productIsPresentInStock($id_product, $id_product_attribute, $id_warehouse)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/Stock.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/Stock.php#L169)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_warehouse **mixed**


