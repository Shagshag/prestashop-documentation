AdminOrdersController
===============

DISCLAIMER

Do not edit or add to this file if you wish to upgrade this module to newer
versions in the future. If you wish to customize this module for your
needs please refer to http://doc.prestashop.com/display/PS15/Overriding+default+behaviors
#Overridingdefaultbehaviors-Overridingamodule%27sbehavior for more information.


* Class name: AdminOrdersController
* Namespace: 
* Parent class: [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This class is defined in override\controllers\admin\AdminOrdersController.php line 16





Properties
----------


### $toolbar_title

    public mixed $toolbar_title





* Visibility: **public**
* This property is defined in override\controllers\admin\AdminOrdersController.php line 43


### $statuses_array

    protected mixed $statuses_array = array()





* Visibility: **protected**
* This property is defined in override\controllers\admin\AdminOrdersController.php line 45


### $object

    public \Order $object





* Visibility: **public**
* This property is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This property is defined in override\controllers\admin\AdminOrdersController.php line 41


Methods
-------


### __construct

    mixed AdminOrdersControllerCore::__construct()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 47




### setOrderCurrency

    mixed AdminOrdersControllerCore::setOrderCurrency($echo, $tr)





* Visibility: **public**
* This method is **static**.
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 199


#### Arguments
* $echo **mixed**
* $tr **mixed**



### initPageHeaderToolbar

    mixed AdminOrdersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 205




### renderForm

    mixed AdminOrdersControllerCore::renderForm()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 227




### initToolbar

    mixed AdminOrdersControllerCore::initToolbar()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 277




### setMedia

    mixed AdminOrdersControllerCore::setMedia()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 333




### printPDFIcons

    mixed AdminOrdersControllerCore::printPDFIcons($id_order, $tr)





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 348


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### printNewCustomer

    mixed AdminOrdersControllerCore::printNewCustomer($id_order, $tr)





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 373


#### Arguments
* $id_order **mixed**
* $tr **mixed**



### processBulkUpdateOrderStatus

    mixed AdminOrdersControllerCore::processBulkUpdateOrderStatus()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 378




### renderList

    mixed AdminOrdersControllerCore::renderList()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 434




### postProcess

    mixed AdminOrdersControllerCore::postProcess()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 450




### renderKpis

    mixed AdminOrdersControllerCore::renderKpis()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 1528




### renderView

    mixed AdminOrdersControllerCore::renderView()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 1597




### ajaxProcessSearchProducts

    mixed AdminOrdersControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 1792




### ajaxProcessSendMailValidateOrder

    mixed AdminOrdersControllerCore::ajaxProcessSendMailValidateOrder()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 1871




### ajaxProcessAddProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessAddProductOnOrder()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 1893




### sendChangedNotification

    mixed AdminOrdersControllerCore::sendChangedNotification(\Order $order)





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2227


#### Arguments
* $order **[Order](OrderCore)**



### ajaxProcessLoadProductInformation

    mixed AdminOrdersControllerCore::ajaxProcessLoadProductInformation()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2236




### ajaxProcessEditProductOnOrder

    mixed AdminOrdersControllerCore::ajaxProcessEditProductOnOrder()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2272




### ajaxProcessDeleteProductLine

    mixed AdminOrdersControllerCore::ajaxProcessDeleteProductLine()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2463




### doEditProductValidation

    mixed AdminOrdersControllerCore::doEditProductValidation(\OrderDetail $order_detail, \Order $order, \OrderInvoice $order_invoice)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2542


#### Arguments
* $order_detail **[OrderDetail](OrderDetailCore)**
* $order **[Order](OrderCore)**
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**



### doDeleteProductLineValidation

    mixed AdminOrdersControllerCore::doDeleteProductLineValidation(\OrderDetail $order_detail, \Order $order)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2615


#### Arguments
* $order_detail **[OrderDetail](OrderDetailCore)**
* $order **[Order](OrderCore)**



### getProducts

    array AdminOrdersControllerCore::getProducts(\Order $order)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2651


#### Arguments
* $order **[Order](OrderCore)**



### reinjectQuantity

    mixed AdminOrdersControllerCore::reinjectQuantity(\OrderDetail $order_detail, integer $qty_cancel_product, boolean $delete)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2678


#### Arguments
* $order_detail **[OrderDetail](OrderDetailCore)**
* $qty_cancel_product **integer**
* $delete **boolean**



### applyDiscountOnInvoice

    mixed AdminOrdersControllerCore::applyDiscountOnInvoice(\OrderInvoice $order_invoice, float $value_tax_incl, float $value_tax_excl)





* Visibility: **protected**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2773


#### Arguments
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**
* $value_tax_incl **float**
* $value_tax_excl **float**



### ajaxProcessChangePaymentMethod

    mixed AdminOrdersControllerCore::ajaxProcessChangePaymentMethod()





* Visibility: **public**
* This method is defined by [AdminOrdersControllerCore](AdminOrdersControllerCore)
* This method is defined in override\controllers\admin\AdminOrdersController.php line 2783



