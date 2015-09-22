AdminControllerCore
===============

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.


* Class name: AdminControllerCore
* Namespace: 
* Parent class: [Controller](ControllerCore)
* This class is defined in classes\controller\AdminController.php line 27





Properties
----------


### $path

    public string $path





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 30


### $currentIndex

    public string $currentIndex





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\controller\AdminController.php line 33


### $content

    public string $content





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 36


### $warnings

    public array $warnings = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 39


### $informations

    public array $informations = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 42


### $confirmations

    public array $confirmations = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 45


### $shopShareDatas

    public string $shopShareDatas = false





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 48


### $_languages

    public array $_languages = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 51


### $default_form_language

    public integer $default_form_language





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 54


### $allow_employee_form_lang

    public boolean $allow_employee_form_lang





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 57


### $layout

    public string $layout = 'layout.tpl'





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 60


### $bootstrap

    public boolean $bootstrap = false





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 63


### $meta_title

    protected string $meta_title = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 66


### $template

    public string $template = 'content.tpl'





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 69


### $table

    public string $table = 'configuration'





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 72


### $list_id

    public string $list_id





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 75


### $identifier

    protected string $identifier = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 78


### $identifier_name

    protected string $identifier_name = 'name'





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 81


### $className

    public string $className





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 84


### $tabAccess

    public array $tabAccess





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 87


### $id

    public integer $id = -1





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 90


### $required_database

    public boolean $required_database = false





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 93


### $token

    public string $token





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 96


### $shopLinkType

    public string $shopLinkType





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 99


### $_defaultOrderBy

    protected string $_defaultOrderBy = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 102


### $_defaultOrderWay

    protected string $_defaultOrderWay = 'ASC'





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 105


### $tpl_form_vars

    public array $tpl_form_vars = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 108


### $tpl_list_vars

    public array $tpl_list_vars = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 111


### $tpl_delete_link_vars

    public array $tpl_delete_link_vars = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 114


### $tpl_option_vars

    public array $tpl_option_vars = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 117


### $tpl_view_vars

    public array $tpl_view_vars = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 120


### $tpl_required_fields_vars

    public array $tpl_required_fields_vars = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 123


### $base_tpl_view

    public string $base_tpl_view = null





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 126


### $base_tpl_form

    public string $base_tpl_form = null





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 129


### $multiple_fieldsets

    public boolean $multiple_fieldsets = false





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 132


### $fields_value

    public array $fields_value = false





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 135


### $errors

    public array $errors = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 138


### $list_simple_header

    protected boolean $list_simple_header





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 141


### $fields_list

    protected array $fields_list





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 144


### $filter_modules_list

    protected array $filter_modules_list = null





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 147


### $modules_list

    protected array $modules_list = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 150


### $fields_form

    protected array $fields_form





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 153


### $fields_form_override

    protected array $fields_form_override





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 156


### $submit_action

    protected string $submit_action





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 159


### $fields_options

    protected array $fields_options = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 162


### $shopLink

    protected string $shopLink





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 165


### $_listsql

    protected string $_listsql = ''





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 168


### $_list

    protected array $_list = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 171


### $toolbar_title

    protected string $toolbar_title





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 174


### $toolbar_btn

    protected array $toolbar_btn = null





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 177


### $toolbar_scroll

    protected boolean $toolbar_scroll = true





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 180


### $show_toolbar

    protected boolean $show_toolbar = true





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 183


### $show_toolbar_options

    protected boolean $show_toolbar_options = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 186


### $_listTotal

    protected integer $_listTotal





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 189


### $lang

    public boolean $lang = false





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 192


### $_filter

    protected array $_filter





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 195


### $_filterHaving

    protected string $_filterHaving





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 198


### $_tmpTableFilter

    protected array $_tmpTableFilter = ''





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 201


### $_pagination

    protected array $_pagination = array(20, 50, 100, 300, 1000)





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 204


### $_default_pagination

    protected integer $_default_pagination = 50





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 207


### $_orderBy

    protected string $_orderBy





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 210


### $_orderWay

    protected string $_orderWay





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 213


### $actions_available

    protected array $actions_available = array('view', 'edit', 'duplicate', 'delete')





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 216


### $actions

    protected array $actions = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 219


### $list_skip_actions

    protected array $list_skip_actions = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 222


### $lite_display

    protected mixed $lite_display = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 225


