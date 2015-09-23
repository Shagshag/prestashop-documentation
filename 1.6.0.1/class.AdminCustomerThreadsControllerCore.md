Class AdminCustomerThreadsControllerCore
=====================





* Class name: AdminCustomerThreadsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCustomerThreadsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L27)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [ajaxProcessMarkAsRead](#method-ajaxProcessMarkAsRead)
* [ajaxProcessSyncImap](#method-ajaxProcessSyncImap)
* [displayButton](#method-displayButton)
* [displayMessage](#method-displayMessage)
* [getList](#method-getList)
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
* Source: [controllers/admin/AdminCustomerThreadsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L29)




### <a name="method-ajaxProcessMarkAsRead"></a>ajaxProcessMarkAsRead

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessMarkAsRead()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 716](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L716)




### <a name="method-ajaxProcessSyncImap"></a>ajaxProcessSyncImap

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessSyncImap()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L727)




### <a name="method-displayButton"></a>displayButton

```php
mixed AdminCustomerThreadsControllerCore::displayButton($content)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L668)


#### Arguments
* $content **mixed**



### <a name="method-displayMessage"></a>displayMessage

```php
mixed AdminCustomerThreadsControllerCore::displayMessage($message, $email, $id_employee)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L621)


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
* Source: [controllers/admin/AdminCustomerThreadsController.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L695)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminCustomerThreadsControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L427)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCustomerThreadsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L263)




### <a name="method-openUploadedFile"></a>openUploadedFile

```php
mixed AdminCustomerThreadsControllerCore::openUploadedFile()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L435)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCustomerThreadsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L269)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCustomerThreadsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L470)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCustomerThreadsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L212)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminCustomerThreadsControllerCore::renderOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 678](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L678)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCustomerThreadsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 517](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L517)




### <a name="method-updateOptionPsSavImapOpt"></a>updateOptionPsSavImapOpt

```php
mixed AdminCustomerThreadsControllerCore::updateOptionPsSavImapOpt($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomerThreadsController.php#L707)


#### Arguments
* $value **mixed**


