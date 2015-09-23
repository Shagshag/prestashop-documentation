Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L28)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$available_tabs](#property-$available_tabs)
* [$available_tabs_lang](#property-$available_tabs_lang)
* [$max_file_size](#property-$max_file_size)
* [$max_image_size](#property-$max_image_size)
* [$tabs_toolbar_save_buttons](#property-$tabs_toolbar_save_buttons)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_errors](#property-$_errors)
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
* [$base_tpl_view](#property-$base_tpl_view)
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
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$fieldsDisplay](#property-$fieldsDisplay)
* [$fields_form](#property-$fields_form)
* [$fields_value](#property-$fields_value)
* [$filter](#property-$filter)
* [$id](#property-$id)
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
* [$meta_title](#property-$meta_title)
* [$multiple_fieldsets](#property-$multiple_fieldsets)
* [$noLink](#property-$noLink)
* [$noTabLink](#property-$noTabLink)
* [$object](#property-$object)
* [$options](#property-$options)
* [$path](#property-$path)
* [$shopLink](#property-$shopLink)
* [$shopLinkType](#property-$shopLinkType)
* [$shopShareDatas](#property-$shopShareDatas)
* [$show_toolbar](#property-$show_toolbar)
* [$show_toolbar_options](#property-$show_toolbar_options)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$tabAccess](#property-$tabAccess)
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
* [ajaxProcessDeleteProductImage](#method-ajaxProcessDeleteProductImage)
* [ajaxProcessHelpAccess](#method-ajaxProcessHelpAccess)
* [ajaxProcessProductManufacturers](#method-ajaxProcessProductManufacturers)
* [ajaxProcessProductQuantity](#method-ajaxProcessProductQuantity)
* [ajaxProcessUpdateCover](#method-ajaxProcessUpdateCover)
* [ajaxProcessUpdateImagePosition](#method-ajaxProcessUpdateImagePosition)
* [ajaxProcessUpdateProductImageShopAsso](#method-ajaxProcessUpdateProductImageShopAsso)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [checkAccess](#method-checkAccess)
* [checkFeatures](#method-checkFeatures)
* [checkToken](#method-checkToken)
* [copyFromPost](#method-copyFromPost)
* [copyImage](#method-copyImage)
* [deleteDownloadProduct](#method-deleteDownloadProduct)
* [deleteVirtualProduct](#method-deleteVirtualProduct)
* [deleteVirtualProductAttribute](#method-deleteVirtualProductAttribute)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayAssoShop](#method-displayAssoShop)
* [displayErrors](#method-displayErrors)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayInformation](#method-displayInformation)
* [displayInitInformationAndAttachment](#method-displayInitInformationAndAttachment)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayWarning](#method-displayWarning)
* [filterToField](#method-filterToField)
* [getAssoShop](#method-getAssoShop)
* [getCarrierList](#method-getCarrierList)
* [getCombinationImagesJS](#method-getCombinationImagesJS)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getL](#method-getL)
* [getLineTableImage](#method-getLineTableImage)
* [getList](#method-getList)
* [getPreviewUrl](#method-getPreviewUrl)
* [getTranslationsFlags](#method-getTranslationsFlags)
* [getlanguages](#method-getlanguages)
* [haveThisAccessory](#method-haveThisAccessory)
* [includeSubTab](#method-includeSubTab)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initForm](#method-initForm)
* [initFormAccounting](#method-initFormAccounting)
* [initFormAttachments](#method-initFormAttachments)
* [initFormAttributes](#method-initFormAttributes)
* [initFormCombinations](#method-initFormCombinations)
* [initFormCustomization](#method-initFormCustomization)
* [initFormFeatures](#method-initFormFeatures)
* [initFormImages](#method-initFormImages)
* [initFormInformations](#method-initFormInformations)
* [initFormPrices](#method-initFormPrices)
* [initFormQuantities](#method-initFormQuantities)
* [initFormSuppliers](#method-initFormSuppliers)
* [initFormWarehouses](#method-initFormWarehouses)
* [initHeader](#method-initHeader)
* [initList](#method-initList)
* [initOptions](#method-initOptions)
* [initPack](#method-initPack)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [initView](#method-initView)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [postProcessFormAccounting](#method-postProcessFormAccounting)
* [postProcessFormSuppliers](#method-postProcessFormSuppliers)
* [postProcessFormWarehouses](#method-postProcessFormWarehouses)
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processPosition](#method-processPosition)
* [processResetFilters](#method-processResetFilters)
* [processSave](#method-processSave)
* [processStatus](#method-processStatus)
* [processUpdateFields](#method-processUpdateFields)
* [processUpdateOptions](#method-processUpdateOptions)
* [recurseCategoryForInclude](#method-recurseCategoryForInclude)
* [redirect](#method-redirect)
* [run](#method-run)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [submitAddProduct](#method-submitAddProduct)
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
private mixed $_category
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L36).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected mixed $available_tabs = array('Informations', 'Images', 'Prices', 'Combinations', 'Features', 'Customization', 'Attachments', 'Quantities', 'Suppliers', 'Warehouses', 'Accounting')
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L38).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L52).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected mixed $max_file_size = 20000000
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L30).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected integer $max_image_size
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L34).


### <a name="property-$tabs_toolbar_save_buttons"></a>$tabs_toolbar_save_buttons

```php
protected mixed $tabs_toolbar_save_buttons = array('Informations' => true, 'Images' => false, 'Prices' => false, 'Combinations' => false, 'Features' => true, 'Customization' => false, 'Attachments' => true, 'Quantities' => false, 'Suppliers' => true, 'Warehouses' => true, 'Accounting' => true)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L54).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L74).


### <a name="property-$_errors"></a>$_errors

```php
public array $_errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L90).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L131).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L189).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L192).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L218).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L183).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L39).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L107).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L125).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L140).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L143).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L137).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L223).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L180).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L134).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L186).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L216).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L149).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'delete', 'duplicate')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L146).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L41).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L82).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L177).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L172).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L158).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L56).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L214).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L36).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L33).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L32).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L40).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L207).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L217).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L226).


### <a name="property-$fieldsDisplay"></a>$fieldsDisplay

```php
protected array $fieldsDisplay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L96).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L99).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L87).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L211).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L53).


### <a name="property-$identifiersDnd"></a>$identifiersDnd

```php
protected mixed $identifiersDnd = array('id_product' => 'id_product', 'id_category' => 'id_category_to_move', 'id_cms_category' => 'id_cms_category_to_move', 'id_cms' => 'id_cms', 'id_attribute' => 'id_attribute')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L198).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L229).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L35).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L194).


### <a name="property-$is_dnd_identifier"></a>$is_dnd_identifier

```php
protected mixed $is_dnd_identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L196).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L128).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L43).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L155).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L93).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L152).


### <a name="property-$meta_title"></a>$meta_title

```php
public mixed $meta_title = 'Administration panel'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L45).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L85).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L212).


### <a name="property-$noTabLink"></a>$noTabLink

```php
public array $noTabLink = array('AdminCatalog', 'AdminTools', 'AdminStock', 'AdminAccounting')
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L65).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L232).


### <a name="property-$options"></a>$options

```php
protected array $options
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L102).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L30).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L104).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L71).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L37).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L119).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L122).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L213).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L59).


### <a name="property-$table"></a>$table

```php
public string $table
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L50).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L47).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L68).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L113).


### <a name="property-$toolbar_fix"></a>$toolbar_fix

```php
protected array $toolbar_fix = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L116).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L110).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L78).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L220).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L76).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L77).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L79).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L80).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L34).


### <a name="property-$ajax"></a>$ajax

```php
protected boolean $ajax = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L36).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L51).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L68)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 1391](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1391)


#### Arguments
* $product **mixed**



### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2146)




### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L136)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 1794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1794)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $defaultLanguage, $type, $fieldIds, $id_customization_field)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 2437](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2437)


#### Arguments
* $label **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**
* $type **mixed**
* $fieldIds **mixed**
* $id_customization_field **mixed**



### <a name="method-_displayLabelFields"></a>_displayLabelFields

```php
mixed AdminProductsControllerCore::_displayLabelFields($obj, $labels, $languages, $defaultLanguage, $type)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 2460](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2460)


#### Arguments
* $obj **mixed**
* $labels **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**
* $type **mixed**



### <a name="method-_displaySpecificPriceModificationForm"></a>_displaySpecificPriceModificationForm

```php
mixed AdminProductsControllerCore::_displaySpecificPriceModificationForm($defaultCurrency, $shops, $currencies, $countries, $groups)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2271](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2271)


#### Arguments
* $defaultCurrency **mixed**
* $shops **mixed**
* $currencies **mixed**
* $countries **mixed**
* $groups **mixed**



### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 2419](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2419)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specificPrice, $productPrice, $taxRate)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 2263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2263)


#### Arguments
* $specificPrice **mixed**
* $productPrice **mixed**
* $taxRate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 1384](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1384)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $price, $from_quantity, $reduction, $reduction_type, $from, $to)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1065](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1065)


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
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
* Source: [classes/Controller.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L219)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**



### <a name="method-addCarriers"></a>addCarriers

```php
mixed AdminProductsControllerCore::addCarriers()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2871](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2871)




### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L251)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L274)


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
* Source: [classes/Controller.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L304)


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
* Source: [classes/Controller.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L285)


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
* Source: [controllers/admin/AdminProductsController.php line 1110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1110)


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
* Source: [classes/AdminController.php line 1280](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1280)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1289](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1289)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2175](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2175)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2170](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2170)


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
* Source: [classes/AdminController.php line 2191](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2191)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2180)


#### Arguments
* $object **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 983](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L983)




### <a name="method-ajaxProcessAddImage"></a>ajaxProcessAddImage

```php
mixed AdminProductsControllerCore::ajaxProcessAddImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 959](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L959)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1039](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1039)




### <a name="method-ajaxProcessHelpAccess"></a>ajaxProcessHelpAccess

```php
mixed AdminControllerCore::ajaxProcessHelpAccess()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L348)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1718](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1718)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3342](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3342)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1027](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1027)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1004](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1004)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 988](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L988)




### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2159)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2314](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2314)




### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 974](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L974)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1083)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L342)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L154)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyImage"></a>copyImage

```php
mixed AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1145](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1145)


#### Arguments
* $id_product **integer** - Product Id for product image filename
* $id_image **integer** - Image Id for product image filename
* $method **mixed**



### <a name="method-deleteDownloadProduct"></a>deleteDownloadProduct

```php
mixed AdminProductsControllerCore::deleteDownloadProduct($id_product_attribute)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1554](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1554)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-deleteVirtualProduct"></a>deleteVirtualProduct

```php
mixed AdminProductsControllerCore::deleteVirtualProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L217)




### <a name="method-deleteVirtualProductAttribute"></a>deleteVirtualProductAttribute

```php
mixed AdminProductsControllerCore::deleteVirtualProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L225)




### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1032](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1032)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1014](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1014)




### <a name="method-displayAssoShop"></a>displayAssoShop

```php
void AdminControllerCore::displayAssoShop(string $type)
```

displayAssoShop



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2325)


#### Arguments
* $type **string**



### <a name="method-displayErrors"></a>displayErrors

```php
mixed AdminProductsControllerCore::displayErrors()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1776](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1776)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L182)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L177)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1114)


#### Arguments
* $msg **string**



### <a name="method-displayInitInformationAndAttachment"></a>displayInitInformationAndAttachment

```php
mixed AdminProductsControllerCore::displayInitInformationAndAttachment()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3547](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3547)




### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1010](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1010)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1104)


#### Arguments
* $msg **string**



### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1000](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1000)


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
* Source: [classes/AdminController.php line 2235](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2235)


#### Arguments
* $table **string**
* $id_object **integer**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2854](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2854)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3432](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3432)




### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L113)


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
* Source: [classes/AdminController.php line 2045](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2045)


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
* Source: [classes/AdminController.php line 2006](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2006)


#### Arguments
* $obj **object** - Object



### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3505](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3505)


#### Arguments
* $key **mixed**



### <a name="method-getLineTableImage"></a>getLineTableImage

```php
mixed AdminProductsControllerCore::getLineTableImage($image, $imagesTotal, $token, $shops)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3388](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3388)


#### Arguments
* $image **mixed**
* $imagesTotal **mixed**
* $token **mixed**
* $shops **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L183)


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
* Source: [controllers/admin/AdminProductsController.php line 1929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1929)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getTranslationsFlags"></a>getTranslationsFlags

```php
string AdminControllerCore::getTranslationsFlags(array $languages, integer $default_language, string $ids, string $id, $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2544](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2544)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **mixed**
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-getlanguages"></a>getlanguages

```php
mixed AdminControllerCore::getlanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1976](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1976)




### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessoryId, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3450](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3450)


#### Arguments
* $accessoryId **mixed**
* $accessories **mixed**



### <a name="method-includeSubTab"></a>includeSubTab

```php
mixed AdminControllerCore::includeSubTab($methodname, $actions)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 996](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L996)


#### Arguments
* $methodname **mixed**
* $actions **mixed**



### <a name="method-init"></a>init

```php
mixed AdminControllerCore::init()
```

Init context and dependencies, handles POST and GET



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1611)




### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1607](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1607)


#### Arguments
* $token **mixed**



### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1338](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1338)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1346](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1346)




### <a name="method-initForm"></a>initForm

```php
void AdminProductsControllerCore::initForm()
```

initForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1886](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1886)




### <a name="method-initFormAccounting"></a>initFormAccounting

```php
mixed AdminProductsControllerCore::initFormAccounting($product, $t)
```

Init data for accounting



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2184)


#### Arguments
* $product **mixed**
* $t **mixed**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj, $languages, $defaultLanguage)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2548](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2548)


#### Arguments
* $obj **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes($product, $languages, $defaultLanguage)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2929)


#### Arguments
* $product **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj, $languages, $defaultLanguage)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2924](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2924)


#### Arguments
* $obj **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization($obj, $languages, $defaultLanguage)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2473](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2473)


