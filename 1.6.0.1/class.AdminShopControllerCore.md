Class AdminShopControllerCore
=====================





* Class name: AdminShopControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminShopController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L28)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessTree](#method-ajaxProcessTree)
* [displayAjaxGetCategoriesFromRootCategory](#method-displayAjaxGetCategoriesFromRootCategory)
* [getList](#method-getList)
* [initCategoriesAssociation](#method-initCategoriesAssociation)
* [initContent](#method-initContent)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processDelete](#method-processDelete)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [viewAccess](#method-viewAccess)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminShopControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L30)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminShopControllerCore::afterAdd($new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L261)


#### Arguments
* $new_shop **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminShopControllerCore::afterUpdate($new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L283)


#### Arguments
* $new_shop **mixed**



### <a name="method-ajaxProcessTree"></a>ajaxProcessTree

```php
mixed AdminShopControllerCore::ajaxProcessTree()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L667)




### <a name="method-displayAjaxGetCategoriesFromRootCategory"></a>displayAjaxGetCategoriesFromRootCategory

```php
mixed AdminShopControllerCore::displayAjaxGetCategoriesFromRootCategory()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L193)




### <a name="method-getList"></a>getList

```php
mixed AdminShopControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L292)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initCategoriesAssociation"></a>initCategoriesAssociation

```php
mixed AdminShopControllerCore::initCategoriesAssociation($id_root)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L639)


#### Arguments
* $id_root **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminShopControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L147)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminShopControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L84)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminShopControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L212)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminShopControllerCore::processAdd()
```

Object creation



* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L580)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminShopControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L245)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminShopControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L309)




### <a name="method-renderList"></a>renderList

```php
mixed AdminShopControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L171)




### <a name="method-viewAccess"></a>viewAccess

```php
mixed AdminShopControllerCore::viewAccess($disable)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminShopController.php#L79)


#### Arguments
* $disable **mixed**


