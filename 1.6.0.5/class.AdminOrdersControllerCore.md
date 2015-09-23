Class AdminOrdersControllerCore
=====================





* Class name: AdminOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminOrdersController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L27)


Contents
--------


### Properties

* [$statuses_array](#property-$statuses_array)
* [$toolbar_title](#property-$toolbar_title)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessAddProductOnOrder](#method-ajaxProcessAddProductOnOrder)
* [ajaxProcessDeleteProductLine](#method-ajaxProcessDeleteProductLine)
* [ajaxProcessEditProductOnOrder](#method-ajaxProcessEditProductOnOrder)
* [ajaxProcessLoadProductInformation](#method-ajaxProcessLoadProductInformation)
* [ajaxProcessSearchCustomers](#method-ajaxProcessSearchCustomers)
* [ajaxProcessSearchProducts](#method-ajaxProcessSearchProducts)
* [ajaxProcessSendMailValidateOrder](#method-ajaxProcessSendMailValidateOrder)
* [applyDiscountOnInvoice](#method-applyDiscountOnInvoice)
* [doDeleteProductLineValidation](#method-doDeleteProductLineValidation)
* [doEditProductValidation](#method-doEditProductValidation)
* [getProducts](#method-getProducts)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [printPDFIcons](#method-printPDFIcons)
* [processBulkUpdateOrderStatus](#method-processBulkUpdateOrderStatus)
* [reinjectQuantity](#method-reinjectQuantity)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [sendChangedNotification](#method-sendChangedNotification)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$statuses_array"></a>$statuses_array

```php
protected mixed $statuses_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L31).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
public mixed $toolbar_title
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminOrdersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L33)




### <a name="method-ajaxProcessAddProductOnOrder"></a>ajaxProcessAddProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1708](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L1708)




### <a name="method-ajaxProcessDeleteProductLine"></a>ajaxProcessDeleteProductLine

```php
mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2233)




### <a name="method-ajaxProcessEditProductOnOrder"></a>ajaxProcessEditProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2051](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2051)




### <a name="method-ajaxProcessLoadProductInformation"></a>ajaxProcessLoadProductInformation

```php
mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2019](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2019)




### <a name="method-ajaxProcessSearchCustomers"></a>ajaxProcessSearchCustomers

```php
mixed AdminOrdersControllerCore::ajaxProcessSearchCustomers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1595](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L1595)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1605](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L1605)




### <a name="method-ajaxProcessSendMailValidateOrder"></a>ajaxProcessSendMailValidateOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1684](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L1684)




### <a name="method-applyDiscountOnInvoice"></a>applyDiscountOnInvoice

```php
mixed AdminOrdersControllerCore::applyDiscountOnInvoice($order_invoice, $value_tax_incl, $value_tax_excl)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2479](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2479)


#### Arguments
* $order_invoice **mixed**
* $value_tax_incl **mixed**
* $value_tax_excl **mixed**



### <a name="method-doDeleteProductLineValidation"></a>doDeleteProductLineValidation

```php
mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2378](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2378)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**



### <a name="method-doEditProductValidation"></a>doEditProductValidation

```php
mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2315)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**



### <a name="method-getProducts"></a>getProducts

```php
mixed AdminOrdersControllerCore::getProducts($order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2406](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2406)


#### Arguments
* $order **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminOrdersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L183)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminOrdersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L245)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminOrdersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L393)




### <a name="method-printPDFIcons"></a>printPDFIcons

```php
mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L303)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-processBulkUpdateOrderStatus"></a>processBulkUpdateOrderStatus

```php
mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L319)




### <a name="method-reinjectQuantity"></a>reinjectQuantity

```php
mixed AdminOrdersControllerCore::reinjectQuantity($order_detail, $qty_cancel_product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2427](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L2427)


#### Arguments
* $order_detail **mixed**
* $qty_cancel_product **mixed**



### <a name="method-renderForm"></a>renderForm

```php
mixed AdminOrdersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L202)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminOrdersControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1374](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L1374)




### <a name="method-renderList"></a>renderList

```php
mixed AdminOrdersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L377)




### <a name="method-renderView"></a>renderView

```php
mixed AdminOrdersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1438](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L1438)




### <a name="method-sendChangedNotification"></a>sendChangedNotification

```php
mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1997](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L1997)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminOrdersControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminOrdersController.php#L287)



