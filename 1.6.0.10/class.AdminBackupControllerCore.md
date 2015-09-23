Class AdminBackupControllerCore
=====================





* Class name: AdminBackupControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminBackupController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L27)


Contents
--------


### Properties

* [$sort_by](#property-$sort_by)

### Methods

* [__construct](#method-__construct)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initToolbar](#method-initToolbar)
* [initViewDownload](#method-initViewDownload)
* [intSort](#method-intSort)
* [loadObject](#method-loadObject)
* [postProcess](#method-postProcess)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [strSort](#method-strSort)




Properties
----------


### <a name="property-$sort_by"></a>$sort_by

```php
protected string $sort_by = 'date'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminBackupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminBackupControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L32)




### <a name="method-getList"></a>getList

```php
mixed AdminBackupControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L191)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminBackupControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L131)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminBackupControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L110)




### <a name="method-initViewDownload"></a>initViewDownload

```php
mixed AdminBackupControllerCore::initViewDownload()
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L103)




### <a name="method-intSort"></a>intSort

```php
mixed AdminBackupControllerCore::intSort($a, $b)
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L300)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-loadObject"></a>loadObject

```php
object AdminBackupControllerCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object
This method overrides the one in AdminTab because AdminTab assumes the id is a UnsignedInt
"Backups" Directory in admin directory must be writeable (CHMOD 777)



* Visibility: **protected**
* Source: [controllers/admin/AdminBackupController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L147)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminBackupControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L158)




### <a name="method-renderList"></a>renderList

```php
mixed AdminBackupControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L79)




### <a name="method-renderView"></a>renderView

```php
mixed AdminBackupControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L87)




### <a name="method-strSort"></a>strSort

```php
mixed AdminBackupControllerCore::strSort($a, $b)
```





* Visibility: **public**
* Source: [controllers/admin/AdminBackupController.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminBackupController.php#L306)


#### Arguments
* $a **mixed**
* $b **mixed**


