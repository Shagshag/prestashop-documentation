Class AdminCategoriesControllerCore
=====================





* Class name: AdminCategoriesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCategoriesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L30)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$disable_products](#property-$disable_products)
* [$object](#property-$object)
* [$original_filter](#property-$original_filter)
* [$position_identifier](#property-$position_identifier)
* [$remove_products](#property-$remove_products)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessStatusCategory](#method-ajaxProcessStatusCategory)
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
* Source: [controllers/admin/AdminCategoriesController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L35).


### <a name="property-$disable_products"></a>$disable_products

```php
public boolean $disable_products = false
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L42).


### <a name="property-$object"></a>$object

```php
public \Category $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L30).


### <a name="property-$original_filter"></a>$original_filter

```php
private mixed $original_filter = ''
```





* Visibility: **private**
* Source: [controllers/admin/AdminCategoriesController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L44).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_category_to_move'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L36).


### <a name="property-$remove_products"></a>$remove_products

```php
public boolean $remove_products = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L39).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCategoriesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L46)




### <a name="method-ajaxProcessStatusCategory"></a>ajaxProcessStatusCategory

```php
mixed AdminCategoriesControllerCore::ajaxProcessStatusCategory()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 849](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L849)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L811)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
mixed AdminCategoriesControllerCore::getDescriptionClean($description)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCategoriesController.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L806)


#### Arguments
* $description **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L246)


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
* Source: [controllers/admin/AdminCategoriesController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L107)




### <a name="method-initContent"></a>initContent

```php
mixed AdminCategoriesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L187)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCategoriesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L166)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminCategoriesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L327)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCategoriesControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L267)




### <a name="method-postImage"></a>postImage

```php
mixed AdminCategoriesControllerCore::postImage($id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L776)


#### Arguments
* $id **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCategoriesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L623)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCategoriesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L644)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminCategoriesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 687](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L687)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminCategoriesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 713](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L713)




### <a name="method-processFatherlessProducts"></a>processFatherlessProducts

```php
mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L733)


#### Arguments
* $id_parent **mixed**



### <a name="method-processForceDeleteImage"></a>processForceDeleteImage

```php
mixed AdminCategoriesControllerCore::processForceDeleteImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 637](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L637)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminCategoriesControllerCore::processPosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 760](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L760)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCategoriesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L413)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCategoriesControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L355)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCategoriesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L206)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCategoriesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L261)




### <a name="method-setDeleteMode"></a>setDeleteMode

```php
mixed AdminCategoriesControllerCore::setDeleteMode()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L674)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCategoriesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCategoriesController.php#L199)



