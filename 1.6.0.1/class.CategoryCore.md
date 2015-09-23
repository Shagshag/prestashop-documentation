Class CategoryCore
=====================





* Class name: CategoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Category.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L27)


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
* [getAllChildren](#method-getAllChildren)
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
* Source: [classes/Category.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L87).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/Category.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L38).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Category.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L74).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Category.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L77).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'category', 'primary' => 'id_category', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('nleft' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'nright' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'level_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'is_root_category' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'position' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Category.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L92).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Category.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L44).


### <a name="property-$groupBox"></a>$groupBox

```php
public mixed $groupBox
```





* Visibility: **public**
* Source: [classes/Category.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L85).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Category.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L29).


### <a name="property-$id_category"></a>$id_category

```php
public integer $id_category
```





* Visibility: **public**
* Source: [classes/Category.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L32).


### <a name="property-$id_category_default"></a>$id_category_default

```php
public integer $id_category_default
```





* Visibility: **public**
* Source: [classes/Category.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L50).


### <a name="property-$id_image"></a>$id_image

```php
public string $id_image = 'default'
```





* Visibility: **public**
* Source: [classes/Category.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L119).


### <a name="property-$id_parent"></a>$id_parent

```php
public integer $id_parent
```





* Visibility: **public**
* Source: [classes/Category.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L47).


### <a name="property-$id_shop_default"></a>$id_shop_default

```php
public integer $id_shop_default
```





* Visibility: **public**
* Source: [classes/Category.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L83).


### <a name="property-$is_root_category"></a>$is_root_category

```php
public boolean $is_root_category
```





* Visibility: **public**
* Source: [classes/Category.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L80).


### <a name="property-$level_depth"></a>$level_depth

```php
public integer $level_depth
```





* Visibility: **public**
* Source: [classes/Category.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L53).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Category.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L62).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Category.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L71).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Category.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L68).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Category.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L65).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Category.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L35).


### <a name="property-$nleft"></a>$nleft

```php
public integer $nleft
```





* Visibility: **public**
* Source: [classes/Category.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L56).


### <a name="property-$nright"></a>$nright

```php
public integer $nright
```





* Visibility: **public**
* Source: [classes/Category.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L59).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Category.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L41).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'categories', 'hidden_fields' => array('nleft', 'nright', 'groupBox'), 'fields' => array('id_parent' => array('xlink_resource' => 'categories'), 'level_depth' => array('setter' => false), 'nb_products_recursive' => array('getter' => 'getWsNbProductsRecursive', 'setter' => false)), 'associations' => array('categories' => array('getter' => 'getChildrenWs', 'resource' => 'category'), 'products' => array('getter' => 'getProductsWs', 'resource' => 'product')))
```





* Visibility: **protected**
* Source: [classes/Category.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L121).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CategoryCore::__construct($id_category, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L135)


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
* Source: [classes/Category.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L402)


#### Arguments
* $categories **mixed**
* $id_category **mixed**
* $n **mixed**



### <a name="method-add"></a>add

```php
mixed CategoryCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Category.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L152)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addGroups"></a>addGroups

```php
mixed CategoryCore::addGroups($groups)
```





* Visibility: **public**
* Source: [classes/Category.php line 1040](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1040)


#### Arguments
* $groups **mixed**



### <a name="method-addGroupsIfNoExist"></a>addGroupsIfNoExist

```php
mixed CategoryCore::addGroupsIfNoExist($id_group)
```





* Visibility: **public**
* Source: [classes/Category.php line 1062](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1062)


#### Arguments
* $id_group **mixed**



### <a name="method-addPosition"></a>addPosition

