Class GuestCore
=====================





* Class name: GuestCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Guest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L27)


Contents
--------


### Properties

* [$accept_language](#property-$accept_language)
* [$adobe_director](#property-$adobe_director)
* [$adobe_flash](#property-$adobe_flash)
* [$apple_quicktime](#property-$apple_quicktime)
* [$definition](#property-$definition)
* [$id_customer](#property-$id_customer)
* [$id_operating_system](#property-$id_operating_system)
* [$id_web_browser](#property-$id_web_browser)
* [$javascript](#property-$javascript)
* [$mobile_theme](#property-$mobile_theme)
* [$real_player](#property-$real_player)
* [$screen_color](#property-$screen_color)
* [$screen_resolution_x](#property-$screen_resolution_x)
* [$screen_resolution_y](#property-$screen_resolution_y)
* [$sun_java](#property-$sun_java)
* [$webserviceParameters](#property-$webserviceParameters)
* [$windows_media](#property-$windows_media)

### Methods

* [getBrowser](#method-getBrowser)
* [getFromCustomer](#method-getFromCustomer)
* [getLanguage](#method-getLanguage)
* [getOs](#method-getOs)
* [mergeWithCustomer](#method-mergeWithCustomer)
* [setNewGuest](#method-setNewGuest)
* [userAgent](#method-userAgent)




Properties
----------


### <a name="property-$accept_language"></a>$accept_language

```php
public mixed $accept_language
```





* Visibility: **public**
* Source: [classes/Guest.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L42).


### <a name="property-$adobe_director"></a>$adobe_director

```php
public mixed $adobe_director
```





* Visibility: **public**
* Source: [classes/Guest.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L38).


### <a name="property-$adobe_flash"></a>$adobe_flash

```php
public mixed $adobe_flash
```





* Visibility: **public**
* Source: [classes/Guest.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L37).


### <a name="property-$apple_quicktime"></a>$apple_quicktime

```php
public mixed $apple_quicktime
```





* Visibility: **public**
* Source: [classes/Guest.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L39).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'guest', 'primary' => 'id_guest', 'fields' => array('id_operating_system' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_web_browser' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'javascript' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'screen_resolution_x' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_resolution_y' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_color' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sun_java' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_flash' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_director' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'apple_quicktime' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'real_player' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'windows_media' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'accept_language' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 8), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Guest.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L48).


### <a name="property-$id_customer"></a>$id_customer

```php
public mixed $id_customer
```





* Visibility: **public**
* Source: [classes/Guest.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L31).


### <a name="property-$id_operating_system"></a>$id_operating_system

```php
public mixed $id_operating_system
```





* Visibility: **public**
* Source: [classes/Guest.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L29).


### <a name="property-$id_web_browser"></a>$id_web_browser

```php
public mixed $id_web_browser
```





* Visibility: **public**
* Source: [classes/Guest.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L30).


### <a name="property-$javascript"></a>$javascript

```php
public mixed $javascript
```





* Visibility: **public**
* Source: [classes/Guest.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L32).


### <a name="property-$mobile_theme"></a>$mobile_theme

```php
public mixed $mobile_theme
```





* Visibility: **public**
* Source: [classes/Guest.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L43).


### <a name="property-$real_player"></a>$real_player

```php
public mixed $real_player
```





* Visibility: **public**
* Source: [classes/Guest.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L40).


### <a name="property-$screen_color"></a>$screen_color

```php
public mixed $screen_color
```





* Visibility: **public**
* Source: [classes/Guest.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L35).


### <a name="property-$screen_resolution_x"></a>$screen_resolution_x

```php
public mixed $screen_resolution_x
```





* Visibility: **public**
* Source: [classes/Guest.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L33).


### <a name="property-$screen_resolution_y"></a>$screen_resolution_y

```php
public mixed $screen_resolution_y
```





* Visibility: **public**
* Source: [classes/Guest.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L34).


### <a name="property-$sun_java"></a>$sun_java

```php
public mixed $sun_java
```





* Visibility: **public**
* Source: [classes/Guest.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L36).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_customer' => array('xlink_resource' => 'customers')))
```





* Visibility: **protected**
* Source: [classes/Guest.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L70).


### <a name="property-$windows_media"></a>$windows_media

```php
public mixed $windows_media
```





* Visibility: **public**
* Source: [classes/Guest.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L41).


Methods
-------


### <a name="method-getBrowser"></a>getBrowser

```php
mixed GuestCore::getBrowser($userAgent)
```





* Visibility: **protected**
* Source: [classes/Guest.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L103)


#### Arguments
* $userAgent **mixed**



### <a name="method-getFromCustomer"></a>getFromCustomer

```php
mixed GuestCore::getFromCustomer($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Guest.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L155)


#### Arguments
* $id_customer **mixed**



### <a name="method-getLanguage"></a>getLanguage

```php
mixed GuestCore::getLanguage($acceptLanguage)
```





* Visibility: **protected**
* Source: [classes/Guest.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L85)


#### Arguments
* $acceptLanguage **mixed**



### <a name="method-getOs"></a>getOs

```php
mixed GuestCore::getOs($userAgent)
```





* Visibility: **protected**
* Source: [classes/Guest.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L131)


#### Arguments
* $userAgent **mixed**



### <a name="method-mergeWithCustomer"></a>mergeWithCustomer

```php
mixed GuestCore::mergeWithCustomer($id_guest, $id_customer)
```





* Visibility: **public**
* Source: [classes/Guest.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L166)


#### Arguments
* $id_guest **mixed**
* $id_customer **mixed**



### <a name="method-setNewGuest"></a>setNewGuest

```php
mixed GuestCore::setNewGuest($cookie)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Guest.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L185)


#### Arguments
* $cookie **mixed**



### <a name="method-userAgent"></a>userAgent

```php
mixed GuestCore::userAgent()
```





* Visibility: **public**
* Source: [classes/Guest.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Guest.php#L76)



