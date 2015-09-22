Class AdminMetaControllerCore
=====================





* Class name: AdminMetaControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminMetaController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L27)


Contents
--------


### Properties

* [$className](#property-$className)
* [$lang](#property-$lang)
* [$table](#property-$table)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$url](#property-$url)

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
* Source: [controllers/admin/AdminMetaController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L30).


### <a name="property-$lang"></a>$lang

```php
public mixed $lang = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L31).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'meta'
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L29).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminMetaController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L33).


### <a name="property-$url"></a>$url

```php
protected mixed $url = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminMetaController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminMetaControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L35)




### <a name="method-addAllRouteFields"></a>addAllRouteFields

```php
mixed AdminMetaControllerCore::addAllRouteFields()
```

Add all custom route fields to the options form



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L714)




### <a name="method-addFieldRoute"></a>addFieldRoute

```php
mixed AdminMetaControllerCore::addFieldRoute($route_id, $title)
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L258)


#### Arguments
* $route_id **mixed**
* $title **mixed**



### <a name="method-checkAndUpdateRoute"></a>checkAndUpdateRoute

```php
mixed AdminMetaControllerCore::checkAndUpdateRoute(string $route_id)
```

Validate route syntax and save it in configuration



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L542)


#### Arguments
* $route_id **string**



### <a name="method-checkConfiguration"></a>checkConfiguration

```php
boolean AdminMetaControllerCore::checkConfiguration(string $file)
```

Check if a file is writable



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 732](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L732)


#### Arguments
* $file **string**



### <a name="method-generateRobotsFile"></a>generateRobotsFile

```php
mixed AdminMetaControllerCore::generateRobotsFile()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L462)




### <a name="method-getList"></a>getList

```php
mixed AdminMetaControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L524)


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
* Source: [controllers/admin/AdminMetaController.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L739)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminMetaControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L231)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminMetaControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L243)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminMetaControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L385)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminMetaControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L274)




### <a name="method-renderList"></a>renderList

```php
mixed AdminMetaControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L529)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminMetaControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 686](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L686)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminMetaControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L251)




### <a name="method-updateOptionDomain"></a>updateOptionDomain

```php
mixed AdminMetaControllerCore::updateOptionDomain($value)
```

Update shop domain (for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L638)


#### Arguments
* $value **mixed**



### <a name="method-updateOptionDomainSsl"></a>updateOptionDomainSsl

```php
mixed AdminMetaControllerCore::updateOptionDomainSsl($value)
```

Update shop SSL domain (for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L656)


#### Arguments
* $value **mixed**



### <a name="method-updateOptionPsRewritingSettings"></a>updateOptionPsRewritingSettings

```php
mixed AdminMetaControllerCore::updateOptionPsRewritingSettings()
```

Called when PS_REWRITING_SETTINGS option is saved



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L573)




### <a name="method-updateOptionPsRouteCategoryRule"></a>updateOptionPsRouteCategoryRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCategoryRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L605)




### <a name="method-updateOptionPsRouteCmsCategoryRule"></a>updateOptionPsRouteCmsCategoryRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCmsCategoryRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 630](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L630)




### <a name="method-updateOptionPsRouteCmsRule"></a>updateOptionPsRouteCmsRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCmsRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L625)




### <a name="method-updateOptionPsRouteLayeredRule"></a>updateOptionPsRouteLayeredRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteLayeredRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L610)




### <a name="method-updateOptionPsRouteManufacturerRule"></a>updateOptionPsRouteManufacturerRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteManufacturerRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L620)




### <a name="method-updateOptionPsRouteProductRule"></a>updateOptionPsRouteProductRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteProductRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 600](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L600)




### <a name="method-updateOptionPsRouteSupplierRule"></a>updateOptionPsRouteSupplierRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteSupplierRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L615)




### <a name="method-updateOptionUri"></a>updateOptionUri

```php
mixed AdminMetaControllerCore::updateOptionUri($value)
```

Update shop physical uri for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminMetaController.php#L674)


#### Arguments
* $value **mixed**


