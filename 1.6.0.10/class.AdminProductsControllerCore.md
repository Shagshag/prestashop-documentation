Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L27)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$available_tabs](#property-$available_tabs)
* [$available_tabs_lang](#property-$available_tabs_lang)
* [$default_tab](#property-$default_tab)
* [$id_current_category](#property-$id_current_category)
* [$max_file_size](#property-$max_file_size)
* [$max_image_size](#property-$max_image_size)
* [$position_identifier](#property-$position_identifier)
* [$submitted_tabs](#property-$submitted_tabs)
* [$tab_display](#property-$tab_display)
* [$tab_display_module](#property-$tab_display_module)
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
* [_applyTaxToEcotax](#method-_applyTaxToEcotax)
* [_childValidation](#method-_childValidation)
* [_cleanMetaKeywords](#method-_cleanMetaKeywords)
* [_displayDraftWarning](#method-_displayDraftWarning)
* [_displayLabelField](#method-_displayLabelField)
* [_displayLabelFields](#method-_displayLabelFields)
* [_displaySpecificPriceModificationForm](#method-_displaySpecificPriceModificationForm)
* [_displayUnavailableProductWarning](#method-_displayUnavailableProductWarning)
* [_getCustomizationFieldIds](#method-_getCustomizationFieldIds)
* [_getFinalPrice](#method-_getFinalPrice)
* [_removeTaxFromEcotax](#method-_removeTaxFromEcotax)
* [_validateSpecificPrice](#method-_validateSpecificPrice)
* [addCSS](#method-addCSS)
* [addCarriers](#method-addCarriers)
* [addFiltersToBreadcrumbs](#method-addFiltersToBreadcrumbs)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addPageHeaderToolBarModulesListButton](#method-addPageHeaderToolBarModulesListButton)
* [addProductImage](#method-addProductImage)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [addToolBarModulesListButton](#method-addToolBarModulesListButton)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcessAddAttachment](#method-ajaxProcessAddAttachment)
* [ajaxProcessCheckProductName](#method-ajaxProcessCheckProductName)
* [ajaxProcessDefaultProductAttribute](#method-ajaxProcessDefaultProductAttribute)
* [ajaxProcessDeleteProductAttribute](#method-ajaxProcessDeleteProductAttribute)
* [ajaxProcessDeleteProductImage](#method-ajaxProcessDeleteProductImage)
* [ajaxProcessDeleteSpecificPrice](#method-ajaxProcessDeleteSpecificPrice)
* [ajaxProcessEditProductAttribute](#method-ajaxProcessEditProductAttribute)
* [ajaxProcessGetCountriesOptions](#method-ajaxProcessGetCountriesOptions)
* [ajaxProcessGetCurrenciesOptions](#method-ajaxProcessGetCurrenciesOptions)
* [ajaxProcessGetGroupsOptions](#method-ajaxProcessGetGroupsOptions)
* [ajaxProcessGetModuleQuickView](#method-ajaxProcessGetModuleQuickView)
* [ajaxProcessOpenHelp](#method-ajaxProcessOpenHelp)
* [ajaxProcessProductManufacturers](#method-ajaxProcessProductManufacturers)
* [ajaxProcessProductQuantity](#method-ajaxProcessProductQuantity)
* [ajaxProcessPublishProduct](#method-ajaxProcessPublishProduct)
* [ajaxProcessUpdateCover](#method-ajaxProcessUpdateCover)
* [ajaxProcessUpdateImagePosition](#method-ajaxProcessUpdateImagePosition)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [ajaxProcessUpdateProductImageShopAsso](#method-ajaxProcessUpdateProductImageShopAsso)
* [ajaxProcessaddProductImage](#method-ajaxProcessaddProductImage)
* [beforeAdd](#method-beforeAdd)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [checkAccess](#method-checkAccess)
* [checkFeatures](#method-checkFeatures)
* [checkProduct](#method-checkProduct)
* [checkToken](#method-checkToken)
* [copyFromPost](#method-copyFromPost)
* [copyImage](#method-copyImage)
* [createTemplate](#method-createTemplate)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayInformation](#method-displayInformation)
* [displayModuleOptions](#method-displayModuleOptions)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayWarning](#method-displayWarning)
* [fillModuleData](#method-fillModuleData)
* [filterTabModuleList](#method-filterTabModuleList)
* [filterToField](#method-filterToField)
* [getCarrierList](#method-getCarrierList)
* [getCombinationImagesJS](#method-getCombinationImagesJS)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getL](#method-getL)
* [getLanguages](#method-getLanguages)
* [getList](#method-getList)
* [getModulesList](#method-getModulesList)
* [getPackItems](#method-getPackItems)
* [getPreviewUrl](#method-getPreviewUrl)
* [getQuantities](#method-getQuantities)
* [getSelectedAssoShop](#method-getSelectedAssoShop)
* [haveThisAccessory](#method-haveThisAccessory)
* [init](#method-init)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initFormAssociations](#method-initFormAssociations)
* [initFormAttachments](#method-initFormAttachments)
* [initFormAttributes](#method-initFormAttributes)
* [initFormCombinations](#method-initFormCombinations)
* [initFormCustomization](#method-initFormCustomization)
* [initFormFeatures](#method-initFormFeatures)
* [initFormImages](#method-initFormImages)
* [initFormInformations](#method-initFormInformations)
* [initFormModules](#method-initFormModules)
* [initFormPack](#method-initFormPack)
* [initFormPrices](#method-initFormPrices)
* [initFormQuantities](#method-initFormQuantities)
* [initFormSeo](#method-initFormSeo)
* [initFormShipping](#method-initFormShipping)
* [initFormSuppliers](#method-initFormSuppliers)
* [initFormVirtualProduct](#method-initFormVirtualProduct)
* [initFormWarehouses](#method-initFormWarehouses)
* [initHeader](#method-initHeader)
* [initModal](#method-initModal)
* [initPack](#method-initPack)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initShopContext](#method-initShopContext)
* [initTabModuleList](#method-initTabModuleList)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [isCached](#method-isCached)
* [isFresh](#method-isFresh)
* [isProductFieldUpdated](#method-isProductFieldUpdated)
* [isTabSubmitted](#method-isTabSubmitted)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [jsonConfirmation](#method-jsonConfirmation)
* [jsonError](#method-jsonError)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [myErrorHandler](#method-myErrorHandler)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processAttachments](#method-processAttachments)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [processBulkDelete](#method-processBulkDelete)
* [processBulkDisableSelection](#method-processBulkDisableSelection)
* [processBulkEnableSelection](#method-processBulkEnableSelection)
* [processBulkStatusSelection](#method-processBulkStatusSelection)
* [processCustomizationConfiguration](#method-processCustomizationConfiguration)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processDeleteVirtualProduct](#method-processDeleteVirtualProduct)
* [processDuplicate](#method-processDuplicate)
* [processExport](#method-processExport)
* [processFeatures](#method-processFeatures)
* [processFilter](#method-processFilter)
* [processImage](#method-processImage)
* [processPosition](#method-processPosition)
* [processPriceAddition](#method-processPriceAddition)
* [processPricesModification](#method-processPricesModification)
* [processProductAttribute](#method-processProductAttribute)
* [processProductCustomization](#method-processProductCustomization)
* [processResetFilters](#method-processResetFilters)
* [processSave](#method-processSave)
* [processSpecificPricePriorities](#method-processSpecificPricePriorities)
* [processStatus](#method-processStatus)
* [processSuppliers](#method-processSuppliers)
* [processUpdate](#method-processUpdate)
* [processUpdateFields](#method-processUpdateFields)
* [processUpdateOptions](#method-processUpdateOptions)
* [processWarehouses](#method-processWarehouses)
* [recurseCategoryForInclude](#method-recurseCategoryForInclude)
* [redirect](#method-redirect)
* [refresh](#method-refresh)
* [removeCSS](#method-removeCSS)
* [removeJS](#method-removeJS)
* [renderDetails](#method-renderDetails)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderListAttributes](#method-renderListAttributes)
* [renderModal](#method-renderModal)
* [renderModulesList](#method-renderModulesList)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)
* [run](#method-run)
* [setDeprecatedMedia](#method-setDeprecatedMedia)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [updateAccessories](#method-updateAccessories)
* [updateAssoShop](#method-updateAssoShop)
* [updateDownloadProduct](#method-updateDownloadProduct)
* [updatePackItems](#method-updatePackItems)
* [updateTags](#method-updateTags)
* [uploadImage](#method-uploadImage)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)




Properties
----------


### <a name="property-$_category"></a>$_category

```php
protected mixed $_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L35).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected array $available_tabs = array()
```

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L47).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L51).


### <a name="property-$default_tab"></a>$default_tab

```php
protected mixed $default_tab = 'Informations'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L49).


### <a name="property-$id_current_category"></a>$id_current_category

```php
protected mixed $id_current_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L57).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected integer $max_file_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L32).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected mixed $max_image_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L33).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_product'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L53).


### <a name="property-$submitted_tabs"></a>$submitted_tabs

```php
protected mixed $submitted_tabs
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L55).


### <a name="property-$tab_display"></a>$tab_display

```php
protected string $tab_display
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L39).


### <a name="property-$tab_display_module"></a>$tab_display_module

```php
protected mixed $tab_display_module
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L40).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L75).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'ASC'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L76).


### <a name="property-$_default_pagination"></a>$_default_pagination

```php
protected integer $_default_pagination = 50
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L160).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L150).


### <a name="property-$_filterHaving"></a>$_filterHaving

```php
protected mixed $_filterHaving
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L151).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L225).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L228).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L250).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L219).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L37).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L126).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L144).


### <a name="property-$_listsql"></a>$_listsql

```php
protected string $_listsql = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L123).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L163).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L166).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300, 1000)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L157).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L258).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L216).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L154).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L222).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L248).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L172).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'duplicate', 'delete')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L169).


### <a name="property-$admin_webpath"></a>$admin_webpath

```php
public mixed $admin_webpath
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L291).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L39).


### <a name="property-$allow_export"></a>$allow_export

```php
protected mixed $allow_export = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L182).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public mixed $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L86).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L85).


### <a name="property-$bo_theme"></a>$bo_theme

```php
protected mixed $bo_theme
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L255).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L42).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L210).


### <a name="property-$breadcrumbs"></a>$breadcrumbs

```php
protected mixed $breadcrumbs
```

Current breadcrumb position as an array of tab names



* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L283).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L205).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L185).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L58).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L244).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L34).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L31).


### <a name="property-$controller_name"></a>$controller_name

```php
public \current $controller_name
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L275).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L30).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L38).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L237).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L249).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L94).


### <a name="property-$explicitSelect"></a>$explicitSelect

```php
protected string $explicitSelect = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L213).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L261).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L109).


### <a name="property-$fields_form_override"></a>$fields_form_override

```php
protected \override $fields_form_override
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L112).


### <a name="property-$fields_list"></a>$fields_list

```php
protected array $fields_list
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L100).


### <a name="property-$fields_options"></a>$fields_options

```php
protected array $fields_options = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L118).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L91).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L241).


### <a name="property-$filter_modules_list"></a>$filter_modules_list

```php
protected array $filter_modules_list = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L103).


### <a name="property-$helper"></a>$helper

```php
protected \Helper $helper
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L191).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L64).


### <a name="property-$id_object"></a>$id_object

```php
protected integer $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L270).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L54).


### <a name="property-$identifier_name"></a>$identifier_name

```php
protected mixed $identifier_name = 'name'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L55).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L264).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L33).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L230).


### <a name="property-$is_prestashop_up"></a>$is_prestashop_up

```php
protected mixed $is_prestashop_up = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3544](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3544).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L147).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L41).


### <a name="property-$list_id"></a>$list_id

```php
public mixed $list_id
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L51).


### <a name="property-$list_natives_modules"></a>$list_natives_modules

```php
protected mixed $list_natives_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L293).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L180).


### <a name="property-$list_partners_modules"></a>$list_partners_modules

```php
protected mixed $list_partners_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L294).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L97).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L175).


### <a name="property-$lite_display"></a>$lite_display

```php
protected mixed $lite_display = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L178).


### <a name="property-$logged_on_addons"></a>$logged_on_addons

```php
protected mixed $logged_on_addons = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L298).


### <a name="property-$meta_title"></a>$meta_title

```php
protected mixed $meta_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L44).


### <a name="property-$modals"></a>$modals

```php
public mixed $modals = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L296).


### <a name="property-$modules_list"></a>$modules_list

```php
protected array $modules_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L106).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L89).


### <a name="property-$multishop_context"></a>$multishop_context

```php
public mixed $multishop_context = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L277).


### <a name="property-$multishop_context_group"></a>$multishop_context_group

```php
public mixed $multishop_context_group = true
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L278).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L242).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L267).


### <a name="property-$page_header_toolbar_btn"></a>$page_header_toolbar_btn

```php
public mixed $page_header_toolbar_btn = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L288).


### <a name="property-$page_header_toolbar_title"></a>$page_header_toolbar_title

```php
public mixed $page_header_toolbar_title
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L287).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L29).


### <a name="property-$position_group_identifier"></a>$position_group_identifier

```php
protected mixed $position_group_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L234).


### <a name="property-$required_database"></a>$required_database

```php
public mixed $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L66).


### <a name="property-$required_fields"></a>$required_fields

```php
public array $required_fields = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L188).


### <a name="property-$row_hover"></a>$row_hover

```php
protected boolean $row_hover = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L246).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L120).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L72).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L35).


### <a name="property-$show_form_cancel_button"></a>$show_form_cancel_button

```php
public mixed $show_form_cancel_button
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L289).


### <a name="property-$show_page_header_toolbar"></a>$show_page_header_toolbar

```php
public mixed $show_page_header_toolbar = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L286).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L138).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L141).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L243).


### <a name="property-$submit_action"></a>$submit_action

```php
protected \override $submit_action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L115).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L61).


### <a name="property-$tab_modules_list"></a>$tab_modules_list

```php
protected mixed $tab_modules_list = array('default_list' => array(), 'slider_list' => array())
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L251).


### <a name="property-$table"></a>$table

```php
public string $table = 'configuration'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L49).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L46).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L69).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L132).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected boolean $toolbar_scroll = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L135).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L129).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L80).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L253).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L78).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L79).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L81).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public mixed $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L83).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L82).


### <a name="property-$translationsTab"></a>$translationsTab

```php
protected mixed $translationsTab = array()
```

Display modules list



* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3596](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3596).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L32).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L75).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L70).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L35).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L81).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L40).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L65).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L55).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L45).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L76).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L50).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L82).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L79).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L77).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L59)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2148)


#### Arguments
* $product **mixed**



### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3082](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3082)




### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L301)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2488](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2488)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3546](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3546)


#### Arguments
* $label **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**
* $fieldIds **mixed**
* $id_customization_field **mixed**



### <a name="method-_displayLabelFields"></a>_displayLabelFields

```php
mixed AdminProductsControllerCore::_displayLabelFields($obj, $labels, $languages, $default_language, $type)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3574](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3574)


#### Arguments
* $obj **mixed**
* $labels **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**



### <a name="method-_displaySpecificPriceModificationForm"></a>_displaySpecificPriceModificationForm

```php
mixed AdminProductsControllerCore::_displaySpecificPriceModificationForm($defaultCurrency, $shops, $currencies, $countries, $groups)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3329](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3329)


#### Arguments
* $defaultCurrency **mixed**
* $shops **mixed**
* $currencies **mixed**
* $countries **mixed**
* $groups **mixed**



### <a name="method-_displayUnavailableProductWarning"></a>_displayUnavailableProductWarning

```php
mixed AdminProductsControllerCore::_displayUnavailableProductWarning()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4693](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4693)




### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3528](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3528)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3324](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3324)


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2141)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1606)


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_customer **mixed**
* $price **mixed**
* $from_quantity **mixed**
* $reduction **mixed**
* $reduction_type **mixed**
* $from **mixed**
* $to **mixed**
* $id_combination **mixed**



### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type, $offset)
```

Add a new stylesheet in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L249)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $offset **mixed**



### <a name="method-addCarriers"></a>addCarriers

```php
mixed AdminProductsControllerCore::addCarriers($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3799](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3799)


#### Arguments
* $product **mixed**



### <a name="method-addFiltersToBreadcrumbs"></a>addFiltersToBreadcrumbs

```php
mixed AdminControllerCore::addFiltersToBreadcrumbs()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L501)




### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L295)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L336)


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
* Source: [classes/controller/Controller.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L368)


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
* Source: [classes/controller/Controller.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L347)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addPageHeaderToolBarModulesListButton"></a>addPageHeaderToolBarModulesListButton

```php
mixed AdminControllerCore::addPageHeaderToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1847](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1847)




### <a name="method-addProductImage"></a>addProductImage

```php
mixed AdminProductsControllerCore::addProductImage(object $product, $method)
```

Add or update a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1661](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1661)


#### Arguments
* $product **object** - Product object to add image
* $method **mixed**



### <a name="method-addRowAction"></a>addRowAction

```php
mixed AdminControllerCore::addRowAction($action)
```

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1741](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1741)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1750](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1750)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-addToolBarModulesListButton"></a>addToolBarModulesListButton

```php
mixed AdminControllerCore::addToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1858](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1858)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3115)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3110)


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
* Source: [classes/controller/AdminController.php line 3131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3131)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3120)


#### Arguments
* $object **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1480](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1480)




### <a name="method-ajaxProcessAddAttachment"></a>ajaxProcessAddAttachment

```php
mixed AdminProductsControllerCore::ajaxProcessAddAttachment()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L481)




### <a name="method-ajaxProcessCheckProductName"></a>ajaxProcessCheckProductName

```php
mixed AdminProductsControllerCore::ajaxProcessCheckProductName()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4703](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4703)




### <a name="method-ajaxProcessDefaultProductAttribute"></a>ajaxProcessDefaultProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1437](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1437)




### <a name="method-ajaxProcessDeleteProductAttribute"></a>ajaxProcessDeleteProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1396](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1396)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1569](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1569)




### <a name="method-ajaxProcessDeleteSpecificPrice"></a>ajaxProcessDeleteSpecificPrice

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1083)




### <a name="method-ajaxProcessEditProductAttribute"></a>ajaxProcessEditProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1463](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1463)




### <a name="method-ajaxProcessGetCountriesOptions"></a>ajaxProcessGetCountriesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCountriesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L415)




### <a name="method-ajaxProcessGetCurrenciesOptions"></a>ajaxProcessGetCurrenciesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCurrenciesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L431)




### <a name="method-ajaxProcessGetGroupsOptions"></a>ajaxProcessGetGroupsOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetGroupsOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L447)




### <a name="method-ajaxProcessGetModuleQuickView"></a>ajaxProcessGetModuleQuickView

```php
mixed AdminControllerCore::ajaxProcessGetModuleQuickView()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3865](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3865)




### <a name="method-ajaxProcessOpenHelp"></a>ajaxProcessOpenHelp

```php
mixed AdminControllerCore::ajaxProcessOpenHelp()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3377)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2428](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2428)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4523](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4523)




### <a name="method-ajaxProcessPublishProduct"></a>ajaxProcessPublishProduct

```php
mixed AdminProductsControllerCore::ajaxProcessPublishProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4761](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4761)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1554](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1554)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1533)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4726](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4726)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1489](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1489)




### <a name="method-ajaxProcessaddProductImage"></a>ajaxProcessaddProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessaddProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3815](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3815)




### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(object $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3470)


#### Arguments
* $object **object** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3099](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3099)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3251)




### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1401](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1401)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1626](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1626)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkProduct"></a>checkProduct

```php
mixed AdminProductsControllerCore::checkProduct()
```

Check that a saved product is valid



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1990](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1990)




### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L559)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L319)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyImage"></a>copyImage

```php
mixed AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1696](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1696)


#### Arguments
* $id_product **integer** - Product Id for product image filename
* $id_image **integer** - Image Id for product image filename
* $method **mixed**



### <a name="method-createTemplate"></a>createTemplate

```php
\Template AdminControllerCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3496](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3496)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1458)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1437](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1437)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L212)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L207)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1542)


#### Arguments
* $msg **string**



### <a name="method-displayModuleOptions"></a>displayModuleOptions

```php
mixed AdminControllerCore::displayModuleOptions($module, $output_type, $back)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3597](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3597)


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
* Source: [classes/controller/AdminController.php line 1433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1433)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminControllerCore::displayRequiredFields()
```

prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3478](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3478)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1532](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1532)


#### Arguments
* $msg **string**



### <a name="method-fillModuleData"></a>fillModuleData

```php
mixed AdminControllerCore::fillModuleData($module, $output_type, $back)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3553](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3553)


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
* Source: [classes/controller/AdminController.php line 1869](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1869)




### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1420)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3782](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3782)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4589](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4589)




### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L133)


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
* Source: [classes/controller/AdminController.php line 2995](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2995)


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
* Source: [classes/controller/AdminController.php line 2945](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2945)


#### Arguments
* $obj **object** - Object



### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4680](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4680)


#### Arguments
* $key **mixed**



### <a name="method-getLanguages"></a>getLanguages

```php
mixed AdminControllerCore::getLanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2917](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2917)




### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L349)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getModulesList"></a>getModulesList

```php
mixed AdminControllerCore::getModulesList($filter_modules_list)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2879](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2879)


#### Arguments
* $filter_modules_list **mixed**



### <a name="method-getPackItems"></a>getPackItems

```php
array AdminProductsControllerCore::getPackItems(\Product $product)
```

Get an array of pack items for display from the product object if specified, else from POST/GET values



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3174)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2708](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2708)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getQuantities"></a>getQuantities

```php
mixed AdminProductsControllerCore::getQuantities($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L274)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### <a name="method-getSelectedAssoShop"></a>getSelectedAssoShop

```php
array AdminControllerCore::getSelectedAssoShop(string $table)
```

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3181)


#### Arguments
* $table **string**



### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4607](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4607)


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### <a name="method-init"></a>init

```php
mixed AdminControllerCore::init()
```

Init context and dependencies, handles POST and GET



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2298)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminControllerCore::initBreadcrumbs($tab_id, $tabs)
```

Set breadcrumbs array for the controller page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L399)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2279)


#### Arguments
* $token **mixed**



### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1910](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1910)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1918](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1918)




### <a name="method-initFormAssociations"></a>initFormAssociations

```php
mixed AdminProductsControllerCore::initFormAssociations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2974](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2974)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3621](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3621)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4018](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4018)


#### Arguments
* $product **mixed**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4013](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4013)


#### Arguments
* $obj **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3587](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3587)


#### Arguments
* $obj **mixed**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4469)


#### Arguments
* $obj **mixed**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3937](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3937)


#### Arguments
* $obj **mixed**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3675](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3675)


#### Arguments
* $product **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminProductsControllerCore::initFormModules($obj)
```

AdminProducts display hook



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4641](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4641)


#### Arguments
* $obj **mixed**



### <a name="method-initFormPack"></a>initFormPack

```php
mixed AdminProductsControllerCore::initFormPack($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3223)


#### Arguments
* $product **mixed**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3040](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3040)


#### Arguments
* $obj **mixed**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4191)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSeo"></a>initFormSeo

```php
mixed AdminProductsControllerCore::initFormSeo($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3149)


#### Arguments
* $product **mixed**



### <a name="method-initFormShipping"></a>initFormShipping

```php
mixed AdminProductsControllerCore::initFormShipping($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3768](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3768)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4341](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4341)


#### Arguments
* $obj **mixed**



### <a name="method-initFormVirtualProduct"></a>initFormVirtualProduct

```php
mixed AdminProductsControllerCore::initFormVirtualProduct($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L3258)


#### Arguments
* $product **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4419](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4419)


#### Arguments
* $obj **mixed**



### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1550)




### <a name="method-initModal"></a>initModal

```php
mixed AdminControllerCore::initModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1941](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1941)




### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4615)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminProductsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2498](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2498)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminProductsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1195)




### <a name="method-initShopContext"></a>initShopContext

```php
mixed AdminControllerCore::initShopContext()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2378](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2378)




### <a name="method-initTabModuleList"></a>initTabModuleList

```php
mixed AdminControllerCore::initTabModuleList()
```

init tab modules list and add button in toolbar



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1822](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1822)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2552](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2552)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
void AdminControllerCore::initToolbarTitle()
```

set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L478)




### <a name="method-isCached"></a>isCached

```php
mixed ControllerCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L436)


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
* Source: [classes/controller/AdminController.php line 3537](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3537)


#### Arguments
* $file **mixed**
* $timeout **mixed**



### <a name="method-isProductFieldUpdated"></a>isProductFieldUpdated

```php
boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)
```

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2125)


#### Arguments
* $field **string** - Name of field
* $id_lang **integer**



### <a name="method-isTabSubmitted"></a>isTabSubmitted

```php
mixed AdminProductsControllerCore::isTabSubmitted($tab_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1814](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1814)


#### Arguments
* $tab_name **mixed**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L390)




### <a name="method-jsonConfirmation"></a>jsonConfirmation

```php
mixed AdminControllerCore::jsonConfirmation($message)
```

Shortcut to set up a json success payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3516](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3516)


#### Arguments
* $message **mixed** - success message



### <a name="method-jsonError"></a>jsonError

```php
mixed AdminControllerCore::jsonError($message)
```

Shortcut to set up a json error payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3529](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3529)


#### Arguments
* $message **mixed** - error message



### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2285](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2285)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
mixed AdminProductsControllerCore::loadObject($opt)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L392)


#### Arguments
* $opt **mixed**



### <a name="method-myErrorHandler"></a>myErrorHandler

```php
mixed ControllerCore::myErrorHandler($errno, $errstr, $errfile, $errline)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L444)


#### Arguments
* $errno **mixed**
* $errstr **mixed**
* $errfile **mixed**
* $errline **mixed**



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3261)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess()
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1352](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1352)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminProductsControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1733](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1733)




### <a name="method-processAttachments"></a>processAttachments

```php
void AdminProductsControllerCore::processAttachments()
```

Attach an existing attachment to the product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 607](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L607)




### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
mixed AdminControllerCore::processBulkAffectZone()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3446](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3446)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminProductsControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 752](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L752)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
boolean AdminControllerCore::processBulkDisableSelection()
```

Disable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3421](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3421)




### <a name="method-processBulkEnableSelection"></a>processBulkEnableSelection

```php
boolean AdminControllerCore::processBulkEnableSelection()
```

Enable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3411](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3411)




### <a name="method-processBulkStatusSelection"></a>processBulkStatusSelection

```php
boolean AdminControllerCore::processBulkStatusSelection($status)
```

Toggle status of multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3431](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3431)


#### Arguments
* $status **mixed**



### <a name="method-processCustomizationConfiguration"></a>processCustomizationConfiguration

```php
mixed AdminProductsControllerCore::processCustomizationConfiguration()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1131)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminProductsControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L667)




### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage()
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 751](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L751)




### <a name="method-processDeleteVirtualProduct"></a>processDeleteVirtualProduct

```php
mixed AdminProductsControllerCore::processDeleteVirtualProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L463)




### <a name="method-processDuplicate"></a>processDuplicate

```php
mixed AdminProductsControllerCore::processDuplicate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L618)




### <a name="method-processExport"></a>processExport

```php
mixed AdminControllerCore::processExport($text_delimiter)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 768](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L768)


#### Arguments
* $text_delimiter **mixed**



### <a name="method-processFeatures"></a>processFeatures

```php
mixed AdminProductsControllerCore::processFeatures()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 952](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L952)




### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L586)




### <a name="method-processImage"></a>processImage

```php
mixed AdminProductsControllerCore::processImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 709](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L709)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminProductsControllerCore::processPosition()
```

Overrides parent for custom redirect link



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1177)




### <a name="method-processPriceAddition"></a>processPriceAddition

```php
mixed AdminProductsControllerCore::processPriceAddition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1036](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1036)




### <a name="method-processPricesModification"></a>processPricesModification

```php
mixed AdminProductsControllerCore::processPricesModification()
```

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 994](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L994)




### <a name="method-processProductAttribute"></a>processProductAttribute

```php
mixed AdminProductsControllerCore::processProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 822](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L822)




### <a name="method-processProductCustomization"></a>processProductCustomization

```php
mixed AdminProductsControllerCore::processProductCustomization()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1158)




### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters($list_id)
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1100)


#### Arguments
* $list_id **mixed**



### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L876)




### <a name="method-processSpecificPricePriorities"></a>processSpecificPricePriorities

```php
mixed AdminProductsControllerCore::processSpecificPricePriorities()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1114)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminProductsControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1825](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1825)




