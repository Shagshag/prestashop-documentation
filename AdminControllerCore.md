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
* Parent class: Controller





Properties
----------


### $path

    public string $path





* Visibility: **public**


### $currentIndex

    public string $currentIndex





* Visibility: **public**
* This property is **static**.


### $content

    public string $content





* Visibility: **public**


### $warnings

    public array $warnings = array()





* Visibility: **public**


### $informations

    public array $informations = array()





* Visibility: **public**


### $confirmations

    public array $confirmations = array()





* Visibility: **public**


### $shopShareDatas

    public string $shopShareDatas = false





* Visibility: **public**


### $_languages

    public array $_languages = array()





* Visibility: **public**


### $default_form_language

    public integer $default_form_language





* Visibility: **public**


### $allow_employee_form_lang

    public boolean $allow_employee_form_lang





* Visibility: **public**


### $layout

    public string $layout = 'layout.tpl'





* Visibility: **public**


### $bootstrap

    public boolean $bootstrap = false





* Visibility: **public**


### $meta_title

    protected string $meta_title = array()





* Visibility: **protected**


### $template

    public string $template = 'content.tpl'





* Visibility: **public**


### $table

    public string $table = 'configuration'





* Visibility: **public**


### $list_id

    public string $list_id





* Visibility: **public**


### $identifier

    protected string $identifier = false





* Visibility: **protected**


### $identifier_name

    protected string $identifier_name = 'name'





* Visibility: **protected**


### $className

    public string $className





* Visibility: **public**


### $tabAccess

    public array $tabAccess





* Visibility: **public**


### $id

    public integer $id = -1





* Visibility: **public**


### $required_database

    public boolean $required_database = false





* Visibility: **public**


### $token

    public string $token





* Visibility: **public**


### $shopLinkType

    public string $shopLinkType





* Visibility: **public**


### $_defaultOrderBy

    protected string $_defaultOrderBy = false





* Visibility: **protected**


### $_defaultOrderWay

    protected string $_defaultOrderWay = 'ASC'





* Visibility: **protected**


### $tpl_form_vars

    public array $tpl_form_vars = array()





* Visibility: **public**


### $tpl_list_vars

    public array $tpl_list_vars = array()





* Visibility: **public**


### $tpl_delete_link_vars

    public array $tpl_delete_link_vars = array()





* Visibility: **public**


### $tpl_option_vars

    public array $tpl_option_vars = array()





* Visibility: **public**


### $tpl_view_vars

    public array $tpl_view_vars = array()





* Visibility: **public**


### $tpl_required_fields_vars

    public array $tpl_required_fields_vars = array()





* Visibility: **public**


### $base_tpl_view

    public string $base_tpl_view = null





* Visibility: **public**


### $base_tpl_form

    public string $base_tpl_form = null





* Visibility: **public**


### $multiple_fieldsets

    public boolean $multiple_fieldsets = false





* Visibility: **public**


### $fields_value

    public array $fields_value = false





* Visibility: **public**


### $errors

    public array $errors = array()





* Visibility: **public**


### $list_simple_header

    protected boolean $list_simple_header





* Visibility: **protected**


### $fields_list

    protected array $fields_list





* Visibility: **protected**


### $filter_modules_list

    protected array $filter_modules_list = null





* Visibility: **protected**


### $modules_list

    protected array $modules_list = array()





* Visibility: **protected**


### $fields_form

    protected array $fields_form





* Visibility: **protected**


### $fields_form_override

    protected array $fields_form_override





* Visibility: **protected**


### $submit_action

    protected string $submit_action





* Visibility: **protected**


### $fields_options

    protected array $fields_options = array()





* Visibility: **protected**


### $shopLink

    protected string $shopLink





* Visibility: **protected**


### $_listsql

    protected string $_listsql = ''





* Visibility: **protected**


### $_list

    protected array $_list = array()





* Visibility: **protected**


### $toolbar_title

    protected string $toolbar_title





* Visibility: **protected**


### $toolbar_btn

    protected array $toolbar_btn = null





