AdminOrdersController
===============

DISCLAIMER

Do not edit or add to this file if you wish to upgrade this module to newer
versions in the future. If you wish to customize this module for your
needs please refer to http://doc.prestashop.com/display/PS15/Overriding+default+behaviors
#Overridingdefaultbehaviors-Overridingamodule%27sbehavior for more information.


* Class name: AdminOrdersController
* Namespace: 
* Parent class: [AdminOrdersControllerCore](AdminOrdersControllerCore.md)





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
* This property is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


Methods
-------


### __construct

    mixed AdminOrdersControllerCore::__construct()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### setOrderCurrency

    mixed AdminOrdersControllerCore::setOrderCurrency($echo, $tr)





* Visibility: **public**
* This method is **static**.
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### initPageHeaderToolbar

    mixed AdminOrdersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### renderForm

    mixed AdminOrdersControllerCore::renderForm()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### initToolbar

    mixed AdminOrdersControllerCore::initToolbar()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### setMedia

    mixed AdminOrdersControllerCore::setMedia()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### printPDFIcons

    mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### printNewCustomer

    mixed AdminOrdersControllerCore::printNewCustomer($id_order, $tr)





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### processBulkUpdateOrderStatus

    mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### renderList

    mixed AdminOrdersControllerCore::renderList()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### postProcess

    mixed AdminOrdersControllerCore::postProcess()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### renderKpis

    mixed AdminOrdersControllerCore::renderKpis()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### renderView

    mixed AdminOrdersControllerCore::renderView()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### ajaxProcessSearchProducts

    mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### ajaxProcessSendMailValidateOrder

    mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### ajaxProcessAddProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### sendChangedNotification

    mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $order **Order**



### ajaxProcessLoadProductInformation

    mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### ajaxProcessEditProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### ajaxProcessDeleteProductLine

    mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)




### doEditProductValidation

    mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $order_detail **OrderDetail**
* $order **Order**
* $order_invoice **OrderInvoice**



### doDeleteProductLineValidation

    mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $order_detail **OrderDetail**
* $order **Order**



### getProducts

    array AdminOrdersControllerCore::getProducts(\Order $order)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $order **Order**



### reinjectQuantity

    mixed AdminOrdersControllerCore::reinjectQuantity(\OrderDetail $order_detail, integer $qty_cancel_product, boolean $delete)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $order_detail **OrderDetail**
* $qty_cancel_product **integer**
* $delete **boolean**



### applyDiscountOnInvoice

    mixed AdminOrdersControllerCore::applyDiscountOnInvoice(\OrderInvoice $order_invoice, float $value_tax_incl, float $value_tax_excl)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)


#### Arguments
* $order_invoice **OrderInvoice**
* $value_tax_incl **float**
* $value_tax_excl **float**



### ajaxProcessChangePaymentMethod

    mixed AdminOrdersControllerCore::ajaxProcessChangePaymentMethod()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore.md)



