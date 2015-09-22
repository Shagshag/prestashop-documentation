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
* Parent class: [Controller](ControllerCore)
* This class is defined in [classes/controller/AdminController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L27)





Properties
----------

* [$path](#property-$path)
* [$currentIndex](#property-$currentIndex)
* [$content](#property-$content)
* [$warnings](#property-$warnings)
* [$informations](#property-$informations)
* [$confirmations](#property-$confirmations)
* [$shopShareDatas](#property-$shopShareDatas)
* [$_languages](#property-$_languages)
* [$default_form_language](#property-$default_form_language)
* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$layout](#property-$layout)
* [$bootstrap](#property-$bootstrap)
* [$meta_title](#property-$meta_title)
* [$template](#property-$template)
* [$table](#property-$table)
* [$list_id](#property-$list_id)
* [$identifier](#property-$identifier)
* [$identifier_name](#property-$identifier_name)
* [$className](#property-$className)
* [$tabAccess](#property-$tabAccess)
* [$id](#property-$id)
* [$required_database](#property-$required_database)
* [$token](#property-$token)
* [$shopLinkType](#property-$shopLinkType)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$tpl_form_vars](#property-$tpl_form_vars)
* [$tpl_list_vars](#property-$tpl_list_vars)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$tpl_option_vars](#property-$tpl_option_vars)
* [$tpl_view_vars](#property-$tpl_view_vars)
* [$tpl_required_fields_vars](#property-$tpl_required_fields_vars)
* [$base_tpl_view](#property-$base_tpl_view)
* [$base_tpl_form](#property-$base_tpl_form)
* [$multiple_fieldsets](#property-$multiple_fieldsets)
* [$fields_value](#property-$fields_value)
* [$errors](#property-$errors)
* [$list_simple_header](#property-$list_simple_header)
* [$fields_list](#property-$fields_list)
* [$filter_modules_list](#property-$filter_modules_list)
* [$modules_list](#property-$modules_list)
* [$fields_form](#property-$fields_form)
* [$fields_form_override](#property-$fields_form_override)
* [$submit_action](#property-$submit_action)
* [$fields_options](#property-$fields_options)
* [$shopLink](#property-$shopLink)
* [$_listsql](#property-$_listsql)
* [$_list](#property-$_list)
* [$toolbar_title](#property-$toolbar_title)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$show_toolbar](#property-$show_toolbar)
* [$show_toolbar_options](#property-$show_toolbar_options)
* [$_listTotal](#property-$_listTotal)
* [$lang](#property-$lang)
* [$_filter](#property-$_filter)
* [$_filterHaving](#property-$_filterHaving)
* [$_tmpTableFilter](#property-$_tmpTableFilter)
* [$_pagination](#property-$_pagination)
* [$_default_pagination](#property-$_default_pagination)
* [$_orderBy](#property-$_orderBy)
* [$_orderWay](#property-$_orderWay)
* [$actions_available](#property-$actions_available)
* [$actions](#property-$actions)
* [$list_skip_actions](#property-$list_skip_actions)
* [$lite_display](#property-$lite_display)
* [$list_no_link](#property-$list_no_link)
* [$allow_export](#property-$allow_export)
* [$cache_lang](#property-$cache_lang)
* [$required_fields](#property-$required_fields)
* [$helper](#property-$helper)
* [$bulk_actions](#property-$bulk_actions)
* [$boxes](#property-$boxes)
* [$explicitSelect](#property-$explicitSelect)
* [$_select](#property-$_select)
* [$_join](#property-$_join)
* [$_where](#property-$_where)
* [$_group](#property-$_group)
* [$_having](#property-$_having)
* [$_use_found_rows](#property-$_use_found_rows)
* [$is_cms](#property-$is_cms)
* [$position_identifier](#property-$position_identifier)
* [$position_group_identifier](#property-$position_group_identifier)
* [$deleted](#property-$deleted)
* [$filter](#property-$filter)
* [$noLink](#property-$noLink)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$colorOnBackground](#property-$colorOnBackground)
* [$row_hover](#property-$row_hover)
* [$action](#property-$action)
* [$display](#property-$display)
* [$_includeContainer](#property-$_includeContainer)
* [$tab_modules_list](#property-$tab_modules_list)
* [$tpl_folder](#property-$tpl_folder)
* [$bo_theme](#property-$bo_theme)
* [$_redirect](#property-$_redirect)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$imageType](#property-$imageType)
* [$object](#property-$object)
* [$id_object](#property-$id_object)
* [$controller_name](#property-$controller_name)
* [$multishop_context](#property-$multishop_context)
* [$multishop_context_group](#property-$multishop_context_group)
* [$breadcrumbs](#property-$breadcrumbs)
* [$show_page_header_toolbar](#property-$show_page_header_toolbar)
* [$page_header_toolbar_title](#property-$page_header_toolbar_title)
* [$page_header_toolbar_btn](#property-$page_header_toolbar_btn)
* [$show_form_cancel_button](#property-$show_form_cancel_button)
* [$admin_webpath](#property-$admin_webpath)
* [$list_natives_modules](#property-$list_natives_modules)
* [$list_partners_modules](#property-$list_partners_modules)
* [$modals](#property-$modals)
* [$logged_on_addons](#property-$logged_on_addons)
* [$can_import](#property-$can_import)
* [$is_prestashop_up](#property-$is_prestashop_up)
* [$translationsTab](#property-$translationsTab)

Methods
-------
* [__construct](#method-__construct)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initToolbarTitle](#method-initToolbarTitle)
* [addFiltersToBreadcrumbs](#method-addFiltersToBreadcrumbs)
* [viewAccess](#method-viewAccess)
* [checkToken](#method-checkToken)
* [processFilter](#method-processFilter)
* [postProcess](#method-postProcess)
* [processDeleteImage](#method-processDeleteImage)
* [processExport](#method-processExport)
* [processDelete](#method-processDelete)
* [processSave](#method-processSave)
* [processAdd](#method-processAdd)
* [processUpdate](#method-processUpdate)
* [processUpdateFields](#method-processUpdateFields)
* [processStatus](#method-processStatus)
* [processPosition](#method-processPosition)
* [processResetFilters](#method-processResetFilters)
* [processUpdateOptions](#method-processUpdateOptions)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [loadObject](#method-loadObject)
* [checkAccess](#method-checkAccess)
* [filterToField](#method-filterToField)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayAjax](#method-displayAjax)
* [redirect](#method-redirect)
* [display](#method-display)
* [displayWarning](#method-displayWarning)
* [displayInformation](#method-displayInformation)
* [initHeader](#method-initHeader)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [initContent](#method-initContent)
* [initTabModuleList](#method-initTabModuleList)
* [addPageHeaderToolBarModulesListButton](#method-addPageHeaderToolBarModulesListButton)
* [addToolBarModulesListButton](#method-addToolBarModulesListButton)
* [filterTabModuleList](#method-filterTabModuleList)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initModal](#method-initModal)
* [renderModal](#method-renderModal)
* [renderModulesList](#method-renderModulesList)
* [renderList](#method-renderList)
* [getTemplateListVars](#method-getTemplateListVars)
* [renderView](#method-renderView)
* [getTemplateViewVars](#method-getTemplateViewVars)
* [renderDetails](#method-renderDetails)
* [renderForm](#method-renderForm)
* [getTemplateFormVars](#method-getTemplateFormVars)
* [renderKpis](#method-renderKpis)
* [renderOptions](#method-renderOptions)
* [setHelperDisplay](#method-setHelperDisplay)
* [setDeprecatedMedia](#method-setDeprecatedMedia)
* [setMedia](#method-setMedia)
* [l](#method-l)
* [init](#method-init)
* [initShopContext](#method-initShopContext)
* [initProcess](#method-initProcess)
* [getList](#method-getList)
* [getModulesList](#method-getModulesList)
* [getLanguages](#method-getLanguages)
* [getFieldsValue](#method-getFieldsValue)
* [getFieldValue](#method-getFieldValue)
* [validateRules](#method-validateRules)
* [_childValidation](#method-_childValidation)
* [viewDetails](#method-viewDetails)
* [beforeDelete](#method-beforeDelete)
* [afterDelete](#method-afterDelete)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [afterImageUpload](#method-afterImageUpload)
* [copyFromPost](#method-copyFromPost)
* [getSelectedAssoShop](#method-getSelectedAssoShop)
* [updateAssoShop](#method-updateAssoShop)
* [validateField](#method-validateField)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [postImage](#method-postImage)
* [uploadImage](#method-uploadImage)
* [processBulkDelete](#method-processBulkDelete)
* [ajaxProcessOpenHelp](#method-ajaxProcessOpenHelp)
* [processBulkEnableSelection](#method-processBulkEnableSelection)
* [processBulkDisableSelection](#method-processBulkDisableSelection)
* [processBulkStatusSelection](#method-processBulkStatusSelection)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [beforeAdd](#method-beforeAdd)
* [displayRequiredFields](#method-displayRequiredFields)
* [createTemplate](#method-createTemplate)
* [jsonConfirmation](#method-jsonConfirmation)
* [jsonError](#method-jsonError)
* [isFresh](#method-isFresh)
* [refresh](#method-refresh)
* [fillModuleData](#method-fillModuleData)
* [displayModuleOptions](#method-displayModuleOptions)
* [ajaxProcessGetModuleQuickView](#method-ajaxProcessGetModuleQuickView)
* [addMetaTitle](#method-addMetaTitle)




Properties
----------


### <a name="property-$path"></a>$path

    public string $path





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L30)


### <a name="property-$currentIndex"></a>$currentIndex

    public string $currentIndex





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L33)


### <a name="property-$content"></a>$content

    public string $content





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L36)


### <a name="property-$warnings"></a>$warnings

    public array $warnings = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L39)


### <a name="property-$informations"></a>$informations

    public array $informations = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L42)


### <a name="property-$confirmations"></a>$confirmations

    public array $confirmations = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L45)


### <a name="property-$shopShareDatas"></a>$shopShareDatas

    public string $shopShareDatas = false





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L48)


### <a name="property-$_languages"></a>$_languages

    public array $_languages = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L51)


### <a name="property-$default_form_language"></a>$default_form_language

    public integer $default_form_language





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L54)


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

    public boolean $allow_employee_form_lang





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L57)


### <a name="property-$layout"></a>$layout

    public string $layout = 'layout.tpl'





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L60)


### <a name="property-$bootstrap"></a>$bootstrap

    public boolean $bootstrap = false





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L63)


### <a name="property-$meta_title"></a>$meta_title

    protected string $meta_title = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L66)


### <a name="property-$template"></a>$template

    public string $template = 'content.tpl'





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L69)


### <a name="property-$table"></a>$table

    public string $table = 'configuration'





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L72)


### <a name="property-$list_id"></a>$list_id

    public string $list_id





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L75)


### <a name="property-$identifier"></a>$identifier

    protected string $identifier = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L78)


### <a name="property-$identifier_name"></a>$identifier_name

    protected string $identifier_name = 'name'





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L81)


### <a name="property-$className"></a>$className

    public string $className





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L84)


### <a name="property-$tabAccess"></a>$tabAccess

    public array $tabAccess





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L87)


### <a name="property-$id"></a>$id

    public integer $id = -1





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L90)


### <a name="property-$required_database"></a>$required_database

    public boolean $required_database = false





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L93)


### <a name="property-$token"></a>$token

    public string $token





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L96)


### <a name="property-$shopLinkType"></a>$shopLinkType

    public string $shopLinkType





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L99)


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

    protected string $_defaultOrderBy = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L102)


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

    protected string $_defaultOrderWay = 'ASC'





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L105)


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

    public array $tpl_form_vars = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L108)


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

    public array $tpl_list_vars = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L111)


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

    public array $tpl_delete_link_vars = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L114)


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

    public array $tpl_option_vars = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L117)


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

    public array $tpl_view_vars = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L120)


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

    public array $tpl_required_fields_vars = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L123)


### <a name="property-$base_tpl_view"></a>$base_tpl_view

    public string $base_tpl_view = null





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L126)


### <a name="property-$base_tpl_form"></a>$base_tpl_form

    public string $base_tpl_form = null





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L129)


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

    public boolean $multiple_fieldsets = false





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L132)


### <a name="property-$fields_value"></a>$fields_value

    public array $fields_value = false





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L135)


### <a name="property-$errors"></a>$errors

    public array $errors = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L138)


### <a name="property-$list_simple_header"></a>$list_simple_header

    protected boolean $list_simple_header





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L141)


### <a name="property-$fields_list"></a>$fields_list

    protected array $fields_list





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L144)


### <a name="property-$filter_modules_list"></a>$filter_modules_list

    protected array $filter_modules_list = null





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L147)


### <a name="property-$modules_list"></a>$modules_list

    protected array $modules_list = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L150)


### <a name="property-$fields_form"></a>$fields_form

    protected array $fields_form





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L153)


### <a name="property-$fields_form_override"></a>$fields_form_override

    protected array $fields_form_override





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L156)


### <a name="property-$submit_action"></a>$submit_action

    protected string $submit_action





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L159)


### <a name="property-$fields_options"></a>$fields_options

    protected array $fields_options = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L162)


### <a name="property-$shopLink"></a>$shopLink

    protected string $shopLink





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L165)


### <a name="property-$_listsql"></a>$_listsql

    protected string $_listsql = ''





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L168)


### <a name="property-$_list"></a>$_list

    protected array $_list = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L171)


### <a name="property-$toolbar_title"></a>$toolbar_title

    protected string $toolbar_title





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L174)


### <a name="property-$toolbar_btn"></a>$toolbar_btn

    protected array $toolbar_btn = null





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L177)


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

    protected boolean $toolbar_scroll = true





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L180)


### <a name="property-$show_toolbar"></a>$show_toolbar

    protected boolean $show_toolbar = true





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L183)


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

    protected boolean $show_toolbar_options = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L186)


### <a name="property-$_listTotal"></a>$_listTotal

    protected integer $_listTotal





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L189)


### <a name="property-$lang"></a>$lang

    public boolean $lang = false





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L192)


### <a name="property-$_filter"></a>$_filter

    protected array $_filter





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L195)


### <a name="property-$_filterHaving"></a>$_filterHaving

    protected string $_filterHaving





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L198)


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

    protected array $_tmpTableFilter = ''





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L201)


### <a name="property-$_pagination"></a>$_pagination

    protected array $_pagination = array(20, 50, 100, 300, 1000)





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L204)


### <a name="property-$_default_pagination"></a>$_default_pagination

    protected integer $_default_pagination = 50





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L207)


### <a name="property-$_orderBy"></a>$_orderBy

    protected string $_orderBy





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L210)


### <a name="property-$_orderWay"></a>$_orderWay

    protected string $_orderWay





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L213)


### <a name="property-$actions_available"></a>$actions_available

    protected array $actions_available = array('view', 'edit', 'duplicate', 'delete')





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L216)


### <a name="property-$actions"></a>$actions

    protected array $actions = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L219)


### <a name="property-$list_skip_actions"></a>$list_skip_actions

    protected array $list_skip_actions = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L222)


### <a name="property-$lite_display"></a>$lite_display

    protected mixed $lite_display = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L225)


### <a name="property-$list_no_link"></a>$list_no_link

    protected boolean $list_no_link = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L228)


### <a name="property-$allow_export"></a>$allow_export

    protected boolean $allow_export = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L231)


### <a name="property-$cache_lang"></a>$cache_lang

    public array $cache_lang = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/controller/AdminController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L234)


### <a name="property-$required_fields"></a>$required_fields

    public array $required_fields = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L237)


### <a name="property-$helper"></a>$helper

    protected \HelperList $helper





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L240)


### <a name="property-$bulk_actions"></a>$bulk_actions

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
* This property is defined in [classes/controller/AdminController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L258)


### <a name="property-$boxes"></a>$boxes

    protected mixed $boxes





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L261)


### <a name="property-$explicitSelect"></a>$explicitSelect

    protected string $explicitSelect = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L264)


### <a name="property-$_select"></a>$_select

    protected string $_select





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L267)


### <a name="property-$_join"></a>$_join

    protected string $_join





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L270)


### <a name="property-$_where"></a>$_where

    protected string $_where





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L273)


### <a name="property-$_group"></a>$_group

    protected string $_group





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L276)


### <a name="property-$_having"></a>$_having

    protected string $_having





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L279)


### <a name="property-$_use_found_rows"></a>$_use_found_rows

    protected string $_use_found_rows = true





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L282)


### <a name="property-$is_cms"></a>$is_cms

    protected boolean $is_cms = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L285)


### <a name="property-$position_identifier"></a>$position_identifier

    protected string $position_identifier





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L288)


### <a name="property-$position_group_identifier"></a>$position_group_identifier

    protected string $position_group_identifier





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L291)


### <a name="property-$deleted"></a>$deleted

    protected boolean $deleted = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L294)


### <a name="property-$filter"></a>$filter

    protected boolean $filter





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L297)


### <a name="property-$noLink"></a>$noLink

    protected boolean $noLink





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L300)


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

    protected boolean $specificConfirmDelete = null





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L303)


### <a name="property-$colorOnBackground"></a>$colorOnBackground

    protected boolean $colorOnBackground





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L306)


### <a name="property-$row_hover"></a>$row_hover

    protected boolean $row_hover = true





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L309)


### <a name="property-$action"></a>$action

    protected string $action





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L312)


### <a name="property-$display"></a>$display

    protected string $display





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L315)


### <a name="property-$_includeContainer"></a>$_includeContainer

    protected boolean $_includeContainer = true





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L318)


### <a name="property-$tab_modules_list"></a>$tab_modules_list

    protected array $tab_modules_list = array('default_list' => array(), 'slider_list' => array())





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L321)


### <a name="property-$tpl_folder"></a>$tpl_folder

    public string $tpl_folder





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L324)


### <a name="property-$bo_theme"></a>$bo_theme

    protected string $bo_theme





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L327)


### <a name="property-$_redirect"></a>$_redirect

    protected boolean $_redirect = true





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L330)


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

    public array $fieldImageSettings = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L333)


### <a name="property-$imageType"></a>$imageType

    public string $imageType = 'jpg'





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L336)


### <a name="property-$object"></a>$object

    protected \ObjectModel $object





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L339)


### <a name="property-$id_object"></a>$id_object

    protected integer $id_object





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L342)


### <a name="property-$controller_name"></a>$controller_name

    public string $controller_name





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L345)


### <a name="property-$multishop_context"></a>$multishop_context

    public integer $multishop_context = -1





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L348)


### <a name="property-$multishop_context_group"></a>$multishop_context_group

    public false $multishop_context_group = true





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L351)


### <a name="property-$breadcrumbs"></a>$breadcrumbs

    protected array $breadcrumbs





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L354)


### <a name="property-$show_page_header_toolbar"></a>$show_page_header_toolbar

    public boolean $show_page_header_toolbar = false





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L357)


### <a name="property-$page_header_toolbar_title"></a>$page_header_toolbar_title

    public string $page_header_toolbar_title





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L360)


### <a name="property-$page_header_toolbar_btn"></a>$page_header_toolbar_btn

    public array $page_header_toolbar_btn = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L363)


### <a name="property-$show_form_cancel_button"></a>$show_form_cancel_button

    public boolean $show_form_cancel_button





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L366)


### <a name="property-$admin_webpath"></a>$admin_webpath

    public string $admin_webpath





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L369)


### <a name="property-$list_natives_modules"></a>$list_natives_modules

    protected array $list_natives_modules = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L372)


### <a name="property-$list_partners_modules"></a>$list_partners_modules

    protected array $list_partners_modules = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L375)


### <a name="property-$modals"></a>$modals

    public array $modals = array()





* Visibility: **public**
* This property is defined in [classes/controller/AdminController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L378)


### <a name="property-$logged_on_addons"></a>$logged_on_addons

    protected boolean $logged_on_addons = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L381)


### <a name="property-$can_import"></a>$can_import

    protected boolean $can_import = false





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L384)


### <a name="property-$is_prestashop_up"></a>$is_prestashop_up

    protected boolean $is_prestashop_up = true





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/controller/AdminController.php line 3976](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3976)


### <a name="property-$translationsTab"></a>$translationsTab

    protected array $translationsTab = array()





* Visibility: **protected**
* This property is defined in [classes/controller/AdminController.php line 4038](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4038)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminControllerCore::__construct()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L386)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

    mixed AdminControllerCore::initBreadcrumbs(integer|null $tab_id, array|null $tabs)

Set breadcrumbs array for the controller page



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 537](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L537)


#### Arguments
* $tab_id **integer|null**
* $tabs **array|null**



### <a name="method-initToolbarTitle"></a>initToolbarTitle

    void AdminControllerCore::initToolbarTitle()

Set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L617)




### <a name="method-addFiltersToBreadcrumbs"></a>addFiltersToBreadcrumbs

    string|void AdminControllerCore::addFiltersToBreadcrumbs()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 646](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L646)




### <a name="method-viewAccess"></a>viewAccess

    boolean AdminControllerCore::viewAccess(boolean $disable)

Check rights to view the current tab



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L693)


#### Arguments
* $disable **boolean**



### <a name="method-checkToken"></a>checkToken

    boolean AdminControllerCore::checkToken()

Check for security token



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L710)




### <a name="method-processFilter"></a>processFilter

    mixed AdminControllerCore::processFilter()

Set the filters used for the list display



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L743)




### <a name="method-postProcess"></a>postProcess

    boolean AdminControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 860](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L860)




### <a name="method-processDeleteImage"></a>processDeleteImage

    \ObjectModel|false AdminControllerCore::processDeleteImage()

Object Delete images



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 915](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L915)




### <a name="method-processExport"></a>processExport

    mixed AdminControllerCore::processExport(string $text_delimiter)





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 935](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L935)


#### Arguments
* $text_delimiter **string**



### <a name="method-processDelete"></a>processDelete

    \ObjectModel|false AdminControllerCore::processDelete()

Object Delete



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1002](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1002)




### <a name="method-processSave"></a>processSave

    \ObjectModel|false|void AdminControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1048)




### <a name="method-processAdd"></a>processAdd

    \ObjectModel|false AdminControllerCore::processAdd()

Object creation



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1064](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1064)




### <a name="method-processUpdate"></a>processUpdate

    \ObjectModel|false|void AdminControllerCore::processUpdate()

Object update



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1115)




### <a name="method-processUpdateFields"></a>processUpdateFields

    \ObjectModel AdminControllerCore::processUpdateFields()

Change object required fields



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1208)




### <a name="method-processStatus"></a>processStatus

    \ObjectModel|false AdminControllerCore::processStatus()

Change object status (active, inactive)



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1232)




### <a name="method-processPosition"></a>processPosition

    \ObjectModel|false AdminControllerCore::processPosition()

Change object position



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1266)




### <a name="method-processResetFilters"></a>processResetFilters

    mixed AdminControllerCore::processResetFilters(integer|null $list_id)

Cancel all filters for this tab



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1286)


#### Arguments
* $list_id **integer|null**



### <a name="method-processUpdateOptions"></a>processUpdateOptions

    mixed AdminControllerCore::processUpdateOptions()

Update options and preferences



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1323)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1443)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminControllerCore::initToolbar()

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1508](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1508)




### <a name="method-loadObject"></a>loadObject

    \ObjectModel|false AdminControllerCore::loadObject(boolean $opt)

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1576)


#### Arguments
* $opt **boolean** - &lt;p&gt;Return an empty object if load fail&lt;/p&gt;



### <a name="method-checkAccess"></a>checkAccess

    boolean AdminControllerCore::checkAccess()

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1609](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1609)




### <a name="method-filterToField"></a>filterToField

    array|false AdminControllerCore::filterToField(string $key, string $filter)





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 1634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1634)


#### Arguments
* $key **string**
* $filter **string**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

    mixed AdminControllerCore::displayNoSmarty()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1651)




### <a name="method-displayAjax"></a>displayAjax

    void AdminControllerCore::displayAjax()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1658](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1658)




### <a name="method-redirect"></a>redirect

    mixed AdminControllerCore::redirect()





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 1673](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1673)




### <a name="method-display"></a>display

    void AdminControllerCore::display()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1683)




### <a name="method-displayWarning"></a>displayWarning

    mixed AdminControllerCore::displayWarning(string $msg)

Add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 1767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1767)


#### Arguments
* $msg **string**



### <a name="method-displayInformation"></a>displayInformation

    mixed AdminControllerCore::displayInformation(string $msg)

Add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 1777](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1777)


#### Arguments
* $msg **string**



### <a name="method-initHeader"></a>initHeader

    mixed AdminControllerCore::initHeader()

Assign smarty variables for the header



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1785](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1785)




### <a name="method-addRowAction"></a>addRowAction

    mixed AdminControllerCore::addRowAction(string $action)

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1967](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1967)


#### Arguments
* $action **string**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

    mixed AdminControllerCore::addRowActionSkipList(string $action, array $list)

Add an action to use for each row in the list



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1979](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1979)


#### Arguments
* $action **string**
* $list **array**



### <a name="method-initContent"></a>initContent

    mixed AdminControllerCore::initContent()

Assign smarty variables for all default views, list and form, then call other init functions



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 1994](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1994)




### <a name="method-initTabModuleList"></a>initTabModuleList

    mixed AdminControllerCore::initTabModuleList()

Init tab modules list and add button in toolbar



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 2048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2048)




### <a name="method-addPageHeaderToolBarModulesListButton"></a>addPageHeaderToolBarModulesListButton

    mixed AdminControllerCore::addPageHeaderToolBarModulesListButton()





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 2087](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2087)




### <a name="method-addToolBarModulesListButton"></a>addToolBarModulesListButton

    mixed AdminControllerCore::addToolBarModulesListButton()





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 2099](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2099)




### <a name="method-filterTabModuleList"></a>filterTabModuleList

    mixed AdminControllerCore::filterTabModuleList()





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 2111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2111)




### <a name="method-initCursedPage"></a>initCursedPage

    void AdminControllerCore::initCursedPage()

Initialize the invalid doom page of death



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2179)




### <a name="method-initFooter"></a>initFooter

    mixed AdminControllerCore::initFooter()

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2187)




### <a name="method-initModal"></a>initModal

    mixed AdminControllerCore::initModal()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2213)




### <a name="method-renderModal"></a>renderModal

    string AdminControllerCore::renderModal()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2256)




### <a name="method-renderModulesList"></a>renderModulesList

    string AdminControllerCore::renderModulesList()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2271](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2271)




### <a name="method-renderList"></a>renderList

    string|false AdminControllerCore::renderList()

Function used to render the list to display for this controller



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2325](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2325)




### <a name="method-getTemplateListVars"></a>getTemplateListVars

    mixed AdminControllerCore::getTemplateListVars()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2382)




### <a name="method-renderView"></a>renderView

    string AdminControllerCore::renderView()

Override to render the view page



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2392)




### <a name="method-getTemplateViewVars"></a>getTemplateViewVars

    mixed AdminControllerCore::getTemplateViewVars()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2405)




### <a name="method-renderDetails"></a>renderDetails

    string|false AdminControllerCore::renderDetails()

Override to render the view page



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2415](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2415)




### <a name="method-renderForm"></a>renderForm

    string AdminControllerCore::renderForm()

Function used to render the form for this controller



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2427)




### <a name="method-getTemplateFormVars"></a>getTemplateFormVars

    mixed AdminControllerCore::getTemplateFormVars()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2485)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2490)




### <a name="method-renderOptions"></a>renderOptions

    string AdminControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2499)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

    void AdminControllerCore::setHelperDisplay(\Helper $helper)

This function sets various display options for helper list



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2531](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2531)


#### Arguments
* $helper **[Helper](HelperCore)**



### <a name="method-setDeprecatedMedia"></a>setDeprecatedMedia

    mixed AdminControllerCore::setDeprecatedMedia()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2586)




### <a name="method-setMedia"></a>setMedia

    mixed AdminControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2590](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2590)




### <a name="method-l"></a>l

    string AdminControllerCore::l(string $string, string|null $class, boolean $addslashes, boolean $htmlentities)

Non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 2648](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2648)


#### Arguments
* $string **string** - &lt;p&gt;Term or expression in english&lt;/p&gt;
* $class **string|null** - &lt;p&gt;Name of the class&lt;/p&gt;
* $addslashes **boolean** - &lt;p&gt;If set to true, the return value will pass through addslashes(). Otherwise, stripslashes().&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;If set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)&lt;/p&gt;



### <a name="method-init"></a>init

    mixed AdminControllerCore::init()

Init context and dependencies, handles POST and GET



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2662)




### <a name="method-initShopContext"></a>initShopContext

    mixed AdminControllerCore::initShopContext()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2751)




### <a name="method-initProcess"></a>initProcess

    mixed AdminControllerCore::initProcess()

Retrieve GET and POST value and translate them to actions



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 2821](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2821)




### <a name="method-getList"></a>getList

    mixed AdminControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

Get the current objects' list form the database



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3005](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3005)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language used for display&lt;/p&gt;
* $order_by **string|null** - &lt;p&gt;ORDER BY clause&lt;/p&gt;
* $order_way **string|null** - &lt;p&gt;Order way (ASC, DESC)&lt;/p&gt;
* $start **integer** - &lt;p&gt;Offset in LIMIT clause&lt;/p&gt;
* $limit **integer|null** - &lt;p&gt;Row count in LIMIT clause&lt;/p&gt;
* $id_lang_shop **integer|boolean**



### <a name="method-getModulesList"></a>getModulesList

    boolean AdminControllerCore::getModulesList(array|string $filter_modules_list)





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3241)


#### Arguments
* $filter_modules_list **array|string**



### <a name="method-getLanguages"></a>getLanguages

    array AdminControllerCore::getLanguages()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3282)




### <a name="method-getFieldsValue"></a>getFieldsValue

    array AdminControllerCore::getFieldsValue(\ObjectModel $obj)

Return the list of fields value



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3314)


#### Arguments
* $obj **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;



### <a name="method-getFieldValue"></a>getFieldValue

    string AdminControllerCore::getFieldValue(\ObjectModel $obj, string $key, integer|null $id_lang)

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3365)


