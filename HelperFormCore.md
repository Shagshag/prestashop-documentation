HelperFormCore
===============






* Class name: HelperFormCore
* Parent class: [Helper](HelperCore)
* This class is defined in [classes/helper/HelperForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L30)





Properties
----------

* [$id](#property-$id)
* [$first_call](#property-$first_call)
* [$fields_form](#property-$fields_form)
* [$fields_value](#property-$fields_value)
* [$name_controller](#property-$name_controller)
* [$title](#property-$title)
* [$submit_action](#property-$submit_action)
* [$token](#property-$token)
* [$languages](#property-$languages)
* [$default_form_language](#property-$default_form_language)
* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$show_cancel_button](#property-$show_cancel_button)
* [$back_url](#property-$back_url)

Methods
-------
* [__construct](#method-__construct)
* [generateForm](#method-generateForm)
* [generate](#method-generate)
* [getFieldsRequired](#method-getFieldsRequired)
* [renderAssoShop](#method-renderAssoShop)




Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L32)


### <a name="property-$first_call"></a>$first_call

    public mixed $first_call = true





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L33)


### <a name="property-$fields_form"></a>$fields_form

    protected array $fields_form = array()





* Visibility: **protected**
* This property is defined in [classes/helper/HelperForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L36)


### <a name="property-$fields_value"></a>$fields_value

    public array $fields_value = array()





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L39)


### <a name="property-$name_controller"></a>$name_controller

    public mixed $name_controller = ''





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L40)


### <a name="property-$title"></a>$title

    public string $title = null





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L43)


### <a name="property-$submit_action"></a>$submit_action

    public string $submit_action





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L46)


### <a name="property-$token"></a>$token

    public mixed $token





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L48)


### <a name="property-$languages"></a>$languages

    public mixed $languages = null





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L49)


### <a name="property-$default_form_language"></a>$default_form_language

    public mixed $default_form_language = null





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L50)


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

    public mixed $allow_employee_form_lang = null





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L51)


### <a name="property-$show_cancel_button"></a>$show_cancel_button

    public mixed $show_cancel_button = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L52)


### <a name="property-$back_url"></a>$back_url

    public mixed $back_url = '#'





* Visibility: **public**
* This property is defined in [classes/helper/HelperForm.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L53)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HelperFormCore::__construct()





* Visibility: **public**
* This method is defined in [classes/helper/HelperForm.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L55)




### <a name="method-generateForm"></a>generateForm

    mixed HelperFormCore::generateForm($fields_form)





* Visibility: **public**
* This method is defined in [classes/helper/HelperForm.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L62)


#### Arguments
* $fields_form **mixed**



### <a name="method-generate"></a>generate

    mixed HelperFormCore::generate()





* Visibility: **public**
* This method is defined in [classes/helper/HelperForm.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L68)




### <a name="method-getFieldsRequired"></a>getFieldsRequired

    mixed HelperFormCore::getFieldsRequired()

Return true if there are required fields



* Visibility: **public**
* This method is defined in [classes/helper/HelperForm.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L260)




### <a name="method-renderAssoShop"></a>renderAssoShop

    string HelperFormCore::renderAssoShop($disable_shared, $template_directory)

Render an area to determinate shop association



* Visibility: **public**
* This method is defined in [classes/helper/HelperForm.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperForm.php#L279)


#### Arguments
* $disable_shared **mixed**
* $template_directory **mixed**


