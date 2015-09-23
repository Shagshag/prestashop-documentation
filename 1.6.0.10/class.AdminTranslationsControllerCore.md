Class AdminTranslationsControllerCore
=====================





* Class name: AdminTranslationsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTranslationsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L27)


Contents
--------

### Constants

* [DEFAULT_THEME_NAME](#constant-DEFAULT_THEME_NAME)
* [TEXTAREA_SIZED](#constant-TEXTAREA_SIZED)

### Properties

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

### Methods

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

```php
const DEFAULT_THEME_NAME = _PS_DEFAULT_THEME_NAME_
```

Name of theme by default



* Source: [controllers/admin/AdminTranslationsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L30).


### <a name="constant-TEXTAREA_SIZED"></a>TEXTAREA_SIZED

```php
const TEXTAREA_SIZED = 70
```





* Source: [controllers/admin/AdminTranslationsController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L31).


Properties
----------


### <a name="property-$all_iso_lang"></a>$all_iso_lang

```php
protected array $all_iso_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L43).


### <a name="property-$ignore_folder"></a>$ignore_folder

```php
protected array $ignore_folder = array('.', '..', '.svn', '.git', '.htaccess', 'index.php')
```





* Visibility: **protected**
* This property is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L49).


### <a name="property-$lang_selected"></a>$lang_selected

```php
protected \Language $lang_selected
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L67).


### <a name="property-$languages"></a>$languages

```php
protected array $languages
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L55).


### <a name="property-$link_lang_pack"></a>$link_lang_pack

```php
protected string $link_lang_pack = 'http://www.prestashop.com/download/lang_packs/get_each_language_pack.php'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L34).


### <a name="property-$missing_translations"></a>$missing_translations

```php
protected integer $missing_translations
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L40).


### <a name="property-$modules_translations"></a>$modules_translations

```php
protected array $modules_translations = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L46).


### <a name="property-$post_limit_exceed"></a>$post_limit_exceed

```php
protected boolean $post_limit_exceed = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L70).


### <a name="property-$theme_selected"></a>$theme_selected

```php
protected string $theme_selected
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L61).


### <a name="property-$themes"></a>$themes

```php
protected array $themes
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L58).


### <a name="property-$total_expression"></a>$total_expression

```php
protected integer $total_expression
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L37).


### <a name="property-$translations_informations"></a>$translations_informations

```php
protected array $translations_informations = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L52).


### <a name="property-$type_selected"></a>$type_selected

```php
protected string $type_selected
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L64).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTranslationsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L72)




### <a name="method-addNewTabs"></a>addNewTabs

```php
mixed AdminTranslationsControllerCore::addNewTabs(array $iso_code, array $files)
```

Add new translations tabs by code ISO



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L615)


#### Arguments
* $iso_code **array**
* $files **array**



### <a name="method-changeModulesKeyTranslation"></a>changeModulesKeyTranslation

```php
boolean AdminTranslationsControllerCore::changeModulesKeyTranslation(string $path, string $theme_from, string $theme_to)
```

Change the key translation to according it to theme name.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L393)


#### Arguments
* $path **string**
* $theme_from **string**
* $theme_to **string**



### <a name="method-checkAndAddMailsFiles"></a>checkAndAddMailsFiles

```php
mixed AdminTranslationsControllerCore::checkAndAddMailsFiles($iso_code, $files_list)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 489](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L489)


#### Arguments
* $iso_code **mixed**
* $files_list **mixed**



### <a name="method-checkAndAddThemesFiles"></a>checkAndAddThemesFiles

```php
mixed AdminTranslationsControllerCore::checkAndAddThemesFiles(array $files, array $themes_selected)
```

Move theme translations in selected themes



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L577)


#### Arguments
* $files **array**
* $themes_selected **array**



### <a name="method-checkDirAndCreate"></a>checkDirAndCreate

```php
boolean AdminTranslationsControllerCore::checkDirAndCreate(string $dest)
```

This method is only used by AdminTranslations::submitCopyLang().

It try to create folder in new theme.

When a translation file is copied for a module, its translation key is wrong.
We have to change the translation key and rewrite the file.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L245)


#### Arguments
* $dest **string** - file name



### <a name="method-checkIfKeyUseSprintf"></a>checkIfKeyUseSprintf

```php
array|boolean AdminTranslationsControllerCore::checkIfKeyUseSprintf($key)
```

Find sentence which use %d, %s, %%, %1$d, %1$s.

..

* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1720](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1720)


#### Arguments
* $key **mixed** - : english sentence



### <a name="method-checkTranslationFile"></a>checkTranslationFile

```php
mixed AdminTranslationsControllerCore::checkTranslationFile($content)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L658)


