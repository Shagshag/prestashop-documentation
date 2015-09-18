AdminSupplyOrdersControllerCore
===============






* Class name: AdminSupplyOrdersControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $warehouses

    protected array $warehouses





* Visibility: **protected**


### $object

    public \SupplyOrder $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminSupplyOrdersControllerCore::__construct()





* Visibility: **public**




### init

    mixed AdminSupplyOrdersControllerCore::init()

AdminController::init() override



* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminSupplyOrdersControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderForm

    mixed AdminSupplyOrdersControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**




### getList

    mixed AdminSupplyOrdersControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### renderList

    mixed AdminSupplyOrdersControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**




### initChangeStateContent

    mixed AdminSupplyOrdersControllerCore::initChangeStateContent()

Init the content of change state action



* Visibility: **public**




### initUpdateSupplyOrderContent

    mixed AdminSupplyOrdersControllerCore::initUpdateSupplyOrderContent()

Init the content of change state action



* Visibility: **public**




### initUpdateReceiptContent

    mixed AdminSupplyOrdersControllerCore::initUpdateReceiptContent()

Inits the content of 'update_receipt' action
Called in initContent()



* Visibility: **public**




### initContent

    mixed AdminSupplyOrdersControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**




### manageOrderProducts

    mixed AdminSupplyOrdersControllerCore::manageOrderProducts()

Ths method manage associated products to the order when updating it



* Visibility: **public**




### postProcess

    mixed AdminSupplyOrdersControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**




### renderCSV

    mixed AdminSupplyOrdersControllerCore::renderCSV()

Exports CSV



* Visibility: **protected**




### postProcessUpdateReceipt

    mixed AdminSupplyOrdersControllerCore::postProcessUpdateReceipt()

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**




### displayUpdateReceiptLink

    string AdminSupplyOrdersControllerCore::displayUpdateReceiptLink(string $token, integer $id)

Display state action link



* Visibility: **public**


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayChangestateLink

    string AdminSupplyOrdersControllerCore::displayChangestateLink(string $token, integer $id)

Display receipt action link



* Visibility: **public**


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayCreateSupplyOrderLink

    string AdminSupplyOrdersControllerCore::displayCreateSupplyOrderLink(string $token, integer $id)

Display state action link



* Visibility: **public**


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### renderDetails

    mixed AdminSupplyOrdersControllerCore::renderDetails()





* Visibility: **public**




### ajaxProcessSearchProduct

    mixed AdminSupplyOrdersControllerCore::ajaxProcessSearchProduct()

method call when ajax request is made for search product to add to the order



* Visibility: **public**




### renderView

    mixed AdminSupplyOrdersControllerCore::renderView()





* Visibility: **public**




### printExportIcons

    string AdminSupplyOrdersControllerCore::printExportIcons(integer $id_supply_order, string $tr)

Callback used to display custom content for a given field



* Visibility: **public**


#### Arguments
* $id_supply_order **integer**
* $tr **string**



### initToolbar

    mixed AdminSupplyOrdersControllerCore::initToolbar()

Assigns default actions in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**




### afterAdd

    boolean AdminSupplyOrdersControllerCore::afterAdd(\ObjectModel $object)

Overrides AdminController::afterAdd()



* Visibility: **protected**


#### Arguments
* $object **ObjectModel**



### loadProducts

    mixed AdminSupplyOrdersControllerCore::loadProducts(integer $threshold)

Loads products which quantity (hysical quantity) is equal or less than $threshold



* Visibility: **protected**


#### Arguments
* $threshold **integer**



### beforeAdd

    true AdminSupplyOrdersControllerCore::beforeAdd(\SupplyOrder $object)

Overrides AdminController::beforeAdd()



* Visibility: **public**


#### Arguments
* $object **SupplyOrder**



### postProcessCopyFromTemplate

    mixed AdminSupplyOrdersControllerCore::postProcessCopyFromTemplate()

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**




### getCurrentWarehouse

    integer AdminSupplyOrdersControllerCore::getCurrentWarehouse()

Gets the current warehouse used



* Visibility: **protected**




### getFilterStatus

    integer AdminSupplyOrdersControllerCore::getFilterStatus()

Gets the current filter used



* Visibility: **protected**




### initProcess

    mixed AdminSupplyOrdersControllerCore::initProcess()





* Visibility: **public**



