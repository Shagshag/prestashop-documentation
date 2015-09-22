ParentOrderControllerCore
===============






* Class name: ParentOrderControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/ParentOrderController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L37)





Properties
----------

* [$ssl](#property-$ssl)
* [$php_self](#property-$php_self)
* [$nbProducts](#property-$nbProducts)

Methods
-------
* [init](#method-init)
* [setMedia](#method-setMedia)
* [_checkFreeOrder](#method-_checkFreeOrder)
* [_updateMessage](#method-_updateMessage)
* [_processCarrier](#method-_processCarrier)
* [validateDeliveryOption](#method-validateDeliveryOption)
* [_assignSummaryInformations](#method-_assignSummaryInformations)
* [_assignAddress](#method-_assignAddress)
* [_assignCarrier](#method-_assignCarrier)
* [_assignWrappingAndTOS](#method-_assignWrappingAndTOS)
* [_assignPayment](#method-_assignPayment)
* [setNoCarrier](#method-setNoCarrier)
* [setDefaultCarrierSelection](#method-setDefaultCarrierSelection)
* [_setDefaultCarrierSelection](#method-_setDefaultCarrierSelection)




Properties
----------


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in [controllers/front/ParentOrderController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L39)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'order'





* Visibility: **public**
* This property is defined in [controllers/front/ParentOrderController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L40)


### <a name="property-$nbProducts"></a>$nbProducts

    public mixed $nbProducts





* Visibility: **public**
* This property is defined in [controllers/front/ParentOrderController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L42)


Methods
-------


### <a name="method-init"></a>init

    mixed ParentOrderControllerCore::init()

Initialize parent order controller



* Visibility: **public**
* This method is defined in [controllers/front/ParentOrderController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L48)




### <a name="method-setMedia"></a>setMedia

    mixed ParentOrderControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/front/ParentOrderController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L141)




### <a name="method-_checkFreeOrder"></a>_checkFreeOrder

    boolean ParentOrderControllerCore::_checkFreeOrder()

Check if order is free



* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L167)




### <a name="method-_updateMessage"></a>_updateMessage

    mixed ParentOrderControllerCore::_updateMessage($messageContent)





* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L178)


#### Arguments
* $messageContent **mixed**



### <a name="method-_processCarrier"></a>_processCarrier

    mixed ParentOrderControllerCore::_processCarrier()





* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L203)




### <a name="method-validateDeliveryOption"></a>validateDeliveryOption

    boolean ParentOrderControllerCore::validateDeliveryOption(array $delivery_option)

Validate get/post param delivery option



* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L269)


#### Arguments
* $delivery_option **array**



### <a name="method-_assignSummaryInformations"></a>_assignSummaryInformations

    mixed ParentOrderControllerCore::_assignSummaryInformations()





* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L284)




### <a name="method-_assignAddress"></a>_assignAddress

    mixed ParentOrderControllerCore::_assignAddress()





* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L376)




### <a name="method-_assignCarrier"></a>_assignCarrier

    mixed ParentOrderControllerCore::_assignCarrier()





* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L479)




### <a name="method-_assignWrappingAndTOS"></a>_assignWrappingAndTOS

    mixed ParentOrderControllerCore::_assignWrappingAndTOS()





* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L514)




### <a name="method-_assignPayment"></a>_assignPayment

    mixed ParentOrderControllerCore::_assignPayment()





* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 556](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L556)




### <a name="method-setNoCarrier"></a>setNoCarrier

    mixed ParentOrderControllerCore::setNoCarrier()

Set id_carrier to 0 (no shipping price)



* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L586)




### <a name="method-setDefaultCarrierSelection"></a>setDefaultCarrierSelection

    \number ParentOrderControllerCore::setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L603)


#### Arguments
* $carriers **array**



### <a name="method-_setDefaultCarrierSelection"></a>_setDefaultCarrierSelection

    \number ParentOrderControllerCore::_setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined in [controllers/front/ParentOrderController.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L619)


#### Arguments
* $carriers **array**


