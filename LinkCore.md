LinkCore
===============






* Class name: LinkCore
* This class is defined in [classes/Link.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L27)





Properties
----------

* [$allow](#property-$allow)
* [$url](#property-$url)
* [$cache](#property-$cache)
* [$protocol_link](#property-$protocol_link)
* [$protocol_content](#property-$protocol_content)
* [$ssl_enable](#property-$ssl_enable)
* [$category_disable_rewrite](#property-$category_disable_rewrite)

Methods
-------
* [__construct](#method-__construct)
* [getProductDeletePictureLink](#method-getProductDeletePictureLink)
* [getProductLink](#method-getProductLink)
* [getCategoryLink](#method-getCategoryLink)
* [getCMSCategoryLink](#method-getCMSCategoryLink)
* [getCMSLink](#method-getCMSLink)
* [getSupplierLink](#method-getSupplierLink)
* [getManufacturerLink](#method-getManufacturerLink)
* [getModuleLink](#method-getModuleLink)
* [getAdminLink](#method-getAdminLink)
* [getImageLink](#method-getImageLink)
* [getMediaLink](#method-getMediaLink)
* [getPageLink](#method-getPageLink)
* [getCatImageLink](#method-getCatImageLink)
* [getLanguageLink](#method-getLanguageLink)
* [goPage](#method-goPage)
* [getPaginationLink](#method-getPaginationLink)
* [addSortDetails](#method-addSortDetails)
* [getLangLink](#method-getLangLink)
* [getBaseLink](#method-getBaseLink)
* [getQuickLink](#method-getQuickLink)
* [matchQuickLink](#method-matchQuickLink)




Properties
----------


### <a name="property-$allow"></a>$allow

    protected boolean $allow





* Visibility: **protected**
* This property is defined in [classes/Link.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L30)


### <a name="property-$url"></a>$url

    protected mixed $url





* Visibility: **protected**
* This property is defined in [classes/Link.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L31)


### <a name="property-$cache"></a>$cache

    public mixed $cache = array('page' => array())





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Link.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L32)


### <a name="property-$protocol_link"></a>$protocol_link

    public mixed $protocol_link





* Visibility: **public**
* This property is defined in [classes/Link.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L34)


### <a name="property-$protocol_content"></a>$protocol_content

    public mixed $protocol_content





* Visibility: **public**
* This property is defined in [classes/Link.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L35)


### <a name="property-$ssl_enable"></a>$ssl_enable

    protected mixed $ssl_enable





* Visibility: **protected**
* This property is defined in [classes/Link.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L37)


### <a name="property-$category_disable_rewrite"></a>$category_disable_rewrite

    protected mixed $category_disable_rewrite = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Link.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L39)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed LinkCore::__construct($protocol_link, $protocol_content)

Constructor (initialization only)



* Visibility: **public**
* This method is defined in [classes/Link.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L44)


#### Arguments
* $protocol_link **mixed**
* $protocol_content **mixed**



### <a name="method-getProductDeletePictureLink"></a>getProductDeletePictureLink

    string LinkCore::getProductDeletePictureLink(mixed $product, integer $id_picture)

Create a link to delete a product



* Visibility: **public**
* This method is defined in [classes/Link.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L72)


#### Arguments
* $product **mixed** - &lt;p&gt;ID of the product OR a Product object&lt;/p&gt;
* $id_picture **integer** - &lt;p&gt;ID of the picture to delete&lt;/p&gt;



### <a name="method-getProductLink"></a>getProductLink

    string LinkCore::getProductLink(mixed $product, string $alias, string $category, string $ean13, integer $id_lang, integer $id_shop, integer $ipa, $force_routes, $relative_protocol, $add_anchor)

Create a link to a product



* Visibility: **public**
* This method is defined in [classes/Link.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L90)


#### Arguments
* $product **mixed** - &lt;p&gt;Product object (can be an ID product, but deprecated)&lt;/p&gt;
* $alias **string**
* $category **string**
* $ean13 **string**
* $id_lang **integer**
* $id_shop **integer** - &lt;p&gt;(since 1.5.0) ID shop need to be used when we generate a product link for a product in a cart&lt;/p&gt;
* $ipa **integer** - &lt;p&gt;ID product attribute&lt;/p&gt;
* $force_routes **mixed**
* $relative_protocol **mixed**
* $add_anchor **mixed**



### <a name="method-getCategoryLink"></a>getCategoryLink

    string LinkCore::getCategoryLink(mixed $category, string $alias, integer $id_lang, string $selected_filters, $id_shop, $relative_protocol)

Create a link to a category



* Visibility: **public**
* This method is defined in [classes/Link.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L168)


#### Arguments
* $category **mixed** - &lt;p&gt;Category object (can be an ID category, but deprecated)&lt;/p&gt;
* $alias **string**
* $id_lang **integer**
* $selected_filters **string** - &lt;p&gt;Url parameter to autocheck filters of the module blocklayered&lt;/p&gt;
* $id_shop **mixed**
* $relative_protocol **mixed**



### <a name="method-getCMSCategoryLink"></a>getCMSCategoryLink

    string LinkCore::getCMSCategoryLink($cms_category, string $alias, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a CMS category



* Visibility: **public**
* This method is defined in [classes/Link.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L208)


#### Arguments
* $cms_category **mixed**
* $alias **string**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### <a name="method-getCMSLink"></a>getCMSLink

    string LinkCore::getCMSLink(mixed $cms, string $alias, boolean $ssl, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a CMS page



* Visibility: **public**
* This method is defined in [classes/Link.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L252)


#### Arguments
* $cms **mixed** - &lt;p&gt;CMS object (can be an ID CMS, but deprecated)&lt;/p&gt;
* $alias **string**
* $ssl **boolean**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### <a name="method-getSupplierLink"></a>getSupplierLink

    string LinkCore::getSupplierLink(mixed $supplier, string $alias, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a supplier



* Visibility: **public**
* This method is defined in [classes/Link.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L294)


#### Arguments
* $supplier **mixed** - &lt;p&gt;Supplier object (can be an ID supplier, but deprecated)&lt;/p&gt;
* $alias **string**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### <a name="method-getManufacturerLink"></a>getManufacturerLink

    string LinkCore::getManufacturerLink(mixed $manufacturer, string $alias, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a manufacturer



* Visibility: **public**
* This method is defined in [classes/Link.php line 328](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L328)


#### Arguments
* $manufacturer **mixed** - &lt;p&gt;Manufacturer object (can be an ID supplier, but deprecated)&lt;/p&gt;
* $alias **string**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### <a name="method-getModuleLink"></a>getModuleLink

    string LinkCore::getModuleLink(string $module, $controller, array $params, $ssl, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a module



* Visibility: **public**
* This method is defined in [classes/Link.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L363)


#### Arguments
* $module **string** - &lt;p&gt;Module name&lt;/p&gt;
* $controller **mixed**
* $params **array**
* $ssl **mixed**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### <a name="method-getAdminLink"></a>getAdminLink

    string LinkCore::getAdminLink(string $controller, boolean $with_token)

Use controller name to create a link



* Visibility: **public**
* This method is defined in [classes/Link.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L390)


#### Arguments
* $controller **string**
* $with_token **boolean** - &lt;p&gt;include or not the token in the url&lt;/p&gt;



### <a name="method-getImageLink"></a>getImageLink

    mixed LinkCore::getImageLink(string $name, string $ids, string $type)

Returns a link to a product image for display
Note: the new image filesystem stores product images in subdirectories of img/p/



* Visibility: **public**
* This method is defined in [classes/Link.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L406)


#### Arguments
* $name **string** - &lt;p&gt;rewrite link of the image&lt;/p&gt;
* $ids **string** - &lt;p&gt;id part of the image filename - can be &quot;id_product-id_image&quot; (legacy support, recommended) or &quot;id_image&quot; (new)&lt;/p&gt;
* $type **string**



### <a name="method-getMediaLink"></a>getMediaLink

    mixed LinkCore::getMediaLink($filepath)





* Visibility: **public**
* This method is defined in [classes/Link.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L440)


#### Arguments
* $filepath **mixed**



### <a name="method-getPageLink"></a>getPageLink

    string LinkCore::getPageLink(string $controller, boolean $ssl, integer $id_lang, string|array $request, boolean $request_url_encode, $id_shop, $relative_protocol)

Create a simple link



* Visibility: **public**
* This method is defined in [classes/Link.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L456)


#### Arguments
* $controller **string**
* $ssl **boolean**
* $id_lang **integer**
* $request **string|array**
* $request_url_encode **boolean** - &lt;p&gt;Use URL encode&lt;/p&gt;
* $id_shop **mixed**
* $relative_protocol **mixed**



### <a name="method-getCatImageLink"></a>getCatImageLink

    mixed LinkCore::getCatImageLink($name, $id_category, $type)





* Visibility: **public**
* This method is defined in [classes/Link.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L493)


#### Arguments
* $name **mixed**
* $id_category **mixed**
* $type **mixed**



### <a name="method-getLanguageLink"></a>getLanguageLink

    string LinkCore::getLanguageLink(integer $id_lang, \Context $context)

Create link after language change, for the change language block



* Visibility: **public**
* This method is defined in [classes/Link.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L509)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $context **[Context](ContextCore)**



### <a name="method-goPage"></a>goPage

    mixed LinkCore::goPage($url, $p)





* Visibility: **public**
* This method is defined in [classes/Link.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L553)


#### Arguments
* $url **mixed**
* $p **mixed**



### <a name="method-getPaginationLink"></a>getPaginationLink

    mixed LinkCore::getPaginationLink(string $type, integer $id_object, boolean $nb, boolean $sort, boolean $pagination, boolean $array)

Get pagination link



* Visibility: **public**
* This method is defined in [classes/Link.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L569)


#### Arguments
* $type **string** - &lt;p&gt;Controller name&lt;/p&gt;
* $id_object **integer**
* $nb **boolean** - &lt;p&gt;Show nb element per page attribute&lt;/p&gt;
* $sort **boolean** - &lt;p&gt;Show sort attribute&lt;/p&gt;
* $pagination **boolean** - &lt;p&gt;Show page number attribute&lt;/p&gt;
* $array **boolean** - &lt;p&gt;If false return an url, if true return an array&lt;/p&gt;



### <a name="method-addSortDetails"></a>addSortDetails

    mixed LinkCore::addSortDetails($url, $orderby, $orderway)





* Visibility: **public**
* This method is defined in [classes/Link.php line 637](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L637)


#### Arguments
* $url **mixed**
* $orderby **mixed**
* $orderway **mixed**



### <a name="method-getLangLink"></a>getLangLink

    mixed LinkCore::getLangLink($id_lang, \Context $context, $id_shop)





* Visibility: **protected**
* This method is defined in [classes/Link.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L642)


#### Arguments
* $id_lang **mixed**
* $context **[Context](ContextCore)**
* $id_shop **mixed**



### <a name="method-getBaseLink"></a>getBaseLink

    mixed LinkCore::getBaseLink($id_shop, $ssl, $relative_protocol)





* Visibility: **protected**
* This method is defined in [classes/Link.php line 659](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L659)


#### Arguments
* $id_shop **mixed**
* $ssl **mixed**
* $relative_protocol **mixed**



### <a name="method-getQuickLink"></a>getQuickLink

    mixed LinkCore::getQuickLink($url)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Link.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L685)


#### Arguments
* $url **mixed**



### <a name="method-matchQuickLink"></a>matchQuickLink

    mixed LinkCore::matchQuickLink($url)





* Visibility: **public**
* This method is defined in [classes/Link.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Link.php#L696)


#### Arguments
* $url **mixed**


