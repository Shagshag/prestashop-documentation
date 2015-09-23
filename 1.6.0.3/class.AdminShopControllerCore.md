Class AdminShopControllerCore
=====================





* Class name: AdminShopControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminShopController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L28)


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
* Source: [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L30)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminShopControllerCore::afterAdd($new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L281)


#### Arguments
* $new_shop **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminShopControllerCore::afterUpdate($new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L303)


#### Arguments
* $new_shop **mixed**



### <a name="method-ajaxProcessTree"></a>ajaxProcessTree

```php
mixed AdminShopControllerCore::ajaxProcessTree()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L693)




### <a name="method-displayAjaxGetCategoriesFromRootCategory"></a>displayAjaxGetCategoriesFromRootCategory

```php
mixed AdminShopControllerCore::displayAjaxGetCategoriesFromRootCategory()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L212)




### <a name="method-getList"></a>getList

```php
mixed AdminShopControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L315)


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
* Source: [controllers/admin/AdminShopController.php line 665](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L665)


#### Arguments
* $id_root **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminShopControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L130)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminShopControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L84)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminShopControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L110)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminShopControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L232)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminShopControllerCore::processAdd()
```

Object creation



* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L604)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminShopControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L265)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminShopControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 332](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L332)




### <a name="method-renderList"></a>renderList

```php
mixed AdminShopControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L190)




### <a name="method-viewAccess"></a>viewAccess

```php
mixed AdminShopControllerCore::viewAccess($disable)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminShopController.php#L79)


#### Arguments
* $disable **mixed**


