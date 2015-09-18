OrderControllerCore
===============






* Class name: OrderControllerCore
* Namespace: 
* Parent class: ParentOrderController



Constants
----------


### STEP_SUMMARY_EMPTY_CART

    const STEP_SUMMARY_EMPTY_CART = -1





### STEP_ADDRESSES

    const STEP_ADDRESSES = 1





### STEP_DELIVERY

    const STEP_DELIVERY = 2





### STEP_PAYMENT

    const STEP_PAYMENT = 3





Properties
----------


### $step

    public mixed $step





* Visibility: **public**


Methods
-------


### init

    mixed OrderControllerCore::init()

Initialize order controller



* Visibility: **public**




### postProcess

    mixed OrderControllerCore::postProcess()





* Visibility: **public**




### initContent

    mixed OrderControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**




### processAddressFormat

    mixed OrderControllerCore::processAddressFormat()





* Visibility: **protected**




### autoStep

    mixed OrderControllerCore::autoStep()

Order process controller



* Visibility: **public**




### processAddress

    mixed OrderControllerCore::processAddress()

Manage address



* Visibility: **public**




### processCarrier

    mixed OrderControllerCore::processCarrier()

Carrier step



* Visibility: **protected**




### _assignAddress

    mixed OrderControllerCore::_assignAddress()

Address step



* Visibility: **protected**




### _assignCarrier

    mixed OrderControllerCore::_assignCarrier()

Carrier step



* Visibility: **protected**




### _assignPayment

    mixed OrderControllerCore::_assignPayment()

Payment step



* Visibility: **protected**




### setMedia

    mixed OrderControllerCore::setMedia()





* Visibility: **public**



