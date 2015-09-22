AdminAttributesGroupsControllerCore
===============






* Class name: AdminAttributesGroupsControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminAttributesGroupsController.php line 30





Properties
----------


### $bootstrap

    public mixed $bootstrap = true





* Visibility: **public**
* This property is defined in controllers\admin\AdminAttributesGroupsController.php line 32


### $id_attribute

    protected mixed $id_attribute





* Visibility: **protected**
* This property is defined in controllers\admin\AdminAttributesGroupsController.php line 33


### $position_identifier

    protected mixed $position_identifier = 'id_attribute_group'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminAttributesGroupsController.php line 34


### $attribute_name

    protected mixed $attribute_name





* Visibility: **protected**
* This property is defined in controllers\admin\AdminAttributesGroupsController.php line 35


### $object

    public \AttributeGroup $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminAttributesGroupsController.php line 30


Methods
-------


### __construct

    mixed AdminAttributesGroupsControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 37




### renderList

    mixed AdminAttributesGroupsControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 91




### renderView

    mixed AdminAttributesGroupsControllerCore::renderView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 101




### renderForm

    mixed AdminAttributesGroupsControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 165




### renderFormAttributes

    mixed AdminAttributesGroupsControllerCore::renderFormAttributes()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 244




### init

    mixed AdminAttributesGroupsControllerCore::init()

AdminController::init() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 380




### processAdd

    mixed AdminAttributesGroupsControllerCore::processAdd()

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 397




### processUpdate

    mixed AdminAttributesGroupsControllerCore::processUpdate()

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 437




### initContent

    mixed AdminAttributesGroupsControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 464




### initPageHeaderToolbar

    mixed AdminAttributesGroupsControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 507




### initToolbar

    mixed AdminAttributesGroupsControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 533




### initToolbarTitle

    mixed AdminAttributesGroupsControllerCore::initToolbarTitle()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 586




### initProcess

    mixed AdminAttributesGroupsControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 636




### setTypeAttribute

    mixed AdminAttributesGroupsControllerCore::setTypeAttribute()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 658




### processPosition

    mixed AdminAttributesGroupsControllerCore::processPosition()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 671




### processSave

    mixed AdminAttributesGroupsControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 698




### postProcess

    mixed AdminAttributesGroupsControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 711




### getList

    mixed AdminAttributesGroupsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 827


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
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 863




### ajaxProcessUpdateGroupsPositions

    mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateGroupsPositions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 881




### ajaxProcessUpdateAttributesPositions

    mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateAttributesPositions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminAttributesGroupsController.php line 914



