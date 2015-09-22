SearchCore
===============






* Class name: SearchCore
* This class is defined in [classes/Search.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#L94)







Methods
-------


### sanitize

    mixed SearchCore::sanitize($string, $id_lang, $indexation, $iso_code)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#96)


#### Arguments
* $string **mixed**
* $id_lang **mixed**
* $indexation **mixed**
* $iso_code **mixed**



### find

    mixed SearchCore::find($id_lang, $expr, $page_number, $page_size, $order_by, $order_way, $ajax, $use_cookie, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#175)


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



### getTags

    string SearchCore::getTags(\Db $db, integer $id_product, integer $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#372)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $id_lang **integer**



### getAttributes

    string SearchCore::getAttributes(\Db $db, integer $id_product, integer $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#391)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $id_lang **integer**



### getFeatures

    string SearchCore::getFeatures(\Db $db, integer $id_product, integer $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#416)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $id_lang **integer**



### getSQLProductAttributeFields

    string SearchCore::getSQLProductAttributeFields($weight_array)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#437)


#### Arguments
* $weight_array **mixed**



### getProductsToIndex

    mixed SearchCore::getProductsToIndex($total_languages, $id_product, $limit, $weight_array)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#463)


#### Arguments
* $total_languages **mixed**
* $id_product **mixed**
* $limit **mixed**
* $weight_array **mixed**



### getAttributesFields

    array|null SearchCore::getAttributesFields(\Db $db, integer $id_product, string $sql_attribute)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#549)


#### Arguments
* $db **[Db](DbCore)**
* $id_product **integer**
* $sql_attribute **string**



### fillProductArray

    mixed SearchCore::fillProductArray($product_array, $weight_array, $key, $value, $id_lang, $iso_code)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#563)


#### Arguments
* $product_array **mixed**
* $weight_array **mixed**
* $key **mixed**
* $value **mixed**
* $id_lang **mixed**
* $iso_code **mixed**



### indexation

    mixed SearchCore::indexation($full, $id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#580)


#### Arguments
* $full **mixed**
* $id_product **mixed**



### removeProductsSearchIndex

    mixed SearchCore::removeProductsSearchIndex($products)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#745)


#### Arguments
* $products **mixed**



### setProductsAsIndexed

    mixed SearchCore::setProductsAsIndexed($products)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#753)


#### Arguments
* $products **mixed**



### saveIndex

    mixed SearchCore::saveIndex($queryArray3)

$queryArray3 is automatically emptied in order to be reused immediatly



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Search.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#761)


#### Arguments
* $queryArray3 **mixed**



### searchTag

    mixed SearchCore::searchTag($id_lang, $tag, $count, $pageNumber, $pageSize, $orderBy, $orderWay, $useCookie, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Search.php line 773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Search.php#773)


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


