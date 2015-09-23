Class CustomerCore
=====================





* Class name: CustomerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Customer.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L28)


Contents
--------


### Properties

* [$_customerHasAddress](#property-$_customerHasAddress)
* [$_customer_groups](#property-$_customer_groups)
* [$_defaultGroupId](#property-$_defaultGroupId)
* [$active](#property-$active)
* [$ape](#property-$ape)
* [$birthday](#property-$birthday)
* [$company](#property-$company)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$days](#property-$days)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$email](#property-$email)
* [$firstname](#property-$firstname)
* [$geoloc_id_country](#property-$geoloc_id_country)
* [$geoloc_id_state](#property-$geoloc_id_state)
* [$geoloc_postcode](#property-$geoloc_postcode)
* [$groupBox](#property-$groupBox)
* [$id](#property-$id)
* [$id_default_group](#property-$id_default_group)
* [$id_gender](#property-$id_gender)
* [$id_guest](#property-$id_guest)
* [$id_risk](#property-$id_risk)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$ip_registration_newsletter](#property-$ip_registration_newsletter)
* [$is_guest](#property-$is_guest)
* [$last_passwd_gen](#property-$last_passwd_gen)
* [$lastname](#property-$lastname)
* [$logged](#property-$logged)
* [$max_payment_days](#property-$max_payment_days)
* [$months](#property-$months)
* [$newsletter](#property-$newsletter)
* [$newsletter_date_add](#property-$newsletter_date_add)
* [$note](#property-$note)
* [$optin](#property-$optin)
* [$outstanding_allow_amount](#property-$outstanding_allow_amount)
* [$passwd](#property-$passwd)
* [$secure_key](#property-$secure_key)
* [$show_public_prices](#property-$show_public_prices)
* [$siret](#property-$siret)
* [$webserviceParameters](#property-$webserviceParameters)
* [$website](#property-$website)
* [$years](#property-$years)
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
* [addGroups](#method-addGroups)
* [associateTo](#method-associateTo)
* [checkPassword](#method-checkPassword)
* [cleanGroups](#method-cleanGroups)
* [clearCache](#method-clearCache)
* [customerExists](#method-customerExists)
* [customerHasAddress](#method-customerHasAddress)
* [customerIdExists](#method-customerIdExists)
* [customerIdExistsStatic](#method-customerIdExistsStatic)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAddresses](#method-getAddresses)
* [getAddressesTotalById](#method-getAddressesTotalById)
* [getAssociatedShops](#method-getAssociatedShops)
* [getBoughtProducts](#method-getBoughtProducts)
* [getByEmail](#method-getByEmail)
* [getCurrentCountry](#method-getCurrentCountry)
* [getCustomers](#method-getCustomers)
* [getCustomersByEmail](#method-getCustomersByEmail)
* [getDefaultGroupId](#method-getDefaultGroupId)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getGroups](#method-getGroups)
* [getGroupsStatic](#method-getGroupsStatic)
* [getLastCart](#method-getLastCart)
* [getLastConnections](#method-getLastConnections)
* [getOutstanding](#method-getOutstanding)
* [getStats](#method-getStats)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsGroups](#method-getWsGroups)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isBanned](#method-isBanned)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isGuest](#method-isGuest)
* [isLangMultishop](#method-isLangMultishop)
* [isLogged](#method-isLogged)
* [isMultishop](#method-isMultishop)
* [isUsed](#method-isUsed)
* [logout](#method-logout)
* [makeTranslationFields](#method-makeTranslationFields)
* [mylogout](#method-mylogout)
* [resetAddressCache](#method-resetAddressCache)
* [save](#method-save)
* [searchByIp](#method-searchByIp)
* [searchByName](#method-searchByName)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setWsGroups](#method-setWsGroups)
* [setWsPasswd](#method-setWsPasswd)
* [toggleStatus](#method-toggleStatus)
* [transformToCustomer](#method-transformToCustomer)
* [update](#method-update)
* [updateGroup](#method-updateGroup)
* [updateMultishopTable](#method-updateMultishopTable)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$_customerHasAddress"></a>$_customerHasAddress

```php
protected mixed $_customerHasAddress = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L191).


### <a name="property-$_customer_groups"></a>$_customer_groups

```php
protected mixed $_customer_groups = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L192).


### <a name="property-$_defaultGroupId"></a>$_defaultGroupId

```php
protected mixed $_defaultGroupId = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L190).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Customer.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L103).


### <a name="property-$ape"></a>$ape

```php
public string $ape
```





* Visibility: **public**
* Source: [classes/Customer.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L82).


### <a name="property-$birthday"></a>$birthday

```php
public string $birthday = null
```





* Visibility: **public**
* Source: [classes/Customer.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L55).


### <a name="property-$company"></a>$company

```php
public string $company
```





* Visibility: **public**
* Source: [classes/Customer.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L76).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L112).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Customer.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L115).


### <a name="property-$days"></a>$days

```php
public mixed $days
```





* Visibility: **public**
* Source: [classes/Customer.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L118).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'customer', 'primary' => 'id_customer', 'fields' => array('secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5', 'copy_post' => false), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswd', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'id_gender' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'birthday' => array('type' => self::TYPE_DATE, 'validate' => 'isBirthDate'), 'newsletter' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'newsletter_date_add' => array('type' => self::TYPE_DATE, 'copy_post' => false), 'ip_registration_newsletter' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'optin' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'website' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'siret' => array('type' => self::TYPE_STRING, 'validate' => 'isSiret'), 'ape' => array('type' => self::TYPE_STRING, 'validate' => 'isApe'), 'outstanding_allow_amount' => array('type' => self::TYPE_INT, 'validate' => 'isFloat', 'copy_post' => false), 'show_public_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_risk' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'max_payment_days' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'note' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 65000, 'copy_post' => false), 'is_guest' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_default_group' => array('type' => self::TYPE_INT, 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Customer.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L154).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Customer.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L109).


### <a name="property-$email"></a>$email

```php
public string $email
```





* Visibility: **public**
* Source: [classes/Customer.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L58).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Customer.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L52).


### <a name="property-$geoloc_id_country"></a>$geoloc_id_country

```php
public integer $geoloc_id_country
```





* Visibility: **public**
* Source: [classes/Customer.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L122).


### <a name="property-$geoloc_id_state"></a>$geoloc_id_state

```php
public integer $geoloc_id_state
```





* Visibility: **public**
* Source: [classes/Customer.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L124).


### <a name="property-$geoloc_postcode"></a>$geoloc_postcode

```php
public string $geoloc_postcode
```





* Visibility: **public**
* Source: [classes/Customer.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L126).


### <a name="property-$groupBox"></a>$groupBox

```php
public mixed $groupBox
```





* Visibility: **public**
* Source: [classes/Customer.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L134).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Customer.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L30).


### <a name="property-$id_default_group"></a>$id_default_group

```php
public integer $id_default_group = _PS_DEFAULT_CUSTOMER_GROUP_
```





* Visibility: **public**
* Source: [classes/Customer.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L46).


### <a name="property-$id_gender"></a>$id_gender

```php
public integer $id_gender
```





* Visibility: **public**
* Source: [classes/Customer.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L43).


### <a name="property-$id_guest"></a>$id_guest

```php
public integer $id_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L132).


### <a name="property-$id_risk"></a>$id_risk

```php
public integer $id_risk
```





* Visibility: **public**
* Source: [classes/Customer.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L91).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Customer.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L32).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* Source: [classes/Customer.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L34).


### <a name="property-$ip_registration_newsletter"></a>$ip_registration_newsletter

```php
public string $ip_registration_newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L64).


### <a name="property-$is_guest"></a>$is_guest

```php
public boolean $is_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L106).


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

```php
public \datetime $last_passwd_gen
```





* Visibility: **public**
* Source: [classes/Customer.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L100).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Customer.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L49).


### <a name="property-$logged"></a>$logged

```php
public boolean $logged
```





* Visibility: **public**
* Source: [classes/Customer.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L129).


### <a name="property-$max_payment_days"></a>$max_payment_days

```php
public integer $max_payment_days
```





* Visibility: **public**
* Source: [classes/Customer.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L94).


### <a name="property-$months"></a>$months

```php
public mixed $months
```





* Visibility: **public**
* Source: [classes/Customer.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L119).


### <a name="property-$newsletter"></a>$newsletter

```php
public boolean $newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L61).


### <a name="property-$newsletter_date_add"></a>$newsletter_date_add

```php
public string $newsletter_date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L67).


### <a name="property-$note"></a>$note

```php
public string $note
```





* Visibility: **public**
* Source: [classes/Customer.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L40).


### <a name="property-$optin"></a>$optin

```php
public boolean $optin
```





* Visibility: **public**
* Source: [classes/Customer.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L70).


### <a name="property-$outstanding_allow_amount"></a>$outstanding_allow_amount

```php
public float $outstanding_allow_amount
```





* Visibility: **public**
* Source: [classes/Customer.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L85).


### <a name="property-$passwd"></a>$passwd

```php
public integer $passwd
```





* Visibility: **public**
* Source: [classes/Customer.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L97).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/Customer.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L37).


### <a name="property-$show_public_prices"></a>$show_public_prices

```php
public integer $show_public_prices
```





* Visibility: **public**
* Source: [classes/Customer.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L88).


### <a name="property-$siret"></a>$siret

```php
public string $siret
```





* Visibility: **public**
* Source: [classes/Customer.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L79).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_default_group' => array('xlink_resource' => 'groups'), 'newsletter_date_add' => array(), 'ip_registration_newsletter' => array(), 'last_passwd_gen' => array('setter' => null), 'secure_key' => array('setter' => null), 'deleted' => array(), 'passwd' => array('setter' => 'setWsPasswd')), 'associations' => array('groups' => array('resource' => 'group')))
```





* Visibility: **protected**
* Source: [classes/Customer.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L136).


### <a name="property-$website"></a>$website

```php
public string $website
```





* Visibility: **public**
* Source: [classes/Customer.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L73).


### <a name="property-$years"></a>$years

```php
public mixed $years
```





* Visibility: **public**
* Source: [classes/Customer.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L117).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L141).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L131).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L106).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L64).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L58).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L117).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L120).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L136).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L169)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed CustomerCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Customer.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L194)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1097](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1097)


#### Arguments
* $fields **mixed**



### <a name="method-addGroups"></a>addGroups

```php
mixed CustomerCore::addGroups($groups)
```





* Visibility: **public**
* Source: [classes/Customer.php line 584](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L584)


#### Arguments
* $groups **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1144)


#### Arguments
* $id_shops **integer|array**



### <a name="method-checkPassword"></a>checkPassword

```php
boolean CustomerCore::checkPassword($id_customer, string $passwd)
```

Check if customer password is the right one



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L455)


#### Arguments
* $id_customer **mixed**
* $passwd **string** - Password



### <a name="method-cleanGroups"></a>cleanGroups

```php
mixed CustomerCore::cleanGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L579)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1111](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1111)


#### Arguments
* $all **mixed**



### <a name="method-customerExists"></a>customerExists

```php
\Customer CustomerCore::customerExists(string $email, $return_id, $ignore_guest)
```

Check if e-mail is already registered in database



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L372)


#### Arguments
* $email **string** - e-mail
* $return_id **mixed** - boolean
* $ignore_guest **mixed** - boolean, to exclude guest customer



### <a name="method-customerHasAddress"></a>customerHasAddress

```php
boolean CustomerCore::customerHasAddress(integer $id_customer, integer $id_address)
```

Check if an address is owned by a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L396)


#### Arguments
* $id_customer **integer** - Customer ID
* $id_address **integer** - Address ID



### <a name="method-customerIdExists"></a>customerIdExists

```php
mixed CustomerCore::customerIdExists($id_customer)
```





* Visibility: **public**
* Source: [classes/Customer.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L550)


#### Arguments
* $id_customer **mixed**



### <a name="method-customerIdExistsStatic"></a>customerIdExistsStatic

```php
mixed CustomerCore::customerIdExistsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L555)


#### Arguments
* $id_customer **mixed**



### <a name="method-delete"></a>delete

```php
mixed CustomerCore::delete()
```





* Visibility: **public**
* Source: [classes/Customer.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L241)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1270](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1270)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L690)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L890)


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
* Source: [classes/ObjectModel.php line 1188](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1188)


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
* Source: [classes/ObjectModel.php line 1307](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1307)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L335)


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
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAddresses"></a>getAddresses

```php
array CustomerCore::getAddresses(integer $id_lang)
```

Return customer addresses



* Visibility: **public**
* Source: [classes/Customer.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L422)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getAddressesTotalById"></a>getAddressesTotalById

```php
integer CustomerCore::getAddressesTotalById(integer $id_customer)
```

Count the number of addresses for a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L439)


#### Arguments
* $id_customer **integer** - Customer ID



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1173)




### <a name="method-getBoughtProducts"></a>getBoughtProducts

```php
mixed CustomerCore::getBoughtProducts()
```





* Visibility: **public**
* Source: [classes/Customer.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L625)




### <a name="method-getByEmail"></a>getByEmail

```php
\Customer CustomerCore::getByEmail(string $email, string $passwd)
```

Return customer instance from its e-mail (optionnaly check password)



* Visibility: **public**
* Source: [classes/Customer.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L302)


#### Arguments
* $email **string** - e-mail
* $passwd **string** - Password is also checked if specified



### <a name="method-getCurrentCountry"></a>getCurrentCountry

```php
mixed CustomerCore::getCurrentCountry($id_customer, \Cart $cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L647)


#### Arguments
* $id_customer **mixed**
* $cart **[Cart](class.CartCore.md)**



### <a name="method-getCustomers"></a>getCustomers

```php
array CustomerCore::getCustomers()
```

Return customers list



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L286)




### <a name="method-getCustomersByEmail"></a>getCustomersByEmail

```php
array CustomerCore::getCustomersByEmail($email)
```

Retrieve customers by email address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L333)


#### Arguments
* $email **mixed**



### <a name="method-getDefaultGroupId"></a>getDefaultGroupId

```php
mixed CustomerCore::getDefaultGroupId($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L633)


#### Arguments
* $id_customer **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1413](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1413)


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
* Source: [classes/ObjectModel.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1490)


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
* Source: [classes/ObjectModel.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L263)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L300)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1089)


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
* Source: [classes/ObjectModel.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L286)




### <a name="method-getGroups"></a>getGroups

```php
mixed CustomerCore::getGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L611)




### <a name="method-getGroupsStatic"></a>getGroupsStatic

```php
mixed CustomerCore::getGroupsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 593](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L593)


#### Arguments
* $id_customer **mixed**



### <a name="method-getLastCart"></a>getLastCart

```php
mixed CustomerCore::getLastCart($with_order)
```





* Visibility: **public**
* Source: [classes/Customer.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L778)


#### Arguments
* $with_order **mixed**



### <a name="method-getLastConnections"></a>getLastConnections

```php
mixed CustomerCore::getLastConnections()
```





* Visibility: **public**
* Source: [classes/Customer.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L530)




### <a name="method-getOutstanding"></a>getOutstanding

```php
mixed CustomerCore::getOutstanding()
```





* Visibility: **public**
* Source: [classes/Customer.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L788)




### <a name="method-getStats"></a>getStats

```php
array CustomerCore::getStats()
```

Return several useful statistics about customer



* Visibility: **public**
* Source: [classes/Customer.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L506)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L722)


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
* Source: [classes/ObjectModel.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L149)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed CustomerCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* Source: [classes/Customer.php line 833](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L833)


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
* Source: [classes/ObjectModel.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L957)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWsGroups"></a>getWsGroups

```php
mixed CustomerCore::getWsGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 810](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L810)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1213](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1213)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1345](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1345)


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
* Source: [classes/ObjectModel.php line 1364](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1364)


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
* Source: [classes/ObjectModel.php line 1126](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1126)


#### Arguments
* $id_shop **integer**



### <a name="method-isBanned"></a>isBanned

```php
boolean CustomerCore::isBanned($id_customer)
```

Check id the customer is active or not



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L349)


#### Arguments
* $id_customer **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1325](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1325)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isGuest"></a>isGuest

```php
mixed CustomerCore::isGuest()
```





* Visibility: **public**
* Source: [classes/Customer.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L676)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1225](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1225)




### <a name="method-isLogged"></a>isLogged

```php
boolean CustomerCore::isLogged(boolean $with_guest)
```

Check customer informations and return customer validity



* Visibility: **public**
* Source: [classes/Customer.php line 742](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L742)


#### Arguments
* $with_guest **boolean**



### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1220](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1220)




### <a name="method-isUsed"></a>isUsed

```php
mixed CustomerCore::isUsed()
```





* Visibility: **public**
* Source: [classes/Customer.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L619)




### <a name="method-logout"></a>logout

```php
mixed CustomerCore::logout()
```

Logout



* Visibility: **public**
* Source: [classes/Customer.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L758)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L738)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-mylogout"></a>mylogout

```php
mixed CustomerCore::mylogout()
```

Soft logout, delete everything links to the customer
but leave there affiliate's informations



* Visibility: **public**
* Source: [classes/Customer.php line 771](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L771)




### <a name="method-resetAddressCache"></a>resetAddressCache

```php
mixed CustomerCore::resetAddressCache($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L410)


#### Arguments
* $id_customer **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L425)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-searchByIp"></a>searchByIp

```php
mixed CustomerCore::searchByIp(string $ip)
```

Search for customers by ip address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 491](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L491)


#### Arguments
* $ip **string** - Searched string



### <a name="method-searchByName"></a>searchByName

```php
array CustomerCore::searchByName(string $query)
```

Light back office search for customers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L473)


#### Arguments
* $query **string** - Searched string



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1436](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1436)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1516](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1516)


#### Arguments
* $fields **array**



### <a name="method-setWsGroups"></a>setWsGroups

```php
mixed CustomerCore::setWsGroups($result)
```





* Visibility: **public**
* Source: [classes/Customer.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L820)


#### Arguments
* $result **mixed**



### <a name="method-setWsPasswd"></a>setWsPasswd

```php
mixed CustomerCore::setWsPasswd($passwd)
```





* Visibility: **public**
* Source: [classes/Customer.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L723)


#### Arguments
* $passwd **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed CustomerCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Customer.php line 664](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L664)




### <a name="method-transformToCustomer"></a>transformToCustomer

```php
mixed CustomerCore::transformToCustomer($id_lang, $password)
```





* Visibility: **public**
* Source: [classes/Customer.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L681)


#### Arguments
* $id_lang **mixed**
* $password **mixed**



### <a name="method-update"></a>update

```php
mixed CustomerCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Customer.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L219)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateGroup"></a>updateGroup

```php
mixed CustomerCore::updateGroup(array $list)
```

Update customer groups associated to the object



* Visibility: **public**
* Source: [classes/Customer.php line 570](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customer.php#L570)


#### Arguments
* $list **array** - groups



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1240](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1240)


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
* Source: [classes/ObjectModel.php line 905](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L905)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L911)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L843)


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
* Source: [classes/ObjectModel.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L776)


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
* Source: [classes/ObjectModel.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L805)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1067](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/ObjectModel.php#L1067)


#### Arguments
* $htmlentities **mixed**


