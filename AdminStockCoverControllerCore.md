AdminStockCoverControllerCore
===============






* Class name: AdminStockCoverControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $stock_cover_warehouses

    protected mixed $stock_cover_warehouses





* Visibility: **protected**


### $stock_cover_periods

    protected mixed $stock_cover_periods





* Visibility: **protected**


### $object

    public \Product $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminStockCoverControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminStockCoverControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderDetails

    mixed AdminStockCoverControllerCore::renderDetails()





* Visibility: **public**




### renderList

    mixed AdminStockCoverControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**




### getList

    mixed AdminStockCoverControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


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




### getCurrentCoverageWarehouse

    integer AdminStockCoverControllerCore::getCurrentCoverageWarehouse()

Gets the current warehouse used



* Visibility: **protected**




### getCurrentWarning

    integer AdminStockCoverControllerCore::getCurrentWarning()

Gets the current warning



* Visibility: **protected**




### getQuantitySold

    integer AdminStockCoverControllerCore::getQuantitySold(integer $id_product, integer $id_product_attribute, integer $coverage)

For a given product, and a given period, returns the quantity sold



* Visibility: **protected**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**



### initContent

    mixed AdminStockCoverControllerCore::initContent()





* Visibility: **public**




### initProcess

    mixed AdminStockCoverControllerCore::initProcess()





* Visibility: **public**



