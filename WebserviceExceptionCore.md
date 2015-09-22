WebserviceExceptionCore
===============






* Class name: WebserviceExceptionCore
* Namespace: 
* Parent class: Exception

* This class is defined in [classes/webservice/WebserviceException.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#27)



Constants
----------


### SIMPLE

    const SIMPLE = 0



* This constant is defined in [classes/webservice/WebserviceException.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#34)


### DID_YOU_MEAN

    const DID_YOU_MEAN = 1



* This constant is defined in [classes/webservice/WebserviceException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#35)


Properties
----------


### $status

    protected mixed $status





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#29)


### $wrong_value

    protected mixed $wrong_value





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#30)


### $available_values

    protected mixed $available_values





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#31)


### $type

    protected mixed $type





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceException.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#32)


Methods
-------


### __construct

    mixed WebserviceExceptionCore::__construct($message, $code)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#37)


#### Arguments
* $message **mixed**
* $code **mixed**



### getType

    mixed WebserviceExceptionCore::getType()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#47)




### setType

    mixed WebserviceExceptionCore::setType($type)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#51)


#### Arguments
* $type **mixed**



### setStatus

    mixed WebserviceExceptionCore::setStatus($status)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#56)


#### Arguments
* $status **mixed**



### getStatus

    mixed WebserviceExceptionCore::getStatus()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#63)




### getWrongValue

    mixed WebserviceExceptionCore::getWrongValue()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#67)




### setDidYouMean

    mixed WebserviceExceptionCore::setDidYouMean($wrong_value, $available_values)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#71)


#### Arguments
* $wrong_value **mixed**
* $available_values **mixed**



### getAvailableValues

    mixed WebserviceExceptionCore::getAvailableValues()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceException.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceException.php#78)



