Class AdminTaxesControllerCore
=====================





* Class name: AdminTaxesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTaxesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayEnableLink](#method-displayEnableLink)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [updateOptionPsUseEcotax](#method-updateOptionPsUseEcotax)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Tax $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTaxesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L32)




### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
string AdminTaxesControllerCore::displayDeleteLink(string|null $token, integer $id)
```

Display delete action link



* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L137)


#### Arguments
* $token **string|null**
* $id **integer**



### <a name="method-displayEnableLink"></a>displayEnableLink

```php
mixed AdminTaxesControllerCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product)
```

Fetch the template for action enable



* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L167)


#### Arguments
* $token **string**
* $id **integer**
* $value **integer** - state enabled or not
* $active **string** - status
* $id_category **integer**
* $id_product **integer**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminTaxesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L115)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminTaxesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L234)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminTaxesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L182)




### <a name="method-updateOptionPsUseEcotax"></a>updateOptionPsUseEcotax

```php
mixed AdminTaxesControllerCore::updateOptionPsUseEcotax($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxesController.php#L280)


#### Arguments
* $value **mixed**


