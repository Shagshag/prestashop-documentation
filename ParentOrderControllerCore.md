ParentOrderControllerCore
===============






* Class name: ParentOrderControllerCore
* Namespace: 
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in controllers\front\ParentOrderController.php line 37





Properties
----------


### $ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in controllers\front\ParentOrderController.php line 39


### $php_self

    public mixed $php_self = 'order'





* Visibility: **public**
* This property is defined in controllers\front\ParentOrderController.php line 40


### $nbProducts

    public mixed $nbProducts





* Visibility: **public**
* This property is defined in controllers\front\ParentOrderController.php line 42


Methods
-------


### init

    mixed ParentOrderControllerCore::init()

Initialize parent order controller



* Visibility: **public**
* This method is defined in controllers\front\ParentOrderController.php line 48




### setMedia

    mixed ParentOrderControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\front\ParentOrderController.php line 141




### _checkFreeOrder

    boolean ParentOrderControllerCore::_checkFreeOrder()

Check if order is free



* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 167




### _updateMessage

    mixed ParentOrderControllerCore::_updateMessage($messageContent)





* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 178


#### Arguments
* $messageContent **mixed**



### _processCarrier

    mixed ParentOrderControllerCore::_processCarrier()





* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 203




### validateDeliveryOption

    boolean ParentOrderControllerCore::validateDeliveryOption(array $delivery_option)

Validate get/post param delivery option



* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 269


#### Arguments
* $delivery_option **array**



### _assignSummaryInformations

    mixed ParentOrderControllerCore::_assignSummaryInformations()





* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 284




### _assignAddress

    mixed ParentOrderControllerCore::_assignAddress()





* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 376




### _assignCarrier

    mixed ParentOrderControllerCore::_assignCarrier()





* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 479




### _assignWrappingAndTOS

    mixed ParentOrderControllerCore::_assignWrappingAndTOS()





* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 514




### _assignPayment

    mixed ParentOrderControllerCore::_assignPayment()





* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 556




### setNoCarrier

    mixed ParentOrderControllerCore::setNoCarrier()

Set id_carrier to 0 (no shipping price)



* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 586




### setDefaultCarrierSelection

    \number ParentOrderControllerCore::setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 603


#### Arguments
* $carriers **array**



### _setDefaultCarrierSelection

    \number ParentOrderControllerCore::_setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined in controllers\front\ParentOrderController.php line 619


#### Arguments
* $carriers **array**