* Visibility: **protected**


### $toolbar_scroll

    protected boolean $toolbar_scroll = true





* Visibility: **protected**


### $show_toolbar

    protected boolean $show_toolbar = true





* Visibility: **protected**


### $show_toolbar_options

    protected boolean $show_toolbar_options = false





* Visibility: **protected**


### $_listTotal

    protected integer $_listTotal





* Visibility: **protected**


### $lang

    public boolean $lang = false





* Visibility: **public**


### $_filter

    protected array $_filter





* Visibility: **protected**


### $_filterHaving

    protected string $_filterHaving





* Visibility: **protected**


### $_tmpTableFilter

    protected array $_tmpTableFilter = ''





* Visibility: **protected**


### $_pagination

    protected array $_pagination = array(20, 50, 100, 300, 1000)





* Visibility: **protected**


### $_default_pagination

    protected integer $_default_pagination = 50





* Visibility: **protected**


### $_orderBy

    protected string $_orderBy





* Visibility: **protected**


### $_orderWay

    protected string $_orderWay





* Visibility: **protected**


### $actions_available

    protected array $actions_available = array('view', 'edit', 'duplicate', 'delete')





* Visibility: **protected**


### $actions

    protected array $actions = array()





* Visibility: **protected**


### $list_skip_actions

    protected array $list_skip_actions = array()





* Visibility: **protected**


### $lite_display

    protected mixed $lite_display = false





* Visibility: **protected**


### $list_no_link

    protected boolean $list_no_link = false





* Visibility: **protected**


### $allow_export

    protected boolean $allow_export = false





* Visibility: **protected**


### $cache_lang

    public array $cache_lang = array()





* Visibility: **public**
* This property is **static**.


### $required_fields

    public array $required_fields = array()





* Visibility: **public**


### $helper

    protected \HelperList $helper





* Visibility: **protected**


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


### $boxes

    protected mixed $boxes





* Visibility: **protected**


### $explicitSelect

    protected string $explicitSelect = false





* Visibility: **protected**


### $_select

    protected string $_select





* Visibility: **protected**


### $_join

    protected string $_join





* Visibility: **protected**


### $_where

    protected string $_where





* Visibility: **protected**


### $_group

    protected string $_group





* Visibility: **protected**


### $_having

    protected string $_having





* Visibility: **protected**


### $_use_found_rows

    protected string $_use_found_rows = true





* Visibility: **protected**


### $is_cms

    protected boolean $is_cms = false





* Visibility: **protected**


### $position_identifier

    protected string $position_identifier





* Visibility: **protected**


### $position_group_identifier

    protected string $position_group_identifier





* Visibility: **protected**


### $deleted

    protected boolean $deleted = false





* Visibility: **protected**


### $filter

    protected boolean $filter





* Visibility: **protected**


### $noLink

    protected boolean $noLink





* Visibility: **protected**


### $specificConfirmDelete

    protected boolean $specificConfirmDelete = null





* Visibility: **protected**


### $colorOnBackground

    protected boolean $colorOnBackground





* Visibility: **protected**


### $row_hover

    protected boolean $row_hover = true





* Visibility: **protected**


### $action

    protected string $action





* Visibility: **protected**


### $display

    protected string $display





* Visibility: **protected**


### $_includeContainer

    protected boolean $_includeContainer = true





* Visibility: **protected**


### $tab_modules_list

    protected array $tab_modules_list = array('default_list' => array(), 'slider_list' => array())





* Visibility: **protected**


### $tpl_folder

    public string $tpl_folder





* Visibility: **public**


### $bo_theme

    protected string $bo_theme





* Visibility: **protected**


### $_redirect

    protected boolean $_redirect = true





* Visibility: **protected**


### $fieldImageSettings

    public array $fieldImageSettings = array()





* Visibility: **public**


### $imageType

    public string $imageType = 'jpg'





* Visibility: **public**


### $object

    protected \ObjectModel $object





* Visibility: **protected**


### $id_object

    protected integer $id_object





* Visibility: **protected**


### $controller_name

    public string $controller_name





