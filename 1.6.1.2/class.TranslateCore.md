Class TranslateCore
=====================





* Class name: TranslateCore
* Source: [classes/Translate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L30)


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
* Source: [classes/Translate.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L264)


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
* Source: [classes/Translate.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L41)


#### Arguments
* $string **mixed**
* $class **string**
* $addslashes **boolean**
* $htmlentities **boolean**
* $sprintf **mixed**



### <a name="method-getGenericAdminTranslation"></a>getGenericAdminTranslation

```php
string TranslateCore::getGenericAdminTranslation($string, null $key, array $lang_array)
```

Return the translation for a string if it exists for the base AdminController or for helpers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L98)


#### Arguments
* $string **mixed** - string to translate
* $key **null** - md5 key if already calculated (optional)
* $lang_array **array** - Global array of admin translations



### <a name="method-getModuleTranslation"></a>getModuleTranslation

```php
string TranslateCore::getModuleTranslation(string|\Module $module, string $string, string $source, $sprintf, $js)
```

Get a translation for a module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L127)


#### Arguments
* $module **string|[string](class.ModuleCore.md)**
* $string **string**
* $source **string**
* $sprintf **mixed**
* $js **mixed**



### <a name="method-getPdfTranslation"></a>getPdfTranslation

```php
string TranslateCore::getPdfTranslation(string $string, $sprintf)
```

Get a translation for a PDF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L221)


#### Arguments
* $string **string**
* $sprintf **mixed**



### <a name="method-postProcessTranslation"></a>postProcessTranslation

```php
mixed TranslateCore::postProcessTranslation($string, $params)
```

Perform operations on translations after everything is escaped and before displaying it



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L279)


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
* Source: [classes/Translate.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L314)


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
* Source: [classes/Translate.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Translate.php#L306)


#### Arguments
* $string **mixed**
* $params **mixed**


