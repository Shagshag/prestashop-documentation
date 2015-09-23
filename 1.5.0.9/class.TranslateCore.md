Class TranslateCore
=====================





* Class name: TranslateCore
* Source: [classes/Translate.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Translate.php#L31)


Contents
--------



### Methods

* [getAdminTranslation](#method-getAdminTranslation)
* [getGenericAdminTranslation](#method-getGenericAdminTranslation)
* [getModuleTranslation](#method-getModuleTranslation)
* [getPdfTranslation](#method-getPdfTranslation)






Methods
-------


### <a name="method-getAdminTranslation"></a>getAdminTranslation

```php
string TranslateCore::getAdminTranslation($string, string $class, boolean $addslashes, boolean $htmlentities)
```

Get a translation for an admin controller



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Translate.php#L42)


#### Arguments
* $string **mixed**
* $class **string**
* $addslashes **boolean**
* $htmlentities **boolean**



### <a name="method-getGenericAdminTranslation"></a>getGenericAdminTranslation

```php
string TranslateCore::getGenericAdminTranslation($string, null $key, $lang_array)
```

Return the translation for a string if it exists for the base AdminController or for helpers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Translate.php#L88)


#### Arguments
* $string **mixed** - string to translate
* $key **null** - md5 key if already calculated (optional)
* $lang_array **mixed** - global array of admin translations



### <a name="method-getModuleTranslation"></a>getModuleTranslation

```php
string TranslateCore::getModuleTranslation(string|\Module $module, string $string, string $source)
```

Get a translation for a module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Translate.php#L114)


#### Arguments
* $module **string|[string](class.ModuleCore.md)**
* $string **string**
* $source **string**



### <a name="method-getPdfTranslation"></a>getPdfTranslation

```php
string TranslateCore::getPdfTranslation(string $string)
```

Get a translation for a PDF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Translate.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Translate.php#L182)


#### Arguments
* $string **string**


