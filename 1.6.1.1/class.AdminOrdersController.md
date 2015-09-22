Class AdminOrdersController
=====================

DISCLAIMER

Do not edit or add to this file if you wish to upgrade this module to newer
versions in the future. If you wish to customize this module for your
needs please refer to http://doc.prestashop.com/display/PS15/Overriding+default+behaviors
#Overridingdefaultbehaviors-Overridingamodule%27sbehavior for more information.

* Class name: AdminOrdersController
* Parent class: [AdminOrdersControllerCore](class.AdminOrdersControllerCore)
* Source: [override/controllers/admin/AdminOrdersController.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L16)



Properties
----------

* [$statuses_array](#property-$statuses_array)
* [$toolbar_title](#property-$toolbar_title)
* [$object](#property-$object)

Methods
-------
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

    protected mixed $statuses_array = array()





* Visibility: **protected**
* Source: [override/controllers/admin/AdminOrdersController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L45)


### <a name="property-$toolbar_title"></a>$toolbar_title

    public mixed $toolbar_title





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L43)


### <a name="property-$object"></a>$object

    public \Order $object





* Visibility: **public**
* This property is defined by [AdminOrdersControllerCore](class.AdminOrdersControllerCore)
* Source: [override/controllers/admin/AdminOrdersController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L41)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminOrdersController::__construct()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L47)




### <a name="method-ajaxProcessAddProductOnOrder"></a>ajaxProcessAddProductOnOrder

    mixed AdminOrdersController::ajaxProcessAddProductOnOrder()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 1893](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L1893)




### <a name="method-ajaxProcessChangePaymentMethod"></a>ajaxProcessChangePaymentMethod

    mixed AdminOrdersController::ajaxProcessChangePaymentMethod()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 2783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2783)




### <a name="method-ajaxProcessDeleteProductLine"></a>ajaxProcessDeleteProductLine

    mixed AdminOrdersController::ajaxProcessDeleteProductLine()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 2463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2463)




### <a name="method-ajaxProcessEditProductOnOrder"></a>ajaxProcessEditProductOnOrder

    mixed AdminOrdersController::ajaxProcessEditProductOnOrder()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 2272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2272)




### <a name="method-ajaxProcessLoadProductInformation"></a>ajaxProcessLoadProductInformation

    mixed AdminOrdersController::ajaxProcessLoadProductInformation()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 2236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2236)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

    mixed AdminOrdersController::ajaxProcessSearchProducts()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 1792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L1792)




### <a name="method-ajaxProcessSendMailValidateOrder"></a>ajaxProcessSendMailValidateOrder

    mixed AdminOrdersController::ajaxProcessSendMailValidateOrder()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 1871](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L1871)




### <a name="method-applyDiscountOnInvoice"></a>applyDiscountOnInvoice

    mixed AdminOrdersController::applyDiscountOnInvoice(\OrderInvoice $order_invoice, float $value_tax_incl, float $value_tax_excl)





* Visibility: **protected**
* Source: [override/controllers/admin/AdminOrdersController.php line 2773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2773)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore)**
* $value_tax_incl **float**
* $value_tax_excl **float**



### <a name="method-doDeleteProductLineValidation"></a>doDeleteProductLineValidation

    mixed AdminOrdersController::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)





* Visibility: **protected**
* Source: [override/controllers/admin/AdminOrdersController.php line 2615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2615)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore)**
* $order **[Order](class.OrderCore)**



### <a name="method-doEditProductValidation"></a>doEditProductValidation

    mixed AdminOrdersController::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)





* Visibility: **protected**
* Source: [override/controllers/admin/AdminOrdersController.php line 2542](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2542)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore)**
* $order **[Order](class.OrderCore)**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore)**



### <a name="method-getProducts"></a>getProducts

    array AdminOrdersController::getProducts(\Order $order)





* Visibility: **protected**
* Source: [override/controllers/admin/AdminOrdersController.php line 2651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2651)


#### Arguments
* $order **[Order](class.OrderCore)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminOrdersController::initPageHeaderToolbar()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L205)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminOrdersController::initToolbar()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L277)




### <a name="method-postProcess"></a>postProcess

    mixed AdminOrdersController::postProcess()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L450)




### <a name="method-printNewCustomer"></a>printNewCustomer

    mixed AdminOrdersController::printNewCustomer($id_order, $tr)





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L373)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-printPDFIcons"></a>printPDFIcons

    mixed AdminOrdersController::printPDFIcons($id_order, $tr)





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L348)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-processBulkUpdateOrderStatus"></a>processBulkUpdateOrderStatus

    mixed AdminOrdersController::processBulkUpdateOrderStatus()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L378)




### <a name="method-reinjectQuantity"></a>reinjectQuantity

    mixed AdminOrdersController::reinjectQuantity(\OrderDetail $order_detail, integer $qty_cancel_product, boolean $delete)





* Visibility: **protected**
* Source: [override/controllers/admin/AdminOrdersController.php line 2678](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2678)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore)**
* $qty_cancel_product **integer**
* $delete **boolean**



### <a name="method-renderForm"></a>renderForm

    mixed AdminOrdersController::renderForm()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L227)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminOrdersController::renderKpis()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 1528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L1528)




### <a name="method-renderList"></a>renderList

    mixed AdminOrdersController::renderList()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L434)




### <a name="method-renderView"></a>renderView

    mixed AdminOrdersController::renderView()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 1597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L1597)




### <a name="method-sendChangedNotification"></a>sendChangedNotification

    mixed AdminOrdersController::sendChangedNotification(\Order $order)





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 2227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L2227)


#### Arguments
* $order **[Order](class.OrderCore)**



### <a name="method-setMedia"></a>setMedia

    mixed AdminOrdersController::setMedia()





* Visibility: **public**
* Source: [override/controllers/admin/AdminOrdersController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L333)




### <a name="method-setOrderCurrency"></a>setOrderCurrency

    mixed AdminOrdersController::setOrderCurrency($echo, $tr)





* Visibility: **public**
* This method is **static**.
* Source: [override/controllers/admin/AdminOrdersController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/admin/AdminOrdersController.php#L199)


#### Arguments
* $echo **mixed**
* $tr **mixed**


