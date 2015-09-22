AdminStockManagementControllerCore
===============






* Class name: AdminStockManagementControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminStockManagementController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#L31)





Properties
----------


### $object

    public \Product $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminStockManagementController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#31)


Methods
-------


### __construct

    mixed AdminStockManagementControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#33)




### initPageHeaderToolbar

    mixed AdminStockManagementControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#80)




### renderList

    mixed AdminStockManagementControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#97)




### renderForm

    mixed AdminStockManagementControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#134)




### postProcess

    mixed AdminStockManagementControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#544)




### initToolbar

    mixed AdminStockManagementControllerCore::initToolbar()

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#755)




### init

    mixed AdminStockManagementControllerCore::init()

AdminController::init() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#792)




### renderDetails

    mixed AdminStockManagementControllerCore::renderDetails()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#812)




### getList

    mixed AdminStockManagementControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#895)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### skipActionByStock

    mixed AdminStockManagementControllerCore::skipActionByStock(array $item, boolean $is_product_variation)

Check stock for a given product or product attribute
and manage available actions in consequence



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 952](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#952)


#### Arguments
* $item **array** - &lt;p&gt;Reference to the current item&lt;/p&gt;
* $is_product_variation **boolean** - &lt;p&gt;Specify if it&#039;s a product or a product variation&lt;/p&gt;



### initContent

    mixed AdminStockManagementControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#977)




### displayAddstockLink

    string AdminStockManagementControllerCore::displayAddstockLink(string $token, integer $id)

Display addstock action link



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 1117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#1117)


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayRemovestockLink

    string AdminStockManagementControllerCore::displayRemovestockLink(string $token, integer $id)

Display removestock action link



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 1139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#1139)


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### displayTransferstockLink

    string AdminStockManagementControllerCore::displayTransferstockLink(string $token, integer $id)

Display transferstock action link



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 1161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#1161)


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### initProcess

    mixed AdminStockManagementControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStockManagementController.php line 1177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStockManagementController.php#1177)



