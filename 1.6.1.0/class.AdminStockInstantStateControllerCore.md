Class AdminStockInstantStateControllerCore
=====================





* Class name: AdminStockInstantStateControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockInstantStateController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L31)


Contents
--------


### Properties

* [$object](#property-$object)
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


### <a name="property-$object"></a>$object

```php
public \Stock $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L31).


### <a name="property-$stock_instant_state_warehouses"></a>$stock_instant_state_warehouses

```php
protected mixed $stock_instant_state_warehouses = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStockInstantStateController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStockInstantStateControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L35)




### <a name="method-getCurrentCoverageWarehouse"></a>getCurrentCoverageWarehouse

```php
integer AdminStockInstantStateControllerCore::getCurrentCoverageWarehouse()
```

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminStockInstantStateController.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L415)




### <a name="method-getList"></a>getList

```php
mixed AdminStockInstantStateControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L271)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-initContent"></a>initContent

```php
mixed AdminStockInstantStateControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 536](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L536)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStockInstantStateControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L110)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminStockInstantStateControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L546)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminStockInstantStateControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L431)




### <a name="method-realQuantityCmp"></a>realQuantityCmp

```php
boolean AdminStockInstantStateControllerCore::realQuantityCmp(array $n, array $m)
```

CMP



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L402)


#### Arguments
* $n **array**
* $m **array**



### <a name="method-renderCSV"></a>renderCSV

```php
mixed AdminStockInstantStateControllerCore::renderCSV()
```

Exports CSV



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L456)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminStockInstantStateControllerCore::renderDetails()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L210)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStockInstantStateControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L144)




### <a name="method-valuationCmp"></a>valuationCmp

```php
boolean AdminStockInstantStateControllerCore::valuationCmp(array $n, array $m)
```

CMP



* Visibility: **public**
* Source: [controllers/admin/AdminStockInstantStateController.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminStockInstantStateController.php#L386)


#### Arguments
* $n **array**
* $m **array**


