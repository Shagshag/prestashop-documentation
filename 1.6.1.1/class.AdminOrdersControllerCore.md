Class AdminOrdersControllerCore
=====================





* Class name: AdminOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminOrdersController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L41)


Contents
--------


### Properties

* [$object](#property-$object)
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


### <a name="property-$object"></a>$object

```php
public \Order $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L41).


### <a name="property-$statuses_array"></a>$statuses_array

```php
protected mixed $statuses_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L45).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
public mixed $toolbar_title
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L43).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminOrdersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L47)




### <a name="method-ajaxProcessAddProductOnOrder"></a>ajaxProcessAddProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1893](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1893)




### <a name="method-ajaxProcessChangePaymentMethod"></a>ajaxProcessChangePaymentMethod

```php
mixed AdminOrdersControllerCore::ajaxProcessChangePaymentMethod()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2783)




### <a name="method-ajaxProcessDeleteProductLine"></a>ajaxProcessDeleteProductLine

```php
mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2463)




### <a name="method-ajaxProcessEditProductOnOrder"></a>ajaxProcessEditProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2272)




### <a name="method-ajaxProcessLoadProductInformation"></a>ajaxProcessLoadProductInformation

```php
mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2236)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1792)




### <a name="method-ajaxProcessSendMailValidateOrder"></a>ajaxProcessSendMailValidateOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1871](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1871)




### <a name="method-applyDiscountOnInvoice"></a>applyDiscountOnInvoice

```php
mixed AdminOrdersControllerCore::applyDiscountOnInvoice(\OrderInvoice $order_invoice, float $value_tax_incl, float $value_tax_excl)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2773)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $value_tax_incl **float**
* $value_tax_excl **float**



### <a name="method-doDeleteProductLineValidation"></a>doDeleteProductLineValidation

```php
mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2615)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**



### <a name="method-doEditProductValidation"></a>doEditProductValidation

```php
mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2542](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2542)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**



### <a name="method-getProducts"></a>getProducts

```php
array AdminOrdersControllerCore::getProducts(\Order $order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2651)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminOrdersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L205)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminOrdersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L277)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminOrdersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L450)




### <a name="method-printNewCustomer"></a>printNewCustomer

```php
mixed AdminOrdersControllerCore::printNewCustomer($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L373)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-printPDFIcons"></a>printPDFIcons

```php
mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L348)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-processBulkUpdateOrderStatus"></a>processBulkUpdateOrderStatus

```php
mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L378)




### <a name="method-reinjectQuantity"></a>reinjectQuantity

```php
mixed AdminOrdersControllerCore::reinjectQuantity(\OrderDetail $order_detail, integer $qty_cancel_product, boolean $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2678](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2678)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $qty_cancel_product **integer**
* $delete **boolean**



### <a name="method-renderForm"></a>renderForm

```php
mixed AdminOrdersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L227)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminOrdersControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1528)




### <a name="method-renderList"></a>renderList

```php
mixed AdminOrdersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L434)




### <a name="method-renderView"></a>renderView

```php
mixed AdminOrdersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1597)




### <a name="method-sendChangedNotification"></a>sendChangedNotification

```php
mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2227)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminOrdersControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L333)




### <a name="method-setOrderCurrency"></a>setOrderCurrency

```php
mixed AdminOrdersControllerCore::setOrderCurrency($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminOrdersController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L199)


#### Arguments
* $echo **mixed**
* $tr **mixed**


