Class CurrencyCore
=====================





* Class name: CurrencyCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Currency.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$blank](#property-$blank)
* [$conversion_rate](#property-$conversion_rate)
* [$currencies](#property-$currencies)
* [$decimals](#property-$decimals)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$format](#property-$format)
* [$id](#property-$id)
* [$iso_code](#property-$iso_code)
* [$iso_code_num](#property-$iso_code_num)
* [$name](#property-$name)
* [$prefix](#property-$prefix)
* [$sign](#property-$sign)
* [$suffix](#property-$suffix)
* [$webserviceParameters](#property-$webserviceParameters)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [checkPaymentCurrencies](#method-checkPaymentCurrencies)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [exists](#method-exists)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getCurrencies](#method-getCurrencies)
* [getCurrenciesByIdShop](#method-getCurrenciesByIdShop)
* [getCurrency](#method-getCurrency)
* [getCurrencyInstance](#method-getCurrencyInstance)
* [getCurrent](#method-getCurrent)
* [getDefaultCurrency](#method-getDefaultCurrency)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getIdByIsoCode](#method-getIdByIsoCode)
* [getIdByIsoCodeNum](#method-getIdByIsoCodeNum)
* [getIdByQuery](#method-getIdByQuery)
* [getPaymentCurrencies](#method-getPaymentCurrencies)
* [getPaymentCurrenciesSpecial](#method-getPaymentCurrenciesSpecial)
* [getSign](#method-getSign)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [refreshCurrencies](#method-refreshCurrencies)
* [refreshCurrency](#method-refreshCurrency)
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




Properties
----------


### <a name="property-$active"></a>$active

```php
public integer $active
```





* Visibility: **public**
* Source: [classes/Currency.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L59).


### <a name="property-$blank"></a>$blank

```php
public integer $blank
```





* Visibility: **public**
* Source: [classes/Currency.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L44).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public string $conversion_rate
```





* Visibility: **public**
* Source: [classes/Currency.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L47).


### <a name="property-$currencies"></a>$currencies

```php
protected array $currencies = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Currency.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L83).


### <a name="property-$decimals"></a>$decimals

```php
public integer $decimals
```





* Visibility: **public**
* Source: [classes/Currency.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L56).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'currency', 'primary' => 'id_currency', 'multilang_shop' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'iso_code_num' => array('type' => self::TYPE_STRING, 'validate' => 'isNumericIsoCode', 'size' => 3), 'blank' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sign' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 8), 'format' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'decimals' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true, 'shop' => true), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Currency.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L64).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Currency.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L50).


### <a name="property-$format"></a>$format

```php
public integer $format
```





* Visibility: **public**
* Source: [classes/Currency.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L53).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Currency.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L29).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/Currency.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L35).


### <a name="property-$iso_code_num"></a>$iso_code_num

```php
public string $iso_code_num
```





* Visibility: **public**
* Source: [classes/Currency.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L38).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Currency.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L32).


### <a name="property-$prefix"></a>$prefix

```php
public string $prefix = null
```

contains the sign to display before price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L93).


### <a name="property-$sign"></a>$sign

```php
public string $sign
```





* Visibility: **public**
* Source: [classes/Currency.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L41).


### <a name="property-$suffix"></a>$suffix

```php
public string $suffix = null
```

contains the sign to display after price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L98).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'currencies')
```





* Visibility: **protected**
* Source: [classes/Currency.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L85).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L130).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L80).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L65).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L95).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L85).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L90).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L105).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L63).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L57).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L59).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L61).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L75).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L116).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L119).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L70).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L110).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L135).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CurrencyCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Currency.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L100)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed CurrencyCore::add($autodate, $nullValues)
```

Overriding check if currency with the same iso code already exists.

If it's true, currency is doesn't added.

* Visibility: **public**
* Source: [classes/Currency.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L114)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1144)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1191](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1191)


#### Arguments
* $id_shops **integer|array**



### <a name="method-checkPaymentCurrencies"></a>checkPaymentCurrencies

```php
mixed CurrencyCore::checkPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L256)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1158](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1158)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed CurrencyCore::delete()
```





* Visibility: **public**
* Source: [classes/Currency.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L155)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1317](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1317)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed CurrencyCore::deleteSelection($selection)
```





* Visibility: **public**
* Source: [classes/Currency.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L138)


#### Arguments
* $selection **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 937](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L937)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\new ObjectModelCore::duplicateObject()
```

Duplicate current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L527)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1235](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1235)


#### Arguments
* $id **mixed**



### <a name="method-exists"></a>exists

```php
boolean CurrencyCore::exists(integer|string $iso_code, $iso_code_num, $id_shop)
```

Check if a curency already exists.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L125)


#### Arguments
* $iso_code **integer|string** - int for iso code number string for iso code
* $iso_code_num **mixed**
* $id_shop **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1354](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1354)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L334)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L380)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1220](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1220)




### <a name="method-getCurrencies"></a>getCurrencies

```php
array CurrencyCore::getCurrencies($object, $active)
```

Return available currencies



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L199)


#### Arguments
* $object **mixed**
* $active **mixed**



### <a name="method-getCurrenciesByIdShop"></a>getCurrenciesByIdShop

```php
mixed CurrencyCore::getCurrenciesByIdShop($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L215)


#### Arguments
* $id_shop **mixed**



### <a name="method-getCurrency"></a>getCurrency

```php
mixed CurrencyCore::getCurrency($id_currency)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L271)


#### Arguments
* $id_currency **mixed**



### <a name="method-getCurrencyInstance"></a>getCurrencyInstance

```php
mixed CurrencyCore::getCurrencyInstance($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L411)


#### Arguments
* $id **mixed**



### <a name="method-getCurrent"></a>getCurrent

```php
\Currency CurrencyCore::getCurrent()
```

Get current currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L405)




### <a name="method-getDefaultCurrency"></a>getDefaultCurrency

```php
mixed CurrencyCore::getDefaultCurrency()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L372)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1460](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1460)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1548](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1548)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L262)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L299)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1136](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1136)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ObjectModelCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we considere they are already validated in getFields() method, this
not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L285)




