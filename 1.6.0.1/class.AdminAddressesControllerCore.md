Class AdminAddressesControllerCore
=====================





* Class name: AdminAddressesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAddressesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L27)


Contents
--------


### Properties

* [$countries_array](#property-$countries_array)

### Methods

* [__construct](#method-__construct)
* [ajaxProcess](#method-ajaxProcess)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [processAdd](#method-processAdd)
* [processAddressFormat](#method-processAddressFormat)
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processSave](#method-processSave)
* [renderForm](#method-renderForm)




Properties
----------


### <a name="property-$countries_array"></a>$countries_array

```php
protected array $countries_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAddressesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminAddressesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L32)




### <a name="method-ajaxProcess"></a>ajaxProcess

```php
mixed AdminAddressesControllerCore::ajaxProcess()
```

Method called when an ajax request is made



* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L440)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminAddressesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L86)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminAddressesControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L76)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminAddressesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L396)




### <a name="method-processAddressFormat"></a>processAddressFormat

```php
array AdminAddressesControllerCore::processAddressFormat()
```

Get Address formats used by the country where the address id retrieved from POST/GET is.



* Visibility: **protected**
* Source: [controllers/admin/AdminAddressesController.php line 409](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L409)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminAddressesControllerCore::processBulkDelete()
```

Delete multiple items



* Visibility: **protected**
* Source: [controllers/admin/AdminAddressesController.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L472)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminAddressesControllerCore::processDelete()
```

Object Delete



* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L458)




### <a name="method-processSave"></a>processSave

```php
mixed AdminAddressesControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L315)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminAddressesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminAddressesController.php#L98)



