AdminWarehousesControllerCore
===============






* Class name: AdminWarehousesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminWarehousesController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#L31)





Properties
----------


### $object

    public \Warehouse $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminWarehousesController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#31)


Methods
-------


### __construct

    mixed AdminWarehousesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#33)




### initPageHeaderToolbar

    mixed AdminWarehousesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#86)




### renderList

    mixed AdminWarehousesControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#103)




### renderForm

    mixed AdminWarehousesControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#142)




### renderView

    mixed AdminWarehousesControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#422)




### afterAdd

    boolean AdminWarehousesControllerCore::afterAdd(\Warehouse $object)

Called once $object is set.

Used to process the associations with address/shops/carriers

* Visibility: **protected**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 466](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#466)


#### Arguments
* $object **[Warehouse](WarehouseCore)**



### getList

    mixed AdminWarehousesControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#499)


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
* This method is defined in [controllers/admin/AdminWarehousesController.php line 525](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#525)




### initProcess

    mixed AdminWarehousesControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#534)




### processAdd

    mixed AdminWarehousesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#546)




### updateAddress

    mixed AdminWarehousesControllerCore::updateAddress()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#562)




### processDelete

    mixed AdminWarehousesControllerCore::processDelete()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#618)




### processUpdate

    mixed AdminWarehousesControllerCore::processUpdate()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#649)




### updateAssoShop

    mixed AdminWarehousesControllerCore::updateAssoShop($id_object)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminWarehousesController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWarehousesController.php#670)


#### Arguments
* $id_object **mixed**


