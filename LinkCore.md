LinkCore
===============






* Class name: LinkCore
* Namespace: 
* This class is defined in classes\Link.php line 27





Properties
----------


### $allow

    protected boolean $allow





* Visibility: **protected**
* This property is defined in classes\Link.php line 30


### $url

    protected mixed $url





* Visibility: **protected**
* This property is defined in classes\Link.php line 31


### $cache

    public mixed $cache = array('page' => array())





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Link.php line 32


### $protocol_link

    public mixed $protocol_link





* Visibility: **public**
* This property is defined in classes\Link.php line 34


### $protocol_content

    public mixed $protocol_content





* Visibility: **public**
* This property is defined in classes\Link.php line 35


### $ssl_enable

    protected mixed $ssl_enable





* Visibility: **protected**
* This property is defined in classes\Link.php line 37


### $category_disable_rewrite

    protected mixed $category_disable_rewrite = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Link.php line 39


Methods
-------


### __construct

    mixed LinkCore::__construct($protocol_link, $protocol_content)

Constructor (initialization only)



* Visibility: **public**
* This method is defined in classes\Link.php line 44


#### Arguments
* $protocol_link **mixed**
* $protocol_content **mixed**



### getProductDeletePictureLink

    string LinkCore::getProductDeletePictureLink(mixed $product, integer $id_picture)

Create a link to delete a product



* Visibility: **public**
* This method is defined in classes\Link.php line 72


#### Arguments
* $product **mixed** - &lt;p&gt;ID of the product OR a Product object&lt;/p&gt;
* $id_picture **integer** - &lt;p&gt;ID of the picture to delete&lt;/p&gt;



### getProductLink

    string LinkCore::getProductLink(mixed $product, string $alias, string $category, string $ean13, integer $id_lang, integer $id_shop, integer $ipa, $force_routes, $relative_protocol, $add_anchor)

Create a link to a product



* Visibility: **public**
* This method is defined in classes\Link.php line 90


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



### getCategoryLink

    string LinkCore::getCategoryLink(mixed $category, string $alias, integer $id_lang, string $selected_filters, $id_shop, $relative_protocol)

Create a link to a category



* Visibility: **public**
* This method is defined in classes\Link.php line 168


#### Arguments
* $category **mixed** - &lt;p&gt;Category object (can be an ID category, but deprecated)&lt;/p&gt;
* $alias **string**
* $id_lang **integer**
* $selected_filters **string** - &lt;p&gt;Url parameter to autocheck filters of the module blocklayered&lt;/p&gt;
* $id_shop **mixed**
* $relative_protocol **mixed**



