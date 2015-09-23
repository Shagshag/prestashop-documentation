Class AdminCategoriesControllerCore
=====================





* Class name: AdminCategoriesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCategoriesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L27)


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
* Source: [controllers/admin/AdminCategoriesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L32).


### <a name="property-$disable_products"></a>$disable_products

```php
public boolean $disable_products = false
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L39).


### <a name="property-$original_filter"></a>$original_filter

```php
private mixed $original_filter = ''
```





* Visibility: **private**
* Source: [controllers/admin/AdminCategoriesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L41).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_category_to_move'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L33).


### <a name="property-$remove_products"></a>$remove_products

```php
public boolean $remove_products = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCategoriesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L43)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 784](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L784)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
string AdminCategoriesControllerCore::getDescriptionClean($description)
```

Allows to display the category description without HTML tags and slashes



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCategoriesController.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L779)


#### Arguments
* $description **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L235)


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
* Source: [controllers/admin/AdminCategoriesController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L102)




### <a name="method-initContent"></a>initContent

```php
mixed AdminCategoriesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L179)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCategoriesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L161)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminCategoriesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L314)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCategoriesControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L256)




### <a name="method-postImage"></a>postImage

```php
mixed AdminCategoriesControllerCore::postImage($id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L753)


#### Arguments
* $id **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCategoriesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 601](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L601)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCategoriesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 622](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L622)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminCategoriesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 665](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L665)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminCategoriesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L691)




### <a name="method-processFatherlessProducts"></a>processFatherlessProducts

```php
mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L710)


#### Arguments
* $id_parent **mixed**



### <a name="method-processForceDeleteImage"></a>processForceDeleteImage

```php
mixed AdminCategoriesControllerCore::processForceDeleteImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L615)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminCategoriesControllerCore::processPosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 737](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L737)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCategoriesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L399)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCategoriesControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L342)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCategoriesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L198)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCategoriesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L250)




### <a name="method-setDeleteMode"></a>setDeleteMode

```php
mixed AdminCategoriesControllerCore::setDeleteMode()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L652)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCategoriesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminCategoriesController.php#L191)