* Visibility: **public**


### $multishop_context

    public integer $multishop_context = -1





* Visibility: **public**


### $multishop_context_group

    public false $multishop_context_group = true





* Visibility: **public**


### $breadcrumbs

    protected array $breadcrumbs





* Visibility: **protected**


### $show_page_header_toolbar

    public boolean $show_page_header_toolbar = false





* Visibility: **public**


### $page_header_toolbar_title

    public string $page_header_toolbar_title





* Visibility: **public**


### $page_header_toolbar_btn

    public array $page_header_toolbar_btn = array()





* Visibility: **public**


### $show_form_cancel_button

    public boolean $show_form_cancel_button





* Visibility: **public**


### $admin_webpath

    public string $admin_webpath





* Visibility: **public**


### $list_natives_modules

    protected array $list_natives_modules = array()





* Visibility: **protected**


### $list_partners_modules

    protected array $list_partners_modules = array()





* Visibility: **protected**


### $modals

    public array $modals = array()





* Visibility: **public**


### $logged_on_addons

    protected boolean $logged_on_addons = false





* Visibility: **protected**


### $can_import

    protected boolean $can_import = false





* Visibility: **protected**


### $is_prestashop_up

    protected boolean $is_prestashop_up = true





* Visibility: **protected**
* This property is **static**.


### $translationsTab

    protected array $translationsTab = array()





* Visibility: **protected**


Methods
-------


### __construct

    mixed AdminControllerCore::__construct()





* Visibility: **public**




### initBreadcrumbs

    mixed AdminControllerCore::initBreadcrumbs(integer|null $tab_id, array|null $tabs)

Set breadcrumbs array for the controller page



* Visibility: **public**


#### Arguments
* $tab_id **integer|null**
* $tabs **array|null**



### initToolbarTitle

    void AdminControllerCore::initToolbarTitle()

Set default toolbar_title to admin breadcrumb



* Visibility: **public**




### addFiltersToBreadcrumbs

    string|void AdminControllerCore::addFiltersToBreadcrumbs()





* Visibility: **public**




### viewAccess

    boolean AdminControllerCore::viewAccess(boolean $disable)

Check rights to view the current tab



* Visibility: **public**


#### Arguments
* $disable **boolean**



### checkToken

    boolean AdminControllerCore::checkToken()

Check for security token



* Visibility: **public**




### processFilter

    mixed AdminControllerCore::processFilter()

Set the filters used for the list display



* Visibility: **public**




### postProcess

    boolean AdminControllerCore::postProcess()





* Visibility: **public**




### processDeleteImage

    \ObjectModel|false AdminControllerCore::processDeleteImage()

Object Delete images



* Visibility: **public**




### processExport

    mixed AdminControllerCore::processExport(string $text_delimiter)





* Visibility: **public**


#### Arguments
* $text_delimiter **string**



### processDelete

    \ObjectModel|false AdminControllerCore::processDelete()

Object Delete



* Visibility: **public**




### processSave

    \ObjectModel|false|void AdminControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**




### processAdd

    \ObjectModel|false AdminControllerCore::processAdd()

Object creation



* Visibility: **public**




### processUpdate

    \ObjectModel|false|void AdminControllerCore::processUpdate()

Object update



* Visibility: **public**




### processUpdateFields

    \ObjectModel AdminControllerCore::processUpdateFields()

Change object required fields



* Visibility: **public**




### processStatus

    \ObjectModel|false AdminControllerCore::processStatus()

Change object status (active, inactive)



* Visibility: **public**




### processPosition

    \ObjectModel|false AdminControllerCore::processPosition()

Change object position



* Visibility: **public**




### processResetFilters

    mixed AdminControllerCore::processResetFilters(integer|null $list_id)

Cancel all filters for this tab



* Visibility: **public**


#### Arguments
* $list_id **integer|null**



### processUpdateOptions

    mixed AdminControllerCore::processUpdateOptions()

Update options and preferences



* Visibility: **protected**




