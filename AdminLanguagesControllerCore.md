AdminLanguagesControllerCore
===============






* Class name: AdminLanguagesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminLanguagesController.php line 30





Properties
----------


### $object

    public \Language $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminLanguagesController.php line 30


Methods
-------


### __construct

    mixed AdminLanguagesControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 32




### initPageHeaderToolbar

    mixed AdminLanguagesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 108




### renderList

    mixed AdminLanguagesControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 121




### renderForm

    mixed AdminLanguagesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 133




### processDelete

    mixed AdminLanguagesControllerCore::processDelete()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 298




### processBulkDelete

    mixed AdminLanguagesControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 311




### checkDeletion

    mixed AdminLanguagesControllerCore::checkDeletion($object)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 329


#### Arguments
* $object **mixed**



### checkDisableStatus

    mixed AdminLanguagesControllerCore::checkDisableStatus($object)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 351


#### Arguments
* $object **mixed**



### processStatus

    mixed AdminLanguagesControllerCore::processStatus()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 369




### processBulkDisableSelection

    mixed AdminLanguagesControllerCore::processBulkDisableSelection()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 379




### processAdd

    mixed AdminLanguagesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 393




### processUpdate

    mixed AdminLanguagesControllerCore::processUpdate()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 415




### copyNoPictureImage

    void|false AdminLanguagesControllerCore::copyNoPictureImage(string $language)

Copy a no-product image



* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 450


#### Arguments
* $language **string** - &lt;p&gt;Language iso_code for no_picture image filename&lt;/p&gt;



### deleteNoPictureImages

    boolean AdminLanguagesControllerCore::deleteNoPictureImages(string $id_language)

deleteNoPictureImages will delete all default image created for the language id_language



* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 492


#### Arguments
* $id_language **string**



### copyFromPost

    mixed AdminLanguagesControllerCore::copyFromPost(\Language $object, string $table)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 520


#### Arguments
* $object **[Language](LanguageCore)**
* $table **string**



### ajaxProcessCheckLangPack

    mixed AdminLanguagesControllerCore::ajaxProcessCheckLangPack()





* Visibility: **public**
* This method is defined in controllers\admin\AdminLanguagesController.php line 530




### checkEmployeeIdLang

    mixed AdminLanguagesControllerCore::checkEmployeeIdLang($current_id_lang)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 560


#### Arguments
* $current_id_lang **mixed**



### afterImageUpload

    mixed AdminLanguagesControllerCore::afterImageUpload()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminLanguagesController.php line 566



