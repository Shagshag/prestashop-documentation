AdminAttributesGroupsControllerCore
===============






* Class name: AdminAttributesGroupsControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $bootstrap

    public mixed $bootstrap = true





* Visibility: **public**


### $id_attribute

    protected mixed $id_attribute





* Visibility: **protected**


### $position_identifier

    protected mixed $position_identifier = 'id_attribute_group'





* Visibility: **protected**


### $attribute_name

    protected mixed $attribute_name





* Visibility: **protected**


### $object

    public \AttributeGroup $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminAttributesGroupsControllerCore::__construct()





* Visibility: **public**




### renderList

    mixed AdminAttributesGroupsControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**




### renderView

    mixed AdminAttributesGroupsControllerCore::renderView()





* Visibility: **public**




### renderForm

    mixed AdminAttributesGroupsControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**




### renderFormAttributes

    mixed AdminAttributesGroupsControllerCore::renderFormAttributes()





* Visibility: **public**




### init

    mixed AdminAttributesGroupsControllerCore::init()

AdminController::init() override



* Visibility: **public**




### processAdd

    mixed AdminAttributesGroupsControllerCore::processAdd()

Override processAdd to change SaveAndStay button action



* Visibility: **public**




### processUpdate

    mixed AdminAttributesGroupsControllerCore::processUpdate()

Override processUpdate to change SaveAndStay button action



* Visibility: **public**




### initContent

    mixed AdminAttributesGroupsControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminAttributesGroupsControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initToolbar

    mixed AdminAttributesGroupsControllerCore::initToolbar()





* Visibility: **public**




### initToolbarTitle

    mixed AdminAttributesGroupsControllerCore::initToolbarTitle()





* Visibility: **public**




### initProcess

    mixed AdminAttributesGroupsControllerCore::initProcess()





* Visibility: **public**




### setTypeAttribute

    mixed AdminAttributesGroupsControllerCore::setTypeAttribute()





* Visibility: **protected**




### processPosition

    mixed AdminAttributesGroupsControllerCore::processPosition()





* Visibility: **public**




### processSave

    mixed AdminAttributesGroupsControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**




### postProcess

    mixed AdminAttributesGroupsControllerCore::postProcess()





* Visibility: **public**




### getList

    mixed AdminAttributesGroupsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### processBulkDelete

    mixed AdminAttributesGroupsControllerCore::processBulkDelete()

Overrides parent to delete items from sublist



* Visibility: **public**




### ajaxProcessUpdateGroupsPositions

    mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateGroupsPositions()





* Visibility: **public**




### ajaxProcessUpdateAttributesPositions

    mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateAttributesPositions()





* Visibility: **public**