#### Arguments
* $obj **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;
* $key **string** - &lt;p&gt;Field name&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Language id (optional)&lt;/p&gt;



### <a name="method-validateRules"></a>validateRules

    mixed AdminControllerCore::validateRules(string|boolean $class_name)

Manage page display (form, list.

..)

* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3382)


#### Arguments
* $class_name **string|boolean** - &lt;p&gt;Allow to validate a different class than the current one&lt;/p&gt;



### <a name="method-_childValidation"></a>_childValidation

    mixed AdminControllerCore::_childValidation()

Overload this method for custom checking



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3460)




### <a name="method-viewDetails"></a>viewDetails

    mixed AdminControllerCore::viewDetails()

Display object details



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3467](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3467)




### <a name="method-beforeDelete"></a>beforeDelete

    boolean AdminControllerCore::beforeDelete(\ObjectModel $object)

Called before deletion



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3477)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;



### <a name="method-afterDelete"></a>afterDelete

    boolean AdminControllerCore::afterDelete(\ObjectModel $object, integer $old_id)

Called before deletion



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3489](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3489)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;
* $old_id **integer**



### <a name="method-afterAdd"></a>afterAdd

    boolean AdminControllerCore::afterAdd(\ObjectModel $object)





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3498](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3498)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)**



### <a name="method-afterUpdate"></a>afterUpdate

    boolean AdminControllerCore::afterUpdate(\ObjectModel $object)





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3507)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)**



