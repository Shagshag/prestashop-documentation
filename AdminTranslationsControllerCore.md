AdminTranslationsControllerCore
===============






* Class name: AdminTranslationsControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminTranslationsController.php line 27



Constants
----------


### DEFAULT_THEME_NAME

    const DEFAULT_THEME_NAME = _PS_DEFAULT_THEME_NAME_



* This constant is defined in controllers\admin\AdminTranslationsController.php line 30


### TEXTAREA_SIZED

    const TEXTAREA_SIZED = 70



* This constant is defined in controllers\admin\AdminTranslationsController.php line 31


Properties
----------


### $link_lang_pack

    protected string $link_lang_pack = 'http://www.prestashop.com/download/lang_packs/get_each_language_pack.php'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 34


### $total_expression

    protected integer $total_expression





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 37


### $missing_translations

    protected integer $missing_translations





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 40


### $all_iso_lang

    protected array $all_iso_lang = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 43


### $modules_translations

    protected array $modules_translations = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 46


### $ignore_folder

    protected array $ignore_folder = array('.', '..', '.svn', '.git', '.htaccess', 'index.php')





* Visibility: **protected**
* This property is **static**.
* This property is defined in controllers\admin\AdminTranslationsController.php line 49


### $translations_informations

    protected array $translations_informations = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 52


### $languages

    protected array $languages





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 55


### $themes

    protected array $themes





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 58


### $theme_selected

    protected string $theme_selected





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 61


### $type_selected

    protected string $type_selected





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 64


### $lang_selected

    protected \Language $lang_selected





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 67


### $post_limit_exceed

    protected boolean $post_limit_exceed = false





* Visibility: **protected**
* This property is defined in controllers\admin\AdminTranslationsController.php line 70


Methods
-------


### __construct

    mixed AdminTranslationsControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 72




### setTypeSelected

    mixed AdminTranslationsControllerCore::setTypeSelected($type_selected)





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 84


#### Arguments
* $type_selected **mixed**



### initContent

    mixed AdminTranslationsControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 93




### initForm

    mixed AdminTranslationsControllerCore::initForm($method_name)

This function create vars by default and call the good method for generate form



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 123


#### Arguments
* $method_name **mixed**



### initToolbar

    mixed AdminTranslationsControllerCore::initToolbar()

AdminController::initToolbar() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 153




### initMain

    mixed AdminTranslationsControllerCore::initMain()

Generate the Main page



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 173




### getModuleTranslations

    mixed AdminTranslationsControllerCore::getModuleTranslations()

This method merge each arrays of modules translation in the array of modules translations



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 220




### checkDirAndCreate

    boolean AdminTranslationsControllerCore::checkDirAndCreate(string $dest)

This method is only used by AdminTranslations::submitCopyLang().

It try to create folder in new theme.

When a translation file is copied for a module, its translation key is wrong.
We have to change the translation key and rewrite the file.

* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 247


#### Arguments
* $dest **string** - &lt;p&gt;file name&lt;/p&gt;



### writeTranslationFile

    mixed AdminTranslationsControllerCore::writeTranslationFile(boolean $override_file)

Read the Post var and write the translation file.

This method overwrites the old translation file.

* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 274


#### Arguments
* $override_file **boolean** - &lt;p&gt;Set true if this file is a override&lt;/p&gt;



### submitCopyLang

    mixed AdminTranslationsControllerCore::submitCopyLang()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 351




### changeModulesKeyTranslation

    boolean AdminTranslationsControllerCore::changeModulesKeyTranslation(string $path, string $theme_from, string $theme_to)

Change the key translation to according it to theme name.



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 406


#### Arguments
* $path **string**
* $theme_from **string**
* $theme_to **string**



### exportTabs

    mixed AdminTranslationsControllerCore::exportTabs()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 421




### submitExportLang

    mixed AdminTranslationsControllerCore::submitExportLang()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 478




### checkAndAddMailsFiles

    mixed AdminTranslationsControllerCore::checkAndAddMailsFiles($iso_code, $files_list)





* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminTranslationsController.php line 506


#### Arguments
* $iso_code **mixed**
* $files_list **mixed**



### checkAndAddThemesFiles

    mixed AdminTranslationsControllerCore::checkAndAddThemesFiles(array $files, array $themes_selected)

Move theme translations in selected themes



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 594


#### Arguments
* $files **array**
* $themes_selected **array**



### addNewTabs

    array AdminTranslationsControllerCore::addNewTabs(array $iso_code, array $files)

