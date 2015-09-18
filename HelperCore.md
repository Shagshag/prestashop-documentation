HelperCore
===============






* Class name: HelperCore
* Namespace: 





Properties
----------


### $currentIndex

    public mixed $currentIndex





* Visibility: **public**


### $table

    public mixed $table = 'configuration'





* Visibility: **public**


### $identifier

    public mixed $identifier





* Visibility: **public**


### $token

    public mixed $token





* Visibility: **public**


### $toolbar_btn

    public mixed $toolbar_btn





* Visibility: **public**


### $ps_help_context

    public mixed $ps_help_context





* Visibility: **public**


### $title

    public mixed $title





* Visibility: **public**


### $show_toolbar

    public mixed $show_toolbar = true





* Visibility: **public**


### $context

    public mixed $context





* Visibility: **public**


### $toolbar_scroll

    public mixed $toolbar_scroll = false





* Visibility: **public**


### $bootstrap

    public mixed $bootstrap = false





* Visibility: **public**


### $module

    public \Module $module





* Visibility: **public**


### $base_folder

    public string $base_folder





* Visibility: **public**


### $override_folder

    public string $override_folder





* Visibility: **public**


### $tpl

    protected \Smarty_Internal_Template $tpl





* Visibility: **protected**


### $base_tpl

    public string $base_tpl = 'content.tpl'





* Visibility: **public**


### $tpl_vars

    public mixed $tpl_vars = array()





* Visibility: **public**


Methods
-------


### __construct

    mixed HelperCore::__construct()





* Visibility: **public**




### setTpl

    mixed HelperCore::setTpl($tpl)





* Visibility: **public**


#### Arguments
* $tpl **mixed**



### createTemplate

    \Smarty_Internal_Template HelperCore::createTemplate(string $tpl_name)

Create a template from the override file, else from the base file.



* Visibility: **public**


#### Arguments
* $tpl_name **string** - &lt;p&gt;filename&lt;/p&gt;



### generate

    string HelperCore::generate()

default behaviour for helper is to return a tpl fetched



* Visibility: **public**




### renderAdminCategorieTree

    mixed HelperCore::renderAdminCategorieTree($translations, $selected_cat, $input_name, $use_radio, $use_search, $disabled_categories, $use_in_popup)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $translations **mixed**
* $selected_cat **mixed**
* $input_name **mixed**
* $use_radio **mixed**
* $use_search **mixed**
* $disabled_categories **mixed**
* $use_in_popup **mixed**



### renderCategoryTree

    string HelperCore::renderCategoryTree(array $root, array $selected_cat, string $input_name, boolean $use_radio, boolean $use_search, array $disabled_categories)





* Visibility: **public**


#### Arguments
* $root **array** - &lt;p&gt;array with the name and ID of the tree root category, if null the Shop&#039;s root category will be used&lt;/p&gt;
* $selected_cat **array** - &lt;p&gt;array of selected categories&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;            Format
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
            )&lt;/code&gt;&lt;/pre&gt;
* $input_name **string** - &lt;p&gt;name of input&lt;/p&gt;
* $use_radio **boolean** - &lt;p&gt;use radio tree or checkbox tree&lt;/p&gt;
* $use_search **boolean** - &lt;p&gt;display a find category search box&lt;/p&gt;
* $disabled_categories **array**



### l

    string HelperCore::l(mixed $string, string $class, boolean $addslashes, boolean $htmlentities)

use translations files to replace english expression.



* Visibility: **protected**


#### Arguments
* $string **mixed** - &lt;p&gt;term or expression in english&lt;/p&gt;
* $class **string**
* $addslashes **boolean** - &lt;p&gt;if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)&lt;/p&gt;



### renderRequiredFields

    string HelperCore::renderRequiredFields(string $class_name, string $identifier, array $table_fields)

Render a form with potentials required fields



* Visibility: **public**


#### Arguments
* $class_name **string**
* $identifier **string**
* $table_fields **array**



### renderModulesList

    mixed HelperCore::renderModulesList($modules_list)





* Visibility: **public**


#### Arguments
* $modules_list **mixed**



### renderShopList

    string HelperCore::renderShopList()

Render shop list



* Visibility: **public**
* This method is **static**.



