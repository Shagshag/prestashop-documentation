ParentOrderControllerCore
===============






* Class name: ParentOrderControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $ssl

    public mixed $ssl = true





* Visibility: **public**


### $php_self

    public mixed $php_self = 'order'





* Visibility: **public**


### $nbProducts

    public mixed $nbProducts





* Visibility: **public**


Methods
-------


### init

    mixed ParentOrderControllerCore::init()

Initialize parent order controller



* Visibility: **public**




### setMedia

    mixed ParentOrderControllerCore::setMedia()





* Visibility: **public**




### _checkFreeOrder

    boolean ParentOrderControllerCore::_checkFreeOrder()

Check if order is free



* Visibility: **protected**




### _updateMessage

    mixed ParentOrderControllerCore::_updateMessage($messageContent)





* Visibility: **protected**


#### Arguments
* $messageContent **mixed**



### _processCarrier

    mixed ParentOrderControllerCore::_processCarrier()





* Visibility: **protected**




### validateDeliveryOption

    boolean ParentOrderControllerCore::validateDeliveryOption(array $delivery_option)

Validate get/post param delivery option



* Visibility: **protected**


#### Arguments
* $delivery_option **array**



### _assignSummaryInformations

    mixed ParentOrderControllerCore::_assignSummaryInformations()





* Visibility: **protected**




### _assignAddress

    mixed ParentOrderControllerCore::_assignAddress()





* Visibility: **protected**




### _assignCarrier

    mixed ParentOrderControllerCore::_assignCarrier()





* Visibility: **protected**




### _assignWrappingAndTOS

    mixed ParentOrderControllerCore::_assignWrappingAndTOS()





* Visibility: **protected**




### _assignPayment

    mixed ParentOrderControllerCore::_assignPayment()





* Visibility: **protected**




### setNoCarrier

    mixed ParentOrderControllerCore::setNoCarrier()

Set id_carrier to 0 (no shipping price)



* Visibility: **protected**




### setDefaultCarrierSelection

    \number ParentOrderControllerCore::setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**


#### Arguments
* $carriers **array**



### _setDefaultCarrierSelection

    \number ParentOrderControllerCore::_setDefaultCarrierSelection(array $carriers)

Decides what the default carrier is and update the cart with it



* Visibility: **protected**


#### Arguments
* $carriers **array**