Add new translations tabs by code ISO



* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminTranslationsController.php line 634


#### Arguments
* $iso_code **array**
* $files **array**



### checkTranslationFile

    mixed AdminTranslationsControllerCore::checkTranslationFile($content)





* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminTranslationsController.php line 676


#### Arguments
* $content **mixed**



### submitImportLang

    mixed AdminTranslationsControllerCore::submitImportLang()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 716




### filterTranslationFiles

    array AdminTranslationsControllerCore::filterTranslationFiles(array $list)

Filter the translation files contained in a .gzip pack
and return only the ones that we want.

Right now the function only needs to check that
the modules for which we want to add translations
are present on the shop (installed or not).

* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminTranslationsController.php line 816


#### Arguments
* $list **array** - &lt;p&gt;Is the output of Archive_Tar::listContent()&lt;/p&gt;



### filesListToPaths

    array AdminTranslationsControllerCore::filesListToPaths(array $list)

Turn the list returned by
AdminTranslationsController::filterTranslationFiles()
into a list of paths that can be passed to
Archive_Tar::extractList()



* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminTranslationsController.php line 844


#### Arguments
* $list **array**



### submitAddLang

    mixed AdminTranslationsControllerCore::submitAddLang()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 853




### findAndWriteTranslationsIntoFile

    mixed AdminTranslationsControllerCore::findAndWriteTranslationsIntoFile(string $file_name, array $files, string $theme_name, string $module_name, string|boolean $dir)

This method check each file (tpl or php file), get its sentences to translate,
compare with posted values and write in iso code translation file.



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 936


#### Arguments
* $file_name **string**
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### clearModuleFiles

    array AdminTranslationsControllerCore::clearModuleFiles($files, string $type_clear, string $path)

Clear the list of module file by type (file or directory)



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1013


#### Arguments
* $files **mixed** - &lt;p&gt;: list of files&lt;/p&gt;
* $type_clear **string** - &lt;p&gt;(file|directory)&lt;/p&gt;
* $path **string**



### findAndFillTranslations

    mixed AdminTranslationsControllerCore::findAndFillTranslations(array $files, string $theme_name, string $module_name, string|boolean $dir)

This method get translation for each files of a module,
compare with global $_MODULES array and fill AdminTranslations::modules_translations array
With key as English sentences and values as their iso code translations.



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1044


#### Arguments
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### getFileToParseByTypeTranslation

    array AdminTranslationsControllerCore::getFileToParseByTypeTranslation()

Get list of files which must be parsed by directory and by type of translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1104




### userParseFile

    array AdminTranslationsControllerCore::userParseFile($content, $type_translation, string|boolean $type_file, string $module_name)

This method parse a file by type of translation and type file



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1215


#### Arguments
* $content **mixed**
* $type_translation **mixed** - &lt;p&gt;: front, back, errors, modules...&lt;/p&gt;
* $type_file **string|boolean** - &lt;p&gt;: (tpl|php)&lt;/p&gt;
* $module_name **string** - &lt;p&gt;: name of the module&lt;/p&gt;



### getTranslationsInformations

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
* This method is defined in controllers\admin\AdminTranslationsController.php line 1300




### getInformations

    mixed AdminTranslationsControllerCore::getInformations()

Get all informations on : languages, theme and the translation type.



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1357




### renderKpis

    mixed AdminTranslationsControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1408




### postProcess

    mixed AdminTranslationsControllerCore::postProcess()

AdminController::postProcess() override



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1462




### redirect

    mixed AdminTranslationsControllerCore::redirect(boolean $save_and_stay, boolean $conf)

This method redirect in the translation main page or in the translation page



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1558


#### Arguments
* $save_and_stay **boolean** - &lt;p&gt;: true if the user has clicked on the button &quot;save and stay&quot;&lt;/p&gt;
* $conf **boolean** - &lt;p&gt;: id of confirmation message&lt;/p&gt;



### getMailPattern

    mixed AdminTranslationsControllerCore::getMailPattern()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1569




### submitTranslationsMails

    mixed AdminTranslationsControllerCore::submitTranslationsMails()

This method is used to write translation for mails.

This writes subject translation files
(in root/mails/lang_choosen/lang.php or root/_PS_THEMES_DIR_/mails/lang_choosen/lang.php)
and mails files.

* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1590




### fileExists

    mixed AdminTranslationsControllerCore::fileExists()

Include file $dir/$file and return the var $var declared in it.

This create the file if not exists

return array : translations

* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1696




