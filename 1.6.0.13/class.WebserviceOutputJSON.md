Class WebserviceOutputJSON
=====================





* Class name: WebserviceOutputJSON
* Source: [classes/webservice/WebserviceOutputJSON.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L28)
* This class implements: [WebserviceOutputInterface](interface.WebserviceOutputInterface.md)

Contents
--------


### Properties

* [$content](#property-$content)
* [$currentAssociatedEntity](#property-$currentAssociatedEntity)
* [$currentEntity](#property-$currentEntity)
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

```php
protected mixed $content = array()
```

Json content



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L48).


### <a name="property-$currentAssociatedEntity"></a>$currentAssociatedEntity

```php
protected mixed $currentAssociatedEntity
```

Current association



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L43).


### <a name="property-$currentEntity"></a>$currentEntity

```php
protected mixed $currentEntity
```

Current entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L38).


### <a name="property-$docUrl"></a>$docUrl

```php
public mixed $docUrl = ''
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L30).


### <a name="property-$languages"></a>$languages

```php
public mixed $languages = array()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L31).


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

```php
protected mixed $schemaToDisplay
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L33).


### <a name="property-$wsUrl"></a>$wsUrl

```php
protected mixed $wsUrl
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputJSON.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed WebserviceOutputJSON::__construct($languages)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L50)


#### Arguments
* $languages **mixed**



### <a name="method-getContentType"></a>getContentType

```php
mixed WebserviceOutputJSON::getContentType()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L78)




### <a name="method-getNodeName"></a>getNodeName

```php
mixed WebserviceOutputJSON::getNodeName($params)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L133)


#### Arguments
* $params **mixed**



### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

```php
mixed WebserviceOutputJSON::getSchemaToDisplay()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L62)




### <a name="method-getWsUrl"></a>getWsUrl

```php
mixed WebserviceOutputJSON::getWsUrl()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L73)




### <a name="method-overrideContent"></a>overrideContent

```php
mixed WebserviceOutputJSON::overrideContent($content)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L162)


#### Arguments
* $content **mixed**



### <a name="method-renderAssociationField"></a>renderAssociationField

```php
mixed WebserviceOutputJSON::renderAssociationField($field)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L182)


#### Arguments
* $field **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

```php
mixed WebserviceOutputJSON::renderAssociationFooter($obj, $params, $assoc_name)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L179)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

```php
mixed WebserviceOutputJSON::renderAssociationHeader($obj, $params, $assoc_name, $closed_tags)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L178)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**
* $closed_tags **mixed**



### <a name="method-renderAssociationWrapperFooter"></a>renderAssociationWrapperFooter

```php
mixed WebserviceOutputJSON::renderAssociationWrapperFooter()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L177)




### <a name="method-renderAssociationWrapperHeader"></a>renderAssociationWrapperHeader

```php
mixed WebserviceOutputJSON::renderAssociationWrapperHeader()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L176)




### <a name="method-renderErrors"></a>renderErrors

```php
mixed WebserviceOutputJSON::renderErrors($message, $code)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L84)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

```php
mixed WebserviceOutputJSON::renderErrorsFooter()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L181)




### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

```php
mixed WebserviceOutputJSON::renderErrorsHeader()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L180)




### <a name="method-renderField"></a>renderField

```php
mixed WebserviceOutputJSON::renderField($field)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L90)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

```php
mixed WebserviceOutputJSON::renderNodeFooter($node_name, $params)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L141)


#### Arguments
* $node_name **mixed**
* $params **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

```php
mixed WebserviceOutputJSON::renderNodeHeader($node_name, $params, $more_attr, $has_child)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L116)


#### Arguments
* $node_name **mixed**
* $params **mixed**
* $more_attr **mixed**
* $has_child **mixed**



### <a name="method-renderi18nField"></a>renderi18nField

```php
mixed WebserviceOutputJSON::renderi18nField($field)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L183)


#### Arguments
* $field **mixed**



### <a name="method-setLanguages"></a>setLanguages

```php
mixed WebserviceOutputJSON::setLanguages($languages)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L170)


#### Arguments
* $languages **mixed**



### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

```php
mixed WebserviceOutputJSON::setSchemaToDisplay($schema)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L55)


#### Arguments
* $schema **mixed**



### <a name="method-setWsUrl"></a>setWsUrl

```php
mixed WebserviceOutputJSON::setWsUrl($url)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputJSON.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceOutputJSON.php#L67)


#### Arguments
* $url **mixed**


