Class StockMvtCore
=====================





* Class name: StockMvtCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/StockMvt.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L30)



Properties
----------

* [$current_wa](#property-$current_wa)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$employee_firstname](#property-$employee_firstname)
* [$employee_lastname](#property-$employee_lastname)
* [$id](#property-$id)
* [$id_employee](#property-$id_employee)
* [$id_order](#property-$id_order)
* [$id_stock](#property-$id_stock)
* [$id_stock_mvt_reason](#property-$id_stock_mvt_reason)
* [$id_supply_order](#property-$id_supply_order)
* [$last_wa](#property-$last_wa)
* [$physical_quantity](#property-$physical_quantity)
* [$price_te](#property-$price_te)
* [$quantity](#property-$quantity)
* [$referer](#property-$referer)
* [$sign](#property-$sign)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [addMissingMvt](#method-addMissingMvt)
* [getLastPositiveStockMvt](#method-getLastPositiveStockMvt)
* [getNegativeStockMvts](#method-getNegativeStockMvts)




Properties
----------


### <a name="property-$current_wa"></a>$current_wa

    public float $current_wa = null





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L100)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L37)


### <a name="property-$date_upd"></a>$date_upd

    public mixed $date_upd





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L118)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'stock_mvt', 'primary' => 'id_stock_mvt', 'fields' => array('id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'id_stock' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'physical_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'id_stock_mvt_reason' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'sign' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'last_wa' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'current_wa' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'referer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/StockMvt.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L130)


### <a name="property-$employee_firstname"></a>$employee_firstname

    public string $employee_firstname





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L48)


### <a name="property-$employee_lastname"></a>$employee_lastname

    public string $employee_lastname





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L54)


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L32)


### <a name="property-$id_employee"></a>$id_employee

    public integer $id_employee





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L42)


### <a name="property-$id_order"></a>$id_order

    public integer $id_order = null





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L76)


### <a name="property-$id_stock"></a>$id_stock

    public integer $id_stock





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L60)


### <a name="property-$id_stock_mvt_reason"></a>$id_stock_mvt_reason

    public integer $id_stock_mvt_reason





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L71)


### <a name="property-$id_supply_order"></a>$id_supply_order

    public integer $id_supply_order = null





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L88)


### <a name="property-$last_wa"></a>$last_wa

    public float $last_wa = null





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L94)


### <a name="property-$physical_quantity"></a>$physical_quantity

    public integer $physical_quantity





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L66)


### <a name="property-$price_te"></a>$price_te

    public float $price_te





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L106)


### <a name="property-$quantity"></a>$quantity

    public integer $quantity





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L125)


### <a name="property-$referer"></a>$referer

    public integer $referer





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L112)


### <a name="property-$sign"></a>$sign

    public integer $sign





* Visibility: **public**
* Source: [classes/stock/StockMvt.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L82)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'stock_movements', 'objectNodeName' => 'stock_movement', 'fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_stock' => array('xlink_resource' => 'stock'), 'id_stock_mvt_reason' => array('xlink_resource' => 'stock_movement_reasons'), 'id_order' => array('xlink_resource' => 'orders'), 'id_supply_order' => array('xlink_resource' => 'supply_order')))





* Visibility: **protected**
* Source: [classes/stock/StockMvt.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L151)


Methods
-------


### <a name="method-addMissingMvt"></a>addMissingMvt

    mixed StockMvtCore::addMissingMvt($id_employee)





* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvt.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L169)


#### Arguments
* $id_employee **mixed**



### <a name="method-getLastPositiveStockMvt"></a>getLastPositiveStockMvt

    boolean|array StockMvtCore::getLastPositiveStockMvt(integer $id_product, integer $id_product_attribute)

For a given product, gets the last positive stock mvt



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvt.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L232)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Use 0 if the product does not have attributes



### <a name="method-getNegativeStockMvts"></a>getNegativeStockMvts

    Array StockMvtCore::getNegativeStockMvts(integer $id_order, integer $id_product, integer $id_product_attribute, integer $quantity, integer $id_warehouse)

Gets the negative (decrements the stock) stock mvts that correspond to the given order, for :
the given product, in the given quantity.



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvt.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#L187)


#### Arguments
* $id_order **integer**
* $id_product **integer**
* $id_product_attribute **integer** - Use 0 if the product does not have attributes
* $quantity **integer**
* $id_warehouse **integer** - Optional


