Class AdminTranslationsControllerCore
=====================





* Class name: AdminTranslationsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTranslationsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L27)


Contents
--------

### Constants

* [DEFAULT_THEME_NAME](#constant-DEFAULT_THEME_NAME)
* [TEXTAREA_SIZED](#constant-TEXTAREA_SIZED)

### Properties

* [$all_iso_lang](#property-$all_iso_lang)
* [$ignore_folder](#property-$ignore_folder)
* [$lang_selected](#property-$lang_selected)
* [$languages](#property-$languages)
* [$link_lang_pack](#property-$link_lang_pack)
* [$missing_translations](#property-$missing_translations)
* [$modules_translations](#property-$modules_translations)
* [$post_limit_exceed](#property-$post_limit_exceed)
* [$theme_selected](#property-$theme_selected)
* [$themes](#property-$themes)
* [$total_expression](#property-$total_expression)
* [$translations_informations](#property-$translations_informations)
* [$type_selected](#property-$type_selected)
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
* [$object](#property-$object)
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
* [addNewTabs](#method-addNewTabs)
* [addPageHeaderToolBarModulesListButton](#method-addPageHeaderToolBarModulesListButton)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [addToolBarModulesListButton](#method-addToolBarModulesListButton)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxDie](#method-ajaxDie)
* [ajaxProcessGetModuleQuickView](#method-ajaxProcessGetModuleQuickView)
* [ajaxProcessOpenHelp](#method-ajaxProcessOpenHelp)
* [beforeAdd](#method-beforeAdd)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [changeModulesKeyTranslation](#method-changeModulesKeyTranslation)
* [checkAccess](#method-checkAccess)
* [checkAndAddMailsFiles](#method-checkAndAddMailsFiles)
* [checkAndAddThemesFiles](#method-checkAndAddThemesFiles)
* [checkDirAndCreate](#method-checkDirAndCreate)
* [checkIfKeyUseSprintf](#method-checkIfKeyUseSprintf)
* [checkToken](#method-checkToken)
* [checkTranslationFile](#method-checkTranslationFile)
* [cleanMailContent](#method-cleanMailContent)
* [clearModuleFiles](#method-clearModuleFiles)
* [copyFromPost](#method-copyFromPost)
* [copyMailFilesForAllLanguages](#method-copyMailFilesForAllLanguages)
* [createTemplate](#method-createTemplate)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayInformation](#method-displayInformation)
* [displayLimitPostWarning](#method-displayLimitPostWarning)
* [displayMailBlockHtml](#method-displayMailBlockHtml)
* [displayMailBlockTxt](#method-displayMailBlockTxt)
* [displayMailContent](#method-displayMailContent)
* [displayMailEditor](#method-displayMailEditor)
* [displayModuleOptions](#method-displayModuleOptions)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayToggleButton](#method-displayToggleButton)
* [displayWarning](#method-displayWarning)
* [exportTabs](#method-exportTabs)
* [fileExists](#method-fileExists)
* [filesListToPaths](#method-filesListToPaths)
* [fillModuleData](#method-fillModuleData)
* [filterTabModuleList](#method-filterTabModuleList)
* [filterToField](#method-filterToField)
* [filterTranslationFiles](#method-filterTranslationFiles)
* [findAndFillTranslations](#method-findAndFillTranslations)
* [findAndWriteTranslationsIntoFile](#method-findAndWriteTranslationsIntoFile)
* [getAllModuleFiles](#method-getAllModuleFiles)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getFileToParseByTypeTranslation](#method-getFileToParseByTypeTranslation)
* [getInformations](#method-getInformations)
* [getLanguages](#method-getLanguages)
* [getList](#method-getList)
* [getListModules](#method-getListModules)
* [getMailContent](#method-getMailContent)
* [getMailFiles](#method-getMailFiles)
* [getMailPattern](#method-getMailPattern)
* [getModuleTranslations](#method-getModuleTranslations)
* [getModulesHasMails](#method-getModulesHasMails)
* [getModulesHasPDF](#method-getModulesHasPDF)
* [getModulesList](#method-getModulesList)
* [getSelectedAssoShop](#method-getSelectedAssoShop)
* [getSubjectMail](#method-getSubjectMail)
* [getSubjectMailContent](#method-getSubjectMailContent)
* [getTemplateFormVars](#method-getTemplateFormVars)
* [getTemplateListVars](#method-getTemplateListVars)
* [getTemplateViewVars](#method-getTemplateViewVars)
* [getTinyMCEForMails](#method-getTinyMCEForMails)
* [getTranslationsInformations](#method-getTranslationsInformations)
* [init](#method-init)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initForm](#method-initForm)
* [initFormBack](#method-initFormBack)
* [initFormErrors](#method-initFormErrors)
* [initFormFields](#method-initFormFields)
* [initFormFront](#method-initFormFront)
* [initFormMails](#method-initFormMails)
* [initFormModules](#method-initFormModules)
* [initFormPDF](#method-initFormPDF)
* [initHeader](#method-initHeader)
* [initMain](#method-initMain)
* [initModal](#method-initModal)
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
* [listFiles](#method-listFiles)
* [loadObject](#method-loadObject)
* [myErrorHandler](#method-myErrorHandler)
* [parsePdfClass](#method-parsePdfClass)
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
* [recursiveGetModuleFiles](#method-recursiveGetModuleFiles)
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
* [renderView](#method-renderView)
* [run](#method-run)
* [setDeprecatedMedia](#method-setDeprecatedMedia)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [setTypeSelected](#method-setTypeSelected)
* [smartyOutputContent](#method-smartyOutputContent)
* [submitAddLang](#method-submitAddLang)
* [submitCopyLang](#method-submitCopyLang)
* [submitExportLang](#method-submitExportLang)
* [submitImportLang](#method-submitImportLang)
* [submitTranslationsMails](#method-submitTranslationsMails)
* [theme_exists](#method-theme_exists)
* [updateAssoShop](#method-updateAssoShop)
* [uploadImage](#method-uploadImage)
* [userParseFile](#method-userParseFile)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)
* [writeSubjectTranslationFile](#method-writeSubjectTranslationFile)
* [writeTranslationFile](#method-writeTranslationFile)


Constants
----------


### <a name="constant-DEFAULT_THEME_NAME"></a>DEFAULT_THEME_NAME

```php
const DEFAULT_THEME_NAME = _PS_DEFAULT_THEME_NAME_
```

Name of theme by default



* Source: [controllers/admin/AdminTranslationsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L30).


### <a name="constant-TEXTAREA_SIZED"></a>TEXTAREA_SIZED

```php
const TEXTAREA_SIZED = 70
```





* Source: [controllers/admin/AdminTranslationsController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L31).


Properties
----------


### <a name="property-$all_iso_lang"></a>$all_iso_lang

```php
protected array $all_iso_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L43).


### <a name="property-$ignore_folder"></a>$ignore_folder

```php
protected array $ignore_folder = array('.', '..', '.svn', '.git', '.htaccess', 'index.php')
```





* Visibility: **protected**
* This property is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L49).


### <a name="property-$lang_selected"></a>$lang_selected

```php
protected \Language $lang_selected
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L67).


### <a name="property-$languages"></a>$languages

```php
protected array $languages
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L55).


### <a name="property-$link_lang_pack"></a>$link_lang_pack

```php
protected string $link_lang_pack = 'http://www.prestashop.com/download/lang_packs/get_each_language_pack.php'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L34).


### <a name="property-$missing_translations"></a>$missing_translations

```php
protected integer $missing_translations
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L40).


### <a name="property-$modules_translations"></a>$modules_translations

```php
protected array $modules_translations = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L46).


### <a name="property-$post_limit_exceed"></a>$post_limit_exceed

```php
protected boolean $post_limit_exceed = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L70).


### <a name="property-$theme_selected"></a>$theme_selected

```php
protected string $theme_selected
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L61).


### <a name="property-$themes"></a>$themes

```php
protected array $themes
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L58).


### <a name="property-$total_expression"></a>$total_expression

```php
protected integer $total_expression
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L37).


### <a name="property-$translations_informations"></a>$translations_informations

```php
protected array $translations_informations = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L52).


### <a name="property-$type_selected"></a>$type_selected

```php
protected string $type_selected
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L64).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L75).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'ASC'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L76).


### <a name="property-$_default_pagination"></a>$_default_pagination

```php
protected integer $_default_pagination = 50
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L160).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L150).


### <a name="property-$_filterHaving"></a>$_filterHaving

```php
protected mixed $_filterHaving
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L151).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L225).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L228).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L250).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L219).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L37).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L126).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L144).


### <a name="property-$_listsql"></a>$_listsql

```php
protected string $_listsql = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L123).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L163).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L166).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300, 1000)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L157).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L258).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L216).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L154).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L222).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L248).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L172).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'duplicate', 'delete')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L169).


### <a name="property-$admin_webpath"></a>$admin_webpath

```php
public mixed $admin_webpath
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L291).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L39).


### <a name="property-$allow_export"></a>$allow_export

```php
protected mixed $allow_export = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L182).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public mixed $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L86).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L85).


### <a name="property-$bo_theme"></a>$bo_theme

```php
protected mixed $bo_theme
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L255).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L42).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L210).


### <a name="property-$breadcrumbs"></a>$breadcrumbs

```php
protected mixed $breadcrumbs
```

Current breadcrumb position as an array of tab names



* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L283).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L205).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L185).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L58).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L244).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L34).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L31).


### <a name="property-$controller_name"></a>$controller_name

```php
public \current $controller_name
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L275).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L30).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L38).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L237).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L249).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L94).


### <a name="property-$explicitSelect"></a>$explicitSelect

```php
protected string $explicitSelect = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L213).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L261).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L109).


### <a name="property-$fields_form_override"></a>$fields_form_override

```php
protected \override $fields_form_override
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L112).


### <a name="property-$fields_list"></a>$fields_list

```php
protected array $fields_list
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L100).


### <a name="property-$fields_options"></a>$fields_options

```php
protected array $fields_options = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L118).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L91).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L241).


### <a name="property-$filter_modules_list"></a>$filter_modules_list

```php
protected array $filter_modules_list = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L103).


### <a name="property-$helper"></a>$helper

```php
protected \Helper $helper
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L191).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L64).


### <a name="property-$id_object"></a>$id_object

```php
protected integer $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L270).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L54).


### <a name="property-$identifier_name"></a>$identifier_name

```php
protected mixed $identifier_name = 'name'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L55).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L264).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L33).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L230).


### <a name="property-$is_prestashop_up"></a>$is_prestashop_up

```php
protected mixed $is_prestashop_up = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3631](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3631).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L147).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L41).


### <a name="property-$list_id"></a>$list_id

```php
public mixed $list_id
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L51).


### <a name="property-$list_natives_modules"></a>$list_natives_modules

```php
protected mixed $list_natives_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L293).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L180).


### <a name="property-$list_partners_modules"></a>$list_partners_modules

```php
protected mixed $list_partners_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L294).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L97).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L175).


### <a name="property-$lite_display"></a>$lite_display

```php
protected mixed $lite_display = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L178).


### <a name="property-$logged_on_addons"></a>$logged_on_addons

```php
protected mixed $logged_on_addons = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L298).


### <a name="property-$meta_title"></a>$meta_title

```php
protected mixed $meta_title = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L44).


### <a name="property-$modals"></a>$modals

```php
public mixed $modals = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L296).


### <a name="property-$modules_list"></a>$modules_list

```php
protected array $modules_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L106).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L89).


### <a name="property-$multishop_context"></a>$multishop_context

```php
public mixed $multishop_context = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L277).


### <a name="property-$multishop_context_group"></a>$multishop_context_group

```php
public mixed $multishop_context_group = true
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L278).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L242).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L267).


### <a name="property-$page_header_toolbar_btn"></a>$page_header_toolbar_btn

```php
public mixed $page_header_toolbar_btn = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L288).


### <a name="property-$page_header_toolbar_title"></a>$page_header_toolbar_title

```php
public mixed $page_header_toolbar_title
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L287).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L29).


### <a name="property-$position_group_identifier"></a>$position_group_identifier

```php
protected mixed $position_group_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L234).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected string $position_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L233).


### <a name="property-$required_database"></a>$required_database

```php
public mixed $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L66).


### <a name="property-$required_fields"></a>$required_fields

```php
public array $required_fields = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L188).


### <a name="property-$row_hover"></a>$row_hover

```php
protected boolean $row_hover = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L246).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L120).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L72).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L35).


### <a name="property-$show_form_cancel_button"></a>$show_form_cancel_button

```php
public mixed $show_form_cancel_button
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L289).


### <a name="property-$show_page_header_toolbar"></a>$show_page_header_toolbar

```php
public mixed $show_page_header_toolbar = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L286).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L138).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L141).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L243).


### <a name="property-$submit_action"></a>$submit_action

```php
protected \override $submit_action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L115).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L61).


### <a name="property-$tab_modules_list"></a>$tab_modules_list

```php
protected mixed $tab_modules_list = array('default_list' => array(), 'slider_list' => array())
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L251).


### <a name="property-$table"></a>$table

```php
public string $table = 'configuration'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L49).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L46).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L69).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L132).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected boolean $toolbar_scroll = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L135).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L129).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L80).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L253).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L78).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L79).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L81).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public mixed $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L83).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L82).


### <a name="property-$translationsTab"></a>$translationsTab

```php
protected mixed $translationsTab = array()
```

Display modules list



* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3683](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3683).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L32).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L75).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L70).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L35).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L81).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L40).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L65).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L55).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L45).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L76).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L50).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L82).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L79).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L77).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTranslationsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L72)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3172)




### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type, integer $offset, boolean $check_path)
```

Add a new stylesheet in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L251)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $offset **integer**
* $check_path **boolean**



### <a name="method-addFiltersToBreadcrumbs"></a>addFiltersToBreadcrumbs

```php
mixed AdminControllerCore::addFiltersToBreadcrumbs()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 525](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L525)




### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri, boolean $check_path)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L319)


#### Arguments
* $js_uri **mixed**
* $check_path **boolean**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L371)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
mixed ControllerCore::addJqueryPlugin($name, null $folder, boolean $css)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L403)


#### Arguments
* $name **mixed**
* $folder **null**
* $css **boolean**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L382)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addMetaTitle"></a>addMetaTitle

```php
mixed AdminControllerCore::addMetaTitle(string $entry)
```

Add an entry to the meta title.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3989](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3989)


#### Arguments
* $entry **string** - New entry.



### <a name="method-addNewTabs"></a>addNewTabs

```php
mixed AdminTranslationsControllerCore::addNewTabs(array $iso_code, array $files)
```

Add new translations tabs by code ISO



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L615)


#### Arguments
* $iso_code **array**
* $files **array**



### <a name="method-addPageHeaderToolBarModulesListButton"></a>addPageHeaderToolBarModulesListButton

```php
mixed AdminControllerCore::addPageHeaderToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1896](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1896)




### <a name="method-addRowAction"></a>addRowAction

```php
mixed AdminControllerCore::addRowAction($action)
```

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1791](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1791)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1800](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1800)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-addToolBarModulesListButton"></a>addToolBarModulesListButton

```php
mixed AdminControllerCore::addToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1907](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1907)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3205)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3200)


#### Arguments
* $object **object** - Object
* $oldId **mixed**



### <a name="method-afterImageUpload"></a>afterImageUpload

```php
boolean AdminControllerCore::afterImageUpload()
```

Check rights to view the current tab



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3221)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3210)


#### Arguments
* $object **mixed**



### <a name="method-ajaxDie"></a>ajaxDie

```php
mixed ControllerCore::ajaxDie($value, $controller, $method)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L513)


#### Arguments
* $value **mixed**
* $controller **mixed**
* $method **mixed**



### <a name="method-ajaxProcessGetModuleQuickView"></a>ajaxProcessGetModuleQuickView

```php
mixed AdminControllerCore::ajaxProcessGetModuleQuickView()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3952](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3952)




### <a name="method-ajaxProcessOpenHelp"></a>ajaxProcessOpenHelp

```php
mixed AdminControllerCore::ajaxProcessOpenHelp()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3463](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3463)




### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(object $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3556](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3556)


#### Arguments
* $object **object** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3189)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3337](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3337)




### <a name="method-changeModulesKeyTranslation"></a>changeModulesKeyTranslation

```php
boolean AdminTranslationsControllerCore::changeModulesKeyTranslation(string $path, string $theme_from, string $theme_to)
```

Change the key translation to according it to theme name.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L393)


#### Arguments
* $path **string**
* $theme_from **string**
* $theme_to **string**



### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1441](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1441)




### <a name="method-checkAndAddMailsFiles"></a>checkAndAddMailsFiles

```php
mixed AdminTranslationsControllerCore::checkAndAddMailsFiles($iso_code, $files_list)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 489](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L489)


#### Arguments
* $iso_code **mixed**
* $files_list **mixed**



### <a name="method-checkAndAddThemesFiles"></a>checkAndAddThemesFiles

```php
mixed AdminTranslationsControllerCore::checkAndAddThemesFiles(array $files, array $themes_selected)
```

Move theme translations in selected themes



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L577)


#### Arguments
* $files **array**
* $themes_selected **array**



### <a name="method-checkDirAndCreate"></a>checkDirAndCreate

```php
boolean AdminTranslationsControllerCore::checkDirAndCreate(string $dest)
```

This method is only used by AdminTranslations::submitCopyLang().

It try to create folder in new theme.

When a translation file is copied for a module, its translation key is wrong.
We have to change the translation key and rewrite the file.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L245)


#### Arguments
* $dest **string** - file name



### <a name="method-checkIfKeyUseSprintf"></a>checkIfKeyUseSprintf

```php
array|boolean AdminTranslationsControllerCore::checkIfKeyUseSprintf($key)
```

Find sentence which use %d, %s, %%, %1$d, %1$s.

..

* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1723](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1723)


#### Arguments
* $key **mixed** - : english sentence



### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L583)




### <a name="method-checkTranslationFile"></a>checkTranslationFile

```php
mixed AdminTranslationsControllerCore::checkTranslationFile($content)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L658)


#### Arguments
* $content **mixed**



### <a name="method-cleanMailContent"></a>cleanMailContent

```php
mixed AdminTranslationsControllerCore::cleanMailContent($content, $lang, $title)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2446](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2446)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $title **mixed**



### <a name="method-clearModuleFiles"></a>clearModuleFiles

```php
array AdminTranslationsControllerCore::clearModuleFiles($files, string $type_clear, string $path)
```

Clear the list of module file by type (file or directory)



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 979](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L979)


#### Arguments
* $files **mixed** - : list of files
* $type_clear **string** - (file|directory)
* $path **string**



### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminControllerCore::copyFromPost($object, string $table)
```

Copy datas from $_POST to object



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3232)


#### Arguments
* $object **mixed**
* $table **string** - Object table



### <a name="method-copyMailFilesForAllLanguages"></a>copyMailFilesForAllLanguages

```php
mixed AdminTranslationsControllerCore::copyMailFilesForAllLanguages()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2619](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2619)




### <a name="method-createTemplate"></a>createTemplate

```php
\Template AdminControllerCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3582](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3582)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1498](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1498)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1477](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1477)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L212)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L207)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1585](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1585)


#### Arguments
* $msg **string**



### <a name="method-displayLimitPostWarning"></a>displayLimitPostWarning

```php
mixed AdminTranslationsControllerCore::displayLimitPostWarning($count)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1698](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1698)


#### Arguments
* $count **mixed**



### <a name="method-displayMailBlockHtml"></a>displayMailBlockHtml

```php
mixed AdminTranslationsControllerCore::displayMailBlockHtml(array $content, string $lang, string $url, string $mail_name, string $group_name, string|boolean $name_for_module)
```

Just build the html structure for display html mails.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2419](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2419)


#### Arguments
* $content **array** - with english and language needed contents
* $lang **string** - iso code of the needed language
* $url **string** - for the html page and displaying an outline
* $mail_name **string** - name of the file to translate (same for txt and html files)
* $group_name **string** - group name allow to distinguish each block of mail.
* $name_for_module **string|boolean** - is not false define add a name for disntiguish mails module



### <a name="method-displayMailBlockTxt"></a>displayMailBlockTxt

```php
mixed AdminTranslationsControllerCore::displayMailBlockTxt(array $content, string $lang, string $mail_name, string $group_name, string|boolean $name_for_module)
```

Just build the html structure for display txt mails



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2400](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2400)


#### Arguments
* $content **array** - with english and language needed contents
* $lang **string** - iso code of the needed language
* $mail_name **string** - name of the file to translate (same for txt and html files)
* $group_name **string** - group name allow to distinguish each block of mail.
* $name_for_module **string|boolean** - is not false define add a name for disntiguish mails module



### <a name="method-displayMailContent"></a>displayMailContent

```php
mixed AdminTranslationsControllerCore::displayMailContent(array $mails, array $all_subject_mail, \Language $obj_lang, string $id_html, string $title, string|boolean $name_for_module)
```

Display mails in html format.

This was create for factorize the html displaying

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2279)


#### Arguments
* $mails **array**
* $all_subject_mail **array**
* $obj_lang **[Language](class.LanguageCore.md)**
* $id_html **string** - use for set html id attribute for the block
* $title **string** - Set the title for the block
* $name_for_module **string|boolean** - is not false define add a name for disntiguish mails module



### <a name="method-displayMailEditor"></a>displayMailEditor

```php
mixed AdminTranslationsControllerCore::displayMailEditor($content, $lang, $url, $mail_name, $group_name, $name_for_module)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2438](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2438)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $url **mixed**
* $mail_name **mixed**
* $group_name **mixed**
* $name_for_module **mixed**



### <a name="method-displayModuleOptions"></a>displayModuleOptions

```php
mixed AdminControllerCore::displayModuleOptions($module, $output_type, $back)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3684](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3684)


#### Arguments
* $module **mixed**
* $output_type **mixed**
* $back **mixed**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1473](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1473)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminControllerCore::displayRequiredFields()
```

prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3564](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3564)




### <a name="method-displayToggleButton"></a>displayToggleButton

```php
mixed AdminTranslationsControllerCore::displayToggleButton($closed)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1682](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1682)


#### Arguments
* $closed **mixed**



### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1575)


#### Arguments
* $msg **string**



### <a name="method-exportTabs"></a>exportTabs

```php
mixed AdminTranslationsControllerCore::exportTabs()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L408)




### <a name="method-fileExists"></a>fileExists

```php
mixed AdminTranslationsControllerCore::fileExists()
```

Include file $dir/$file and return the var $var declared in it.

This create the file if not exists

return array : translations

* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1663](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1663)




### <a name="method-filesListToPaths"></a>filesListToPaths

```php
mixed AdminTranslationsControllerCore::filesListToPaths($list)
```

Turn the list returned by
AdminTranslationsController::filterTranslationFiles()
into a list of paths that can be passed to
Archive_Tar::extractList()



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L827)


#### Arguments
* $list **mixed**



### <a name="method-fillModuleData"></a>fillModuleData

```php
mixed AdminControllerCore::fillModuleData($module, $output_type, $back)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3640](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3640)


#### Arguments
* $module **mixed**
* $output_type **mixed**
* $back **mixed**



### <a name="method-filterTabModuleList"></a>filterTabModuleList

```php
mixed AdminControllerCore::filterTabModuleList()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1918](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1918)




### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1460](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1460)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-filterTranslationFiles"></a>filterTranslationFiles

```php
mixed AdminTranslationsControllerCore::filterTranslationFiles($list)
```

Filter the translation files contained in a .gzip pack
and return only the ones that we want.

Right now the function only needs to check that
the modules for which we want to add translations
are present on the shop (installed or not).

$list is the output of Archive_Tar::listContent()

* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 803](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L803)


#### Arguments
* $list **mixed**



### <a name="method-findAndFillTranslations"></a>findAndFillTranslations

```php
void AdminTranslationsControllerCore::findAndFillTranslations(array $files, string $theme_name, string $module_name, string|boolean $dir)
```

This method get translation for each files of a module,
compare with global $_MODULES array and fill AdminTranslations::modules_translations array
With key as English sentences and values as their iso code translations.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1012](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1012)


#### Arguments
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-findAndWriteTranslationsIntoFile"></a>findAndWriteTranslationsIntoFile

```php
void AdminTranslationsControllerCore::findAndWriteTranslationsIntoFile(string $file_name, array $files, string $theme_name, string $module_name, string|boolean $dir)
```

This method check each file (tpl or php file), get its sentences to translate,
compare with posted values and write in iso code translation file.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L899)


#### Arguments
* $file_name **string**
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-getAllModuleFiles"></a>getAllModuleFiles

```php
mixed AdminTranslationsControllerCore::getAllModuleFiles(array $modules, string $root_dir, string $lang, boolean $is_default)
```

This method get translation in each translations file.

The file depend on $lang param.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2815](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2815)


#### Arguments
* $modules **array** - list of modules
* $root_dir **string** - path where it get each modules
* $lang **string** - iso code of choosen language to translate
* $is_default **boolean** - set it if modules are located in root/prestashop/modules folder
              This allow to distinguish overrided prestashop theme and original module



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L133)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getFieldValue"></a>getFieldValue

```php
string AdminControllerCore::getFieldValue(object $obj, string $key, integer $id_lang)
```

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3086](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3086)


#### Arguments
* $obj **object** - Object
* $key **string** - Field name
* $id_lang **integer** - Language id (optional)



### <a name="method-getFieldsValue"></a>getFieldsValue

```php
array AdminControllerCore::getFieldsValue(object $obj)
```

Return the list of fields value



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3036](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3036)


#### Arguments
* $obj **object** - Object



### <a name="method-getFileToParseByTypeTranslation"></a>getFileToParseByTypeTranslation

```php
array AdminTranslationsControllerCore::getFileToParseByTypeTranslation()
```

Get list of files which must be parsed by directory and by type of translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1075](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1075)




### <a name="method-getInformations"></a>getInformations

```php
mixed AdminTranslationsControllerCore::getInformations()
```

Get all informations on : languages, theme and the translation type.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1324](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1324)




### <a name="method-getLanguages"></a>getLanguages

```php
mixed AdminControllerCore::getLanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3008](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3008)




### <a name="method-getList"></a>getList

```php
mixed AdminControllerCore::getList(integer $id_lang, string $order_by, $order_way, integer $start, integer $limit, $id_lang_shop)
```

Get the current objects' list form the database



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2752](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2752)


#### Arguments
* $id_lang **integer** - Language used for display
* $order_by **string** - ORDER BY clause
* $order_way **mixed**
* $start **integer** - Offset in LIMIT clause
* $limit **integer** - Row count in LIMIT clause
* $id_lang_shop **mixed**



### <a name="method-getListModules"></a>getListModules

```php
array AdminTranslationsControllerCore::getListModules()
```

Check if directory and file exist and return an list of modules



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2015](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2015)




### <a name="method-getMailContent"></a>getMailContent

```php
array AdminTranslationsControllerCore::getMailContent(string $dir, string $file)
```

Get content of the mail file.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2258)


#### Arguments
* $dir **string**
* $file **string**



### <a name="method-getMailFiles"></a>getMailFiles

```php
array AdminTranslationsControllerCore::getMailFiles(string $dir, string $group_name)
```

Get each informations for each mails found in the folder $dir.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2195)


#### Arguments
* $dir **string**
* $group_name **string**



### <a name="method-getMailPattern"></a>getMailPattern

```php
mixed AdminTranslationsControllerCore::getMailPattern()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1538](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1538)




### <a name="method-getModuleTranslations"></a>getModuleTranslations

```php
mixed AdminTranslationsControllerCore::getModuleTranslations()
```

This method merge each arrays of modules translation in the array of modules translations



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L220)




### <a name="method-getModulesHasMails"></a>getModulesHasMails

```php
array AdminTranslationsControllerCore::getModulesHasMails($with_module_name)
```

Check in each module if contains mails folder.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2472](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2472)


#### Arguments
* $with_module_name **mixed**



### <a name="method-getModulesHasPDF"></a>getModulesHasPDF

```php
array AdminTranslationsControllerCore::getModulesHasPDF($classes)
```

Check in each module if contains pdf folder.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2505](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2505)


#### Arguments
* $classes **mixed**



### <a name="method-getModulesList"></a>getModulesList

```php
mixed AdminControllerCore::getModulesList($filter_modules_list)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2970](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2970)


#### Arguments
* $filter_modules_list **mixed**



### <a name="method-getSelectedAssoShop"></a>getSelectedAssoShop

```php
array AdminControllerCore::getSelectedAssoShop(string $table)
```

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3267)


#### Arguments
* $table **string**



### <a name="method-getSubjectMail"></a>getSubjectMail

```php
array AdminTranslationsControllerCore::getSubjectMail($dir, $file, $subject_mail)
```

Get list of subjects of mails



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2681](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2681)


#### Arguments
* $dir **mixed**
* $file **mixed**
* $subject_mail **mixed**



### <a name="method-getSubjectMailContent"></a>getSubjectMailContent

```php
array AdminTranslationsControllerCore::getSubjectMailContent($directory)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2724](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2724)


#### Arguments
* $directory **mixed** - : name of directory



### <a name="method-getTemplateFormVars"></a>getTemplateFormVars

```php
mixed AdminControllerCore::getTemplateFormVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2228)




### <a name="method-getTemplateListVars"></a>getTemplateListVars

```php
mixed AdminControllerCore::getTemplateListVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2139)




### <a name="method-getTemplateViewVars"></a>getTemplateViewVars

```php
mixed AdminControllerCore::getTemplateViewVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2159)




### <a name="method-getTinyMCEForMails"></a>getTinyMCEForMails

```php
mixed AdminTranslationsControllerCore::getTinyMCEForMails($iso_lang)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2534](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2534)


#### Arguments
* $iso_lang **mixed**



### <a name="method-getTranslationsInformations"></a>getTranslationsInformations

```php
mixed AdminTranslationsControllerCore::getTranslationsInformations()
```

Get all translations informations for all type of translations

array(
	'type' => array(
		'name' => string : title for the translation type,
		'var' => string : name of var for the translation file,
		'dir' => string : dir of translation file
		'file' => string : file name of translation file
	)
)

* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1266)




### <a name="method-init"></a>init

```php
mixed AdminControllerCore::init()
```

Init context and dependencies, handles POST and GET



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2385](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2385)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminControllerCore::initBreadcrumbs($tab_id, $tabs)
```

Set breadcrumbs array for the controller page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L419)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminTranslationsControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L93)




### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1966](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1966)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1974](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1974)




### <a name="method-initForm"></a>initForm

```php
\call AdminTranslationsControllerCore::initForm($method_name)
```

This function create vars by default and call the good method for generate form



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L125)


#### Arguments
* $method_name **mixed**



### <a name="method-initFormBack"></a>initFormBack

```php
mixed AdminTranslationsControllerCore::initFormBack()
```

This method generate the form for back translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1823](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1823)




### <a name="method-initFormErrors"></a>initFormErrors

```php
mixed AdminTranslationsControllerCore::initFormErrors()
```

This method generate the form for errors translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2034](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2034)




### <a name="method-initFormFields"></a>initFormFields

```php
mixed AdminTranslationsControllerCore::initFormFields()
```

This method generate the form for fields translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2095](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2095)




### <a name="method-initFormFront"></a>initFormFront

```php
mixed AdminTranslationsControllerCore::initFormFront()
```

This method generate the form for front translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1733](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1733)




### <a name="method-initFormMails"></a>initFormMails

```php
mixed AdminTranslationsControllerCore::initFormMails($no_display)
```

This method generate the form for mails translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2553](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2553)


#### Arguments
* $no_display **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminTranslationsControllerCore::initFormModules()
```

