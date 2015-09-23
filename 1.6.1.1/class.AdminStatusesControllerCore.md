Class AdminStatusesControllerCore
=====================





* Class name: AdminStatusesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStatusesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$_default_pagination](#property-$_default_pagination)
* [$_filter](#property-$_filter)
* [$_filterHaving](#property-$_filterHaving)
* [$_group](#property-$_group)
* [$_having](#property-$_having)
* [$_includeContainer](#property-$_includeContainer)
* [$_join](#property-$_join)
* [$_languages](#property-$_languages)
* [$_list](#property-$_list)
* [$_listTotal](#property-$_listTotal)
* [$_listsql](#property-$_listsql)
* [$_orderBy](#property-$_orderBy)
* [$_orderWay](#property-$_orderWay)
* [$_pagination](#property-$_pagination)
* [$_redirect](#property-$_redirect)
* [$_select](#property-$_select)
* [$_tmpTableFilter](#property-$_tmpTableFilter)
* [$_use_found_rows](#property-$_use_found_rows)
* [$_where](#property-$_where)
* [$action](#property-$action)
* [$actions](#property-$actions)
* [$actions_available](#property-$actions_available)
* [$admin_webpath](#property-$admin_webpath)
* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$allow_export](#property-$allow_export)
* [$base_tpl_form](#property-$base_tpl_form)
* [$base_tpl_view](#property-$base_tpl_view)
* [$bo_theme](#property-$bo_theme)
* [$bootstrap](#property-$bootstrap)
* [$boxes](#property-$boxes)
* [$breadcrumbs](#property-$breadcrumbs)
* [$bulk_actions](#property-$bulk_actions)
* [$cache_lang](#property-$cache_lang)
* [$can_import](#property-$can_import)
* [$className](#property-$className)
* [$colorOnBackground](#property-$colorOnBackground)
* [$confirmations](#property-$confirmations)
* [$content](#property-$content)
* [$controller_name](#property-$controller_name)
* [$currentIndex](#property-$currentIndex)
* [$default_form_language](#property-$default_form_language)
* [$deleted](#property-$deleted)
* [$display](#property-$display)
* [$errors](#property-$errors)
* [$explicitSelect](#property-$explicitSelect)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$fields_form](#property-$fields_form)
* [$fields_form_override](#property-$fields_form_override)
* [$fields_list](#property-$fields_list)
* [$fields_options](#property-$fields_options)
* [$fields_value](#property-$fields_value)
* [$filter](#property-$filter)
* [$filter_modules_list](#property-$filter_modules_list)
* [$helper](#property-$helper)
* [$id](#property-$id)
* [$id_object](#property-$id_object)
* [$identifier](#property-$identifier)
* [$identifier_name](#property-$identifier_name)
* [$imageType](#property-$imageType)
* [$informations](#property-$informations)
* [$is_cms](#property-$is_cms)
* [$is_prestashop_up](#property-$is_prestashop_up)
* [$lang](#property-$lang)
* [$layout](#property-$layout)
* [$list_id](#property-$list_id)
* [$list_natives_modules](#property-$list_natives_modules)
* [$list_no_link](#property-$list_no_link)
* [$list_partners_modules](#property-$list_partners_modules)
* [$list_simple_header](#property-$list_simple_header)
* [$list_skip_actions](#property-$list_skip_actions)
* [$lite_display](#property-$lite_display)
* [$logged_on_addons](#property-$logged_on_addons)
* [$meta_title](#property-$meta_title)
* [$modals](#property-$modals)
* [$modules_list](#property-$modules_list)
* [$multiple_fieldsets](#property-$multiple_fieldsets)
* [$multishop_context](#property-$multishop_context)
* [$multishop_context_group](#property-$multishop_context_group)
* [$noLink](#property-$noLink)
* [$page_header_toolbar_btn](#property-$page_header_toolbar_btn)
* [$page_header_toolbar_title](#property-$page_header_toolbar_title)
* [$path](#property-$path)
* [$position_group_identifier](#property-$position_group_identifier)
* [$position_identifier](#property-$position_identifier)
* [$required_database](#property-$required_database)
* [$required_fields](#property-$required_fields)
* [$row_hover](#property-$row_hover)
* [$shopLink](#property-$shopLink)
* [$shopLinkType](#property-$shopLinkType)
* [$shopShareDatas](#property-$shopShareDatas)
* [$show_form_cancel_button](#property-$show_form_cancel_button)
* [$show_page_header_toolbar](#property-$show_page_header_toolbar)
* [$show_toolbar](#property-$show_toolbar)
* [$show_toolbar_options](#property-$show_toolbar_options)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$submit_action](#property-$submit_action)
* [$tabAccess](#property-$tabAccess)
* [$tab_modules_list](#property-$tab_modules_list)
* [$table](#property-$table)
* [$template](#property-$template)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$toolbar_title](#property-$toolbar_title)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$tpl_folder](#property-$tpl_folder)
* [$tpl_form_vars](#property-$tpl_form_vars)
* [$tpl_list_vars](#property-$tpl_list_vars)
* [$tpl_option_vars](#property-$tpl_option_vars)
* [$tpl_required_fields_vars](#property-$tpl_required_fields_vars)
* [$tpl_view_vars](#property-$tpl_view_vars)
* [$translationsTab](#property-$translationsTab)
* [$warnings](#property-$warnings)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$controller_type](#property-$controller_type)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$display_header_javascript](#property-$display_header_javascript)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$php_errors](#property-$php_errors)
* [$php_self](#property-$php_self)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)

### Methods

* [__construct](#method-__construct)
* [_childValidation](#method-_childValidation)
* [addCSS](#method-addCSS)
* [addFiltersToBreadcrumbs](#method-addFiltersToBreadcrumbs)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addMetaTitle](#method-addMetaTitle)
* [addPageHeaderToolBarModulesListButton](#method-addPageHeaderToolBarModulesListButton)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [addToolBarModulesListButton](#method-addToolBarModulesListButton)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxDie](#method-ajaxDie)
* [ajaxProcessDeliveryOrderState](#method-ajaxProcessDeliveryOrderState)
* [ajaxProcessGetModuleQuickView](#method-ajaxProcessGetModuleQuickView)
* [ajaxProcessInvoiceOrderState](#method-ajaxProcessInvoiceOrderState)
* [ajaxProcessOpenHelp](#method-ajaxProcessOpenHelp)
* [ajaxProcessSendEmailOrderState](#method-ajaxProcessSendEmailOrderState)
* [beforeAdd](#method-beforeAdd)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [checkAccess](#method-checkAccess)
* [checkFilterForOrdersReturnsList](#method-checkFilterForOrdersReturnsList)
* [checkToken](#method-checkToken)
* [copyFromPost](#method-copyFromPost)
* [createTemplate](#method-createTemplate)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayHeaderJavaScript](#method-displayHeaderJavaScript)
* [displayInformation](#method-displayInformation)
* [displayModuleOptions](#method-displayModuleOptions)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayWarning](#method-displayWarning)
* [fillModuleData](#method-fillModuleData)
* [filterTabModuleList](#method-filterTabModuleList)
* [filterToField](#method-filterToField)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getLanguages](#method-getLanguages)
* [getList](#method-getList)
* [getModulesList](#method-getModulesList)
* [getSelectedAssoShop](#method-getSelectedAssoShop)
* [getTemplateFormVars](#method-getTemplateFormVars)
* [getTemplateListVars](#method-getTemplateListVars)
* [getTemplateViewVars](#method-getTemplateViewVars)
* [getTemplates](#method-getTemplates)
* [init](#method-init)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [initModal](#method-initModal)
* [initOrderReturnsForm](#method-initOrderReturnsForm)
* [initOrderStatutsList](#method-initOrderStatutsList)
* [initOrdersReturnsList](#method-initOrdersReturnsList)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initShopContext](#method-initShopContext)
* [initTabModuleList](#method-initTabModuleList)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [isCached](#method-isCached)
* [isFresh](#method-isFresh)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [jsonConfirmation](#method-jsonConfirmation)
* [jsonError](#method-jsonError)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [myErrorHandler](#method-myErrorHandler)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [processBulkDelete](#method-processBulkDelete)
* [processBulkDisableSelection](#method-processBulkDisableSelection)
* [processBulkEnableSelection](#method-processBulkEnableSelection)
* [processBulkStatusSelection](#method-processBulkStatusSelection)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processExport](#method-processExport)
* [processFilter](#method-processFilter)
* [processPosition](#method-processPosition)
* [processResetFilters](#method-processResetFilters)
* [processSave](#method-processSave)
* [processStatus](#method-processStatus)
* [processUpdate](#method-processUpdate)
* [processUpdateFields](#method-processUpdateFields)
* [processUpdateOptions](#method-processUpdateOptions)
* [redirect](#method-redirect)
* [refresh](#method-refresh)
* [removeCSS](#method-removeCSS)
* [removeJS](#method-removeJS)
* [renderDetails](#method-renderDetails)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderModal](#method-renderModal)
* [renderModulesList](#method-renderModulesList)
* [renderOptions](#method-renderOptions)
* [renderOrderReturnsForm](#method-renderOrderReturnsForm)
* [renderOrderStatusForm](#method-renderOrderStatusForm)
* [renderView](#method-renderView)
* [run](#method-run)
* [setDeprecatedMedia](#method-setDeprecatedMedia)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setRedirectAfter](#method-setRedirectAfter)
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [updateAssoShop](#method-updateAssoShop)
* [uploadImage](#method-uploadImage)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \OrderState $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L30).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L102).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected string $_defaultOrderWay = 'ASC'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L105).


### <a name="property-$_default_pagination"></a>$_default_pagination

```php
protected integer $_default_pagination = 50
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L207).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L195).


### <a name="property-$_filterHaving"></a>$_filterHaving

```php
protected string $_filterHaving
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L198).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L276).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L279).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected boolean $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L318).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L270).


### <a name="property-$_languages"></a>$_languages

```php
public array $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L51).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L171).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L189).


### <a name="property-$_listsql"></a>$_listsql

```php
protected string $_listsql = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L168).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L210).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L213).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300, 1000)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L204).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L330).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L267).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L201).


### <a name="property-$_use_found_rows"></a>$_use_found_rows

```php
protected string $_use_found_rows = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L282).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L273).


### <a name="property-$action"></a>$action

```php
protected string $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L312).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L219).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'duplicate', 'delete')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L216).


### <a name="property-$admin_webpath"></a>$admin_webpath

```php
public string $admin_webpath
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L369).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public boolean $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L57).


### <a name="property-$allow_export"></a>$allow_export

```php
protected boolean $allow_export = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L231).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public string $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L129).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public string $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L126).


### <a name="property-$bo_theme"></a>$bo_theme

```php
protected string $bo_theme
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L327).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public boolean $bootstrap = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L63).


### <a name="property-$boxes"></a>$boxes

```php
protected mixed $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L261).


### <a name="property-$breadcrumbs"></a>$breadcrumbs

```php
protected array $breadcrumbs
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L354).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```

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
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L258).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L234).


### <a name="property-$can_import"></a>$can_import

```php
protected boolean $can_import = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L384).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L84).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected boolean $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L306).


### <a name="property-$confirmations"></a>$confirmations

```php
public array $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L45).


### <a name="property-$content"></a>$content

```php
public string $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L36).


### <a name="property-$controller_name"></a>$controller_name

```php
public string $controller_name
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L345).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public string $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L33).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public integer $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L54).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L294).


### <a name="property-$display"></a>$display

```php
protected string $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L315).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L138).


### <a name="property-$explicitSelect"></a>$explicitSelect

```php
protected string $explicitSelect = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L264).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L333).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L153).


### <a name="property-$fields_form_override"></a>$fields_form_override

```php
protected array $fields_form_override
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L156).


### <a name="property-$fields_list"></a>$fields_list

```php
protected array $fields_list
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L144).


### <a name="property-$fields_options"></a>$fields_options

```php
protected array $fields_options = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L162).


### <a name="property-$fields_value"></a>$fields_value

```php
public array $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L135).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L297).


### <a name="property-$filter_modules_list"></a>$filter_modules_list

```php
protected array $filter_modules_list = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L147).


### <a name="property-$helper"></a>$helper

```php
protected \HelperList $helper
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L240).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L90).


### <a name="property-$id_object"></a>$id_object

```php
protected integer $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L342).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L78).


### <a name="property-$identifier_name"></a>$identifier_name

```php
protected string $identifier_name = 'name'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L81).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L336).


### <a name="property-$informations"></a>$informations

```php
public array $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L42).


### <a name="property-$is_cms"></a>$is_cms

```php
protected boolean $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L285).


### <a name="property-$is_prestashop_up"></a>$is_prestashop_up

```php
protected boolean $is_prestashop_up = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3976](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3976).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L192).


### <a name="property-$layout"></a>$layout

```php
public string $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L60).


### <a name="property-$list_id"></a>$list_id

```php
public string $list_id
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L75).


### <a name="property-$list_natives_modules"></a>$list_natives_modules

```php
protected array $list_natives_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L372).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L228).


### <a name="property-$list_partners_modules"></a>$list_partners_modules

```php
protected array $list_partners_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L375).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected boolean $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L141).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L222).


### <a name="property-$lite_display"></a>$lite_display

```php
protected mixed $lite_display = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L225).


### <a name="property-$logged_on_addons"></a>$logged_on_addons

```php
protected boolean $logged_on_addons = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L381).


### <a name="property-$meta_title"></a>$meta_title

```php
protected string $meta_title = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L66).


### <a name="property-$modals"></a>$modals

```php
public array $modals = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L378).


### <a name="property-$modules_list"></a>$modules_list

```php
protected array $modules_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L150).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L132).


### <a name="property-$multishop_context"></a>$multishop_context

```php
public integer $multishop_context = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L348).


### <a name="property-$multishop_context_group"></a>$multishop_context_group

```php
public false $multishop_context_group = true
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L351).


### <a name="property-$noLink"></a>$noLink

```php
protected boolean $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L300).


### <a name="property-$page_header_toolbar_btn"></a>$page_header_toolbar_btn

```php
public array $page_header_toolbar_btn = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L363).


### <a name="property-$page_header_toolbar_title"></a>$page_header_toolbar_title

```php
public string $page_header_toolbar_title
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L360).


### <a name="property-$path"></a>$path

```php
public string $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L30).


### <a name="property-$position_group_identifier"></a>$position_group_identifier

```php
protected string $position_group_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L291).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected string $position_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L288).


### <a name="property-$required_database"></a>$required_database

```php
public boolean $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L93).


### <a name="property-$required_fields"></a>$required_fields

```php
public array $required_fields = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L237).


### <a name="property-$row_hover"></a>$row_hover

```php
protected boolean $row_hover = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L309).


### <a name="property-$shopLink"></a>$shopLink

```php
protected string $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L165).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L99).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public string $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L48).


### <a name="property-$show_form_cancel_button"></a>$show_form_cancel_button

```php
public boolean $show_form_cancel_button
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L366).


### <a name="property-$show_page_header_toolbar"></a>$show_page_header_toolbar

```php
public boolean $show_page_header_toolbar = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L357).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L183).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L186).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected boolean $specificConfirmDelete = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L303).


### <a name="property-$submit_action"></a>$submit_action

```php
protected string $submit_action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L159).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L87).


### <a name="property-$tab_modules_list"></a>$tab_modules_list

```php
protected array $tab_modules_list = array('default_list' => array(), 'slider_list' => array())
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L321).


### <a name="property-$table"></a>$table

```php
public string $table = 'configuration'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L72).


### <a name="property-$template"></a>$template

```php
public string $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L69).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L96).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L177).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected boolean $toolbar_scroll = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L180).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected string $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L174).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public array $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L114).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public string $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L324).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public array $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L108).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public array $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L111).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public array $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L117).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public array $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L123).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public array $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L120).


### <a name="property-$translationsTab"></a>$translationsTab

```php
protected array $translationsTab = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 4038](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4038).


### <a name="property-$warnings"></a>$warnings

```php
public array $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L39).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L61).


### <a name="property-$content_only"></a>$content_only

```php
protected boolean $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L58).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L34).


### <a name="property-$controller_type"></a>$controller_type

```php
public string $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L76).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L37).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L55).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L46).


### <a name="property-$display_header_javascript"></a>$display_header_javascript

```php
protected boolean $display_header_javascript
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L49).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L40).


### <a name="property-$json"></a>$json

```php
protected boolean $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L64).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L43).


### <a name="property-$php_self"></a>$php_self

```php
public string $php_self
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L79).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected string $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L73).


### <a name="property-$status"></a>$status

```php
protected string $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L67).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStatusesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L32)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3460)




### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(string|array $css_uri, string $css_media_type, integer|null $offset, boolean $check_path)
```

Adds a new stylesheet(s) to the page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L299)


#### Arguments
* $css_uri **string|array** - Path to CSS file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $offset **integer|null**
* $check_path **boolean**



### <a name="method-addFiltersToBreadcrumbs"></a>addFiltersToBreadcrumbs

```php
string|void AdminControllerCore::addFiltersToBreadcrumbs()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 646](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L646)




### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(string|array $js_uri, boolean $check_path)
```

Adds a new JavaScript file(s) to the page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L373)


#### Arguments
* $js_uri **string|array** - Path to JS file or an array like: array(uri, ...)
* $check_path **boolean**



### <a name="method-addJquery"></a>addJquery

```php
mixed ControllerCore::addJquery(string|null $version, string|null $folder, boolean $minifier)
```

Adds jQuery library file to queued JS file list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L437)


#### Arguments
* $version **string|null** - jQuery library version
* $folder **string|null** - jQuery file folder
* $minifier **boolean** - If set tot true, a minified version will be included.



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
mixed ControllerCore::addJqueryPlugin(string|array $name, $folder, boolean $css)
```

Adds jQuery plugin(s) to queued JS file list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L469)


#### Arguments
* $name **string|array**
* $folder **mixed**
* $css **boolean**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
mixed ControllerCore::addJqueryUI(string|array $component, string $theme, boolean $check_dependencies)
```

Adds jQuery UI component(s) to queued JS file list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L449)


#### Arguments
* $component **string|array**
* $theme **string**
* $check_dependencies **boolean**



### <a name="method-addMetaTitle"></a>addMetaTitle

```php
mixed AdminControllerCore::addMetaTitle(string $entry)
```

Add an entry to the meta title.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 4357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4357)


#### Arguments
* $entry **string** - New entry.



### <a name="method-addPageHeaderToolBarModulesListButton"></a>addPageHeaderToolBarModulesListButton

```php
mixed AdminControllerCore::addPageHeaderToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2087](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2087)




### <a name="method-addRowAction"></a>addRowAction

```php
mixed AdminControllerCore::addRowAction(string $action)
```

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1967](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1967)


#### Arguments
* $action **string**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList(string $action, array $list)
```

Add an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1979](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1979)


#### Arguments
* $action **string**
* $list **array**



### <a name="method-addToolBarModulesListButton"></a>addToolBarModulesListButton

```php
mixed AdminControllerCore::addToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2099](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2099)




### <a name="method-afterAdd"></a>afterAdd

```php
boolean AdminControllerCore::afterAdd(\ObjectModel $object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3498](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3498)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(\ObjectModel $object, integer $old_id)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3489](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3489)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - Object
* $old_id **integer**



### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminStatusesControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L626)




### <a name="method-afterUpdate"></a>afterUpdate

```php
boolean AdminControllerCore::afterUpdate(\ObjectModel $object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3507)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-ajaxDie"></a>ajaxDie

```php
mixed ControllerCore::ajaxDie(string|null $value, string|null $controller, string|null $method)
```

Dies and echoes output value



* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L626)


#### Arguments
* $value **string|null**
* $controller **string|null**
* $method **string|null**



### <a name="method-ajaxProcessDeliveryOrderState"></a>ajaxProcessDeliveryOrderState

```php
mixed AdminStatusesControllerCore::ajaxProcessDeliveryOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L656)




### <a name="method-ajaxProcessGetModuleQuickView"></a>ajaxProcessGetModuleQuickView

```php
mixed AdminControllerCore::ajaxProcessGetModuleQuickView()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 4316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4316)




### <a name="method-ajaxProcessInvoiceOrderState"></a>ajaxProcessInvoiceOrderState

```php
mixed AdminStatusesControllerCore::ajaxProcessInvoiceOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L670)




### <a name="method-ajaxProcessOpenHelp"></a>ajaxProcessOpenHelp

```php
mixed AdminControllerCore::ajaxProcessOpenHelp()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3791](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3791)




### <a name="method-ajaxProcessSendEmailOrderState"></a>ajaxProcessSendEmailOrderState

```php
mixed AdminStatusesControllerCore::ajaxProcessSendEmailOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L642)




### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(\ObjectModel $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3889](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3889)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(\ObjectModel $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3477)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overridden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3653](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3653)




### <a name="method-checkAccess"></a>checkAccess

```php
boolean AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1609](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1609)




### <a name="method-checkFilterForOrdersReturnsList"></a>checkFilterForOrdersReturnsList

```php
mixed AdminStatusesControllerCore::checkFilterForOrdersReturnsList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L242)




### <a name="method-checkToken"></a>checkToken

```php
boolean AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L710)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminControllerCore::copyFromPost($object, string $table)
```

Copy data values from $_POST to object



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3528)


#### Arguments
* $object **mixed**
* $table **string** - Object table



### <a name="method-createTemplate"></a>createTemplate

```php
\Smarty_Internal_Template AdminControllerCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3918](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3918)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-display"></a>display

```php
void AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1683)




### <a name="method-displayAjax"></a>displayAjax

```php
void AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1658](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1658)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter(boolean $display)
```

Sets page header display



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L242)


#### Arguments
* $display **boolean**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader(boolean $display)
```

Sets page header display



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L222)


#### Arguments
* $display **boolean**



### <a name="method-displayHeaderJavaScript"></a>displayHeaderJavaScript

```php
mixed ControllerCore::displayHeaderJavaScript(boolean $display)
```

Sets page header javascript display



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L232)


#### Arguments
* $display **boolean**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

Add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1777](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1777)


#### Arguments
* $msg **string**



### <a name="method-displayModuleOptions"></a>displayModuleOptions

```php
string|array AdminControllerCore::displayModuleOptions(\Module $module, string $output_type, string|null $back)
```

Display modules list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 4048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L4048)


#### Arguments
* $module **[Module](class.ModuleCore.md)**
* $output_type **string** - (link or select)
* $back **string|null**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1651)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
string|void AdminControllerCore::displayRequiredFields()
```

Prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3899)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

Add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1767)


#### Arguments
* $msg **string**



### <a name="method-fillModuleData"></a>fillModuleData

```php
mixed AdminControllerCore::fillModuleData(\Module $module, string $output_type, string|null $back)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3997](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3997)


#### Arguments
* $module **[Module](class.ModuleCore.md)**
* $output_type **string**
* $back **string|null**



### <a name="method-filterTabModuleList"></a>filterTabModuleList

```php
mixed AdminControllerCore::filterTabModuleList()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2111)




### <a name="method-filterToField"></a>filterToField

```php
mixed AdminStatusesControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L615)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-getController"></a>getController

```php
\Controller ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

returns a new instance of this controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L132)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getFieldValue"></a>getFieldValue

```php
string AdminControllerCore::getFieldValue(\ObjectModel $obj, string $key, integer|null $id_lang)
```

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3365)


#### Arguments
* $obj **[ObjectModel](class.ObjectModelCore.md)** - Object
* $key **string** - Field name
* $id_lang **integer|null** - Language id (optional)



### <a name="method-getFieldsValue"></a>getFieldsValue

```php
array AdminControllerCore::getFieldsValue(\ObjectModel $obj)
```

Return the list of fields value



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3314)


#### Arguments
* $obj **[ObjectModel](class.ObjectModelCore.md)** - Object



### <a name="method-getLanguages"></a>getLanguages

```php
array AdminControllerCore::getLanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3282)




### <a name="method-getList"></a>getList

```php
mixed AdminControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

Get the current objects' list form the database



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3005](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3005)


#### Arguments
* $id_lang **integer** - Language used for display
* $order_by **string|null** - ORDER BY clause
* $order_way **string|null** - Order way (ASC, DESC)
* $start **integer** - Offset in LIMIT clause
* $limit **integer|null** - Row count in LIMIT clause
* $id_lang_shop **integer|boolean**



### <a name="method-getModulesList"></a>getModulesList

```php
boolean AdminControllerCore::getModulesList(array|string $filter_modules_list)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3241)


#### Arguments
* $filter_modules_list **array|string**



### <a name="method-getSelectedAssoShop"></a>getSelectedAssoShop

```php
array AdminControllerCore::getSelectedAssoShop(string $table)
```

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3569)


#### Arguments
* $table **string**



### <a name="method-getTemplateFormVars"></a>getTemplateFormVars

```php
mixed AdminControllerCore::getTemplateFormVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2485)




### <a name="method-getTemplateListVars"></a>getTemplateListVars

```php
mixed AdminControllerCore::getTemplateListVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2382)




### <a name="method-getTemplateViewVars"></a>getTemplateViewVars

```php
mixed AdminControllerCore::getTemplateViewVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2405)




### <a name="method-getTemplates"></a>getTemplates

```php
mixed AdminStatusesControllerCore::getTemplates()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L493)




### <a name="method-init"></a>init

```php
mixed AdminStatusesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L51)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminControllerCore::initBreadcrumbs(integer|null $tab_id, array|null $tabs)
```

Set breadcrumbs array for the controller page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 537](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L537)


#### Arguments
* $tab_id **integer|null**
* $tabs **array|null**



### <a name="method-initContent"></a>initContent

```php
mixed AdminControllerCore::initContent()
```

Assign smarty variables for all default views, list and form, then call other init functions



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1994](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1994)




### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

Initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2179)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2187)




### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1785](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1785)




### <a name="method-initModal"></a>initModal

```php
mixed AdminControllerCore::initModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2213)




### <a name="method-initOrderReturnsForm"></a>initOrderReturnsForm

```php
mixed AdminStatusesControllerCore::initOrderReturnsForm()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L148)




### <a name="method-initOrderStatutsList"></a>initOrderStatutsList

```php
mixed AdminStatusesControllerCore::initOrderStatutsList()
```

init all variables to render the order status list



* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L66)




### <a name="method-initOrdersReturnsList"></a>initOrdersReturnsList

```php
mixed AdminStatusesControllerCore::initOrdersReturnsList()
```

init all variables to render the order return list



* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L124)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStatusesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L188)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminControllerCore::initProcess()
```

Retrieve GET and POST value and translate them to actions



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2821](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2821)




### <a name="method-initShopContext"></a>initShopContext

```php
mixed AdminControllerCore::initShopContext()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2751)




### <a name="method-initTabModuleList"></a>initTabModuleList

```php
mixed AdminControllerCore::initTabModuleList()
```

Init tab modules list and add button in toolbar



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2048)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminControllerCore::initToolbar()
```

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1508](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1508)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
void AdminControllerCore::initToolbarTitle()
```

Set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L617)




### <a name="method-isCached"></a>isCached

```php
boolean ControllerCore::isCached(string $template, string|null $cache_id, string|null $compile_id)
```

Checks if a template is cached



* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L565)


#### Arguments
* $template **string**
* $cache_id **string|null** - Cache item ID
* $compile_id **string|null**



### <a name="method-isFresh"></a>isFresh

```php
boolean AdminControllerCore::isFresh(string $file, integer $timeout)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3966](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3966)


#### Arguments
* $file **string**
* $timeout **integer**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```

Checks if the controller has been called from XmlHttpRequest (AJAX)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L494)




### <a name="method-jsonConfirmation"></a>jsonConfirmation

```php
mixed AdminControllerCore::jsonConfirmation(string $message)
```

Shortcut to set up a json success payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3938](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3938)


#### Arguments
* $message **string** - Success message



### <a name="method-jsonError"></a>jsonError

```php
mixed AdminControllerCore::jsonError(string $message)
```

Shortcut to set up a json error payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3952](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3952)


#### Arguments
* $message **string** - Error message



### <a name="method-l"></a>l

```php
string AdminControllerCore::l(string $string, string|null $class, boolean $addslashes, boolean $htmlentities)
```

Non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2648](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2648)


#### Arguments
* $string **string** - Term or expression in english
* $class **string|null** - Name of the class
* $addslashes **boolean** - If set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - If set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
\ObjectModel|false AdminControllerCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1576)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-myErrorHandler"></a>myErrorHandler

```php
boolean ControllerCore::myErrorHandler(string $errno, string $errstr, string $errfile, integer $errline)
```

Custom error handler



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L583)


#### Arguments
* $errno **string**
* $errstr **string**
* $errfile **string**
* $errline **integer**



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3663](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3663)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminStatusesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L527)




### <a name="method-processAdd"></a>processAdd

```php
\ObjectModel|false AdminControllerCore::processAdd()
```

Object creation



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1064](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1064)




### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
boolean AdminControllerCore::processBulkAffectZone()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3864)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminControllerCore::processBulkDelete()
```

Delete multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3738)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
boolean AdminControllerCore::processBulkDisableSelection()
```

Disable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3835](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3835)




### <a name="method-processBulkEnableSelection"></a>processBulkEnableSelection

```php
boolean AdminControllerCore::processBulkEnableSelection()
```

Enable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3825](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3825)




### <a name="method-processBulkStatusSelection"></a>processBulkStatusSelection

```php
boolean AdminControllerCore::processBulkStatusSelection(boolean $status)
```

Toggle status of multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3847](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3847)


#### Arguments
* $status **boolean**



### <a name="method-processDelete"></a>processDelete

```php
\ObjectModel|false AdminControllerCore::processDelete()
```

Object Delete



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1002](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1002)




### <a name="method-processDeleteImage"></a>processDeleteImage

```php
\ObjectModel|false AdminControllerCore::processDeleteImage()
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 915](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L915)




### <a name="method-processExport"></a>processExport

```php
mixed AdminControllerCore::processExport(string $text_delimiter)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 935](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L935)


#### Arguments
* $text_delimiter **string**



### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L743)




### <a name="method-processPosition"></a>processPosition

```php
\ObjectModel|false AdminControllerCore::processPosition()
```

Change object position



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1266)




### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters(integer|null $list_id)
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1286)


#### Arguments
* $list_id **integer|null**



### <a name="method-processSave"></a>processSave

```php
\ObjectModel|false|void AdminControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1048)




### <a name="method-processStatus"></a>processStatus

```php
\ObjectModel|false AdminControllerCore::processStatus()
```

Change object status (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1232)




### <a name="method-processUpdate"></a>processUpdate

```php
\ObjectModel|false|void AdminControllerCore::processUpdate()
```

Object update



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1115)




### <a name="method-processUpdateFields"></a>processUpdateFields

```php
\ObjectModel AdminControllerCore::processUpdateFields()
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1208)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions()
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1323)




### <a name="method-redirect"></a>redirect

```php
mixed AdminControllerCore::redirect()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1673](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L1673)




### <a name="method-refresh"></a>refresh

```php
boolean AdminControllerCore::refresh(string $file_to_refresh, string $external_file)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3983](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3983)


#### Arguments
* $file_to_refresh **string**
* $external_file **string**



### <a name="method-removeCSS"></a>removeCSS

```php
mixed ControllerCore::removeCSS(string|array $css_uri, string $css_media_type, boolean $check_path)
```

Removes CSS stylesheet(s) from the queued stylesheet list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L339)


#### Arguments
* $css_uri **string|array** - Path to CSS file or an array like: array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $check_path **boolean**



### <a name="method-removeJS"></a>removeJS

```php
mixed ControllerCore::removeJS(string|array $js_uri, boolean $check_path)
```

Removes JS file(s) from the queued JS file list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L405)


#### Arguments
* $js_uri **string|array** - Path to JS file or an array like: array(uri, ...)
* $check_path **boolean**



### <a name="method-renderDetails"></a>renderDetails

```php
string|false AdminControllerCore::renderDetails()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2415](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2415)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminStatusesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L257)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminControllerCore::renderKpis()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2490)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStatusesControllerCore::renderList()
```

Function used to render the list to display for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L209)




### <a name="method-renderModal"></a>renderModal

```php
string AdminControllerCore::renderModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2256)




### <a name="method-renderModulesList"></a>renderModulesList

```php
string AdminControllerCore::renderModulesList()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2271](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2271)




### <a name="method-renderOptions"></a>renderOptions

```php
string AdminControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2499)




### <a name="method-renderOrderReturnsForm"></a>renderOrderReturnsForm

```php
mixed AdminStatusesControllerCore::renderOrderReturnsForm()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L446)




### <a name="method-renderOrderStatusForm"></a>renderOrderStatusForm

```php
mixed AdminStatusesControllerCore::renderOrderStatusForm()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L419)




### <a name="method-renderView"></a>renderView

```php
string AdminControllerCore::renderView()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2392)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Starts the controller process (this method should not be overridden!)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L168)




### <a name="method-setDeprecatedMedia"></a>setDeprecatedMedia

```php
mixed AdminControllerCore::setDeprecatedMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2586)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

This function sets various display options for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2531](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2531)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2590](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L2590)




### <a name="method-setRedirectAfter"></a>setRedirectAfter

```php
mixed ControllerCore::setRedirectAfter($url)
```

Set $this->redirect_after that will be used by redirect() after the process



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L285)


#### Arguments
* $url **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate(string $template)
```

Sets template file for page content output



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L252)


#### Arguments
* $template **string**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent(array|string $content)
```

Renders controller templates and generates page content



* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L506)


#### Arguments
* $content **array|string** - Template file(s) to be rendered



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
boolean|void AdminControllerCore::updateAssoShop(integer $id_object)
```

Update the associations of shops



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3599](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3599)


#### Arguments
* $id_object **integer**



### <a name="method-uploadImage"></a>uploadImage

```php
boolean AdminControllerCore::uploadImage(integer $id, string $name, string $dir, string|boolean $ext, integer|null $width, integer|null $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3686)


#### Arguments
* $id **integer**
* $name **string**
* $dir **string**
* $ext **string|boolean**
* $width **integer|null**
* $height **integer|null**



### <a name="method-validateField"></a>validateField

```php
boolean AdminControllerCore::validateField(mixed $value, array $field)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3635](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3635)


#### Arguments
* $value **mixed**
* $field **array**



### <a name="method-validateRules"></a>validateRules

```php
mixed AdminControllerCore::validateRules(string|boolean $class_name)
```

Manage page display (form, list.

..)

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3382)


#### Arguments
* $class_name **string|boolean** - Allow to validate a different class than the current one



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L693)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3467](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/AdminController.php#L3467)



