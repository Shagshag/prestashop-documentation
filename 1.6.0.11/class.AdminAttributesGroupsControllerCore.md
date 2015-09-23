Class AdminAttributesGroupsControllerCore
=====================





* Class name: AdminAttributesGroupsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminAttributesGroupsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L27)


Contents
--------


### Properties

* [$attribute_name](#property-$attribute_name)
* [$bootstrap](#property-$bootstrap)
* [$id_attribute](#property-$id_attribute)
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
* Source: [controllers/admin/AdminAttributesGroupsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L32).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L29).


### <a name="property-$id_attribute"></a>$id_attribute

```php
protected mixed $id_attribute
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_attribute_group'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminAttributesGroupsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L34)




### <a name="method-ajaxProcessUpdateAttributesPositions"></a>ajaxProcessUpdateAttributesPositions

```php
mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateAttributesPositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 900](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L900)




### <a name="method-ajaxProcessUpdateGroupsPositions"></a>ajaxProcessUpdateGroupsPositions

```php
mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateGroupsPositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 869](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L869)




### <a name="method-getList"></a>getList

```php
mixed AdminAttributesGroupsControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 811](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L811)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-init"></a>init

```php
mixed AdminAttributesGroupsControllerCore::init()
```

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L378)




### <a name="method-initContent"></a>initContent

```php
mixed AdminAttributesGroupsControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L455)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminAttributesGroupsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L502)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminAttributesGroupsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L625)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminAttributesGroupsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L528)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminAttributesGroupsControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L579)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminAttributesGroupsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L703)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminAttributesGroupsControllerCore::processAdd()
```

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L394)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminAttributesGroupsControllerCore::processBulkDelete()
```

Overrides parent to delete items from sublist



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 850](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L850)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminAttributesGroupsControllerCore::processPosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L661)




### <a name="method-processSave"></a>processSave

```php
mixed AdminAttributesGroupsControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 692](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L692)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminAttributesGroupsControllerCore::processUpdate()
```

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L430)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminAttributesGroupsControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L165)




### <a name="method-renderFormAttributes"></a>renderFormAttributes

```php
mixed AdminAttributesGroupsControllerCore::renderFormAttributes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L244)




### <a name="method-renderList"></a>renderList

```php
mixed AdminAttributesGroupsControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L88)




### <a name="method-renderView"></a>renderView

```php
mixed AdminAttributesGroupsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L98)




### <a name="method-setTypeAttribute"></a>setTypeAttribute

```php
mixed AdminAttributesGroupsControllerCore::setTypeAttribute()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributesGroupsController.php line 648](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminAttributesGroupsController.php#L648)