### getCMSCategoryLink

    string LinkCore::getCMSCategoryLink($cms_category, string $alias, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a CMS category



* Visibility: **public**
* This method is defined in classes\Link.php line 208


#### Arguments
* $cms_category **mixed**
* $alias **string**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### getCMSLink

    string LinkCore::getCMSLink(mixed $cms, string $alias, boolean $ssl, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a CMS page



* Visibility: **public**
* This method is defined in classes\Link.php line 252


#### Arguments
* $cms **mixed** - &lt;p&gt;CMS object (can be an ID CMS, but deprecated)&lt;/p&gt;
* $alias **string**
* $ssl **boolean**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### getSupplierLink

    string LinkCore::getSupplierLink(mixed $supplier, string $alias, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a supplier



* Visibility: **public**
* This method is defined in classes\Link.php line 294


#### Arguments
* $supplier **mixed** - &lt;p&gt;Supplier object (can be an ID supplier, but deprecated)&lt;/p&gt;
* $alias **string**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### getManufacturerLink

    string LinkCore::getManufacturerLink(mixed $manufacturer, string $alias, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a manufacturer



* Visibility: **public**
* This method is defined in classes\Link.php line 328


#### Arguments
* $manufacturer **mixed** - &lt;p&gt;Manufacturer object (can be an ID supplier, but deprecated)&lt;/p&gt;
* $alias **string**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### getModuleLink

    string LinkCore::getModuleLink(string $module, $controller, array $params, $ssl, integer $id_lang, $id_shop, $relative_protocol)

Create a link to a module



* Visibility: **public**
* This method is defined in classes\Link.php line 363


#### Arguments
* $module **string** - &lt;p&gt;Module name&lt;/p&gt;
* $controller **mixed**
* $params **array**
* $ssl **mixed**
* $id_lang **integer**
* $id_shop **mixed**
* $relative_protocol **mixed**



### getAdminLink

    string LinkCore::getAdminLink(string $controller, boolean $with_token)

Use controller name to create a link



* Visibility: **public**
* This method is defined in classes\Link.php line 390


#### Arguments
* $controller **string**
* $with_token **boolean** - &lt;p&gt;include or not the token in the url&lt;/p&gt;



### getImageLink

    mixed LinkCore::getImageLink(string $name, string $ids, string $type)

Returns a link to a product image for display
Note: the new image filesystem stores product images in subdirectories of img/p/



* Visibility: **public**
* This method is defined in classes\Link.php line 406


#### Arguments
* $name **string** - &lt;p&gt;rewrite link of the image&lt;/p&gt;
* $ids **string** - &lt;p&gt;id part of the image filename - can be &quot;id_product-id_image&quot; (legacy support, recommended) or &quot;id_image&quot; (new)&lt;/p&gt;
* $type **string**



### getMediaLink

    mixed LinkCore::getMediaLink($filepath)





* Visibility: **public**
* This method is defined in classes\Link.php line 440


#### Arguments
* $filepath **mixed**



### getPageLink

    string LinkCore::getPageLink(string $controller, boolean $ssl, integer $id_lang, string|array $request, boolean $request_url_encode, $id_shop, $relative_protocol)

Create a simple link



* Visibility: **public**
* This method is defined in classes\Link.php line 456


#### Arguments
* $controller **string**
* $ssl **boolean**
* $id_lang **integer**
* $request **string|array**
* $request_url_encode **boolean** - &lt;p&gt;Use URL encode&lt;/p&gt;
* $id_shop **mixed**
* $relative_protocol **mixed**



### getCatImageLink

    mixed LinkCore::getCatImageLink($name, $id_category, $type)





* Visibility: **public**
* This method is defined in classes\Link.php line 493


#### Arguments
* $name **mixed**
* $id_category **mixed**
* $type **mixed**



### getLanguageLink

    string LinkCore::getLanguageLink(integer $id_lang, \Context $context)

Create link after language change, for the change language block



* Visibility: **public**
* This method is defined in classes\Link.php line 509


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $context **[Context](ContextCore)**



### goPage

    mixed LinkCore::goPage($url, $p)





* Visibility: **public**
* This method is defined in classes\Link.php line 553


#### Arguments
* $url **mixed**
* $p **mixed**



### getPaginationLink

    mixed LinkCore::getPaginationLink(string $type, integer $id_object, boolean $nb, boolean $sort, boolean $pagination, boolean $array)

Get pagination link



* Visibility: **public**
* This method is defined in classes\Link.php line 569


#### Arguments
* $type **string** - &lt;p&gt;Controller name&lt;/p&gt;
* $id_object **integer**
* $nb **boolean** - &lt;p&gt;Show nb element per page attribute&lt;/p&gt;
* $sort **boolean** - &lt;p&gt;Show sort attribute&lt;/p&gt;
* $pagination **boolean** - &lt;p&gt;Show page number attribute&lt;/p&gt;
* $array **boolean** - &lt;p&gt;If false return an url, if true return an array&lt;/p&gt;



### addSortDetails

    mixed LinkCore::addSortDetails($url, $orderby, $orderway)





* Visibility: **public**
* This method is defined in classes\Link.php line 637


#### Arguments
* $url **mixed**
* $orderby **mixed**
* $orderway **mixed**



### getLangLink

    mixed LinkCore::getLangLink($id_lang, \Context $context, $id_shop)





* Visibility: **protected**
* This method is defined in classes\Link.php line 642


#### Arguments
* $id_lang **mixed**
* $context **[Context](ContextCore)**
* $id_shop **mixed**



### getBaseLink

    mixed LinkCore::getBaseLink($id_shop, $ssl, $relative_protocol)





* Visibility: **protected**
* This method is defined in classes\Link.php line 659


#### Arguments
* $id_shop **mixed**
* $ssl **mixed**
* $relative_protocol **mixed**



### getQuickLink

    mixed LinkCore::getQuickLink($url)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Link.php line 685


#### Arguments
* $url **mixed**



### matchQuickLink

    mixed LinkCore::matchQuickLink($url)





* Visibility: **public**
* This method is defined in classes\Link.php line 696


#### Arguments
* $url **mixed**


