Class LinkCore
=====================





* Class name: LinkCore
* Source: [classes/Link.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L28)


Contents
--------


### Properties

* [$allow](#property-$allow)
* [$cache](#property-$cache)
* [$protocol_content](#property-$protocol_content)
* [$protocol_link](#property-$protocol_link)
* [$ssl_enable](#property-$ssl_enable)
* [$url](#property-$url)

### Methods

* [__construct](#method-__construct)
* [addSortDetails](#method-addSortDetails)
* [getAdminLink](#method-getAdminLink)
* [getCMSCategoryLink](#method-getCMSCategoryLink)
* [getCMSLink](#method-getCMSLink)
* [getCatImageLink](#method-getCatImageLink)
* [getCategoryLink](#method-getCategoryLink)
* [getImageLink](#method-getImageLink)
* [getLangLink](#method-getLangLink)
* [getLanguageLink](#method-getLanguageLink)
* [getManufacturerLink](#method-getManufacturerLink)
* [getMediaLink](#method-getMediaLink)
* [getModuleLink](#method-getModuleLink)
* [getPageLink](#method-getPageLink)
* [getPaginationLink](#method-getPaginationLink)
* [getProductDeletePictureLink](#method-getProductDeletePictureLink)
* [getProductLink](#method-getProductLink)
* [getSupplierLink](#method-getSupplierLink)
* [goPage](#method-goPage)




Properties
----------


### <a name="property-$allow"></a>$allow

```php
protected boolean $allow
```





* Visibility: **protected**
* Source: [classes/Link.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L31).


### <a name="property-$cache"></a>$cache

```php
public mixed $cache = array('page' => array())
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Link.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L33).


### <a name="property-$protocol_content"></a>$protocol_content

```php
public mixed $protocol_content
```





* Visibility: **public**
* Source: [classes/Link.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L36).


### <a name="property-$protocol_link"></a>$protocol_link

```php
public mixed $protocol_link
```





* Visibility: **public**
* Source: [classes/Link.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L35).


### <a name="property-$ssl_enable"></a>$ssl_enable

```php
protected mixed $ssl_enable
```





* Visibility: **protected**
* Source: [classes/Link.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L38).


### <a name="property-$url"></a>$url

```php
protected mixed $url
```





* Visibility: **protected**
* Source: [classes/Link.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed LinkCore::__construct($protocol_link, $protocol_content)
```

Constructor (initialization only)



* Visibility: **public**
* Source: [classes/Link.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L43)


#### Arguments
* $protocol_link **mixed**
* $protocol_content **mixed**



### <a name="method-addSortDetails"></a>addSortDetails

```php
mixed LinkCore::addSortDetails($url, $orderby, $orderway)
```





* Visibility: **public**
* Source: [classes/Link.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L545)


#### Arguments
* $url **mixed**
* $orderby **mixed**
* $orderway **mixed**



### <a name="method-getAdminLink"></a>getAdminLink

```php
\controller LinkCore::getAdminLink(string $controller, boolean $with_token)
```

Use controller name to create a link



* Visibility: **public**
* Source: [classes/Link.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L336)


#### Arguments
* $controller **string**
* $with_token **boolean** - include or not the token in the url



### <a name="method-getCMSCategoryLink"></a>getCMSCategoryLink

```php
string LinkCore::getCMSCategoryLink(mixed $category, string $alias, integer $id_lang)
```

Create a link to a CMS category



* Visibility: **public**
* Source: [classes/Link.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L190)


#### Arguments
* $category **mixed** - CMSCategory object (can be an ID category, but deprecated)
* $alias **string**
* $id_lang **integer**



### <a name="method-getCMSLink"></a>getCMSLink

```php
string LinkCore::getCMSLink(mixed $cms, string $alias, boolean $ssl, integer $id_lang)
```

Create a link to a CMS page



* Visibility: **public**
* Source: [classes/Link.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L218)


#### Arguments
* $cms **mixed** - CMS object (can be an ID CMS, but deprecated)
* $alias **string**
* $ssl **boolean**
* $id_lang **integer**



### <a name="method-getCatImageLink"></a>getCatImageLink

```php
mixed LinkCore::getCatImageLink($name, $id_category, $type)
```





* Visibility: **public**
* Source: [classes/Link.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L420)


#### Arguments
* $name **mixed**
* $id_category **mixed**
* $type **mixed**



### <a name="method-getCategoryLink"></a>getCategoryLink

```php
string LinkCore::getCategoryLink(mixed $category, string $alias, integer $id_lang, string $selected_filters)
```

Create a link to a category



* Visibility: **public**
* Source: [classes/Link.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L152)


#### Arguments
* $category **mixed** - Category object (can be an ID category, but deprecated)
* $alias **string**
* $id_lang **integer**
* $selected_filters **string** - Url parameter to autocheck filters of the module blocklayered



### <a name="method-getImageLink"></a>getImageLink

```php
mixed LinkCore::getImageLink(string $name, string $ids, string $type)
```

Returns a link to a product image for display
Note: the new image filesystem stores product images in subdirectories of img/p/



* Visibility: **public**
* Source: [classes/Link.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L352)


#### Arguments
* $name **string** - rewrite link of the image
* $ids **string** - id part of the image filename - can be &quot;id_product-id_image&quot; (legacy support, recommended) or &quot;id_image&quot; (new)
* $type **string**



### <a name="method-getLangLink"></a>getLangLink

```php
mixed LinkCore::getLangLink($id_lang, \Context $context)
```





* Visibility: **protected**
* Source: [classes/Link.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L550)


#### Arguments
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getLanguageLink"></a>getLanguageLink

```php
string LinkCore::getLanguageLink(integer $id_lang, \Context $context)
```

Create link after language change, for the change language block



* Visibility: **public**
* Source: [classes/Link.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L431)


#### Arguments
* $id_lang **integer** - Language ID
* $context **[Context](class.ContextCore.md)**



### <a name="method-getManufacturerLink"></a>getManufacturerLink

```php
string LinkCore::getManufacturerLink(mixed $manufacturer, string $alias, integer $id_lang)
```

Create a link to a manufacturer



* Visibility: **public**
* Source: [classes/Link.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L282)


#### Arguments
* $manufacturer **mixed** - Manufacturer object (can be an ID supplier, but deprecated)
* $alias **string**
* $id_lang **integer**



### <a name="method-getMediaLink"></a>getMediaLink

```php
mixed LinkCore::getMediaLink($filepath)
```





* Visibility: **public**
* Source: [classes/Link.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L380)


#### Arguments
* $filepath **mixed**



### <a name="method-getModuleLink"></a>getModuleLink

```php
string LinkCore::getModuleLink(string $module, $controller, array $params, $ssl, integer $id_lang)
```

Create a link to a module



* Visibility: **public**
* Source: [classes/Link.php line 310](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L310)


#### Arguments
* $module **string** - Module name
* $controller **mixed**
* $params **array**
* $ssl **mixed**
* $id_lang **integer**



### <a name="method-getPageLink"></a>getPageLink

```php
string LinkCore::getPageLink(string $controller, boolean $ssl, integer $id_lang, string|array $request, boolean $request_url_encode)
```

Create a simple link



* Visibility: **public**
* Source: [classes/Link.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L396)


#### Arguments
* $controller **string**
* $ssl **boolean**
* $id_lang **integer**
* $request **string|array**
* $request_url_encode **boolean** - Use URL encode



### <a name="method-getPaginationLink"></a>getPaginationLink

```php
mixed LinkCore::getPaginationLink(string $type, integer $id_object, boolean $nb, boolean $sort, boolean $pagination, boolean $array)
```

Get pagination link



* Visibility: **public**
* Source: [classes/Link.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L479)


#### Arguments
* $type **string** - Controller name
* $id_object **integer**
* $nb **boolean** - Show nb element per page attribute
* $sort **boolean** - Show sort attribute
* $pagination **boolean** - Show page number attribute
* $array **boolean** - If false return an url, if true return an array



### <a name="method-getProductDeletePictureLink"></a>getProductDeletePictureLink

```php
string LinkCore::getProductDeletePictureLink(mixed $product, integer $id_picture)
```

Create a link to delete a product



* Visibility: **public**
* Source: [classes/Link.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L65)


#### Arguments
* $product **mixed** - ID of the product OR a Product object
* $id_picture **integer** - ID of the picture to delete



### <a name="method-getProductLink"></a>getProductLink

```php
string LinkCore::getProductLink(mixed $product, string $alias, string $category, string $ean13, integer $id_lang, integer $id_shop, integer $ipa, $force_routes)
```

Create a link to a product



* Visibility: **public**
* Source: [classes/Link.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L83)


#### Arguments
* $product **mixed** - Product object (can be an ID product, but deprecated)
* $alias **string**
* $category **string**
* $ean13 **string**
* $id_lang **integer**
* $id_shop **integer** - (since 1.5.0) ID shop need to be used when we generate a product link for a product in a cart
* $ipa **integer** - ID product attribute
* $force_routes **mixed**



### <a name="method-getSupplierLink"></a>getSupplierLink

```php
string LinkCore::getSupplierLink(mixed $supplier, string $alias, integer $id_lang)
```

Create a link to a supplier



* Visibility: **public**
* Source: [classes/Link.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L255)


#### Arguments
* $supplier **mixed** - Supplier object (can be an ID supplier, but deprecated)
* $alias **string**
* $id_lang **integer**



### <a name="method-goPage"></a>goPage

```php
mixed LinkCore::goPage($url, $p)
```





* Visibility: **public**
* Source: [classes/Link.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Link.php#L464)


#### Arguments
* $url **mixed**
* $p **mixed**


