Class ContextCore
=====================





* Class name: ContextCore
* Source: [classes/Context.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L30)


Contents
--------

### Constants

* [DEVICE_COMPUTER](#constant-DEVICE_COMPUTER)
* [DEVICE_MOBILE](#constant-DEVICE_MOBILE)
* [DEVICE_TABLET](#constant-DEVICE_TABLET)

### Properties

* [$cart](#property-$cart)
* [$controller](#property-$controller)
* [$cookie](#property-$cookie)
* [$country](#property-$country)
* [$currency](#property-$currency)
* [$customer](#property-$customer)
* [$employee](#property-$employee)
* [$instance](#property-$instance)
* [$language](#property-$language)
* [$link](#property-$link)
* [$mobile_detect](#property-$mobile_detect)
* [$mobile_device](#property-$mobile_device)
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


Constants
----------


### <a name="constant-DEVICE_COMPUTER"></a>DEVICE_COMPUTER

```php
const DEVICE_COMPUTER = 1
```





* Source: [classes/Context.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L112).


### <a name="constant-DEVICE_MOBILE"></a>DEVICE_MOBILE

```php
const DEVICE_MOBILE = 4
```





* Source: [classes/Context.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L116).


### <a name="constant-DEVICE_TABLET"></a>DEVICE_TABLET

```php
const DEVICE_TABLET = 2
```





* Source: [classes/Context.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L114).


Properties
----------


### <a name="property-$cart"></a>$cart

```php
public \Cart $cart
```





* Visibility: **public**
* Source: [classes/Context.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L40).


### <a name="property-$controller"></a>$controller

```php
public \Controller $controller
```





* Visibility: **public**
* Source: [classes/Context.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L70).


### <a name="property-$cookie"></a>$cookie

```php
public \Cookie $cookie
```





* Visibility: **public**
* Source: [classes/Context.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L50).


### <a name="property-$country"></a>$country

```php
public \Country $country
```





* Visibility: **public**
* Source: [classes/Context.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L60).


### <a name="property-$currency"></a>$currency

```php
public \Currency $currency
```





* Visibility: **public**
* Source: [classes/Context.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L80).


### <a name="property-$customer"></a>$customer

```php
public \Customer $customer
```





* Visibility: **public**
* Source: [classes/Context.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L45).


### <a name="property-$employee"></a>$employee

```php
public \Employee $employee
```





* Visibility: **public**
* Source: [classes/Context.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L65).


### <a name="property-$instance"></a>$instance

```php
protected \Context $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Context.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L35).


### <a name="property-$language"></a>$language

```php
public \Language $language
```





* Visibility: **public**
* Source: [classes/Context.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L75).


### <a name="property-$link"></a>$link

```php
public \Link $link
```





* Visibility: **public**
* Source: [classes/Context.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L55).


### <a name="property-$mobile_detect"></a>$mobile_detect

```php
public mixed $mobile_detect
```





* Visibility: **public**
* Source: [classes/Context.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L105).


### <a name="property-$mobile_device"></a>$mobile_device

```php
protected boolean $mobile_device = null
```





* Visibility: **protected**
* Source: [classes/Context.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L110).


### <a name="property-$shop"></a>$shop

```php
public \Shop $shop
```





* Visibility: **public**
* Source: [classes/Context.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L90).


### <a name="property-$smarty"></a>$smarty

```php
public \Smarty $smarty
```





* Visibility: **public**
* Source: [classes/Context.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L100).


### <a name="property-$tab"></a>$tab

```php
public \AdminTab $tab
```





* Visibility: **public**
* Source: [classes/Context.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L85).


### <a name="property-$theme"></a>$theme

```php
public \Theme $theme
```





* Visibility: **public**
* Source: [classes/Context.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L95).


Methods
-------


### <a name="method-checkMobileContext"></a>checkMobileContext

```php
mixed ContextCore::checkMobileContext()
```





* Visibility: **protected**
* Source: [classes/Context.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L180)




### <a name="method-cloneContext"></a>cloneContext

```php
\Context ContextCore::cloneContext()
```

Clone current context



* Visibility: **public**
* Source: [classes/Context.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L228)




### <a name="method-getContext"></a>getContext

```php
\Context ContextCore::getContext()
```

Get a singleton context



* Visibility: **public**
* This method is **static**.
* Source: [classes/Context.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L216)




### <a name="method-getDevice"></a>getDevice

```php
mixed ContextCore::getDevice()
```





* Visibility: **public**
* Source: [classes/Context.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L162)




### <a name="method-getMobileDetect"></a>getMobileDetect

```php
mixed ContextCore::getMobileDetect()
```





* Visibility: **public**
* Source: [classes/Context.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L118)




### <a name="method-getMobileDevice"></a>getMobileDevice

```php
mixed ContextCore::getMobileDevice()
```





* Visibility: **public**
* Source: [classes/Context.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Context.php#L128)



