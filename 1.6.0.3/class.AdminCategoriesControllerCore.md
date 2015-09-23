Class AdminCategoriesControllerCore
=====================





* Class name: AdminCategoriesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCategoriesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L27)


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
* Source: [controllers/admin/AdminCategoriesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L32).


### <a name="property-$disable_products"></a>$disable_products

```php
public boolean $disable_products = false
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L39).


### <a name="property-$original_filter"></a>$original_filter

```php
private mixed $original_filter = ''
```





* Visibility: **private**
* Source: [controllers/admin/AdminCategoriesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L41).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_category_to_move'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L33).


### <a name="property-$remove_products"></a>$remove_products

```php
public boolean $remove_products = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCategoriesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L43)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 786](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L786)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
string AdminCategoriesControllerCore::getDescriptionClean($description)
```

Allows to display the category description without HTML tags and slashes



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCategoriesController.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L781)


#### Arguments
* $description **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L237)


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
* Source: [controllers/admin/AdminCategoriesController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L102)




### <a name="method-initContent"></a>initContent

```php
mixed AdminCategoriesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L181)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCategoriesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L161)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminCategoriesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L316)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCategoriesControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L258)




### <a name="method-postImage"></a>postImage

```php
mixed AdminCategoriesControllerCore::postImage($id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 755](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L755)


#### Arguments
* $id **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCategoriesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L603)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCategoriesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L624)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminCategoriesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L667)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminCategoriesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L693)




### <a name="method-processFatherlessProducts"></a>processFatherlessProducts

```php
mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L712)


#### Arguments
* $id_parent **mixed**



### <a name="method-processForceDeleteImage"></a>processForceDeleteImage

```php
mixed AdminCategoriesControllerCore::processForceDeleteImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L617)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminCategoriesControllerCore::processPosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L739)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCategoriesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L401)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCategoriesControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L344)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCategoriesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L200)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCategoriesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L252)




### <a name="method-setDeleteMode"></a>setDeleteMode

```php
mixed AdminCategoriesControllerCore::setDeleteMode()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 654](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L654)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCategoriesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminCategoriesController.php#L193)