### <a name="method-afterImageUpload"></a>afterImageUpload

    boolean AdminControllerCore::afterImageUpload()

Check rights to view the current tab



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3517](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3517)




### <a name="method-copyFromPost"></a>copyFromPost

    mixed AdminControllerCore::copyFromPost($object, string $table)

Copy data values from $_POST to object



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3528)


#### Arguments
* $object **mixed**
* $table **string** - &lt;p&gt;Object table&lt;/p&gt;



### <a name="method-getSelectedAssoShop"></a>getSelectedAssoShop

    array AdminControllerCore::getSelectedAssoShop(string $table)

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3569)


#### Arguments
* $table **string**



### <a name="method-updateAssoShop"></a>updateAssoShop

    boolean|void AdminControllerCore::updateAssoShop(integer $id_object)

Update the associations of shops



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3599](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3599)


#### Arguments
* $id_object **integer**



### <a name="method-validateField"></a>validateField

    boolean AdminControllerCore::validateField(mixed $value, array $field)





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3635](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3635)


#### Arguments
* $value **mixed**
* $field **array**



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

    mixed AdminControllerCore::beforeUpdateOptions()

Can be overridden



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3653](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3653)




### <a name="method-postImage"></a>postImage

    boolean AdminControllerCore::postImage(integer $id)

