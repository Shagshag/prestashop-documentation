Class OrderControllerCore
=====================





* Class name: OrderControllerCore
* Parent class: [ParentOrderController](class.ParentOrderControllerCore.md)
* Source: [controllers/front/OrderController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L27)


Contents
--------

### Constants

* [STEP_ADDRESSES](#constant-STEP_ADDRESSES)
* [STEP_DELIVERY](#constant-STEP_DELIVERY)
* [STEP_PAYMENT](#constant-STEP_PAYMENT)
* [STEP_SUMMARY_EMPTY_CART](#constant-STEP_SUMMARY_EMPTY_CART)

### Properties

* [$step](#property-$step)

### Methods

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

```php
const STEP_ADDRESSES = 1
```





* Source: [controllers/front/OrderController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L31).


### <a name="constant-STEP_DELIVERY"></a>STEP_DELIVERY

```php
const STEP_DELIVERY = 2
```





* Source: [controllers/front/OrderController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L32).


### <a name="constant-STEP_PAYMENT"></a>STEP_PAYMENT

```php
const STEP_PAYMENT = 3
```





* Source: [controllers/front/OrderController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L33).


### <a name="constant-STEP_SUMMARY_EMPTY_CART"></a>STEP_SUMMARY_EMPTY_CART

```php
const STEP_SUMMARY_EMPTY_CART = -1
```





* Source: [controllers/front/OrderController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L30).


Properties
----------


### <a name="property-$step"></a>$step

```php
public mixed $step
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L29).


Methods
-------


### <a name="method-_assignAddress"></a>_assignAddress

```php
mixed OrderControllerCore::_assignAddress()
```

Address step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 400](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L400)




### <a name="method-_assignCarrier"></a>_assignCarrier

```php
mixed OrderControllerCore::_assignCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L414)




### <a name="method-_assignPayment"></a>_assignPayment

```php
mixed OrderControllerCore::_assignPayment()
```

Payment step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L432)




### <a name="method-autoStep"></a>autoStep

```php
mixed OrderControllerCore::autoStep()
```

Order process controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L255)




### <a name="method-init"></a>init

```php
mixed OrderControllerCore::init()
```

Initialize order controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L39)




### <a name="method-initContent"></a>initContent

```php
mixed OrderControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L118)




### <a name="method-postProcess"></a>postProcess

```php
mixed OrderControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L106)




### <a name="method-processAddress"></a>processAddress

```php
mixed OrderControllerCore::processAddress()
```

Manage address



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L308)




### <a name="method-processAddressFormat"></a>processAddressFormat

```php
mixed OrderControllerCore::processAddressFormat()
```





* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L239)




### <a name="method-processCarrier"></a>processCarrier

```php
mixed OrderControllerCore::processCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L382)




### <a name="method-setMedia"></a>setMedia

```php
mixed OrderControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/OrderController.php#L463)



