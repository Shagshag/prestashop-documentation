Class Smarty_CacheResource_Mysql
=====================





* Class name: Smarty_CacheResource_Mysql
* Parent class: Smarty_CacheResource_Custom
* Source: [classes/SmartyCacheResourceMysql.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/SmartyCacheResourceMysql.php#L29)


Contents
--------



### Methods

* [delete](#method-delete)
* [fetch](#method-fetch)
* [fetchTimestamp](#method-fetchTimestamp)
* [save](#method-save)






Methods
-------


### <a name="method-delete"></a>delete

```php
integer Smarty_CacheResource_Mysql::delete(string $name, string $cache_id, string $compile_id, integer|null $exp_time)
```

Delete content from cache



* Visibility: **protected**
* Source: [classes/SmartyCacheResourceMysql.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/SmartyCacheResourceMysql.php#L108)


#### Arguments
* $name **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id
* $exp_time **integer|null** - seconds till expiration or null



### <a name="method-fetch"></a>fetch

```php
void Smarty_CacheResource_Mysql::fetch(string $id, string $name, string $cache_id, string $compile_id, string $content, integer $mtime)
```

fetch cached content and its modification time from data source



* Visibility: **protected**
* Source: [classes/SmartyCacheResourceMysql.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/SmartyCacheResourceMysql.php#L42)


#### Arguments
* $id **string** - unique cache content identifier
* $name **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id
* $content **string** - cached content
* $mtime **integer** - cache modification timestamp (epoch)



### <a name="method-fetchTimestamp"></a>fetchTimestamp

```php
integer|boolean Smarty_CacheResource_Mysql::fetchTimestamp(string $id, string $name, string $cache_id, string $compile_id)
```

Fetch cached content's modification timestamp from data source



* Visibility: **protected**
* Source: [classes/SmartyCacheResourceMysql.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/SmartyCacheResourceMysql.php#L67)


#### Arguments
* $id **string** - unique cache content identifier
* $name **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-save"></a>save

```php
boolean Smarty_CacheResource_Mysql::save(string $id, string $name, string $cache_id, string $compile_id, integer|null $exp_time, string $content)
```

Save content to cache



* Visibility: **protected**
* Source: [classes/SmartyCacheResourceMysql.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/SmartyCacheResourceMysql.php#L85)


#### Arguments
* $id **string** - unique cache content identifier
* $name **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id
* $exp_time **integer|null** - seconds till expiration time in seconds or null
* $content **string** - content to cache