This method generate the form for modules translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2865](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2865)




### <a name="method-initFormPDF"></a>initFormPDF

```php
mixed AdminTranslationsControllerCore::initFormPDF()
```

This method generate the form for PDF translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2933](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2933)




### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1593](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1593)




### <a name="method-initMain"></a>initMain

```php
mixed AdminTranslationsControllerCore::initMain()
```

Generate the Main page



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L175)




### <a name="method-initModal"></a>initModal

```php
mixed AdminControllerCore::initModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1997](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1997)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1286)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminControllerCore::initProcess()
```

Retrieve GET and POST value and translate them to actions



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2540](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2540)




### <a name="method-initShopContext"></a>initShopContext

```php
mixed AdminControllerCore::initShopContext()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2465](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2465)




### <a name="method-initTabModuleList"></a>initTabModuleList

```php
mixed AdminControllerCore::initTabModuleList()
```

init tab modules list and add button in toolbar



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1871](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1871)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminTranslationsControllerCore::initToolbar()
```

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L155)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
void AdminControllerCore::initToolbarTitle()
```

set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 499](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L499)




### <a name="method-isCached"></a>isCached

```php
mixed ControllerCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 471](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L471)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isFresh"></a>isFresh

```php
mixed AdminControllerCore::isFresh($file, $timeout)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3623)


#### Arguments
* $file **mixed**
* $timeout **mixed**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L425)




### <a name="method-jsonConfirmation"></a>jsonConfirmation

```php
mixed AdminControllerCore::jsonConfirmation($message)
```

Shortcut to set up a json success payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3602)


#### Arguments
* $message **mixed** - success message



### <a name="method-jsonError"></a>jsonError

```php
mixed AdminControllerCore::jsonError($message)
```

Shortcut to set up a json error payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3615)


#### Arguments
* $message **mixed** - error message



### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2372](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2372)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-listFiles"></a>listFiles

```php
mixed AdminTranslationsControllerCore::listFiles($dir, $list, $file_ext)
```

recursively list files in directory $dir



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 3021](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L3021)


#### Arguments
* $dir **mixed**
* $list **mixed**
* $file_ext **mixed**



### <a name="method-loadObject"></a>loadObject

```php
object|boolean AdminControllerCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1410](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1410)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-myErrorHandler"></a>myErrorHandler

