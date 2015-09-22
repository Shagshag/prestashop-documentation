StockAvailableCore
===============

Represents quantities available
It is either synchronized with Stock or manualy set by the seller




* Class name: StockAvailableCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\stock\StockAvailable.php line 33





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in classes\stock\StockAvailable.php line 36


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in classes\stock\StockAvailable.php line 39


### $id_shop

    public integer $id_shop





* Visibility: **public**
* This property is defined in classes\stock\StockAvailable.php line 42


### $id_shop_group

    public integer $id_shop_group





* Visibility: **public**
* This property is defined in classes\stock\StockAvailable.php line 45


### $quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in classes\stock\StockAvailable.php line 48


### $depends_on_stock

    public boolean $depends_on_stock = false





* Visibility: **public**
* This property is defined in classes\stock\StockAvailable.php line 51


### $out_of_stock

    public boolean $out_of_stock = false





* Visibility: **public**
* This property is defined in classes\stock\StockAvailable.php line 54


### $definition

    public mixed $definition = array('table' => 'stock_available', 'primary' => 'id_stock_available', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'depends_on_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'out_of_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\stock\StockAvailable.php line 59


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_shop_group' => array('xlink_resource' => 'shop_groups')), 'hidden_fields' => array(), 'objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'))





* Visibility: **protected**
* This property is defined in classes\stock\StockAvailable.php line 76


Methods
-------


### updateWs

    integer StockAvailableCore::updateWs()

For a given {id_product, id_product_attribute and id_shop}, gets the stock available id associated



* Visibility: **public**
* This method is defined in classes\stock\StockAvailable.php line 100




### getStockAvailableIdByProductId

    mixed StockAvailableCore::getStockAvailableIdByProductId($id_product, $id_product_attribute, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 108


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_shop **mixed**



### synchronize

    mixed StockAvailableCore::synchronize(integer $id_product, $order_id_shop)

For a given id_product, synchronizes StockAvailable::quantity with Stock::usable_quantity



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 132


#### Arguments
* $id_product **integer**
* $order_id_shop **mixed**



### setProductDependsOnStock

    mixed StockAvailableCore::setProductDependsOnStock(integer $id_product, integer $depends_on_stock, integer $id_shop, $id_product_attribute)

For a given id_product, sets if stock available depends on stock



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 286


#### Arguments
* $id_product **integer**
* $depends_on_stock **integer** - &lt;p&gt;Optional : true by default&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional : gets context by default&lt;/p&gt;
* $id_product_attribute **mixed**



### setProductOutOfStock

    mixed StockAvailableCore::setProductOutOfStock(integer $id_product, integer $out_of_stock, integer $id_shop, $id_product_attribute)

For a given id_product, sets if product is available out of stocks



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 322


#### Arguments
* $id_product **integer**
* $out_of_stock **integer** - &lt;p&gt;Optional false by default&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional gets context by default&lt;/p&gt;
* $id_product_attribute **mixed**



### getQuantityAvailableByProduct

    integer StockAvailableCore::getQuantityAvailableByProduct(integer $id_product, integer $id_product_attribute, integer $id_shop)

For a given id_product and id_product_attribute, gets its stock available



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 358


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional : gets context by default&lt;/p&gt;



### add

    mixed StockAvailableCore::add($autodate, $null_values)

Upgrades total_quantity_available after having saved



* Visibility: **public**
* This method is defined in classes\stock\StockAvailable.php line 390


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed StockAvailableCore::update($null_values)

Upgrades total_quantity_available after having update



* Visibility: **public**
* This method is defined in classes\stock\StockAvailable.php line 404


#### Arguments
* $null_values **mixed**



### postSave

    mixed StockAvailableCore::postSave()

Upgrades total_quantity_available after having saved



* Visibility: **public**
* This method is defined in classes\stock\StockAvailable.php line 419




### updateQuantity

    mixed StockAvailableCore::updateQuantity(integer $id_product, integer $id_product_attribute, integer $delta_quantity, integer $id_shop)

For a given id_product and id_product_attribute updates the quantity available
If $avoid_parent_pack_update is true, then packs containing the given product won't be updated



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 461


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $delta_quantity **integer** - &lt;p&gt;The delta quantity to update&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional&lt;/p&gt;



### setQuantity

    mixed StockAvailableCore::setQuantity(integer $id_product, integer $id_product_attribute, $quantity, integer $id_shop)

For a given id_product and id_product_attribute sets the quantity available



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 484


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $quantity **mixed**
* $id_shop **integer** - &lt;p&gt;Optional&lt;/p&gt;



### removeProductFromStockAvailable

    boolean StockAvailableCore::removeProductFromStockAvailable(integer $id_product, integer|null $id_product_attribute, \Shop|null $shop)

Removes a given product from the stock available



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 552


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer|null** - &lt;p&gt;Optional&lt;/p&gt;
* $shop **[Shop](ShopCore)|null** - &lt;p&gt;Shop id or shop object Optional&lt;/p&gt;



### resetProductFromStockAvailableByShopGroup

    mixed StockAvailableCore::resetProductFromStockAvailableByShopGroup(\ShopGroup $shop_group)

Removes all product quantities from all a group of shops
If stocks are shared, remoe all old available quantities for all shops of the group
Else remove all available quantities for the current group



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 611


#### Arguments
* $shop_group **[ShopGroup](ShopGroupCore)** - &lt;p&gt;the ShopGroup object&lt;/p&gt;



### dependsOnStock

    boolean StockAvailableCore::dependsOnStock(integer $id_product, integer $id_shop)

For a given product, tells if it depends on the physical (usable) stock



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 632


#### Arguments
* $id_product **integer**
* $id_shop **integer** - &lt;p&gt;Optional : gets context if null @see Context::getContext()&lt;/p&gt;



### outOfStock

    boolean StockAvailableCore::outOfStock(integer $id_product, integer $id_shop)

For a given product, get its "out of stock" flag



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 656


#### Arguments
* $id_product **integer**
* $id_shop **integer** - &lt;p&gt;Optional : gets context if null @see Context::getContext()&lt;/p&gt;



### addSqlShopRestriction

    string|\DbQuery StockAvailableCore::addSqlShopRestriction(\DbQuery|string|null $sql, \Shop|integer|null $shop, string|null $alias)

Add an sql restriction for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 682


#### Arguments
* $sql **[DbQuery](DbQueryCore)|string|null** - &lt;p&gt;Reference to the query object&lt;/p&gt;
* $shop **[Shop](ShopCore)|integer|null** - &lt;p&gt;Optional : The shop ID&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Optional : The current table alias&lt;/p&gt;



### addSqlShopParams

    mixed StockAvailableCore::addSqlShopParams(array $params, integer $id_shop)

Add sql params for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 736


#### Arguments
* $params **array** - &lt;p&gt;Reference to the params array&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional : The shop ID&lt;/p&gt;



### copyStockAvailableFromShopToShop

    boolean StockAvailableCore::copyStockAvailableFromShopToShop(integer $src_shop_id, integer $dst_shop_id)

Copies stock available content table



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockAvailable.php line 778


#### Arguments
* $src_shop_id **integer**
* $dst_shop_id **integer**


