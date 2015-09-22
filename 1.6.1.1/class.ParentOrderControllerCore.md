Class ParentOrderControllerCore
=====================





* Class name: ParentOrderControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/ParentOrderController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L37)



Properties
----------

* [$nbProducts](#property-$nbProducts)
* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)

Methods
-------
* [_assignAddress](#method-_assignAddress)
* [_assignCarrier](#method-_assignCarrier)
* [_assignPayment](#method-_assignPayment)
* [_assignSummaryInformations](#method-_assignSummaryInformations)
* [_assignWrappingAndTOS](#method-_assignWrappingAndTOS)
* [_checkFreeOrder](#method-_checkFreeOrder)
* [_processCarrier](#method-_processCarrier)
* [_setDefaultCarrierSelection](#method-_setDefaultCarrierSelection)
* [_updateMessage](#method-_updateMessage)
* [init](#method-init)
* [setDefaultCarrierSelection](#method-setDefaultCarrierSelection)
* [setMedia](#method-setMedia)
* [setNoCarrier](#method-setNoCarrier)
* [validateDeliveryOption](#method-validateDeliveryOption)




Properties
----------


### <a name="property-$nbProducts"></a>$nbProducts

    public mixed $nbProducts





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L42)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'order'





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L40)


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L39)


Methods
-------


### <a name="method-_assignAddress"></a>_assignAddress

    mixed ParentOrderControllerCore::_assignAddress()





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L376)




### <a name="method-_assignCarrier"></a>_assignCarrier

    mixed ParentOrderControllerCore::_assignCarrier()





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L479)




### <a name="method-_assignPayment"></a>_assignPayment

    mixed ParentOrderControllerCore::_assignPayment()





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 556](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L556)




### <a name="method-_assignSummaryInformations"></a>_assignSummaryInformations

    mixed ParentOrderControllerCore::_assignSummaryInformations()





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L284)




### <a name="method-_assignWrappingAndTOS"></a>_assignWrappingAndTOS

    mixed ParentOrderControllerCore::_assignWrappingAndTOS()





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L514)




### <a name="method-_checkFreeOrder"></a>_checkFreeOrder

    boolean ParentOrderControllerCore::_checkFreeOrder()

Check if order is free



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L167)




### <a name="method-_processCarrier"></a>_processCarrier

    mixed ParentOrderControllerCore::_processCarrier()





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L203)




### <a name="method-_setDefaultCarrierSelection"></a>_setDefaultCarrierSelection

    \number ParentOrderControllerCore::_setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L619)


#### Arguments
* $carriers **array**



### <a name="method-_updateMessage"></a>_updateMessage

    mixed ParentOrderControllerCore::_updateMessage($messageContent)





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L178)


#### Arguments
* $messageContent **mixed**



### <a name="method-init"></a>init

    mixed ParentOrderControllerCore::init()

Initialize parent order controller



* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L48)




### <a name="method-setDefaultCarrierSelection"></a>setDefaultCarrierSelection

    \number ParentOrderControllerCore::setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L603)


#### Arguments
* $carriers **array**



### <a name="method-setMedia"></a>setMedia

    mixed ParentOrderControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L141)




### <a name="method-setNoCarrier"></a>setNoCarrier

    mixed ParentOrderControllerCore::setNoCarrier()

Set id_carrier to 0 (no shipping price)



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L586)




### <a name="method-validateDeliveryOption"></a>validateDeliveryOption

    boolean ParentOrderControllerCore::validateDeliveryOption(array $delivery_option)

Validate get/post param delivery option



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ParentOrderController.php#L269)


#### Arguments
* $delivery_option **array**


