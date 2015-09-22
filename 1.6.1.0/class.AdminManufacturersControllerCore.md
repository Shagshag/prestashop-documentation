Class AdminManufacturersControllerCore
=====================





* Class name: AdminManufacturersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminManufacturersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L30)


Contents
--------


### Properties

* [$bootstrap](#property-$bootstrap)
* [$countries_array](#property-$countries_array)
* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [afterImageUpload](#method-afterImageUpload)
* [beforeDelete](#method-beforeDelete)
* [displayEditaddressesLink](#method-displayEditaddressesLink)
* [getAddressFieldsList](#method-getAddressFieldsList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initListManufacturer](#method-initListManufacturer)
* [initListManufacturerAddresses](#method-initListManufacturerAddresses)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [processExport](#method-processExport)
* [processSave](#method-processSave)
* [renderForm](#method-renderForm)
* [renderFormAddress](#method-renderFormAddress)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L32).


### <a name="property-$countries_array"></a>$countries_array

```php
protected array $countries_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L34).


### <a name="property-$object"></a>$object

```php
public \Manufacturer $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminManufacturersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L36)




### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminManufacturersControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L815)




### <a name="method-beforeDelete"></a>beforeDelete

```php
mixed AdminManufacturersControllerCore::beforeDelete($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L857)


#### Arguments
* $object **mixed**



### <a name="method-displayEditaddressesLink"></a>displayEditaddressesLink

```php
string AdminManufacturersControllerCore::displayEditaddressesLink(string $token, integer $id)
```

Display editaddresses action link



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L284)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getAddressFieldsList"></a>getAddressFieldsList

```php
mixed AdminManufacturersControllerCore::getAddressFieldsList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L164)




### <a name="method-init"></a>init

```php
mixed AdminManufacturersControllerCore::init()
```

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 786](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L786)




### <a name="method-initContent"></a>initContent

```php
mixed AdminManufacturersControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L746)




### <a name="method-initListManufacturer"></a>initListManufacturer

```php
mixed AdminManufacturersControllerCore::initListManufacturer()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L143)




### <a name="method-initListManufacturerAddresses"></a>initListManufacturerAddresses

```php
mixed AdminManufacturersControllerCore::initListManufacturerAddresses()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L216)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminManufacturersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L110)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminManufacturersControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L802)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminManufacturersControllerCore::initToolbar()
```

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L647)




### <a name="method-processExport"></a>processExport

```php
mixed AdminManufacturersControllerCore::processExport($text_delimiter)
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L205)


#### Arguments
* $text_delimiter **mixed**



### <a name="method-processSave"></a>processSave

```php
mixed AdminManufacturersControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 862](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L862)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminManufacturersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L299)




### <a name="method-renderFormAddress"></a>renderFormAddress

```php
mixed AdminManufacturersControllerCore::renderFormAddress()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L440)




### <a name="method-renderList"></a>renderList

```php
mixed AdminManufacturersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L272)




### <a name="method-renderView"></a>renderView

```php
mixed AdminManufacturersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L683)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminManufacturersControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminManufacturersController.php#L103)



