Interface WebserviceSpecificManagementInterface
=========================





* Interface name: WebserviceSpecificManagementInterface
* This is an **interface**
* Source: [classes/webservice/WebserviceSpecificManagementInterface.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementInterface.php#L28)

Contents
--------



### Methods

* [getContent](#method-getContent)
* [getObjectOutput](#method-getObjectOutput)
* [getWsObject](#method-getWsObject)
* [manage](#method-manage)
* [setObjectOutput](#method-setObjectOutput)
* [setWsObject](#method-setWsObject)






Methods
-------


### <a name="method-getContent"></a>getContent

```php
array WebserviceSpecificManagementInterface::getContent()
```

This must be return an array with specific values as WebserviceRequest expects.



* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementInterface.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementInterface.php#L42)




### <a name="method-getObjectOutput"></a>getObjectOutput

```php
mixed WebserviceSpecificManagementInterface::getObjectOutput()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementInterface.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementInterface.php#L31)




### <a name="method-getWsObject"></a>getWsObject

```php
mixed WebserviceSpecificManagementInterface::getWsObject()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementInterface.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementInterface.php#L33)




### <a name="method-manage"></a>manage

```php
mixed WebserviceSpecificManagementInterface::manage()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementInterface.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementInterface.php#L35)




### <a name="method-setObjectOutput"></a>setObjectOutput

```php
mixed WebserviceSpecificManagementInterface::setObjectOutput(\WebserviceOutputBuilderCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementInterface.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementInterface.php#L30)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](class.WebserviceOutputBuilderCore.md)**



### <a name="method-setWsObject"></a>setWsObject

```php
mixed WebserviceSpecificManagementInterface::setWsObject(\WebserviceRequestCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementInterface.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementInterface.php#L32)


#### Arguments
* $obj **[WebserviceRequestCore](class.WebserviceRequestCore.md)**


