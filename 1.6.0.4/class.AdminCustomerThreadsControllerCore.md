Class AdminCustomerThreadsControllerCore
=====================





* Class name: AdminCustomerThreadsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCustomerThreadsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L27)


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
* Source: [controllers/admin/AdminCustomerThreadsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L29)




### <a name="method-ajaxProcessMarkAsRead"></a>ajaxProcessMarkAsRead

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessMarkAsRead()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L796)




### <a name="method-ajaxProcessSyncImap"></a>ajaxProcessSyncImap

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessSyncImap()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L807)




### <a name="method-displayButton"></a>displayButton

```php
mixed AdminCustomerThreadsControllerCore::displayButton($content)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L753)


#### Arguments
* $content **mixed**



### <a name="method-displayMessage"></a>displayMessage

```php
mixed AdminCustomerThreadsControllerCore::displayMessage($message, $email, $id_employee)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L704)


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
* Source: [controllers/admin/AdminCustomerThreadsController.php line 775](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L775)


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
* Source: [controllers/admin/AdminCustomerThreadsController.php line 663](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L663)


#### Arguments
* $messages **mixed**
* $id_order **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminCustomerThreadsControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L439)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCustomerThreadsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L266)




### <a name="method-openUploadedFile"></a>openUploadedFile

```php
mixed AdminCustomerThreadsControllerCore::openUploadedFile()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L447)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCustomerThreadsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L272)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCustomerThreadsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L483)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCustomerThreadsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L215)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminCustomerThreadsControllerCore::renderOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L758)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCustomerThreadsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L530)




### <a name="method-updateOptionPsSavImapOpt"></a>updateOptionPsSavImapOpt

```php
mixed AdminCustomerThreadsControllerCore::updateOptionPsSavImapOpt($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminCustomerThreadsController.php#L787)


#### Arguments
* $value **mixed**


