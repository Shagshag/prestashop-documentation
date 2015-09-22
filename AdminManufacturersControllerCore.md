AdminManufacturersControllerCore
===============






* Class name: AdminManufacturersControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminManufacturersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L30)





Properties
----------

* [$bootstrap](#property-$bootstrap)
* [$countries_array](#property-$countries_array)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [setMedia](#method-setMedia)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initListManufacturer](#method-initListManufacturer)
* [getAddressFieldsList](#method-getAddressFieldsList)
* [processExport](#method-processExport)
* [initListManufacturerAddresses](#method-initListManufacturerAddresses)
* [renderList](#method-renderList)
* [displayEditaddressesLink](#method-displayEditaddressesLink)
* [renderForm](#method-renderForm)
* [renderFormAddress](#method-renderFormAddress)
* [initToolbar](#method-initToolbar)
* [renderView](#method-renderView)
* [initContent](#method-initContent)
* [init](#method-init)
* [initProcess](#method-initProcess)
* [afterImageUpload](#method-afterImageUpload)
* [beforeDelete](#method-beforeDelete)
* [processSave](#method-processSave)




Properties
----------


### <a name="property-$bootstrap"></a>$bootstrap

    public mixed $bootstrap = true





* Visibility: **public**
* This property is defined in [controllers/admin/AdminManufacturersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L32)


### <a name="property-$countries_array"></a>$countries_array

    protected array $countries_array = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminManufacturersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L34)


### <a name="property-$object"></a>$object

    public \Manufacturer $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminManufacturersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminManufacturersControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L36)




### <a name="method-setMedia"></a>setMedia

    mixed AdminManufacturersControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L103)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminManufacturersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L110)




### <a name="method-initListManufacturer"></a>initListManufacturer

    mixed AdminManufacturersControllerCore::initListManufacturer()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L141)




### <a name="method-getAddressFieldsList"></a>getAddressFieldsList

    mixed AdminManufacturersControllerCore::getAddressFieldsList()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L162)




### <a name="method-processExport"></a>processExport

    mixed AdminManufacturersControllerCore::processExport($text_delimiter)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L204)


#### Arguments
* $text_delimiter **mixed**



### <a name="method-initListManufacturerAddresses"></a>initListManufacturerAddresses

    mixed AdminManufacturersControllerCore::initListManufacturerAddresses()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L214)




### <a name="method-renderList"></a>renderList

    mixed AdminManufacturersControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L270)




### <a name="method-displayEditaddressesLink"></a>displayEditaddressesLink

    string AdminManufacturersControllerCore::displayEditaddressesLink(string $token, integer $id)

Display editaddresses action link



* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L282)


#### Arguments
* $token **string** - &lt;p&gt;the token to add to the link&lt;/p&gt;
* $id **integer** - &lt;p&gt;the identifier to add to the link&lt;/p&gt;



### <a name="method-renderForm"></a>renderForm

    mixed AdminManufacturersControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L298)




### <a name="method-renderFormAddress"></a>renderFormAddress

    mixed AdminManufacturersControllerCore::renderFormAddress()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L439)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminManufacturersControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L649)




### <a name="method-renderView"></a>renderView

    mixed AdminManufacturersControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L685)




### <a name="method-initContent"></a>initContent

    mixed AdminManufacturersControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L746)




### <a name="method-init"></a>init

    mixed AdminManufacturersControllerCore::init()

AdminController::init() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L783)




### <a name="method-initProcess"></a>initProcess

    mixed AdminManufacturersControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 800](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L800)




### <a name="method-afterImageUpload"></a>afterImageUpload

    mixed AdminManufacturersControllerCore::afterImageUpload()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L812)




### <a name="method-beforeDelete"></a>beforeDelete

    mixed AdminManufacturersControllerCore::beforeDelete($object)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L855)


#### Arguments
* $object **mixed**



### <a name="method-processSave"></a>processSave

    mixed AdminManufacturersControllerCore::processSave()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminManufacturersController.php line 860](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminManufacturersController.php#L860)



