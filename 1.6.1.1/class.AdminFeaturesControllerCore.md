Class AdminFeaturesControllerCore
=====================





* Class name: AdminFeaturesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminFeaturesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L30)



Properties
----------

* [$bootstrap](#property-$bootstrap)
* [$feature_name](#property-$feature_name)
* [$object](#property-$object)
* [$position_identifier](#property-$position_identifier)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initFormFeatureValue](#method-initFormFeatureValue)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processSave](#method-processSave)
* [processUpdate](#method-processUpdate)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [setTypeFeature](#method-setTypeFeature)
* [setTypeValue](#method-setTypeValue)




Properties
----------


### <a name="property-$bootstrap"></a>$bootstrap

    public mixed $bootstrap = true





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L32)


### <a name="property-$feature_name"></a>$feature_name

    protected mixed $feature_name





* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L34)


### <a name="property-$object"></a>$object

    public \Feature $object





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L30)


### <a name="property-$position_identifier"></a>$position_identifier

    protected mixed $position_identifier = 'id_feature'





* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminFeaturesControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L36)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

    mixed AdminFeaturesControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L598)




### <a name="method-getList"></a>getList

    mixed AdminFeaturesControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L573)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-initContent"></a>initContent

    mixed AdminFeaturesControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L405)




### <a name="method-initFormFeatureValue"></a>initFormFeatureValue

    mixed AdminFeaturesControllerCore::initFormFeatureValue()

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L317)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminFeaturesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L190)




### <a name="method-initProcess"></a>initProcess

    mixed AdminFeaturesControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L448)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminFeaturesControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L221)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

    mixed AdminFeaturesControllerCore::initToolbarTitle()





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L267)




### <a name="method-postProcess"></a>postProcess

    mixed AdminFeaturesControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L475)




### <a name="method-processAdd"></a>processAdd

    mixed AdminFeaturesControllerCore::processAdd()

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L501)




### <a name="method-processSave"></a>processSave

    mixed AdminFeaturesControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L538)




### <a name="method-processUpdate"></a>processUpdate

    mixed AdminFeaturesControllerCore::processUpdate()

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L522)




### <a name="method-renderForm"></a>renderForm

    mixed AdminFeaturesControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L154)




### <a name="method-renderList"></a>renderList

    mixed AdminFeaturesControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L85)




### <a name="method-renderView"></a>renderView

    mixed AdminFeaturesControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L114)




### <a name="method-setTypeFeature"></a>setTypeFeature

    mixed AdminFeaturesControllerCore::setTypeFeature()

Change object type to feature (use when processing a feature)



* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L107)




### <a name="method-setTypeValue"></a>setTypeValue

    mixed AdminFeaturesControllerCore::setTypeValue()

Change object type to feature value (use when processing a feature value)



* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#L97)