### $list_no_link

    protected boolean $list_no_link = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 228


### $allow_export

    protected boolean $allow_export = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 231


### $cache_lang

    public array $cache_lang = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\controller\AdminController.php line 234


### $required_fields

    public array $required_fields = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 237


### $helper

    protected \HelperList $helper





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 240


### $bulk_actions

    protected array $bulk_actions

Actions to execute on multiple selections.

Usage:

array(
     'actionName' => array(
     'text' => $this->l('Message displayed on the submit button (mandatory)'),
     'confirm' => $this->l('If set, this confirmation message will pop-up (optional)')),
     'anotherAction' => array(...)
);

If your action is named 'actionName', you need to have a method named bulkactionName() that will be executed when the button is clicked.

* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 258


### $boxes

    protected mixed $boxes





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 261


### $explicitSelect

    protected string $explicitSelect = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 264


### $_select

    protected string $_select





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 267


### $_join

    protected string $_join





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 270


### $_where

    protected string $_where





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 273


### $_group

    protected string $_group





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 276


### $_having

    protected string $_having





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 279


### $_use_found_rows

    protected string $_use_found_rows = true





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 282


### $is_cms

    protected boolean $is_cms = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 285


### $position_identifier

    protected string $position_identifier





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 288


### $position_group_identifier

    protected string $position_group_identifier





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 291


### $deleted

    protected boolean $deleted = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 294


### $filter

    protected boolean $filter





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 297


### $noLink

    protected boolean $noLink





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 300


### $specificConfirmDelete

    protected boolean $specificConfirmDelete = null





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 303


### $colorOnBackground

    protected boolean $colorOnBackground





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 306


### $row_hover

    protected boolean $row_hover = true





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 309


### $action

    protected string $action





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 312


### $display

    protected string $display





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 315


### $_includeContainer

    protected boolean $_includeContainer = true





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 318


### $tab_modules_list

    protected array $tab_modules_list = array('default_list' => array(), 'slider_list' => array())





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 321


### $tpl_folder

    public string $tpl_folder





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 324


### $bo_theme

    protected string $bo_theme





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 327


### $_redirect

    protected boolean $_redirect = true





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 330


### $fieldImageSettings

    public array $fieldImageSettings = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 333


### $imageType

    public string $imageType = 'jpg'





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 336


### $object

    protected \ObjectModel $object





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 339


### $id_object

    protected integer $id_object





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 342


### $controller_name

    public string $controller_name





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 345


### $multishop_context

    public integer $multishop_context = -1





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 348


### $multishop_context_group

    public false $multishop_context_group = true





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 351


### $breadcrumbs

    protected array $breadcrumbs





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 354


### $show_page_header_toolbar

    public boolean $show_page_header_toolbar = false





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 357


### $page_header_toolbar_title

    public string $page_header_toolbar_title





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 360


### $page_header_toolbar_btn

    public array $page_header_toolbar_btn = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 363


### $show_form_cancel_button

    public boolean $show_form_cancel_button





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 366


### $admin_webpath

    public string $admin_webpath





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 369


### $list_natives_modules

    protected array $list_natives_modules = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 372


### $list_partners_modules

    protected array $list_partners_modules = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 375


### $modals

    public array $modals = array()





* Visibility: **public**
* This property is defined in classes\controller\AdminController.php line 378


### $logged_on_addons

    protected boolean $logged_on_addons = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 381


### $can_import

    protected boolean $can_import = false





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 384


### $is_prestashop_up

    protected boolean $is_prestashop_up = true





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\controller\AdminController.php line 3976


### $translationsTab

    protected array $translationsTab = array()





* Visibility: **protected**
* This property is defined in classes\controller\AdminController.php line 4038


Methods
-------


### __construct

    mixed AdminControllerCore::__construct()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 386




### initBreadcrumbs

    mixed AdminControllerCore::initBreadcrumbs(integer|null $tab_id, array|null $tabs)

Set breadcrumbs array for the controller page



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 537


#### Arguments
* $tab_id **integer|null**
* $tabs **array|null**



### initToolbarTitle

    void AdminControllerCore::initToolbarTitle()

Set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 617




### addFiltersToBreadcrumbs

    string|void AdminControllerCore::addFiltersToBreadcrumbs()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 646




### viewAccess

    boolean AdminControllerCore::viewAccess(boolean $disable)

Check rights to view the current tab



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 693


