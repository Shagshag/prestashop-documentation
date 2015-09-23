Class ProductControllerCore
=====================





* Class name: ProductControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/ProductController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L27)


Contents
--------


### Properties

* [$category](#property-$category)
* [$php_self](#property-$php_self)
* [$product](#property-$product)

### Methods

* [assignAttributesCombinations](#method-assignAttributesCombinations)
* [assignAttributesGroups](#method-assignAttributesGroups)
* [assignCategory](#method-assignCategory)
* [assignImages](#method-assignImages)
* [assignPriceAndTax](#method-assignPriceAndTax)
* [canonicalRedirection](#method-canonicalRedirection)
* [formTargetFormat](#method-formTargetFormat)
* [formatQuantityDiscounts](#method-formatQuantityDiscounts)
* [getCategory](#method-getCategory)
* [getProduct](#method-getProduct)
* [init](#method-init)
* [initContent](#method-initContent)
* [pictureUpload](#method-pictureUpload)
* [setMedia](#method-setMedia)
* [textRecord](#method-textRecord)
* [transformDescriptionWithImg](#method-transformDescriptionWithImg)




Properties
----------


### <a name="property-$category"></a>$category

```php
protected mixed $category
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L32).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'product'
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L29).


### <a name="property-$product"></a>$product

```php
protected mixed $product
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L31).


Methods
-------


### <a name="method-assignAttributesCombinations"></a>assignAttributesCombinations

```php
mixed ProductControllerCore::assignAttributesCombinations()
```

Get and assign attributes combinations informations



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L518)




### <a name="method-assignAttributesGroups"></a>assignAttributesGroups

```php
mixed ProductControllerCore::assignAttributesGroups()
```

Assign template vars related to attribute groups and colors



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L397)




### <a name="method-assignCategory"></a>assignCategory

```php
mixed ProductControllerCore::assignCategory()
```

Assign template vars related to category



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 537](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L537)




### <a name="method-assignImages"></a>assignImages

```php
mixed ProductControllerCore::assignImages()
```

Assign template vars related to images



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L347)




### <a name="method-assignPriceAndTax"></a>assignPriceAndTax

```php
mixed ProductControllerCore::assignPriceAndTax()
```

Assign price and tax to the template



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L290)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed ProductControllerCore::canonicalRedirection($canonical_url)
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L63)


#### Arguments
* $canonical_url **mixed**



### <a name="method-formTargetFormat"></a>formTargetFormat

```php
mixed ProductControllerCore::formTargetFormat()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L636)




### <a name="method-formatQuantityDiscounts"></a>formatQuantityDiscounts

```php
mixed ProductControllerCore::formatQuantityDiscounts($specific_prices, $price, $tax_rate, $ecotax_amount)
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L647)


#### Arguments
* $specific_prices **mixed**
* $price **mixed**
* $tax_rate **mixed**
* $ecotax_amount **mixed**



### <a name="method-getCategory"></a>getCategory

```php
mixed ProductControllerCore::getCategory()
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 678](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L678)




### <a name="method-getProduct"></a>getProduct

```php
mixed ProductControllerCore::getProduct()
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 673](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L673)




### <a name="method-init"></a>init

```php
mixed ProductControllerCore::init()
```

Initialize product controller



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L75)




### <a name="method-initContent"></a>initContent

```php
mixed ProductControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L172)




### <a name="method-pictureUpload"></a>pictureUpload

```php
mixed ProductControllerCore::pictureUpload()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L577)




### <a name="method-setMedia"></a>setMedia

```php
mixed ProductControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L34)




### <a name="method-textRecord"></a>textRecord

```php
mixed ProductControllerCore::textRecord()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 613](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L613)




### <a name="method-transformDescriptionWithImg"></a>transformDescriptionWithImg

```php
mixed ProductControllerCore::transformDescriptionWithImg($desc)
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/front/ProductController.php#L564)


#### Arguments
* $desc **mixed**


