Class AdminGeolocationControllerCore
=====================





* Class name: AdminGeolocationControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminGeolocationController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/controllers/admin/AdminGeolocationController.php#L28)


Contents
--------


### Properties

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
* [$base_tpl_form](#property-$base_tpl_form)
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
* [$meta_title](#property-$meta_title)
* [$multiple_fieldsets](#property-$multiple_fieldsets)
* [$noLink](#property-$noLink)
* [$noTabLink](#property-$noTabLink)
* [$object](#property-$object)
* [$options](#property-$options)
* [$path](#property-$path)
* [$required_database](#property-$required_database)
* [$required_fields](#property-$required_fields)
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
* [$tpl_required_fields_vars](#property-$tpl_required_fields_vars)
* [$tpl_view_vars](#property-$tpl_view_vars)
* [$warnings](#property-$warnings)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$hook_list](#property-$hook_list)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)

### Methods

* [__construct](#method-__construct)
* [_childValidation](#method-_childValidation)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessHelpAccess](#method-ajaxProcessHelpAccess)
* [beforeAdd](#method-beforeAdd)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [checkAccess](#method-checkAccess)
* [checkToken](#method-checkToken)
* [copyFromPost](#method-copyFromPost)
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
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getList](#method-getList)
* [getTranslationsFlags](#method-getTranslationsFlags)
* [getlanguages](#method-getlanguages)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [isGeoLiteCityAvailable](#method-isGeoLiteCityAvailable)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processFilter](#method-processFilter)
* [processPosition](#method-processPosition)
* [processResetFilters](#method-processResetFilters)
* [processSave](#method-processSave)
* [processStatus](#method-processStatus)
* [processUpdate](#method-processUpdate)
* [processUpdateFields](#method-processUpdateFields)
* [processUpdateOptions](#method-processUpdateOptions)
* [redirect](#method-redirect)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)
* [run](#method-run)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [translate](#method-translate)
* [updateAssoShop](#method-updateAssoShop)
* [uploadImage](#method-uploadImage)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)




Properties
----------


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L76).


### <a name="property-$_errors"></a>$_errors

```php
public array $_errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L94).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L135).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L196).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L199).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L225).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L190).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L39).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L111).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L129).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L144).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L147).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L141).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L230).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L187).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L138).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L193).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L223).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L153).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'delete', 'duplicate')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L150).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L41).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public mixed $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L86).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L85).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L184).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L179).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L162).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L56).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L221).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L36).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L33).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L32).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L40).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L214).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L224).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L233).


### <a name="property-$fieldsDisplay"></a>$fieldsDisplay

```php
protected array $fieldsDisplay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L100).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L103).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L91).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L218).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L62).


### <a name="property-$id_object"></a>$id_object

```php
protected \current $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L242).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L53).


### <a name="property-$identifiersDnd"></a>$identifiersDnd

```php
protected mixed $identifiersDnd = array('id_product' => 'id_product', 'id_category' => 'id_category_to_move', 'id_cms_category' => 'id_cms_category_to_move', 'id_cms' => 'id_cms', 'id_attribute' => 'id_attribute')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L205).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L236).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L35).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L201).


### <a name="property-$is_dnd_identifier"></a>$is_dnd_identifier

```php
protected mixed $is_dnd_identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L203).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L132).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L43).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L159).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L97).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L156).


### <a name="property-$meta_title"></a>$meta_title

```php
public mixed $meta_title = 'Administration panel'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L45).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L89).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L219).


### <a name="property-$noTabLink"></a>$noTabLink

```php
public array $noTabLink = array('AdminCatalog', 'AdminTools', 'AdminStock', 'AdminAccounting')
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L65).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L239).


### <a name="property-$options"></a>$options

```php
protected array $options
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L106).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L30).


### <a name="property-$required_database"></a>$required_database

```php
public mixed $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L67).


### <a name="property-$required_fields"></a>$required_fields

```php
public array $required_fields = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L165).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L108).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L73).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L37).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L123).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L126).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L220).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L59).


### <a name="property-$table"></a>$table

```php
public string $table
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L50).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L47).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L70).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L117).


### <a name="property-$toolbar_fix"></a>$toolbar_fix

```php
protected array $toolbar_fix = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L120).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L114).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L80).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L227).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L78).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L79).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L81).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public mixed $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L83).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L82).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L34).


### <a name="property-$ajax"></a>$ajax

```php
protected boolean $ajax = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L36).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L51).


### <a name="property-$hook_list"></a>$hook_list

```php
public mixed $hook_list = array()
```

hook_list is used with liveEdit



* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L78).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminGeolocationControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGeolocationController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/controllers/admin/AdminGeolocationController.php#L30)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2205](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2205)




### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type)
```

Add a new stylesheet in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L228)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**



### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L260)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L283)


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
* Source: [classes/Controller.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L313)


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
* Source: [classes/Controller.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L294)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addRowAction"></a>addRowAction

```php
mixed AdminControllerCore::addRowAction($action)
```

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1331](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1331)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1340](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1340)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2234)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2229](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2229)


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
* Source: [classes/AdminController.php line 2250](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2250)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2239)


#### Arguments
* $object **mixed**



### <a name="method-ajaxProcessHelpAccess"></a>ajaxProcessHelpAccess

