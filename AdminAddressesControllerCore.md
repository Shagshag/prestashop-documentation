AdminAddressesControllerCore
===============






* Class name: AdminAddressesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $countries_array

    protected array $countries_array = array()





* Visibility: **protected**


### $object

    public \Address $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminAddressesControllerCore::__construct()





* Visibility: **public**




### initToolbar

    mixed AdminAddressesControllerCore::initToolbar()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminAddressesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderForm

    mixed AdminAddressesControllerCore::renderForm()





* Visibility: **public**




### processSave

    mixed AdminAddressesControllerCore::processSave()





* Visibility: **public**




### processAdd

    mixed AdminAddressesControllerCore::processAdd()





* Visibility: **public**




### processAddressFormat

    array AdminAddressesControllerCore::processAddressFormat()

Get Address formats used by the country where the address id retrieved from POST/GET is.



* Visibility: **protected**




### ajaxProcess

    mixed AdminAddressesControllerCore::ajaxProcess()

Method called when an ajax request is made



* Visibility: **public**




### processDelete

    mixed AdminAddressesControllerCore::processDelete()

Object Delete



* Visibility: **public**




### processBulkDelete

    boolean AdminAddressesControllerCore::processBulkDelete()

Delete multiple items



* Visibility: **protected**



