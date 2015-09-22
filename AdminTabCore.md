AdminTabCore
===============






* Class name: AdminTabCore
* This is an **abstract** class
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* This class is defined in [classes/AdminTab.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L30)





Properties
----------

* [$id](#property-$id)
* [$table](#property-$table)
* [$identifier](#property-$identifier)
* [$className](#property-$className)
* [$token](#property-$token)
* [$lang](#property-$lang)
* [$edit](#property-$edit)
* [$view](#property-$view)
* [$delete](#property-$delete)
* [$deleted](#property-$deleted)
* [$duplicate](#property-$duplicate)
* [$noLink](#property-$noLink)
* [$requiredDatabase](#property-$requiredDatabase)
* [$colorOnBackground](#property-$colorOnBackground)
* [$_select](#property-$_select)
* [$_join](#property-$_join)
* [$_where](#property-$_where)
* [$_group](#property-$_group)
* [$_having](#property-$_having)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$imageType](#property-$imageType)
* [$fieldsDisplay](#property-$fieldsDisplay)
* [$optionTitle](#property-$optionTitle)
* [$shopLinkType](#property-$shopLinkType)
* [$shopShareDatas](#property-$shopShareDatas)
* [$_list](#property-$_list)
* [$_listTotal](#property-$_listTotal)
* [$_filter](#property-$_filter)
* [$_tmpTableFilter](#property-$_tmpTableFilter)
* [$_pagination](#property-$_pagination)
* [$_orderBy](#property-$_orderBy)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_orderWay](#property-$_orderWay)
* [$maxImageSize](#property-$maxImageSize)
* [$_errors](#property-$_errors)
* [$_conf](#property-$_conf)
* [$_object](#property-$_object)
* [$tabAccess](#property-$tabAccess)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$currentIndex](#property-$currentIndex)
* [$smarty](#property-$smarty)
* [$identifiersDnd](#property-$identifiersDnd)
* [$_redirect](#property-$_redirect)
* [$formOptions](#property-$formOptions)
* [$_fieldsOptions](#property-$_fieldsOptions)
* [$optionsList](#property-$optionsList)
* [$context](#property-$context)
* [$_languages](#property-$_languages)
* [$_defaultFormLanguage](#property-$_defaultFormLanguage)
* [$_includeObj](#property-$_includeObj)
* [$_includeVars](#property-$_includeVars)
* [$_includeContainer](#property-$_includeContainer)
* [$ajax](#property-$ajax)
* [$ignore_sleep](#property-$ignore_sleep)
* [$tabParenting](#property-$tabParenting)

Methods
-------
* [__construct](#method-__construct)
* [l](#method-l)
* [displayAjax](#method-displayAjax)
* [display](#method-display)
* [displayRequiredFields](#method-displayRequiredFields)
* [includeSubTab](#method-includeSubTab)
* [validateRules](#method-validateRules)
* [_childValidation](#method-_childValidation)
* [deleteImage](#method-deleteImage)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcess](#method-ajaxProcess)
* [postProcess](#method-postProcess)
* [updateAssoShop](#method-updateAssoShop)
* [getAssoShop](#method-getAssoShop)
* [updateOptions](#method-updateOptions)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [validateField](#method-validateField)
* [uploadImage](#method-uploadImage)
* [postImage](#method-postImage)
* [copyFromPost](#method-copyFromPost)
* [displayErrors](#method-displayErrors)
* [displayWarning](#method-displayWarning)
* [displayConf](#method-displayConf)
* [getList](#method-getList)
* [displayImage](#method-displayImage)
* [displayListHeader](#method-displayListHeader)
* [displayTop](#method-displayTop)
* [displayList](#method-displayList)
* [displayListContent](#method-displayListContent)
* [displayAddButton](#method-displayAddButton)
* [_displayEnableLink](#method-_displayEnableLink)
* [_displayDuplicate](#method-_displayDuplicate)
* [_displayViewLink](#method-_displayViewLink)
* [_displayEditLink](#method-_displayEditLink)
* [_displayDeleteLink](#method-_displayDeleteLink)
* [displayListFooter](#method-displayListFooter)
* [displayOptionsList](#method-displayOptionsList)
* [displayTopOptionCategory](#method-displayTopOptionCategory)
* [displayBottomOptionCategory](#method-displayBottomOptionCategory)
* [displayOptionTypeSelect](#method-displayOptionTypeSelect)
* [displayOptionTypeBool](#method-displayOptionTypeBool)
* [displayOptionTypeRadio](#method-displayOptionTypeRadio)
* [displayOptionTypeText](#method-displayOptionTypeText)
* [displayOptionTypePassword](#method-displayOptionTypePassword)
* [displayOptionTypeTextarea](#method-displayOptionTypeTextarea)
* [displayOptionTypeFile](#method-displayOptionTypeFile)
* [displayOptionTypeImage](#method-displayOptionTypeImage)
* [displayOptionTypeTextLang](#method-displayOptionTypeTextLang)
* [displayOptionTypeTextareaLang](#method-displayOptionTypeTextareaLang)
* [displayOptionTypeSelectLang](#method-displayOptionTypeSelectLang)
* [displayOptionTypePrice](#method-displayOptionTypePrice)
* [displayOptionTypeDisabled](#method-displayOptionTypeDisabled)
* [loadObject](#method-loadObject)
* [getFieldValue](#method-getFieldValue)
* [displayForm](#method-displayForm)
* [viewDetails](#method-viewDetails)
* [beforeDelete](#method-beforeDelete)
* [afterDelete](#method-afterDelete)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [afterImageUpload](#method-afterImageUpload)
* [viewAccess](#method-viewAccess)
* [checkToken](#method-checkToken)
* [displayFlags](#method-displayFlags)
* [filterToField](#method-filterToField)
* [warnDomainName](#method-warnDomainName)
* [displayAssoShop](#method-displayAssoShop)
* [getCurrentUrl](#method-getCurrentUrl)




Properties
----------


### <a name="property-$id"></a>$id

    public integer $id = -1





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L33)


### <a name="property-$table"></a>$table

    public string $table





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L36)


### <a name="property-$identifier"></a>$identifier

    protected string $identifier = false





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L39)


### <a name="property-$className"></a>$className

    public string $className





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L42)


### <a name="property-$token"></a>$token

    public string $token





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L45)


### <a name="property-$lang"></a>$lang

    public boolean $lang = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L48)


### <a name="property-$edit"></a>$edit

    public boolean $edit = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L51)


### <a name="property-$view"></a>$view

    public boolean $view = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L54)


### <a name="property-$delete"></a>$delete

    public boolean $delete = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L57)


### <a name="property-$deleted"></a>$deleted

    public boolean $deleted = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L60)


### <a name="property-$duplicate"></a>$duplicate

    public boolean $duplicate = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L63)


### <a name="property-$noLink"></a>$noLink

    public boolean $noLink = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L66)


### <a name="property-$requiredDatabase"></a>$requiredDatabase

    public boolean $requiredDatabase = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L69)


### <a name="property-$colorOnBackground"></a>$colorOnBackground

    public boolean $colorOnBackground = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L72)


### <a name="property-$_select"></a>$_select

    protected string $_select





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L75)


### <a name="property-$_join"></a>$_join

    protected string $_join





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L78)


### <a name="property-$_where"></a>$_where

    protected string $_where





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L81)


### <a name="property-$_group"></a>$_group

    protected string $_group





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L84)


### <a name="property-$_having"></a>$_having

    protected string $_having





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L87)


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

    public array $fieldImageSettings = array()





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L90)


### <a name="property-$imageType"></a>$imageType

    public string $imageType = 'jpg'





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L93)


### <a name="property-$fieldsDisplay"></a>$fieldsDisplay

    public array $fieldsDisplay = array()





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L96)


### <a name="property-$optionTitle"></a>$optionTitle

    public mixed $optionTitle = null





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L98)


### <a name="property-$shopLinkType"></a>$shopLinkType

    public string $shopLinkType





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L101)


### <a name="property-$shopShareDatas"></a>$shopShareDatas

    public boolean $shopShareDatas = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L104)


### <a name="property-$_list"></a>$_list

    protected array $_list = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L107)


### <a name="property-$_listTotal"></a>$_listTotal

    protected integer $_listTotal





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L110)


### <a name="property-$_filter"></a>$_filter

    protected array $_filter





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L113)


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

    protected array $_tmpTableFilter = ''





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L116)


### <a name="property-$_pagination"></a>$_pagination

    protected array $_pagination = array(20, 50, 100, 300, 1000)





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L119)


### <a name="property-$_orderBy"></a>$_orderBy

    protected string $_orderBy





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L122)


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

    protected string $_defaultOrderBy = false





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L125)


### <a name="property-$_orderWay"></a>$_orderWay

    protected string $_orderWay





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L128)


### <a name="property-$maxImageSize"></a>$maxImageSize

    protected integer $maxImageSize





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L133)


### <a name="property-$_errors"></a>$_errors

    public array $_errors = array()





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L136)


### <a name="property-$_conf"></a>$_conf

    protected array $_conf





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L139)


### <a name="property-$_object"></a>$_object

    protected object $_object = false





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L142)


### <a name="property-$tabAccess"></a>$tabAccess

    public array $tabAccess





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L145)


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

    public string $specificConfirmDelete = null





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L148)


### <a name="property-$currentIndex"></a>$currentIndex

    public mixed $currentIndex





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/AdminTab.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L150)


### <a name="property-$smarty"></a>$smarty

    public mixed $smarty





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L152)


### <a name="property-$identifiersDnd"></a>$identifiersDnd

    protected mixed $identifiersDnd = array('id_product' => 'id_product', 'id_category' => 'id_category_to_move', 'id_cms_category' => 'id_cms_category_to_move', 'id_cms' => 'id_cms', 'id_attribute' => 'id_attribute', 'id_attribute_group' => 'id_attribute_group', 'id_feature' => 'id_feature', 'id_carrier' => 'id_carrier')





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L154)


### <a name="property-$_redirect"></a>$_redirect

    protected boolean $_redirect = true





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L157)


### <a name="property-$formOptions"></a>$formOptions

    protected boolean $formOptions = true





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L160)


### <a name="property-$_fieldsOptions"></a>$_fieldsOptions

    public mixed $_fieldsOptions = array()





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L162)


### <a name="property-$optionsList"></a>$optionsList

    public array $optionsList = array()





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L168)


### <a name="property-$context"></a>$context

    public \Context $context





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L174)


### <a name="property-$_languages"></a>$_languages

    protected mixed $_languages = null





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L176)


### <a name="property-$_defaultFormLanguage"></a>$_defaultFormLanguage

    protected mixed $_defaultFormLanguage = null





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L177)


### <a name="property-$_includeObj"></a>$_includeObj

    protected mixed $_includeObj = array()





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L179)


### <a name="property-$_includeVars"></a>$_includeVars

    protected mixed $_includeVars = false





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L180)


### <a name="property-$_includeContainer"></a>$_includeContainer

    protected mixed $_includeContainer = true





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L181)


### <a name="property-$ajax"></a>$ajax

    public mixed $ajax = false





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L183)


### <a name="property-$ignore_sleep"></a>$ignore_sleep

    public boolean $ignore_sleep = false

if true, ajax-tab will not wait 1 sec



* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/AdminTab.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L189)


### <a name="property-$tabParenting"></a>$tabParenting

    public mixed $tabParenting = array('AdminCms' => 'AdminCmsContent', 'AdminCmsCategories' => 'AdminCmsContent', 'AdminOrdersStates' => 'AdminStatuses', 'AdminAttributeGenerator' => 'AdminProducts', 'AdminAttributes' => 'AdminAttributesGroups', 'AdminFeaturesValues' => 'AdminFeatures', 'AdminReturnStates' => 'AdminStatuses', 'AdminStatsTab' => 'AdminStats')





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/AdminTab.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L191)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminTabCore::__construct()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L202)




### <a name="method-l"></a>l

    string AdminTabCore::l(string $string, string $class, boolean $addslashes, boolean $htmlentities)

Uses translations files to find a translation for a given string (string should be in english).



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L247)


#### Arguments
* $string **string** - &lt;p&gt;term or expression in english&lt;/p&gt;
* $class **string**
* $addslashes **boolean** - &lt;p&gt;if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)&lt;/p&gt;



### <a name="method-displayAjax"></a>displayAjax

    void AdminTabCore::displayAjax()

ajaxDisplay is the default ajax return sytem



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L272)




### <a name="method-display"></a>display

    mixed AdminTabCore::display()

Manage page display (form, list.

..)

* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L278)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

    mixed AdminTabCore::displayRequiredFields()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L315)




### <a name="method-includeSubTab"></a>includeSubTab

    mixed AdminTabCore::includeSubTab($methodname, $actions)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L364)


#### Arguments
* $methodname **mixed**
* $actions **mixed**



### <a name="method-validateRules"></a>validateRules

    mixed AdminTabCore::validateRules(string $className)

Manage page display (form, list.

..)

* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L456)


#### Arguments
* $className **string** - &lt;p&gt;Allow to validate a different class than the current one&lt;/p&gt;



### <a name="method-_childValidation"></a>_childValidation

    mixed AdminTabCore::_childValidation()

Overload this method for custom checking



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L541)




### <a name="method-deleteImage"></a>deleteImage

    mixed AdminTabCore::deleteImage(integer $id)

Overload this method for custom checking



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 551](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L551)


#### Arguments
* $id **integer** - &lt;p&gt;Object id used for deleting images&lt;/p&gt;



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

    void AdminTabCore::ajaxPreProcess()

ajaxPreProcess is a method called in ajax-tab.php before displayConf().



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L582)




### <a name="method-ajaxProcess"></a>ajaxProcess

    void AdminTabCore::ajaxProcess()

ajaxProcess is the default handle method for request with ajax-tab.php



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 591](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L591)




### <a name="method-postProcess"></a>postProcess

    mixed AdminTabCore::postProcess()

Manage page processing



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L598)




### <a name="method-updateAssoShop"></a>updateAssoShop

    mixed AdminTabCore::updateAssoShop($id_object)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 947](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L947)


#### Arguments
* $id_object **mixed**



### <a name="method-getAssoShop"></a>getAssoShop

    mixed AdminTabCore::getAssoShop($table, $id_object)





* Visibility: **protected**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L964)


#### Arguments
* $table **mixed**
* $id_object **mixed**



### <a name="method-updateOptions"></a>updateOptions

    mixed AdminTabCore::updateOptions(string $token)

Update options and preferences



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 988](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L988)


#### Arguments
* $token **string**



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

    mixed AdminTabCore::beforeUpdateOptions()

Can be overriden



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1089)




### <a name="method-validateField"></a>validateField

    mixed AdminTabCore::validateField($value, $field)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1093](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1093)


#### Arguments
* $value **mixed**
* $field **mixed**



### <a name="method-uploadImage"></a>uploadImage

    mixed AdminTabCore::uploadImage($id, $name, $dir, $ext, $width, $height)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1107)


#### Arguments
* $id **mixed**
* $name **mixed**
* $dir **mixed**
* $ext **mixed**
* $width **mixed**
* $height **mixed**



### <a name="method-postImage"></a>postImage

    boolean AdminTabCore::postImage(integer $id)

Overload this method for custom checking



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1150)


#### Arguments
* $id **integer** - &lt;p&gt;Object id used for deleting images&lt;/p&gt;



### <a name="method-copyFromPost"></a>copyFromPost

    mixed AdminTabCore::copyFromPost($object, string $table)

Copy datas from $_POST to object



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1170)


#### Arguments
* $object **mixed**
* $table **string** - &lt;p&gt;Object table&lt;/p&gt;



### <a name="method-displayErrors"></a>displayErrors

    mixed AdminTabCore::displayErrors()

Display errors



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1204)




### <a name="method-displayWarning"></a>displayWarning

    mixed AdminTabCore::displayWarning(string $warn)

Display a warning message



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1237)


#### Arguments
* $warn **string** - &lt;p&gt;Warning message to display&lt;/p&gt;



### <a name="method-displayConf"></a>displayConf

    mixed AdminTabCore::displayConf()

Display confirmations



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1285)




### <a name="method-getList"></a>getList

    mixed AdminTabCore::getList(integer $id_lang, string $orderBy, $orderWay, integer $start, integer $limit, $id_lang_shop)

Get the current objects' list form the database



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1304](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1304)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language used for display&lt;/p&gt;
* $orderBy **string** - &lt;p&gt;ORDER BY clause&lt;/p&gt;
* $orderWay **mixed**
* $start **integer** - &lt;p&gt;Offset in LIMIT clause&lt;/p&gt;
* $limit **integer** - &lt;p&gt;Row count in LIMIT clause&lt;/p&gt;
* $id_lang_shop **mixed**



### <a name="method-displayImage"></a>displayImage

    mixed AdminTabCore::displayImage(integer $id, string $image, integer $size, integer $id_image, string $token, boolean $disableCache)

Display image aside object form



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1406)


#### Arguments
* $id **integer** - &lt;p&gt;Object id&lt;/p&gt;
* $image **string** - &lt;p&gt;Local image filepath&lt;/p&gt;
* $size **integer** - &lt;p&gt;Image width&lt;/p&gt;
* $id_image **integer** - &lt;p&gt;Image id (for products with several images)&lt;/p&gt;
* $token **string** - &lt;p&gt;Employee token used in the image deletion link&lt;/p&gt;
* $disableCache **boolean** - &lt;p&gt;When turned on a timestamp will be added to the image URI to disable the HTTP cache&lt;/p&gt;



### <a name="method-displayListHeader"></a>displayListHeader

    mixed AdminTabCore::displayListHeader($token)

Display list header (filtering, pagination and column names)



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1425)


#### Arguments
* $token **mixed**



### <a name="method-displayTop"></a>displayTop

    mixed AdminTabCore::displayTop()





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1623](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1623)




### <a name="method-displayList"></a>displayList

    mixed AdminTabCore::displayList()

Display list



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1630](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1630)




### <a name="method-displayListContent"></a>displayListContent

    mixed AdminTabCore::displayListContent($token)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1657)


#### Arguments
* $token **mixed**



### <a name="method-displayAddButton"></a>displayAddButton

    mixed AdminTabCore::displayAddButton()





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1786](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1786)




### <a name="method-_displayEnableLink"></a>_displayEnableLink

    mixed AdminTabCore::_displayEnableLink($token, $id, $value, $active, $id_category, $id_product)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1791](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1791)


#### Arguments
* $token **mixed**
* $id **mixed**
* $value **mixed**
* $active **mixed**
* $id_category **mixed**
* $id_product **mixed**



### <a name="method-_displayDuplicate"></a>_displayDuplicate

    mixed AdminTabCore::_displayDuplicate($token, $id)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1801](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1801)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-_displayViewLink"></a>_displayViewLink

    mixed AdminTabCore::_displayViewLink($token, $id)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1811)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-_displayEditLink"></a>_displayEditLink

    mixed AdminTabCore::_displayEditLink($token, $id)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1820](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1820)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-_displayDeleteLink"></a>_displayDeleteLink

    mixed AdminTabCore::_displayDeleteLink($token, $id)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1829)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-displayListFooter"></a>displayListFooter

    mixed AdminTabCore::displayListFooter($token)

Close list table and submit button



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1843](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1843)


#### Arguments
* $token **mixed**



### <a name="method-displayOptionsList"></a>displayOptionsList

    mixed AdminTabCore::displayOptionsList()

Options lists



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1863](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1863)




### <a name="method-displayTopOptionCategory"></a>displayTopOptionCategory

    mixed AdminTabCore::displayTopOptionCategory($category, $data)

Can be overriden



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1990](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1990)


#### Arguments
* $category **mixed**
* $data **mixed**



### <a name="method-displayBottomOptionCategory"></a>displayBottomOptionCategory

    mixed AdminTabCore::displayBottomOptionCategory($category, $data)

Can be overriden



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 1997](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L1997)


#### Arguments
* $category **mixed**
* $data **mixed**



### <a name="method-displayOptionTypeSelect"></a>displayOptionTypeSelect

    mixed AdminTabCore::displayOptionTypeSelect($key, $field, $value)

Type = select



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2004](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2004)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeBool"></a>displayOptionTypeBool

    mixed AdminTabCore::displayOptionTypeBool($key, $field, $value)

Type = bool



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2016](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2016)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeRadio"></a>displayOptionTypeRadio

    mixed AdminTabCore::displayOptionTypeRadio($key, $field, $value)

Type = radio



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2030](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2030)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeText"></a>displayOptionTypeText

    mixed AdminTabCore::displayOptionTypeText($key, $field, $value)

Type = text



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2041](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2041)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypePassword"></a>displayOptionTypePassword

    mixed AdminTabCore::displayOptionTypePassword($key, $field, $value)

Type = password



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2049](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2049)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeTextarea"></a>displayOptionTypeTextarea

    mixed AdminTabCore::displayOptionTypeTextarea($key, $field, $value)

Type = textarea



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2057](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2057)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeFile"></a>displayOptionTypeFile

    mixed AdminTabCore::displayOptionTypeFile($key, $field, $value)

Type = file



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2065](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2065)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeImage"></a>displayOptionTypeImage

    mixed AdminTabCore::displayOptionTypeImage($key, $field, $value)

Type = image



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2076](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2076)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeTextLang"></a>displayOptionTypeTextLang

    mixed AdminTabCore::displayOptionTypeTextLang($key, $field, $value)

Type = textLang



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2116)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeTextareaLang"></a>displayOptionTypeTextareaLang

    mixed AdminTabCore::displayOptionTypeTextareaLang($key, $field, $value)

Type = TextareaLang



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2131)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeSelectLang"></a>displayOptionTypeSelectLang

    mixed AdminTabCore::displayOptionTypeSelectLang($key, $field, $value)

Type = selectLang



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2147)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypePrice"></a>displayOptionTypePrice

    mixed AdminTabCore::displayOptionTypePrice($key, $field, $value)

Type = price



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2165)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeDisabled"></a>displayOptionTypeDisabled

    mixed AdminTabCore::displayOptionTypeDisabled($key, $field, $value)

Type = disabled



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2175)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-loadObject"></a>loadObject

    object AdminTabCore::loadObject(boolean $opt)

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2187)


#### Arguments
* $opt **boolean** - &lt;p&gt;Return an empty object if load fail&lt;/p&gt;



### <a name="method-getFieldValue"></a>getFieldValue

    string AdminTabCore::getFieldValue(object $obj, string $key, integer $id_lang, $id_shop)

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2219)


