Class LanguageCore
=====================





* Class name: LanguageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Language.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L27)



Properties
----------

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

Methods
-------
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
* [getIDs](#method-getIDs)
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
* [updateModulesTranslations](#method-updateModulesTranslations)




Properties
----------


### <a name="property-$_LANGUAGES"></a>$_LANGUAGES

    protected mixed $_LANGUAGES





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L72).


### <a name="property-$_cache_language_installation"></a>$_cache_language_installation

    protected mixed $_cache_language_installation = null





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L870).


### <a name="property-$_checkedLangs"></a>$_checkedLangs

    protected array $_checkedLangs





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L71).


### <a name="property-$active"></a>$active

    public boolean $active = true





* Visibility: **public**
* Source: [classes/Language.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L50).


### <a name="property-$countActiveLanguages"></a>$countActiveLanguages

    protected mixed $countActiveLanguages = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L73).


### <a name="property-$date_format_full"></a>$date_format_full

    public string $date_format_full = 'Y-m-d H:i:s'





* Visibility: **public**
* Source: [classes/Language.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L44).


### <a name="property-$date_format_lite"></a>$date_format_lite

    public string $date_format_lite = 'Y-m-d'





* Visibility: **public**
* Source: [classes/Language.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L41).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'lang', 'primary' => 'id_lang', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 2), 'language_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageCode', 'size' => 5), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_rtl' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_format_lite' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32), 'date_format_full' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Language.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L55).


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* Source: [classes/Language.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L29).


### <a name="property-$is_rtl"></a>$is_rtl

    public boolean $is_rtl = false





* Visibility: **public**
* Source: [classes/Language.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L47).


### <a name="property-$iso_code"></a>$iso_code

    public string $iso_code





* Visibility: **public**
* Source: [classes/Language.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L35).


### <a name="property-$language_code"></a>$language_code

    public string $language_code





* Visibility: **public**
* Source: [classes/Language.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L38).


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Language.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L32).


### <a name="property-$translationsFilesAndVars"></a>$translationsFilesAndVars

    protected mixed $translationsFilesAndVars = array('fields' => '_FIELDS', 'errors' => '_ERRORS', 'admin' => '_LANGADM', 'pdf' => '_LANGPDF', 'tabs' => 'tabs')





* Visibility: **protected**
* Source: [classes/Language.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L80).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'language', 'objectsNodeName' => 'languages')





* Visibility: **protected**
* Source: [classes/Language.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L75).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed LanguageCore::__construct($id, $id_lang)





* Visibility: **public**
* Source: [classes/Language.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L88)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-_copyNoneFlag"></a>_copyNoneFlag

    mixed LanguageCore::_copyNoneFlag($id)





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Language.php line 865](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L865)


#### Arguments
* $id **mixed**



### <a name="method-_generateFiles"></a>_generateFiles

    mixed LanguageCore::_generateFiles($newIso)

Generate translations files



* Visibility: **protected**
* Source: [classes/Language.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L111)


#### Arguments
* $newIso **mixed**



### <a name="method-_getThemesList"></a>_getThemesList

    \array([theme LanguageCore::_getThemesList()

Return an array of theme



* Visibility: **protected**
* Source: [classes/Language.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L194)




### <a name="method-add"></a>add

    mixed LanguageCore::add($autodate, $nullValues, $only_add)





* Visibility: **public**
* Source: [classes/Language.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L210)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $only_add **mixed**



### <a name="method-checkAndAddLanguage"></a>checkAndAddLanguage

    mixed LanguageCore::checkAndAddLanguage($iso_code, $lang_pack, $only_add, $params_lang)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 786](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L786)


#### Arguments
* $iso_code **mixed**
* $lang_pack **mixed**
* $only_add **mixed**
* $params_lang **mixed**



### <a name="method-checkFiles"></a>checkFiles

    mixed LanguageCore::checkFiles()





* Visibility: **public**
* Source: [classes/Language.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L229)




### <a name="method-checkFilesWithIsoCode"></a>checkFilesWithIsoCode

    mixed LanguageCore::checkFilesWithIsoCode(mixed $iso_code)

This functions checks if every files exists for the language $iso_code.

Concerned files are those located in translations/$iso_code/
and translations/mails/$iso_code .

* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L243)


#### Arguments
* $iso_code **mixed**



### <a name="method-copyLanguageData"></a>copyLanguageData

    mixed LanguageCore::copyLanguageData($from, $to)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L740)


#### Arguments
* $from **mixed**
* $to **mixed**



### <a name="method-countActiveLanguages"></a>countActiveLanguages

    mixed LanguageCore::countActiveLanguages($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L883)


#### Arguments
* $id_shop **mixed**



### <a name="method-delete"></a>delete

    mixed LanguageCore::delete()





