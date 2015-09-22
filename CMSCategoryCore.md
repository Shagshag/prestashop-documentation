CMSCategoryCore
===============






* Class name: CMSCategoryCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/CMSCategory.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L27)





Properties
----------

* [$id](#property-$id)
* [$id_cms_category](#property-$id_cms_category)
* [$name](#property-$name)
* [$active](#property-$active)
* [$description](#property-$description)
* [$id_parent](#property-$id_parent)
* [$position](#property-$position)
* [$level_depth](#property-$level_depth)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_title](#property-$meta_title)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_description](#property-$meta_description)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$_links](#property-$_links)
* [$definition](#property-$definition)

Methods
-------
* [add](#method-add)
* [update](#method-update)
* [recurseLiteCategTree](#method-recurseLiteCategTree)
* [getRecurseCategory](#method-getRecurseCategory)
* [recurseCMSCategory](#method-recurseCMSCategory)
* [recursiveDelete](#method-recursiveDelete)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [calcLevelDepth](#method-calcLevelDepth)
* [getCategories](#method-getCategories)
* [getSimpleCategories](#method-getSimpleCategories)
* [getSubCategories](#method-getSubCategories)
* [hideCMSCategoryPosition](#method-hideCMSCategoryPosition)
* [getHomeCategories](#method-getHomeCategories)
* [getChildren](#method-getChildren)
* [checkBeforeMove](#method-checkBeforeMove)
* [getLinkRewrite](#method-getLinkRewrite)
* [getLink](#method-getLink)
* [getName](#method-getName)
* [searchByName](#method-searchByName)
* [searchByNameAndParentCMSCategoryId](#method-searchByNameAndParentCMSCategoryId)
* [getParentsCategories](#method-getParentsCategories)
* [updatePosition](#method-updatePosition)
* [cleanPositions](#method-cleanPositions)
* [getLastPosition](#method-getLastPosition)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)




Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L29)


### <a name="property-$id_cms_category"></a>$id_cms_category

    public integer $id_cms_category





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L32)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L35)


### <a name="property-$active"></a>$active

    public boolean $active = 1





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L38)


### <a name="property-$description"></a>$description

    public string $description





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L41)


### <a name="property-$id_parent"></a>$id_parent

    public integer $id_parent





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L44)


### <a name="property-$position"></a>$position

    public integer $position





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L47)


### <a name="property-$level_depth"></a>$level_depth

    public integer $level_depth





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L50)


### <a name="property-$link_rewrite"></a>$link_rewrite

    public string $link_rewrite





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L53)


### <a name="property-$meta_title"></a>$meta_title

    public string $meta_title





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L56)


### <a name="property-$meta_keywords"></a>$meta_keywords

    public string $meta_keywords





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L59)


### <a name="property-$meta_description"></a>$meta_description

    public string $meta_description





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L62)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L65)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/CMSCategory.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L68)


### <a name="property-$_links"></a>$_links

    protected mixed $_links = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/CMSCategory.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L70)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'cms_category', 'primary' => 'id_cms_category', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'position' => array('type' => self::TYPE_INT), 'level_depth' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 64), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/CMSCategory.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L75)


Methods
-------


### <a name="method-add"></a>add

    mixed CMSCategoryCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L98)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-update"></a>update

    mixed CMSCategoryCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L112)


#### Arguments
* $null_values **mixed**



### <a name="method-recurseLiteCategTree"></a>recurseLiteCategTree

    array CMSCategoryCore::recurseLiteCategTree(integer $max_depth, integer $currentDepth, $id_lang, array $excluded_ids_array, \Link $link)

Recursive scan of subcategories



* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L133)


#### Arguments
* $max_depth **integer** - &lt;p&gt;Maximum depth of the tree (i.e. 2 =&gt; 3 levels depth)&lt;/p&gt;
* $currentDepth **integer** - &lt;p&gt;specify the current depth in the tree (don&#039;t use it, only for rucursivity!)&lt;/p&gt;
* $id_lang **mixed**
* $excluded_ids_array **array** - &lt;p&gt;specify a list of ids to exclude of results&lt;/p&gt;
* $link **[Link](LinkCore)**



### <a name="method-getRecurseCategory"></a>getRecurseCategory

    mixed CMSCategoryCore::getRecurseCategory($id_lang, $current, $active, $links, \Link $link)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L167)


#### Arguments
* $id_lang **mixed**
* $current **mixed**
* $active **mixed**
* $links **mixed**
* $link **[Link](LinkCore)**



### <a name="method-recurseCMSCategory"></a>recurseCMSCategory

    mixed CMSCategoryCore::recurseCMSCategory($categories, $current, $id_cms_category, $id_selected, $is_html)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L210)


#### Arguments
* $categories **mixed**
* $current **mixed**
* $id_cms_category **mixed**
* $id_selected **mixed**
* $is_html **mixed**



### <a name="method-recursiveDelete"></a>recursiveDelete

    mixed CMSCategoryCore::recursiveDelete($to_delete, array|integer $id_cms_category)

Recursively add specified CMSCategory childs to $toDelete array



* Visibility: **protected**
* This method is defined in [classes/CMSCategory.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L232)


#### Arguments
* $to_delete **mixed**
* $id_cms_category **array|integer** - &lt;p&gt;Parent CMSCategory ID&lt;/p&gt;



### <a name="method-delete"></a>delete

    mixed CMSCategoryCore::delete()





* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L248)




### <a name="method-deleteSelection"></a>deleteSelection

    mixed CMSCategoryCore::deleteSelection($categories)

Delete several categories from database

return boolean Deletion result

* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L297)


#### Arguments
* $categories **mixed**



### <a name="method-calcLevelDepth"></a>calcLevelDepth

    integer CMSCategoryCore::calcLevelDepth()

Get the number of parent categories



* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L312)




### <a name="method-getCategories"></a>getCategories

    array CMSCategoryCore::getCategories(integer $id_lang, boolean $active, $order)

Return available categories



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 328](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L328)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active categories&lt;/p&gt;
* $order **mixed**



### <a name="method-getSimpleCategories"></a>getSimpleCategories

    mixed CMSCategoryCore::getSimpleCategories($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L353)


#### Arguments
* $id_lang **mixed**



### <a name="method-getSubCategories"></a>getSubCategories

    array CMSCategoryCore::getSubCategories(integer $id_lang, boolean $active)

Return current CMSCategory childs



* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L370)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active categories&lt;/p&gt;



### <a name="method-hideCMSCategoryPosition"></a>hideCMSCategoryPosition

    string CMSCategoryCore::hideCMSCategoryPosition(string $name)

Hide CMSCategory prefix used for position



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L398)


#### Arguments
* $name **string** - &lt;p&gt;CMSCategory name&lt;/p&gt;



### <a name="method-getHomeCategories"></a>getHomeCategories

    array CMSCategoryCore::getHomeCategories(integer $id_lang, boolean $active)

Return main categories



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L410)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active categories&lt;/p&gt;



### <a name="method-getChildren"></a>getChildren

    mixed CMSCategoryCore::getChildren($id_parent, $id_lang, $active)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L415)


#### Arguments
* $id_parent **mixed**
* $id_lang **mixed**
* $active **mixed**



### <a name="method-checkBeforeMove"></a>checkBeforeMove

    boolean CMSCategoryCore::checkBeforeMove($id_cms_category, integer $id_parent)

Check if CMSCategory can be moved in another one



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L445)


#### Arguments
* $id_cms_category **mixed**
* $id_parent **integer** - &lt;p&gt;Parent candidate&lt;/p&gt;



### <a name="method-getLinkRewrite"></a>getLinkRewrite

    mixed CMSCategoryCore::getLinkRewrite($id_cms_category, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L470)


#### Arguments
* $id_cms_category **mixed**
* $id_lang **mixed**



### <a name="method-getLink"></a>getLink

    mixed CMSCategoryCore::getLink(\Link $link)





* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L490)