### <a name="method-processSuppliers"></a>processSuppliers

```php
mixed AdminProductsControllerCore::processSuppliers()
```

Post treatment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2740](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2740)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminProductsControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1843](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1843)




### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields()
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1032)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions()
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1132)




### <a name="method-processWarehouses"></a>processWarehouses

```php
mixed AdminProductsControllerCore::processWarehouses()
```

Post treatment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2897](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2897)




### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
mixed AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, array $current, integer $id_category, $id_category_default, $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 2446](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2446)


#### Arguments
* $id_obj **mixed**
* $indexedCategories **array** - Array with categories where product is indexed (in order to check checkbox)
* $categories **array** - Categories to list
* $current **array** - Current category
* $id_category **integer** - Current category id
* $id_category_default **mixed**
* $has_suite **mixed**



### <a name="method-redirect"></a>redirect

```php
mixed AdminControllerCore::redirect()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1452)




### <a name="method-refresh"></a>refresh

```php
mixed AdminControllerCore::refresh($file_to_refresh, $external_file)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3545](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3545)


#### Arguments
* $file_to_refresh **mixed**
* $external_file **mixed**



### <a name="method-removeCSS"></a>removeCSS

```php
mixed ControllerCore::removeCSS($css_uri, $css_media_type)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L273)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### <a name="method-removeJS"></a>removeJS

```php
mixed ControllerCore::removeJS($js_uri)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L313)


