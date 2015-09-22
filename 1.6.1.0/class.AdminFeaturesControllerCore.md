Class AdminFeaturesControllerCore
=====================





* Class name: AdminFeaturesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminFeaturesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L30)


Contents
--------


### Properties

* [$bootstrap](#property-$bootstrap)
* [$feature_name](#property-$feature_name)
* [$object](#property-$object)
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
* Source: [controllers/admin/AdminFeaturesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L32).


### <a name="property-$feature_name"></a>$feature_name

```php
protected mixed $feature_name
```





* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L34).


### <a name="property-$object"></a>$object

```php
public \Feature $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_feature'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminFeaturesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L36)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminFeaturesControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L603)




### <a name="method-getList"></a>getList

```php
mixed AdminFeaturesControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L577)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-initContent"></a>initContent

```php
mixed AdminFeaturesControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L405)




### <a name="method-initFormFeatureValue"></a>initFormFeatureValue

```php
mixed AdminFeaturesControllerCore::initFormFeatureValue()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L319)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminFeaturesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L193)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminFeaturesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L455)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminFeaturesControllerCore::initToolbar()
```

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L224)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminFeaturesControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L269)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminFeaturesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 484](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L484)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminFeaturesControllerCore::processAdd()
```

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L506)




### <a name="method-processSave"></a>processSave

```php
mixed AdminFeaturesControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L542)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminFeaturesControllerCore::processUpdate()
```

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L527)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminFeaturesControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L156)




### <a name="method-renderList"></a>renderList

```php
mixed AdminFeaturesControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L85)




### <a name="method-renderView"></a>renderView

```php
mixed AdminFeaturesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminFeaturesController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L114)




### <a name="method-setTypeFeature"></a>setTypeFeature

```php
mixed AdminFeaturesControllerCore::setTypeFeature()
```

Change object type to feature (use when processing a feature)



* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L107)




### <a name="method-setTypeValue"></a>setTypeValue

```php
mixed AdminFeaturesControllerCore::setTypeValue()
```

Change object type to feature value (use when processing a feature value)



* Visibility: **protected**
* Source: [controllers/admin/AdminFeaturesController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminFeaturesController.php#L97)



