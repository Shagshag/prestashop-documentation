Class AddressCore
=====================





* Class name: AddressCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Address.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L28)


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
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$dni](#property-$dni)
* [$firstname](#property-$firstname)
* [$id_country](#property-$id_country)
* [$id_customer](#property-$id_customer)
* [$id_manufacturer](#property-$id_manufacturer)
* [$id_state](#property-$id_state)
* [$id_supplier](#property-$id_supplier)
* [$id_warehouse](#property-$id_warehouse)
* [$lastname](#property-$lastname)
* [$other](#property-$other)
* [$phone](#property-$phone)
* [$phone_mobile](#property-$phone_mobile)
* [$postcode](#property-$postcode)
* [$vat_number](#property-$vat_number)
* [$webserviceParameters](#property-$webserviceParameters)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id](#property-$id)
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
* [addressExists](#method-addressExists)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAddressIdBySupplierId](#method-getAddressIdBySupplierId)
* [getAssociatedShops](#method-getAssociatedShops)
* [getCountryAndState](#method-getCountryAndState)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getFieldsValidate](#method-getFieldsValidate)
* [getFirstCustomerAddressId](#method-getFirstCustomerAddressId)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getZoneById](#method-getZoneById)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [initialize](#method-initialize)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCountryActiveById](#method-isCountryActiveById)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isMultishop](#method-isMultishop)
* [isUsed](#method-isUsed)
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




Properties
----------


### <a name="property-$_idCountries"></a>$_idCountries

```php
protected mixed $_idCountries = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Address.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L103).


### <a name="property-$_idZones"></a>$_idZones

```php
protected mixed $_idZones = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Address.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L102).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = false
```





* Visibility: **protected**
* Source: [classes/Address.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L138).


### <a name="property-$_includeVars"></a>$_includeVars

```php
protected mixed $_includeVars = array('addressType' => 'table')
```





* Visibility: **protected**
* Source: [classes/Address.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L137).


### <a name="property-$address1"></a>$address1

```php
public string $address1
```





* Visibility: **public**
* Source: [classes/Address.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L67).


### <a name="property-$address2"></a>$address2

```php
public string $address2
```





* Visibility: **public**
* Source: [classes/Address.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L70).


### <a name="property-$alias"></a>$alias

```php
public string $alias
```





* Visibility: **public**
* Source: [classes/Address.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L55).


### <a name="property-$city"></a>$city

```php
public string $city
```





* Visibility: **public**
* Source: [classes/Address.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L76).


### <a name="property-$company"></a>$company

```php
public string $company
```





* Visibility: **public**
* Source: [classes/Address.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L58).


### <a name="property-$country"></a>$country

```php
public string $country
```





* Visibility: **public**
* Source: [classes/Address.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L52).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Address.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L94).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Address.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L97).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'address', 'primary' => 'id_address', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId'), 'alias' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 32), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'vat_number' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'address1' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'required' => true, 'size' => 128), 'address2' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'size' => 128), 'postcode' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode', 'size' => 12), 'city' => array('type' => self::TYPE_STRING, 'validate' => 'isCityName', 'required' => true, 'size' => 64), 'other' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage', 'size' => 300), 'phone' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'phone_mobile' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'dni' => array('type' => self::TYPE_STRING, 'validate' => 'isDniLite', 'size' => 16), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'copy_post' => false)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Address.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L108).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Address.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L100).


### <a name="property-$dni"></a>$dni

```php
public string $dni
```





* Visibility: **public**
* Source: [classes/Address.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L91).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Address.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L64).


### <a name="property-$id_country"></a>$id_country

```php
public integer $id_country
```





* Visibility: **public**
* Source: [classes/Address.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L46).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer = null
```





* Visibility: **public**
* Source: [classes/Address.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L31).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer = null
```





* Visibility: **public**
* Source: [classes/Address.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L34).


### <a name="property-$id_state"></a>$id_state

```php
public integer $id_state
```





* Visibility: **public**
* Source: [classes/Address.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L49).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier = null
```





* Visibility: **public**
* Source: [classes/Address.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L37).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse = null
```





* Visibility: **public**
* Source: [classes/Address.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L43).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Address.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L61).


### <a name="property-$other"></a>$other

```php
public string $other
```





* Visibility: **public**
* Source: [classes/Address.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L79).


### <a name="property-$phone"></a>$phone

```php
public string $phone
```





* Visibility: **public**
* Source: [classes/Address.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L82).


### <a name="property-$phone_mobile"></a>$phone_mobile

```php
public string $phone_mobile
```





* Visibility: **public**
* Source: [classes/Address.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L85).


### <a name="property-$postcode"></a>$postcode

```php
public string $postcode
```





* Visibility: **public**
* Source: [classes/Address.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L73).


### <a name="property-$vat_number"></a>$vat_number

```php
public string $vat_number
```





* Visibility: **public**
* Source: [classes/Address.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L88).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'addresses', 'fields' => array('id_customer' => array('xlink_resource' => 'customers'), 'id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_warehouse' => array('xlink_resource' => 'warehouse'), 'id_country' => array('xlink_resource' => 'countries'), 'id_state' => array('xlink_resource' => 'states')))
```





* Visibility: **protected**
* Source: [classes/Address.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L131).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L106).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L64).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L55).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L60).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L117).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L120).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L136).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AddressCore::__construct(integer $id_address, $id_lang)
```

Build an address



* Visibility: **public**
* Source: [classes/Address.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L157)


#### Arguments
* $id_address **integer** - Existing address id in order to load object (optional)
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed AddressCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Address.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L169)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1040](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1040)


#### Arguments
* $fields **mixed**



### <a name="method-addressExists"></a>addressExists

```php
boolean AddressCore::addressExists($id_address)
```

Specify if an address is already in base



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L294)


#### Arguments
* $id_address **mixed** - Address id



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1087](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1087)


#### Arguments
* $id_shops **integer|array**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1054](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1054)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed AddressCore::delete()
```





* Visibility: **public**
* Source: [classes/Address.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L182)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1214)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L669)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 869](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L869)


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
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1131)


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
* Source: [classes/ObjectModel.php line 1248](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1248)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L327)


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
* Source: [classes/ObjectModel.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L373)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAddressIdBySupplierId"></a>getAddressIdBySupplierId

```php
integer AddressCore::getAddressIdBySupplierId(integer $id_supplier)
```

Returns id_address for a given id_supplier



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L351)


#### Arguments
* $id_supplier **integer**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1116)




### <a name="method-getCountryAndState"></a>getCountryAndState

```php
mixed AddressCore::getCountryAndState($id_address)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L277)


#### Arguments
* $id_address **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1351](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1351)


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
* Source: [classes/ObjectModel.php line 1428](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1428)


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
* Source: [classes/ObjectModel.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L255)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L292)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1032](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1032)


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
* Source: [classes/ObjectModel.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L278)




### <a name="method-getFieldsValidate"></a>getFieldsValidate

```php
array AddressCore::getFieldsValidate()
```

Returns fields required for an address in an array hash



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L200)




### <a name="method-getFirstCustomerAddressId"></a>getFirstCustomerAddressId

```php
mixed AddressCore::getFirstCustomerAddressId($id_customer, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L306)


#### Arguments
* $id_customer **mixed**
* $active **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 701](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L701)


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
* Source: [classes/ObjectModel.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L144)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1005](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1005)


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
* Source: [classes/ObjectModel.php line 931](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L931)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getZoneById"></a>getZoneById

```php
integer AddressCore::getZoneById(integer $id_address)
```

Get zone id for a given address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L228)


#### Arguments
* $id_address **integer** - Address id for which we want to get zone id



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1156)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1283](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1283)


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
* Source: [classes/ObjectModel.php line 1302](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1302)


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
* Source: [classes/Address.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L325)


#### Arguments
* $id_address **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1069)


#### Arguments
* $id_shop **integer**



### <a name="method-isCountryActiveById"></a>isCountryActiveById

```php
integer AddressCore::isCountryActiveById(integer $id_address)
```

Check if country is active for a given address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L250)


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
* Source: [classes/ObjectModel.php line 1266](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1266)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1169](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1169)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1164)




### <a name="method-isUsed"></a>isUsed

```php
integer AddressCore::isUsed()
```

Check if address is used (at least one order placed)



* Visibility: **public**
* Source: [classes/Address.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L266)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 717](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L717)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L417)


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
* Source: [classes/ObjectModel.php line 1374](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1374)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1454](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1454)


#### Arguments
* $fields **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L685)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L513)


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
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L1184)


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
* Source: [classes/ObjectModel.php line 884](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L884)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed AddressCore::validateController($htmlentities)
```





* Visibility: **public**
* Source: [classes/Address.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Address.php#L212)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 822](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L822)


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
* Source: [classes/ObjectModel.php line 755](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L755)


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
* Source: [classes/ObjectModel.php line 784](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/ObjectModel.php#L784)


#### Arguments
* $die **boolean**
* $error_return **boolean**


