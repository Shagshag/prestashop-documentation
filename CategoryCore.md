CategoryCore
===============






* Class name: CategoryCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Category.php line 27





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in classes\Category.php line 29


### $id_category

    public integer $id_category





* Visibility: **public**
* This property is defined in classes\Category.php line 32


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\Category.php line 35


### $active

    public boolean $active = 1





* Visibility: **public**
* This property is defined in classes\Category.php line 38


### $position

    public integer $position





* Visibility: **public**
* This property is defined in classes\Category.php line 41


### $description

    public string $description





* Visibility: **public**
* This property is defined in classes\Category.php line 44


### $id_parent

    public integer $id_parent





* Visibility: **public**
* This property is defined in classes\Category.php line 47


### $id_category_default

    public integer $id_category_default





* Visibility: **public**
* This property is defined in classes\Category.php line 50


### $level_depth

    public integer $level_depth





* Visibility: **public**
* This property is defined in classes\Category.php line 53


### $nleft

    public integer $nleft





* Visibility: **public**
* This property is defined in classes\Category.php line 56


### $nright

    public integer $nright





* Visibility: **public**
* This property is defined in classes\Category.php line 59


### $link_rewrite

    public string $link_rewrite





* Visibility: **public**
* This property is defined in classes\Category.php line 62


### $meta_title

    public string $meta_title





* Visibility: **public**
* This property is defined in classes\Category.php line 65


### $meta_keywords

    public string $meta_keywords





* Visibility: **public**
* This property is defined in classes\Category.php line 68


### $meta_description

    public string $meta_description





* Visibility: **public**
* This property is defined in classes\Category.php line 71


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in classes\Category.php line 74


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in classes\Category.php line 77


### $is_root_category

    public boolean $is_root_category





* Visibility: **public**
* This property is defined in classes\Category.php line 80


### $id_shop_default

    public integer $id_shop_default





* Visibility: **public**
* This property is defined in classes\Category.php line 83


### $groupBox

    public mixed $groupBox





* Visibility: **public**
* This property is defined in classes\Category.php line 85


### $_links

    protected mixed $_links = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Category.php line 87


