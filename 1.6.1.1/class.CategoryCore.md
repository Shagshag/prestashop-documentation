Class CategoryCore
=====================





* Class name: CategoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Category.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L27)


Contents
--------


### Properties

* [$_links](#property-$_links)
* [$active](#property-$active)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$groupBox](#property-$groupBox)
* [$id](#property-$id)
* [$id_category](#property-$id_category)
* [$id_category_default](#property-$id_category_default)
* [$id_image](#property-$id_image)
* [$id_parent](#property-$id_parent)
* [$id_shop_default](#property-$id_shop_default)
* [$is_root_category](#property-$is_root_category)
* [$level_depth](#property-$level_depth)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$name](#property-$name)
* [$nleft](#property-$nleft)
* [$nright](#property-$nright)
* [$position](#property-$position)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [_subTree](#method-_subTree)
* [add](#method-add)
* [addGroups](#method-addGroups)
* [addGroupsIfNoExist](#method-addGroupsIfNoExist)
* [addPosition](#method-addPosition)
* [addShop](#method-addShop)
* [addToShop](#method-addToShop)
* [calcLevelDepth](#method-calcLevelDepth)
* [categoryExists](#method-categoryExists)
* [checkAccess](#method-checkAccess)
* [checkBeforeMove](#method-checkBeforeMove)
* [cleanAssoProducts](#method-cleanAssoProducts)
* [cleanGroups](#method-cleanGroups)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [deleteCategoriesFromShop](#method-deleteCategoriesFromShop)
* [deleteFromShop](#method-deleteFromShop)
* [deleteLite](#method-deleteLite)
* [deleteSelection](#method-deleteSelection)
* [duplicateProductCategories](#method-duplicateProductCategories)
* [existsInShop](#method-existsInShop)
* [getAllCategoriesName](#method-getAllCategoriesName)
* [getAllChildren](#method-getAllChildren)
* [getAllParents](#method-getAllParents)
* [getCategories](#method-getCategories)
* [getCategoriesWithoutParent](#method-getCategoriesWithoutParent)
* [getCategoryInformations](#method-getCategoryInformations)
* [getChildren](#method-getChildren)
* [getChildrenWithNbSelectedSubCat](#method-getChildrenWithNbSelectedSubCat)
* [getChildrenWs](#method-getChildrenWs)
* [getDescriptionClean](#method-getDescriptionClean)
* [getDuplicatePosition](#method-getDuplicatePosition)
* [getGroups](#method-getGroups)
* [getHomeCategories](#method-getHomeCategories)
* [getInterval](#method-getInterval)
* [getLastPosition](#method-getLastPosition)
* [getLink](#method-getLink)
* [getLinkRewrite](#method-getLinkRewrite)
* [getName](#method-getName)
* [getNestedCategories](#method-getNestedCategories)
* [getParentsCategories](#method-getParentsCategories)
* [getProducts](#method-getProducts)
* [getProductsWs](#method-getProductsWs)
* [getRootCategories](#method-getRootCategories)
* [getRootCategory](#method-getRootCategory)
* [getShopID](#method-getShopID)
* [getShopsByCategory](#method-getShopsByCategory)
* [getSimpleCategories](#method-getSimpleCategories)
* [getSubCategories](#method-getSubCategories)
* [getTopCategory](#method-getTopCategory)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [getWsNbProductsRecursive](#method-getWsNbProductsRecursive)
* [hasChildren](#method-hasChildren)
* [inShop](#method-inShop)
* [inShopStatic](#method-inShopStatic)
* [isParentCategoryAvailable](#method-isParentCategoryAvailable)
* [isRootCategoryForAShop](#method-isRootCategoryForAShop)
* [recalculateLevelDepth](#method-recalculateLevelDepth)
* [recurseCategory](#method-recurseCategory)
* [recurseLiteCategTree](#method-recurseLiteCategTree)
* [recursiveDelete](#method-recursiveDelete)
* [regenerateEntireNtree](#method-regenerateEntireNtree)
* [searchByName](#method-searchByName)
* [searchByNameAndParentCategoryId](#method-searchByNameAndParentCategoryId)
* [searchByPath](#method-searchByPath)
* [setNewGroupForHome](#method-setNewGroupForHome)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateFromShop](#method-updateFromShop)
* [updateGroup](#method-updateGroup)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$_links"></a>$_links

```php
protected mixed $_links = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Category.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L87).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/Category.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L38).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Category.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L74).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Category.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L77).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'category', 'primary' => 'id_category', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('nleft' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'nright' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'level_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'is_root_category' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'position' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Category.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L92).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Category.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L44).


### <a name="property-$groupBox"></a>$groupBox

```php
public mixed $groupBox
```





* Visibility: **public**
* Source: [classes/Category.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L85).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Category.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L29).


### <a name="property-$id_category"></a>$id_category

```php
public integer $id_category
```





* Visibility: **public**
* Source: [classes/Category.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L32).


### <a name="property-$id_category_default"></a>$id_category_default

```php
public integer $id_category_default
```





* Visibility: **public**
* Source: [classes/Category.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L50).


### <a name="property-$id_image"></a>$id_image

```php
public string $id_image = 'default'
```





* Visibility: **public**
* Source: [classes/Category.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L119).


### <a name="property-$id_parent"></a>$id_parent

```php
public integer $id_parent
```





* Visibility: **public**
* Source: [classes/Category.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L47).


### <a name="property-$id_shop_default"></a>$id_shop_default

```php
public integer $id_shop_default
```





* Visibility: **public**
* Source: [classes/Category.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L83).


### <a name="property-$is_root_category"></a>$is_root_category

```php
public boolean $is_root_category
```





* Visibility: **public**
* Source: [classes/Category.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L80).


### <a name="property-$level_depth"></a>$level_depth

```php
public integer $level_depth
```





* Visibility: **public**
* Source: [classes/Category.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L53).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Category.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L62).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Category.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L71).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Category.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L68).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Category.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L65).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Category.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L35).


### <a name="property-$nleft"></a>$nleft

```php
public integer $nleft
```





* Visibility: **public**
* Source: [classes/Category.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L56).


### <a name="property-$nright"></a>$nright

```php
public integer $nright
```





* Visibility: **public**
* Source: [classes/Category.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L59).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Category.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L41).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'categories', 'hidden_fields' => array('nleft', 'nright', 'groupBox'), 'fields' => array('id_parent' => array('xlink_resource' => 'categories'), 'level_depth' => array('setter' => false), 'nb_products_recursive' => array('getter' => 'getWsNbProductsRecursive', 'setter' => false)), 'associations' => array('categories' => array('getter' => 'getChildrenWs', 'resource' => 'category'), 'products' => array('getter' => 'getProductsWs', 'resource' => 'product')))
```





* Visibility: **protected**
* Source: [classes/Category.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L121).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CategoryCore::__construct($id_category, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L135)


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-_subTree"></a>_subTree

```php
mixed CategoryCore::_subTree($categories, $id_category, $n)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Category.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L426)


#### Arguments
* $categories **mixed**
* $id_category **mixed**
* $n **mixed**



### <a name="method-add"></a>add

```php
mixed CategoryCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Category.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L147)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addGroups"></a>addGroups

```php
mixed CategoryCore::addGroups($groups)
```





* Visibility: **public**
* Source: [classes/Category.php line 1257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1257)


#### Arguments
* $groups **mixed**



### <a name="method-addGroupsIfNoExist"></a>addGroupsIfNoExist

```php
mixed CategoryCore::addGroupsIfNoExist($id_group)
```





* Visibility: **public**
* Source: [classes/Category.php line 1284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1284)


#### Arguments
* $id_group **mixed**



### <a name="method-addPosition"></a>addPosition

```php
mixed CategoryCore::addPosition($position, $id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 1701](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1701)


#### Arguments
* $position **mixed**
* $id_shop **mixed**



### <a name="method-addShop"></a>addShop

```php
boolean CategoryCore::addShop(integer $id_shop)
```

Add association between shop and categories



* Visibility: **public**
* Source: [classes/Category.php line 1620](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1620)


#### Arguments
* $id_shop **integer**



### <a name="method-addToShop"></a>addToShop

```php
boolean CategoryCore::addToShop(array $categories, $id_shop)
```

Add some categories to a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1787)


#### Arguments
* $categories **array**
* $id_shop **mixed**



### <a name="method-calcLevelDepth"></a>calcLevelDepth

```php
integer CategoryCore::calcLevelDepth()
```

Get the depth level for the category



* Visibility: **public**
* Source: [classes/Category.php line 388](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L388)




### <a name="method-categoryExists"></a>categoryExists

```php
boolean CategoryCore::categoryExists(integer $id_category)
```

Specify if a category already in base



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1237)


#### Arguments
* $id_category **integer** - Category id



### <a name="method-checkAccess"></a>checkAccess

```php
boolean CategoryCore::checkAccess(mixed $id_customer)
```

checkAccess return true if id_customer is in a group allowed to see this category.



* Visibility: **public**
* Source: [classes/Category.php line 1300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1300)


#### Arguments
* $id_customer **mixed**



### <a name="method-checkBeforeMove"></a>checkBeforeMove

```php
boolean CategoryCore::checkBeforeMove(integer $id_category, integer $id_parent)
```

Check if category can be moved in another one.

The category cannot be moved in a child category.

* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1016](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1016)


#### Arguments
* $id_category **integer** - current category
* $id_parent **integer** - Parent candidate



### <a name="method-cleanAssoProducts"></a>cleanAssoProducts

```php
mixed CategoryCore::cleanAssoProducts()
```





* Visibility: **public**
* Source: [classes/Category.php line 1252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1252)




### <a name="method-cleanGroups"></a>cleanGroups

```php
mixed CategoryCore::cleanGroups()
```





* Visibility: **public**
* Source: [classes/Category.php line 1247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1247)




### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean CategoryCore::cleanPositions(mixed $id_category_parent)
```

cleanPositions keep order of category in $id_category_parent,
but remove duplicate position. Should not be used if positions
are clean at the beginning !



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1396](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1396)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-delete"></a>delete

```php
mixed CategoryCore::delete()
```





* Visibility: **public**
* Source: [classes/Category.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L327)




### <a name="method-deleteCategoriesFromShop"></a>deleteCategoriesFromShop

```php
boolean CategoryCore::deleteCategoriesFromShop($id_shop)
```

Delete every categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1777](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1777)


#### Arguments
* $id_shop **mixed**



### <a name="method-deleteFromShop"></a>deleteFromShop

```php
boolean CategoryCore::deleteFromShop(integer $id_shop)
```

Delete category from shop $id_shop



* Visibility: **public**
* Source: [classes/Category.php line 1765](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1765)


#### Arguments
* $id_shop **integer**



### <a name="method-deleteLite"></a>deleteLite

```php
mixed CategoryCore::deleteLite()
```





* Visibility: **public**
* Source: [classes/Category.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L321)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed CategoryCore::deleteSelection($categories)
```

Delete several categories from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/Category.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L369)


#### Arguments
* $categories **mixed**



### <a name="method-duplicateProductCategories"></a>duplicateProductCategories

```php
boolean CategoryCore::duplicateProductCategories(integer $id_old, boolean $id_new)
```

Copy products from a category to another



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 983](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L983)


#### Arguments
* $id_old **integer** - Source category ID
* $id_new **boolean** - Destination category ID



### <a name="method-existsInShop"></a>existsInShop

```php
mixed CategoryCore::existsInShop($id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 1811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1811)


#### Arguments
* $id_shop **mixed**



### <a name="method-getAllCategoriesName"></a>getAllCategoriesName

```php
mixed CategoryCore::getAllCategoriesName($root_category, $id_lang, $active, $groups, $use_shop_restriction, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L509)


#### Arguments
* $root_category **mixed**
* $id_lang **mixed**
* $active **mixed**
* $groups **mixed**
* $use_shop_restriction **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getAllChildren"></a>getAllChildren

```php
\PrestaShopCollection CategoryCore::getAllChildren(integer $id_lang)
```

Return an array of all children of the current category



* Visibility: **public**
* Source: [classes/Category.php line 901](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L901)


#### Arguments
* $id_lang **integer**



### <a name="method-getAllParents"></a>getAllParents

```php
\PrestaShopCollection CategoryCore::getAllParents(integer $id_lang)
```

Return an array of all parents of the current category



* Visibility: **public**
* Source: [classes/Category.php line 919](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L919)


#### Arguments
* $id_lang **integer**



### <a name="method-getCategories"></a>getCategories

```php
array CategoryCore::getCategories(integer $id_lang, boolean $active, $order, $sql_filter, $sql_sort, $sql_limit)
```

Return available categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L480)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories
* $order **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getCategoriesWithoutParent"></a>getCategoriesWithoutParent

```php
mixed CategoryCore::getCategoriesWithoutParent()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1656)




### <a name="method-getCategoryInformations"></a>getCategoryInformations

```php
Array CategoryCore::getCategoryInformations(Array $ids_category, integer $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1573)


#### Arguments
* $ids_category **Array**
* $id_lang **integer**



### <a name="method-getChildren"></a>getChildren

```php
array CategoryCore::getChildren(integer $id_parent, integer $id_lang, boolean $active, boolean $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 841](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L841)


#### Arguments
* $id_parent **integer**
* $id_lang **integer**
* $active **boolean**
* $id_shop **boolean**



### <a name="method-getChildrenWithNbSelectedSubCat"></a>getChildrenWithNbSelectedSubCat

```php
array CategoryCore::getChildrenWithNbSelectedSubCat(integer $id_parent, $selected_cat, integer $id_lang, \Shop $shop, $use_shop_context)
```

This method allow to return children categories with the number of sub children selected for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L939)


#### Arguments
* $id_parent **integer**
* $selected_cat **mixed**
* $id_lang **integer**
* $shop **[Shop](class.ShopCore.md)**
* $use_shop_context **mixed**



### <a name="method-getChildrenWs"></a>getChildrenWs

```php
mixed CategoryCore::getChildrenWs()
```





* Visibility: **public**
* Source: [classes/Category.php line 1507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1507)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
mixed CategoryCore::getDescriptionClean($description)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L142)


#### Arguments
* $description **mixed**



### <a name="method-getDuplicatePosition"></a>getDuplicatePosition

```php
array CategoryCore::getDuplicatePosition()
```

Search for another category with the same parent and the same position



* Visibility: **public**
* Source: [classes/Category.php line 1534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1534)




### <a name="method-getGroups"></a>getGroups

```php
mixed CategoryCore::getGroups()
```





* Visibility: **public**
* Source: [classes/Category.php line 1266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1266)




### <a name="method-getHomeCategories"></a>getHomeCategories

```php
array CategoryCore::getHomeCategories(integer $id_lang, boolean $active, $id_shop)
```

Return main categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 803](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L803)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories
* $id_shop **mixed**



### <a name="method-getInterval"></a>getInterval

```php
array CategoryCore::getInterval(integer $id)
```

Return nleft and nright fields for a given category



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1461)


#### Arguments
* $id **integer**



### <a name="method-getLastPosition"></a>getLastPosition

```php
integer CategoryCore::getLastPosition(integer $id_category_parent, integer $id_shop)
```

this function return the number of category + 1 having $id_category_parent as parent.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1426](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1426)


#### Arguments
* $id_category_parent **integer** - the parent category
* $id_shop **integer**



### <a name="method-getLink"></a>getLink

```php
mixed CategoryCore::getLink(\Link $link, $id_lang)
```





* Visibility: **public**
* Source: [classes/Category.php line 1058](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1058)


#### Arguments
* $link **[Link](class.LinkCore.md)**
* $id_lang **mixed**



### <a name="method-getLinkRewrite"></a>getLinkRewrite

```php
mixed CategoryCore::getLinkRewrite($id_category, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1041](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1041)


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**



### <a name="method-getName"></a>getName

```php
mixed CategoryCore::getName($id_lang)
```





* Visibility: **public**
* Source: [classes/Category.php line 1072](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1072)


#### Arguments
* $id_lang **mixed**



### <a name="method-getNestedCategories"></a>getNestedCategories

```php
mixed CategoryCore::getNestedCategories($root_category, $id_lang, $active, $groups, $use_shop_restriction, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L552)


#### Arguments
* $root_category **mixed**
* $id_lang **mixed**
* $active **mixed**
* $groups **mixed**
* $use_shop_restriction **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getParentsCategories"></a>getParentsCategories

```php
array CategoryCore::getParentsCategories(integer $id_lang)
```

Get Each parent category of this category until the root category



* Visibility: **public**
* Source: [classes/Category.php line 1181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1181)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getProducts"></a>getProducts

```php
array|integer|false CategoryCore::getProducts(integer $id_lang, integer $p, integer $n, string|null $order_by, string|null $order_way, boolean $get_total, boolean $active, boolean $random, integer $random_number_products, boolean $check_access, \Context|null $context)
```

Returns category products



* Visibility: **public**
* Source: [classes/Category.php line 686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L686)


#### Arguments
* $id_lang **integer** - Language ID
* $p **integer** - Page number
* $n **integer** - Number of products per page
* $order_by **string|null** - ORDER BY column
* $order_way **string|null** - Order way
* $get_total **boolean** - If set to true, returns the total number of results only
* $active **boolean** - If set to true, finds only active products
* $random **boolean** - If true, sets a random filter for returned products
* $random_number_products **integer** - Number of products to return if random is activated
* $check_access **boolean** - If set tot rue, check if the current customer
                                           can see products from this category
* $context **[Context](class.ContextCore.md)|null**



### <a name="method-getProductsWs"></a>getProductsWs

```php
mixed CategoryCore::getProductsWs()
```





* Visibility: **public**
* Source: [classes/Category.php line 1519](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1519)




### <a name="method-getRootCategories"></a>getRootCategories

```php
mixed CategoryCore::getRootCategories($id_lang, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1642)


#### Arguments
* $id_lang **mixed**
* $active **mixed**



### <a name="method-getRootCategory"></a>getRootCategory

```php
mixed CategoryCore::getRootCategory($id_lang, \Shop $shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L808)


#### Arguments
* $id_lang **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getShopID"></a>getShopID

```php
mixed CategoryCore::getShopID()
```





* Visibility: **public**
* Source: [classes/Category.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L626)




### <a name="method-getShopsByCategory"></a>getShopsByCategory

```php
mixed CategoryCore::getShopsByCategory($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1730)


#### Arguments
* $id_category **mixed**



### <a name="method-getSimpleCategories"></a>getSimpleCategories

```php
mixed CategoryCore::getSimpleCategories($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 613](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L613)


#### Arguments
* $id_lang **mixed**



### <a name="method-getSubCategories"></a>getSubCategories

```php
array CategoryCore::getSubCategories(integer $id_lang, boolean $active)
```

Return current category childs



* Visibility: **public**
* Source: [classes/Category.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L638)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getTopCategory"></a>getTopCategory

```php
\Category CategoryCore::getTopCategory(null $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1683)


#### Arguments
* $id_lang **null**



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed CategoryCore::getUrlRewriteInformations($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1443)


#### Arguments
* $id_category **mixed**



### <a name="method-getWsNbProductsRecursive"></a>getWsNbProductsRecursive

```php
mixed CategoryCore::getWsNbProductsRecursive()
```





* Visibility: **public**
* Source: [classes/Category.php line 1545](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1545)




### <a name="method-hasChildren"></a>hasChildren

```php
array CategoryCore::hasChildren(integer $id_parent, integer $id_lang, boolean $active, boolean $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L873)


#### Arguments
* $id_parent **integer**
* $id_lang **integer**
* $active **boolean**
* $id_shop **boolean**



### <a name="method-inShop"></a>inShop

```php
boolean CategoryCore::inShop(\Shop $shop)
```

Check if current category is a child of shop root category



* Visibility: **public**
* Source: [classes/Category.php line 1482](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1482)


#### Arguments
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-inShopStatic"></a>inShopStatic

```php
mixed CategoryCore::inShopStatic($id_category, \Shop $shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1494)


#### Arguments
* $id_category **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-isParentCategoryAvailable"></a>isParentCategoryAvailable

```php
boolean CategoryCore::isParentCategoryAvailable($id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 1603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1603)


#### Arguments
* $id_shop **mixed**



### <a name="method-isRootCategoryForAShop"></a>isRootCategoryForAShop

```php
mixed CategoryCore::isRootCategoryForAShop()
```





* Visibility: **public**
* Source: [classes/Category.php line 1671](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1671)




### <a name="method-recalculateLevelDepth"></a>recalculateLevelDepth

```php
mixed CategoryCore::recalculateLevelDepth(integer $id_category)
```

Updates level_depth for all children of the given id_category



* Visibility: **public**
* Source: [classes/Category.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L447)


#### Arguments
* $id_category **integer** - parent category



### <a name="method-recurseCategory"></a>recurseCategory

```php
mixed CategoryCore::recurseCategory($categories, $current, $id_category, $id_selected)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L283)


#### Arguments
* $categories **mixed**
* $current **mixed**
* $id_category **mixed**
* $id_selected **mixed**



### <a name="method-recurseLiteCategTree"></a>recurseLiteCategTree

```php
array CategoryCore::recurseLiteCategTree(integer $max_depth, integer $current_depth, integer $id_lang, array $excluded_ids_array)
```

Recursive scan of subcategories



* Visibility: **public**
* Source: [classes/Category.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L249)


#### Arguments
* $max_depth **integer** - Maximum depth of the tree (i.e. 2 =&gt; 3 levels depth)
* $current_depth **integer** - specify the current depth in the tree (don&#039;t use it, only for rucursivity!)
* $id_lang **integer** - Specify the id of the language used
* $excluded_ids_array **array** - specify a list of ids to exclude of results



### <a name="method-recursiveDelete"></a>recursiveDelete

```php
mixed CategoryCore::recursiveDelete($to_delete, integer $id_category)
```

Recursively add specified category childs to $to_delete array



* Visibility: **protected**
* Source: [classes/Category.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L305)


#### Arguments
* $to_delete **mixed**
* $id_category **integer** - Parent category ID



### <a name="method-regenerateEntireNtree"></a>regenerateEntireNtree

```php
mixed CategoryCore::regenerateEntireNtree()
```

Re-calculate the values of all branches of the nested tree



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L405)




### <a name="method-searchByName"></a>searchByName

```php
array CategoryCore::searchByName(integer $id_lang, string $query, boolean $unrestricted, boolean $skip_cache)
```

Light back office search for categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1094](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1094)


#### Arguments
* $id_lang **integer** - Language ID
* $query **string** - Searched string
* $unrestricted **boolean** - allows search without lang and includes first category and exact match
* $skip_cache **boolean**



### <a name="method-searchByNameAndParentCategoryId"></a>searchByNameAndParentCategoryId

```php
array CategoryCore::searchByNameAndParentCategoryId(integer $id_lang, string $category_name, integer $id_parent_category)
```

Retrieve category by name and parent category id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1128)


#### Arguments
* $id_lang **integer** - Language ID
* $category_name **string** - Searched category name
* $id_parent_category **integer** - parent category ID



### <a name="method-searchByPath"></a>searchByPath

```php
array CategoryCore::searchByPath(integer $id_lang, string $path, boolean $object_to_create, $method_to_create)
```

Search with Pathes for categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1150)


#### Arguments
* $id_lang **integer** - Language ID
* $path **string** - of category
* $object_to_create **boolean** - a category
 * @param bool $method_to_create a category
* $method_to_create **mixed**



### <a name="method-setNewGroupForHome"></a>setNewGroupForHome

```php
mixed CategoryCore::setNewGroupForHome($id_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1336)


#### Arguments
* $id_group **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed CategoryCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Category.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L232)




### <a name="method-update"></a>update

```php
boolean CategoryCore::update(mixed $null_values)
```

update category positions in parent



* Visibility: **public**
* Source: [classes/Category.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L183)


#### Arguments
* $null_values **mixed**



### <a name="method-updateFromShop"></a>updateFromShop

```php
array CategoryCore::updateFromShop(string $categories, string $id_shop)
```

Update categories for a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1745)


#### Arguments
* $categories **string** - Categories list to associate a shop
* $id_shop **string** - Categories list to associate a shop



### <a name="method-updateGroup"></a>updateGroup

```php
mixed CategoryCore::updateGroup(array $list)
```

Update customer groups associated to the object



* Visibility: **public**
* Source: [classes/Category.php line 1327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1327)


#### Arguments
* $list **array** - groups



### <a name="method-updatePosition"></a>updatePosition

```php
mixed CategoryCore::updatePosition($way, $position)
```





* Visibility: **public**
* Source: [classes/Category.php line 1347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Category.php#L1347)


#### Arguments
* $way **mixed**
* $position **mixed**


