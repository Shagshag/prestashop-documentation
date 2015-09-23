Class AdminCarriersControllerCore
=====================





* Class name: AdminCarriersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarriersController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L27)


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
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [processIsFree](#method-processIsFree)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_carrier'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCarriersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L31)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminCarriersControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L631)




### <a name="method-beforeDelete"></a>beforeDelete

```php
mixed AdminCarriersControllerCore::beforeDelete($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 584](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L584)


#### Arguments
* $object **mixed**



### <a name="method-changeGroups"></a>changeGroups

```php
mixed AdminCarriersControllerCore::changeGroups($id_carrier, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L589)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

```php
mixed AdminCarriersControllerCore::changeZones($id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L602)


#### Arguments
* $id **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed AdminCarriersControllerCore::displayDeleteLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L676)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed AdminCarriersControllerCore::displayEditLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L656)


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
* Source: [controllers/admin/AdminCarriersController.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L548)


#### Arguments
* $obj **object**



### <a name="method-getList"></a>getList

```php
mixed AdminCarriersControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

Modifying initial getList method to display position feature (drag and drop)



* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 622](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L622)


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
* Source: [controllers/admin/AdminCarriersController.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L119)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCarriersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L111)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCarriersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L395)




### <a name="method-processIsFree"></a>processIsFree

```php
mixed AdminCarriersControllerCore::processIsFree()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 532](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L532)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCarriersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L142)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCarriersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/controllers/admin/AdminCarriersController.php#L131)



