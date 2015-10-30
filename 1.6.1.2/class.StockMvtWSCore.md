Class StockMvtWSCore
=====================

Webservice entity for stock movements

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.

* Class name: StockMvtWSCore
* Parent class: [ObjectModelCore](class.ObjectModelCore.md)
* Source: [classes/stock/StockMvtWS.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L31)


Contents
--------

### Constants

* [FORMAT_COMMON](#constant-FORMAT_COMMON)
* [FORMAT_LANG](#constant-FORMAT_LANG)
* [FORMAT_SHOP](#constant-FORMAT_SHOP)
* [HAS_MANY](#constant-HAS_MANY)
* [HAS_ONE](#constant-HAS_ONE)
* [TYPE_BOOL](#constant-TYPE_BOOL)
* [TYPE_DATE](#constant-TYPE_DATE)
* [TYPE_FLOAT](#constant-TYPE_FLOAT)
* [TYPE_HTML](#constant-TYPE_HTML)
* [TYPE_INT](#constant-TYPE_INT)
* [TYPE_NOTHING](#constant-TYPE_NOTHING)
* [TYPE_SQL](#constant-TYPE_SQL)
* [TYPE_STRING](#constant-TYPE_STRING)

### Properties

* [$cache_objects](#property-$cache_objects)
* [$current_wa](#property-$current_wa)
* [$date_add](#property-$date_add)
* [$db](#property-$db)
* [$def](#property-$def)
* [$definition](#property-$definition)
* [$ean13](#property-$ean13)
* [$employee_firstname](#property-$employee_firstname)
* [$employee_lastname](#property-$employee_lastname)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$force_id](#property-$force_id)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id](#property-$id)
* [$id_currency](#property-$id_currency)
* [$id_employee](#property-$id_employee)
* [$id_lang](#property-$id_lang)
* [$id_order](#property-$id_order)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$id_stock](#property-$id_stock)
* [$id_stock_mvt_reason](#property-$id_stock_mvt_reason)
* [$id_supply_order](#property-$id_supply_order)
* [$id_warehouse](#property-$id_warehouse)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$last_wa](#property-$last_wa)
* [$loaded_classes](#property-$loaded_classes)
* [$management_type](#property-$management_type)
* [$physical_quantity](#property-$physical_quantity)
* [$price_te](#property-$price_te)
* [$product_name](#property-$product_name)
* [$reference](#property-$reference)
* [$referer](#property-$referer)
* [$sign](#property-$sign)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$tables_assoc](#property-$tables_assoc)
* [$upc](#property-$upc)
* [$update_fields](#property-$update_fields)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [enableCache](#method-enableCache)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWSProductName](#method-getWSProductName)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)


Constants
----------


### <a name="constant-FORMAT_COMMON"></a>FORMAT_COMMON

```php
const FORMAT_COMMON = 1
```

List of data to format



* Source: [classes/stock/StockMvtWS.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L44).


### <a name="constant-FORMAT_LANG"></a>FORMAT_LANG

```php
const FORMAT_LANG = 2
```





* Source: [classes/stock/StockMvtWS.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L45).


### <a name="constant-FORMAT_SHOP"></a>FORMAT_SHOP

```php
const FORMAT_SHOP = 3
```





* Source: [classes/stock/StockMvtWS.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L46).


### <a name="constant-HAS_MANY"></a>HAS_MANY

```php
const HAS_MANY = 2
```





* Source: [classes/stock/StockMvtWS.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L52).


### <a name="constant-HAS_ONE"></a>HAS_ONE

```php
const HAS_ONE = 1
```

List of association types



* Source: [classes/stock/StockMvtWS.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L51).


### <a name="constant-TYPE_BOOL"></a>TYPE_BOOL

```php
const TYPE_BOOL = 2
```





* Source: [classes/stock/StockMvtWS.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L33).


### <a name="constant-TYPE_DATE"></a>TYPE_DATE

```php
const TYPE_DATE = 5
```





* Source: [classes/stock/StockMvtWS.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L36).


### <a name="constant-TYPE_FLOAT"></a>TYPE_FLOAT

```php
const TYPE_FLOAT = 4
```





* Source: [classes/stock/StockMvtWS.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L35).


### <a name="constant-TYPE_HTML"></a>TYPE_HTML

```php
const TYPE_HTML = 6
```





* Source: [classes/stock/StockMvtWS.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L37).


### <a name="constant-TYPE_INT"></a>TYPE_INT

```php
const TYPE_INT = 1
```

List of field types



* Source: [classes/stock/StockMvtWS.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L32).


### <a name="constant-TYPE_NOTHING"></a>TYPE_NOTHING

```php
const TYPE_NOTHING = 7
```





* Source: [classes/stock/StockMvtWS.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L38).


### <a name="constant-TYPE_SQL"></a>TYPE_SQL

```php
const TYPE_SQL = 8
```





* Source: [classes/stock/StockMvtWS.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L39).


### <a name="constant-TYPE_STRING"></a>TYPE_STRING

```php
const TYPE_STRING = 3
```





* Source: [classes/stock/StockMvtWS.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L34).


Properties
----------


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/stock/StockMvtWS.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L164).


### <a name="property-$current_wa"></a>$current_wa

```php
public float $current_wa = null
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L93).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L38).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/stock/StockMvtWS.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L150).


### <a name="property-$definition"></a>$definition

```php
public array $definition = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/StockMvtWS.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L139).


### <a name="property-$ean13"></a>$ean13

```php
public string $ean13
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L138).


### <a name="property-$employee_firstname"></a>$employee_firstname

```php
public string $employee_firstname
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L48).


### <a name="property-$employee_lastname"></a>$employee_lastname

```php
public string $employee_lastname
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L53).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected array $fieldsRequired = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L88).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected array $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/stock/StockMvtWS.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L70).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L106).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L94).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L112).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected array $fieldsValidate = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L100).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L118).


### <a name="property-$force_id"></a>$force_id

```php
public boolean $force_id = false
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L159).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected boolean $get_shop_from_context = true
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L67).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L55).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L123).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L43).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L58).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order = null
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L73).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L108).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L113).


### <a name="property-$id_shop"></a>$id_shop

```php
protected integer $id_shop = null
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L61).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public array $id_shop_list = null
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L64).


### <a name="property-$id_stock"></a>$id_stock

```php
public integer $id_stock
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L58).


### <a name="property-$id_stock_mvt_reason"></a>$id_stock_mvt_reason

```php
public integer $id_stock_mvt_reason
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L68).


### <a name="property-$id_supply_order"></a>$id_supply_order

```php
public integer $id_supply_order = null
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L83).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L118).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L82).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L130).


### <a name="property-$image_format"></a>$image_format

```php
protected String $image_format = 'jpg'
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L133).


### <a name="property-$last_wa"></a>$last_wa

```php
public float $last_wa = null
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L88).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected array $loaded_classes = array()
```

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* Source: [classes/stock/StockMvtWS.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L147).


### <a name="property-$management_type"></a>$management_type

```php
public string $management_type
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L128).


### <a name="property-$physical_quantity"></a>$physical_quantity

```php
public integer $physical_quantity
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L63).


### <a name="property-$price_te"></a>$price_te

```php
public float $price_te
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L98).


### <a name="property-$product_name"></a>$product_name

```php
public mixed $product_name
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L133).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L148).


### <a name="property-$referer"></a>$referer

```php
public integer $referer
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L103).


### <a name="property-$sign"></a>$sign

```php
public integer $sign
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L78).


### <a name="property-$table"></a>$table

```php
protected string $table
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L76).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L124).


### <a name="property-$tables_assoc"></a>$tables_assoc

```php
protected Array $tables_assoc = array('id_product' => array('table' => 's'), 'id_product_attribute' => array('table' => 's'), 'id_warehouse' => array('table' => 's'), 'id_currency' => array('table' => 's'), 'management_type' => array('table' => 'w'), 'ean13' => array('table' => 's'), 'upc' => array('table' => 's'), 'reference' => array('table' => 's'))
```

Associations tables for attributes that require different tables than stated in ObjectModel::definition



* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L205).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L143).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L153).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L127).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed StockMvtWSCore::__construct(integer|null $id, integer|null $id_lang, integer|null $id_shop)
```

Builds the object



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L201)


#### Arguments
* $id **integer|null** - If specified, loads and existing object from DB (optional).
* $id_lang **integer|null** - Required if object is multilingual (optional).
* $id_shop **integer|null** - ID shop for objects with multishop tables.



### <a name="method-add"></a>add

```php
boolean StockMvtWSCore::add(boolean $auto_date, boolean $null_values)
```

Adds current object to the database



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L458)


#### Arguments
* $auto_date **boolean**
* $null_values **boolean**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
boolean StockMvtWSCore::addFieldsRequiredDatabase(array $fields)
```

Sets required field for this class in the database.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1390)


#### Arguments
* $fields **array**



### <a name="method-associateTo"></a>associateTo

```php
boolean|void StockMvtWSCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1464)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed StockMvtWSCore::cacheFieldsRequiredDatabase(boolean $all)
```

Caches data about required objects fields in memory



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1368)


#### Arguments
* $all **boolean** - If true, caches required fields of all object classes.



### <a name="method-clearCache"></a>clearCache

```php
mixed StockMvtWSCore::clearCache(boolean $all)
```

Clears cache entries that have this object's ID.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1414)


#### Arguments
* $all **boolean** - If true, clears cache for all objects



### <a name="method-delete"></a>delete

```php
boolean StockMvtWSCore::delete()
```

Deletes current object from database



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L743)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean StockMvtWSCore::deleteImage(boolean $force_delete)
```

Delete images associated with the object



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1643)


#### Arguments
* $force_delete **boolean**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean StockMvtWSCore::deleteSelection(array $ids)
```

Deletes multiple objects from the database at once



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L790)


#### Arguments
* $ids **array** - Array of objects IDs.



### <a name="method-disableCache"></a>disableCache

```php
mixed StockMvtWSCore::disableCache()
```

Disables object caching



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1969)




### <a name="method-displayFieldName"></a>displayFieldName

```php
string StockMvtWSCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)
```

Returns field name translation



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1083)


#### Arguments
* $field **string** - Field name
* $class **string** - ObjectModel class name
* $htmlentities **boolean** - If true, applies htmlentities() to result string
* $context **[Context](class.ContextCore.md)|null** - Context object



### <a name="method-duplicateObject"></a>duplicateObject

```php
\ObjectModel|false StockMvtWSCore::duplicateObject()
```

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L549)




### <a name="method-duplicateShops"></a>duplicateShops

```php
boolean|void StockMvtWSCore::duplicateShops($id)
```

Copies shop association data from object with specified ID.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1523)


#### Arguments
* $id **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed StockMvtWSCore::enableCache()
```

Enables object caching



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1961)




### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean StockMvtWSCore::existsInDatabase(integer $id_entity, string $table)
```

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1686)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array StockMvtWSCore::formatFields(integer $type, integer $id_lang)
```

Formats values of each fields.



* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L327)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed StockMvtWSCore::formatValue(mixed $value, integer $type, boolean $with_quotes, boolean $purify, boolean $allow_null)
```

Formats a value



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array StockMvtWSCore::getAssociatedShops()
```

Gets the list of associated shop IDs



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1499)




### <a name="method-getDefinition"></a>getDefinition

```php
array StockMvtWSCore::getDefinition(string $class, string|null $field)
```

Returns object definition



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1809)


#### Arguments
* $class **string** - Name of object
* $field **string|null** - Name of field if we want the definition of one field only



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed StockMvtWSCore::getFieldByLang(string $field_name, integer|null $id_lang)
```

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1927)


#### Arguments
* $field_name **string**
* $id_lang **integer|null**



### <a name="method-getFields"></a>getFields

```php
array StockMvtWSCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval, .

..)

* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L244)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array StockMvtWSCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L288)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
array|null StockMvtWSCore::getFieldsRequiredDatabase(boolean $all)
```

Returns an array of required fields



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1355)


#### Arguments
* $all **boolean** - If true, returns required fields of all object classes.



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array StockMvtWSCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we consider they are already validated in getFields() method,
this is not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L270)




### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

```php
mixed StockMvtWSCore::getRepositoryClassName()
```

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L166)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array StockMvtWSCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L831)


#### Arguments
* $fields_array **array**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array StockMvtWSCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L178)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWSProductName"></a>getWSProductName

```php
mixed StockMvtWSCore::getWSProductName()
```

Webservice : getter for the product name



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L286)




### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
array|null StockMvtWSCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)
```

Returns webservice object list.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1279)


#### Arguments
* $sql_join **string**
* $sql_filter **string**
* $sql_sort **string**
* $sql_limit **string**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
array StockMvtWSCore::getWebserviceParameters(string|null $ws_params_attribute_name)
```

Returns webservice parameters of this object.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1176)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean StockMvtWSCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1550)




### <a name="method-hydrate"></a>hydrate

```php
mixed StockMvtWSCore::hydrate(array $data, integer|null $id_lang)
```

Fill an object with given data. Data must be an array with this syntax:
array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1730)


#### Arguments
* $data **array**
* $id_lang **integer|null**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array StockMvtWSCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1755)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer|null**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean StockMvtWSCore::isAssociatedToShop(integer|null $id_shop)
```

Checks if current object is associated to a shop.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1430)


#### Arguments
* $id_shop **integer|null**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean StockMvtWSCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)
```

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1706)