Overload this method for custom checking



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3663](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3663)


#### Arguments
* $id **integer** - &lt;p&gt;Object id used for deleting images&lt;/p&gt;



### <a name="method-uploadImage"></a>uploadImage

    boolean AdminControllerCore::uploadImage(integer $id, string $name, string $dir, string|boolean $ext, integer|null $width, integer|null $height)





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3686)


#### Arguments
* $id **integer**
* $name **string**
* $dir **string**
* $ext **string|boolean**
* $width **integer|null**
* $height **integer|null**



### <a name="method-processBulkDelete"></a>processBulkDelete

    boolean AdminControllerCore::processBulkDelete()

Delete multiple items



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3738)




### <a name="method-ajaxProcessOpenHelp"></a>ajaxProcessOpenHelp

    mixed AdminControllerCore::ajaxProcessOpenHelp()





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3791](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3791)




### <a name="method-processBulkEnableSelection"></a>processBulkEnableSelection

    boolean AdminControllerCore::processBulkEnableSelection()

Enable multiple items



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3825](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3825)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

    boolean AdminControllerCore::processBulkDisableSelection()

Disable multiple items



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3835](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3835)




### <a name="method-processBulkStatusSelection"></a>processBulkStatusSelection

    boolean AdminControllerCore::processBulkStatusSelection(boolean $status)

