Class AdminSupplyOrdersControllerCore
=====================





* Class name: AdminSupplyOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminSupplyOrdersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L31)



Properties
----------

* [$object](#property-$object)
* [$warehouses](#property-$warehouses)

Methods
-------
* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [ajaxProcessSearchProduct](#method-ajaxProcessSearchProduct)
* [beforeAdd](#method-beforeAdd)
* [displayChangestateLink](#method-displayChangestateLink)
* [displayCreateSupplyOrderLink](#method-displayCreateSupplyOrderLink)
* [displayUpdateReceiptLink](#method-displayUpdateReceiptLink)
* [getCurrentWarehouse](#method-getCurrentWarehouse)
* [getFilterStatus](#method-getFilterStatus)
* [getList](#method-getList)
* [init](#method-init)
* [initChangeStateContent](#method-initChangeStateContent)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initUpdateReceiptContent](#method-initUpdateReceiptContent)
* [initUpdateSupplyOrderContent](#method-initUpdateSupplyOrderContent)
* [loadProducts](#method-loadProducts)
* [manageOrderProducts](#method-manageOrderProducts)
* [postProcess](#method-postProcess)
* [postProcessCopyFromTemplate](#method-postProcessCopyFromTemplate)
* [postProcessUpdateReceipt](#method-postProcessUpdateReceipt)
* [printExportIcons](#method-printExportIcons)
* [renderCSV](#method-renderCSV)
* [renderDetails](#method-renderDetails)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$object"></a>$object

    public \SupplyOrder $object





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L31).


### <a name="property-$warehouses"></a>$warehouses

    protected array $warehouses





* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminSupplyOrdersControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L38)




### <a name="method-afterAdd"></a>afterAdd

    boolean AdminSupplyOrdersControllerCore::afterAdd(\ObjectModel $object)

Overrides AdminController::afterAdd()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2021](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L2021)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-ajaxProcessSearchProduct"></a>ajaxProcessSearchProduct

    mixed AdminSupplyOrdersControllerCore::ajaxProcessSearchProduct()

method call when ajax request is made for search product to add to the order



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1667](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1667)




### <a name="method-beforeAdd"></a>beforeAdd

    true AdminSupplyOrdersControllerCore::beforeAdd(\SupplyOrder $object)

Overrides AdminController::beforeAdd()



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L2135)


#### Arguments
* $object **[SupplyOrder](class.SupplyOrderCore.md)**



### <a name="method-displayChangestateLink"></a>displayChangestateLink

    string AdminSupplyOrdersControllerCore::displayChangestateLink(string $token, integer $id)

Display receipt action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1522](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1522)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayCreateSupplyOrderLink"></a>displayCreateSupplyOrderLink

    string AdminSupplyOrdersControllerCore::displayCreateSupplyOrderLink(string $token, integer $id)

Display state action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1544)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayUpdateReceiptLink"></a>displayUpdateReceiptLink

    string AdminSupplyOrdersControllerCore::displayUpdateReceiptLink(string $token, integer $id)

Display state action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1500)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getCurrentWarehouse"></a>getCurrentWarehouse

    integer AdminSupplyOrdersControllerCore::getCurrentWarehouse()

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L2187)




### <a name="method-getFilterStatus"></a>getFilterStatus

    integer AdminSupplyOrdersControllerCore::getFilterStatus()

Gets the current filter used



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L2205)




### <a name="method-getList"></a>getList

    mixed AdminSupplyOrdersControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L382)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-init"></a>init

    mixed AdminSupplyOrdersControllerCore::init()

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L116)




### <a name="method-initChangeStateContent"></a>initChangeStateContent

    mixed AdminSupplyOrdersControllerCore::initChangeStateContent()

Init the content of change state action



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L586)




### <a name="method-initContent"></a>initContent

    mixed AdminSupplyOrdersControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L908)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminSupplyOrdersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L156)




### <a name="method-initProcess"></a>initProcess

    mixed AdminSupplyOrdersControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L2217)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminSupplyOrdersControllerCore::initToolbar()

Assigns default actions in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1980](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1980)




### <a name="method-initUpdateReceiptContent"></a>initUpdateReceiptContent

    mixed AdminSupplyOrdersControllerCore::initUpdateReceiptContent()

Inits the content of 'update_receipt' action
Called in initContent()



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 742](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L742)




### <a name="method-initUpdateSupplyOrderContent"></a>initUpdateSupplyOrderContent

    mixed AdminSupplyOrdersControllerCore::initUpdateSupplyOrderContent()

Init the content of change state action



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L681)




### <a name="method-loadProducts"></a>loadProducts

    mixed AdminSupplyOrdersControllerCore::loadProducts(integer $threshold)

Loads products which quantity (hysical quantity) is equal or less than $threshold



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2035](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L2035)


#### Arguments
* $threshold **integer**



### <a name="method-manageOrderProducts"></a>manageOrderProducts

    mixed AdminSupplyOrdersControllerCore::manageOrderProducts()

Ths method manage associated products to the order when updating it



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 938](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L938)




### <a name="method-postProcess"></a>postProcess

    mixed AdminSupplyOrdersControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1081)




### <a name="method-postProcessCopyFromTemplate"></a>postProcessCopyFromTemplate

    mixed AdminSupplyOrdersControllerCore::postProcessCopyFromTemplate()

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L2148)




### <a name="method-postProcessUpdateReceipt"></a>postProcessUpdateReceipt

    mixed AdminSupplyOrdersControllerCore::postProcessUpdateReceipt()

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1387](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1387)




### <a name="method-printExportIcons"></a>printExportIcons

    string AdminSupplyOrdersControllerCore::printExportIcons(integer $id_supply_order, string $tr)

Callback used to display custom content for a given field



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1946](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1946)


#### Arguments
* $id_supply_order **integer**
* $tr **string**



### <a name="method-renderCSV"></a>renderCSV

    mixed AdminSupplyOrdersControllerCore::renderCSV()

Exports CSV



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1294)




### <a name="method-renderDetails"></a>renderDetails

    mixed AdminSupplyOrdersControllerCore::renderDetails()





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1565)




### <a name="method-renderForm"></a>renderForm

    mixed AdminSupplyOrdersControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L184)




### <a name="method-renderList"></a>renderList

    mixed AdminSupplyOrdersControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L452)




### <a name="method-renderView"></a>renderView

    mixed AdminSupplyOrdersControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1733](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminSupplyOrdersController.php#L1733)



