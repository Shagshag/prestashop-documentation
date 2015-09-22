AdminOrdersControllerCore
===============






* Class name: AdminOrdersControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminOrdersController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L41)





Properties
----------

* [$toolbar_title](#property-$toolbar_title)
* [$statuses_array](#property-$statuses_array)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [setOrderCurrency](#method-setOrderCurrency)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [renderForm](#method-renderForm)
* [initToolbar](#method-initToolbar)
* [setMedia](#method-setMedia)
* [printPDFIcons](#method-printPDFIcons)
* [printNewCustomer](#method-printNewCustomer)
* [processBulkUpdateOrderStatus](#method-processBulkUpdateOrderStatus)
* [renderList](#method-renderList)
* [postProcess](#method-postProcess)
* [renderKpis](#method-renderKpis)
* [renderView](#method-renderView)
* [ajaxProcessSearchProducts](#method-ajaxProcessSearchProducts)
* [ajaxProcessSendMailValidateOrder](#method-ajaxProcessSendMailValidateOrder)
* [ajaxProcessAddProductOnOrder](#method-ajaxProcessAddProductOnOrder)
* [sendChangedNotification](#method-sendChangedNotification)
* [ajaxProcessLoadProductInformation](#method-ajaxProcessLoadProductInformation)
* [ajaxProcessEditProductOnOrder](#method-ajaxProcessEditProductOnOrder)
* [ajaxProcessDeleteProductLine](#method-ajaxProcessDeleteProductLine)
* [doEditProductValidation](#method-doEditProductValidation)
* [doDeleteProductLineValidation](#method-doDeleteProductLineValidation)
* [getProducts](#method-getProducts)
* [reinjectQuantity](#method-reinjectQuantity)
* [applyDiscountOnInvoice](#method-applyDiscountOnInvoice)
* [ajaxProcessChangePaymentMethod](#method-ajaxProcessChangePaymentMethod)




Properties
----------


### <a name="property-$toolbar_title"></a>$toolbar_title

    public mixed $toolbar_title





* Visibility: **public**
* This property is defined in [controllers/admin/AdminOrdersController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L43)


### <a name="property-$statuses_array"></a>$statuses_array

    protected mixed $statuses_array = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminOrdersController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L45)


### <a name="property-$object"></a>$object

    public \Order $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminOrdersController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L41)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminOrdersControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L47)




### <a name="method-setOrderCurrency"></a>setOrderCurrency

    mixed AdminOrdersControllerCore::setOrderCurrency($echo, $tr)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminOrdersController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L199)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminOrdersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L205)




### <a name="method-renderForm"></a>renderForm

    mixed AdminOrdersControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L227)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminOrdersControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L277)




### <a name="method-setMedia"></a>setMedia

    mixed AdminOrdersControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L333)




### <a name="method-printPDFIcons"></a>printPDFIcons

    mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L348)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-printNewCustomer"></a>printNewCustomer

    mixed AdminOrdersControllerCore::printNewCustomer($id_order, $tr)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L373)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### <a name="method-processBulkUpdateOrderStatus"></a>processBulkUpdateOrderStatus

    mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L378)




### <a name="method-renderList"></a>renderList

    mixed AdminOrdersControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L434)




### <a name="method-postProcess"></a>postProcess

    mixed AdminOrdersControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L450)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminOrdersControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 1528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1528)




### <a name="method-renderView"></a>renderView

    mixed AdminOrdersControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 1597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1597)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

    mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 1792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1792)




### <a name="method-ajaxProcessSendMailValidateOrder"></a>ajaxProcessSendMailValidateOrder

    mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 1871](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1871)




### <a name="method-ajaxProcessAddProductOnOrder"></a>ajaxProcessAddProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 1893](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L1893)




### <a name="method-sendChangedNotification"></a>sendChangedNotification

    mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2227)


#### Arguments
* $order **[Order](OrderCore)**



### <a name="method-ajaxProcessLoadProductInformation"></a>ajaxProcessLoadProductInformation

    mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2236)




### <a name="method-ajaxProcessEditProductOnOrder"></a>ajaxProcessEditProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2272)




### <a name="method-ajaxProcessDeleteProductLine"></a>ajaxProcessDeleteProductLine

    mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2463)




### <a name="method-doEditProductValidation"></a>doEditProductValidation

    mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2542](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2542)


#### Arguments
* $order_detail **[OrderDetail](OrderDetailCore)**
* $order **[Order](OrderCore)**
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**



### <a name="method-doDeleteProductLineValidation"></a>doDeleteProductLineValidation

    mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2615)


#### Arguments
* $order_detail **[OrderDetail](OrderDetailCore)**
* $order **[Order](OrderCore)**



### <a name="method-getProducts"></a>getProducts

    array AdminOrdersControllerCore::getProducts(\Order $order)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2651)


#### Arguments
* $order **[Order](OrderCore)**



### <a name="method-reinjectQuantity"></a>reinjectQuantity

    mixed AdminOrdersControllerCore::reinjectQuantity(\OrderDetail $order_detail, integer $qty_cancel_product, boolean $delete)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2678](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2678)


#### Arguments
* $order_detail **[OrderDetail](OrderDetailCore)**
* $qty_cancel_product **integer**
* $delete **boolean**



### <a name="method-applyDiscountOnInvoice"></a>applyDiscountOnInvoice

    mixed AdminOrdersControllerCore::applyDiscountOnInvoice(\OrderInvoice $order_invoice, float $value_tax_incl, float $value_tax_excl)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2773)


#### Arguments
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**
* $value_tax_incl **float**
* $value_tax_excl **float**



### <a name="method-ajaxProcessChangePaymentMethod"></a>ajaxProcessChangePaymentMethod

    mixed AdminOrdersControllerCore::ajaxProcessChangePaymentMethod()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOrdersController.php line 2783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOrdersController.php#L2783)



