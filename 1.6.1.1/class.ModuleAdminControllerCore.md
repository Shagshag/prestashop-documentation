Class ModuleAdminControllerCore
=====================





* Class name: ModuleAdminControllerCore
* This is an **abstract** class
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [classes/controller/ModuleAdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleAdminController.php#L30)


Contents
--------


### Properties

* [$module](#property-$module)

### Methods

* [__construct](#method-__construct)
* [createTemplate](#method-createTemplate)
* [getTemplatePath](#method-getTemplatePath)




Properties
----------


### <a name="property-$module"></a>$module

```php
public \Module $module
```





* Visibility: **public**
* Source: [classes/controller/ModuleAdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleAdminController.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleAdminControllerCore::__construct()
```





* Visibility: **public**
* Source: [classes/controller/ModuleAdminController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleAdminController.php#L38)




### <a name="method-createTemplate"></a>createTemplate

```php
\Smarty_Internal_Template ModuleAdminControllerCore::createTemplate(string $tpl_name)
```

Creates a template object



* Visibility: **public**
* Source: [classes/controller/ModuleAdminController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleAdminController.php#L61)


#### Arguments
* $tpl_name **string** - Template filename



### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string ModuleAdminControllerCore::getTemplatePath()
```

Get path to back office templates for the module



* Visibility: **public**
* Source: [classes/controller/ModuleAdminController.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleAdminController.php#L77)



