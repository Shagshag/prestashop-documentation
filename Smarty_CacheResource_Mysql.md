Smarty_CacheResource_Mysql
===============






* Class name: Smarty_CacheResource_Mysql
* Namespace: 
* Parent class: Smarty_CacheResource_Custom







Methods
-------


### fetch

    void Smarty_CacheResource_Mysql::fetch(string $id, string $name, string $cache_id, string $compile_id, string $content, integer $mtime)

fetch cached content and its modification time from data source



* Visibility: **protected**


#### Arguments
* $id **string** - &lt;p&gt;unique cache content identifier&lt;/p&gt;
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $content **string** - &lt;p&gt;cached content&lt;/p&gt;
* $mtime **integer** - &lt;p&gt;cache modification timestamp (epoch)&lt;/p&gt;



### fetchTimestamp

    integer|boolean Smarty_CacheResource_Mysql::fetchTimestamp(string $id, string $name, string $cache_id, string $compile_id)

Fetch cached content's modification timestamp from data source



* Visibility: **protected**


#### Arguments
* $id **string** - &lt;p&gt;unique cache content identifier&lt;/p&gt;
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;



### save

    boolean Smarty_CacheResource_Mysql::save(string $id, string $name, string $cache_id, string $compile_id, integer|null $exp_time, string $content)

Save content to cache



* Visibility: **protected**


#### Arguments
* $id **string** - &lt;p&gt;unique cache content identifier&lt;/p&gt;
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $exp_time **integer|null** - &lt;p&gt;seconds till expiration time in seconds or null&lt;/p&gt;
* $content **string** - &lt;p&gt;content to cache&lt;/p&gt;



### delete

    integer Smarty_CacheResource_Mysql::delete(string $name, string $cache_id, string $compile_id, integer|null $exp_time)

Delete content from cache



* Visibility: **protected**


#### Arguments
* $name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $exp_time **integer|null** - &lt;p&gt;seconds till expiration or null&lt;/p&gt;


