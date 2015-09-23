Class AdminStockInstantStateControllerCore
=====================





* Class name: AdminStockInstantStateControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockInstantStateController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L30)


Contents
--------


### Properties

* [$stock_instant_state_warehouses](#property-$stock_instant_state_warehouses)

### Methods

* [__construct](#method-__construct)
* [getCurrentCoverageWarehouse](#method-getCurrentCoverageWarehouse)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [realQuantityCmp](#method-realQuantityCmp)
* [renderCSV](#method-renderCSV)
* [renderDetails](#method-renderDetails)
* [renderList](#method-renderList)
* [valuationCmp](#method-valuationCmp)




Properties
----------


### <a name="property-$stock_instant_state_warehouses"></a>$stock_instant_state_warehouses

```php
protected mixed $stock_instant_state_warehouses = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStockInstantStateController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStockInstantStateControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L34)




### <a name="method-getCurrentCoverageWarehouse"></a>getCurrentCoverageWarehouse

```php
integer AdminStockInstantStateControllerCore::getCurrentCoverageWarehouse()
```

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockInstantStateController.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L385)




### <a name="method-getList"></a>getList

```php
mixed AdminStockInstantStateControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L262)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminStockInstantStateControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L506)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStockInstantStateControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L109)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminStockInstantStateControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L516)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminStockInstantStateControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L401)




### <a name="method-realQuantityCmp"></a>realQuantityCmp

```php
mixed AdminStockInstantStateControllerCore::realQuantityCmp(array $n, array $m)
```

CMP



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L372)


#### Arguments
* $n **array**
* $m **array**



### <a name="method-renderCSV"></a>renderCSV

```php
mixed AdminStockInstantStateControllerCore::renderCSV()
```

Exports CSV



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L426)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminStockInstantStateControllerCore::renderDetails()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L209)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStockInstantStateControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L143)




### <a name="method-valuationCmp"></a>valuationCmp

```php
mixed AdminStockInstantStateControllerCore::valuationCmp(array $n, array $m)
```

CMP



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminStockInstantStateController.php#L358)


#### Arguments
* $n **array**
* $m **array**


