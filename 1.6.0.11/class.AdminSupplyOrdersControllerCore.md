Class AdminSupplyOrdersControllerCore
=====================





* Class name: AdminSupplyOrdersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminSupplyOrdersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L30)


Contents
--------


### Properties

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


### <a name="property-$warehouses"></a>$warehouses

```php
protected mixed $warehouses
```





* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L35).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminSupplyOrdersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L37)




### <a name="method-afterAdd"></a>afterAdd

```php
boolean AdminSupplyOrdersControllerCore::afterAdd(\ObjectModel $object)
```

Overrides AdminController::afterAdd()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2002](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L2002)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-ajaxProcessSearchProduct"></a>ajaxProcessSearchProduct

```php
mixed AdminSupplyOrdersControllerCore::ajaxProcessSearchProduct()
```

method call when ajax request is made for search product to add to the order



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1654](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1654)




### <a name="method-beforeAdd"></a>beforeAdd

```php
mixed AdminSupplyOrdersControllerCore::beforeAdd(\ObjectModel $object)
```

Overrides AdminController::beforeAdd()



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L2115)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-displayChangestateLink"></a>displayChangestateLink

```php
string AdminSupplyOrdersControllerCore::displayChangestateLink(string $token, integer $id)
```

Display receipt action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1509)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayCreateSupplyOrderLink"></a>displayCreateSupplyOrderLink

```php
string AdminSupplyOrdersControllerCore::displayCreateSupplyOrderLink(string $token, integer $id)
```

Display state action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1530)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayUpdateReceiptLink"></a>displayUpdateReceiptLink

```php
string AdminSupplyOrdersControllerCore::displayUpdateReceiptLink(string $token, integer $id)
```

Display state action link



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1488](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1488)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getCurrentWarehouse"></a>getCurrentWarehouse

```php
integer AdminSupplyOrdersControllerCore::getCurrentWarehouse()
```

Gets the current warehouse used



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L2166)




### <a name="method-getFilterStatus"></a>getFilterStatus

```php
integer AdminSupplyOrdersControllerCore::getFilterStatus()
```

Gets the current filter used



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L2184)




### <a name="method-getList"></a>getList

```php
mixed AdminSupplyOrdersControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L376)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-init"></a>init

```php
mixed AdminSupplyOrdersControllerCore::init()
```

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L115)




### <a name="method-initChangeStateContent"></a>initChangeStateContent

```php
mixed AdminSupplyOrdersControllerCore::initChangeStateContent()
```

Init the content of change state action



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L586)




### <a name="method-initContent"></a>initContent

```php
mixed AdminSupplyOrdersControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L911)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminSupplyOrdersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L154)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminSupplyOrdersControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L2195)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminSupplyOrdersControllerCore::initToolbar()
```

Assigns default actions in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1960](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1960)




### <a name="method-initUpdateReceiptContent"></a>initUpdateReceiptContent

```php
mixed AdminSupplyOrdersControllerCore::initUpdateReceiptContent()
```

Inits the content of 'update_receipt' action
Called in initContent()



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L747)




### <a name="method-initUpdateSupplyOrderContent"></a>initUpdateSupplyOrderContent

```php
mixed AdminSupplyOrdersControllerCore::initUpdateSupplyOrderContent()
```

Init the content of change state action



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L685)




### <a name="method-loadProducts"></a>loadProducts

```php
mixed AdminSupplyOrdersControllerCore::loadProducts(integer $threshold)
```

Loads products which quantity (hysical quantity) is equal or less than $threshold



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2015](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L2015)


#### Arguments
* $threshold **integer**



### <a name="method-manageOrderProducts"></a>manageOrderProducts

```php
mixed AdminSupplyOrdersControllerCore::manageOrderProducts()
```

Ths method manage associated products to the order when updating it



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L946)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminSupplyOrdersControllerCore::postProcess()
```

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1093](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1093)




### <a name="method-postProcessCopyFromTemplate"></a>postProcessCopyFromTemplate

```php
mixed AdminSupplyOrdersControllerCore::postProcessCopyFromTemplate()
```

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 2127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L2127)




### <a name="method-postProcessUpdateReceipt"></a>postProcessUpdateReceipt

```php
mixed AdminSupplyOrdersControllerCore::postProcessUpdateReceipt()
```

Helper function for AdminSupplyOrdersController::postProcess()



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1369)




### <a name="method-printExportIcons"></a>printExportIcons

```php
string AdminSupplyOrdersControllerCore::printExportIcons(integer $id_supply_order, string $tr)
```

Callback used to display custom content for a given field



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1930](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1930)


#### Arguments
* $id_supply_order **integer**
* $tr **string**



### <a name="method-renderCSV"></a>renderCSV

```php
mixed AdminSupplyOrdersControllerCore::renderCSV()
```

Exports CSV



* Visibility: **protected**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1277](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1277)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminSupplyOrdersControllerCore::renderDetails()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1549](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1549)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminSupplyOrdersControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L183)




### <a name="method-renderList"></a>renderList

```php
mixed AdminSupplyOrdersControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L448)




### <a name="method-renderView"></a>renderView

```php
mixed AdminSupplyOrdersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminSupplyOrdersController.php line 1717](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminSupplyOrdersController.php#L1717)



