Class AdminOutstandingControllerCore
=====================





* Class name: AdminOutstandingControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminOutstandingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOutstandingController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [initToolbar](#method-initToolbar)
* [printOutstandingCalculation](#method-printOutstandingCalculation)
* [printPDFIcons](#method-printPDFIcons)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \OrderInvoice $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOutstandingController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminOutstandingControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOutstandingController.php#L32)




### <a name="method-initToolbar"></a>initToolbar

```php
boolean AdminOutstandingControllerCore::initToolbar()
```

Toolbar initialisation



* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOutstandingController.php#L120)




### <a name="method-printOutstandingCalculation"></a>printOutstandingCalculation

```php
mixed AdminOutstandingControllerCore::printOutstandingCalculation($id_invoice, $tr)
```





* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOutstandingController.php#L140)


#### Arguments
* $id_invoice **mixed**
* $tr **mixed**



### <a name="method-printPDFIcons"></a>printPDFIcons

```php
string AdminOutstandingControllerCore::printPDFIcons($id_invoice, $tr)
```

Column callback for print PDF incon



* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOutstandingController.php#L131)


#### Arguments
* $id_invoice **mixed** - integer Invoice ID
* $tr **mixed** - array Row data



### <a name="method-renderView"></a>renderView

```php
mixed AdminOutstandingControllerCore::renderView()
```

View render



* Visibility: **public**
* Source: [controllers/admin/AdminOutstandingController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminOutstandingController.php#L159)



