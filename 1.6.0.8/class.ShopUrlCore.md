Class ShopUrlCore
=====================





* Class name: ShopUrlCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/shop/ShopUrl.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L27)


Contents
--------


### Properties

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

### Methods

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

```php
public mixed $active
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L35).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'shop_url', 'primary' => 'id_shop_url', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'main' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'domain' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 255, 'validate' => 'isCleanHtml'), 'domain_ssl' => array('type' => self::TYPE_STRING, 'size' => 255, 'validate' => 'isCleanHtml'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'physical_uri' => array('type' => self::TYPE_STRING, 'size' => 64), 'virtual_uri' => array('type' => self::TYPE_STRING, 'size' => 64)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/shop/ShopUrl.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L43).


### <a name="property-$domain"></a>$domain

```php
public mixed $domain
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L30).


### <a name="property-$domain_ssl"></a>$domain_ssl

```php
public mixed $domain_ssl
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L31).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L29).


### <a name="property-$main"></a>$main

```php
public mixed $main
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L34).


### <a name="property-$main_domain"></a>$main_domain

```php
protected mixed $main_domain = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/ShopUrl.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L37).


### <a name="property-$main_domain_ssl"></a>$main_domain_ssl

```php
protected mixed $main_domain_ssl = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/shop/ShopUrl.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L38).


### <a name="property-$physical_uri"></a>$physical_uri

```php
public mixed $physical_uri
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L32).


### <a name="property-$virtual_uri"></a>$virtual_uri

```php
public mixed $virtual_uri
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L33).


Methods
-------


### <a name="method-cacheMainDomainForShop"></a>cacheMainDomainForShop

```php
mixed ShopUrlCore::cacheMainDomainForShop($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L149)


#### Arguments
* $id_shop **mixed**



### <a name="method-canAddThisUrl"></a>canAddThisUrl

```php
mixed ShopUrlCore::canAddThisUrl($domain, $domain_ssl, $physical_uri, $virtual_uri)
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L127)


#### Arguments
* $domain **mixed**
* $domain_ssl **mixed**
* $physical_uri **mixed**
* $virtual_uri **mixed**



### <a name="method-getBaseURI"></a>getBaseURI

```php
mixed ShopUrlCore::getBaseURI()
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L79)




### <a name="method-getFields"></a>getFields

```php
array ShopUrlCore::getFields()
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L61)




### <a name="method-getMainShopDomain"></a>getMainShopDomain

```php
mixed ShopUrlCore::getMainShopDomain($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L169)


#### Arguments
* $id_shop **mixed**



### <a name="method-getMainShopDomainSSL"></a>getMainShopDomainSSL

```php
mixed ShopUrlCore::getMainShopDomainSSL($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L175)


#### Arguments
* $id_shop **mixed**



### <a name="method-getShopUrls"></a>getShopUrls

```php
\PrestaShopCollection ShopUrlCore::getShopUrls(boolean $id_shop)
```

Get list of shop urls



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L99)


#### Arguments
* $id_shop **boolean**



### <a name="method-getURL"></a>getURL

```php
mixed ShopUrlCore::getURL($ssl)
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L84)


#### Arguments
* $ssl **mixed**



### <a name="method-resetMainDomainCache"></a>resetMainDomainCache

```php
mixed ShopUrlCore::resetMainDomainCache()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopUrl.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L163)




### <a name="method-setMain"></a>setMain

```php
mixed ShopUrlCore::setMain()
```





* Visibility: **public**
* Source: [classes/shop/ShopUrl.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/shop/ShopUrl.php#L107)



