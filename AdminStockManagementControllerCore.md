AdminStockManagementControllerCore
===============






* Class name: AdminStockManagementControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \Product $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminStockManagementControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminStockManagementControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderList

    mixed AdminStockManagementControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**




### renderForm

    mixed AdminStockManagementControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**




### postProcess

    mixed AdminStockManagementControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**




### initToolbar

    mixed AdminStockManagementControllerCore::initToolbar()

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**




### init

    mixed AdminStockManagementControllerCore::init()

AdminController::init() override



* Visibility: **public**




### renderDetails

    mixed AdminStockManagementControllerCore::renderDetails()





* Visibility: **public**




### getList

    mixed AdminStockManagementControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### skipActionByStock

    mixed AdminStockManagementControllerCore::skipActionByStock(array $item, boolean $is_product_variation)

Check stock for a given product or product attribute
and manage available actions in consequence



* Visibility: **protected**


#### Arguments
* $item **array** - &lt;p&gt;Reference to the current item&lt;/p&gt;
* $is_product_variation **boolean** - &lt;p&gt;Specify if it&#039;s a product or a product variation&lt;/p&gt;



### initContent

    mixed AdminStockManagementControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**




### displayAddstockLink

    string AdminStockManagementControllerCore::displayAddstockLink(string $token, integer $id)

Display addstock action link



* Visibility: **public**


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayRemovestockLink

    string AdminStockManagementControllerCore::displayRemovestockLink(string $token, integer $id)

Display removestock action link



* Visibility: **public**


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayTransferstockLink

    string AdminStockManagementControllerCore::displayTransferstockLink(string $token, integer $id)

Display transferstock action link



* Visibility: **public**


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### initProcess

    mixed AdminStockManagementControllerCore::initProcess()





* Visibility: **public**



