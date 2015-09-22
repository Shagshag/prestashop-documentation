Class StoreCore
=====================





* Class name: StoreCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Store.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$address1](#property-$address1)
* [$address2](#property-$address2)
* [$city](#property-$city)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$email](#property-$email)
* [$fax](#property-$fax)
* [$hours](#property-$hours)
* [$id_country](#property-$id_country)
* [$id_state](#property-$id_state)
* [$latitude](#property-$latitude)
* [$longitude](#property-$longitude)
* [$name](#property-$name)
* [$note](#property-$note)
* [$phone](#property-$phone)
* [$postcode](#property-$postcode)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [getWsHours](#method-getWsHours)
* [setWsHours](#method-setWsHours)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Store.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L78).


### <a name="property-$address1"></a>$address1

```php
public string $address1
```





* Visibility: **public**
* Source: [classes/Store.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L39).


### <a name="property-$address2"></a>$address2

```php
public string $address2
```





* Visibility: **public**
* Source: [classes/Store.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L42).


### <a name="property-$city"></a>$city

```php
public string $city
```





* Visibility: **public**
* Source: [classes/Store.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L48).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Store.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L72).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Store.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L75).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'store', 'primary' => 'id_store', 'fields' => array('id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'address1' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'required' => true, 'size' => 128), 'address2' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'size' => 128), 'postcode' => array('type' => self::TYPE_STRING, 'size' => 12), 'city' => array('type' => self::TYPE_STRING, 'validate' => 'isCityName', 'required' => true, 'size' => 64), 'latitude' => array('type' => self::TYPE_FLOAT, 'validate' => 'isCoordinate', 'size' => 13), 'longitude' => array('type' => self::TYPE_FLOAT, 'validate' => 'isCoordinate', 'size' => 13), 'hours' => array('type' => self::TYPE_STRING, 'validate' => 'isSerializedArray', 'size' => 65000), 'phone' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'fax' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'note' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65000), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 128), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Store.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L83).


### <a name="property-$email"></a>$email

```php
public string $email
```





* Visibility: **public**
* Source: [classes/Store.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L69).


### <a name="property-$fax"></a>$fax

```php
public string $fax
```





* Visibility: **public**
* Source: [classes/Store.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L63).


### <a name="property-$hours"></a>$hours

```php
public string $hours
```





* Visibility: **public**
* Source: [classes/Store.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L57).


### <a name="property-$id_country"></a>$id_country

```php
public integer $id_country
```





* Visibility: **public**
* Source: [classes/Store.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L30).


### <a name="property-$id_state"></a>$id_state

```php
public integer $id_state
```





* Visibility: **public**
* Source: [classes/Store.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L33).


### <a name="property-$latitude"></a>$latitude

```php
public float $latitude
```





* Visibility: **public**
* Source: [classes/Store.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L51).


### <a name="property-$longitude"></a>$longitude

```php
public float $longitude
```





* Visibility: **public**
* Source: [classes/Store.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L54).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Store.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L36).


### <a name="property-$note"></a>$note

```php
public string $note
```





* Visibility: **public**
* Source: [classes/Store.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L66).


### <a name="property-$phone"></a>$phone

```php
public string $phone
```





* Visibility: **public**
* Source: [classes/Store.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L60).


### <a name="property-$postcode"></a>$postcode

```php
public string $postcode
```





* Visibility: **public**
* Source: [classes/Store.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L45).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_country' => array('xlink_resource' => 'countries'), 'id_state' => array('xlink_resource' => 'states'), 'hours' => array('getter' => 'getWsHours', 'setter' => 'setWsHours')))
```





* Visibility: **protected**
* Source: [classes/Store.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L107).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed StoreCore::__construct($id_store, $id_lang)
```





* Visibility: **public**
* Source: [classes/Store.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L115)


#### Arguments
* $id_store **mixed**
* $id_lang **mixed**



### <a name="method-getWsHours"></a>getWsHours

```php
mixed StoreCore::getWsHours()
```





* Visibility: **public**
* Source: [classes/Store.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L122)




### <a name="method-setWsHours"></a>setWsHours

```php
mixed StoreCore::setWsHours($hours)
```





* Visibility: **public**
* Source: [classes/Store.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Store.php#L127)


#### Arguments
* $hours **mixed**