#### Arguments
* $obj **object** - &lt;p&gt;Object&lt;/p&gt;
* $key **string** - &lt;p&gt;Field name&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Language id (optional)&lt;/p&gt;
* $id_shop **mixed**



### <a name="method-displayForm"></a>displayForm

    mixed AdminTabCore::displayForm($firstCall)

Display form



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2237)


#### Arguments
* $firstCall **mixed**



### <a name="method-viewDetails"></a>viewDetails

    mixed AdminTabCore::viewDetails()

Display object details



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2283)




### <a name="method-beforeDelete"></a>beforeDelete

    boolean AdminTabCore::beforeDelete(object $object)

Called before deletion



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2293)


#### Arguments
* $object **object** - &lt;p&gt;Object&lt;/p&gt;



### <a name="method-afterDelete"></a>afterDelete

    boolean AdminTabCore::afterDelete(object $object, $oldId)

Called before deletion



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2304](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2304)


#### Arguments
* $object **object** - &lt;p&gt;Object&lt;/p&gt;
* $oldId **mixed**



### <a name="method-afterAdd"></a>afterAdd

    mixed AdminTabCore::afterAdd($object)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2309](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2309)


#### Arguments
* $object **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

    mixed AdminTabCore::afterUpdate($object)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2314)


#### Arguments
* $object **mixed**



