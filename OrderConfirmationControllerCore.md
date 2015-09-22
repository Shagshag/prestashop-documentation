OrderConfirmationControllerCore
===============






* Class name: OrderConfirmationControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/OrderConfirmationController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L27)





Properties
----------

* [$ssl](#property-$ssl)
* [$php_self](#property-$php_self)
* [$id_cart](#property-$id_cart)
* [$id_module](#property-$id_module)
* [$id_order](#property-$id_order)
* [$reference](#property-$reference)
* [$secure_key](#property-$secure_key)

Methods
-------
* [init](#method-init)
* [initContent](#method-initContent)
* [displayPaymentReturn](#method-displayPaymentReturn)
* [displayOrderConfirmation](#method-displayOrderConfirmation)




Properties
----------


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in [controllers/front/OrderConfirmationController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L29)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'order-confirmation'





* Visibility: **public**
* This property is defined in [controllers/front/OrderConfirmationController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L30)


### <a name="property-$id_cart"></a>$id_cart

    public mixed $id_cart





* Visibility: **public**
* This property is defined in [controllers/front/OrderConfirmationController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L31)


### <a name="property-$id_module"></a>$id_module

    public mixed $id_module





* Visibility: **public**
* This property is defined in [controllers/front/OrderConfirmationController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L32)


### <a name="property-$id_order"></a>$id_order

    public mixed $id_order





* Visibility: **public**
* This property is defined in [controllers/front/OrderConfirmationController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L33)


### <a name="property-$reference"></a>$reference

    public mixed $reference





* Visibility: **public**
* This property is defined in [controllers/front/OrderConfirmationController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L34)


### <a name="property-$secure_key"></a>$secure_key

    public mixed $secure_key





* Visibility: **public**
* This property is defined in [controllers/front/OrderConfirmationController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L35)


Methods
-------


### <a name="method-init"></a>init

    mixed OrderConfirmationControllerCore::init()

Initialize order confirmation controller



* Visibility: **public**
* This method is defined in [controllers/front/OrderConfirmationController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L41)




### <a name="method-initContent"></a>initContent

    mixed OrderConfirmationControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/OrderConfirmationController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L81)




### <a name="method-displayPaymentReturn"></a>displayPaymentReturn

    mixed OrderConfirmationControllerCore::displayPaymentReturn()

Execute the hook displayPaymentReturn



* Visibility: **public**
* This method is defined in [controllers/front/OrderConfirmationController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L108)




### <a name="method-displayOrderConfirmation"></a>displayOrderConfirmation

    mixed OrderConfirmationControllerCore::displayOrderConfirmation()

Execute the hook displayOrderConfirmation



* Visibility: **public**
* This method is defined in [controllers/front/OrderConfirmationController.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/OrderConfirmationController.php#L130)



