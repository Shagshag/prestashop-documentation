Class ShopCore
=====================





* Class name: ShopCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/shop/Shop.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L31)


Contents
--------

### Constants

* [CONTEXT_ALL](#constant-CONTEXT_ALL)
* [CONTEXT_GROUP](#constant-CONTEXT_GROUP)
* [CONTEXT_SHOP](#constant-CONTEXT_SHOP)
* [SHARE_CUSTOMER](#constant-SHARE_CUSTOMER)
* [SHARE_ORDER](#constant-SHARE_ORDER)

### Properties

* [$active](#property-$active)
* [$asso_tables](#property-$asso_tables)
* [$deleted](#property-$deleted)
* [$domain](#property-$domain)
* [$domain_ssl](#property-$domain_ssl)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$group](#property-$group)
* [$id_category](#property-$id_category)
* [$id_group_shop](#property-$id_group_shop)
* [$id_theme](#property-$id_theme)
* [$identifier](#property-$identifier)
* [$name](#property-$name)
* [$physical_uri](#property-$physical_uri)
* [$shops](#property-$shops)
* [$table](#property-$table)
* [$theme_name](#property-$theme_name)
* [$virtual_uri](#property-$virtual_uri)
* [$webserviceParameters](#property-$webserviceParameters)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addSqlAssociation](#method-addSqlAssociation)
* [addSqlRestriction](#method-addSqlRestriction)
* [addSqlRestrictionOnLang](#method-addSqlRestrictionOnLang)
* [associateTo](#method-associateTo)
* [cacheShops](#method-cacheShops)
* [checkIfGroupShopExist](#method-checkIfGroupShopExist)
* [checkIfShopExist](#method-checkIfShopExist)
* [clearCache](#method-clearCache)
* [copyShopData](#method-copyShopData)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getAddress](#method-getAddress)
* [getAssoTables](#method-getAssoTables)
* [getBaseURI](#method-getBaseURI)
* [getBaseURL](#method-getBaseURL)
* [getCategory](#method-getCategory)
* [getContext](#method-getContext)
* [getContextGroupID](#method-getContextGroupID)
* [getContextID](#method-getContextID)
* [getContextType](#method-getContextType)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getGroup](#method-getGroup)
* [getGroupFromShop](#method-getGroupFromShop)
* [getGroupID](#method-getGroupID)
* [getID](#method-getID)
* [getIdByName](#method-getIdByName)
* [getIdShopsByIdGroupShop](#method-getIdShopsByIdGroupShop)
* [getIdentifier](#method-getIdentifier)
* [getInstance](#method-getInstance)
* [getListOfID](#method-getListOfID)
* [getPhysicalURI](#method-getPhysicalURI)
* [getSharedShops](#method-getSharedShops)
* [getShop](#method-getShop)
* [getShopById](#method-getShopById)
* [getShopWithoutUrls](#method-getShopWithoutUrls)
* [getShops](#method-getShops)
* [getTheme](#method-getTheme)
* [getTotalShops](#method-getTotalShops)
* [getTotalShopsByIdGroupShop](#method-getTotalShopsByIdGroupShop)
* [getTotalShopsWhoExists](#method-getTotalShopsWhoExists)
* [getTranslationsFields](#method-getTranslationsFields)
* [getTree](#method-getTree)
* [getUrls](#method-getUrls)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [has_dependency](#method-has_dependency)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [initialize](#method-initialize)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isDefaultShop](#method-isDefaultShop)
* [isFeatureActive](#method-isFeatureActive)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-CONTEXT_ALL"></a>CONTEXT_ALL

```php
const CONTEXT_ALL = 3
```





* Source: [classes/shop/Shop.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L104).


### <a name="constant-CONTEXT_GROUP"></a>CONTEXT_GROUP

```php
const CONTEXT_GROUP = 2
```





* Source: [classes/shop/Shop.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L103).


### <a name="constant-CONTEXT_SHOP"></a>CONTEXT_SHOP

```php
const CONTEXT_SHOP = 1
```

There are 3 kinds of shop context : shop, group shop and general



* Source: [classes/shop/Shop.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L102).


### <a name="constant-SHARE_CUSTOMER"></a>SHARE_CUSTOMER

```php
const SHARE_CUSTOMER = 'share_customer'
```

Some data can be shared between shops, like customers or orders



* Source: [classes/shop/Shop.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L109).


### <a name="constant-SHARE_ORDER"></a>SHARE_ORDER

```php
const SHARE_ORDER = 'share_order'
```





* Source: [classes/shop/Shop.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L110).


Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L36).


### <a name="property-$asso_tables"></a>$asso_tables

```php
private mixed $asso_tables = array('carrier' => array('type' => 'shop'), 'carrier_lang' => array('type' => 'fk_shop'), 'category_lang' => array('type' => 'fk_shop'), 'cms' => array('type' => 'shop'), 'contact' => array('type' => 'shop'), 'country' => array('type' => 'shop'), 'currency' => array('type' => 'shop'), 'employee' => array('type' => 'shop'), 'hook_module' => array('type' => 'fk_shop'), 'hook_module_exceptions' => array('type' => 'fk_shop', 'primary' => 'id_hook_module_exceptions'), 'image' => array('type' => 'shop'), 'lang' => array('type' => 'shop'), 'meta_lang' => array('type' => 'fk_shop'), 'module' => array('type' => 'shop'), 'module_currency' => array('type' => 'fk_shop'), 'module_country' => array('type' => 'fk_shop'), 'module_group' => array('type' => 'fk_shop'), 'product' => array('type' => 'shop'), 'product_lang' => array('type' => 'fk_shop'), 'referrer' => array('type' => 'shop'), 'scene' => array('type' => 'shop'), 'store' => array('type' => 'shop'), 'webservice_account' => array('type' => 'shop'), 'warehouse' => array('type' => 'shop'), 'stock_available' => array('type' => 'fk_shop', 'primary' => 'id_stock_available'))
```





* Visibility: **private**
* This property is **static**.
* Source: [classes/shop/Shop.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L63).


### <a name="property-$deleted"></a>$deleted

```php
public mixed $deleted
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L38).


### <a name="property-$domain"></a>$domain

```php
public mixed $domain
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L43).


### <a name="property-$domain_ssl"></a>$domain_ssl

```php
public mixed $domain_ssl
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L44).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('id_theme', 'id_category', 'id_group_shop', 'name')
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L51).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('name' => 64)
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L52).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('active' => 'isBool', 'name' => 'isGenericName')
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L53).


### <a name="property-$group"></a>$group

```php
protected \GroupShop $group
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L49).


### <a name="property-$id_category"></a>$id_category

```php
public mixed $id_category
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L37).


### <a name="property-$id_group_shop"></a>$id_group_shop

```php
public mixed $id_group_shop
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L33).


### <a name="property-$id_theme"></a>$id_theme

```php
public mixed $id_theme
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L34).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_shop'
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L58).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L35).


### <a name="property-$physical_uri"></a>$physical_uri

```php
public mixed $physical_uri
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L41).


### <a name="property-$shops"></a>$shops

```php
protected array $shops
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L61).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'shop'
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L57).


### <a name="property-$theme_name"></a>$theme_name

```php
public mixed $theme_name
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L40).


### <a name="property-$virtual_uri"></a>$virtual_uri

```php
public mixed $virtual_uri
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L42).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_group_shop' => array('xlink_resource' => 'shop_groups'), 'id_category' => array(), 'id_theme' => array()))
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L91).


### <a name="property-$_cache"></a>$_cache

```php
protected mixed $_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L75).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected \fieldsRequiredDatabase $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L50).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L59).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L62).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L65).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L31).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L34).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L36).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L78).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L81).


### <a name="property-$langMultiShop"></a>$langMultiShop

```php
protected mixed $langMultiShop = false
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L67).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L70).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ShopCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L125)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed ShopCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L150)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L780)


#### Arguments
* $fields **mixed**



### <a name="method-addSqlAssociation"></a>addSqlAssociation

```php
string ShopCore::addSqlAssociation(string $table, string $alias, boolean $inner_join)
```

Add an SQL JOIN in query between a table and its associated table in multishop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 768](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L768)


#### Arguments
* $table **string** - Table name (E.g. product, module, etc.)
* $alias **string** - Alias of table
* $inner_join **boolean** - Use or not INNER JOIN



### <a name="method-addSqlRestriction"></a>addSqlRestriction

```php
mixed ShopCore::addSqlRestriction(integer $share, string $alias, string $type)
```

Add an sql restriction for shops fields



* Visibility: **public**
* Source: [classes/shop/Shop.php line 729](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L729)


#### Arguments
* $share **integer** - If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value
* $alias **string**
* $type **string** - shop|group_shop



### <a name="method-addSqlRestrictionOnLang"></a>addSqlRestrictionOnLang

```php
string ShopCore::addSqlRestrictionOnLang(string $alias)
```

Add a restriction on id_shop for multishop lang table



* Visibility: **public**
* Source: [classes/shop/Shop.php line 791](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L791)


#### Arguments
* $alias **string**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 828](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L828)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-cacheShops"></a>cacheShops

```php
mixed ShopCore::cacheShops(boolean $refresh)
```

Load list of groups and shops, and cache it



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L430)


#### Arguments
* $refresh **boolean**



### <a name="method-checkIfGroupShopExist"></a>checkIfGroupShopExist

```php
mixed ShopCore::checkIfGroupShopExist($id)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L868)


#### Arguments
* $id **mixed**



### <a name="method-checkIfShopExist"></a>checkIfShopExist

```php
mixed ShopCore::checkIfShopExist($id)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 863](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L863)


#### Arguments
* $id **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L794)


#### Arguments
* $all **mixed**



### <a name="method-copyShopData"></a>copyShopData

```php
mixed ShopCore::copyShopData($old_id, $tables_import, $deleted)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 819](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L819)


#### Arguments
* $old_id **mixed**
* $tables_import **mixed**
* $deleted **mixed**



### <a name="method-delete"></a>delete

```php
mixed ShopCore::delete()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L157)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L898)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ObjectModelCore::deleteSelection($selection)
```

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L387)


#### Arguments
* $selection **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L558)


#### Arguments
* $field **mixed**
* $className **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L868)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase($id_entity, $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 931](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L931)


#### Arguments
* $id_entity **mixed** - entity id
* $table **mixed**



### <a name="method-getAddress"></a>getAddress

```php
\Address ShopCore::getAddress()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L291)




### <a name="method-getAssoTables"></a>getAssoTables

```php
array ShopCore::getAssoTables()
```

Get list of associated tables to shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L420)




### <a name="method-getBaseURI"></a>getBaseURI

```php
string ShopCore::getBaseURI()
```

Get shop URI



* Visibility: **public**
* Source: [classes/shop/Shop.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L325)




### <a name="method-getBaseURL"></a>getBaseURL

```php
string ShopCore::getBaseURL()
```

Get shop URL



* Visibility: **public**
* Source: [classes/shop/Shop.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L340)




### <a name="method-getCategory"></a>getCategory

```php
integer ShopCore::getCategory()
```

Get root category of current shop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L386)




### <a name="method-getContext"></a>getContext

```php
\array(id_shop, ShopCore::getContext($type)
```

Retrieve the current shop context in FO or BO



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L661)


#### Arguments
* $type **mixed**



### <a name="method-getContextGroupID"></a>getContextGroupID

```php
integer ShopCore::getContextGroupID()
```

Get ID shop from context



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L702)




### <a name="method-getContextID"></a>getContextID

```php
integer ShopCore::getContextID()
```

Get ID shop from context



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 692](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L692)




### <a name="method-getContextType"></a>getContextType

```php
integer ShopCore::getContextType()
```

Check in which type of shop context we are



* Visibility: **public**
* Source: [classes/shop/Shop.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L712)




### <a name="method-getFields"></a>getFields

```php
mixed ShopCore::getFields()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L112)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L772)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsValidateLang"></a>getFieldsValidateLang

```php
array ObjectModelCore::getFieldsValidateLang()
```

Get list of fields related to language to validate



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L975)




### <a name="method-getGroup"></a>getGroup

```php
\GroupShop ShopCore::getGroup()
```

Get group of current shop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L352)




### <a name="method-getGroupFromShop"></a>getGroupFromShop

```php
integer ShopCore::getGroupFromShop(integer $shop_id, $as_id)
```

Retrieve group ID of a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 587](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L587)


#### Arguments
* $shop_id **integer** - Shop ID
* $as_id **mixed**



### <a name="method-getGroupID"></a>getGroupID

```php
integer ShopCore::getGroupID()
```

Get current shop group ID



* Visibility: **public**
* Source: [classes/shop/Shop.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L374)




### <a name="method-getID"></a>getID

```php
integer ShopCore::getID($use_default)
```

Get current shop ID



* Visibility: **public**
* Source: [classes/shop/Shop.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L364)


#### Arguments
* $use_default **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer ShopCore::getIdByName(string $name)
```

Return a shop ID from shop name



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L538)


#### Arguments
* $name **string**



### <a name="method-getIdShopsByIdGroupShop"></a>getIdShopsByIdGroupShop

```php
mixed ShopCore::getIdShopsByIdGroupShop($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L572)


#### Arguments
* $id **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getInstance"></a>getInstance

```php
\Shop ShopCore::getInstance(integer $id)
```

Get a new instance of a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L215)


#### Arguments
* $id **integer** - shop ID



### <a name="method-getListOfID"></a>getListOfID

```php
array ShopCore::getListOfID(string $share)
```

Get a list of ID concerned by the shop context (E.g. if context is shop group, get list of children shop ID)



* Visibility: **public**
* Source: [classes/shop/Shop.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L621)


#### Arguments
* $share **string** - If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value



### <a name="method-getPhysicalURI"></a>getPhysicalURI

```php
mixed ShopCore::getPhysicalURI()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L330)




### <a name="method-getSharedShops"></a>getSharedShops

```php
array ShopCore::getSharedShops(integer $shop_id, integer $type)
```

If the shop group has the option $type activated, get all shops ID of this group, else get current shop ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L603)


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
* Source: [classes/shop/Shop.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L523)


#### Arguments
* $shop_id **integer**



### <a name="method-getShopById"></a>getShopById

```php
array ShopCore::getShopById(integer $id, string $identifier, string $table)
```

Return the list of shop by id



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L644)


#### Arguments
* $id **integer**
* $identifier **string**
* $table **string**



### <a name="method-getShopWithoutUrls"></a>getShopWithoutUrls

```php
mixed ShopCore::getShopWithoutUrls($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L873)


#### Arguments
* $id_shop **mixed**



### <a name="method-getShops"></a>getShops

```php
mixed ShopCore::getShops(boolean $active, integer $id_group_shop, boolean $get_as_list_id)
```

Get shops list



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L500)


#### Arguments
* $active **boolean**
* $id_group_shop **integer**
* $get_as_list_id **boolean**



### <a name="method-getTheme"></a>getTheme

```php
string ShopCore::getTheme()
```

Get shop theme name



* Visibility: **public**
* Source: [classes/shop/Shop.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L315)




### <a name="method-getTotalShops"></a>getTotalShops

```php
integer ShopCore::getTotalShops($active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 551](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L551)


#### Arguments
* $active **mixed**



### <a name="method-getTotalShopsByIdGroupShop"></a>getTotalShopsByIdGroupShop

```php
integer ShopCore::getTotalShopsByIdGroupShop($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L567)


#### Arguments
* $id **mixed**



### <a name="method-getTotalShopsWhoExists"></a>getTotalShopsWhoExists

```php
integer ShopCore::getTotalShopsWhoExists()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L559)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields(array $fieldsArray)
```

Prepare multilingual fields for database insertion



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L430)


#### Arguments
* $fieldsArray **array** - Multilingual fields to prepare
return array Prepared fields for database insertion



### <a name="method-getTree"></a>getTree

```php
array ShopCore::getTree()
```

Get all groups and associated shops as subarrays



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 801](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L801)




### <a name="method-getUrls"></a>getUrls

```php
array ShopCore::getUrls()
```

Get list of shop's urls



* Visibility: **public**
* Source: [classes/shop/Shop.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L396)




### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L89)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L747)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($wsParamsAttributeName)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L617)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-has_dependency"></a>has_dependency

```php
boolean ShopCore::has_dependency($id_shop)
```

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L185)


#### Arguments
* $id_shop **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L987)


#### Arguments
* $data **array**
* $id_lang **integer**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L1006)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-initialize"></a>initialize

```php
\Shop ShopCore::initialize()
```

Find the shop from current domain / uri and get an instance of this shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L225)




### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L854)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L809)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L948)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isDefaultShop"></a>isDefaultShop

```php
boolean ShopCore::isDefaultShop()
```

Check if current shop ID is the same as default shop in configuration



* Visibility: **public**
* Source: [classes/shop/Shop.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L410)




### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean ShopCore::isFeatureActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 810](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/shop/Shop.php#L810)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L888)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L447)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
mixed ObjectModelCore::save($nullValues, $autodate)
```

Save current object to database (add or update)

return boolean Insertion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L192)


#### Arguments
* $nullValues **mixed**
* $autodate **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed ObjectModelCore::toggleStatus()
```

Toggle object status in database

return boolean Update result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L405)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update($nullValues)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L274)


#### Arguments
* $nullValues **mixed**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L571)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L577)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateFields"></a>validateFields

```php
mixed ObjectModelCore::validateFields($die, $errorReturn)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L481)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
mixed ObjectModelCore::validateFieldsLang($die, $errorReturn)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L514)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**


