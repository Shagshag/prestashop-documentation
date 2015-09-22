WebserviceExceptionCore
===============






* Class name: WebserviceExceptionCore
* Parent class: Exception
* This class is defined in [classes/webservice/WebserviceException.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L27)



Constants
----------

* [SIMPLE](#constant-SIMPLE)
* [DID_YOU_MEAN](#constant-DID_YOU_MEAN)

Properties
----------

* [$status](#property-$status)
* [$wrong_value](#property-$wrong_value)
* [$available_values](#property-$available_values)
* [$type](#property-$type)

Methods
-------
* [__construct](#method-__construct)
* [getType](#method-getType)
* [setType](#method-setType)
* [setStatus](#method-setStatus)
* [getStatus](#method-getStatus)
* [getWrongValue](#method-getWrongValue)
* [setDidYouMean](#method-setDidYouMean)
* [getAvailableValues](#method-getAvailableValues)


Constants
----------


### <a name="constant-SIMPLE"></a>SIMPLE

    const SIMPLE = 0



* This constant is defined in [classes/webservice/WebserviceException.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L34)


### <a name="constant-DID_YOU_MEAN"></a>DID_YOU_MEAN

    const DID_YOU_MEAN = 1



* This constant is defined in [classes/webservice/WebserviceException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L35)


Properties
----------


### <a name="property-$status"></a>$status

    protected mixed $status





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L29)


### <a name="property-$wrong_value"></a>$wrong_value

    protected mixed $wrong_value





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L30)


### <a name="property-$available_values"></a>$available_values

    protected mixed $available_values





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L31)


### <a name="property-$type"></a>$type

    protected mixed $type





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L32)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed WebserviceExceptionCore::__construct($message, $code)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L37)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-getType"></a>getType

    mixed WebserviceExceptionCore::getType()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L47)




### <a name="method-setType"></a>setType

    mixed WebserviceExceptionCore::setType($type)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L51)


#### Arguments
* $type **mixed**



### <a name="method-setStatus"></a>setStatus

    mixed WebserviceExceptionCore::setStatus($status)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L56)


#### Arguments
* $status **mixed**



### <a name="method-getStatus"></a>getStatus

    mixed WebserviceExceptionCore::getStatus()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L63)




### <a name="method-getWrongValue"></a>getWrongValue

    mixed WebserviceExceptionCore::getWrongValue()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L67)




### <a name="method-setDidYouMean"></a>setDidYouMean

    mixed WebserviceExceptionCore::setDidYouMean($wrong_value, $available_values)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L71)


#### Arguments
* $wrong_value **mixed**
* $available_values **mixed**



### <a name="method-getAvailableValues"></a>getAvailableValues

    mixed WebserviceExceptionCore::getAvailableValues()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#L78)