#### Arguments
* $content **mixed**



### <a name="method-cleanMailContent"></a>cleanMailContent

```php
mixed AdminTranslationsControllerCore::cleanMailContent($content, $lang, $title)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2441](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2441)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $title **mixed**



### <a name="method-clearModuleFiles"></a>clearModuleFiles

```php
array AdminTranslationsControllerCore::clearModuleFiles($files, string $type_clear, string $path)
```

Clear the list of module file by type (file or directory)



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L977)


#### Arguments
* $files **mixed** - : list of files
* $type_clear **string** - (file|directory)
* $path **string**



### <a name="method-copyMailFilesForAllLanguages"></a>copyMailFilesForAllLanguages

```php
mixed AdminTranslationsControllerCore::copyMailFilesForAllLanguages()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2575)




### <a name="method-displayLimitPostWarning"></a>displayLimitPostWarning

```php
mixed AdminTranslationsControllerCore::displayLimitPostWarning($count)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1695](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1695)


#### Arguments
* $count **mixed**



### <a name="method-displayMailBlockHtml"></a>displayMailBlockHtml

```php
mixed AdminTranslationsControllerCore::displayMailBlockHtml(array $content, string $lang, string $url, string $mail_name, string $group_name, string|boolean $name_for_module)
```

Just build the html structure for display html mails.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2414](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2414)


#### Arguments
* $content **array** - with english and language needed contents
* $lang **string** - iso code of the needed language
* $url **string** - for the html page and displaying an outline
* $mail_name **string** - name of the file to translate (same for txt and html files)
* $group_name **string** - group name allow to distinguish each block of mail.
* $name_for_module **string|boolean** - is not false define add a name for disntiguish mails module



### <a name="method-displayMailBlockTxt"></a>displayMailBlockTxt

```php
mixed AdminTranslationsControllerCore::displayMailBlockTxt(array $content, string $lang, string $mail_name, string $group_name, string|boolean $name_for_module)
```

Just build the html structure for display txt mails



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2395)


#### Arguments
* $content **array** - with english and language needed contents
* $lang **string** - iso code of the needed language
* $mail_name **string** - name of the file to translate (same for txt and html files)
* $group_name **string** - group name allow to distinguish each block of mail.
* $name_for_module **string|boolean** - is not false define add a name for disntiguish mails module



### <a name="method-displayMailContent"></a>displayMailContent

```php
mixed AdminTranslationsControllerCore::displayMailContent(array $mails, array $all_subject_mail, \Language $obj_lang, string $id_html, string $title, string|boolean $name_for_module)
```

Display mails in html format.

This was create for factorize the html displaying

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2276](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2276)


#### Arguments
* $mails **array**
* $all_subject_mail **array**
* $obj_lang **[Language](class.LanguageCore.md)**
* $id_html **string** - use for set html id attribute for the block
* $title **string** - Set the title for the block
* $name_for_module **string|boolean** - is not false define add a name for disntiguish mails module



### <a name="method-displayMailEditor"></a>displayMailEditor

```php
mixed AdminTranslationsControllerCore::displayMailEditor($content, $lang, $url, $mail_name, $group_name, $name_for_module)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2433)


#### Arguments
* $content **mixed**
* $lang **mixed**
* $url **mixed**
* $mail_name **mixed**
* $group_name **mixed**
* $name_for_module **mixed**



