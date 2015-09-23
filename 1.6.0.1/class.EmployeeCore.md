Class EmployeeCore
=====================





* Class name: EmployeeCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Employee.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$associated_shops](#property-$associated_shops)
* [$bo_color](#property-$bo_color)
* [$bo_menu](#property-$bo_menu)
* [$bo_show_screencast](#property-$bo_show_screencast)
* [$bo_theme](#property-$bo_theme)
* [$bo_width](#property-$bo_width)
* [$default_tab](#property-$default_tab)
* [$definition](#property-$definition)
* [$email](#property-$email)
* [$firstname](#property-$firstname)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_profile](#property-$id_profile)
* [$last_passwd_gen](#property-$last_passwd_gen)
* [$lastname](#property-$lastname)
* [$passwd](#property-$passwd)
* [$remote_addr](#property-$remote_addr)
* [$stats_compare_from](#property-$stats_compare_from)
* [$stats_compare_option](#property-$stats_compare_option)
* [$stats_compare_to](#property-$stats_compare_to)
* [$stats_date_from](#property-$stats_date_from)
* [$stats_date_to](#property-$stats_date_to)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [checkPassword](#method-checkPassword)
* [countProfile](#method-countProfile)
* [employeeExists](#method-employeeExists)
* [getByEmail](#method-getByEmail)
* [getDefaultShopID](#method-getDefaultShopID)
* [getEmployees](#method-getEmployees)
* [getEmployeesByProfile](#method-getEmployeesByProfile)
* [getFields](#method-getFields)
* [getImage](#method-getImage)
* [hasAuthOnShop](#method-hasAuthOnShop)
* [hasAuthOnShopGroup](#method-hasAuthOnShopGroup)
* [isLastAdmin](#method-isLastAdmin)
* [isLoggedBack](#method-isLoggedBack)
* [isSuperAdmin](#method-isSuperAdmin)
* [logout](#method-logout)
* [setWsPasswd](#method-setWsPasswd)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/Employee.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L77).


### <a name="property-$associated_shops"></a>$associated_shops

```php
protected mixed $associated_shops = array()
```





* Visibility: **protected**
* Source: [classes/Employee.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L121).


### <a name="property-$bo_color"></a>$bo_color

```php
public string $bo_color
```





* Visibility: **public**
* Source: [classes/Employee.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L60).


### <a name="property-$bo_menu"></a>$bo_menu

```php
public \bool, $bo_menu = 1
```





* Visibility: **public**
* Source: [classes/Employee.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L71).


### <a name="property-$bo_show_screencast"></a>$bo_show_screencast

```php
public mixed $bo_show_screencast = false
```





* Visibility: **public**
* Source: [classes/Employee.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L74).


### <a name="property-$bo_theme"></a>$bo_theme

```php
public string $bo_theme
```





* Visibility: **public**
* Source: [classes/Employee.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L65).


### <a name="property-$bo_width"></a>$bo_width

```php
public integer $bo_width
```





* Visibility: **public**
* Source: [classes/Employee.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L68).


### <a name="property-$default_tab"></a>$default_tab

```php
public mixed $default_tab
```





* Visibility: **public**
* Source: [classes/Employee.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L62).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'employee', 'primary' => 'id_employee', 'fields' => array('lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswdAdmin', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_profile' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'bo_color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'default_tab' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'bo_theme' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 32), 'bo_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'bo_menu' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'stats_date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_option' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Employee.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L84).


### <a name="property-$email"></a>$email

```php
public string $email
```





* Visibility: **public**
* Source: [classes/Employee.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L44).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Employee.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L41).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Employee.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L29).


### <a name="property-$id_lang"></a>$id_lang

```php
public string $id_lang
```





* Visibility: **public**
* Source: [classes/Employee.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L35).


### <a name="property-$id_profile"></a>$id_profile

```php
public string $id_profile
```





* Visibility: **public**
* Source: [classes/Employee.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L32).


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

```php
public \datetime $last_passwd_gen
```





* Visibility: **public**
* Source: [classes/Employee.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L50).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Employee.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L38).


### <a name="property-$passwd"></a>$passwd

```php
public string $passwd
```





* Visibility: **public**
* Source: [classes/Employee.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L47).


### <a name="property-$remote_addr"></a>$remote_addr

```php
public mixed $remote_addr
```





* Visibility: **public**
* Source: [classes/Employee.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L79).


### <a name="property-$stats_compare_from"></a>$stats_compare_from

```php
public mixed $stats_compare_from
```





* Visibility: **public**
* Source: [classes/Employee.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L55).


### <a name="property-$stats_compare_option"></a>$stats_compare_option

```php
public mixed $stats_compare_option = 1
```





* Visibility: **public**
* Source: [classes/Employee.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L57).


### <a name="property-$stats_compare_to"></a>$stats_compare_to

```php
public mixed $stats_compare_to
```





* Visibility: **public**
* Source: [classes/Employee.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L56).


### <a name="property-$stats_date_from"></a>$stats_date_from

```php
public mixed $stats_date_from
```





* Visibility: **public**
* Source: [classes/Employee.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L52).


### <a name="property-$stats_date_to"></a>$stats_date_to

```php
public mixed $stats_date_to
```





* Visibility: **public**
* Source: [classes/Employee.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L53).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'last_passwd_gen' => array('setter' => null), 'stats_date_from' => array('setter' => null), 'stats_date_to' => array('setter' => null), 'stats_compare_from' => array('setter' => null), 'stats_compare_to' => array('setter' => null), 'passwd' => array('setter' => 'setWsPasswd')))
```





* Visibility: **protected**
* Source: [classes/Employee.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L109).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed EmployeeCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Employee.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L123)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed EmployeeCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Employee.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L154)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-checkPassword"></a>checkPassword

```php
boolean EmployeeCore::checkPassword($id_employee, string $passwd)
```

Check if employee password is the right one



* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L218)


#### Arguments
* $id_employee **mixed**
* $passwd **string** - Password



### <a name="method-countProfile"></a>countProfile

```php
mixed EmployeeCore::countProfile($id_profile, $active_only)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L231)


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### <a name="method-employeeExists"></a>employeeExists

```php
mixed EmployeeCore::employeeExists($email)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L201)


#### Arguments
* $email **mixed**



### <a name="method-getByEmail"></a>getByEmail

```php
\Employee EmployeeCore::getByEmail(string $email, string $passwd)
```

Return employee instance from its e-mail (optionnaly check password)



* Visibility: **public**
* Source: [classes/Employee.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L180)


#### Arguments
* $email **string** - e-mail
* $passwd **string** - Password is also checked if specified



### <a name="method-getDefaultShopID"></a>getDefaultShopID

```php
integer EmployeeCore::getDefaultShopID()
```

Get default id_shop with auth for current employee



* Visibility: **public**
* Source: [classes/Employee.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L327)




### <a name="method-getEmployees"></a>getEmployees

```php
mixed EmployeeCore::getEmployees()
```

Return list of employees



* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L163)




### <a name="method-getEmployeesByProfile"></a>getEmployeesByProfile

```php
mixed EmployeeCore::getEmployeesByProfile($id_profile, $active_only)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L334)


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### <a name="method-getFields"></a>getFields

```php
array EmployeeCore::getFields()
```





* Visibility: **public**
* Source: [classes/Employee.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L137)




### <a name="method-getImage"></a>getImage

```php
mixed EmployeeCore::getImage()
```





* Visibility: **public**
* Source: [classes/Employee.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L353)




### <a name="method-hasAuthOnShop"></a>hasAuthOnShop

```php
boolean EmployeeCore::hasAuthOnShop(integer $id_shop)
```

Check if the employee is associated to a specific shop



* Visibility: **public**
* Source: [classes/Employee.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L298)


#### Arguments
* $id_shop **integer**



### <a name="method-hasAuthOnShopGroup"></a>hasAuthOnShopGroup

```php
boolean EmployeeCore::hasAuthOnShopGroup($id_shop_group)
```

Check if the employee is associated to a specific shop group



* Visibility: **public**
* Source: [classes/Employee.php line 310](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L310)


#### Arguments
* $id_shop_group **mixed**



### <a name="method-isLastAdmin"></a>isLastAdmin

```php
mixed EmployeeCore::isLastAdmin()
```





* Visibility: **public**
* Source: [classes/Employee.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L240)




### <a name="method-isLoggedBack"></a>isLoggedBack

```php
boolean EmployeeCore::isLoggedBack()
```

Check employee informations saved into cookie and return employee validity



* Visibility: **public**
* Source: [classes/Employee.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L265)




### <a name="method-isSuperAdmin"></a>isSuperAdmin

```php
boolean EmployeeCore::isSuperAdmin()
```

Check if current employee is super administrator



* Visibility: **public**
* Source: [classes/Employee.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L348)




### <a name="method-logout"></a>logout

```php
mixed EmployeeCore::logout()
```

Logout



* Visibility: **public**
* Source: [classes/Employee.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L281)




### <a name="method-setWsPasswd"></a>setWsPasswd

```php
mixed EmployeeCore::setWsPasswd($passwd)
```





* Visibility: **public**
* Source: [classes/Employee.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Employee.php#L248)


#### Arguments
* $passwd **mixed**