### initPageHeaderToolbar

    mixed AdminControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initToolbar

    mixed AdminControllerCore::initToolbar()

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**




### loadObject

    \ObjectModel|false AdminControllerCore::loadObject(boolean $opt)

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**


#### Arguments
* $opt **boolean** - &lt;p&gt;Return an empty object if load fail&lt;/p&gt;



### checkAccess

    boolean AdminControllerCore::checkAccess()

Check if the token is valid, else display a warning page



* Visibility: **public**




### filterToField

    array|false AdminControllerCore::filterToField(string $key, string $filter)





* Visibility: **protected**


#### Arguments
* $key **string**
* $filter **string**



### displayNoSmarty

    mixed AdminControllerCore::displayNoSmarty()





* Visibility: **public**




### displayAjax

    void AdminControllerCore::displayAjax()





* Visibility: **public**




### redirect

    mixed AdminControllerCore::redirect()





* Visibility: **protected**




### display

    void AdminControllerCore::display()





* Visibility: **public**




### displayWarning

    mixed AdminControllerCore::displayWarning(string $msg)

Add a warning message to display at the top of the page



* Visibility: **protected**


#### Arguments
* $msg **string**



### displayInformation

    mixed AdminControllerCore::displayInformation(string $msg)

Add a info message to display at the top of the page



* Visibility: **protected**


#### Arguments
* $msg **string**



### initHeader

    mixed AdminControllerCore::initHeader()

Assign smarty variables for the header



* Visibility: **public**




### addRowAction

    mixed AdminControllerCore::addRowAction(string $action)

Declare an action to use for each row in the list



* Visibility: **public**


#### Arguments
* $action **string**



### addRowActionSkipList

    mixed AdminControllerCore::addRowActionSkipList(string $action, array $list)

Add an action to use for each row in the list



* Visibility: **public**


#### Arguments
* $action **string**
* $list **array**



### initContent

    mixed AdminControllerCore::initContent()

Assign smarty variables for all default views, list and form, then call other init functions



* Visibility: **public**




### initTabModuleList

    mixed AdminControllerCore::initTabModuleList()

Init tab modules list and add button in toolbar



* Visibility: **protected**




### addPageHeaderToolBarModulesListButton

    mixed AdminControllerCore::addPageHeaderToolBarModulesListButton()





* Visibility: **protected**




### addToolBarModulesListButton

    mixed AdminControllerCore::addToolBarModulesListButton()





* Visibility: **protected**




### filterTabModuleList

    mixed AdminControllerCore::filterTabModuleList()





* Visibility: **protected**




### initCursedPage

    void AdminControllerCore::initCursedPage()

Initialize the invalid doom page of death



* Visibility: **public**




### initFooter

    mixed AdminControllerCore::initFooter()

Assign smarty variables for the footer



* Visibility: **public**




### initModal

    mixed AdminControllerCore::initModal()





* Visibility: **public**




### renderModal

    string AdminControllerCore::renderModal()





* Visibility: **public**




### renderModulesList

    string AdminControllerCore::renderModulesList()





* Visibility: **public**




### renderList

    string|false AdminControllerCore::renderList()

Function used to render the list to display for this controller



* Visibility: **public**




### getTemplateListVars

    mixed AdminControllerCore::getTemplateListVars()





* Visibility: **public**




### renderView

    string AdminControllerCore::renderView()

Override to render the view page



* Visibility: **public**




### getTemplateViewVars

    mixed AdminControllerCore::getTemplateViewVars()





* Visibility: **public**




### renderDetails

    string|false AdminControllerCore::renderDetails()

Override to render the view page



* Visibility: **public**




### renderForm

    string AdminControllerCore::renderForm()

Function used to render the form for this controller



* Visibility: **public**




### getTemplateFormVars

    mixed AdminControllerCore::getTemplateFormVars()





* Visibility: **public**




### renderKpis

    mixed AdminControllerCore::renderKpis()





* Visibility: **public**




### renderOptions

    string AdminControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**




### setHelperDisplay

    void AdminControllerCore::setHelperDisplay(\Helper $helper)

