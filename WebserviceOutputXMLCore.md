WebserviceOutputXMLCore
===============






* Class name: WebserviceOutputXMLCore
* This class is defined in [classes/webservice/WebserviceOutputXML.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L27)
* This class implements: [WebserviceOutputInterface](WebserviceOutputInterface)




Properties
----------

* [$docUrl](#property-$docUrl)
* [$languages](#property-$languages)
* [$wsUrl](#property-$wsUrl)
* [$schemaToDisplay](#property-$schemaToDisplay)

Methods
-------
* [setSchemaToDisplay](#method-setSchemaToDisplay)
* [getSchemaToDisplay](#method-getSchemaToDisplay)
* [setWsUrl](#method-setWsUrl)
* [getWsUrl](#method-getWsUrl)
* [getContentType](#method-getContentType)
* [__construct](#method-__construct)
* [setLanguages](#method-setLanguages)
* [renderErrorsHeader](#method-renderErrorsHeader)
* [renderErrorsFooter](#method-renderErrorsFooter)
* [renderErrors](#method-renderErrors)
* [renderField](#method-renderField)
* [renderNodeHeader](#method-renderNodeHeader)
* [getNodeName](#method-getNodeName)
* [renderNodeFooter](#method-renderNodeFooter)
* [overrideContent](#method-overrideContent)
* [renderAssociationWrapperHeader](#method-renderAssociationWrapperHeader)
* [renderAssociationWrapperFooter](#method-renderAssociationWrapperFooter)
* [renderAssociationHeader](#method-renderAssociationHeader)
* [renderAssociationFooter](#method-renderAssociationFooter)




Properties
----------


### <a name="property-$docUrl"></a>$docUrl

    public mixed $docUrl = ''





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceOutputXML.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L29)


### <a name="property-$languages"></a>$languages

    public mixed $languages = array()





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceOutputXML.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L30)


### <a name="property-$wsUrl"></a>$wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputXML.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L31)


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputXML.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L32)


Methods
-------


### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L33)


#### Arguments
* $schema **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L34)




### <a name="method-setWsUrl"></a>setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L30)


#### Arguments
* $url **mixed**



### <a name="method-getWsUrl"></a>getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L31)




### <a name="method-getContentType"></a>getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L32)




### <a name="method-__construct"></a>__construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L29)


#### Arguments
* $languages **mixed**



### <a name="method-setLanguages"></a>setLanguages

    mixed WebserviceOutputXMLCore::setLanguages($languages)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L64)


#### Arguments
* $languages **mixed**



### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L41)




### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L42)




### <a name="method-renderErrors"></a>renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L43)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderField"></a>renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L35)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L36)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### <a name="method-getNodeName"></a>getNodeName

    mixed WebserviceOutputXMLCore::getNodeName($params)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L162)


#### Arguments
* $params **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L37)


#### Arguments
* $obj **mixed**
* $params **mixed**



### <a name="method-overrideContent"></a>overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L40)


#### Arguments
* $content **mixed**



### <a name="method-renderAssociationWrapperHeader"></a>renderAssociationWrapperHeader

    mixed WebserviceOutputXMLCore::renderAssociationWrapperHeader()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L182)




### <a name="method-renderAssociationWrapperFooter"></a>renderAssociationWrapperFooter

    mixed WebserviceOutputXMLCore::renderAssociationWrapperFooter()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L186)




### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L38)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputXML.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L39)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**


