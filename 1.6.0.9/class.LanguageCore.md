Class LanguageCore
=====================





* Class name: LanguageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Language.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L27)


Contents
--------


### Properties

* [$_LANGUAGES](#property-$_LANGUAGES)
* [$_cache_language_installation](#property-$_cache_language_installation)
* [$_checkedLangs](#property-$_checkedLangs)
* [$active](#property-$active)
* [$countActiveLanguages](#property-$countActiveLanguages)
* [$date_format_full](#property-$date_format_full)
* [$date_format_lite](#property-$date_format_lite)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$is_rtl](#property-$is_rtl)
* [$iso_code](#property-$iso_code)
* [$language_code](#property-$language_code)
* [$name](#property-$name)
* [$translationsFilesAndVars](#property-$translationsFilesAndVars)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [_copyNoneFlag](#method-_copyNoneFlag)
* [_generateFiles](#method-_generateFiles)
* [_getThemesList](#method-_getThemesList)
* [add](#method-add)
* [checkAndAddLanguage](#method-checkAndAddLanguage)
* [checkFiles](#method-checkFiles)
* [checkFilesWithIsoCode](#method-checkFilesWithIsoCode)
* [copyLanguageData](#method-copyLanguageData)
* [countActiveLanguages](#method-countActiveLanguages)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [downloadAndInstallLanguagePack](#method-downloadAndInstallLanguagePack)
* [getFields](#method-getFields)
* [getFilesList](#method-getFilesList)
* [getIdByIso](#method-getIdByIso)
* [getIsoById](#method-getIsoById)
* [getIsoIds](#method-getIsoIds)
* [getLanguage](#method-getLanguage)
* [getLanguageByIETFCode](#method-getLanguageByIETFCode)
* [getLanguageCodeByIso](#method-getLanguageCodeByIso)
* [getLanguagePackListContent](#method-getLanguagePackListContent)
* [getLanguages](#method-getLanguages)
* [isInstalled](#method-isInstalled)
* [isMultiLanguageActivated](#method-isMultiLanguageActivated)
* [loadLanguages](#method-loadLanguages)
* [loadUpdateSQL](#method-loadUpdateSQL)
* [moveToIso](#method-moveToIso)
* [recurseDeleteDir](#method-recurseDeleteDir)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateModulesTranslations](#method-updateModulesTranslations)




Properties
----------


### <a name="property-$_LANGUAGES"></a>$_LANGUAGES

```php
protected mixed $_LANGUAGES
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L72).


### <a name="property-$_cache_language_installation"></a>$_cache_language_installation

```php
protected mixed $_cache_language_installation = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L796).


### <a name="property-$_checkedLangs"></a>$_checkedLangs

```php
protected array $_checkedLangs
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L71).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Language.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L50).


### <a name="property-$countActiveLanguages"></a>$countActiveLanguages

```php
protected mixed $countActiveLanguages = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L73).


### <a name="property-$date_format_full"></a>$date_format_full

```php
public string $date_format_full = 'Y-m-d H:i:s'
```





* Visibility: **public**
* Source: [classes/Language.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L44).


### <a name="property-$date_format_lite"></a>$date_format_lite

```php
public string $date_format_lite = 'Y-m-d'
```





* Visibility: **public**
* Source: [classes/Language.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L41).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'lang', 'primary' => 'id_lang', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 2), 'language_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageCode', 'size' => 5), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_rtl' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_format_lite' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32), 'date_format_full' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Language.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L55).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Language.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L29).


### <a name="property-$is_rtl"></a>$is_rtl

```php
public boolean $is_rtl = false
```





* Visibility: **public**
* Source: [classes/Language.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L47).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/Language.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L35).


### <a name="property-$language_code"></a>$language_code

```php
public string $language_code
```





* Visibility: **public**
* Source: [classes/Language.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L38).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Language.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L32).


### <a name="property-$translationsFilesAndVars"></a>$translationsFilesAndVars

```php
protected mixed $translationsFilesAndVars = array('fields' => '_FIELDS', 'errors' => '_ERRORS', 'admin' => '_LANGADM', 'pdf' => '_LANGPDF', 'tabs' => 'tabs')
```





* Visibility: **protected**
* Source: [classes/Language.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L80).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'language', 'objectsNodeName' => 'languages')
```





* Visibility: **protected**
* Source: [classes/Language.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L75).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed LanguageCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Language.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L88)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-_copyNoneFlag"></a>_copyNoneFlag

```php
mixed LanguageCore::_copyNoneFlag($id)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Language.php line 791](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L791)


#### Arguments
* $id **mixed**



### <a name="method-_generateFiles"></a>_generateFiles

```php
mixed LanguageCore::_generateFiles($newIso)
```

Generate translations files



* Visibility: **protected**
* Source: [classes/Language.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L110)


#### Arguments
* $newIso **mixed**



### <a name="method-_getThemesList"></a>_getThemesList

```php
\array([theme LanguageCore::_getThemesList()
```

Return an array of theme



* Visibility: **protected**
* Source: [classes/Language.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L184)




### <a name="method-add"></a>add

```php
mixed LanguageCore::add($autodate, $nullValues, $only_add)
```





* Visibility: **public**
* Source: [classes/Language.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L199)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $only_add **mixed**



### <a name="method-checkAndAddLanguage"></a>checkAndAddLanguage

```php
mixed LanguageCore::checkAndAddLanguage($iso_code, $lang_pack, $only_add, $params_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 729](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L729)


#### Arguments
* $iso_code **mixed**
* $lang_pack **mixed**
* $only_add **mixed**
* $params_lang **mixed**



### <a name="method-checkFiles"></a>checkFiles

```php
mixed LanguageCore::checkFiles()
```





* Visibility: **public**
* Source: [classes/Language.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L224)




### <a name="method-checkFilesWithIsoCode"></a>checkFilesWithIsoCode

```php
mixed LanguageCore::checkFilesWithIsoCode(mixed $iso_code)
```

This functions checks if every files exists for the language $iso_code.

Concerned files are those located in translations/$iso_code/
and translations/mails/$iso_code .

* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L238)


#### Arguments
* $iso_code **mixed**



### <a name="method-copyLanguageData"></a>copyLanguageData

```php
mixed LanguageCore::copyLanguageData($from, $to)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L676)


#### Arguments
* $from **mixed**
* $to **mixed**



### <a name="method-countActiveLanguages"></a>countActiveLanguages

```php
mixed LanguageCore::countActiveLanguages($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L809)


#### Arguments
* $id_shop **mixed**



### <a name="method-delete"></a>delete

```php
mixed LanguageCore::delete()
```





* Visibility: **public**
* Source: [classes/Language.php line 484](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L484)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed LanguageCore::deleteSelection($selection)
```





* Visibility: **public**
* Source: [classes/Language.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L557)


#### Arguments
* $selection **mixed**



### <a name="method-downloadAndInstallLanguagePack"></a>downloadAndInstallLanguagePack

```php
mixed LanguageCore::downloadAndInstallLanguagePack($iso, $version, $params, $install)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L823)


#### Arguments
* $iso **mixed**
* $version **mixed**
* $params **mixed**
* $install **mixed**



### <a name="method-getFields"></a>getFields

```php
array LanguageCore::getFields()
```





* Visibility: **public**
* Source: [classes/Language.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L97)




### <a name="method-getFilesList"></a>getFilesList

```php
mixed LanguageCore::getFilesList($iso_from, $theme_from, $iso_to, $theme_to, $select, $check, $modules)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L250)


#### Arguments
* $iso_from **mixed**
* $theme_from **mixed**
* $iso_to **mixed**
* $theme_to **mixed**
* $select **mixed**
* $check **mixed**
* $modules **mixed**



### <a name="method-getIdByIso"></a>getIdByIso

```php
integer LanguageCore::getIdByIso(string $iso_code)
```

Return id from iso code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L619)


#### Arguments
* $iso_code **string** - Iso code



### <a name="method-getIsoById"></a>getIsoById

```php
string LanguageCore::getIsoById(integer $id_lang)
```

Return iso code from id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L606)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getIsoIds"></a>getIsoIds

```php
array LanguageCore::getIsoIds($active)
```

Return array (id_lang, iso_code)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L671)


#### Arguments
* $active **mixed**



### <a name="method-getLanguage"></a>getLanguage

```php
mixed LanguageCore::getLanguage($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 593](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L593)


#### Arguments
* $id_lang **mixed**



### <a name="method-getLanguageByIETFCode"></a>getLanguageByIETFCode

```php
mixed LanguageCore::getLanguageByIETFCode($code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 635](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L635)


#### Arguments
* $code **mixed**



### <a name="method-getLanguageCodeByIso"></a>getLanguageCodeByIso

```php
mixed LanguageCore::getLanguageCodeByIso($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L627)


#### Arguments
* $iso_code **mixed**



### <a name="method-getLanguagePackListContent"></a>getLanguagePackListContent

```php
mixed LanguageCore::getLanguagePackListContent($iso, $tar)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 921](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L921)


#### Arguments
* $iso **mixed**
* $tar **mixed**



### <a name="method-getLanguages"></a>getLanguages

```php
array LanguageCore::getLanguages(boolean $active, $id_shop)
```

Return available languages



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 578](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L578)


#### Arguments
* $active **boolean** - Select only active languages
* $id_shop **mixed**



### <a name="method-isInstalled"></a>isInstalled

```php
mixed LanguageCore::isInstalled($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 797](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L797)


#### Arguments
* $iso_code **mixed**



### <a name="method-isMultiLanguageActivated"></a>isMultiLanguageActivated

```php
boolean LanguageCore::isMultiLanguageActivated($id_shop)
```

Check if more on than one language is activated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 916](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L916)


#### Arguments
* $id_shop **mixed**



### <a name="method-loadLanguages"></a>loadLanguages

```php
mixed LanguageCore::loadLanguages()
```

Load all languages in memory for caching



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L704)




### <a name="method-loadUpdateSQL"></a>loadUpdateSQL

```php
boolean LanguageCore::loadUpdateSQL()
```

loadUpdateSQL will create default lang values when you create a new lang, based on default id lang



* Visibility: **public**
* Source: [classes/Language.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L397)




### <a name="method-moveToIso"></a>moveToIso

```php
mixed LanguageCore::moveToIso($newIso)
```

Move translations files after editing language iso code



* Visibility: **public**
* Source: [classes/Language.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L142)


#### Arguments
* $newIso **mixed**



### <a name="method-recurseDeleteDir"></a>recurseDeleteDir

```php
mixed LanguageCore::recurseDeleteDir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L464)


#### Arguments
* $dir **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed LanguageCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Language.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L216)




### <a name="method-update"></a>update

```php
mixed LanguageCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Language.php line 721](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L721)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateModulesTranslations"></a>updateModulesTranslations

```php
mixed LanguageCore::updateModulesTranslations(array $modules_list)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Language.php#L933)


#### Arguments
* $modules_list **array**


