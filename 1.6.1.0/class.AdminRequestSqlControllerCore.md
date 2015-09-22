Class AdminRequestSqlControllerCore
=====================





* Class name: AdminRequestSqlControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminRequestSqlController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L30)


Contents
--------


### Properties

* [$encoding_file](#property-$encoding_file)
* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [_childValidation](#method-_childValidation)
* [ajaxProcess](#method-ajaxProcess)
* [displayError](#method-displayError)
* [displayExportLink](#method-displayExportLink)
* [generateExport](#method-generateExport)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$encoding_file"></a>$encoding_file

```php
public array $encoding_file = array(array('value' => 1, 'name' => 'utf-8'), array('value' => 2, 'name' => 'iso-8859-1'))
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminRequestSqlController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L35).


### <a name="property-$object"></a>$object

```php
public \RequestSql $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminRequestSqlControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L40)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminRequestSqlControllerCore::_childValidation()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L234)




### <a name="method-ajaxProcess"></a>ajaxProcess

```php
mixed AdminRequestSqlControllerCore::ajaxProcess()
```

method call when ajax request is made with the details row action



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L184)




### <a name="method-displayError"></a>displayError

```php
mixed AdminRequestSqlControllerCore::displayError($e)
```

Display all errors



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L386)


#### Arguments
* $e **mixed** - : array of errors



### <a name="method-displayExportLink"></a>displayExportLink

```php
string AdminRequestSqlControllerCore::displayExportLink($token, integer $id)
```

Display export action link



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L257)


#### Arguments
* $token **mixed**
* $id **integer**



### <a name="method-generateExport"></a>generateExport

```php
mixed AdminRequestSqlControllerCore::generateExport()
```

Genrating a export file



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L331)




### <a name="method-initContent"></a>initContent

```php
mixed AdminRequestSqlControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L279)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminRequestSqlControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L316)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminRequestSqlControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L269)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminRequestSqlControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L95)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminRequestSqlControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L169)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminRequestSqlControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L133)




### <a name="method-renderList"></a>renderList

```php
mixed AdminRequestSqlControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L109)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminRequestSqlControllerCore::renderOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L84)




### <a name="method-renderView"></a>renderView

```php
mixed AdminRequestSqlControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminRequestSqlController.php#L204)


