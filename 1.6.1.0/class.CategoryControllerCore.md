Class CategoryControllerCore
=====================





* Class name: CategoryControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/CategoryController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L27)


Contents
--------


### Properties

* [$cat_products](#property-$cat_products)
* [$category](#property-$category)
* [$customer_access](#property-$customer_access)
* [$nbProducts](#property-$nbProducts)
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


### <a name="property-$cat_products"></a>$cat_products

```php
protected array $cat_products
```





* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L42).


### <a name="property-$category"></a>$category

```php
protected \Category $category
```





* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L33).


### <a name="property-$customer_access"></a>$customer_access

```php
public boolean $customer_access = true
```





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L36).


### <a name="property-$nbProducts"></a>$nbProducts

```php
protected integer $nbProducts
```





* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L39).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'category'
```

string Internal controller name



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L30).


Methods
-------


### <a name="method-assignProductList"></a>assignProductList

```php
mixed CategoryControllerCore::assignProductList()
```

Assigns product list template variables



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L213)




### <a name="method-assignScenes"></a>assignScenes

```php
mixed CategoryControllerCore::assignScenes()
```

Assigns scenes template variables



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L171)




### <a name="method-assignSubcategories"></a>assignSubcategories

```php
mixed CategoryControllerCore::assignSubcategories()
```

Assigns subcategory templates variables



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L198)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed CategoryControllerCore::canonicalRedirection(string $canonical_url)
```

Redirects to canonical or "Not Found" URL



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L76)


#### Arguments
* $canonical_url **string**



### <a name="method-getCategory"></a>getCategory

```php
\Category CategoryControllerCore::getCategory()
```

Returns an instance of the current category



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L254)




### <a name="method-init"></a>init

```php
mixed CategoryControllerCore::init()
```

Initializes controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L97)




### <a name="method-initContent"></a>initContent

```php
mixed CategoryControllerCore::initContent()
```

Initializes page content variables



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L129)




### <a name="method-setMedia"></a>setMedia

```php
mixed CategoryControllerCore::setMedia()
```

Sets default medias for this controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/CategoryController.php#L47)



