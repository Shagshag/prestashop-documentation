Class CustomerCore
=====================





* Class name: CustomerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Customer.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L28)


Contents
--------


### Properties

* [$_customerHasAddress](#property-$_customerHasAddress)
* [$_customer_groups](#property-$_customer_groups)
* [$_defaultGroupId](#property-$_defaultGroupId)
* [$active](#property-$active)
* [$birthday](#property-$birthday)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$days](#property-$days)
* [$deleted](#property-$deleted)
* [$email](#property-$email)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$firstname](#property-$firstname)
* [$geoloc_id_country](#property-$geoloc_id_country)
* [$geoloc_id_state](#property-$geoloc_id_state)
* [$geoloc_postcode](#property-$geoloc_postcode)
* [$id](#property-$id)
* [$id_default_group](#property-$id_default_group)
* [$id_gender](#property-$id_gender)
* [$id_group_shop](#property-$id_group_shop)
* [$id_guest](#property-$id_guest)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$ip_registration_newsletter](#property-$ip_registration_newsletter)
* [$is_guest](#property-$is_guest)
* [$last_passwd_gen](#property-$last_passwd_gen)
* [$lastname](#property-$lastname)
* [$logged](#property-$logged)
* [$months](#property-$months)
* [$newsletter](#property-$newsletter)
* [$newsletter_date_add](#property-$newsletter_date_add)
* [$note](#property-$note)
* [$optin](#property-$optin)
* [$passwd](#property-$passwd)
* [$secure_key](#property-$secure_key)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)
* [$years](#property-$years)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id_lang](#property-$id_lang)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)

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
* [getAddresses](#method-getAddresses)
* [getAddressesTotalById](#method-getAddressesTotalById)
* [getBoughtProducts](#method-getBoughtProducts)
* [getByEmail](#method-getByEmail)
* [getCurrentCountry](#method-getCurrentCountry)
* [getCustomers](#method-getCustomers)
* [getDefaultGroupId](#method-getDefaultGroupId)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getGroups](#method-getGroups)
* [getGroupsStatic](#method-getGroupsStatic)
* [getIdentifier](#method-getIdentifier)
* [getLastCart](#method-getLastCart)
* [getLastConnections](#method-getLastConnections)
* [getStats](#method-getStats)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isBanned](#method-isBanned)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isGuest](#method-isGuest)
* [isLangMultishop](#method-isLangMultishop)
* [isLogged](#method-isLogged)
* [isUsed](#method-isUsed)
* [logout](#method-logout)
* [makeTranslationFields](#method-makeTranslationFields)
* [mylogout](#method-mylogout)
* [resetAddressCache](#method-resetAddressCache)
* [save](#method-save)
* [searchByIp](#method-searchByIp)
* [searchByName](#method-searchByName)
* [setWsPasswd](#method-setWsPasswd)
* [toggleStatus](#method-toggleStatus)
* [transformToCustomer](#method-transformToCustomer)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_customerHasAddress"></a>$_customerHasAddress

```php
protected mixed $_customerHasAddress = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L147).


### <a name="property-$_customer_groups"></a>$_customer_groups

```php
protected mixed $_customer_groups = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L148).


### <a name="property-$_defaultGroupId"></a>$_defaultGroupId

```php
protected mixed $_defaultGroupId = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L146).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Customer.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L79).


### <a name="property-$birthday"></a>$birthday

```php
public string $birthday = null
```





* Visibility: **public**
* Source: [classes/Customer.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L55).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L88).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Customer.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L91).


### <a name="property-$days"></a>$days

```php
public mixed $days
```





* Visibility: **public**
* Source: [classes/Customer.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L94).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Customer.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L85).


### <a name="property-$email"></a>$email

```php
public string $email
```





* Visibility: **public**
* Source: [classes/Customer.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L58).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('lastname', 'passwd', 'firstname', 'email')
```





* Visibility: **protected**
* Source: [classes/Customer.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L112).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('lastname' => 32, 'passwd' => 32, 'firstname' => 32, 'email' => 128, 'note' => 65000)
```





* Visibility: **protected**
* Source: [classes/Customer.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L113).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('secure_key' => 'isMd5', 'lastname' => 'isName', 'firstname' => 'isName', 'email' => 'isEmail', 'passwd' => 'isPasswd', 'id_gender' => 'isUnsignedId', 'birthday' => 'isBirthDate', 'newsletter' => 'isBool', 'optin' => 'isBool', 'active' => 'isBool', 'note' => 'isCleanHtml', 'is_guest' => 'isBool', 'id_shop' => 'isUnsignedId', 'id_group_shop' => 'isUnsignedId')
```





* Visibility: **protected**
* Source: [classes/Customer.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L114).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Customer.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L52).


### <a name="property-$geoloc_id_country"></a>$geoloc_id_country

```php
public integer $geoloc_id_country
```





* Visibility: **public**
* Source: [classes/Customer.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L98).


### <a name="property-$geoloc_id_state"></a>$geoloc_id_state

```php
public integer $geoloc_id_state
```





* Visibility: **public**
* Source: [classes/Customer.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L100).


### <a name="property-$geoloc_postcode"></a>$geoloc_postcode

```php
public string $geoloc_postcode
```





* Visibility: **public**
* Source: [classes/Customer.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L102).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Customer.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L30).


### <a name="property-$id_default_group"></a>$id_default_group

```php
public integer $id_default_group = _PS_DEFAULT_CUSTOMER_GROUP_
```





* Visibility: **public**
* Source: [classes/Customer.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L46).


### <a name="property-$id_gender"></a>$id_gender

```php
public integer $id_gender
```





* Visibility: **public**
* Source: [classes/Customer.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L43).


### <a name="property-$id_group_shop"></a>$id_group_shop

```php
public mixed $id_group_shop
```





* Visibility: **public**
* Source: [classes/Customer.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L34).


### <a name="property-$id_guest"></a>$id_guest

```php
public integer $id_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L108).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Customer.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L32).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_customer'
```





* Visibility: **protected**
* Source: [classes/Customer.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L144).


### <a name="property-$ip_registration_newsletter"></a>$ip_registration_newsletter

```php
public string $ip_registration_newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L64).


### <a name="property-$is_guest"></a>$is_guest

```php
public boolean $is_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L82).


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

```php
public \datetime $last_passwd_gen
```





* Visibility: **public**
* Source: [classes/Customer.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L76).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Customer.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L49).


### <a name="property-$logged"></a>$logged

```php
public boolean $logged
```





* Visibility: **public**
* Source: [classes/Customer.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L105).


### <a name="property-$months"></a>$months

```php
public mixed $months
```





* Visibility: **public**
* Source: [classes/Customer.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L95).


### <a name="property-$newsletter"></a>$newsletter

```php
public boolean $newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L61).


### <a name="property-$newsletter_date_add"></a>$newsletter_date_add

```php
public string $newsletter_date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L67).


### <a name="property-$note"></a>$note

```php
public string $note
```





* Visibility: **public**
* Source: [classes/Customer.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L40).


### <a name="property-$optin"></a>$optin

```php
public boolean $optin
```





* Visibility: **public**
* Source: [classes/Customer.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L70).


### <a name="property-$passwd"></a>$passwd

```php
public integer $passwd
```





* Visibility: **public**
* Source: [classes/Customer.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L73).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/Customer.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L37).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'customer'
```





* Visibility: **protected**
* Source: [classes/Customer.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L143).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array('customer')
```





* Visibility: **protected**
* Source: [classes/Customer.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L110).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_default_group' => array('xlink_resource' => 'groups'), 'newsletter_date_add' => array(), 'ip_registration_newsletter' => array(), 'last_passwd_gen' => array('setter' => null), 'secure_key' => array('setter' => null), 'deleted' => array(), 'passwd' => array('setter' => 'setWsPasswd')))
```





* Visibility: **protected**
* Source: [classes/Customer.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L131).


### <a name="property-$years"></a>$years

```php
public mixed $years
```





* Visibility: **public**
* Source: [classes/Customer.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L93).


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


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L34).


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



### <a name="method-add"></a>add

```php
mixed CustomerCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Customer.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L180)


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



### <a name="method-addGroups"></a>addGroups

```php
mixed CustomerCore::addGroups($groups)
```





* Visibility: **public**
* Source: [classes/Customer.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L507)


#### Arguments
* $groups **mixed**



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



### <a name="method-checkPassword"></a>checkPassword

```php
boolean CustomerCore::checkPassword($id_customer, string $passwd)
```

Check if customer password is the right one



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L389)


#### Arguments
* $id_customer **mixed**
* $passwd **string** - Password



### <a name="method-cleanGroups"></a>cleanGroups

```php
mixed CustomerCore::cleanGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L502)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L794)


#### Arguments
* $all **mixed**



### <a name="method-customerExists"></a>customerExists

```php
\Customer CustomerCore::customerExists(string $email, $return_id, $ignore_guest, \Shop $shop)
```

Check if e-mail is already registered in database



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L303)


#### Arguments
* $email **string** - e-mail
* $return_id **mixed** - boolean
* $ignore_guest **mixed** - boolean, to exclude guest customer
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-customerHasAddress"></a>customerHasAddress

```php
boolean CustomerCore::customerHasAddress(integer $id_customer, integer $id_address)
```

Check if an address is owned by a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L330)


#### Arguments
* $id_customer **integer** - Customer ID
* $id_address **integer** - Address ID



### <a name="method-customerIdExists"></a>customerIdExists

```php
mixed CustomerCore::customerIdExists($id_customer)
```





* Visibility: **public**
* Source: [classes/Customer.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L487)


#### Arguments
* $id_customer **mixed**



### <a name="method-customerIdExistsStatic"></a>customerIdExistsStatic

```php
mixed CustomerCore::customerIdExistsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L492)


#### Arguments
* $id_customer **mixed**



### <a name="method-delete"></a>delete

```php
mixed CustomerCore::delete()
```





* Visibility: **public**
* Source: [classes/Customer.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L210)




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



### <a name="method-getAddresses"></a>getAddresses

```php
array CustomerCore::getAddresses(integer $id_lang)
```

Return customer addresses



* Visibility: **public**
* Source: [classes/Customer.php line 356](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L356)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getAddressesTotalById"></a>getAddressesTotalById

```php
integer CustomerCore::getAddressesTotalById(integer $id_customer)
```

Count the number of addresses for a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L373)


#### Arguments
* $id_customer **integer** - Customer ID



### <a name="method-getBoughtProducts"></a>getBoughtProducts

```php
mixed CustomerCore::getBoughtProducts()
```





* Visibility: **public**
* Source: [classes/Customer.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L555)




### <a name="method-getByEmail"></a>getByEmail

```php
\Customer CustomerCore::getByEmail(string $email, string $passwd, \Shop $shop)
```

Return customer instance from its e-mail (optionnaly check password)



* Visibility: **public**
* Source: [classes/Customer.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L247)


#### Arguments
* $email **string** - e-mail
* $passwd **string** - Password is also checked if specified
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getCurrentCountry"></a>getCurrentCountry

```php
mixed CustomerCore::getCurrentCountry($id_customer, \Cart $cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L577)


#### Arguments
* $id_customer **mixed**
* $cart **[Cart](class.CartCore.md)**



### <a name="method-getCustomers"></a>getCustomers

```php
array CustomerCore::getCustomers(\Shop $shop)
```

Return customers list



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L228)


#### Arguments
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getDefaultGroupId"></a>getDefaultGroupId

```php
mixed CustomerCore::getDefaultGroupId($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L563)


#### Arguments
* $id_customer **mixed**



### <a name="method-getFields"></a>getFields

```php
mixed CustomerCore::getFields()
```





* Visibility: **public**
* Source: [classes/Customer.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L150)




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




### <a name="method-getGroups"></a>getGroups

```php
mixed CustomerCore::getGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L545)




### <a name="method-getGroupsStatic"></a>getGroupsStatic

```php
mixed CustomerCore::getGroupsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L527)


#### Arguments
* $id_customer **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getLastCart"></a>getLastCart

```php
mixed CustomerCore::getLastCart()
```





* Visibility: **public**
* Source: [classes/Customer.php line 701](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L701)




### <a name="method-getLastConnections"></a>getLastConnections

```php
mixed CustomerCore::getLastConnections()
```





* Visibility: **public**
* Source: [classes/Customer.php line 467](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L467)




### <a name="method-getStats"></a>getStats

```php
array CustomerCore::getStats()
```

Return several useful statistics about customer



* Visibility: **public**
* Source: [classes/Customer.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L443)




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



### <a name="method-isBanned"></a>isBanned

```php
boolean CustomerCore::isBanned($id_customer)
```

Check id the customer is active or not



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L280)


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
* Source: [classes/ObjectModel.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L948)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isGuest"></a>isGuest

```php
mixed CustomerCore::isGuest()
```





* Visibility: **public**
* Source: [classes/Customer.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L606)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L888)




### <a name="method-isLogged"></a>isLogged

```php
boolean CustomerCore::isLogged(boolean $with_guest)
```

Check customer informations and return customer validity



* Visibility: **public**
* Source: [classes/Customer.php line 665](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L665)


#### Arguments
* $with_guest **boolean**



### <a name="method-isUsed"></a>isUsed

```php
mixed CustomerCore::isUsed()
```





* Visibility: **public**
* Source: [classes/Customer.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L550)




### <a name="method-logout"></a>logout

```php
mixed CustomerCore::logout()
```

Logout



* Visibility: **public**
* Source: [classes/Customer.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L681)




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



### <a name="method-mylogout"></a>mylogout

```php
mixed CustomerCore::mylogout()
```

Soft logout, delete everything links to the customer
but leave there affiliate's informations



* Visibility: **public**
* Source: [classes/Customer.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L694)




### <a name="method-resetAddressCache"></a>resetAddressCache

```php
mixed CustomerCore::resetAddressCache($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L344)


#### Arguments
* $id_customer **mixed**



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



### <a name="method-searchByIp"></a>searchByIp

```php
mixed CustomerCore::searchByIp(string $ip)
```

Search for customers by ip address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 428](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L428)


#### Arguments
* $ip **string** - Searched string



### <a name="method-searchByName"></a>searchByName

```php
array CustomerCore::searchByName(string $query, \Shop $shop)
```

Light back office search for customers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L407)


#### Arguments
* $query **string** - Searched string
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-setWsPasswd"></a>setWsPasswd

```php
mixed CustomerCore::setWsPasswd($passwd)
```





* Visibility: **public**
* Source: [classes/Customer.php line 646](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L646)


#### Arguments
* $passwd **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed CustomerCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Customer.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L594)




### <a name="method-transformToCustomer"></a>transformToCustomer

```php
mixed CustomerCore::transformToCustomer($id_lang, $password)
```





* Visibility: **public**
* Source: [classes/Customer.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L611)


#### Arguments
* $id_lang **mixed**
* $password **mixed**



### <a name="method-update"></a>update

```php
mixed CustomerCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Customer.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Customer.php#L202)


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


