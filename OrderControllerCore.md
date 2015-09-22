OrderControllerCore
===============






* Class name: OrderControllerCore
* Namespace: 
* Parent class: [ParentOrderController](ParentOrderControllerCore)

* This class is defined in [controllers/front/OrderController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#27)



Constants
----------


### STEP_SUMMARY_EMPTY_CART

    const STEP_SUMMARY_EMPTY_CART = -1



* This constant is defined in [controllers/front/OrderController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#30)


### STEP_ADDRESSES

    const STEP_ADDRESSES = 1



* This constant is defined in [controllers/front/OrderController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#31)


### STEP_DELIVERY

    const STEP_DELIVERY = 2



* This constant is defined in [controllers/front/OrderController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#32)


### STEP_PAYMENT

    const STEP_PAYMENT = 3



* This constant is defined in [controllers/front/OrderController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#33)


Properties
----------


### $step

    public mixed $step





* Visibility: **public**
* This property is defined in [controllers/front/OrderController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#29)


Methods
-------


### init

    mixed OrderControllerCore::init()

Initialize order controller



* Visibility: **public**
* This method is defined in [controllers/front/OrderController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#39)




### postProcess

    mixed OrderControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/front/OrderController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#110)




### initContent

    mixed OrderControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/OrderController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#123)




### processAddressFormat

    mixed OrderControllerCore::processAddressFormat()





* Visibility: **protected**
* This method is defined in [controllers/front/OrderController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#246)




### autoStep

    mixed OrderControllerCore::autoStep()

Order process controller



* Visibility: **public**
* This method is defined in [controllers/front/OrderController.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#262)




### processAddress

    mixed OrderControllerCore::processAddress()

Manage address



* Visibility: **public**
* This method is defined in [controllers/front/OrderController.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#318)




### processCarrier

    mixed OrderControllerCore::processCarrier()

Carrier step



* Visibility: **protected**
* This method is defined in [controllers/front/OrderController.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#390)




### _assignAddress

    mixed OrderControllerCore::_assignAddress()

Address step



* Visibility: **protected**
* This method is defined in [controllers/front/OrderController.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#407)




### _assignCarrier

    mixed OrderControllerCore::_assignCarrier()

Carrier step



* Visibility: **protected**
* This method is defined in [controllers/front/OrderController.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#421)




### _assignPayment

    mixed OrderControllerCore::_assignPayment()

Payment step



* Visibility: **protected**
* This method is defined in [controllers/front/OrderController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#440)




### setMedia

    mixed OrderControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/front/OrderController.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#472)



