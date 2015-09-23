Class AddressFormatCore
=====================





* Class name: AddressFormatCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/AddressFormat.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L27)


Contents
--------

### Constants

* [_CLEANING_REGEX_](#constant-_CLEANING_REGEX_)

### Properties

* [$_errorFormatList](#property-$_errorFormatList)
* [$definition](#property-$definition)
* [$forbiddenClassList](#property-$forbiddenClassList)
* [$forbiddenPropertyList](#property-$forbiddenPropertyList)
* [$format](#property-$format)
* [$id_address_format](#property-$id_address_format)
* [$id_country](#property-$id_country)
* [$requireFormFieldsList](#property-$requireFormFieldsList)

### Methods

* [_checkLiableAssociation](#method-_checkLiableAssociation)
* [_checkValidateClassField](#method-_checkValidateClassField)
* [_getFormatDB](#method-_getFormatDB)
* [_setOriginalDisplayFormat](#method-_setOriginalDisplayFormat)
* [checkFormatFields](#method-checkFormatFields)
* [cleanOrderedAddress](#method-cleanOrderedAddress)
* [generateAddress](#method-generateAddress)
* [generateAddressSmarty](#method-generateAddressSmarty)
* [getAddressCountryFormat](#method-getAddressCountryFormat)
* [getErrorList](#method-getErrorList)
* [getFieldsRequired](#method-getFieldsRequired)
* [getFormat](#method-getFormat)
* [getFormattedAddressFieldsValues](#method-getFormattedAddressFieldsValues)
* [getFormattedLayoutData](#method-getFormattedLayoutData)
* [getLiableClass](#method-getLiableClass)
* [getOrderedAddressFields](#method-getOrderedAddressFields)
* [getValidateFields](#method-getValidateFields)


Constants
----------


### <a name="constant-_CLEANING_REGEX_"></a>_CLEANING_REGEX_

```php
const _CLEANING_REGEX_ = '#([^\w:_]+)#i'
```





* Source: [classes/AddressFormat.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L107).


Properties
----------


### <a name="property-$_errorFormatList"></a>$_errorFormatList

```php
protected mixed $_errorFormatList = array()
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L38).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'address_format', 'primary' => 'id_country', 'fields' => array('format' => array('type' => self::TYPE_HTML, 'validate' => 'isGenericName', 'required' => true), 'id_country' => array('type' => self::TYPE_INT)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AddressFormat.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L43).


### <a name="property-$forbiddenClassList"></a>$forbiddenClassList

```php
public mixed $forbiddenClassList = array('Manufacturer', 'Supplier')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AddressFormat.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L103).


### <a name="property-$forbiddenPropertyList"></a>$forbiddenPropertyList

```php
public mixed $forbiddenPropertyList = array('deleted', 'date_add', 'alias', 'secure_key', 'note', 'newsletter', 'ip_registration_newsletter', 'newsletter_date_add', 'optin', 'passwd', 'last_passwd_gen', 'active', 'is_guest', 'date_upd', 'country', 'years', 'days', 'months', 'description', 'meta_description', 'short_description', 'link_rewrite', 'meta_title', 'meta_keywords', 'display_tax_label', 'need_zip_code', 'contains_states', 'call_prefixes', 'show_public_prices', 'max_payment', 'max_payment_days', 'geoloc_postcode', 'logged', 'account_number', 'groupBox', 'ape', 'max_payment', 'outstanding_allow_amount', 'call_prefix', 'definition', 'debug_list')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AddressFormat.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L59).


### <a name="property-$format"></a>$format

```php
public string $format
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L36).


### <a name="property-$id_address_format"></a>$id_address_format

```php
public integer $id_address_format
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L30).


### <a name="property-$id_country"></a>$id_country

```php
public integer $id_country
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L33).


### <a name="property-$requireFormFieldsList"></a>$requireFormFieldsList

```php
public mixed $requireFormFieldsList = array('firstname', 'lastname', 'address1', 'city', 'Country:name')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AddressFormat.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L52).


Methods
-------


### <a name="method-_checkLiableAssociation"></a>_checkLiableAssociation

```php
mixed AddressFormatCore::_checkLiableAssociation($patternName, $fieldsValidate)
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L155)


#### Arguments
* $patternName **mixed**
* $fieldsValidate **mixed**



### <a name="method-_checkValidateClassField"></a>_checkValidateClassField

```php
mixed AddressFormatCore::_checkValidateClassField($className, $fieldName, $isIdField)
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L116)


#### Arguments
* $className **mixed**
* $fieldName **mixed**
* $isIdField **mixed**



### <a name="method-_getFormatDB"></a>_getFormatDB

```php
mixed AddressFormatCore::_getFormatDB($id_country)
```





* Visibility: **protected**
* Source: [classes/AddressFormat.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L535)


#### Arguments
* $id_country **mixed**



### <a name="method-_setOriginalDisplayFormat"></a>_setOriginalDisplayFormat

```php
mixed AddressFormatCore::_setOriginalDisplayFormat($formattedValueList, $currentLine, $currentKeyList)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/AddressFormat.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L245)


#### Arguments
* $formattedValueList **mixed**
* $currentLine **mixed**
* $currentKeyList **mixed**



### <a name="method-checkFormatFields"></a>checkFormatFields

```php
mixed AddressFormatCore::checkFormatFields()
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L202)




### <a name="method-cleanOrderedAddress"></a>cleanOrderedAddress

```php
mixed AddressFormatCore::cleanOrderedAddress($orderedAddressField)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L280)


#### Arguments
* $orderedAddressField **mixed**



### <a name="method-generateAddress"></a>generateAddress

```php
string AddressFormatCore::generateAddress(\Address $address, $patternRules, $newLine, $separator, $style)
```

Generates the full address text



* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L360)


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
* Source: [classes/AddressFormat.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L387)


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
* Source: [classes/AddressFormat.php line 510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L510)


#### Arguments
* $id_country **mixed**



### <a name="method-getErrorList"></a>getErrorList

```php
mixed AddressFormatCore::getErrorList()
```





* Visibility: **public**
* Source: [classes/AddressFormat.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L235)




### <a name="method-getFieldsRequired"></a>getFieldsRequired

```php
mixed AddressFormatCore::getFieldsRequired()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L548)




### <a name="method-getFormat"></a>getFormat

```php
String AddressFormatCore::getFormat($id_country)
```

Returns address format by country



* Visibility: **public**
* Source: [classes/AddressFormat.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L527)


#### Arguments
* $id_country **mixed**



### <a name="method-getFormattedAddressFieldsValues"></a>getFormattedAddressFieldsValues

```php
mixed AddressFormatCore::getFormattedAddressFieldsValues($address, $addressFormat, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L302)


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
* Source: [classes/AddressFormat.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L485)


#### Arguments
* $address **mixed**



### <a name="method-getLiableClass"></a>getLiableClass

```php
mixed AddressFormatCore::getLiableClass($className)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L429)


#### Arguments
* $className **mixed**



### <a name="method-getOrderedAddressFields"></a>getOrderedAddressFields

```php
Array AddressFormatCore::getOrderedAddressFields($id_country, $split_all, $cleaned)
```

Returns address format fields in array by country



* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L463)


#### Arguments
* $id_country **mixed**
* $split_all **mixed**
* $cleaned **mixed**



### <a name="method-getValidateFields"></a>getValidateFields

```php
array AddressFormatCore::getValidateFields($className)
```

Returns selected fields required for an address in an array according to a selection hash



* Visibility: **public**
* This method is **static**.
* Source: [classes/AddressFormat.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/AddressFormat.php#L402)


#### Arguments
* $className **mixed**


