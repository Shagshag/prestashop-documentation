Class SearchCore
=====================





* Class name: SearchCore
* Source: [classes/Search.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L95)


Contents
--------



### Methods

* [find](#method-find)
* [getAttributes](#method-getAttributes)
* [getFeatures](#method-getFeatures)
* [getProductsToIndex](#method-getProductsToIndex)
* [getTags](#method-getTags)
* [indexation](#method-indexation)
* [sanitize](#method-sanitize)
* [saveIndex](#method-saveIndex)
* [searchTag](#method-searchTag)
* [setProductsAsIndexed](#method-setProductsAsIndexed)






Methods
-------


### <a name="method-find"></a>find

```php
mixed SearchCore::find($id_lang, $expr, $page_number, $page_size, $order_by, $order_way, $ajax, $use_cookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L148)


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
mixed SearchCore::getAttributes($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L335)


#### Arguments
* $db **mixed**
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getFeatures"></a>getFeatures

```php
mixed SearchCore::getFeatures($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L351)


#### Arguments
* $db **mixed**
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getProductsToIndex"></a>getProductsToIndex

```php
mixed SearchCore::getProductsToIndex($total_languages, $id_product, $limit)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L366)


#### Arguments
* $total_languages **mixed**
* $id_product **mixed**
* $limit **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed SearchCore::getTags($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L323)


#### Arguments
* $db **mixed**
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-indexation"></a>indexation

```php
mixed SearchCore::indexation($full, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L387)


#### Arguments
* $full **mixed**
* $id_product **mixed**



### <a name="method-sanitize"></a>sanitize

```php
mixed SearchCore::sanitize($string, $id_lang, $indexation)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L97)


#### Arguments
* $string **mixed**
* $id_lang **mixed**
* $indexation **mixed**



### <a name="method-saveIndex"></a>saveIndex

```php
mixed SearchCore::saveIndex($queryArray3)
```

$queryArray3 is automatically emptied in order to be reused immediatly



* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 568](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L568)


#### Arguments
* $queryArray3 **mixed**



### <a name="method-searchTag"></a>searchTag

```php
mixed SearchCore::searchTag($id_lang, $tag, $count, $pageNumber, $pageSize, $orderBy, $orderWay, $useCookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L579)


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
* Source: [classes/Search.php line 556](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Search.php#L556)


#### Arguments
* $products **mixed**