```php
mixed CategoryCore::addPosition($position, $id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 1461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1461)


#### Arguments
* $position **mixed**
* $id_shop **mixed**



### <a name="method-addShop"></a>addShop

```php
boolean CategoryCore::addShop(integer $id_shop)
```

Add association between shop and cateogries



* Visibility: **public**
* Source: [classes/Category.php line 1395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1395)


#### Arguments
* $id_shop **integer**



### <a name="method-addToShop"></a>addToShop

```php
boolean CategoryCore::addToShop(array $categories, $id_shop)
```

Add some categories to a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1550)


#### Arguments
* $categories **array**
* $id_shop **mixed**



### <a name="method-calcLevelDepth"></a>calcLevelDepth

```php
integer CategoryCore::calcLevelDepth()
```

Get the depth level for the category



* Visibility: **public**
* Source: [classes/Category.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L368)




### <a name="method-categoryExists"></a>categoryExists

```php
boolean CategoryCore::categoryExists($id_category)
```

Specify if a category already in base



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1020](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1020)


#### Arguments
* $id_category **mixed** - Category id



### <a name="method-checkAccess"></a>checkAccess

```php
boolean CategoryCore::checkAccess(mixed $id_customer)
```

checkAccess return true if id_customer is in a group allowed to see this category.



* Visibility: **public**
* Source: [classes/Category.php line 1078](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1078)


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
* Source: [classes/Category.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L854)


#### Arguments
* $id_category **integer** - current category
* $id_parent **integer** - Parent candidate



### <a name="method-cleanAssoProducts"></a>cleanAssoProducts

```php
mixed CategoryCore::cleanAssoProducts()
```





* Visibility: **public**
* Source: [classes/Category.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1035)




### <a name="method-cleanGroups"></a>cleanGroups

```php
mixed CategoryCore::cleanGroups()
```





* Visibility: **public**
* Source: [classes/Category.php line 1030](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1030)




### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean CategoryCore::cleanPositions(mixed $id_category_parent)
```

cleanPositions keep order of category in $id_category_parent,
but remove duplicate position. Should not be used if positions
are clean at the beginning !



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1175)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-delete"></a>delete

```php
mixed CategoryCore::delete()
```





* Visibility: **public**
* Source: [classes/Category.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L309)




### <a name="method-deleteCategoriesFromShop"></a>deleteCategoriesFromShop

```php
boolean CategoryCore::deleteCategoriesFromShop($id_shop)
```

Delete every categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1538](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1538)


#### Arguments
* $id_shop **mixed**



### <a name="method-deleteFromShop"></a>deleteFromShop

```php
boolean CategoryCore::deleteFromShop(integer $id_shop)
```

Delete category from shop $id_shop



* Visibility: **public**
* Source: [classes/Category.php line 1525](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1525)


#### Arguments
* $id_shop **integer**



### <a name="method-deleteLite"></a>deleteLite

```php
mixed CategoryCore::deleteLite()
```





* Visibility: **public**
* Source: [classes/Category.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L303)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed CategoryCore::deleteSelection($categories)
```

Delete several categories from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/Category.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L349)


#### Arguments
* $categories **mixed**



### <a name="method-duplicateProductCategories"></a>duplicateProductCategories

```php
boolean CategoryCore::duplicateProductCategories(integer $id_old, boolean $id_new)
```

Copy products from a category to another



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L823)


#### Arguments
* $id_old **integer** - Source category ID
* $id_new **boolean** - Destination category ID



### <a name="method-existsInShop"></a>existsInShop

```php
mixed CategoryCore::existsInShop($id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 1573](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1573)


#### Arguments
* $id_shop **mixed**



### <a name="method-getAllChildren"></a>getAllChildren

```php
\Collection CategoryCore::getAllChildren(integer $id_lang)
```

Return an array of all children of the current category



* Visibility: **public**
* Source: [classes/Category.php line 766](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L766)


#### Arguments
* $id_lang **integer**



### <a name="method-getCategories"></a>getCategories

```php
array CategoryCore::getCategories(integer $id_lang, boolean $active, $order, $sql_filter, $sql_sort, $sql_limit)
```

Return available categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L455)


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
* Source: [classes/Category.php line 1428](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1428)




### <a name="method-getCategoryInformations"></a>getCategoryInformations

```php
Array CategoryCore::getCategoryInformations(Array $ids_category, integer $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1349)


#### Arguments
* $ids_category **Array**
* $id_lang **integer**



### <a name="method-getChildren"></a>getChildren

```php
array CategoryCore::getChildren(integer $id_parent, integer $id_lang, boolean $active, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L743)


#### Arguments
* $id_parent **integer**
* $id_lang **integer**
* $active **boolean**
* $id_shop **mixed**



### <a name="method-getChildrenWithNbSelectedSubCat"></a>getChildrenWithNbSelectedSubCat

```php
array CategoryCore::getChildrenWithNbSelectedSubCat(integer $id_parent, $selected_cat, integer $id_lang, \Shop $shop, $use_shop_context)
```

