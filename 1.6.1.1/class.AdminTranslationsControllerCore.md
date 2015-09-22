Class AdminTranslationsControllerCore
=====================





* Class name: AdminTranslationsControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminTranslationsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L27)

Constants
----------

* [DEFAULT_THEME_NAME](#constant-DEFAULT_THEME_NAME)
* [TEXTAREA_SIZED](#constant-TEXTAREA_SIZED)

Properties
----------

* [$all_iso_lang](#property-$all_iso_lang)
* [$ignore_folder](#property-$ignore_folder)
* [$lang_selected](#property-$lang_selected)
* [$languages](#property-$languages)
* [$link_lang_pack](#property-$link_lang_pack)
* [$missing_translations](#property-$missing_translations)
* [$modules_translations](#property-$modules_translations)
* [$post_limit_exceed](#property-$post_limit_exceed)
* [$theme_selected](#property-$theme_selected)
* [$themes](#property-$themes)
* [$total_expression](#property-$total_expression)
* [$translations_informations](#property-$translations_informations)
* [$type_selected](#property-$type_selected)

Methods
-------
* [__construct](#method-__construct)
* [addNewTabs](#method-addNewTabs)
* [changeModulesKeyTranslation](#method-changeModulesKeyTranslation)
* [checkAndAddMailsFiles](#method-checkAndAddMailsFiles)
* [checkAndAddThemesFiles](#method-checkAndAddThemesFiles)
* [checkDirAndCreate](#method-checkDirAndCreate)
* [checkIfKeyUseSprintf](#method-checkIfKeyUseSprintf)
* [checkTranslationFile](#method-checkTranslationFile)
* [cleanMailContent](#method-cleanMailContent)
* [clearModuleFiles](#method-clearModuleFiles)
* [copyMailFilesForAllLanguages](#method-copyMailFilesForAllLanguages)
* [displayLimitPostWarning](#method-displayLimitPostWarning)
* [displayMailBlockHtml](#method-displayMailBlockHtml)
* [displayMailBlockTxt](#method-displayMailBlockTxt)
* [displayMailContent](#method-displayMailContent)
* [displayMailEditor](#method-displayMailEditor)
* [displayToggleButton](#method-displayToggleButton)
* [exportTabs](#method-exportTabs)
* [fileExists](#method-fileExists)
* [filesListToPaths](#method-filesListToPaths)
* [filterTranslationFiles](#method-filterTranslationFiles)
* [findAndFillTranslations](#method-findAndFillTranslations)
* [findAndWriteTranslationsIntoFile](#method-findAndWriteTranslationsIntoFile)
* [getAllModuleFiles](#method-getAllModuleFiles)
* [getFileToParseByTypeTranslation](#method-getFileToParseByTypeTranslation)
* [getInformations](#method-getInformations)
* [getListModules](#method-getListModules)
* [getMailContent](#method-getMailContent)
* [getMailFiles](#method-getMailFiles)
* [getMailPattern](#method-getMailPattern)
* [getModuleTranslations](#method-getModuleTranslations)
* [getModulesHasMails](#method-getModulesHasMails)
* [getModulesHasPDF](#method-getModulesHasPDF)
* [getSubjectMail](#method-getSubjectMail)
* [getSubjectMailContent](#method-getSubjectMailContent)
* [getTinyMCEForMails](#method-getTinyMCEForMails)
* [getTranslationsInformations](#method-getTranslationsInformations)
* [initContent](#method-initContent)
* [initForm](#method-initForm)
* [initFormBack](#method-initFormBack)
* [initFormErrors](#method-initFormErrors)
* [initFormFields](#method-initFormFields)
* [initFormFront](#method-initFormFront)
* [initFormMails](#method-initFormMails)
* [initFormModules](#method-initFormModules)
* [initFormPDF](#method-initFormPDF)
* [initMain](#method-initMain)
* [initToolbar](#method-initToolbar)
* [listFiles](#method-listFiles)
* [parsePdfClass](#method-parsePdfClass)
* [postProcess](#method-postProcess)
* [recursiveGetModuleFiles](#method-recursiveGetModuleFiles)
* [redirect](#method-redirect)
* [renderKpis](#method-renderKpis)
* [setTypeSelected](#method-setTypeSelected)
* [submitAddLang](#method-submitAddLang)
* [submitCopyLang](#method-submitCopyLang)
* [submitExportLang](#method-submitExportLang)
* [submitImportLang](#method-submitImportLang)
* [submitTranslationsMails](#method-submitTranslationsMails)
* [theme_exists](#method-theme_exists)
* [userParseFile](#method-userParseFile)
* [writeSubjectTranslationFile](#method-writeSubjectTranslationFile)
* [writeTranslationFile](#method-writeTranslationFile)


Constants
----------


### <a name="constant-DEFAULT_THEME_NAME"></a>DEFAULT_THEME_NAME

    const DEFAULT_THEME_NAME = _PS_DEFAULT_THEME_NAME_



* Source: [controllers/admin/AdminTranslationsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L30)


### <a name="constant-TEXTAREA_SIZED"></a>TEXTAREA_SIZED

    const TEXTAREA_SIZED = 70



* Source: [controllers/admin/AdminTranslationsController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L31)


Properties
----------


### <a name="property-$all_iso_lang"></a>$all_iso_lang

    protected array $all_iso_lang = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L43)


### <a name="property-$ignore_folder"></a>$ignore_folder

    protected array $ignore_folder = array('.', '..', '.svn', '.git', '.htaccess', 'index.php')





* Visibility: **protected**
* This property is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L49)


### <a name="property-$lang_selected"></a>$lang_selected

    protected \Language $lang_selected





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L67)


### <a name="property-$languages"></a>$languages

    protected array $languages





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L55)


### <a name="property-$link_lang_pack"></a>$link_lang_pack

    protected string $link_lang_pack = 'http://www.prestashop.com/download/lang_packs/get_each_language_pack.php'





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L34)


### <a name="property-$missing_translations"></a>$missing_translations

    protected integer $missing_translations





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L40)


### <a name="property-$modules_translations"></a>$modules_translations

    protected array $modules_translations = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L46)


### <a name="property-$post_limit_exceed"></a>$post_limit_exceed

    protected boolean $post_limit_exceed = false





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L70)


### <a name="property-$theme_selected"></a>$theme_selected

    protected string $theme_selected





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L61)


### <a name="property-$themes"></a>$themes

    protected array $themes





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L58)


### <a name="property-$total_expression"></a>$total_expression

    protected integer $total_expression





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L37)


### <a name="property-$translations_informations"></a>$translations_informations

    protected array $translations_informations = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L52)


### <a name="property-$type_selected"></a>$type_selected

    protected string $type_selected





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L64)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminTranslationsControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L72)




### <a name="method-addNewTabs"></a>addNewTabs

    array AdminTranslationsControllerCore::addNewTabs(array $iso_code, array $files)

Add new translations tabs by code ISO



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L634)


#### Arguments
* $iso_code **array**
* $files **array**



### <a name="method-changeModulesKeyTranslation"></a>changeModulesKeyTranslation

    boolean AdminTranslationsControllerCore::changeModulesKeyTranslation(string $path, string $theme_from, string $theme_to)

Change the key translation to according it to theme name.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L406)


#### Arguments
* $path **string**
* $theme_from **string**
* $theme_to **string**



### <a name="method-checkAndAddMailsFiles"></a>checkAndAddMailsFiles

    mixed AdminTranslationsControllerCore::checkAndAddMailsFiles($iso_code, $files_list)





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L506)


#### Arguments
* $iso_code **mixed**
* $files_list **mixed**



### <a name="method-checkAndAddThemesFiles"></a>checkAndAddThemesFiles

    mixed AdminTranslationsControllerCore::checkAndAddThemesFiles(array $files, array $themes_selected)

Move theme translations in selected themes



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L594)


#### Arguments
* $files **array**
* $themes_selected **array**



### <a name="method-checkDirAndCreate"></a>checkDirAndCreate

    boolean AdminTranslationsControllerCore::checkDirAndCreate(string $dest)

This method is only used by AdminTranslations::submitCopyLang().

It try to create folder in new theme.

When a translation file is copied for a module, its translation key is wrong.
We have to change the translation key and rewrite the file.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L247)


#### Arguments
* $dest **string** - file name



### <a name="method-checkIfKeyUseSprintf"></a>checkIfKeyUseSprintf

    array|boolean AdminTranslationsControllerCore::checkIfKeyUseSprintf($key)

Find sentence which use %d, %s, %%, %1$d, %1$s.

..

* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1759](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1759)


#### Arguments
* $key **mixed** - : english sentence



### <a name="method-checkTranslationFile"></a>checkTranslationFile

    mixed AdminTranslationsControllerCore::checkTranslationFile($content)





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L676)


#### Arguments
* $content **mixed**



### <a name="method-cleanMailContent"></a>cleanMailContent

    mixed AdminTranslationsControllerCore::cleanMailContent($content, $lang, $title)





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2481)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $title **mixed**



### <a name="method-clearModuleFiles"></a>clearModuleFiles

    array AdminTranslationsControllerCore::clearModuleFiles($files, string $type_clear, string $path)

Clear the list of module file by type (file or directory)



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1013](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1013)


#### Arguments
* $files **mixed** - : list of files
* $type_clear **string** - (file|directory)
* $path **string**



### <a name="method-copyMailFilesForAllLanguages"></a>copyMailFilesForAllLanguages

    mixed AdminTranslationsControllerCore::copyMailFilesForAllLanguages()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2661)




### <a name="method-displayLimitPostWarning"></a>displayLimitPostWarning

    mixed AdminTranslationsControllerCore::displayLimitPostWarning($count)





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1737](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1737)


#### Arguments
* $count **mixed**



### <a name="method-displayMailBlockHtml"></a>displayMailBlockHtml

    string AdminTranslationsControllerCore::displayMailBlockHtml(array $content, string $lang, string $url, string $mail_name, string $group_name, string|boolean $name_for_module)

Just build the html structure for display html mails.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2454](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2454)


#### Arguments
* $content **array** - With english and language needed contents
* $lang **string** - ISO code of the needed language
* $url **string** - for         The html page and displaying an outline
* $mail_name **string** - Name of the file to translate (same for txt and html files)
* $group_name **string** - Group name allow to distinguish each block of mail.
* $name_for_module **string|boolean** - Is not false define add a name for distinguish mails module



### <a name="method-displayMailBlockTxt"></a>displayMailBlockTxt

    string AdminTranslationsControllerCore::displayMailBlockTxt(array $content, string $lang, string $mail_name, string $group_name, string|boolean $name_for_module)

Just build the html structure for display txt mails



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2432)


#### Arguments
* $content **array** - With english and language needed contents
* $lang **string** - ISO code of the needed language
* $mail_name **string** - Name of the file to translate (same for txt and html files)
* $group_name **string** - Group name allow to distinguish each block of mail.
* $name_for_module **string|boolean** - Is not false define add a name for distinguish mails module



### <a name="method-displayMailContent"></a>displayMailContent

    string AdminTranslationsControllerCore::displayMailContent(array $mails, array $all_subject_mail, \Language $obj_lang, string $id_html, string $title, string|boolean $name_for_module)

Display mails in html format.

This was create for factorize the html displaying

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2315)


#### Arguments
* $mails **array**
* $all_subject_mail **array**
* $obj_lang **[Language](class.LanguageCore)**
* $id_html **string** - Use for set html id attribute for the block
* $title **string** - Set the title for the block
* $name_for_module **string|boolean** - Is not false define add a name for distinguish mails module



### <a name="method-displayMailEditor"></a>displayMailEditor

    mixed AdminTranslationsControllerCore::displayMailEditor($content, $lang, $url, $mail_name, $group_name, $name_for_module)





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2473](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2473)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $url **mixed**
* $mail_name **mixed**
* $group_name **mixed**
* $name_for_module **mixed**



### <a name="method-displayToggleButton"></a>displayToggleButton

    mixed AdminTranslationsControllerCore::displayToggleButton($closed)





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1720](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1720)


#### Arguments
* $closed **mixed**



### <a name="method-exportTabs"></a>exportTabs

    mixed AdminTranslationsControllerCore::exportTabs()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L421)




### <a name="method-fileExists"></a>fileExists

    mixed AdminTranslationsControllerCore::fileExists()

Include file $dir/$file and return the var $var declared in it.

This create the file if not exists

return array : translations

* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1696)




### <a name="method-filesListToPaths"></a>filesListToPaths

    array AdminTranslationsControllerCore::filesListToPaths(array $list)

Turn the list returned by
AdminTranslationsController::filterTranslationFiles()
into a list of paths that can be passed to
Archive_Tar::extractList()



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 844](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L844)


#### Arguments
* $list **array**



### <a name="method-filterTranslationFiles"></a>filterTranslationFiles

    array AdminTranslationsControllerCore::filterTranslationFiles(array $list)

Filter the translation files contained in a .gzip pack
and return only the ones that we want.

Right now the function only needs to check that
the modules for which we want to add translations
are present on the shop (installed or not).

* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L816)


#### Arguments
* $list **array** - Is the output of Archive_Tar::listContent()



### <a name="method-findAndFillTranslations"></a>findAndFillTranslations

    mixed AdminTranslationsControllerCore::findAndFillTranslations(array $files, string $theme_name, string $module_name, string|boolean $dir)

This method get translation for each files of a module,
compare with global $_MODULES array and fill AdminTranslations::modules_translations array
With key as English sentences and values as their iso code translations.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1044](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1044)


#### Arguments
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-findAndWriteTranslationsIntoFile"></a>findAndWriteTranslationsIntoFile

    mixed AdminTranslationsControllerCore::findAndWriteTranslationsIntoFile(string $file_name, array $files, string $theme_name, string $module_name, string|boolean $dir)

This method check each file (tpl or php file), get its sentences to translate,
compare with posted values and write in iso code translation file.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 936](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L936)


#### Arguments
* $file_name **string**
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-getAllModuleFiles"></a>getAllModuleFiles

    array AdminTranslationsControllerCore::getAllModuleFiles(array $modules, string|null $root_dir, string $lang, boolean $is_default)

This method get translation in each translations file.

The file depend on $lang param.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2864)


#### Arguments
* $modules **array** - List of modules
* $root_dir **string|null** - path where it get each modules
* $lang **string** - ISO code of chosen language to translate
* $is_default **boolean** - Set it if modules are located in root/prestashop/modules folder
                           This allow to distinguish overridden prestashop theme and original module



### <a name="method-getFileToParseByTypeTranslation"></a>getFileToParseByTypeTranslation

    array AdminTranslationsControllerCore::getFileToParseByTypeTranslation()

Get list of files which must be parsed by directory and by type of translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1104)




### <a name="method-getInformations"></a>getInformations

    mixed AdminTranslationsControllerCore::getInformations()

Get all informations on : languages, theme and the translation type.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1357)




### <a name="method-getListModules"></a>getListModules

    array AdminTranslationsControllerCore::getListModules()

Check if directory and file exist and return an list of modules



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2046](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2046)




### <a name="method-getMailContent"></a>getMailContent

    array AdminTranslationsControllerCore::getMailContent(string $dir, string $file)

Get content of the mail file.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2291)


#### Arguments
* $dir **string**
* $file **string**



### <a name="method-getMailFiles"></a>getMailFiles

    array AdminTranslationsControllerCore::getMailFiles(string $dir, string $group_name)

Get each informations for each mails found in the folder $dir.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2228)


#### Arguments
* $dir **string**
* $group_name **string**



### <a name="method-getMailPattern"></a>getMailPattern

    mixed AdminTranslationsControllerCore::getMailPattern()





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1569)




### <a name="method-getModuleTranslations"></a>getModuleTranslations

    mixed AdminTranslationsControllerCore::getModuleTranslations()

This method merge each arrays of modules translation in the array of modules translations



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L220)




### <a name="method-getModulesHasMails"></a>getModulesHasMails

    array AdminTranslationsControllerCore::getModulesHasMails(boolean $with_module_name)

Check in each module if contains mails folder.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2507)


#### Arguments
* $with_module_name **boolean**



### <a name="method-getModulesHasPDF"></a>getModulesHasPDF

    array AdminTranslationsControllerCore::getModulesHasPDF(boolean $classes)

Check in each module if contains pdf folder.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2540)


#### Arguments
* $classes **boolean**



### <a name="method-getSubjectMail"></a>getSubjectMail

    array AdminTranslationsControllerCore::getSubjectMail($dir, $file, $subject_mail)

Get list of subjects of mails



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2724](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2724)


#### Arguments
* $dir **mixed**
* $file **mixed**
* $subject_mail **mixed**



### <a name="method-getSubjectMailContent"></a>getSubjectMailContent

    array AdminTranslationsControllerCore::getSubjectMailContent($directory)





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2768](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2768)


#### Arguments
* $directory **mixed** - : name of directory



### <a name="method-getTinyMCEForMails"></a>getTinyMCEForMails

    mixed AdminTranslationsControllerCore::getTinyMCEForMails($iso_lang)





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2570](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2570)


#### Arguments
* $iso_lang **mixed**



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
* Source: [controllers/admin/AdminTranslationsController.php line 1300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1300)




### <a name="method-initContent"></a>initContent

    mixed AdminTranslationsControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L93)




### <a name="method-initForm"></a>initForm

    mixed AdminTranslationsControllerCore::initForm($method_name)

This function create vars by default and call the good method for generate form



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L123)


#### Arguments
* $method_name **mixed**



### <a name="method-initFormBack"></a>initFormBack

    mixed AdminTranslationsControllerCore::initFormBack()

This method generate the form for back translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1853)




### <a name="method-initFormErrors"></a>initFormErrors

    mixed AdminTranslationsControllerCore::initFormErrors()

This method generate the form for errors translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2068](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2068)




### <a name="method-initFormFields"></a>initFormFields

    mixed AdminTranslationsControllerCore::initFormFields()

This method generate the form for fields translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2131)




### <a name="method-initFormFront"></a>initFormFront

    mixed AdminTranslationsControllerCore::initFormFront()

This method generate the form for front translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1770](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1770)




### <a name="method-initFormMails"></a>initFormMails

    array|string AdminTranslationsControllerCore::initFormMails(boolean $no_display)

This method generate the form for mails translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2593](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2593)


#### Arguments
* $no_display **boolean**



### <a name="method-initFormModules"></a>initFormModules

    mixed AdminTranslationsControllerCore::initFormModules()

This method generate the form for modules translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2917](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2917)




### <a name="method-initFormPDF"></a>initFormPDF

    mixed AdminTranslationsControllerCore::initFormPDF()

This method generate the form for PDF translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2987](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2987)




### <a name="method-initMain"></a>initMain

    mixed AdminTranslationsControllerCore::initMain()

Generate the Main page



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L173)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminTranslationsControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L153)




### <a name="method-listFiles"></a>listFiles

    array AdminTranslationsControllerCore::listFiles(string $dir, array $list, string $file_ext)

Recursively list files in directory $dir



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 3079](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L3079)


#### Arguments
* $dir **string**
* $list **array**
* $file_ext **string**



### <a name="method-parsePdfClass"></a>parsePdfClass

    array AdminTranslationsControllerCore::parsePdfClass(string $file_path, string $file_type, array $lang_array, string $tab, array $tabs_array, array $count_missing)

Parse PDF class



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2959](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2959)


#### Arguments
* $file_path **string** - File to parse
* $file_type **string** - Type of file
* $lang_array **array** - Contains expression in the chosen language
* $tab **string** - name      To use with the md5 key
* $tabs_array **array**
* $count_missing **array**



### <a name="method-postProcess"></a>postProcess

    mixed AdminTranslationsControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1462)




### <a name="method-recursiveGetModuleFiles"></a>recursiveGetModuleFiles

    mixed AdminTranslationsControllerCore::recursiveGetModuleFiles(string $path, array $array_files, string $module_name, string $lang_file, boolean $is_default)

This get files to translate in module directory.

Recursive method allow to get each files for a module no matter his depth.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2825](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2825)


#### Arguments
* $path **string** - directory path to scan
* $array_files **array** - by reference - array which saved files to parse.
* $module_name **string** - module name
* $lang_file **string** - full path of translation file
* $is_default **boolean**



### <a name="method-redirect"></a>redirect

    mixed AdminTranslationsControllerCore::redirect(boolean $save_and_stay, boolean $conf)

This method redirect in the translation main page or in the translation page



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1558)


#### Arguments
* $save_and_stay **boolean** - : true if the user has clicked on the button &quot;save and stay&quot;
* $conf **boolean** - : id of confirmation message



### <a name="method-renderKpis"></a>renderKpis

    mixed AdminTranslationsControllerCore::renderKpis()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1408)




### <a name="method-setTypeSelected"></a>setTypeSelected

    mixed AdminTranslationsControllerCore::setTypeSelected($type_selected)





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L84)


#### Arguments
* $type_selected **mixed**



### <a name="method-submitAddLang"></a>submitAddLang

    mixed AdminTranslationsControllerCore::submitAddLang()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L853)




### <a name="method-submitCopyLang"></a>submitCopyLang

    mixed AdminTranslationsControllerCore::submitCopyLang()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L351)




### <a name="method-submitExportLang"></a>submitExportLang

    mixed AdminTranslationsControllerCore::submitExportLang()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L478)




### <a name="method-submitImportLang"></a>submitImportLang

    mixed AdminTranslationsControllerCore::submitImportLang()





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 716](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L716)




### <a name="method-submitTranslationsMails"></a>submitTranslationsMails

    mixed AdminTranslationsControllerCore::submitTranslationsMails()

This method is used to write translation for mails.

This writes subject translation files
(in root/mails/lang_choosen/lang.php or root/_PS_THEMES_DIR_/mails/lang_choosen/lang.php)
and mails files.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1590](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1590)




### <a name="method-theme_exists"></a>theme_exists

    boolean AdminTranslationsControllerCore::theme_exists(string $theme)

Checks if theme exists



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 3104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L3104)


#### Arguments
* $theme **string**



### <a name="method-userParseFile"></a>userParseFile

    array AdminTranslationsControllerCore::userParseFile($content, $type_translation, string|boolean $type_file, string $module_name)

This method parse a file by type of translation and type file



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L1215)


#### Arguments
* $content **mixed**
* $type_translation **mixed** - : front, back, errors, modules...
* $type_file **string|boolean** - : (tpl|php)
* $module_name **string** - : name of the module



### <a name="method-writeSubjectTranslationFile"></a>writeSubjectTranslationFile

    mixed AdminTranslationsControllerCore::writeSubjectTranslationFile($sub, $path)





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2789](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L2789)


#### Arguments
* $sub **mixed**
* $path **mixed**



### <a name="method-writeTranslationFile"></a>writeTranslationFile

    mixed AdminTranslationsControllerCore::writeTranslationFile(boolean $override_file)

Read the Post var and write the translation file.

This method overwrites the old translation file.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTranslationsController.php#L274)


#### Arguments
* $override_file **boolean** - Set true if this file is a override


