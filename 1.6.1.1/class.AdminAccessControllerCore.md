Class AdminAccessControllerCore
=====================





* Class name: AdminAccessControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAccessController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L30)



Properties
----------

* [$accesses_black_list](#property-$accesses_black_list)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessUpdateAccess](#method-ajaxProcessUpdateAccess)
* [ajaxProcessUpdateModuleAccess](#method-ajaxProcessUpdateModuleAccess)
* [getCurrentProfileId](#method-getCurrentProfileId)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [renderForm](#method-renderForm)
* [sortModuleByName](#method-sortModuleByName)




Properties
----------


### <a name="property-$accesses_black_list"></a>$accesses_black_list

    public mixed $accesses_black_list = array()





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L33)


### <a name="property-$object"></a>$object

    public \Profile $object





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminAccessControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L35)




### <a name="method-ajaxProcessUpdateAccess"></a>ajaxProcessUpdateAccess

    mixed AdminAccessControllerCore::ajaxProcessUpdateAccess()





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L155)




### <a name="method-ajaxProcessUpdateModuleAccess"></a>ajaxProcessUpdateModuleAccess

    mixed AdminAccessControllerCore::ajaxProcessUpdateModuleAccess()





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L212)




### <a name="method-getCurrentProfileId"></a>getCurrentProfileId

    integer AdminAccessControllerCore::getCurrentProfileId()

Get the current profile id



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L255)




### <a name="method-initContent"></a>initContent

    mixed AdminAccessControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L124)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminAccessControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L149)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

    mixed AdminAccessControllerCore::initToolbarTitle()





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L144)




### <a name="method-renderForm"></a>renderForm

    mixed AdminAccessControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L55)




### <a name="method-sortModuleByName"></a>sortModuleByName

    mixed AdminAccessControllerCore::sortModuleByName($a, $b)





* Visibility: **private**
* Source: [controllers/admin/AdminAccessController.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAccessController.php#L260)


#### Arguments
* $a **mixed**
* $b **mixed**


