Class AdminTrackingControllerCore
=====================





* Class name: AdminTrackingControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTrackingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L30)


Contents
--------


### Properties

* [$_helper_list](#property-$_helper_list)
* [$bootstrap](#property-$bootstrap)
* [$object](#property-$object)

### Methods

* [clearFilters](#method-clearFilters)
* [clearListOptions](#method-clearListOptions)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayEditLink](#method-displayEditLink)
* [displayEnableLink](#method-displayEnableLink)
* [getCustomListCategoriesEmpty](#method-getCustomListCategoriesEmpty)
* [getCustomListProductsAttributesNoStock](#method-getCustomListProductsAttributesNoStock)
* [getCustomListProductsDisabled](#method-getCustomListProductsDisabled)
* [getCustomListProductsNoStock](#method-getCustomListProductsNoStock)
* [getDescriptionClean](#method-getDescriptionClean)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [postprocess](#method-postprocess)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$_helper_list"></a>$_helper_list

```php
protected \HelperList $_helper_list
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTrackingController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L35).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = true
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L32).


### <a name="property-$object"></a>$object

```php
public \Product|\Category $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L30).


Methods
-------


### <a name="method-clearFilters"></a>clearFilters

```php
mixed AdminTrackingControllerCore::clearFilters()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTrackingController.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L303)




### <a name="method-clearListOptions"></a>clearListOptions

```php
mixed AdminTrackingControllerCore::clearListOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L318)




### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed AdminTrackingControllerCore::displayDeleteLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L285)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed AdminTrackingControllerCore::displayEditLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L294)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEnableLink"></a>displayEnableLink

```php
mixed AdminTrackingControllerCore::displayEnableLink($token, $id, $value, $active, $id_category, $id_product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L276)


#### Arguments
* $token **mixed**
* $id **mixed**
* $value **mixed**
* $active **mixed**
* $id_category **mixed**
* $id_product **mixed**



### <a name="method-getCustomListCategoriesEmpty"></a>getCustomListCategoriesEmpty

```php
mixed AdminTrackingControllerCore::getCustomListCategoriesEmpty()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L89)




### <a name="method-getCustomListProductsAttributesNoStock"></a>getCustomListProductsAttributesNoStock

```php
mixed AdminTrackingControllerCore::getCustomListProductsAttributesNoStock()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L126)




### <a name="method-getCustomListProductsDisabled"></a>getCustomListProductsDisabled

```php
mixed AdminTrackingControllerCore::getCustomListProductsDisabled()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L212)




### <a name="method-getCustomListProductsNoStock"></a>getCustomListProductsNoStock

```php
mixed AdminTrackingControllerCore::getCustomListProductsNoStock()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L169)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
mixed AdminTrackingControllerCore::getDescriptionClean($description)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTrackingController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L338)


#### Arguments
* $description **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminTrackingControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L333)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminTrackingControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L59)




### <a name="method-postprocess"></a>postprocess

```php
mixed AdminTrackingControllerCore::postprocess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L37)




### <a name="method-renderList"></a>renderList

```php
mixed AdminTrackingControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTrackingController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTrackingController.php#L243)



