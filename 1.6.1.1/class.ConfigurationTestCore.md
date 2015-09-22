Class ConfigurationTestCore
=====================





* Class name: ConfigurationTestCore
* Source: [classes/ConfigurationTest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L27)



Properties
----------

* [$test_files](#property-$test_files)

Methods
-------
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

    public mixed $test_files = array('/cache/smarty/compile/index.php', '/classes/log/index.php', '/classes/cache/index.php', '/config/index.php', '/tools/tar/Archive_Tar.php', '/tools/pear/PEAR.php', '/controllers/admin/AdminLoginController.php', '/css/index.php', '/download/index.php', '/img/404.gif', '/js/tools.js', '/js/jquery/plugins/fancybox/jquery.fancybox.js', '/localization/fr.xml', '/mails/index.php', '/modules/index.php', '/override/controllers/front/index.php', '/pdf/order-return.tpl', '/themes/default-bootstrap/css/global.css', '/translations/export/index.php', '/webservice/dispatcher.php', '/upload/index.php', '/index.php')





* Visibility: **public**
* This property is **static**.
* Source: [classes/ConfigurationTest.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L29).


Methods
-------


### <a name="method-check"></a>check

    array ConfigurationTestCore::check(array $tests)

run all test defined in $tests



* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L123)


#### Arguments
* $tests **array**



### <a name="method-getDefaultTests"></a>getDefaultTests

    array ConfigurationTestCore::getDefaultTests()

getDefaultTests return an array of tests to executes.

key are method name, value are parameters (false for no parameter)
all path are _PS_ROOT_DIR_ related

* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L61)




### <a name="method-getDefaultTestsOp"></a>getDefaultTestsOp

    array ConfigurationTestCore::getDefaultTestsOp()

getDefaultTestsOp return an array of tests to executes.

key are method name, value are parameters (false for no parameter)

* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L102)




### <a name="method-run"></a>run

    mixed ConfigurationTestCore::run($ptr, $arg)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L132)


#### Arguments
* $ptr **mixed**
* $arg **mixed**



### <a name="method-test_admin_dir"></a>test_admin_dir

    mixed ConfigurationTestCore::test_admin_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L262)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_dir"></a>test_cache_dir

    mixed ConfigurationTestCore::test_cache_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L277)


#### Arguments
* $dir **mixed**



### <a name="method-test_cache_v2_dir"></a>test_cache_v2_dir

    mixed ConfigurationTestCore::test_cache_v2_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L287)


#### Arguments
* $dir **mixed**



### <a name="method-test_config_dir"></a>test_config_dir

    mixed ConfigurationTestCore::test_config_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L242)


#### Arguments
* $dir **mixed**



### <a name="method-test_customizable_products_dir"></a>test_customizable_products_dir

    mixed ConfigurationTestCore::test_customizable_products_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L334)


#### Arguments
* $dir **mixed**



### <a name="method-test_dir"></a>test_dir

    mixed ConfigurationTestCore::test_dir($relative_dir, $recursive, $full_report)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L203)


#### Arguments
* $relative_dir **mixed**
* $recursive **mixed**
* $full_report **mixed**



### <a name="method-test_dom"></a>test_dom

    mixed ConfigurationTestCore::test_dom()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L362)




### <a name="method-test_download_dir"></a>test_download_dir

    mixed ConfigurationTestCore::test_download_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L292)


#### Arguments
* $dir **mixed**



### <a name="method-test_file"></a>test_file

    mixed ConfigurationTestCore::test_file($file_relative)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L236)


#### Arguments
* $file_relative **mixed**



### <a name="method-test_files"></a>test_files

    mixed ConfigurationTestCore::test_files($full)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L367)


#### Arguments
* $full **mixed**



### <a name="method-test_fopen"></a>test_fopen

    mixed ConfigurationTestCore::test_fopen()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L170)




### <a name="method-test_gd"></a>test_gd

    mixed ConfigurationTestCore::test_gd()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L185)




### <a name="method-test_gz"></a>test_gz

    mixed ConfigurationTestCore::test_gz()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L195)




### <a name="method-test_img_dir"></a>test_img_dir

    mixed ConfigurationTestCore::test_img_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L267)


#### Arguments
* $dir **mixed**



### <a name="method-test_log_dir"></a>test_log_dir

    mixed ConfigurationTestCore::test_log_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L257)


#### Arguments
* $dir **mixed**



### <a name="method-test_magicquotes"></a>test_magicquotes

    mixed ConfigurationTestCore::test_magicquotes()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L160)




### <a name="method-test_mails_dir"></a>test_mails_dir

    mixed ConfigurationTestCore::test_mails_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L297)


#### Arguments
* $dir **mixed**



### <a name="method-test_mbstring"></a>test_mbstring

    mixed ConfigurationTestCore::test_mbstring()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L344)




### <a name="method-test_mcrypt"></a>test_mcrypt

    mixed ConfigurationTestCore::test_mcrypt()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L349)




### <a name="method-test_module_dir"></a>test_module_dir

    mixed ConfigurationTestCore::test_module_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L272)


#### Arguments
* $dir **mixed**



### <a name="method-test_mysql_support"></a>test_mysql_support

    mixed ConfigurationTestCore::test_mysql_support()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L150)




### <a name="method-test_new_phpversion"></a>test_new_phpversion

    mixed ConfigurationTestCore::test_new_phpversion()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L145)




### <a name="method-test_pdo_mysql"></a>test_pdo_mysql

    mixed ConfigurationTestCore::test_pdo_mysql()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L155)




### <a name="method-test_phpversion"></a>test_phpversion

    mixed ConfigurationTestCore::test_phpversion()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L140)




### <a name="method-test_register_globals"></a>test_register_globals

    mixed ConfigurationTestCore::test_register_globals()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L190)




### <a name="method-test_root_dir"></a>test_root_dir

    mixed ConfigurationTestCore::test_root_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L252)


#### Arguments
* $dir **mixed**



### <a name="method-test_sessions"></a>test_sessions

    mixed ConfigurationTestCore::test_sessions()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L354)




### <a name="method-test_sitemap"></a>test_sitemap

    mixed ConfigurationTestCore::test_sitemap($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L247)


#### Arguments
* $dir **mixed**



### <a name="method-test_system"></a>test_system

    mixed ConfigurationTestCore::test_system($funcs)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L175)


#### Arguments
* $funcs **mixed**



### <a name="method-test_theme_cache_dir"></a>test_theme_cache_dir

    mixed ConfigurationTestCore::test_theme_cache_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L325)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_lang_dir"></a>test_theme_lang_dir

    mixed ConfigurationTestCore::test_theme_lang_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L307)


#### Arguments
* $dir **mixed**



### <a name="method-test_theme_pdf_lang_dir"></a>test_theme_pdf_lang_dir

    mixed ConfigurationTestCore::test_theme_pdf_lang_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L316)


#### Arguments
* $dir **mixed**



### <a name="method-test_tools_v2_dir"></a>test_tools_v2_dir

    mixed ConfigurationTestCore::test_tools_v2_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L282)


#### Arguments
* $dir **mixed**



### <a name="method-test_translations_dir"></a>test_translations_dir

    mixed ConfigurationTestCore::test_translations_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L302)


#### Arguments
* $dir **mixed**



### <a name="method-test_upload"></a>test_upload

    mixed ConfigurationTestCore::test_upload()





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L165)




### <a name="method-test_virtual_products_dir"></a>test_virtual_products_dir

    mixed ConfigurationTestCore::test_virtual_products_dir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConfigurationTest.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ConfigurationTest.php#L339)


#### Arguments
* $dir **mixed**


