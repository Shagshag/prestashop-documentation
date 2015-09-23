Class TranslateCore
=====================





* Class name: TranslateCore
* Source: [classes/Translate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L30)


Contents
--------



### Methods

* [checkAndReplaceArgs](#method-checkAndReplaceArgs)
* [getAdminTranslation](#method-getAdminTranslation)
* [getGenericAdminTranslation](#method-getGenericAdminTranslation)
* [getModuleTranslation](#method-getModuleTranslation)
* [getPdfTranslation](#method-getPdfTranslation)
* [postProcessTranslation](#method-postProcessTranslation)
* [ppTags](#method-ppTags)
* [smartyPostProcessTranslation](#method-smartyPostProcessTranslation)






Methods
-------


### <a name="method-checkAndReplaceArgs"></a>checkAndReplaceArgs

```php
string TranslateCore::checkAndReplaceArgs($string, $args)
```

Check if string use a specif syntax for sprintf and replace arguments if use it



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L248)


#### Arguments
* $string **mixed**
* $args **mixed**



### <a name="method-getAdminTranslation"></a>getAdminTranslation

```php
string TranslateCore::getAdminTranslation($string, string $class, boolean $addslashes, boolean $htmlentities, $sprintf)
```

Get a translation for an admin controller



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L41)


#### Arguments
* $string **mixed**
* $class **string**
* $addslashes **boolean**
* $htmlentities **boolean**
* $sprintf **mixed**



### <a name="method-getGenericAdminTranslation"></a>getGenericAdminTranslation

```php
string TranslateCore::getGenericAdminTranslation($string, null $key, $lang_array)
```

Return the translation for a string if it exists for the base AdminController or for helpers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L94)


#### Arguments
* $string **mixed** - string to translate
* $key **null** - md5 key if already calculated (optional)
* $lang_array **mixed** - global array of admin translations



### <a name="method-getModuleTranslation"></a>getModuleTranslation

```php
string TranslateCore::getModuleTranslation(string|\Module $module, string $string, string $source, $sprintf, $js)
```

Get a translation for a module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L121)


#### Arguments
* $module **string|[string](class.ModuleCore.md)**
* $string **string**
* $source **string**
* $sprintf **mixed**
* $js **mixed**



### <a name="method-getPdfTranslation"></a>getPdfTranslation

```php
string TranslateCore::getPdfTranslation(string $string)
```

Get a translation for a PDF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L213)


#### Arguments
* $string **string**



### <a name="method-postProcessTranslation"></a>postProcessTranslation

```php
mixed TranslateCore::postProcessTranslation($string, $params)
```

Perform operations on translations after everything is escaped and before displaying it



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L263)


#### Arguments
* $string **mixed**
* $params **mixed**



### <a name="method-ppTags"></a>ppTags

```php
mixed TranslateCore::ppTags($string, $tags)
```

Helper function to make calls to postProcessTranslation more readable.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L301)


#### Arguments
* $string **mixed**
* $tags **mixed**



### <a name="method-smartyPostProcessTranslation"></a>smartyPostProcessTranslation

```php
mixed TranslateCore::smartyPostProcessTranslation($string, $params)
```

Compatibility method that just calls postProcessTranslation.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Translate.php#L293)


#### Arguments
* $string **mixed**
* $params **mixed**


