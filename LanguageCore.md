LanguageCore
===============






* Class name: LanguageCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $iso_code

    public string $iso_code





* Visibility: **public**


### $language_code

    public string $language_code





* Visibility: **public**


### $date_format_lite

    public string $date_format_lite = 'Y-m-d'





* Visibility: **public**


### $date_format_full

    public string $date_format_full = 'Y-m-d H:i:s'





* Visibility: **public**


### $is_rtl

    public boolean $is_rtl = false





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'lang', 'primary' => 'id_lang', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 2), 'language_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageCode', 'size' => 5), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_rtl' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_format_lite' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32), 'date_format_full' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.


### $_checkedLangs

    protected array $_checkedLangs





* Visibility: **protected**
* This property is **static**.


### $_LANGUAGES

    protected mixed $_LANGUAGES





* Visibility: **protected**
* This property is **static**.


### $countActiveLanguages

    protected mixed $countActiveLanguages = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'language', 'objectsNodeName' => 'languages')





* Visibility: **protected**


### $translationsFilesAndVars

    protected mixed $translationsFilesAndVars = array('fields' => '_FIELDS', 'errors' => '_ERRORS', 'admin' => '_LANGADM', 'pdf' => '_LANGPDF', 'tabs' => 'tabs')





* Visibility: **protected**


### $_cache_language_installation

    protected mixed $_cache_language_installation = null





* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed LanguageCore::__construct($id, $id_lang)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### getFields

    array LanguageCore::getFields()





* Visibility: **public**




### _generateFiles

    mixed LanguageCore::_generateFiles($newIso)

Generate translations files



* Visibility: **protected**


#### Arguments
* $newIso **mixed**



### moveToIso

    mixed LanguageCore::moveToIso($newIso)

Move translations files after editing language iso code



* Visibility: **public**


#### Arguments
* $newIso **mixed**



### _getThemesList

    \array([theme LanguageCore::_getThemesList()

Return an array of theme



* Visibility: **protected**




### add

    mixed LanguageCore::add($autodate, $nullValues, $only_add)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $only_add **mixed**



### checkFiles

    mixed LanguageCore::checkFiles()





* Visibility: **public**




### checkFilesWithIsoCode

    mixed LanguageCore::checkFilesWithIsoCode(mixed $iso_code)

This functions checks if every files exists for the language $iso_code.

Concerned files are those located in translations/$iso_code/
and translations/mails/$iso_code .

* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **mixed**



### getFilesList

    mixed LanguageCore::getFilesList($iso_from, $theme_from, $iso_to, $theme_to, $select, $check, $modules)





* Visibility: **public**
* This method is **static**.


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




### recurseDeleteDir

    mixed LanguageCore::recurseDeleteDir($dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **mixed**



### delete

    mixed LanguageCore::delete()





* Visibility: **public**




### deleteSelection

    mixed LanguageCore::deleteSelection($selection)





* Visibility: **public**


#### Arguments
* $selection **mixed**



### getLanguages

    array LanguageCore::getLanguages(boolean $active, integer|boolean $id_shop, boolean $ids_only)

Returns available languages



* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **boolean** - &lt;p&gt;Select only active languages&lt;/p&gt;
* $id_shop **integer|boolean** - &lt;p&gt;Shop ID&lt;/p&gt;
* $ids_only **boolean** - &lt;p&gt;If true, returns an array of language IDs&lt;/p&gt;



### getIDs

    array LanguageCore::getIDs(boolean $active, integer|boolean $id_shop)

Returns an array of language IDs



* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **boolean** - &lt;p&gt;Select only active languages&lt;/p&gt;
* $id_shop **integer|boolean** - &lt;p&gt;Shop ID&lt;/p&gt;



### getLanguage

    mixed LanguageCore::getLanguage($id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**



### getIsoById

    string LanguageCore::getIsoById(integer $id_lang)

Return iso code from id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### getIdByIso

    false|null|string LanguageCore::getIdByIso(string $iso_code, boolean $no_cache)

Return id from iso code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **string** - &lt;p&gt;Iso code&lt;/p&gt;
* $no_cache **boolean**



### getLanguageCodeByIso

    mixed LanguageCore::getLanguageCodeByIso($iso_code)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **mixed**



### getLanguageByIETFCode

    mixed LanguageCore::getLanguageByIETFCode($code)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $code **mixed**



### getIsoIds

    array LanguageCore::getIsoIds($active)

Return array (id_lang, iso_code)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **mixed**



### copyLanguageData

    mixed LanguageCore::copyLanguageData($from, $to)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $from **mixed**
* $to **mixed**



### loadLanguages

    mixed LanguageCore::loadLanguages()

Load all languages in memory for caching



* Visibility: **public**
* This method is **static**.




### checkAndAddLanguage

    mixed LanguageCore::checkAndAddLanguage($iso_code, $lang_pack, $only_add, $params_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **mixed**
* $lang_pack **mixed**
* $only_add **mixed**
* $params_lang **mixed**



### _copyNoneFlag

    mixed LanguageCore::_copyNoneFlag($id)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $id **mixed**



### isInstalled

    mixed LanguageCore::isInstalled($iso_code)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **mixed**



### countActiveLanguages

    mixed LanguageCore::countActiveLanguages($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**



### downloadAndInstallLanguagePack

    mixed LanguageCore::downloadAndInstallLanguagePack($iso, $version, $params, $install)





* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $id_shop **mixed**



### getLanguagePackListContent

    mixed LanguageCore::getLanguagePackListContent($iso, $tar)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso **mixed**
* $tar **mixed**



### updateModulesTranslations

    mixed LanguageCore::updateModulesTranslations(array $modules_list)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $modules_list **array**


