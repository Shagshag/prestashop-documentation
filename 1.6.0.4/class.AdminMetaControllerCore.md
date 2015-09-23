Class AdminMetaControllerCore
=====================





* Class name: AdminMetaControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminMetaController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L27)


Contents
--------


### Properties

* [$className](#property-$className)
* [$lang](#property-$lang)
* [$table](#property-$table)
* [$toolbar_scroll](#property-$toolbar_scroll)

### Methods

* [__construct](#method-__construct)
* [addAllRouteFields](#method-addAllRouteFields)
* [addFieldRoute](#method-addFieldRoute)
* [checkAndUpdateRoute](#method-checkAndUpdateRoute)
* [checkConfiguration](#method-checkConfiguration)
* [generateRobotsFile](#method-generateRobotsFile)
* [getList](#method-getList)
* [getRobotsContent](#method-getRobotsContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderOptions](#method-renderOptions)
* [setMedia](#method-setMedia)
* [updateOptionDomain](#method-updateOptionDomain)
* [updateOptionDomainSsl](#method-updateOptionDomainSsl)
* [updateOptionPsRewritingSettings](#method-updateOptionPsRewritingSettings)
* [updateOptionPsRouteCategoryRule](#method-updateOptionPsRouteCategoryRule)
* [updateOptionPsRouteCmsCategoryRule](#method-updateOptionPsRouteCmsCategoryRule)
* [updateOptionPsRouteCmsRule](#method-updateOptionPsRouteCmsRule)
* [updateOptionPsRouteLayeredRule](#method-updateOptionPsRouteLayeredRule)
* [updateOptionPsRouteManufacturerRule](#method-updateOptionPsRouteManufacturerRule)
* [updateOptionPsRouteProductRule](#method-updateOptionPsRouteProductRule)
* [updateOptionPsRouteSupplierRule](#method-updateOptionPsRouteSupplierRule)
* [updateOptionUri](#method-updateOptionUri)




Properties
----------


### <a name="property-$className"></a>$className

```php
public mixed $className = 'Meta'
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L30).


### <a name="property-$lang"></a>$lang

```php
public mixed $lang = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L31).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'meta'
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L29).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminMetaController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminMetaControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L34)




### <a name="method-addAllRouteFields"></a>addAllRouteFields

```php
mixed AdminMetaControllerCore::addAllRouteFields()
```

Add all custom route fields to the options form



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L683)




### <a name="method-addFieldRoute"></a>addFieldRoute

```php
mixed AdminMetaControllerCore::addFieldRoute($route_id, $title)
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L241)


#### Arguments
* $route_id **mixed**
* $title **mixed**



### <a name="method-checkAndUpdateRoute"></a>checkAndUpdateRoute

```php
mixed AdminMetaControllerCore::checkAndUpdateRoute(string $route_id)
```

Validate route syntax and save it in configuration



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L513)


#### Arguments
* $route_id **string**



### <a name="method-checkConfiguration"></a>checkConfiguration

```php
boolean AdminMetaControllerCore::checkConfiguration(string $file)
```

Check if a file is writable



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 701](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L701)


#### Arguments
* $file **string**



### <a name="method-generateRobotsFile"></a>generateRobotsFile

```php
mixed AdminMetaControllerCore::generateRobotsFile()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L438)




### <a name="method-getList"></a>getList

```php
mixed AdminMetaControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L495)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getRobotsContent"></a>getRobotsContent

```php
mixed AdminMetaControllerCore::getRobotsContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 708](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L708)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminMetaControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L214)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminMetaControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L226)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminMetaControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L368)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminMetaControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L257)




### <a name="method-renderList"></a>renderList

```php
mixed AdminMetaControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L500)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminMetaControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L657)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminMetaControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L234)




### <a name="method-updateOptionDomain"></a>updateOptionDomain

```php
mixed AdminMetaControllerCore::updateOptionDomain($value)
```

Update shop domain (for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L609)


#### Arguments
* $value **mixed**



### <a name="method-updateOptionDomainSsl"></a>updateOptionDomainSsl

```php
mixed AdminMetaControllerCore::updateOptionDomainSsl($value)
```

Update shop SSL domain (for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L627)


#### Arguments
* $value **mixed**



### <a name="method-updateOptionPsRewritingSettings"></a>updateOptionPsRewritingSettings

```php
mixed AdminMetaControllerCore::updateOptionPsRewritingSettings()
```

Called when PS_REWRITING_SETTINGS option is saved



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L544)




### <a name="method-updateOptionPsRouteCategoryRule"></a>updateOptionPsRouteCategoryRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCategoryRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L576)




### <a name="method-updateOptionPsRouteCmsCategoryRule"></a>updateOptionPsRouteCmsCategoryRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCmsCategoryRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 601](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L601)




### <a name="method-updateOptionPsRouteCmsRule"></a>updateOptionPsRouteCmsRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCmsRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L596)




### <a name="method-updateOptionPsRouteLayeredRule"></a>updateOptionPsRouteLayeredRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteLayeredRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L581)




### <a name="method-updateOptionPsRouteManufacturerRule"></a>updateOptionPsRouteManufacturerRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteManufacturerRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 591](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L591)




### <a name="method-updateOptionPsRouteProductRule"></a>updateOptionPsRouteProductRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteProductRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L571)




### <a name="method-updateOptionPsRouteSupplierRule"></a>updateOptionPsRouteSupplierRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteSupplierRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L586)




### <a name="method-updateOptionUri"></a>updateOptionUri

```php
mixed AdminMetaControllerCore::updateOptionUri($value)
```

Update shop physical uri for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 645](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminMetaController.php#L645)


#### Arguments
* $value **mixed**


