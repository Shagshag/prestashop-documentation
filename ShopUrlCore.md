ShopUrlCore
===============






* Class name: ShopUrlCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_shop

    public mixed $id_shop





* Visibility: **public**


### $domain

    public mixed $domain





* Visibility: **public**


### $domain_ssl

    public mixed $domain_ssl





* Visibility: **public**


### $physical_uri

    public mixed $physical_uri





* Visibility: **public**


### $virtual_uri

    public mixed $virtual_uri





* Visibility: **public**


### $main

    public mixed $main





* Visibility: **public**


### $active

    public mixed $active





* Visibility: **public**


### $main_domain

    protected mixed $main_domain = array()





* Visibility: **protected**
* This property is **static**.


### $main_domain_ssl

    protected mixed $main_domain_ssl = array()





* Visibility: **protected**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'shop_url', 'primary' => 'id_shop_url', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'main' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'domain' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 255, 'validate' => 'isCleanHtml'), 'domain_ssl' => array('type' => self::TYPE_STRING, 'size' => 255, 'validate' => 'isCleanHtml'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'physical_uri' => array('type' => self::TYPE_STRING, 'size' => 64), 'virtual_uri' => array('type' => self::TYPE_STRING, 'size' => 64)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_shop' => array('xlink_resource' => 'shops')))





* Visibility: **protected**


Methods
-------


### getFields

    array ShopUrlCore::getFields()





* Visibility: **public**




### getBaseURI

    mixed ShopUrlCore::getBaseURI()





* Visibility: **public**




### getURL

    mixed ShopUrlCore::getURL($ssl)





* Visibility: **public**


#### Arguments
* $ssl **mixed**



### getShopUrls

    \PrestaShopCollection ShopUrlCore::getShopUrls(boolean $id_shop)

Get list of shop urls



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **boolean**



### setMain

    mixed ShopUrlCore::setMain()





* Visibility: **public**




### canAddThisUrl

    mixed ShopUrlCore::canAddThisUrl($domain, $domain_ssl, $physical_uri, $virtual_uri)





* Visibility: **public**


#### Arguments
* $domain **mixed**
* $domain_ssl **mixed**
* $physical_uri **mixed**
* $virtual_uri **mixed**



### cacheMainDomainForShop

    mixed ShopUrlCore::cacheMainDomainForShop($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**



### resetMainDomainCache

    mixed ShopUrlCore::resetMainDomainCache()





* Visibility: **public**
* This method is **static**.




### getMainShopDomain

    mixed ShopUrlCore::getMainShopDomain($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**



### getMainShopDomainSSL

    mixed ShopUrlCore::getMainShopDomainSSL($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**


