Class ProductControllerCore
=====================





* Class name: ProductControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/ProductController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L27)


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
protected \Category $category
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L35).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'product'
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L29).


### <a name="property-$product"></a>$product

```php
protected \Product $product
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L32).


Methods
-------


### <a name="method-assignAttributesCombinations"></a>assignAttributesCombinations

```php
mixed ProductControllerCore::assignAttributesCombinations()
```

Get and assign attributes combinations informations



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L560)




### <a name="method-assignAttributesGroups"></a>assignAttributesGroups

```php
mixed ProductControllerCore::assignAttributesGroups()
```

Assign template vars related to attribute groups and colors



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L418)




### <a name="method-assignCategory"></a>assignCategory

```php
mixed ProductControllerCore::assignCategory()
```

Assign template vars related to category



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L579)




### <a name="method-assignImages"></a>assignImages

```php
mixed ProductControllerCore::assignImages()
```

Assign template vars related to images



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L367)




### <a name="method-assignPriceAndTax"></a>assignPriceAndTax

```php
mixed ProductControllerCore::assignPriceAndTax()
```

Assign price and tax to the template



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L305)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed ProductControllerCore::canonicalRedirection($canonical_url)
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L67)


#### Arguments
* $canonical_url **mixed**



### <a name="method-formTargetFormat"></a>formTargetFormat

```php
mixed ProductControllerCore::formTargetFormat()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 684](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L684)




### <a name="method-formatQuantityDiscounts"></a>formatQuantityDiscounts

```php
mixed ProductControllerCore::formatQuantityDiscounts($specific_prices, $price, $tax_rate, $ecotax_amount)
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L695)


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
* Source: [controllers/front/ProductController.php line 734](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L734)




### <a name="method-getProduct"></a>getProduct

```php
mixed ProductControllerCore::getProduct()
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 729](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L729)




### <a name="method-init"></a>init

```php
mixed ProductControllerCore::init()
```

Initialize product controller



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L79)




### <a name="method-initContent"></a>initContent

```php
mixed ProductControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L178)




### <a name="method-pictureUpload"></a>pictureUpload

```php
mixed ProductControllerCore::pictureUpload()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L625)




### <a name="method-setMedia"></a>setMedia

```php
mixed ProductControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L37)




### <a name="method-textRecord"></a>textRecord

```php
mixed ProductControllerCore::textRecord()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L661)




### <a name="method-transformDescriptionWithImg"></a>transformDescriptionWithImg

```php
mixed ProductControllerCore::transformDescriptionWithImg($desc)
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 612](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ProductController.php#L612)


#### Arguments
* $desc **mixed**


