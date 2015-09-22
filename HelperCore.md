HelperCore
===============






* Class name: HelperCore
* This class is defined in [classes/helper/Helper.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L27)





Properties
----------


### $currentIndex

    public mixed $currentIndex





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#29)


### $table

    public mixed $table = 'configuration'





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#30)


### $identifier

    public mixed $identifier





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#31)


### $token

    public mixed $token





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#32)


### $toolbar_btn

    public mixed $toolbar_btn





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#33)


### $ps_help_context

    public mixed $ps_help_context





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#34)


### $title

    public mixed $title





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#35)


### $show_toolbar

    public mixed $show_toolbar = true





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#36)


### $context

    public mixed $context





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#37)


### $toolbar_scroll

    public mixed $toolbar_scroll = false





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#38)


### $bootstrap

    public mixed $bootstrap = false





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#39)


### $module

    public \Module $module





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#44)


### $base_folder

    public string $base_folder





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#47)


### $override_folder

    public string $override_folder





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#50)


### $tpl

    protected \Smarty_Internal_Template $tpl





* Visibility: **protected**
* This property is defined in [classes/helper/Helper.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#55)


### $base_tpl

    public string $base_tpl = 'content.tpl'





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#60)


### $tpl_vars

    public mixed $tpl_vars = array()





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#62)


Methods
-------


### __construct

    mixed HelperCore::__construct()





* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#64)




### setTpl

    mixed HelperCore::setTpl($tpl)





* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#69)


#### Arguments
* $tpl **mixed**



### createTemplate

    \Smarty_Internal_Template HelperCore::createTemplate(string $tpl_name)

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#80)


#### Arguments
* $tpl_name **string** - &lt;p&gt;filename&lt;/p&gt;



### generate

    string HelperCore::generate()

default behaviour for helper is to return a tpl fetched



* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#110)




### renderAdminCategorieTree

    mixed HelperCore::renderAdminCategorieTree($translations, $selected_cat, $input_name, $use_radio, $use_search, $disabled_categories, $use_in_popup)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/helper/Helper.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#119)


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
* This method is defined in [classes/helper/Helper.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#166)


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
* This method is defined in [classes/helper/Helper.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#299)


#### Arguments
* $string **mixed** - &lt;p&gt;term or expression in english&lt;/p&gt;
* $class **string**
* $addslashes **boolean** - &lt;p&gt;if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)&lt;/p&gt;



### renderRequiredFields

    string HelperCore::renderRequiredFields(string $class_name, string $identifier, array $table_fields)

Render a form with potentials required fields



* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#318)


#### Arguments
* $class_name **string**
* $identifier **string**
* $table_fields **array**



### renderModulesList

    mixed HelperCore::renderModulesList($modules_list)





* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#350)


#### Arguments
* $modules_list **mixed**



### renderShopList

    string HelperCore::renderShopList()

Render shop list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/helper/Helper.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#374)