#### Arguments
* $obj **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3299](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3299)


#### Arguments
* $obj **mixed**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages($obj, $token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2883](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2883)


#### Arguments
* $obj **mixed**
* $token **mixed**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations($product, $languages, $defaultLanguage)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2620](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2620)


#### Arguments
* $product **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices($obj, $languages, $defaultLanguage)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2218)


#### Arguments
* $obj **mixed**
* $languages **mixed**
* $defaultLanguage **mixed**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3146)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3190](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3190)


#### Arguments
* $obj **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3258](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3258)


#### Arguments
* $obj **mixed**



### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1122)




### <a name="method-initList"></a>initList

```php
mixed AdminProductsControllerCore::initList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1711](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1711)




### <a name="method-initOptions"></a>initOptions

```php
mixed AdminControllerCore::initOptions()
```

Function used to initialise the options to display for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1444](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1444)




### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **private**
* Source: [controllers/admin/AdminProductsController.php line 3458](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3458)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1809)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
void AdminControllerCore::initToolbarTitle()
```

set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L290)




### <a name="method-initView"></a>initView

```php
mixed AdminControllerCore::initView()
```

Override to init display of the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1398](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1398)




### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1597](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1597)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class, without &quot;Controller&quot; suffix
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
object AdminProductsControllerCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3525](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3525)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2437](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2437)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess(mixed $token)
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L239)


#### Arguments
* $token **mixed**



### <a name="method-postProcessFormAccounting"></a>postProcessFormAccounting

```php
mixed AdminProductsControllerCore::postProcessFormAccounting()
```

Post traitment for accounting



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1961)




### <a name="method-postProcessFormSuppliers"></a>postProcessFormSuppliers

```php
mixed AdminProductsControllerCore::postProcessFormSuppliers()
```

Post traitment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1993](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1993)




### <a name="method-postProcessFormWarehouses"></a>postProcessFormWarehouses

```php
mixed AdminProductsControllerCore::postProcessFormWarehouses()
```

Post traitment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L2102)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminControllerCore::processBulkDelete($token)
```

Delete multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2489](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2489)


#### Arguments
* $token **mixed**



### <a name="method-processDelete"></a>processDelete

```php
mixed AdminControllerCore::processDelete(string $token)
```

Object Delete



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L495)


#### Arguments
* $token **string**



### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage(string $token)
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L473)


#### Arguments
* $token **string**



### <a name="method-processPosition"></a>processPosition

```php
mixed AdminControllerCore::processPosition(string $token)
```

Change object position



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 716](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L716)


#### Arguments
* $token **string**



### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters()
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L739)




### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave(string $token)
```

Object update and creation
TODO: split processAdd and processUpdate



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L541)


#### Arguments
* $token **string**



### <a name="method-processStatus"></a>processStatus

```php
mixed AdminControllerCore::processStatus(string $token)
```

Change object statuts (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L691)


#### Arguments
* $token **string**



### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields(string $token)
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L672)


#### Arguments
* $token **string**



### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions(string $token)
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 773](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L773)


#### Arguments
* $token **string**



### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
mixed AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, array $current, integer $id_category, $id_category_default, $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 1738](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1738)


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
* Source: [classes/AdminController.php line 1027](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1027)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L134)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1468](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1468)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1511](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1511)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L187)


#### Arguments
* $template **mixed**



### <a name="method-submitAddProduct"></a>submitAddProduct

```php
mixed AdminProductsControllerCore::submitAddProduct($token)
```

Add or update a product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1177](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1177)


#### Arguments
* $token **mixed**



### <a name="method-translate"></a>translate

```php
string AdminControllerCore::translate(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **public**
* This method is **static**.
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1540](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L1540)


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
* Source: [controllers/admin/AdminProductsController.php line 1571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1571)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminControllerCore::updateAssoShop(integer $id_object, integer $new_id_object)
```

Update the associations of shops



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2263)


#### Arguments
* $id_object **integer**
* $new_id_object **integer**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(object $product, $edit, $id_product_attribute)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1404](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1404)


#### Arguments
* $product **object** - Product
* $edit **mixed**
* $id_product_attribute **mixed**



### <a name="method-updatePackItems"></a>updatePackItems

```php
mixed AdminProductsControllerCore::updatePackItems($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3480](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L3480)


#### Arguments
* $product **mixed**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags($languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1592](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/admin/AdminProductsController.php#L1592)


#### Arguments
* $languages **mixed**
* $product **object** - Product



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2448](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2448)


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
* Source: [classes/AdminController.php line 2293](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2293)


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
* Source: [classes/AdminController.php line 2060](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2060)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess($disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L327)


#### Arguments
* $disable **mixed**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2151](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/AdminController.php#L2151)