```php
mixed ControllerCore::myErrorHandler($errno, $errstr, $errfile, $errline)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L479)


#### Arguments
* $errno **mixed**
* $errstr **mixed**
* $errfile **mixed**
* $errline **mixed**



### <a name="method-parsePdfClass"></a>parsePdfClass

```php
array AdminTranslationsControllerCore::parsePdfClass(string $file_path, string $file_type, $lang_array, string $tab, array $tabs_array, $count_missing)
```

Parse PDF class



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2904](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2904)


#### Arguments
* $file_path **string** - file to parse
* $file_type **string** - type of file
* $lang_array **mixed**
* $tab **string** - name to use with the md5 key
* $tabs_array **array**
* $count_missing **mixed**



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3347)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminTranslationsControllerCore::postProcess()
```

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1423](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1423)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminControllerCore::processAdd()
```

Object creation



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L925)




### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
mixed AdminControllerCore::processBulkAffectZone()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3532](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3532)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminControllerCore::processBulkDelete()
```

Delete multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3405](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3405)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
boolean AdminControllerCore::processBulkDisableSelection()
```

Disable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3507](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3507)




### <a name="method-processBulkEnableSelection"></a>processBulkEnableSelection

```php
boolean AdminControllerCore::processBulkEnableSelection()
```

Enable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3497](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3497)




### <a name="method-processBulkStatusSelection"></a>processBulkStatusSelection

```php
boolean AdminControllerCore::processBulkStatusSelection($status)
```

Toggle status of multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3517](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3517)


#### Arguments
* $status **mixed**



### <a name="method-processDelete"></a>processDelete

```php
mixed AdminControllerCore::processDelete()
```

Object Delete



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 862](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L862)




### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage()
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L781)




### <a name="method-processExport"></a>processExport

```php
mixed AdminControllerCore::processExport($text_delimiter)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 798](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L798)


