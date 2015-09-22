Class AdminStockInstantStateControllerCore
=====================





* Class name: AdminStockInstantStateControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminStockInstantStateController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L31)



Properties
----------

* [$object](#property-$object)
* [$stock_instant_state_warehouses](#property-$stock_instant_state_warehouses)

Methods
-------
* [__construct](#method-__construct)
* [getCurrentCoverageWarehouse](#method-getCurrentCoverageWarehouse)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [realQuantityCmp](#method-realQuantityCmp)
* [renderCSV](#method-renderCSV)
* [renderDetails](#method-renderDetails)
* [renderList](#method-renderList)
* [valuationCmp](#method-valuationCmp)




Properties
----------


### <a name="property-$object"></a>$object

    public \Stock $object





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L31)


### <a name="property-$stock_instant_state_warehouses"></a>$stock_instant_state_warehouses

    protected mixed $stock_instant_state_warehouses = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminStockInstantStateController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminStockInstantStateControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L35)




### <a name="method-getCurrentCoverageWarehouse"></a>getCurrentCoverageWarehouse

    integer AdminStockInstantStateControllerCore::getCurrentCoverageWarehouse()

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockInstantStateController.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L413)




### <a name="method-getList"></a>getList

    mixed AdminStockInstantStateControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L270)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-initContent"></a>initContent

    mixed AdminStockInstantStateControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L529)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminStockInstantStateControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L110)




### <a name="method-initProcess"></a>initProcess

    mixed AdminStockInstantStateControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L538)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminStockInstantStateControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L429)




### <a name="method-realQuantityCmp"></a>realQuantityCmp

    boolean AdminStockInstantStateControllerCore::realQuantityCmp(array $n, array $m)

CMP



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L399)


#### Arguments
* $n **array**
* $m **array**



### <a name="method-renderCSV"></a>renderCSV

    mixed AdminStockInstantStateControllerCore::renderCSV()

Exports CSV



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L453)




### <a name="method-renderDetails"></a>renderDetails

    mixed AdminStockInstantStateControllerCore::renderDetails()





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L206)




### <a name="method-renderList"></a>renderList

    mixed AdminStockInstantStateControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L143)




### <a name="method-valuationCmp"></a>valuationCmp

    boolean AdminStockInstantStateControllerCore::valuationCmp(array $n, array $m)

CMP



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockInstantStateController.php#L382)


#### Arguments
* $n **array**
* $m **array**


