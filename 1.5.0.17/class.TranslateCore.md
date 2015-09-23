Class TranslateCore
=====================





* Class name: TranslateCore
* Source: [classes/Translate.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Translate.php#L31)


Contents
--------



### Methods

* [checkAndReplaceArgs](#method-checkAndReplaceArgs)
* [getAdminTranslation](#method-getAdminTranslation)
* [getGenericAdminTranslation](#method-getGenericAdminTranslation)
* [getModuleTranslation](#method-getModuleTranslation)
* [getPdfTranslation](#method-getPdfTranslation)






Methods
-------


### <a name="method-checkAndReplaceArgs"></a>checkAndReplaceArgs

```php
string TranslateCore::checkAndReplaceArgs($string, $args)
```

Check if string use a specif syntax for sprintf and replace arguments if use it



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Translate.php#L226)


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
* Source: [classes/Translate.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Translate.php#L42)


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
* Source: [classes/Translate.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Translate.php#L94)


#### Arguments
* $string **mixed** - string to translate
* $key **null** - md5 key if already calculated (optional)
* $lang_array **mixed** - global array of admin translations



### <a name="method-getModuleTranslation"></a>getModuleTranslation

```php
string TranslateCore::getModuleTranslation(string|\Module $module, string $string, string $source, $sprintf)
```

Get a translation for a module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Translate.php#L120)


#### Arguments
* $module **string|[string](class.ModuleCore.md)**
* $string **string**
* $source **string**
* $sprintf **mixed**



### <a name="method-getPdfTranslation"></a>getPdfTranslation

```php
string TranslateCore::getPdfTranslation(string $string)
```

Get a translation for a PDF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/Translate.php#L192)


#### Arguments
* $string **string**


