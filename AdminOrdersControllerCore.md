AdminOrdersControllerCore
===============






* Class name: AdminOrdersControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $toolbar_title

    public mixed $toolbar_title





* Visibility: **public**


### $statuses_array

    protected mixed $statuses_array = array()





* Visibility: **protected**


### $object

    public \Order $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminOrdersControllerCore::__construct()





* Visibility: **public**




### setOrderCurrency

    mixed AdminOrdersControllerCore::setOrderCurrency($echo, $tr)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $echo **mixed**
* $tr **mixed**



### initPageHeaderToolbar

    mixed AdminOrdersControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderForm

    mixed AdminOrdersControllerCore::renderForm()





* Visibility: **public**




### initToolbar

    mixed AdminOrdersControllerCore::initToolbar()





* Visibility: **public**




### setMedia

    mixed AdminOrdersControllerCore::setMedia()





* Visibility: **public**




### printPDFIcons

    mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)





* Visibility: **public**


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### printNewCustomer

    mixed AdminOrdersControllerCore::printNewCustomer($id_order, $tr)





* Visibility: **public**


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### processBulkUpdateOrderStatus

    mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()





* Visibility: **public**




### renderList

    mixed AdminOrdersControllerCore::renderList()





* Visibility: **public**




### postProcess

    mixed AdminOrdersControllerCore::postProcess()





* Visibility: **public**




### renderKpis

    mixed AdminOrdersControllerCore::renderKpis()





* Visibility: **public**




### renderView

    mixed AdminOrdersControllerCore::renderView()





* Visibility: **public**




### ajaxProcessSearchProducts

    mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**




### ajaxProcessSendMailValidateOrder

    mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()





* Visibility: **public**




### ajaxProcessAddProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()





* Visibility: **public**




### sendChangedNotification

    mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)





* Visibility: **public**


#### Arguments
* $order **Order**



### ajaxProcessLoadProductInformation

    mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()





* Visibility: **public**




### ajaxProcessEditProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()





* Visibility: **public**




### ajaxProcessDeleteProductLine

    mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()





* Visibility: **public**




### doEditProductValidation

    mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)





* Visibility: **protected**


#### Arguments
* $order_detail **OrderDetail**
* $order **Order**
* $order_invoice **OrderInvoice**



### doDeleteProductLineValidation

    mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)





* Visibility: **protected**


#### Arguments
* $order_detail **OrderDetail**
* $order **Order**



### getProducts

    array AdminOrdersControllerCore::getProducts(\Order $order)





* Visibility: **protected**


#### Arguments
* $order **Order**



### reinjectQuantity

    mixed AdminOrdersControllerCore::reinjectQuantity(\OrderDetail $order_detail, integer $qty_cancel_product, boolean $delete)





* Visibility: **protected**


#### Arguments
* $order_detail **OrderDetail**
* $qty_cancel_product **integer**
* $delete **boolean**



### applyDiscountOnInvoice

    mixed AdminOrdersControllerCore::applyDiscountOnInvoice(\OrderInvoice $order_invoice, float $value_tax_incl, float $value_tax_excl)





* Visibility: **protected**


#### Arguments
* $order_invoice **OrderInvoice**
* $value_tax_incl **float**
* $value_tax_excl **float**



### ajaxProcessChangePaymentMethod

    mixed AdminOrdersControllerCore::ajaxProcessChangePaymentMethod()





* Visibility: **public**



