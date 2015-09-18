ConfigurationTestCore
===============






* Class name: ConfigurationTestCore
* Namespace: 





Properties
----------


### $test_files

    public mixed $test_files = array('/cache/smarty/compile/index.php', '/classes/log/index.php', '/classes/cache/index.php', '/config/index.php', '/tools/tar/Archive_Tar.php', '/tools/pear/PEAR.php', '/controllers/admin/AdminLoginController.php', '/css/index.php', '/download/index.php', '/img/404.gif', '/js/tools.js', '/js/jquery/plugins/fancybox/jquery.fancybox.js', '/localization/fr.xml', '/mails/index.php', '/modules/index.php', '/override/controllers/front/index.php', '/pdf/order-return.tpl', '/themes/default-bootstrap/css/global.css', '/translations/export/index.php', '/webservice/dispatcher.php', '/upload/index.php', '/index.php')





* Visibility: **public**
* This property is **static**.


Methods
-------


### getDefaultTests

    array ConfigurationTestCore::getDefaultTests()

getDefaultTests return an array of tests to executes.

key are method name, value are parameters (false for no parameter)
all path are _PS_ROOT_DIR_ related

* Visibility: **public**
* This method is **static**.




### getDefaultTestsOp

    array ConfigurationTestCore::getDefaultTestsOp()

getDefaultTestsOp return an array of tests to executes.

key are method name, value are parameters (false for no parameter)

* Visibility: **public**
* This method is **static**.




### check

    array ConfigurationTestCore::check(array $tests)

run all test defined in $tests



* Visibility: **public**
* This method is **static**.


#### Arguments
* $tests **array**



### run

    mixed ConfigurationTestCore::run($ptr, $arg)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $ptr **mixed**
* $arg **mixed**



### test_phpversion

    mixed ConfigurationTestCore::test_phpversion()





* Visibility: **public**
* This method is **static**.




### test_new_phpversion

    mixed ConfigurationTestCore::test_new_phpversion()





* Visibility: **public**
* This method is **static**.




### test_mysql_support

    mixed ConfigurationTestCore::test_mysql_support()





* Visibility: **public**
* This method is **static**.




### test_pdo_mysql

    mixed ConfigurationTestCore::test_pdo_mysql()





* Visibility: **public**
* This method is **static**.




### test_magicquotes

    mixed ConfigurationTestCore::test_magicquotes()





* Visibility: **public**
* This method is **static**.




### test_upload

    mixed ConfigurationTestCore::test_upload()





* Visibility: **public**
* This method is **static**.




### test_fopen

    mixed ConfigurationTestCore::test_fopen()





* Visibility: **public**
* This method is **static**.




### test_system

    mixed ConfigurationTestCore::test_system($funcs)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $funcs **mixed**



### test_gd

    mixed ConfigurationTestCore::test_gd()





* Visibility: **public**
* This method is **static**.




### test_register_globals

    mixed ConfigurationTestCore::test_register_globals()





* Visibility: **public**
* This method is **static**.




### test_gz

    mixed ConfigurationTestCore::test_gz()





* Visibility: **public**
* This method is **static**.




### test_dir

    mixed ConfigurationTestCore::test_dir($relative_dir, $recursive, $full_report)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $relative_dir **mixed**
* $recursive **mixed**
* $full_report **mixed**



### test_file

    mixed ConfigurationTestCore::test_file($file_relative)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $file_relative **mixed**



### test_config_dir

    mixed ConfigurationTestCore::test_config_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_sitemap

    mixed ConfigurationTestCore::test_sitemap($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_root_dir

    mixed ConfigurationTestCore::test_root_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_log_dir

    mixed ConfigurationTestCore::test_log_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_admin_dir

    mixed ConfigurationTestCore::test_admin_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_img_dir

    mixed ConfigurationTestCore::test_img_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_module_dir

    mixed ConfigurationTestCore::test_module_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_cache_dir

    mixed ConfigurationTestCore::test_cache_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_tools_v2_dir

    mixed ConfigurationTestCore::test_tools_v2_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_cache_v2_dir

    mixed ConfigurationTestCore::test_cache_v2_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_download_dir

    mixed ConfigurationTestCore::test_download_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_mails_dir

    mixed ConfigurationTestCore::test_mails_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_translations_dir

    mixed ConfigurationTestCore::test_translations_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_theme_lang_dir

    mixed ConfigurationTestCore::test_theme_lang_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_theme_pdf_lang_dir

    mixed ConfigurationTestCore::test_theme_pdf_lang_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_theme_cache_dir

    mixed ConfigurationTestCore::test_theme_cache_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_customizable_products_dir

    mixed ConfigurationTestCore::test_customizable_products_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_virtual_products_dir

    mixed ConfigurationTestCore::test_virtual_products_dir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### test_mbstring

    mixed ConfigurationTestCore::test_mbstring()





* Visibility: **public**
* This method is **static**.




### test_mcrypt

    mixed ConfigurationTestCore::test_mcrypt()





* Visibility: **public**
* This method is **static**.




### test_sessions

    mixed ConfigurationTestCore::test_sessions()





* Visibility: **public**
* This method is **static**.




### test_dom

    mixed ConfigurationTestCore::test_dom()





* Visibility: **public**
* This method is **static**.




### test_files

    mixed ConfigurationTestCore::test_files($full)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $full **mixed**