### $definition

    public mixed $definition = array('table' => 'category', 'primary' => 'id_category', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('nleft' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'nright' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'level_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'is_root_category' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'position' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Category.php line 92


### $id_image

    public string $id_image = 'default'





* Visibility: **public**
* This property is defined in classes\Category.php line 119


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'categories', 'hidden_fields' => array('nleft', 'nright', 'groupBox'), 'fields' => array('id_parent' => array('xlink_resource' => 'categories'), 'level_depth' => array('setter' => false), 'nb_products_recursive' => array('getter' => 'getWsNbProductsRecursive', 'setter' => false)), 'associations' => array('categories' => array('getter' => 'getChildrenWs', 'resource' => 'category'), 'products' => array('getter' => 'getProductsWs', 'resource' => 'product')))





* Visibility: **protected**
* This property is defined in classes\Category.php line 121


Methods
-------


### __construct

    mixed CategoryCore::__construct($id_category, $id_lang, $id_shop)





* Visibility: **public**
* This method is defined in classes\Category.php line 135


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### getDescriptionClean

    mixed CategoryCore::getDescriptionClean($description)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 142


#### Arguments
* $description **mixed**



### add

    mixed CategoryCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\Category.php line 147


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    boolean CategoryCore::update(mixed $null_values)

update category positions in parent



* Visibility: **public**
* This method is defined in classes\Category.php line 183


#### Arguments
* $null_values **mixed**



### toggleStatus

    mixed CategoryCore::toggleStatus()





* Visibility: **public**
* This method is defined in classes\Category.php line 232




### recurseLiteCategTree

    array CategoryCore::recurseLiteCategTree(integer $max_depth, integer $current_depth, integer $id_lang, array $excluded_ids_array)

Recursive scan of subcategories



* Visibility: **public**
* This method is defined in classes\Category.php line 249


#### Arguments
* $max_depth **integer** - &lt;p&gt;Maximum depth of the tree (i.e. 2 =&gt; 3 levels depth)&lt;/p&gt;
* $current_depth **integer** - &lt;p&gt;specify the current depth in the tree (don&#039;t use it, only for rucursivity!)&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Specify the id of the language used&lt;/p&gt;
* $excluded_ids_array **array** - &lt;p&gt;specify a list of ids to exclude of results&lt;/p&gt;



### recurseCategory

    mixed CategoryCore::recurseCategory($categories, $current, $id_category, $id_selected)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 283


#### Arguments
* $categories **mixed**
* $current **mixed**
* $id_category **mixed**
* $id_selected **mixed**



### recursiveDelete

    mixed CategoryCore::recursiveDelete($to_delete, integer $id_category)

Recursively add specified category childs to $to_delete array



* Visibility: **protected**
* This method is defined in classes\Category.php line 305


#### Arguments
* $to_delete **mixed**
* $id_category **integer** - &lt;p&gt;Parent category ID&lt;/p&gt;



### deleteLite

    mixed CategoryCore::deleteLite()





* Visibility: **public**
* This method is defined in classes\Category.php line 321




### delete

    mixed CategoryCore::delete()





* Visibility: **public**
* This method is defined in classes\Category.php line 327




### deleteSelection

    mixed CategoryCore::deleteSelection($categories)

Delete several categories from database

return boolean Deletion result

* Visibility: **public**
* This method is defined in classes\Category.php line 369


#### Arguments
* $categories **mixed**



### calcLevelDepth

    integer CategoryCore::calcLevelDepth()

Get the depth level for the category



* Visibility: **public**
* This method is defined in classes\Category.php line 388




### regenerateEntireNtree

    mixed CategoryCore::regenerateEntireNtree()

Re-calculate the values of all branches of the nested tree



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 405




### _subTree

    mixed CategoryCore::_subTree($categories, $id_category, $n)





* Visibility: **protected**
* This method is **static**.
* This method is defined in classes\Category.php line 426


#### Arguments
* $categories **mixed**
* $id_category **mixed**
* $n **mixed**



### recalculateLevelDepth

    mixed CategoryCore::recalculateLevelDepth(integer $id_category)

Updates level_depth for all children of the given id_category



* Visibility: **public**
* This method is defined in classes\Category.php line 447


#### Arguments
* $id_category **integer** - &lt;p&gt;parent category&lt;/p&gt;



### getCategories

    array CategoryCore::getCategories(integer $id_lang, boolean $active, $order, $sql_filter, $sql_sort, $sql_limit)

Return available categories



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 480


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active categories&lt;/p&gt;
* $order **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### getAllCategoriesName

    mixed CategoryCore::getAllCategoriesName($root_category, $id_lang, $active, $groups, $use_shop_restriction, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 509


#### Arguments
* $root_category **mixed**
* $id_lang **mixed**
* $active **mixed**
* $groups **mixed**
* $use_shop_restriction **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### getNestedCategories

    mixed CategoryCore::getNestedCategories($root_category, $id_lang, $active, $groups, $use_shop_restriction, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 552


#### Arguments
* $root_category **mixed**
* $id_lang **mixed**
* $active **mixed**
* $groups **mixed**
* $use_shop_restriction **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### getSimpleCategories

    mixed CategoryCore::getSimpleCategories($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 613


#### Arguments
* $id_lang **mixed**



### getShopID

    mixed CategoryCore::getShopID()





* Visibility: **public**
* This method is defined in classes\Category.php line 626




### getSubCategories

    array CategoryCore::getSubCategories(integer $id_lang, boolean $active)

Return current category childs



* Visibility: **public**
* This method is defined in classes\Category.php line 638


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active categories&lt;/p&gt;



### getProducts

    array|integer|false CategoryCore::getProducts(integer $id_lang, integer $p, integer $n, string|null $order_by, string|null $order_way, boolean $get_total, boolean $active, boolean $random, integer $random_number_products, boolean $check_access, \Context|null $context)

Returns category products



* Visibility: **public**
* This method is defined in classes\Category.php line 686


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $p **integer** - &lt;p&gt;Page number&lt;/p&gt;
* $n **integer** - &lt;p&gt;Number of products per page&lt;/p&gt;
* $order_by **string|null** - &lt;p&gt;ORDER BY column&lt;/p&gt;
* $order_way **string|null** - &lt;p&gt;Order way&lt;/p&gt;
* $get_total **boolean** - &lt;p&gt;If set to true, returns the total number of results only&lt;/p&gt;
* $active **boolean** - &lt;p&gt;If set to true, finds only active products&lt;/p&gt;
* $random **boolean** - &lt;p&gt;If true, sets a random filter for returned products&lt;/p&gt;
* $random_number_products **integer** - &lt;p&gt;Number of products to return if random is activated&lt;/p&gt;
* $check_access **boolean** - &lt;p&gt;If set tot rue, check if the current customer
                                           can see products from this category&lt;/p&gt;
* $context **[Context](ContextCore)|null**



### getHomeCategories

    array CategoryCore::getHomeCategories(integer $id_lang, boolean $active, $id_shop)

Return main categories



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 803


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $active **boolean** - &lt;p&gt;return only active categories&lt;/p&gt;
* $id_shop **mixed**



### getRootCategory

    mixed CategoryCore::getRootCategory($id_lang, \Shop $shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 808


#### Arguments
* $id_lang **mixed**
* $shop **[Shop](ShopCore)**



### getChildren

    array CategoryCore::getChildren(integer $id_parent, integer $id_lang, boolean $active, boolean $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 841


#### Arguments
* $id_parent **integer**
* $id_lang **integer**
* $active **boolean**
* $id_shop **boolean**



### hasChildren

    array CategoryCore::hasChildren(integer $id_parent, integer $id_lang, boolean $active, boolean $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 873


#### Arguments
* $id_parent **integer**
* $id_lang **integer**
* $active **boolean**
* $id_shop **boolean**



### getAllChildren

    \PrestaShopCollection CategoryCore::getAllChildren(integer $id_lang)

Return an array of all children of the current category



* Visibility: **public**
* This method is defined in classes\Category.php line 901


#### Arguments
* $id_lang **integer**



### getAllParents

    \PrestaShopCollection CategoryCore::getAllParents(integer $id_lang)

Return an array of all parents of the current category



* Visibility: **public**
* This method is defined in classes\Category.php line 919


#### Arguments
* $id_lang **integer**



### getChildrenWithNbSelectedSubCat

    array CategoryCore::getChildrenWithNbSelectedSubCat(integer $id_parent, $selected_cat, integer $id_lang, \Shop $shop, $use_shop_context)

This method allow to return children categories with the number of sub children selected for a product



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 939


#### Arguments
* $id_parent **integer**
* $selected_cat **mixed**
* $id_lang **integer**
* $shop **[Shop](ShopCore)**
* $use_shop_context **mixed**



### duplicateProductCategories

    boolean CategoryCore::duplicateProductCategories(integer $id_old, boolean $id_new)

Copy products from a category to another



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 983


#### Arguments
* $id_old **integer** - &lt;p&gt;Source category ID&lt;/p&gt;
* $id_new **boolean** - &lt;p&gt;Destination category ID&lt;/p&gt;



### checkBeforeMove

    boolean CategoryCore::checkBeforeMove(integer $id_category, integer $id_parent)

Check if category can be moved in another one.

The category cannot be moved in a child category.

* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1016


#### Arguments
* $id_category **integer** - &lt;p&gt;current category&lt;/p&gt;
* $id_parent **integer** - &lt;p&gt;Parent candidate&lt;/p&gt;



### getLinkRewrite

    mixed CategoryCore::getLinkRewrite($id_category, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1041


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**



### getLink

    mixed CategoryCore::getLink(\Link $link, $id_lang)





* Visibility: **public**
* This method is defined in classes\Category.php line 1058


#### Arguments
* $link **[Link](LinkCore)**
* $id_lang **mixed**



### getName

    mixed CategoryCore::getName($id_lang)





* Visibility: **public**
* This method is defined in classes\Category.php line 1072


#### Arguments
* $id_lang **mixed**



### searchByName

    array CategoryCore::searchByName(integer $id_lang, string $query, boolean $unrestricted, boolean $skip_cache)

Light back office search for categories



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1094


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $query **string** - &lt;p&gt;Searched string&lt;/p&gt;
* $unrestricted **boolean** - &lt;p&gt;allows search without lang and includes first category and exact match&lt;/p&gt;
* $skip_cache **boolean**



### searchByNameAndParentCategoryId

    array CategoryCore::searchByNameAndParentCategoryId(integer $id_lang, string $category_name, integer $id_parent_category)

Retrieve category by name and parent category id



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1128


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $category_name **string** - &lt;p&gt;Searched category name&lt;/p&gt;
* $id_parent_category **integer** - &lt;p&gt;parent category ID&lt;/p&gt;



### searchByPath

    array CategoryCore::searchByPath(integer $id_lang, string $path, boolean $object_to_create, $method_to_create)

Search with Pathes for categories



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1150


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $path **string** - &lt;p&gt;of category&lt;/p&gt;
* $object_to_create **boolean** - &lt;p&gt;a category&lt;/p&gt;
&lt;pre&gt;&lt;code&gt; * @param bool $method_to_create a category&lt;/code&gt;&lt;/pre&gt;
* $method_to_create **mixed**



### getParentsCategories

    array CategoryCore::getParentsCategories(integer $id_lang)

Get Each parent category of this category until the root category



* Visibility: **public**
* This method is defined in classes\Category.php line 1181


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### categoryExists

    boolean CategoryCore::categoryExists(integer $id_category)

Specify if a category already in base



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1237


#### Arguments
* $id_category **integer** - &lt;p&gt;Category id&lt;/p&gt;



### cleanGroups

    mixed CategoryCore::cleanGroups()





* Visibility: **public**
* This method is defined in classes\Category.php line 1247




### cleanAssoProducts

    mixed CategoryCore::cleanAssoProducts()





* Visibility: **public**
* This method is defined in classes\Category.php line 1252




### addGroups

    mixed CategoryCore::addGroups($groups)





* Visibility: **public**
* This method is defined in classes\Category.php line 1257


#### Arguments
* $groups **mixed**



### getGroups

    mixed CategoryCore::getGroups()





* Visibility: **public**
* This method is defined in classes\Category.php line 1266




### addGroupsIfNoExist

    mixed CategoryCore::addGroupsIfNoExist($id_group)





* Visibility: **public**
* This method is defined in classes\Category.php line 1284


#### Arguments
* $id_group **mixed**



### checkAccess

    boolean CategoryCore::checkAccess(mixed $id_customer)

checkAccess return true if id_customer is in a group allowed to see this category.



* Visibility: **public**
* This method is defined in classes\Category.php line 1300


#### Arguments
* $id_customer **mixed**



### updateGroup

    mixed CategoryCore::updateGroup(array $list)

Update customer groups associated to the object



* Visibility: **public**
* This method is defined in classes\Category.php line 1327


#### Arguments
* $list **array** - &lt;p&gt;groups&lt;/p&gt;



### setNewGroupForHome

    mixed CategoryCore::setNewGroupForHome($id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1336


#### Arguments
* $id_group **mixed**



### updatePosition

    mixed CategoryCore::updatePosition($way, $position)





* Visibility: **public**
* This method is defined in classes\Category.php line 1347


#### Arguments
* $way **mixed**
* $position **mixed**



### cleanPositions

    boolean CategoryCore::cleanPositions(mixed $id_category_parent)

cleanPositions keep order of category in $id_category_parent,
but remove duplicate position. Should not be used if positions
are clean at the beginning !



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1396


#### Arguments
* $id_category_parent **mixed**



### getLastPosition

    integer CategoryCore::getLastPosition(integer $id_category_parent, integer $id_shop)

this function return the number of category + 1 having $id_category_parent as parent.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1426


#### Arguments
* $id_category_parent **integer** - &lt;p&gt;the parent category&lt;/p&gt;
* $id_shop **integer**



### getUrlRewriteInformations

    mixed CategoryCore::getUrlRewriteInformations($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1443


#### Arguments
* $id_category **mixed**



### getInterval

    array CategoryCore::getInterval(integer $id)

Return nleft and nright fields for a given category



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1461


#### Arguments
* $id **integer**



### inShop

    boolean CategoryCore::inShop(\Shop $shop)

Check if current category is a child of shop root category



* Visibility: **public**
* This method is defined in classes\Category.php line 1482


#### Arguments
* $shop **[Shop](ShopCore)**



### inShopStatic

    mixed CategoryCore::inShopStatic($id_category, \Shop $shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1494


#### Arguments
* $id_category **mixed**
* $shop **[Shop](ShopCore)**



### getChildrenWs

    mixed CategoryCore::getChildrenWs()





* Visibility: **public**
* This method is defined in classes\Category.php line 1507




### getProductsWs

    mixed CategoryCore::getProductsWs()





* Visibility: **public**
* This method is defined in classes\Category.php line 1519




### getDuplicatePosition

    array CategoryCore::getDuplicatePosition()

Search for another category with the same parent and the same position



* Visibility: **public**
* This method is defined in classes\Category.php line 1534




### getWsNbProductsRecursive

    mixed CategoryCore::getWsNbProductsRecursive()





* Visibility: **public**
* This method is defined in classes\Category.php line 1545




### getCategoryInformations

    Array CategoryCore::getCategoryInformations(Array $ids_category, integer $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1573


#### Arguments
* $ids_category **Array**
* $id_lang **integer**



### isParentCategoryAvailable

    boolean CategoryCore::isParentCategoryAvailable($id_shop)





* Visibility: **public**
* This method is defined in classes\Category.php line 1603


#### Arguments
* $id_shop **mixed**



### addShop

    boolean CategoryCore::addShop(integer $id_shop)

Add association between shop and categories



* Visibility: **public**
* This method is defined in classes\Category.php line 1620


#### Arguments
* $id_shop **integer**



### getRootCategories

    mixed CategoryCore::getRootCategories($id_lang, $active)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1642


#### Arguments
* $id_lang **mixed**
* $active **mixed**



### getCategoriesWithoutParent

    mixed CategoryCore::getCategoriesWithoutParent()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1656




### isRootCategoryForAShop

    mixed CategoryCore::isRootCategoryForAShop()





* Visibility: **public**
* This method is defined in classes\Category.php line 1671




### getTopCategory

    \Category CategoryCore::getTopCategory(null $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1683


#### Arguments
* $id_lang **null**



### addPosition

    mixed CategoryCore::addPosition($position, $id_shop)





* Visibility: **public**
* This method is defined in classes\Category.php line 1701


#### Arguments
* $position **mixed**
* $id_shop **mixed**



### getShopsByCategory

    mixed CategoryCore::getShopsByCategory($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1730


#### Arguments
* $id_category **mixed**



### updateFromShop

    array CategoryCore::updateFromShop(string $categories, string $id_shop)

Update categories for a shop



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1745


#### Arguments
* $categories **string** - &lt;p&gt;Categories list to associate a shop&lt;/p&gt;
* $id_shop **string** - &lt;p&gt;Categories list to associate a shop&lt;/p&gt;



### deleteFromShop

    boolean CategoryCore::deleteFromShop(integer $id_shop)

Delete category from shop $id_shop



* Visibility: **public**
* This method is defined in classes\Category.php line 1765


#### Arguments
* $id_shop **integer**



### deleteCategoriesFromShop

    boolean CategoryCore::deleteCategoriesFromShop($id_shop)

Delete every categories



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1777


#### Arguments
* $id_shop **mixed**



### addToShop

    boolean CategoryCore::addToShop(array $categories, $id_shop)

Add some categories to a shop



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Category.php line 1787


#### Arguments
* $categories **array**
* $id_shop **mixed**



### existsInShop

    mixed CategoryCore::existsInShop($id_shop)





* Visibility: **public**
* This method is defined in classes\Category.php line 1811


#### Arguments
* $id_shop **mixed**