#### Arguments
* $disable **boolean**



### checkToken

    boolean AdminControllerCore::checkToken()

Check for security token



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 710




### processFilter

    mixed AdminControllerCore::processFilter()

Set the filters used for the list display



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 743




### postProcess

    boolean AdminControllerCore::postProcess()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 860




### processDeleteImage

    \ObjectModel|false AdminControllerCore::processDeleteImage()

Object Delete images



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 915




### processExport

    mixed AdminControllerCore::processExport(string $text_delimiter)





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 935


#### Arguments
* $text_delimiter **string**



### processDelete

    \ObjectModel|false AdminControllerCore::processDelete()

Object Delete



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1002




### processSave

    \ObjectModel|false|void AdminControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1048




### processAdd

    \ObjectModel|false AdminControllerCore::processAdd()

Object creation



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1064




### processUpdate

    \ObjectModel|false|void AdminControllerCore::processUpdate()

Object update



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1115




### processUpdateFields

    \ObjectModel AdminControllerCore::processUpdateFields()

Change object required fields



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1208




### processStatus

    \ObjectModel|false AdminControllerCore::processStatus()

Change object status (active, inactive)



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1232




### processPosition

    \ObjectModel|false AdminControllerCore::processPosition()

Change object position



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1266




### processResetFilters

    mixed AdminControllerCore::processResetFilters(integer|null $list_id)

Cancel all filters for this tab



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1286


#### Arguments
* $list_id **integer|null**



### processUpdateOptions

    mixed AdminControllerCore::processUpdateOptions()

Update options and preferences



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 1323




### initPageHeaderToolbar

    mixed AdminControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1443




### initToolbar

    mixed AdminControllerCore::initToolbar()

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1508




### loadObject

    \ObjectModel|false AdminControllerCore::loadObject(boolean $opt)

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 1576


#### Arguments
* $opt **boolean** - &lt;p&gt;Return an empty object if load fail&lt;/p&gt;



### checkAccess

    boolean AdminControllerCore::checkAccess()

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1609




### filterToField

    array|false AdminControllerCore::filterToField(string $key, string $filter)





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 1634


#### Arguments
* $key **string**
* $filter **string**



### displayNoSmarty

    mixed AdminControllerCore::displayNoSmarty()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1651




### displayAjax

    void AdminControllerCore::displayAjax()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1658




### redirect

    mixed AdminControllerCore::redirect()





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 1673




### display

    void AdminControllerCore::display()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1683




### displayWarning

    mixed AdminControllerCore::displayWarning(string $msg)

Add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 1767


#### Arguments
* $msg **string**



### displayInformation

    mixed AdminControllerCore::displayInformation(string $msg)

Add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 1777


#### Arguments
* $msg **string**



### initHeader

    mixed AdminControllerCore::initHeader()

Assign smarty variables for the header



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1785




### addRowAction

    mixed AdminControllerCore::addRowAction(string $action)

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1967


#### Arguments
* $action **string**



### addRowActionSkipList

    mixed AdminControllerCore::addRowActionSkipList(string $action, array $list)

Add an action to use for each row in the list



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1979


#### Arguments
* $action **string**
* $list **array**



### initContent

    mixed AdminControllerCore::initContent()

Assign smarty variables for all default views, list and form, then call other init functions



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 1994




### initTabModuleList

    mixed AdminControllerCore::initTabModuleList()

Init tab modules list and add button in toolbar



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 2048




### addPageHeaderToolBarModulesListButton

    mixed AdminControllerCore::addPageHeaderToolBarModulesListButton()





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 2087




### addToolBarModulesListButton

    mixed AdminControllerCore::addToolBarModulesListButton()





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 2099




### filterTabModuleList

    mixed AdminControllerCore::filterTabModuleList()





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 2111




### initCursedPage

    void AdminControllerCore::initCursedPage()

Initialize the invalid doom page of death



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2179




### initFooter

    mixed AdminControllerCore::initFooter()

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2187




### initModal

    mixed AdminControllerCore::initModal()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2213




### renderModal

    string AdminControllerCore::renderModal()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2256




### renderModulesList

    string AdminControllerCore::renderModulesList()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2271




### renderList

    string|false AdminControllerCore::renderList()

Function used to render the list to display for this controller



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2325




### getTemplateListVars

    mixed AdminControllerCore::getTemplateListVars()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2382