#### Arguments
* $text_delimiter **mixed**



### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L610)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminControllerCore::processPosition()
```

Change object position



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1114)




### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters($list_id)
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1135)


#### Arguments
* $list_id **mixed**



### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L911)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminControllerCore::processStatus()
```

Change object status (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1084](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1084)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminControllerCore::processUpdate()
```

Object update



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L975)




### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields()
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1067](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1067)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions()
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L1167)




### <a name="method-recursiveGetModuleFiles"></a>recursiveGetModuleFiles

```php
mixed AdminTranslationsControllerCore::recursiveGetModuleFiles(string $path, array $array_files, string $module_name, string $lang_file, boolean $is_default)
```

This get files to translate in module directory.

Recursive method allow to get each files for a module no matter his depth.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2782](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2782)


#### Arguments
* $path **string** - directory path to scan
* $array_files **array** - by reference - array which saved files to parse.
* $module_name **string** - module name
* $lang_file **string** - full path of translation file
* $is_default **boolean**



### <a name="method-redirect"></a>redirect

```php
mixed AdminTranslationsControllerCore::redirect(boolean $save_and_stay, boolean $conf)
```

This method redirect in the translation main page or in the translation page



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1528](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1528)


#### Arguments
* $save_and_stay **boolean** - : true if the user has clicked on the button &quot;save and stay&quot;
* $conf **boolean** - : id of confirmation message



### <a name="method-refresh"></a>refresh

```php
mixed AdminControllerCore::refresh($file_to_refresh, $external_file)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3632](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3632)


