Class AdminWarehousesControllerCore
=====================





* Class name: AdminWarehousesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminWarehousesController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L31)


Contents
--------


### Properties

* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [processAdd](#method-processAdd)
* [processDelete](#method-processDelete)
* [processUpdate](#method-processUpdate)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [updateAddress](#method-updateAddress)
* [updateAssoShop](#method-updateAssoShop)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Warehouse $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminWarehousesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L33)




### <a name="method-afterAdd"></a>afterAdd

```php
boolean AdminWarehousesControllerCore::afterAdd(\Warehouse $object)
```

Called once $object is set.

Used to process the associations with address/shops/carriers

* Visibility: **protected**
* Source: [controllers/admin/AdminWarehousesController.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L459)


#### Arguments
* $object **[Warehouse](class.WarehouseCore.md)**



### <a name="method-getList"></a>getList

```php
mixed AdminWarehousesControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L492)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-initContent"></a>initContent

```php
mixed AdminWarehousesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L519)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminWarehousesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L86)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminWarehousesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L529)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminWarehousesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L542)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminWarehousesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L609)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminWarehousesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L640)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminWarehousesControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L141)




### <a name="method-renderList"></a>renderList

```php
mixed AdminWarehousesControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L102)




### <a name="method-renderView"></a>renderView

```php
mixed AdminWarehousesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminWarehousesController.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L416)




### <a name="method-updateAddress"></a>updateAddress

```php
mixed AdminWarehousesControllerCore::updateAddress()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWarehousesController.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L558)




### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminWarehousesControllerCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminWarehousesController.php line 659](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminWarehousesController.php#L659)


#### Arguments
* $id_object **mixed**


