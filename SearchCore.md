SearchCore
===============






* Class name: SearchCore
* This class is defined in [classes/Search.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L94)







Methods
-------
* [sanitize](#method-sanitize)
* [find](#method-find)
* [getTags](#method-getTags)
* [getAttributes](#method-getAttributes)
* [getFeatures](#method-getFeatures)
* [getSQLProductAttributeFields](#method-getSQLProductAttributeFields)
* [getProductsToIndex](#method-getProductsToIndex)
* [getAttributesFields](#method-getAttributesFields)
* [fillProductArray](#method-fillProductArray)
* [indexation](#method-indexation)
* [removeProductsSearchIndex](#method-removeProductsSearchIndex)
* [setProductsAsIndexed](#method-setProductsAsIndexed)
* [saveIndex](#method-saveIndex)
* [searchTag](#method-searchTag)






Methods
-------


### <a name="method-sanitize"></a>sanitize

    mixed SearchCore::sanitize($string, $id_lang, $indexation, $iso_code)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L96)


#### Arguments
* $string **mixed**
* $id_lang **mixed**
* $indexation **mixed**
* $iso_code **mixed**



### <a name="method-find"></a>find

    mixed SearchCore::find($id_lang, $expr, $page_number, $page_size, $order_by, $order_way, $ajax, $use_cookie, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L175)


#### Arguments
* $id_lang **mixed**
* $expr **mixed**
* $page_number **mixed**
* $page_size **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $ajax **mixed**
* $use_cookie **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getTags"></a>getTags

    string SearchCore::getTags(\Db $db, integer $id_product, integer $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L372)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $id_lang **integer**



### <a name="method-getAttributes"></a>getAttributes

    string SearchCore::getAttributes(\Db $db, integer $id_product, integer $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L391)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $id_lang **integer**



### <a name="method-getFeatures"></a>getFeatures

    string SearchCore::getFeatures(\Db $db, integer $id_product, integer $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L416)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $id_lang **integer**



### <a name="method-getSQLProductAttributeFields"></a>getSQLProductAttributeFields

    string SearchCore::getSQLProductAttributeFields($weight_array)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L437)


#### Arguments
* $weight_array **mixed**



### <a name="method-getProductsToIndex"></a>getProductsToIndex

    mixed SearchCore::getProductsToIndex($total_languages, $id_product, $limit, $weight_array)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L463)


#### Arguments
* $total_languages **mixed**
* $id_product **mixed**
* $limit **mixed**
* $weight_array **mixed**



### <a name="method-getAttributesFields"></a>getAttributesFields

    array|null SearchCore::getAttributesFields(\Db $db, integer $id_product, string $sql_attribute)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L549)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $sql_attribute **string**



### <a name="method-fillProductArray"></a>fillProductArray

    mixed SearchCore::fillProductArray($product_array, $weight_array, $key, $value, $id_lang, $iso_code)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L563)


#### Arguments
* $product_array **mixed**
* $weight_array **mixed**
* $key **mixed**
* $value **mixed**
* $id_lang **mixed**
* $iso_code **mixed**



### <a name="method-indexation"></a>indexation

    mixed SearchCore::indexation($full, $id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L580)


#### Arguments
* $full **mixed**
* $id_product **mixed**



### <a name="method-removeProductsSearchIndex"></a>removeProductsSearchIndex

    mixed SearchCore::removeProductsSearchIndex($products)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L745)


#### Arguments
* $products **mixed**



### <a name="method-setProductsAsIndexed"></a>setProductsAsIndexed

    mixed SearchCore::setProductsAsIndexed($products)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L753)


#### Arguments
* $products **mixed**



### <a name="method-saveIndex"></a>saveIndex

    mixed SearchCore::saveIndex($queryArray3)

$queryArray3 is automatically emptied in order to be reused immediatly



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L761)


#### Arguments
* $queryArray3 **mixed**



### <a name="method-searchTag"></a>searchTag

    mixed SearchCore::searchTag($id_lang, $tag, $count, $pageNumber, $pageSize, $orderBy, $orderWay, $useCookie, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L773)


#### Arguments
* $id_lang **mixed**
* $tag **mixed**
* $count **mixed**
* $pageNumber **mixed**
* $pageSize **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $useCookie **mixed**
* $context **[Context](ContextCore)**