#### Arguments
* $file_to_refresh **mixed**
* $external_file **mixed**



### <a name="method-removeCSS"></a>removeCSS

```php
mixed ControllerCore::removeCSS($css_uri, $css_media_type, $check_path)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L285)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**
* $check_path **mixed**



### <a name="method-removeJS"></a>removeJS

```php
mixed ControllerCore::removeJS($js_uri, $check_path)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L343)


#### Arguments
* $js_uri **mixed**
* $check_path **mixed**



### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminControllerCore::renderDetails()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2167)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminControllerCore::renderForm()
```

Function used to render the form for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2175)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminTranslationsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1372](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1372)




### <a name="method-renderList"></a>renderList

```php
mixed AdminControllerCore::renderList()
```

Function used to render the list to display for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2084](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2084)




### <a name="method-renderModal"></a>renderModal

```php
mixed AdminControllerCore::renderModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2036](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2036)




### <a name="method-renderModulesList"></a>renderModulesList

```php
mixed AdminControllerCore::renderModulesList()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2050](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2050)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2240)




### <a name="method-renderView"></a>renderView

```php
mixed AdminControllerCore::renderView()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2147)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L161)




### <a name="method-setDeprecatedMedia"></a>setDeprecatedMedia

```php
mixed AdminControllerCore::setDeprecatedMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2323](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2323)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2272](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2272)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2328](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L2328)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L217)


#### Arguments
* $template **mixed**



### <a name="method-setTypeSelected"></a>setTypeSelected

```php
mixed AdminTranslationsControllerCore::setTypeSelected($type_selected)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L84)