#### Arguments
* $table **string|null** - Name of table linked to entity
* $has_active_column **boolean** - True if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
boolean StockMvtWSCore::isLangMultishop()
```

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1586)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
boolean StockMvtWSCore::isMultiShopField(string $field)
```

Checks if a field is a multi-shop field.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1576)


#### Arguments
* $field **string**



### <a name="method-isMultishop"></a>isMultishop

```php
boolean StockMvtWSCore::isMultishop()
```

Checks if object is multi-shop object.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1564)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed StockMvtWSCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L854)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-save"></a>save

```php
boolean StockMvtWSCore::save(boolean $null_values, boolean $auto_date)
```

Saves current object to database (add or update)



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L443)


#### Arguments
* $null_values **boolean**
* $auto_date **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed StockMvtWSCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* Source: [classes/stock/StockMvtWS.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1855)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed StockMvtWSCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1953](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1953)


#### Arguments
* $fields **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean StockMvtWSCore::toggleStatus()
```

Toggles object status in database



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L807)




### <a name="method-update"></a>update

```php
boolean StockMvtWSCore::update(boolean $null_values)
```

Updates the current object in the database



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L619)


#### Arguments
* $null_values **boolean**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean StockMvtWSCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtWS.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1602)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-validateControler"></a>validateControler

```php
array StockMvtWSCore::validateControler(boolean $htmlentities)
```





* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1105)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

```php
array StockMvtWSCore::validateController(boolean $htmlentities)
```

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1118)


#### Arguments
* $htmlentities **boolean** - If true, uses htmlentities() for field name translations in errors.



### <a name="method-validateField"></a>validateField

```php
true|string StockMvtWSCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)
```

Validate a single field



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L977)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer|null** - Language ID
* $skip **array** - Array of fields to skip.
* $human_errors **boolean** - If true, uses more descriptive, translatable error strings.



### <a name="method-validateFields"></a>validateFields

```php
boolean|string StockMvtWSCore::validateFields(boolean $die, boolean $error_return)
```

Checks if object field values are valid before database interaction



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L895)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string StockMvtWSCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Checks if multilingual object field values are valid before database interaction.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L927)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
array StockMvtWSCore::validateFieldsRequiredDatabase(boolean $htmlentities)
```

Validate required fields.



* Visibility: **public**
* Source: [classes/stock/StockMvtWS.php line 1322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/stock/StockMvtWS.php#L1322)


#### Arguments
* $htmlentities **boolean**


