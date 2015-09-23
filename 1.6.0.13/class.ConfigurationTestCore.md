Class ConfigurationTestCore
=====================





* Class name: ConfigurationTestCore
* Source: [classes/ConfigurationTest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L27)


Contents
--------


### Properties

* [$test_files](#property-$test_files)

### Methods

* [check](#method-check)
* [getDefaultTests](#method-getDefaultTests)
* [getDefaultTestsOp](#method-getDefaultTestsOp)
* [run](#method-run)
* [test_admin_dir](#method-test_admin_dir)
* [test_cache_dir](#method-test_cache_dir)
* [test_cache_v2_dir](#method-test_cache_v2_dir)
* [test_config_dir](#method-test_config_dir)
* [test_customizable_products_dir](#method-test_customizable_products_dir)
* [test_dir](#method-test_dir)
* [test_dom](#method-test_dom)
* [test_download_dir](#method-test_download_dir)
* [test_file](#method-test_file)
* [test_files](#method-test_files)
* [test_fopen](#method-test_fopen)
* [test_gd](#method-test_gd)
* [test_gz](#method-test_gz)
* [test_img_dir](#method-test_img_dir)
* [test_log_dir](#method-test_log_dir)
* [test_magicquotes](#method-test_magicquotes)
* [test_mails_dir](#method-test_mails_dir)
* [test_mbstring](#method-test_mbstring)
* [test_mcrypt](#method-test_mcrypt)
* [test_module_dir](#method-test_module_dir)
* [test_mysql_support](#method-test_mysql_support)
* [test_pdo_mysql](#method-test_pdo_mysql)
* [test_phpversion](#method-test_phpversion)
* [test_register_globals](#method-test_register_globals)
* [test_root_dir](#method-test_root_dir)
* [test_sessions](#method-test_sessions)
* [test_sitemap](#method-test_sitemap)
* [test_system](#method-test_system)
* [test_theme_cache_dir](#method-test_theme_cache_dir)
* [test_theme_lang_dir](#method-test_theme_lang_dir)
* [test_theme_pdf_lang_dir](#method-test_theme_pdf_lang_dir)
* [test_tools_v2_dir](#method-test_tools_v2_dir)
* [test_translations_dir](#method-test_translations_dir)
* [test_upload](#method-test_upload)
* [test_virtual_products_dir](#method-test_virtual_products_dir)




Properties
----------


### <a name="property-$test_files"></a>$test_files

```php
public mixed $test_files = array('/cache/smarty/compile/index.php', '/classes/log/index.php', '/classes/cache/index.php', '/config/index.php', '/tools/tar/Archive_Tar.php', '/tools/pear/PEAR.php', '/controllers/admin/AdminLoginController.php', '/css/index.php', '/download/index.php', '/img/404.gif', '/js/tools.js', '/js/jquery/plugins/fancybox/jquery.fancybox.js', '/localization/fr.xml', '/mails/index.php', '/modules/index.php', '/override/controllers/front/index.php', '/pdf/order-return.tpl', '/themes/default-bootstrap/css/global.css', '/translations/export/index.php', '/webservice/dispatcher.php', '/upload/index.php', '/index.php')
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/ConfigurationTest.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L30).


Methods
-------


### <a name="method-check"></a>check

```php
array ConfigurationTestCore::check(array $tests)
```

run all test defined in $tests



* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L122)


#### Arguments
* $tests **array**



### <a name="method-getDefaultTests"></a>getDefaultTests

```php
array ConfigurationTestCore::getDefaultTests()
```

getDefaultTests return an array of tests to executes.

key are method name, value are parameters (false for no parameter)
all path are _PS_ROOT_DIR_ related

* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L62)




### <a name="method-getDefaultTestsOp"></a>getDefaultTestsOp

```php
array ConfigurationTestCore::getDefaultTestsOp()
```

getDefaultTestsOp return an array of tests to executes.

key are method name, value are parameters (false for no parameter)

* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L102)




### <a name="method-run"></a>run

```php
mixed ConfigurationTestCore::run($ptr, $arg)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L130)


#### Arguments
* $ptr **mixed**
* $arg **mixed**



### <a name="method-test_admin_dir"></a>test_admin_dir

```php
mixed ConfigurationTestCore::test_admin_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L252)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_dir"></a>test_cache_dir

```php
mixed ConfigurationTestCore::test_cache_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L267)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_v2_dir"></a>test_cache_v2_dir

```php
mixed ConfigurationTestCore::test_cache_v2_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L277)


#### Arguments
* $dir **mixed**



### <a name="method-test_config_dir"></a>test_config_dir

```php
mixed ConfigurationTestCore::test_config_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L232)


#### Arguments
* $dir **mixed**



### <a name="method-test_customizable_products_dir"></a>test_customizable_products_dir

```php
mixed ConfigurationTestCore::test_customizable_products_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L321)


#### Arguments
* $dir **mixed**



### <a name="method-test_dir"></a>test_dir

```php
mixed ConfigurationTestCore::test_dir($relative_dir, $recursive, $full_report)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L192)


#### Arguments
* $relative_dir **mixed**
* $recursive **mixed**
* $full_report **mixed**



### <a name="method-test_dom"></a>test_dom

```php
mixed ConfigurationTestCore::test_dom()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L348)




### <a name="method-test_download_dir"></a>test_download_dir

```php
mixed ConfigurationTestCore::test_download_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L282)


#### Arguments
* $dir **mixed**



### <a name="method-test_file"></a>test_file

```php
mixed ConfigurationTestCore::test_file($file_relative)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L226)


#### Arguments
* $file_relative **mixed**



### <a name="method-test_files"></a>test_files

```php
mixed ConfigurationTestCore::test_files($full)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L353)


#### Arguments
* $full **mixed**



### <a name="method-test_fopen"></a>test_fopen

```php
mixed ConfigurationTestCore::test_fopen()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L162)




### <a name="method-test_gd"></a>test_gd

```php
mixed ConfigurationTestCore::test_gd()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L175)




### <a name="method-test_gz"></a>test_gz

```php
mixed ConfigurationTestCore::test_gz()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L185)




### <a name="method-test_img_dir"></a>test_img_dir

```php
mixed ConfigurationTestCore::test_img_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L257)


#### Arguments
* $dir **mixed**



### <a name="method-test_log_dir"></a>test_log_dir

```php
mixed ConfigurationTestCore::test_log_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L247)


#### Arguments
* $dir **mixed**



### <a name="method-test_magicquotes"></a>test_magicquotes

```php
mixed ConfigurationTestCore::test_magicquotes()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L152)




### <a name="method-test_mails_dir"></a>test_mails_dir

```php
mixed ConfigurationTestCore::test_mails_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L287)


#### Arguments
* $dir **mixed**



### <a name="method-test_mbstring"></a>test_mbstring

```php
mixed ConfigurationTestCore::test_mbstring()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L331)




### <a name="method-test_mcrypt"></a>test_mcrypt

```php
mixed ConfigurationTestCore::test_mcrypt()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L336)




### <a name="method-test_module_dir"></a>test_module_dir

```php
mixed ConfigurationTestCore::test_module_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L262)


#### Arguments
* $dir **mixed**



### <a name="method-test_mysql_support"></a>test_mysql_support

```php
mixed ConfigurationTestCore::test_mysql_support()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L142)




### <a name="method-test_pdo_mysql"></a>test_pdo_mysql

```php
mixed ConfigurationTestCore::test_pdo_mysql()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L147)




### <a name="method-test_phpversion"></a>test_phpversion

```php
mixed ConfigurationTestCore::test_phpversion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L137)




### <a name="method-test_register_globals"></a>test_register_globals

```php
mixed ConfigurationTestCore::test_register_globals()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L180)




### <a name="method-test_root_dir"></a>test_root_dir

```php
mixed ConfigurationTestCore::test_root_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L242)


#### Arguments
* $dir **mixed**



### <a name="method-test_sessions"></a>test_sessions

```php
mixed ConfigurationTestCore::test_sessions()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L341)




### <a name="method-test_sitemap"></a>test_sitemap

```php
mixed ConfigurationTestCore::test_sitemap($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L237)


#### Arguments
* $dir **mixed**



### <a name="method-test_system"></a>test_system

```php
mixed ConfigurationTestCore::test_system($funcs)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L167)


#### Arguments
* $funcs **mixed**



### <a name="method-test_theme_cache_dir"></a>test_theme_cache_dir

```php
mixed ConfigurationTestCore::test_theme_cache_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L313)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_lang_dir"></a>test_theme_lang_dir

```php
mixed ConfigurationTestCore::test_theme_lang_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L297)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_pdf_lang_dir"></a>test_theme_pdf_lang_dir

```php
mixed ConfigurationTestCore::test_theme_pdf_lang_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L305)


#### Arguments
* $dir **mixed**



### <a name="method-test_tools_v2_dir"></a>test_tools_v2_dir

```php
mixed ConfigurationTestCore::test_tools_v2_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L272)


#### Arguments
* $dir **mixed**



### <a name="method-test_translations_dir"></a>test_translations_dir

```php
mixed ConfigurationTestCore::test_translations_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L292)


#### Arguments
* $dir **mixed**



### <a name="method-test_upload"></a>test_upload

```php
mixed ConfigurationTestCore::test_upload()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L157)




### <a name="method-test_virtual_products_dir"></a>test_virtual_products_dir

```php
mixed ConfigurationTestCore::test_virtual_products_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/ConfigurationTest.php#L326)


#### Arguments
* $dir **mixed**


