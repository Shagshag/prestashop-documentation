AdminLanguagesControllerCore
===============






* Class name: AdminLanguagesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \Language $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminLanguagesControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminLanguagesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderList

    mixed AdminLanguagesControllerCore::renderList()





* Visibility: **public**




### renderForm

    mixed AdminLanguagesControllerCore::renderForm()





* Visibility: **public**




### processDelete

    mixed AdminLanguagesControllerCore::processDelete()





* Visibility: **public**




### processBulkDelete

    mixed AdminLanguagesControllerCore::processBulkDelete()





* Visibility: **protected**




### checkDeletion

    mixed AdminLanguagesControllerCore::checkDeletion($object)





* Visibility: **protected**


#### Arguments
* $object **mixed**



### checkDisableStatus

    mixed AdminLanguagesControllerCore::checkDisableStatus($object)





* Visibility: **protected**


#### Arguments
* $object **mixed**



### processStatus

    mixed AdminLanguagesControllerCore::processStatus()





* Visibility: **public**




### processBulkDisableSelection

    mixed AdminLanguagesControllerCore::processBulkDisableSelection()





* Visibility: **protected**




### processAdd

    mixed AdminLanguagesControllerCore::processAdd()





* Visibility: **public**




### processUpdate

    mixed AdminLanguagesControllerCore::processUpdate()





* Visibility: **public**




### copyNoPictureImage

    void|false AdminLanguagesControllerCore::copyNoPictureImage(string $language)

Copy a no-product image



* Visibility: **public**


#### Arguments
* $language **string** - &lt;p&gt;Language iso_code for no_picture image filename&lt;/p&gt;



### deleteNoPictureImages

    boolean AdminLanguagesControllerCore::deleteNoPictureImages(string $id_language)

deleteNoPictureImages will delete all default image created for the language id_language



* Visibility: **protected**


#### Arguments
* $id_language **string**



### copyFromPost

    mixed AdminLanguagesControllerCore::copyFromPost(\Language $object, string $table)





* Visibility: **protected**


#### Arguments
* $object **Language**
* $table **string**



### ajaxProcessCheckLangPack

    mixed AdminLanguagesControllerCore::ajaxProcessCheckLangPack()





* Visibility: **public**




### checkEmployeeIdLang

    mixed AdminLanguagesControllerCore::checkEmployeeIdLang($current_id_lang)





* Visibility: **protected**


#### Arguments
* $current_id_lang **mixed**



### afterImageUpload

    mixed AdminLanguagesControllerCore::afterImageUpload()





* Visibility: **protected**



