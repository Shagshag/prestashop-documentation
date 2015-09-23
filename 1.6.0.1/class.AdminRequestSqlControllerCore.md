Class AdminRequestSqlControllerCore
=====================





* Class name: AdminRequestSqlControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminRequestSqlController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L27)


Contents
--------


### Properties

* [$encoding_file](#property-$encoding_file)

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
* Source: [controllers/admin/AdminRequestSqlController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminRequestSqlControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L37)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminRequestSqlControllerCore::_childValidation()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L228)




### <a name="method-ajaxProcess"></a>ajaxProcess

```php
mixed AdminRequestSqlControllerCore::ajaxProcess()
```

method call when ajax request is made with the details row action



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L177)




### <a name="method-displayError"></a>displayError

```php
mixed AdminRequestSqlControllerCore::displayError($e)
```

Display all errors



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L371)


#### Arguments
* $e **mixed** - : array of errors



### <a name="method-displayExportLink"></a>displayExportLink

```php
mixed AdminRequestSqlControllerCore::displayExportLink($token, $id)
```

Display export action link



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L244)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-generateExport"></a>generateExport

```php
mixed AdminRequestSqlControllerCore::generateExport()
```

Genrating a export file



* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L317)




### <a name="method-initContent"></a>initContent

```php
mixed AdminRequestSqlControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L266)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminRequestSqlControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L302)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminRequestSqlControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L256)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminRequestSqlControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L86)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminRequestSqlControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L161)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminRequestSqlControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L124)




### <a name="method-renderList"></a>renderList

```php
mixed AdminRequestSqlControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L100)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminRequestSqlControllerCore::renderOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L75)




### <a name="method-renderView"></a>renderView

```php
mixed AdminRequestSqlControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminRequestSqlController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminRequestSqlController.php#L198)