This method allow to return children categories with the number of sub children selected for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L785)


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
* Source: [classes/Category.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1279)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
string CategoryCore::getDescriptionClean($description)
```

Allows to display the category description without HTML tags and slashes



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L147)


#### Arguments
* $description **mixed**



### <a name="method-getDuplicatePosition"></a>getDuplicatePosition

```php
array CategoryCore::getDuplicatePosition()
```

Search for another category with the same parent and the same position



* Visibility: **public**
* Source: [classes/Category.php line 1309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1309)




### <a name="method-getGroups"></a>getGroups

```php
mixed CategoryCore::getGroups()
```





* Visibility: **public**
* Source: [classes/Category.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1049)




### <a name="method-getHomeCategories"></a>getHomeCategories

```php
array CategoryCore::getHomeCategories(integer $id_lang, boolean $active)
```

Return main categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L710)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getInterval"></a>getInterval

```php
array CategoryCore::getInterval(integer $id)
```

Return nleft and nright fields for a given category



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1241)


#### Arguments
* $id **integer**



### <a name="method-getLastPosition"></a>getLastPosition

```php
integer CategoryCore::getLastPosition(integer $id_category_parent, integer $id_shop)
```

this function return the number of category + 1 having $id_category_parent as parent.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1213)


#### Arguments
* $id_category_parent **integer** - the parent category
* $id_shop **integer**



### <a name="method-getLink"></a>getLink

```php
mixed CategoryCore::getLink(\Link $link)
```





* Visibility: **public**
* Source: [classes/Category.php line 886](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L886)


#### Arguments
* $link **[Link](class.LinkCore.md)**



### <a name="method-getLinkRewrite"></a>getLinkRewrite

```php
mixed CategoryCore::getLinkRewrite($id_category, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L870)


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**



### <a name="method-getName"></a>getName

```php
mixed CategoryCore::getName($id_lang)
```





* Visibility: **public**
* Source: [classes/Category.php line 893](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L893)


#### Arguments
* $id_lang **mixed**



### <a name="method-getNestedCategories"></a>getNestedCategories

```php
mixed CategoryCore::getNestedCategories($root_category, $id_lang, $active, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L481)


#### Arguments
* $root_category **mixed**
* $id_lang **mixed**
* $active **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getParentsCategories"></a>getParentsCategories

```php
array CategoryCore::getParentsCategories(integer $id_lang)
```

Get Each parent category of this category until the root category



* Visibility: **public**
* Source: [classes/Category.php line 963](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L963)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getProducts"></a>getProducts

```php
mixed CategoryCore::getProducts(integer $id_lang, integer $p, integer $n, $order_by, $order_way, boolean $get_total, boolean $active, boolean $random, integer $random_number_products, boolean $check_access, \Context $context)
```

Return current category products



* Visibility: **public**
* Source: [classes/Category.php line 593](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L593)


#### Arguments
* $id_lang **integer** - Language ID
* $p **integer** - Page number
* $n **integer** - Number of products per page
* $order_by **mixed**
* $order_way **mixed**
* $get_total **boolean** - return the number of results instead of the results themself
* $active **boolean** - return only active products
* $random **boolean** - active a random filter for returned products
* $random_number_products **integer** - number of products to return if random is activated
* $check_access **boolean** - set to false to return all products (even if customer hasn&#039;t access)
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductsWs"></a>getProductsWs

```php
mixed CategoryCore::getProductsWs()
```





* Visibility: **public**
* Source: [classes/Category.php line 1294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1294)




### <a name="method-getRootCategories"></a>getRootCategories

```php
mixed CategoryCore::getRootCategories($id_lang, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1416](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1416)


#### Arguments
* $id_lang **mixed**
* $active **mixed**



### <a name="method-getRootCategory"></a>getRootCategory

```php
mixed CategoryCore::getRootCategory($id_lang, \Shop $shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 715](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L715)


#### Arguments
* $id_lang **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getShopID"></a>getShopID

```php
mixed CategoryCore::getShopID()
```





* Visibility: **public**
* Source: [classes/Category.php line 536](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L536)




### <a name="method-getShopsByCategory"></a>getShopsByCategory

```php
mixed CategoryCore::getShopsByCategory($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1491](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1491)


#### Arguments
* $id_category **mixed**



### <a name="method-getSimpleCategories"></a>getSimpleCategories

```php
mixed CategoryCore::getSimpleCategories($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L523)


#### Arguments
* $id_lang **mixed**



### <a name="method-getSubCategories"></a>getSubCategories

```php
array CategoryCore::getSubCategories(integer $id_lang, boolean $active)
```

Return current category childs



* Visibility: **public**
* Source: [classes/Category.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L548)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getTopCategory"></a>getTopCategory

```php
\Category CategoryCore::getTopCategory(null $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1450](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1450)


#### Arguments
* $id_lang **null**



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed CategoryCore::getUrlRewriteInformations($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1223)


#### Arguments
* $id_category **mixed**



### <a name="method-getWsNbProductsRecursive"></a>getWsNbProductsRecursive

```php
mixed CategoryCore::getWsNbProductsRecursive()
```





