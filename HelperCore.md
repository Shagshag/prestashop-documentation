HelperCore
===============






* Class name: HelperCore
* This class is defined in [classes/helper/Helper.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L27)





Properties
----------

* [$currentIndex](#property-$currentIndex)
* [$table](#property-$table)
* [$identifier](#property-$identifier)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$ps_help_context](#property-$ps_help_context)
* [$title](#property-$title)
* [$show_toolbar](#property-$show_toolbar)
* [$context](#property-$context)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$bootstrap](#property-$bootstrap)
* [$module](#property-$module)
* [$base_folder](#property-$base_folder)
* [$override_folder](#property-$override_folder)
* [$tpl](#property-$tpl)
* [$base_tpl](#property-$base_tpl)
* [$tpl_vars](#property-$tpl_vars)

Methods
-------
* [__construct](#method-__construct)
* [setTpl](#method-setTpl)
* [createTemplate](#method-createTemplate)
* [generate](#method-generate)
* [renderAdminCategorieTree](#method-renderAdminCategorieTree)
* [renderCategoryTree](#method-renderCategoryTree)
* [l](#method-l)
* [renderRequiredFields](#method-renderRequiredFields)
* [renderModulesList](#method-renderModulesList)
* [renderShopList](#method-renderShopList)




Properties
----------


### <a name="property-$currentIndex"></a>$currentIndex

    public mixed $currentIndex





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L29)


### <a name="property-$table"></a>$table

    public mixed $table = 'configuration'





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L30)


### <a name="property-$identifier"></a>$identifier

    public mixed $identifier





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L31)


### <a name="property-$token"></a>$token

    public mixed $token





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L32)


### <a name="property-$toolbar_btn"></a>$toolbar_btn

    public mixed $toolbar_btn





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L33)


### <a name="property-$ps_help_context"></a>$ps_help_context

    public mixed $ps_help_context





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L34)


### <a name="property-$title"></a>$title

    public mixed $title





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L35)


### <a name="property-$show_toolbar"></a>$show_toolbar

    public mixed $show_toolbar = true





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L36)


### <a name="property-$context"></a>$context

    public mixed $context





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L37)


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

    public mixed $toolbar_scroll = false





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L38)


### <a name="property-$bootstrap"></a>$bootstrap

    public mixed $bootstrap = false





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L39)


### <a name="property-$module"></a>$module

    public \Module $module





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L44)


### <a name="property-$base_folder"></a>$base_folder

    public string $base_folder





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L47)


### <a name="property-$override_folder"></a>$override_folder

    public string $override_folder





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L50)


### <a name="property-$tpl"></a>$tpl

    protected \Smarty_Internal_Template $tpl





* Visibility: **protected**
* This property is defined in [classes/helper/Helper.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L55)


### <a name="property-$base_tpl"></a>$base_tpl

    public string $base_tpl = 'content.tpl'





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L60)


### <a name="property-$tpl_vars"></a>$tpl_vars

    public mixed $tpl_vars = array()





* Visibility: **public**
* This property is defined in [classes/helper/Helper.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L62)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HelperCore::__construct()





* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L64)




### <a name="method-setTpl"></a>setTpl

    mixed HelperCore::setTpl($tpl)





* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L69)


#### Arguments
* $tpl **mixed**



### <a name="method-createTemplate"></a>createTemplate

    \Smarty_Internal_Template HelperCore::createTemplate(string $tpl_name)

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L80)


#### Arguments
* $tpl_name **string** - &lt;p&gt;filename&lt;/p&gt;



### <a name="method-generate"></a>generate

    string HelperCore::generate()

default behaviour for helper is to return a tpl fetched



* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L110)




### <a name="method-renderAdminCategorieTree"></a>renderAdminCategorieTree

    mixed HelperCore::renderAdminCategorieTree($translations, $selected_cat, $input_name, $use_radio, $use_search, $disabled_categories, $use_in_popup)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/helper/Helper.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L119)


#### Arguments
* $translations **mixed**
* $selected_cat **mixed**
* $input_name **mixed**
* $use_radio **mixed**
* $use_search **mixed**
* $disabled_categories **mixed**
* $use_in_popup **mixed**



### <a name="method-renderCategoryTree"></a>renderCategoryTree

    string HelperCore::renderCategoryTree(array $root, array $selected_cat, string $input_name, boolean $use_radio, boolean $use_search, array $disabled_categories)





* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L166)


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



### <a name="method-l"></a>l

    string HelperCore::l(mixed $string, string $class, boolean $addslashes, boolean $htmlentities)

use translations files to replace english expression.



* Visibility: **protected**
* This method is defined in [classes/helper/Helper.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L299)


#### Arguments
* $string **mixed** - &lt;p&gt;term or expression in english&lt;/p&gt;
* $class **string**
* $addslashes **boolean** - &lt;p&gt;if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)&lt;/p&gt;



### <a name="method-renderRequiredFields"></a>renderRequiredFields

    string HelperCore::renderRequiredFields(string $class_name, string $identifier, array $table_fields)

Render a form with potentials required fields



* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L318)


#### Arguments
* $class_name **string**
* $identifier **string**
* $table_fields **array**



### <a name="method-renderModulesList"></a>renderModulesList

    mixed HelperCore::renderModulesList($modules_list)





* Visibility: **public**
* This method is defined in [classes/helper/Helper.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L350)


#### Arguments
* $modules_list **mixed**



### <a name="method-renderShopList"></a>renderShopList

    string HelperCore::renderShopList()

Render shop list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/helper/Helper.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/Helper.php#L374)



