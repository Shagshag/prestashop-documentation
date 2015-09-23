Class HelperFormCore
=====================





* Class name: HelperFormCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L30)


Contents
--------


### Properties

* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$back_url](#property-$back_url)
* [$default_form_language](#property-$default_form_language)
* [$fields_form](#property-$fields_form)
* [$fields_value](#property-$fields_value)
* [$first_call](#property-$first_call)
* [$id](#property-$id)
* [$languages](#property-$languages)
* [$name_controller](#property-$name_controller)
* [$show_cancel_button](#property-$show_cancel_button)
* [$submit_action](#property-$submit_action)
* [$title](#property-$title)
* [$token](#property-$token)

### Methods

* [__construct](#method-__construct)
* [generate](#method-generate)
* [generateForm](#method-generateForm)
* [getFieldsRequired](#method-getFieldsRequired)
* [renderAssoShop](#method-renderAssoShop)




Properties
----------


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L51).


### <a name="property-$back_url"></a>$back_url

```php
public mixed $back_url = '#'
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L53).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L50).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form = array()
```





* Visibility: **protected**
* Source: [classes/helper/HelperForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L36).


### <a name="property-$fields_value"></a>$fields_value

```php
public array $fields_value = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L39).


### <a name="property-$first_call"></a>$first_call

```php
public mixed $first_call = true
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L33).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L32).


### <a name="property-$languages"></a>$languages

```php
public mixed $languages = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L49).


### <a name="property-$name_controller"></a>$name_controller

```php
public mixed $name_controller = ''
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L40).


### <a name="property-$show_cancel_button"></a>$show_cancel_button

```php
public mixed $show_cancel_button = false
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L52).


### <a name="property-$submit_action"></a>$submit_action

```php
public string $submit_action
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L46).


### <a name="property-$title"></a>$title

```php
public string $title = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L43).


### <a name="property-$token"></a>$token

```php
public mixed $token
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L48).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperFormCore::__construct()
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L55)




### <a name="method-generate"></a>generate

```php
mixed HelperFormCore::generate()
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L68)




### <a name="method-generateForm"></a>generateForm

```php
mixed HelperFormCore::generateForm($fields_form)
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L62)


#### Arguments
* $fields_form **mixed**



### <a name="method-getFieldsRequired"></a>getFieldsRequired

```php
mixed HelperFormCore::getFieldsRequired()
```

Return true if there are required fields



* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L243)




### <a name="method-renderAssoShop"></a>renderAssoShop

```php
string HelperFormCore::renderAssoShop($disable_shared, $template_directory)
```

Render an area to determinate shop association



* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/helper/HelperForm.php#L259)


#### Arguments
* $disable_shared **mixed**
* $template_directory **mixed**


