AdminEmployeesControllerCore
===============






* Class name: AdminEmployeesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L30)





Properties
----------


### $profiles_array

    protected array $profiles_array = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#33)


### $themes

    protected array $themes = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#36)


### $tabs_list

    protected array $tabs_list = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#39)


### $restrict_edition

    protected mixed $restrict_edition = false





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#41)


### $object

    public \Employee $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#30)


Methods
-------


### __construct

    mixed AdminEmployeesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#43)




### setMedia

    mixed AdminEmployeesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#168)




### initPageHeaderToolbar

    mixed AdminEmployeesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#176)




### renderList

    mixed AdminEmployeesControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#200)




### renderForm

    mixed AdminEmployeesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#211)




### _childValidation

    mixed AdminEmployeesControllerCore::_childValidation()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#430)




### processDelete

    mixed AdminEmployeesControllerCore::processDelete()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#447)




### processStatus

    mixed AdminEmployeesControllerCore::processStatus()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#456)




### processBulkDelete

    mixed AdminEmployeesControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#465)




### canModifyEmployee

    mixed AdminEmployeesControllerCore::canModifyEmployee()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#479)




### processSave

    mixed AdminEmployeesControllerCore::processSave()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#502)




### validateRules

    mixed AdminEmployeesControllerCore::validateRules($class_name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#603)


#### Arguments
* $class_name **mixed**



### postProcess

    mixed AdminEmployeesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#615)




### initContent

    mixed AdminEmployeesControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#626)




### afterUpdate

    boolean AdminEmployeesControllerCore::afterUpdate(\Employee $object)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#640)


#### Arguments
* $object **[Employee](EmployeeCore)**



### ajaxProcessFormLanguage

    mixed AdminEmployeesControllerCore::ajaxProcessFormLanguage()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#661)




### ajaxProcessToggleMenu

    mixed AdminEmployeesControllerCore::ajaxProcessToggleMenu()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#670)




### ajaxProcessGetTabByIdProfile

    mixed AdminEmployeesControllerCore::ajaxProcessGetTabByIdProfile()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#675)



