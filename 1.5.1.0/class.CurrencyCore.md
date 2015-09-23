Class CurrencyCore
=====================





* Class name: CurrencyCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Currency.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L28)


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
* Source: [classes/Currency.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L60).


### <a name="property-$blank"></a>$blank

```php
public integer $blank
```





* Visibility: **public**
* Source: [classes/Currency.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L45).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public string $conversion_rate
```





* Visibility: **public**
* Source: [classes/Currency.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L48).


### <a name="property-$currencies"></a>$currencies

```php
protected array $currencies = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Currency.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L84).


### <a name="property-$decimals"></a>$decimals

```php
public integer $decimals
```





* Visibility: **public**
* Source: [classes/Currency.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L57).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'currency', 'primary' => 'id_currency', 'multilang_shop' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'iso_code_num' => array('type' => self::TYPE_STRING, 'validate' => 'isNumericIsoCode', 'size' => 3), 'blank' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sign' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 8), 'format' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'decimals' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Currency.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L65).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Currency.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L51).


### <a name="property-$format"></a>$format

```php
public integer $format
```





* Visibility: **public**
* Source: [classes/Currency.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L54).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Currency.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L30).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/Currency.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L36).


### <a name="property-$iso_code_num"></a>$iso_code_num

```php
public string $iso_code_num
```





* Visibility: **public**
* Source: [classes/Currency.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L39).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Currency.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L33).


### <a name="property-$prefix"></a>$prefix

```php
public string $prefix = null
```

contains the sign to display before price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L94).


### <a name="property-$sign"></a>$sign

```php
public string $sign
```





* Visibility: **public**
* Source: [classes/Currency.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L42).


### <a name="property-$suffix"></a>$suffix

```php
public string $suffix = null
```

contains the sign to display after price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L99).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'currencies')
```





* Visibility: **protected**
* Source: [classes/Currency.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L86).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L141).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L131).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L106).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L64).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L60).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L117).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L120).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L136).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CurrencyCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Currency.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L101)


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
* Source: [classes/Currency.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L115)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1097](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1097)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1144)


#### Arguments
* $id_shops **integer|array**



### <a name="method-checkPaymentCurrencies"></a>checkPaymentCurrencies

```php
mixed CurrencyCore::checkPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L257)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1111](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1111)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed CurrencyCore::delete()
```





* Visibility: **public**
* Source: [classes/Currency.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L156)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1270](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1270)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed CurrencyCore::deleteSelection($selection)
```





* Visibility: **public**
* Source: [classes/Currency.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L139)


#### Arguments
* $selection **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L890)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1188](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1188)


#### Arguments
* $id **mixed**



### <a name="method-exists"></a>exists

```php
boolean CurrencyCore::exists(integer|string $iso_code, $iso_code_num, $id_shop)
```

Check if a curency already exists.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L126)


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
* Source: [classes/ObjectModel.php line 1307](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1307)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L335)


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
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L381)


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
* Source: [classes/ObjectModel.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1173)




### <a name="method-getCurrencies"></a>getCurrencies

```php
array CurrencyCore::getCurrencies($object, $active)
```

Return available currencies



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L200)


#### Arguments
* $object **mixed**
* $active **mixed**



### <a name="method-getCurrenciesByIdShop"></a>getCurrenciesByIdShop

```php
mixed CurrencyCore::getCurrenciesByIdShop($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L216)


#### Arguments
* $id_shop **mixed**



### <a name="method-getCurrency"></a>getCurrency

```php
mixed CurrencyCore::getCurrency($id_currency)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L272)


#### Arguments
* $id_currency **mixed**



### <a name="method-getCurrencyInstance"></a>getCurrencyInstance

```php
mixed CurrencyCore::getCurrencyInstance($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L411)


#### Arguments
* $id **mixed**



### <a name="method-getCurrent"></a>getCurrent

```php
\Currency CurrencyCore::getCurrent()
```

Get current currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L405)




### <a name="method-getDefaultCurrency"></a>getDefaultCurrency

```php
mixed CurrencyCore::getDefaultCurrency()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L372)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1413](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1413)


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
* Source: [classes/ObjectModel.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1490)


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
* Source: [classes/ObjectModel.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L263)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L300)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1089)


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
* Source: [classes/ObjectModel.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L286)




### <a name="method-getIdByIsoCode"></a>getIdByIsoCode

```php
integer CurrencyCore::getIdByIsoCode($iso_code, integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L287)


#### Arguments
* $iso_code **mixed**
* $id_shop **integer**



### <a name="method-getIdByIsoCodeNum"></a>getIdByIsoCodeNum

```php
integer CurrencyCore::getIdByIsoCodeNum($iso_code_num, integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L301)


#### Arguments
* $iso_code_num **mixed**
* $id_shop **integer**



### <a name="method-getIdByQuery"></a>getIdByQuery

```php
\DbQuery CurrencyCore::getIdByQuery(integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L314)


#### Arguments
* $id_shop **integer**



### <a name="method-getPaymentCurrencies"></a>getPaymentCurrencies

```php
mixed CurrencyCore::getPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L241)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getPaymentCurrenciesSpecial"></a>getPaymentCurrenciesSpecial

```php
mixed CurrencyCore::getPaymentCurrenciesSpecial($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L229)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getSign"></a>getSign

```php
string CurrencyCore::getSign(string $side)
```

Return formated sign



* Visibility: **public**
* Source: [classes/Currency.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L175)


#### Arguments
* $side **string** - left or right



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L722)


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
* Source: [classes/ObjectModel.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L149)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1031](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1031)


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
* Source: [classes/ObjectModel.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L957)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1213](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1213)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1345](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1345)


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
* Source: [classes/ObjectModel.php line 1364](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1364)


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
* Source: [classes/ObjectModel.php line 1126](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1126)


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
* Source: [classes/ObjectModel.php line 1325](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1325)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1225](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1225)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1220](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1220)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L738)


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
* Source: [classes/Currency.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L381)




### <a name="method-refreshCurrency"></a>refreshCurrency

```php
mixed CurrencyCore::refreshCurrency($data, $isoCodeSource, $defaultCurrency)
```

Refresh the currency conversion rate
The XML file define conversion rate for each from a default currency ($isoCodeSource).



* Visibility: **public**
* Source: [classes/Currency.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Currency.php#L337)


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
* Source: [classes/ObjectModel.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L425)


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
* Source: [classes/ObjectModel.php line 1436](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1436)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1516](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1516)


#### Arguments
* $fields **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 706](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L706)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L529)


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
* Source: [classes/ObjectModel.php line 1240](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1240)


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
* Source: [classes/ObjectModel.php line 905](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L905)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L911)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L843)


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
* Source: [classes/ObjectModel.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L776)


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
* Source: [classes/ObjectModel.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L805)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1067](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1067)


#### Arguments
* $htmlentities **mixed**