Toggle status of multiple items



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3847](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3847)


#### Arguments
* $status **boolean**



### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

    boolean AdminControllerCore::processBulkAffectZone()





* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3864)




### <a name="method-beforeAdd"></a>beforeAdd

    boolean AdminControllerCore::beforeAdd(\ObjectModel $object)

Called before Add



* Visibility: **protected**
* This method is defined in [classes/controller/AdminController.php line 3889](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3889)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;Object&lt;/p&gt;



### <a name="method-displayRequiredFields"></a>displayRequiredFields

    string|void AdminControllerCore::displayRequiredFields()

Prepare the view to display the required fields form



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3899)




### <a name="method-createTemplate"></a>createTemplate

    \Smarty_Internal_Template AdminControllerCore::createTemplate(string $tpl_name)

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3918](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3918)


#### Arguments
* $tpl_name **string** - &lt;p&gt;filename&lt;/p&gt;



### <a name="method-jsonConfirmation"></a>jsonConfirmation

    mixed AdminControllerCore::jsonConfirmation(string $message)

Shortcut to set up a json success payload



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3938](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3938)


#### Arguments
* $message **string** - &lt;p&gt;Success message&lt;/p&gt;



### <a name="method-jsonError"></a>jsonError

    mixed AdminControllerCore::jsonError(string $message)