```php
mixed AdminControllerCore::ajaxProcessHelpAccess()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L359)




### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(object $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2531](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2531)


#### Arguments
* $object **object** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2218)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2366](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2366)




### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1031](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1031)




### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L353)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminControllerCore::copyFromPost($object, string $table)
```

Copy datas from $_POST to object



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2261)


#### Arguments
* $object **mixed**
* $table **string** - Object table



### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1082](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1082)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1064](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1064)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L191)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L186)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1164)


#### Arguments
* $msg **string**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1060](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1060)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminControllerCore::displayRequiredFields()
```

prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2539](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2539)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1154)


#### Arguments
* $msg **string**



### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1050](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1050)


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
* Source: [classes/AdminController.php line 2294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2294)


#### Arguments
* $table **string**
* $id_object **integer**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L122)


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
* Source: [classes/AdminController.php line 2104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2104)


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
* Source: [classes/AdminController.php line 2065](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2065)


#### Arguments
* $obj **object** - Object



### <a name="method-getList"></a>getList

```php
mixed AdminControllerCore::getList(integer $id_lang, string $order_by, $order_way, integer $start, integer $limit, $id_lang_shop)
```

Get the current objects' list form the database



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1905](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1905)


#### Arguments
* $id_lang **integer** - Language used for display
* $order_by **string** - ORDER BY clause
* $order_way **mixed**
* $start **integer** - Offset in LIMIT clause
* $limit **integer** - Row count in LIMIT clause
* $id_lang_shop **mixed**



### <a name="method-getTranslationsFlags"></a>getTranslationsFlags

```php
string AdminControllerCore::getTranslationsFlags(array $languages, integer $default_language, string $ids, string $id, $return, boolean $use_vars_instead_of_ids)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2500](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2500)


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
* Source: [classes/AdminController.php line 2035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2035)




### <a name="method-init"></a>init

```php
mixed AdminControllerCore::init()
```

Init context and dependencies, handles POST and GET



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1668](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1668)




### <a name="method-initContent"></a>initContent

```php
mixed AdminGeolocationControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGeolocationController.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/controllers/admin/AdminGeolocationController.php#L139)




### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1393](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1393)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1401](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1401)




### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1172)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminControllerCore::initProcess()
```

Retrieve GET and POST value and translate them to actions



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1750](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1750)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminControllerCore::initToolbar()
```

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L953)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
void AdminControllerCore::initToolbarTitle()
```

set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L298)




### <a name="method-isGeoLiteCityAvailable"></a>isGeoLiteCityAvailable

```php
mixed AdminGeolocationControllerCore::isGeoLiteCityAvailable()
```





* Visibility: **private**
* Source: [controllers/admin/AdminGeolocationController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/controllers/admin/AdminGeolocationController.php#L150)




### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1654](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1654)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class, without &quot;Controller&quot; suffix
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
object AdminControllerCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1001](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1001)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2376](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2376)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminGeolocationControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGeolocationController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/controllers/admin/AdminGeolocationController.php#L88)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminControllerCore::processAdd(string $token)
```

Object creation



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L594)


#### Arguments
* $token **string**



### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
mixed AdminControllerCore::processBulkAffectZone($token)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2469](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2469)


#### Arguments
* $token **mixed**



### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminControllerCore::processBulkDelete($token)
```

Delete multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2428](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2428)


#### Arguments
* $token **mixed**



### <a name="method-processDelete"></a>processDelete

```php
mixed AdminControllerCore::processDelete(string $token)
```

Object Delete



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L529)


#### Arguments
* $token **string**



### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage(string $token)
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L507)


#### Arguments
* $token **string**



### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L377)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminControllerCore::processPosition(string $token)
```

Change object position



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 775](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L775)


#### Arguments
* $token **string**



### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters()
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 798](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L798)




### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave($token)
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L581)


#### Arguments
* $token **mixed**



### <a name="method-processStatus"></a>processStatus

```php
mixed AdminControllerCore::processStatus(string $token)
```

Change object status (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 750](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L750)


#### Arguments
* $token **string**



### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminControllerCore::processUpdate(string $token)
```

Object update



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L642)


#### Arguments
* $token **string**



### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields(string $token)
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 731](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L731)


#### Arguments
* $token **string**



### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions(string $token)
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 832](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L832)


#### Arguments
* $token **string**



### <a name="method-redirect"></a>redirect

```php
mixed AdminControllerCore::redirect()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1077](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1077)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminControllerCore::renderForm()
```

Function used to render the form for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1468](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1468)




### <a name="method-renderList"></a>renderList

```php
mixed AdminControllerCore::renderList()
```

Function used to render the list to display for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1421](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1421)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminGeolocationControllerCore::renderOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGeolocationController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/controllers/admin/AdminGeolocationController.php#L132)




### <a name="method-renderView"></a>renderView

```php
mixed AdminControllerCore::renderView()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1453](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1453)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L143)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1524](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1524)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 1568](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1568)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Controller.php#L196)


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
* Source: [classes/AdminController.php line 1597](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L1597)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - the classname (without &quot;Controller&quot; suffix)
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminControllerCore::updateAssoShop(integer $id_object, integer $new_id_object)
```

Update the associations of shops



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2324](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2324)


#### Arguments
* $id_object **integer**
* $new_id_object **integer**



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2387)


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
* Source: [classes/AdminController.php line 2345](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2345)


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
* Source: [classes/AdminController.php line 2119](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2119)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L338)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/AdminController.php line 2210](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/AdminController.php#L2210)



