Class AddressCore
=====================





* Class name: AddressCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Address.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L28)


Contents
--------


### Properties

* [$_idCountries](#property-$_idCountries)
* [$_idZones](#property-$_idZones)
* [$_includeContainer](#property-$_includeContainer)
* [$_includeVars](#property-$_includeVars)
* [$address1](#property-$address1)
* [$address2](#property-$address2)
* [$alias](#property-$alias)
* [$city](#property-$city)
* [$company](#property-$company)
* [$country](#property-$country)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$deleted](#property-$deleted)
* [$dni](#property-$dni)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$firstname](#property-$firstname)
* [$id_country](#property-$id_country)
* [$id_customer](#property-$id_customer)
* [$id_manufacturer](#property-$id_manufacturer)
* [$id_state](#property-$id_state)
* [$id_supplier](#property-$id_supplier)
* [$identifier](#property-$identifier)
* [$lastname](#property-$lastname)
* [$other](#property-$other)
* [$phone](#property-$phone)
* [$phone_mobile](#property-$phone_mobile)
* [$postcode](#property-$postcode)
* [$table](#property-$table)
* [$vat_number](#property-$vat_number)
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
* [addressExists](#method-addressExists)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getCountryAndState](#method-getCountryAndState)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidate](#method-getFieldsValidate)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getFirstCustomerAddressId](#method-getFirstCustomerAddressId)
* [getIdentifier](#method-getIdentifier)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getZoneById](#method-getZoneById)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [initialize](#method-initialize)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCountryActiveById](#method-isCountryActiveById)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isUsed](#method-isUsed)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_idCountries"></a>$_idCountries

```php
protected mixed $_idCountries = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Address.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L97).


### <a name="property-$_idZones"></a>$_idZones

```php
protected mixed $_idZones = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Address.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L96).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = false
```





* Visibility: **protected**
* Source: [classes/Address.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L113).


### <a name="property-$_includeVars"></a>$_includeVars

```php
protected mixed $_includeVars = array('addressType' => 'table')
```





* Visibility: **protected**
* Source: [classes/Address.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L112).


### <a name="property-$address1"></a>$address1

```php
public string $address1
```





* Visibility: **public**
* Source: [classes/Address.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L61).


### <a name="property-$address2"></a>$address2

```php
public string $address2
```





* Visibility: **public**
* Source: [classes/Address.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L64).


### <a name="property-$alias"></a>$alias

```php
public string $alias
```





* Visibility: **public**
* Source: [classes/Address.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L49).


### <a name="property-$city"></a>$city

```php
public string $city
```





* Visibility: **public**
* Source: [classes/Address.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L70).


### <a name="property-$company"></a>$company

```php
public string $company
```





* Visibility: **public**
* Source: [classes/Address.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L52).


### <a name="property-$country"></a>$country

```php
public string $country
```





* Visibility: **public**
* Source: [classes/Address.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L46).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Address.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L88).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Address.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L91).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Address.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L94).


### <a name="property-$dni"></a>$dni

```php
public string $dni
```





* Visibility: **public**
* Source: [classes/Address.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L85).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('id_country', 'alias', 'lastname', 'firstname', 'address1', 'city')
```





* Visibility: **protected**
* Source: [classes/Address.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L99).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('alias' => 32, 'company' => 32, 'lastname' => 32, 'firstname' => 32, 'address1' => 128, 'address2' => 128, 'postcode' => 12, 'city' => 64, 'other' => 300, 'phone' => 16, 'phone_mobile' => 16, 'dni' => 16)
```





* Visibility: **protected**
* Source: [classes/Address.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('id_customer' => 'isNullOrUnsignedId', 'id_manufacturer' => 'isNullOrUnsignedId', 'id_supplier' => 'isNullOrUnsignedId', 'id_country' => 'isUnsignedId', 'id_state' => 'isNullOrUnsignedId', 'alias' => 'isGenericName', 'company' => 'isGenericName', 'lastname' => 'isName', 'vat_number' => 'isGenericName', 'firstname' => 'isName', 'address1' => 'isAddress', 'address2' => 'isAddress', 'postcode' => 'isPostCode', 'city' => 'isCityName', 'other' => 'isMessage', 'phone' => 'isPhoneNumber', 'phone_mobile' => 'isPhoneNumber', 'deleted' => 'isBool', 'dni' => 'isDniLite')
```





* Visibility: **protected**
* Source: [classes/Address.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L103).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Address.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L58).


### <a name="property-$id_country"></a>$id_country

```php
public integer $id_country
```





* Visibility: **public**
* Source: [classes/Address.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L40).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer = null
```





* Visibility: **public**
* Source: [classes/Address.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L31).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer = null
```





* Visibility: **public**
* Source: [classes/Address.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L34).


### <a name="property-$id_state"></a>$id_state

```php
public integer $id_state
```





* Visibility: **public**
* Source: [classes/Address.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L43).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier = null
```





* Visibility: **public**
* Source: [classes/Address.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L37).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_address'
```





* Visibility: **protected**
* Source: [classes/Address.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L111).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Address.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L55).


### <a name="property-$other"></a>$other

```php
public string $other
```





* Visibility: **public**
* Source: [classes/Address.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L73).


### <a name="property-$phone"></a>$phone

```php
public string $phone
```





* Visibility: **public**
* Source: [classes/Address.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L76).


### <a name="property-$phone_mobile"></a>$phone_mobile

```php
public string $phone_mobile
```





* Visibility: **public**
* Source: [classes/Address.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L79).


### <a name="property-$postcode"></a>$postcode

```php
public string $postcode
```





* Visibility: **public**
* Source: [classes/Address.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L67).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'address'
```





* Visibility: **protected**
* Source: [classes/Address.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L110).


### <a name="property-$vat_number"></a>$vat_number

```php
public string $vat_number
```





* Visibility: **public**
* Source: [classes/Address.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L82).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'addresses', 'fields' => array('id_customer' => array('xlink_resource' => 'customers'), 'id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_country' => array('xlink_resource' => 'countries'), 'id_state' => array('xlink_resource' => 'states')))
```





* Visibility: **protected**
* Source: [classes/Address.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L115).


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
mixed AddressCore::__construct(integer $id_address, $id_lang)
```

Build an address



* Visibility: **public**
* Source: [classes/Address.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L131)


#### Arguments
* $id_address **integer** - Existing address id in order to load object (optional)
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed AddressCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Address.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L146)


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



### <a name="method-addressExists"></a>addressExists

```php
boolean AddressCore::addressExists($id_address)
```

Specify if an address is already in base



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L297)


#### Arguments
* $id_address **mixed** - Address id



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
mixed AddressCore::delete()
```





* Visibility: **public**
* Source: [classes/Address.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L156)




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



### <a name="method-getCountryAndState"></a>getCountryAndState

```php
mixed AddressCore::getCountryAndState($id_address)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L280)


#### Arguments
* $id_address **mixed**



### <a name="method-getFields"></a>getFields

```php
mixed AddressCore::getFields()
```





* Visibility: **public**
* Source: [classes/Address.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L186)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L772)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsValidate"></a>getFieldsValidate

```php
array AddressCore::getFieldsValidate()
```

Returns fields required for an address in an array hash



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L174)




### <a name="method-getFieldsValidateLang"></a>getFieldsValidateLang

```php
array ObjectModelCore::getFieldsValidateLang()
```

Get list of fields related to language to validate



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L975)




### <a name="method-getFirstCustomerAddressId"></a>getFirstCustomerAddressId

```php
mixed AddressCore::getFirstCustomerAddressId($id_customer, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L307)


#### Arguments
* $id_customer **mixed**
* $active **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




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



### <a name="method-getZoneById"></a>getZoneById

```php
integer AddressCore::getZoneById(integer $id_address)
```

Get zone id for a given address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L231)


#### Arguments
* $id_address **integer** - Address id for which we want to get zone id



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
\Address AddressCore::initialize(integer $id_address)
```

Initiliaze an address corresponding to the specified id address or if empty to the
default shop configuration



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L323)


#### Arguments
* $id_address **integer**



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



### <a name="method-isCountryActiveById"></a>isCountryActiveById

```php
integer AddressCore::isCountryActiveById(integer $id_address)
```

Check if country is active for a given address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L253)


#### Arguments
* $id_address **integer** - Address id for which we want to get country status



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




### <a name="method-isUsed"></a>isUsed

```php
integer AddressCore::isUsed()
```

Check if address is used (at least one order placed)



* Visibility: **public**
* Source: [classes/Address.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L269)




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
mixed AddressCore::validateController($htmlentities)
```





* Visibility: **public**
* Source: [classes/Address.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Address.php#L215)


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


