WebserviceOutputInterface
===============






* Interface name: WebserviceOutputInterface
* Namespace: 
* This is an **interface**






Methods
-------


### __construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**


#### Arguments
* $languages **mixed**



### setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**


#### Arguments
* $url **mixed**



### getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**




### getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**




### setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**


#### Arguments
* $schema **mixed**



### getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**




### renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**


#### Arguments
* $field **mixed**



### renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**


#### Arguments
* $obj **mixed**
* $params **mixed**



### renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**


#### Arguments
* $content **mixed**



### renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**




### renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**




### renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**


#### Arguments
* $message **mixed**
* $code **mixed**