Shortcut to set up a json error payload



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3952](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3952)


#### Arguments
* $message **string** - &lt;p&gt;Error message&lt;/p&gt;



### <a name="method-isFresh"></a>isFresh

    boolean AdminControllerCore::isFresh(string $file, integer $timeout)





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3966](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3966)


#### Arguments
* $file **string**
* $timeout **integer**



### <a name="method-refresh"></a>refresh

    boolean AdminControllerCore::refresh(string $file_to_refresh, string $external_file)





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3983](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3983)


#### Arguments
* $file_to_refresh **string**
* $external_file **string**



### <a name="method-fillModuleData"></a>fillModuleData

    mixed AdminControllerCore::fillModuleData(\Module $module, string $output_type, string|null $back)





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 3997](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3997)


#### Arguments
* $module **[Module](ModuleCore)**
* $output_type **string**
* $back **string|null**



### <a name="method-displayModuleOptions"></a>displayModuleOptions

    string|array AdminControllerCore::displayModuleOptions(\Module $module, string $output_type, string|null $back)

Display modules list



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 4048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4048)


#### Arguments
* $module **[Module](ModuleCore)**
* $output_type **string** - &lt;p&gt;(link or select)&lt;/p&gt;
* $back **string|null**



### <a name="method-ajaxProcessGetModuleQuickView"></a>ajaxProcessGetModuleQuickView

    mixed AdminControllerCore::ajaxProcessGetModuleQuickView()





* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 4316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4316)




### <a name="method-addMetaTitle"></a>addMetaTitle

    mixed AdminControllerCore::addMetaTitle(string $entry)

Add an entry to the meta title.



* Visibility: **public**
* This method is defined in [classes/controller/AdminController.php line 4357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4357)


#### Arguments
* $entry **string** - &lt;p&gt;New entry.&lt;/p&gt;


