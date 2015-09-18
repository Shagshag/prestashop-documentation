ShopCore
===============






* Class name: ShopCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### CONTEXT_SHOP

    const CONTEXT_SHOP = 1





### CONTEXT_GROUP

    const CONTEXT_GROUP = 2





### CONTEXT_ALL

    const CONTEXT_ALL = 4





### SHARE_CUSTOMER

    const SHARE_CUSTOMER = 'share_customer'





### SHARE_ORDER

    const SHARE_ORDER = 'share_order'





### SHARE_STOCK

    const SHARE_STOCK = 'share_stock'





Properties
----------


### $id_shop_group

    public integer $id_shop_group





* Visibility: **public**


### $id_category

    public integer $id_category





* Visibility: **public**


### $id_theme

    public integer $id_theme





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $active

    public mixed $active = true





* Visibility: **public**


### $deleted

    public mixed $deleted





* Visibility: **public**


### $theme_name

    public string $theme_name





* Visibility: **public**


### $theme_directory

    public string $theme_directory





* Visibility: **public**


### $physical_uri

    public string $physical_uri





* Visibility: **public**


### $virtual_uri

    public string $virtual_uri





* Visibility: **public**


### $domain

    public string $domain





* Visibility: **public**


### $domain_ssl

    public string $domain_ssl





* Visibility: **public**


### $group

    protected \ShopGroup $group





* Visibility: **protected**


