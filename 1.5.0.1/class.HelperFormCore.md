Class HelperFormCore
=====================





* Class name: HelperFormCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/HelperForm.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L28)


Contents
--------


### Properties

* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$default_form_language](#property-$default_form_language)
* [$fields_form](#property-$fields_form)
* [$fields_value](#property-$fields_value)
* [$first_call](#property-$first_call)
* [$id](#property-$id)
* [$languages](#property-$languages)
* [$submit_action](#property-$submit_action)
* [$table](#property-$table)
* [$title](#property-$title)
* [$token](#property-$token)
* [$base_folder](#property-$base_folder)
* [$base_tpl](#property-$base_tpl)
* [$context](#property-$context)
* [$currentIndex](#property-$currentIndex)
* [$identifier](#property-$identifier)
* [$override_folder](#property-$override_folder)
* [$ps_help_context](#property-$ps_help_context)
* [$show_toolbar](#property-$show_toolbar)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_fix](#property-$toolbar_fix)
* [$tpl](#property-$tpl)
* [$tpl_vars](#property-$tpl_vars)

### Methods

* [__construct](#method-__construct)
* [buildHtmlOptions](#method-buildHtmlOptions)
* [createTemplate](#method-createTemplate)
* [displayAssoShop](#method-displayAssoShop)
* [generate](#method-generate)
* [generateForm](#method-generateForm)
* [getFieldsRequired](#method-getFieldsRequired)
* [l](#method-l)
* [renderAdminCategorieTree](#method-renderAdminCategorieTree)
* [selectInput](#method-selectInput)
* [setTpl](#method-setTpl)




Properties
----------


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang = null
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L50).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language = null
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L49).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form = array()
```





* Visibility: **protected**
* Source: [classes/HelperForm.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L34).


### <a name="property-$fields_value"></a>$fields_value

```php
public array $fields_value = array()
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L37).


### <a name="property-$first_call"></a>$first_call

```php
public mixed $first_call = true
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L31).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L30).


### <a name="property-$languages"></a>$languages

```php
public mixed $languages = null
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L48).


### <a name="property-$submit_action"></a>$submit_action

```php
public string $submit_action = ''
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L45).


### <a name="property-$table"></a>$table

```php
public mixed $table
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L39).


### <a name="property-$title"></a>$title

```php
public string $title = null
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L42).


### <a name="property-$token"></a>$token

```php
public mixed $token
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L47).


### <a name="property-$base_folder"></a>$base_folder

```php
public string $base_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L47).


### <a name="property-$base_tpl"></a>$base_tpl

```php
public string $base_tpl = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L60).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L43).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L35).


### <a name="property-$identifier"></a>$identifier

```php
public mixed $identifier
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L37).


### <a name="property-$override_folder"></a>$override_folder

```php
public string $override_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L50).


### <a name="property-$ps_help_context"></a>$ps_help_context

```php
public mixed $ps_help_context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L40).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
public mixed $show_toolbar = true
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L42).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
public mixed $toolbar_btn
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L39).


### <a name="property-$toolbar_fix"></a>$toolbar_fix

```php
public mixed $toolbar_fix = false
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L44).


### <a name="property-$tpl"></a>$tpl

```php
protected \smartyTemplate $tpl
```





* Visibility: **protected**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L55).


### <a name="property-$tpl_vars"></a>$tpl_vars

```php
public mixed $tpl_vars = array()
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L62).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperFormCore::__construct()
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L52)




### <a name="method-buildHtmlOptions"></a>buildHtmlOptions

```php
string HelperCore::buildHtmlOptions(array $html_options)
```

Create html a string containing html options
eg: buildHtmlOptions(array('name' => 'myInputName', 'id' => 'myInputId'));
    return => 'name="myInputName" id="myInputId"'



* Visibility: **protected**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L263)


#### Arguments
* $html_options **array**



### <a name="method-createTemplate"></a>createTemplate

```php
\Template HelperCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L80)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-displayAssoShop"></a>displayAssoShop

```php
mixed HelperCore::displayAssoShop($type)
```





* Visibility: **protected**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L302)


#### Arguments
* $type **mixed**



### <a name="method-generate"></a>generate

```php
mixed HelperFormCore::generate()
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L65)




### <a name="method-generateForm"></a>generateForm

```php
mixed HelperFormCore::generateForm($fields_form)
```





* Visibility: **public**
* Source: [classes/HelperForm.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L59)


#### Arguments
* $fields_form **mixed**



### <a name="method-getFieldsRequired"></a>getFieldsRequired

```php
mixed HelperFormCore::getFieldsRequired()
```

Return true if there are required fields



* Visibility: **public**
* Source: [classes/HelperForm.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperForm.php#L173)




### <a name="method-l"></a>l

```php
string HelperCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **protected**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L282)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string**
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-renderAdminCategorieTree"></a>renderAdminCategorieTree

```php
string HelperCore::renderAdminCategorieTree(\type $trads, \type $selected_cat, \type $input_name, $use_radio, $use_search, $disabled_categories)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L124)


#### Arguments
* $trads **type** - values of translations keys
				For the moment, translation are not automatic
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
                            [link_rewrite] =&gt; home
                      )
            )
* $input_name **type** - name of input
* $use_radio **mixed**
* $use_search **mixed**
* $disabled_categories **mixed**



### <a name="method-selectInput"></a>selectInput

```php
string HelperCore::selectInput(array $values, array $html_options, array $select_options)
```

Create a select input field



* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L219)


#### Arguments
* $values **array**
* $html_options **array** - any key =&gt; value options
* $select_options **array** - 
key: the array value that will be used as a key in my select (optional)
value: the array value that will be used as a label in my select (optional)
empty: the label displayed as an empty value (optional)
selected: the key corresponding to the selected value  (optional)




### <a name="method-setTpl"></a>setTpl

```php
mixed HelperCore::setTpl($tpl)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L69)


#### Arguments
* $tpl **mixed**


