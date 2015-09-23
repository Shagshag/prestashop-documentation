Class ProductControllerCore
=====================





* Class name: ProductControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/ProductController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L27)


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
* Source: [controllers/front/ProductController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L38).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'product'
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L29).


### <a name="property-$product"></a>$product

```php
protected \Product $product
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L33).


Methods
-------


### <a name="method-assignAttributesCombinations"></a>assignAttributesCombinations

```php
mixed ProductControllerCore::assignAttributesCombinations()
```

Get and assign attributes combinations informations



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 511](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L511)




### <a name="method-assignAttributesGroups"></a>assignAttributesGroups

```php
mixed ProductControllerCore::assignAttributesGroups()
```

Assign template vars related to attribute groups and colors



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L390)




### <a name="method-assignCategory"></a>assignCategory

```php
mixed ProductControllerCore::assignCategory()
```

Assign template vars related to category



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L530)




### <a name="method-assignImages"></a>assignImages

```php
mixed ProductControllerCore::assignImages()
```

Assign template vars related to images



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L340)




### <a name="method-assignPriceAndTax"></a>assignPriceAndTax

```php
mixed ProductControllerCore::assignPriceAndTax()
```

Assign price and tax to the template



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L283)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed ProductControllerCore::canonicalRedirection($canonical_url)
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L69)


#### Arguments
* $canonical_url **mixed**



### <a name="method-formTargetFormat"></a>formTargetFormat

```php
mixed ProductControllerCore::formTargetFormat()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 630](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L630)




### <a name="method-formatQuantityDiscounts"></a>formatQuantityDiscounts

```php
mixed ProductControllerCore::formatQuantityDiscounts($specific_prices, $price, $tax_rate, $ecotax_amount)
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 641](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L641)


#### Arguments
* $specific_prices **mixed**
* $price **mixed**
* $tax_rate **mixed**
* $ecotax_amount **mixed**



### <a name="method-getProduct"></a>getProduct

```php
mixed ProductControllerCore::getProduct()
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L667)




### <a name="method-init"></a>init

```php
mixed ProductControllerCore::init()
```

Initialize product controller



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L81)




### <a name="method-initContent"></a>initContent

```php
mixed ProductControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L172)




### <a name="method-pictureUpload"></a>pictureUpload

```php
mixed ProductControllerCore::pictureUpload()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L571)




### <a name="method-setMedia"></a>setMedia

```php
mixed ProductControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L40)




### <a name="method-textRecord"></a>textRecord

```php
mixed ProductControllerCore::textRecord()
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 607](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L607)




### <a name="method-transformDescriptionWithImg"></a>transformDescriptionWithImg

```php
mixed ProductControllerCore::transformDescriptionWithImg($desc)
```





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/ProductController.php#L558)


#### Arguments
* $desc **mixed**


