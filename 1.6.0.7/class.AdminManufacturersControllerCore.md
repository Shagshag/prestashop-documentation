Class AdminManufacturersControllerCore
=====================





* Class name: AdminManufacturersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminManufacturersController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L27)


Contents
--------


### Properties

* [$bootstrap](#property-$bootstrap)
* [$countries_array](#property-$countries_array)

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
* Source: [controllers/admin/AdminManufacturersController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L29).


### <a name="property-$countries_array"></a>$countries_array

```php
protected array $countries_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminManufacturersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L33)




### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminManufacturersControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L805)




### <a name="method-beforeDelete"></a>beforeDelete

```php
mixed AdminManufacturersControllerCore::beforeDelete($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L838)


#### Arguments
* $object **mixed**



### <a name="method-displayEditaddressesLink"></a>displayEditaddressesLink

```php
string AdminManufacturersControllerCore::displayEditaddressesLink(string $token, integer $id)
```

Display editaddresses action link



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L278)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getAddressFieldsList"></a>getAddressFieldsList

```php
mixed AdminManufacturersControllerCore::getAddressFieldsList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L161)




### <a name="method-init"></a>init

```php
mixed AdminManufacturersControllerCore::init()
```

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L776)




### <a name="method-initContent"></a>initContent

```php
mixed AdminManufacturersControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 736](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L736)




### <a name="method-initListManufacturer"></a>initListManufacturer

```php
mixed AdminManufacturersControllerCore::initListManufacturer()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L140)




### <a name="method-initListManufacturerAddresses"></a>initListManufacturerAddresses

```php
mixed AdminManufacturersControllerCore::initListManufacturerAddresses()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L210)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminManufacturersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L107)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminManufacturersControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 792](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L792)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminManufacturersControllerCore::initToolbar()
```

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 641](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L641)




### <a name="method-processExport"></a>processExport

```php
mixed AdminManufacturersControllerCore::processExport($text_delimiter)
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L202)


#### Arguments
* $text_delimiter **mixed**



### <a name="method-processSave"></a>processSave

```php
mixed AdminManufacturersControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L843)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminManufacturersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L293)




### <a name="method-renderFormAddress"></a>renderFormAddress

```php
mixed AdminManufacturersControllerCore::renderFormAddress()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L434)




### <a name="method-renderList"></a>renderList

```php
mixed AdminManufacturersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L266)




### <a name="method-renderView"></a>renderView

```php
mixed AdminManufacturersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L675)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminManufacturersControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminManufacturersController.php#L100)



