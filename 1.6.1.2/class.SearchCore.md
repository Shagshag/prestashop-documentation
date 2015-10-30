Class SearchCore
=====================





* Class name: SearchCore
* Source: [classes/Search.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L94)


Contents
--------



### Methods

* [fillProductArray](#method-fillProductArray)
* [find](#method-find)
* [getAttributes](#method-getAttributes)
* [getAttributesFields](#method-getAttributesFields)
* [getFeatures](#method-getFeatures)
* [getProductsToIndex](#method-getProductsToIndex)
* [getSQLProductAttributeFields](#method-getSQLProductAttributeFields)
* [getTags](#method-getTags)
* [indexation](#method-indexation)
* [removeProductsSearchIndex](#method-removeProductsSearchIndex)
* [sanitize](#method-sanitize)
* [saveIndex](#method-saveIndex)
* [searchTag](#method-searchTag)
* [setProductsAsIndexed](#method-setProductsAsIndexed)






Methods
-------


### <a name="method-fillProductArray"></a>fillProductArray

```php
mixed SearchCore::fillProductArray($product_array, $weight_array, $key, $value, $id_lang, $iso_code)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L560)


#### Arguments
* $product_array **mixed**
* $weight_array **mixed**
* $key **mixed**
* $value **mixed**
* $id_lang **mixed**
* $iso_code **mixed**



### <a name="method-find"></a>find

```php
mixed SearchCore::find($id_lang, $expr, $page_number, $page_size, $order_by, $order_way, $ajax, $use_cookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L172)


#### Arguments
* $id_lang **mixed**
* $expr **mixed**
* $page_number **mixed**
* $page_size **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $ajax **mixed**
* $use_cookie **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAttributes"></a>getAttributes

```php
string SearchCore::getAttributes(\Db $db, integer $id_product, integer $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 388](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L388)


#### Arguments
* $db **[Db](class.DbCore.md)**
* $id_product **integer**
* $id_lang **integer**



### <a name="method-getAttributesFields"></a>getAttributesFields

```php
array|null SearchCore::getAttributesFields(\Db $db, integer $id_product, string $sql_attribute)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L546)


#### Arguments
* $db **[Db](class.DbCore.md)**
* $id_product **integer**
* $sql_attribute **string**



### <a name="method-getFeatures"></a>getFeatures

```php
string SearchCore::getFeatures(\Db $db, integer $id_product, integer $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L413)


#### Arguments
* $db **[Db](class.DbCore.md)**
* $id_product **integer**
* $id_lang **integer**



### <a name="method-getProductsToIndex"></a>getProductsToIndex

```php
mixed SearchCore::getProductsToIndex($total_languages, $id_product, $limit, $weight_array)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L460)


#### Arguments
* $total_languages **mixed**
* $id_product **mixed**
* $limit **mixed**
* $weight_array **mixed**



### <a name="method-getSQLProductAttributeFields"></a>getSQLProductAttributeFields

```php
string SearchCore::getSQLProductAttributeFields($weight_array)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L434)


#### Arguments
* $weight_array **mixed**



### <a name="method-getTags"></a>getTags

```php
string SearchCore::getTags(\Db $db, integer $id_product, integer $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L369)


#### Arguments
* $db **[Db](class.DbCore.md)**
* $id_product **integer**
* $id_lang **integer**



### <a name="method-indexation"></a>indexation

```php
mixed SearchCore::indexation($full, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L577)


#### Arguments
* $full **mixed**
* $id_product **mixed**



### <a name="method-removeProductsSearchIndex"></a>removeProductsSearchIndex

```php
mixed SearchCore::removeProductsSearchIndex($products)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 742](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L742)


#### Arguments
* $products **mixed**



### <a name="method-sanitize"></a>sanitize

```php
mixed SearchCore::sanitize($string, $id_lang, $indexation, $iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L96)


#### Arguments
* $string **mixed**
* $id_lang **mixed**
* $indexation **mixed**
* $iso_code **mixed**



### <a name="method-saveIndex"></a>saveIndex

```php
mixed SearchCore::saveIndex($queryArray3)
```

$queryArray3 is automatically emptied in order to be reused immediatly



* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L758)


#### Arguments
* $queryArray3 **mixed**



### <a name="method-searchTag"></a>searchTag

```php
mixed SearchCore::searchTag($id_lang, $tag, $count, $pageNumber, $pageSize, $orderBy, $orderWay, $useCookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 770](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L770)


#### Arguments
* $id_lang **mixed**
* $tag **mixed**
* $count **mixed**
* $pageNumber **mixed**
* $pageSize **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $useCookie **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-setProductsAsIndexed"></a>setProductsAsIndexed

```php
mixed SearchCore::setProductsAsIndexed($products)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 750](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Search.php#L750)


#### Arguments
* $products **mixed**


