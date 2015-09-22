HelperFormCore
===============






* Class name: HelperFormCore
* Namespace: 
* Parent class: [Helper](HelperCore)
* This class is defined in classes\helper\HelperForm.php line 30





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 32


### $first_call

    public mixed $first_call = true





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 33


### $fields_form

    protected array $fields_form = array()





* Visibility: **protected**
* This property is defined in classes\helper\HelperForm.php line 36


### $fields_value

    public array $fields_value = array()





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 39


### $name_controller

    public mixed $name_controller = ''





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 40


### $title

    public string $title = null





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 43


### $submit_action

    public string $submit_action





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 46


### $token

    public mixed $token





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 48


### $languages

    public mixed $languages = null





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 49


### $default_form_language

    public mixed $default_form_language = null





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 50


### $allow_employee_form_lang

    public mixed $allow_employee_form_lang = null





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 51


### $show_cancel_button

    public mixed $show_cancel_button = false





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 52


### $back_url

    public mixed $back_url = '#'





* Visibility: **public**
* This property is defined in classes\helper\HelperForm.php line 53


Methods
-------


### __construct

    mixed HelperFormCore::__construct()





* Visibility: **public**
* This method is defined in classes\helper\HelperForm.php line 55




### generateForm

    mixed HelperFormCore::generateForm($fields_form)





* Visibility: **public**
* This method is defined in classes\helper\HelperForm.php line 62


#### Arguments
* $fields_form **mixed**



### generate

    mixed HelperFormCore::generate()





* Visibility: **public**
* This method is defined in classes\helper\HelperForm.php line 68




### getFieldsRequired

    mixed HelperFormCore::getFieldsRequired()

Return true if there are required fields



* Visibility: **public**
* This method is defined in classes\helper\HelperForm.php line 260




### renderAssoShop

    string HelperFormCore::renderAssoShop($disable_shared, $template_directory)

Render an area to determinate shop association



* Visibility: **public**
* This method is defined in classes\helper\HelperForm.php line 279


#### Arguments
* $disable_shared **mixed**
* $template_directory **mixed**


