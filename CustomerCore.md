CustomerCore
===============






* Class name: CustomerCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Customer.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L27)





Properties
----------

* [$id](#property-$id)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$secure_key](#property-$secure_key)
* [$note](#property-$note)
* [$id_gender](#property-$id_gender)
* [$id_default_group](#property-$id_default_group)
* [$id_lang](#property-$id_lang)
* [$lastname](#property-$lastname)
* [$firstname](#property-$firstname)
* [$birthday](#property-$birthday)
* [$email](#property-$email)
* [$newsletter](#property-$newsletter)
* [$ip_registration_newsletter](#property-$ip_registration_newsletter)
* [$newsletter_date_add](#property-$newsletter_date_add)
* [$optin](#property-$optin)
* [$website](#property-$website)
* [$company](#property-$company)
* [$siret](#property-$siret)
* [$ape](#property-$ape)
* [$outstanding_allow_amount](#property-$outstanding_allow_amount)
* [$show_public_prices](#property-$show_public_prices)
* [$id_risk](#property-$id_risk)
* [$max_payment_days](#property-$max_payment_days)
* [$passwd](#property-$passwd)
* [$last_passwd_gen](#property-$last_passwd_gen)
* [$active](#property-$active)
* [$is_guest](#property-$is_guest)
* [$deleted](#property-$deleted)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$years](#property-$years)
* [$days](#property-$days)
* [$months](#property-$months)
* [$geoloc_id_country](#property-$geoloc_id_country)
* [$geoloc_id_state](#property-$geoloc_id_state)
* [$geoloc_postcode](#property-$geoloc_postcode)
* [$logged](#property-$logged)
* [$id_guest](#property-$id_guest)
* [$groupBox](#property-$groupBox)
* [$webserviceParameters](#property-$webserviceParameters)
* [$definition](#property-$definition)
* [$_defaultGroupId](#property-$_defaultGroupId)
* [$_customerHasAddress](#property-$_customerHasAddress)
* [$_customer_groups](#property-$_customer_groups)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [update](#method-update)
* [delete](#method-delete)
* [getCustomers](#method-getCustomers)
* [getByEmail](#method-getByEmail)
* [getCustomersByEmail](#method-getCustomersByEmail)
* [isBanned](#method-isBanned)
* [customerExists](#method-customerExists)
* [customerHasAddress](#method-customerHasAddress)
* [resetAddressCache](#method-resetAddressCache)
* [getAddresses](#method-getAddresses)
* [getAddressesTotalById](#method-getAddressesTotalById)
* [checkPassword](#method-checkPassword)
* [searchByName](#method-searchByName)
* [searchByIp](#method-searchByIp)
* [getStats](#method-getStats)
* [getLastEmails](#method-getLastEmails)
* [getLastConnections](#method-getLastConnections)
* [customerIdExists](#method-customerIdExists)
* [customerIdExistsStatic](#method-customerIdExistsStatic)
* [updateGroup](#method-updateGroup)
* [cleanGroups](#method-cleanGroups)
* [addGroups](#method-addGroups)
* [getGroupsStatic](#method-getGroupsStatic)
* [getGroups](#method-getGroups)
* [isUsed](#method-isUsed)
* [getBoughtProducts](#method-getBoughtProducts)
* [getDefaultGroupId](#method-getDefaultGroupId)
* [getCurrentCountry](#method-getCurrentCountry)
* [toggleStatus](#method-toggleStatus)
* [isGuest](#method-isGuest)
* [transformToCustomer](#method-transformToCustomer)
* [setWsPasswd](#method-setWsPasswd)
* [isLogged](#method-isLogged)
* [logout](#method-logout)
* [mylogout](#method-mylogout)
* [getLastCart](#method-getLastCart)
* [getOutstanding](#method-getOutstanding)
* [getWsGroups](#method-getWsGroups)
* [setWsGroups](#method-setWsGroups)
* [getWebserviceObjectList](#method-getWebserviceObjectList)




Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Customer.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L29)


### <a name="property-$id_shop"></a>$id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in [classes/Customer.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L31)


### <a name="property-$id_shop_group"></a>$id_shop_group

    public mixed $id_shop_group





* Visibility: **public**
* This property is defined in [classes/Customer.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L33)


### <a name="property-$secure_key"></a>$secure_key

    public string $secure_key





* Visibility: **public**
* This property is defined in [classes/Customer.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L36)


### <a name="property-$note"></a>$note

    public string $note





* Visibility: **public**
* This property is defined in [classes/Customer.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L39)


### <a name="property-$id_gender"></a>$id_gender

    public integer $id_gender





* Visibility: **public**
* This property is defined in [classes/Customer.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L42)


### <a name="property-$id_default_group"></a>$id_default_group

    public integer $id_default_group





* Visibility: **public**
* This property is defined in [classes/Customer.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L45)


### <a name="property-$id_lang"></a>$id_lang

    public integer $id_lang





* Visibility: **public**
* This property is defined in [classes/Customer.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L48)


### <a name="property-$lastname"></a>$lastname

    public string $lastname





* Visibility: **public**
* This property is defined in [classes/Customer.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L51)


### <a name="property-$firstname"></a>$firstname

    public string $firstname





* Visibility: **public**
* This property is defined in [classes/Customer.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L54)


### <a name="property-$birthday"></a>$birthday

    public string $birthday = null





* Visibility: **public**
* This property is defined in [classes/Customer.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L57)


### <a name="property-$email"></a>$email

    public string $email





* Visibility: **public**
* This property is defined in [classes/Customer.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L60)


### <a name="property-$newsletter"></a>$newsletter

    public boolean $newsletter





* Visibility: **public**
* This property is defined in [classes/Customer.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L63)


### <a name="property-$ip_registration_newsletter"></a>$ip_registration_newsletter

    public string $ip_registration_newsletter





* Visibility: **public**
* This property is defined in [classes/Customer.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L66)


### <a name="property-$newsletter_date_add"></a>$newsletter_date_add

    public string $newsletter_date_add





* Visibility: **public**
* This property is defined in [classes/Customer.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L69)


### <a name="property-$optin"></a>$optin

    public boolean $optin





* Visibility: **public**
* This property is defined in [classes/Customer.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L72)


### <a name="property-$website"></a>$website

    public string $website





* Visibility: **public**
* This property is defined in [classes/Customer.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L75)


### <a name="property-$company"></a>$company

    public string $company





* Visibility: **public**
* This property is defined in [classes/Customer.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L78)


### <a name="property-$siret"></a>$siret

    public string $siret





* Visibility: **public**
* This property is defined in [classes/Customer.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L81)


### <a name="property-$ape"></a>$ape

    public string $ape





* Visibility: **public**
* This property is defined in [classes/Customer.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L84)


### <a name="property-$outstanding_allow_amount"></a>$outstanding_allow_amount

    public float $outstanding_allow_amount





* Visibility: **public**
* This property is defined in [classes/Customer.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L87)


### <a name="property-$show_public_prices"></a>$show_public_prices

    public integer $show_public_prices





* Visibility: **public**
* This property is defined in [classes/Customer.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L90)


### <a name="property-$id_risk"></a>$id_risk

    public integer $id_risk





* Visibility: **public**
* This property is defined in [classes/Customer.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L93)


### <a name="property-$max_payment_days"></a>$max_payment_days

    public integer $max_payment_days





* Visibility: **public**
* This property is defined in [classes/Customer.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L96)


### <a name="property-$passwd"></a>$passwd

    public integer $passwd





* Visibility: **public**
* This property is defined in [classes/Customer.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L99)


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

    public string $last_passwd_gen





* Visibility: **public**
* This property is defined in [classes/Customer.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L102)


### <a name="property-$active"></a>$active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Customer.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L105)


### <a name="property-$is_guest"></a>$is_guest

    public boolean $is_guest





* Visibility: **public**
* This property is defined in [classes/Customer.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L108)


### <a name="property-$deleted"></a>$deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in [classes/Customer.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L111)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Customer.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L114)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/Customer.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L117)


### <a name="property-$years"></a>$years

    public mixed $years





* Visibility: **public**
* This property is defined in [classes/Customer.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L119)


### <a name="property-$days"></a>$days

    public mixed $days





* Visibility: **public**
* This property is defined in [classes/Customer.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L120)


### <a name="property-$months"></a>$months

    public mixed $months





* Visibility: **public**
* This property is defined in [classes/Customer.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L121)


### <a name="property-$geoloc_id_country"></a>$geoloc_id_country

    public integer $geoloc_id_country





* Visibility: **public**
* This property is defined in [classes/Customer.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L124)


### <a name="property-$geoloc_id_state"></a>$geoloc_id_state

    public integer $geoloc_id_state





* Visibility: **public**
* This property is defined in [classes/Customer.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L126)


### <a name="property-$geoloc_postcode"></a>$geoloc_postcode

    public string $geoloc_postcode





* Visibility: **public**
* This property is defined in [classes/Customer.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L128)


### <a name="property-$logged"></a>$logged

    public boolean $logged





* Visibility: **public**
* This property is defined in [classes/Customer.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L131)


### <a name="property-$id_guest"></a>$id_guest

    public integer $id_guest





* Visibility: **public**
* This property is defined in [classes/Customer.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L134)


### <a name="property-$groupBox"></a>$groupBox

    public mixed $groupBox





* Visibility: **public**
* This property is defined in [classes/Customer.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L136)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_default_group' => array('xlink_resource' => 'groups'), 'id_lang' => array('xlink_resource' => 'languages'), 'newsletter_date_add' => array(), 'ip_registration_newsletter' => array(), 'last_passwd_gen' => array('setter' => null), 'secure_key' => array('setter' => null), 'deleted' => array(), 'passwd' => array('setter' => 'setWsPasswd')), 'associations' => array('groups' => array('resource' => 'group')))





* Visibility: **protected**
* This property is defined in [classes/Customer.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L138)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'customer', 'primary' => 'id_customer', 'fields' => array('secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5', 'copy_post' => false), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswd', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'id_gender' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'birthday' => array('type' => self::TYPE_DATE, 'validate' => 'isBirthDate'), 'newsletter' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'newsletter_date_add' => array('type' => self::TYPE_DATE, 'copy_post' => false), 'ip_registration_newsletter' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'optin' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'website' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'siret' => array('type' => self::TYPE_STRING, 'validate' => 'isSiret'), 'ape' => array('type' => self::TYPE_STRING, 'validate' => 'isApe'), 'outstanding_allow_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'copy_post' => false), 'show_public_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_risk' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'max_payment_days' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'note' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 65000, 'copy_post' => false), 'is_guest' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_default_group' => array('type' => self::TYPE_INT, 'copy_post' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Customer.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L157)


### <a name="property-$_defaultGroupId"></a>$_defaultGroupId

    protected mixed $_defaultGroupId = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Customer.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L194)


### <a name="property-$_customerHasAddress"></a>$_customerHasAddress

    protected mixed $_customerHasAddress = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Customer.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L195)


### <a name="property-$_customer_groups"></a>$_customer_groups

    protected mixed $_customer_groups = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Customer.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L196)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed CustomerCore::__construct($id)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L198)


#### Arguments
* $id **mixed**



### <a name="method-add"></a>add

    mixed CustomerCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L204)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-update"></a>update

    mixed CustomerCore::update($nullValues)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L234)


#### Arguments
* $nullValues **mixed**



### <a name="method-delete"></a>delete

    mixed CustomerCore::delete()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L256)




### <a name="method-getCustomers"></a>getCustomers

    array CustomerCore::getCustomers()

Return customers list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L299)




### <a name="method-getByEmail"></a>getByEmail

    \Customer CustomerCore::getByEmail(string $email, string $passwd, $ignore_guest)

Return customer instance from its e-mail (optionnaly check password)



* Visibility: **public**
* This method is defined in [classes/Customer.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L315)


#### Arguments
* $email **string** - &lt;p&gt;e-mail&lt;/p&gt;
* $passwd **string** - &lt;p&gt;Password is also checked if specified&lt;/p&gt;
* $ignore_guest **mixed**



### <a name="method-getCustomersByEmail"></a>getCustomersByEmail

    array CustomerCore::getCustomersByEmail($email)

Retrieve customers by email address



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L348)


#### Arguments
* $email **mixed**



### <a name="method-isBanned"></a>isBanned

    boolean CustomerCore::isBanned($id_customer)

Check id the customer is active or not



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L364)


#### Arguments
* $id_customer **mixed**



### <a name="method-customerExists"></a>customerExists

    \Customer CustomerCore::customerExists(string $email, $return_id, $ignore_guest)

Check if e-mail is already registered in database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L391)


#### Arguments
* $email **string** - &lt;p&gt;e-mail&lt;/p&gt;
* $return_id **mixed** - &lt;p&gt;boolean&lt;/p&gt;
* $ignore_guest **mixed** - &lt;p&gt;boolean, to exclude guest customer&lt;/p&gt;



### <a name="method-customerHasAddress"></a>customerHasAddress

    boolean CustomerCore::customerHasAddress(integer $id_customer, integer $id_address)

Check if an address is owned by a customer



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L416)


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer ID&lt;/p&gt;
* $id_address **integer** - &lt;p&gt;Address ID&lt;/p&gt;



### <a name="method-resetAddressCache"></a>resetAddressCache

    mixed CustomerCore::resetAddressCache($id_customer, $id_address)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L430)


#### Arguments
* $id_customer **mixed**
* $id_address **mixed**



### <a name="method-getAddresses"></a>getAddresses

    array CustomerCore::getAddresses(integer $id_lang)

Return customer addresses



* Visibility: **public**
* This method is defined in [classes/Customer.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L444)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### <a name="method-getAddressesTotalById"></a>getAddressesTotalById

    integer CustomerCore::getAddressesTotalById(integer $id_customer)

Count the number of addresses for a customer



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L470)


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer ID&lt;/p&gt;



### <a name="method-checkPassword"></a>checkPassword

    boolean CustomerCore::checkPassword($id_customer, string $passwd)

Check if customer password is the right one



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L486)


#### Arguments
* $id_customer **mixed**
* $passwd **string** - &lt;p&gt;Password&lt;/p&gt;



### <a name="method-searchByName"></a>searchByName

    array|false|\mysqli_result|null|\PDOStatement|resource CustomerCore::searchByName(string $query, null|integer $limit)

Light back office search for customers



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 512](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L512)


#### Arguments
* $query **string** - &lt;p&gt;Searched string&lt;/p&gt;
* $limit **null|integer** - &lt;p&gt;Limit query results&lt;/p&gt;



### <a name="method-searchByIp"></a>searchByIp

    mixed CustomerCore::searchByIp(string $ip)

Search for customers by ip address



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L534)


#### Arguments
* $ip **string** - &lt;p&gt;Searched string&lt;/p&gt;



### <a name="method-getStats"></a>getStats

    array CustomerCore::getStats()

Return several useful statistics about customer



* Visibility: **public**
* This method is defined in [classes/Customer.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L549)




### <a name="method-getLastEmails"></a>getLastEmails

    mixed CustomerCore::getLastEmails()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L573)




### <a name="method-getLastConnections"></a>getLastConnections

    mixed CustomerCore::getLastConnections()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 587](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L587)




### <a name="method-customerIdExists"></a>customerIdExists

    mixed CustomerCore::customerIdExists($id_customer)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L610)


#### Arguments
* $id_customer **mixed**



### <a name="method-customerIdExistsStatic"></a>customerIdExistsStatic

    mixed CustomerCore::customerIdExistsStatic($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L615)


#### Arguments
* $id_customer **mixed**



### <a name="method-updateGroup"></a>updateGroup

    mixed CustomerCore::updateGroup(array $list)

Update customer groups associated to the object



* Visibility: **public**
* This method is defined in [classes/Customer.php line 634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L634)


#### Arguments
* $list **array** - &lt;p&gt;groups&lt;/p&gt;



### <a name="method-cleanGroups"></a>cleanGroups

    mixed CustomerCore::cleanGroups()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L644)




### <a name="method-addGroups"></a>addGroups

    mixed CustomerCore::addGroups($groups)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L649)


#### Arguments
* $groups **mixed**



### <a name="method-getGroupsStatic"></a>getGroupsStatic

    mixed CustomerCore::getGroupsStatic($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L657)


#### Arguments
* $id_customer **mixed**



### <a name="method-getGroups"></a>getGroups

    mixed CustomerCore::getGroups()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L680)




### <a name="method-isUsed"></a>isUsed

    mixed CustomerCore::isUsed()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L688)




### <a name="method-getBoughtProducts"></a>getBoughtProducts

    mixed CustomerCore::getBoughtProducts()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L694)




### <a name="method-getDefaultGroupId"></a>getDefaultGroupId

    mixed CustomerCore::getDefaultGroupId($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L702)


#### Arguments
* $id_customer **mixed**



### <a name="method-getCurrentCountry"></a>getCurrentCountry

    mixed CustomerCore::getCurrentCountry($id_customer, \Cart $cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customer.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L722)


#### Arguments
* $id_customer **mixed**
* $cart **[Cart](CartCore)**



### <a name="method-toggleStatus"></a>toggleStatus

    mixed CustomerCore::toggleStatus()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 741](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L741)




### <a name="method-isGuest"></a>isGuest

    mixed CustomerCore::isGuest()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L753)




### <a name="method-transformToCustomer"></a>transformToCustomer

    mixed CustomerCore::transformToCustomer($id_lang, $password)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L758)


#### Arguments
* $id_lang **mixed**
* $password **mixed**



### <a name="method-setWsPasswd"></a>setWsPasswd

    mixed CustomerCore::setWsPasswd($passwd)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L802)


#### Arguments
* $passwd **mixed**



### <a name="method-isLogged"></a>isLogged

    boolean CustomerCore::isLogged(boolean $with_guest)

Check customer informations and return customer validity



* Visibility: **public**
* This method is defined in [classes/Customer.php line 817](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L817)


#### Arguments
* $with_guest **boolean**



### <a name="method-logout"></a>logout

    mixed CustomerCore::logout()

Logout



* Visibility: **public**
* This method is defined in [classes/Customer.php line 832](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L832)




### <a name="method-mylogout"></a>mylogout

    mixed CustomerCore::mylogout()

Soft logout, delete everything links to the customer
but leave there affiliate's informations



* Visibility: **public**
* This method is defined in [classes/Customer.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L851)




### <a name="method-getLastCart"></a>getLastCart

    mixed CustomerCore::getLastCart($with_order)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L864)


#### Arguments
* $with_order **mixed**



### <a name="method-getOutstanding"></a>getOutstanding

    mixed CustomerCore::getOutstanding()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 875](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L875)




### <a name="method-getWsGroups"></a>getWsGroups

    mixed CustomerCore::getWsGroups()





* Visibility: **public**
* This method is defined in [classes/Customer.php line 897](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L897)




### <a name="method-setWsGroups"></a>setWsGroups

    mixed CustomerCore::setWsGroups($result)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 907](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L907)


#### Arguments
* $result **mixed**



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

    mixed CustomerCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**
* This method is defined in [classes/Customer.php line 921](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customer.php#L921)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**


