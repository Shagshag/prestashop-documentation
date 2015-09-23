Class CustomerCore
=====================





* Class name: CustomerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Customer.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L27)


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
* [$id_lang](#property-$id_lang)
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
* [$force_id](#property-$force_id)
* [$get_shop_from_context](#property-$get_shop_from_context)
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
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
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
* [duplicateObject](#method-duplicateObject)
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
* [isMultiShopField](#method-isMultiShopField)
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
* Source: [classes/Customer.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L195).


### <a name="property-$_customer_groups"></a>$_customer_groups

```php
protected mixed $_customer_groups = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L196).


### <a name="property-$_defaultGroupId"></a>$_defaultGroupId

```php
protected mixed $_defaultGroupId = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L194).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Customer.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L105).


### <a name="property-$ape"></a>$ape

```php
public string $ape
```





* Visibility: **public**
* Source: [classes/Customer.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L84).


### <a name="property-$birthday"></a>$birthday

```php
public string $birthday = null
```





* Visibility: **public**
* Source: [classes/Customer.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L57).


### <a name="property-$company"></a>$company

```php
public string $company
```





* Visibility: **public**
* Source: [classes/Customer.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L78).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L114).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Customer.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L117).


### <a name="property-$days"></a>$days

```php
public mixed $days
```





* Visibility: **public**
* Source: [classes/Customer.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L120).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'customer', 'primary' => 'id_customer', 'fields' => array('secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5', 'copy_post' => false), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswd', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'id_gender' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'birthday' => array('type' => self::TYPE_DATE, 'validate' => 'isBirthDate'), 'newsletter' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'newsletter_date_add' => array('type' => self::TYPE_DATE, 'copy_post' => false), 'ip_registration_newsletter' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'optin' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'website' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'siret' => array('type' => self::TYPE_STRING, 'validate' => 'isSiret'), 'ape' => array('type' => self::TYPE_STRING, 'validate' => 'isApe'), 'outstanding_allow_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'copy_post' => false), 'show_public_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_risk' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'max_payment_days' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'note' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 65000, 'copy_post' => false), 'is_guest' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_default_group' => array('type' => self::TYPE_INT, 'copy_post' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Customer.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L157).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Customer.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L111).


### <a name="property-$email"></a>$email

```php
public string $email
```





* Visibility: **public**
* Source: [classes/Customer.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L60).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Customer.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L54).


### <a name="property-$geoloc_id_country"></a>$geoloc_id_country

```php
public integer $geoloc_id_country
```





* Visibility: **public**
* Source: [classes/Customer.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L124).


### <a name="property-$geoloc_id_state"></a>$geoloc_id_state

```php
public integer $geoloc_id_state
```





* Visibility: **public**
* Source: [classes/Customer.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L126).


### <a name="property-$geoloc_postcode"></a>$geoloc_postcode

```php
public string $geoloc_postcode
```





* Visibility: **public**
* Source: [classes/Customer.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L128).


### <a name="property-$groupBox"></a>$groupBox

```php
public mixed $groupBox
```





* Visibility: **public**
* Source: [classes/Customer.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L136).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Customer.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L29).


### <a name="property-$id_default_group"></a>$id_default_group

```php
public integer $id_default_group
```





* Visibility: **public**
* Source: [classes/Customer.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L45).


### <a name="property-$id_gender"></a>$id_gender

```php
public integer $id_gender
```





* Visibility: **public**
* Source: [classes/Customer.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L42).


### <a name="property-$id_guest"></a>$id_guest

```php
public integer $id_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L134).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/Customer.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L48).


### <a name="property-$id_risk"></a>$id_risk

```php
public integer $id_risk
```





* Visibility: **public**
* Source: [classes/Customer.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L93).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Customer.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L31).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* Source: [classes/Customer.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L33).


### <a name="property-$ip_registration_newsletter"></a>$ip_registration_newsletter

```php
public string $ip_registration_newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L66).


### <a name="property-$is_guest"></a>$is_guest

