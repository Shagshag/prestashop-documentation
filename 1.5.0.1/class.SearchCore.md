Class SearchCore
=====================





* Class name: SearchCore
* Source: [classes/Search.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L95)


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
mixed SearchCore::find($id_lang, $expr, $pageNumber, $pageSize, $orderBy, $orderWay, $ajax, $useCookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L148)


#### Arguments
* $id_lang **mixed**
* $expr **mixed**
* $pageNumber **mixed**
* $pageSize **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $ajax **mixed**
* $useCookie **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed SearchCore::getAttributes($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L309)


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
* Source: [classes/Search.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L325)


#### Arguments
* $db **mixed**
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getProductsToIndex"></a>getProductsToIndex

```php
mixed SearchCore::getProductsToIndex($nbLanguages, $limit)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L340)


#### Arguments
* $nbLanguages **mixed**
* $limit **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed SearchCore::getTags($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L297)


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
* Source: [classes/Search.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L354)


#### Arguments
* $full **mixed**
* $id_product **mixed**



### <a name="method-sanitize"></a>sanitize

```php
mixed SearchCore::sanitize($string, $id_lang, $indexation)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L97)


#### Arguments
* $string **mixed**
* $id_lang **mixed**
* $indexation **mixed**



### <a name="method-saveIndex"></a>saveIndex

```php
mixed SearchCore::saveIndex($queryArray3)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L527)


#### Arguments
* $queryArray3 **mixed**



### <a name="method-searchTag"></a>searchTag

```php
mixed SearchCore::searchTag($id_lang, $tag, $count, $pageNumber, $pageSize, $orderBy, $orderWay, $useCookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L534)


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
* Source: [classes/Search.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Search.php#L519)


#### Arguments
* $products **mixed**


