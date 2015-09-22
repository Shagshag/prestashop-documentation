Class WebserviceOutputXMLCore
=====================





* Class name: WebserviceOutputXMLCore
* Source: [classes/webservice/WebserviceOutputXML.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L27)
* This class implements: [WebserviceOutputInterface](interface.WebserviceOutputInterface)


Properties
----------

* [$docUrl](#property-$docUrl)
* [$languages](#property-$languages)
* [$schemaToDisplay](#property-$schemaToDisplay)
* [$wsUrl](#property-$wsUrl)

Methods
-------
* [__construct](#method-__construct)
* [getContentType](#method-getContentType)
* [getNodeName](#method-getNodeName)
* [getSchemaToDisplay](#method-getSchemaToDisplay)
* [getWsUrl](#method-getWsUrl)
* [overrideContent](#method-overrideContent)
* [renderAssociationFooter](#method-renderAssociationFooter)
* [renderAssociationHeader](#method-renderAssociationHeader)
* [renderAssociationWrapperFooter](#method-renderAssociationWrapperFooter)
* [renderAssociationWrapperHeader](#method-renderAssociationWrapperHeader)
* [renderErrors](#method-renderErrors)
* [renderErrorsFooter](#method-renderErrorsFooter)
* [renderErrorsHeader](#method-renderErrorsHeader)
* [renderField](#method-renderField)
* [renderNodeFooter](#method-renderNodeFooter)
* [renderNodeHeader](#method-renderNodeHeader)
* [setLanguages](#method-setLanguages)
* [setSchemaToDisplay](#method-setSchemaToDisplay)
* [setWsUrl](#method-setWsUrl)




Properties
----------


### <a name="property-$docUrl"></a>$docUrl

    public mixed $docUrl = ''





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L29)


### <a name="property-$languages"></a>$languages

    public mixed $languages = array()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L30)


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputXML.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L32)


### <a name="property-$wsUrl"></a>$wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputXML.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L31)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed WebserviceOutputXMLCore::__construct($languages)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L60)


#### Arguments
* $languages **mixed**



### <a name="method-getContentType"></a>getContentType

    mixed WebserviceOutputXMLCore::getContentType()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L56)




### <a name="method-getNodeName"></a>getNodeName

    mixed WebserviceOutputXMLCore::getNodeName($params)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L162)


#### Arguments
* $params **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

    mixed WebserviceOutputXMLCore::getSchemaToDisplay()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L42)




### <a name="method-getWsUrl"></a>getWsUrl

    mixed WebserviceOutputXMLCore::getWsUrl()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L52)




### <a name="method-overrideContent"></a>overrideContent

    mixed WebserviceOutputXMLCore::overrideContent($content)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L174)


#### Arguments
* $content **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

    mixed WebserviceOutputXMLCore::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L211)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

    mixed WebserviceOutputXMLCore::renderAssociationHeader($obj, $params, $assoc_name, $closed_tags)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L190)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**
* $closed_tags **mixed**



### <a name="method-renderAssociationWrapperFooter"></a>renderAssociationWrapperFooter

    mixed WebserviceOutputXMLCore::renderAssociationWrapperFooter()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L186)




### <a name="method-renderAssociationWrapperHeader"></a>renderAssociationWrapperHeader

    mixed WebserviceOutputXMLCore::renderAssociationWrapperHeader()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L182)




### <a name="method-renderErrors"></a>renderErrors

    mixed WebserviceOutputXMLCore::renderErrors($message, $code)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L77)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

    mixed WebserviceOutputXMLCore::renderErrorsFooter()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L73)




### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

    mixed WebserviceOutputXMLCore::renderErrorsHeader()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L69)




### <a name="method-renderField"></a>renderField

    mixed WebserviceOutputXMLCore::renderField($field)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L87)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

    mixed WebserviceOutputXMLCore::renderNodeFooter($node_name, $params)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L170)


#### Arguments
* $node_name **mixed**
* $params **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

    mixed WebserviceOutputXMLCore::renderNodeHeader($node_name, $params, $more_attr, $has_child)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L147)


#### Arguments
* $node_name **mixed**
* $params **mixed**
* $more_attr **mixed**
* $has_child **mixed**



### <a name="method-setLanguages"></a>setLanguages

    mixed WebserviceOutputXMLCore::setLanguages($languages)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L64)


#### Arguments
* $languages **mixed**



### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

    mixed WebserviceOutputXMLCore::setSchemaToDisplay($schema)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L34)


#### Arguments
* $schema **mixed**



### <a name="method-setWsUrl"></a>setWsUrl

    mixed WebserviceOutputXMLCore::setWsUrl($url)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputXML.php#L47)


#### Arguments
* $url **mixed**


