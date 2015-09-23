Class ReferrerCore
=====================





* Class name: ReferrerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Referrer.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L27)


Contents
--------


### Properties

* [$_join](#property-$_join)
* [$base_fee](#property-$base_fee)
* [$click_fee](#property-$click_fee)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$http_referer_like](#property-$http_referer_like)
* [$http_referer_like_not](#property-$http_referer_like_not)
* [$http_referer_regexp](#property-$http_referer_regexp)
* [$http_referer_regexp_not](#property-$http_referer_regexp_not)
* [$id_shop](#property-$id_shop)
* [$name](#property-$name)
* [$passwd](#property-$passwd)
* [$percent_fee](#property-$percent_fee)
* [$request_uri_like](#property-$request_uri_like)
* [$request_uri_like_not](#property-$request_uri_like_not)
* [$request_uri_regexp](#property-$request_uri_regexp)
* [$request_uri_regexp_not](#property-$request_uri_regexp_not)

### Methods

* [add](#method-add)
* [cacheNewSource](#method-cacheNewSource)
* [getAjaxProduct](#method-getAjaxProduct)
* [getReferrers](#method-getReferrers)
* [getRegistrations](#method-getRegistrations)
* [getStatsSales](#method-getStatsSales)
* [getStatsVisits](#method-getStatsVisits)
* [refreshCache](#method-refreshCache)
* [refreshIndex](#method-refreshIndex)




Properties
----------


### <a name="property-$_join"></a>$_join

```php
protected mixed $_join = '(r.http_referer_like IS NULL OR r.http_referer_like = \'\' OR cs.http_referer LIKE r.http_referer_like)
			AND (r.request_uri_like IS NULL OR r.request_uri_like = \'\' OR cs.request_uri LIKE r.request_uri_like)
			AND (r.http_referer_like_not IS NULL OR r.http_referer_like_not = \'\' OR cs.http_referer NOT LIKE r.http_referer_like_not)
			AND (r.request_uri_like_not IS NULL OR r.request_uri_like_not = \'\' OR cs.request_uri NOT LIKE r.request_uri_like_not)
			AND (r.http_referer_regexp IS NULL OR r.http_referer_regexp = \'\' OR cs.http_referer REGEXP r.http_referer_regexp)
			AND (r.request_uri_regexp IS NULL OR r.request_uri_regexp = \'\' OR cs.request_uri REGEXP r.request_uri_regexp)
			AND (r.http_referer_regexp_not IS NULL OR r.http_referer_regexp_not = \'\' OR cs.http_referer NOT REGEXP r.http_referer_regexp_not)
			AND (r.request_uri_regexp_not IS NULL OR r.request_uri_regexp_not = \'\' OR cs.request_uri NOT REGEXP r.request_uri_regexp_not)'
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Referrer.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L72).


### <a name="property-$base_fee"></a>$base_fee

```php
public mixed $base_fee
```





* Visibility: **public**
* Source: [classes/Referrer.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L42).


### <a name="property-$click_fee"></a>$click_fee

```php
public mixed $click_fee
```





* Visibility: **public**
* Source: [classes/Referrer.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L44).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/Referrer.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L46).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'referrer', 'primary' => 'id_referrer', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswd', 'size' => 32), 'http_referer_regexp' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'request_uri_regexp' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'http_referer_like' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'request_uri_like' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'http_referer_regexp_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'request_uri_regexp_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'http_referer_like_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'request_uri_like_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'base_fee' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'percent_fee' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPercentage'), 'click_fee' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Referrer.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L51).


### <a name="property-$http_referer_like"></a>$http_referer_like

```php
public mixed $http_referer_like
```





* Visibility: **public**
* Source: [classes/Referrer.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L34).


### <a name="property-$http_referer_like_not"></a>$http_referer_like_not

```php
public mixed $http_referer_like_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L38).


### <a name="property-$http_referer_regexp"></a>$http_referer_regexp

```php
public mixed $http_referer_regexp
```





* Visibility: **public**
* Source: [classes/Referrer.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L33).


### <a name="property-$http_referer_regexp_not"></a>$http_referer_regexp_not

```php
public mixed $http_referer_regexp_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L37).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Referrer.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L29).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Referrer.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L30).


### <a name="property-$passwd"></a>$passwd

```php
public mixed $passwd
```





* Visibility: **public**
* Source: [classes/Referrer.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L31).


### <a name="property-$percent_fee"></a>$percent_fee

```php
public mixed $percent_fee
```





* Visibility: **public**
* Source: [classes/Referrer.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L43).


### <a name="property-$request_uri_like"></a>$request_uri_like

```php
public mixed $request_uri_like
```





* Visibility: **public**
* Source: [classes/Referrer.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L36).


### <a name="property-$request_uri_like_not"></a>$request_uri_like_not

```php
public mixed $request_uri_like_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L40).


### <a name="property-$request_uri_regexp"></a>$request_uri_regexp

```php
public mixed $request_uri_regexp
```





* Visibility: **public**
* Source: [classes/Referrer.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L35).


### <a name="property-$request_uri_regexp_not"></a>$request_uri_regexp_not

```php
public mixed $request_uri_regexp_not
```





* Visibility: **public**
* Source: [classes/Referrer.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L39).


Methods
-------


### <a name="method-add"></a>add

```php
mixed ReferrerCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Referrer.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L81)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-cacheNewSource"></a>cacheNewSource

```php
mixed ReferrerCore::cacheNewSource($id_connections_source)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L90)


#### Arguments
* $id_connections_source **mixed**



### <a name="method-getAjaxProduct"></a>getAjaxProduct

```php
mixed ReferrerCore::getAjaxProduct($id_referrer, $id_product, $employee)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L323)


#### Arguments
* $id_referrer **mixed**
* $id_product **mixed**
* $employee **mixed**



### <a name="method-getReferrers"></a>getReferrers

```php
mixed ReferrerCore::getReferrers(integer $id_customer)
```

Get list of referrers connections of a customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L109)


#### Arguments
* $id_customer **integer**



### <a name="method-getRegistrations"></a>getRegistrations

```php
mixed ReferrerCore::getRegistrations(integer $id_product, integer $employee)
```

Get some statistics on customers registrations for current referrer



* Visibility: **public**
* Source: [classes/Referrer.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L168)


#### Arguments
* $id_product **integer**
* $employee **integer**



### <a name="method-getStatsSales"></a>getStatsSales

```php
mixed ReferrerCore::getStatsSales(integer $id_product, integer $employee)
```

Get some statistics on orders for current referrer



* Visibility: **public**
* Source: [classes/Referrer.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L205)


#### Arguments
* $id_product **integer**
* $employee **integer**



### <a name="method-getStatsVisits"></a>getStatsVisits

```php
mixed ReferrerCore::getStatsVisits(integer $id_product, integer $employee)
```

Get some statistics on visitors connection for current referrer



* Visibility: **public**
* Source: [classes/Referrer.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L130)


#### Arguments
* $id_product **integer**
* $employee **integer**



### <a name="method-refreshCache"></a>refreshCache

```php
true ReferrerCore::refreshCache(array $referrers, integer $employee)
```

Refresh cache data of referrer statistics in referrer_shop table



* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L257)


#### Arguments
* $referrers **array**
* $employee **integer**



### <a name="method-refreshIndex"></a>refreshIndex

```php
mixed ReferrerCore::refreshIndex(array $referrers)
```

Cache liaison between connections_source data and referrers data



* Visibility: **public**
* This method is **static**.
* Source: [classes/Referrer.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Referrer.php#L296)


#### Arguments
* $referrers **array**


