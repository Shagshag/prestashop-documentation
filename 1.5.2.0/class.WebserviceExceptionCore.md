Class WebserviceExceptionCore
=====================





* Class name: WebserviceExceptionCore
* Parent class: Exception
* Source: [classes/webservice/WebserviceException.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L28)


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





* Source: [classes/webservice/WebserviceException.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L36).


### <a name="constant-SIMPLE"></a>SIMPLE

```php
const SIMPLE = 0
```





* Source: [classes/webservice/WebserviceException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L35).


Properties
----------


### <a name="property-$available_values"></a>$available_values

```php
protected mixed $available_values
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L32).


### <a name="property-$status"></a>$status

```php
protected mixed $status
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L30).


### <a name="property-$type"></a>$type

```php
protected mixed $type
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L33).


### <a name="property-$wrong_value"></a>$wrong_value

```php
protected mixed $wrong_value
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceException.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed WebserviceExceptionCore::__construct($message, $code)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L38)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-getAvailableValues"></a>getAvailableValues

```php
mixed WebserviceExceptionCore::getAvailableValues()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L79)




### <a name="method-getStatus"></a>getStatus

```php
mixed WebserviceExceptionCore::getStatus()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L64)




### <a name="method-getType"></a>getType

```php
mixed WebserviceExceptionCore::getType()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L49)




### <a name="method-getWrongValue"></a>getWrongValue

```php
mixed WebserviceExceptionCore::getWrongValue()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L68)




### <a name="method-setDidYouMean"></a>setDidYouMean

```php
mixed WebserviceExceptionCore::setDidYouMean($wrong_value, $available_values)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L72)


#### Arguments
* $wrong_value **mixed**
* $available_values **mixed**



### <a name="method-setStatus"></a>setStatus

```php
mixed WebserviceExceptionCore::setStatus($status)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L58)


#### Arguments
* $status **mixed**



### <a name="method-setType"></a>setType

```php
mixed WebserviceExceptionCore::setType($type)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceException.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/webservice/WebserviceException.php#L53)


#### Arguments
* $type **mixed**


