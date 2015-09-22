Class AdminAttributesGroupsControllerCore
=====================





* Class name: AdminAttributesGroupsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAttributesGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L30)


Contents
--------


### Properties

* [$attribute_name](#property-$attribute_name)
* [$bootstrap](#property-$bootstrap)
* [$id_attribute](#property-$id_attribute)
* [$object](#property-$object)
* [$position_identifier](#property-$position_identifier)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessUpdateAttributesPositions](#method-ajaxProcessUpdateAttributesPositions)
* [ajaxProcessUpdateGroupsPositions](#method-ajaxProcessUpdateGroupsPositions)
* [getList](#method-getList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processBulkDelete](#method-processBulkDelete)
* [processPosition](#method-processPosition)
* [processSave](#method-processSave)
* [processUpdate](#method-processUpdate)
* [renderForm](#method-renderForm)
* [renderFormAttributes](#method-renderFormAttributes)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [setTypeAttribute](#method-setTypeAttribute)




Properties
----------


### <a name="property-$attribute_name"></a>$attribute_name

```php
protected mixed $attribute_name
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L35).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L32).


### <a name="property-$id_attribute"></a>$id_attribute

```php
protected mixed $id_attribute
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L33).


### <a name="property-$object"></a>$object

```php
public \AttributeGroup $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_attribute_group'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminAttributesGroupsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L37)




### <a name="method-ajaxProcessUpdateAttributesPositions"></a>ajaxProcessUpdateAttributesPositions

```php
mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateAttributesPositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 916](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L916)




### <a name="method-ajaxProcessUpdateGroupsPositions"></a>ajaxProcessUpdateGroupsPositions

```php
mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateGroupsPositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 885](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L885)




### <a name="method-getList"></a>getList

```php
mixed AdminAttributesGroupsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L827)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-init"></a>init

```php
mixed AdminAttributesGroupsControllerCore::init()
```

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L379)




### <a name="method-initContent"></a>initContent

```php
mixed AdminAttributesGroupsControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L457)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminAttributesGroupsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L504)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminAttributesGroupsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L631)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminAttributesGroupsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L530)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminAttributesGroupsControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L582)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminAttributesGroupsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 709](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L709)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminAttributesGroupsControllerCore::processAdd()
```

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L395)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminAttributesGroupsControllerCore::processBulkDelete()
```

Overrides parent to delete items from sublist



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 866](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L866)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminAttributesGroupsControllerCore::processPosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L667)




### <a name="method-processSave"></a>processSave

```php
mixed AdminAttributesGroupsControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 698](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L698)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminAttributesGroupsControllerCore::processUpdate()
```

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L432)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminAttributesGroupsControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L166)




### <a name="method-renderFormAttributes"></a>renderFormAttributes

```php
mixed AdminAttributesGroupsControllerCore::renderFormAttributes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L245)




### <a name="method-renderList"></a>renderList

```php
mixed AdminAttributesGroupsControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L91)




### <a name="method-renderView"></a>renderView

```php
mixed AdminAttributesGroupsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L101)




### <a name="method-setTypeAttribute"></a>setTypeAttribute

```php
mixed AdminAttributesGroupsControllerCore::setTypeAttribute()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 654](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminAttributesGroupsController.php#L654)



