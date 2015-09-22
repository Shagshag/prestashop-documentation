AddressFormatCore
===============






* Class name: AddressFormatCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/AddressFormat.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#L27)



Constants
----------


### _CLEANING_REGEX_

    const _CLEANING_REGEX_ = '#([^\w:_]+)#i'



* This constant is defined in [classes/AddressFormat.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#107)


Properties
----------


### $id_address_format

    public integer $id_address_format





* Visibility: **public**
* This property is defined in [classes/AddressFormat.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#30)


### $id_country

    public integer $id_country





* Visibility: **public**
* This property is defined in [classes/AddressFormat.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#33)


### $format

    public string $format





* Visibility: **public**
* This property is defined in [classes/AddressFormat.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#36)


### $_errorFormatList

    protected mixed $_errorFormatList = array()





* Visibility: **protected**
* This property is defined in [classes/AddressFormat.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#38)


### $definition

    public mixed $definition = array('table' => 'address_format', 'primary' => 'id_country', 'fields' => array('format' => array('type' => self::TYPE_HTML, 'validate' => 'isGenericName', 'required' => true), 'id_country' => array('type' => self::TYPE_INT)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#43)


### $requireFormFieldsList

    public mixed $requireFormFieldsList = array('firstname', 'lastname', 'address1', 'city', 'Country:name')





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#52)


### $forbiddenPropertyList

    public mixed $forbiddenPropertyList = array('deleted', 'date_add', 'alias', 'secure_key', 'note', 'newsletter', 'ip_registration_newsletter', 'newsletter_date_add', 'optin', 'passwd', 'last_passwd_gen', 'active', 'is_guest', 'date_upd', 'country', 'years', 'days', 'months', 'description', 'meta_description', 'short_description', 'link_rewrite', 'meta_title', 'meta_keywords', 'display_tax_label', 'need_zip_code', 'contains_states', 'call_prefixes', 'show_public_prices', 'max_payment', 'max_payment_days', 'geoloc_postcode', 'logged', 'account_number', 'groupBox', 'ape', 'max_payment', 'outstanding_allow_amount', 'call_prefix', 'definition', 'debug_list')





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#59)


### $forbiddenClassList

    public mixed $forbiddenClassList = array('Manufacturer', 'Supplier')





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AddressFormat.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#103)


Methods
-------


### _checkValidateClassField

    mixed AddressFormatCore::_checkValidateClassField($className, $fieldName, $isIdField)





* Visibility: **protected**
* This method is defined in [classes/AddressFormat.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#116)


#### Arguments
* $className **mixed**
* $fieldName **mixed**
* $isIdField **mixed**



### _checkLiableAssociation

    mixed AddressFormatCore::_checkLiableAssociation($patternName, $fieldsValidate)





* Visibility: **protected**
* This method is defined in [classes/AddressFormat.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#155)


#### Arguments
* $patternName **mixed**
* $fieldsValidate **mixed**



### checkFormatFields

    mixed AddressFormatCore::checkFormatFields()





* Visibility: **public**
* This method is defined in [classes/AddressFormat.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#198)




### getErrorList

    mixed AddressFormatCore::getErrorList()





* Visibility: **public**
* This method is defined in [classes/AddressFormat.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#229)




### _setOriginalDisplayFormat

    mixed AddressFormatCore::_setOriginalDisplayFormat($formattedValueList, $currentLine, $currentKeyList)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#239)


#### Arguments
* $formattedValueList **mixed**
* $currentLine **mixed**
* $currentKeyList **mixed**



### cleanOrderedAddress

    mixed AddressFormatCore::cleanOrderedAddress($orderedAddressField)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#290)


#### Arguments
* $orderedAddressField **mixed**



### getFormattedAddressFieldsValues

    mixed AddressFormatCore::getFormattedAddressFieldsValues($address, $addressFormat, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#311)


#### Arguments
* $address **mixed**
* $addressFormat **mixed**
* $id_lang **mixed**



### generateAddress

    string AddressFormatCore::generateAddress(\Address $address, array $patternRules, string $newLine, string $separator, array $style)

Generates the full address text



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#372)


#### Arguments
* $address **[Address](AddressCore)**
* $patternRules **array** - &lt;p&gt;A defined rules array to avoid some pattern&lt;/p&gt;
* $newLine **string** - &lt;p&gt;A string containing the newLine format&lt;/p&gt;
* $separator **string** - &lt;p&gt;A string containing the separator format&lt;/p&gt;
* $style **array**



### generateAddressSmarty

    mixed AddressFormatCore::generateAddressSmarty($params, $smarty)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#401)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### getValidateFields

    array AddressFormatCore::getValidateFields($className)

Returns selected fields required for an address in an array according to a selection hash



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#416)


#### Arguments
* $className **mixed**



### getLiableClass

    mixed AddressFormatCore::getLiableClass($className)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#442)


#### Arguments
* $className **mixed**



### getOrderedAddressFields

    Array AddressFormatCore::getOrderedAddressFields(integer $id_country, boolean $split_all, boolean $cleaned)

Returns address format fields in array by country



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#476)


#### Arguments
* $id_country **integer** - &lt;p&gt;If null using PS_COUNTRY_DEFAULT&lt;/p&gt;
* $split_all **boolean**
* $cleaned **boolean**



### getFormattedLayoutData

    mixed AddressFormatCore::getFormattedLayoutData($address)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#500)


#### Arguments
* $address **mixed**



### getAddressCountryFormat

    String AddressFormatCore::getAddressCountryFormat(integer $id_country)

Returns address format by country if not defined using default country



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#526)


#### Arguments
* $id_country **integer**



### getFormat

    String AddressFormatCore::getFormat(integer $id_country)

Returns address format by country



* Visibility: **public**
* This method is defined in [classes/AddressFormat.php line 543](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#543)


#### Arguments
* $id_country **integer**



### _getFormatDB

    mixed AddressFormatCore::_getFormatDB($id_country)





* Visibility: **protected**
* This method is defined in [classes/AddressFormat.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#552)


#### Arguments
* $id_country **mixed**



### getFieldsRequired

    mixed AddressFormatCore::getFieldsRequired()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AddressFormat.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AddressFormat.php#566)