### displayToggleButton

    mixed AdminTranslationsControllerCore::displayToggleButton($closed)





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1720


#### Arguments
* $closed **mixed**



### displayLimitPostWarning

    mixed AdminTranslationsControllerCore::displayLimitPostWarning($count)





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1737


#### Arguments
* $count **mixed**



### checkIfKeyUseSprintf

    array|boolean AdminTranslationsControllerCore::checkIfKeyUseSprintf($key)

Find sentence which use %d, %s, %%, %1$d, %1$s.

..

* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1759


#### Arguments
* $key **mixed** - &lt;p&gt;: english sentence&lt;/p&gt;



### initFormFront

    mixed AdminTranslationsControllerCore::initFormFront()

This method generate the form for front translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1770




### initFormBack

    mixed AdminTranslationsControllerCore::initFormBack()

This method generate the form for back translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 1853




### getListModules

    array AdminTranslationsControllerCore::getListModules()

Check if directory and file exist and return an list of modules



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2046




### initFormErrors

    mixed AdminTranslationsControllerCore::initFormErrors()

This method generate the form for errors translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2068




### initFormFields

    mixed AdminTranslationsControllerCore::initFormFields()

This method generate the form for fields translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2131




### getMailFiles

    array AdminTranslationsControllerCore::getMailFiles(string $dir, string $group_name)

Get each informations for each mails found in the folder $dir.



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2228


#### Arguments
* $dir **string**
* $group_name **string**



### getMailContent

    array AdminTranslationsControllerCore::getMailContent(string $dir, string $file)

Get content of the mail file.



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2291


#### Arguments
* $dir **string**
* $file **string**



### displayMailContent

    string AdminTranslationsControllerCore::displayMailContent(array $mails, array $all_subject_mail, \Language $obj_lang, string $id_html, string $title, string|boolean $name_for_module)

Display mails in html format.

This was create for factorize the html displaying

* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2315


#### Arguments
* $mails **array**
* $all_subject_mail **array**
* $obj_lang **[Language](LanguageCore)**
* $id_html **string** - &lt;p&gt;Use for set html id attribute for the block&lt;/p&gt;
* $title **string** - &lt;p&gt;Set the title for the block&lt;/p&gt;
* $name_for_module **string|boolean** - &lt;p&gt;Is not false define add a name for distinguish mails module&lt;/p&gt;



### displayMailBlockTxt

    string AdminTranslationsControllerCore::displayMailBlockTxt(array $content, string $lang, string $mail_name, string $group_name, string|boolean $name_for_module)

Just build the html structure for display txt mails



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2432


#### Arguments
* $content **array** - &lt;p&gt;With english and language needed contents&lt;/p&gt;
* $lang **string** - &lt;p&gt;ISO code of the needed language&lt;/p&gt;
* $mail_name **string** - &lt;p&gt;Name of the file to translate (same for txt and html files)&lt;/p&gt;
* $group_name **string** - &lt;p&gt;Group name allow to distinguish each block of mail.&lt;/p&gt;
* $name_for_module **string|boolean** - &lt;p&gt;Is not false define add a name for distinguish mails module&lt;/p&gt;



### displayMailBlockHtml

    string AdminTranslationsControllerCore::displayMailBlockHtml(array $content, string $lang, string $url, string $mail_name, string $group_name, string|boolean $name_for_module)

Just build the html structure for display html mails.



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2454


#### Arguments
* $content **array** - &lt;p&gt;With english and language needed contents&lt;/p&gt;
* $lang **string** - &lt;p&gt;ISO code of the needed language&lt;/p&gt;
* $url **string** - &lt;p&gt;for         The html page and displaying an outline&lt;/p&gt;
* $mail_name **string** - &lt;p&gt;Name of the file to translate (same for txt and html files)&lt;/p&gt;
* $group_name **string** - &lt;p&gt;Group name allow to distinguish each block of mail.&lt;/p&gt;
* $name_for_module **string|boolean** - &lt;p&gt;Is not false define add a name for distinguish mails module&lt;/p&gt;



### displayMailEditor

    mixed AdminTranslationsControllerCore::displayMailEditor($content, $lang, $url, $mail_name, $group_name, $name_for_module)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2473


#### Arguments
* $content **mixed**
* $lang **mixed**
* $url **mixed**
* $mail_name **mixed**
* $group_name **mixed**
* $name_for_module **mixed**



### cleanMailContent

    mixed AdminTranslationsControllerCore::cleanMailContent($content, $lang, $title)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2481