### <a name="method-getIdByIsoCode"></a>getIdByIsoCode

```php
integer CurrencyCore::getIdByIsoCode($iso_code, integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L286)


#### Arguments
* $iso_code **mixed**
* $id_shop **integer**



### <a name="method-getIdByIsoCodeNum"></a>getIdByIsoCodeNum

```php
integer CurrencyCore::getIdByIsoCodeNum($iso_code_num, integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L300)


#### Arguments
* $iso_code_num **mixed**
* $id_shop **integer**



### <a name="method-getIdByQuery"></a>getIdByQuery

```php
\DbQuery CurrencyCore::getIdByQuery(integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L313)


#### Arguments
* $id_shop **integer**



### <a name="method-getPaymentCurrencies"></a>getPaymentCurrencies

```php
mixed CurrencyCore::getPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L240)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getPaymentCurrenciesSpecial"></a>getPaymentCurrenciesSpecial

```php
mixed CurrencyCore::getPaymentCurrenciesSpecial($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L228)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getSign"></a>getSign

```php
string CurrencyCore::getSign(string $side)
```

Return formated sign



* Visibility: **public**
* Source: [classes/Currency.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L174)


#### Arguments
* $side **string** - left or right



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L769)


#### Arguments
* $fields_array **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L148)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1078](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1078)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($ws_params_attribute_name)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1004](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1004)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1260](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1260)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1392](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1392)


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
* Source: [classes/ObjectModel.php line 1411](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1411)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1173)


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
* Source: [classes/ObjectModel.php line 1372](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1372)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1272](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1272)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1267](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1267)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L785)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-refreshCurrencies"></a>refreshCurrencies

```php
mixed CurrencyCore::refreshCurrencies()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L381)




### <a name="method-refreshCurrency"></a>refreshCurrency

```php
mixed CurrencyCore::refreshCurrency($data, $isoCodeSource, $defaultCurrency)
```

Refresh the currency conversion rate
The XML file define conversion rate for each from a default currency ($isoCodeSource).



* Visibility: **public**
* Source: [classes/Currency.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/Currency.php#L336)


#### Arguments
* $data **mixed** - XML content which contains all the conversion rates
* $isoCodeSource **mixed** - The default currency used in the XML file
* $defaultCurrency **mixed** - The default currency object



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L424)


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
* Source: [classes/ObjectModel.php line 1488](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1488)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1574](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1574)


#### Arguments
* $fields **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L753)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L576)


#### Arguments
* $null_values **boolean**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1287](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1287)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 952](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L952)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L958)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L890)


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
* Source: [classes/ObjectModel.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L823)


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
* Source: [classes/ObjectModel.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L852)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1114](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/ObjectModel.php#L1114)


#### Arguments
* $htmlentities **mixed**


