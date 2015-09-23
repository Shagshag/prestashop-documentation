Class ContextCore
=====================





* Class name: ContextCore
* Source: [classes/Context.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L30)


Contents
--------

### Constants

* [DEVICE_COMPUTER](#constant-DEVICE_COMPUTER)
* [DEVICE_MOBILE](#constant-DEVICE_MOBILE)
* [DEVICE_TABLET](#constant-DEVICE_TABLET)
* [MODE_HOST](#constant-MODE_HOST)
* [MODE_HOST_CONTRIB](#constant-MODE_HOST_CONTRIB)
* [MODE_STD](#constant-MODE_STD)
* [MODE_STD_CONTRIB](#constant-MODE_STD_CONTRIB)

### Properties

* [$cart](#property-$cart)
* [$controller](#property-$controller)
* [$cookie](#property-$cookie)
* [$country](#property-$country)
* [$currency](#property-$currency)
* [$customer](#property-$customer)
* [$employee](#property-$employee)
* [$instance](#property-$instance)
* [$is_mobile](#property-$is_mobile)
* [$is_tablet](#property-$is_tablet)
* [$language](#property-$language)
* [$link](#property-$link)
* [$mobile_detect](#property-$mobile_detect)
* [$mobile_device](#property-$mobile_device)
* [$mode](#property-$mode)
* [$override_controller_name_for_translations](#property-$override_controller_name_for_translations)
* [$shop](#property-$shop)
* [$smarty](#property-$smarty)
* [$tab](#property-$tab)
* [$theme](#property-$theme)

### Methods

* [checkMobileContext](#method-checkMobileContext)
* [cloneContext](#method-cloneContext)
* [getContext](#method-getContext)
* [getDevice](#method-getDevice)
* [getMobileDetect](#method-getMobileDetect)
* [getMobileDevice](#method-getMobileDevice)
* [isMobile](#method-isMobile)
* [isTablet](#method-isTablet)


Constants
----------


### <a name="constant-DEVICE_COMPUTER"></a>DEVICE_COMPUTER

```php
const DEVICE_COMPUTER = 1
```





* Source: [classes/Context.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L123).


### <a name="constant-DEVICE_MOBILE"></a>DEVICE_MOBILE

```php
const DEVICE_MOBILE = 4
```





* Source: [classes/Context.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L127).


### <a name="constant-DEVICE_TABLET"></a>DEVICE_TABLET

```php
const DEVICE_TABLET = 2
```





* Source: [classes/Context.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L125).


### <a name="constant-MODE_HOST"></a>MODE_HOST

```php
const MODE_HOST = 8
```





* Source: [classes/Context.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L135).


### <a name="constant-MODE_HOST_CONTRIB"></a>MODE_HOST_CONTRIB

```php
const MODE_HOST_CONTRIB = 4
```





* Source: [classes/Context.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L133).


### <a name="constant-MODE_STD"></a>MODE_STD

```php
const MODE_STD = 1
```





* Source: [classes/Context.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L129).


### <a name="constant-MODE_STD_CONTRIB"></a>MODE_STD_CONTRIB

```php
const MODE_STD_CONTRIB = 2
```





* Source: [classes/Context.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L131).


Properties
----------


### <a name="property-$cart"></a>$cart

```php
public \Cart $cart
```





* Visibility: **public**
* Source: [classes/Context.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L40).


### <a name="property-$controller"></a>$controller

```php
public \Controller $controller
```





* Visibility: **public**
* Source: [classes/Context.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L70).


### <a name="property-$cookie"></a>$cookie

```php
public \Cookie $cookie
```





* Visibility: **public**
* Source: [classes/Context.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L50).


### <a name="property-$country"></a>$country

```php
public \Country $country
```





* Visibility: **public**
* Source: [classes/Context.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L60).


### <a name="property-$currency"></a>$currency

```php
public \Currency $currency
```





* Visibility: **public**
* Source: [classes/Context.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L85).


### <a name="property-$customer"></a>$customer

```php
public \Customer $customer
```





* Visibility: **public**
* Source: [classes/Context.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L45).


### <a name="property-$employee"></a>$employee

```php
public \Employee $employee
```





* Visibility: **public**
* Source: [classes/Context.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L65).


### <a name="property-$instance"></a>$instance

```php
protected \Context $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Context.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L35).


### <a name="property-$is_mobile"></a>$is_mobile

```php
protected mixed $is_mobile = null
```





* Visibility: **protected**
* Source: [classes/Context.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L119).


### <a name="property-$is_tablet"></a>$is_tablet

```php
protected mixed $is_tablet = null
```





* Visibility: **protected**
* Source: [classes/Context.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L121).


### <a name="property-$language"></a>$language

```php
public \Language $language
```





* Visibility: **public**
* Source: [classes/Context.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L80).


### <a name="property-$link"></a>$link

```php
public \Link $link
```





* Visibility: **public**
* Source: [classes/Context.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L55).


### <a name="property-$mobile_detect"></a>$mobile_detect

```php
public mixed $mobile_detect
```





* Visibility: **public**
* Source: [classes/Context.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L110).


### <a name="property-$mobile_device"></a>$mobile_device

```php
protected boolean $mobile_device = null
```





* Visibility: **protected**
* Source: [classes/Context.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L117).


### <a name="property-$mode"></a>$mode

```php
public mixed $mode
```





* Visibility: **public**
* Source: [classes/Context.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L112).


### <a name="property-$override_controller_name_for_translations"></a>$override_controller_name_for_translations

```php
public string $override_controller_name_for_translations
```





* Visibility: **public**
* Source: [classes/Context.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L75).


### <a name="property-$shop"></a>$shop

```php
public \Shop $shop
```





* Visibility: **public**
* Source: [classes/Context.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L95).


### <a name="property-$smarty"></a>$smarty

```php
public \Smarty $smarty
```





* Visibility: **public**
* Source: [classes/Context.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L105).


### <a name="property-$tab"></a>$tab

```php
public \AdminTab $tab
```





* Visibility: **public**
* Source: [classes/Context.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L90).


### <a name="property-$theme"></a>$theme

```php
public \Theme $theme
```





* Visibility: **public**
* Source: [classes/Context.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L100).


Methods
-------


### <a name="method-checkMobileContext"></a>checkMobileContext

```php
mixed ContextCore::checkMobileContext()
```





* Visibility: **protected**
* Source: [classes/Context.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L217)




### <a name="method-cloneContext"></a>cloneContext

```php
\Context ContextCore::cloneContext()
```

Clone current context



* Visibility: **public**
* Source: [classes/Context.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L265)




### <a name="method-getContext"></a>getContext

```php
\Context ContextCore::getContext()
```

Get a singleton context



* Visibility: **public**
* This method is **static**.
* Source: [classes/Context.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L253)




### <a name="method-getDevice"></a>getDevice

```php
mixed ContextCore::getDevice()
```





* Visibility: **public**
* Source: [classes/Context.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L200)




### <a name="method-getMobileDetect"></a>getMobileDetect

```php
mixed ContextCore::getMobileDetect()
```





* Visibility: **public**
* Source: [classes/Context.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L137)




### <a name="method-getMobileDevice"></a>getMobileDevice

```php
mixed ContextCore::getMobileDevice()
```





* Visibility: **public**
* Source: [classes/Context.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L167)




### <a name="method-isMobile"></a>isMobile

```php
mixed ContextCore::isMobile()
```





* Visibility: **public**
* Source: [classes/Context.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L147)




### <a name="method-isTablet"></a>isTablet

```php
mixed ContextCore::isTablet()
```





* Visibility: **public**
* Source: [classes/Context.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Context.php#L157)



