StockMvtCore
===============






* Class name: StockMvtCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/stock/StockMvt.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#30)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#32)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#37)


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#42)


### $employee_firstname

    public string $employee_firstname





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#48)


### $employee_lastname

    public string $employee_lastname





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#54)


### $id_stock

    public integer $id_stock





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#60)


### $physical_quantity

    public integer $physical_quantity





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#66)


### $id_stock_mvt_reason

    public integer $id_stock_mvt_reason





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#71)


### $id_order

    public integer $id_order = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#76)


### $sign

    public integer $sign





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#82)


### $id_supply_order

    public integer $id_supply_order = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#88)


### $last_wa

    public float $last_wa = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#94)


### $current_wa

    public float $current_wa = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#100)


### $price_te

    public float $price_te





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#106)


### $referer

    public integer $referer





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#112)


### $date_upd

    public mixed $date_upd





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#118)


### $quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in [classes/stock/StockMvt.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#125)


### $definition

    public mixed $definition = array('table' => 'stock_mvt', 'primary' => 'id_stock_mvt', 'fields' => array('id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'id_stock' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'physical_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'id_stock_mvt_reason' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'sign' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'last_wa' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'current_wa' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'referer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/StockMvt.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#130)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'stock_movements', 'objectNodeName' => 'stock_movement', 'fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_stock' => array('xlink_resource' => 'stock'), 'id_stock_mvt_reason' => array('xlink_resource' => 'stock_movement_reasons'), 'id_order' => array('xlink_resource' => 'orders'), 'id_supply_order' => array('xlink_resource' => 'supply_order')))





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvt.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#151)


Methods
-------


### addMissingMvt

    mixed StockMvtCore::addMissingMvt($id_employee)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockMvt.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#169)


#### Arguments
* $id_employee **mixed**



### getNegativeStockMvts

    Array StockMvtCore::getNegativeStockMvts(integer $id_order, integer $id_product, integer $id_product_attribute, integer $quantity, integer $id_warehouse)

Gets the negative (decrements the stock) stock mvts that correspond to the given order, for :
the given product, in the given quantity.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockMvt.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#187)


#### Arguments
* $id_order **integer**
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Use 0 if the product does not have attributes&lt;/p&gt;
* $quantity **integer**
* $id_warehouse **integer** - &lt;p&gt;Optional&lt;/p&gt;



### getLastPositiveStockMvt

    boolean|array StockMvtCore::getLastPositiveStockMvt(integer $id_product, integer $id_product_attribute)

For a given product, gets the last positive stock mvt



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockMvt.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvt.php#232)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Use 0 if the product does not have attributes&lt;/p&gt;


