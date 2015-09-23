Class AdminAccessControllerCore
=====================





* Class name: AdminAccessControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAccessController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L27)


Contents
--------


### Properties

* [$accesses_black_list](#property-$accesses_black_list)

### Methods

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

```php
public mixed $accesses_black_list = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminAccessControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L32)




### <a name="method-ajaxProcessUpdateAccess"></a>ajaxProcessUpdateAccess

```php
mixed AdminAccessControllerCore::ajaxProcessUpdateAccess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L147)




### <a name="method-ajaxProcessUpdateModuleAccess"></a>ajaxProcessUpdateModuleAccess

```php
mixed AdminAccessControllerCore::ajaxProcessUpdateModuleAccess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L204)




### <a name="method-getCurrentProfileId"></a>getCurrentProfileId

```php
\the AdminAccessControllerCore::getCurrentProfileId()
```

Get the current profile id



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L244)




### <a name="method-initContent"></a>initContent

```php
mixed AdminAccessControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L117)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminAccessControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L141)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminAccessControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L136)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminAccessControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L52)




### <a name="method-sortModuleByName"></a>sortModuleByName

```php
mixed AdminAccessControllerCore::sortModuleByName($a, $b)
```





* Visibility: **private**
* Source: [controllers/admin/AdminAccessController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminAccessController.php#L249)


#### Arguments
* $a **mixed**
* $b **mixed**


