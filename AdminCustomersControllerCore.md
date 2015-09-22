AdminCustomersControllerCore
===============






* Class name: AdminCustomersControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminCustomersController.php line 30





Properties
----------


### $delete_mode

    protected mixed $delete_mode





* Visibility: **protected**
* This property is defined in controllers\admin\AdminCustomersController.php line 32


### $_defaultOrderBy

    protected mixed $_defaultOrderBy = 'date_add'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminCustomersController.php line 34


### $_defaultOrderWay

    protected mixed $_defaultOrderWay = 'DESC'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminCustomersController.php line 35


### $can_add_customer

    protected mixed $can_add_customer = true





* Visibility: **protected**
* This property is defined in controllers\admin\AdminCustomersController.php line 36


### $meaning_status

    protected mixed $meaning_status = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in controllers\admin\AdminCustomersController.php line 37


### $object

    public \Customer $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminCustomersController.php line 30


Methods
-------


### __construct

    mixed AdminCustomersControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 39




### postProcess

    mixed AdminCustomersControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 186




### initContent

    mixed AdminCustomersControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 195




### initToolbar

    mixed AdminCustomersControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 212




### getList

    mixed AdminCustomersControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 226


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### initToolbarTitle

    mixed AdminCustomersControllerCore::initToolbarTitle()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 238




### initPageHeaderToolbar

    mixed AdminCustomersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 273




### initProcess

    mixed AdminCustomersControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 286




### renderList

    mixed AdminCustomersControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 320




### renderForm

    mixed AdminCustomersControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 333




### beforeAdd

    mixed AdminCustomersControllerCore::beforeAdd($customer)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 626


#### Arguments
* $customer **mixed**



### renderKpis

    mixed AdminCustomersControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 631




### renderView

    mixed AdminCustomersControllerCore::renderView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 695




### processDelete

    mixed AdminCustomersControllerCore::processDelete()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 876




### _setDeletedMode

    mixed AdminCustomersControllerCore::_setDeletedMode()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCustomersController.php line 882




### processBulkDelete

    mixed AdminCustomersControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCustomersController.php line 894




### processAdd

    mixed AdminCustomersControllerCore::processAdd()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 900




### processUpdate

    mixed AdminCustomersControllerCore::processUpdate()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 926




### processSave

    mixed AdminCustomersControllerCore::processSave()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 949




### afterDelete

    mixed AdminCustomersControllerCore::afterDelete($object, $old_id)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCustomersController.php line 963


#### Arguments
* $object **mixed**
* $old_id **mixed**



### processGuestToCustomer

    mixed AdminCustomersControllerCore::processGuestToCustomer()

Transform a guest account into a registered customer account



* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 977




### processChangeNewsletterVal

    mixed AdminCustomersControllerCore::processChangeNewsletterVal()

Toggle the newsletter flag



* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 999




### processChangeOptinVal

    mixed AdminCustomersControllerCore::processChangeOptinVal()

Toggle newsletter optin flag



* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 1015




### printNewsIcon

    mixed AdminCustomersControllerCore::printNewsIcon($value, $customer)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 1028


#### Arguments
* $value **mixed**
* $customer **mixed**



### printOptinIcon

    mixed AdminCustomersControllerCore::printOptinIcon($value, $customer)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 1036


#### Arguments
* $value **mixed**
* $customer **mixed**



### displayDeleteLink

    mixed AdminCustomersControllerCore::displayDeleteLink(string $token, integer $id, string $name)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 1050


#### Arguments
* $token **string**
* $id **integer**
* $name **string**



### ajaxProcessSearchCustomers

    void AdminCustomersControllerCore::ajaxProcessSearchCustomers()

add to $this->content the result of Customer::SearchByName
(encoded in json)



* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 1074




### ajaxProcessUpdateCustomerNote

    void AdminCustomersControllerCore::ajaxProcessUpdateCustomerNote()

Uodate the customer note



* Visibility: **public**
* This method is defined in controllers\admin\AdminCustomersController.php line 1106