#### Arguments
* $type_selected **mixed**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent($content)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/Controller.php#L430)


#### Arguments
* $content **mixed**



### <a name="method-submitAddLang"></a>submitAddLang

```php
mixed AdminTranslationsControllerCore::submitAddLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L835)




### <a name="method-submitCopyLang"></a>submitCopyLang

```php
mixed AdminTranslationsControllerCore::submitCopyLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L342)




### <a name="method-submitExportLang"></a>submitExportLang

```php
mixed AdminTranslationsControllerCore::submitExportLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L459)




### <a name="method-submitImportLang"></a>submitImportLang

```php
mixed AdminTranslationsControllerCore::submitImportLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L697)




### <a name="method-submitTranslationsMails"></a>submitTranslationsMails

```php
mixed AdminTranslationsControllerCore::submitTranslationsMails()
```

This method is used to write translation for mails.

This writes subject translation files
(in root/mails/lang_choosen/lang.php or root/_PS_THEMES_DIR_/mails/lang_choosen/lang.php)
and mails files.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1559](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1559)




### <a name="method-theme_exists"></a>theme_exists

```php
mixed AdminTranslationsControllerCore::theme_exists($theme)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 3040](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L3040)


#### Arguments
* $theme **mixed**



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminControllerCore::updateAssoShop(integer $id_object)
```

