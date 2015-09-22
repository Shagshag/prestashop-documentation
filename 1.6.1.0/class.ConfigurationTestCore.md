Class ConfigurationTestCore
=====================





* Class name: ConfigurationTestCore
* Source: [classes/ConfigurationTest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L27)


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
* [test_new_phpversion](#method-test_new_phpversion)
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
* Source: [classes/ConfigurationTest.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L30).


Methods
-------


### <a name="method-check"></a>check

```php
array ConfigurationTestCore::check(array $tests)
```

run all test defined in $tests



* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L123)


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
* Source: [classes/ConfigurationTest.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L62)




### <a name="method-getDefaultTestsOp"></a>getDefaultTestsOp

```php
array ConfigurationTestCore::getDefaultTestsOp()
```

getDefaultTestsOp return an array of tests to executes.

key are method name, value are parameters (false for no parameter)

* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L102)




### <a name="method-run"></a>run

```php
mixed ConfigurationTestCore::run($ptr, $arg)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L131)


#### Arguments
* $ptr **mixed**
* $arg **mixed**



### <a name="method-test_admin_dir"></a>test_admin_dir

```php
mixed ConfigurationTestCore::test_admin_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L258)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_dir"></a>test_cache_dir

```php
mixed ConfigurationTestCore::test_cache_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L273)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_v2_dir"></a>test_cache_v2_dir

```php
mixed ConfigurationTestCore::test_cache_v2_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L283)


#### Arguments
* $dir **mixed**



### <a name="method-test_config_dir"></a>test_config_dir

```php
mixed ConfigurationTestCore::test_config_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L238)


#### Arguments
* $dir **mixed**



### <a name="method-test_customizable_products_dir"></a>test_customizable_products_dir

```php
mixed ConfigurationTestCore::test_customizable_products_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L327)


#### Arguments
* $dir **mixed**



### <a name="method-test_dir"></a>test_dir

```php
mixed ConfigurationTestCore::test_dir($relative_dir, $recursive, $full_report)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L198)


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
* Source: [classes/ConfigurationTest.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L354)




### <a name="method-test_download_dir"></a>test_download_dir

```php
mixed ConfigurationTestCore::test_download_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L288)


#### Arguments
* $dir **mixed**



### <a name="method-test_file"></a>test_file

```php
mixed ConfigurationTestCore::test_file($file_relative)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L232)


#### Arguments
* $file_relative **mixed**



### <a name="method-test_files"></a>test_files

```php
mixed ConfigurationTestCore::test_files($full)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L359)


#### Arguments
* $full **mixed**



### <a name="method-test_fopen"></a>test_fopen

```php
mixed ConfigurationTestCore::test_fopen()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L168)




### <a name="method-test_gd"></a>test_gd

```php
mixed ConfigurationTestCore::test_gd()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L181)




### <a name="method-test_gz"></a>test_gz

```php
mixed ConfigurationTestCore::test_gz()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L191)




### <a name="method-test_img_dir"></a>test_img_dir

```php
mixed ConfigurationTestCore::test_img_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L263)


#### Arguments
* $dir **mixed**



### <a name="method-test_log_dir"></a>test_log_dir

```php
mixed ConfigurationTestCore::test_log_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L253)


#### Arguments
* $dir **mixed**



### <a name="method-test_magicquotes"></a>test_magicquotes

```php
mixed ConfigurationTestCore::test_magicquotes()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L158)




### <a name="method-test_mails_dir"></a>test_mails_dir

```php
mixed ConfigurationTestCore::test_mails_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L293)


#### Arguments
* $dir **mixed**



### <a name="method-test_mbstring"></a>test_mbstring

```php
mixed ConfigurationTestCore::test_mbstring()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L337)




### <a name="method-test_mcrypt"></a>test_mcrypt

```php
mixed ConfigurationTestCore::test_mcrypt()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L342)




### <a name="method-test_module_dir"></a>test_module_dir

```php
mixed ConfigurationTestCore::test_module_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L268)


#### Arguments
* $dir **mixed**



### <a name="method-test_mysql_support"></a>test_mysql_support

```php
mixed ConfigurationTestCore::test_mysql_support()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L148)




### <a name="method-test_new_phpversion"></a>test_new_phpversion

```php
mixed ConfigurationTestCore::test_new_phpversion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L143)




### <a name="method-test_pdo_mysql"></a>test_pdo_mysql

```php
mixed ConfigurationTestCore::test_pdo_mysql()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L153)




### <a name="method-test_phpversion"></a>test_phpversion

```php
mixed ConfigurationTestCore::test_phpversion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L138)




### <a name="method-test_register_globals"></a>test_register_globals

```php
mixed ConfigurationTestCore::test_register_globals()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L186)




### <a name="method-test_root_dir"></a>test_root_dir

```php
mixed ConfigurationTestCore::test_root_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L248)


#### Arguments
* $dir **mixed**



### <a name="method-test_sessions"></a>test_sessions

```php
mixed ConfigurationTestCore::test_sessions()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L347)




### <a name="method-test_sitemap"></a>test_sitemap

```php
mixed ConfigurationTestCore::test_sitemap($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L243)


#### Arguments
* $dir **mixed**



### <a name="method-test_system"></a>test_system

```php
mixed ConfigurationTestCore::test_system($funcs)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L173)


#### Arguments
* $funcs **mixed**



### <a name="method-test_theme_cache_dir"></a>test_theme_cache_dir

```php
mixed ConfigurationTestCore::test_theme_cache_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L319)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_lang_dir"></a>test_theme_lang_dir

```php
mixed ConfigurationTestCore::test_theme_lang_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L303)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_pdf_lang_dir"></a>test_theme_pdf_lang_dir

```php
mixed ConfigurationTestCore::test_theme_pdf_lang_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L311)


#### Arguments
* $dir **mixed**



### <a name="method-test_tools_v2_dir"></a>test_tools_v2_dir

```php
mixed ConfigurationTestCore::test_tools_v2_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L278)


#### Arguments
* $dir **mixed**



### <a name="method-test_translations_dir"></a>test_translations_dir

```php
mixed ConfigurationTestCore::test_translations_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L298)


#### Arguments
* $dir **mixed**



### <a name="method-test_upload"></a>test_upload

```php
mixed ConfigurationTestCore::test_upload()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L163)




### <a name="method-test_virtual_products_dir"></a>test_virtual_products_dir

```php
mixed ConfigurationTestCore::test_virtual_products_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 332](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ConfigurationTest.php#L332)


#### Arguments
* $dir **mixed**


