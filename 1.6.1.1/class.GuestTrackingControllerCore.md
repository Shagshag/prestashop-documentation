Class GuestTrackingControllerCore
=====================





* Class name: GuestTrackingControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/GuestTrackingController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L27)


Contents
--------


### Properties

* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)

### Methods

* [assignOrderTracking](#method-assignOrderTracking)
* [init](#method-init)
* [initContent](#method-initContent)
* [postProcess](#method-postProcess)
* [processAddressFormat](#method-processAddressFormat)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'guest-tracking'
```





* Visibility: **public**
* Source: [controllers/front/GuestTrackingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L30).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* Source: [controllers/front/GuestTrackingController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L29).


Methods
-------


### <a name="method-assignOrderTracking"></a>assignOrderTracking

```php
mixed GuestTrackingControllerCore::assignOrderTracking(\PrestaShopCollection $order_collection)
```

Assigns template vars related to order tracking information



* Visibility: **protected**
* Source: [controllers/front/GuestTrackingController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L135)


#### Arguments
* $order_collection **[PrestaShopCollection](class.PrestaShopCollectionCore.md)**



### <a name="method-init"></a>init

```php
mixed GuestTrackingControllerCore::init()
```

Initialize guest tracking controller



* Visibility: **public**
* Source: [controllers/front/GuestTrackingController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L36)




### <a name="method-initContent"></a>initContent

```php
mixed GuestTrackingControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/GuestTrackingController.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L112)




### <a name="method-postProcess"></a>postProcess

```php
mixed GuestTrackingControllerCore::postProcess()
```

Start forms process



* Visibility: **public**
* Source: [controllers/front/GuestTrackingController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L48)




### <a name="method-processAddressFormat"></a>processAddressFormat

```php
mixed GuestTrackingControllerCore::processAddressFormat(\Address $delivery, \Address $invoice)
```





* Visibility: **protected**
* Source: [controllers/front/GuestTrackingController.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L196)


#### Arguments
* $delivery **[Address](class.AddressCore.md)**
* $invoice **[Address](class.AddressCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed GuestTrackingControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/GuestTrackingController.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/GuestTrackingController.php#L188)



