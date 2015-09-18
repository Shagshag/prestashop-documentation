GuestTrackingControllerCore
===============






* Class name: GuestTrackingControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $ssl

    public mixed $ssl = true





* Visibility: **public**


### $php_self

    public mixed $php_self = 'guest-tracking'





* Visibility: **public**


Methods
-------


### init

    mixed GuestTrackingControllerCore::init()

Initialize guest tracking controller



* Visibility: **public**




### postProcess

    mixed GuestTrackingControllerCore::postProcess()

Start forms process



* Visibility: **public**




### initContent

    mixed GuestTrackingControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**




### assignOrderTracking

    mixed GuestTrackingControllerCore::assignOrderTracking(\PrestaShopCollection $order_collection)

Assigns template vars related to order tracking information



* Visibility: **protected**


#### Arguments
* $order_collection **PrestaShopCollection**



### setMedia

    mixed GuestTrackingControllerCore::setMedia()





* Visibility: **public**




### processAddressFormat

    mixed GuestTrackingControllerCore::processAddressFormat(\Address $delivery, \Address $invoice)





* Visibility: **protected**


#### Arguments
* $delivery **Address**
* $invoice **Address**