### <a name="method-displayToggleButton"></a>displayToggleButton

```php
mixed AdminTranslationsControllerCore::displayToggleButton($closed)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1679](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1679)


#### Arguments
* $closed **mixed**



### <a name="method-exportTabs"></a>exportTabs

```php
mixed AdminTranslationsControllerCore::exportTabs()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L408)




### <a name="method-fileExists"></a>fileExists

```php
mixed AdminTranslationsControllerCore::fileExists()
```

Include file $dir/$file and return the var $var declared in it.

This create the file if not exists

return array : translations

* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1660](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1660)




### <a name="method-filesListToPaths"></a>filesListToPaths

```php
mixed AdminTranslationsControllerCore::filesListToPaths($list)
```

Turn the list returned by
AdminTranslationsController::filterTranslationFiles()
into a list of paths that can be passed to
Archive_Tar::extractList()



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L827)


#### Arguments
* $list **mixed**



### <a name="method-filterTranslationFiles"></a>filterTranslationFiles

```php
mixed AdminTranslationsControllerCore::filterTranslationFiles($list)
```

Filter the translation files contained in a .gzip pack
and return only the ones that we want.

Right now the function only needs to check that
the modules for which we want to add translations
are present on the shop (installed or not).

$list is the output of Archive_Tar::listContent()

* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminTranslationsController.php line 803](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L803)


#### Arguments
* $list **mixed**



### <a name="method-findAndFillTranslations"></a>findAndFillTranslations

```php
void AdminTranslationsControllerCore::findAndFillTranslations(array $files, string $theme_name, string $module_name, string|boolean $dir)
```

This method get translation for each files of a module,
compare with global $_MODULES array and fill AdminTranslations::modules_translations array
With key as English sentences and values as their iso code translations.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1010](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1010)


#### Arguments
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-findAndWriteTranslationsIntoFile"></a>findAndWriteTranslationsIntoFile

```php
void AdminTranslationsControllerCore::findAndWriteTranslationsIntoFile(string $file_name, array $files, string $theme_name, string $module_name, string|boolean $dir)
```

This method check each file (tpl or php file), get its sentences to translate,
compare with posted values and write in iso code translation file.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L899)


#### Arguments
* $file_name **string**
* $files **array**
* $theme_name **string**
* $module_name **string**
* $dir **string|boolean**



### <a name="method-getAllModuleFiles"></a>getAllModuleFiles

```php
mixed AdminTranslationsControllerCore::getAllModuleFiles(array $modules, string $root_dir, string $lang, boolean $is_default)
```

This method get translation in each translations file.

The file depend on $lang param.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2770](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2770)


#### Arguments
* $modules **array** - list of modules
* $root_dir **string** - path where it get each modules
* $lang **string** - iso code of choosen language to translate
* $is_default **boolean** - set it if modules are located in root/prestashop/modules folder
              This allow to distinguish overrided prestashop theme and original module



### <a name="method-getFileToParseByTypeTranslation"></a>getFileToParseByTypeTranslation

```php
array AdminTranslationsControllerCore::getFileToParseByTypeTranslation()
```

Get list of files which must be parsed by directory and by type of translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1073](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1073)




### <a name="method-getInformations"></a>getInformations

```php
mixed AdminTranslationsControllerCore::getInformations()
```

Get all informations on : languages, theme and the translation type.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1321](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1321)




### <a name="method-getListModules"></a>getListModules

```php
array AdminTranslationsControllerCore::getListModules()
```

Check if directory and file exist and return an list of modules



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2012](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2012)




### <a name="method-getMailContent"></a>getMailContent

```php
array AdminTranslationsControllerCore::getMailContent(string $dir, string $file)
```

Get content of the mail file.



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2255)


#### Arguments
* $dir **string**
* $file **string**



### <a name="method-getMailFiles"></a>getMailFiles

```php
array AdminTranslationsControllerCore::getMailFiles(string $dir, string $group_name)
```

