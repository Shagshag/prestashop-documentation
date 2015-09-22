EmployeeCore
===============






* Class name: EmployeeCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Employee.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L27)





Properties
----------

* [$id](#property-$id)
* [$id_profile](#property-$id_profile)
* [$id_lang](#property-$id_lang)
* [$lastname](#property-$lastname)
* [$firstname](#property-$firstname)
* [$email](#property-$email)
* [$passwd](#property-$passwd)
* [$last_passwd_gen](#property-$last_passwd_gen)
* [$stats_date_from](#property-$stats_date_from)
* [$stats_date_to](#property-$stats_date_to)
* [$stats_compare_from](#property-$stats_compare_from)
* [$stats_compare_to](#property-$stats_compare_to)
* [$stats_compare_option](#property-$stats_compare_option)
* [$preselect_date_range](#property-$preselect_date_range)
* [$bo_color](#property-$bo_color)
* [$default_tab](#property-$default_tab)
* [$bo_theme](#property-$bo_theme)
* [$bo_css](#property-$bo_css)
* [$bo_width](#property-$bo_width)
* [$bo_menu](#property-$bo_menu)
* [$bo_show_screencast](#property-$bo_show_screencast)
* [$active](#property-$active)
* [$optin](#property-$optin)
* [$remote_addr](#property-$remote_addr)
* [$id_last_order](#property-$id_last_order)
* [$id_last_customer_message](#property-$id_last_customer_message)
* [$id_last_customer](#property-$id_last_customer)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)
* [$associated_shops](#property-$associated_shops)

Methods
-------
* [__construct](#method-__construct)
* [getFields](#method-getFields)
* [add](#method-add)
* [update](#method-update)
* [updateTextDirection](#method-updateTextDirection)
* [saveOptin](#method-saveOptin)
* [getEmployees](#method-getEmployees)
* [getByEmail](#method-getByEmail)
* [employeeExists](#method-employeeExists)
* [checkPassword](#method-checkPassword)
* [countProfile](#method-countProfile)
* [isLastAdmin](#method-isLastAdmin)
* [setWsPasswd](#method-setWsPasswd)
* [isLoggedBack](#method-isLoggedBack)
* [logout](#method-logout)
* [favoriteModulesList](#method-favoriteModulesList)
* [hasAuthOnShop](#method-hasAuthOnShop)
* [hasAuthOnShopGroup](#method-hasAuthOnShopGroup)
* [getDefaultShopID](#method-getDefaultShopID)
* [getEmployeesByProfile](#method-getEmployeesByProfile)
* [isSuperAdmin](#method-isSuperAdmin)
* [getImage](#method-getImage)
* [getLastElementsForNotify](#method-getLastElementsForNotify)
* [setLastConnectionDate](#method-setLastConnectionDate)




Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Employee.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L29)


### <a name="property-$id_profile"></a>$id_profile

    public string $id_profile





* Visibility: **public**
* This property is defined in [classes/Employee.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L32)


### <a name="property-$id_lang"></a>$id_lang

    public string $id_lang





* Visibility: **public**
* This property is defined in [classes/Employee.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L35)


### <a name="property-$lastname"></a>$lastname

    public string $lastname





* Visibility: **public**
* This property is defined in [classes/Employee.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L38)


### <a name="property-$firstname"></a>$firstname

    public string $firstname





* Visibility: **public**
* This property is defined in [classes/Employee.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L41)


### <a name="property-$email"></a>$email

    public string $email





* Visibility: **public**
* This property is defined in [classes/Employee.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L44)


### <a name="property-$passwd"></a>$passwd

    public string $passwd





* Visibility: **public**
* This property is defined in [classes/Employee.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L47)


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

    public \datetime $last_passwd_gen





* Visibility: **public**
* This property is defined in [classes/Employee.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L50)


### <a name="property-$stats_date_from"></a>$stats_date_from

    public mixed $stats_date_from





* Visibility: **public**
* This property is defined in [classes/Employee.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L52)


### <a name="property-$stats_date_to"></a>$stats_date_to

    public mixed $stats_date_to





* Visibility: **public**
* This property is defined in [classes/Employee.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L53)


### <a name="property-$stats_compare_from"></a>$stats_compare_from

    public mixed $stats_compare_from





* Visibility: **public**
* This property is defined in [classes/Employee.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L55)


### <a name="property-$stats_compare_to"></a>$stats_compare_to

    public mixed $stats_compare_to





* Visibility: **public**
* This property is defined in [classes/Employee.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L56)


### <a name="property-$stats_compare_option"></a>$stats_compare_option

    public mixed $stats_compare_option = 1





* Visibility: **public**
* This property is defined in [classes/Employee.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L57)


### <a name="property-$preselect_date_range"></a>$preselect_date_range

    public mixed $preselect_date_range





* Visibility: **public**
* This property is defined in [classes/Employee.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L59)


### <a name="property-$bo_color"></a>$bo_color

    public string $bo_color





* Visibility: **public**
* This property is defined in [classes/Employee.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L62)


### <a name="property-$default_tab"></a>$default_tab

    public mixed $default_tab





* Visibility: **public**
* This property is defined in [classes/Employee.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L64)


### <a name="property-$bo_theme"></a>$bo_theme

    public string $bo_theme





* Visibility: **public**
* This property is defined in [classes/Employee.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L67)


### <a name="property-$bo_css"></a>$bo_css

    public string $bo_css = 'admin-theme.css'





* Visibility: **public**
* This property is defined in [classes/Employee.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L70)


### <a name="property-$bo_width"></a>$bo_width

    public integer $bo_width





* Visibility: **public**
* This property is defined in [classes/Employee.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L73)


### <a name="property-$bo_menu"></a>$bo_menu

    public \bool, $bo_menu = 1





* Visibility: **public**
* This property is defined in [classes/Employee.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L76)


### <a name="property-$bo_show_screencast"></a>$bo_show_screencast

    public mixed $bo_show_screencast = false





* Visibility: **public**
* This property is defined in [classes/Employee.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L79)


### <a name="property-$active"></a>$active

    public boolean $active = 1





* Visibility: **public**
* This property is defined in [classes/Employee.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L82)


### <a name="property-$optin"></a>$optin

    public boolean $optin = 1





* Visibility: **public**
* This property is defined in [classes/Employee.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L85)


### <a name="property-$remote_addr"></a>$remote_addr

    public mixed $remote_addr





* Visibility: **public**
* This property is defined in [classes/Employee.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L87)


### <a name="property-$id_last_order"></a>$id_last_order

    public mixed $id_last_order





* Visibility: **public**
* This property is defined in [classes/Employee.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L90)


### <a name="property-$id_last_customer_message"></a>$id_last_customer_message

    public mixed $id_last_customer_message





* Visibility: **public**
* This property is defined in [classes/Employee.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L91)


### <a name="property-$id_last_customer"></a>$id_last_customer

    public mixed $id_last_customer





* Visibility: **public**
* This property is defined in [classes/Employee.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L92)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'employee', 'primary' => 'id_employee', 'fields' => array('lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswdAdmin', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'optin' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_profile' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'bo_color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'default_tab' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'bo_theme' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 32), 'bo_css' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'bo_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'bo_menu' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'stats_date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_option' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'preselect_date_range' => array('type' => self::TYPE_STRING, 'size' => 32), 'id_last_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_last_customer_message' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_last_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Employee.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L97)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'last_passwd_gen' => array('setter' => null), 'stats_date_from' => array('setter' => null), 'stats_date_to' => array('setter' => null), 'stats_compare_from' => array('setter' => null), 'stats_compare_to' => array('setter' => null), 'passwd' => array('setter' => 'setWsPasswd')))





* Visibility: **protected**
* This property is defined in [classes/Employee.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L128)


### <a name="property-$associated_shops"></a>$associated_shops

    protected mixed $associated_shops = array()





* Visibility: **protected**
* This property is defined in [classes/Employee.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L140)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed EmployeeCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* This method is defined in [classes/Employee.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L142)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-getFields"></a>getFields

    array EmployeeCore::getFields()





* Visibility: **public**
* This method is defined in [classes/Employee.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L161)




### <a name="method-add"></a>add

    mixed EmployeeCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Employee.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L182)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-update"></a>update

    mixed EmployeeCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/Employee.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L190)


#### Arguments
* $null_values **mixed**



### <a name="method-updateTextDirection"></a>updateTextDirection

    mixed EmployeeCore::updateTextDirection()





* Visibility: **protected**
* This method is defined in [classes/Employee.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L210)




### <a name="method-saveOptin"></a>saveOptin

    mixed EmployeeCore::saveOptin()





* Visibility: **protected**
* This method is defined in [classes/Employee.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L234)




### <a name="method-getEmployees"></a>getEmployees

    array|false EmployeeCore::getEmployees(boolean $active_only)

Return list of employees



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Employee.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L255)


#### Arguments
* $active_only **boolean** - &lt;p&gt;Filter employee by active status&lt;/p&gt;



### <a name="method-getByEmail"></a>getByEmail

    \Employee EmployeeCore::getByEmail(string $email, string $passwd, boolean $active_only)

Return employee instance from its e-mail (optionnaly check password)



* Visibility: **public**
* This method is defined in [classes/Employee.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L273)


#### Arguments
* $email **string** - &lt;p&gt;e-mail&lt;/p&gt;
* $passwd **string** - &lt;p&gt;Password is also checked if specified&lt;/p&gt;
* $active_only **boolean** - &lt;p&gt;Filter employee by active status&lt;/p&gt;



### <a name="method-employeeExists"></a>employeeExists

    mixed EmployeeCore::employeeExists($email)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Employee.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L298)


#### Arguments
* $email **mixed**



### <a name="method-checkPassword"></a>checkPassword

    boolean EmployeeCore::checkPassword($id_employee, string $passwd)

Check if employee password is the right one



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Employee.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L316)


#### Arguments
* $id_employee **mixed**
* $passwd **string** - &lt;p&gt;Password&lt;/p&gt;



### <a name="method-countProfile"></a>countProfile

    mixed EmployeeCore::countProfile($id_profile, $active_only)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Employee.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L330)


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### <a name="method-isLastAdmin"></a>isLastAdmin

    mixed EmployeeCore::isLastAdmin()





* Visibility: **public**
* This method is defined in [classes/Employee.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L339)




### <a name="method-setWsPasswd"></a>setWsPasswd

    mixed EmployeeCore::setWsPasswd($passwd)





* Visibility: **public**
* This method is defined in [classes/Employee.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L347)


#### Arguments
* $passwd **mixed**



### <a name="method-isLoggedBack"></a>isLoggedBack

    boolean EmployeeCore::isLoggedBack()

Check employee informations saved into cookie and return employee validity



* Visibility: **public**
* This method is defined in [classes/Employee.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L364)




### <a name="method-logout"></a>logout

    mixed EmployeeCore::logout()

Logout



* Visibility: **public**
* This method is defined in [classes/Employee.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L381)




### <a name="method-favoriteModulesList"></a>favoriteModulesList

    mixed EmployeeCore::favoriteModulesList()





* Visibility: **public**
* This method is defined in [classes/Employee.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L390)




### <a name="method-hasAuthOnShop"></a>hasAuthOnShop

    boolean EmployeeCore::hasAuthOnShop(integer $id_shop)

Check if the employee is associated to a specific shop



* Visibility: **public**
* This method is defined in [classes/Employee.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L406)


#### Arguments
* $id_shop **integer**



### <a name="method-hasAuthOnShopGroup"></a>hasAuthOnShopGroup

    boolean EmployeeCore::hasAuthOnShopGroup($id_shop_group)

Check if the employee is associated to a specific shop group



* Visibility: **public**
* This method is defined in [classes/Employee.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L418)


#### Arguments
* $id_shop_group **mixed**



### <a name="method-getDefaultShopID"></a>getDefaultShopID

    integer EmployeeCore::getDefaultShopID()

Get default id_shop with auth for current employee



* Visibility: **public**
* This method is defined in [classes/Employee.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L438)




### <a name="method-getEmployeesByProfile"></a>getEmployeesByProfile

    mixed EmployeeCore::getEmployeesByProfile($id_profile, $active_only)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Employee.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L446)


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### <a name="method-isSuperAdmin"></a>isSuperAdmin

    boolean EmployeeCore::isSuperAdmin()

Check if current employee is super administrator



* Visibility: **public**
* This method is defined in [classes/Employee.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L460)




### <a name="method-getImage"></a>getImage

    mixed EmployeeCore::getImage()





* Visibility: **public**
* This method is defined in [classes/Employee.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L465)




### <a name="method-getLastElementsForNotify"></a>getLastElementsForNotify

    mixed EmployeeCore::getLastElementsForNotify($element)





* Visibility: **public**
* This method is defined in [classes/Employee.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L473)


#### Arguments
* $element **mixed**



### <a name="method-setLastConnectionDate"></a>setLastConnectionDate

    mixed EmployeeCore::setLastConnectionDate($id_employee)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Employee.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Employee.php#L488)


#### Arguments
* $id_employee **mixed**