### $definition

    public mixed $definition = array('table' => 'shop', 'primary' => 'id_shop', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_theme' => array('type' => self::TYPE_INT, 'required' => true), 'id_category' => array('type' => self::TYPE_INT, 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $shops

    protected array $shops





* Visibility: **protected**
* This property is **static**.


### $asso_tables

    protected mixed $asso_tables = array()





* Visibility: **protected**
* This property is **static**.


### $id_shop_default_tables

    protected mixed $id_shop_default_tables = array()





* Visibility: **protected**
* This property is **static**.


### $initialized

    protected mixed $initialized = false





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_shop_group' => array('xlink_resource' => 'shop_groups'), 'id_category' => array(), 'id_theme' => array()))





* Visibility: **protected**


### $context

    protected integer $context





* Visibility: **protected**
* This property is **static**.


### $context_id_shop

    protected integer $context_id_shop





* Visibility: **protected**
* This property is **static**.


### $context_id_shop_group

    protected integer $context_id_shop_group





* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed ShopCore::__construct(integer $id, integer $id_lang, integer $id_shop)

On shop instance, get its theme and URL data too



* Visibility: **public**


#### Arguments
* $id **integer**
* $id_lang **integer**
* $id_shop **integer**



### init

    mixed ShopCore::init()

Initialize an array with all the multistore associations in the database



* Visibility: **protected**
* This method is **static**.




### setUrl

    mixed ShopCore::setUrl()





* Visibility: **public**




### add

    boolean ShopCore::add(boolean $autodate, boolean $null_values)

Add a shop, and clear the cache



* Visibility: **public**


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### associateSuperAdmins

    mixed ShopCore::associateSuperAdmins()





* Visibility: **public**




### delete

    boolean ShopCore::delete()

Remove a shop only if it has no dependencies, and remove its associations



* Visibility: **public**




### hasDependency

    boolean ShopCore::hasDependency(integer $id_shop)

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **integer**



### initialize

    \Shop ShopCore::initialize()

Find the shop from current domain / uri and get an instance of this shop
if INSTALL_VERSION is defined, will return an empty shop object



* Visibility: **public**
* This method is **static**.




### getAddress

    \Address ShopCore::getAddress()





* Visibility: **public**




### getTheme

    string ShopCore::getTheme()

Get shop theme name



* Visibility: **public**




### getBaseURI

    string ShopCore::getBaseURI()

Get shop URI



* Visibility: **public**




### getBaseURL

    string ShopCore::getBaseURL(string $auto_secure_mode, string $add_base_uri)

Get shop URL



* Visibility: **public**


#### Arguments
* $auto_secure_mode **string** - &lt;p&gt;if set to true, secure mode will be checked&lt;/p&gt;
* $add_base_uri **string** - &lt;p&gt;if set to true, shop base uri will be added&lt;/p&gt;



### getGroup

    \ShopGroup ShopCore::getGroup()

Get group of current shop



* Visibility: **public**




### getCategory

    integer ShopCore::getCategory()

Get root category of current shop



* Visibility: **public**




### getUrls

    array ShopCore::getUrls()

Get list of shop's urls



* Visibility: **public**




### isDefaultShop

    boolean ShopCore::isDefaultShop()

Check if current shop ID is the same as default shop in configuration



* Visibility: **public**




### getAssoTable

    array ShopCore::getAssoTable($table)

Get the associated table if available



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **mixed**



### checkIdShopDefault

    boolean ShopCore::checkIdShopDefault($table)

check if the table has an id_shop_default



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **mixed**



### getAssoTables

    array ShopCore::getAssoTables()

Get list of associated tables to shop



* Visibility: **public**
* This method is **static**.




### addTableAssociation

    boolean ShopCore::addTableAssociation(string $table_name, array $table_details)

Add table associated to shop



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table_name **string**
* $table_details **array**



### isTableAssociated

    boolean ShopCore::isTableAssociated(string $table)

Check if given table is associated to shop



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **string**



### cacheShops

    mixed ShopCore::cacheShops(boolean $refresh)

Load list of groups and shops, and cache it



* Visibility: **public**
* This method is **static**.


#### Arguments
* $refresh **boolean**



### getCompleteListOfShopsID

    mixed ShopCore::getCompleteListOfShopsID()





* Visibility: **public**
* This method is **static**.




### getShops

    array ShopCore::getShops(boolean $active, integer $id_shop_group, boolean $get_as_list_id)

Get shops list



* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **boolean**
* $id_shop_group **integer**
* $get_as_list_id **boolean**



### getUrlsSharedCart

    mixed ShopCore::getUrlsSharedCart()





* Visibility: **public**




### getShopsCollection

    \PrestaShopCollection ShopCore::getShopsCollection(boolean $active, integer $id_shop_group)

Get a collection of shops



* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **boolean**
* $id_shop_group **integer**



### getShop

    array ShopCore::getShop(integer $shop_id)

Return some informations cached for one shop



* Visibility: **public**
* This method is **static**.


#### Arguments
* $shop_id **integer**



### getIdByName

    integer ShopCore::getIdByName(string $name)

Return a shop ID from shop name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string**



### getTotalShops

    integer ShopCore::getTotalShops(boolean $active, integer $id_shop_group)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **boolean**
* $id_shop_group **integer**



### getGroupFromShop

    integer ShopCore::getGroupFromShop(integer $shop_id, $as_id)

Retrieve group ID of a shop



* Visibility: **public**
* This method is **static**.


#### Arguments
* $shop_id **integer** - &lt;p&gt;Shop ID&lt;/p&gt;
* $as_id **mixed**



### getSharedShops

    array ShopCore::getSharedShops(integer $shop_id, integer $type)

If the shop group has the option $type activated, get all shops ID of this group, else get current shop ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $shop_id **integer**
* $type **integer** - &lt;p&gt;Shop::SHARE_CUSTOMER | Shop::SHARE_ORDER&lt;/p&gt;



### getContextListShopID

    array ShopCore::getContextListShopID(string $share)

Get a list of ID concerned by the shop context (E.g. if context is shop group, get list of children shop ID)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $share **string** - &lt;p&gt;If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value&lt;/p&gt;



### getShopById

    array ShopCore::getShopById(integer $id, string $identifier, string $table)

Return the list of shop by id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **integer**
* $identifier **string**
* $table **string**



### setContext

    mixed ShopCore::setContext(integer $type, integer $id)

Change the current shop context



* Visibility: **public**
* This method is **static**.


#### Arguments
* $type **integer** - &lt;p&gt;Shop::CONTEXT_ALL | Shop::CONTEXT_GROUP | Shop::CONTEXT_SHOP&lt;/p&gt;
* $id **integer** - &lt;p&gt;ID shop if CONTEXT_SHOP or id shop group if CONTEXT_GROUP&lt;/p&gt;



### getContext

    integer ShopCore::getContext()

Get current context of shop



* Visibility: **public**
* This method is **static**.




### getContextShopID

    integer ShopCore::getContextShopID($null_value_without_multishop)

Get current ID of shop if context is CONTEXT_SHOP



* Visibility: **public**
* This method is **static**.


#### Arguments
* $null_value_without_multishop **mixed**



### getContextShopGroupID

    integer ShopCore::getContextShopGroupID($null_value_without_multishop)

Get current ID of shop group if context is CONTEXT_SHOP or CONTEXT_GROUP



* Visibility: **public**
* This method is **static**.


#### Arguments
* $null_value_without_multishop **mixed**



### getContextShopGroup

    mixed ShopCore::getContextShopGroup()





* Visibility: **public**
* This method is **static**.




### addSqlRestriction

    mixed ShopCore::addSqlRestriction(integer $share, string $alias)

Add an sql restriction for shops fields



* Visibility: **public**
* This method is **static**.


#### Arguments
* $share **integer** - &lt;p&gt;If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value&lt;/p&gt;
* $alias **string**



### addSqlAssociation

    string ShopCore::addSqlAssociation(string $table, string $alias, boolean $inner_join, string $on, $force_not_default)

Add an SQL JOIN in query between a table and its associated table in multishop



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **string** - &lt;p&gt;Table name (E.g. product, module, etc.)&lt;/p&gt;
* $alias **string** - &lt;p&gt;Alias of table&lt;/p&gt;
* $inner_join **boolean** - &lt;p&gt;Use or not INNER JOIN&lt;/p&gt;
* $on **string**
* $force_not_default **mixed**



### addSqlRestrictionOnLang

    string ShopCore::addSqlRestrictionOnLang(string $alias, $id_shop)

Add a restriction on id_shop for multishop lang table



* Visibility: **public**
* This method is **static**.


#### Arguments
* $alias **string**
* $id_shop **mixed**



### getTree

    array ShopCore::getTree()

Get all groups and associated shops as subarrays



* Visibility: **public**
* This method is **static**.




### isFeatureActive

    boolean ShopCore::isFeatureActive()





* Visibility: **public**
* This method is **static**.




### copyShopData

    mixed ShopCore::copyShopData($old_id, $tables_import, $deleted)





* Visibility: **public**


#### Arguments
* $old_id **mixed**
* $tables_import **mixed**
* $deleted **mixed**



### getCategories

    array ShopCore::getCategories(integer $id, $only_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **integer**
* $only_id **mixed**



### getCurrentShop

    mixed ShopCore::getCurrentShop()





* Visibility: **public**
* This method is **static**.




### getEntityIds

    array|boolean ShopCore::getEntityIds(string $entity, integer $id_shop, $active, $delete)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $entity **string**
* $id_shop **integer**
* $active **mixed**
* $delete **mixed**


