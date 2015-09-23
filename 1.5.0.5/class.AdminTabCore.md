Class AdminTabCore
=====================





* Class name: AdminTabCore
* This is an **abstract** class
* Source: [classes/AdminTab.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L28)


Contents
--------


### Properties

* [$_conf](#property-$_conf)
* [$_defaultFormLanguage](#property-$_defaultFormLanguage)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_errors](#property-$_errors)
* [$_fieldsOptions](#property-$_fieldsOptions)
* [$_filter](#property-$_filter)
* [$_group](#property-$_group)
* [$_having](#property-$_having)
* [$_includeContainer](#property-$_includeContainer)
* [$_includeObj](#property-$_includeObj)
* [$_includeVars](#property-$_includeVars)
* [$_join](#property-$_join)
* [$_languages](#property-$_languages)
* [$_list](#property-$_list)
* [$_listTotal](#property-$_listTotal)
* [$_object](#property-$_object)
* [$_orderBy](#property-$_orderBy)
* [$_orderWay](#property-$_orderWay)
* [$_pagination](#property-$_pagination)
* [$_redirect](#property-$_redirect)
* [$_select](#property-$_select)
* [$_tmpTableFilter](#property-$_tmpTableFilter)
* [$_where](#property-$_where)
* [$ajax](#property-$ajax)
* [$className](#property-$className)
* [$colorOnBackground](#property-$colorOnBackground)
* [$context](#property-$context)
* [$currentIndex](#property-$currentIndex)
* [$delete](#property-$delete)
* [$deleted](#property-$deleted)
* [$duplicate](#property-$duplicate)
* [$edit](#property-$edit)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$fieldsDisplay](#property-$fieldsDisplay)
* [$formOptions](#property-$formOptions)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$identifiersDnd](#property-$identifiersDnd)
* [$ignore_sleep](#property-$ignore_sleep)
* [$imageType](#property-$imageType)
* [$lang](#property-$lang)
* [$maxImageSize](#property-$maxImageSize)
* [$noLink](#property-$noLink)
* [$noTabLink](#property-$noTabLink)
* [$optionTitle](#property-$optionTitle)
* [$optionsList](#property-$optionsList)
* [$requiredDatabase](#property-$requiredDatabase)
* [$shopLinkType](#property-$shopLinkType)
* [$shopShareDatas](#property-$shopShareDatas)
* [$smarty](#property-$smarty)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$tabAccess](#property-$tabAccess)
* [$tabParenting](#property-$tabParenting)
* [$table](#property-$table)
* [$token](#property-$token)
* [$view](#property-$view)

### Methods

* [__construct](#method-__construct)
* [_childValidation](#method-_childValidation)
* [_displayDeleteLink](#method-_displayDeleteLink)
* [_displayDuplicate](#method-_displayDuplicate)
* [_displayEditLink](#method-_displayEditLink)
* [_displayEnableLink](#method-_displayEnableLink)
* [_displayViewLink](#method-_displayViewLink)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcess](#method-ajaxProcess)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [checkToken](#method-checkToken)
* [copyFromPost](#method-copyFromPost)
* [deleteImage](#method-deleteImage)
* [display](#method-display)
* [displayAddButton](#method-displayAddButton)
* [displayAjax](#method-displayAjax)
* [displayAssoShop](#method-displayAssoShop)
* [displayBottomOptionCategory](#method-displayBottomOptionCategory)
* [displayConf](#method-displayConf)
* [displayErrors](#method-displayErrors)
* [displayFlags](#method-displayFlags)
* [displayForm](#method-displayForm)
* [displayImage](#method-displayImage)
* [displayList](#method-displayList)
* [displayListContent](#method-displayListContent)
* [displayListFooter](#method-displayListFooter)
* [displayListHeader](#method-displayListHeader)
* [displayOptionTypeBool](#method-displayOptionTypeBool)
* [displayOptionTypeDisabled](#method-displayOptionTypeDisabled)
* [displayOptionTypeFile](#method-displayOptionTypeFile)
* [displayOptionTypeImage](#method-displayOptionTypeImage)
* [displayOptionTypePassword](#method-displayOptionTypePassword)
* [displayOptionTypePrice](#method-displayOptionTypePrice)
* [displayOptionTypeRadio](#method-displayOptionTypeRadio)
* [displayOptionTypeSelect](#method-displayOptionTypeSelect)
* [displayOptionTypeSelectLang](#method-displayOptionTypeSelectLang)
* [displayOptionTypeText](#method-displayOptionTypeText)
* [displayOptionTypeTextLang](#method-displayOptionTypeTextLang)
* [displayOptionTypeTextarea](#method-displayOptionTypeTextarea)
* [displayOptionTypeTextareaLang](#method-displayOptionTypeTextareaLang)
* [displayOptionsList](#method-displayOptionsList)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayTop](#method-displayTop)
* [displayTopOptionCategory](#method-displayTopOptionCategory)
* [displayWarning](#method-displayWarning)
* [filterToField](#method-filterToField)
* [getAssoShop](#method-getAssoShop)
* [getCurrentUrl](#method-getCurrentUrl)
* [getFieldValue](#method-getFieldValue)
* [getList](#method-getList)
* [includeSubTab](#method-includeSubTab)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [updateAssoShop](#method-updateAssoShop)
* [updateOptions](#method-updateOptions)
* [uploadImage](#method-uploadImage)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)
* [warnDomainName](#method-warnDomainName)




Properties
----------


### <a name="property-$_conf"></a>$_conf

```php
protected array $_conf
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L137).


### <a name="property-$_defaultFormLanguage"></a>$_defaultFormLanguage

```php
protected mixed $_defaultFormLanguage = NULL
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L175).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L123).


### <a name="property-$_errors"></a>$_errors

```php
public array $_errors = array()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L134).


### <a name="property-$_fieldsOptions"></a>$_fieldsOptions

```php
public mixed $_fieldsOptions = array()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L160).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L111).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L82).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L85).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L179).


### <a name="property-$_includeObj"></a>$_includeObj

```php
protected mixed $_includeObj = array()
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L177).


### <a name="property-$_includeVars"></a>$_includeVars

```php
protected mixed $_includeVars = false
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L178).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L76).


### <a name="property-$_languages"></a>$_languages

```php
protected mixed $_languages = NULL
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L174).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L105).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L108).


### <a name="property-$_object"></a>$_object

```php
protected object $_object = false
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L140).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L120).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L126).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L117).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L155).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L73).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L114).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L79).


### <a name="property-$ajax"></a>$ajax

```php
public mixed $ajax = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L181).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L40).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
public boolean $colorOnBackground = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L70).


### <a name="property-$context"></a>$context

```php
public \Context $context
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L172).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AdminTab.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L148).


### <a name="property-$delete"></a>$delete

```php
public boolean $delete = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L55).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L58).


### <a name="property-$duplicate"></a>$duplicate

```php
public boolean $duplicate = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L61).


### <a name="property-$edit"></a>$edit

```php
public boolean $edit = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L49).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L88).


### <a name="property-$fieldsDisplay"></a>$fieldsDisplay

```php
public array $fieldsDisplay = array()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L94).


### <a name="property-$formOptions"></a>$formOptions

```php
protected boolean $formOptions = true
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L158).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L31).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L37).


### <a name="property-$identifiersDnd"></a>$identifiersDnd

```php
protected mixed $identifiersDnd = array('id_product' => 'id_product', 'id_category' => 'id_category_to_move', 'id_cms_category' => 'id_cms_category_to_move', 'id_cms' => 'id_cms', 'id_attribute' => 'id_attribute', 'id_attribute_group' => 'id_attribute_group', 'id_feature' => 'id_feature', 'id_carrier' => 'id_carrier')
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L152).


### <a name="property-$ignore_sleep"></a>$ignore_sleep

```php
public boolean $ignore_sleep = false
```

if true, ajax-tab will not wait 1 sec



* Visibility: **public**
* Source: [classes/AdminTab.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L187).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L91).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L46).


### <a name="property-$maxImageSize"></a>$maxImageSize

```php
protected integer $maxImageSize
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L131).


### <a name="property-$noLink"></a>$noLink

```php
public boolean $noLink = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L64).


### <a name="property-$noTabLink"></a>$noTabLink

```php
public array $noTabLink = array('AdminCatalog', 'AdminTools', 'AdminStock', 'AdminAccounting')
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L203).


### <a name="property-$optionTitle"></a>$optionTitle

```php
public mixed $optionTitle = null
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L96).


### <a name="property-$optionsList"></a>$optionsList

```php
public array $optionsList = array()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L166).


### <a name="property-$requiredDatabase"></a>$requiredDatabase

```php
public boolean $requiredDatabase = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L67).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L99).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public boolean $shopShareDatas = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L102).


### <a name="property-$smarty"></a>$smarty

```php
public mixed $smarty
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L150).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
public string $specificConfirmDelete = NULL
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L146).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L143).


### <a name="property-$tabParenting"></a>$tabParenting

```php
public mixed $tabParenting = array('AdminCms' => 'AdminCmsContent', 'AdminCmsCategories' => 'AdminCmsContent', 'AdminOrdersStates' => 'AdminStatuses', 'AdminAttributeGenerator' => 'AdminProducts', 'AdminAttributes' => 'AdminAttributesGroups', 'AdminFeaturesValues' => 'AdminFeatures', 'AdminReturnStates' => 'AdminStatuses', 'AdminStatsTab' => 'AdminStats')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AdminTab.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L189).


### <a name="property-$table"></a>$table

```php
public string $table
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L34).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L43).


### <a name="property-$view"></a>$view

```php
public boolean $view = false
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L52).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTabCore::__construct()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L205)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminTabCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* Source: [classes/AdminTab.php line 511](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L511)




### <a name="method-_displayDeleteLink"></a>_displayDeleteLink

```php
mixed AdminTabCore::_displayDeleteLink($token, $id)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1783](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1783)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-_displayDuplicate"></a>_displayDuplicate

```php
mixed AdminTabCore::_displayDuplicate($token, $id)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1753)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-_displayEditLink"></a>_displayEditLink

```php
mixed AdminTabCore::_displayEditLink($token, $id)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1774](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1774)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-_displayEnableLink"></a>_displayEnableLink

```php
mixed AdminTabCore::_displayEnableLink($token, $id, $value, $active, $id_category, $id_product)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1745](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1745)


#### Arguments
* $token **mixed**
* $id **mixed**
* $value **mixed**
* $active **mixed**
* $id_category **mixed**
* $id_product **mixed**



### <a name="method-_displayViewLink"></a>_displayViewLink

```php
mixed AdminTabCore::_displayViewLink($token, $id)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1765](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1765)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminTabCore::afterAdd($object)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 2241](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2241)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminTabCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* Source: [classes/AdminTab.php line 2239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2239)


#### Arguments
* $object **object** - Object
* $oldId **mixed**



### <a name="method-afterImageUpload"></a>afterImageUpload

```php
boolean AdminTabCore::afterImageUpload()
```

Check rights to view the current tab



* Visibility: **protected**
* Source: [classes/AdminTab.php line 2251](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2251)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminTabCore::afterUpdate($object)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 2243](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2243)


#### Arguments
* $object **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
void AdminTabCore::ajaxPreProcess()
```

ajaxPreProcess is a method called in ajax-tab.php before displayConf().



* Visibility: **public**
* Source: [classes/AdminTab.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L546)




### <a name="method-ajaxProcess"></a>ajaxProcess

```php
void AdminTabCore::ajaxProcess()
```

ajaxProcess is the default handle method for request with ajax-tab.php



* Visibility: **public**
* Source: [classes/AdminTab.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L555)




### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminTabCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* Source: [classes/AdminTab.php line 2231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2231)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminTabCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* Source: [classes/AdminTab.php line 1052](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1052)




### <a name="method-checkToken"></a>checkToken

```php
mixed AdminTabCore::checkToken()
```

Check for security token



* Visibility: **public**
* Source: [classes/AdminTab.php line 2276](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2276)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminTabCore::copyFromPost($object, string $table)
```

Copy datas from $_POST to object



* Visibility: **protected**
* Source: [classes/AdminTab.php line 1133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1133)


#### Arguments
* $object **mixed**
* $table **string** - Object table



### <a name="method-deleteImage"></a>deleteImage

```php
mixed AdminTabCore::deleteImage(integer $id)
```

Overload this method for custom checking



* Visibility: **public**
* Source: [classes/AdminTab.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L519)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-display"></a>display

```php
mixed AdminTabCore::display()
```

Manage page display (form, list.

..)

* Visibility: **public**
* Source: [classes/AdminTab.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L276)




### <a name="method-displayAddButton"></a>displayAddButton

```php
mixed AdminTabCore::displayAddButton()
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1740)




### <a name="method-displayAjax"></a>displayAjax

```php
void AdminTabCore::displayAjax()
```

ajaxDisplay is the default ajax return sytem



* Visibility: **public**
* Source: [classes/AdminTab.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L270)




### <a name="method-displayAssoShop"></a>displayAssoShop

```php
mixed AdminTabCore::displayAssoShop($type)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 2333](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2333)


#### Arguments
* $type **mixed**



### <a name="method-displayBottomOptionCategory"></a>displayBottomOptionCategory

```php
mixed AdminTabCore::displayBottomOptionCategory($category, $data)
```

Can be overriden



* Visibility: **public**
* Source: [classes/AdminTab.php line 1945](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1945)


#### Arguments
* $category **mixed**
* $data **mixed**



### <a name="method-displayConf"></a>displayConf

```php
mixed AdminTabCore::displayConf()
```

Display confirmations



* Visibility: **public**
* Source: [classes/AdminTab.php line 1245](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1245)




### <a name="method-displayErrors"></a>displayErrors

```php
mixed AdminTabCore::displayErrors()
```

Display errors



* Visibility: **public**
* Source: [classes/AdminTab.php line 1163](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1163)




### <a name="method-displayFlags"></a>displayFlags

```php
mixed AdminTabCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* Source: [classes/AdminTab.php line 2292](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2292)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-displayForm"></a>displayForm

```php
mixed AdminTabCore::displayForm($firstCall)
```

Display form



* Visibility: **public**
* Source: [classes/AdminTab.php line 2182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2182)


#### Arguments
* $firstCall **mixed**



### <a name="method-displayImage"></a>displayImage

```php
mixed AdminTabCore::displayImage(integer $id, string $image, integer $size, integer $id_image, string $token, boolean $disableCache)
```

Display image aside object form



* Visibility: **public**
* Source: [classes/AdminTab.php line 1370](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1370)


#### Arguments
* $id **integer** - Object id
* $image **string** - Local image filepath
* $size **integer** - Image width
* $id_image **integer** - Image id (for products with several images)
* $token **string** - Employee token used in the image deletion link
* $disableCache **boolean** - When turned on a timestamp will be added to the image URI to disable the HTTP cache



### <a name="method-displayList"></a>displayList

```php
mixed AdminTabCore::displayList()
```

Display list



* Visibility: **public**
* Source: [classes/AdminTab.php line 1581](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1581)




### <a name="method-displayListContent"></a>displayListContent

```php
mixed AdminTabCore::displayListContent($token)
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 1607](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1607)


#### Arguments
* $token **mixed**



### <a name="method-displayListFooter"></a>displayListFooter

```php
mixed AdminTabCore::displayListFooter($token)
```

Close list table and submit button



* Visibility: **public**
* Source: [classes/AdminTab.php line 1797](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1797)


#### Arguments
* $token **mixed**



### <a name="method-displayListHeader"></a>displayListHeader

```php
mixed AdminTabCore::displayListHeader($token)
```

Display list header (filtering, pagination and column names)



* Visibility: **public**
* Source: [classes/AdminTab.php line 1387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1387)


#### Arguments
* $token **mixed**



### <a name="method-displayOptionTypeBool"></a>displayOptionTypeBool

```php
mixed AdminTabCore::displayOptionTypeBool($key, $field, $value)
```

Type = bool



* Visibility: **public**
* Source: [classes/AdminTab.php line 1963](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1963)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeDisabled"></a>displayOptionTypeDisabled

```php
mixed AdminTabCore::displayOptionTypeDisabled($key, $field, $value)
```

Type = disabled



* Visibility: **public**
* Source: [classes/AdminTab.php line 2122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2122)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeFile"></a>displayOptionTypeFile

```php
mixed AdminTabCore::displayOptionTypeFile($key, $field, $value)
```

Type = file



* Visibility: **public**
* Source: [classes/AdminTab.php line 2011](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2011)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeImage"></a>displayOptionTypeImage

```php
mixed AdminTabCore::displayOptionTypeImage($key, $field, $value)
```

Type = image



* Visibility: **public**
* Source: [classes/AdminTab.php line 2021](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2021)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypePassword"></a>displayOptionTypePassword

```php
mixed AdminTabCore::displayOptionTypePassword($key, $field, $value)
```

Type = password



* Visibility: **public**
* Source: [classes/AdminTab.php line 1995](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1995)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypePrice"></a>displayOptionTypePrice

```php
mixed AdminTabCore::displayOptionTypePrice($key, $field, $value)
```

Type = price



* Visibility: **public**
* Source: [classes/AdminTab.php line 2112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2112)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeRadio"></a>displayOptionTypeRadio

```php
mixed AdminTabCore::displayOptionTypeRadio($key, $field, $value)
```

Type = radio



* Visibility: **public**
* Source: [classes/AdminTab.php line 1977](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1977)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeSelect"></a>displayOptionTypeSelect

```php
mixed AdminTabCore::displayOptionTypeSelect($key, $field, $value)
```

Type = select



* Visibility: **public**
* Source: [classes/AdminTab.php line 1952](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1952)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeSelectLang"></a>displayOptionTypeSelectLang

```php
mixed AdminTabCore::displayOptionTypeSelectLang($key, $field, $value)
```

Type = selectLang



* Visibility: **public**
* Source: [classes/AdminTab.php line 2094](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2094)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeText"></a>displayOptionTypeText

```php
mixed AdminTabCore::displayOptionTypeText($key, $field, $value)
```

Type = text



* Visibility: **public**
* Source: [classes/AdminTab.php line 1987](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1987)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeTextLang"></a>displayOptionTypeTextLang

```php
mixed AdminTabCore::displayOptionTypeTextLang($key, $field, $value)
```

Type = textLang



* Visibility: **public**
* Source: [classes/AdminTab.php line 2061](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2061)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeTextarea"></a>displayOptionTypeTextarea

```php
mixed AdminTabCore::displayOptionTypeTextarea($key, $field, $value)
```

Type = textarea



* Visibility: **public**
* Source: [classes/AdminTab.php line 2003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2003)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeTextareaLang"></a>displayOptionTypeTextareaLang

```php
mixed AdminTabCore::displayOptionTypeTextareaLang($key, $field, $value)
```

Type = TextareaLang



* Visibility: **public**
* Source: [classes/AdminTab.php line 2077](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2077)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionsList"></a>displayOptionsList

```php
mixed AdminTabCore::displayOptionsList()
```

Options lists



* Visibility: **public**
* Source: [classes/AdminTab.php line 1815](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1815)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminTabCore::displayRequiredFields()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L318)




### <a name="method-displayTop"></a>displayTop

```php
mixed AdminTabCore::displayTop()
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 1574](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1574)




### <a name="method-displayTopOptionCategory"></a>displayTopOptionCategory

```php
mixed AdminTabCore::displayTopOptionCategory($category, $data)
```

Can be overriden



* Visibility: **public**
* Source: [classes/AdminTab.php line 1938](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1938)


#### Arguments
* $category **mixed**
* $data **mixed**



### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminTabCore::displayWarning(string $warn)
```

Display a warning message



* Visibility: **public**
* Source: [classes/AdminTab.php line 1197](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1197)


#### Arguments
* $warn **string** - Warning message to display



### <a name="method-filterToField"></a>filterToField

```php
mixed AdminTabCore::filterToField($key, $filter)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 2314](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2314)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-getAssoShop"></a>getAssoShop

```php
mixed AdminTabCore::getAssoShop($table, $id_object)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/AdminTab.php line 926](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L926)


#### Arguments
* $table **mixed**
* $id_object **mixed**



### <a name="method-getCurrentUrl"></a>getCurrentUrl

```php
string AdminTabCore::getCurrentUrl(array $remove)
```

Get current URL



* Visibility: **protected**
* Source: [classes/AdminTab.php line 2442](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2442)


#### Arguments
* $remove **array** - List of keys to remove from URL



### <a name="method-getFieldValue"></a>getFieldValue

```php
string AdminTabCore::getFieldValue(object $obj, string $key, integer $id_lang, $id_shop)
```

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* Source: [classes/AdminTab.php line 2166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2166)


#### Arguments
* $obj **object** - Object
* $key **string** - Field name
* $id_lang **integer** - Language id (optional)
* $id_shop **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminTabCore::getList(integer $id_lang, string $orderBy, $orderWay, integer $start, integer $limit, $id_lang_shop)
```

Get the current objects' list form the database



* Visibility: **public**
* Source: [classes/AdminTab.php line 1263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1263)


#### Arguments
* $id_lang **integer** - Language used for display
* $orderBy **string** - ORDER BY clause
* $orderWay **mixed**
* $start **integer** - Offset in LIMIT clause
* $limit **integer** - Row count in LIMIT clause
* $id_lang_shop **mixed**



### <a name="method-includeSubTab"></a>includeSubTab

```php
mixed AdminTabCore::includeSubTab($methodname, $actions)
```





* Visibility: **public**
* Source: [classes/AdminTab.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L363)


#### Arguments
* $methodname **mixed**
* $actions **mixed**



### <a name="method-l"></a>l

```php
string AdminTabCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **protected**
* Source: [classes/AdminTab.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L245)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string**
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
object AdminTabCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* Source: [classes/AdminTab.php line 2134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2134)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-postImage"></a>postImage

```php
boolean AdminTabCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* Source: [classes/AdminTab.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1116)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminTabCore::postProcess()
```

Manage page processing



* Visibility: **public**
* Source: [classes/AdminTab.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L562)




### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminTabCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 912](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L912)


#### Arguments
* $id_object **mixed**



### <a name="method-updateOptions"></a>updateOptions

```php
mixed AdminTabCore::updateOptions(string $token)
```

Update options and preferences



* Visibility: **protected**
* Source: [classes/AdminTab.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L953)


#### Arguments
* $token **string**



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminTabCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1073](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1073)


#### Arguments
* $id **mixed**
* $name **mixed**
* $dir **mixed**
* $ext **mixed**
* $width **mixed**
* $height **mixed**



### <a name="method-validateField"></a>validateField

```php
mixed AdminTabCore::validateField($value, $field)
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 1056](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L1056)


#### Arguments
* $value **mixed**
* $field **mixed**



### <a name="method-validateRules"></a>validateRules

```php
mixed AdminTabCore::validateRules(string $className)
```

Manage page display (form, list.

..)

* Visibility: **public**
* Source: [classes/AdminTab.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L443)


#### Arguments
* $className **string** - Allow to validate a different class than the current one



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminTabCore::viewAccess($disable)
```

Check rights to view the current tab



* Visibility: **public**
* Source: [classes/AdminTab.php line 2261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2261)


#### Arguments
* $disable **mixed**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminTabCore::viewDetails()
```

Display object details



* Visibility: **public**
* Source: [classes/AdminTab.php line 2223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2223)




### <a name="method-warnDomainName"></a>warnDomainName

```php
mixed AdminTabCore::warnDomainName()
```





* Visibility: **protected**
* Source: [classes/AdminTab.php line 2324](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/AdminTab.php#L2324)