Get each informations for each mails found in the folder $dir.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2192)


#### Arguments
* $dir **string**
* $group_name **string**



### <a name="method-getMailPattern"></a>getMailPattern

```php
mixed AdminTranslationsControllerCore::getMailPattern()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1535](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1535)




### <a name="method-getModuleTranslations"></a>getModuleTranslations

```php
mixed AdminTranslationsControllerCore::getModuleTranslations()
```

This method merge each arrays of modules translation in the array of modules translations



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L220)




### <a name="method-getModulesHasMails"></a>getModulesHasMails

```php
array AdminTranslationsControllerCore::getModulesHasMails($with_module_name)
```

Check in each module if contains mails folder.



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2467](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2467)


#### Arguments
* $with_module_name **mixed**



### <a name="method-getSubjectMail"></a>getSubjectMail

```php
array AdminTranslationsControllerCore::getSubjectMail($dir, $file, $subject_mail)
```

Get list of subjects of mails



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2638)


#### Arguments
* $dir **mixed**
* $file **mixed**
* $subject_mail **mixed**



### <a name="method-getSubjectMailContent"></a>getSubjectMailContent

```php
array AdminTranslationsControllerCore::getSubjectMailContent($directory)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2679](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2679)


#### Arguments
* $directory **mixed** - : name of directory



### <a name="method-getTinyMCEForMails"></a>getTinyMCEForMails

```php
mixed AdminTranslationsControllerCore::getTinyMCEForMails($iso_lang)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2491](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2491)


#### Arguments
* $iso_lang **mixed**



### <a name="method-getTranslationsInformations"></a>getTranslationsInformations

```php
mixed AdminTranslationsControllerCore::getTranslationsInformations()
```

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
* Source: [controllers/admin/AdminTranslationsController.php line 1263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1263)




### <a name="method-initContent"></a>initContent

```php
mixed AdminTranslationsControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L93)




### <a name="method-initForm"></a>initForm

```php
\call AdminTranslationsControllerCore::initForm($method_name)
```

This function create vars by default and call the good method for generate form



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L125)


#### Arguments
* $method_name **mixed**



### <a name="method-initFormBack"></a>initFormBack

```php
mixed AdminTranslationsControllerCore::initFormBack()
```

This method generate the form for back translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1820](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1820)




### <a name="method-initFormErrors"></a>initFormErrors

```php
mixed AdminTranslationsControllerCore::initFormErrors()
```

This method generate the form for errors translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2031](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2031)




### <a name="method-initFormFields"></a>initFormFields

```php
mixed AdminTranslationsControllerCore::initFormFields()
```

This method generate the form for fields translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2092](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2092)




### <a name="method-initFormFront"></a>initFormFront

```php
mixed AdminTranslationsControllerCore::initFormFront()
```

This method generate the form for front translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1730)




### <a name="method-initFormMails"></a>initFormMails

```php
mixed AdminTranslationsControllerCore::initFormMails($no_display)
```

This method generate the form for mails translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2510)


#### Arguments
* $no_display **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminTranslationsControllerCore::initFormModules()
```

This method generate the form for modules translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2820](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2820)




### <a name="method-initFormPDF"></a>initFormPDF

```php
mixed AdminTranslationsControllerCore::initFormPDF()
```

This method generate the form for PDF translations



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2888](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2888)




### <a name="method-initMain"></a>initMain

```php
mixed AdminTranslationsControllerCore::initMain()
```

Generate the Main page



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L175)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminTranslationsControllerCore::initToolbar()
```

AdminController::initToolbar() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L155)




### <a name="method-listFiles"></a>listFiles

```php
mixed AdminTranslationsControllerCore::listFiles($dir, $list, $file_ext)
```

recursively list files in directory $dir



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 2976](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2976)


#### Arguments
* $dir **mixed**
* $list **mixed**
* $file_ext **mixed**



### <a name="method-parsePdfClass"></a>parsePdfClass

