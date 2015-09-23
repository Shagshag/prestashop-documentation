Class OrderControllerCore
=====================





* Class name: OrderControllerCore
* Parent class: [ParentOrderController](class.ParentOrderControllerCore.md)
* Source: [controllers/front/OrderController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L27)


Contents
--------


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




Properties
----------


### <a name="property-$step"></a>$step

```php
public mixed $step
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L29).


Methods
-------


### <a name="method-_assignAddress"></a>_assignAddress

```php
mixed OrderControllerCore::_assignAddress()
```

Address step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L324)




### <a name="method-_assignCarrier"></a>_assignCarrier

```php
mixed OrderControllerCore::_assignCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L338)




### <a name="method-_assignPayment"></a>_assignPayment

```php
mixed OrderControllerCore::_assignPayment()
```

Payment step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 356](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L356)




### <a name="method-autoStep"></a>autoStep

```php
mixed OrderControllerCore::autoStep()
```

Order process controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L224)




### <a name="method-init"></a>init

```php
mixed OrderControllerCore::init()
```

Initialize order controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L35)




### <a name="method-initContent"></a>initContent

```php
mixed OrderControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L95)




### <a name="method-postProcess"></a>postProcess

```php
mixed OrderControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L83)




### <a name="method-processAddress"></a>processAddress

```php
mixed OrderControllerCore::processAddress()
```

Manage address



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L249)




### <a name="method-processAddressFormat"></a>processAddressFormat

```php
mixed OrderControllerCore::processAddressFormat()
```





* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L208)




### <a name="method-processCarrier"></a>processCarrier

```php
mixed OrderControllerCore::processCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L306)




### <a name="method-setMedia"></a>setMedia

```php
mixed OrderControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/front/OrderController.php#L374)



