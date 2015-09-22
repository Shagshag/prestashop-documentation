ReferrerCore
===============






* Class name: ReferrerCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Referrer.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#27)





Properties
----------


### $id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#29)


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#30)


### $passwd

    public mixed $passwd





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#31)


### $http_referer_regexp

    public mixed $http_referer_regexp





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#33)


### $http_referer_like

    public mixed $http_referer_like





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#34)


### $request_uri_regexp

    public mixed $request_uri_regexp





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#35)


### $request_uri_like

    public mixed $request_uri_like





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#36)


### $http_referer_regexp_not

    public mixed $http_referer_regexp_not





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#37)


### $http_referer_like_not

    public mixed $http_referer_like_not





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#38)


### $request_uri_regexp_not

    public mixed $request_uri_regexp_not





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#39)


### $request_uri_like_not

    public mixed $request_uri_like_not





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#40)


### $base_fee

    public mixed $base_fee





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#42)


### $percent_fee

    public mixed $percent_fee





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#43)


### $click_fee

    public mixed $click_fee





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#44)


### $date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in [classes/Referrer.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#46)


### $definition

    public mixed $definition = array('table' => 'referrer', 'primary' => 'id_referrer', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'passwd' => array('type' => self::TYPE_STRING, 'validate' => 'isPasswd', 'size' => 32), 'http_referer_regexp' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'request_uri_regexp' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'http_referer_like' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'request_uri_like' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 64), 'http_referer_regexp_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'request_uri_regexp_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'http_referer_like_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'request_uri_like_not' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml'), 'base_fee' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'percent_fee' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPercentage'), 'click_fee' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Referrer.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#51)


### $_join

    protected mixed $_join = '(r.http_referer_like IS NULL OR r.http_referer_like = \'\' OR cs.http_referer LIKE r.http_referer_like)
			AND (r.request_uri_like IS NULL OR r.request_uri_like = \'\' OR cs.request_uri LIKE r.request_uri_like)
			AND (r.http_referer_like_not IS NULL OR r.http_referer_like_not = \'\' OR cs.http_referer NOT LIKE r.http_referer_like_not)
			AND (r.request_uri_like_not IS NULL OR r.request_uri_like_not = \'\' OR cs.request_uri NOT LIKE r.request_uri_like_not)
			AND (r.http_referer_regexp IS NULL OR r.http_referer_regexp = \'\' OR cs.http_referer REGEXP r.http_referer_regexp)
			AND (r.request_uri_regexp IS NULL OR r.request_uri_regexp = \'\' OR cs.request_uri REGEXP r.request_uri_regexp)
			AND (r.http_referer_regexp_not IS NULL OR r.http_referer_regexp_not = \'\' OR cs.http_referer NOT REGEXP r.http_referer_regexp_not)
			AND (r.request_uri_regexp_not IS NULL OR r.request_uri_regexp_not = \'\' OR cs.request_uri NOT REGEXP r.request_uri_regexp_not)'





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Referrer.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#72)


Methods
-------


### add

    mixed ReferrerCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Referrer.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#81)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### cacheNewSource

    mixed ReferrerCore::cacheNewSource($id_connections_source)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Referrer.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#91)


#### Arguments
* $id_connections_source **mixed**



### getReferrers

    mixed ReferrerCore::getReferrers(integer $id_customer)

Get list of referrers connections of a customer



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Referrer.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#111)


#### Arguments
* $id_customer **integer**



### getStatsVisits

    mixed ReferrerCore::getStatsVisits(integer $id_product, integer $employee)

Get some statistics on visitors connection for current referrer



* Visibility: **public**
* This method is defined in [classes/Referrer.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#131)


#### Arguments
* $id_product **integer**
* $employee **integer**



### getRegistrations

    mixed ReferrerCore::getRegistrations(integer $id_product, integer $employee)

Get some statistics on customers registrations for current referrer



* Visibility: **public**
* This method is defined in [classes/Referrer.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#167)


#### Arguments
* $id_product **integer**
* $employee **integer**



### getStatsSales

    mixed ReferrerCore::getStatsSales(integer $id_product, integer $employee)

Get some statistics on orders for current referrer



* Visibility: **public**
* This method is defined in [classes/Referrer.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#203)


#### Arguments
* $id_product **integer**
* $employee **integer**



### refreshCache

    true ReferrerCore::refreshCache(array $referrers, integer $employee)

Refresh cache data of referrer statistics in referrer_shop table



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Referrer.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#255)


#### Arguments
* $referrers **array**
* $employee **integer**



### refreshIndex

    mixed ReferrerCore::refreshIndex(array $referrers)

Cache liaison between connections_source data and referrers data



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Referrer.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#294)


#### Arguments
* $referrers **array**



### getAjaxProduct

    mixed ReferrerCore::getAjaxProduct($id_referrer, $id_product, $employee)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Referrer.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Referrer.php#319)


#### Arguments
* $id_referrer **mixed**
* $id_product **mixed**
* $employee **mixed**


