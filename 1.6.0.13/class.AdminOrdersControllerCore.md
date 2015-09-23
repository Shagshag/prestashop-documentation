Class AdminOrdersControllerCore
=====================





* Class name: AdminOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminOrdersController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L38)


Contents
--------


### Properties

* [$statuses_array](#property-$statuses_array)
* [$toolbar_title](#property-$toolbar_title)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessAddProductOnOrder](#method-ajaxProcessAddProductOnOrder)
* [ajaxProcessChangePaymentMethod](#method-ajaxProcessChangePaymentMethod)
* [ajaxProcessDeleteProductLine](#method-ajaxProcessDeleteProductLine)
* [ajaxProcessEditProductOnOrder](#method-ajaxProcessEditProductOnOrder)
* [ajaxProcessLoadProductInformation](#method-ajaxProcessLoadProductInformation)
* [ajaxProcessSearchProducts](#method-ajaxProcessSearchProducts)
* [ajaxProcessSendMailValidateOrder](#method-ajaxProcessSendMailValidateOrder)
* [applyDiscountOnInvoice](#method-applyDiscountOnInvoice)
* [doDeleteProductLineValidation](#method-doDeleteProductLineValidation)
* [doEditProductValidation](#method-doEditProductValidation)
* [getProducts](#method-getProducts)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [printNewCustomer](#method-printNewCustomer)
* [printPDFIcons](#method-printPDFIcons)
* [processBulkUpdateOrderStatus](#method-processBulkUpdateOrderStatus)
* [reinjectQuantity](#method-reinjectQuantity)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [sendChangedNotification](#method-sendChangedNotification)
* [setMedia](#method-setMedia)
* [setOrderCurrency](#method-setOrderCurrency)




Properties
----------


### <a name="property-$statuses_array"></a>$statuses_array

```php
protected mixed $statuses_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L42).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
public mixed $toolbar_title
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminOrdersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L44)




### <a name="method-ajaxProcessAddProductOnOrder"></a>ajaxProcessAddProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L1870)




### <a name="method-ajaxProcessChangePaymentMethod"></a>ajaxProcessChangePaymentMethod

```php
mixed AdminOrdersControllerCore::ajaxProcessChangePaymentMethod()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2731](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2731)




### <a name="method-ajaxProcessDeleteProductLine"></a>ajaxProcessDeleteProductLine

```php
mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2434)




### <a name="method-ajaxProcessEditProductOnOrder"></a>ajaxProcessEditProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2252)




### <a name="method-ajaxProcessLoadProductInformation"></a>ajaxProcessLoadProductInformation

```php
mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2220)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L1767)




### <a name="method-ajaxProcessSendMailValidateOrder"></a>ajaxProcessSendMailValidateOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1846](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L1846)




### <a name="method-applyDiscountOnInvoice"></a>applyDiscountOnInvoice

```php
mixed AdminOrdersControllerCore::applyDiscountOnInvoice($order_invoice, $value_tax_incl, $value_tax_excl)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2721](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2721)


#### Arguments
* $order_invoice **mixed**
* $value_tax_incl **mixed**
* $value_tax_excl **mixed**



### <a name="method-doDeleteProductLineValidation"></a>doDeleteProductLineValidation

```php
mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2576](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2576)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**



### <a name="method-doEditProductValidation"></a>doEditProductValidation

```php
mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2513](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2513)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**



### <a name="method-getProducts"></a>getProducts

```php
mixed AdminOrdersControllerCore::getProducts($order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2604](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2604)


#### Arguments
* $order **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminOrdersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L202)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminOrdersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L266)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminOrdersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L433)




### <a name="method-printNewCustomer"></a>printNewCustomer

```php
mixed AdminOrdersControllerCore::printNewCustomer($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L354)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-printPDFIcons"></a>printPDFIcons

```php
mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 332](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L332)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-processBulkUpdateOrderStatus"></a>processBulkUpdateOrderStatus

```php
mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L359)




### <a name="method-reinjectQuantity"></a>reinjectQuantity

```php
mixed AdminOrdersControllerCore::reinjectQuantity($order_detail, $qty_cancel_product, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2627](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2627)


#### Arguments
* $order_detail **mixed**
* $qty_cancel_product **mixed**
* $delete **mixed**



### <a name="method-renderForm"></a>renderForm

```php
mixed AdminOrdersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L221)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminOrdersControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1517](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L1517)




### <a name="method-renderList"></a>renderList

```php
mixed AdminOrdersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L417)




### <a name="method-renderView"></a>renderView

```php
mixed AdminOrdersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1581](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L1581)




### <a name="method-sendChangedNotification"></a>sendChangedNotification

```php
mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L2198)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminOrdersControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L316)




### <a name="method-setOrderCurrency"></a>setOrderCurrency

```php
mixed AdminOrdersControllerCore::setOrderCurrency($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminOrdersController.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/controllers/admin/AdminOrdersController.php#L196)


#### Arguments
* $echo **mixed**
* $tr **mixed**


