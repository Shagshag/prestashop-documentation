Class AdminStockMvtControllerCore
=====================





* Class name: AdminStockMvtControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminStockMvtController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L31)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [getCurrentWarehouseId](#method-getCurrentWarehouseId)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [renderCSV](#method-renderCSV)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$object"></a>$object

    public \StockMvt $object





* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L31)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminStockMvtControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L33)




### <a name="method-getCurrentWarehouseId"></a>getCurrentWarehouseId

    integer AdminStockMvtControllerCore::getCurrentWarehouseId()

Gets the current warehouse for this controller



* Visibility: **protected**
* Source: [controllers/admin/AdminStockMvtController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L209)




### <a name="method-getList"></a>getList

    mixed AdminStockMvtControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L236)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-initContent"></a>initContent

    mixed AdminStockMvtControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L316)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminStockMvtControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L114)




### <a name="method-initProcess"></a>initProcess

    mixed AdminStockMvtControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L325)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminStockMvtControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L263)




### <a name="method-renderCSV"></a>renderCSV

    mixed AdminStockMvtControllerCore::renderCSV()

Exports CSV



* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L281)




### <a name="method-renderList"></a>renderList

    mixed AdminStockMvtControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockMvtController.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockMvtController.php#L134)



