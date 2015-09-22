OrderOpcController
===============

DISCLAIMER

Do not edit or add to this file if you wish to upgrade this module to newer
versions in the future. If you wish to customize this module for your
needs please refer to http://doc.prestashop.com/display/PS15/Overriding+default+behaviors
#Overridingdefaultbehaviors-Overridingamodule%27sbehavior for more information.


* Class name: OrderOpcController
* Parent class: [OrderOpcControllerCore](OrderOpcControllerCore)
* This class is defined in [override/controllers/front/OrderOpcController.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L16)





Properties
----------

* [$php_self](#property-$php_self)
* [$isLogged](#property-$isLogged)
* [$ajax_refresh](#property-$ajax_refresh)

Methods
-------
* [_getPaymentMethods](#method-_getPaymentMethods)
* [init](#method-init)
* [setMedia](#method-setMedia)
* [initContent](#method-initContent)
* [_getGuestInformations](#method-_getGuestInformations)
* [_assignCarrier](#method-_assignCarrier)
* [_assignPayment](#method-_assignPayment)
* [_getCarrierList](#method-_getCarrierList)
* [_processAddressFormat](#method-_processAddressFormat)
* [getFormatedSummaryDetail](#method-getFormatedSummaryDetail)




Properties
----------


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'order-opc'





* Visibility: **public**
* This property is defined in [override/controllers/front/OrderOpcController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L29)


### <a name="property-$isLogged"></a>$isLogged

    public mixed $isLogged





* Visibility: **public**
* This property is defined in [override/controllers/front/OrderOpcController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L30)


### <a name="property-$ajax_refresh"></a>$ajax_refresh

    protected mixed $ajax_refresh = false





* Visibility: **protected**
* This property is defined in [override/controllers/front/OrderOpcController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L32)


Methods
-------


### <a name="method-_getPaymentMethods"></a>_getPaymentMethods

    mixed OrderOpcControllerCore::_getPaymentMethods()





* Visibility: **protected**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L544)




### <a name="method-init"></a>init

    mixed OrderOpcControllerCore::init()

Initialize order opc controller



* Visibility: **public**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L38)




### <a name="method-setMedia"></a>setMedia

    mixed OrderOpcControllerCore::setMedia()





* Visibility: **public**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L325)




### <a name="method-initContent"></a>initContent

    mixed OrderOpcControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L351)




### <a name="method-_getGuestInformations"></a>_getGuestInformations

    mixed OrderOpcControllerCore::_getGuestInformations()





* Visibility: **protected**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L437)




### <a name="method-_assignCarrier"></a>_assignCarrier

    mixed OrderOpcControllerCore::_assignCarrier()





* Visibility: **protected**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L506)




### <a name="method-_assignPayment"></a>_assignPayment

    mixed OrderOpcControllerCore::_assignPayment()





* Visibility: **protected**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L527)




### <a name="method-_getCarrierList"></a>_getCarrierList

    mixed OrderOpcControllerCore::_getCarrierList()





* Visibility: **protected**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L609)




### <a name="method-_processAddressFormat"></a>_processAddressFormat

    mixed OrderOpcControllerCore::_processAddressFormat()





* Visibility: **protected**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L695)




### <a name="method-getFormatedSummaryDetail"></a>getFormatedSummaryDetail

    mixed OrderOpcControllerCore::getFormatedSummaryDetail()





* Visibility: **protected**
* This method is defined by [OrderOpcControllerCore](OrderOpcControllerCore)
* This method is defined in [override/controllers/front/OrderOpcController.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L738)



