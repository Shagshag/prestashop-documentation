LanguageCore
===============






* Class name: LanguageCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Language.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Language.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#29)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Language.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#32)


### $iso_code

    public string $iso_code





* Visibility: **public**
* This property is defined in [classes/Language.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#35)


### $language_code

    public string $language_code





* Visibility: **public**
* This property is defined in [classes/Language.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#38)


### $date_format_lite

    public string $date_format_lite = 'Y-m-d'





* Visibility: **public**
* This property is defined in [classes/Language.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#41)


### $date_format_full

    public string $date_format_full = 'Y-m-d H:i:s'





* Visibility: **public**
* This property is defined in [classes/Language.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#44)


### $is_rtl

    public boolean $is_rtl = false





* Visibility: **public**
* This property is defined in [classes/Language.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#47)


### $active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Language.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#50)


### $definition

    public mixed $definition = array('table' => 'lang', 'primary' => 'id_lang', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 2), 'language_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageCode', 'size' => 5), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_rtl' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_format_lite' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32), 'date_format_full' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Language.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#55)


### $_checkedLangs

    protected array $_checkedLangs





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Language.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#71)


### $_LANGUAGES

    protected mixed $_LANGUAGES





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Language.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#72)


### $countActiveLanguages

    protected mixed $countActiveLanguages = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Language.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#73)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'language', 'objectsNodeName' => 'languages')





* Visibility: **protected**
* This property is defined in [classes/Language.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#75)


### $translationsFilesAndVars

    protected mixed $translationsFilesAndVars = array('fields' => '_FIELDS', 'errors' => '_ERRORS', 'admin' => '_LANGADM', 'pdf' => '_LANGPDF', 'tabs' => 'tabs')





* Visibility: **protected**
* This property is defined in [classes/Language.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#80)


### $_cache_language_installation

    protected mixed $_cache_language_installation = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Language.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#870)


Methods
-------


### __construct

    mixed LanguageCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Language.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#88)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### getFields

    array LanguageCore::getFields()





* Visibility: **public**
* This method is defined in [classes/Language.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#97)




### _generateFiles

    mixed LanguageCore::_generateFiles($newIso)

Generate translations files



* Visibility: **protected**
* This method is defined in [classes/Language.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#111)


#### Arguments
* $newIso **mixed**



### moveToIso

    mixed LanguageCore::moveToIso($newIso)

Move translations files after editing language iso code



* Visibility: **public**
* This method is defined in [classes/Language.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#144)


#### Arguments
* $newIso **mixed**



### _getThemesList

    \array([theme LanguageCore::_getThemesList()

Return an array of theme



* Visibility: **protected**
* This method is defined in [classes/Language.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#194)




### add

    mixed LanguageCore::add($autodate, $nullValues, $only_add)





* Visibility: **public**
* This method is defined in [classes/Language.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#210)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $only_add **mixed**



### checkFiles

    mixed LanguageCore::checkFiles()





* Visibility: **public**
* This method is defined in [classes/Language.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#229)




### checkFilesWithIsoCode

    mixed LanguageCore::checkFilesWithIsoCode(mixed $iso_code)

This functions checks if every files exists for the language $iso_code.

Concerned files are those located in translations/$iso_code/
and translations/mails/$iso_code .

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#243)


#### Arguments
* $iso_code **mixed**



### getFilesList

    mixed LanguageCore::getFilesList($iso_from, $theme_from, $iso_to, $theme_to, $select, $check, $modules)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#258)


#### Arguments
* $iso_from **mixed**
* $theme_from **mixed**
* $iso_to **mixed**
* $theme_to **mixed**
* $select **mixed**
* $check **mixed**
* $modules **mixed**



### loadUpdateSQL

    boolean LanguageCore::loadUpdateSQL()

loadUpdateSQL will create default lang values when you create a new lang, based on default id lang



* Visibility: **public**
* This method is defined in [classes/Language.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#414)




### recurseDeleteDir

    mixed LanguageCore::recurseDeleteDir($dir)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#483)


#### Arguments
* $dir **mixed**



### delete

    mixed LanguageCore::delete()





* Visibility: **public**
* This method is defined in [classes/Language.php line 505](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#505)




### deleteSelection

    mixed LanguageCore::deleteSelection($selection)





* Visibility: **public**
* This method is defined in [classes/Language.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#588)


#### Arguments
* $selection **mixed**



### getLanguages

    array LanguageCore::getLanguages(boolean $active, integer|boolean $id_shop, boolean $ids_only)

Returns available languages



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 612](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#612)


#### Arguments
* $active **boolean** - &lt;p&gt;Select only active languages&lt;/p&gt;
* $id_shop **integer|boolean** - &lt;p&gt;Shop ID&lt;/p&gt;
* $ids_only **boolean** - &lt;p&gt;If true, returns an array of language IDs&lt;/p&gt;



### getIDs

    array LanguageCore::getIDs(boolean $active, integer|boolean $id_shop)

Returns an array of language IDs



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#638)


#### Arguments
* $active **boolean** - &lt;p&gt;Select only active languages&lt;/p&gt;
* $id_shop **integer|boolean** - &lt;p&gt;Shop ID&lt;/p&gt;



### getLanguage

    mixed LanguageCore::getLanguage($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#643)


#### Arguments
* $id_lang **mixed**



### getIsoById

    string LanguageCore::getIsoById(integer $id_lang)

Return iso code from id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#657)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### getIdByIso

    false|null|string LanguageCore::getIdByIso(string $iso_code, boolean $no_cache)

Return id from iso code



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#672)


#### Arguments
* $iso_code **string** - &lt;p&gt;Iso code&lt;/p&gt;
* $no_cache **boolean**



### getLanguageCodeByIso

    mixed LanguageCore::getLanguageCodeByIso($iso_code)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#688)


#### Arguments
* $iso_code **mixed**



### getLanguageByIETFCode

    mixed LanguageCore::getLanguageByIETFCode($code)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#697)


#### Arguments
* $code **mixed**



### getIsoIds

    array LanguageCore::getIsoIds($active)

Return array (id_lang, iso_code)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#735)


#### Arguments
* $active **mixed**



### copyLanguageData

    mixed LanguageCore::copyLanguageData($from, $to)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#740)


#### Arguments
* $from **mixed**
* $to **mixed**



### loadLanguages

    mixed LanguageCore::loadLanguages()

Load all languages in memory for caching



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#769)




### checkAndAddLanguage

    mixed LanguageCore::checkAndAddLanguage($iso_code, $lang_pack, $only_add, $params_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 786](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#786)


#### Arguments
* $iso_code **mixed**
* $lang_pack **mixed**
* $only_add **mixed**
* $params_lang **mixed**



### _copyNoneFlag

    mixed LanguageCore::_copyNoneFlag($id)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Language.php line 865](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#865)


#### Arguments
* $id **mixed**



### isInstalled

    mixed LanguageCore::isInstalled($iso_code)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 871](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#871)


#### Arguments
* $iso_code **mixed**



### countActiveLanguages

    mixed LanguageCore::countActiveLanguages($id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#883)


#### Arguments
* $id_shop **mixed**



### downloadAndInstallLanguagePack

    mixed LanguageCore::downloadAndInstallLanguagePack($iso, $version, $params, $install)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#899)


#### Arguments
* $iso **mixed**
* $version **mixed**
* $params **mixed**
* $install **mixed**



### isMultiLanguageActivated

    boolean LanguageCore::isMultiLanguageActivated($id_shop)

Check if more on than one language is activated



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 989](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#989)


#### Arguments
* $id_shop **mixed**



### getLanguagePackListContent

    mixed LanguageCore::getLanguagePackListContent($iso, $tar)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 994](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#994)


#### Arguments
* $iso **mixed**
* $tar **mixed**



### updateModulesTranslations

    mixed LanguageCore::updateModulesTranslations(array $modules_list)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Language.php line 1008](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Language.php#1008)


#### Arguments
* $modules_list **array**


