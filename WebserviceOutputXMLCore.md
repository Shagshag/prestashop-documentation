WebserviceOutputXMLCore
===============






* Class name: WebserviceOutputXMLCore
* Namespace: 
* This class implements: [WebserviceOutputInterface](WebserviceOutputInterface.md)




Properties
----------


### $docUrl

    public mixed $docUrl = ''





* Visibility: **public**


### $languages

    public mixed $languages = array()





* Visibility: **public**


### $wsUrl

    protected mixed $wsUrl





* Visibility: **protected**


### $schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**


Methods
-------


### setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $schema **mixed**



### getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)




### setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $url **mixed**



### getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)




### getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)




### __construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $languages **mixed**



### setLanguages

    mixed WebserviceOutputXMLCore::setLanguages($languages)





* Visibility: **public**


#### Arguments
* $languages **mixed**



### renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)




### renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)




### renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $message **mixed**
* $code **mixed**



### renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $field **mixed**



### renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### getNodeName

    mixed WebserviceOutputXMLCore::getNodeName($params)





* Visibility: **public**


#### Arguments
* $params **mixed**



### renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $obj **mixed**
* $params **mixed**



### overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $content **mixed**



### renderAssociationWrapperHeader

    mixed WebserviceOutputXMLCore::renderAssociationWrapperHeader()





* Visibility: **public**




### renderAssociationWrapperFooter

    mixed WebserviceOutputXMLCore::renderAssociationWrapperFooter()





* Visibility: **public**




### renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface.md)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**


