Class OrderControllerCore
=====================





* Class name: OrderControllerCore
* Parent class: [ParentOrderController](class.ParentOrderControllerCore.md)
* Source: [controllers/front/OrderController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L27)

Constants
----------

* [STEP_ADDRESSES](#constant-STEP_ADDRESSES)
* [STEP_DELIVERY](#constant-STEP_DELIVERY)
* [STEP_PAYMENT](#constant-STEP_PAYMENT)
* [STEP_SUMMARY_EMPTY_CART](#constant-STEP_SUMMARY_EMPTY_CART)

Properties
----------

* [$step](#property-$step)

Methods
-------
* [_assignAddress](#method-_assignAddress)
* [_assignCarrier](#method-_assignCarrier)
* [_assignPayment](#method-_assignPayment)
* [autoStep](#method-autoStep)
* [init](#method-init)
* [initContent](#method-initContent)
* [postProcess](#method-postProcess)
* [processAddress](#method-processAddress)
* [processAddressFormat](#method-processAddressFormat)
* [processCarrier](#method-processCarrier)
* [setMedia](#method-setMedia)


Constants
----------


### <a name="constant-STEP_ADDRESSES"></a>STEP_ADDRESSES

    const STEP_ADDRESSES = 1





* Source: [controllers/front/OrderController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L31).


### <a name="constant-STEP_DELIVERY"></a>STEP_DELIVERY

    const STEP_DELIVERY = 2





* Source: [controllers/front/OrderController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L32).


### <a name="constant-STEP_PAYMENT"></a>STEP_PAYMENT

    const STEP_PAYMENT = 3





* Source: [controllers/front/OrderController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L33).


### <a name="constant-STEP_SUMMARY_EMPTY_CART"></a>STEP_SUMMARY_EMPTY_CART

    const STEP_SUMMARY_EMPTY_CART = -1





* Source: [controllers/front/OrderController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L30).


Properties
----------


### <a name="property-$step"></a>$step

    public mixed $step





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L29).


Methods
-------


### <a name="method-_assignAddress"></a>_assignAddress

    mixed OrderControllerCore::_assignAddress()

Address step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L407)




### <a name="method-_assignCarrier"></a>_assignCarrier

    mixed OrderControllerCore::_assignCarrier()

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L421)




### <a name="method-_assignPayment"></a>_assignPayment

    mixed OrderControllerCore::_assignPayment()

Payment step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L440)




### <a name="method-autoStep"></a>autoStep

    mixed OrderControllerCore::autoStep()

Order process controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L262)




### <a name="method-init"></a>init

    mixed OrderControllerCore::init()

Initialize order controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L39)




### <a name="method-initContent"></a>initContent

    mixed OrderControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L123)




### <a name="method-postProcess"></a>postProcess

    mixed OrderControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L110)




### <a name="method-processAddress"></a>processAddress

    mixed OrderControllerCore::processAddress()

Manage address



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L318)




### <a name="method-processAddressFormat"></a>processAddressFormat

    mixed OrderControllerCore::processAddressFormat()





* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L246)




### <a name="method-processCarrier"></a>processCarrier

    mixed OrderControllerCore::processCarrier()

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L390)




### <a name="method-setMedia"></a>setMedia

    mixed OrderControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderController.php#L472)



