StoresControllerCore
===============






* Class name: StoresControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $php_self

    public mixed $php_self = 'stores'





* Visibility: **public**


Methods
-------


### init

    mixed StoresControllerCore::init()

Initialize stores controller



* Visibility: **public**




### processStoreAddress

    string StoresControllerCore::processStoreAddress(array $store)

Get formatted string address



* Visibility: **protected**


#### Arguments
* $store **array**



### assignStoresSimplified

    mixed StoresControllerCore::assignStoresSimplified()

Assign template vars for simplified stores



* Visibility: **protected**




### renderStoreWorkingHours

    mixed StoresControllerCore::renderStoreWorkingHours($store)





* Visibility: **public**


#### Arguments
* $store **mixed**



### getStores

    mixed StoresControllerCore::getStores()





* Visibility: **public**




### assignStores

    mixed StoresControllerCore::assignStores()

Assign template vars for classical stores



* Visibility: **protected**




### displayAjax

    mixed StoresControllerCore::displayAjax()

Display the Xml for showing the nodes in the google map



* Visibility: **protected**




### initContent

    mixed StoresControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**




### setMedia

    mixed StoresControllerCore::setMedia()





* Visibility: **public**



