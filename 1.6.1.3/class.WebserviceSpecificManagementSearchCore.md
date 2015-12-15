Class WebserviceSpecificManagementSearchCore
=====================





* Class name: WebserviceSpecificManagementSearchCore
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L27)
* This class implements: [WebserviceSpecificManagementInterface](interface.WebserviceSpecificManagementInterface.md)

Contents
--------


### Properties

* [$objOutput](#property-$objOutput)
* [$output](#property-$output)
* [$wsObject](#property-$wsObject)

### Methods

* [getContent](#method-getContent)
* [getObjectOutput](#method-getObjectOutput)
* [getUrlSegment](#method-getUrlSegment)
* [getWsObject](#method-getWsObject)
* [manage](#method-manage)
* [setObjectOutput](#method-setObjectOutput)
* [setUrlSegment](#method-setUrlSegment)
* [setWsObject](#method-setWsObject)




Properties
----------


### <a name="property-$objOutput"></a>$objOutput

```php
protected \WebserviceOutputBuilder $objOutput
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L30).


### <a name="property-$output"></a>$output

```php
protected mixed $output
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L31).


### <a name="property-$wsObject"></a>$wsObject

```php
protected \WebserviceRequest $wsObject
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L34).


Methods
-------


### <a name="method-getContent"></a>getContent

```php
string WebserviceSpecificManagementSearchCore::getContent()
```

This must be return a string with specific values as WebserviceRequest expects.



* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L127)




### <a name="method-getObjectOutput"></a>getObjectOutput

```php
mixed WebserviceSpecificManagementSearchCore::getObjectOutput()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L60)




### <a name="method-getUrlSegment"></a>getUrlSegment

```php
mixed WebserviceSpecificManagementSearchCore::getUrlSegment()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L71)




### <a name="method-getWsObject"></a>getWsObject

```php
mixed WebserviceSpecificManagementSearchCore::getWsObject()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L56)




### <a name="method-manage"></a>manage

```php
mixed WebserviceSpecificManagementSearchCore::manage()
```

Management of search



* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L80)




### <a name="method-setObjectOutput"></a>setObjectOutput

```php
\WebserviceSpecificManagementInterface WebserviceSpecificManagementSearchCore::setObjectOutput(\WebserviceOutputBuilderCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L44)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](class.WebserviceOutputBuilderCore.md)**



### <a name="method-setUrlSegment"></a>setUrlSegment

```php
mixed WebserviceSpecificManagementSearchCore::setUrlSegment($segments)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L65)


#### Arguments
* $segments **mixed**



### <a name="method-setWsObject"></a>setWsObject

```php
mixed WebserviceSpecificManagementSearchCore::setWsObject(\WebserviceRequestCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementSearch.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/webservice/WebserviceSpecificManagementSearch.php#L50)


#### Arguments
* $obj **[WebserviceRequestCore](class.WebserviceRequestCore.md)**


