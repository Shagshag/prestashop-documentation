Class AdminStockCoverControllerCore
=====================





* Class name: AdminStockCoverControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockCoverController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L30)


Contents
--------


### Properties

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


### <a name="property-$stock_cover_periods"></a>$stock_cover_periods

```php
protected mixed $stock_cover_periods
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L33).


### <a name="property-$stock_cover_warehouses"></a>$stock_cover_warehouses

```php
protected mixed $stock_cover_warehouses
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStockCoverControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L35)




### <a name="method-getCurrentCoveragePeriod"></a>getCurrentCoveragePeriod

```php
integer AdminStockCoverControllerCore::getCurrentCoveragePeriod()
```

Gets the current coverage period used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L298)




### <a name="method-getCurrentCoverageWarehouse"></a>getCurrentCoverageWarehouse

```php
integer AdminStockCoverControllerCore::getCurrentCoverageWarehouse()
```

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L316)




### <a name="method-getCurrentWarning"></a>getCurrentWarning

```php
integer AdminStockCoverControllerCore::getCurrentWarning()
```

Gets the current warning



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L334)




### <a name="method-getList"></a>getList

```php
mixed AdminStockCoverControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L208)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getQuantitySold"></a>getQuantitySold

```php
integer AdminStockCoverControllerCore::getQuantitySold(integer $id_product, integer $id_product_attribute, integer $coverage)
```

For a given product, and a given period, returns the quantity sold



* Visibility: **protected**
* Source: [controllers/admin/AdminStockCoverController.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L355)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $coverage **integer**



### <a name="method-initContent"></a>initContent

```php
mixed AdminStockCoverControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L373)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStockCoverControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L105)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminStockCoverControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L383)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminStockCoverControllerCore::renderDetails()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L122)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStockCoverControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockCoverController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminStockCoverController.php#L161)



