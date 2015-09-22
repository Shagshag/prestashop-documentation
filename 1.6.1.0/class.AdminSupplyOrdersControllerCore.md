Class AdminSupplyOrdersControllerCore
=====================





* Class name: AdminSupplyOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminSupplyOrdersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L31)


Contents
--------


### Properties

* [$object](#property-$object)
* [$warehouses](#property-$warehouses)

### Methods

* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [ajaxProcessSearchProduct](#method-ajaxProcessSearchProduct)
* [beforeAdd](#method-beforeAdd)
* [displayChangestateLink](#method-displayChangestateLink)
* [displayCreateSupplyOrderLink](#method-displayCreateSupplyOrderLink)
* [displayUpdateReceiptLink](#method-displayUpdateReceiptLink)
* [getCurrentWarehouse](#method-getCurrentWarehouse)
* [getFilterStatus](#method-getFilterStatus)
* [getList](#method-getList)
* [init](#method-init)
* [initChangeStateContent](#method-initChangeStateContent)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initUpdateReceiptContent](#method-initUpdateReceiptContent)
* [initUpdateSupplyOrderContent](#method-initUpdateSupplyOrderContent)
* [loadProducts](#method-loadProducts)
* [manageOrderProducts](#method-manageOrderProducts)
* [postProcess](#method-postProcess)
* [postProcessCopyFromTemplate](#method-postProcessCopyFromTemplate)
* [postProcessUpdateReceipt](#method-postProcessUpdateReceipt)
* [printExportIcons](#method-printExportIcons)
* [renderCSV](#method-renderCSV)
* [renderDetails](#method-renderDetails)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \SupplyOrder $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L31).


### <a name="property-$warehouses"></a>$warehouses

```php
protected array $warehouses
```





* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminSupplyOrdersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L38)




### <a name="method-afterAdd"></a>afterAdd

```php
boolean AdminSupplyOrdersControllerCore::afterAdd(\ObjectModel $object)
```

Overrides AdminController::afterAdd()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2039](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L2039)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-ajaxProcessSearchProduct"></a>ajaxProcessSearchProduct

```php
mixed AdminSupplyOrdersControllerCore::ajaxProcessSearchProduct()
```

method call when ajax request is made for search product to add to the order



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1691](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1691)




### <a name="method-beforeAdd"></a>beforeAdd

```php
true AdminSupplyOrdersControllerCore::beforeAdd(\SupplyOrder $object)
```

Overrides AdminController::beforeAdd()



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L2155)


#### Arguments
* $object **[SupplyOrder](class.SupplyOrderCore.md)**



### <a name="method-displayChangestateLink"></a>displayChangestateLink

```php
string AdminSupplyOrdersControllerCore::displayChangestateLink(string $token, integer $id)
```

Display receipt action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1546)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayCreateSupplyOrderLink"></a>displayCreateSupplyOrderLink

```php
string AdminSupplyOrdersControllerCore::displayCreateSupplyOrderLink(string $token, integer $id)
```

Display state action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1567](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1567)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayUpdateReceiptLink"></a>displayUpdateReceiptLink

```php
string AdminSupplyOrdersControllerCore::displayUpdateReceiptLink(string $token, integer $id)
```

Display state action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1525](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1525)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getCurrentWarehouse"></a>getCurrentWarehouse

```php
integer AdminSupplyOrdersControllerCore::getCurrentWarehouse()
```

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L2206)




### <a name="method-getFilterStatus"></a>getFilterStatus

```php
integer AdminSupplyOrdersControllerCore::getFilterStatus()
```

Gets the current filter used



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L2224)




### <a name="method-getList"></a>getList

```php
mixed AdminSupplyOrdersControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L386)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-init"></a>init

```php
mixed AdminSupplyOrdersControllerCore::init()
```

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L116)




### <a name="method-initChangeStateContent"></a>initChangeStateContent

```php
mixed AdminSupplyOrdersControllerCore::initChangeStateContent()
```

Init the content of change state action



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L595)




### <a name="method-initContent"></a>initContent

```php
mixed AdminSupplyOrdersControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 920](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L920)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminSupplyOrdersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L155)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminSupplyOrdersControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L2235)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminSupplyOrdersControllerCore::initToolbar()
```

Assigns default actions in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1997](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1997)




### <a name="method-initUpdateReceiptContent"></a>initUpdateReceiptContent

```php
mixed AdminSupplyOrdersControllerCore::initUpdateReceiptContent()
```

Inits the content of 'update_receipt' action
Called in initContent()



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 756](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L756)




### <a name="method-initUpdateSupplyOrderContent"></a>initUpdateSupplyOrderContent

```php
mixed AdminSupplyOrdersControllerCore::initUpdateSupplyOrderContent()
```

Init the content of change state action



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L694)




### <a name="method-loadProducts"></a>loadProducts

```php
mixed AdminSupplyOrdersControllerCore::loadProducts(integer $threshold)
```

Loads products which quantity (hysical quantity) is equal or less than $threshold



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2052](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L2052)


#### Arguments
* $threshold **integer**



### <a name="method-manageOrderProducts"></a>manageOrderProducts

```php
mixed AdminSupplyOrdersControllerCore::manageOrderProducts()
```

Ths method manage associated products to the order when updating it



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 955](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L955)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminSupplyOrdersControllerCore::postProcess()
```

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1102)




### <a name="method-postProcessCopyFromTemplate"></a>postProcessCopyFromTemplate

```php
mixed AdminSupplyOrdersControllerCore::postProcessCopyFromTemplate()
```

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L2167)




### <a name="method-postProcessUpdateReceipt"></a>postProcessUpdateReceipt

```php
mixed AdminSupplyOrdersControllerCore::postProcessUpdateReceipt()
```

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1406)




### <a name="method-printExportIcons"></a>printExportIcons

```php
string AdminSupplyOrdersControllerCore::printExportIcons(integer $id_supply_order, string $tr)
```

Callback used to display custom content for a given field



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1967](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1967)


#### Arguments
* $id_supply_order **integer**
* $tr **string**



### <a name="method-renderCSV"></a>renderCSV

```php
mixed AdminSupplyOrdersControllerCore::renderCSV()
```

Exports CSV



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1314)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminSupplyOrdersControllerCore::renderDetails()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1586)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminSupplyOrdersControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L184)




### <a name="method-renderList"></a>renderList

```php
mixed AdminSupplyOrdersControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L457)




### <a name="method-renderView"></a>renderView

```php
mixed AdminSupplyOrdersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1754](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminSupplyOrdersController.php#L1754)



