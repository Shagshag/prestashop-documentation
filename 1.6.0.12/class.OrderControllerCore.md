Class OrderControllerCore
=====================





* Class name: OrderControllerCore
* Parent class: [ParentOrderController](class.ParentOrderControllerCore.md)
* Source: [controllers/front/OrderController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L27)


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
* Source: [controllers/front/OrderController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L29).


Methods
-------


### <a name="method-_assignAddress"></a>_assignAddress

```php
mixed OrderControllerCore::_assignAddress()
```

Address step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L364)




### <a name="method-_assignCarrier"></a>_assignCarrier

```php
mixed OrderControllerCore::_assignCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L378)




### <a name="method-_assignPayment"></a>_assignPayment

```php
mixed OrderControllerCore::_assignPayment()
```

Payment step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L396)




### <a name="method-autoStep"></a>autoStep

```php
mixed OrderControllerCore::autoStep()
```

Order process controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L239)




### <a name="method-init"></a>init

```php
mixed OrderControllerCore::init()
```

Initialize order controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L35)




### <a name="method-initContent"></a>initContent

```php
mixed OrderControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L114)




### <a name="method-postProcess"></a>postProcess

```php
mixed OrderControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L102)




### <a name="method-processAddress"></a>processAddress

```php
mixed OrderControllerCore::processAddress()
```

Manage address



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L292)




### <a name="method-processAddressFormat"></a>processAddressFormat

```php
mixed OrderControllerCore::processAddressFormat()
```





* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L223)




### <a name="method-processCarrier"></a>processCarrier

```php
mixed OrderControllerCore::processCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L346)




### <a name="method-setMedia"></a>setMedia

```php
mixed OrderControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/controllers/front/OrderController.php#L414)



