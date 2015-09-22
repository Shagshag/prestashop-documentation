Class AdminShopControllerCore
=====================





* Class name: AdminShopControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

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




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Shop $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminShopControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L32)




### <a name="method-afterAdd"></a>afterAdd

```php
boolean AdminShopControllerCore::afterAdd(\Shop $new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L292)


#### Arguments
* $new_shop **[Shop](class.ShopCore.md)**



### <a name="method-afterUpdate"></a>afterUpdate

```php
boolean AdminShopControllerCore::afterUpdate(\Shop $new_shop)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L318)


#### Arguments
* $new_shop **[Shop](class.ShopCore.md)**



### <a name="method-ajaxProcessTree"></a>ajaxProcessTree

```php
mixed AdminShopControllerCore::ajaxProcessTree()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 741](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L741)




### <a name="method-displayAjaxGetCategoriesFromRootCategory"></a>displayAjaxGetCategoriesFromRootCategory

```php
mixed AdminShopControllerCore::displayAjaxGetCategoriesFromRootCategory()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L219)




### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed AdminShopControllerCore::displayEditLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L693)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminShopControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L341)


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
* Source: [controllers/admin/AdminShopController.php line 713](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L713)


#### Arguments
* $id_root **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminShopControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L137)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminShopControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L91)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminShopControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L117)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminShopControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L235)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminShopControllerCore::processAdd()
```

Object creation



* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L633)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminShopControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L272)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminShopControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L358)




### <a name="method-renderList"></a>renderList

```php
mixed AdminShopControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L197)




### <a name="method-viewAccess"></a>viewAccess

```php
mixed AdminShopControllerCore::viewAccess($disable)
```





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminShopController.php#L86)


#### Arguments
* $disable **mixed**


