Class AdminWebserviceControllerCore
=====================





* Class name: AdminWebserviceControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminWebserviceController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L30)


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
* Source: [controllers/admin/AdminWebserviceController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L33).


### <a name="property-$object"></a>$object

```php
public \WebserviceKey $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L30).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminWebserviceControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L36)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminWebserviceControllerCore::afterAdd($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L257)


#### Arguments
* $object **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminWebserviceControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L263)


#### Arguments
* $object **mixed**



### <a name="method-checkForWarning"></a>checkForWarning

```php
mixed AdminWebserviceControllerCore::checkForWarning()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L269)




### <a name="method-initContent"></a>initContent

```php
mixed AdminWebserviceControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L207)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminWebserviceControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L103)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminWebserviceControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L237)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminWebserviceControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L246)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminWebserviceControllerCore::processUpdateOptions()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWebserviceController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L117)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminWebserviceControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L123)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminWebserviceControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminWebserviceController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminWebserviceController.php#L219)