#### Arguments
* $link **[Link](LinkCore)**



### <a name="method-getName"></a>getName

    mixed CMSCategoryCore::getName($id_lang)





* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 498](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L498)


#### Arguments
* $id_lang **mixed**



### <a name="method-searchByName"></a>searchByName

    array CMSCategoryCore::searchByName(integer $id_lang, string $query, boolean $unrestricted)

Light back office search for categories



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L519)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $query **string** - &lt;p&gt;Searched string&lt;/p&gt;
* $unrestricted **boolean** - &lt;p&gt;allows search without lang and includes first CMSCategory and exact match&lt;/p&gt;



### <a name="method-searchByNameAndParentCMSCategoryId"></a>searchByNameAndParentCMSCategoryId

    array CMSCategoryCore::searchByNameAndParentCMSCategoryId(integer $id_lang, string $CMSCategory_name, integer $id_parent_CMSCategory)

Retrieve CMSCategory by name and parent CMSCategory id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L545)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $CMSCategory_name **string** - &lt;p&gt;Searched CMSCategory name&lt;/p&gt;
* $id_parent_CMSCategory **integer** - &lt;p&gt;parent CMSCategory ID&lt;/p&gt;



### <a name="method-getParentsCategories"></a>getParentsCategories

    array CMSCategoryCore::getParentsCategories(integer $id_lang)

Get Each parent CMSCategory of this CMSCategory until the root CMSCategory



* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L563)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### <a name="method-updatePosition"></a>updatePosition

    mixed CMSCategoryCore::updatePosition($way, $position)





* Visibility: **public**
* This method is defined in [classes/CMSCategory.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L588)


#### Arguments
* $way **mixed**
* $position **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

    mixed CMSCategoryCore::cleanPositions($id_category_parent)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L624)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-getLastPosition"></a>getLastPosition

    mixed CMSCategoryCore::getLastPosition($id_category_parent)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L643)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

    mixed CMSCategoryCore::getUrlRewriteInformations($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSCategory.php line 648](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSCategory.php#L648)


#### Arguments
* $id_category **mixed**


