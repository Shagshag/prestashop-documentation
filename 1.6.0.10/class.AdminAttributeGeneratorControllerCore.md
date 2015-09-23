Class AdminAttributeGeneratorControllerCore
=====================





* Class name: AdminAttributeGeneratorControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L29)


Contents
--------


### Properties

* [$combinations](#property-$combinations)
* [$product](#property-$product)

### Methods

* [__construct](#method-__construct)
* [addAttribute](#method-addAttribute)
* [createCombinations](#method-createCombinations)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initContent](#method-initContent)
* [initGroupTable](#method-initGroupTable)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [processGenerate](#method-processGenerate)
* [setAttributesImpacts](#method-setAttributesImpacts)




Properties
----------


### <a name="property-$combinations"></a>$combinations

```php
protected mixed $combinations = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L31).


### <a name="property-$product"></a>$product

```php
protected mixed $product
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminAttributeGeneratorControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L34)




### <a name="method-addAttribute"></a>addAttribute

```php
mixed AdminAttributeGeneratorControllerCore::addAttribute($attributes, $price, $weight)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L44)


#### Arguments
* $attributes **mixed**
* $price **mixed**
* $weight **mixed**



### <a name="method-createCombinations"></a>createCombinations

```php
mixed AdminAttributeGeneratorControllerCore::createCombinations($list)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L67)


#### Arguments
* $list **mixed**



### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminAttributeGeneratorControllerCore::initBreadcrumbs($tab_id, $tabs)
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L198)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminAttributeGeneratorControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L204)




### <a name="method-initGroupTable"></a>initGroupTable

```php
mixed AdminAttributeGeneratorControllerCore::initGroupTable()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L165)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminAttributeGeneratorControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L187)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminAttributeGeneratorControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L82)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminAttributeGeneratorControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L94)




### <a name="method-processGenerate"></a>processGenerate

```php
mixed AdminAttributeGeneratorControllerCore::processGenerate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L101)




### <a name="method-setAttributesImpacts"></a>setAttributesImpacts

```php
mixed AdminAttributeGeneratorControllerCore::setAttributesImpacts($id_product, $tab)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminAttributeGeneratorController.php#L148)


#### Arguments
* $id_product **mixed**
* $tab **mixed**