This function sets various display options for helper list



* Visibility: **public**


#### Arguments
* $helper **Helper**



### setDeprecatedMedia

    mixed AdminControllerCore::setDeprecatedMedia()





* Visibility: **public**




### setMedia

    mixed AdminControllerCore::setMedia()





* Visibility: **public**




### l

    string AdminControllerCore::l(string $string, string|null $class, boolean $addslashes, boolean $htmlentities)

Non-static method which uses AdminController::translate()



* Visibility: **protected**


#### Arguments
* $string **string** - &lt;p&gt;Term or expression in english&lt;/p&gt;
* $class **string|null** - &lt;p&gt;Name of the class&lt;/p&gt;
* $addslashes **boolean** - &lt;p&gt;If set to true, the return value will pass through addslashes(). Otherwise, stripslashes().&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;If set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)&lt;/p&gt;



### init

    mixed AdminControllerCore::init()

Init context and dependencies, handles POST and GET



* Visibility: **public**




### initShopContext

    mixed AdminControllerCore::initShopContext()





* Visibility: **public**




### initProcess

    mixed AdminControllerCore::initProcess()

Retrieve GET and POST value and translate them to actions



* Visibility: **public**




### getList

    mixed AdminControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

Get the current objects' list form the database



* Visibility: **public**


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


#### Arguments
* $filter_modules_list **array|string**



### getLanguages

    array AdminControllerCore::getLanguages()





* Visibility: **public**




### getFieldsValue

    array AdminControllerCore::getFieldsValue(\ObjectModel $obj)

Return the list of fields value



* Visibility: **public**


#### Arguments
* $obj **ObjectModel** - &lt;p&gt;Object&lt;/p&gt;



### getFieldValue

    string AdminControllerCore::getFieldValue(\ObjectModel $obj, string $key, integer|null $id_lang)

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**


#### Arguments
* $obj **ObjectModel** - &lt;p&gt;Object&lt;/p&gt;
* $key **string** - &lt;p&gt;Field name&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Language id (optional)&lt;/p&gt;



### validateRules

    mixed AdminControllerCore::validateRules(string|boolean $class_name)

Manage page display (form, list.

..)

* Visibility: **public**


#### Arguments
* $class_name **string|boolean** - &lt;p&gt;Allow to validate a different class than the current one&lt;/p&gt;



### _childValidation

    mixed AdminControllerCore::_childValidation()

Overload this method for custom checking



* Visibility: **protected**




### viewDetails

    mixed AdminControllerCore::viewDetails()

Display object details



* Visibility: **public**




### beforeDelete

    boolean AdminControllerCore::beforeDelete(\ObjectModel $object)

Called before deletion



* Visibility: **protected**


#### Arguments
* $object **ObjectModel** - &lt;p&gt;Object&lt;/p&gt;



### afterDelete

    boolean AdminControllerCore::afterDelete(\ObjectModel $object, integer $old_id)

Called before deletion



* Visibility: **protected**


#### Arguments
* $object **ObjectModel** - &lt;p&gt;Object&lt;/p&gt;
* $old_id **integer**



### afterAdd

    boolean AdminControllerCore::afterAdd(\ObjectModel $object)





* Visibility: **protected**


#### Arguments
* $object **ObjectModel**



### afterUpdate

    boolean AdminControllerCore::afterUpdate(\ObjectModel $object)





* Visibility: **protected**


#### Arguments
* $object **ObjectModel**



### afterImageUpload

    boolean AdminControllerCore::afterImageUpload()

Check rights to view the current tab



* Visibility: **protected**




### copyFromPost

    mixed AdminControllerCore::copyFromPost($object, string $table)

Copy data values from $_POST to object



* Visibility: **protected**


#### Arguments
* $object **mixed**
* $table **string** - &lt;p&gt;Object table&lt;/p&gt;



### getSelectedAssoShop

    array AdminControllerCore::getSelectedAssoShop(string $table)

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**


#### Arguments
* $table **string**



### updateAssoShop

    boolean|void AdminControllerCore::updateAssoShop(integer $id_object)

