AdminFeaturesControllerCore
===============






* Class name: AdminFeaturesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $bootstrap

    public mixed $bootstrap = true





* Visibility: **public**


### $position_identifier

    protected mixed $position_identifier = 'id_feature'





* Visibility: **protected**


### $feature_name

    protected mixed $feature_name





* Visibility: **protected**


### $object

    public \Feature $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminFeaturesControllerCore::__construct()





* Visibility: **public**




### renderList

    mixed AdminFeaturesControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**




### setTypeValue

    mixed AdminFeaturesControllerCore::setTypeValue()

Change object type to feature value (use when processing a feature value)



* Visibility: **protected**




### setTypeFeature

    mixed AdminFeaturesControllerCore::setTypeFeature()

Change object type to feature (use when processing a feature)



* Visibility: **protected**




### renderView

    mixed AdminFeaturesControllerCore::renderView()





* Visibility: **public**




### renderForm

    mixed AdminFeaturesControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminFeaturesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initToolbar

    mixed AdminFeaturesControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**




### initToolbarTitle

    mixed AdminFeaturesControllerCore::initToolbarTitle()





* Visibility: **public**




### initFormFeatureValue

    mixed AdminFeaturesControllerCore::initFormFeatureValue()

AdminController::renderForm() override



* Visibility: **public**




### initContent

    mixed AdminFeaturesControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**




### initProcess

    mixed AdminFeaturesControllerCore::initProcess()





* Visibility: **public**




### postProcess

    mixed AdminFeaturesControllerCore::postProcess()





* Visibility: **public**




### processAdd

    mixed AdminFeaturesControllerCore::processAdd()

Override processAdd to change SaveAndStay button action



* Visibility: **public**




### processUpdate

    mixed AdminFeaturesControllerCore::processUpdate()

Override processUpdate to change SaveAndStay button action



* Visibility: **public**




### processSave

    mixed AdminFeaturesControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**




### getList

    mixed AdminFeaturesControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


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