Update the associations of shops



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3290](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3290)


#### Arguments
* $id_object **integer**



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3358](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3358)


#### Arguments
* $id **mixed**
* $name **mixed**
* $dir **mixed**
* $ext **mixed**
* $width **mixed**
* $height **mixed**



### <a name="method-userParseFile"></a>userParseFile

```php
\return AdminTranslationsControllerCore::userParseFile($content, $type_translation, string|boolean $type_file, string $module_name)
```

This method parse a file by type of translation and type file



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L1184)


#### Arguments
* $content **mixed**
* $type_translation **mixed** - : front, back, errors, modules...
* $type_file **string|boolean** - : (tpl|php)
* $module_name **string** - : name of the module



### <a name="method-validateField"></a>validateField

```php
mixed AdminControllerCore::validateField($value, $field)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3316)


#### Arguments
* $value **mixed**
* $field **mixed**



### <a name="method-validateRules"></a>validateRules

```php
mixed AdminControllerCore::validateRules($class_name)
```

Manage page display (form, list.

..)

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3101)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 570](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L570)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/controller/AdminController.php#L3179)




### <a name="method-writeSubjectTranslationFile"></a>writeSubjectTranslationFile

```php
mixed AdminTranslationsControllerCore::writeSubjectTranslationFile($sub, $path)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2747](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L2747)


#### Arguments
* $sub **mixed**
* $path **mixed**



### <a name="method-writeTranslationFile"></a>writeTranslationFile

```php
mixed AdminTranslationsControllerCore::writeTranslationFile(boolean $override_file)
```

Read the Post var and write the translation file.

This method overwrites the old translation file.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminTranslationsController.php#L270)


#### Arguments
* $override_file **boolean** - : set true if this file is a override


