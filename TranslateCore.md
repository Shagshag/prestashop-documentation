TranslateCore
===============






* Class name: TranslateCore
* Namespace: 

* This class is defined in [classes/Translate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#30)







Methods
-------


### getAdminTranslation

    string TranslateCore::getAdminTranslation($string, string $class, boolean $addslashes, boolean $htmlentities, $sprintf)

Get a translation for an admin controller



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#41)


#### Arguments
* $string **mixed**
* $class **string**
* $addslashes **boolean**
* $htmlentities **boolean**
* $sprintf **mixed**



### getGenericAdminTranslation

    string TranslateCore::getGenericAdminTranslation($string, null $key, array $lang_array)

Return the translation for a string if it exists for the base AdminController or for helpers



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#98)


#### Arguments
* $string **mixed** - &lt;p&gt;string to translate&lt;/p&gt;
* $key **null** - &lt;p&gt;md5 key if already calculated (optional)&lt;/p&gt;
* $lang_array **array** - &lt;p&gt;Global array of admin translations&lt;/p&gt;



### getModuleTranslation

    string TranslateCore::getModuleTranslation(string|\Module $module, string $string, string $source, $sprintf, $js)

Get a translation for a module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#127)


#### Arguments
* $module **string|[string](ModuleCore)**
* $string **string**
* $source **string**
* $sprintf **mixed**
* $js **mixed**



### getPdfTranslation

    string TranslateCore::getPdfTranslation(string $string, $sprintf)

Get a translation for a PDF



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#221)


#### Arguments
* $string **string**
* $sprintf **mixed**



### checkAndReplaceArgs

    string TranslateCore::checkAndReplaceArgs($string, $args)

Check if string use a specif syntax for sprintf and replace arguments if use it



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#264)


#### Arguments
* $string **mixed**
* $args **mixed**



### postProcessTranslation

    mixed TranslateCore::postProcessTranslation($string, $params)

Perform operations on translations after everything is escaped and before displaying it



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#279)


#### Arguments
* $string **mixed**
* $params **mixed**



### smartyPostProcessTranslation

    mixed TranslateCore::smartyPostProcessTranslation($string, $params)

Compatibility method that just calls postProcessTranslation.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#306)


#### Arguments
* $string **mixed**
* $params **mixed**



### ppTags

    mixed TranslateCore::ppTags($string, $tags)

Helper function to make calls to postProcessTranslation more readable.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Translate.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Translate.php#314)


#### Arguments
* $string **mixed**
* $tags **mixed**


