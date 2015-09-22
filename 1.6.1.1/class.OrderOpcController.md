Class OrderOpcController
=====================

DISCLAIMER

Do not edit or add to this file if you wish to upgrade this module to newer
versions in the future. If you wish to customize this module for your
needs please refer to http://doc.prestashop.com/display/PS15/Overriding+default+behaviors
#Overridingdefaultbehaviors-Overridingamodule%27sbehavior for more information.

* Class name: OrderOpcController
* Parent class: [OrderOpcControllerCore](class.OrderOpcControllerCore.md)
* Source: [override/controllers/front/OrderOpcController.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L16)


Contents
--------


### Properties

* [$ajax_refresh](#property-$ajax_refresh)
* [$isLogged](#property-$isLogged)
* [$php_self](#property-$php_self)

### Methods

* [_assignCarrier](#method-_assignCarrier)
* [_assignPayment](#method-_assignPayment)
* [_getCarrierList](#method-_getCarrierList)
* [_getGuestInformations](#method-_getGuestInformations)
* [_getPaymentMethods](#method-_getPaymentMethods)
* [_processAddressFormat](#method-_processAddressFormat)
* [getFormatedSummaryDetail](#method-getFormatedSummaryDetail)
* [init](#method-init)
* [initContent](#method-initContent)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$ajax_refresh"></a>$ajax_refresh

```php
protected mixed $ajax_refresh = false
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L32).


### <a name="property-$isLogged"></a>$isLogged

```php
public mixed $isLogged
```





* Visibility: **public**
* Source: [override/controllers/front/OrderOpcController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L30).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'order-opc'
```





* Visibility: **public**
* Source: [override/controllers/front/OrderOpcController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L29).


Methods
-------


### <a name="method-_assignCarrier"></a>_assignCarrier

```php
mixed OrderOpcController::_assignCarrier()
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L506)




### <a name="method-_assignPayment"></a>_assignPayment

```php
mixed OrderOpcController::_assignPayment()
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L527)




### <a name="method-_getCarrierList"></a>_getCarrierList

```php
mixed OrderOpcController::_getCarrierList()
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L609)




### <a name="method-_getGuestInformations"></a>_getGuestInformations

```php
mixed OrderOpcController::_getGuestInformations()
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L437)




### <a name="method-_getPaymentMethods"></a>_getPaymentMethods

```php
mixed OrderOpcController::_getPaymentMethods()
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L544)




### <a name="method-_processAddressFormat"></a>_processAddressFormat

```php
mixed OrderOpcController::_processAddressFormat()
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L695)




### <a name="method-getFormatedSummaryDetail"></a>getFormatedSummaryDetail

```php
mixed OrderOpcController::getFormatedSummaryDetail()
```





* Visibility: **protected**
* Source: [override/controllers/front/OrderOpcController.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L738)




### <a name="method-init"></a>init

```php
mixed OrderOpcController::init()
```

Initialize order opc controller



* Visibility: **public**
* Source: [override/controllers/front/OrderOpcController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L38)




### <a name="method-initContent"></a>initContent

```php
mixed OrderOpcController::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [override/controllers/front/OrderOpcController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L351)




### <a name="method-setMedia"></a>setMedia

```php
mixed OrderOpcController::setMedia()
```





* Visibility: **public**
* Source: [override/controllers/front/OrderOpcController.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/controllers/front/OrderOpcController.php#L325)



