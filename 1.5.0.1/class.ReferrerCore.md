Class ReferrerCore
=====================





* Class name: ReferrerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Referrer.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L28)


Contents
--------


### Properties

* [$_join](#property-$_join)
* [$base_fee](#property-$base_fee)
* [$click_fee](#property-$click_fee)
* [$date_add](#property-$date_add)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$http_referer_like](#property-$http_referer_like)
* [$http_referer_like_not](#property-$http_referer_like_not)
* [$http_referer_regexp](#property-$http_referer_regexp)
* [$http_referer_regexp_not](#property-$http_referer_regexp_not)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$name](#property-$name)
* [$passwd](#property-$passwd)
* [$percent_fee](#property-$percent_fee)
* [$request_uri_like](#property-$request_uri_like)
* [$request_uri_like_not](#property-$request_uri_like_not)
* [$request_uri_regexp](#property-$request_uri_regexp)
* [$request_uri_regexp_not](#property-$request_uri_regexp_not)
* [$table](#property-$table)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [cacheNewSource](#method-cacheNewSource)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getAjaxProduct](#method-getAjaxProduct)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getIdentifier](#method-getIdentifier)
* [getReferrers](#method-getReferrers)
* [getRegistrations](#method-getRegistrations)
* [getStatsSales](#method-getStatsSales)
* [getStatsVisits](#method-getStatsVisits)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [refreshCache](#method-refreshCache)
* [refreshIndex](#method-refreshIndex)
* [save](#method-save)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_join"></a>$_join

```php
protected mixed $_join = '(r.http_referer_like IS NULL OR r.http_referer_like = \'\' OR cs.http_referer LIKE r.http_referer_like)
			AND (r.request_uri_like IS NULL OR r.request_uri_like = \'\' OR cs.request_uri LIKE r.request_uri_like)
			AND (r.http_referer_like_not IS NULL OR r.http_referer_like_not = \'\' OR cs.http_referer NOT LIKE r.http_referer_like_not)
			AND (r.request_uri_like_not IS NULL OR r.request_uri_like_not = \'\' OR cs.request_uri NOT LIKE r.request_uri_like_not)
			AND (r.http_referer_regexp IS NULL OR r.http_referer_regexp = \'\' OR cs.http_referer REGEXP r.http_referer_regexp)
			AND (r.request_uri_regexp IS NULL OR r.request_uri_regexp = \'\' OR cs.request_uri REGEXP r.request_uri_regexp)
			AND (r.http_referer_regexp_not IS NULL OR r.http_referer_regexp_not = \'\' OR cs.http_referer NOT REGEXP r.http_referer_regexp_not)
			AND (r.request_uri_regexp_not IS NULL OR r.request_uri_regexp_not = \'\' OR cs.request_uri NOT REGEXP r.request_uri_regexp_not)'
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Referrer.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L79).


### <a name="property-$base_fee"></a>$base_fee

```php
public mixed $base_fee
```





* Visibility: **public**
* Source: [classes/Referrer.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L43).


### <a name="property-$click_fee"></a>$click_fee

```php
public mixed $click_fee
```





* Visibility: **public**
* Source: [classes/Referrer.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L45).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/Referrer.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L47).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('name')
```





* Visibility: **protected**
* Source: [classes/Referrer.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L49).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('name' => 64, 'http_referer_regexp' => 64, 'request_uri_regexp' => 64, 'http_referer_like' => 64, 'request_uri_like' => 64, 'passwd' => 32)
```





* Visibility: **protected**
* Source: [classes/Referrer.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L50).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('id_shop' => 'isUnsignedInt', 'name' => 'isGenericName', 'passwd' => 'isPasswd', 'http_referer_regexp' => 'isCleanHtml', 'request_uri_regexp' => 'isCleanHtml', 'http_referer_like' => 'isCleanHtml', 'request_uri_like' => 'isCleanHtml', 'http_referer_regexp_not' => 'isCleanHtml', 'request_uri_regexp_not' => 'isCleanHtml', 'http_referer_like_not' => 'isCleanHtml', 'request_uri_like_not' => 'isCleanHtml', 'base_fee' => 'isFloat', 'percent_fee' => 'isFloat', 'click_fee' => 'isFloat')
```





* Visibility: **protected**
* Source: [classes/Referrer.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L59).


### <a name="property-$http_referer_like"></a>$http_referer_like

```php
public mixed $http_referer_like
```





* Visibility: **public**
* Source: [classes/Referrer.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L35).


### <a name="property-$http_referer_like_not"></a>$http_referer_like_not

```php
public mixed $http_referer_like_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L39).


### <a name="property-$http_referer_regexp"></a>$http_referer_regexp

```php
public mixed $http_referer_regexp
```





* Visibility: **public**
* Source: [classes/Referrer.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L34).


### <a name="property-$http_referer_regexp_not"></a>$http_referer_regexp_not

```php
public mixed $http_referer_regexp_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L38).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Referrer.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L30).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_referrer'
```





* Visibility: **protected**
* Source: [classes/Referrer.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L77).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Referrer.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L31).


### <a name="property-$passwd"></a>$passwd

```php
public mixed $passwd
```





* Visibility: **public**
* Source: [classes/Referrer.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L32).


### <a name="property-$percent_fee"></a>$percent_fee

```php
public mixed $percent_fee
```





* Visibility: **public**
* Source: [classes/Referrer.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L44).


### <a name="property-$request_uri_like"></a>$request_uri_like

```php
public mixed $request_uri_like
```





* Visibility: **public**
* Source: [classes/Referrer.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L37).


### <a name="property-$request_uri_like_not"></a>$request_uri_like_not

```php
public mixed $request_uri_like_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L41).


### <a name="property-$request_uri_regexp"></a>$request_uri_regexp

```php
public mixed $request_uri_regexp
```





* Visibility: **public**
* Source: [classes/Referrer.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L36).


### <a name="property-$request_uri_regexp_not"></a>$request_uri_regexp_not

```php
public mixed $request_uri_regexp_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L40).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'referrer'
```





* Visibility: **protected**
* Source: [classes/Referrer.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L76).


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
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L115)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed ReferrerCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/Referrer.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L109)


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



### <a name="method-cacheNewSource"></a>cacheNewSource

```php
mixed ReferrerCore::cacheNewSource($id_connections_source)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L118)


#### Arguments
* $id_connections_source **mixed**



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
mixed ObjectModelCore::delete()
```

Delete current object from database

return boolean Deletion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L349)




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



### <a name="method-getAjaxProduct"></a>getAjaxProduct

```php
mixed ReferrerCore::getAjaxProduct($id_referrer, $id_product, $employee)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L350)


#### Arguments
* $id_referrer **mixed**
* $id_product **mixed**
* $employee **mixed**



### <a name="method-getFields"></a>getFields

```php
mixed ReferrerCore::getFields()
```





* Visibility: **public**
* Source: [classes/Referrer.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L88)




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




### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getReferrers"></a>getReferrers

```php
mixed ReferrerCore::getReferrers(integer $id_customer)
```

Get list of referrers connections of a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L137)


#### Arguments
* $id_customer **integer**



### <a name="method-getRegistrations"></a>getRegistrations

```php
mixed ReferrerCore::getRegistrations(integer $id_product, integer $employee, \Shop $shop)
```

Get some statistics on customers registrations for current referrer



* Visibility: **public**
* Source: [classes/Referrer.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L195)


#### Arguments
* $id_product **integer**
* $employee **integer**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getStatsSales"></a>getStatsSales

```php
mixed ReferrerCore::getStatsSales(integer $id_product, integer $employee, \Shop $shop)
```

Get some statistics on orders for current referrer



* Visibility: **public**
* Source: [classes/Referrer.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L233)


#### Arguments
* $id_product **integer**
* $employee **integer**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getStatsVisits"></a>getStatsVisits

```php
mixed ReferrerCore::getStatsVisits(integer $id_product, integer $employee, \Shop $shop)
```

Get some statistics on visitors connection for current referrer



* Visibility: **public**
* Source: [classes/Referrer.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L158)


#### Arguments
* $id_product **integer**
* $employee **integer**
* $shop **[Shop](class.ShopCore.md)**



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



### <a name="method-refreshCache"></a>refreshCache

```php
mixed ReferrerCore::refreshCache(array $referrers, integer $employee)
```

Refresh cache data of referrer statistics in referrer_shop table



* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L284)


#### Arguments
* $referrers **array**
* $employee **integer**



### <a name="method-refreshIndex"></a>refreshIndex

```php
mixed ReferrerCore::refreshIndex(array $referrers)
```

Cache liaison between connections_source data and referrers data



* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Referrer.php#L324)


#### Arguments
* $referrers **array**



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


