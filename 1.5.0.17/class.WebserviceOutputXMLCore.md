Class WebserviceOutputXMLCore
=====================





* Class name: WebserviceOutputXMLCore
* Source: [classes/webservice/WebserviceOutputXML.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L28)
* This class implements: [WebserviceOutputInterface](interface.WebserviceOutputInterface.md)

Contents
--------


### Properties

* [$docUrl](#property-$docUrl)
* [$languages](#property-$languages)
* [$schemaToDisplay](#property-$schemaToDisplay)
* [$wsUrl](#property-$wsUrl)

### Methods

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

```php
public mixed $docUrl = ''
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L30).


### <a name="property-$languages"></a>$languages

```php
public mixed $languages = array()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L31).


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

```php
protected mixed $schemaToDisplay
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputXML.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L33).


### <a name="property-$wsUrl"></a>$wsUrl

```php
protected mixed $wsUrl
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputXML.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed WebserviceOutputXMLCore::__construct($languages)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L60)


#### Arguments
* $languages **mixed**



### <a name="method-getContentType"></a>getContentType

```php
mixed WebserviceOutputXMLCore::getContentType()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L56)




### <a name="method-getNodeName"></a>getNodeName

```php
mixed WebserviceOutputXMLCore::getNodeName($params)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L155)


#### Arguments
* $params **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

```php
mixed WebserviceOutputXMLCore::getSchemaToDisplay()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L42)




### <a name="method-getWsUrl"></a>getWsUrl

```php
mixed WebserviceOutputXMLCore::getWsUrl()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L52)




### <a name="method-overrideContent"></a>overrideContent

```php
mixed WebserviceOutputXMLCore::overrideContent($content)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L166)


#### Arguments
* $content **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

```php
mixed WebserviceOutputXMLCore::renderAssociationFooter($obj, $params, $assoc_name)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L193)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

```php
mixed WebserviceOutputXMLCore::renderAssociationHeader($obj, $params, $assoc_name, $closed_tags)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L182)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**
* $closed_tags **mixed**



### <a name="method-renderAssociationWrapperFooter"></a>renderAssociationWrapperFooter

```php
mixed WebserviceOutputXMLCore::renderAssociationWrapperFooter()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L178)




### <a name="method-renderAssociationWrapperHeader"></a>renderAssociationWrapperHeader

```php
mixed WebserviceOutputXMLCore::renderAssociationWrapperHeader()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L174)




### <a name="method-renderErrors"></a>renderErrors

```php
mixed WebserviceOutputXMLCore::renderErrors($message, $code)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L77)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

```php
mixed WebserviceOutputXMLCore::renderErrorsFooter()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L73)




### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

```php
mixed WebserviceOutputXMLCore::renderErrorsHeader()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L69)




### <a name="method-renderField"></a>renderField

```php
mixed WebserviceOutputXMLCore::renderField($field)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L86)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

```php
mixed WebserviceOutputXMLCore::renderNodeFooter($node_name, $params)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L162)


#### Arguments
* $node_name **mixed**
* $params **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

```php
mixed WebserviceOutputXMLCore::renderNodeHeader($node_name, $params, $more_attr, $has_child)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L139)


#### Arguments
* $node_name **mixed**
* $params **mixed**
* $more_attr **mixed**
* $has_child **mixed**



### <a name="method-setLanguages"></a>setLanguages

```php
mixed WebserviceOutputXMLCore::setLanguages($languages)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L64)


#### Arguments
* $languages **mixed**



### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

```php
mixed WebserviceOutputXMLCore::setSchemaToDisplay($schema)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L35)


#### Arguments
* $schema **mixed**



### <a name="method-setWsUrl"></a>setWsUrl

```php
mixed WebserviceOutputXMLCore::setWsUrl($url)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/webservice/WebserviceOutputXML.php#L47)


#### Arguments
* $url **mixed**


