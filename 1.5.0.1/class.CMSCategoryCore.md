Class CMSCategoryCore
=====================





* Class name: CMSCategoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CMSCategory.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L28)


Contents
--------


### Properties

* [$_links](#property-$_links)
* [$active](#property-$active)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$description](#property-$description)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_cms_category](#property-$id_cms_category)
* [$id_parent](#property-$id_parent)
* [$identifier](#property-$identifier)
* [$level_depth](#property-$level_depth)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$name](#property-$name)
* [$position](#property-$position)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [calcLevelDepth](#method-calcLevelDepth)
* [checkBeforeMove](#method-checkBeforeMove)
* [cleanPositions](#method-cleanPositions)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getCategories](#method-getCategories)
* [getChildren](#method-getChildren)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getHomeCategories](#method-getHomeCategories)
* [getIdentifier](#method-getIdentifier)
* [getLastPosition](#method-getLastPosition)
* [getLink](#method-getLink)
* [getLinkRewrite](#method-getLinkRewrite)
* [getName](#method-getName)
* [getParentsCategories](#method-getParentsCategories)
* [getRecurseCategory](#method-getRecurseCategory)
* [getSimpleCategories](#method-getSimpleCategories)
* [getSubCategories](#method-getSubCategories)
* [getTranslationsFields](#method-getTranslationsFields)
* [getTranslationsFieldsChild](#method-getTranslationsFieldsChild)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hideCMSCategoryPosition](#method-hideCMSCategoryPosition)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [recurseCMSCategory](#method-recurseCMSCategory)
* [recurseLiteCategTree](#method-recurseLiteCategTree)
* [recursiveDelete](#method-recursiveDelete)
* [save](#method-save)
* [searchByName](#method-searchByName)
* [searchByNameAndParentCMSCategoryId](#method-searchByNameAndParentCMSCategoryId)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updatePosition](#method-updatePosition)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_links"></a>$_links

```php
protected mixed $_links = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/CMSCategory.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L71).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L39).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L66).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L69).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L42).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('id_parent', 'active')
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L76).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array('name', 'link_rewrite')
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L79).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('id_parent' => 10, 'active' => 1)
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array('name' => 64, 'link_rewrite' => 64, 'meta_title' => 128, 'meta_description' => 255, 'meta_keywords' => 255)
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L80).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('active' => 'isBool', 'id_parent' => 'isUnsignedInt')
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L78).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array('name' => 'isCatalogName', 'link_rewrite' => 'isLinkRewrite', 'description' => 'isCleanHtml', 'meta_title' => 'isGenericName', 'meta_description' => 'isGenericName', 'meta_keywords' => 'isGenericName')
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L81).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L30).


### <a name="property-$id_cms_category"></a>$id_cms_category

```php
public integer $id_cms_category
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L33).


### <a name="property-$id_parent"></a>$id_parent

```php
public integer $id_parent
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L45).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_cms_category'
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L85).


### <a name="property-$level_depth"></a>$level_depth

```php
public integer $level_depth
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L51).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L54).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L63).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L60).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L57).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L36).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L48).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'cms_category'
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L84).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array('cms_category', 'cms_category_lang')
```





* Visibility: **protected**
* Source: [classes/CMSCategory.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L74).


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


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CMSCategoryCore::__construct($id_cms_category, $id_lang)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L87)


#### Arguments
* $id_cms_category **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed CMSCategoryCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L117)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L780)


#### Arguments
* $fields **mixed**



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



### <a name="method-calcLevelDepth"></a>calcLevelDepth

```php
integer CMSCategoryCore::calcLevelDepth()
```

Get the number of parent categories



* Visibility: **public**
* Source: [classes/CMSCategory.php line 310](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L310)




### <a name="method-checkBeforeMove"></a>checkBeforeMove

```php
boolean CMSCategoryCore::checkBeforeMove($id_cms_category, integer $id_parent)
```

Check if CMSCategory can be moved in another one



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L439)


#### Arguments
* $id_cms_category **mixed**
* $id_parent **integer** - Parent candidate



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed CMSCategoryCore::cleanPositions($id_category_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 601](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L601)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L794)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed CMSCategoryCore::delete()
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L257)




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
mixed CMSCategoryCore::deleteSelection($categories)
```

Delete several categories from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/CMSCategory.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L294)


#### Arguments
* $categories **mixed**



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



### <a name="method-getCategories"></a>getCategories

```php
array CMSCategoryCore::getCategories(integer $id_lang, boolean $active, $order)
```

Return available categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L325)


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
* Source: [classes/CMSCategory.php line 409](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L409)


#### Arguments
* $id_parent **mixed**
* $id_lang **mixed**
* $active **mixed**



### <a name="method-getFields"></a>getFields

```php
mixed CMSCategoryCore::getFields()
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L92)




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




### <a name="method-getHomeCategories"></a>getHomeCategories

```php
array CMSCategoryCore::getHomeCategories(integer $id_lang, boolean $active)
```

Return main categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L404)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getLastPosition"></a>getLastPosition

```php
mixed CMSCategoryCore::getLastPosition($id_category_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 620](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L620)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-getLink"></a>getLink

```php
mixed CMSCategoryCore::getLink(\Link $link)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L473)


#### Arguments
* $link **[Link](class.LinkCore.md)**



### <a name="method-getLinkRewrite"></a>getLinkRewrite

```php
mixed CMSCategoryCore::getLinkRewrite($id_cms_category, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L455)


#### Arguments
* $id_cms_category **mixed**
* $id_lang **mixed**



### <a name="method-getName"></a>getName

```php
mixed CMSCategoryCore::getName($id_lang)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L480)


#### Arguments
* $id_lang **mixed**



### <a name="method-getParentsCategories"></a>getParentsCategories

```php
array CMSCategoryCore::getParentsCategories(integer $id_lang)
```

Get Each parent CMSCategory of this CMSCategory until the root CMSCategory



* Visibility: **public**
* Source: [classes/CMSCategory.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L545)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getRecurseCategory"></a>getRecurseCategory

```php
mixed CMSCategoryCore::getRecurseCategory($id_lang, $current, $active, $links, \Link $link, \Shop $shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L180)


#### Arguments
* $id_lang **mixed**
* $current **mixed**
* $active **mixed**
* $links **mixed**
* $link **[Link](class.LinkCore.md)**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getSimpleCategories"></a>getSimpleCategories

```php
mixed CMSCategoryCore::getSimpleCategories($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L347)


#### Arguments
* $id_lang **mixed**



### <a name="method-getSubCategories"></a>getSubCategories

```php
array CMSCategoryCore::getSubCategories(integer $id_lang, boolean $active)
```

Return current CMSCategory childs



* Visibility: **public**
* Source: [classes/CMSCategory.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L364)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



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



### <a name="method-getTranslationsFieldsChild"></a>getTranslationsFieldsChild

```php
array CMSCategoryCore::getTranslationsFieldsChild()
```

Check then return multilingual fields for database interaction



* Visibility: **public**
* Source: [classes/CMSCategory.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L111)




### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed CMSCategoryCore::getUrlRewriteInformations($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L624)


#### Arguments
* $id_category **mixed**



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



### <a name="method-hideCMSCategoryPosition"></a>hideCMSCategoryPosition

```php
string CMSCategoryCore::hideCMSCategoryPosition(string $name)
```

Hide CMSCategory prefix used for position



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L392)


#### Arguments
* $name **string** - CMSCategory name



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



### <a name="method-recurseCMSCategory"></a>recurseCMSCategory

```php
mixed CMSCategoryCore::recurseCMSCategory($categories, $current, $id_cms_category, $id_selected, $is_html)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L221)


#### Arguments
* $categories **mixed**
* $current **mixed**
* $id_cms_category **mixed**
* $id_selected **mixed**
* $is_html **mixed**



### <a name="method-recurseLiteCategTree"></a>recurseLiteCategTree

```php
array CMSCategoryCore::recurseLiteCategTree(integer $maxDepth, integer $currentDepth, $id_lang, array $excludedIdsArray, \Link $link)
```

Recursive scan of subcategories



* Visibility: **public**
* Source: [classes/CMSCategory.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L148)


#### Arguments
* $maxDepth **integer** - Maximum depth of the tree (i.e. 2 =&gt; 3 levels depth)
* $currentDepth **integer** - specify the current depth in the tree (don&#039;t use it, only for rucursivity!)
* $id_lang **mixed**
* $excludedIdsArray **array** - specify a list of ids to exclude of results
* $link **[Link](class.LinkCore.md)**



### <a name="method-recursiveDelete"></a>recursiveDelete

```php
mixed CMSCategoryCore::recursiveDelete($toDelete, array $id_cms_category)
```

Recursively add specified CMSCategory childs to $toDelete array



* Visibility: **protected**
* Source: [classes/CMSCategory.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L241)


#### Arguments
* $toDelete **mixed**
* $id_cms_category **array** - Parent CMSCategory ID



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



### <a name="method-searchByName"></a>searchByName

```php
array CMSCategoryCore::searchByName(integer $id_lang, string $query, boolean $unrestricted)
```

Light back office search for categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L502)


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
* Source: [classes/CMSCategory.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L527)


#### Arguments
* $id_lang **integer** - Language ID
* $CMSCategory_name **string** - Searched CMSCategory name
* $id_parent_CMSCategory **integer** - parent CMSCategory ID



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
mixed CMSCategoryCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L129)


#### Arguments
* $nullValues **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
mixed CMSCategoryCore::updatePosition($way, $position)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CMSCategory.php#L569)


#### Arguments
* $way **mixed**
* $position **mixed**



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


