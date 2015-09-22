ShopUrlCore
===============






* Class name: ShopUrlCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/shop/ShopUrl.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#L27)





Properties
----------


### $id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in [classes/shop/ShopUrl.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#29)


### $domain

    public mixed $domain





* Visibility: **public**
* This property is defined in [classes/shop/ShopUrl.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#30)


### $domain_ssl

    public mixed $domain_ssl





* Visibility: **public**
* This property is defined in [classes/shop/ShopUrl.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#31)


### $physical_uri

    public mixed $physical_uri





* Visibility: **public**
* This property is defined in [classes/shop/ShopUrl.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#32)


### $virtual_uri

    public mixed $virtual_uri





* Visibility: **public**
* This property is defined in [classes/shop/ShopUrl.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#33)


### $main

    public mixed $main





* Visibility: **public**
* This property is defined in [classes/shop/ShopUrl.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#34)


### $active

    public mixed $active





* Visibility: **public**
* This property is defined in [classes/shop/ShopUrl.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#35)


### $main_domain

    protected mixed $main_domain = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/ShopUrl.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#37)


### $main_domain_ssl

    protected mixed $main_domain_ssl = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/shop/ShopUrl.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#38)


### $definition

    public mixed $definition = array('table' => 'shop_url', 'primary' => 'id_shop_url', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'main' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'domain' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 255, 'validate' => 'isCleanHtml'), 'domain_ssl' => array('type' => self::TYPE_STRING, 'size' => 255, 'validate' => 'isCleanHtml'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'physical_uri' => array('type' => self::TYPE_STRING, 'size' => 64), 'virtual_uri' => array('type' => self::TYPE_STRING, 'size' => 64)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/shop/ShopUrl.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#43)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_shop' => array('xlink_resource' => 'shops')))





* Visibility: **protected**
* This property is defined in [classes/shop/ShopUrl.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#57)


Methods
-------


### getFields

    array ShopUrlCore::getFields()





* Visibility: **public**
* This method is defined in [classes/shop/ShopUrl.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#67)




### getBaseURI

    mixed ShopUrlCore::getBaseURI()





* Visibility: **public**
* This method is defined in [classes/shop/ShopUrl.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#87)




### getURL

    mixed ShopUrlCore::getURL($ssl)





* Visibility: **public**
* This method is defined in [classes/shop/ShopUrl.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#92)


#### Arguments
* $ssl **mixed**



### getShopUrls

    \PrestaShopCollection ShopUrlCore::getShopUrls(boolean $id_shop)

Get list of shop urls



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopUrl.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#108)


#### Arguments
* $id_shop **boolean**



### setMain

    mixed ShopUrlCore::setMain()





* Visibility: **public**
* This method is defined in [classes/shop/ShopUrl.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#117)




### canAddThisUrl

    mixed ShopUrlCore::canAddThisUrl($domain, $domain_ssl, $physical_uri, $virtual_uri)





* Visibility: **public**
* This method is defined in [classes/shop/ShopUrl.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#138)


#### Arguments
* $domain **mixed**
* $domain_ssl **mixed**
* $physical_uri **mixed**
* $virtual_uri **mixed**



### cacheMainDomainForShop

    mixed ShopUrlCore::cacheMainDomainForShop($id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopUrl.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#162)


#### Arguments
* $id_shop **mixed**



### resetMainDomainCache

    mixed ShopUrlCore::resetMainDomainCache()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopUrl.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#175)




### getMainShopDomain

    mixed ShopUrlCore::getMainShopDomain($id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopUrl.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#181)


#### Arguments
* $id_shop **mixed**



### getMainShopDomainSSL

    mixed ShopUrlCore::getMainShopDomainSSL($id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopUrl.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopUrl.php#187)


#### Arguments
* $id_shop **mixed**


