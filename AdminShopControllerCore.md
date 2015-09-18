AdminShopControllerCore
===============






* Class name: AdminShopControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \Shop $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminShopControllerCore::__construct()





* Visibility: **public**




### viewAccess

    mixed AdminShopControllerCore::viewAccess($disable)





* Visibility: **public**


#### Arguments
* $disable **mixed**



### initPageHeaderToolbar

    mixed AdminShopControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initToolbar

    mixed AdminShopControllerCore::initToolbar()





* Visibility: **public**




### initContent

    mixed AdminShopControllerCore::initContent()





* Visibility: **public**




### renderList

    mixed AdminShopControllerCore::renderList()





* Visibility: **public**




### displayAjaxGetCategoriesFromRootCategory

    mixed AdminShopControllerCore::displayAjaxGetCategoriesFromRootCategory()





* Visibility: **public**




### postProcess

    mixed AdminShopControllerCore::postProcess()





* Visibility: **public**




### processDelete

    mixed AdminShopControllerCore::processDelete()





* Visibility: **public**




### afterAdd

    boolean AdminShopControllerCore::afterAdd(\Shop $new_shop)





* Visibility: **protected**


#### Arguments
* $new_shop **Shop**



### afterUpdate

    boolean AdminShopControllerCore::afterUpdate(\Shop $new_shop)





* Visibility: **protected**


#### Arguments
* $new_shop **Shop**



### getList

    mixed AdminShopControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**


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




### processAdd

    mixed AdminShopControllerCore::processAdd()

Object creation



* Visibility: **public**




### displayEditLink

    mixed AdminShopControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### initCategoriesAssociation

    mixed AdminShopControllerCore::initCategoriesAssociation($id_root)





* Visibility: **public**


#### Arguments
* $id_root **mixed**



### ajaxProcessTree

    mixed AdminShopControllerCore::ajaxProcessTree()





* Visibility: **public**



