Class AdminAddressesControllerCore
=====================





* Class name: AdminAddressesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAddressesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L30)


Contents
--------


### Properties

* [$countries_array](#property-$countries_array)
* [$object](#property-$object)

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
* Source: [controllers/admin/AdminAddressesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L33).


### <a name="property-$object"></a>$object

```php
public \Address $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminAddressesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L35)




### <a name="method-ajaxProcess"></a>ajaxProcess

```php
mixed AdminAddressesControllerCore::ajaxProcess()
```

Method called when an ajax request is made



* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L485)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminAddressesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L97)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminAddressesControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L86)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminAddressesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 441](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L441)




### <a name="method-processAddressFormat"></a>processAddressFormat

```php
array AdminAddressesControllerCore::processAddressFormat()
```

Get Address formats used by the country where the address id retrieved from POST/GET is.



* Visibility: **protected**
* Source: [controllers/admin/AdminAddressesController.php line 454](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L454)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminAddressesControllerCore::processBulkDelete()
```

Delete multiple items



* Visibility: **protected**
* Source: [controllers/admin/AdminAddressesController.php line 520](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L520)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminAddressesControllerCore::processDelete()
```

Object Delete



* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 503](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L503)




### <a name="method-processSave"></a>processSave

```php
mixed AdminAddressesControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L354)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminAddressesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAddressesController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAddressesController.php#L109)



