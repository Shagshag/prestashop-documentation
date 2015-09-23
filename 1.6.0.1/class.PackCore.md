Class PackCore
=====================





* Class name: PackCore
* Parent class: [Product](class.ProductCore.md)
* Source: [classes/Pack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L27)


Contents
--------


### Properties

* [$cacheIsPack](#property-$cacheIsPack)
* [$cacheIsPacked](#property-$cacheIsPacked)
* [$cachePackItems](#property-$cachePackItems)

### Methods

* [addItem](#method-addItem)
* [deleteItems](#method-deleteItems)
* [duplicate](#method-duplicate)
* [getItemTable](#method-getItemTable)
* [getItems](#method-getItems)
* [getPacksTable](#method-getPacksTable)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [isInStock](#method-isInStock)
* [isPack](#method-isPack)
* [isPacked](#method-isPacked)
* [noPackPrice](#method-noPackPrice)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)




Properties
----------


### <a name="property-$cacheIsPack"></a>$cacheIsPack

```php
protected mixed $cacheIsPack = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L30).


### <a name="property-$cacheIsPacked"></a>$cacheIsPacked

```php
protected mixed $cacheIsPacked = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L31).


### <a name="property-$cachePackItems"></a>$cachePackItems

```php
protected mixed $cachePackItems = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L29).


Methods
-------


### <a name="method-addItem"></a>addItem

```php
boolean PackCore::addItem(integer $id_product, integer $id_item, integer $qty)
```

Add an item to the pack



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L211)


#### Arguments
* $id_product **integer**
* $id_item **integer**
* $qty **integer**



### <a name="method-deleteItems"></a>deleteItems

```php
mixed PackCore::deleteItems($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L196)


#### Arguments
* $id_product **mixed**



### <a name="method-duplicate"></a>duplicate

```php
mixed PackCore::duplicate($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L218)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-getItemTable"></a>getItemTable

```php
mixed PackCore::getItemTable($id_product, $id_lang, $full)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L122)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**



### <a name="method-getItems"></a>getItems

```php
mixed PackCore::getItems($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L86)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getPacksTable"></a>getPacksTable

```php
mixed PackCore::getPacksTable($id_product, $id_lang, $full, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L158)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**
* $limit **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean PackCore::isCurrentlyUsed($table, $has_active_column)
```

This method is allow to know if a Pack entity is currently used



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L244)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean PackCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L232)




### <a name="method-isInStock"></a>isInStock

```php
mixed PackCore::isInStock($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L106)


#### Arguments
* $id_product **mixed**



### <a name="method-isPack"></a>isPack

```php
boolean PackCore::isPack($id_product)
```

Is product a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L40)


#### Arguments
* $id_product **mixed**



### <a name="method-isPacked"></a>isPacked

```php
boolean PackCore::isPacked($id_product)
```

Is product in a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L63)


#### Arguments
* $id_product **mixed**



### <a name="method-noPackPrice"></a>noPackPrice

```php
mixed PackCore::noPackPrice($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L76)


#### Arguments
* $id_product **mixed**



### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

```php
boolean PackCore::usesAdvancedStockManagement(integer $id_product)
```

For a given pack, tells if it has at least one product using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Pack.php#L259)


#### Arguments
* $id_product **integer** - id_pack


