AdminCustomerThreadsControllerCore
===============






* Class name: AdminCustomerThreadsControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \CustomerThread $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminCustomerThreadsControllerCore::__construct()





* Visibility: **public**




### renderList

    mixed AdminCustomerThreadsControllerCore::renderList()





* Visibility: **public**




### initToolbar

    mixed AdminCustomerThreadsControllerCore::initToolbar()





* Visibility: **public**




### postProcess

    mixed AdminCustomerThreadsControllerCore::postProcess()





* Visibility: **public**




### initContent

    mixed AdminCustomerThreadsControllerCore::initContent()





* Visibility: **public**




### openUploadedFile

    mixed AdminCustomerThreadsControllerCore::openUploadedFile()





* Visibility: **protected**




### renderKpis

    mixed AdminCustomerThreadsControllerCore::renderKpis()





* Visibility: **public**




### renderView

    mixed AdminCustomerThreadsControllerCore::renderView()





* Visibility: **public**




### getTimeline

    mixed AdminCustomerThreadsControllerCore::getTimeline($messages, $id_order)





* Visibility: **public**


#### Arguments
* $messages **mixed**
* $id_order **mixed**



### displayMessage

    mixed AdminCustomerThreadsControllerCore::displayMessage($message, $email, $id_employee)





* Visibility: **protected**


#### Arguments
* $message **mixed**
* $email **mixed**
* $id_employee **mixed**



### displayButton

    mixed AdminCustomerThreadsControllerCore::displayButton($content)





* Visibility: **protected**


#### Arguments
* $content **mixed**



### renderOptions

    mixed AdminCustomerThreadsControllerCore::renderOptions()





* Visibility: **public**




### getList

    mixed AdminCustomerThreadsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### updateOptionPsSavImapOpt

    mixed AdminCustomerThreadsControllerCore::updateOptionPsSavImapOpt($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### ajaxProcessMarkAsRead

    mixed AdminCustomerThreadsControllerCore::ajaxProcessMarkAsRead()





* Visibility: **public**




### ajaxProcessSyncImap

    mixed AdminCustomerThreadsControllerCore::ajaxProcessSyncImap()

Call the IMAP synchronization during an AJAX process.



* Visibility: **public**




### renderProcessSyncImap

    mixed AdminCustomerThreadsControllerCore::renderProcessSyncImap()

Call the IMAP synchronization during the render process.



* Visibility: **public**




### syncImap

    array AdminCustomerThreadsControllerCore::syncImap()

Imap synchronization method.



* Visibility: **public**



