Class AdminOrdersControllerCore
=====================





* Class name: AdminOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminOrdersController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L27)


Contents
--------


### Properties

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
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [printPDFIcons](#method-printPDFIcons)
* [reinjectQuantity](#method-reinjectQuantity)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderView](#method-renderView)
* [sendChangedNotification](#method-sendChangedNotification)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
public mixed $toolbar_title
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminOrdersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L31)




### <a name="method-ajaxProcessAddProductOnOrder"></a>ajaxProcessAddProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1615)




### <a name="method-ajaxProcessDeleteProductLine"></a>ajaxProcessDeleteProductLine

```php
mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 2140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L2140)




### <a name="method-ajaxProcessEditProductOnOrder"></a>ajaxProcessEditProductOnOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1958](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1958)




### <a name="method-ajaxProcessLoadProductInformation"></a>ajaxProcessLoadProductInformation

```php
mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1926](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1926)




### <a name="method-ajaxProcessSearchCustomers"></a>ajaxProcessSearchCustomers

```php
mixed AdminOrdersControllerCore::ajaxProcessSearchCustomers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1502](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1502)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1512](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1512)




### <a name="method-ajaxProcessSendMailValidateOrder"></a>ajaxProcessSendMailValidateOrder

```php
mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1591](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1591)




### <a name="method-applyDiscountOnInvoice"></a>applyDiscountOnInvoice

```php
mixed AdminOrdersControllerCore::applyDiscountOnInvoice($order_invoice, $value_tax_incl, $value_tax_excl)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2386](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L2386)


#### Arguments
* $order_invoice **mixed**
* $value_tax_incl **mixed**
* $value_tax_excl **mixed**



### <a name="method-doDeleteProductLineValidation"></a>doDeleteProductLineValidation

```php
mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2285](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L2285)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**



### <a name="method-doEditProductValidation"></a>doEditProductValidation

```php
mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2222](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L2222)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $order **[Order](class.OrderCore.md)**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**



### <a name="method-getProducts"></a>getProducts

```php
mixed AdminOrdersControllerCore::getProducts($order)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L2313)


#### Arguments
* $order **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminOrdersControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L167)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminOrdersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L172)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminOrdersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L234)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminOrdersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L305)




### <a name="method-printPDFIcons"></a>printPDFIcons

```php
mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L289)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-reinjectQuantity"></a>reinjectQuantity

```php
mixed AdminOrdersControllerCore::reinjectQuantity($order_detail, $qty_cancel_product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminOrdersController.php line 2334](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L2334)


#### Arguments
* $order_detail **mixed**
* $qty_cancel_product **mixed**



### <a name="method-renderForm"></a>renderForm

```php
mixed AdminOrdersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L191)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminOrdersControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1286)




### <a name="method-renderView"></a>renderView

```php
mixed AdminOrdersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1350](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1350)




### <a name="method-sendChangedNotification"></a>sendChangedNotification

```php
mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 1904](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L1904)


#### Arguments
* $order **[Order](class.OrderCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminOrdersControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOrdersController.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminOrdersController.php#L276)



