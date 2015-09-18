TranslateCore
===============






* Class name: TranslateCore
* Namespace: 







Methods
-------


### getAdminTranslation

    string TranslateCore::getAdminTranslation($string, string $class, boolean $addslashes, boolean $htmlentities, $sprintf)

Get a translation for an admin controller



* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $string **mixed** - &lt;p&gt;string to translate&lt;/p&gt;
* $key **null** - &lt;p&gt;md5 key if already calculated (optional)&lt;/p&gt;
* $lang_array **array** - &lt;p&gt;Global array of admin translations&lt;/p&gt;



### getModuleTranslation

    string TranslateCore::getModuleTranslation(string|\Module $module, string $string, string $source, $sprintf, $js)

Get a translation for a module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module **string|Module**
* $string **string**
* $source **string**
* $sprintf **mixed**
* $js **mixed**



### getPdfTranslation

    string TranslateCore::getPdfTranslation(string $string, $sprintf)

Get a translation for a PDF



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **string**
* $sprintf **mixed**



### checkAndReplaceArgs

    string TranslateCore::checkAndReplaceArgs($string, $args)

Check if string use a specif syntax for sprintf and replace arguments if use it



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**
* $args **mixed**



### postProcessTranslation

    mixed TranslateCore::postProcessTranslation($string, $params)

Perform operations on translations after everything is escaped and before displaying it



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**
* $params **mixed**



### smartyPostProcessTranslation

    mixed TranslateCore::smartyPostProcessTranslation($string, $params)

Compatibility method that just calls postProcessTranslation.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**
* $params **mixed**



### ppTags

    mixed TranslateCore::ppTags($string, $tags)

Helper function to make calls to postProcessTranslation more readable.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**
* $tags **mixed**


