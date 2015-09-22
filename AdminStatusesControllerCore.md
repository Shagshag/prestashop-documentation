AdminStatusesControllerCore
===============






* Class name: AdminStatusesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminStatusesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L30)





Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [init](#method-init)
* [initOrderStatutsList](#method-initOrderStatutsList)
* [initOrdersReturnsList](#method-initOrdersReturnsList)
* [initOrderReturnsForm](#method-initOrderReturnsForm)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [renderList](#method-renderList)
* [checkFilterForOrdersReturnsList](#method-checkFilterForOrdersReturnsList)
* [renderForm](#method-renderForm)
* [renderOrderStatusForm](#method-renderOrderStatusForm)
* [renderOrderReturnsForm](#method-renderOrderReturnsForm)
* [getTemplates](#method-getTemplates)
* [postProcess](#method-postProcess)
* [filterToField](#method-filterToField)
* [afterImageUpload](#method-afterImageUpload)
* [ajaxProcessSendEmailOrderState](#method-ajaxProcessSendEmailOrderState)
* [ajaxProcessDeliveryOrderState](#method-ajaxProcessDeliveryOrderState)
* [ajaxProcessInvoiceOrderState](#method-ajaxProcessInvoiceOrderState)




Properties
----------


### <a name="property-$object"></a>$object

    public \OrderState $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminStatusesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminStatusesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L32)




### <a name="method-init"></a>init

    mixed AdminStatusesControllerCore::init()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L51)




### <a name="method-initOrderStatutsList"></a>initOrderStatutsList

    mixed AdminStatusesControllerCore::initOrderStatutsList()

init all variables to render the order status list



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L66)




### <a name="method-initOrdersReturnsList"></a>initOrdersReturnsList

    mixed AdminStatusesControllerCore::initOrdersReturnsList()

init all variables to render the order return list



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L124)




### <a name="method-initOrderReturnsForm"></a>initOrderReturnsForm

    mixed AdminStatusesControllerCore::initOrderReturnsForm()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L148)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminStatusesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L188)




### <a name="method-renderList"></a>renderList

    mixed AdminStatusesControllerCore::renderList()

Function used to render the list to display for this controller



* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L209)




### <a name="method-checkFilterForOrdersReturnsList"></a>checkFilterForOrdersReturnsList

    mixed AdminStatusesControllerCore::checkFilterForOrdersReturnsList()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L242)




### <a name="method-renderForm"></a>renderForm

    mixed AdminStatusesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L257)




### <a name="method-renderOrderStatusForm"></a>renderOrderStatusForm

    mixed AdminStatusesControllerCore::renderOrderStatusForm()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L419)




### <a name="method-renderOrderReturnsForm"></a>renderOrderReturnsForm

    mixed AdminStatusesControllerCore::renderOrderReturnsForm()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L446)




### <a name="method-getTemplates"></a>getTemplates

    mixed AdminStatusesControllerCore::getTemplates()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L493)




### <a name="method-postProcess"></a>postProcess

    mixed AdminStatusesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L527)




### <a name="method-filterToField"></a>filterToField

    mixed AdminStatusesControllerCore::filterToField($key, $filter)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L615)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-afterImageUpload"></a>afterImageUpload

    mixed AdminStatusesControllerCore::afterImageUpload()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatusesController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L626)




### <a name="method-ajaxProcessSendEmailOrderState"></a>ajaxProcessSendEmailOrderState

    mixed AdminStatusesControllerCore::ajaxProcessSendEmailOrderState()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L642)




### <a name="method-ajaxProcessDeliveryOrderState"></a>ajaxProcessDeliveryOrderState

    mixed AdminStatusesControllerCore::ajaxProcessDeliveryOrderState()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L656)




### <a name="method-ajaxProcessInvoiceOrderState"></a>ajaxProcessInvoiceOrderState

    mixed AdminStatusesControllerCore::ajaxProcessInvoiceOrderState()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatusesController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatusesController.php#L670)



