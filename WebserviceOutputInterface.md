WebserviceOutputInterface
===============






* Interface name: WebserviceOutputInterface
* This is an **interface**
* This interface is defined in [classes/webservice/WebserviceOutputInterface.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L27)






Methods
-------
* [__construct](#method-__construct)
* [setWsUrl](#method-setWsUrl)
* [getWsUrl](#method-getWsUrl)
* [getContentType](#method-getContentType)
* [setSchemaToDisplay](#method-setSchemaToDisplay)
* [getSchemaToDisplay](#method-getSchemaToDisplay)
* [renderField](#method-renderField)
* [renderNodeHeader](#method-renderNodeHeader)
* [renderNodeFooter](#method-renderNodeFooter)
* [renderAssociationHeader](#method-renderAssociationHeader)
* [renderAssociationFooter](#method-renderAssociationFooter)
* [overrideContent](#method-overrideContent)
* [renderErrorsHeader](#method-renderErrorsHeader)
* [renderErrorsFooter](#method-renderErrorsFooter)
* [renderErrors](#method-renderErrors)






Methods
-------


### <a name="method-__construct"></a>__construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L29)


#### Arguments
* $languages **mixed**



### <a name="method-setWsUrl"></a>setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L30)


#### Arguments
* $url **mixed**



### <a name="method-getWsUrl"></a>getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L31)




### <a name="method-getContentType"></a>getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L32)




### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L33)


#### Arguments
* $schema **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L34)




### <a name="method-renderField"></a>renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L35)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L36)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L37)


#### Arguments
* $obj **mixed**
* $params **mixed**



### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L38)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L39)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-overrideContent"></a>overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L40)


#### Arguments
* $content **mixed**



### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L41)




### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L42)




### <a name="method-renderErrors"></a>renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputInterface.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputInterface.php#L43)


#### Arguments
* $message **mixed**
* $code **mixed**


