WebserviceOutputJSON
===============






* Class name: WebserviceOutputJSON
* This class is defined in [classes/webservice/WebserviceOutputJSON.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L28)
* This class implements: [WebserviceOutputInterface](WebserviceOutputInterface)




Properties
----------


### $docUrl

    public mixed $docUrl = ''





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#30)


### $languages

    public mixed $languages = array()





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#31)


### $wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#32)


### $schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#33)


### $currentEntity

    protected mixed $currentEntity

Current entity



* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#38)


### $currentAssociatedEntity

    protected mixed $currentAssociatedEntity

Current association



* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#43)


### $content

    protected mixed $content = array()

Json content



* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputJSON.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#48)


Methods
-------


### __construct

    mixed WebserviceOutputInterface::__construct($languages)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#29)


#### Arguments
* $languages **mixed**



### setSchemaToDisplay

    mixed WebserviceOutputInterface::setSchemaToDisplay($schema)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#33)


#### Arguments
* $schema **mixed**



### getSchemaToDisplay

    mixed WebserviceOutputInterface::getSchemaToDisplay()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#34)




### setWsUrl

    mixed WebserviceOutputInterface::setWsUrl($url)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#30)


#### Arguments
* $url **mixed**



### getWsUrl

    mixed WebserviceOutputInterface::getWsUrl()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#31)




### getContentType

    mixed WebserviceOutputInterface::getContentType()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#32)




### renderErrors

    mixed WebserviceOutputInterface::renderErrors($message, $code)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#43)


#### Arguments
* $message **mixed**
* $code **mixed**



### renderField

    mixed WebserviceOutputInterface::renderField($field)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#35)


#### Arguments
* $field **mixed**



### renderNodeHeader

    mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#36)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### getNodeName

    mixed WebserviceOutputJSON::getNodeName($params)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#130)


#### Arguments
* $params **mixed**



### renderNodeFooter

    mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#37)


#### Arguments
* $obj **mixed**
* $params **mixed**



### overrideContent

    mixed WebserviceOutputInterface::overrideContent($content)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#40)


#### Arguments
* $content **mixed**



### setLanguages

    mixed WebserviceOutputJSON::setLanguages($languages)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#168)


#### Arguments
* $languages **mixed**



### renderAssociationWrapperHeader

    mixed WebserviceOutputJSON::renderAssociationWrapperHeader()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#174)




### renderAssociationWrapperFooter

    mixed WebserviceOutputJSON::renderAssociationWrapperFooter()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#178)




### renderAssociationHeader

    mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#38)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### renderAssociationFooter

    mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#39)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### renderErrorsHeader

    mixed WebserviceOutputInterface::renderErrorsHeader()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#41)




### renderErrorsFooter

    mixed WebserviceOutputInterface::renderErrorsFooter()





* Visibility: **public**
* This method is defined by [WebserviceOutputInterface](WebserviceOutputInterface)
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#42)




### renderAssociationField

    mixed WebserviceOutputJSON::renderAssociationField($field)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#198)


#### Arguments
* $field **mixed**



### renderi18nField

    mixed WebserviceOutputJSON::renderi18nField($field)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputJSON.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#202)


#### Arguments
* $field **mixed**


