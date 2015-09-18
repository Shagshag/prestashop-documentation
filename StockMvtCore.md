StockMvtCore
===============






* Class name: StockMvtCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $id_employee

    public integer $id_employee





* Visibility: **public**


### $employee_firstname

    public string $employee_firstname





* Visibility: **public**


### $employee_lastname

    public string $employee_lastname





* Visibility: **public**


### $id_stock

    public integer $id_stock





* Visibility: **public**


### $physical_quantity

    public integer $physical_quantity





* Visibility: **public**


### $id_stock_mvt_reason

    public integer $id_stock_mvt_reason





* Visibility: **public**


### $id_order

    public integer $id_order = null





* Visibility: **public**


### $sign

    public integer $sign





* Visibility: **public**


### $id_supply_order

    public integer $id_supply_order = null





* Visibility: **public**


### $last_wa

    public float $last_wa = null





* Visibility: **public**


### $current_wa

    public float $current_wa = null





* Visibility: **public**


### $price_te

    public float $price_te





* Visibility: **public**


### $referer

    public integer $referer





* Visibility: **public**


### $date_upd

    public mixed $date_upd





* Visibility: **public**


### $quantity

    public integer $quantity





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'stock_mvt', 'primary' => 'id_stock_mvt', 'fields' => array('id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'employee_firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'employee_lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'id_stock' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'physical_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'id_stock_mvt_reason' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'sign' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'last_wa' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'current_wa' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'referer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'stock_movements', 'objectNodeName' => 'stock_movement', 'fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_stock' => array('xlink_resource' => 'stock'), 'id_stock_mvt_reason' => array('xlink_resource' => 'stock_movement_reasons'), 'id_order' => array('xlink_resource' => 'orders'), 'id_supply_order' => array('xlink_resource' => 'supply_order')))





* Visibility: **protected**


Methods
-------


### addMissingMvt

    mixed StockMvtCore::addMissingMvt($id_employee)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_employee **mixed**



### getNegativeStockMvts

    Array StockMvtCore::getNegativeStockMvts(integer $id_order, integer $id_product, integer $id_product_attribute, integer $quantity, integer $id_warehouse)

Gets the negative (decrements the stock) stock mvts that correspond to the given order, for :
the given product, in the given quantity.



* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Use 0 if the product does not have attributes&lt;/p&gt;


