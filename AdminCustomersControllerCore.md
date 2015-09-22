AdminCustomersControllerCore
===============






* Class name: AdminCustomersControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminCustomersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L30)





Properties
----------

* [$delete_mode](#property-$delete_mode)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$can_add_customer](#property-$can_add_customer)
* [$meaning_status](#property-$meaning_status)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [postProcess](#method-postProcess)
* [initContent](#method-initContent)
* [initToolbar](#method-initToolbar)
* [getList](#method-getList)
* [initToolbarTitle](#method-initToolbarTitle)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [renderList](#method-renderList)
* [renderForm](#method-renderForm)
* [beforeAdd](#method-beforeAdd)
* [renderKpis](#method-renderKpis)
* [renderView](#method-renderView)
* [processDelete](#method-processDelete)
* [_setDeletedMode](#method-_setDeletedMode)
* [processBulkDelete](#method-processBulkDelete)
* [processAdd](#method-processAdd)
* [processUpdate](#method-processUpdate)
* [processSave](#method-processSave)
* [afterDelete](#method-afterDelete)
* [processGuestToCustomer](#method-processGuestToCustomer)
* [processChangeNewsletterVal](#method-processChangeNewsletterVal)
* [processChangeOptinVal](#method-processChangeOptinVal)
* [printNewsIcon](#method-printNewsIcon)
* [printOptinIcon](#method-printOptinIcon)
* [displayDeleteLink](#method-displayDeleteLink)
* [ajaxProcessSearchCustomers](#method-ajaxProcessSearchCustomers)
* [ajaxProcessUpdateCustomerNote](#method-ajaxProcessUpdateCustomerNote)




Properties
----------


### <a name="property-$delete_mode"></a>$delete_mode

    protected mixed $delete_mode





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCustomersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L32)


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

    protected mixed $_defaultOrderBy = 'date_add'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCustomersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L34)


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

    protected mixed $_defaultOrderWay = 'DESC'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCustomersController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L35)


### <a name="property-$can_add_customer"></a>$can_add_customer

    protected mixed $can_add_customer = true





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCustomersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L36)


### <a name="property-$meaning_status"></a>$meaning_status

    protected mixed $meaning_status = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [controllers/admin/AdminCustomersController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L37)


### <a name="property-$object"></a>$object

    public \Customer $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCustomersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCustomersControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L39)




### <a name="method-postProcess"></a>postProcess

    mixed AdminCustomersControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L186)




### <a name="method-initContent"></a>initContent

    mixed AdminCustomersControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L195)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminCustomersControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L212)




### <a name="method-getList"></a>getList

    mixed AdminCustomersControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L226)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initToolbarTitle"></a>initToolbarTitle

    mixed AdminCustomersControllerCore::initToolbarTitle()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L238)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCustomersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L273)




### <a name="method-initProcess"></a>initProcess

    mixed AdminCustomersControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L286)




### <a name="method-renderList"></a>renderList

    mixed AdminCustomersControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L320)




### <a name="method-renderForm"></a>renderForm

    mixed AdminCustomersControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L333)




### <a name="method-beforeAdd"></a>beforeAdd

    mixed AdminCustomersControllerCore::beforeAdd($customer)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L626)


#### Arguments
* $customer **mixed**



### <a name="method-renderKpis"></a>renderKpis

    mixed AdminCustomersControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L631)




### <a name="method-renderView"></a>renderView

    mixed AdminCustomersControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L695)




### <a name="method-processDelete"></a>processDelete

    mixed AdminCustomersControllerCore::processDelete()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L876)




### <a name="method-_setDeletedMode"></a>_setDeletedMode

    mixed AdminCustomersControllerCore::_setDeletedMode()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCustomersController.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L882)




### <a name="method-processBulkDelete"></a>processBulkDelete

    mixed AdminCustomersControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCustomersController.php line 894](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L894)




### <a name="method-processAdd"></a>processAdd

    mixed AdminCustomersControllerCore::processAdd()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 900](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L900)




### <a name="method-processUpdate"></a>processUpdate

    mixed AdminCustomersControllerCore::processUpdate()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 926](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L926)




### <a name="method-processSave"></a>processSave

    mixed AdminCustomersControllerCore::processSave()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 949](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L949)




### <a name="method-afterDelete"></a>afterDelete

    mixed AdminCustomersControllerCore::afterDelete($object, $old_id)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCustomersController.php line 963](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L963)


#### Arguments
* $object **mixed**
* $old_id **mixed**



### <a name="method-processGuestToCustomer"></a>processGuestToCustomer

    mixed AdminCustomersControllerCore::processGuestToCustomer()

Transform a guest account into a registered customer account



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L977)




### <a name="method-processChangeNewsletterVal"></a>processChangeNewsletterVal

    mixed AdminCustomersControllerCore::processChangeNewsletterVal()

Toggle the newsletter flag



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 999](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L999)




### <a name="method-processChangeOptinVal"></a>processChangeOptinVal

    mixed AdminCustomersControllerCore::processChangeOptinVal()

Toggle newsletter optin flag



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 1015](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1015)




### <a name="method-printNewsIcon"></a>printNewsIcon

    mixed AdminCustomersControllerCore::printNewsIcon($value, $customer)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 1028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1028)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-printOptinIcon"></a>printOptinIcon

    mixed AdminCustomersControllerCore::printOptinIcon($value, $customer)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 1036](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1036)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

    mixed AdminCustomersControllerCore::displayDeleteLink(string $token, integer $id, string $name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 1050](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1050)


#### Arguments
* $token **string**
* $id **integer**
* $name **string**



### <a name="method-ajaxProcessSearchCustomers"></a>ajaxProcessSearchCustomers

    void AdminCustomersControllerCore::ajaxProcessSearchCustomers()

add to $this->content the result of Customer::SearchByName
(encoded in json)



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 1074](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1074)




### <a name="method-ajaxProcessUpdateCustomerNote"></a>ajaxProcessUpdateCustomerNote

    void AdminCustomersControllerCore::ajaxProcessUpdateCustomerNote()

Uodate the customer note



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCustomersController.php line 1106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCustomersController.php#L1106)



