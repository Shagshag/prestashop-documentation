Class AdminCarriersControllerCore
=====================





* Class name: AdminCarriersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarriersController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L27)


Contents
--------


### Properties

* [$position_identifier](#property-$position_identifier)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [beforeDelete](#method-beforeDelete)
* [changeGroups](#method-changeGroups)
* [changeZones](#method-changeZones)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayEditLink](#method-displayEditLink)
* [getFieldsValues](#method-getFieldsValues)
* [getList](#method-getList)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initTabModuleList](#method-initTabModuleList)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [processIsFree](#method-processIsFree)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_carrier'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCarriersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L31)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminCarriersControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L644)




### <a name="method-beforeDelete"></a>beforeDelete

```php
mixed AdminCarriersControllerCore::beforeDelete($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L597)


#### Arguments
* $object **mixed**



### <a name="method-changeGroups"></a>changeGroups

```php
mixed AdminCarriersControllerCore::changeGroups($id_carrier, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L602)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

```php
mixed AdminCarriersControllerCore::changeZones($id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L615)


#### Arguments
* $id **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed AdminCarriersControllerCore::displayDeleteLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 689](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L689)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed AdminCarriersControllerCore::displayEditLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L669)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-getFieldsValues"></a>getFieldsValues

```php
mixed AdminCarriersControllerCore::getFieldsValues(object $obj)
```

Overload the property $fields_value



* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L561)


#### Arguments
* $obj **object**



### <a name="method-getList"></a>getList

```php
mixed AdminCarriersControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

Modifying initial getList method to display position feature (drag and drop)



* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 635](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L635)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCarriersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L122)




### <a name="method-initTabModuleList"></a>initTabModuleList

```php
mixed AdminCarriersControllerCore::initTabModuleList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 724](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L724)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCarriersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L114)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCarriersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L405)




### <a name="method-processIsFree"></a>processIsFree

```php
mixed AdminCarriersControllerCore::processIsFree()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L545)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCarriersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L152)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCarriersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L145)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCarriersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminCarriersController.php#L135)



