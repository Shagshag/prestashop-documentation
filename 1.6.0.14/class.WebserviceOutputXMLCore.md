Class WebserviceOutputXMLCore
=====================





* Class name: WebserviceOutputXMLCore
* Source: [classes/webservice/WebserviceOutputXML.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L27)
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
* Source: [classes/webservice/WebserviceOutputXML.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L29).


### <a name="property-$languages"></a>$languages

```php
public mixed $languages = array()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L30).


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

```php
protected mixed $schemaToDisplay
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputXML.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L32).


### <a name="property-$wsUrl"></a>$wsUrl

```php
protected mixed $wsUrl
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputXML.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed WebserviceOutputXMLCore::__construct($languages)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L59)


#### Arguments
* $languages **mixed**



### <a name="method-getContentType"></a>getContentType

```php
mixed WebserviceOutputXMLCore::getContentType()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L55)




### <a name="method-getNodeName"></a>getNodeName

```php
mixed WebserviceOutputXMLCore::getNodeName($params)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L161)


#### Arguments
* $params **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

```php
mixed WebserviceOutputXMLCore::getSchemaToDisplay()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L41)




### <a name="method-getWsUrl"></a>getWsUrl

```php
mixed WebserviceOutputXMLCore::getWsUrl()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L51)




### <a name="method-overrideContent"></a>overrideContent

```php
mixed WebserviceOutputXMLCore::overrideContent($content)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L172)


#### Arguments
* $content **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

```php
mixed WebserviceOutputXMLCore::renderAssociationFooter($obj, $params, $assoc_name)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L211)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

```php
mixed WebserviceOutputXMLCore::renderAssociationHeader($obj, $params, $assoc_name, $closed_tags)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L188)


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
* Source: [classes/webservice/WebserviceOutputXML.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L184)




### <a name="method-renderAssociationWrapperHeader"></a>renderAssociationWrapperHeader

```php
mixed WebserviceOutputXMLCore::renderAssociationWrapperHeader()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L180)




### <a name="method-renderErrors"></a>renderErrors

```php
mixed WebserviceOutputXMLCore::renderErrors($message, $code)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L76)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

```php
mixed WebserviceOutputXMLCore::renderErrorsFooter()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L72)




### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

```php
mixed WebserviceOutputXMLCore::renderErrorsHeader()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L68)




### <a name="method-renderField"></a>renderField

```php
mixed WebserviceOutputXMLCore::renderField($field)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L85)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

```php
mixed WebserviceOutputXMLCore::renderNodeFooter($node_name, $params)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L168)


#### Arguments
* $node_name **mixed**
* $params **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

```php
mixed WebserviceOutputXMLCore::renderNodeHeader($node_name, $params, $more_attr, $has_child)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L145)


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
* Source: [classes/webservice/WebserviceOutputXML.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L63)


#### Arguments
* $languages **mixed**



### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

```php
mixed WebserviceOutputXMLCore::setSchemaToDisplay($schema)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L34)


#### Arguments
* $schema **mixed**



### <a name="method-setWsUrl"></a>setWsUrl

```php
mixed WebserviceOutputXMLCore::setWsUrl($url)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputXML.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceOutputXML.php#L46)


#### Arguments
* $url **mixed**


