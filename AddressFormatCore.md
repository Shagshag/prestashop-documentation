AddressFormatCore
===============






* Class name: AddressFormatCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### _CLEANING_REGEX_

    const _CLEANING_REGEX_ = '#([^\w:_]+)#i'





Properties
----------


### $id_address_format

    public integer $id_address_format





* Visibility: **public**


### $id_country

    public integer $id_country





* Visibility: **public**


### $format

    public string $format





* Visibility: **public**


### $_errorFormatList

    protected mixed $_errorFormatList = array()





* Visibility: **protected**


### $definition

    public mixed $definition = array('table' => 'address_format', 'primary' => 'id_country', 'fields' => array('format' => array('type' => self::TYPE_HTML, 'validate' => 'isGenericName', 'required' => true), 'id_country' => array('type' => self::TYPE_INT)))





* Visibility: **public**
* This property is **static**.


### $requireFormFieldsList

    public mixed $requireFormFieldsList = array('firstname', 'lastname', 'address1', 'city', 'Country:name')





* Visibility: **public**
* This property is **static**.


### $forbiddenPropertyList

    public mixed $forbiddenPropertyList = array('deleted', 'date_add', 'alias', 'secure_key', 'note', 'newsletter', 'ip_registration_newsletter', 'newsletter_date_add', 'optin', 'passwd', 'last_passwd_gen', 'active', 'is_guest', 'date_upd', 'country', 'years', 'days', 'months', 'description', 'meta_description', 'short_description', 'link_rewrite', 'meta_title', 'meta_keywords', 'display_tax_label', 'need_zip_code', 'contains_states', 'call_prefixes', 'show_public_prices', 'max_payment', 'max_payment_days', 'geoloc_postcode', 'logged', 'account_number', 'groupBox', 'ape', 'max_payment', 'outstanding_allow_amount', 'call_prefix', 'definition', 'debug_list')





* Visibility: **public**
* This property is **static**.


### $forbiddenClassList

    public mixed $forbiddenClassList = array('Manufacturer', 'Supplier')





* Visibility: **public**
* This property is **static**.


Methods
-------


### _checkValidateClassField

    mixed AddressFormatCore::_checkValidateClassField($className, $fieldName, $isIdField)





* Visibility: **protected**


#### Arguments
* $className **mixed**
* $fieldName **mixed**
* $isIdField **mixed**



### _checkLiableAssociation

    mixed AddressFormatCore::_checkLiableAssociation($patternName, $fieldsValidate)





* Visibility: **protected**


#### Arguments
* $patternName **mixed**
* $fieldsValidate **mixed**



### checkFormatFields

    mixed AddressFormatCore::checkFormatFields()





* Visibility: **public**




### getErrorList

    mixed AddressFormatCore::getErrorList()





* Visibility: **public**




### _setOriginalDisplayFormat

    mixed AddressFormatCore::_setOriginalDisplayFormat($formattedValueList, $currentLine, $currentKeyList)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $formattedValueList **mixed**
* $currentLine **mixed**
* $currentKeyList **mixed**



### cleanOrderedAddress

    mixed AddressFormatCore::cleanOrderedAddress($orderedAddressField)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $orderedAddressField **mixed**



### getFormattedAddressFieldsValues

    mixed AddressFormatCore::getFormattedAddressFieldsValues($address, $addressFormat, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **mixed**
* $addressFormat **mixed**
* $id_lang **mixed**



### generateAddress

    string AddressFormatCore::generateAddress(\Address $address, array $patternRules, string $newLine, string $separator, array $style)

Generates the full address text



* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **Address**
* $patternRules **array** - &lt;p&gt;A defined rules array to avoid some pattern&lt;/p&gt;
* $newLine **string** - &lt;p&gt;A string containing the newLine format&lt;/p&gt;
* $separator **string** - &lt;p&gt;A string containing the separator format&lt;/p&gt;
* $style **array**



### generateAddressSmarty

    mixed AddressFormatCore::generateAddressSmarty($params, $smarty)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **mixed**
* $smarty **mixed**



### getValidateFields

    array AddressFormatCore::getValidateFields($className)

Returns selected fields required for an address in an array according to a selection hash



* Visibility: **public**
* This method is **static**.


#### Arguments
* $className **mixed**



### getLiableClass

    mixed AddressFormatCore::getLiableClass($className)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $className **mixed**



### getOrderedAddressFields

    Array AddressFormatCore::getOrderedAddressFields(integer $id_country, boolean $split_all, boolean $cleaned)

Returns address format fields in array by country



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **integer** - &lt;p&gt;If null using PS_COUNTRY_DEFAULT&lt;/p&gt;
* $split_all **boolean**
* $cleaned **boolean**



### getFormattedLayoutData

    mixed AddressFormatCore::getFormattedLayoutData($address)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **mixed**



### getAddressCountryFormat

    String AddressFormatCore::getAddressCountryFormat(integer $id_country)

Returns address format by country if not defined using default country



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **integer**



### getFormat

    String AddressFormatCore::getFormat(integer $id_country)

Returns address format by country



* Visibility: **public**


#### Arguments
* $id_country **integer**



### _getFormatDB

    mixed AddressFormatCore::_getFormatDB($id_country)





* Visibility: **protected**


#### Arguments
* $id_country **mixed**



### getFieldsRequired

    mixed AddressFormatCore::getFieldsRequired()





* Visibility: **public**
* This method is **static**.