* Visibility: **public**
* Source: [classes/Category.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1323)




### <a name="method-inShop"></a>inShop

```php
boolean CategoryCore::inShop(\Shop $shop)
```

Check if current category is a child of shop root category



* Visibility: **public**
* Source: [classes/Category.php line 1258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1258)


#### Arguments
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-inShopStatic"></a>inShopStatic

```php
mixed CategoryCore::inShopStatic($id_category, \Shop $shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1268](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1268)


#### Arguments
* $id_category **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-isParentCategoryAvailable"></a>isParentCategoryAvailable

```php
boolean CategoryCore::isParentCategoryAvailable($id_shop)
```





* Visibility: **public**
* Source: [classes/Category.php line 1377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1377)


#### Arguments
* $id_shop **mixed**



### <a name="method-isRootCategoryForAShop"></a>isRootCategoryForAShop

```php
mixed CategoryCore::isRootCategoryForAShop()
```





* Visibility: **public**
* Source: [classes/Category.php line 1437](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1437)




### <a name="method-recalculateLevelDepth"></a>recalculateLevelDepth

```php
mixed CategoryCore::recalculateLevelDepth(integer $id_category)
```

Updates level_depth for all children of the given id_category



* Visibility: **public**
* Source: [classes/Category.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L422)


#### Arguments
* $id_category **integer** - parent category



### <a name="method-recurseCategory"></a>recurseCategory

```php
mixed CategoryCore::recurseCategory($categories, $current, $id_category, $id_selected)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L271)


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
* Source: [classes/Category.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L238)


#### Arguments
* $max_depth **integer** - Maximum depth of the tree (i.e. 2 =&gt; 3 levels depth)
* $current_depth **integer** - specify the current depth in the tree (don&#039;t use it, only for rucursivity!)
* $id_lang **integer** - Specify the id of the language used
* $excluded_ids_array **array** - specify a list of ids to exclude of results



### <a name="method-recursiveDelete"></a>recursiveDelete

```php
mixed CategoryCore::recursiveDelete($to_delete, array $id_category)
```

Recursively add specified category childs to $to_delete array



* Visibility: **protected**
* Source: [classes/Category.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L287)


#### Arguments
* $to_delete **mixed**
* $id_category **array** - Parent category ID



### <a name="method-regenerateEntireNtree"></a>regenerateEntireNtree

```php
mixed CategoryCore::regenerateEntireNtree()
```

Re-calculate the values of all branches of the nested tree



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L383)




### <a name="method-searchByName"></a>searchByName

```php
array CategoryCore::searchByName(integer $id_lang, string $query, boolean $unrestricted)
```

Light back office search for categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 913](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L913)


#### Arguments
* $id_lang **integer** - Language ID
* $query **string** - Searched string
* $unrestricted **boolean** - allows search without lang and includes first category and exact match



### <a name="method-searchByNameAndParentCategoryId"></a>searchByNameAndParentCategoryId

```php
array CategoryCore::searchByNameAndParentCategoryId(integer $id_lang, string $category_name, integer $id_parent_category)
```

Retrieve category by name and parent category id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 943](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L943)


#### Arguments
* $id_lang **integer** - Language ID
* $category_name **string** - Searched category name
* $id_parent_category **integer** - parent category ID



### <a name="method-setNewGroupForHome"></a>setNewGroupForHome

```php
mixed CategoryCore::setNewGroupForHome($id_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1114)


#### Arguments
* $id_group **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed CategoryCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Category.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L221)




### <a name="method-update"></a>update

```php
void CategoryCore::update(mixed $null_values)
```

update category positions in parent



* Visibility: **public**
* Source: [classes/Category.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L184)


#### Arguments
* $null_values **mixed**



### <a name="method-updateFromShop"></a>updateFromShop

```php
array CategoryCore::updateFromShop(string $categories, string $id_shop)
```

Update categories for a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Category.php line 1506](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1506)


#### Arguments
* $categories **string** - Categories list to associate a shop
* $id_shop **string** - Categories list to associate a shop



### <a name="method-updateGroup"></a>updateGroup

```php
mixed CategoryCore::updateGroup(array $list)
```

Update customer groups associated to the object



* Visibility: **public**
* Source: [classes/Category.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1105)


#### Arguments
* $list **array** - groups



### <a name="method-updatePosition"></a>updatePosition

```php
mixed CategoryCore::updatePosition($way, $position)
```





* Visibility: **public**
* Source: [classes/Category.php line 1124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Category.php#L1124)


#### Arguments
* $way **mixed**
* $position **mixed**