### renderView

    string AdminControllerCore::renderView()

Override to render the view page



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2392




### getTemplateViewVars

    mixed AdminControllerCore::getTemplateViewVars()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2405




### renderDetails

    string|false AdminControllerCore::renderDetails()

Override to render the view page



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2415




### renderForm

    string AdminControllerCore::renderForm()

Function used to render the form for this controller



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2427




### getTemplateFormVars

    mixed AdminControllerCore::getTemplateFormVars()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2485




### renderKpis

    mixed AdminControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2490




### renderOptions

    string AdminControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2499




### setHelperDisplay

    void AdminControllerCore::setHelperDisplay(\Helper $helper)

This function sets various display options for helper list



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2531


#### Arguments
* $helper **[Helper](HelperCore)**



### setDeprecatedMedia

    mixed AdminControllerCore::setDeprecatedMedia()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2586




### setMedia

    mixed AdminControllerCore::setMedia()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2590




### l

    string AdminControllerCore::l(string $string, string|null $class, boolean $addslashes, boolean $htmlentities)

Non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 2648


#### Arguments
* $string **string** - &lt;p&gt;Term or expression in english&lt;/p&gt;
* $class **string|null** - &lt;p&gt;Name of the class&lt;/p&gt;
* $addslashes **boolean** - &lt;p&gt;If set to true, the return value will pass through addslashes(). Otherwise, stripslashes().&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;If set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)&lt;/p&gt;



### init

    mixed AdminControllerCore::init()

Init context and dependencies, handles POST and GET



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2662




### initShopContext

    mixed AdminControllerCore::initShopContext()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2751




### initProcess

    mixed AdminControllerCore::initProcess()

Retrieve GET and POST value and translate them to actions



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 2821




### getList

    mixed AdminControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

Get the current objects' list form the database



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3005


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language used for display&lt;/p&gt;
* $order_by **string|null** - &lt;p&gt;ORDER BY clause&lt;/p&gt;
* $order_way **string|null** - &lt;p&gt;Order way (ASC, DESC)&lt;/p&gt;
* $start **integer** - &lt;p&gt;Offset in LIMIT clause&lt;/p&gt;
* $limit **integer|null** - &lt;p&gt;Row count in LIMIT clause&lt;/p&gt;
* $id_lang_shop **integer|boolean**



### getModulesList

    boolean AdminControllerCore::getModulesList(array|string $filter_modules_list)





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3241


#### Arguments
* $filter_modules_list **array|string**



### getLanguages

    array AdminControllerCore::getLanguages()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3282




### getFieldsValue

    array AdminControllerCore::getFieldsValue(\ObjectModel $obj)

Return the list of fields value



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3314


#### Arguments
* $obj **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;



### getFieldValue

    string AdminControllerCore::getFieldValue(\ObjectModel $obj, string $key, integer|null $id_lang)

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3365


#### Arguments
* $obj **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;
* $key **string** - &lt;p&gt;Field name&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Language id (optional)&lt;/p&gt;



### validateRules

    mixed AdminControllerCore::validateRules(string|boolean $class_name)

Manage page display (form, list.

..)

* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3382


#### Arguments
* $class_name **string|boolean** - &lt;p&gt;Allow to validate a different class than the current one&lt;/p&gt;



### _childValidation

    mixed AdminControllerCore::_childValidation()

Overload this method for custom checking



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3460




### viewDetails

    mixed AdminControllerCore::viewDetails()

Display object details



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3467




### beforeDelete

    boolean AdminControllerCore::beforeDelete(\ObjectModel $object)

Called before deletion



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3477


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;



### afterDelete

    boolean AdminControllerCore::afterDelete(\ObjectModel $object, integer $old_id)

Called before deletion



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3489


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;
* $old_id **integer**



### afterAdd

    boolean AdminControllerCore::afterAdd(\ObjectModel $object)





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3498


#### Arguments
* $object **[ObjectModel](ObjectModelCore)**



### afterUpdate

    boolean AdminControllerCore::afterUpdate(\ObjectModel $object)





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3507


#### Arguments
* $object **[ObjectModel](ObjectModelCore)**



### afterImageUpload

    boolean AdminControllerCore::afterImageUpload()

Check rights to view the current tab



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3517




### copyFromPost

    mixed AdminControllerCore::copyFromPost($object, string $table)

Copy data values from $_POST to object



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3528


