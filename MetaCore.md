MetaCore
===============






* Class name: MetaCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $page

    public mixed $page





* Visibility: **public**


### $configurable

    public mixed $configurable = 1





* Visibility: **public**


### $title

    public mixed $title





* Visibility: **public**


### $description

    public mixed $description





* Visibility: **public**


### $keywords

    public mixed $keywords





* Visibility: **public**


### $url_rewrite

    public mixed $url_rewrite





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'meta', 'primary' => 'id_meta', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('page' => array('type' => self::TYPE_STRING, 'validate' => 'isFileName', 'required' => true, 'size' => 64), 'configurable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'url_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'size' => 255)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getPages

    mixed MetaCore::getPages($exclude_filled, $add_page)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $exclude_filled **mixed**
* $add_page **mixed**



### getMetas

    mixed MetaCore::getMetas()





* Visibility: **public**
* This method is **static**.




### getMetasByIdLang

    mixed MetaCore::getMetasByIdLang($id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**



### getMetaByPage

    mixed MetaCore::getMetaByPage($page, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $page **mixed**
* $id_lang **mixed**



### update

    mixed MetaCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### delete

    mixed MetaCore::delete()





* Visibility: **public**




### deleteSelection

    mixed MetaCore::deleteSelection($selection)





* Visibility: **public**


#### Arguments
* $selection **mixed**



### getEquivalentUrlRewrite

    mixed MetaCore::getEquivalentUrlRewrite($new_id_lang, $id_lang, $url_rewrite)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $new_id_lang **mixed**
* $id_lang **mixed**
* $url_rewrite **mixed**



### getMetaTags

    mixed MetaCore::getMetaTags($id_lang, $page_name, $title)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $page_name **mixed**
* $title **mixed**



### getHomeMetas

    array MetaCore::getHomeMetas(integer $id_lang, string $page_name)

Get meta tags for a given page



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer**
* $page_name **string**



### getProductMetas

    array MetaCore::getProductMetas(integer $id_product, integer $id_lang, string $page_name)

Get product meta tags



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $id_lang **integer**
* $page_name **string**



### getCategoryMetas

    array MetaCore::getCategoryMetas(integer $id_category, integer $id_lang, string $page_name, $title)

Get category meta tags



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **integer**
* $id_lang **integer**
* $page_name **string**
* $title **mixed**



### getManufacturerMetas

    array MetaCore::getManufacturerMetas(integer $id_manufacturer, integer $id_lang, string $page_name)

Get manufacturer meta tags



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_manufacturer **integer**
* $id_lang **integer**
* $page_name **string**



### getSupplierMetas

    array MetaCore::getSupplierMetas(integer $id_supplier, integer $id_lang, string $page_name)

Get supplier meta tags



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supplier **integer**
* $id_lang **integer**
* $page_name **string**



### getCmsMetas

    array MetaCore::getCmsMetas(integer $id_cms, integer $id_lang, string $page_name)

Get CMS meta tags



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cms **integer**
* $id_lang **integer**
* $page_name **string**



### getCmsCategoryMetas

    array MetaCore::getCmsCategoryMetas(integer $id_cms_category, integer $id_lang, string $page_name)

Get CMS category meta tags



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cms_category **integer**
* $id_lang **integer**
* $page_name **string**



### completeMetaTags

    mixed MetaCore::completeMetaTags($meta_tags, $default_value, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $meta_tags **mixed**
* $default_value **mixed**
* $context **Context**


