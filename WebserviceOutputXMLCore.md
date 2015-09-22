WebserviceOutputXMLCore
===============






* Class name: WebserviceOutputXMLCore
* Namespace: 
* This class implements: [WebserviceOutputInterface](WebserviceOutputInterface)* This class is defined in classes\webservice\WebserviceOutputXML.php line 27





Properties
----------


### $docUrl

    public mixed $docUrl = ''





* Visibility: **public**
* This property is defined in classes\webservice\WebserviceOutputXML.php line 29


### $languages

    public mixed $languages = array()





* Visibility: **public**
* This property is defined in classes\webservice\WebserviceOutputXML.php line 30


### $wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceOutputXML.php line 31


### $schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceOutputXML.php line 32


Methods
-------


### setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 33


#### Arguments
* $schema **mixed**



### getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 34




### setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 30


#### Arguments
* $url **mixed**



### getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 31




### getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 32




### __construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 29


#### Arguments
* $languages **mixed**



### setLanguages

    mixed WebserviceOutputXMLCore::setLanguages($languages)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputXML.php line 64


#### Arguments
* $languages **mixed**



### renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 41




### renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 42




### renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 43


#### Arguments
* $message **mixed**
* $code **mixed**



### renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 35


#### Arguments
* $field **mixed**



### renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 36


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### getNodeName

    mixed WebserviceOutputXMLCore::getNodeName($params)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputXML.php line 162


#### Arguments
* $params **mixed**



### renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 37


#### Arguments
* $obj **mixed**
* $params **mixed**



### overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 40


#### Arguments
* $content **mixed**



### renderAssociationWrapperHeader

    mixed WebserviceOutputXMLCore::renderAssociationWrapperHeader()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputXML.php line 182




### renderAssociationWrapperFooter

    mixed WebserviceOutputXMLCore::renderAssociationWrapperFooter()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceOutputXML.php line 186




### renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 38


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in classes\webservice\WebserviceOutputXML.php line 39


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**


