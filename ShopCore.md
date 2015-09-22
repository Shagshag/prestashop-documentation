ShopCore
===============






* Class name: ShopCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/shop/Shop.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L30)



Constants
----------

* [CONTEXT_SHOP](#constant-CONTEXT_SHOP)
* [CONTEXT_GROUP](#constant-CONTEXT_GROUP)
* [CONTEXT_ALL](#constant-CONTEXT_ALL)
* [SHARE_CUSTOMER](#constant-SHARE_CUSTOMER)
* [SHARE_ORDER](#constant-SHARE_ORDER)
* [SHARE_STOCK](#constant-SHARE_STOCK)

Properties
----------

* [$id_shop_group](#property-$id_shop_group)
* [$id_category](#property-$id_category)
* [$id_theme](#property-$id_theme)
* [$name](#property-$name)
* [$active](#property-$active)
* [$deleted](#property-$deleted)
* [$theme_name](#property-$theme_name)
* [$theme_directory](#property-$theme_directory)
* [$physical_uri](#property-$physical_uri)
* [$virtual_uri](#property-$virtual_uri)
* [$domain](#property-$domain)
* [$domain_ssl](#property-$domain_ssl)
* [$group](#property-$group)
* [$definition](#property-$definition)
* [$shops](#property-$shops)
* [$asso_tables](#property-$asso_tables)
* [$id_shop_default_tables](#property-$id_shop_default_tables)
* [$initialized](#property-$initialized)
* [$webserviceParameters](#property-$webserviceParameters)
* [$context](#property-$context)
* [$context_id_shop](#property-$context_id_shop)
* [$context_id_shop_group](#property-$context_id_shop_group)

Methods
-------
* [__construct](#method-__construct)
* [init](#method-init)
* [setUrl](#method-setUrl)
* [add](#method-add)
* [associateSuperAdmins](#method-associateSuperAdmins)
* [delete](#method-delete)
* [hasDependency](#method-hasDependency)
* [initialize](#method-initialize)
* [getAddress](#method-getAddress)
* [getTheme](#method-getTheme)
* [getBaseURI](#method-getBaseURI)
* [getBaseURL](#method-getBaseURL)
* [getGroup](#method-getGroup)
* [getCategory](#method-getCategory)
* [getUrls](#method-getUrls)
* [isDefaultShop](#method-isDefaultShop)
* [getAssoTable](#method-getAssoTable)
* [checkIdShopDefault](#method-checkIdShopDefault)
* [getAssoTables](#method-getAssoTables)
* [addTableAssociation](#method-addTableAssociation)
* [isTableAssociated](#method-isTableAssociated)
* [cacheShops](#method-cacheShops)
* [getCompleteListOfShopsID](#method-getCompleteListOfShopsID)
* [getShops](#method-getShops)
* [getUrlsSharedCart](#method-getUrlsSharedCart)
* [getShopsCollection](#method-getShopsCollection)
* [getShop](#method-getShop)
* [getIdByName](#method-getIdByName)
* [getTotalShops](#method-getTotalShops)
* [getGroupFromShop](#method-getGroupFromShop)
* [getSharedShops](#method-getSharedShops)
* [getContextListShopID](#method-getContextListShopID)
* [getShopById](#method-getShopById)
* [setContext](#method-setContext)
* [getContext](#method-getContext)
* [getContextShopID](#method-getContextShopID)
* [getContextShopGroupID](#method-getContextShopGroupID)
* [getContextShopGroup](#method-getContextShopGroup)
* [addSqlRestriction](#method-addSqlRestriction)
* [addSqlAssociation](#method-addSqlAssociation)
* [addSqlRestrictionOnLang](#method-addSqlRestrictionOnLang)
* [getTree](#method-getTree)
* [isFeatureActive](#method-isFeatureActive)
* [copyShopData](#method-copyShopData)
* [getCategories](#method-getCategories)
* [getCurrentShop](#method-getCurrentShop)
* [getEntityIds](#method-getEntityIds)


Constants
----------


### <a name="constant-CONTEXT_SHOP"></a>CONTEXT_SHOP

    const CONTEXT_SHOP = 1



* This constant is defined in [classes/shop/Shop.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L111)


### <a name="constant-CONTEXT_GROUP"></a>CONTEXT_GROUP

    const CONTEXT_GROUP = 2



* This constant is defined in [classes/shop/Shop.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L112)


### <a name="constant-CONTEXT_ALL"></a>CONTEXT_ALL

    const CONTEXT_ALL = 4



* This constant is defined in [classes/shop/Shop.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L113)


### <a name="constant-SHARE_CUSTOMER"></a>SHARE_CUSTOMER

    const SHARE_CUSTOMER = 'share_customer'



* This constant is defined in [classes/shop/Shop.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L118)


### <a name="constant-SHARE_ORDER"></a>SHARE_ORDER

    const SHARE_ORDER = 'share_order'



* This constant is defined in [classes/shop/Shop.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L119)


### <a name="constant-SHARE_STOCK"></a>SHARE_STOCK

    const SHARE_STOCK = 'share_stock'



* This constant is defined in [classes/shop/Shop.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L120)


Properties
----------


### <a name="property-$id_shop_group"></a>$id_shop_group

    public integer $id_shop_group





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L33)


### <a name="property-$id_category"></a>$id_category

    public integer $id_category





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L36)


### <a name="property-$id_theme"></a>$id_theme

    public integer $id_theme





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L39)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L42)


### <a name="property-$active"></a>$active

    public mixed $active = true





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L44)


### <a name="property-$deleted"></a>$deleted

    public mixed $deleted





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L45)


### <a name="property-$theme_name"></a>$theme_name

    public string $theme_name





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L48)


### <a name="property-$theme_directory"></a>$theme_directory

    public string $theme_directory





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L51)


### <a name="property-$physical_uri"></a>$physical_uri

    public string $physical_uri





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L54)


### <a name="property-$virtual_uri"></a>$virtual_uri

    public string $virtual_uri





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L57)


### <a name="property-$domain"></a>$domain

    public string $domain





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L60)


### <a name="property-$domain_ssl"></a>$domain_ssl

    public string $domain_ssl





* Visibility: **public**
* This property is defined in [classes/shop/Shop.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L63)


### <a name="property-$group"></a>$group

    protected \ShopGroup $group





* Visibility: **protected**
* This property is defined in [classes/shop/Shop.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L66)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'shop', 'primary' => 'id_shop', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_theme' => array('type' => self::TYPE_INT, 'required' => true), 'id_category' => array('type' => self::TYPE_INT, 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L71)


### <a name="property-$shops"></a>$shops

    protected array $shops





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L85)


### <a name="property-$asso_tables"></a>$asso_tables

    protected mixed $asso_tables = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L87)


### <a name="property-$id_shop_default_tables"></a>$id_shop_default_tables

    protected mixed $id_shop_default_tables = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L88)


### <a name="property-$initialized"></a>$initialized

    protected mixed $initialized = false





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L89)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_shop_group' => array('xlink_resource' => 'shop_groups'), 'id_category' => array(), 'id_theme' => array()))





* Visibility: **protected**
* This property is defined in [classes/shop/Shop.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L91)


### <a name="property-$context"></a>$context

    protected integer $context





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L100)


### <a name="property-$context_id_shop"></a>$context_id_shop

    protected integer $context_id_shop





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L103)


### <a name="property-$context_id_shop_group"></a>$context_id_shop_group

    protected integer $context_id_shop_group





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/Shop.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L106)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ShopCore::__construct(integer $id, integer $id_lang, integer $id_shop)

On shop instance, get its theme and URL data too



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L129)


#### Arguments
* $id **integer**
* $id_lang **integer**
* $id_shop **integer**



### <a name="method-init"></a>init

    mixed ShopCore::init()

Initialize an array with all the multistore associations in the database



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L140)




### <a name="method-setUrl"></a>setUrl

    mixed ShopCore::setUrl()





* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L193)




### <a name="method-add"></a>add

    boolean ShopCore::add(boolean $autodate, boolean $null_values)

Add a shop, and clear the cache



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L230)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-associateSuperAdmins"></a>associateSuperAdmins

    mixed ShopCore::associateSuperAdmins()





* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L237)




### <a name="method-delete"></a>delete

    boolean ShopCore::delete()

Remove a shop only if it has no dependencies, and remove its associations



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L251)




### <a name="method-hasDependency"></a>hasDependency

    boolean ShopCore::hasDependency(integer $id_shop)

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L287)


#### Arguments
* $id_shop **integer**



### <a name="method-initialize"></a>initialize

    \Shop ShopCore::initialize()

Find the shop from current domain / uri and get an instance of this shop
if INSTALL_VERSION is defined, will return an empty shop object



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L317)




### <a name="method-getAddress"></a>getAddress

    \Address ShopCore::getAddress()





* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L448)




### <a name="method-getTheme"></a>getTheme

    string ShopCore::getTheme()

Get shop theme name



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 471](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L471)




### <a name="method-getBaseURI"></a>getBaseURI

    string ShopCore::getBaseURI()

Get shop URI



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L481)




### <a name="method-getBaseURL"></a>getBaseURL

    string ShopCore::getBaseURL(string $auto_secure_mode, string $add_base_uri)

Get shop URL



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L493)


#### Arguments
* $auto_secure_mode **string** - &lt;p&gt;if set to true, secure mode will be checked&lt;/p&gt;
* $add_base_uri **string** - &lt;p&gt;if set to true, shop base uri will be added&lt;/p&gt;



### <a name="method-getGroup"></a>getGroup

    \ShopGroup ShopCore::getGroup()

Get group of current shop



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 515](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L515)




### <a name="method-getCategory"></a>getCategory

    integer ShopCore::getCategory()

Get root category of current shop



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L528)




### <a name="method-getUrls"></a>getUrls

    array ShopCore::getUrls()

Get list of shop's urls



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L538)




### <a name="method-isDefaultShop"></a>isDefaultShop

    boolean ShopCore::isDefaultShop()

Check if current shop ID is the same as default shop in configuration



* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L552)




### <a name="method-getAssoTable"></a>getAssoTable

    array ShopCore::getAssoTable($table)

Get the associated table if available



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L562)


#### Arguments
* $table **mixed**



### <a name="method-checkIdShopDefault"></a>checkIdShopDefault

    boolean ShopCore::checkIdShopDefault($table)

check if the table has an id_shop_default



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L575)


#### Arguments
* $table **mixed**



### <a name="method-getAssoTables"></a>getAssoTables

    array ShopCore::getAssoTables()

Get list of associated tables to shop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L588)




### <a name="method-addTableAssociation"></a>addTableAssociation

    boolean ShopCore::addTableAssociation(string $table_name, array $table_details)

Add table associated to shop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L603)


#### Arguments
* $table_name **string**
* $table_details **array**



### <a name="method-isTableAssociated"></a>isTableAssociated

    boolean ShopCore::isTableAssociated(string $table)

Check if given table is associated to shop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L619)


#### Arguments
* $table **string**



### <a name="method-cacheShops"></a>cacheShops

    mixed ShopCore::cacheShops(boolean $refresh)

Load list of groups and shops, and cache it



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 632](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L632)


#### Arguments
* $refresh **boolean**



### <a name="method-getCompleteListOfShopsID"></a>getCompleteListOfShopsID

    mixed ShopCore::getCompleteListOfShopsID()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L691)




### <a name="method-getShops"></a>getShops

    array ShopCore::getShops(boolean $active, integer $id_shop_group, boolean $get_as_list_id)

Get shops list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 715](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L715)


#### Arguments
* $active **boolean**
* $id_shop_group **integer**
* $get_as_list_id **boolean**



### <a name="method-getUrlsSharedCart"></a>getUrlsSharedCart

    mixed ShopCore::getUrlsSharedCart()





* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L735)




### <a name="method-getShopsCollection"></a>getShopsCollection

    \PrestaShopCollection ShopCore::getShopsCollection(boolean $active, integer $id_shop_group)

Get a collection of shops



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 762](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L762)


#### Arguments
* $active **boolean**
* $id_shop_group **integer**



### <a name="method-getShop"></a>getShop

    array ShopCore::getShop(integer $shop_id)

Return some informations cached for one shop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 782](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L782)


#### Arguments
* $shop_id **integer**



### <a name="method-getIdByName"></a>getIdByName

    integer ShopCore::getIdByName(string $name)

Return a shop ID from shop name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L799)


#### Arguments
* $name **string**



### <a name="method-getTotalShops"></a>getTotalShops

    integer ShopCore::getTotalShops(boolean $active, integer $id_shop_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 817](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L817)


#### Arguments
* $active **boolean**
* $id_shop_group **integer**



### <a name="method-getGroupFromShop"></a>getGroupFromShop

    integer ShopCore::getGroupFromShop(integer $shop_id, $as_id)

Retrieve group ID of a shop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 828](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L828)


#### Arguments
* $shop_id **integer** - &lt;p&gt;Shop ID&lt;/p&gt;
* $as_id **mixed**



### <a name="method-getSharedShops"></a>getSharedShops

    array ShopCore::getSharedShops(integer $shop_id, integer $type)

If the shop group has the option $type activated, get all shops ID of this group, else get current shop ID



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 846](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L846)


#### Arguments
* $shop_id **integer**
* $type **integer** - &lt;p&gt;Shop::SHARE_CUSTOMER | Shop::SHARE_ORDER&lt;/p&gt;



### <a name="method-getContextListShopID"></a>getContextListShopID

    array ShopCore::getContextListShopID(string $share)

Get a list of ID concerned by the shop context (E.g. if context is shop group, get list of children shop ID)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 867](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L867)


#### Arguments
* $share **string** - &lt;p&gt;If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value&lt;/p&gt;



### <a name="method-getShopById"></a>getShopById

    array ShopCore::getShopById(integer $id, string $identifier, string $table)

Return the list of shop by id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L888)


#### Arguments
* $id **integer**
* $identifier **string**
* $table **string**



### <a name="method-setContext"></a>setContext

    mixed ShopCore::setContext(integer $type, integer $id)

Change the current shop context



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 903](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L903)


#### Arguments
* $type **integer** - &lt;p&gt;Shop::CONTEXT_ALL | Shop::CONTEXT_GROUP | Shop::CONTEXT_SHOP&lt;/p&gt;
* $id **integer** - &lt;p&gt;ID shop if CONTEXT_SHOP or id shop group if CONTEXT_GROUP&lt;/p&gt;



### <a name="method-getContext"></a>getContext

    integer ShopCore::getContext()

Get current context of shop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L933)




### <a name="method-getContextShopID"></a>getContextShopID

    integer ShopCore::getContextShopID($null_value_without_multishop)

Get current ID of shop if context is CONTEXT_SHOP



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 943](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L943)


#### Arguments
* $null_value_without_multishop **mixed**



### <a name="method-getContextShopGroupID"></a>getContextShopGroupID

    integer ShopCore::getContextShopGroupID($null_value_without_multishop)

Get current ID of shop group if context is CONTEXT_SHOP or CONTEXT_GROUP



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 956](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L956)


#### Arguments
* $null_value_without_multishop **mixed**



### <a name="method-getContextShopGroup"></a>getContextShopGroup

    mixed ShopCore::getContextShopGroup()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 965](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L965)




### <a name="method-addSqlRestriction"></a>addSqlRestriction

    mixed ShopCore::addSqlRestriction(integer $share, string $alias)

Add an sql restriction for shops fields



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 980](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L980)


#### Arguments
* $share **integer** - &lt;p&gt;If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value&lt;/p&gt;
* $alias **string**



### <a name="method-addSqlAssociation"></a>addSqlAssociation

    string ShopCore::addSqlAssociation(string $table, string $alias, boolean $inner_join, string $on, $force_not_default)

Add an SQL JOIN in query between a table and its associated table in multishop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 1005](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1005)


#### Arguments
* $table **string** - &lt;p&gt;Table name (E.g. product, module, etc.)&lt;/p&gt;
* $alias **string** - &lt;p&gt;Alias of table&lt;/p&gt;
* $inner_join **boolean** - &lt;p&gt;Use or not INNER JOIN&lt;/p&gt;
* $on **string**
* $force_not_default **mixed**



### <a name="method-addSqlRestrictionOnLang"></a>addSqlRestrictionOnLang

    string ShopCore::addSqlRestrictionOnLang(string $alias, $id_shop)

Add a restriction on id_shop for multishop lang table



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 1036](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1036)


#### Arguments
* $alias **string**
* $id_shop **mixed**



### <a name="method-getTree"></a>getTree

    array ShopCore::getTree()

Get all groups and associated shops as subarrays



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 1053](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1053)




### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean ShopCore::isFeatureActive()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 1062](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1062)




### <a name="method-copyShopData"></a>copyShopData

    mixed ShopCore::copyShopData($old_id, $tables_import, $deleted)





* Visibility: **public**
* This method is defined in [classes/shop/Shop.php line 1074](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1074)


#### Arguments
* $old_id **mixed**
* $tables_import **mixed**
* $deleted **mixed**



### <a name="method-getCategories"></a>getCategories

    array ShopCore::getCategories(integer $id, $only_id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 1178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1178)


#### Arguments
* $id **integer**
* $only_id **mixed**



### <a name="method-getCurrentShop"></a>getCurrentShop

    mixed ShopCore::getCurrentShop()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 1208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1208)




### <a name="method-getEntityIds"></a>getEntityIds

    array|boolean ShopCore::getEntityIds(string $entity, integer $id_shop, $active, $delete)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/Shop.php line 1219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/Shop.php#L1219)


#### Arguments
* $entity **string**
* $id_shop **integer**
* $active **mixed**
* $delete **mixed**