### <a name="method-afterImageUpload"></a>afterImageUpload

    boolean AdminTabCore::afterImageUpload()

Check rights to view the current tab



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2325](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2325)




### <a name="method-viewAccess"></a>viewAccess

    boolean AdminTabCore::viewAccess($disable)

Check rights to view the current tab



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2336)


#### Arguments
* $disable **mixed**



### <a name="method-checkToken"></a>checkToken

    mixed AdminTabCore::checkToken()

Check for security token



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2353)




### <a name="method-displayFlags"></a>displayFlags

    mixed AdminTabCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)

Display flags in forms for translations



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2369)


#### Arguments
* $languages **array** - &lt;p&gt;All languages available&lt;/p&gt;
* $default_language **integer** - &lt;p&gt;Default language id&lt;/p&gt;
* $ids **string** - &lt;p&gt;Multilingual div ids in form&lt;/p&gt;
* $id **string** - &lt;p&gt;Current div id]&lt;/p&gt;
* $return **boolean** - &lt;p&gt;define the return way : false for a display, true for a return&lt;/p&gt;
* $use_vars_instead_of_ids **boolean** - &lt;p&gt;use an js vars instead of ids seperate by &quot;¤&quot;&lt;/p&gt;



### <a name="method-filterToField"></a>filterToField

    mixed AdminTabCore::filterToField($key, $filter)





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2400](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2400)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-warnDomainName"></a>warnDomainName

    mixed AdminTabCore::warnDomainName()





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2413](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2413)




### <a name="method-displayAssoShop"></a>displayAssoShop

    mixed AdminTabCore::displayAssoShop()





* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2423](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2423)




### <a name="method-getCurrentUrl"></a>getCurrentUrl

    string AdminTabCore::getCurrentUrl(array $remove)

Get current URL



* Visibility: **protected**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/AdminTab.php line 2525](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AdminTab.php#L2525)


#### Arguments
* $remove **array** - &lt;p&gt;List of keys to remove from URL&lt;/p&gt;