```php
public boolean $is_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L108).


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

```php
public string $last_passwd_gen
```





* Visibility: **public**
* Source: [classes/Customer.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L102).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Customer.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L51).


### <a name="property-$logged"></a>$logged

```php
public boolean $logged
```





* Visibility: **public**
* Source: [classes/Customer.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L131).


### <a name="property-$max_payment_days"></a>$max_payment_days

```php
public integer $max_payment_days
```





* Visibility: **public**
* Source: [classes/Customer.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L96).


### <a name="property-$months"></a>$months

```php
public mixed $months
```





* Visibility: **public**
* Source: [classes/Customer.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L121).


### <a name="property-$newsletter"></a>$newsletter

```php
public boolean $newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L63).


### <a name="property-$newsletter_date_add"></a>$newsletter_date_add

```php
public string $newsletter_date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L69).


### <a name="property-$note"></a>$note

```php
public string $note
```





* Visibility: **public**
* Source: [classes/Customer.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L39).


### <a name="property-$optin"></a>$optin

```php
public boolean $optin
```





* Visibility: **public**
* Source: [classes/Customer.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L72).


### <a name="property-$outstanding_allow_amount"></a>$outstanding_allow_amount

```php
public float $outstanding_allow_amount
```





* Visibility: **public**
* Source: [classes/Customer.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L87).


### <a name="property-$passwd"></a>$passwd

```php
public integer $passwd
```





* Visibility: **public**
* Source: [classes/Customer.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L99).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/Customer.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L36).


### <a name="property-$show_public_prices"></a>$show_public_prices

```php
public integer $show_public_prices
```





* Visibility: **public**
* Source: [classes/Customer.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L90).


### <a name="property-$siret"></a>$siret

```php
public string $siret
```





* Visibility: **public**
* Source: [classes/Customer.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L81).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_default_group' => array('xlink_resource' => 'groups'), 'id_lang' => array('xlink_resource' => 'languages'), 'newsletter_date_add' => array(), 'ip_registration_newsletter' => array(), 'last_passwd_gen' => array('setter' => null), 'secure_key' => array('setter' => null), 'deleted' => array(), 'passwd' => array('setter' => 'setWsPasswd')), 'associations' => array('groups' => array('resource' => 'group')))
```





* Visibility: **protected**
* Source: [classes/Customer.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L138).


### <a name="property-$website"></a>$website

```php
public string $website
```





* Visibility: **public**
* Source: [classes/Customer.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L75).


### <a name="property-$years"></a>$years

```php
public mixed $years
```





* Visibility: **public**
* Source: [classes/Customer.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L119).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L130).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L80).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L65).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L95).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L85).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L90).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L105).


### <a name="property-$force_id"></a>$force_id

```php
public \boolean, $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L145).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L63).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L61).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L75).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L116).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L119).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L70).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L110).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L135).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CustomerCore::__construct($id)
```





* Visibility: **public**
* Source: [classes/Customer.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L198)


#### Arguments
* $id **mixed**



### <a name="method-add"></a>add

```php
mixed CustomerCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Customer.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L204)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1218)


#### Arguments
* $fields **mixed**



### <a name="method-addGroups"></a>addGroups

```php
mixed CustomerCore::addGroups($groups)
```





* Visibility: **public**
* Source: [classes/Customer.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L625)


#### Arguments
* $groups **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1270)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1205)




### <a name="method-checkPassword"></a>checkPassword

```php
boolean CustomerCore::checkPassword($id_customer, string $passwd)
```

Check if customer password is the right one



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L485)


#### Arguments
* $id_customer **mixed**
* $passwd **string** - Password



### <a name="method-cleanGroups"></a>cleanGroups

```php
mixed CustomerCore::cleanGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L620)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1232)


#### Arguments
* $all **mixed**



### <a name="method-customerExists"></a>customerExists

```php
\Customer CustomerCore::customerExists(string $email, $return_id, $ignore_guest)
```

Check if e-mail is already registered in database



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L387)


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
* Source: [classes/Customer.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L416)


