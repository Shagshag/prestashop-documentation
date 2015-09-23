Class ConfigurationTestCore
=====================





* Class name: ConfigurationTestCore
* Source: [classes/ConfigurationTest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L27)


Contents
--------



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






Methods
-------


### <a name="method-check"></a>check

```php
array ConfigurationTestCore::check(array $tests)
```

run all test defined in $tests



* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L93)


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
* Source: [classes/ConfigurationTest.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L37)




### <a name="method-getDefaultTestsOp"></a>getDefaultTestsOp

```php
array ConfigurationTestCore::getDefaultTestsOp()
```

getDefaultTestsOp return an array of tests to executes.

key are method name, value are parameters (false for no parameter)

* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L73)




### <a name="method-run"></a>run

```php
mixed ConfigurationTestCore::run($ptr, $arg)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L101)


#### Arguments
* $ptr **mixed**
* $arg **mixed**



### <a name="method-test_admin_dir"></a>test_admin_dir

```php
mixed ConfigurationTestCore::test_admin_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L223)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_dir"></a>test_cache_dir

```php
mixed ConfigurationTestCore::test_cache_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L238)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_v2_dir"></a>test_cache_v2_dir

```php
mixed ConfigurationTestCore::test_cache_v2_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L248)


#### Arguments
* $dir **mixed**



### <a name="method-test_config_dir"></a>test_config_dir

```php
mixed ConfigurationTestCore::test_config_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L203)


#### Arguments
* $dir **mixed**



### <a name="method-test_customizable_products_dir"></a>test_customizable_products_dir

```php
mixed ConfigurationTestCore::test_customizable_products_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L289)


#### Arguments
* $dir **mixed**



### <a name="method-test_dir"></a>test_dir

```php
mixed ConfigurationTestCore::test_dir($relative_dir, $recursive, $full_report)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L163)


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
* Source: [classes/ConfigurationTest.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L316)




### <a name="method-test_download_dir"></a>test_download_dir

```php
mixed ConfigurationTestCore::test_download_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L253)


#### Arguments
* $dir **mixed**



### <a name="method-test_file"></a>test_file

```php
mixed ConfigurationTestCore::test_file($file_relative)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L197)


#### Arguments
* $file_relative **mixed**



### <a name="method-test_fopen"></a>test_fopen

```php
mixed ConfigurationTestCore::test_fopen()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L133)




### <a name="method-test_gd"></a>test_gd

```php
mixed ConfigurationTestCore::test_gd()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L146)




### <a name="method-test_gz"></a>test_gz

```php
mixed ConfigurationTestCore::test_gz()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L156)




### <a name="method-test_img_dir"></a>test_img_dir

```php
mixed ConfigurationTestCore::test_img_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L228)


#### Arguments
* $dir **mixed**



### <a name="method-test_log_dir"></a>test_log_dir

```php
mixed ConfigurationTestCore::test_log_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L218)


#### Arguments
* $dir **mixed**



### <a name="method-test_magicquotes"></a>test_magicquotes

```php
mixed ConfigurationTestCore::test_magicquotes()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L123)




### <a name="method-test_mails_dir"></a>test_mails_dir

```php
mixed ConfigurationTestCore::test_mails_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L258)


#### Arguments
* $dir **mixed**



### <a name="method-test_mbstring"></a>test_mbstring

```php
mixed ConfigurationTestCore::test_mbstring()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L299)




### <a name="method-test_mcrypt"></a>test_mcrypt

```php
mixed ConfigurationTestCore::test_mcrypt()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L304)




### <a name="method-test_module_dir"></a>test_module_dir

```php
mixed ConfigurationTestCore::test_module_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L233)


#### Arguments
* $dir **mixed**



### <a name="method-test_mysql_support"></a>test_mysql_support

```php
mixed ConfigurationTestCore::test_mysql_support()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L113)




### <a name="method-test_pdo_mysql"></a>test_pdo_mysql

```php
mixed ConfigurationTestCore::test_pdo_mysql()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L118)




### <a name="method-test_phpversion"></a>test_phpversion

```php
mixed ConfigurationTestCore::test_phpversion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L108)




### <a name="method-test_register_globals"></a>test_register_globals

```php
mixed ConfigurationTestCore::test_register_globals()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L151)




### <a name="method-test_root_dir"></a>test_root_dir

```php
mixed ConfigurationTestCore::test_root_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L213)


#### Arguments
* $dir **mixed**



### <a name="method-test_sessions"></a>test_sessions

```php
mixed ConfigurationTestCore::test_sessions()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L309)




### <a name="method-test_sitemap"></a>test_sitemap

```php
mixed ConfigurationTestCore::test_sitemap($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L208)


#### Arguments
* $dir **mixed**



### <a name="method-test_system"></a>test_system

```php
mixed ConfigurationTestCore::test_system($funcs)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L138)


#### Arguments
* $funcs **mixed**



### <a name="method-test_theme_cache_dir"></a>test_theme_cache_dir

```php
mixed ConfigurationTestCore::test_theme_cache_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L282)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_lang_dir"></a>test_theme_lang_dir

```php
mixed ConfigurationTestCore::test_theme_lang_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L268)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_pdf_lang_dir"></a>test_theme_pdf_lang_dir

```php
mixed ConfigurationTestCore::test_theme_pdf_lang_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L275)


#### Arguments
* $dir **mixed**



### <a name="method-test_tools_v2_dir"></a>test_tools_v2_dir

```php
mixed ConfigurationTestCore::test_tools_v2_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L243)


#### Arguments
* $dir **mixed**



### <a name="method-test_translations_dir"></a>test_translations_dir

```php
mixed ConfigurationTestCore::test_translations_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L263)


#### Arguments
* $dir **mixed**



### <a name="method-test_upload"></a>test_upload

```php
mixed ConfigurationTestCore::test_upload()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L128)




### <a name="method-test_virtual_products_dir"></a>test_virtual_products_dir

```php
mixed ConfigurationTestCore::test_virtual_products_dir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ConfigurationTest.php#L294)


#### Arguments
* $dir **mixed**


