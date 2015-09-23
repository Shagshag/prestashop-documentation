Class CMSCategoryCore
=====================





* Class name: CMSCategoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CMSCategory.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L27)


Contents
--------


### Properties

* [$_links](#property-$_links)
* [$active](#property-$active)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$id](#property-$id)
* [$id_cms_category](#property-$id_cms_category)
* [$id_parent](#property-$id_parent)
* [$level_depth](#property-$level_depth)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$name](#property-$name)
* [$position](#property-$position)

### Methods

* [add](#method-add)
* [calcLevelDepth](#method-calcLevelDepth)
* [checkBeforeMove](#method-checkBeforeMove)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [getCategories](#method-getCategories)
* [getChildren](#method-getChildren)
* [getHomeCategories](#method-getHomeCategories)
* [getLastPosition](#method-getLastPosition)
* [getLink](#method-getLink)
* [getLinkRewrite](#method-getLinkRewrite)
* [getName](#method-getName)
* [getParentsCategories](#method-getParentsCategories)
* [getRecurseCategory](#method-getRecurseCategory)
* [getSimpleCategories](#method-getSimpleCategories)
* [getSubCategories](#method-getSubCategories)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [hideCMSCategoryPosition](#method-hideCMSCategoryPosition)
* [recurseCMSCategory](#method-recurseCMSCategory)
* [recurseLiteCategTree](#method-recurseLiteCategTree)
* [recursiveDelete](#method-recursiveDelete)
* [searchByName](#method-searchByName)
* [searchByNameAndParentCMSCategoryId](#method-searchByNameAndParentCMSCategoryId)
* [update](#method-update)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$_links"></a>$_links

```php
protected mixed $_links = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/CMSCategory.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L70).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L38).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L65).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L68).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cms_category', 'primary' => 'id_cms_category', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'position' => array('type' => self::TYPE_INT), 'level_depth' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 64), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CMSCategory.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L75).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L41).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L29).


### <a name="property-$id_cms_category"></a>$id_cms_category

```php
public integer $id_cms_category
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L32).


### <a name="property-$id_parent"></a>$id_parent

```php
public integer $id_parent
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L44).


### <a name="property-$level_depth"></a>$level_depth

```php
public integer $level_depth
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L50).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L53).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L62).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L59).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L56).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L35).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L47).


Methods
-------


### <a name="method-add"></a>add

```php
mixed CMSCategoryCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L98)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-calcLevelDepth"></a>calcLevelDepth

```php
integer CMSCategoryCore::calcLevelDepth()
```

Get the number of parent categories



* Visibility: **public**
* Source: [classes/CMSCategory.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L300)




### <a name="method-checkBeforeMove"></a>checkBeforeMove

```php
boolean CMSCategoryCore::checkBeforeMove($id_cms_category, integer $id_parent)
```

Check if CMSCategory can be moved in another one



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L427)


#### Arguments
* $id_cms_category **mixed**
* $id_parent **integer** - Parent candidate



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed CMSCategoryCore::cleanPositions($id_category_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L588)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-delete"></a>delete

```php
mixed CMSCategoryCore::delete()
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L237)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed CMSCategoryCore::deleteSelection($categories)
```

Delete several categories from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/CMSCategory.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L284)


#### Arguments
* $categories **mixed**



### <a name="method-getCategories"></a>getCategories

```php
array CMSCategoryCore::getCategories(integer $id_lang, boolean $active, $order)
```

Return available categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L315)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories
* $order **mixed**



### <a name="method-getChildren"></a>getChildren

```php
mixed CMSCategoryCore::getChildren($id_parent, $id_lang, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L397)


#### Arguments
* $id_parent **mixed**
* $id_lang **mixed**
* $active **mixed**



### <a name="method-getHomeCategories"></a>getHomeCategories

```php
array CMSCategoryCore::getHomeCategories(integer $id_lang, boolean $active)
```

Return main categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L392)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getLastPosition"></a>getLastPosition

```php
mixed CMSCategoryCore::getLastPosition($id_category_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 608](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L608)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-getLink"></a>getLink

```php
mixed CMSCategoryCore::getLink(\Link $link)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L461)


#### Arguments
* $link **[Link](class.LinkCore.md)**



### <a name="method-getLinkRewrite"></a>getLinkRewrite

```php
mixed CMSCategoryCore::getLinkRewrite($id_cms_category, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L443)


#### Arguments
* $id_cms_category **mixed**
* $id_lang **mixed**



### <a name="method-getName"></a>getName

```php
mixed CMSCategoryCore::getName($id_lang)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L468)


#### Arguments
* $id_lang **mixed**



### <a name="method-getParentsCategories"></a>getParentsCategories

```php
array CMSCategoryCore::getParentsCategories(integer $id_lang)
```

Get Each parent CMSCategory of this CMSCategory until the root CMSCategory



* Visibility: **public**
* Source: [classes/CMSCategory.php line 532](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L532)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getRecurseCategory"></a>getRecurseCategory

```php
mixed CMSCategoryCore::getRecurseCategory($id_lang, $current, $active, $links, \Link $link)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L162)


#### Arguments
* $id_lang **mixed**
* $current **mixed**
* $active **mixed**
* $links **mixed**
* $link **[Link](class.LinkCore.md)**



### <a name="method-getSimpleCategories"></a>getSimpleCategories

```php
mixed CMSCategoryCore::getSimpleCategories($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L337)


#### Arguments
* $id_lang **mixed**



### <a name="method-getSubCategories"></a>getSubCategories

```php
array CMSCategoryCore::getSubCategories(integer $id_lang, boolean $active)
```

Return current CMSCategory childs



* Visibility: **public**
* Source: [classes/CMSCategory.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L354)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed CMSCategoryCore::getUrlRewriteInformations($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 613](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L613)


#### Arguments
* $id_category **mixed**



### <a name="method-hideCMSCategoryPosition"></a>hideCMSCategoryPosition

```php
string CMSCategoryCore::hideCMSCategoryPosition(string $name)
```

Hide CMSCategory prefix used for position



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L380)


#### Arguments
* $name **string** - CMSCategory name



### <a name="method-recurseCMSCategory"></a>recurseCMSCategory

```php
mixed CMSCategoryCore::recurseCMSCategory($categories, $current, $id_cms_category, $id_selected, $is_html)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L202)


#### Arguments
* $categories **mixed**
* $current **mixed**
* $id_cms_category **mixed**
* $id_selected **mixed**
* $is_html **mixed**



### <a name="method-recurseLiteCategTree"></a>recurseLiteCategTree

```php
array CMSCategoryCore::recurseLiteCategTree(integer $max_depth, integer $currentDepth, $id_lang, array $excluded_ids_array, \Link $link)
```

Recursive scan of subcategories



* Visibility: **public**
* Source: [classes/CMSCategory.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L129)


#### Arguments
* $max_depth **integer** - Maximum depth of the tree (i.e. 2 =&gt; 3 levels depth)
* $currentDepth **integer** - specify the current depth in the tree (don&#039;t use it, only for rucursivity!)
* $id_lang **mixed**
* $excluded_ids_array **array** - specify a list of ids to exclude of results
* $link **[Link](class.LinkCore.md)**



### <a name="method-recursiveDelete"></a>recursiveDelete

```php
mixed CMSCategoryCore::recursiveDelete($to_delete, array|integer $id_cms_category)
```

Recursively add specified CMSCategory childs to $toDelete array



* Visibility: **protected**
* Source: [classes/CMSCategory.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L221)


#### Arguments
* $to_delete **mixed**
* $id_cms_category **array|integer** - Parent CMSCategory ID



### <a name="method-searchByName"></a>searchByName

```php
array CMSCategoryCore::searchByName(integer $id_lang, string $query, boolean $unrestricted)
```

Light back office search for categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 489](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L489)


#### Arguments
* $id_lang **integer** - Language ID
* $query **string** - Searched string
* $unrestricted **boolean** - allows search without lang and includes first CMSCategory and exact match



### <a name="method-searchByNameAndParentCMSCategoryId"></a>searchByNameAndParentCMSCategoryId

```php
array CMSCategoryCore::searchByNameAndParentCMSCategoryId(integer $id_lang, string $CMSCategory_name, integer $id_parent_CMSCategory)
```

Retrieve CMSCategory by name and parent CMSCategory id



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L514)


#### Arguments
* $id_lang **integer** - Language ID
* $CMSCategory_name **string** - Searched CMSCategory name
* $id_parent_CMSCategory **integer** - parent CMSCategory ID



### <a name="method-update"></a>update

```php
mixed CMSCategoryCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L110)


#### Arguments
* $null_values **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
mixed CMSCategoryCore::updatePosition($way, $position)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 556](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/CMSCategory.php#L556)


#### Arguments
* $way **mixed**
* $position **mixed**


