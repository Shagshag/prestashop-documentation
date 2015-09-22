AdminCustomerThreadsControllerCore
===============






* Class name: AdminCustomerThreadsControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)

* This class is defined in [controllers/admin/AdminCustomerThreadsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#30)





Properties
----------


### $object

    public \CustomerThread $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCustomerThreadsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#30)


Methods
-------


### __construct

    mixed AdminCustomerThreadsControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#32)




### renderList

    mixed AdminCustomerThreadsControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#221)




### initToolbar

    mixed AdminCustomerThreadsControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#281)




### postProcess

    mixed AdminCustomerThreadsControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#287)




### initContent

    mixed AdminCustomerThreadsControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#440)




### openUploadedFile

    mixed AdminCustomerThreadsControllerCore::openUploadedFile()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#449)




### renderKpis

    mixed AdminCustomerThreadsControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#487)




### renderView

    mixed AdminCustomerThreadsControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#538)




### getTimeline

    mixed AdminCustomerThreadsControllerCore::getTimeline($messages, $id_order)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#699)


#### Arguments
* $messages **mixed**
* $id_order **mixed**



### displayMessage

    mixed AdminCustomerThreadsControllerCore::displayMessage($message, $email, $id_employee)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#746)


#### Arguments
* $message **mixed**
* $email **mixed**
* $id_employee **mixed**



### displayButton

    mixed AdminCustomerThreadsControllerCore::displayButton($content)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#797)


#### Arguments
* $content **mixed**



### renderOptions

    mixed AdminCustomerThreadsControllerCore::renderOptions()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#802)




### getList

    mixed AdminCustomerThreadsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#829)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### updateOptionPsSavImapOpt

    mixed AdminCustomerThreadsControllerCore::updateOptionPsSavImapOpt($value)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 841](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#841)


#### Arguments
* $value **mixed**



### ajaxProcessMarkAsRead

    mixed AdminCustomerThreadsControllerCore::ajaxProcessMarkAsRead()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#852)




### ajaxProcessSyncImap

    mixed AdminCustomerThreadsControllerCore::ajaxProcessSyncImap()

Call the IMAP synchronization during an AJAX process.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#870)




### renderProcessSyncImap

    mixed AdminCustomerThreadsControllerCore::renderProcessSyncImap()

Call the IMAP synchronization during the render process.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 884](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#884)




### syncImap

    array AdminCustomerThreadsControllerCore::syncImap()

Imap synchronization method.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomerThreadsController.php line 913](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#913)



