Class CmsControllerCore
=====================





* Class name: CmsControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/CmsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L27)


Contents
--------


### Properties

* [$assignCase](#property-$assignCase)
* [$cms](#property-$cms)
* [$cms_category](#property-$cms_category)
* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)

### Methods

* [canonicalRedirection](#method-canonicalRedirection)
* [init](#method-init)
* [initContent](#method-initContent)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$assignCase"></a>$assignCase

```php
public mixed $assignCase
```





* Visibility: **public**
* Source: [controllers/front/CmsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L30).


### <a name="property-$cms"></a>$cms

```php
public mixed $cms
```





* Visibility: **public**
* Source: [controllers/front/CmsController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L31).


### <a name="property-$cms_category"></a>$cms_category

```php
public \CMSCategory $cms_category
```





* Visibility: **public**
* Source: [controllers/front/CmsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L34).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'cms'
```





* Visibility: **public**
* Source: [controllers/front/CmsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L29).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = false
```





* Visibility: **public**
* Source: [controllers/front/CmsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L35).


Methods
-------


### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed CmsControllerCore::canonicalRedirection($canonicalURL)
```





* Visibility: **public**
* Source: [controllers/front/CmsController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L37)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-init"></a>init

```php
mixed CmsControllerCore::init()
```

Initialize cms controller



* Visibility: **public**
* Source: [controllers/front/CmsController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L53)




### <a name="method-initContent"></a>initContent

```php
mixed CmsControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/CmsController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L102)




### <a name="method-setMedia"></a>setMedia

```php
mixed CmsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/CmsController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CmsController.php#L87)



