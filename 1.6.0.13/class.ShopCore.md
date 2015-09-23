Class ShopCore
=====================





* Class name: ShopCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/shop/Shop.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L30)


Contents
--------

### Constants

* [CONTEXT_ALL](#constant-CONTEXT_ALL)
* [CONTEXT_GROUP](#constant-CONTEXT_GROUP)
* [CONTEXT_SHOP](#constant-CONTEXT_SHOP)
* [SHARE_CUSTOMER](#constant-SHARE_CUSTOMER)
* [SHARE_ORDER](#constant-SHARE_ORDER)
* [SHARE_STOCK](#constant-SHARE_STOCK)

### Properties

* [$active](#property-$active)
* [$asso_tables](#property-$asso_tables)
* [$context](#property-$context)
* [$context_id_shop](#property-$context_id_shop)
* [$context_id_shop_group](#property-$context_id_shop_group)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$domain](#property-$domain)
* [$domain_ssl](#property-$domain_ssl)
* [$group](#property-$group)
* [$id_category](#property-$id_category)
* [$id_shop_default_tables](#property-$id_shop_default_tables)
* [$id_shop_group](#property-$id_shop_group)
* [$id_theme](#property-$id_theme)
* [$initialized](#property-$initialized)
* [$name](#property-$name)
* [$physical_uri](#property-$physical_uri)
* [$shops](#property-$shops)
* [$theme_directory](#property-$theme_directory)
* [$theme_name](#property-$theme_name)
* [$virtual_uri](#property-$virtual_uri)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addSqlAssociation](#method-addSqlAssociation)
* [addSqlRestriction](#method-addSqlRestriction)
* [addSqlRestrictionOnLang](#method-addSqlRestrictionOnLang)
* [addTableAssociation](#method-addTableAssociation)
* [associateSuperAdmins](#method-associateSuperAdmins)
* [cacheShops](#method-cacheShops)
* [checkIdShopDefault](#method-checkIdShopDefault)
* [copyShopData](#method-copyShopData)
* [delete](#method-delete)
* [getAddress](#method-getAddress)
* [getAssoTable](#method-getAssoTable)
* [getAssoTables](#method-getAssoTables)
* [getBaseURI](#method-getBaseURI)
* [getBaseURL](#method-getBaseURL)
* [getCategories](#method-getCategories)
* [getCategory](#method-getCategory)
* [getCompleteListOfShopsID](#method-getCompleteListOfShopsID)
* [getContext](#method-getContext)
* [getContextListShopID](#method-getContextListShopID)
* [getContextShopGroup](#method-getContextShopGroup)
* [getContextShopGroupID](#method-getContextShopGroupID)
* [getContextShopID](#method-getContextShopID)
* [getCurrentShop](#method-getCurrentShop)
* [getEntityIds](#method-getEntityIds)
* [getGroup](#method-getGroup)
* [getGroupFromShop](#method-getGroupFromShop)
* [getIdByName](#method-getIdByName)
* [getSharedShops](#method-getSharedShops)
* [getShop](#method-getShop)
* [getShopById](#method-getShopById)
* [getShops](#method-getShops)
* [getShopsCollection](#method-getShopsCollection)
* [getTheme](#method-getTheme)
* [getTotalShops](#method-getTotalShops)
* [getTree](#method-getTree)
* [getUrls](#method-getUrls)
* [getUrlsSharedCart](#method-getUrlsSharedCart)
* [hasDependency](#method-hasDependency)
* [init](#method-init)
* [initialize](#method-initialize)
* [isDefaultShop](#method-isDefaultShop)
* [isFeatureActive](#method-isFeatureActive)
* [isTableAssociated](#method-isTableAssociated)
* [setContext](#method-setContext)
* [setUrl](#method-setUrl)


Constants
----------


### <a name="constant-CONTEXT_ALL"></a>CONTEXT_ALL

```php
const CONTEXT_ALL = 4
```





* Source: [classes/shop/Shop.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L113).


### <a name="constant-CONTEXT_GROUP"></a>CONTEXT_GROUP

```php
const CONTEXT_GROUP = 2
```





* Source: [classes/shop/Shop.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L112).


### <a name="constant-CONTEXT_SHOP"></a>CONTEXT_SHOP

```php
const CONTEXT_SHOP = 1
```

There are 3 kinds of shop context : shop, group shop and general



* Source: [classes/shop/Shop.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L111).


### <a name="constant-SHARE_CUSTOMER"></a>SHARE_CUSTOMER

```php
const SHARE_CUSTOMER = 'share_customer'
```

Some data can be shared between shops, like customers or orders



* Source: [classes/shop/Shop.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L118).


### <a name="constant-SHARE_ORDER"></a>SHARE_ORDER

```php
const SHARE_ORDER = 'share_order'
```





* Source: [classes/shop/Shop.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L119).


### <a name="constant-SHARE_STOCK"></a>SHARE_STOCK

```php
const SHARE_STOCK = 'share_stock'
```





* Source: [classes/shop/Shop.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L120).


Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active = true
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L44).


### <a name="property-$asso_tables"></a>$asso_tables

```php
protected mixed $asso_tables = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L87).


### <a name="property-$context"></a>$context

```php
protected integer $context
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L100).


### <a name="property-$context_id_shop"></a>$context_id_shop

```php
protected integer $context_id_shop
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L103).


### <a name="property-$context_id_shop_group"></a>$context_id_shop_group

```php
protected integer $context_id_shop_group
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L106).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'shop', 'primary' => 'id_shop', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_theme' => array('type' => self::TYPE_INT, 'required' => true), 'id_category' => array('type' => self::TYPE_INT, 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/shop/Shop.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L71).


### <a name="property-$deleted"></a>$deleted

```php
public mixed $deleted
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L45).


### <a name="property-$domain"></a>$domain

```php
public string $domain
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L60).


### <a name="property-$domain_ssl"></a>$domain_ssl

```php
public string $domain_ssl
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L63).


### <a name="property-$group"></a>$group

```php
protected \ShopGroup $group
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L66).


### <a name="property-$id_category"></a>$id_category

```php
public integer $id_category
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L36).


### <a name="property-$id_shop_default_tables"></a>$id_shop_default_tables

```php
protected mixed $id_shop_default_tables = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L88).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public integer $id_shop_group
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L33).


### <a name="property-$id_theme"></a>$id_theme

```php
public integer $id_theme
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L39).


### <a name="property-$initialized"></a>$initialized

```php
protected mixed $initialized = false
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L89).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L42).


### <a name="property-$physical_uri"></a>$physical_uri

```php
public string $physical_uri
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L54).


### <a name="property-$shops"></a>$shops

```php
protected array $shops
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L85).


### <a name="property-$theme_directory"></a>$theme_directory

```php
public string $theme_directory
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L51).


### <a name="property-$theme_name"></a>$theme_name

```php
public string $theme_name
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L48).


### <a name="property-$virtual_uri"></a>$virtual_uri

```php
public string $virtual_uri
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L57).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_shop_group' => array('xlink_resource' => 'shop_groups'), 'id_category' => array(), 'id_theme' => array()))
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L91).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ShopCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

On shop instance, get its theme and URL data too



* Visibility: **public**
* Source: [classes/shop/Shop.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L129)


#### Arguments
* $id **integer**
* $id_lang **integer**
* $id_shop **integer**



### <a name="method-add"></a>add

```php
boolean ShopCore::add(boolean $autodate, boolean $null_values)
```

Add a shop, and clear the cache



* Visibility: **public**
* Source: [classes/shop/Shop.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L225)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-addSqlAssociation"></a>addSqlAssociation

```php
string ShopCore::addSqlAssociation(string $table, string $alias, boolean $inner_join, string $on, $force_not_default)
```

Add an SQL JOIN in query between a table and its associated table in multishop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L957)


#### Arguments
* $table **string** - Table name (E.g. product, module, etc.)
* $alias **string** - Alias of table
* $inner_join **boolean** - Use or not INNER JOIN
* $on **string**
* $force_not_default **mixed**



### <a name="method-addSqlRestriction"></a>addSqlRestriction

```php
mixed ShopCore::addSqlRestriction(integer $share, string $alias)
```

Add an sql restriction for shops fields



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 934](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L934)


#### Arguments
* $share **integer** - If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value
* $alias **string**



### <a name="method-addSqlRestrictionOnLang"></a>addSqlRestrictionOnLang

```php
string ShopCore::addSqlRestrictionOnLang(string $alias, $id_shop)
```

Add a restriction on id_shop for multishop lang table



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 985](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L985)


#### Arguments
* $alias **string**
* $id_shop **mixed**



### <a name="method-addTableAssociation"></a>addTableAssociation

```php
boolean ShopCore::addTableAssociation(string $table_name, array $table_details)
```

Add table associated to shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 584](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L584)


#### Arguments
* $table_name **string**
* $table_details **array**



### <a name="method-associateSuperAdmins"></a>associateSuperAdmins

```php
mixed ShopCore::associateSuperAdmins()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L232)




### <a name="method-cacheShops"></a>cacheShops

```php
mixed ShopCore::cacheShops(boolean $refresh)
```

Load list of groups and shops, and cache it



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L611)


#### Arguments
* $refresh **boolean**



### <a name="method-checkIdShopDefault"></a>checkIdShopDefault

```php
boolean ShopCore::checkIdShopDefault($table)
```

check if the table has an id_shop_default



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L558)


#### Arguments
* $table **mixed**



### <a name="method-copyShopData"></a>copyShopData

```php
mixed ShopCore::copyShopData($old_id, $tables_import, $deleted)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 1020](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L1020)


#### Arguments
* $old_id **mixed**
* $tables_import **mixed**
* $deleted **mixed**



### <a name="method-delete"></a>delete

```php
boolean ShopCore::delete()
```

Remove a shop only if it has no dependencies, and remove its associations



* Visibility: **public**
* Source: [classes/shop/Shop.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L247)




### <a name="method-getAddress"></a>getAddress

```php
\Address ShopCore::getAddress()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L444)




### <a name="method-getAssoTable"></a>getAssoTable

```php
array ShopCore::getAssoTable($table)
```

Get the associated table if available



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L546)


#### Arguments
* $table **mixed**



### <a name="method-getAssoTables"></a>getAssoTables

```php
array ShopCore::getAssoTables()
```

Get list of associated tables to shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 570](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L570)




### <a name="method-getBaseURI"></a>getBaseURI

```php
string ShopCore::getBaseURI()
```

Get shop URI



* Visibility: **public**
* Source: [classes/shop/Shop.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L478)




### <a name="method-getBaseURL"></a>getBaseURL

```php
string ShopCore::getBaseURL()
```

Get shop URL



* Visibility: **public**
* Source: [classes/shop/Shop.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L488)




### <a name="method-getCategories"></a>getCategories

```php
array ShopCore::getCategories(integer $id, $only_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 1117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L1117)


#### Arguments
* $id **integer**
* $only_id **mixed**



### <a name="method-getCategory"></a>getCategory

```php
integer ShopCore::getCategory()
```

Get root category of current shop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 512](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L512)




### <a name="method-getCompleteListOfShopsID"></a>getCompleteListOfShopsID

```php
mixed ShopCore::getCompleteListOfShopsID()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L671)




### <a name="method-getContext"></a>getContext

```php
integer ShopCore::getContext()
```

Get current context of shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L890)




### <a name="method-getContextListShopID"></a>getContextListShopID

```php
array ShopCore::getContextListShopID(string $share)
```

Get a list of ID concerned by the shop context (E.g. if context is shop group, get list of children shop ID)



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 824](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L824)


#### Arguments
* $share **string** - If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value



### <a name="method-getContextShopGroup"></a>getContextShopGroup

```php
mixed ShopCore::getContextShopGroup()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 920](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L920)




### <a name="method-getContextShopGroupID"></a>getContextShopGroupID

```php
integer ShopCore::getContextShopGroupID($null_value_without_multishop)
```

Get current ID of shop group if context is CONTEXT_SHOP or CONTEXT_GROUP



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 912](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L912)


#### Arguments
* $null_value_without_multishop **mixed**



### <a name="method-getContextShopID"></a>getContextShopID

```php
integer ShopCore::getContextShopID($null_value_without_multishop)
```

Get current ID of shop if context is CONTEXT_SHOP



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 900](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L900)


#### Arguments
* $null_value_without_multishop **mixed**



### <a name="method-getCurrentShop"></a>getCurrentShop

```php
mixed ShopCore::getCurrentShop()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 1146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L1146)




### <a name="method-getEntityIds"></a>getEntityIds

```php
array|boolean ShopCore::getEntityIds(string $entity, integer $id_shop, $active, $delete)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 1157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L1157)


#### Arguments
* $entity **string**
* $id_shop **integer**
* $active **mixed**
* $delete **mixed**



### <a name="method-getGroup"></a>getGroup

```php
\ShopGroup ShopCore::getGroup()
```

Get group of current shop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L500)




### <a name="method-getGroupFromShop"></a>getGroupFromShop

```php
integer ShopCore::getGroupFromShop(integer $shop_id, $as_id)
```

Retrieve group ID of a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L790)


#### Arguments
* $shop_id **integer** - Shop ID
* $as_id **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer ShopCore::getIdByName(string $name)
```

Return a shop ID from shop name



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 764](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L764)


#### Arguments
* $name **string**



### <a name="method-getSharedShops"></a>getSharedShops

```php
array ShopCore::getSharedShops(integer $shop_id, integer $type)
```

If the shop group has the option $type activated, get all shops ID of this group, else get current shop ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L806)


#### Arguments
* $shop_id **integer**
* $type **integer** - Shop::SHARE_CUSTOMER | Shop::SHARE_ORDER



### <a name="method-getShop"></a>getShop

```php
array ShopCore::getShop(integer $shop_id)
```

Return some informations cached for one shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 749](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L749)


#### Arguments
* $shop_id **integer**



### <a name="method-getShopById"></a>getShopById

```php
array ShopCore::getShopById(integer $id, string $identifier, string $table)
```

Return the list of shop by id



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 844](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L844)


#### Arguments
* $id **integer**
* $identifier **string**
* $table **string**



### <a name="method-getShops"></a>getShops

```php
array ShopCore::getShops(boolean $active, integer $id_shop_group, boolean $get_as_list_id)
```

Get shops list



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 688](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L688)


#### Arguments
* $active **boolean**
* $id_shop_group **integer**
* $get_as_list_id **boolean**



### <a name="method-getShopsCollection"></a>getShopsCollection

```php
\PrestaShopCollection ShopCore::getShopsCollection(boolean $active, integer $id_shop_group)
```

Get a collection of shops



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 731](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L731)


#### Arguments
* $active **boolean**
* $id_shop_group **integer**



### <a name="method-getTheme"></a>getTheme

```php
string ShopCore::getTheme()
```

Get shop theme name



* Visibility: **public**
* Source: [classes/shop/Shop.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L468)




### <a name="method-getTotalShops"></a>getTotalShops

```php
integer ShopCore::getTotalShops(boolean $active, integer $id_shop_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L779)


#### Arguments
* $active **boolean**
* $id_shop_group **integer**



### <a name="method-getTree"></a>getTree

```php
array ShopCore::getTree()
```

Get all groups and associated shops as subarrays



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 1000](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L1000)




### <a name="method-getUrls"></a>getUrls

```php
array ShopCore::getUrls()
```

Get list of shop's urls



* Visibility: **public**
* Source: [classes/shop/Shop.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L522)




### <a name="method-getUrlsSharedCart"></a>getUrlsSharedCart

```php
mixed ShopCore::getUrlsSharedCart()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 706](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L706)




### <a name="method-hasDependency"></a>hasDependency

```php
boolean ShopCore::hasDependency(integer $id_shop)
```

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L282)


#### Arguments
* $id_shop **integer**



### <a name="method-init"></a>init

```php
mixed ShopCore::init()
```

Initialize an array with all the multistore associations in the database



* Visibility: **protected**
* This method is **static**.
* Source: [classes/shop/Shop.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L139)




### <a name="method-initialize"></a>initialize

```php
\Shop ShopCore::initialize()
```

Find the shop from current domain / uri and get an instance of this shop
if INSTALL_VERSION is defined, will return an empty shop object



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L312)




### <a name="method-isDefaultShop"></a>isDefaultShop

```php
boolean ShopCore::isDefaultShop()
```

Check if current shop ID is the same as default shop in configuration



* Visibility: **public**
* Source: [classes/shop/Shop.php line 536](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L536)




### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean ShopCore::isFeatureActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L1009)




### <a name="method-isTableAssociated"></a>isTableAssociated

```php
boolean ShopCore::isTableAssociated(string $table)
```

Check if given table is associated to shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 599](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L599)


#### Arguments
* $table **string**



### <a name="method-setContext"></a>setContext

```php
mixed ShopCore::setContext(integer $type, integer $id)
```

Change the current shop context



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 859](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L859)


#### Arguments
* $type **integer** - Shop::CONTEXT_ALL | Shop::CONTEXT_GROUP | Shop::CONTEXT_SHOP
* $id **integer** - ID shop if CONTEXT_SHOP or id shop group if CONTEXT_GROUP



### <a name="method-setUrl"></a>setUrl

```php
mixed ShopCore::setUrl()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/shop/Shop.php#L189)



