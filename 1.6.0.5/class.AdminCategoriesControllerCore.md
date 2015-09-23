Class AdminCategoriesControllerCore
=====================





* Class name: AdminCategoriesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCategoriesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L27)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$disable_products](#property-$disable_products)
* [$original_filter](#property-$original_filter)
* [$position_identifier](#property-$position_identifier)
* [$remove_products](#property-$remove_products)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [getDescriptionClean](#method-getDescriptionClean)
* [getList](#method-getList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processFatherlessProducts](#method-processFatherlessProducts)
* [processForceDeleteImage](#method-processForceDeleteImage)
* [processPosition](#method-processPosition)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [setDeleteMode](#method-setDeleteMode)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$_category"></a>$_category

```php
protected object $_category = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L32).


### <a name="property-$disable_products"></a>$disable_products

```php
public boolean $disable_products = false
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L39).


### <a name="property-$original_filter"></a>$original_filter

```php
private mixed $original_filter = ''
```





* Visibility: **private**
* Source: [controllers/admin/AdminCategoriesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L41).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_category_to_move'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L33).


### <a name="property-$remove_products"></a>$remove_products

```php
public boolean $remove_products = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCategoriesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L43)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L787)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
string AdminCategoriesControllerCore::getDescriptionClean($description)
```

Allows to display the category description without HTML tags and slashes



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCategoriesController.php line 782](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L782)


#### Arguments
* $description **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L238)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-init"></a>init

```php
mixed AdminCategoriesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L103)




### <a name="method-initContent"></a>initContent

```php
mixed AdminCategoriesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L182)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCategoriesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L162)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminCategoriesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L317)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCategoriesControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L259)




### <a name="method-postImage"></a>postImage

```php
mixed AdminCategoriesControllerCore::postImage($id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 756](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L756)


#### Arguments
* $id **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCategoriesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L604)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCategoriesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L625)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminCategoriesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L668)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminCategoriesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L694)




### <a name="method-processFatherlessProducts"></a>processFatherlessProducts

```php
mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 713](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L713)


#### Arguments
* $id_parent **mixed**



### <a name="method-processForceDeleteImage"></a>processForceDeleteImage

```php
mixed AdminCategoriesControllerCore::processForceDeleteImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L618)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminCategoriesControllerCore::processPosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L740)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCategoriesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L402)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCategoriesControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L345)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCategoriesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L201)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCategoriesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L253)




### <a name="method-setDeleteMode"></a>setDeleteMode

```php
mixed AdminCategoriesControllerCore::setDeleteMode()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 655](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L655)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCategoriesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/controllers/admin/AdminCategoriesController.php#L194)



