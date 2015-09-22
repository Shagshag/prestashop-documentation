MetaCore
===============






* Class name: MetaCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Meta.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L27)





Properties
----------

* [$page](#property-$page)
* [$configurable](#property-$configurable)
* [$title](#property-$title)
* [$description](#property-$description)
* [$keywords](#property-$keywords)
* [$url_rewrite](#property-$url_rewrite)
* [$definition](#property-$definition)

Methods
-------
* [getPages](#method-getPages)
* [getMetas](#method-getMetas)
* [getMetasByIdLang](#method-getMetasByIdLang)
* [getMetaByPage](#method-getMetaByPage)
* [update](#method-update)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [getEquivalentUrlRewrite](#method-getEquivalentUrlRewrite)
* [getMetaTags](#method-getMetaTags)
* [getHomeMetas](#method-getHomeMetas)
* [getProductMetas](#method-getProductMetas)
* [getCategoryMetas](#method-getCategoryMetas)
* [getManufacturerMetas](#method-getManufacturerMetas)
* [getSupplierMetas](#method-getSupplierMetas)
* [getCmsMetas](#method-getCmsMetas)
* [getCmsCategoryMetas](#method-getCmsCategoryMetas)
* [completeMetaTags](#method-completeMetaTags)




Properties
----------


### <a name="property-$page"></a>$page

    public mixed $page





* Visibility: **public**
* This property is defined in [classes/Meta.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L29)


### <a name="property-$configurable"></a>$configurable

    public mixed $configurable = 1





* Visibility: **public**
* This property is defined in [classes/Meta.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L30)


### <a name="property-$title"></a>$title

    public mixed $title





* Visibility: **public**
* This property is defined in [classes/Meta.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L31)


### <a name="property-$description"></a>$description

    public mixed $description





* Visibility: **public**
* This property is defined in [classes/Meta.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L32)


### <a name="property-$keywords"></a>$keywords

    public mixed $keywords





* Visibility: **public**
* This property is defined in [classes/Meta.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L33)


### <a name="property-$url_rewrite"></a>$url_rewrite

    public mixed $url_rewrite





* Visibility: **public**
* This property is defined in [classes/Meta.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L34)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'meta', 'primary' => 'id_meta', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('page' => array('type' => self::TYPE_STRING, 'validate' => 'isFileName', 'required' => true, 'size' => 64), 'configurable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'url_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'size' => 255)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Meta.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L39)


Methods
-------


### <a name="method-getPages"></a>getPages

    mixed MetaCore::getPages($exclude_filled, $add_page)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L56)


#### Arguments
* $exclude_filled **mixed**
* $add_page **mixed**



### <a name="method-getMetas"></a>getMetas

    mixed MetaCore::getMetas()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L122)




### <a name="method-getMetasByIdLang"></a>getMetasByIdLang

    mixed MetaCore::getMetasByIdLang($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L127)


#### Arguments
* $id_lang **mixed**



### <a name="method-getMetaByPage"></a>getMetaByPage

    mixed MetaCore::getMetaByPage($page, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L138)


#### Arguments
* $page **mixed**
* $id_lang **mixed**



### <a name="method-update"></a>update

    mixed MetaCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/Meta.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L152)


#### Arguments
* $null_values **mixed**



### <a name="method-delete"></a>delete

    mixed MetaCore::delete()





* Visibility: **public**
* This method is defined in [classes/Meta.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L161)




### <a name="method-deleteSelection"></a>deleteSelection

    mixed MetaCore::deleteSelection($selection)





* Visibility: **public**
* This method is defined in [classes/Meta.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L170)


#### Arguments
* $selection **mixed**



### <a name="method-getEquivalentUrlRewrite"></a>getEquivalentUrlRewrite

    mixed MetaCore::getEquivalentUrlRewrite($new_id_lang, $id_lang, $url_rewrite)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L184)


#### Arguments
* $new_id_lang **mixed**
* $id_lang **mixed**
* $url_rewrite **mixed**



### <a name="method-getMetaTags"></a>getMetaTags

    mixed MetaCore::getMetaTags($id_lang, $page_name, $title)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L202)


#### Arguments
* $id_lang **mixed**
* $page_name **mixed**
* $title **mixed**



### <a name="method-getHomeMetas"></a>getHomeMetas

    array MetaCore::getHomeMetas(integer $id_lang, string $page_name)

Get meta tags for a given page



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L232)


#### Arguments
* $id_lang **integer**
* $page_name **string**



### <a name="method-getProductMetas"></a>getProductMetas

    array MetaCore::getProductMetas(integer $id_product, integer $id_lang, string $page_name)

Get product meta tags



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L250)


#### Arguments
* $id_product **integer**
* $id_lang **integer**
* $page_name **string**



### <a name="method-getCategoryMetas"></a>getCategoryMetas

    array MetaCore::getCategoryMetas(integer $id_category, integer $id_lang, string $page_name, $title)

Get category meta tags



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L278)


#### Arguments
* $id_category **integer**
* $id_lang **integer**
* $page_name **string**
* $title **mixed**



### <a name="method-getManufacturerMetas"></a>getManufacturerMetas

    array MetaCore::getManufacturerMetas(integer $id_manufacturer, integer $id_lang, string $page_name)

Get manufacturer meta tags



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L326)


#### Arguments
* $id_manufacturer **integer**
* $id_lang **integer**
* $page_name **string**



### <a name="method-getSupplierMetas"></a>getSupplierMetas

    array MetaCore::getSupplierMetas(integer $id_supplier, integer $id_lang, string $page_name)

Get supplier meta tags



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L355)


#### Arguments
* $id_supplier **integer**
* $id_lang **integer**
* $page_name **string**



### <a name="method-getCmsMetas"></a>getCmsMetas

    array MetaCore::getCmsMetas(integer $id_cms, integer $id_lang, string $page_name)

Get CMS meta tags



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L384)


#### Arguments
* $id_cms **integer**
* $id_lang **integer**
* $page_name **string**



### <a name="method-getCmsCategoryMetas"></a>getCmsCategoryMetas

    array MetaCore::getCmsCategoryMetas(integer $id_cms_category, integer $id_lang, string $page_name)

Get CMS category meta tags



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L410)


#### Arguments
* $id_cms_category **integer**
* $id_lang **integer**
* $page_name **string**



### <a name="method-completeMetaTags"></a>completeMetaTags

    mixed MetaCore::completeMetaTags($meta_tags, $default_value, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Meta.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Meta.php#L429)


#### Arguments
* $meta_tags **mixed**
* $default_value **mixed**
* $context **[Context](ContextCore)**