#### Arguments
* $js_uri **mixed**



### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminControllerCore::renderDetails()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2090](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2090)




### <a name="method-renderForm"></a>renderForm

```php
string|void AdminProductsControllerCore::renderForm()
```

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2592](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2592)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminProductsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2359](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2359)




### <a name="method-renderList"></a>renderList

```php
mixed AdminProductsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2420)




### <a name="method-renderListAttributes"></a>renderListAttributes

```php
mixed AdminProductsControllerCore::renderListAttributes($product, $currency)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4094](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4094)


#### Arguments
* $product **mixed**
* $currency **mixed**



### <a name="method-renderModal"></a>renderModal

```php
mixed AdminControllerCore::renderModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1971](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1971)




### <a name="method-renderModulesList"></a>renderModulesList

```php
mixed AdminControllerCore::renderModulesList()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1985](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L1985)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2158)




### <a name="method-renderView"></a>renderView

```php
mixed AdminControllerCore::renderView()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2075](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2075)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L161)




### <a name="method-setDeprecatedMedia"></a>setDeprecatedMedia

```php
mixed AdminControllerCore::setDeprecatedMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2241)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L2190)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminProductsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L282)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L217)


#### Arguments
* $template **mixed**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent($content)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/Controller.php#L395)


#### Arguments
* $content **mixed**



### <a name="method-updateAccessories"></a>updateAccessories

```php
mixed AdminProductsControllerCore::updateAccessories(object $product)
```

Update product accessories



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2241)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminProductsControllerCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1727](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L1727)


#### Arguments
* $id_object **mixed**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(object $product, $edit)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2161)


#### Arguments
* $product **object** - Product
* $edit **mixed**



### <a name="method-updatePackItems"></a>updatePackItems

```php
boolean AdminProductsControllerCore::updatePackItems(\Product $product)
```

delete all items in pack, then check if type_product value is 2.

if yes, add the pack items from input "inputPackItems"

* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4654](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L4654)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags($languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2262](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminProductsController.php#L2262)


#### Arguments
* $languages **mixed**
* $product **object** - Product



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3272](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3272)


#### Arguments
* $id **mixed**
* $name **mixed**
* $dir **mixed**
* $ext **mixed**
* $width **mixed**
* $height **mixed**



### <a name="method-validateField"></a>validateField

```php
mixed AdminControllerCore::validateField($value, $field)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3230)


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
* Source: [classes/controller/AdminController.php line 3010](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3010)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L546)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3089](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/controller/AdminController.php#L3089)



