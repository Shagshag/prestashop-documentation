Class PackCore
=====================





* Class name: PackCore
* Parent class: [Product](class.ProductCore.md)
* Source: [classes/Pack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L27)



Properties
----------

* [$cacheIsPack](#property-$cacheIsPack)
* [$cacheIsPacked](#property-$cacheIsPacked)
* [$cachePackItems](#property-$cachePackItems)

Methods
-------
* [addItem](#method-addItem)
* [allUsesAdvancedStockManagement](#method-allUsesAdvancedStockManagement)
* [deleteItems](#method-deleteItems)
* [duplicate](#method-duplicate)
* [getItemTable](#method-getItemTable)
* [getItems](#method-getItems)
* [getPacksContainingItem](#method-getPacksContainingItem)
* [getPacksTable](#method-getPacksTable)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [isInStock](#method-isInStock)
* [isPack](#method-isPack)
* [isPacked](#method-isPacked)
* [noPackPrice](#method-noPackPrice)
* [noPackWholesalePrice](#method-noPackWholesalePrice)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)




Properties
----------


### <a name="property-$cacheIsPack"></a>$cacheIsPack

    protected mixed $cacheIsPack = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L30)


### <a name="property-$cacheIsPacked"></a>$cacheIsPacked

    protected mixed $cacheIsPacked = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L31)


### <a name="property-$cachePackItems"></a>$cachePackItems

    protected mixed $cachePackItems = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L29)


Methods
-------


### <a name="method-addItem"></a>addItem

    boolean PackCore::addItem(integer $id_product, integer $id_item, integer $qty, integer $id_attribute_item)

Add an item to the pack



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L307)


#### Arguments
* $id_product **integer**
* $id_item **integer**
* $qty **integer**
* $id_attribute_item **integer**



### <a name="method-allUsesAdvancedStockManagement"></a>allUsesAdvancedStockManagement

    boolean PackCore::allUsesAdvancedStockManagement(integer $id_product)

For a given pack, tells if all products using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L384)


#### Arguments
* $id_product **integer** - id_pack



### <a name="method-deleteItems"></a>deleteItems

    mixed PackCore::deleteItems($id_product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L290)


#### Arguments
* $id_product **mixed**



### <a name="method-duplicate"></a>duplicate

    mixed PackCore::duplicate($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L320)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-getItemTable"></a>getItemTable

    mixed PackCore::getItemTable($id_product, $id_lang, $full)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L171)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**



### <a name="method-getItems"></a>getItems

    mixed PackCore::getItems($id_product, $id_lang)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L113)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getPacksContainingItem"></a>getPacksContainingItem

    \array[Product] PackCore::getPacksContainingItem(integer $id_item, integer $id_attribute_item, integer $id_lang)

Returns Packs that conatins the given product in the right declinaison.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 409](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L409)


#### Arguments
* $id_item **integer** - Product item id that could be contained in a|many pack(s)
* $id_attribute_item **integer** - The declinaison of the product
* $id_lang **integer**



### <a name="method-getPacksTable"></a>getPacksTable

    mixed PackCore::getPacksTable($id_product, $id_lang, $full, $limit)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L242)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**
* $limit **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

    boolean PackCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if a Pack entity is currently used



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L346)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean PackCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L334)




### <a name="method-isInStock"></a>isInStock

    mixed PackCore::isInStock($id_product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L153)


#### Arguments
* $id_product **mixed**



### <a name="method-isPack"></a>isPack

    boolean PackCore::isPack($id_product)

Is product a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L39)


#### Arguments
* $id_product **mixed**



### <a name="method-isPacked"></a>isPacked

    boolean PackCore::isPacked($id_product, $id_product_attribute)

Is product in a pack?
If $id_product_attribute specified, then will restrict search on the given combination,
else this method will match a product if at least one of all its combination is in a pack.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L65)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed** - Optional combination of the product



### <a name="method-noPackPrice"></a>noPackPrice

    mixed PackCore::noPackPrice($id_product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L90)


#### Arguments
* $id_product **mixed**



### <a name="method-noPackWholesalePrice"></a>noPackWholesalePrice

    mixed PackCore::noPackWholesalePrice($id_product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L103)


#### Arguments
* $id_product **mixed**



### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

    boolean PackCore::usesAdvancedStockManagement(integer $id_product)

For a given pack, tells if it has at least one product using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Pack.php#L361)


#### Arguments
* $id_product **integer** - id_pack


