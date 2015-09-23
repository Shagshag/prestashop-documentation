Class AdminGroupsControllerCore
=====================





* Class name: AdminGroupsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminGroupsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L27)


Contents
--------



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






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminGroupsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L29)




### <a name="method-ajaxProcessAddCategoryReduction"></a>ajaxProcessAddCategoryReduction

```php
mixed AdminGroupsControllerCore::ajaxProcessAddCategoryReduction()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L445)




### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed AdminGroupsControllerCore::displayEditLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L579)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-formatCategoryDiscountList"></a>formatCategoryDiscountList

```php
mixed AdminGroupsControllerCore::formatCategoryDiscountList($id_group)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L349)


#### Arguments
* $id_group **mixed**



### <a name="method-formatModuleListAuth"></a>formatModuleListAuth

```php
mixed AdminGroupsControllerCore::formatModuleListAuth($id_group)
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L379)


#### Arguments
* $id_group **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminGroupsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L155)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminGroupsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L167)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminGroupsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L143)




### <a name="method-printShowPricesIcon"></a>printShowPricesIcon

```php
string AdminGroupsControllerCore::printShowPricesIcon($id_group, $tr)
```

Print enable / disable icon for show prices option



* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 543](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L543)


#### Arguments
* $id_group **mixed** - integer Group ID
* $tr **mixed** - array Row data



### <a name="method-processChangeShowPricesVal"></a>processChangeShowPricesVal

```php
mixed AdminGroupsControllerCore::processChangeShowPricesVal()
```

Toggle show prices flag



* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L524)




### <a name="method-processSave"></a>processSave

```php
mixed AdminGroupsControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L424)




### <a name="method-renderCustomersList"></a>renderCustomersList

```php
mixed AdminGroupsControllerCore::renderCustomersList($group)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L203)


#### Arguments
* $group **mixed**



### <a name="method-renderForm"></a>renderForm

```php
mixed AdminGroupsControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L241)




### <a name="method-renderList"></a>renderList

```php
mixed AdminGroupsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L553)




### <a name="method-renderView"></a>renderView

```php
mixed AdminGroupsControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L187)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminGroupsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminGroupsController.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L136)




### <a name="method-updateCategoryReduction"></a>updateCategoryReduction

```php
mixed AdminGroupsControllerCore::updateCategoryReduction()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L487)




### <a name="method-updateRestrictions"></a>updateRestrictions

```php
mixed AdminGroupsControllerCore::updateRestrictions()
```

Update (or create) restrictions for modules by group



* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L474)




### <a name="method-validateDiscount"></a>validateDiscount

```php
mixed AdminGroupsControllerCore::validateDiscount($reduction)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminGroupsController.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminGroupsController.php#L437)


#### Arguments
* $reduction **mixed**


