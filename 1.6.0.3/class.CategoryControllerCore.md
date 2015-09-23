Class CategoryControllerCore
=====================





* Class name: CategoryControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/CategoryController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L27)


Contents
--------


### Properties

* [$category](#property-$category)
* [$customer_access](#property-$customer_access)
* [$php_self](#property-$php_self)

### Methods

* [assignProductList](#method-assignProductList)
* [assignScenes](#method-assignScenes)
* [assignSubcategories](#method-assignSubcategories)
* [canonicalRedirection](#method-canonicalRedirection)
* [getCategory](#method-getCategory)
* [init](#method-init)
* [initContent](#method-initContent)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$category"></a>$category

```php
protected mixed $category
```





* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L30).


### <a name="property-$customer_access"></a>$customer_access

```php
public mixed $customer_access = true
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L31).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'category'
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L29).


Methods
-------


### <a name="method-assignProductList"></a>assignProductList

```php
mixed CategoryControllerCore::assignProductList()
```

Assign list of products template vars



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L179)




### <a name="method-assignScenes"></a>assignScenes

```php
mixed CategoryControllerCore::assignScenes()
```

Assign scenes template vars



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L137)




### <a name="method-assignSubcategories"></a>assignSubcategories

```php
mixed CategoryControllerCore::assignSubcategories()
```

Assign sub categories templates vars



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L164)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed CategoryControllerCore::canonicalRedirection($canonicalURL)
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L52)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-getCategory"></a>getCategory

```php
mixed CategoryControllerCore::getCategory()
```

Get instance of current category



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L218)




### <a name="method-init"></a>init

```php
mixed CategoryControllerCore::init()
```

Initialize category controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L69)




### <a name="method-initContent"></a>initContent

```php
mixed CategoryControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L96)




### <a name="method-setMedia"></a>setMedia

```php
mixed CategoryControllerCore::setMedia()
```

Set default medias for this controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/front/CategoryController.php#L36)



