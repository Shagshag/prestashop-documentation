AdminTranslationsControllerCore
===============






* Class name: AdminTranslationsControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminTranslationsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L27)



Constants
----------

* [DEFAULT_THEME_NAME](#constant-DEFAULT_THEME_NAME)
* [TEXTAREA_SIZED](#constant-TEXTAREA_SIZED)

Properties
----------

* [$link_lang_pack](#property-$link_lang_pack)
* [$total_expression](#property-$total_expression)
* [$missing_translations](#property-$missing_translations)
* [$all_iso_lang](#property-$all_iso_lang)
* [$modules_translations](#property-$modules_translations)
* [$ignore_folder](#property-$ignore_folder)
* [$translations_informations](#property-$translations_informations)
* [$languages](#property-$languages)
* [$themes](#property-$themes)
* [$theme_selected](#property-$theme_selected)
* [$type_selected](#property-$type_selected)
* [$lang_selected](#property-$lang_selected)
* [$post_limit_exceed](#property-$post_limit_exceed)

Methods
-------
* [__construct](#method-__construct)
* [setTypeSelected](#method-setTypeSelected)
* [initContent](#method-initContent)
* [initForm](#method-initForm)
* [initToolbar](#method-initToolbar)
* [initMain](#method-initMain)
* [getModuleTranslations](#method-getModuleTranslations)
* [checkDirAndCreate](#method-checkDirAndCreate)
* [writeTranslationFile](#method-writeTranslationFile)
* [submitCopyLang](#method-submitCopyLang)
* [changeModulesKeyTranslation](#method-changeModulesKeyTranslation)
* [exportTabs](#method-exportTabs)
* [submitExportLang](#method-submitExportLang)
* [checkAndAddMailsFiles](#method-checkAndAddMailsFiles)
* [checkAndAddThemesFiles](#method-checkAndAddThemesFiles)
* [addNewTabs](#method-addNewTabs)
* [checkTranslationFile](#method-checkTranslationFile)
* [submitImportLang](#method-submitImportLang)
* [filterTranslationFiles](#method-filterTranslationFiles)
* [filesListToPaths](#method-filesListToPaths)
* [submitAddLang](#method-submitAddLang)
* [findAndWriteTranslationsIntoFile](#method-findAndWriteTranslationsIntoFile)
* [clearModuleFiles](#method-clearModuleFiles)
* [findAndFillTranslations](#method-findAndFillTranslations)
* [getFileToParseByTypeTranslation](#method-getFileToParseByTypeTranslation)
* [userParseFile](#method-userParseFile)
* [getTranslationsInformations](#method-getTranslationsInformations)
* [getInformations](#method-getInformations)
* [renderKpis](#method-renderKpis)
* [postProcess](#method-postProcess)
* [redirect](#method-redirect)
* [getMailPattern](#method-getMailPattern)
* [submitTranslationsMails](#method-submitTranslationsMails)
* [fileExists](#method-fileExists)
* [displayToggleButton](#method-displayToggleButton)
* [displayLimitPostWarning](#method-displayLimitPostWarning)
* [checkIfKeyUseSprintf](#method-checkIfKeyUseSprintf)
* [initFormFront](#method-initFormFront)
* [initFormBack](#method-initFormBack)
* [getListModules](#method-getListModules)
* [initFormErrors](#method-initFormErrors)
* [initFormFields](#method-initFormFields)
* [getMailFiles](#method-getMailFiles)
* [getMailContent](#method-getMailContent)
* [displayMailContent](#method-displayMailContent)
* [displayMailBlockTxt](#method-displayMailBlockTxt)
* [displayMailBlockHtml](#method-displayMailBlockHtml)
* [displayMailEditor](#method-displayMailEditor)
* [cleanMailContent](#method-cleanMailContent)
* [getModulesHasMails](#method-getModulesHasMails)
* [getModulesHasPDF](#method-getModulesHasPDF)
* [getTinyMCEForMails](#method-getTinyMCEForMails)
* [initFormMails](#method-initFormMails)
* [copyMailFilesForAllLanguages](#method-copyMailFilesForAllLanguages)
* [getSubjectMail](#method-getSubjectMail)
* [getSubjectMailContent](#method-getSubjectMailContent)
* [writeSubjectTranslationFile](#method-writeSubjectTranslationFile)
* [recursiveGetModuleFiles](#method-recursiveGetModuleFiles)
* [getAllModuleFiles](#method-getAllModuleFiles)
* [initFormModules](#method-initFormModules)
* [parsePdfClass](#method-parsePdfClass)
* [initFormPDF](#method-initFormPDF)
* [listFiles](#method-listFiles)
* [theme_exists](#method-theme_exists)


Constants
----------


### <a name="constant-DEFAULT_THEME_NAME"></a>DEFAULT_THEME_NAME

    const DEFAULT_THEME_NAME = _PS_DEFAULT_THEME_NAME_



* This constant is defined in [controllers/admin/AdminTranslationsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L30)


### <a name="constant-TEXTAREA_SIZED"></a>TEXTAREA_SIZED

    const TEXTAREA_SIZED = 70



* This constant is defined in [controllers/admin/AdminTranslationsController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L31)


Properties
----------


### <a name="property-$link_lang_pack"></a>$link_lang_pack

    protected string $link_lang_pack = 'http://www.prestashop.com/download/lang_packs/get_each_language_pack.php'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L34)


### <a name="property-$total_expression"></a>$total_expression

    protected integer $total_expression





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L37)


### <a name="property-$missing_translations"></a>$missing_translations

    protected integer $missing_translations





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L40)


### <a name="property-$all_iso_lang"></a>$all_iso_lang

    protected array $all_iso_lang = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L43)


### <a name="property-$modules_translations"></a>$modules_translations

    protected array $modules_translations = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L46)


### <a name="property-$ignore_folder"></a>$ignore_folder

    protected array $ignore_folder = array('.', '..', '.svn', '.git', '.htaccess', 'index.php')





* Visibility: **protected**
* This property is **static**.
* This property is defined in [controllers/admin/AdminTranslationsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L49)


### <a name="property-$translations_informations"></a>$translations_informations

    protected array $translations_informations = array()





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L52)


### <a name="property-$languages"></a>$languages

    protected array $languages





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L55)


### <a name="property-$themes"></a>$themes

    protected array $themes





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L58)


### <a name="property-$theme_selected"></a>$theme_selected

    protected string $theme_selected





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L61)


### <a name="property-$type_selected"></a>$type_selected

    protected string $type_selected





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L64)


### <a name="property-$lang_selected"></a>$lang_selected

    protected \Language $lang_selected





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L67)


### <a name="property-$post_limit_exceed"></a>$post_limit_exceed

    protected boolean $post_limit_exceed = false





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTranslationsController.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L70)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminTranslationsControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L72)




### <a name="method-setTypeSelected"></a>setTypeSelected

    mixed AdminTranslationsControllerCore::setTypeSelected($type_selected)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L84)


#### Arguments
* $type_selected **mixed**



### <a name="method-initContent"></a>initContent

    mixed AdminTranslationsControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L93)




### <a name="method-initForm"></a>initForm

    mixed AdminTranslationsControllerCore::initForm($method_name)

This function create vars by default and call the good method for generate form



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L123)


#### Arguments
* $method_name **mixed**



### <a name="method-initToolbar"></a>initToolbar

    mixed AdminTranslationsControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L153)




### <a name="method-initMain"></a>initMain

    mixed AdminTranslationsControllerCore::initMain()

Generate the Main page



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L173)




### <a name="method-getModuleTranslations"></a>getModuleTranslations

    mixed AdminTranslationsControllerCore::getModuleTranslations()

This method merge each arrays of modules translation in the array of modules translations



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L220)




### <a name="method-checkDirAndCreate"></a>checkDirAndCreate

    boolean AdminTranslationsControllerCore::checkDirAndCreate(string $dest)

This method is only used by AdminTranslations::submitCopyLang().

It try to create folder in new theme.

When a translation file is copied for a module, its translation key is wrong.
We have to change the translation key and rewrite the file.

* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L247)


#### Arguments
* $dest **string** - &lt;p&gt;file name&lt;/p&gt;



### <a name="method-writeTranslationFile"></a>writeTranslationFile

    mixed AdminTranslationsControllerCore::writeTranslationFile(boolean $override_file)

Read the Post var and write the translation file.

This method overwrites the old translation file.

* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L274)


#### Arguments
* $override_file **boolean** - &lt;p&gt;Set true if this file is a override&lt;/p&gt;



### <a name="method-submitCopyLang"></a>submitCopyLang

    mixed AdminTranslationsControllerCore::submitCopyLang()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L351)




### <a name="method-changeModulesKeyTranslation"></a>changeModulesKeyTranslation

    boolean AdminTranslationsControllerCore::changeModulesKeyTranslation(string $path, string $theme_from, string $theme_to)

Change the key translation to according it to theme name.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L406)


#### Arguments
* $path **string**
* $theme_from **string**
* $theme_to **string**



### <a name="method-exportTabs"></a>exportTabs

    mixed AdminTranslationsControllerCore::exportTabs()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L421)




### <a name="method-submitExportLang"></a>submitExportLang

    mixed AdminTranslationsControllerCore::submitExportLang()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L478)




### <a name="method-checkAndAddMailsFiles"></a>checkAndAddMailsFiles

    mixed AdminTranslationsControllerCore::checkAndAddMailsFiles($iso_code, $files_list)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminTranslationsController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L506)


#### Arguments
* $iso_code **mixed**
* $files_list **mixed**



### <a name="method-checkAndAddThemesFiles"></a>checkAndAddThemesFiles

    mixed AdminTranslationsControllerCore::checkAndAddThemesFiles(array $files, array $themes_selected)

Move theme translations in selected themes



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L594)


#### Arguments
* $files **array**
* $themes_selected **array**



### <a name="method-addNewTabs"></a>addNewTabs

    array AdminTranslationsControllerCore::addNewTabs(array $iso_code, array $files)

Add new translations tabs by code ISO



* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminTranslationsController.php line 634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L634)


#### Arguments
* $iso_code **array**
* $files **array**



### <a name="method-checkTranslationFile"></a>checkTranslationFile

    mixed AdminTranslationsControllerCore::checkTranslationFile($content)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminTranslationsController.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L676)


#### Arguments
* $content **mixed**



### <a name="method-submitImportLang"></a>submitImportLang

    mixed AdminTranslationsControllerCore::submitImportLang()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 716](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L716)




### <a name="method-filterTranslationFiles"></a>filterTranslationFiles

    array AdminTranslationsControllerCore::filterTranslationFiles(array $list)

Filter the translation files contained in a .gzip pack
and return only the ones that we want.

Right now the function only needs to check that
the modules for which we want to add translations
are present on the shop (installed or not).

* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminTranslationsController.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L816)


#### Arguments
* $list **array** - &lt;p&gt;Is the output of Archive_Tar::listContent()&lt;/p&gt;



### <a name="method-filesListToPaths"></a>filesListToPaths

    array AdminTranslationsControllerCore::filesListToPaths(array $list)

Turn the list returned by
AdminTranslationsController::filterTranslationFiles()
into a list of paths that can be passed to
Archive_Tar::extractList()



* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminTranslationsController.php line 844](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L844)


#### Arguments
* $list **array**



### <a name="method-submitAddLang"></a>submitAddLang

    mixed AdminTranslationsControllerCore::submitAddLang()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L853)




### <a name="method-findAndWriteTranslationsIntoFile"></a>findAndWriteTranslationsIntoFile

    mixed AdminTranslationsControllerCore::findAndWriteTranslationsIntoFile(string $file_name, array $files, string $theme_name, string $module_name, string|boolean $dir)

This method check each file (tpl or php file), get its sentences to translate,
compare with posted values and write in iso code translation file.



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 936](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L936)


#### Arguments
* $file_name **string**
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-clearModuleFiles"></a>clearModuleFiles

    array AdminTranslationsControllerCore::clearModuleFiles($files, string $type_clear, string $path)

Clear the list of module file by type (file or directory)



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1013](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1013)


#### Arguments
* $files **mixed** - &lt;p&gt;: list of files&lt;/p&gt;
* $type_clear **string** - &lt;p&gt;(file|directory)&lt;/p&gt;
* $path **string**



### <a name="method-findAndFillTranslations"></a>findAndFillTranslations

    mixed AdminTranslationsControllerCore::findAndFillTranslations(array $files, string $theme_name, string $module_name, string|boolean $dir)

This method get translation for each files of a module,
compare with global $_MODULES array and fill AdminTranslations::modules_translations array
With key as English sentences and values as their iso code translations.



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1044](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1044)


#### Arguments
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-getFileToParseByTypeTranslation"></a>getFileToParseByTypeTranslation

    array AdminTranslationsControllerCore::getFileToParseByTypeTranslation()

Get list of files which must be parsed by directory and by type of translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1104)




### <a name="method-userParseFile"></a>userParseFile

    array AdminTranslationsControllerCore::userParseFile($content, $type_translation, string|boolean $type_file, string $module_name)

This method parse a file by type of translation and type file



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1215)


#### Arguments
* $content **mixed**
* $type_translation **mixed** - &lt;p&gt;: front, back, errors, modules...&lt;/p&gt;
* $type_file **string|boolean** - &lt;p&gt;: (tpl|php)&lt;/p&gt;
* $module_name **string** - &lt;p&gt;: name of the module&lt;/p&gt;



### <a name="method-getTranslationsInformations"></a>getTranslationsInformations

    mixed AdminTranslationsControllerCore::getTranslationsInformations()

Get all translations informations for all type of translations

array(
	'type' => array(
		'name' => string : title for the translation type,
		'var' => string : name of var for the translation file,
		'dir' => string : dir of translation file
		'file' => string : file name of translation file
	)
)

* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1300)




### <a name="method-getInformations"></a>getInformations

    mixed AdminTranslationsControllerCore::getInformations()

Get all informations on : languages, theme and the translation type.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1357)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminTranslationsControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1408)




### <a name="method-postProcess"></a>postProcess

    mixed AdminTranslationsControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1462)




### <a name="method-redirect"></a>redirect

    mixed AdminTranslationsControllerCore::redirect(boolean $save_and_stay, boolean $conf)

This method redirect in the translation main page or in the translation page



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1558)


#### Arguments
* $save_and_stay **boolean** - &lt;p&gt;: true if the user has clicked on the button &quot;save and stay&quot;&lt;/p&gt;
* $conf **boolean** - &lt;p&gt;: id of confirmation message&lt;/p&gt;



### <a name="method-getMailPattern"></a>getMailPattern

    mixed AdminTranslationsControllerCore::getMailPattern()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1569)




### <a name="method-submitTranslationsMails"></a>submitTranslationsMails

    mixed AdminTranslationsControllerCore::submitTranslationsMails()

This method is used to write translation for mails.

This writes subject translation files
(in root/mails/lang_choosen/lang.php or root/_PS_THEMES_DIR_/mails/lang_choosen/lang.php)
and mails files.

* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1590](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1590)




### <a name="method-fileExists"></a>fileExists

    mixed AdminTranslationsControllerCore::fileExists()

Include file $dir/$file and return the var $var declared in it.

This create the file if not exists

return array : translations

* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1696)




### <a name="method-displayToggleButton"></a>displayToggleButton

    mixed AdminTranslationsControllerCore::displayToggleButton($closed)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1720](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1720)


#### Arguments
* $closed **mixed**



### <a name="method-displayLimitPostWarning"></a>displayLimitPostWarning

    mixed AdminTranslationsControllerCore::displayLimitPostWarning($count)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1737](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1737)


#### Arguments
* $count **mixed**



### <a name="method-checkIfKeyUseSprintf"></a>checkIfKeyUseSprintf

    array|boolean AdminTranslationsControllerCore::checkIfKeyUseSprintf($key)

Find sentence which use %d, %s, %%, %1$d, %1$s.

..

* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1759](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1759)


#### Arguments
* $key **mixed** - &lt;p&gt;: english sentence&lt;/p&gt;



### <a name="method-initFormFront"></a>initFormFront

    mixed AdminTranslationsControllerCore::initFormFront()

This method generate the form for front translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1770](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1770)




### <a name="method-initFormBack"></a>initFormBack

    mixed AdminTranslationsControllerCore::initFormBack()

This method generate the form for back translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 1853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1853)




### <a name="method-getListModules"></a>getListModules

    array AdminTranslationsControllerCore::getListModules()

Check if directory and file exist and return an list of modules



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2046](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2046)




### <a name="method-initFormErrors"></a>initFormErrors

    mixed AdminTranslationsControllerCore::initFormErrors()

This method generate the form for errors translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2068](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2068)




### <a name="method-initFormFields"></a>initFormFields

    mixed AdminTranslationsControllerCore::initFormFields()

This method generate the form for fields translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2131)




### <a name="method-getMailFiles"></a>getMailFiles

    array AdminTranslationsControllerCore::getMailFiles(string $dir, string $group_name)

Get each informations for each mails found in the folder $dir.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2228)


#### Arguments
* $dir **string**
* $group_name **string**



### <a name="method-getMailContent"></a>getMailContent

    array AdminTranslationsControllerCore::getMailContent(string $dir, string $file)

Get content of the mail file.



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2291)


#### Arguments
* $dir **string**
* $file **string**



### <a name="method-displayMailContent"></a>displayMailContent

    string AdminTranslationsControllerCore::displayMailContent(array $mails, array $all_subject_mail, \Language $obj_lang, string $id_html, string $title, string|boolean $name_for_module)

Display mails in html format.

This was create for factorize the html displaying

* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2315)


#### Arguments
* $mails **array**
* $all_subject_mail **array**
* $obj_lang **[Language](LanguageCore)**
* $id_html **string** - &lt;p&gt;Use for set html id attribute for the block&lt;/p&gt;
* $title **string** - &lt;p&gt;Set the title for the block&lt;/p&gt;
* $name_for_module **string|boolean** - &lt;p&gt;Is not false define add a name for distinguish mails module&lt;/p&gt;



### <a name="method-displayMailBlockTxt"></a>displayMailBlockTxt

    string AdminTranslationsControllerCore::displayMailBlockTxt(array $content, string $lang, string $mail_name, string $group_name, string|boolean $name_for_module)

Just build the html structure for display txt mails



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2432)


#### Arguments
* $content **array** - &lt;p&gt;With english and language needed contents&lt;/p&gt;
* $lang **string** - &lt;p&gt;ISO code of the needed language&lt;/p&gt;
* $mail_name **string** - &lt;p&gt;Name of the file to translate (same for txt and html files)&lt;/p&gt;
* $group_name **string** - &lt;p&gt;Group name allow to distinguish each block of mail.&lt;/p&gt;
* $name_for_module **string|boolean** - &lt;p&gt;Is not false define add a name for distinguish mails module&lt;/p&gt;



### <a name="method-displayMailBlockHtml"></a>displayMailBlockHtml

    string AdminTranslationsControllerCore::displayMailBlockHtml(array $content, string $lang, string $url, string $mail_name, string $group_name, string|boolean $name_for_module)

Just build the html structure for display html mails.



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2454](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2454)


#### Arguments
* $content **array** - &lt;p&gt;With english and language needed contents&lt;/p&gt;
* $lang **string** - &lt;p&gt;ISO code of the needed language&lt;/p&gt;
* $url **string** - &lt;p&gt;for         The html page and displaying an outline&lt;/p&gt;
* $mail_name **string** - &lt;p&gt;Name of the file to translate (same for txt and html files)&lt;/p&gt;
* $group_name **string** - &lt;p&gt;Group name allow to distinguish each block of mail.&lt;/p&gt;
* $name_for_module **string|boolean** - &lt;p&gt;Is not false define add a name for distinguish mails module&lt;/p&gt;



### <a name="method-displayMailEditor"></a>displayMailEditor

    mixed AdminTranslationsControllerCore::displayMailEditor($content, $lang, $url, $mail_name, $group_name, $name_for_module)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2473](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2473)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $url **mixed**
* $mail_name **mixed**
* $group_name **mixed**
* $name_for_module **mixed**



### <a name="method-cleanMailContent"></a>cleanMailContent

    mixed AdminTranslationsControllerCore::cleanMailContent($content, $lang, $title)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2481)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $title **mixed**



### <a name="method-getModulesHasMails"></a>getModulesHasMails

    array AdminTranslationsControllerCore::getModulesHasMails(boolean $with_module_name)

Check in each module if contains mails folder.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2507)


#### Arguments
* $with_module_name **boolean**



### <a name="method-getModulesHasPDF"></a>getModulesHasPDF

    array AdminTranslationsControllerCore::getModulesHasPDF(boolean $classes)

Check in each module if contains pdf folder.



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2540)


#### Arguments
* $classes **boolean**



### <a name="method-getTinyMCEForMails"></a>getTinyMCEForMails

    mixed AdminTranslationsControllerCore::getTinyMCEForMails($iso_lang)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2570](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2570)


#### Arguments
* $iso_lang **mixed**



### <a name="method-initFormMails"></a>initFormMails

    array|string AdminTranslationsControllerCore::initFormMails(boolean $no_display)

This method generate the form for mails translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2593](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2593)


#### Arguments
* $no_display **boolean**



### <a name="method-copyMailFilesForAllLanguages"></a>copyMailFilesForAllLanguages

    mixed AdminTranslationsControllerCore::copyMailFilesForAllLanguages()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2661)




### <a name="method-getSubjectMail"></a>getSubjectMail

    array AdminTranslationsControllerCore::getSubjectMail($dir, $file, $subject_mail)

Get list of subjects of mails



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2724](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2724)


#### Arguments
* $dir **mixed**
* $file **mixed**
* $subject_mail **mixed**



### <a name="method-getSubjectMailContent"></a>getSubjectMailContent

    array AdminTranslationsControllerCore::getSubjectMailContent($directory)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2768](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2768)


#### Arguments
* $directory **mixed** - &lt;p&gt;: name of directory&lt;/p&gt;



### <a name="method-writeSubjectTranslationFile"></a>writeSubjectTranslationFile

    mixed AdminTranslationsControllerCore::writeSubjectTranslationFile($sub, $path)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2789](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2789)


#### Arguments
* $sub **mixed**
* $path **mixed**



### <a name="method-recursiveGetModuleFiles"></a>recursiveGetModuleFiles

    mixed AdminTranslationsControllerCore::recursiveGetModuleFiles(string $path, array $array_files, string $module_name, string $lang_file, boolean $is_default)

This get files to translate in module directory.

Recursive method allow to get each files for a module no matter his depth.

* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2825](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2825)


#### Arguments
* $path **string** - &lt;p&gt;directory path to scan&lt;/p&gt;
* $array_files **array** - &lt;p&gt;by reference - array which saved files to parse.&lt;/p&gt;
* $module_name **string** - &lt;p&gt;module name&lt;/p&gt;
* $lang_file **string** - &lt;p&gt;full path of translation file&lt;/p&gt;
* $is_default **boolean**



### <a name="method-getAllModuleFiles"></a>getAllModuleFiles

    array AdminTranslationsControllerCore::getAllModuleFiles(array $modules, string|null $root_dir, string $lang, boolean $is_default)

This method get translation in each translations file.

The file depend on $lang param.

* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2864)


#### Arguments
* $modules **array** - &lt;p&gt;List of modules&lt;/p&gt;
* $root_dir **string|null** - &lt;p&gt;path where it get each modules&lt;/p&gt;
* $lang **string** - &lt;p&gt;ISO code of chosen language to translate&lt;/p&gt;
* $is_default **boolean** - &lt;p&gt;Set it if modules are located in root/prestashop/modules folder&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                           This allow to distinguish overridden prestashop theme and original module&lt;/code&gt;&lt;/pre&gt;



### <a name="method-initFormModules"></a>initFormModules

    mixed AdminTranslationsControllerCore::initFormModules()

This method generate the form for modules translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2917](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2917)




### <a name="method-parsePdfClass"></a>parsePdfClass

    array AdminTranslationsControllerCore::parsePdfClass(string $file_path, string $file_type, array $lang_array, string $tab, array $tabs_array, array $count_missing)

Parse PDF class



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2959](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2959)


#### Arguments
* $file_path **string** - &lt;p&gt;File to parse&lt;/p&gt;
* $file_type **string** - &lt;p&gt;Type of file&lt;/p&gt;
* $lang_array **array** - &lt;p&gt;Contains expression in the chosen language&lt;/p&gt;
* $tab **string** - &lt;p&gt;name      To use with the md5 key&lt;/p&gt;
* $tabs_array **array**
* $count_missing **array**



### <a name="method-initFormPDF"></a>initFormPDF

    mixed AdminTranslationsControllerCore::initFormPDF()

This method generate the form for PDF translations



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 2987](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2987)




### <a name="method-listFiles"></a>listFiles

    array AdminTranslationsControllerCore::listFiles(string $dir, array $list, string $file_ext)

Recursively list files in directory $dir



* Visibility: **public**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 3079](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L3079)


#### Arguments
* $dir **string**
* $list **array**
* $file_ext **string**



### <a name="method-theme_exists"></a>theme_exists

    boolean AdminTranslationsControllerCore::theme_exists(string $theme)

Checks if theme exists



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTranslationsController.php line 3104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L3104)


#### Arguments
* $theme **string**


