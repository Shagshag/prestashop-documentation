AdminShopControllerCore
===============






* Class name: AdminShopControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)

* This class is defined in [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#30)





Properties
----------


### $object

    public \Shop $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#30)


Methods
-------


### __construct

    mixed AdminShopControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#32)




### viewAccess

    mixed AdminShopControllerCore::viewAccess($disable)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#87)


#### Arguments
* $disable **mixed**



### initPageHeaderToolbar

    mixed AdminShopControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#92)




### initToolbar

    mixed AdminShopControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#119)




### initContent

    mixed AdminShopControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#140)




### renderList

    mixed AdminShopControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#199)




### displayAjaxGetCategoriesFromRootCategory

    mixed AdminShopControllerCore::displayAjaxGetCategoriesFromRootCategory()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#222)




### postProcess

    mixed AdminShopControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#238)




### processDelete

    mixed AdminShopControllerCore::processDelete()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#279)




### afterAdd

    boolean AdminShopControllerCore::afterAdd(\Shop $new_shop)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminShopController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#298)


#### Arguments
* $new_shop **[Shop](ShopCore)**



### afterUpdate

    boolean AdminShopControllerCore::afterUpdate(\Shop $new_shop)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminShopController.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#323)


#### Arguments
* $new_shop **[Shop](ShopCore)**



### getList

    mixed AdminShopControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#348)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### renderForm

    mixed AdminShopControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#366)




### processAdd

    mixed AdminShopControllerCore::processAdd()

Object creation



* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#647)




### displayEditLink

    mixed AdminShopControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#707)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### initCategoriesAssociation

    mixed AdminShopControllerCore::initCategoriesAssociation($id_root)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#727)


#### Arguments
* $id_root **mixed**



### ajaxProcessTree

    mixed AdminShopControllerCore::ajaxProcessTree()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminShopController.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#757)



