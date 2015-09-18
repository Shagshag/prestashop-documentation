CustomerCore
===============






* Class name: CustomerCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_shop

    public mixed $id_shop





* Visibility: **public**


### $id_shop_group

    public mixed $id_shop_group





* Visibility: **public**


### $secure_key

    public string $secure_key





* Visibility: **public**


### $note

    public string $note





* Visibility: **public**


### $id_gender

    public integer $id_gender





* Visibility: **public**


### $id_default_group

    public integer $id_default_group





* Visibility: **public**


### $id_lang

    public integer $id_lang





* Visibility: **public**


### $lastname

    public string $lastname





* Visibility: **public**


### $firstname

    public string $firstname





* Visibility: **public**


### $birthday

    public string $birthday = null





* Visibility: **public**


### $email

    public string $email





* Visibility: **public**


### $newsletter

    public boolean $newsletter





* Visibility: **public**


### $ip_registration_newsletter

    public string $ip_registration_newsletter





* Visibility: **public**


### $newsletter_date_add

    public string $newsletter_date_add





* Visibility: **public**


### $optin

    public boolean $optin





* Visibility: **public**


### $website

    public string $website





* Visibility: **public**


### $company

    public string $company





* Visibility: **public**


### $siret

    public string $siret





* Visibility: **public**


### $ape

    public string $ape





* Visibility: **public**


### $outstanding_allow_amount

    public float $outstanding_allow_amount





* Visibility: **public**


### $show_public_prices

    public integer $show_public_prices





* Visibility: **public**


### $id_risk

    public integer $id_risk





* Visibility: **public**


### $max_payment_days

    public integer $max_payment_days





* Visibility: **public**


### $passwd

    public integer $passwd





* Visibility: **public**


### $last_passwd_gen

    public string $last_passwd_gen





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $is_guest

    public boolean $is_guest





* Visibility: **public**


### $deleted

    public boolean $deleted





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $years

    public mixed $years





* Visibility: **public**


### $days

    public mixed $days





* Visibility: **public**


### $months

    public mixed $months





* Visibility: **public**


### $geoloc_id_country

    public integer $geoloc_id_country





* Visibility: **public**


### $geoloc_id_state

    public integer $geoloc_id_state





* Visibility: **public**


### $geoloc_postcode

    public string $geoloc_postcode





* Visibility: **public**


### $logged

    public boolean $logged





* Visibility: **public**


### $id_guest

    public integer $id_guest





* Visibility: **public**


### $groupBox

    public mixed $groupBox





* Visibility: **public**


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_default_group' => array('xlink_resource' => 'groups'), 'id_lang' => array('xlink_resource' => 'languages'), 'newsletter_date_add' => array(), 'ip_registration_newsletter' => array(), 'last_passwd_gen' => array('setter' => null), 'secure_key' => array('setter' => null), 'deleted' => array(), 'passwd' => array('setter' => 'setWsPasswd')), 'associations' => array('groups' => array('resource' => 'group')))





* Visibility: **protected**


### $definition

    public mixed $definition = array('table' => 'customer', 'primary' => 'id_customer', 'fields' => array('secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5', 'copy_post' => false), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswd', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'id_gender' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'birthday' => array('type' => self::TYPE_DATE, 'validate' => 'isBirthDate'), 'newsletter' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'newsletter_date_add' => array('type' => self::TYPE_DATE, 'copy_post' => false), 'ip_registration_newsletter' => array('type' => self::TYPE_STRING, 'copy_post' => false), 'optin' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'website' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'siret' => array('type' => self::TYPE_STRING, 'validate' => 'isSiret'), 'ape' => array('type' => self::TYPE_STRING, 'validate' => 'isApe'), 'outstanding_allow_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'copy_post' => false), 'show_public_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_risk' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'max_payment_days' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'copy_post' => false), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'note' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml', 'size' => 65000, 'copy_post' => false), 'is_guest' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'id_default_group' => array('type' => self::TYPE_INT, 'copy_post' => false), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false)))





* Visibility: **public**
* This property is **static**.


### $_defaultGroupId

    protected mixed $_defaultGroupId = array()





* Visibility: **protected**
* This property is **static**.


### $_customerHasAddress

    protected mixed $_customerHasAddress = array()





* Visibility: **protected**
* This property is **static**.


### $_customer_groups

    protected mixed $_customer_groups = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed CustomerCore::__construct($id)





* Visibility: **public**


#### Arguments
* $id **mixed**



### add

    mixed CustomerCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed CustomerCore::update($nullValues)





* Visibility: **public**


#### Arguments
* $nullValues **mixed**



### delete

    mixed CustomerCore::delete()





* Visibility: **public**




### getCustomers

    array CustomerCore::getCustomers()

Return customers list



* Visibility: **public**
* This method is **static**.




### getByEmail

    \Customer CustomerCore::getByEmail(string $email, string $passwd, $ignore_guest)

Return customer instance from its e-mail (optionnaly check password)



* Visibility: **public**


#### Arguments
* $email **string** - &lt;p&gt;e-mail&lt;/p&gt;
* $passwd **string** - &lt;p&gt;Password is also checked if specified&lt;/p&gt;
* $ignore_guest **mixed**



