StockAvailableCore
===============

Represents quantities available
It is either synchronized with Stock or manualy set by the seller




* Class name: StockAvailableCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/stock/StockAvailable.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L33)





Properties
----------

* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$quantity](#property-$quantity)
* [$depends_on_stock](#property-$depends_on_stock)
* [$out_of_stock](#property-$out_of_stock)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [updateWs](#method-updateWs)
* [getStockAvailableIdByProductId](#method-getStockAvailableIdByProductId)
* [synchronize](#method-synchronize)
* [setProductDependsOnStock](#method-setProductDependsOnStock)
* [setProductOutOfStock](#method-setProductOutOfStock)
* [getQuantityAvailableByProduct](#method-getQuantityAvailableByProduct)
* [add](#method-add)
* [update](#method-update)
* [postSave](#method-postSave)
* [updateQuantity](#method-updateQuantity)
* [setQuantity](#method-setQuantity)
* [removeProductFromStockAvailable](#method-removeProductFromStockAvailable)
* [resetProductFromStockAvailableByShopGroup](#method-resetProductFromStockAvailableByShopGroup)
* [dependsOnStock](#method-dependsOnStock)
* [outOfStock](#method-outOfStock)
* [addSqlShopRestriction](#method-addSqlShopRestriction)
* [addSqlShopParams](#method-addSqlShopParams)
* [copyStockAvailableFromShopToShop](#method-copyStockAvailableFromShopToShop)




Properties
----------


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/stock/StockAvailable.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L36)


### <a name="property-$id_product_attribute"></a>$id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/stock/StockAvailable.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L39)


### <a name="property-$id_shop"></a>$id_shop

    public integer $id_shop





* Visibility: **public**
* This property is defined in [classes/stock/StockAvailable.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L42)


### <a name="property-$id_shop_group"></a>$id_shop_group

    public integer $id_shop_group





* Visibility: **public**
* This property is defined in [classes/stock/StockAvailable.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L45)


### <a name="property-$quantity"></a>$quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in [classes/stock/StockAvailable.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L48)


### <a name="property-$depends_on_stock"></a>$depends_on_stock

    public boolean $depends_on_stock = false





* Visibility: **public**
* This property is defined in [classes/stock/StockAvailable.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L51)


### <a name="property-$out_of_stock"></a>$out_of_stock

    public boolean $out_of_stock = false





* Visibility: **public**
* This property is defined in [classes/stock/StockAvailable.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L54)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'stock_available', 'primary' => 'id_stock_available', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'depends_on_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'out_of_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/StockAvailable.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L59)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_shop_group' => array('xlink_resource' => 'shop_groups')), 'hidden_fields' => array(), 'objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'))





* Visibility: **protected**
* This property is defined in [classes/stock/StockAvailable.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L76)


Methods
-------


### <a name="method-updateWs"></a>updateWs

    integer StockAvailableCore::updateWs()

For a given {id_product, id_product_attribute and id_shop}, gets the stock available id associated



* Visibility: **public**
* This method is defined in [classes/stock/StockAvailable.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L100)




### <a name="method-getStockAvailableIdByProductId"></a>getStockAvailableIdByProductId

    mixed StockAvailableCore::getStockAvailableIdByProductId($id_product, $id_product_attribute, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L108)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_shop **mixed**



### <a name="method-synchronize"></a>synchronize

    mixed StockAvailableCore::synchronize(integer $id_product, $order_id_shop)

For a given id_product, synchronizes StockAvailable::quantity with Stock::usable_quantity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L132)


#### Arguments
* $id_product **integer**
* $order_id_shop **mixed**



### <a name="method-setProductDependsOnStock"></a>setProductDependsOnStock

    mixed StockAvailableCore::setProductDependsOnStock(integer $id_product, integer $depends_on_stock, integer $id_shop, $id_product_attribute)

For a given id_product, sets if stock available depends on stock



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L286)


#### Arguments
* $id_product **integer**
* $depends_on_stock **integer** - &lt;p&gt;Optional : true by default&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional : gets context by default&lt;/p&gt;
* $id_product_attribute **mixed**



### <a name="method-setProductOutOfStock"></a>setProductOutOfStock

    mixed StockAvailableCore::setProductOutOfStock(integer $id_product, integer $out_of_stock, integer $id_shop, $id_product_attribute)

For a given id_product, sets if product is available out of stocks



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L322)


#### Arguments
* $id_product **integer**
* $out_of_stock **integer** - &lt;p&gt;Optional false by default&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional gets context by default&lt;/p&gt;
* $id_product_attribute **mixed**



### <a name="method-getQuantityAvailableByProduct"></a>getQuantityAvailableByProduct

    integer StockAvailableCore::getQuantityAvailableByProduct(integer $id_product, integer $id_product_attribute, integer $id_shop)

For a given id_product and id_product_attribute, gets its stock available



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L358)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional : gets context by default&lt;/p&gt;



### <a name="method-add"></a>add

    mixed StockAvailableCore::add($autodate, $null_values)

Upgrades total_quantity_available after having saved



* Visibility: **public**
* This method is defined in [classes/stock/StockAvailable.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L390)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-update"></a>update

    mixed StockAvailableCore::update($null_values)

Upgrades total_quantity_available after having update



* Visibility: **public**
* This method is defined in [classes/stock/StockAvailable.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L404)


#### Arguments
* $null_values **mixed**



### <a name="method-postSave"></a>postSave

    mixed StockAvailableCore::postSave()

Upgrades total_quantity_available after having saved



* Visibility: **public**
* This method is defined in [classes/stock/StockAvailable.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L419)




### <a name="method-updateQuantity"></a>updateQuantity

    mixed StockAvailableCore::updateQuantity(integer $id_product, integer $id_product_attribute, integer $delta_quantity, integer $id_shop)

For a given id_product and id_product_attribute updates the quantity available
If $avoid_parent_pack_update is true, then packs containing the given product won't be updated



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L461)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $delta_quantity **integer** - &lt;p&gt;The delta quantity to update&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional&lt;/p&gt;



### <a name="method-setQuantity"></a>setQuantity

    mixed StockAvailableCore::setQuantity(integer $id_product, integer $id_product_attribute, $quantity, integer $id_shop)

For a given id_product and id_product_attribute sets the quantity available



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 484](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L484)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $quantity **mixed**
* $id_shop **integer** - &lt;p&gt;Optional&lt;/p&gt;



### <a name="method-removeProductFromStockAvailable"></a>removeProductFromStockAvailable

    boolean StockAvailableCore::removeProductFromStockAvailable(integer $id_product, integer|null $id_product_attribute, \Shop|null $shop)

Removes a given product from the stock available



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L552)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer|null** - &lt;p&gt;Optional&lt;/p&gt;
* $shop **[Shop](ShopCore)|null** - &lt;p&gt;Shop id or shop object Optional&lt;/p&gt;



### <a name="method-resetProductFromStockAvailableByShopGroup"></a>resetProductFromStockAvailableByShopGroup

    mixed StockAvailableCore::resetProductFromStockAvailableByShopGroup(\ShopGroup $shop_group)

Removes all product quantities from all a group of shops
If stocks are shared, remoe all old available quantities for all shops of the group
Else remove all available quantities for the current group



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L611)


#### Arguments
* $shop_group **[ShopGroup](ShopGroupCore)** - &lt;p&gt;the ShopGroup object&lt;/p&gt;



### <a name="method-dependsOnStock"></a>dependsOnStock

    boolean StockAvailableCore::dependsOnStock(integer $id_product, integer $id_shop)

For a given product, tells if it depends on the physical (usable) stock



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 632](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L632)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - &lt;p&gt;Optional : gets context if null @see Context::getContext()&lt;/p&gt;



### <a name="method-outOfStock"></a>outOfStock

    boolean StockAvailableCore::outOfStock(integer $id_product, integer $id_shop)

For a given product, get its "out of stock" flag



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L656)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - &lt;p&gt;Optional : gets context if null @see Context::getContext()&lt;/p&gt;



### <a name="method-addSqlShopRestriction"></a>addSqlShopRestriction

    string|\DbQuery StockAvailableCore::addSqlShopRestriction(\DbQuery|string|null $sql, \Shop|integer|null $shop, string|null $alias)

Add an sql restriction for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 682](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L682)


#### Arguments
* $sql **[DbQuery](DbQueryCore)|string|null** - &lt;p&gt;Reference to the query object&lt;/p&gt;
* $shop **[Shop](ShopCore)|integer|null** - &lt;p&gt;Optional : The shop ID&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Optional : The current table alias&lt;/p&gt;



### <a name="method-addSqlShopParams"></a>addSqlShopParams

    mixed StockAvailableCore::addSqlShopParams(array $params, integer $id_shop)

Add sql params for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 736](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L736)


#### Arguments
* $params **array** - &lt;p&gt;Reference to the params array&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;Optional : The shop ID&lt;/p&gt;



### <a name="method-copyStockAvailableFromShopToShop"></a>copyStockAvailableFromShopToShop

    boolean StockAvailableCore::copyStockAvailableFromShopToShop(integer $src_shop_id, integer $dst_shop_id)

Copies stock available content table



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockAvailable.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L778)


#### Arguments
* $src_shop_id **integer**
* $dst_shop_id **integer**


