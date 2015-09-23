Class AdminFeaturesControllerCore
=====================





* Class name: AdminFeaturesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminFeaturesController.php line 26](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L26)


Contents
--------


### Properties

* [$bootstrap](#property-$bootstrap)
* [$feature_name](#property-$feature_name)
* [$position_identifier](#property-$position_identifier)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initFormFeatureValue](#method-initFormFeatureValue)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processSave](#method-processSave)
* [processUpdate](#method-processUpdate)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [setTypeFeature](#method-setTypeFeature)
* [setTypeValue](#method-setTypeValue)




Properties
----------


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L28).


### <a name="property-$feature_name"></a>$feature_name

```php
protected mixed $feature_name
```





* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_feature'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminFeaturesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L32)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminFeaturesControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L575)




### <a name="method-getList"></a>getList

```php
mixed AdminFeaturesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L549)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminFeaturesControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L395)




### <a name="method-initFormFeatureValue"></a>initFormFeatureValue

```php
mixed AdminFeaturesControllerCore::initFormFeatureValue()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L309)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminFeaturesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L189)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminFeaturesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L445)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminFeaturesControllerCore::initToolbar()
```

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L220)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminFeaturesControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L265)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminFeaturesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L470)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminFeaturesControllerCore::processAdd()
```

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L492)




### <a name="method-processSave"></a>processSave

```php
mixed AdminFeaturesControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L523)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminFeaturesControllerCore::processUpdate()
```

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 508](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L508)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminFeaturesControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L152)




### <a name="method-renderList"></a>renderList

```php
mixed AdminFeaturesControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L80)




### <a name="method-renderView"></a>renderView

```php
mixed AdminFeaturesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L110)




### <a name="method-setTypeFeature"></a>setTypeFeature

```php
mixed AdminFeaturesControllerCore::setTypeFeature()
```

Change object type to feature (use when processing a feature)



* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L103)




### <a name="method-setTypeValue"></a>setTypeValue

```php
mixed AdminFeaturesControllerCore::setTypeValue()
```

Change object type to feature value (use when processing a feature value)



* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminFeaturesController.php#L93)



