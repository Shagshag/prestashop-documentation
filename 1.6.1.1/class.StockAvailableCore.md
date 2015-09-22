Class StockAvailableCore
=====================

Represents quantities available
It is either synchronized with Stock or manualy set by the seller



* Class name: StockAvailableCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/StockAvailable.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L33)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$depends_on_stock](#property-$depends_on_stock)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$out_of_stock](#property-$out_of_stock)
* [$quantity](#property-$quantity)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [addSqlShopParams](#method-addSqlShopParams)
* [addSqlShopRestriction](#method-addSqlShopRestriction)
* [copyStockAvailableFromShopToShop](#method-copyStockAvailableFromShopToShop)
* [dependsOnStock](#method-dependsOnStock)
* [getQuantityAvailableByProduct](#method-getQuantityAvailableByProduct)
* [getStockAvailableIdByProductId](#method-getStockAvailableIdByProductId)
* [outOfStock](#method-outOfStock)
* [postSave](#method-postSave)
* [removeProductFromStockAvailable](#method-removeProductFromStockAvailable)
* [resetProductFromStockAvailableByShopGroup](#method-resetProductFromStockAvailableByShopGroup)
* [setProductDependsOnStock](#method-setProductDependsOnStock)
* [setProductOutOfStock](#method-setProductOutOfStock)
* [setQuantity](#method-setQuantity)
* [synchronize](#method-synchronize)
* [update](#method-update)
* [updateQuantity](#method-updateQuantity)
* [updateWs](#method-updateWs)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'stock_available', 'primary' => 'id_stock_available', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'depends_on_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'out_of_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/StockAvailable.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L59).


### <a name="property-$depends_on_stock"></a>$depends_on_stock

```php
public boolean $depends_on_stock = false
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L51).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L36).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L39).


### <a name="property-$id_shop"></a>$id_shop

```php
public integer $id_shop
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L42).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public integer $id_shop_group
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L45).


### <a name="property-$out_of_stock"></a>$out_of_stock

```php
public boolean $out_of_stock = false
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L54).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L48).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_shop_group' => array('xlink_resource' => 'shop_groups')), 'hidden_fields' => array(), 'objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'))
```





* Visibility: **protected**
* Source: [classes/stock/StockAvailable.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L76).


Methods
-------


### <a name="method-add"></a>add

```php
mixed StockAvailableCore::add($autodate, $null_values)
```

Upgrades total_quantity_available after having saved



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L390)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addSqlShopParams"></a>addSqlShopParams

```php
mixed StockAvailableCore::addSqlShopParams(array $params, integer $id_shop)
```

Add sql params for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 736](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L736)


#### Arguments
* $params **array** - Reference to the params array
* $id_shop **integer** - Optional : The shop ID



### <a name="method-addSqlShopRestriction"></a>addSqlShopRestriction

```php
string|\DbQuery StockAvailableCore::addSqlShopRestriction(\DbQuery|string|null $sql, \Shop|integer|null $shop, string|null $alias)
```

Add an sql restriction for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 682](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L682)


#### Arguments
* $sql **[DbQuery](class.DbQueryCore.md)|string|null** - Reference to the query object
* $shop **[Shop](class.ShopCore.md)|integer|null** - Optional : The shop ID
* $alias **string|null** - Optional : The current table alias



### <a name="method-copyStockAvailableFromShopToShop"></a>copyStockAvailableFromShopToShop

```php
boolean StockAvailableCore::copyStockAvailableFromShopToShop(integer $src_shop_id, integer $dst_shop_id)
```

Copies stock available content table



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L778)


#### Arguments
* $src_shop_id **integer**
* $dst_shop_id **integer**



### <a name="method-dependsOnStock"></a>dependsOnStock

```php
boolean StockAvailableCore::dependsOnStock(integer $id_product, integer $id_shop)
```

For a given product, tells if it depends on the physical (usable) stock



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 632](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L632)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - Optional : gets context if null @see Context::getContext()



### <a name="method-getQuantityAvailableByProduct"></a>getQuantityAvailableByProduct

```php
integer StockAvailableCore::getQuantityAvailableByProduct(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given id_product and id_product_attribute, gets its stock available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L358)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $id_shop **integer** - Optional : gets context by default



### <a name="method-getStockAvailableIdByProductId"></a>getStockAvailableIdByProductId

```php
mixed StockAvailableCore::getStockAvailableIdByProductId($id_product, $id_product_attribute, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L108)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_shop **mixed**



### <a name="method-outOfStock"></a>outOfStock

```php
boolean StockAvailableCore::outOfStock(integer $id_product, integer $id_shop)
```

For a given product, get its "out of stock" flag



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L656)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - Optional : gets context if null @see Context::getContext()



### <a name="method-postSave"></a>postSave

```php
mixed StockAvailableCore::postSave()
```

Upgrades total_quantity_available after having saved



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L419)




### <a name="method-removeProductFromStockAvailable"></a>removeProductFromStockAvailable

```php
boolean StockAvailableCore::removeProductFromStockAvailable(integer $id_product, integer|null $id_product_attribute, \Shop|null $shop)
```

Removes a given product from the stock available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L552)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer|null** - Optional
* $shop **[Shop](class.ShopCore.md)|null** - Shop id or shop object Optional



### <a name="method-resetProductFromStockAvailableByShopGroup"></a>resetProductFromStockAvailableByShopGroup

```php
mixed StockAvailableCore::resetProductFromStockAvailableByShopGroup(\ShopGroup $shop_group)
```

Removes all product quantities from all a group of shops
If stocks are shared, remoe all old available quantities for all shops of the group
Else remove all available quantities for the current group



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L611)


#### Arguments
* $shop_group **[ShopGroup](class.ShopGroupCore.md)** - the ShopGroup object



### <a name="method-setProductDependsOnStock"></a>setProductDependsOnStock

```php
mixed StockAvailableCore::setProductDependsOnStock(integer $id_product, integer $depends_on_stock, integer $id_shop, $id_product_attribute)
```

For a given id_product, sets if stock available depends on stock



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L286)


#### Arguments
* $id_product **integer**
* $depends_on_stock **integer** - Optional : true by default
* $id_shop **integer** - Optional : gets context by default
* $id_product_attribute **mixed**



### <a name="method-setProductOutOfStock"></a>setProductOutOfStock

```php
mixed StockAvailableCore::setProductOutOfStock(integer $id_product, integer $out_of_stock, integer $id_shop, $id_product_attribute)
```

For a given id_product, sets if product is available out of stocks



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L322)


#### Arguments
* $id_product **integer**
* $out_of_stock **integer** - Optional false by default
* $id_shop **integer** - Optional gets context by default
* $id_product_attribute **mixed**



### <a name="method-setQuantity"></a>setQuantity

```php
mixed StockAvailableCore::setQuantity(integer $id_product, integer $id_product_attribute, $quantity, integer $id_shop)
```

For a given id_product and id_product_attribute sets the quantity available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 484](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L484)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $quantity **mixed**
* $id_shop **integer** - Optional



### <a name="method-synchronize"></a>synchronize

```php
mixed StockAvailableCore::synchronize(integer $id_product, $order_id_shop)
```

For a given id_product, synchronizes StockAvailable::quantity with Stock::usable_quantity



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L132)


#### Arguments
* $id_product **integer**
* $order_id_shop **mixed**



### <a name="method-update"></a>update

```php
mixed StockAvailableCore::update($null_values)
```

Upgrades total_quantity_available after having update



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L404)


#### Arguments
* $null_values **mixed**



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed StockAvailableCore::updateQuantity(integer $id_product, integer $id_product_attribute, integer $delta_quantity, integer $id_shop)
```

For a given id_product and id_product_attribute updates the quantity available
If $avoid_parent_pack_update is true, then packs containing the given product won't be updated



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L461)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $delta_quantity **integer** - The delta quantity to update
* $id_shop **integer** - Optional



### <a name="method-updateWs"></a>updateWs

```php
integer StockAvailableCore::updateWs()
```

For a given {id_product, id_product_attribute and id_shop}, gets the stock available id associated



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockAvailable.php#L100)



