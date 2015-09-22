SmartyCustomCore
===============






* Class name: SmartyCustomCore
* Parent class: Smarty
* This class is defined in [classes/SmartyCustom.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#L27)







Methods
-------


### __construct

    mixed SmartyCustomCore::__construct()





* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#29)




### clearCompiledTemplate

    integer SmartyCustomCore::clearCompiledTemplate(string $resource_name, string $compile_id, integer $exp_time)

Delete compiled template file (lazy delete if resource_name is not specified)



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#44)


#### Arguments
* $resource_name **string** - &lt;p&gt;template name&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $exp_time **integer** - &lt;p&gt;expiration time&lt;/p&gt;



### clearAllCache

    integer SmartyCustomCore::clearAllCache(integer $exp_time, string $type)

Mark all template files to be regenerated



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#62)


#### Arguments
* $exp_time **integer** - &lt;p&gt;expiration time&lt;/p&gt;
* $type **string** - &lt;p&gt;resource type&lt;/p&gt;



### clearCache

    integer SmartyCustomCore::clearCache(string $template_name, string $cache_id, string $compile_id, integer $exp_time, string $type)

Mark file to be regenerated for a specific template



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#79)


#### Arguments
* $template_name **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;
* $exp_time **integer** - &lt;p&gt;expiration time&lt;/p&gt;
* $type **string** - &lt;p&gt;resource type&lt;/p&gt;



### check_compile_cache_invalidation

    mixed SmartyCustomCore::check_compile_cache_invalidation()

Check the compile cache needs to be invalidated (multi front + local cache compatible)



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#87)




### fetch

    mixed SmartyCustomCore::fetch($template, $cache_id, $compile_id, $parent, $display, $merge_tpl_vars, $no_output_filter)

{@inheritDoc}



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#107)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**
* $parent **mixed**
* $display **mixed**
* $merge_tpl_vars **mixed**
* $no_output_filter **mixed**



### createTemplate

    mixed SmartyCustomCore::createTemplate($template, $cache_id, $compile_id, $parent, $do_clone)

{@inheritDoc}



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#116)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**
* $parent **mixed**
* $do_clone **mixed**



### check_template_invalidation

    mixed SmartyCustomCore::check_template_invalidation(string $template, string $cache_id, string $compile_id)

Handle the lazy template cache invalidation



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#134)


#### Arguments
* $template **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;



### update_filepath

    mixed SmartyCustomCore::update_filepath(string $filepath, string $template, string $cache_id, string $compile_id)

Store the cache file path



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#170)


#### Arguments
* $filepath **string** - &lt;p&gt;cache file path&lt;/p&gt;
* $template **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;



### is_in_lazy_cache

    boolean SmartyCustomCore::is_in_lazy_cache(string $template, string $cache_id, string $compile_id)

Check if the current template is stored in the lazy cache
Entry in the lazy cache = no need to regenerate the template



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#196)


#### Arguments
* $template **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;



### insert_in_lazy_cache

    boolean SmartyCustomCore::insert_in_lazy_cache(string $template, string $cache_id, string $compile_id)

Insert the current template in the lazy cache



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#248)


#### Arguments
* $template **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;



### delete_from_lazy_cache

    boolean SmartyCustomCore::delete_from_lazy_cache(string $template, string $cache_id, string $compile_id)

Delete the current template from the lazy cache or the whole cache if no template name is given



* Visibility: **public**
* This method is defined in [classes/SmartyCustom.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SmartyCustom.php#275)


#### Arguments
* $template **string** - &lt;p&gt;template name&lt;/p&gt;
* $cache_id **string** - &lt;p&gt;cache id&lt;/p&gt;
* $compile_id **string** - &lt;p&gt;compile id&lt;/p&gt;


