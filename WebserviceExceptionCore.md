WebserviceExceptionCore
===============






* Class name: WebserviceExceptionCore
* Namespace: 
* Parent class: Exception



Constants
----------


### SIMPLE

    const SIMPLE = 0





### DID_YOU_MEAN

    const DID_YOU_MEAN = 1





Properties
----------


### $status

    protected mixed $status





* Visibility: **protected**


### $wrong_value

    protected mixed $wrong_value





* Visibility: **protected**


### $available_values

    protected mixed $available_values





* Visibility: **protected**


### $type

    protected mixed $type





* Visibility: **protected**


Methods
-------


### __construct

    mixed WebserviceExceptionCore::__construct($message, $code)





* Visibility: **public**


#### Arguments
* $message **mixed**
* $code **mixed**



### getType

    mixed WebserviceExceptionCore::getType()





* Visibility: **public**




### setType

    mixed WebserviceExceptionCore::setType($type)





* Visibility: **public**


#### Arguments
* $type **mixed**



### setStatus

    mixed WebserviceExceptionCore::setStatus($status)





* Visibility: **public**


#### Arguments
* $status **mixed**



### getStatus

    mixed WebserviceExceptionCore::getStatus()





* Visibility: **public**




### getWrongValue

    mixed WebserviceExceptionCore::getWrongValue()





* Visibility: **public**




### setDidYouMean

    mixed WebserviceExceptionCore::setDidYouMean($wrong_value, $available_values)





* Visibility: **public**


#### Arguments
* $wrong_value **mixed**
* $available_values **mixed**



### getAvailableValues

    mixed WebserviceExceptionCore::getAvailableValues()





* Visibility: **public**



