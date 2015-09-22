Class AdminStockConfigurationControllerCore
=====================





* Class name: AdminStockConfigurationControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockConfigurationController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L31)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessDeliveryNoteSupplyOrderState](#method-ajaxProcessDeliveryNoteSupplyOrderState)
* [ajaxProcessEditableSupplyOrderState](#method-ajaxProcessEditableSupplyOrderState)
* [ajaxProcessEnclosedSupplyOrderState](#method-ajaxProcessEnclosedSupplyOrderState)
* [ajaxProcessPendingReceiptSupplyOrderState](#method-ajaxProcessPendingReceiptSupplyOrderState)
* [ajaxProcessReceiptStateSupplyOrderState](#method-ajaxProcessReceiptStateSupplyOrderState)
* [getList](#method-getList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initProcess](#method-initProcess)
* [initSupplyOrderStatusList](#method-initSupplyOrderStatusList)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$object"></a>$object

    public \StockMvtReason $object





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L31)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminStockConfigurationControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L36)




### <a name="method-ajaxProcessDeliveryNoteSupplyOrderState"></a>ajaxProcessDeliveryNoteSupplyOrderState

    mixed AdminStockConfigurationControllerCore::ajaxProcessDeliveryNoteSupplyOrderState()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L582)




### <a name="method-ajaxProcessEditableSupplyOrderState"></a>ajaxProcessEditableSupplyOrderState

    mixed AdminStockConfigurationControllerCore::ajaxProcessEditableSupplyOrderState()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 568](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L568)




### <a name="method-ajaxProcessEnclosedSupplyOrderState"></a>ajaxProcessEnclosedSupplyOrderState

    mixed AdminStockConfigurationControllerCore::ajaxProcessEnclosedSupplyOrderState()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L624)




### <a name="method-ajaxProcessPendingReceiptSupplyOrderState"></a>ajaxProcessPendingReceiptSupplyOrderState

    mixed AdminStockConfigurationControllerCore::ajaxProcessPendingReceiptSupplyOrderState()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L596)




### <a name="method-ajaxProcessReceiptStateSupplyOrderState"></a>ajaxProcessReceiptStateSupplyOrderState

    mixed AdminStockConfigurationControllerCore::ajaxProcessReceiptStateSupplyOrderState()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L610)




### <a name="method-getList"></a>getList

    mixed AdminStockConfigurationControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L530)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-init"></a>init

    mixed AdminStockConfigurationControllerCore::init()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L129)




### <a name="method-initContent"></a>initContent

    mixed AdminStockConfigurationControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L550)




### <a name="method-initProcess"></a>initProcess

    mixed AdminStockConfigurationControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L559)




### <a name="method-initSupplyOrderStatusList"></a>initSupplyOrderStatusList

    mixed AdminStockConfigurationControllerCore::initSupplyOrderStatusList()





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L415)




### <a name="method-postProcess"></a>postProcess

    mixed AdminStockConfigurationControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L493)




### <a name="method-renderForm"></a>renderForm

    mixed AdminStockConfigurationControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L148)




### <a name="method-renderList"></a>renderList

    mixed AdminStockConfigurationControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockConfigurationController.php#L366)



