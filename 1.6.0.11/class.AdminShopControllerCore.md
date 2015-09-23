Class AdminShopControllerCore
=====================





* Class name: AdminShopControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminShopController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L28)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessTree](#method-ajaxProcessTree)
* [displayAjaxGetCategoriesFromRootCategory](#method-displayAjaxGetCategoriesFromRootCategory)
* [displayEditLink](#method-displayEditLink)
* [getList](#method-getList)
* [initCategoriesAssociation](#method-initCategoriesAssociation)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
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
* Source: [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L30)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminShopControllerCore::afterAdd($new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L285)


#### Arguments
* $new_shop **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminShopControllerCore::afterUpdate($new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L307)


#### Arguments
* $new_shop **mixed**



### <a name="method-ajaxProcessTree"></a>ajaxProcessTree

```php
mixed AdminShopControllerCore::ajaxProcessTree()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L727)




### <a name="method-displayAjaxGetCategoriesFromRootCategory"></a>displayAjaxGetCategoriesFromRootCategory

```php
mixed AdminShopControllerCore::displayAjaxGetCategoriesFromRootCategory()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L217)




### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed AdminShopControllerCore::displayEditLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 679](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L679)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminShopControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L330)


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
* Source: [controllers/admin/AdminShopController.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L699)


#### Arguments
* $id_root **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminShopControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L135)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminShopControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L89)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminShopControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L115)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminShopControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L233)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminShopControllerCore::processAdd()
```

Object creation



* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L620)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminShopControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L269)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminShopControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L347)




### <a name="method-renderList"></a>renderList

```php
mixed AdminShopControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L195)




### <a name="method-viewAccess"></a>viewAccess

```php
mixed AdminShopControllerCore::viewAccess($disable)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminShopController.php#L84)


#### Arguments
* $disable **mixed**


