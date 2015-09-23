Class LinkCore
=====================





* Class name: LinkCore
* Source: [classes/Link.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L27)


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
* Source: [classes/Link.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L30).


### <a name="property-$cache"></a>$cache

```php
public mixed $cache = array('page' => array())
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Link.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L32).


### <a name="property-$protocol_content"></a>$protocol_content

```php
public mixed $protocol_content
```





* Visibility: **public**
* Source: [classes/Link.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L35).


### <a name="property-$protocol_link"></a>$protocol_link

```php
public mixed $protocol_link
```





* Visibility: **public**
* Source: [classes/Link.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L34).


### <a name="property-$ssl_enable"></a>$ssl_enable

```php
protected mixed $ssl_enable
```





* Visibility: **protected**
* Source: [classes/Link.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L37).


### <a name="property-$url"></a>$url

```php
protected mixed $url
```





* Visibility: **protected**
* Source: [classes/Link.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed LinkCore::__construct($protocol_link, $protocol_content)
```

Constructor (initialization only)



* Visibility: **public**
* Source: [classes/Link.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L42)


#### Arguments
* $protocol_link **mixed**
* $protocol_content **mixed**



### <a name="method-addSortDetails"></a>addSortDetails

```php
mixed LinkCore::addSortDetails($url, $orderby, $orderway)
```





* Visibility: **public**
* Source: [classes/Link.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L549)


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
* Source: [classes/Link.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L339)


#### Arguments
* $controller **string**
* $with_token **boolean** - include or not the token in the url



### <a name="method-getCMSCategoryLink"></a>getCMSCategoryLink

```php
string LinkCore::getCMSCategoryLink(mixed $category, string $alias, integer $id_lang)
```

Create a link to a CMS category



* Visibility: **public**
* Source: [classes/Link.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L193)


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
* Source: [classes/Link.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L221)


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
* Source: [classes/Link.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L423)


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
* Source: [classes/Link.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L155)


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
* Source: [classes/Link.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L355)


#### Arguments
* $name **string** - rewrite link of the image
* $ids **string** - id part of the image filename - can be &quot;id_product-id_image&quot; (legacy support, recommended) or &quot;id_image&quot; (new)
* $type **string**



### <a name="method-getLangLink"></a>getLangLink

```php
mixed LinkCore::getLangLink($id_lang, \Context $context)
```





* Visibility: **protected**
* Source: [classes/Link.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L554)


#### Arguments
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getLanguageLink"></a>getLanguageLink

```php
string LinkCore::getLanguageLink(integer $id_lang, \Context $context)
```

Create link after language change, for the change language block



* Visibility: **public**
* Source: [classes/Link.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L435)


#### Arguments
* $id_lang **integer** - Language ID
* $context **[Context](class.ContextCore.md)**



### <a name="method-getManufacturerLink"></a>getManufacturerLink

```php
string LinkCore::getManufacturerLink(mixed $manufacturer, string $alias, integer $id_lang)
```

Create a link to a manufacturer



* Visibility: **public**
* Source: [classes/Link.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L285)


#### Arguments
* $manufacturer **mixed** - Manufacturer object (can be an ID supplier, but deprecated)
* $alias **string**
* $id_lang **integer**



### <a name="method-getMediaLink"></a>getMediaLink

```php
mixed LinkCore::getMediaLink($filepath)
```





* Visibility: **public**
* Source: [classes/Link.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L384)


#### Arguments
* $filepath **mixed**



### <a name="method-getModuleLink"></a>getModuleLink

```php
string LinkCore::getModuleLink(string $module, $controller, array $params, $ssl, integer $id_lang)
```

Create a link to a module



* Visibility: **public**
* Source: [classes/Link.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L313)


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
* Source: [classes/Link.php line 400](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L400)


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
* Source: [classes/Link.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L483)


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
* Source: [classes/Link.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L64)


#### Arguments
* $product **mixed** - ID of the product OR a Product object
* $id_picture **integer** - ID of the picture to delete



### <a name="method-getProductLink"></a>getProductLink

```php
string LinkCore::getProductLink(mixed $product, string $alias, string $category, string $ean13, integer $id_lang, integer $id_shop, integer $ipa, $force_routes)
```

Create a link to a product



* Visibility: **public**
* Source: [classes/Link.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L82)


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
* Source: [classes/Link.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L258)


#### Arguments
* $supplier **mixed** - Supplier object (can be an ID supplier, but deprecated)
* $alias **string**
* $id_lang **integer**



### <a name="method-goPage"></a>goPage

```php
mixed LinkCore::goPage($url, $p)
```





* Visibility: **public**
* Source: [classes/Link.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Link.php#L468)


#### Arguments
* $url **mixed**
* $p **mixed**


