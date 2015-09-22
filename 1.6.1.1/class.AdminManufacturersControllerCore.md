Class AdminManufacturersControllerCore
=====================





* Class name: AdminManufacturersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminManufacturersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L30)



Properties
----------

* [$bootstrap](#property-$bootstrap)
* [$countries_array](#property-$countries_array)
* [$object](#property-$object)

Methods
-------
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

    public mixed $bootstrap = true





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L32).


### <a name="property-$countries_array"></a>$countries_array

    protected array $countries_array = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L34).


### <a name="property-$object"></a>$object

    public \Manufacturer $object





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminManufacturersControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L36)




### <a name="method-afterImageUpload"></a>afterImageUpload

    mixed AdminManufacturersControllerCore::afterImageUpload()





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L812)




### <a name="method-beforeDelete"></a>beforeDelete

    mixed AdminManufacturersControllerCore::beforeDelete($object)





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L855)


#### Arguments
* $object **mixed**



### <a name="method-displayEditaddressesLink"></a>displayEditaddressesLink

    string AdminManufacturersControllerCore::displayEditaddressesLink(string $token, integer $id)

Display editaddresses action link



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L282)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getAddressFieldsList"></a>getAddressFieldsList

    mixed AdminManufacturersControllerCore::getAddressFieldsList()





* Visibility: **protected**
* Source: [controllers/admin/AdminManufacturersController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L162)




### <a name="method-init"></a>init

    mixed AdminManufacturersControllerCore::init()

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L783)




### <a name="method-initContent"></a>initContent

    mixed AdminManufacturersControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L746)




### <a name="method-initListManufacturer"></a>initListManufacturer

    mixed AdminManufacturersControllerCore::initListManufacturer()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L141)




### <a name="method-initListManufacturerAddresses"></a>initListManufacturerAddresses

    mixed AdminManufacturersControllerCore::initListManufacturerAddresses()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L214)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminManufacturersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L110)




### <a name="method-initProcess"></a>initProcess

    mixed AdminManufacturersControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 800](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L800)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminManufacturersControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L649)




### <a name="method-processExport"></a>processExport

    mixed AdminManufacturersControllerCore::processExport($text_delimiter)





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L204)


#### Arguments
* $text_delimiter **mixed**



### <a name="method-processSave"></a>processSave

    mixed AdminManufacturersControllerCore::processSave()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 860](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L860)




### <a name="method-renderForm"></a>renderForm

    mixed AdminManufacturersControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L298)




### <a name="method-renderFormAddress"></a>renderFormAddress

    mixed AdminManufacturersControllerCore::renderFormAddress()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L439)




### <a name="method-renderList"></a>renderList

    mixed AdminManufacturersControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L270)




### <a name="method-renderView"></a>renderView

    mixed AdminManufacturersControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L685)




### <a name="method-setMedia"></a>setMedia

    mixed AdminManufacturersControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/admin/AdminManufacturersController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L103)