#### Arguments
* $id_customer **integer** - Customer ID
* $id_address **integer** - Address ID



### <a name="method-customerIdExists"></a>customerIdExists

```php
mixed CustomerCore::customerIdExists($id_customer)
```





* Visibility: **public**
* Source: [classes/Customer.php line 585](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L585)


#### Arguments
* $id_customer **mixed**



### <a name="method-customerIdExistsStatic"></a>customerIdExistsStatic

```php
mixed CustomerCore::customerIdExistsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 590](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L590)


#### Arguments
* $id_customer **mixed**



### <a name="method-delete"></a>delete

```php
mixed CustomerCore::delete()
```





* Visibility: **public**
* Source: [classes/Customer.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L252)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1401](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1401)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L743)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 988](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L988)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\new ObjectModelCore::duplicateObject()
```

Duplicate current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L527)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1314](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1314)


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
* Source: [classes/ObjectModel.php line 1438](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1438)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L330)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes, $purify)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L377)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**
* $purify **mixed**



### <a name="method-getAddresses"></a>getAddresses

```php
array CustomerCore::getAddresses(integer $id_lang)
```

Return customer addresses



* Visibility: **public**
* Source: [classes/Customer.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L443)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getAddressesTotalById"></a>getAddressesTotalById

```php
integer CustomerCore::getAddressesTotalById(integer $id_customer)
```

Count the number of addresses for a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L469)


#### Arguments
* $id_customer **integer** - Customer ID



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1299](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1299)




### <a name="method-getBoughtProducts"></a>getBoughtProducts

```php
mixed CustomerCore::getBoughtProducts()
```





* Visibility: **public**
* Source: [classes/Customer.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L669)




### <a name="method-getByEmail"></a>getByEmail

```php
\Customer CustomerCore::getByEmail(string $email, string $passwd, $ignore_guest)
```

Return customer instance from its e-mail (optionnaly check password)



* Visibility: **public**
* Source: [classes/Customer.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L313)


#### Arguments
* $email **string** - e-mail
* $passwd **string** - Password is also checked if specified
* $ignore_guest **mixed**



### <a name="method-getCurrentCountry"></a>getCurrentCountry

```php
mixed CustomerCore::getCurrentCountry($id_customer, \Cart $cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L691)


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
* Source: [classes/Customer.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L297)




### <a name="method-getCustomersByEmail"></a>getCustomersByEmail

```php
array CustomerCore::getCustomersByEmail($email)
```

Retrieve customers by email address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L345)


#### Arguments
* $email **mixed**



### <a name="method-getDefaultGroupId"></a>getDefaultGroupId

```php
mixed CustomerCore::getDefaultGroupId($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 677](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L677)


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
* Source: [classes/ObjectModel.php line 1544](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1544)


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
* Source: [classes/ObjectModel.php line 1651](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1651)


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
* Source: [classes/ObjectModel.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L258)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L295)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1197](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1197)


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
* Source: [classes/ObjectModel.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L281)




### <a name="method-getGroups"></a>getGroups

```php
mixed CustomerCore::getGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 655](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L655)




### <a name="method-getGroupsStatic"></a>getGroupsStatic

```php
mixed CustomerCore::getGroupsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 634](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L634)


#### Arguments
* $id_customer **mixed**



### <a name="method-getLastCart"></a>getLastCart

```php
mixed CustomerCore::getLastCart($with_order)
```





* Visibility: **public**
* Source: [classes/Customer.php line 822](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L822)


#### Arguments
* $with_order **mixed**



### <a name="method-getLastConnections"></a>getLastConnections

```php
mixed CustomerCore::getLastConnections()
```





* Visibility: **public**
* Source: [classes/Customer.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L565)




### <a name="method-getOutstanding"></a>getOutstanding

```php
mixed CustomerCore::getOutstanding()
```





* Visibility: **public**
* Source: [classes/Customer.php line 832](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L832)




### <a name="method-getStats"></a>getStats

```php
array CustomerCore::getStats()
```

