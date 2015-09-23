Class EmployeeCore
=====================





* Class name: EmployeeCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Employee.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$associated_shops](#property-$associated_shops)
* [$bo_color](#property-$bo_color)
* [$bo_css](#property-$bo_css)
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
* [$id_shop](#property-$id_shop)
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
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [checkPassword](#method-checkPassword)
* [clearCache](#method-clearCache)
* [countProfile](#method-countProfile)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [employeeExists](#method-employeeExists)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getByEmail](#method-getByEmail)
* [getDefaultShopID](#method-getDefaultShopID)
* [getDefinition](#method-getDefinition)
* [getEmployees](#method-getEmployees)
* [getEmployeesByProfile](#method-getEmployeesByProfile)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getImage](#method-getImage)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasAuthOnShop](#method-hasAuthOnShop)
* [hasAuthOnShopGroup](#method-hasAuthOnShopGroup)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isLastAdmin](#method-isLastAdmin)
* [isLoggedBack](#method-isLoggedBack)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [isSuperAdmin](#method-isSuperAdmin)
* [logout](#method-logout)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setWsPasswd](#method-setWsPasswd)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/Employee.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L80).


### <a name="property-$associated_shops"></a>$associated_shops

```php
protected mixed $associated_shops = array()
```





* Visibility: **protected**
* Source: [classes/Employee.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L125).


### <a name="property-$bo_color"></a>$bo_color

```php
public string $bo_color
```





* Visibility: **public**
* Source: [classes/Employee.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L60).


### <a name="property-$bo_css"></a>$bo_css

```php
public string $bo_css = 'admin-theme.css'
```





* Visibility: **public**
* Source: [classes/Employee.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L68).


### <a name="property-$bo_menu"></a>$bo_menu

```php
public \bool, $bo_menu = 1
```





* Visibility: **public**
* Source: [classes/Employee.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L74).


### <a name="property-$bo_show_screencast"></a>$bo_show_screencast

```php
public mixed $bo_show_screencast = false
```





* Visibility: **public**
* Source: [classes/Employee.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L77).


### <a name="property-$bo_theme"></a>$bo_theme

```php
public string $bo_theme
```





* Visibility: **public**
* Source: [classes/Employee.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L65).


### <a name="property-$bo_width"></a>$bo_width

```php
public integer $bo_width
```





* Visibility: **public**
* Source: [classes/Employee.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L71).


### <a name="property-$default_tab"></a>$default_tab

```php
public mixed $default_tab
```





* Visibility: **public**
* Source: [classes/Employee.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L62).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'employee', 'primary' => 'id_employee', 'fields' => array('lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'required' => true, 'size' => 128), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswdAdmin', 'required' => true, 'size' => 32), 'last_passwd_gen' => array('type' => self::TYPE_STRING), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_profile' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'bo_color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'default_tab' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'bo_theme' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 32), 'bo_css' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'bo_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'bo_menu' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'stats_date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'stats_compare_option' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Employee.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L87).


### <a name="property-$email"></a>$email

```php
public string $email
```





* Visibility: **public**
* Source: [classes/Employee.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L44).


### <a name="property-$firstname"></a>$firstname

```php
public string $firstname
```





* Visibility: **public**
* Source: [classes/Employee.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L41).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Employee.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L29).


### <a name="property-$id_lang"></a>$id_lang

```php
public string $id_lang
```





* Visibility: **public**
* Source: [classes/Employee.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L35).


### <a name="property-$id_profile"></a>$id_profile

```php
public string $id_profile
```





* Visibility: **public**
* Source: [classes/Employee.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L32).


### <a name="property-$last_passwd_gen"></a>$last_passwd_gen

```php
public \datetime $last_passwd_gen
```





* Visibility: **public**
* Source: [classes/Employee.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L50).


### <a name="property-$lastname"></a>$lastname

```php
public string $lastname
```





* Visibility: **public**
* Source: [classes/Employee.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L38).


### <a name="property-$passwd"></a>$passwd

```php
public string $passwd
```





* Visibility: **public**
* Source: [classes/Employee.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L47).


### <a name="property-$remote_addr"></a>$remote_addr

```php
public mixed $remote_addr
```





* Visibility: **public**
* Source: [classes/Employee.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L82).


### <a name="property-$stats_compare_from"></a>$stats_compare_from

```php
public mixed $stats_compare_from
```





* Visibility: **public**
* Source: [classes/Employee.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L55).


### <a name="property-$stats_compare_option"></a>$stats_compare_option

```php
public mixed $stats_compare_option = 1
```





* Visibility: **public**
* Source: [classes/Employee.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L57).


### <a name="property-$stats_compare_to"></a>$stats_compare_to

```php
public mixed $stats_compare_to
```





* Visibility: **public**
* Source: [classes/Employee.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L56).


### <a name="property-$stats_date_from"></a>$stats_date_from

```php
public mixed $stats_date_from
```





* Visibility: **public**
* Source: [classes/Employee.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L52).


### <a name="property-$stats_date_to"></a>$stats_date_to

```php
public mixed $stats_date_to
```





* Visibility: **public**
* Source: [classes/Employee.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L53).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'last_passwd_gen' => array('setter' => null), 'stats_date_from' => array('setter' => null), 'stats_date_to' => array('setter' => null), 'stats_compare_from' => array('setter' => null), 'stats_compare_to' => array('setter' => null), 'passwd' => array('setter' => 'setWsPasswd')))
```





* Visibility: **protected**
* Source: [classes/Employee.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L113).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L130).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L80).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L65).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L95).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L85).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L90).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L105).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L63).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L59).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L61).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L75).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L116).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L119).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L70).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L110).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L135).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed EmployeeCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Employee.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L127)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed EmployeeCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Employee.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L161)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1209)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1261)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1196)




### <a name="method-checkPassword"></a>checkPassword

```php
boolean EmployeeCore::checkPassword($id_employee, string $passwd)
```

Check if employee password is the right one



* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L234)


#### Arguments
* $id_employee **mixed**
* $passwd **string** - Password



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1223)


#### Arguments
* $all **mixed**



### <a name="method-countProfile"></a>countProfile

```php
mixed EmployeeCore::countProfile($id_profile, $active_only)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L247)


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 688](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L688)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1392](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1392)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 734](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L734)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 979](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L979)


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
* Source: [classes/ObjectModel.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L518)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1305)


#### Arguments
* $id **mixed**



### <a name="method-employeeExists"></a>employeeExists

```php
mixed EmployeeCore::employeeExists($email)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L217)


#### Arguments
* $email **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1429](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1429)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L325)


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
* Source: [classes/ObjectModel.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L371)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1290](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1290)




### <a name="method-getByEmail"></a>getByEmail

```php
\Employee EmployeeCore::getByEmail(string $email, string $passwd)
```

Return employee instance from its e-mail (optionnaly check password)



* Visibility: **public**
* Source: [classes/Employee.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L196)


#### Arguments
* $email **string** - e-mail
* $passwd **string** - Password is also checked if specified



### <a name="method-getDefaultShopID"></a>getDefaultShopID

```php
integer EmployeeCore::getDefaultShopID()
```

Get default id_shop with auth for current employee



* Visibility: **public**
* Source: [classes/Employee.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L343)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1535](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1535)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getEmployees"></a>getEmployees

```php
mixed EmployeeCore::getEmployees()
```

Return list of employees



* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L179)




### <a name="method-getEmployeesByProfile"></a>getEmployeesByProfile

```php
mixed EmployeeCore::getEmployeesByProfile($id_profile, $active_only)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Employee.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L350)


#### Arguments
* $id_profile **mixed**
* $active_only **mixed**



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1642](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1642)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array EmployeeCore::getFields()
```





* Visibility: **public**
* Source: [classes/Employee.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L144)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L290)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1188](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1188)


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
* Source: [classes/ObjectModel.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L276)




### <a name="method-getImage"></a>getImage

```php
mixed EmployeeCore::getImage()
```





* Visibility: **public**
* Source: [classes/Employee.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L369)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L769)


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
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L148)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1129)


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
* Source: [classes/ObjectModel.php line 1051](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1051)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hasAuthOnShop"></a>hasAuthOnShop

```php
boolean EmployeeCore::hasAuthOnShop(integer $id_shop)
```

Check if the employee is associated to a specific shop



* Visibility: **public**
* Source: [classes/Employee.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L314)


#### Arguments
* $id_shop **integer**



### <a name="method-hasAuthOnShopGroup"></a>hasAuthOnShopGroup

```php
boolean EmployeeCore::hasAuthOnShopGroup($id_shop_group)
```

Check if the employee is associated to a specific shop group



* Visibility: **public**
* Source: [classes/Employee.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L326)


#### Arguments
* $id_shop_group **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1330)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1467](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1467)


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
* Source: [classes/ObjectModel.php line 1486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1486)


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
* Source: [classes/ObjectModel.php line 1238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1238)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1447)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1347)




### <a name="method-isLastAdmin"></a>isLastAdmin

```php
mixed EmployeeCore::isLastAdmin()
```





* Visibility: **public**
* Source: [classes/Employee.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L256)




### <a name="method-isLoggedBack"></a>isLoggedBack

```php
boolean EmployeeCore::isLoggedBack()
```

Check employee informations saved into cookie and return employee validity



* Visibility: **public**
* Source: [classes/Employee.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L281)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
mixed ObjectModelCore::isMultiShopField($field)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1342)


#### Arguments
* $field **mixed**



### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1337](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1337)




### <a name="method-isSuperAdmin"></a>isSuperAdmin

```php
boolean EmployeeCore::isSuperAdmin()
```

Check if current employee is super administrator



* Visibility: **public**
* Source: [classes/Employee.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L364)




### <a name="method-logout"></a>logout

```php
mixed EmployeeCore::logout()
```

Logout



* Visibility: **public**
* Source: [classes/Employee.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L297)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L785)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L415)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1573](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1573)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1668)


#### Arguments
* $fields **array**



### <a name="method-setWsPasswd"></a>setWsPasswd

```php
mixed EmployeeCore::setWsPasswd($passwd)
```





* Visibility: **public**
* Source: [classes/Employee.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L264)


#### Arguments
* $passwd **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 750](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L750)




### <a name="method-update"></a>update

```php
mixed EmployeeCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Employee.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Employee.php#L167)


#### Arguments
* $null_values **mixed**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1362](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1362)


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
* Source: [classes/ObjectModel.php line 997](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L997)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1003)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang, $skip, $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 896](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L896)


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
* Source: [classes/ObjectModel.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L823)


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
* Source: [classes/ObjectModel.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L852)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ObjectModel.php#L1165)


#### Arguments
* $htmlentities **mixed**


