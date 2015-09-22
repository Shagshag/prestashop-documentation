Class AdminGroupsControllerCore
=====================





* Class name: AdminGroupsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessAddCategoryReduction](#method-ajaxProcessAddCategoryReduction)
* [displayEditLink](#method-displayEditLink)
* [formatCategoryDiscountList](#method-formatCategoryDiscountList)
* [formatModuleListAuth](#method-formatModuleListAuth)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [printShowPricesIcon](#method-printShowPricesIcon)
* [processChangeShowPricesVal](#method-processChangeShowPricesVal)
* [processSave](#method-processSave)
* [renderCustomersList](#method-renderCustomersList)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [setMedia](#method-setMedia)
* [updateCategoryReduction](#method-updateCategoryReduction)
* [updateRestrictions](#method-updateRestrictions)
* [validateDiscount](#method-validateDiscount)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Group $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminGroupsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L32)




### <a name="method-ajaxProcessAddCategoryReduction"></a>ajaxProcessAddCategoryReduction

```php
mixed AdminGroupsControllerCore::ajaxProcessAddCategoryReduction()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L451)




### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed AdminGroupsControllerCore::displayEditLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L585)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-formatCategoryDiscountList"></a>formatCategoryDiscountList

```php
mixed AdminGroupsControllerCore::formatCategoryDiscountList($id_group)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L355)


#### Arguments
* $id_group **mixed**



### <a name="method-formatModuleListAuth"></a>formatModuleListAuth

```php
mixed AdminGroupsControllerCore::formatModuleListAuth($id_group)
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L385)


#### Arguments
* $id_group **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminGroupsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L159)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminGroupsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L171)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminGroupsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L147)




### <a name="method-printShowPricesIcon"></a>printShowPricesIcon

```php
string AdminGroupsControllerCore::printShowPricesIcon($id_group, $tr)
```

Print enable / disable icon for show prices option



* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L549)


#### Arguments
* $id_group **mixed** - integer Group ID
* $tr **mixed** - array Row data



### <a name="method-processChangeShowPricesVal"></a>processChangeShowPricesVal

```php
mixed AdminGroupsControllerCore::processChangeShowPricesVal()
```

Toggle show prices flag



* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L530)




### <a name="method-processSave"></a>processSave

```php
mixed AdminGroupsControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L430)




### <a name="method-renderCustomersList"></a>renderCustomersList

```php
mixed AdminGroupsControllerCore::renderCustomersList($group)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L207)


#### Arguments
* $group **mixed**



### <a name="method-renderForm"></a>renderForm

```php
mixed AdminGroupsControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L247)




### <a name="method-renderList"></a>renderList

```php
mixed AdminGroupsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L559)




### <a name="method-renderView"></a>renderView

```php
mixed AdminGroupsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L191)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminGroupsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L140)




### <a name="method-updateCategoryReduction"></a>updateCategoryReduction

```php
mixed AdminGroupsControllerCore::updateCategoryReduction()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L493)




### <a name="method-updateRestrictions"></a>updateRestrictions

```php
mixed AdminGroupsControllerCore::updateRestrictions()
```

Update (or create) restrictions for modules by group



* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L480)




### <a name="method-validateDiscount"></a>validateDiscount

```php
mixed AdminGroupsControllerCore::validateDiscount($reduction)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminGroupsController.php#L443)


#### Arguments
* $reduction **mixed**