#### Arguments
* $content **mixed**
* $lang **mixed**
* $title **mixed**



### getModulesHasMails

    array AdminTranslationsControllerCore::getModulesHasMails(boolean $with_module_name)

Check in each module if contains mails folder.



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2507


#### Arguments
* $with_module_name **boolean**



### getModulesHasPDF

    array AdminTranslationsControllerCore::getModulesHasPDF(boolean $classes)

Check in each module if contains pdf folder.



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2540


#### Arguments
* $classes **boolean**



### getTinyMCEForMails

    mixed AdminTranslationsControllerCore::getTinyMCEForMails($iso_lang)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2570


#### Arguments
* $iso_lang **mixed**



### initFormMails

    array|string AdminTranslationsControllerCore::initFormMails(boolean $no_display)

This method generate the form for mails translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2593


#### Arguments
* $no_display **boolean**



### copyMailFilesForAllLanguages

    mixed AdminTranslationsControllerCore::copyMailFilesForAllLanguages()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2661




### getSubjectMail

    array AdminTranslationsControllerCore::getSubjectMail($dir, $file, $subject_mail)

Get list of subjects of mails



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2724


#### Arguments
* $dir **mixed**
* $file **mixed**
* $subject_mail **mixed**



### getSubjectMailContent

    array AdminTranslationsControllerCore::getSubjectMailContent($directory)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2768


#### Arguments
* $directory **mixed** - &lt;p&gt;: name of directory&lt;/p&gt;



### writeSubjectTranslationFile

    mixed AdminTranslationsControllerCore::writeSubjectTranslationFile($sub, $path)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2789


#### Arguments
* $sub **mixed**
* $path **mixed**



### recursiveGetModuleFiles

    mixed AdminTranslationsControllerCore::recursiveGetModuleFiles(string $path, array $array_files, string $module_name, string $lang_file, boolean $is_default)

This get files to translate in module directory.

Recursive method allow to get each files for a module no matter his depth.

* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2825


#### Arguments
* $path **string** - &lt;p&gt;directory path to scan&lt;/p&gt;
* $array_files **array** - &lt;p&gt;by reference - array which saved files to parse.&lt;/p&gt;
* $module_name **string** - &lt;p&gt;module name&lt;/p&gt;
* $lang_file **string** - &lt;p&gt;full path of translation file&lt;/p&gt;
* $is_default **boolean**



### getAllModuleFiles

    array AdminTranslationsControllerCore::getAllModuleFiles(array $modules, string|null $root_dir, string $lang, boolean $is_default)

This method get translation in each translations file.

The file depend on $lang param.

* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2864


#### Arguments
* $modules **array** - &lt;p&gt;List of modules&lt;/p&gt;
* $root_dir **string|null** - &lt;p&gt;path where it get each modules&lt;/p&gt;
* $lang **string** - &lt;p&gt;ISO code of chosen language to translate&lt;/p&gt;
* $is_default **boolean** - &lt;p&gt;Set it if modules are located in root/prestashop/modules folder&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                           This allow to distinguish overridden prestashop theme and original module&lt;/code&gt;&lt;/pre&gt;



### initFormModules

    mixed AdminTranslationsControllerCore::initFormModules()

This method generate the form for modules translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2917




### parsePdfClass

    array AdminTranslationsControllerCore::parsePdfClass(string $file_path, string $file_type, array $lang_array, string $tab, array $tabs_array, array $count_missing)

Parse PDF class



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2959


#### Arguments
* $file_path **string** - &lt;p&gt;File to parse&lt;/p&gt;
* $file_type **string** - &lt;p&gt;Type of file&lt;/p&gt;
* $lang_array **array** - &lt;p&gt;Contains expression in the chosen language&lt;/p&gt;
* $tab **string** - &lt;p&gt;name      To use with the md5 key&lt;/p&gt;
* $tabs_array **array**
* $count_missing **array**



### initFormPDF

    mixed AdminTranslationsControllerCore::initFormPDF()

This method generate the form for PDF translations



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 2987




### listFiles

    array AdminTranslationsControllerCore::listFiles(string $dir, array $list, string $file_ext)

Recursively list files in directory $dir



* Visibility: **public**
* This method is defined in controllers\admin\AdminTranslationsController.php line 3079


#### Arguments
* $dir **string**
* $list **array**
* $file_ext **string**



### theme_exists

    boolean AdminTranslationsControllerCore::theme_exists(string $theme)

Checks if theme exists



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTranslationsController.php line 3104


#### Arguments
* $theme **string**


