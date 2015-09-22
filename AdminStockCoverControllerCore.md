AdminStockCoverControllerCore
===============






* Class name: AdminStockCoverControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminStockCoverController.php line 31





Properties
----------


### $stock_cover_warehouses

    protected mixed $stock_cover_warehouses





* Visibility: **protected**
* This property is defined in controllers\admin\AdminStockCoverController.php line 33


### $stock_cover_periods

    protected mixed $stock_cover_periods





* Visibility: **protected**
* This property is defined in controllers\admin\AdminStockCoverController.php line 34


### $object

    public \Product $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminStockCoverController.php line 31


Methods
-------


### __construct

    mixed AdminStockCoverControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminStockCoverController.php line 36




### initPageHeaderToolbar

    mixed AdminStockCoverControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminStockCoverController.php line 106




### renderDetails

    mixed AdminStockCoverControllerCore::renderDetails()





* Visibility: **public**
* This method is defined in controllers\admin\AdminStockCoverController.php line 124




### renderList

    mixed AdminStockCoverControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminStockCoverController.php line 165




### getList

    mixed AdminStockCoverControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminStockCoverController.php line 220


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### getCurrentCoveragePeriod

    integer AdminStockCoverControllerCore::getCurrentCoveragePeriod()

Gets the current coverage period used



* Visibility: **protected**
* This method is defined in controllers\admin\AdminStockCoverController.php line 306




### getCurrentCoverageWarehouse

    integer AdminStockCoverControllerCore::getCurrentCoverageWarehouse()

Gets the current warehouse used



* Visibility: **protected**
* This method is defined in controllers\admin\AdminStockCoverController.php line 324




### getCurrentWarning

    integer AdminStockCoverControllerCore::getCurrentWarning()

Gets the current warning



* Visibility: **protected**
* This method is defined in controllers\admin\AdminStockCoverController.php line 342




### getQuantitySold

    integer AdminStockCoverControllerCore::getQuantitySold(integer $id_product, integer $id_product_attribute, integer $coverage)

For a given product, and a given period, returns the quantity sold



* Visibility: **protected**
* This method is defined in controllers\admin\AdminStockCoverController.php line 363


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**



### initContent

    mixed AdminStockCoverControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminStockCoverController.php line 381




### initProcess

    mixed AdminStockCoverControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminStockCoverController.php line 390



