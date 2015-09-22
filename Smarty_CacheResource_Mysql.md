Smarty_CacheResource_Mysql
===============






* Class name: Smarty_CacheResource_Mysql
* Parent class: Smarty_CacheResource_Custom
* This class is defined in [classes/SmartyCacheResourceMysql.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCacheResourceMysql.php#L29)







Methods
-------
* [fetch](#method-fetch)
* [fetchTimestamp](#method-fetchTimestamp)
* [save](#method-save)
* [delete](#method-delete)






Methods
-------


### <a name="method-fetch"></a>fetch

    void Smarty_CacheResource_Mysql::fetch(string $id, string $name, string $cache_id, string $compile_id, string $content, integer $mtime)

fetch cached content and its modification time from data source



* Visibility: **protected**
* This method is defined in [classes/SmartyCacheResourceMysql.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCacheResourceMysql.php#L42)


#### Arguments
* $id **string** - &lt;p&gt;unique cache content identifier&lt;/p&gt;
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $content **string** - &lt;p&gt;cached content&lt;/p&gt;
* $mtime **integer** - &lt;p&gt;cache modification timestamp (epoch)&lt;/p&gt;



### <a name="method-fetchTimestamp"></a>fetchTimestamp

    integer|boolean Smarty_CacheResource_Mysql::fetchTimestamp(string $id, string $name, string $cache_id, string $compile_id)

Fetch cached content's modification timestamp from data source



* Visibility: **protected**
* This method is defined in [classes/SmartyCacheResourceMysql.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCacheResourceMysql.php#L64)


#### Arguments
* $id **string** - &lt;p&gt;unique cache content identifier&lt;/p&gt;
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;



### <a name="method-save"></a>save

    boolean Smarty_CacheResource_Mysql::save(string $id, string $name, string $cache_id, string $compile_id, integer|null $exp_time, string $content)

Save content to cache



* Visibility: **protected**
* This method is defined in [classes/SmartyCacheResourceMysql.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCacheResourceMysql.php#L82)


#### Arguments
* $id **string** - &lt;p&gt;unique cache content identifier&lt;/p&gt;
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $exp_time **integer|null** - &lt;p&gt;seconds till expiration time in seconds or null&lt;/p&gt;
* $content **string** - &lt;p&gt;content to cache&lt;/p&gt;



### <a name="method-delete"></a>delete

    integer Smarty_CacheResource_Mysql::delete(string $name, string $cache_id, string $compile_id, integer|null $exp_time)

Delete content from cache



* Visibility: **protected**
* This method is defined in [classes/SmartyCacheResourceMysql.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCacheResourceMysql.php#L105)


#### Arguments
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $exp_time **integer|null** - &lt;p&gt;seconds till expiration or null&lt;/p&gt;


