Class AdminCustomerThreadsControllerCore
=====================





* Class name: AdminCustomerThreadsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCustomerThreadsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L27)


Contents
--------



### Methods

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
* [renderView](#method-renderView)
* [updateOptionPsSavImapOpt](#method-updateOptionPsSavImapOpt)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCustomerThreadsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L29)




### <a name="method-ajaxProcessMarkAsRead"></a>ajaxProcessMarkAsRead

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessMarkAsRead()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L805)




### <a name="method-ajaxProcessSyncImap"></a>ajaxProcessSyncImap

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessSyncImap()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L816)




### <a name="method-displayButton"></a>displayButton

```php
mixed AdminCustomerThreadsControllerCore::displayButton($content)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 762](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L762)


#### Arguments
* $content **mixed**



### <a name="method-displayMessage"></a>displayMessage

```php
mixed AdminCustomerThreadsControllerCore::displayMessage($message, $email, $id_employee)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 713](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L713)


#### Arguments
* $message **mixed**
* $email **mixed**
* $id_employee **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminCustomerThreadsControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 784](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L784)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getTimeline"></a>getTimeline

```php
mixed AdminCustomerThreadsControllerCore::getTimeline($messages, $id_order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L672)


#### Arguments
* $messages **mixed**
* $id_order **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminCustomerThreadsControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 441](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L441)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCustomerThreadsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L268)




### <a name="method-openUploadedFile"></a>openUploadedFile

```php
mixed AdminCustomerThreadsControllerCore::openUploadedFile()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L449)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCustomerThreadsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L274)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCustomerThreadsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L485)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCustomerThreadsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L215)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminCustomerThreadsControllerCore::renderOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L767)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCustomerThreadsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L533)




### <a name="method-updateOptionPsSavImapOpt"></a>updateOptionPsSavImapOpt

```php
mixed AdminCustomerThreadsControllerCore::updateOptionPsSavImapOpt($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/admin/AdminCustomerThreadsController.php#L796)


#### Arguments
* $value **mixed**


