Class SmartyCustomCore
=====================





* Class name: SmartyCustomCore
* Parent class: Smarty
* Source: [classes/SmartyCustom.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L27)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [check_compile_cache_invalidation](#method-check_compile_cache_invalidation)
* [check_template_invalidation](#method-check_template_invalidation)
* [clearAllCache](#method-clearAllCache)
* [clearCache](#method-clearCache)
* [clearCompiledTemplate](#method-clearCompiledTemplate)
* [createTemplate](#method-createTemplate)
* [delete_from_lazy_cache](#method-delete_from_lazy_cache)
* [fetch](#method-fetch)
* [insert_in_lazy_cache](#method-insert_in_lazy_cache)
* [is_in_lazy_cache](#method-is_in_lazy_cache)
* [update_filepath](#method-update_filepath)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed SmartyCustomCore::__construct()
```





* Visibility: **public**
* Source: [classes/SmartyCustom.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L30)




### <a name="method-check_compile_cache_invalidation"></a>check_compile_cache_invalidation

```php
mixed SmartyCustomCore::check_compile_cache_invalidation()
```

Check the compile cache needs to be invalidated (multi front + local cache compatible)



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L89)




### <a name="method-check_template_invalidation"></a>check_template_invalidation

```php
mixed SmartyCustomCore::check_template_invalidation(string $template, string $cache_id, string $compile_id)
```

Handle the lazy template cache invalidation



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L140)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-clearAllCache"></a>clearAllCache

```php
integer SmartyCustomCore::clearAllCache(integer $exp_time, string $type)
```

Mark all template files to be regenerated



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L64)


#### Arguments
* $exp_time **integer** - expiration time
* $type **string** - resource type



### <a name="method-clearCache"></a>clearCache

```php
integer SmartyCustomCore::clearCache(string $template_name, string $cache_id, string $compile_id, integer $exp_time, string $type)
```

Mark file to be regenerated for a specific template



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L81)


#### Arguments
* $template_name **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id
* $exp_time **integer** - expiration time
* $type **string** - resource type



### <a name="method-clearCompiledTemplate"></a>clearCompiledTemplate

```php
integer SmartyCustomCore::clearCompiledTemplate(string $resource_name, string $compile_id, integer $exp_time)
```

Delete compiled template file (lazy delete if resource_name is not specified)



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L45)


#### Arguments
* $resource_name **string** - template name
* $compile_id **string** - compile id
* $exp_time **integer** - expiration time



### <a name="method-createTemplate"></a>createTemplate

```php
mixed SmartyCustomCore::createTemplate($template, $cache_id, $compile_id, $parent, $do_clone)
```

{@inheritDoc}



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L121)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**
* $parent **mixed**
* $do_clone **mixed**



### <a name="method-delete_from_lazy_cache"></a>delete_from_lazy_cache

```php
boolean SmartyCustomCore::delete_from_lazy_cache(string $template, string $cache_id, string $compile_id)
```

Delete the current template from the lazy cache or the whole cache if no template name is given



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L285)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-fetch"></a>fetch

```php
mixed SmartyCustomCore::fetch($template, $cache_id, $compile_id, $parent, $display, $merge_tpl_vars, $no_output_filter)
```

{@inheritDoc}



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L112)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**
* $parent **mixed**
* $display **mixed**
* $merge_tpl_vars **mixed**
* $no_output_filter **mixed**



### <a name="method-insert_in_lazy_cache"></a>insert_in_lazy_cache

```php
boolean SmartyCustomCore::insert_in_lazy_cache(string $template, string $cache_id, string $compile_id)
```

Insert the current template in the lazy cache



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L259)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-is_in_lazy_cache"></a>is_in_lazy_cache

```php
boolean SmartyCustomCore::is_in_lazy_cache(string $template, string $cache_id, string $compile_id)
```

Check if the current template is stored in the lazy cache
Entry in the lazy cache = no need to regenerate the template



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L206)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-update_filepath"></a>update_filepath

```php
mixed SmartyCustomCore::update_filepath(string $filepath, string $template, string $cache_id, string $compile_id)
```

Store the cache file path



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/SmartyCustom.php#L181)


#### Arguments
* $filepath **string** - cache file path
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id


