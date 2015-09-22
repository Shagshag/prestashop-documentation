AdminFeaturesControllerCore
===============






* Class name: AdminFeaturesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)

* This class is defined in [controllers/admin/AdminFeaturesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#30)





Properties
----------


### $bootstrap

    public mixed $bootstrap = true





* Visibility: **public**
* This property is defined in [controllers/admin/AdminFeaturesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#32)


### $position_identifier

    protected mixed $position_identifier = 'id_feature'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminFeaturesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#33)


### $feature_name

    protected mixed $feature_name





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminFeaturesController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#34)


### $object

    public \Feature $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminFeaturesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#30)


Methods
-------


### __construct

    mixed AdminFeaturesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#36)




### renderList

    mixed AdminFeaturesControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#85)




### setTypeValue

    mixed AdminFeaturesControllerCore::setTypeValue()

Change object type to feature value (use when processing a feature value)



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#97)




### setTypeFeature

    mixed AdminFeaturesControllerCore::setTypeFeature()

Change object type to feature (use when processing a feature)



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#107)




### renderView

    mixed AdminFeaturesControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#114)




### renderForm

    mixed AdminFeaturesControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#154)




### initPageHeaderToolbar

    mixed AdminFeaturesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#190)




### initToolbar

    mixed AdminFeaturesControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#221)




### initToolbarTitle

    mixed AdminFeaturesControllerCore::initToolbarTitle()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#267)




### initFormFeatureValue

    mixed AdminFeaturesControllerCore::initFormFeatureValue()

AdminController::renderForm() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#317)




### initContent

    mixed AdminFeaturesControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#405)




### initProcess

    mixed AdminFeaturesControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#448)




### postProcess

    mixed AdminFeaturesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#475)




### processAdd

    mixed AdminFeaturesControllerCore::processAdd()

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#501)




### processUpdate

    mixed AdminFeaturesControllerCore::processUpdate()

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#522)




### processSave

    mixed AdminFeaturesControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#538)




### getList

    mixed AdminFeaturesControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#573)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### ajaxProcessUpdatePositions

    mixed AdminFeaturesControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminFeaturesController.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminFeaturesController.php#598)



