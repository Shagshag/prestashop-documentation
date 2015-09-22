AdminAddressesControllerCore
===============






* Class name: AdminAddressesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminAddressesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L30)





Properties
----------

* [$countries_array](#property-$countries_array)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [initToolbar](#method-initToolbar)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [renderForm](#method-renderForm)
* [processSave](#method-processSave)
* [processAdd](#method-processAdd)
* [processAddressFormat](#method-processAddressFormat)
* [ajaxProcess](#method-ajaxProcess)
* [processDelete](#method-processDelete)
* [processBulkDelete](#method-processBulkDelete)




Properties
----------


### <a name="property-$countries_array"></a>$countries_array

    protected array $countries_array = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminAddressesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L33)


### <a name="property-$object"></a>$object

    public \Address $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminAddressesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminAddressesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L35)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminAddressesControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L88)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminAddressesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L100)




### <a name="method-renderForm"></a>renderForm

    mixed AdminAddressesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L113)




### <a name="method-processSave"></a>processSave

    mixed AdminAddressesControllerCore::processSave()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L340)




### <a name="method-processAdd"></a>processAdd

    mixed AdminAddressesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L431)




### <a name="method-processAddressFormat"></a>processAddressFormat

    array AdminAddressesControllerCore::processAddressFormat()

Get Address formats used by the country where the address id retrieved from POST/GET is.



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminAddressesController.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L445)




### <a name="method-ajaxProcess"></a>ajaxProcess

    mixed AdminAddressesControllerCore::ajaxProcess()

Method called when an ajax request is made



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L477)




### <a name="method-processDelete"></a>processDelete

    mixed AdminAddressesControllerCore::processDelete()

Object Delete



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L493)




### <a name="method-processBulkDelete"></a>processBulkDelete

    boolean AdminAddressesControllerCore::processBulkDelete()

Delete multiple items



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminAddressesController.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L516)



