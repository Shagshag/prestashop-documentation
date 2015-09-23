Class CategoryControllerCore
=====================





* Class name: CategoryControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/CategoryController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L27)


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
* Source: [controllers/front/CategoryController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L30).


### <a name="property-$customer_access"></a>$customer_access

```php
public mixed $customer_access = true
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L31).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'category'
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L29).


Methods
-------


### <a name="method-assignProductList"></a>assignProductList

```php
mixed CategoryControllerCore::assignProductList()
```

Assign list of products template vars



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L180)




### <a name="method-assignScenes"></a>assignScenes

```php
mixed CategoryControllerCore::assignScenes()
```

Assign scenes template vars



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L138)




### <a name="method-assignSubcategories"></a>assignSubcategories

```php
mixed CategoryControllerCore::assignSubcategories()
```

Assign sub categories templates vars



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L165)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed CategoryControllerCore::canonicalRedirection($canonicalURL)
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L54)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-getCategory"></a>getCategory

```php
mixed CategoryControllerCore::getCategory()
```

Get instance of current category



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L219)




### <a name="method-init"></a>init

```php
mixed CategoryControllerCore::init()
```

Initialize category controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L71)




### <a name="method-initContent"></a>initContent

```php
mixed CategoryControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L98)




### <a name="method-setMedia"></a>setMedia

```php
mixed CategoryControllerCore::setMedia()
```

Set default medias for this controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CategoryController.php#L36)



