AdminCustomersControllerCore
===============






* Class name: AdminCustomersControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $delete_mode

    protected mixed $delete_mode





* Visibility: **protected**


### $_defaultOrderBy

    protected mixed $_defaultOrderBy = 'date_add'





* Visibility: **protected**


### $_defaultOrderWay

    protected mixed $_defaultOrderWay = 'DESC'





* Visibility: **protected**


### $can_add_customer

    protected mixed $can_add_customer = true





* Visibility: **protected**


### $meaning_status

    protected mixed $meaning_status = array()





* Visibility: **protected**
* This property is **static**.


### $object

    public \Customer $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminCustomersControllerCore::__construct()





* Visibility: **public**




### postProcess

    mixed AdminCustomersControllerCore::postProcess()





* Visibility: **public**




### initContent

    mixed AdminCustomersControllerCore::initContent()





* Visibility: **public**




### initToolbar

    mixed AdminCustomersControllerCore::initToolbar()





* Visibility: **public**




### getList

    mixed AdminCustomersControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**


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




### initPageHeaderToolbar

    mixed AdminCustomersControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initProcess

    mixed AdminCustomersControllerCore::initProcess()





* Visibility: **public**




### renderList

    mixed AdminCustomersControllerCore::renderList()





* Visibility: **public**




### renderForm

    mixed AdminCustomersControllerCore::renderForm()





* Visibility: **public**




### beforeAdd

    mixed AdminCustomersControllerCore::beforeAdd($customer)





* Visibility: **public**


#### Arguments
* $customer **mixed**



### renderKpis

    mixed AdminCustomersControllerCore::renderKpis()





* Visibility: **public**




### renderView

    mixed AdminCustomersControllerCore::renderView()





* Visibility: **public**




### processDelete

    mixed AdminCustomersControllerCore::processDelete()





* Visibility: **public**




### _setDeletedMode

    mixed AdminCustomersControllerCore::_setDeletedMode()





* Visibility: **protected**




### processBulkDelete

    mixed AdminCustomersControllerCore::processBulkDelete()





* Visibility: **protected**




### processAdd

    mixed AdminCustomersControllerCore::processAdd()





* Visibility: **public**




### processUpdate

    mixed AdminCustomersControllerCore::processUpdate()





* Visibility: **public**




### processSave

    mixed AdminCustomersControllerCore::processSave()





* Visibility: **public**




### afterDelete

    mixed AdminCustomersControllerCore::afterDelete($object, $old_id)





* Visibility: **protected**


#### Arguments
* $object **mixed**
* $old_id **mixed**



### processGuestToCustomer

    mixed AdminCustomersControllerCore::processGuestToCustomer()

Transform a guest account into a registered customer account



* Visibility: **public**




### processChangeNewsletterVal

    mixed AdminCustomersControllerCore::processChangeNewsletterVal()

Toggle the newsletter flag



* Visibility: **public**




### processChangeOptinVal

    mixed AdminCustomersControllerCore::processChangeOptinVal()

Toggle newsletter optin flag



* Visibility: **public**




### printNewsIcon

    mixed AdminCustomersControllerCore::printNewsIcon($value, $customer)





* Visibility: **public**


#### Arguments
* $value **mixed**
* $customer **mixed**



### printOptinIcon

    mixed AdminCustomersControllerCore::printOptinIcon($value, $customer)





* Visibility: **public**


#### Arguments
* $value **mixed**
* $customer **mixed**



### displayDeleteLink

    mixed AdminCustomersControllerCore::displayDeleteLink(string $token, integer $id, string $name)





* Visibility: **public**


#### Arguments
* $token **string**
* $id **integer**
* $name **string**



### ajaxProcessSearchCustomers

    void AdminCustomersControllerCore::ajaxProcessSearchCustomers()

add to $this->content the result of Customer::SearchByName
(encoded in json)



* Visibility: **public**




### ajaxProcessUpdateCustomerNote

    void AdminCustomersControllerCore::ajaxProcessUpdateCustomerNote()

Uodate the customer note



* Visibility: **public**



