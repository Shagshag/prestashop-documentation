Class ShopUrlCore
=====================





* Class name: ShopUrlCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/shop/ShopUrl.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L27)



Properties
----------

* [$active](#property-$active)
* [$definition](#property-$definition)
* [$domain](#property-$domain)
* [$domain_ssl](#property-$domain_ssl)
* [$id_shop](#property-$id_shop)
* [$main](#property-$main)
* [$main_domain](#property-$main_domain)
* [$main_domain_ssl](#property-$main_domain_ssl)
* [$physical_uri](#property-$physical_uri)
* [$virtual_uri](#property-$virtual_uri)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [cacheMainDomainForShop](#method-cacheMainDomainForShop)
* [canAddThisUrl](#method-canAddThisUrl)
* [getBaseURI](#method-getBaseURI)
* [getFields](#method-getFields)
* [getMainShopDomain](#method-getMainShopDomain)
* [getMainShopDomainSSL](#method-getMainShopDomainSSL)
* [getShopUrls](#method-getShopUrls)
* [getURL](#method-getURL)
* [resetMainDomainCache](#method-resetMainDomainCache)
* [setMain](#method-setMain)




Properties
----------


### <a name="property-$active"></a>$active

    public mixed $active





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L35)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'shop_url', 'primary' => 'id_shop_url', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'main' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'domain' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 255, 'validate' => 'isCleanHtml'), 'domain_ssl' => array('type' => self::TYPE_STRING, 'size' => 255, 'validate' => 'isCleanHtml'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'physical_uri' => array('type' => self::TYPE_STRING, 'size' => 64), 'virtual_uri' => array('type' => self::TYPE_STRING, 'size' => 64)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/shop/ShopUrl.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L43)


### <a name="property-$domain"></a>$domain

    public mixed $domain





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L30)


### <a name="property-$domain_ssl"></a>$domain_ssl

    public mixed $domain_ssl





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L31)


### <a name="property-$id_shop"></a>$id_shop

    public mixed $id_shop





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L29)


### <a name="property-$main"></a>$main

    public mixed $main





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L34)


### <a name="property-$main_domain"></a>$main_domain

    protected mixed $main_domain = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/ShopUrl.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L37)


### <a name="property-$main_domain_ssl"></a>$main_domain_ssl

    protected mixed $main_domain_ssl = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/ShopUrl.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L38)


### <a name="property-$physical_uri"></a>$physical_uri

    public mixed $physical_uri





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L32)


### <a name="property-$virtual_uri"></a>$virtual_uri

    public mixed $virtual_uri





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L33)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_shop' => array('xlink_resource' => 'shops')))





* Visibility: **protected**
* Source: [classes/shop/ShopUrl.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L57)


Methods
-------


### <a name="method-cacheMainDomainForShop"></a>cacheMainDomainForShop

    mixed ShopUrlCore::cacheMainDomainForShop($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L162)


#### Arguments
* $id_shop **mixed**



### <a name="method-canAddThisUrl"></a>canAddThisUrl

    mixed ShopUrlCore::canAddThisUrl($domain, $domain_ssl, $physical_uri, $virtual_uri)





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L138)


#### Arguments
* $domain **mixed**
* $domain_ssl **mixed**
* $physical_uri **mixed**
* $virtual_uri **mixed**



### <a name="method-getBaseURI"></a>getBaseURI

    mixed ShopUrlCore::getBaseURI()





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L87)




### <a name="method-getFields"></a>getFields

    array ShopUrlCore::getFields()





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L67)




### <a name="method-getMainShopDomain"></a>getMainShopDomain

    mixed ShopUrlCore::getMainShopDomain($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L181)


#### Arguments
* $id_shop **mixed**



### <a name="method-getMainShopDomainSSL"></a>getMainShopDomainSSL

    mixed ShopUrlCore::getMainShopDomainSSL($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L187)


#### Arguments
* $id_shop **mixed**



### <a name="method-getShopUrls"></a>getShopUrls

    \PrestaShopCollection ShopUrlCore::getShopUrls(boolean $id_shop)

Get list of shop urls



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L108)


#### Arguments
* $id_shop **boolean**



### <a name="method-getURL"></a>getURL

    mixed ShopUrlCore::getURL($ssl)





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L92)


#### Arguments
* $ssl **mixed**



### <a name="method-resetMainDomainCache"></a>resetMainDomainCache

    mixed ShopUrlCore::resetMainDomainCache()





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L175)




### <a name="method-setMain"></a>setMain

    mixed ShopUrlCore::setMain()





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L117)



