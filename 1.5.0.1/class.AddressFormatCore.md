Class AddressFormatCore
=====================





* Class name: AddressFormatCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/AddressFormat.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L28)


Contents
--------

### Constants

* [_CLEANING_REGEX_](#constant-_CLEANING_REGEX_)

### Properties

* [$_errorFormatList](#property-$_errorFormatList)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsValidate](#property-$fieldsValidate)
* [$forbiddenClassList](#property-$forbiddenClassList)
* [$forbiddenPropertyList](#property-$forbiddenPropertyList)
* [$format](#property-$format)
* [$id_address_format](#property-$id_address_format)
* [$id_country](#property-$id_country)
* [$identifier](#property-$identifier)
* [$requireFormFieldsList](#property-$requireFormFieldsList)
* [$table](#property-$table)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [_checkLiableAssociation](#method-_checkLiableAssociation)
* [_checkValidateClassField](#method-_checkValidateClassField)
* [_getFormatDB](#method-_getFormatDB)
* [_setOriginalDisplayFormat](#method-_setOriginalDisplayFormat)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [checkFormatFields](#method-checkFormatFields)
* [cleanOrderedAddress](#method-cleanOrderedAddress)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [generateAddress](#method-generateAddress)
* [generateAddressSmarty](#method-generateAddressSmarty)
* [getAddressCountryFormat](#method-getAddressCountryFormat)
* [getErrorList](#method-getErrorList)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getFormat](#method-getFormat)
* [getFormattedAddressFieldsValues](#method-getFormattedAddressFieldsValues)
* [getFormattedLayoutData](#method-getFormattedLayoutData)
* [getIdentifier](#method-getIdentifier)
* [getLiableClass](#method-getLiableClass)
* [getOrderedAddressFields](#method-getOrderedAddressFields)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidateFields](#method-getValidateFields)
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
* [save](#method-save)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-_CLEANING_REGEX_"></a>_CLEANING_REGEX_

```php
const _CLEANING_REGEX_ = '#([^\w:_]+)#i'
```





* Source: [classes/AddressFormat.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L92).


Properties
----------


### <a name="property-$_errorFormatList"></a>$_errorFormatList

```php
private mixed $_errorFormatList = array()
```





* Visibility: **private**
* Source: [classes/AddressFormat.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L39).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('format')
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L41).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('format' => 'isGenericName')
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L42).


### <a name="property-$forbiddenClassList"></a>$forbiddenClassList

```php
public mixed $forbiddenClassList = array('Manufacturer', 'Supplier')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AddressFormat.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L88).


### <a name="property-$forbiddenPropertyList"></a>$forbiddenPropertyList

```php
public mixed $forbiddenPropertyList = array('deleted', 'date_add', 'other', 'alias', 'secure_key', 'note', 'newsletter', 'ip_registration_newsletter', 'newsletter_date_add', 'optin', 'passwd', 'last_passwd_gen', 'active', 'is_guest', 'date_upd', 'years', 'days', 'months', 'description', 'meta_description', 'short_description', 'link_rewrite', 'meta_title', 'meta_keywords', 'display_tax_label', 'need_zip_code', 'contains_states', 'call_prefixes', 'call_prefix')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AddressFormat.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L57).


### <a name="property-$format"></a>$format

```php
public string $format
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L37).


### <a name="property-$id_address_format"></a>$id_address_format

```php
public integer $id_address_format
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L31).


### <a name="property-$id_country"></a>$id_country

```php
public integer $id_country
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L34).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_country'
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L46).


### <a name="property-$requireFormFieldsList"></a>$requireFormFieldsList

```php
public mixed $requireFormFieldsList = array('firstname', 'name', 'address1', 'city', 'postcode', 'Country:name', 'State:name')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AddressFormat.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L48).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'address_format'
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L45).


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


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L53).


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



### <a name="method-_checkLiableAssociation"></a>_checkLiableAssociation

```php
mixed AddressFormatCore::_checkLiableAssociation($patternName, $fieldsValidate)
```





* Visibility: **private**
* Source: [classes/AddressFormat.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L150)


#### Arguments
* $patternName **mixed**
* $fieldsValidate **mixed**



### <a name="method-_checkValidateClassField"></a>_checkValidateClassField

```php
mixed AddressFormatCore::_checkValidateClassField($className, $fieldName, $isIdField)
```





* Visibility: **private**
* Source: [classes/AddressFormat.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L111)


#### Arguments
* $className **mixed**
* $fieldName **mixed**
* $isIdField **mixed**



### <a name="method-_getFormatDB"></a>_getFormatDB

```php
mixed AddressFormatCore::_getFormatDB($id_country)
```





* Visibility: **private**
* Source: [classes/AddressFormat.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L523)


#### Arguments
* $id_country **mixed**



### <a name="method-_setOriginalDisplayFormat"></a>_setOriginalDisplayFormat

```php
mixed AddressFormatCore::_setOriginalDisplayFormat($formattedValueList, $currentLine, $currentKeyList)
```





* Visibility: **private**
* This method is **static**.
* Source: [classes/AddressFormat.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L237)


#### Arguments
* $formattedValueList **mixed**
* $currentLine **mixed**
* $currentKeyList **mixed**



### <a name="method-add"></a>add

```php
mixed ObjectModelCore::add($autodate, $nullValues)
```

Add current object to database

return boolean Insertion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L202)


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



### <a name="method-checkFormatFields"></a>checkFormatFields

```php
mixed AddressFormatCore::checkFormatFields()
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L195)




### <a name="method-cleanOrderedAddress"></a>cleanOrderedAddress

```php
mixed AddressFormatCore::cleanOrderedAddress($orderedAddressField)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L272)


#### Arguments
* $orderedAddressField **mixed**



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



### <a name="method-generateAddress"></a>generateAddress

```php
string AddressFormatCore::generateAddress(\Address $address, $patternRules, $newLine, $separator, $style)
```

Generates the full address text



* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L352)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $patternRules **mixed**
* $newLine **mixed**
* $separator **mixed**
* $style **mixed**



### <a name="method-generateAddressSmarty"></a>generateAddressSmarty

```php
mixed AddressFormatCore::generateAddressSmarty($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L379)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-getAddressCountryFormat"></a>getAddressCountryFormat

```php
String AddressFormatCore::getAddressCountryFormat($id_country)
```

Returns address format by country if not defined using default country



* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 496](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L496)


#### Arguments
* $id_country **mixed**



### <a name="method-getErrorList"></a>getErrorList

```php
mixed AddressFormatCore::getErrorList()
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L227)




### <a name="method-getFields"></a>getFields

```php
mixed AddressFormatCore::getFields()
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L94)




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




### <a name="method-getFormat"></a>getFormat

```php
String AddressFormatCore::getFormat($id_country)
```

Returns address format by country



* Visibility: **public**
* Source: [classes/AddressFormat.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L514)


#### Arguments
* $id_country **mixed**



### <a name="method-getFormattedAddressFieldsValues"></a>getFormattedAddressFieldsValues

```php
mixed AddressFormatCore::getFormattedAddressFieldsValues($address, $addressFormat, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L294)


#### Arguments
* $address **mixed**
* $addressFormat **mixed**
* $id_lang **mixed**



### <a name="method-getFormattedLayoutData"></a>getFormattedLayoutData

```php
mixed AddressFormatCore::getFormattedLayoutData($address)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L477)


#### Arguments
* $address **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getLiableClass"></a>getLiableClass

```php
mixed AddressFormatCore::getLiableClass($className)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L421)


#### Arguments
* $className **mixed**



### <a name="method-getOrderedAddressFields"></a>getOrderedAddressFields

```php
Array AddressFormatCore::getOrderedAddressFields($id_country, $split_all, $cleaned)
```

Returns address format fields in array by country



* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L455)


#### Arguments
* $id_country **mixed**
* $split_all **mixed**
* $cleaned **mixed**



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



### <a name="method-getValidateFields"></a>getValidateFields

```php
array AddressFormatCore::getValidateFields($className)
```

Returns selected fields required for an address in an array according to a selection hash



* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AddressFormat.php#L394)


#### Arguments
* $className **mixed**



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


