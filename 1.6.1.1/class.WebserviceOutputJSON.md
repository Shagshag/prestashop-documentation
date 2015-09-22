Class WebserviceOutputJSON
=====================





* Class name: WebserviceOutputJSON
* Source: [classes/webservice/WebserviceOutputJSON.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L28)
* This class implements: [WebserviceOutputInterface](interface.WebserviceOutputInterface.md)


Properties
----------

* [$content](#property-$content)
* [$currentAssociatedEntity](#property-$currentAssociatedEntity)
* [$currentEntity](#property-$currentEntity)
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
* [renderAssociationField](#method-renderAssociationField)
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
* [renderi18nField](#method-renderi18nField)
* [setLanguages](#method-setLanguages)
* [setSchemaToDisplay](#method-setSchemaToDisplay)
* [setWsUrl](#method-setWsUrl)




Properties
----------


### <a name="property-$content"></a>$content

    protected mixed $content = array()

Json content



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L48).


### <a name="property-$currentAssociatedEntity"></a>$currentAssociatedEntity

    protected mixed $currentAssociatedEntity

Current association



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L43).


### <a name="property-$currentEntity"></a>$currentEntity

    protected mixed $currentEntity

Current entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L38).


### <a name="property-$docUrl"></a>$docUrl

    public mixed $docUrl = ''





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L30).


### <a name="property-$languages"></a>$languages

    public mixed $languages = array()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L31).


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L33).


### <a name="property-$wsUrl"></a>$wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed WebserviceOutputJSON::__construct($languages)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L50)


#### Arguments
* $languages **mixed**



### <a name="method-getContentType"></a>getContentType

    mixed WebserviceOutputJSON::getContentType()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L79)




### <a name="method-getNodeName"></a>getNodeName

    mixed WebserviceOutputJSON::getNodeName($params)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L130)


#### Arguments
* $params **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

    mixed WebserviceOutputJSON::getSchemaToDisplay()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L63)




### <a name="method-getWsUrl"></a>getWsUrl

    mixed WebserviceOutputJSON::getWsUrl()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L74)




### <a name="method-overrideContent"></a>overrideContent

    mixed WebserviceOutputJSON::overrideContent($content)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L160)


#### Arguments
* $content **mixed**



### <a name="method-renderAssociationField"></a>renderAssociationField

    mixed WebserviceOutputJSON::renderAssociationField($field)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L198)


#### Arguments
* $field **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

    mixed WebserviceOutputJSON::renderAssociationFooter($obj, $params, $assoc_name)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L186)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

    mixed WebserviceOutputJSON::renderAssociationHeader($obj, $params, $assoc_name, $closed_tags)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L182)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**
* $closed_tags **mixed**



### <a name="method-renderAssociationWrapperFooter"></a>renderAssociationWrapperFooter

    mixed WebserviceOutputJSON::renderAssociationWrapperFooter()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L178)




### <a name="method-renderAssociationWrapperHeader"></a>renderAssociationWrapperHeader

    mixed WebserviceOutputJSON::renderAssociationWrapperHeader()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L174)




### <a name="method-renderErrors"></a>renderErrors

    mixed WebserviceOutputJSON::renderErrors($message, $code)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L84)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

    mixed WebserviceOutputJSON::renderErrorsFooter()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L194)




### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

    mixed WebserviceOutputJSON::renderErrorsHeader()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L190)




### <a name="method-renderField"></a>renderField

    mixed WebserviceOutputJSON::renderField($field)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L90)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

    mixed WebserviceOutputJSON::renderNodeFooter($node_name, $params)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L139)


#### Arguments
* $node_name **mixed**
* $params **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

    mixed WebserviceOutputJSON::renderNodeHeader($node_name, $params, $more_attr, $has_child)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L114)


#### Arguments
* $node_name **mixed**
* $params **mixed**
* $more_attr **mixed**
* $has_child **mixed**



### <a name="method-renderi18nField"></a>renderi18nField

    mixed WebserviceOutputJSON::renderi18nField($field)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L202)


#### Arguments
* $field **mixed**



### <a name="method-setLanguages"></a>setLanguages

    mixed WebserviceOutputJSON::setLanguages($languages)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L168)


#### Arguments
* $languages **mixed**



### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

    mixed WebserviceOutputJSON::setSchemaToDisplay($schema)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L55)


#### Arguments
* $schema **mixed**



### <a name="method-setWsUrl"></a>setWsUrl

    mixed WebserviceOutputJSON::setWsUrl($url)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputJSON.php#L68)


#### Arguments
* $url **mixed**


