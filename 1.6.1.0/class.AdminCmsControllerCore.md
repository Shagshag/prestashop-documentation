Class AdminCmsControllerCore
=====================





* Class name: AdminCmsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCmsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L30)


Contents
--------


### Properties

* [$category](#property-$category)
* [$id_cms_category](#property-$id_cms_category)
* [$object](#property-$object)
* [$position_identifier](#property-$position_identifier)

### Methods

* [__construct](#method-__construct)
* [displayList](#method-displayList)
* [getPreviewUrl](#method-getPreviewUrl)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)




Properties
----------


### <a name="property-$category"></a>$category

```php
protected mixed $category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCmsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L32).


### <a name="property-$id_cms_category"></a>$id_cms_category

```php
public mixed $id_cms_category
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L34).


### <a name="property-$object"></a>$object

```php
public \CMS $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_cms'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCmsController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCmsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L38)




### <a name="method-displayList"></a>displayList

```php
mixed AdminCmsControllerCore::displayList($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L264)


#### Arguments
* $token **mixed**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminCmsControllerCore::getPreviewUrl(\CMS $cms)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L411)


#### Arguments
* $cms **[CMS](class.CMSCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCmsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L84)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCmsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L278)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCmsControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L99)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCmsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCmsController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCmsController.php#L249)



