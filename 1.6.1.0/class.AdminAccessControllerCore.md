Class AdminAccessControllerCore
=====================





* Class name: AdminAccessControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAccessController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L30)


Contents
--------


### Properties

* [$accesses_black_list](#property-$accesses_black_list)
* [$object](#property-$object)

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
* Source: [controllers/admin/AdminAccessController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L33).


### <a name="property-$object"></a>$object

```php
public \Profile $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminAccessControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L35)




### <a name="method-ajaxProcessUpdateAccess"></a>ajaxProcessUpdateAccess

```php
mixed AdminAccessControllerCore::ajaxProcessUpdateAccess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L152)




### <a name="method-ajaxProcessUpdateModuleAccess"></a>ajaxProcessUpdateModuleAccess

```php
mixed AdminAccessControllerCore::ajaxProcessUpdateModuleAccess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L209)




### <a name="method-getCurrentProfileId"></a>getCurrentProfileId

```php
integer AdminAccessControllerCore::getCurrentProfileId()
```

Get the current profile id



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L249)




### <a name="method-initContent"></a>initContent

```php
mixed AdminAccessControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L122)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminAccessControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L146)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminAccessControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L141)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminAccessControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminAccessController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L55)




### <a name="method-sortModuleByName"></a>sortModuleByName

```php
mixed AdminAccessControllerCore::sortModuleByName($a, $b)
```





* Visibility: **private**
* Source: [controllers/admin/AdminAccessController.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAccessController.php#L254)


#### Arguments
* $a **mixed**
* $b **mixed**


