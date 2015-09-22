Class ContextCore
=====================

Class ContextCore



* Class name: ContextCore
* Source: [classes/Context.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L32)


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
* [deleteTestingInstance](#method-deleteTestingInstance)
* [getContext](#method-getContext)
* [getDevice](#method-getDevice)
* [getMobileDetect](#method-getMobileDetect)
* [getMobileDevice](#method-getMobileDevice)
* [isMobile](#method-isMobile)
* [isTablet](#method-isTablet)
* [setInstanceForTesting](#method-setInstanceForTesting)


Constants
----------


### <a name="constant-DEVICE_COMPUTER"></a>DEVICE_COMPUTER

```php
const DEVICE_COMPUTER = 1
```





* Source: [classes/Context.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L99).


### <a name="constant-DEVICE_MOBILE"></a>DEVICE_MOBILE

```php
const DEVICE_MOBILE = 4
```





* Source: [classes/Context.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L105).


### <a name="constant-DEVICE_TABLET"></a>DEVICE_TABLET

```php
const DEVICE_TABLET = 2
```





* Source: [classes/Context.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L102).


### <a name="constant-MODE_HOST"></a>MODE_HOST

```php
const MODE_HOST = 8
```





* Source: [classes/Context.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L117).


### <a name="constant-MODE_HOST_CONTRIB"></a>MODE_HOST_CONTRIB

```php
const MODE_HOST_CONTRIB = 4
```





* Source: [classes/Context.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L114).


### <a name="constant-MODE_STD"></a>MODE_STD

```php
const MODE_STD = 1
```





* Source: [classes/Context.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L108).


### <a name="constant-MODE_STD_CONTRIB"></a>MODE_STD_CONTRIB

```php
const MODE_STD_CONTRIB = 2
```





* Source: [classes/Context.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L111).


Properties
----------


### <a name="property-$cart"></a>$cart

```php
public \Cart $cart
```





* Visibility: **public**
* Source: [classes/Context.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L38).


### <a name="property-$controller"></a>$controller

```php
public \AdminController $controller
```





* Visibility: **public**
* Source: [classes/Context.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L56).


### <a name="property-$cookie"></a>$cookie

```php
public \Cookie $cookie
```





* Visibility: **public**
* Source: [classes/Context.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L44).


### <a name="property-$country"></a>$country

```php
public \Country $country
```





* Visibility: **public**
* Source: [classes/Context.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L50).


### <a name="property-$currency"></a>$currency

```php
public \Currency $currency
```





* Visibility: **public**
* Source: [classes/Context.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L65).


### <a name="property-$customer"></a>$customer

```php
public \Customer $customer
```





* Visibility: **public**
* Source: [classes/Context.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L41).


### <a name="property-$employee"></a>$employee

```php
public \Employee $employee
```





* Visibility: **public**
* Source: [classes/Context.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L53).


### <a name="property-$instance"></a>$instance

```php
protected mixed $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Context.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L35).


### <a name="property-$is_mobile"></a>$is_mobile

```php
protected boolean $is_mobile = null
```





* Visibility: **protected**
* Source: [classes/Context.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L93).


### <a name="property-$is_tablet"></a>$is_tablet

```php
protected boolean $is_tablet = null
```





* Visibility: **protected**
* Source: [classes/Context.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L96).


### <a name="property-$language"></a>$language

```php
public \Language $language
```





* Visibility: **public**
* Source: [classes/Context.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L62).


### <a name="property-$link"></a>$link

```php
public \Link $link
```





* Visibility: **public**
* Source: [classes/Context.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L47).


### <a name="property-$mobile_detect"></a>$mobile_detect

```php
public \Mobile_Detect $mobile_detect
```





* Visibility: **public**
* Source: [classes/Context.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L80).


### <a name="property-$mobile_device"></a>$mobile_device

```php
protected boolean $mobile_device = null
```

Mobile device of the customer



* Visibility: **protected**
* Source: [classes/Context.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L90).


### <a name="property-$mode"></a>$mode

```php
public integer $mode
```





* Visibility: **public**
* Source: [classes/Context.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L83).


### <a name="property-$override_controller_name_for_translations"></a>$override_controller_name_for_translations

```php
public string $override_controller_name_for_translations
```





* Visibility: **public**
* Source: [classes/Context.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L59).


### <a name="property-$shop"></a>$shop

```php
public \Shop $shop
```





* Visibility: **public**
* Source: [classes/Context.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L71).


### <a name="property-$smarty"></a>$smarty

```php
public \Smarty $smarty
```





* Visibility: **public**
* Source: [classes/Context.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L77).


### <a name="property-$tab"></a>$tab

```php
public \AdminTab $tab
```





* Visibility: **public**
* Source: [classes/Context.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L68).


### <a name="property-$theme"></a>$theme

```php
public \Theme $theme
```





* Visibility: **public**
* Source: [classes/Context.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L74).


Methods
-------


### <a name="method-checkMobileContext"></a>checkMobileContext

```php
boolean ContextCore::checkMobileContext()
```

Checks if mobile context is possible



* Visibility: **protected**
* Source: [classes/Context.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L229)




### <a name="method-cloneContext"></a>cloneContext

```php
\Context ContextCore::cloneContext()
```

Clone current context object



* Visibility: **public**
* Source: [classes/Context.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L295)




### <a name="method-deleteTestingInstance"></a>deleteTestingInstance

```php
mixed ContextCore::deleteTestingInstance()
```

Unit testing purpose only



* Visibility: **public**
* This method is **static**.
* Source: [classes/Context.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L285)




### <a name="method-getContext"></a>getContext

```php
\Context ContextCore::getContext()
```

Get a singleton instance of Context object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Context.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L265)




### <a name="method-getDevice"></a>getDevice

```php
integer ContextCore::getDevice()
```

Returns mobile device type



* Visibility: **public**
* Source: [classes/Context.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L206)




### <a name="method-getMobileDetect"></a>getMobileDetect

```php
\Mobile_Detect ContextCore::getMobileDetect()
```

Sets Mobile_Detect tool object



* Visibility: **public**
* Source: [classes/Context.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L124)




### <a name="method-getMobileDevice"></a>getMobileDevice

```php
boolean ContextCore::getMobileDevice()
```

Sets mobile_device context variable



* Visibility: **public**
* Source: [classes/Context.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L169)




### <a name="method-isMobile"></a>isMobile

```php
boolean ContextCore::isMobile()
```

Checks if visitor's device is a mobile device



* Visibility: **public**
* Source: [classes/Context.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L139)




### <a name="method-isTablet"></a>isTablet

```php
boolean ContextCore::isTablet()
```

Checks if visitor's device is a tablet device



* Visibility: **public**
* Source: [classes/Context.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L154)




### <a name="method-setInstanceForTesting"></a>setInstanceForTesting

```php
mixed ContextCore::setInstanceForTesting($test_instance)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Context.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Context.php#L277)


#### Arguments
* $test_instance **mixed** - Context
Unit testing purpose only


