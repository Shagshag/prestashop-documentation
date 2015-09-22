Class PackCore
=====================





* Class name: PackCore
* Parent class: [Product](class.ProductCore.md)
* Source: [classes/Pack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L27)


Contents
--------


### Properties

* [$cacheIsPack](#property-$cacheIsPack)
* [$cacheIsPacked](#property-$cacheIsPacked)
* [$cachePackItems](#property-$cachePackItems)

### Methods

* [addItem](#method-addItem)
* [allUsesAdvancedStockManagement](#method-allUsesAdvancedStockManagement)
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
* [noPackWholesalePrice](#method-noPackWholesalePrice)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)




Properties
----------


### <a name="property-$cacheIsPack"></a>$cacheIsPack

```php
protected mixed $cacheIsPack = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L30).


### <a name="property-$cacheIsPacked"></a>$cacheIsPacked

```php
protected mixed $cacheIsPacked = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L31).


### <a name="property-$cachePackItems"></a>$cachePackItems

```php
protected mixed $cachePackItems = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L29).


Methods
-------


### <a name="method-addItem"></a>addItem

```php
boolean PackCore::addItem(integer $id_product, integer $id_item, integer $qty, integer $id_attribute_item)
```

Add an item to the pack



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L281)


#### Arguments
* $id_product **integer**
* $id_item **integer**
* $qty **integer**
* $id_attribute_item **integer**



### <a name="method-allUsesAdvancedStockManagement"></a>allUsesAdvancedStockManagement

```php
boolean PackCore::allUsesAdvancedStockManagement(integer $id_product)
```

For a given pack, tells if all products using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L357)


#### Arguments
* $id_product **integer** - id_pack



### <a name="method-deleteItems"></a>deleteItems

```php
mixed PackCore::deleteItems($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L264)


#### Arguments
* $id_product **mixed**



### <a name="method-duplicate"></a>duplicate

```php
mixed PackCore::duplicate($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L294)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-getItemTable"></a>getItemTable

```php
mixed PackCore::getItemTable($id_product, $id_lang, $full)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L153)


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
* Source: [classes/Pack.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L97)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getPacksTable"></a>getPacksTable

```php
mixed PackCore::getPacksTable($id_product, $id_lang, $full, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L222)


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
* Source: [classes/Pack.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L320)


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
* Source: [classes/Pack.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L308)




### <a name="method-isInStock"></a>isInStock

```php
mixed PackCore::isInStock($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L136)


#### Arguments
* $id_product **mixed**



### <a name="method-isPack"></a>isPack

```php
boolean PackCore::isPack($id_product)
```

Is product a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L39)


#### Arguments
* $id_product **mixed**



### <a name="method-isPacked"></a>isPacked

```php
boolean PackCore::isPacked($id_product)
```

Is product in a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L61)


#### Arguments
* $id_product **mixed**



### <a name="method-noPackPrice"></a>noPackPrice

```php
mixed PackCore::noPackPrice($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L74)


#### Arguments
* $id_product **mixed**



### <a name="method-noPackWholesalePrice"></a>noPackWholesalePrice

```php
mixed PackCore::noPackWholesalePrice($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L88)


#### Arguments
* $id_product **mixed**



### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

```php
boolean PackCore::usesAdvancedStockManagement(integer $id_product)
```

For a given pack, tells if it has at least one product using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Pack.php#L335)


#### Arguments
* $id_product **integer** - id_pack


