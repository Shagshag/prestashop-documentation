Class AdminWebserviceControllerCore
=====================





* Class name: AdminWebserviceControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminWebserviceController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L30)


Contents
--------


### Properties

* [$fields_form](#property-$fields_form)
* [$object](#property-$object)
* [$toolbar_scroll](#property-$toolbar_scroll)

### Methods

* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [checkForWarning](#method-checkForWarning)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [processUpdateOptions](#method-processUpdateOptions)
* [renderForm](#method-renderForm)
* [renderOptions](#method-renderOptions)




Properties
----------


### <a name="property-$fields_form"></a>$fields_form

```php
public mixed $fields_form = array('webservice form')
```

this will be filled later



* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L33).


### <a name="property-$object"></a>$object

```php
public \WebserviceKey $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L30).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminWebserviceControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L36)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminWebserviceControllerCore::afterAdd($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L252)


#### Arguments
* $object **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminWebserviceControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L258)


#### Arguments
* $object **mixed**



### <a name="method-checkForWarning"></a>checkForWarning

```php
mixed AdminWebserviceControllerCore::checkForWarning()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L264)




### <a name="method-initContent"></a>initContent

```php
mixed AdminWebserviceControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L205)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminWebserviceControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L102)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminWebserviceControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L235)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminWebserviceControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L243)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminWebserviceControllerCore::processUpdateOptions()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L115)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminWebserviceControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L121)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminWebserviceControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWebserviceController.php#L216)



