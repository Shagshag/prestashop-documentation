Class AdminStockManagementControllerCore
=====================





* Class name: AdminStockManagementControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockManagementController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L31)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [displayAddstockLink](#method-displayAddstockLink)
* [displayRemovestockLink](#method-displayRemovestockLink)
* [displayTransferstockLink](#method-displayTransferstockLink)
* [getList](#method-getList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [renderDetails](#method-renderDetails)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [skipActionByStock](#method-skipActionByStock)




Properties
----------


### <a name="property-$object"></a>$object

    public \Product $object





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L31)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminStockManagementControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L33)




### <a name="method-displayAddstockLink"></a>displayAddstockLink

    string AdminStockManagementControllerCore::displayAddstockLink(string $token, integer $id)

Display addstock action link



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L1117)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayRemovestockLink"></a>displayRemovestockLink

    string AdminStockManagementControllerCore::displayRemovestockLink(string $token, integer $id)

Display removestock action link



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L1139)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayTransferstockLink"></a>displayTransferstockLink

    string AdminStockManagementControllerCore::displayTransferstockLink(string $token, integer $id)

Display transferstock action link



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L1161)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getList"></a>getList

    mixed AdminStockManagementControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L895)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-init"></a>init

    mixed AdminStockManagementControllerCore::init()

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L792)




### <a name="method-initContent"></a>initContent

    mixed AdminStockManagementControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L977)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminStockManagementControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L80)




### <a name="method-initProcess"></a>initProcess

    mixed AdminStockManagementControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L1177)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminStockManagementControllerCore::initToolbar()

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L755)




### <a name="method-postProcess"></a>postProcess

    mixed AdminStockManagementControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L544)




### <a name="method-renderDetails"></a>renderDetails

    mixed AdminStockManagementControllerCore::renderDetails()





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L812)




### <a name="method-renderForm"></a>renderForm

    mixed AdminStockManagementControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L134)




### <a name="method-renderList"></a>renderList

    mixed AdminStockManagementControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L97)




### <a name="method-skipActionByStock"></a>skipActionByStock

    mixed AdminStockManagementControllerCore::skipActionByStock(array $item, boolean $is_product_variation)

Check stock for a given product or product attribute
and manage available actions in consequence



* Visibility: **protected**
* Source: [controllers/admin/AdminStockManagementController.php line 952](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L952)


#### Arguments
* $item **array** - Reference to the current item
* $is_product_variation **boolean** - Specify if it&#039;s a product or a product variation


