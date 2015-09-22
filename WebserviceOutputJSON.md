WebserviceOutputJSON
===============






* Class name: WebserviceOutputJSON
* This class is defined in [classes/webservice/WebserviceOutputJSON.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L28)
* This class implements: [WebserviceOutputInterface](WebserviceOutputInterface)




Properties
----------

* [$docUrl](#property-$docUrl)
* [$languages](#property-$languages)
* [$wsUrl](#property-$wsUrl)
* [$schemaToDisplay](#property-$schemaToDisplay)
* [$currentEntity](#property-$currentEntity)
* [$currentAssociatedEntity](#property-$currentAssociatedEntity)
* [$content](#property-$content)

Methods
-------
* [__construct](#method-__construct)
* [setSchemaToDisplay](#method-setSchemaToDisplay)
* [getSchemaToDisplay](#method-getSchemaToDisplay)
* [setWsUrl](#method-setWsUrl)
* [getWsUrl](#method-getWsUrl)
* [getContentType](#method-getContentType)
* [renderErrors](#method-renderErrors)
* [renderField](#method-renderField)
* [renderNodeHeader](#method-renderNodeHeader)
* [getNodeName](#method-getNodeName)
* [renderNodeFooter](#method-renderNodeFooter)
* [overrideContent](#method-overrideContent)
* [setLanguages](#method-setLanguages)
* [renderAssociationWrapperHeader](#method-renderAssociationWrapperHeader)
* [renderAssociationWrapperFooter](#method-renderAssociationWrapperFooter)
* [renderAssociationHeader](#method-renderAssociationHeader)
* [renderAssociationFooter](#method-renderAssociationFooter)
* [renderErrorsHeader](#method-renderErrorsHeader)
* [renderErrorsFooter](#method-renderErrorsFooter)
* [renderAssociationField](#method-renderAssociationField)
* [renderi18nField](#method-renderi18nField)




Properties
----------


### <a name="property-$docUrl"></a>$docUrl

    public mixed $docUrl = ''





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L30)


### <a name="property-$languages"></a>$languages

    public mixed $languages = array()





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L31)


### <a name="property-$wsUrl"></a>$wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L32)


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L33)


### <a name="property-$currentEntity"></a>$currentEntity

    protected mixed $currentEntity

Current entity



* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L38)


### <a name="property-$currentAssociatedEntity"></a>$currentAssociatedEntity

    protected mixed $currentAssociatedEntity

Current association



* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L43)


### <a name="property-$content"></a>$content

    protected mixed $content = array()

Json content



* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L48)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L29)


#### Arguments
* $languages **mixed**



### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L33)


#### Arguments
* $schema **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L34)




### <a name="method-setWsUrl"></a>setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L30)


#### Arguments
* $url **mixed**



### <a name="method-getWsUrl"></a>getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L31)




### <a name="method-getContentType"></a>getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L32)




### <a name="method-renderErrors"></a>renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L43)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderField"></a>renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L35)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L36)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### <a name="method-getNodeName"></a>getNodeName

    mixed WebserviceOutputJSON::getNodeName($params)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L130)


#### Arguments
* $params **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L37)


#### Arguments
* $obj **mixed**
* $params **mixed**



### <a name="method-overrideContent"></a>overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L40)


#### Arguments
* $content **mixed**



### <a name="method-setLanguages"></a>setLanguages

    mixed WebserviceOutputJSON::setLanguages($languages)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L168)


#### Arguments
* $languages **mixed**



### <a name="method-renderAssociationWrapperHeader"></a>renderAssociationWrapperHeader

    mixed WebserviceOutputJSON::renderAssociationWrapperHeader()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L174)




### <a name="method-renderAssociationWrapperFooter"></a>renderAssociationWrapperFooter

    mixed WebserviceOutputJSON::renderAssociationWrapperFooter()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L178)




### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L38)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L39)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L41)




### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L42)




### <a name="method-renderAssociationField"></a>renderAssociationField

    mixed WebserviceOutputJSON::renderAssociationField($field)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L198)


#### Arguments
* $field **mixed**



### <a name="method-renderi18nField"></a>renderi18nField

    mixed WebserviceOutputJSON::renderi18nField($field)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L202)


#### Arguments
* $field **mixed**


