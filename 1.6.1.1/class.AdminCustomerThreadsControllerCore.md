Class AdminCustomerThreadsControllerCore
=====================





* Class name: AdminCustomerThreadsControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminCustomerThreadsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L30)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessMarkAsRead](#method-ajaxProcessMarkAsRead)
* [ajaxProcessSyncImap](#method-ajaxProcessSyncImap)
* [displayButton](#method-displayButton)
* [displayMessage](#method-displayMessage)
* [getList](#method-getList)
* [getTimeline](#method-getTimeline)
* [initContent](#method-initContent)
* [initToolbar](#method-initToolbar)
* [openUploadedFile](#method-openUploadedFile)
* [postProcess](#method-postProcess)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderOptions](#method-renderOptions)
* [renderProcessSyncImap](#method-renderProcessSyncImap)
* [renderView](#method-renderView)
* [syncImap](#method-syncImap)
* [updateOptionPsSavImapOpt](#method-updateOptionPsSavImapOpt)




Properties
----------


### <a name="property-$object"></a>$object

    public \CustomerThread $object





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCustomerThreadsControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L32)




### <a name="method-ajaxProcessMarkAsRead"></a>ajaxProcessMarkAsRead

    mixed AdminCustomerThreadsControllerCore::ajaxProcessMarkAsRead()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L852)




### <a name="method-ajaxProcessSyncImap"></a>ajaxProcessSyncImap

    mixed AdminCustomerThreadsControllerCore::ajaxProcessSyncImap()

Call the IMAP synchronization during an AJAX process.



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L870)




### <a name="method-displayButton"></a>displayButton

    mixed AdminCustomerThreadsControllerCore::displayButton($content)





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L797)


#### Arguments
* $content **mixed**



### <a name="method-displayMessage"></a>displayMessage

    mixed AdminCustomerThreadsControllerCore::displayMessage($message, $email, $id_employee)





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L746)


#### Arguments
* $message **mixed**
* $email **mixed**
* $id_employee **mixed**



### <a name="method-getList"></a>getList

    mixed AdminCustomerThreadsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L829)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-getTimeline"></a>getTimeline

    mixed AdminCustomerThreadsControllerCore::getTimeline($messages, $id_order)





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L699)


#### Arguments
* $messages **mixed**
* $id_order **mixed**



### <a name="method-initContent"></a>initContent

    mixed AdminCustomerThreadsControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L440)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminCustomerThreadsControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L281)




### <a name="method-openUploadedFile"></a>openUploadedFile

    mixed AdminCustomerThreadsControllerCore::openUploadedFile()





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L449)




### <a name="method-postProcess"></a>postProcess

    mixed AdminCustomerThreadsControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L287)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminCustomerThreadsControllerCore::renderKpis()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L487)




### <a name="method-renderList"></a>renderList

    mixed AdminCustomerThreadsControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L221)




### <a name="method-renderOptions"></a>renderOptions

    mixed AdminCustomerThreadsControllerCore::renderOptions()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L802)




### <a name="method-renderProcessSyncImap"></a>renderProcessSyncImap

    mixed AdminCustomerThreadsControllerCore::renderProcessSyncImap()

Call the IMAP synchronization during the render process.



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 884](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L884)




### <a name="method-renderView"></a>renderView

    mixed AdminCustomerThreadsControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L538)




### <a name="method-syncImap"></a>syncImap

    array AdminCustomerThreadsControllerCore::syncImap()

Imap synchronization method.



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 913](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L913)




### <a name="method-updateOptionPsSavImapOpt"></a>updateOptionPsSavImapOpt

    mixed AdminCustomerThreadsControllerCore::updateOptionPsSavImapOpt($value)





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 841](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomerThreadsController.php#L841)


#### Arguments
* $value **mixed**