```php
array AdminTranslationsControllerCore::parsePdfClass(string $file_path, string $file_type, $lang_array, string $tab, array $tabs_array, $count_missing)
```

Parse PDF class



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2859](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2859)


#### Arguments
* $file_path **string** - file to parse
* $file_type **string** - type of file
* $lang_array **mixed**
* $tab **string** - name to use with the md5 key
* $tabs_array **array**
* $count_missing **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminTranslationsControllerCore::postProcess()
```

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1420)




### <a name="method-recursiveGetModuleFiles"></a>recursiveGetModuleFiles

```php
mixed AdminTranslationsControllerCore::recursiveGetModuleFiles(string $path, array $array_files, string $module_name, string $lang_file, boolean $is_default)
```

This get files to translate in module directory.

Recursive method allow to get each files for a module no matter his depth.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2737](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2737)


#### Arguments
* $path **string** - directory path to scan
* $array_files **array** - by reference - array which saved files to parse.
* $module_name **string** - module name
* $lang_file **string** - full path of translation file
* $is_default **boolean**



### <a name="method-redirect"></a>redirect

```php
mixed AdminTranslationsControllerCore::redirect(boolean $save_and_stay, boolean $conf)
```

This method redirect in the translation main page or in the translation page



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1525](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1525)


#### Arguments
* $save_and_stay **boolean** - : true if the user has clicked on the button &quot;save and stay&quot;
* $conf **boolean** - : id of confirmation message



### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminTranslationsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 1369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1369)




### <a name="method-setTypeSelected"></a>setTypeSelected

```php
mixed AdminTranslationsControllerCore::setTypeSelected($type_selected)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L84)


#### Arguments
* $type_selected **mixed**



### <a name="method-submitAddLang"></a>submitAddLang

```php
mixed AdminTranslationsControllerCore::submitAddLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L835)




### <a name="method-submitCopyLang"></a>submitCopyLang

```php
mixed AdminTranslationsControllerCore::submitCopyLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L342)




### <a name="method-submitExportLang"></a>submitExportLang

```php
mixed AdminTranslationsControllerCore::submitExportLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L459)




### <a name="method-submitImportLang"></a>submitImportLang

```php
mixed AdminTranslationsControllerCore::submitImportLang()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTranslationsController.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L697)




### <a name="method-submitTranslationsMails"></a>submitTranslationsMails

```php
mixed AdminTranslationsControllerCore::submitTranslationsMails()
```

This method is used to write translation for mails.

This writes subject translation files
(in root/mails/lang_choosen/lang.php or root/_PS_THEMES_DIR_/mails/lang_choosen/lang.php)
and mails files.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1556](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1556)




### <a name="method-theme_exists"></a>theme_exists

```php
mixed AdminTranslationsControllerCore::theme_exists($theme)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2995](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2995)


#### Arguments
* $theme **mixed**



### <a name="method-userParseFile"></a>userParseFile

```php
\return AdminTranslationsControllerCore::userParseFile($content, $type_translation, string|boolean $type_file, string $module_name)
```

This method parse a file by type of translation and type file



* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 1181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L1181)


#### Arguments
* $content **mixed**
* $type_translation **mixed** - : front, back, errors, modules...
* $type_file **string|boolean** - : (tpl|php)
* $module_name **string** - : name of the module



### <a name="method-writeSubjectTranslationFile"></a>writeSubjectTranslationFile

```php
mixed AdminTranslationsControllerCore::writeSubjectTranslationFile($sub, $path)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 2702](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L2702)


#### Arguments
* $sub **mixed**
* $path **mixed**



### <a name="method-writeTranslationFile"></a>writeTranslationFile

```php
mixed AdminTranslationsControllerCore::writeTranslationFile(boolean $override_file)
```

Read the Post var and write the translation file.

This method overwrites the old translation file.

* Visibility: **protected**
* Source: [controllers/admin/AdminTranslationsController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminTranslationsController.php#L270)


#### Arguments
* $override_file **boolean** - : set true if this file is a override


