Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L28)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$available_tabs](#property-$available_tabs)
* [$available_tabs_lang](#property-$available_tabs_lang)
* [$default_tab](#property-$default_tab)
* [$max_file_size](#property-$max_file_size)
* [$max_image_size](#property-$max_image_size)
* [$tab_display](#property-$tab_display)
* [$tab_display_module](#property-$tab_display_module)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$_filter](#property-$_filter)
* [$_group](#property-$_group)
* [$_having](#property-$_having)
* [$_includeContainer](#property-$_includeContainer)
* [$_join](#property-$_join)
* [$_languages](#property-$_languages)
* [$_list](#property-$_list)
* [$_listTotal](#property-$_listTotal)
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
* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$base_tpl_form](#property-$base_tpl_form)
* [$base_tpl_view](#property-$base_tpl_view)
* [$bo_theme](#property-$bo_theme)
* [$boxes](#property-$boxes)
* [$bulk_actions](#property-$bulk_actions)
* [$cache_lang](#property-$cache_lang)
* [$className](#property-$className)
* [$colorOnBackground](#property-$colorOnBackground)
* [$confirmations](#property-$confirmations)
* [$content](#property-$content)
* [$currentIndex](#property-$currentIndex)
* [$default_form_language](#property-$default_form_language)
* [$deleted](#property-$deleted)
* [$display](#property-$display)
* [$errors](#property-$errors)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$fieldsDisplay](#property-$fieldsDisplay)
* [$fields_form](#property-$fields_form)
* [$fields_form_override](#property-$fields_form_override)
* [$fields_value](#property-$fields_value)
* [$filter](#property-$filter)
* [$id](#property-$id)
* [$id_object](#property-$id_object)
* [$identifier](#property-$identifier)
* [$identifiersDnd](#property-$identifiersDnd)
* [$imageType](#property-$imageType)
* [$informations](#property-$informations)
* [$is_cms](#property-$is_cms)
* [$is_dnd_identifier](#property-$is_dnd_identifier)
* [$lang](#property-$lang)
* [$layout](#property-$layout)
* [$list_no_link](#property-$list_no_link)
* [$list_simple_header](#property-$list_simple_header)
* [$list_skip_actions](#property-$list_skip_actions)
* [$lite_display](#property-$lite_display)
* [$meta_title](#property-$meta_title)
* [$multiple_fieldsets](#property-$multiple_fieldsets)
* [$noLink](#property-$noLink)
* [$noTabLink](#property-$noTabLink)
* [$object](#property-$object)
* [$options](#property-$options)
* [$path](#property-$path)
* [$required_database](#property-$required_database)
* [$required_fields](#property-$required_fields)
* [$row_hover](#property-$row_hover)
* [$shopLink](#property-$shopLink)
* [$shopLinkType](#property-$shopLinkType)
* [$shopShareDatas](#property-$shopShareDatas)
* [$show_toolbar](#property-$show_toolbar)
* [$show_toolbar_options](#property-$show_toolbar_options)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$tabAccess](#property-$tabAccess)
* [$tab_module_list](#property-$tab_module_list)
* [$table](#property-$table)
* [$template](#property-$template)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_fix](#property-$toolbar_fix)
* [$toolbar_title](#property-$toolbar_title)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$tpl_folder](#property-$tpl_folder)
* [$tpl_form_vars](#property-$tpl_form_vars)
* [$tpl_list_vars](#property-$tpl_list_vars)
* [$tpl_option_vars](#property-$tpl_option_vars)
* [$tpl_required_fields_vars](#property-$tpl_required_fields_vars)
* [$tpl_view_vars](#property-$tpl_view_vars)
* [$warnings](#property-$warnings)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
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
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addProductImage](#method-addProductImage)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcessAddImage](#method-ajaxProcessAddImage)
* [ajaxProcessDefaultProductAttribute](#method-ajaxProcessDefaultProductAttribute)
* [ajaxProcessDeleteProductAttribute](#method-ajaxProcessDeleteProductAttribute)
* [ajaxProcessDeleteProductImage](#method-ajaxProcessDeleteProductImage)
* [ajaxProcessEditProductAttribute](#method-ajaxProcessEditProductAttribute)
* [ajaxProcessHelpAccess](#method-ajaxProcessHelpAccess)
* [ajaxProcessProductManufacturers](#method-ajaxProcessProductManufacturers)
* [ajaxProcessProductQuantity](#method-ajaxProcessProductQuantity)
* [ajaxProcessUpdateCover](#method-ajaxProcessUpdateCover)
* [ajaxProcessUpdateImagePosition](#method-ajaxProcessUpdateImagePosition)
* [ajaxProcessUpdateProductImageShopAsso](#method-ajaxProcessUpdateProductImageShopAsso)
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
* [deleteDownloadProduct](#method-deleteDownloadProduct)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayInformation](#method-displayInformation)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayWarning](#method-displayWarning)
* [filterToField](#method-filterToField)
* [getAssoShop](#method-getAssoShop)
* [getCarrierList](#method-getCarrierList)
* [getCombinationImagesJS](#method-getCombinationImagesJS)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getL](#method-getL)
* [getLanguages](#method-getLanguages)
* [getList](#method-getList)
* [getPreviewUrl](#method-getPreviewUrl)
* [getTranslationsFlags](#method-getTranslationsFlags)
* [haveThisAccessory](#method-haveThisAccessory)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initFormAccounting](#method-initFormAccounting)
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
* [initModuleCacheTab](#method-initModuleCacheTab)
* [initPack](#method-initPack)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAccounting](#method-processAccounting)
* [processAdd](#method-processAdd)
* [processAddAttachments](#method-processAddAttachments)
* [processAttachments](#method-processAttachments)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [processBulkDelete](#method-processBulkDelete)
* [processCustomizationConfiguration](#method-processCustomizationConfiguration)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processDeleteSpecificPrice](#method-processDeleteSpecificPrice)
* [processDeleteVirtualProduct](#method-processDeleteVirtualProduct)
* [processDeleteVirtualProductAttribute](#method-processDeleteVirtualProductAttribute)
* [processDuplicate](#method-processDuplicate)
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
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderListAttributes](#method-renderListAttributes)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)
* [run](#method-run)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [translate](#method-translate)
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
* Source: [controllers/admin/AdminProductsController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L36).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected array $available_tabs = array('Informations' => 0, 'Pack' => 7, 'VirtualProduct' => 8, 'Prices' => 1, 'Seo' => 2, 'Associations' => 3, 'Images' => 9, 'Shipping' => 4, 'Combinations' => 5, 'Features' => 10, 'Customization' => 11, 'Attachments' => 12, 'Quantities' => 6, 'Suppliers' => 13, 'Warehouses' => 14, 'Accounting' => 15)
```

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L48).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L69).


### <a name="property-$default_tab"></a>$default_tab

```php
protected mixed $default_tab = 'Informations'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L67).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected integer $max_file_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L33).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected mixed $max_image_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L34).


### <a name="property-$tab_display"></a>$tab_display

```php
protected string $tab_display
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L40).


### <a name="property-$tab_display_module"></a>$tab_display_module

```php
protected mixed $tab_display_module
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L41).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L75).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'ASC'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L76).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L138).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L204).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L207).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L235).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L198).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L38).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L114).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L132).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L147).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L150).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L144).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L242).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L195).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L141).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L201).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L233).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L156).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'delete', 'duplicate')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L153).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L40).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public mixed $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L86).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L85).


### <a name="property-$bo_theme"></a>$bo_theme

```php
protected mixed $bo_theme
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L239).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L192).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L187).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L167).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L55).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L229).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L35).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L32).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L31).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L39).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L222).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L234).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L94).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L245).


### <a name="property-$fieldsDisplay"></a>$fieldsDisplay

```php
protected array $fieldsDisplay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L100).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L103).


### <a name="property-$fields_form_override"></a>$fields_form_override

```php
protected \override $fields_form_override
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L106).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L91).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L226).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L61).


### <a name="property-$id_object"></a>$id_object

```php
protected \current $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L254).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L52).


### <a name="property-$identifiersDnd"></a>$identifiersDnd

```php
protected mixed $identifiersDnd = array('id_product' => 'id_product', 'id_category' => 'id_category_to_move', 'id_cms_category' => 'id_cms_category_to_move', 'id_cms' => 'id_cms', 'id_attribute' => 'id_attribute')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L213).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L248).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L34).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L209).


### <a name="property-$is_dnd_identifier"></a>$is_dnd_identifier

```php
protected mixed $is_dnd_identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L211).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L135).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L42).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L164).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L97).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L159).


### <a name="property-$lite_display"></a>$lite_display

```php
protected mixed $lite_display = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L162).


### <a name="property-$meta_title"></a>$meta_title

```php
public mixed $meta_title = 'Administration panel'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L44).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L89).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L227).


### <a name="property-$noTabLink"></a>$noTabLink

```php
public array $noTabLink = array('AdminCatalog', 'AdminTools', 'AdminStock', 'AdminAccounting')
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L64).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L251).


### <a name="property-$options"></a>$options

```php
protected array $options
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L109).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L30).


### <a name="property-$required_database"></a>$required_database

```php
public mixed $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L66).


### <a name="property-$required_fields"></a>$required_fields

```php
public array $required_fields = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L173).


### <a name="property-$row_hover"></a>$row_hover

```php
protected boolean $row_hover = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L231).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L111).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L72).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L36).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L126).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L129).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L228).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L58).


### <a name="property-$tab_module_list"></a>$tab_module_list

```php
public array $tab_module_list
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L170).


### <a name="property-$table"></a>$table

```php
public string $table
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L49).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L46).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L69).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L120).


### <a name="property-$toolbar_fix"></a>$toolbar_fix

```php
protected array $toolbar_fix = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L123).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L117).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L80).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L237).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L78).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L79).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L81).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public mixed $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L83).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L82).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L33).


### <a name="property-$ajax"></a>$ajax

```php
protected boolean $ajax = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L36).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L51).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L71)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1610](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1610)


#### Arguments
* $product **mixed**



### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2231)




### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L205)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1964)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2911](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2911)


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
* Source: [controllers/admin/AdminProductsController.php line 2934](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2934)


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
* Source: [controllers/admin/AdminProductsController.php line 2725](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2725)


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
* Source: [controllers/admin/AdminProductsController.php line 3889](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3889)




### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2893](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2893)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $productPrice, $taxRate)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2717](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2717)


#### Arguments
* $specific_price **mixed**
* $productPrice **mixed**
* $taxRate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1603](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1603)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1253](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1253)


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



### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type)
```

Add a new stylesheet in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L233)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**



### <a name="method-addCarriers"></a>addCarriers

```php
mixed AdminProductsControllerCore::addCarriers()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3118)




### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L265)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L288)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
void ControllerCore::addJqueryPlugin($name, $folder)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L318)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L299)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addProductImage"></a>addProductImage

```php
mixed AdminProductsControllerCore::addProductImage(object $product, $method)
```

Add or update a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1298](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1298)


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
* Source: [classes/controller/AdminController.php line 1325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1325)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1334](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1334)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2264](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2264)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2259](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2259)


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
* Source: [classes/controller/AdminController.php line 2280](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2280)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2269)


#### Arguments
* $object **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1152](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1152)




### <a name="method-ajaxProcessAddImage"></a>ajaxProcessAddImage

```php
mixed AdminProductsControllerCore::ajaxProcessAddImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1022](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1022)




### <a name="method-ajaxProcessDefaultProductAttribute"></a>ajaxProcessDefaultProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1097](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1097)




### <a name="method-ajaxProcessDeleteProductAttribute"></a>ajaxProcessDeleteProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1048](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1048)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1222](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1222)




### <a name="method-ajaxProcessEditProductAttribute"></a>ajaxProcessEditProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1123)




### <a name="method-ajaxProcessHelpAccess"></a>ajaxProcessHelpAccess

```php
mixed AdminControllerCore::ajaxProcessHelpAccess()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L373)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1908](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1908)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3688](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3688)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1206](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1206)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1183](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1183)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1161](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1161)




### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(object $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2563](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2563)


#### Arguments
* $object **object** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2248](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2248)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2396](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2396)




### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1043](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1043)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1271](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1271)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkProduct"></a>checkProduct

```php
mixed AdminProductsControllerCore::checkProduct()
```

Check that a saved product is valid



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1527](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1527)




### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L367)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L223)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyImage"></a>copyImage

```php
mixed AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1333](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1333)


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
* Source: [classes/controller/AdminController.php line 2588](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2588)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-deleteDownloadProduct"></a>deleteDownloadProduct

```php
mixed AdminProductsControllerCore::deleteDownloadProduct($id_product_attribute)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1767](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1767)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1094](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1094)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1076](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1076)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L196)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L191)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1172)


#### Arguments
* $msg **string**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1072](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1072)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminControllerCore::displayRequiredFields()
```

prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2571)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1162)


#### Arguments
* $msg **string**



### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1062](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1062)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-getAssoShop"></a>getAssoShop

```php
mixed AdminControllerCore::getAssoShop(string $table, integer $id_object)
```

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is **static**.
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2324](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2324)


#### Arguments
* $table **string**
* $id_object **integer**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3101](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3101)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3746](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3746)




### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L125)


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
* Source: [classes/controller/AdminController.php line 2130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2130)


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
* Source: [classes/controller/AdminController.php line 2091](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2091)


#### Arguments
* $obj **object** - Object



### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3838](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3838)


#### Arguments
* $key **mixed**



### <a name="method-getLanguages"></a>getLanguages

```php
mixed AdminControllerCore::getLanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2061](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2061)




### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L253)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2133)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getTranslationsFlags"></a>getTranslationsFlags

```php
string AdminControllerCore::getTranslationsFlags(array $languages, integer $default_language, string $ids, string $id, $return, boolean $use_vars_instead_of_ids)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2532](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2532)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **mixed**
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3764](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3764)


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
* Source: [classes/controller/AdminController.php line 1673](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1673)




### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1818](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1818)


#### Arguments
* $token **mixed**



### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1387)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1395](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1395)




### <a name="method-initFormAccounting"></a>initFormAccounting

```php
mixed AdminProductsControllerCore::initFormAccounting($obj)
```

Init data for accounting



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2421](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2421)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAssociations"></a>initFormAssociations

```php
mixed AdminProductsControllerCore::initFormAssociations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2463](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2463)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj, $languages, $default_language)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2976](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2976)


#### Arguments
* $obj **mixed**
* $languages **mixed**
* $default_language **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3177](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3177)


#### Arguments
* $product **mixed**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj, $languages, $default_language)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3172)


#### Arguments
* $obj **mixed**
* $languages **mixed**
* $default_language **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization($obj, $languages, $default_language)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2947](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2947)


#### Arguments
* $obj **mixed**
* $languages **mixed**
* $default_language **mixed**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3642](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3642)


#### Arguments
* $obj **mixed**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3130)


#### Arguments
* $obj **mixed**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3008](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3008)


#### Arguments
* $product **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminProductsControllerCore::initFormModules($obj)
```

AdminProducts display hook



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3798](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3798)


#### Arguments
* $obj **mixed**



### <a name="method-initFormPack"></a>initFormPack

```php
mixed AdminProductsControllerCore::initFormPack($product, $languages, $default_language)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2609](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2609)


#### Arguments
* $product **mixed**
* $languages **mixed**
* $default_language **mixed**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2519](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2519)


#### Arguments
* $obj **mixed**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities($obj, $languages)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3392](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3392)


#### Arguments
* $obj **mixed**
* $languages **mixed**



### <a name="method-initFormSeo"></a>initFormSeo

```php
mixed AdminProductsControllerCore::initFormSeo($product, $languages, $default_language)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2595)


#### Arguments
* $product **mixed**
* $languages **mixed**
* $default_language **mixed**



### <a name="method-initFormShipping"></a>initFormShipping

```php
mixed AdminProductsControllerCore::initFormShipping($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3087](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3087)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3524](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3524)


#### Arguments
* $obj **mixed**



### <a name="method-initFormVirtualProduct"></a>initFormVirtualProduct

```php
mixed AdminProductsControllerCore::initFormVirtualProduct($product, $languages, $default_language)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2642](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2642)


#### Arguments
* $product **mixed**
* $languages **mixed**
* $default_language **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3597](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3597)


#### Arguments
* $obj **mixed**



### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1180)




### <a name="method-initModuleCacheTab"></a>initModuleCacheTab

```php
mixed AdminControllerCore::initModuleCacheTab()
```

Init a cache list of tab existing in a module



* Visibility: **public**
* This method is **static**.
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1664](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1664)




### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3772)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initProcess"></a>initProcess

```php
mixed AdminProductsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 860](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L860)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1979](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1979)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminProductsControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2054](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2054)




### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1650](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1650)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class, without &quot;Controller&quot; suffix
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
object AdminProductsControllerCore::loadObject(boolean $opt)
```

Override parent to add stock data to object
We don't want to make a "full" product load because of side effects to prices



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1001](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1001)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2406](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2406)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess(mixed $token)
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1015](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1015)


#### Arguments
* $token **mixed**



### <a name="method-processAccounting"></a>processAccounting

```php
mixed AdminProductsControllerCore::processAccounting($token)
```

Post treatment for accounting



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2160](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2160)


#### Arguments
* $token **mixed**



### <a name="method-processAdd"></a>processAdd

```php
mixed AdminProductsControllerCore::processAdd($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1365](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1365)


#### Arguments
* $token **mixed**



### <a name="method-processAddAttachments"></a>processAddAttachments

```php
void AdminProductsControllerCore::processAddAttachments($token)
```

Upload new attachment



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L309)


#### Arguments
* $token **mixed**



### <a name="method-processAttachments"></a>processAttachments

```php
void AdminProductsControllerCore::processAttachments($token)
```

Attach an existing attachment to the product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L389)


#### Arguments
* $token **mixed**



### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
mixed AdminControllerCore::processBulkAffectZone($token)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2501](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2501)


#### Arguments
* $token **mixed**



### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminProductsControllerCore::processBulkDelete($token)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 511](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L511)


#### Arguments
* $token **mixed**



### <a name="method-processCustomizationConfiguration"></a>processCustomizationConfiguration

```php
mixed AdminProductsControllerCore::processCustomizationConfiguration($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L807)


#### Arguments
* $token **mixed**



### <a name="method-processDelete"></a>processDelete

```php
mixed AdminProductsControllerCore::processDelete($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L440)


#### Arguments
* $token **mixed**



### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage(string $token)
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L509)


#### Arguments
* $token **string**



### <a name="method-processDeleteSpecificPrice"></a>processDeleteSpecificPrice

```php
mixed AdminProductsControllerCore::processDeleteSpecificPrice($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 773](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L773)


#### Arguments
* $token **mixed**



### <a name="method-processDeleteVirtualProduct"></a>processDeleteVirtualProduct

```php
mixed AdminProductsControllerCore::processDeleteVirtualProduct($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L287)


#### Arguments
* $token **mixed**



### <a name="method-processDeleteVirtualProductAttribute"></a>processDeleteVirtualProductAttribute

```php
mixed AdminProductsControllerCore::processDeleteVirtualProductAttribute($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L295)


#### Arguments
* $token **mixed**



### <a name="method-processDuplicate"></a>processDuplicate

```php
mixed AdminProductsControllerCore::processDuplicate($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L401)


#### Arguments
* $token **mixed**



### <a name="method-processFeatures"></a>processFeatures

```php
mixed AdminProductsControllerCore::processFeatures($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L656)


#### Arguments
* $token **mixed**



### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L394)




### <a name="method-processImage"></a>processImage

```php
mixed AdminProductsControllerCore::processImage($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L468)


#### Arguments
* $token **mixed**



### <a name="method-processPosition"></a>processPosition

```php
mixed AdminProductsControllerCore::processPosition($token)
```

Overrides parent for custom redirect link



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 847](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L847)


#### Arguments
* $token **mixed**



### <a name="method-processPriceAddition"></a>processPriceAddition

```php
mixed AdminProductsControllerCore::processPriceAddition($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L735)


#### Arguments
* $token **mixed**



### <a name="method-processPricesModification"></a>processPricesModification

```php
mixed AdminProductsControllerCore::processPricesModification($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L697)


#### Arguments
* $token **mixed**



### <a name="method-processProductAttribute"></a>processProductAttribute

```php
mixed AdminProductsControllerCore::processProductAttribute($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L550)


#### Arguments
* $token **mixed**



### <a name="method-processProductCustomization"></a>processProductCustomization

```php
mixed AdminProductsControllerCore::processProductCustomization($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L827)


#### Arguments
* $token **mixed**



### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters()
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L802)




### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave($token)
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L583)


#### Arguments
* $token **mixed**



### <a name="method-processSpecificPricePriorities"></a>processSpecificPricePriorities

```php
mixed AdminProductsControllerCore::processSpecificPricePriorities($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L788)


#### Arguments
* $token **mixed**



### <a name="method-processStatus"></a>processStatus

```php
mixed AdminControllerCore::processStatus(string $token)
```

Change object status (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 754](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L754)


#### Arguments
* $token **string**



### <a name="method-processSuppliers"></a>processSuppliers

```php
mixed AdminProductsControllerCore::processSuppliers($token)
```

Post treatment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2189)


#### Arguments
* $token **mixed**



### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminProductsControllerCore::processUpdate($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1447](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1447)


#### Arguments
* $token **mixed**



### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields(string $token)
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L735)


#### Arguments
* $token **string**



### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions(string $token)
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L838)


#### Arguments
* $token **string**



### <a name="method-processWarehouses"></a>processWarehouses

```php
mixed AdminProductsControllerCore::processWarehouses($token)
```

Post treatment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2342](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2342)


#### Arguments
* $token **mixed**



### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
mixed AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, array $current, integer $id_category, $id_category_default, $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 1926](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1926)


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
* Source: [classes/controller/AdminController.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1089)




### <a name="method-renderForm"></a>renderForm

```php
void AdminProductsControllerCore::renderForm()
```

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2067](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L2067)




### <a name="method-renderList"></a>renderList

```php
mixed AdminProductsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1896](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1896)




### <a name="method-renderListAttributes"></a>renderListAttributes

```php
mixed AdminProductsControllerCore::renderListAttributes($id_product_download, $product, $currency)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3248](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3248)


#### Arguments
* $id_product_download **mixed**
* $product **mixed**
* $currency **mixed**



### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1494](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1494)




### <a name="method-renderView"></a>renderView

```php
mixed AdminControllerCore::renderView()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1443](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1443)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L146)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1518](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1518)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminProductsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3851](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3851)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L201)


#### Arguments
* $template **mixed**



### <a name="method-translate"></a>translate

```php
string AdminControllerCore::translate(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **public**
* This method is **static**.
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L1595)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - the classname (without &quot;Controller&quot; suffix)
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-updateAccessories"></a>updateAccessories

```php
mixed AdminProductsControllerCore::updateAccessories(object $product)
```

Update product accessories



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1784](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1784)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminControllerCore::updateAssoShop(integer $id_object, integer $new_id_object)
```

Update the associations of shops



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2356](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2356)


#### Arguments
* $id_object **integer**
* $new_id_object **integer**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(object $product, $edit, $id_product_attribute)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1623](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1623)


#### Arguments
* $product **object** - Product
* $edit **mixed**
* $id_product_attribute **mixed**



### <a name="method-updatePackItems"></a>updatePackItems

```php
boolean AdminProductsControllerCore::updatePackItems(\Product $product)
```

delete all items in pack, then check if type_product value is 2.

if yes, add the pack items from input "inputPackItems"

* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3813](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L3813)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags($languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1805](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/admin/AdminProductsController.php#L1805)


#### Arguments
* $languages **mixed**
* $product **object** - Product



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2417](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2417)


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
* Source: [classes/controller/AdminController.php line 2375](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2375)


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
* Source: [classes/controller/AdminController.php line 2145](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2145)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L354)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2238](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/AdminController.php#L2238)



