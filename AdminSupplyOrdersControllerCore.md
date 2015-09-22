AdminSupplyOrdersControllerCore
===============






* Class name: AdminSupplyOrdersControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminSupplyOrdersController.php line 31





Properties
----------


### $warehouses

    protected array $warehouses





* Visibility: **protected**
* This property is defined in controllers\admin\AdminSupplyOrdersController.php line 36


### $object

    public \SupplyOrder $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminSupplyOrdersController.php line 31


Methods
-------


### __construct

    mixed AdminSupplyOrdersControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 38




### init

    mixed AdminSupplyOrdersControllerCore::init()

AdminController::init() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 116




### initPageHeaderToolbar

    mixed AdminSupplyOrdersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 156




### renderForm

    mixed AdminSupplyOrdersControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 184




### getList

    mixed AdminSupplyOrdersControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 382


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
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 452




### initChangeStateContent

    mixed AdminSupplyOrdersControllerCore::initChangeStateContent()

Init the content of change state action



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 586




### initUpdateSupplyOrderContent

    mixed AdminSupplyOrdersControllerCore::initUpdateSupplyOrderContent()

Init the content of change state action



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 681




### initUpdateReceiptContent

    mixed AdminSupplyOrdersControllerCore::initUpdateReceiptContent()

Inits the content of 'update_receipt' action
Called in initContent()



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 742




### initContent

    mixed AdminSupplyOrdersControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 908




### manageOrderProducts

    mixed AdminSupplyOrdersControllerCore::manageOrderProducts()

Ths method manage associated products to the order when updating it



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 938




### postProcess

    mixed AdminSupplyOrdersControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1081




### renderCSV

    mixed AdminSupplyOrdersControllerCore::renderCSV()

Exports CSV



* Visibility: **protected**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1294




### postProcessUpdateReceipt

    mixed AdminSupplyOrdersControllerCore::postProcessUpdateReceipt()

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1387




### displayUpdateReceiptLink

    string AdminSupplyOrdersControllerCore::displayUpdateReceiptLink(string $token, integer $id)

Display state action link



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1500


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayChangestateLink

    string AdminSupplyOrdersControllerCore::displayChangestateLink(string $token, integer $id)

Display receipt action link



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1522


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayCreateSupplyOrderLink

    string AdminSupplyOrdersControllerCore::displayCreateSupplyOrderLink(string $token, integer $id)

Display state action link



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1544


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### renderDetails

    mixed AdminSupplyOrdersControllerCore::renderDetails()





* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1565




### ajaxProcessSearchProduct

    mixed AdminSupplyOrdersControllerCore::ajaxProcessSearchProduct()

method call when ajax request is made for search product to add to the order



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1667




### renderView

    mixed AdminSupplyOrdersControllerCore::renderView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1733




### printExportIcons

    string AdminSupplyOrdersControllerCore::printExportIcons(integer $id_supply_order, string $tr)

Callback used to display custom content for a given field



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1946


#### Arguments
* $id_supply_order **integer**
* $tr **string**



### initToolbar

    mixed AdminSupplyOrdersControllerCore::initToolbar()

Assigns default actions in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 1980




### afterAdd

    boolean AdminSupplyOrdersControllerCore::afterAdd(\ObjectModel $object)

Overrides AdminController::afterAdd()



* Visibility: **protected**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 2021


#### Arguments
* $object **[ObjectModel](ObjectModelCore)**



### loadProducts

    mixed AdminSupplyOrdersControllerCore::loadProducts(integer $threshold)

Loads products which quantity (hysical quantity) is equal or less than $threshold



* Visibility: **protected**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 2035


#### Arguments
* $threshold **integer**



### beforeAdd

    true AdminSupplyOrdersControllerCore::beforeAdd(\SupplyOrder $object)

Overrides AdminController::beforeAdd()



* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 2135


#### Arguments
* $object **[SupplyOrder](SupplyOrderCore)**



### postProcessCopyFromTemplate

    mixed AdminSupplyOrdersControllerCore::postProcessCopyFromTemplate()

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 2148




### getCurrentWarehouse

    integer AdminSupplyOrdersControllerCore::getCurrentWarehouse()

Gets the current warehouse used



* Visibility: **protected**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 2187




### getFilterStatus

    integer AdminSupplyOrdersControllerCore::getFilterStatus()

Gets the current filter used



* Visibility: **protected**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 2205




### initProcess

    mixed AdminSupplyOrdersControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminSupplyOrdersController.php line 2217



