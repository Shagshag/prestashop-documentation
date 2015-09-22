AddressFormatCore
===============






* Class name: AddressFormatCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/AddressFormat.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L27)



Constants
----------

* [_CLEANING_REGEX_](#constant-_CLEANING_REGEX_)

Properties
----------

* [$id_address_format](#property-$id_address_format)
* [$id_country](#property-$id_country)
* [$format](#property-$format)
* [$_errorFormatList](#property-$_errorFormatList)
* [$definition](#property-$definition)
* [$requireFormFieldsList](#property-$requireFormFieldsList)
* [$forbiddenPropertyList](#property-$forbiddenPropertyList)
* [$forbiddenClassList](#property-$forbiddenClassList)

Methods
-------
* [_checkValidateClassField](#method-_checkValidateClassField)
* [_checkLiableAssociation](#method-_checkLiableAssociation)
* [checkFormatFields](#method-checkFormatFields)
* [getErrorList](#method-getErrorList)
* [_setOriginalDisplayFormat](#method-_setOriginalDisplayFormat)
* [cleanOrderedAddress](#method-cleanOrderedAddress)
* [getFormattedAddressFieldsValues](#method-getFormattedAddressFieldsValues)
* [generateAddress](#method-generateAddress)
* [generateAddressSmarty](#method-generateAddressSmarty)
* [getValidateFields](#method-getValidateFields)
* [getLiableClass](#method-getLiableClass)
* [getOrderedAddressFields](#method-getOrderedAddressFields)
* [getFormattedLayoutData](#method-getFormattedLayoutData)
* [getAddressCountryFormat](#method-getAddressCountryFormat)
* [getFormat](#method-getFormat)
* [_getFormatDB](#method-_getFormatDB)
* [getFieldsRequired](#method-getFieldsRequired)


Constants
----------


### <a name="constant-_CLEANING_REGEX_"></a>_CLEANING_REGEX_

    const _CLEANING_REGEX_ = '#([^\w:_]+)#i'



* This constant is defined in [classes/AddressFormat.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L107)


Properties
----------


### <a name="property-$id_address_format"></a>$id_address_format

    public integer $id_address_format





* Visibility: **public**
* This property is defined in [classes/AddressFormat.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L30)


### <a name="property-$id_country"></a>$id_country

    public integer $id_country





* Visibility: **public**
* This property is defined in [classes/AddressFormat.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L33)


### <a name="property-$format"></a>$format

    public string $format





* Visibility: **public**
* This property is defined in [classes/AddressFormat.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L36)


### <a name="property-$_errorFormatList"></a>$_errorFormatList

    protected mixed $_errorFormatList = array()





* Visibility: **protected**
* This property is defined in [classes/AddressFormat.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L38)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'address_format', 'primary' => 'id_country', 'fields' => array('format' => array('type' => self::TYPE_HTML, 'validate' => 'isGenericName', 'required' => true), 'id_country' => array('type' => self::TYPE_INT)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L43)


### <a name="property-$requireFormFieldsList"></a>$requireFormFieldsList

    public mixed $requireFormFieldsList = array('firstname', 'lastname', 'address1', 'city', 'Country:name')





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L52)


### <a name="property-$forbiddenPropertyList"></a>$forbiddenPropertyList

    public mixed $forbiddenPropertyList = array('deleted', 'date_add', 'alias', 'secure_key', 'note', 'newsletter', 'ip_registration_newsletter', 'newsletter_date_add', 'optin', 'passwd', 'last_passwd_gen', 'active', 'is_guest', 'date_upd', 'country', 'years', 'days', 'months', 'description', 'meta_description', 'short_description', 'link_rewrite', 'meta_title', 'meta_keywords', 'display_tax_label', 'need_zip_code', 'contains_states', 'call_prefixes', 'show_public_prices', 'max_payment', 'max_payment_days', 'geoloc_postcode', 'logged', 'account_number', 'groupBox', 'ape', 'max_payment', 'outstanding_allow_amount', 'call_prefix', 'definition', 'debug_list')





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L59)


### <a name="property-$forbiddenClassList"></a>$forbiddenClassList

    public mixed $forbiddenClassList = array('Manufacturer', 'Supplier')





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L103)


Methods
-------


### <a name="method-_checkValidateClassField"></a>_checkValidateClassField

    mixed AddressFormatCore::_checkValidateClassField($className, $fieldName, $isIdField)





* Visibility: **protected**
* This method is defined in [classes/AddressFormat.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L116)


#### Arguments
* $className **mixed**
* $fieldName **mixed**
* $isIdField **mixed**



### <a name="method-_checkLiableAssociation"></a>_checkLiableAssociation

    mixed AddressFormatCore::_checkLiableAssociation($patternName, $fieldsValidate)





* Visibility: **protected**
* This method is defined in [classes/AddressFormat.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L155)


#### Arguments
* $patternName **mixed**
* $fieldsValidate **mixed**



### <a name="method-checkFormatFields"></a>checkFormatFields

    mixed AddressFormatCore::checkFormatFields()





* Visibility: **public**
* This method is defined in [classes/AddressFormat.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L198)




### <a name="method-getErrorList"></a>getErrorList

    mixed AddressFormatCore::getErrorList()





* Visibility: **public**
* This method is defined in [classes/AddressFormat.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L229)




### <a name="method-_setOriginalDisplayFormat"></a>_setOriginalDisplayFormat

    mixed AddressFormatCore::_setOriginalDisplayFormat($formattedValueList, $currentLine, $currentKeyList)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L239)


#### Arguments
* $formattedValueList **mixed**
* $currentLine **mixed**
* $currentKeyList **mixed**



### <a name="method-cleanOrderedAddress"></a>cleanOrderedAddress

    mixed AddressFormatCore::cleanOrderedAddress($orderedAddressField)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L290)


#### Arguments
* $orderedAddressField **mixed**



### <a name="method-getFormattedAddressFieldsValues"></a>getFormattedAddressFieldsValues

    mixed AddressFormatCore::getFormattedAddressFieldsValues($address, $addressFormat, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L311)


#### Arguments
* $address **mixed**
* $addressFormat **mixed**
* $id_lang **mixed**



### <a name="method-generateAddress"></a>generateAddress

    string AddressFormatCore::generateAddress(\Address $address, array $patternRules, string $newLine, string $separator, array $style)

Generates the full address text



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L372)


#### Arguments
* $address **[Address](AddressCore)**
* $patternRules **array** - &lt;p&gt;A defined rules array to avoid some pattern&lt;/p&gt;
* $newLine **string** - &lt;p&gt;A string containing the newLine format&lt;/p&gt;
* $separator **string** - &lt;p&gt;A string containing the separator format&lt;/p&gt;
* $style **array**



### <a name="method-generateAddressSmarty"></a>generateAddressSmarty

    mixed AddressFormatCore::generateAddressSmarty($params, $smarty)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L401)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-getValidateFields"></a>getValidateFields

    array AddressFormatCore::getValidateFields($className)

Returns selected fields required for an address in an array according to a selection hash



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L416)


#### Arguments
* $className **mixed**



### <a name="method-getLiableClass"></a>getLiableClass

    mixed AddressFormatCore::getLiableClass($className)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L442)


#### Arguments
* $className **mixed**



### <a name="method-getOrderedAddressFields"></a>getOrderedAddressFields

    Array AddressFormatCore::getOrderedAddressFields(integer $id_country, boolean $split_all, boolean $cleaned)

Returns address format fields in array by country



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L476)


#### Arguments
* $id_country **integer** - &lt;p&gt;If null using PS_COUNTRY_DEFAULT&lt;/p&gt;
* $split_all **boolean**
* $cleaned **boolean**



### <a name="method-getFormattedLayoutData"></a>getFormattedLayoutData

    mixed AddressFormatCore::getFormattedLayoutData($address)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L500)


#### Arguments
* $address **mixed**



### <a name="method-getAddressCountryFormat"></a>getAddressCountryFormat

    String AddressFormatCore::getAddressCountryFormat(integer $id_country)

Returns address format by country if not defined using default country



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L526)


#### Arguments
* $id_country **integer**



### <a name="method-getFormat"></a>getFormat

    String AddressFormatCore::getFormat(integer $id_country)

Returns address format by country



* Visibility: **public**
* This method is defined in [classes/AddressFormat.php line 543](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L543)


#### Arguments
* $id_country **integer**



### <a name="method-_getFormatDB"></a>_getFormatDB

    mixed AddressFormatCore::_getFormatDB($id_country)





* Visibility: **protected**
* This method is defined in [classes/AddressFormat.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L552)


#### Arguments
* $id_country **mixed**



### <a name="method-getFieldsRequired"></a>getFieldsRequired

    mixed AddressFormatCore::getFieldsRequired()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L566)



