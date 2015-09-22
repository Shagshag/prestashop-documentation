Class ProductControllerCore
=====================





* Class name: ProductControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/ProductController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L27)



Properties
----------

* [$category](#property-$category)
* [$php_self](#property-$php_self)
* [$product](#property-$product)

Methods
-------
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

    protected \Category $category





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L35)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'product'





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L29)


### <a name="property-$product"></a>$product

    protected \Product $product





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L32)


Methods
-------


### <a name="method-assignAttributesCombinations"></a>assignAttributesCombinations

    mixed ProductControllerCore::assignAttributesCombinations()

Get and assign attributes combinations informations



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L560)




### <a name="method-assignAttributesGroups"></a>assignAttributesGroups

    mixed ProductControllerCore::assignAttributesGroups()

Assign template vars related to attribute groups and colors



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L416)




### <a name="method-assignCategory"></a>assignCategory

    mixed ProductControllerCore::assignCategory()

Assign template vars related to category



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L582)




### <a name="method-assignImages"></a>assignImages

    mixed ProductControllerCore::assignImages()

Assign template vars related to images



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L367)




### <a name="method-assignPriceAndTax"></a>assignPriceAndTax

    mixed ProductControllerCore::assignPriceAndTax()

Assign price and tax to the template



* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L302)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

    mixed ProductControllerCore::canonicalRedirection($canonical_url)





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L66)


#### Arguments
* $canonical_url **mixed**



### <a name="method-formTargetFormat"></a>formTargetFormat

    mixed ProductControllerCore::formTargetFormat()





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L697)




### <a name="method-formatQuantityDiscounts"></a>formatQuantityDiscounts

    mixed ProductControllerCore::formatQuantityDiscounts($specific_prices, $price, $tax_rate, $ecotax_amount)





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L711)


#### Arguments
* $specific_prices **mixed**
* $price **mixed**
* $tax_rate **mixed**
* $ecotax_amount **mixed**



### <a name="method-getCategory"></a>getCategory

    mixed ProductControllerCore::getCategory()





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 750](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L750)




### <a name="method-getProduct"></a>getProduct

    mixed ProductControllerCore::getProduct()





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L745)




### <a name="method-init"></a>init

    mixed ProductControllerCore::init()

Initialize product controller



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L80)




### <a name="method-initContent"></a>initContent

    mixed ProductControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/ProductController.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L170)




### <a name="method-pictureUpload"></a>pictureUpload

    mixed ProductControllerCore::pictureUpload()





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L627)




### <a name="method-setMedia"></a>setMedia

    mixed ProductControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/front/ProductController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L37)




### <a name="method-textRecord"></a>textRecord

    mixed ProductControllerCore::textRecord()





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L670)




### <a name="method-transformDescriptionWithImg"></a>transformDescriptionWithImg

    mixed ProductControllerCore::transformDescriptionWithImg($desc)





* Visibility: **protected**
* Source: [controllers/front/ProductController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L615)


#### Arguments
* $desc **mixed**


