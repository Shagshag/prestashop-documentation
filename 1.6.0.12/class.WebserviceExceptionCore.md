Class WebserviceExceptionCore
=====================





* Class name: WebserviceExceptionCore
* Parent class: Exception
* Source: [classes/webservice/WebserviceException.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L27)


Contents
--------

### Constants

* [DID_YOU_MEAN](#constant-DID_YOU_MEAN)
* [SIMPLE](#constant-SIMPLE)

### Properties

* [$available_values](#property-$available_values)
* [$status](#property-$status)
* [$type](#property-$type)
* [$wrong_value](#property-$wrong_value)

### Methods

* [__construct](#method-__construct)
* [getAvailableValues](#method-getAvailableValues)
* [getStatus](#method-getStatus)
* [getType](#method-getType)
* [getWrongValue](#method-getWrongValue)
* [setDidYouMean](#method-setDidYouMean)
* [setStatus](#method-setStatus)
* [setType](#method-setType)


Constants
----------


### <a name="constant-DID_YOU_MEAN"></a>DID_YOU_MEAN

```php
const DID_YOU_MEAN = 1
```





* Source: [classes/webservice/WebserviceException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L35).


### <a name="constant-SIMPLE"></a>SIMPLE

```php
const SIMPLE = 0
```





* Source: [classes/webservice/WebserviceException.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L34).


Properties
----------


### <a name="property-$available_values"></a>$available_values

```php
protected mixed $available_values
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L31).


### <a name="property-$status"></a>$status

```php
protected mixed $status
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L29).


### <a name="property-$type"></a>$type

```php
protected mixed $type
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L32).


### <a name="property-$wrong_value"></a>$wrong_value

```php
protected mixed $wrong_value
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed WebserviceExceptionCore::__construct($message, $code)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L37)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-getAvailableValues"></a>getAvailableValues

```php
mixed WebserviceExceptionCore::getAvailableValues()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L78)




### <a name="method-getStatus"></a>getStatus

```php
mixed WebserviceExceptionCore::getStatus()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L63)




### <a name="method-getType"></a>getType

```php
mixed WebserviceExceptionCore::getType()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L48)




### <a name="method-getWrongValue"></a>getWrongValue

```php
mixed WebserviceExceptionCore::getWrongValue()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L67)




### <a name="method-setDidYouMean"></a>setDidYouMean

```php
mixed WebserviceExceptionCore::setDidYouMean($wrong_value, $available_values)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L71)


#### Arguments
* $wrong_value **mixed**
* $available_values **mixed**



### <a name="method-setStatus"></a>setStatus

```php
mixed WebserviceExceptionCore::setStatus($status)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L57)


#### Arguments
* $status **mixed**



### <a name="method-setType"></a>setType

```php
mixed WebserviceExceptionCore::setType($type)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/webservice/WebserviceException.php#L52)


#### Arguments
* $type **mixed**


