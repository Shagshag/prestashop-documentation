AdminWarehousesControllerCore
===============






* Class name: AdminWarehousesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \Warehouse $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminWarehousesControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminWarehousesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderList

    mixed AdminWarehousesControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**




### renderForm

    mixed AdminWarehousesControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**




### renderView

    mixed AdminWarehousesControllerCore::renderView()





* Visibility: **public**




### afterAdd

    boolean AdminWarehousesControllerCore::afterAdd(\Warehouse $object)

Called once $object is set.

Used to process the associations with address/shops/carriers

* Visibility: **protected**


#### Arguments
* $object **Warehouse**



### getList

    mixed AdminWarehousesControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### initContent

    mixed AdminWarehousesControllerCore::initContent()





* Visibility: **public**




### initProcess

    mixed AdminWarehousesControllerCore::initProcess()





* Visibility: **public**




### processAdd

    mixed AdminWarehousesControllerCore::processAdd()





* Visibility: **public**




### updateAddress

    mixed AdminWarehousesControllerCore::updateAddress()





* Visibility: **protected**




### processDelete

    mixed AdminWarehousesControllerCore::processDelete()





* Visibility: **public**




### processUpdate

    mixed AdminWarehousesControllerCore::processUpdate()





* Visibility: **public**




### updateAssoShop

    mixed AdminWarehousesControllerCore::updateAssoShop($id_object)





* Visibility: **protected**


#### Arguments
* $id_object **mixed**


