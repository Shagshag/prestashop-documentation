AdminStockInstantStateControllerCore
===============






* Class name: AdminStockInstantStateControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $stock_instant_state_warehouses

    protected mixed $stock_instant_state_warehouses = array()





* Visibility: **protected**


### $object

    public \Stock $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminStockInstantStateControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminStockInstantStateControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderList

    mixed AdminStockInstantStateControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**




### renderDetails

    mixed AdminStockInstantStateControllerCore::renderDetails()





* Visibility: **public**




### getList

    mixed AdminStockInstantStateControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### valuationCmp

    boolean AdminStockInstantStateControllerCore::valuationCmp(array $n, array $m)

CMP



* Visibility: **public**


#### Arguments
* $n **array**
* $m **array**



### realQuantityCmp

    boolean AdminStockInstantStateControllerCore::realQuantityCmp(array $n, array $m)

CMP



* Visibility: **public**


#### Arguments
* $n **array**
* $m **array**



### getCurrentCoverageWarehouse

    integer AdminStockInstantStateControllerCore::getCurrentCoverageWarehouse()

Gets the current warehouse used



* Visibility: **protected**




### initToolbar

    mixed AdminStockInstantStateControllerCore::initToolbar()





* Visibility: **public**




### renderCSV

    mixed AdminStockInstantStateControllerCore::renderCSV()

Exports CSV



* Visibility: **public**




### initContent

    mixed AdminStockInstantStateControllerCore::initContent()





* Visibility: **public**




### initProcess

    mixed AdminStockInstantStateControllerCore::initProcess()





* Visibility: **public**



