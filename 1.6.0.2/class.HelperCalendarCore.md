Class HelperCalendarCore
=====================





* Class name: HelperCalendarCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperCalendar.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L27)


Contents
--------

### Constants

* [DEFAULT_COMPARE_OPTION](#constant-DEFAULT_COMPARE_OPTION)
* [DEFAULT_DATE_FORMAT](#constant-DEFAULT_DATE_FORMAT)

### Properties

* [$_actions](#property-$_actions)
* [$_compare_actions](#property-$_compare_actions)
* [$_compare_date_from](#property-$_compare_date_from)
* [$_compare_date_option](#property-$_compare_date_option)
* [$_compare_date_to](#property-$_compare_date_to)
* [$_date_format](#property-$_date_format)
* [$_date_from](#property-$_date_from)
* [$_date_to](#property-$_date_to)
* [$_rtl](#property-$_rtl)
* [$base_folder](#property-$base_folder)
* [$base_tpl](#property-$base_tpl)
* [$bootstrap](#property-$bootstrap)
* [$context](#property-$context)
* [$currentIndex](#property-$currentIndex)
* [$identifier](#property-$identifier)
* [$module](#property-$module)
* [$override_folder](#property-$override_folder)
* [$ps_help_context](#property-$ps_help_context)
* [$show_toolbar](#property-$show_toolbar)
* [$table](#property-$table)
* [$title](#property-$title)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$tpl](#property-$tpl)
* [$tpl_vars](#property-$tpl_vars)

### Methods

* [__construct](#method-__construct)
* [addAction](#method-addAction)
* [addCompareAction](#method-addCompareAction)
* [createTemplate](#method-createTemplate)
* [generate](#method-generate)
* [getActions](#method-getActions)
* [getCompareActions](#method-getCompareActions)
* [getCompareDateFrom](#method-getCompareDateFrom)
* [getCompareDateTo](#method-getCompareDateTo)
* [getCompareOption](#method-getCompareOption)
* [getDateFormat](#method-getDateFormat)
* [getDateFrom](#method-getDateFrom)
* [getDateTo](#method-getDateTo)
* [isRTL](#method-isRTL)
* [l](#method-l)
* [renderAdminCategorieTree](#method-renderAdminCategorieTree)
* [renderCategoryTree](#method-renderCategoryTree)
* [renderModulesList](#method-renderModulesList)
* [renderRequiredFields](#method-renderRequiredFields)
* [renderShopList](#method-renderShopList)
* [setActions](#method-setActions)
* [setCompareActions](#method-setCompareActions)
* [setCompareDateFrom](#method-setCompareDateFrom)
* [setCompareDateTo](#method-setCompareDateTo)
* [setCompareOption](#method-setCompareOption)
* [setDateFormat](#method-setDateFormat)
* [setDateFrom](#method-setDateFrom)
* [setDateTo](#method-setDateTo)
* [setRTL](#method-setRTL)
* [setTpl](#method-setTpl)


Constants
----------


### <a name="constant-DEFAULT_COMPARE_OPTION"></a>DEFAULT_COMPARE_OPTION

```php
const DEFAULT_COMPARE_OPTION = 1
```





* Source: [classes/helper/HelperCalendar.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L30).


### <a name="constant-DEFAULT_DATE_FORMAT"></a>DEFAULT_DATE_FORMAT

```php
const DEFAULT_DATE_FORMAT = 'Y-m-d'
```





* Source: [classes/helper/HelperCalendar.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L29).


Properties
----------


### <a name="property-$_actions"></a>$_actions

```php
private mixed $_actions
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L32).


### <a name="property-$_compare_actions"></a>$_compare_actions

```php
private mixed $_compare_actions
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L33).


### <a name="property-$_compare_date_from"></a>$_compare_date_from

```php
private mixed $_compare_date_from
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L34).


### <a name="property-$_compare_date_option"></a>$_compare_date_option

```php
private mixed $_compare_date_option
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L36).


### <a name="property-$_compare_date_to"></a>$_compare_date_to

```php
private mixed $_compare_date_to
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L35).


### <a name="property-$_date_format"></a>$_date_format

```php
private mixed $_date_format
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L37).


### <a name="property-$_date_from"></a>$_date_from

```php
private mixed $_date_from
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L38).


### <a name="property-$_date_to"></a>$_date_to

```php
private mixed $_date_to
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L39).


### <a name="property-$_rtl"></a>$_rtl

```php
private mixed $_rtl
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L40).


### <a name="property-$base_folder"></a>$base_folder

```php
public string $base_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L47).


### <a name="property-$base_tpl"></a>$base_tpl

```php
public string $base_tpl = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L60).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = false
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L39).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L37).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L29).


### <a name="property-$identifier"></a>$identifier

```php
public mixed $identifier
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L31).


### <a name="property-$module"></a>$module

```php
public \Module $module
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L44).


### <a name="property-$override_folder"></a>$override_folder

```php
public string $override_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L50).


### <a name="property-$ps_help_context"></a>$ps_help_context

```php
public mixed $ps_help_context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L34).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
public mixed $show_toolbar = true
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L36).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'configuration'
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L30).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L35).


### <a name="property-$token"></a>$token

```php
public mixed $token
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L32).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
public mixed $toolbar_btn
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L33).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
public mixed $toolbar_scroll = false
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L38).


### <a name="property-$tpl"></a>$tpl

```php
protected \smartyTemplate $tpl
```





* Visibility: **protected**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L55).


### <a name="property-$tpl_vars"></a>$tpl_vars

```php
public mixed $tpl_vars = array()
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L62).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperCalendarCore::__construct()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L42)




### <a name="method-addAction"></a>addAction

```php
mixed HelperCalendarCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L182)


#### Arguments
* $action **mixed**



### <a name="method-addCompareAction"></a>addCompareAction

```php
mixed HelperCalendarCore::addCompareAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L192)


#### Arguments
* $action **mixed**



### <a name="method-createTemplate"></a>createTemplate

```php
\Template HelperCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L80)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-generate"></a>generate

```php
mixed HelperCalendarCore::generate()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L202)




### <a name="method-getActions"></a>getActions

```php
mixed HelperCalendarCore::getActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L58)




### <a name="method-getCompareActions"></a>getCompareActions

```php
mixed HelperCalendarCore::getCompareActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L75)




### <a name="method-getCompareDateFrom"></a>getCompareDateFrom

```php
mixed HelperCalendarCore::getCompareDateFrom()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L89)




### <a name="method-getCompareDateTo"></a>getCompareDateTo

```php
mixed HelperCalendarCore::getCompareDateTo()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L100)




### <a name="method-getCompareOption"></a>getCompareOption

```php
mixed HelperCalendarCore::getCompareOption()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L111)




### <a name="method-getDateFormat"></a>getDateFormat

```php
mixed HelperCalendarCore::getDateFormat()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L128)




### <a name="method-getDateFrom"></a>getDateFrom

```php
mixed HelperCalendarCore::getDateFrom()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L148)




### <a name="method-getDateTo"></a>getDateTo

```php
mixed HelperCalendarCore::getDateTo()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L168)




### <a name="method-isRTL"></a>isRTL

```php
mixed HelperCalendarCore::isRTL()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L247)




### <a name="method-l"></a>l

```php
string HelperCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **protected**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L313)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string**
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-renderAdminCategorieTree"></a>renderAdminCategorieTree

```php
mixed HelperCore::renderAdminCategorieTree($translations, $selected_cat, $input_name, $use_radio, $use_search, $disabled_categories, $use_in_popup)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L120)


#### Arguments
* $translations **mixed**
* $selected_cat **mixed**
* $input_name **mixed**
* $use_radio **mixed**
* $use_search **mixed**
* $disabled_categories **mixed**
* $use_in_popup **mixed**



### <a name="method-renderCategoryTree"></a>renderCategoryTree

```php
string HelperCore::renderCategoryTree(array $root, \type $selected_cat, string $input_name, boolean $use_radio, boolean $use_search, array $disabled_categories, boolean $use_in_popup, boolean $use_shop_context)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L168)


#### Arguments
* $root **array** - array with the name and ID of the tree root category, if null the Shop&#039;s root category will be used
* $selected_cat **type** - array of selected categories
            Format
                Array
                (
                     [0] =&gt; 1
                 [1] =&gt; 2
            )
                OR
            Array
            (
                 [1] =&gt; Array
                      (
                            [id_category] =&gt; 1
                            [name] =&gt; Home page
                      )
            )
* $input_name **string** - name of input
* $use_radio **boolean** - use radio tree or checkbox tree
* $use_search **boolean** - display a find category search box
* $disabled_categories **array**
* $use_in_popup **boolean**
* $use_shop_context **boolean**



### <a name="method-renderModulesList"></a>renderModulesList

```php
mixed HelperCore::renderModulesList($modules_list)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L360)


#### Arguments
* $modules_list **mixed**



### <a name="method-renderRequiredFields"></a>renderRequiredFields

```php
string HelperCore::renderRequiredFields(string $class_name, string $identifier, array $table_fields)
```

Render a form with potentials required fields



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L331)


#### Arguments
* $class_name **string**
* $identifier **string**
* $table_fields **array**



### <a name="method-renderShopList"></a>renderShopList

```php
mixed HelperCore::renderShopList()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L369)




### <a name="method-setActions"></a>setActions

```php
mixed HelperCalendarCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L49)


#### Arguments
* $value **mixed**



### <a name="method-setCompareActions"></a>setCompareActions

```php
mixed HelperCalendarCore::setCompareActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L66)


#### Arguments
* $value **mixed**



### <a name="method-setCompareDateFrom"></a>setCompareDateFrom

```php
mixed HelperCalendarCore::setCompareDateFrom($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L83)


#### Arguments
* $value **mixed**



### <a name="method-setCompareDateTo"></a>setCompareDateTo

```php
mixed HelperCalendarCore::setCompareDateTo($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L94)


#### Arguments
* $value **mixed**



### <a name="method-setCompareOption"></a>setCompareOption

```php
mixed HelperCalendarCore::setCompareOption($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L105)


#### Arguments
* $value **mixed**



### <a name="method-setDateFormat"></a>setDateFormat

```php
mixed HelperCalendarCore::setDateFormat($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L119)


#### Arguments
* $value **mixed**



### <a name="method-setDateFrom"></a>setDateFrom

```php
mixed HelperCalendarCore::setDateFrom($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L136)


#### Arguments
* $value **mixed**



### <a name="method-setDateTo"></a>setDateTo

```php
mixed HelperCalendarCore::setDateTo($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L156)


#### Arguments
* $value **mixed**



### <a name="method-setRTL"></a>setRTL

```php
mixed HelperCalendarCore::setRTL($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/HelperCalendar.php#L176)


#### Arguments
* $value **mixed**



### <a name="method-setTpl"></a>setTpl

```php
mixed HelperCore::setTpl($tpl)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/helper/Helper.php#L69)


#### Arguments
* $tpl **mixed**


