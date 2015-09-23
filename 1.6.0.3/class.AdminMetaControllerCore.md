Class AdminMetaControllerCore
=====================





* Class name: AdminMetaControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminMetaController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L27)


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
* Source: [controllers/admin/AdminMetaController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L30).


### <a name="property-$lang"></a>$lang

```php
public mixed $lang = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L31).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'meta'
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L29).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminMetaController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminMetaControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L34)




### <a name="method-addAllRouteFields"></a>addAllRouteFields

```php
mixed AdminMetaControllerCore::addAllRouteFields()
```

Add all custom route fields to the options form



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 653](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L653)




### <a name="method-addFieldRoute"></a>addFieldRoute

```php
mixed AdminMetaControllerCore::addFieldRoute($route_id, $title)
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L235)


#### Arguments
* $route_id **mixed**
* $title **mixed**



### <a name="method-checkAndUpdateRoute"></a>checkAndUpdateRoute

```php
mixed AdminMetaControllerCore::checkAndUpdateRoute(string $route_id)
```

Validate route syntax and save it in configuration



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L483)


#### Arguments
* $route_id **string**



### <a name="method-checkConfiguration"></a>checkConfiguration

```php
boolean AdminMetaControllerCore::checkConfiguration(string $file)
```

Check if a file is writable



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L671)


#### Arguments
* $file **string**



### <a name="method-generateRobotsFile"></a>generateRobotsFile

```php
mixed AdminMetaControllerCore::generateRobotsFile()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L408)




### <a name="method-getList"></a>getList

```php
mixed AdminMetaControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L465)


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
* Source: [controllers/admin/AdminMetaController.php line 678](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L678)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminMetaControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L208)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminMetaControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L220)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminMetaControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L362)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminMetaControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L251)




### <a name="method-renderList"></a>renderList

```php
mixed AdminMetaControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L470)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminMetaControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L627)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminMetaControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L228)




### <a name="method-updateOptionDomain"></a>updateOptionDomain

```php
mixed AdminMetaControllerCore::updateOptionDomain($value)
```

Update shop domain (for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L579)


#### Arguments
* $value **mixed**



### <a name="method-updateOptionDomainSsl"></a>updateOptionDomainSsl

```php
mixed AdminMetaControllerCore::updateOptionDomainSsl($value)
```

Update shop SSL domain (for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L597)


#### Arguments
* $value **mixed**



### <a name="method-updateOptionPsRewritingSettings"></a>updateOptionPsRewritingSettings

```php
mixed AdminMetaControllerCore::updateOptionPsRewritingSettings()
```

Called when PS_REWRITING_SETTINGS option is saved



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L514)




### <a name="method-updateOptionPsRouteCategoryRule"></a>updateOptionPsRouteCategoryRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCategoryRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L546)




### <a name="method-updateOptionPsRouteCmsCategoryRule"></a>updateOptionPsRouteCmsCategoryRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCmsCategoryRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L571)




### <a name="method-updateOptionPsRouteCmsRule"></a>updateOptionPsRouteCmsRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteCmsRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L566)




### <a name="method-updateOptionPsRouteLayeredRule"></a>updateOptionPsRouteLayeredRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteLayeredRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 551](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L551)




### <a name="method-updateOptionPsRouteManufacturerRule"></a>updateOptionPsRouteManufacturerRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteManufacturerRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L561)




### <a name="method-updateOptionPsRouteProductRule"></a>updateOptionPsRouteProductRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteProductRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L541)




### <a name="method-updateOptionPsRouteSupplierRule"></a>updateOptionPsRouteSupplierRule

```php
mixed AdminMetaControllerCore::updateOptionPsRouteSupplierRule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 556](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L556)




### <a name="method-updateOptionUri"></a>updateOptionUri

```php
mixed AdminMetaControllerCore::updateOptionUri($value)
```

Update shop physical uri for mono shop)



* Visibility: **public**
* Source: [controllers/admin/AdminMetaController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminMetaController.php#L615)


#### Arguments
* $value **mixed**


