Class AdminStatusesControllerCore
=====================





* Class name: AdminStatusesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStatusesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [afterImageUpload](#method-afterImageUpload)
* [ajaxProcessDeliveryOrderState](#method-ajaxProcessDeliveryOrderState)
* [ajaxProcessInvoiceOrderState](#method-ajaxProcessInvoiceOrderState)
* [ajaxProcessSendEmailOrderState](#method-ajaxProcessSendEmailOrderState)
* [checkFilterForOrdersReturnsList](#method-checkFilterForOrdersReturnsList)
* [filterToField](#method-filterToField)
* [getTemplates](#method-getTemplates)
* [init](#method-init)
* [initOrderReturnsForm](#method-initOrderReturnsForm)
* [initOrderStatutsList](#method-initOrderStatutsList)
* [initOrdersReturnsList](#method-initOrdersReturnsList)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderOrderReturnsForm](#method-renderOrderReturnsForm)
* [renderOrderStatusForm](#method-renderOrderStatusForm)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \OrderState $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStatusesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L32)




### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminStatusesControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L626)




### <a name="method-ajaxProcessDeliveryOrderState"></a>ajaxProcessDeliveryOrderState

```php
mixed AdminStatusesControllerCore::ajaxProcessDeliveryOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L656)




### <a name="method-ajaxProcessInvoiceOrderState"></a>ajaxProcessInvoiceOrderState

```php
mixed AdminStatusesControllerCore::ajaxProcessInvoiceOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L670)




### <a name="method-ajaxProcessSendEmailOrderState"></a>ajaxProcessSendEmailOrderState

```php
mixed AdminStatusesControllerCore::ajaxProcessSendEmailOrderState()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L642)




### <a name="method-checkFilterForOrdersReturnsList"></a>checkFilterForOrdersReturnsList

```php
mixed AdminStatusesControllerCore::checkFilterForOrdersReturnsList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L242)




### <a name="method-filterToField"></a>filterToField

```php
mixed AdminStatusesControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L615)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-getTemplates"></a>getTemplates

```php
mixed AdminStatusesControllerCore::getTemplates()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L493)




### <a name="method-init"></a>init

```php
mixed AdminStatusesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L51)




### <a name="method-initOrderReturnsForm"></a>initOrderReturnsForm

```php
mixed AdminStatusesControllerCore::initOrderReturnsForm()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L148)




### <a name="method-initOrderStatutsList"></a>initOrderStatutsList

```php
mixed AdminStatusesControllerCore::initOrderStatutsList()
```

init all variables to render the order status list



* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L66)




### <a name="method-initOrdersReturnsList"></a>initOrdersReturnsList

```php
mixed AdminStatusesControllerCore::initOrdersReturnsList()
```

init all variables to render the order return list



* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L124)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStatusesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L188)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminStatusesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L527)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminStatusesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L257)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStatusesControllerCore::renderList()
```

Function used to render the list to display for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminStatusesController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L209)




### <a name="method-renderOrderReturnsForm"></a>renderOrderReturnsForm

```php
mixed AdminStatusesControllerCore::renderOrderReturnsForm()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L446)




### <a name="method-renderOrderStatusForm"></a>renderOrderStatusForm

```php
mixed AdminStatusesControllerCore::renderOrderStatusForm()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatusesController.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L419)



