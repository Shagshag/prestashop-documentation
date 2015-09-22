AdminEmployeesControllerCore
===============






* Class name: AdminEmployeesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L30)





Properties
----------

* [$profiles_array](#property-$profiles_array)
* [$themes](#property-$themes)
* [$tabs_list](#property-$tabs_list)
* [$restrict_edition](#property-$restrict_edition)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [setMedia](#method-setMedia)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [renderList](#method-renderList)
* [renderForm](#method-renderForm)
* [_childValidation](#method-_childValidation)
* [processDelete](#method-processDelete)
* [processStatus](#method-processStatus)
* [processBulkDelete](#method-processBulkDelete)
* [canModifyEmployee](#method-canModifyEmployee)
* [processSave](#method-processSave)
* [validateRules](#method-validateRules)
* [postProcess](#method-postProcess)
* [initContent](#method-initContent)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessFormLanguage](#method-ajaxProcessFormLanguage)
* [ajaxProcessToggleMenu](#method-ajaxProcessToggleMenu)
* [ajaxProcessGetTabByIdProfile](#method-ajaxProcessGetTabByIdProfile)




Properties
----------


### <a name="property-$profiles_array"></a>$profiles_array

    protected array $profiles_array = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L33)


### <a name="property-$themes"></a>$themes

    protected array $themes = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L36)


### <a name="property-$tabs_list"></a>$tabs_list

    protected array $tabs_list = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L39)


### <a name="property-$restrict_edition"></a>$restrict_edition

    protected mixed $restrict_edition = false





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L41)


### <a name="property-$object"></a>$object

    public \Employee $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminEmployeesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L43)




### <a name="method-setMedia"></a>setMedia

    mixed AdminEmployeesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L168)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminEmployeesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L176)




### <a name="method-renderList"></a>renderList

    mixed AdminEmployeesControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L200)




### <a name="method-renderForm"></a>renderForm

    mixed AdminEmployeesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L211)




### <a name="method-_childValidation"></a>_childValidation

    mixed AdminEmployeesControllerCore::_childValidation()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L430)




### <a name="method-processDelete"></a>processDelete

    mixed AdminEmployeesControllerCore::processDelete()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L447)




### <a name="method-processStatus"></a>processStatus

    mixed AdminEmployeesControllerCore::processStatus()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L456)




### <a name="method-processBulkDelete"></a>processBulkDelete

    mixed AdminEmployeesControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L465)




### <a name="method-canModifyEmployee"></a>canModifyEmployee

    mixed AdminEmployeesControllerCore::canModifyEmployee()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L479)




### <a name="method-processSave"></a>processSave

    mixed AdminEmployeesControllerCore::processSave()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L502)




### <a name="method-validateRules"></a>validateRules

    mixed AdminEmployeesControllerCore::validateRules($class_name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L603)


#### Arguments
* $class_name **mixed**



### <a name="method-postProcess"></a>postProcess

    mixed AdminEmployeesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L615)




### <a name="method-initContent"></a>initContent

    mixed AdminEmployeesControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L626)




### <a name="method-afterUpdate"></a>afterUpdate

    boolean AdminEmployeesControllerCore::afterUpdate(\Employee $object)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L640)


#### Arguments
* $object **[Employee](EmployeeCore)**



### <a name="method-ajaxProcessFormLanguage"></a>ajaxProcessFormLanguage

    mixed AdminEmployeesControllerCore::ajaxProcessFormLanguage()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L661)




### <a name="method-ajaxProcessToggleMenu"></a>ajaxProcessToggleMenu

    mixed AdminEmployeesControllerCore::ajaxProcessToggleMenu()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L670)




### <a name="method-ajaxProcessGetTabByIdProfile"></a>ajaxProcessGetTabByIdProfile

    mixed AdminEmployeesControllerCore::ajaxProcessGetTabByIdProfile()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminEmployeesController.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L675)



