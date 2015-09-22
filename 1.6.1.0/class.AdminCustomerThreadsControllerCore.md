Class AdminCustomerThreadsControllerCore
=====================





* Class name: AdminCustomerThreadsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCustomerThreadsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

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
* [renderProcessSyncImap](#method-renderProcessSyncImap)
* [renderView](#method-renderView)
* [syncImap](#method-syncImap)
* [updateOptionPsSavImapOpt](#method-updateOptionPsSavImapOpt)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \CustomerThread $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCustomerThreadsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L32)




### <a name="method-ajaxProcessMarkAsRead"></a>ajaxProcessMarkAsRead

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessMarkAsRead()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 848](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L848)




### <a name="method-ajaxProcessSyncImap"></a>ajaxProcessSyncImap

```php
mixed AdminCustomerThreadsControllerCore::ajaxProcessSyncImap()
```

Call the IMAP synchronization during an AJAX process.



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L864)




### <a name="method-displayButton"></a>displayButton

```php
mixed AdminCustomerThreadsControllerCore::displayButton($content)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L796)


#### Arguments
* $content **mixed**



### <a name="method-displayMessage"></a>displayMessage

```php
mixed AdminCustomerThreadsControllerCore::displayMessage($message, $email, $id_employee)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L747)


#### Arguments
* $message **mixed**
* $email **mixed**
* $id_employee **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminCustomerThreadsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L827)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-getTimeline"></a>getTimeline

```php
mixed AdminCustomerThreadsControllerCore::getTimeline($messages, $id_order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 698](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L698)


#### Arguments
* $messages **mixed**
* $id_order **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminCustomerThreadsControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L450)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCustomerThreadsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L277)




### <a name="method-openUploadedFile"></a>openUploadedFile

```php
mixed AdminCustomerThreadsControllerCore::openUploadedFile()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L458)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCustomerThreadsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L283)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCustomerThreadsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L494)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCustomerThreadsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L218)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminCustomerThreadsControllerCore::renderOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 801](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L801)




### <a name="method-renderProcessSyncImap"></a>renderProcessSyncImap

```php
mixed AdminCustomerThreadsControllerCore::renderProcessSyncImap()
```

Call the IMAP synchronization during the render process.



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L876)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCustomerThreadsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L542)




### <a name="method-syncImap"></a>syncImap

```php
array AdminCustomerThreadsControllerCore::syncImap()
```

Imap synchronization method.



* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 901](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L901)




### <a name="method-updateOptionPsSavImapOpt"></a>updateOptionPsSavImapOpt

```php
mixed AdminCustomerThreadsControllerCore::updateOptionPsSavImapOpt($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomerThreadsController.php line 839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomerThreadsController.php#L839)


#### Arguments
* $value **mixed**


