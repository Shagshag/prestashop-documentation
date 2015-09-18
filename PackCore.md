PackCore
===============






* Class name: PackCore
* Namespace: 
* Parent class: Product





Properties
----------


### $cachePackItems

    protected mixed $cachePackItems = array()





* Visibility: **protected**
* This property is **static**.


### $cacheIsPack

    protected mixed $cacheIsPack = array()





* Visibility: **protected**
* This property is **static**.


### $cacheIsPacked

    protected mixed $cacheIsPacked = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### isPack

    boolean PackCore::isPack($id_product)

Is product a pack?



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### isPacked

    boolean PackCore::isPacked($id_product, $id_product_attribute)

Is product in a pack?
If $id_product_attribute specified, then will restrict search on the given combination,
else this method will match a product if at least one of all its combination is in a pack.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed** - &lt;p&gt;Optional combination of the product&lt;/p&gt;



### noPackPrice

    mixed PackCore::noPackPrice($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### noPackWholesalePrice

    mixed PackCore::noPackWholesalePrice($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### getItems

    mixed PackCore::getItems($id_product, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### isInStock

    mixed PackCore::isInStock($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### getItemTable

    mixed PackCore::getItemTable($id_product, $id_lang, $full)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**



### getPacksTable

    mixed PackCore::getPacksTable($id_product, $id_lang, $full, $limit)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**
* $limit **mixed**



### deleteItems

    mixed PackCore::deleteItems($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### addItem

    boolean PackCore::addItem(integer $id_product, integer $id_item, integer $qty, integer $id_attribute_item)

Add an item to the pack



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $id_item **integer**
* $qty **integer**
* $id_attribute_item **integer**



### duplicate

    mixed PackCore::duplicate($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### isFeatureActive

    boolean PackCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.




### isCurrentlyUsed

    boolean PackCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if a Pack entity is currently used



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### usesAdvancedStockManagement

    boolean PackCore::usesAdvancedStockManagement(integer $id_product)

For a given pack, tells if it has at least one product using the advanced stock management



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;id_pack&lt;/p&gt;



### allUsesAdvancedStockManagement

    boolean PackCore::allUsesAdvancedStockManagement(integer $id_product)

For a given pack, tells if all products using the advanced stock management



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;id_pack&lt;/p&gt;



### getPacksContainingItem

    \array[Product] PackCore::getPacksContainingItem(integer $id_item, integer $id_attribute_item, integer $id_lang)

Returns Packs that conatins the given product in the right declinaison.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_item **integer** - &lt;p&gt;Product item id that could be contained in a|many pack(s)&lt;/p&gt;
* $id_attribute_item **integer** - &lt;p&gt;The declinaison of the product&lt;/p&gt;
* $id_lang **integer**


