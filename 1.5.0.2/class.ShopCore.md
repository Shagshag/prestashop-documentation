Class ShopCore
=====================





* Class name: ShopCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/shop/Shop.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L31)


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
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$domain](#property-$domain)
* [$domain_ssl](#property-$domain_ssl)
* [$group](#property-$group)
* [$id_category](#property-$id_category)
* [$id_group_shop](#property-$id_group_shop)
* [$id_theme](#property-$id_theme)
* [$name](#property-$name)
* [$physical_uri](#property-$physical_uri)
* [$shops](#property-$shops)
* [$theme_name](#property-$theme_name)
* [$virtual_uri](#property-$virtual_uri)
* [$webserviceParameters](#property-$webserviceParameters)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
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
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAddress](#method-getAddress)
* [getAssoTables](#method-getAssoTables)
* [getBaseURI](#method-getBaseURI)
* [getBaseURL](#method-getBaseURL)
* [getCategory](#method-getCategory)
* [getContext](#method-getContext)
* [getContextGroupID](#method-getContextGroupID)
* [getContextID](#method-getContextID)
* [getContextType](#method-getContextType)
* [getDefinition](#method-getDefinition)
* [getEntity](#method-getEntity)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getGroup](#method-getGroup)
* [getGroupFromShop](#method-getGroupFromShop)
* [getGroupID](#method-getGroupID)
* [getID](#method-getID)
* [getIdByName](#method-getIdByName)
* [getIdShopsByIdGroupShop](#method-getIdShopsByIdGroupShop)
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
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-CONTEXT_ALL"></a>CONTEXT_ALL

```php
const CONTEXT_ALL = 3
```





* Source: [classes/shop/Shop.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L111).


### <a name="constant-CONTEXT_GROUP"></a>CONTEXT_GROUP

```php
const CONTEXT_GROUP = 2
```





* Source: [classes/shop/Shop.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L110).


### <a name="constant-CONTEXT_SHOP"></a>CONTEXT_SHOP

```php
const CONTEXT_SHOP = 1
```

There are 3 kinds of shop context : shop, group shop and general



* Source: [classes/shop/Shop.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L109).


### <a name="constant-SHARE_CUSTOMER"></a>SHARE_CUSTOMER

```php
const SHARE_CUSTOMER = 'share_customer'
```

Some data can be shared between shops, like customers or orders



* Source: [classes/shop/Shop.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L116).


### <a name="constant-SHARE_ORDER"></a>SHARE_ORDER

```php
const SHARE_ORDER = 'share_order'
```





* Source: [classes/shop/Shop.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L117).


Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L36).


### <a name="property-$asso_tables"></a>$asso_tables

```php
private mixed $asso_tables = array('carrier' => array('type' => 'shop'), 'carrier_lang' => array('type' => 'fk_shop'), 'category_lang' => array('type' => 'fk_shop'), 'cms' => array('type' => 'shop'), 'contact' => array('type' => 'shop'), 'country' => array('type' => 'shop'), 'currency' => array('type' => 'shop'), 'employee' => array('type' => 'shop'), 'hook_module' => array('type' => 'fk_shop'), 'hook_module_exceptions' => array('type' => 'fk_shop', 'primary' => 'id_hook_module_exceptions'), 'image' => array('type' => 'shop'), 'lang' => array('type' => 'shop'), 'meta_lang' => array('type' => 'fk_shop'), 'module' => array('type' => 'shop'), 'module_currency' => array('type' => 'fk_shop'), 'module_country' => array('type' => 'fk_shop'), 'module_group' => array('type' => 'fk_shop'), 'product' => array('type' => 'shop'), 'product_lang' => array('type' => 'fk_shop'), 'referrer' => array('type' => 'shop'), 'scene' => array('type' => 'shop'), 'store' => array('type' => 'shop'), 'webservice_account' => array('type' => 'shop'), 'warehouse' => array('type' => 'shop'))
```





* Visibility: **private**
* This property is **static**.
* Source: [classes/shop/Shop.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L70).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'shop', 'primary' => 'id_shop', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'id_theme' => array('type' => self::TYPE_INT, 'required' => true), 'id_category' => array('type' => self::TYPE_INT, 'required' => true), 'id_group_shop' => array('type' => self::TYPE_INT, 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/shop/Shop.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L54).


### <a name="property-$deleted"></a>$deleted

```php
public mixed $deleted
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L38).


### <a name="property-$domain"></a>$domain

```php
public mixed $domain
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L43).


### <a name="property-$domain_ssl"></a>$domain_ssl

```php
public mixed $domain_ssl
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L44).


### <a name="property-$group"></a>$group

```php
protected \GroupShop $group
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L49).


### <a name="property-$id_category"></a>$id_category

```php
public mixed $id_category
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L37).


### <a name="property-$id_group_shop"></a>$id_group_shop

```php
public mixed $id_group_shop
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L33).


### <a name="property-$id_theme"></a>$id_theme

```php
public mixed $id_theme
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L34).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L35).


### <a name="property-$physical_uri"></a>$physical_uri

```php
public mixed $physical_uri
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L41).


### <a name="property-$shops"></a>$shops

```php
protected array $shops
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/Shop.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L68).


### <a name="property-$theme_name"></a>$theme_name

```php
public mixed $theme_name
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L40).


### <a name="property-$virtual_uri"></a>$virtual_uri

```php
public mixed $virtual_uri
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L42).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_group_shop' => array('xlink_resource' => 'shop_groups'), 'id_category' => array(), 'id_theme' => array()))
```





* Visibility: **protected**
* Source: [classes/shop/Shop.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L98).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ShopCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L119)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed ShopCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L144)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L961)


#### Arguments
* $fields **mixed**



### <a name="method-addSqlAssociation"></a>addSqlAssociation

```php
string ShopCore::addSqlAssociation(string $table, string $alias, boolean $inner_join)
```

Add an SQL JOIN in query between a table and its associated table in multishop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L778)


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
* Source: [classes/shop/Shop.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L739)


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
* Source: [classes/shop/Shop.php line 801](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L801)


#### Arguments
* $alias **string**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1009)


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
* Source: [classes/shop/Shop.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L440)


#### Arguments
* $refresh **boolean**



### <a name="method-checkIfGroupShopExist"></a>checkIfGroupShopExist

```php
mixed ShopCore::checkIfGroupShopExist($id)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 878](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L878)


#### Arguments
* $id **mixed**



### <a name="method-checkIfShopExist"></a>checkIfShopExist

```php
mixed ShopCore::checkIfShopExist($id)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L873)


#### Arguments
* $id **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L975)


#### Arguments
* $all **mixed**



### <a name="method-copyShopData"></a>copyShopData

```php
mixed ShopCore::copyShopData($old_id, $tables_import, $deleted)
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L829)


#### Arguments
* $old_id **mixed**
* $tables_import **mixed**
* $deleted **mixed**



### <a name="method-delete"></a>delete

```php
mixed ShopCore::delete()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L151)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1079)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L553)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L740)


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
* Source: [classes/ObjectModel.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1049)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1113)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L272)


#### Arguments
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAddress"></a>getAddress

```php
\Address ShopCore::getAddress()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L301)




### <a name="method-getAssoTables"></a>getAssoTables

```php
array ShopCore::getAssoTables()
```

Get list of associated tables to shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L430)




### <a name="method-getBaseURI"></a>getBaseURI

```php
string ShopCore::getBaseURI()
```

Get shop URI



* Visibility: **public**
* Source: [classes/shop/Shop.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L335)




### <a name="method-getBaseURL"></a>getBaseURL

```php
string ShopCore::getBaseURL()
```

Get shop URL



* Visibility: **public**
* Source: [classes/shop/Shop.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L350)




### <a name="method-getCategory"></a>getCategory

```php
integer ShopCore::getCategory()
```

Get root category of current shop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L396)




### <a name="method-getContext"></a>getContext

```php
\array(id_shop, ShopCore::getContext($type)
```

Retrieve the current shop context in FO or BO



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L671)


#### Arguments
* $type **mixed**



### <a name="method-getContextGroupID"></a>getContextGroupID

```php
integer ShopCore::getContextGroupID()
```

Get ID shop from context



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L712)




### <a name="method-getContextID"></a>getContextID

```php
integer ShopCore::getContextID()
```

Get ID shop from context



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L702)




### <a name="method-getContextType"></a>getContextType

```php
integer ShopCore::getContextType()
```

Check in which type of shop context we are



* Visibility: **public**
* Source: [classes/shop/Shop.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L722)




### <a name="method-getDefinition"></a>getDefinition

```php
mixed ObjectModelCore::getDefinition($class, $field)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1209)


#### Arguments
* $class **mixed**
* $field **mixed**



### <a name="method-getEntity"></a>getEntity

```php
mixed ObjectModelCore::getEntity($entity)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1269)


#### Arguments
* $entity **mixed**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L953)


#### Arguments
* $all **mixed**



### <a name="method-getGroup"></a>getGroup

```php
\GroupShop ShopCore::getGroup()
```

Get group of current shop



* Visibility: **public**
* Source: [classes/shop/Shop.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L362)




### <a name="method-getGroupFromShop"></a>getGroupFromShop

```php
integer ShopCore::getGroupFromShop(integer $shop_id, $as_id)
```

Retrieve group ID of a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L597)


#### Arguments
* $shop_id **integer** - Shop ID
* $as_id **mixed**



### <a name="method-getGroupID"></a>getGroupID

```php
integer ShopCore::getGroupID()
```

Get current shop group ID



* Visibility: **public**
* Source: [classes/shop/Shop.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L384)




### <a name="method-getID"></a>getID

```php
integer ShopCore::getID($use_default)
```

Get current shop ID



* Visibility: **public**
* Source: [classes/shop/Shop.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L374)


#### Arguments
* $use_default **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer ShopCore::getIdByName(string $name)
```

Return a shop ID from shop name



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L548)


#### Arguments
* $name **string**



### <a name="method-getIdShopsByIdGroupShop"></a>getIdShopsByIdGroupShop

```php
mixed ShopCore::getIdShopsByIdGroupShop($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L582)


#### Arguments
* $id **mixed**



### <a name="method-getInstance"></a>getInstance

```php
\Shop ShopCore::getInstance(integer $id)
```

Get a new instance of a shop



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L214)


#### Arguments
* $id **integer** - shop ID



### <a name="method-getListOfID"></a>getListOfID

```php
array ShopCore::getListOfID(string $share)
```

Get a list of ID concerned by the shop context (E.g. if context is shop group, get list of children shop ID)



* Visibility: **public**
* Source: [classes/shop/Shop.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L631)


#### Arguments
* $share **string** - If false, dont check share datas from group. Else can take a Shop::SHARE_* constant value



### <a name="method-getPhysicalURI"></a>getPhysicalURI

```php
mixed ShopCore::getPhysicalURI()
```





* Visibility: **public**
* Source: [classes/shop/Shop.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L340)




### <a name="method-getSharedShops"></a>getSharedShops

```php
array ShopCore::getSharedShops(integer $shop_id, integer $type)
```

If the shop group has the option $type activated, get all shops ID of this group, else get current shop ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 613](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L613)


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
* Source: [classes/shop/Shop.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L533)


#### Arguments
* $shop_id **integer**



### <a name="method-getShopById"></a>getShopById

```php
array ShopCore::getShopById(integer $id, string $identifier, string $table)
```

Return the list of shop by id



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 654](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L654)


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
* Source: [classes/shop/Shop.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L883)


#### Arguments
* $id_shop **mixed**



### <a name="method-getShops"></a>getShops

```php
mixed ShopCore::getShops(boolean $active, integer $id_group_shop, boolean $get_as_list_id)
```

Get shops list



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 510](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L510)


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
* Source: [classes/shop/Shop.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L325)




### <a name="method-getTotalShops"></a>getTotalShops

```php
integer ShopCore::getTotalShops($active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L561)


#### Arguments
* $active **mixed**



### <a name="method-getTotalShopsByIdGroupShop"></a>getTotalShopsByIdGroupShop

```php
integer ShopCore::getTotalShopsByIdGroupShop($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L577)


#### Arguments
* $id **mixed**



### <a name="method-getTotalShopsWhoExists"></a>getTotalShopsWhoExists

```php
integer ShopCore::getTotalShopsWhoExists()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L569)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fieldsArray)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L589)


#### Arguments
* $fieldsArray **mixed**



### <a name="method-getTree"></a>getTree

```php
array ShopCore::getTree()
```

Get all groups and associated shops as subarrays



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 811](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L811)




### <a name="method-getUrls"></a>getUrls

```php
array ShopCore::getUrls()
```

Get list of shop's urls



* Visibility: **public**
* Source: [classes/shop/Shop.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L406)




### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L130)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L929)


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
* Source: [classes/ObjectModel.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L799)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-has_dependency"></a>has_dependency

```php
boolean ShopCore::has_dependency($id_shop)
```

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L184)


#### Arguments
* $id_shop **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1148)


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
* Source: [classes/ObjectModel.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1167)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-initialize"></a>initialize

```php
\Shop ShopCore::initialize()
```

Find the shop from current domain / uri and get an instance of this shop
if INSTALL_VERSION is defined, will return an empty shop object



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L225)




### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1035)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L990)


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
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1131)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isDefaultShop"></a>isDefaultShop

```php
boolean ShopCore::isDefaultShop()
```

Check if current shop ID is the same as default shop in configuration



* Visibility: **public**
* Source: [classes/shop/Shop.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L420)




### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean ShopCore::isFeatureActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/Shop.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/shop/Shop.php#L820)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1069)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L605)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1224)




### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L569)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L444)


#### Arguments
* $null_values **boolean**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L753)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L759)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L704)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L643)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L669)


#### Arguments
* $die **boolean**
* $error_return **boolean**