Return several useful statistics about customer



* Visibility: **public**
* Source: [classes/Customer.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L541)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L778)


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
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L153)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed CustomerCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* Source: [classes/Customer.php line 877](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L877)


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
* Source: [classes/ObjectModel.php line 1060](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1060)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWsGroups"></a>getWsGroups

```php
mixed CustomerCore::getWsGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L854)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1339](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1339)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1476](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1476)


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
* Source: [classes/ObjectModel.php line 1495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1495)


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
* Source: [classes/ObjectModel.php line 1247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1247)


#### Arguments
* $id_shop **integer**



### <a name="method-isBanned"></a>isBanned

```php
boolean CustomerCore::isBanned($id_customer)
```

Check id the customer is active or not



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L361)


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
* Source: [classes/ObjectModel.php line 1456](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1456)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isGuest"></a>isGuest

```php
mixed CustomerCore::isGuest()
```





* Visibility: **public**
* Source: [classes/Customer.php line 720](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L720)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1356](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1356)




### <a name="method-isLogged"></a>isLogged

```php
boolean CustomerCore::isLogged(boolean $with_guest)
```

Check customer informations and return customer validity



* Visibility: **public**
* Source: [classes/Customer.php line 786](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L786)


#### Arguments
* $with_guest **boolean**



### <a name="method-isMultiShopField"></a>isMultiShopField

```php
mixed ObjectModelCore::isMultiShopField($field)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1351](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1351)


#### Arguments
* $field **mixed**



### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1346](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1346)




### <a name="method-isUsed"></a>isUsed

```php
mixed CustomerCore::isUsed()
```





* Visibility: **public**
* Source: [classes/Customer.php line 663](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L663)




### <a name="method-logout"></a>logout

```php
mixed CustomerCore::logout()
```

Logout



* Visibility: **public**
* Source: [classes/Customer.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L802)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L794)


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
* Source: [classes/Customer.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L815)




### <a name="method-resetAddressCache"></a>resetAddressCache

```php
mixed CustomerCore::resetAddressCache($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L431)


#### Arguments
* $id_customer **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L423)


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
* Source: [classes/Customer.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L526)


#### Arguments
* $ip **string** - Searched string



### <a name="method-searchByName"></a>searchByName

```php
array CustomerCore::searchByName(string $query)
```

Light back office search for customers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 508](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L508)


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
* Source: [classes/ObjectModel.php line 1582](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1582)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1677](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1677)


#### Arguments
* $fields **array**



### <a name="method-setWsGroups"></a>setWsGroups

```php
mixed CustomerCore::setWsGroups($result)
```





* Visibility: **public**
* Source: [classes/Customer.php line 864](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L864)


#### Arguments
* $result **mixed**



### <a name="method-setWsPasswd"></a>setWsPasswd

```php
mixed CustomerCore::setWsPasswd($passwd)
```





* Visibility: **public**
* Source: [classes/Customer.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L767)


#### Arguments
* $passwd **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed CustomerCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Customer.php line 708](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L708)




### <a name="method-transformToCustomer"></a>transformToCustomer

```php
mixed CustomerCore::transformToCustomer($id_lang, $password)
```





* Visibility: **public**
* Source: [classes/Customer.php line 725](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L725)


#### Arguments
* $id_lang **mixed**
* $password **mixed**



### <a name="method-update"></a>update

```php
mixed CustomerCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Customer.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L230)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateGroup"></a>updateGroup

```php
mixed CustomerCore::updateGroup(array $list)
```

Update customer groups associated to the object



* Visibility: **public**
* Source: [classes/Customer.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Customer.php#L609)


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
* Source: [classes/ObjectModel.php line 1371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1371)


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
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1006)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1012](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1012)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang, $skip, $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 905](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L905)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**
* $skip **mixed**
* $human_errors **mixed**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 832](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L832)


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
* Source: [classes/ObjectModel.php line 861](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L861)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/ObjectModel.php#L1174)


#### Arguments
* $htmlentities **mixed**


