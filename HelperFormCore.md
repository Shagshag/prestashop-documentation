HelperFormCore
===============






* Class name: HelperFormCore
* Namespace: 
* Parent class: Helper





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $first_call

    public mixed $first_call = true





* Visibility: **public**


### $fields_form

    protected array $fields_form = array()





* Visibility: **protected**


### $fields_value

    public array $fields_value = array()





* Visibility: **public**


### $name_controller

    public mixed $name_controller = ''





* Visibility: **public**


### $title

    public string $title = null





* Visibility: **public**


### $submit_action

    public string $submit_action





* Visibility: **public**


### $token

    public mixed $token





* Visibility: **public**


### $languages

    public mixed $languages = null





* Visibility: **public**


### $default_form_language

    public mixed $default_form_language = null





* Visibility: **public**


### $allow_employee_form_lang

    public mixed $allow_employee_form_lang = null





* Visibility: **public**


### $show_cancel_button

    public mixed $show_cancel_button = false





* Visibility: **public**


### $back_url

    public mixed $back_url = '#'





* Visibility: **public**


Methods
-------


### __construct

    mixed HelperFormCore::__construct()





* Visibility: **public**




### generateForm

    mixed HelperFormCore::generateForm($fields_form)





* Visibility: **public**


#### Arguments
* $fields_form **mixed**



### generate

    mixed HelperFormCore::generate()





* Visibility: **public**




### getFieldsRequired

    mixed HelperFormCore::getFieldsRequired()

Return true if there are required fields



* Visibility: **public**




### renderAssoShop

    string HelperFormCore::renderAssoShop($disable_shared, $template_directory)

Render an area to determinate shop association



* Visibility: **public**


#### Arguments
* $disable_shared **mixed**
* $template_directory **mixed**


