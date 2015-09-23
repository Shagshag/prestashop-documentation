Class CurrencyCore
=====================





* Class name: CurrencyCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Currency.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L28)


Contents
--------


### Properties

* [$active](#property-$active)
* [$blank](#property-$blank)
* [$conversion_rate](#property-$conversion_rate)
* [$currencies](#property-$currencies)
* [$decimals](#property-$decimals)
* [$deleted](#property-$deleted)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$format](#property-$format)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$iso_code](#property-$iso_code)
* [$iso_code_num](#property-$iso_code_num)
* [$name](#property-$name)
* [$prefix](#property-$prefix)
* [$sign](#property-$sign)
* [$suffix](#property-$suffix)
* [$table](#property-$table)
* [$webserviceParameters](#property-$webserviceParameters)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
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
* [associateTo](#method-associateTo)
* [checkPaymentCurrencies](#method-checkPaymentCurrencies)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [exists](#method-exists)
* [existsInDatabase](#method-existsInDatabase)
* [getCurrencies](#method-getCurrencies)
* [getCurrency](#method-getCurrency)
* [getCurrencyInstance](#method-getCurrencyInstance)
* [getCurrent](#method-getCurrent)
* [getDefaultCurrency](#method-getDefaultCurrency)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getIdByIsoCode](#method-getIdByIsoCode)
* [getIdByIsoCodeNum](#method-getIdByIsoCodeNum)
* [getIdentifier](#method-getIdentifier)
* [getPaymentCurrencies](#method-getPaymentCurrencies)
* [getPaymentCurrenciesSpecial](#method-getPaymentCurrenciesSpecial)
* [getSign](#method-getSign)
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
* [refreshCurrencies](#method-refreshCurrencies)
* [refreshCurrency](#method-refreshCurrency)
* [save](#method-save)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$active"></a>$active

```php
public integer $active
```





* Visibility: **public**
* Source: [classes/Currency.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L60).


### <a name="property-$blank"></a>$blank

```php
public integer $blank
```





* Visibility: **public**
* Source: [classes/Currency.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L45).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public string $conversion_rate
```





* Visibility: **public**
* Source: [classes/Currency.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L48).


### <a name="property-$currencies"></a>$currencies

```php
protected array $currencies = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Currency.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L71).


### <a name="property-$decimals"></a>$decimals

```php
public integer $decimals
```





* Visibility: **public**
* Source: [classes/Currency.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L57).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Currency.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L51).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('name', 'iso_code', 'sign', 'conversion_rate', 'format', 'decimals')
```





* Visibility: **protected**
* Source: [classes/Currency.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L62).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('name' => 32, 'iso_code' => 3, 'iso_code_num' => 3, 'sign' => 8)
```





* Visibility: **protected**
* Source: [classes/Currency.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L63).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('name' => 'isGenericName', 'iso_code' => 'isLanguageIsoCode', 'iso_code_num' => 'isNumericIsoCode', 'blank' => 'isInt', 'sign' => 'isGenericName', 'format' => 'isUnsignedId', 'decimals' => 'isBool', 'conversion_rate' => 'isFloat', 'deleted' => 'isBool', 'active' => 'isBool')
```





* Visibility: **protected**
* Source: [classes/Currency.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L64).


### <a name="property-$format"></a>$format

```php
public integer $format
```





* Visibility: **public**
* Source: [classes/Currency.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L54).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Currency.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L30).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_currency'
```





* Visibility: **protected**
* Source: [classes/Currency.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L68).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/Currency.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L36).


### <a name="property-$iso_code_num"></a>$iso_code_num

```php
public string $iso_code_num
```





* Visibility: **public**
* Source: [classes/Currency.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L39).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Currency.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L33).


### <a name="property-$prefix"></a>$prefix

```php
public string $prefix = null
```

contains the sign to display before price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L81).


### <a name="property-$sign"></a>$sign

```php
public string $sign
```





* Visibility: **public**
* Source: [classes/Currency.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L42).


### <a name="property-$suffix"></a>$suffix

```php
public string $suffix = null
```

contains the sign to display after price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L86).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'currency'
```





* Visibility: **protected**
* Source: [classes/Currency.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L67).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'currencies')
```





* Visibility: **protected**
* Source: [classes/Currency.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L73).


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
mixed CurrencyCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Currency.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L88)


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
* Source: [classes/Currency.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L103)


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



### <a name="method-checkPaymentCurrencies"></a>checkPaymentCurrencies

```php
mixed CurrencyCore::checkPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L247)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



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
mixed CurrencyCore::delete()
```





* Visibility: **public**
* Source: [classes/Currency.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L160)




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
mixed CurrencyCore::deleteSelection($selection)
```





* Visibility: **public**
* Source: [classes/Currency.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L145)


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



### <a name="method-exists"></a>exists

```php
boolean CurrencyCore::exists(integer|string $iso_code)
```

Check if a curency already exists.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L114)


#### Arguments
* $iso_code **integer|string** - int for iso code number string for iso code



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



### <a name="method-getCurrencies"></a>getCurrencies

```php
array CurrencyCore::getCurrencies($object, $active, \Shop $shop)
```

Return available currencies



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L201)


#### Arguments
* $object **mixed**
* $active **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getCurrency"></a>getCurrency

```php
mixed CurrencyCore::getCurrency($id_currency)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L259)


#### Arguments
* $id_currency **mixed**



### <a name="method-getCurrencyInstance"></a>getCurrencyInstance

```php
mixed CurrencyCore::getCurrencyInstance($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L370)


#### Arguments
* $id **mixed**



### <a name="method-getCurrent"></a>getCurrent

```php
\Currency CurrencyCore::getCurrent()
```

Get current currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L364)




### <a name="method-getDefaultCurrency"></a>getDefaultCurrency

```php
mixed CurrencyCore::getDefaultCurrency()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L331)




### <a name="method-getFields"></a>getFields

```php
mixed CurrencyCore::getFields()
```





* Visibility: **public**
* Source: [classes/Currency.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L127)




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




### <a name="method-getIdByIsoCode"></a>getIdByIsoCode

```php
mixed CurrencyCore::getIdByIsoCode($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L268)


#### Arguments
* $iso_code **mixed**



### <a name="method-getIdByIsoCodeNum"></a>getIdByIsoCodeNum

```php
mixed CurrencyCore::getIdByIsoCodeNum($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L278)


#### Arguments
* $iso_code **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getPaymentCurrencies"></a>getPaymentCurrencies

```php
mixed CurrencyCore::getPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L231)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getPaymentCurrenciesSpecial"></a>getPaymentCurrenciesSpecial

```php
mixed CurrencyCore::getPaymentCurrenciesSpecial($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L219)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getSign"></a>getSign

```php
string CurrencyCore::getSign(string $side)
```

Return formated sign



* Visibility: **public**
* Source: [classes/Currency.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L179)


#### Arguments
* $side **string** - left or right



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



### <a name="method-refreshCurrencies"></a>refreshCurrencies

```php
mixed CurrencyCore::refreshCurrencies()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L340)




### <a name="method-refreshCurrency"></a>refreshCurrency

```php
mixed CurrencyCore::refreshCurrency($data, $isoCodeSource, $defaultCurrency)
```

Refresh the currency conversion rate
The XML file define conversion rate for each from a default currency ($isoCodeSource).



* Visibility: **public**
* Source: [classes/Currency.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Currency.php#L296)


#### Arguments
* $data **mixed** - XML content which contains all the conversion rates
* $isoCodeSource **mixed** - The default currency used in the XML file
* $defaultCurrency **mixed** - The default currency object



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


