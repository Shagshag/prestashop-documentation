WebserviceOutputInterface
===============






* Interface name: WebserviceOutputInterface
* Namespace: 
* This is an **interface**
* This interface is defined in classes\webservice\WebserviceOutputInterface.php line 27






Methods
-------


### __construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 29


#### Arguments
* $languages **mixed**



### setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 30


#### Arguments
* $url **mixed**



### getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 31




### getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 32




### setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 33


#### Arguments
* $schema **mixed**



### getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 34




### renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 35


#### Arguments
* $field **mixed**



### renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 36


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 37


#### Arguments
* $obj **mixed**
* $params **mixed**



### renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 38


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 39


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 40


#### Arguments
* $content **mixed**



### renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 41




### renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 42




### renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputInterface.php line 43


#### Arguments
* $message **mixed**
* $code **mixed**


