Class AdminCustomersControllerCore
=====================





* Class name: AdminCustomersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCustomersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L30)



Properties
----------

* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$can_add_customer](#property-$can_add_customer)
* [$delete_mode](#property-$delete_mode)
* [$meaning_status](#property-$meaning_status)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [_setDeletedMode](#method-_setDeletedMode)
* [afterDelete](#method-afterDelete)
* [ajaxProcessSearchCustomers](#method-ajaxProcessSearchCustomers)
* [ajaxProcessUpdateCustomerNote](#method-ajaxProcessUpdateCustomerNote)
* [beforeAdd](#method-beforeAdd)
* [displayDeleteLink](#method-displayDeleteLink)
* [getList](#method-getList)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [postProcess](#method-postProcess)
* [printNewsIcon](#method-printNewsIcon)
* [printOptinIcon](#method-printOptinIcon)
* [processAdd](#method-processAdd)
* [processBulkDelete](#method-processBulkDelete)
* [processChangeNewsletterVal](#method-processChangeNewsletterVal)
* [processChangeOptinVal](#method-processChangeOptinVal)
* [processDelete](#method-processDelete)
* [processGuestToCustomer](#method-processGuestToCustomer)
* [processSave](#method-processSave)
* [processUpdate](#method-processUpdate)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

    protected mixed $_defaultOrderBy = 'date_add'





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L34).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

    protected mixed $_defaultOrderWay = 'DESC'





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L35).


### <a name="property-$can_add_customer"></a>$can_add_customer

    protected mixed $can_add_customer = true





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L36).


### <a name="property-$delete_mode"></a>$delete_mode

    protected mixed $delete_mode





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L32).


### <a name="property-$meaning_status"></a>$meaning_status

    protected mixed $meaning_status = array()





* Visibility: **protected**
* This property is **static**.
* Source: [controllers/admin/AdminCustomersController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L37).


### <a name="property-$object"></a>$object

    public \Customer $object





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCustomersControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L39)




### <a name="method-_setDeletedMode"></a>_setDeletedMode

    mixed AdminCustomersControllerCore::_setDeletedMode()





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L882)




### <a name="method-afterDelete"></a>afterDelete

    mixed AdminCustomersControllerCore::afterDelete($object, $old_id)





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 963](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L963)


#### Arguments
* $object **mixed**
* $old_id **mixed**



### <a name="method-ajaxProcessSearchCustomers"></a>ajaxProcessSearchCustomers

    void AdminCustomersControllerCore::ajaxProcessSearchCustomers()

add to $this->content the result of Customer::SearchByName
(encoded in json)



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1074](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1074)




### <a name="method-ajaxProcessUpdateCustomerNote"></a>ajaxProcessUpdateCustomerNote

    void AdminCustomersControllerCore::ajaxProcessUpdateCustomerNote()

Uodate the customer note



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1106)




### <a name="method-beforeAdd"></a>beforeAdd

    mixed AdminCustomersControllerCore::beforeAdd($customer)





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L626)


#### Arguments
* $customer **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

    mixed AdminCustomersControllerCore::displayDeleteLink(string $token, integer $id, string $name)





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1050](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1050)


#### Arguments
* $token **string**
* $id **integer**
* $name **string**



### <a name="method-getList"></a>getList

    mixed AdminCustomersControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L226)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initContent"></a>initContent

    mixed AdminCustomersControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L195)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCustomersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L273)




### <a name="method-initProcess"></a>initProcess

    mixed AdminCustomersControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L286)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminCustomersControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L212)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

    mixed AdminCustomersControllerCore::initToolbarTitle()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L238)




### <a name="method-postProcess"></a>postProcess

    mixed AdminCustomersControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L186)




### <a name="method-printNewsIcon"></a>printNewsIcon

    mixed AdminCustomersControllerCore::printNewsIcon($value, $customer)





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1028)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-printOptinIcon"></a>printOptinIcon

    mixed AdminCustomersControllerCore::printOptinIcon($value, $customer)





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1036](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1036)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-processAdd"></a>processAdd

    mixed AdminCustomersControllerCore::processAdd()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 900](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L900)




### <a name="method-processBulkDelete"></a>processBulkDelete

    mixed AdminCustomersControllerCore::processBulkDelete()





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 894](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L894)




### <a name="method-processChangeNewsletterVal"></a>processChangeNewsletterVal

    mixed AdminCustomersControllerCore::processChangeNewsletterVal()

Toggle the newsletter flag



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 999](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L999)




### <a name="method-processChangeOptinVal"></a>processChangeOptinVal

    mixed AdminCustomersControllerCore::processChangeOptinVal()

Toggle newsletter optin flag



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1015](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1015)




### <a name="method-processDelete"></a>processDelete

    mixed AdminCustomersControllerCore::processDelete()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L876)




### <a name="method-processGuestToCustomer"></a>processGuestToCustomer

    mixed AdminCustomersControllerCore::processGuestToCustomer()

Transform a guest account into a registered customer account



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L977)




### <a name="method-processSave"></a>processSave

    mixed AdminCustomersControllerCore::processSave()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 949](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L949)




### <a name="method-processUpdate"></a>processUpdate

    mixed AdminCustomersControllerCore::processUpdate()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 926](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L926)




### <a name="method-renderForm"></a>renderForm

    mixed AdminCustomersControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L333)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminCustomersControllerCore::renderKpis()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L631)




### <a name="method-renderList"></a>renderList

    mixed AdminCustomersControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L320)




### <a name="method-renderView"></a>renderView

    mixed AdminCustomersControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L695)



