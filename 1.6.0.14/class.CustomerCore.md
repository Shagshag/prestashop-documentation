Class CustomerCore
=====================





* Class name: CustomerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Customer.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L27)


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

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addGroups](#method-addGroups)
* [checkPassword](#method-checkPassword)
* [cleanGroups](#method-cleanGroups)
* [customerExists](#method-customerExists)
* [customerHasAddress](#method-customerHasAddress)
* [customerIdExists](#method-customerIdExists)
* [customerIdExistsStatic](#method-customerIdExistsStatic)
* [delete](#method-delete)
* [getAddresses](#method-getAddresses)
* [getAddressesTotalById](#method-getAddressesTotalById)
* [getBoughtProducts](#method-getBoughtProducts)
* [getByEmail](#method-getByEmail)
* [getCurrentCountry](#method-getCurrentCountry)
* [getCustomers](#method-getCustomers)
* [getCustomersByEmail](#method-getCustomersByEmail)
* [getDefaultGroupId](#method-getDefaultGroupId)
* [getGroups](#method-getGroups)
* [getGroupsStatic](#method-getGroupsStatic)
* [getLastCart](#method-getLastCart)
* [getLastConnections](#method-getLastConnections)
* [getLastEmails](#method-getLastEmails)
* [getOutstanding](#method-getOutstanding)
* [getStats](#method-getStats)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWsGroups](#method-getWsGroups)
* [isBanned](#method-isBanned)
* [isGuest](#method-isGuest)
* [isLogged](#method-isLogged)
* [isUsed](#method-isUsed)
* [logout](#method-logout)
* [mylogout](#method-mylogout)
* [resetAddressCache](#method-resetAddressCache)
* [searchByIp](#method-searchByIp)
* [searchByName](#method-searchByName)
* [setWsGroups](#method-setWsGroups)
* [setWsPasswd](#method-setWsPasswd)
* [toggleStatus](#method-toggleStatus)
* [transformToCustomer](#method-transformToCustomer)
* [update](#method-update)
* [updateGroup](#method-updateGroup)




Properties
----------


### <a name="property-$_customerHasAddress"></a>$_customerHasAddress

```php
protected mixed $_customerHasAddress = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L195).


### <a name="property-$_customer_groups"></a>$_customer_groups

```php
protected mixed $_customer_groups = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L196).


### <a name="property-$_defaultGroupId"></a>$_defaultGroupId

```php
protected mixed $_defaultGroupId = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Customer.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L194).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Customer.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L105).


### <a name="property-$ape"></a>$ape

```php
public string $ape
```





* Visibility: **public**
* Source: [classes/Customer.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L84).


### <a name="property-$birthday"></a>$birthday

```php
public string $birthday = null
```





* Visibility: **public**
* Source: [classes/Customer.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L57).


### <a name="property-$company"></a>$company

```php
public string $company
```





* Visibility: **public**
* Source: [classes/Customer.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L78).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L114).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Customer.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L117).


### <a name="property-$days"></a>$days

```php
public mixed $days
```





* Visibility: **public**
* Source: [classes/Customer.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L120).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'customer', 'primary' => 'id_customer', 'fields' => array('secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5', 'copy_post' => false), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswd', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'id_gender' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'birthday' => array('type' => self::TYPE_DATE, 'validate' => 'isBirthDate'), 'newsletter' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'newsletter_date_add' => array('type' => self::TYPE_DATE, 'copy_post' => false), 'ip_registration_newsletter' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'optin' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'website' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'siret' => array('type' => self::TYPE_STRING, 'validate' => 'isSiret'), 'ape' => array('type' => self::TYPE_STRING, 'validate' => 'isApe'), 'outstanding_allow_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'copy_post' => false), 'show_public_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_risk' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'max_payment_days' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'note' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 65000, 'copy_post' => false), 'is_guest' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_default_group' => array('type' => self::TYPE_INT, 'copy_post' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Customer.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L157).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Customer.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L111).


### <a name="property-$email"></a>$email

```php
public string $email
```





* Visibility: **public**
* Source: [classes/Customer.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L60).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Customer.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L54).


### <a name="property-$geoloc_id_country"></a>$geoloc_id_country

```php
public integer $geoloc_id_country
```





* Visibility: **public**
* Source: [classes/Customer.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L124).


### <a name="property-$geoloc_id_state"></a>$geoloc_id_state

```php
public integer $geoloc_id_state
```





* Visibility: **public**
* Source: [classes/Customer.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L126).


### <a name="property-$geoloc_postcode"></a>$geoloc_postcode

```php
public string $geoloc_postcode
```





* Visibility: **public**
* Source: [classes/Customer.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L128).


### <a name="property-$groupBox"></a>$groupBox

```php
public mixed $groupBox
```





* Visibility: **public**
* Source: [classes/Customer.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L136).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Customer.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L29).


### <a name="property-$id_default_group"></a>$id_default_group

```php
public integer $id_default_group
```





* Visibility: **public**
* Source: [classes/Customer.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L45).


### <a name="property-$id_gender"></a>$id_gender

```php
public integer $id_gender
```





* Visibility: **public**
* Source: [classes/Customer.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L42).


### <a name="property-$id_guest"></a>$id_guest

```php
public integer $id_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L134).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/Customer.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L48).


### <a name="property-$id_risk"></a>$id_risk

```php
public integer $id_risk
```





* Visibility: **public**
* Source: [classes/Customer.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L93).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Customer.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L31).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* Source: [classes/Customer.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L33).


### <a name="property-$ip_registration_newsletter"></a>$ip_registration_newsletter

```php
public string $ip_registration_newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L66).


### <a name="property-$is_guest"></a>$is_guest

```php
public boolean $is_guest
```





* Visibility: **public**
* Source: [classes/Customer.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L108).


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

```php
public string $last_passwd_gen
```





* Visibility: **public**
* Source: [classes/Customer.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L102).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Customer.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L51).


### <a name="property-$logged"></a>$logged

```php
public boolean $logged
```





* Visibility: **public**
* Source: [classes/Customer.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L131).


### <a name="property-$max_payment_days"></a>$max_payment_days

```php
public integer $max_payment_days
```





* Visibility: **public**
* Source: [classes/Customer.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L96).


### <a name="property-$months"></a>$months

```php
public mixed $months
```





* Visibility: **public**
* Source: [classes/Customer.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L121).


### <a name="property-$newsletter"></a>$newsletter

```php
public boolean $newsletter
```





* Visibility: **public**
* Source: [classes/Customer.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L63).


### <a name="property-$newsletter_date_add"></a>$newsletter_date_add

```php
public string $newsletter_date_add
```





* Visibility: **public**
* Source: [classes/Customer.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L69).


### <a name="property-$note"></a>$note

```php
public string $note
```





* Visibility: **public**
* Source: [classes/Customer.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L39).


### <a name="property-$optin"></a>$optin

```php
public boolean $optin
```





* Visibility: **public**
* Source: [classes/Customer.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L72).


### <a name="property-$outstanding_allow_amount"></a>$outstanding_allow_amount

```php
public float $outstanding_allow_amount
```





* Visibility: **public**
* Source: [classes/Customer.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L87).


### <a name="property-$passwd"></a>$passwd

```php
public integer $passwd
```





* Visibility: **public**
* Source: [classes/Customer.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L99).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/Customer.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L36).


### <a name="property-$show_public_prices"></a>$show_public_prices

```php
public integer $show_public_prices
```





* Visibility: **public**
* Source: [classes/Customer.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L90).


### <a name="property-$siret"></a>$siret

```php
public string $siret
```





* Visibility: **public**
* Source: [classes/Customer.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L81).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_default_group' => array('xlink_resource' => 'groups'), 'id_lang' => array('xlink_resource' => 'languages'), 'newsletter_date_add' => array(), 'ip_registration_newsletter' => array(), 'last_passwd_gen' => array('setter' => null), 'secure_key' => array('setter' => null), 'deleted' => array(), 'passwd' => array('setter' => 'setWsPasswd')), 'associations' => array('groups' => array('resource' => 'group')))
```





* Visibility: **protected**
* Source: [classes/Customer.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L138).


### <a name="property-$website"></a>$website

```php
public string $website
```





* Visibility: **public**
* Source: [classes/Customer.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L75).


### <a name="property-$years"></a>$years

```php
public mixed $years
```





* Visibility: **public**
* Source: [classes/Customer.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L119).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CustomerCore::__construct($id)
```





* Visibility: **public**
* Source: [classes/Customer.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L198)


#### Arguments
* $id **mixed**



### <a name="method-add"></a>add

```php
mixed CustomerCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Customer.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L204)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addGroups"></a>addGroups

```php
mixed CustomerCore::addGroups($groups)
```





* Visibility: **public**
* Source: [classes/Customer.php line 637](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L637)


#### Arguments
* $groups **mixed**



### <a name="method-checkPassword"></a>checkPassword

```php
boolean CustomerCore::checkPassword($id_customer, string $passwd)
```

Check if customer password is the right one



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L481)


#### Arguments
* $id_customer **mixed**
* $passwd **string** - Password



### <a name="method-cleanGroups"></a>cleanGroups

```php
mixed CustomerCore::cleanGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 632](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L632)




### <a name="method-customerExists"></a>customerExists

```php
\Customer CustomerCore::customerExists(string $email, $return_id, $ignore_guest)
```

Check if e-mail is already registered in database



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L386)


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
* Source: [classes/Customer.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L411)


#### Arguments
* $id_customer **integer** - Customer ID
* $id_address **integer** - Address ID



### <a name="method-customerIdExists"></a>customerIdExists

```php
mixed CustomerCore::customerIdExists($id_customer)
```





* Visibility: **public**
* Source: [classes/Customer.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L597)


#### Arguments
* $id_customer **mixed**



### <a name="method-customerIdExistsStatic"></a>customerIdExistsStatic

```php
mixed CustomerCore::customerIdExistsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L602)


#### Arguments
* $id_customer **mixed**



### <a name="method-delete"></a>delete

```php
mixed CustomerCore::delete()
```





* Visibility: **public**
* Source: [classes/Customer.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L252)




### <a name="method-getAddresses"></a>getAddresses

```php
array CustomerCore::getAddresses(integer $id_lang)
```

Return customer addresses



* Visibility: **public**
* Source: [classes/Customer.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L439)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getAddressesTotalById"></a>getAddressesTotalById

```php
integer CustomerCore::getAddressesTotalById(integer $id_customer)
```

Count the number of addresses for a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L465)


#### Arguments
* $id_customer **integer** - Customer ID



### <a name="method-getBoughtProducts"></a>getBoughtProducts

```php
mixed CustomerCore::getBoughtProducts()
```





* Visibility: **public**
* Source: [classes/Customer.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L681)




### <a name="method-getByEmail"></a>getByEmail

```php
\Customer CustomerCore::getByEmail(string $email, string $passwd, $ignore_guest)
```

Return customer instance from its e-mail (optionnaly check password)



* Visibility: **public**
* Source: [classes/Customer.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L313)


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
* Source: [classes/Customer.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L703)


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
* Source: [classes/Customer.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L297)




### <a name="method-getCustomersByEmail"></a>getCustomersByEmail

```php
array CustomerCore::getCustomersByEmail($email)
```

Retrieve customers by email address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L344)


#### Arguments
* $email **mixed**



### <a name="method-getDefaultGroupId"></a>getDefaultGroupId

```php
mixed CustomerCore::getDefaultGroupId($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 689](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L689)


#### Arguments
* $id_customer **mixed**



### <a name="method-getGroups"></a>getGroups

```php
mixed CustomerCore::getGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L667)




### <a name="method-getGroupsStatic"></a>getGroupsStatic

```php
mixed CustomerCore::getGroupsStatic($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 646](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L646)


#### Arguments
* $id_customer **mixed**



### <a name="method-getLastCart"></a>getLastCart

```php
mixed CustomerCore::getLastCart($with_order)
```





* Visibility: **public**
* Source: [classes/Customer.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L827)


#### Arguments
* $with_order **mixed**



### <a name="method-getLastConnections"></a>getLastConnections

```php
mixed CustomerCore::getLastConnections()
```





* Visibility: **public**
* Source: [classes/Customer.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L575)




### <a name="method-getLastEmails"></a>getLastEmails

```php
mixed CustomerCore::getLastEmails()
```





* Visibility: **public**
* Source: [classes/Customer.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L562)




### <a name="method-getOutstanding"></a>getOutstanding

```php
mixed CustomerCore::getOutstanding()
```





* Visibility: **public**
* Source: [classes/Customer.php line 837](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L837)




### <a name="method-getStats"></a>getStats

```php
array CustomerCore::getStats()
```

Return several useful statistics about customer



* Visibility: **public**
* Source: [classes/Customer.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L538)




### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed CustomerCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* Source: [classes/Customer.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L882)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWsGroups"></a>getWsGroups

```php
mixed CustomerCore::getWsGroups()
```





* Visibility: **public**
* Source: [classes/Customer.php line 859](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L859)




### <a name="method-isBanned"></a>isBanned

```php
boolean CustomerCore::isBanned($id_customer)
```

Check id the customer is active or not



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L360)


#### Arguments
* $id_customer **mixed**



### <a name="method-isGuest"></a>isGuest

```php
mixed CustomerCore::isGuest()
```





* Visibility: **public**
* Source: [classes/Customer.php line 732](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L732)




### <a name="method-isLogged"></a>isLogged

```php
boolean CustomerCore::isLogged(boolean $with_guest)
```

Check customer informations and return customer validity



* Visibility: **public**
* Source: [classes/Customer.php line 793](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L793)


#### Arguments
* $with_guest **boolean**



### <a name="method-isUsed"></a>isUsed

```php
mixed CustomerCore::isUsed()
```





* Visibility: **public**
* Source: [classes/Customer.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L675)




### <a name="method-logout"></a>logout

```php
mixed CustomerCore::logout()
```

Logout



* Visibility: **public**
* Source: [classes/Customer.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L807)




### <a name="method-mylogout"></a>mylogout

```php
mixed CustomerCore::mylogout()
```

Soft logout, delete everything links to the customer
but leave there affiliate's informations



* Visibility: **public**
* Source: [classes/Customer.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L820)




### <a name="method-resetAddressCache"></a>resetAddressCache

```php
mixed CustomerCore::resetAddressCache($id_customer, $id_address)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L426)


#### Arguments
* $id_customer **mixed**
* $id_address **mixed**



### <a name="method-searchByIp"></a>searchByIp

```php
mixed CustomerCore::searchByIp(string $ip)
```

Search for customers by ip address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L523)


#### Arguments
* $ip **string** - Searched string



### <a name="method-searchByName"></a>searchByName

```php
array CustomerCore::searchByName(string $query)
```

Light back office search for customers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customer.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L504)


#### Arguments
* $query **string** - Searched string



### <a name="method-setWsGroups"></a>setWsGroups

```php
mixed CustomerCore::setWsGroups($result)
```





* Visibility: **public**
* Source: [classes/Customer.php line 869](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L869)


#### Arguments
* $result **mixed**



### <a name="method-setWsPasswd"></a>setWsPasswd

```php
mixed CustomerCore::setWsPasswd($passwd)
```





* Visibility: **public**
* Source: [classes/Customer.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L779)


#### Arguments
* $passwd **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed CustomerCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Customer.php line 720](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L720)




### <a name="method-transformToCustomer"></a>transformToCustomer

```php
mixed CustomerCore::transformToCustomer($id_lang, $password)
```





* Visibility: **public**
* Source: [classes/Customer.php line 737](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L737)


#### Arguments
* $id_lang **mixed**
* $password **mixed**



### <a name="method-update"></a>update

```php
mixed CustomerCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Customer.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L230)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateGroup"></a>updateGroup

```php
mixed CustomerCore::updateGroup(array $list)
```

Update customer groups associated to the object



* Visibility: **public**
* Source: [classes/Customer.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customer.php#L621)


#### Arguments
* $list **array** - groups


