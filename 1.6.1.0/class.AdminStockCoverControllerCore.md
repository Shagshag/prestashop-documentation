Class AdminStockCoverControllerCore
=====================





* Class name: AdminStockCoverControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockCoverController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L31)


Contents
--------


### Properties

* [$object](#property-$object)
* [$stock_cover_periods](#property-$stock_cover_periods)
* [$stock_cover_warehouses](#property-$stock_cover_warehouses)

### Methods

* [__construct](#method-__construct)
* [getCurrentCoveragePeriod](#method-getCurrentCoveragePeriod)
* [getCurrentCoverageWarehouse](#method-getCurrentCoverageWarehouse)
* [getCurrentWarning](#method-getCurrentWarning)
* [getList](#method-getList)
* [getQuantitySold](#method-getQuantitySold)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [renderDetails](#method-renderDetails)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Product $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L31).


### <a name="property-$stock_cover_periods"></a>$stock_cover_periods

```php
protected mixed $stock_cover_periods
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L34).


### <a name="property-$stock_cover_warehouses"></a>$stock_cover_warehouses

```php
protected mixed $stock_cover_warehouses
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStockCoverControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L36)




### <a name="method-getCurrentCoveragePeriod"></a>getCurrentCoveragePeriod

```php
integer AdminStockCoverControllerCore::getCurrentCoveragePeriod()
```

Gets the current coverage period used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L308)




### <a name="method-getCurrentCoverageWarehouse"></a>getCurrentCoverageWarehouse

```php
integer AdminStockCoverControllerCore::getCurrentCoverageWarehouse()
```

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L326)




### <a name="method-getCurrentWarning"></a>getCurrentWarning

```php
integer AdminStockCoverControllerCore::getCurrentWarning()
```

Gets the current warning



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L344)




### <a name="method-getList"></a>getList

```php
mixed AdminStockCoverControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L218)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-getQuantitySold"></a>getQuantitySold

```php
integer AdminStockCoverControllerCore::getQuantitySold(integer $id_product, integer $id_product_attribute, integer $coverage)
```

For a given product, and a given period, returns the quantity sold



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L365)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**



### <a name="method-initContent"></a>initContent

```php
mixed AdminStockCoverControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L383)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStockCoverControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L106)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminStockCoverControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L393)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminStockCoverControllerCore::renderDetails()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L123)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStockCoverControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockCoverController.php#L162)



