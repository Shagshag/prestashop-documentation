EmployeeCore
===============






* Class name: EmployeeCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_profile

    public string $id_profile





* Visibility: **public**


### $id_lang

    public string $id_lang





* Visibility: **public**


### $lastname

    public string $lastname





* Visibility: **public**


### $firstname

    public string $firstname





* Visibility: **public**


### $email

    public string $email





* Visibility: **public**


### $passwd

    public string $passwd





* Visibility: **public**


### $last_passwd_gen

    public \datetime $last_passwd_gen





* Visibility: **public**


### $stats_date_from

    public mixed $stats_date_from





* Visibility: **public**


### $stats_date_to

    public mixed $stats_date_to





* Visibility: **public**


### $stats_compare_from

    public mixed $stats_compare_from





* Visibility: **public**


### $stats_compare_to

    public mixed $stats_compare_to





* Visibility: **public**


### $stats_compare_option

    public mixed $stats_compare_option = 1





* Visibility: **public**


### $preselect_date_range

    public mixed $preselect_date_range





* Visibility: **public**


### $bo_color

    public string $bo_color





* Visibility: **public**


### $default_tab

    public mixed $default_tab





* Visibility: **public**


### $bo_theme

    public string $bo_theme





* Visibility: **public**


### $bo_css

    public string $bo_css = 'admin-theme.css'





* Visibility: **public**


### $bo_width

    public integer $bo_width





* Visibility: **public**


### $bo_menu

    public \bool, $bo_menu = 1





* Visibility: **public**


### $bo_show_screencast

    public mixed $bo_show_screencast = false





* Visibility: **public**


### $active

    public boolean $active = 1





* Visibility: **public**


### $optin

    public boolean $optin = 1





* Visibility: **public**


### $remote_addr

    public mixed $remote_addr





* Visibility: **public**


### $id_last_order

    public mixed $id_last_order





* Visibility: **public**


### $id_last_customer_message

    public mixed $id_last_customer_message





* Visibility: **public**


### $id_last_customer

    public mixed $id_last_customer





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'employee', 'primary' => 'id_employee', 'fields' => array('lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswdAdmin', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'optin' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_profile' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'bo_color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'default_tab' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'bo_theme' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 32), 'bo_css' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'bo_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'bo_menu' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'stats_date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_option' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'preselect_date_range' => array('type' => self::TYPE_STRING, 'size' => 32), 'id_last_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_last_customer_message' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_last_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'last_passwd_gen' => array('setter' => null), 'stats_date_from' => array('setter' => null), 'stats_date_to' => array('setter' => null), 'stats_compare_from' => array('setter' => null), 'stats_compare_to' => array('setter' => null), 'passwd' => array('setter' => 'setWsPasswd')))





* Visibility: **protected**


### $associated_shops

    protected mixed $associated_shops = array()





* Visibility: **protected**


Methods
-------


### __construct

    mixed EmployeeCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### getFields

    array EmployeeCore::getFields()





* Visibility: **public**




### add

    mixed EmployeeCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed EmployeeCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### updateTextDirection

    mixed EmployeeCore::updateTextDirection()





* Visibility: **protected**




### saveOptin

    mixed EmployeeCore::saveOptin()





* Visibility: **protected**




### getEmployees

    array|false EmployeeCore::getEmployees(boolean $active_only)

Return list of employees



* Visibility: **public**
* This method is **static**.


#### Arguments
* $active_only **boolean** - &lt;p&gt;Filter employee by active status&lt;/p&gt;



### getByEmail

    \Employee EmployeeCore::getByEmail(string $email, string $passwd, boolean $active_only)

Return employee instance from its e-mail (optionnaly check password)



* Visibility: **public**


#### Arguments
* $email **string** - &lt;p&gt;e-mail&lt;/p&gt;
* $passwd **string** - &lt;p&gt;Password is also checked if specified&lt;/p&gt;
* $active_only **boolean** - &lt;p&gt;Filter employee by active status&lt;/p&gt;



### employeeExists

    mixed EmployeeCore::employeeExists($email)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $email **mixed**



### checkPassword

    boolean EmployeeCore::checkPassword($id_employee, string $passwd)

Check if employee password is the right one



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_employee **mixed**
* $passwd **string** - &lt;p&gt;Password&lt;/p&gt;



### countProfile

    mixed EmployeeCore::countProfile($id_profile, $active_only)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### isLastAdmin

    mixed EmployeeCore::isLastAdmin()





* Visibility: **public**




### setWsPasswd

    mixed EmployeeCore::setWsPasswd($passwd)





* Visibility: **public**


#### Arguments
* $passwd **mixed**



### isLoggedBack

    boolean EmployeeCore::isLoggedBack()

Check employee informations saved into cookie and return employee validity



* Visibility: **public**




### logout

    mixed EmployeeCore::logout()

Logout



* Visibility: **public**




### favoriteModulesList

    mixed EmployeeCore::favoriteModulesList()





* Visibility: **public**




### hasAuthOnShop

    boolean EmployeeCore::hasAuthOnShop(integer $id_shop)

Check if the employee is associated to a specific shop



* Visibility: **public**


#### Arguments
* $id_shop **integer**



### hasAuthOnShopGroup

    boolean EmployeeCore::hasAuthOnShopGroup($id_shop_group)

Check if the employee is associated to a specific shop group



* Visibility: **public**


#### Arguments
* $id_shop_group **mixed**



### getDefaultShopID

    integer EmployeeCore::getDefaultShopID()

Get default id_shop with auth for current employee



* Visibility: **public**




### getEmployeesByProfile

    mixed EmployeeCore::getEmployeesByProfile($id_profile, $active_only)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### isSuperAdmin

    boolean EmployeeCore::isSuperAdmin()

Check if current employee is super administrator



* Visibility: **public**




### getImage

    mixed EmployeeCore::getImage()





* Visibility: **public**




### getLastElementsForNotify

    mixed EmployeeCore::getLastElementsForNotify($element)





* Visibility: **public**


#### Arguments
* $element **mixed**



### setLastConnectionDate

    mixed EmployeeCore::setLastConnectionDate($id_employee)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_employee **mixed**


