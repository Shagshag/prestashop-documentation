Class AdminStockCoverControllerCore
=====================





* Class name: AdminStockCoverControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockCoverController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L31)



Properties
----------

* [$object](#property-$object)
* [$stock_cover_periods](#property-$stock_cover_periods)
* [$stock_cover_warehouses](#property-$stock_cover_warehouses)

Methods
-------
* [__construct](#method-__construct)
* [getCurrentCoveragePeriod](#method-getCurrentCoveragePeriod)
* [getCurrentCoverageWarehouse](#method-getCurrentCoverageWarehouse)
* [getCurrentWarning](#method-getCurrentWarning)
* [getList](#method-getList)
* [getQuantitySold](#method-getQuantitySold)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [renderDetails](#method-renderDetails)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$object"></a>$object

    public \Product $object





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L31)


### <a name="property-$stock_cover_periods"></a>$stock_cover_periods

    protected mixed $stock_cover_periods





* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L34)


### <a name="property-$stock_cover_warehouses"></a>$stock_cover_warehouses

    protected mixed $stock_cover_warehouses





* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminStockCoverControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L36)




### <a name="method-getCurrentCoveragePeriod"></a>getCurrentCoveragePeriod

    integer AdminStockCoverControllerCore::getCurrentCoveragePeriod()

Gets the current coverage period used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L306)




### <a name="method-getCurrentCoverageWarehouse"></a>getCurrentCoverageWarehouse

    integer AdminStockCoverControllerCore::getCurrentCoverageWarehouse()

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L324)




### <a name="method-getCurrentWarning"></a>getCurrentWarning

    integer AdminStockCoverControllerCore::getCurrentWarning()

Gets the current warning



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L342)




### <a name="method-getList"></a>getList

    mixed AdminStockCoverControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L220)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-getQuantitySold"></a>getQuantitySold

    integer AdminStockCoverControllerCore::getQuantitySold(integer $id_product, integer $id_product_attribute, integer $coverage)

For a given product, and a given period, returns the quantity sold



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L363)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**



### <a name="method-initContent"></a>initContent

    mixed AdminStockCoverControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L381)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminStockCoverControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L106)




### <a name="method-initProcess"></a>initProcess

    mixed AdminStockCoverControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L390)




### <a name="method-renderDetails"></a>renderDetails

    mixed AdminStockCoverControllerCore::renderDetails()





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L124)




### <a name="method-renderList"></a>renderList

    mixed AdminStockCoverControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockCoverController.php#L165)



