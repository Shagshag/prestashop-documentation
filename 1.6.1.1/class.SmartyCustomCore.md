Class SmartyCustomCore
=====================





* Class name: SmartyCustomCore
* Parent class: Smarty
* Source: [classes/SmartyCustom.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L27)





Methods
-------
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

    mixed SmartyCustomCore::__construct()





* Visibility: **public**
* Source: [classes/SmartyCustom.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L29)




### <a name="method-check_compile_cache_invalidation"></a>check_compile_cache_invalidation

    mixed SmartyCustomCore::check_compile_cache_invalidation()

Check the compile cache needs to be invalidated (multi front + local cache compatible)



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L87)




### <a name="method-check_template_invalidation"></a>check_template_invalidation

    mixed SmartyCustomCore::check_template_invalidation(string $template, string $cache_id, string $compile_id)

Handle the lazy template cache invalidation



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L134)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-clearAllCache"></a>clearAllCache

    integer SmartyCustomCore::clearAllCache(integer $exp_time, string $type)

Mark all template files to be regenerated



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L62)


#### Arguments
* $exp_time **integer** - expiration time
* $type **string** - resource type



### <a name="method-clearCache"></a>clearCache

    integer SmartyCustomCore::clearCache(string $template_name, string $cache_id, string $compile_id, integer $exp_time, string $type)

Mark file to be regenerated for a specific template



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L79)


#### Arguments
* $template_name **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id
* $exp_time **integer** - expiration time
* $type **string** - resource type



### <a name="method-clearCompiledTemplate"></a>clearCompiledTemplate

    integer SmartyCustomCore::clearCompiledTemplate(string $resource_name, string $compile_id, integer $exp_time)

Delete compiled template file (lazy delete if resource_name is not specified)



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L44)


#### Arguments
* $resource_name **string** - template name
* $compile_id **string** - compile id
* $exp_time **integer** - expiration time



### <a name="method-createTemplate"></a>createTemplate

    mixed SmartyCustomCore::createTemplate($template, $cache_id, $compile_id, $parent, $do_clone)

{@inheritDoc}



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L116)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**
* $parent **mixed**
* $do_clone **mixed**



### <a name="method-delete_from_lazy_cache"></a>delete_from_lazy_cache

    boolean SmartyCustomCore::delete_from_lazy_cache(string $template, string $cache_id, string $compile_id)

Delete the current template from the lazy cache or the whole cache if no template name is given



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L275)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-fetch"></a>fetch

    mixed SmartyCustomCore::fetch($template, $cache_id, $compile_id, $parent, $display, $merge_tpl_vars, $no_output_filter)

{@inheritDoc}



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L107)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**
* $parent **mixed**
* $display **mixed**
* $merge_tpl_vars **mixed**
* $no_output_filter **mixed**



### <a name="method-insert_in_lazy_cache"></a>insert_in_lazy_cache

    boolean SmartyCustomCore::insert_in_lazy_cache(string $template, string $cache_id, string $compile_id)

Insert the current template in the lazy cache



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L248)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-is_in_lazy_cache"></a>is_in_lazy_cache

    boolean SmartyCustomCore::is_in_lazy_cache(string $template, string $cache_id, string $compile_id)

Check if the current template is stored in the lazy cache
Entry in the lazy cache = no need to regenerate the template



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L196)


#### Arguments
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id



### <a name="method-update_filepath"></a>update_filepath

    mixed SmartyCustomCore::update_filepath(string $filepath, string $template, string $cache_id, string $compile_id)

Store the cache file path



* Visibility: **public**
* Source: [classes/SmartyCustom.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L170)


#### Arguments
* $filepath **string** - cache file path
* $template **string** - template name
* $cache_id **string** - cache id
* $compile_id **string** - compile id