### getCustomersByEmail

    array CustomerCore::getCustomersByEmail($email)

Retrieve customers by email address



* Visibility: **public**
* This method is **static**.


#### Arguments
* $email **mixed**



### isBanned

    boolean CustomerCore::isBanned($id_customer)

Check id the customer is active or not



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### customerExists

    \Customer CustomerCore::customerExists(string $email, $return_id, $ignore_guest)

Check if e-mail is already registered in database



* Visibility: **public**
* This method is **static**.


#### Arguments
* $email **string** - &lt;p&gt;e-mail&lt;/p&gt;
* $return_id **mixed** - &lt;p&gt;boolean&lt;/p&gt;
* $ignore_guest **mixed** - &lt;p&gt;boolean, to exclude guest customer&lt;/p&gt;



### customerHasAddress

    boolean CustomerCore::customerHasAddress(integer $id_customer, integer $id_address)

Check if an address is owned by a customer



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer ID&lt;/p&gt;
* $id_address **integer** - &lt;p&gt;Address ID&lt;/p&gt;



### resetAddressCache

    mixed CustomerCore::resetAddressCache($id_customer, $id_address)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $id_address **mixed**



### getAddresses

    array CustomerCore::getAddresses(integer $id_lang)

Return customer addresses



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### getAddressesTotalById

    integer CustomerCore::getAddressesTotalById(integer $id_customer)

Count the number of addresses for a customer



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **integer** - &lt;p&gt;Customer ID&lt;/p&gt;



### checkPassword

    boolean CustomerCore::checkPassword($id_customer, string $passwd)

Check if customer password is the right one



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $passwd **string** - &lt;p&gt;Password&lt;/p&gt;



### searchByName

    array|false|\mysqli_result|null|\PDOStatement|resource CustomerCore::searchByName(string $query, null|integer $limit)

Light back office search for customers



* Visibility: **public**
* This method is **static**.


#### Arguments
* $query **string** - &lt;p&gt;Searched string&lt;/p&gt;
* $limit **null|integer** - &lt;p&gt;Limit query results&lt;/p&gt;



### searchByIp

    mixed CustomerCore::searchByIp(string $ip)

Search for customers by ip address



* Visibility: **public**
* This method is **static**.


#### Arguments
* $ip **string** - &lt;p&gt;Searched string&lt;/p&gt;



### getStats

    array CustomerCore::getStats()

Return several useful statistics about customer



* Visibility: **public**




### getLastEmails

    mixed CustomerCore::getLastEmails()





* Visibility: **public**




### getLastConnections

    mixed CustomerCore::getLastConnections()





* Visibility: **public**




### customerIdExists

    mixed CustomerCore::customerIdExists($id_customer)





* Visibility: **public**


#### Arguments
* $id_customer **mixed**



### customerIdExistsStatic

    mixed CustomerCore::customerIdExistsStatic($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### updateGroup

    mixed CustomerCore::updateGroup(array $list)

Update customer groups associated to the object



* Visibility: **public**


#### Arguments
* $list **array** - &lt;p&gt;groups&lt;/p&gt;



### cleanGroups

    mixed CustomerCore::cleanGroups()





* Visibility: **public**




### addGroups

    mixed CustomerCore::addGroups($groups)





* Visibility: **public**


#### Arguments
* $groups **mixed**



### getGroupsStatic

    mixed CustomerCore::getGroupsStatic($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### getGroups

    mixed CustomerCore::getGroups()





* Visibility: **public**




### isUsed

    mixed CustomerCore::isUsed()





* Visibility: **public**




### getBoughtProducts

    mixed CustomerCore::getBoughtProducts()





* Visibility: **public**




### getDefaultGroupId

    mixed CustomerCore::getDefaultGroupId($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### getCurrentCountry

    mixed CustomerCore::getCurrentCountry($id_customer, \Cart $cart)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $cart **Cart**



### toggleStatus

    mixed CustomerCore::toggleStatus()





* Visibility: **public**




### isGuest

    mixed CustomerCore::isGuest()





* Visibility: **public**




### transformToCustomer

    mixed CustomerCore::transformToCustomer($id_lang, $password)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**
* $password **mixed**



### setWsPasswd

    mixed CustomerCore::setWsPasswd($passwd)





* Visibility: **public**


#### Arguments
* $passwd **mixed**



### isLogged

    boolean CustomerCore::isLogged(boolean $with_guest)

Check customer informations and return customer validity



* Visibility: **public**


#### Arguments
* $with_guest **boolean**



### logout

    mixed CustomerCore::logout()

Logout



* Visibility: **public**




### mylogout

    mixed CustomerCore::mylogout()

Soft logout, delete everything links to the customer
but leave there affiliate's informations



* Visibility: **public**




### getLastCart

    mixed CustomerCore::getLastCart($with_order)





* Visibility: **public**


#### Arguments
* $with_order **mixed**



### getOutstanding

    mixed CustomerCore::getOutstanding()





* Visibility: **public**




### getWsGroups

    mixed CustomerCore::getWsGroups()





* Visibility: **public**




### setWsGroups

    mixed CustomerCore::setWsGroups($result)





* Visibility: **public**


#### Arguments
* $result **mixed**



### getWebserviceObjectList

    mixed CustomerCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**


