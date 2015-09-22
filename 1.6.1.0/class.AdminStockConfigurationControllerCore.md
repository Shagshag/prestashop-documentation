Class AdminStockConfigurationControllerCore
=====================





* Class name: AdminStockConfigurationControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockConfigurationController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L31)


Contents
--------


### Properties

* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessDeliveryNoteSupplyOrderState](#method-ajaxProcessDeliveryNoteSupplyOrderState)
* [ajaxProcessEditableSupplyOrderState](#method-ajaxProcessEditableSupplyOrderState)
* [ajaxProcessEnclosedSupplyOrderState](#method-ajaxProcessEnclosedSupplyOrderState)
* [ajaxProcessPendingReceiptSupplyOrderState](#method-ajaxProcessPendingReceiptSupplyOrderState)
* [ajaxProcessReceiptStateSupplyOrderState](#method-ajaxProcessReceiptStateSupplyOrderState)
* [getList](#method-getList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initProcess](#method-initProcess)
* [initSupplyOrderStatusList](#method-initSupplyOrderStatusList)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \StockMvtReason $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStockConfigurationControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L36)




### <a name="method-ajaxProcessDeliveryNoteSupplyOrderState"></a>ajaxProcessDeliveryNoteSupplyOrderState

```php
mixed AdminStockConfigurationControllerCore::ajaxProcessDeliveryNoteSupplyOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 584](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L584)




### <a name="method-ajaxProcessEditableSupplyOrderState"></a>ajaxProcessEditableSupplyOrderState

```php
mixed AdminStockConfigurationControllerCore::ajaxProcessEditableSupplyOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L571)




### <a name="method-ajaxProcessEnclosedSupplyOrderState"></a>ajaxProcessEnclosedSupplyOrderState

```php
mixed AdminStockConfigurationControllerCore::ajaxProcessEnclosedSupplyOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L623)




### <a name="method-ajaxProcessPendingReceiptSupplyOrderState"></a>ajaxProcessPendingReceiptSupplyOrderState

```php
mixed AdminStockConfigurationControllerCore::ajaxProcessPendingReceiptSupplyOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L597)




### <a name="method-ajaxProcessReceiptStateSupplyOrderState"></a>ajaxProcessReceiptStateSupplyOrderState

```php
mixed AdminStockConfigurationControllerCore::ajaxProcessReceiptStateSupplyOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L610)




### <a name="method-getList"></a>getList

```php
mixed AdminStockConfigurationControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 531](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L531)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-init"></a>init

```php
mixed AdminStockConfigurationControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L129)




### <a name="method-initContent"></a>initContent

```php
mixed AdminStockConfigurationControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 551](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L551)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminStockConfigurationControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L561)




### <a name="method-initSupplyOrderStatusList"></a>initSupplyOrderStatusList

```php
mixed AdminStockConfigurationControllerCore::initSupplyOrderStatusList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L417)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminStockConfigurationControllerCore::postProcess()
```

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L495)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminStockConfigurationControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L149)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStockConfigurationControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockConfigurationController.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockConfigurationController.php#L369)