Update the associations of shops



* Visibility: **protected**


#### Arguments
* $id_object **integer**



### validateField

    boolean AdminControllerCore::validateField(mixed $value, array $field)





* Visibility: **protected**


#### Arguments
* $value **mixed**
* $field **array**



### beforeUpdateOptions

    mixed AdminControllerCore::beforeUpdateOptions()

Can be overridden



* Visibility: **public**




### postImage

    boolean AdminControllerCore::postImage(integer $id)

Overload this method for custom checking



* Visibility: **protected**


#### Arguments
* $id **integer** - &lt;p&gt;Object id used for deleting images&lt;/p&gt;



### uploadImage

    boolean AdminControllerCore::uploadImage(integer $id, string $name, string $dir, string|boolean $ext, integer|null $width, integer|null $height)





* Visibility: **protected**


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




### ajaxProcessOpenHelp

    mixed AdminControllerCore::ajaxProcessOpenHelp()





* Visibility: **protected**




### processBulkEnableSelection

    boolean AdminControllerCore::processBulkEnableSelection()

Enable multiple items



* Visibility: **protected**




### processBulkDisableSelection

    boolean AdminControllerCore::processBulkDisableSelection()

Disable multiple items



* Visibility: **protected**




### processBulkStatusSelection

    boolean AdminControllerCore::processBulkStatusSelection(boolean $status)

Toggle status of multiple items



* Visibility: **protected**


#### Arguments
* $status **boolean**



### processBulkAffectZone

    boolean AdminControllerCore::processBulkAffectZone()





* Visibility: **protected**




### beforeAdd

    boolean AdminControllerCore::beforeAdd(\ObjectModel $object)

Called before Add



* Visibility: **protected**


#### Arguments
* $object **ObjectModel** - &lt;p&gt;Object&lt;/p&gt;



### displayRequiredFields

    string|void AdminControllerCore::displayRequiredFields()

Prepare the view to display the required fields form



* Visibility: **public**




### createTemplate

    \Smarty_Internal_Template AdminControllerCore::createTemplate(string $tpl_name)

Create a template from the override file, else from the base file.



* Visibility: **public**


#### Arguments
* $tpl_name **string** - &lt;p&gt;filename&lt;/p&gt;



### jsonConfirmation

    mixed AdminControllerCore::jsonConfirmation(string $message)

Shortcut to set up a json success payload



* Visibility: **public**


#### Arguments
* $message **string** - &lt;p&gt;Success message&lt;/p&gt;



### jsonError

    mixed AdminControllerCore::jsonError(string $message)

Shortcut to set up a json error payload



* Visibility: **public**


#### Arguments
* $message **string** - &lt;p&gt;Error message&lt;/p&gt;



### isFresh

    boolean AdminControllerCore::isFresh(string $file, integer $timeout)





* Visibility: **public**


#### Arguments
* $file **string**
* $timeout **integer**



### refresh

    boolean AdminControllerCore::refresh(string $file_to_refresh, string $external_file)





* Visibility: **public**


#### Arguments
* $file_to_refresh **string**
* $external_file **string**



### fillModuleData

    mixed AdminControllerCore::fillModuleData(\Module $module, string $output_type, string|null $back)





* Visibility: **public**


#### Arguments
* $module **Module**
* $output_type **string**
* $back **string|null**



### displayModuleOptions

    string|array AdminControllerCore::displayModuleOptions(\Module $module, string $output_type, string|null $back)

Display modules list



* Visibility: **public**


#### Arguments
* $module **Module**
* $output_type **string** - &lt;p&gt;(link or select)&lt;/p&gt;
* $back **string|null**



### ajaxProcessGetModuleQuickView

    mixed AdminControllerCore::ajaxProcessGetModuleQuickView()





* Visibility: **public**




### addMetaTitle

    mixed AdminControllerCore::addMetaTitle(string $entry)

Add an entry to the meta title.



* Visibility: **public**


#### Arguments
* $entry **string** - &lt;p&gt;New entry.&lt;/p&gt;


