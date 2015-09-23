Interface WebserviceOutputInterface
=========================





* Interface name: WebserviceOutputInterface
* This is an **interface**
* Source: [classes/webservice/WebserviceOutputInterface.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L27)

Contents
--------



### Methods

* [__construct](#method-__construct)
* [getContentType](#method-getContentType)
* [getSchemaToDisplay](#method-getSchemaToDisplay)
* [getWsUrl](#method-getWsUrl)
* [overrideContent](#method-overrideContent)
* [renderAssociationFooter](#method-renderAssociationFooter)
* [renderAssociationHeader](#method-renderAssociationHeader)
* [renderErrors](#method-renderErrors)
* [renderErrorsFooter](#method-renderErrorsFooter)
* [renderErrorsHeader](#method-renderErrorsHeader)
* [renderField](#method-renderField)
* [renderNodeFooter](#method-renderNodeFooter)
* [renderNodeHeader](#method-renderNodeHeader)
* [setSchemaToDisplay](#method-setSchemaToDisplay)
* [setWsUrl](#method-setWsUrl)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed WebserviceOutputInterface::__construct($languages)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L29)


#### Arguments
* $languages **mixed**



### <a name="method-getContentType"></a>getContentType

```php
mixed WebserviceOutputInterface::getContentType()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L32)




### <a name="method-getSchemaToDisplay"></a>getSchemaToDisplay

```php
mixed WebserviceOutputInterface::getSchemaToDisplay()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L34)




### <a name="method-getWsUrl"></a>getWsUrl

```php
mixed WebserviceOutputInterface::getWsUrl()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L31)




### <a name="method-overrideContent"></a>overrideContent

```php
mixed WebserviceOutputInterface::overrideContent($content)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L40)


#### Arguments
* $content **mixed**



### <a name="method-renderAssociationFooter"></a>renderAssociationFooter

```php
mixed WebserviceOutputInterface::renderAssociationFooter($obj, $params, $assoc_name)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L39)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderAssociationHeader"></a>renderAssociationHeader

```php
mixed WebserviceOutputInterface::renderAssociationHeader($obj, $params, $assoc_name)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L38)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $assoc_name **mixed**



### <a name="method-renderErrors"></a>renderErrors

```php
mixed WebserviceOutputInterface::renderErrors($message, $code)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L43)


#### Arguments
* $message **mixed**
* $code **mixed**



### <a name="method-renderErrorsFooter"></a>renderErrorsFooter

```php
mixed WebserviceOutputInterface::renderErrorsFooter()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L42)




### <a name="method-renderErrorsHeader"></a>renderErrorsHeader

```php
mixed WebserviceOutputInterface::renderErrorsHeader()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L41)




### <a name="method-renderField"></a>renderField

```php
mixed WebserviceOutputInterface::renderField($field)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L35)


#### Arguments
* $field **mixed**



### <a name="method-renderNodeFooter"></a>renderNodeFooter

```php
mixed WebserviceOutputInterface::renderNodeFooter($obj, $params)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L37)


#### Arguments
* $obj **mixed**
* $params **mixed**



### <a name="method-renderNodeHeader"></a>renderNodeHeader

```php
mixed WebserviceOutputInterface::renderNodeHeader($obj, $params, $more_attr)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L36)


#### Arguments
* $obj **mixed**
* $params **mixed**
* $more_attr **mixed**



### <a name="method-setSchemaToDisplay"></a>setSchemaToDisplay

```php
mixed WebserviceOutputInterface::setSchemaToDisplay($schema)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L33)


#### Arguments
* $schema **mixed**



### <a name="method-setWsUrl"></a>setWsUrl

```php
mixed WebserviceOutputInterface::setWsUrl($url)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputInterface.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceOutputInterface.php#L30)


#### Arguments
* $url **mixed**


