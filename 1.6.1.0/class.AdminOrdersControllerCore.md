Class AdminOrdersControllerCore
=====================





* Class name: AdminOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminOrdersController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L41)


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
* Source: [controllers/admin/AdminOrdersController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L41).


### <a name="property-$statuses_array"></a>$statuses_array

```php
protected mixed $statuses_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L45).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
public mixed $toolbar_title
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L43).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminOrdersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L47)




### <a name="method-ajaxProcessAddProductOnOrder"></a>ajaxProcessAddProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1911](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L1911)




### <a name="method-ajaxProcessChangePaymentMethod"></a>ajaxProcessChangePaymentMethod

```php
mixed AdminOrdersControllerCore::ajaxProcessChangePaymentMethod()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2794](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2794)




### <a name="method-ajaxProcessDeleteProductLine"></a>ajaxProcessDeleteProductLine

```php
mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2482](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2482)




### <a name="method-ajaxProcessEditProductOnOrder"></a>ajaxProcessEditProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2290)




### <a name="method-ajaxProcessLoadProductInformation"></a>ajaxProcessLoadProductInformation

```php
mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2257)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L1808)




### <a name="method-ajaxProcessSendMailValidateOrder"></a>ajaxProcessSendMailValidateOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1887](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L1887)




### <a name="method-applyDiscountOnInvoice"></a>applyDiscountOnInvoice

```php
mixed AdminOrdersControllerCore::applyDiscountOnInvoice(\OrderInvoice $order_invoice, float $value_tax_incl, float $value_tax_excl)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2784](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2784)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $value_tax_incl **float**
* $value_tax_excl **float**



### <a name="method-doDeleteProductLineValidation"></a>doDeleteProductLineValidation

```php
mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2625)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**



### <a name="method-doEditProductValidation"></a>doEditProductValidation

```php
mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2562](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2562)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**



### <a name="method-getProducts"></a>getProducts

```php
array AdminOrdersControllerCore::getProducts(\Order $order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2657)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminOrdersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L206)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminOrdersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L270)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminOrdersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L438)




### <a name="method-printNewCustomer"></a>printNewCustomer

```php
mixed AdminOrdersControllerCore::printNewCustomer($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L359)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-printPDFIcons"></a>printPDFIcons

```php
mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L337)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-processBulkUpdateOrderStatus"></a>processBulkUpdateOrderStatus

```php
mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L364)




### <a name="method-reinjectQuantity"></a>reinjectQuantity

```php
mixed AdminOrdersControllerCore::reinjectQuantity(\OrderDetail $order_detail, integer $qty_cancel_product, boolean $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2685)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $qty_cancel_product **integer**
* $delete **boolean**



### <a name="method-renderForm"></a>renderForm

```php
mixed AdminOrdersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L225)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminOrdersControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L1550)




### <a name="method-renderList"></a>renderList

```php
mixed AdminOrdersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L422)




### <a name="method-renderView"></a>renderView

```php
mixed AdminOrdersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1614](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L1614)




### <a name="method-sendChangedNotification"></a>sendChangedNotification

```php
mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L2249)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminOrdersControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L321)




### <a name="method-setOrderCurrency"></a>setOrderCurrency

```php
mixed AdminOrdersControllerCore::setOrderCurrency($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminOrdersController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOrdersController.php#L200)


#### Arguments
* $echo **mixed**
* $tr **mixed**


