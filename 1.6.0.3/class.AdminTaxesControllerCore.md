Class AdminTaxesControllerCore
=====================





* Class name: AdminTaxesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTaxesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L27)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayEnableLink](#method-displayEnableLink)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [updateOptionPsUseEcotax](#method-updateOptionPsUseEcotax)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTaxesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L29)




### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed AdminTaxesControllerCore::displayDeleteLink($token, $id)
```

Display delete action link



* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L126)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-displayEnableLink"></a>displayEnableLink

```php
mixed AdminTaxesControllerCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product)
```

Fetch the template for action enable



* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L156)


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
* Source: [controllers/admin/AdminTaxesController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L111)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminTaxesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L224)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminTaxesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L172)




### <a name="method-updateOptionPsUseEcotax"></a>updateOptionPsUseEcotax

```php
mixed AdminTaxesControllerCore::updateOptionPsUseEcotax($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminTaxesController.php#L268)


#### Arguments
* $value **mixed**


