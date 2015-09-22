AdminAddressesControllerCore
===============






* Class name: AdminAddressesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminAddressesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#L30)





Properties
----------


### $countries_array

    protected array $countries_array = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminAddressesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#33)


### $object

    public \Address $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminAddressesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#30)


Methods
-------


### __construct

    mixed AdminAddressesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#35)




### initToolbar

    mixed AdminAddressesControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#88)




### initPageHeaderToolbar

    mixed AdminAddressesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#100)




### renderForm

    mixed AdminAddressesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#113)




### processSave

    mixed AdminAddressesControllerCore::processSave()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#340)




### processAdd

    mixed AdminAddressesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#431)




### processAddressFormat

    array AdminAddressesControllerCore::processAddressFormat()

Get Address formats used by the country where the address id retrieved from POST/GET is.



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminAddressesController.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#445)




### ajaxProcess

    mixed AdminAddressesControllerCore::ajaxProcess()

Method called when an ajax request is made



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#477)




### processDelete

    mixed AdminAddressesControllerCore::processDelete()

Object Delete



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAddressesController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#493)




### processBulkDelete

    boolean AdminAddressesControllerCore::processBulkDelete()

Delete multiple items



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminAddressesController.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAddressesController.php#516)