* Visibility: **public**
* Source: [classes/Language.php line 505](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L505)




### <a name="method-deleteSelection"></a>deleteSelection

    mixed LanguageCore::deleteSelection($selection)





* Visibility: **public**
* Source: [classes/Language.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L588)


#### Arguments
* $selection **mixed**



### <a name="method-downloadAndInstallLanguagePack"></a>downloadAndInstallLanguagePack

    mixed LanguageCore::downloadAndInstallLanguagePack($iso, $version, $params, $install)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L899)


#### Arguments
* $iso **mixed**
* $version **mixed**
* $params **mixed**
* $install **mixed**



### <a name="method-getFields"></a>getFields

    array LanguageCore::getFields()





* Visibility: **public**
* Source: [classes/Language.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L97)




### <a name="method-getFilesList"></a>getFilesList

    mixed LanguageCore::getFilesList($iso_from, $theme_from, $iso_to, $theme_to, $select, $check, $modules)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L258)


#### Arguments
* $iso_from **mixed**
* $theme_from **mixed**
* $iso_to **mixed**
* $theme_to **mixed**
* $select **mixed**
* $check **mixed**
* $modules **mixed**



### <a name="method-getIDs"></a>getIDs

    array LanguageCore::getIDs(boolean $active, integer|boolean $id_shop)

Returns an array of language IDs



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L638)


#### Arguments
* $active **boolean** - Select only active languages
* $id_shop **integer|boolean** - Shop ID



### <a name="method-getIdByIso"></a>getIdByIso

    false|null|string LanguageCore::getIdByIso(string $iso_code, boolean $no_cache)

Return id from iso code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L672)


#### Arguments
* $iso_code **string** - Iso code
* $no_cache **boolean**



### <a name="method-getIsoById"></a>getIsoById

    string LanguageCore::getIsoById(integer $id_lang)

Return iso code from id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L657)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getIsoIds"></a>getIsoIds

    array LanguageCore::getIsoIds($active)

Return array (id_lang, iso_code)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L735)


#### Arguments
* $active **mixed**



### <a name="method-getLanguage"></a>getLanguage

    mixed LanguageCore::getLanguage($id_lang)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L643)


#### Arguments
* $id_lang **mixed**



### <a name="method-getLanguageByIETFCode"></a>getLanguageByIETFCode

    mixed LanguageCore::getLanguageByIETFCode($code)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L697)


#### Arguments
* $code **mixed**



### <a name="method-getLanguageCodeByIso"></a>getLanguageCodeByIso

    mixed LanguageCore::getLanguageCodeByIso($iso_code)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L688)


#### Arguments
* $iso_code **mixed**



### <a name="method-getLanguagePackListContent"></a>getLanguagePackListContent

    mixed LanguageCore::getLanguagePackListContent($iso, $tar)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 994](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L994)


#### Arguments
* $iso **mixed**
* $tar **mixed**



### <a name="method-getLanguages"></a>getLanguages

    array LanguageCore::getLanguages(boolean $active, integer|boolean $id_shop, boolean $ids_only)

Returns available languages



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 612](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L612)


#### Arguments
* $active **boolean** - Select only active languages
* $id_shop **integer|boolean** - Shop ID
* $ids_only **boolean** - If true, returns an array of language IDs



### <a name="method-isInstalled"></a>isInstalled

    mixed LanguageCore::isInstalled($iso_code)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 871](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L871)


#### Arguments
* $iso_code **mixed**



### <a name="method-isMultiLanguageActivated"></a>isMultiLanguageActivated

    boolean LanguageCore::isMultiLanguageActivated($id_shop)

Check if more on than one language is activated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 989](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L989)


#### Arguments
* $id_shop **mixed**



### <a name="method-loadLanguages"></a>loadLanguages

    mixed LanguageCore::loadLanguages()

Load all languages in memory for caching



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L769)




### <a name="method-loadUpdateSQL"></a>loadUpdateSQL

    boolean LanguageCore::loadUpdateSQL()

loadUpdateSQL will create default lang values when you create a new lang, based on default id lang



* Visibility: **public**
* Source: [classes/Language.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L414)




### <a name="method-moveToIso"></a>moveToIso

    mixed LanguageCore::moveToIso($newIso)

Move translations files after editing language iso code



* Visibility: **public**
* Source: [classes/Language.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L144)


#### Arguments
* $newIso **mixed**



### <a name="method-recurseDeleteDir"></a>recurseDeleteDir

    mixed LanguageCore::recurseDeleteDir($dir)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L483)


#### Arguments
* $dir **mixed**



### <a name="method-updateModulesTranslations"></a>updateModulesTranslations

    mixed LanguageCore::updateModulesTranslations(array $modules_list)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 1008](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#L1008)


#### Arguments
* $modules_list **array**


