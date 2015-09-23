Class AdminOutstandingControllerCore
=====================





* Class name: AdminOutstandingControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminOutstandingController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminOutstandingController.php#L27)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [initToolbar](#method-initToolbar)
* [printOutstandingCalculation](#method-printOutstandingCalculation)
* [printPDFIcons](#method-printPDFIcons)
* [renderView](#method-renderView)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminOutstandingControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminOutstandingController.php#L29)




### <a name="method-initToolbar"></a>initToolbar

```php
boolean AdminOutstandingControllerCore::initToolbar()
```

Toolbar initialisation



* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminOutstandingController.php#L112)




### <a name="method-printOutstandingCalculation"></a>printOutstandingCalculation

```php
mixed AdminOutstandingControllerCore::printOutstandingCalculation($id_invoice, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminOutstandingController.php#L132)


#### Arguments
* $id_invoice **mixed**
* $tr **mixed**



### <a name="method-printPDFIcons"></a>printPDFIcons

```php
string AdminOutstandingControllerCore::printPDFIcons($id_invoice, $tr)
```

Column callback for print PDF incon



* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminOutstandingController.php#L123)


#### Arguments
* $id_invoice **mixed** - integer Invoice ID
* $tr **mixed** - array Row data



### <a name="method-renderView"></a>renderView

```php
mixed AdminOutstandingControllerCore::renderView()
```

View render



* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminOutstandingController.php#L151)