#### Arguments
* $object **mixed**
* $table **string** - &lt;p&gt;Object table&lt;/p&gt;



### getSelectedAssoShop

    array AdminControllerCore::getSelectedAssoShop(string $table)

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3569


#### Arguments
* $table **string**



### updateAssoShop

    boolean|void AdminControllerCore::updateAssoShop(integer $id_object)

Update the associations of shops



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3599


#### Arguments
* $id_object **integer**



### validateField

    boolean AdminControllerCore::validateField(mixed $value, array $field)





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3635


#### Arguments
* $value **mixed**
* $field **array**



### beforeUpdateOptions

    mixed AdminControllerCore::beforeUpdateOptions()

Can be overridden



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3653




### postImage

    boolean AdminControllerCore::postImage(integer $id)

Overload this method for custom checking



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3663


#### Arguments
* $id **integer** - &lt;p&gt;Object id used for deleting images&lt;/p&gt;



### uploadImage

    boolean AdminControllerCore::uploadImage(integer $id, string $name, string $dir, string|boolean $ext, integer|null $width, integer|null $height)





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3686


#### Arguments
* $id **integer**
* $name **string**
* $dir **string**
* $ext **string|boolean**
* $width **integer|null**
* $height **integer|null**



### processBulkDelete

    boolean AdminControllerCore::processBulkDelete()

Delete multiple items



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3738




### ajaxProcessOpenHelp

    mixed AdminControllerCore::ajaxProcessOpenHelp()





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3791




### processBulkEnableSelection

    boolean AdminControllerCore::processBulkEnableSelection()

Enable multiple items



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3825




### processBulkDisableSelection

    boolean AdminControllerCore::processBulkDisableSelection()

Disable multiple items



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3835




### processBulkStatusSelection

    boolean AdminControllerCore::processBulkStatusSelection(boolean $status)

Toggle status of multiple items



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3847


#### Arguments
* $status **boolean**



### processBulkAffectZone

    boolean AdminControllerCore::processBulkAffectZone()





* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3864




### beforeAdd

    boolean AdminControllerCore::beforeAdd(\ObjectModel $object)

Called before Add



* Visibility: **protected**
* This method is defined in classes\controller\AdminController.php line 3889


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;



### displayRequiredFields

    string|void AdminControllerCore::displayRequiredFields()

Prepare the view to display the required fields form



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3899




### createTemplate

    \Smarty_Internal_Template AdminControllerCore::createTemplate(string $tpl_name)

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3918


#### Arguments
* $tpl_name **string** - &lt;p&gt;filename&lt;/p&gt;



### jsonConfirmation

    mixed AdminControllerCore::jsonConfirmation(string $message)

Shortcut to set up a json success payload



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3938


#### Arguments
* $message **string** - &lt;p&gt;Success message&lt;/p&gt;



### jsonError

    mixed AdminControllerCore::jsonError(string $message)

Shortcut to set up a json error payload



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3952


#### Arguments
* $message **string** - &lt;p&gt;Error message&lt;/p&gt;



### isFresh

    boolean AdminControllerCore::isFresh(string $file, integer $timeout)





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3966


#### Arguments
* $file **string**
* $timeout **integer**



### refresh

    boolean AdminControllerCore::refresh(string $file_to_refresh, string $external_file)





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3983


#### Arguments
* $file_to_refresh **string**
* $external_file **string**



### fillModuleData

    mixed AdminControllerCore::fillModuleData(\Module $module, string $output_type, string|null $back)





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 3997


#### Arguments
* $module **[Module](ModuleCore)**
* $output_type **string**
* $back **string|null**



### displayModuleOptions

    string|array AdminControllerCore::displayModuleOptions(\Module $module, string $output_type, string|null $back)

Display modules list



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 4048


#### Arguments
* $module **[Module](ModuleCore)**
* $output_type **string** - &lt;p&gt;(link or select)&lt;/p&gt;
* $back **string|null**



### ajaxProcessGetModuleQuickView

    mixed AdminControllerCore::ajaxProcessGetModuleQuickView()





* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 4316




### addMetaTitle

    mixed AdminControllerCore::addMetaTitle(string $entry)

Add an entry to the meta title.



* Visibility: **public**
* This method is defined in classes\controller\AdminController.php line 4357


#### Arguments
* $entry **string** - &lt;p&gt;New entry.&lt;/p&gt;


