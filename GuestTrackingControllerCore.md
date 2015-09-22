GuestTrackingControllerCore
===============






* Class name: GuestTrackingControllerCore
* Namespace: 
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in controllers\front\GuestTrackingController.php line 27





Properties
----------


### $ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in controllers\front\GuestTrackingController.php line 29


### $php_self

    public mixed $php_self = 'guest-tracking'





* Visibility: **public**
* This property is defined in controllers\front\GuestTrackingController.php line 30


Methods
-------


### init

    mixed GuestTrackingControllerCore::init()

Initialize guest tracking controller



* Visibility: **public**
* This method is defined in controllers\front\GuestTrackingController.php line 36




### postProcess

    mixed GuestTrackingControllerCore::postProcess()

Start forms process



* Visibility: **public**
* This method is defined in controllers\front\GuestTrackingController.php line 48




### initContent

    mixed GuestTrackingControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in controllers\front\GuestTrackingController.php line 112




### assignOrderTracking

    mixed GuestTrackingControllerCore::assignOrderTracking(\PrestaShopCollection $order_collection)

Assigns template vars related to order tracking information



* Visibility: **protected**
* This method is defined in controllers\front\GuestTrackingController.php line 135


#### Arguments
* $order_collection **[PrestaShopCollection](PrestaShopCollectionCore)**



### setMedia

    mixed GuestTrackingControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\front\GuestTrackingController.php line 188




### processAddressFormat

    mixed GuestTrackingControllerCore::processAddressFormat(\Address $delivery, \Address $invoice)





* Visibility: **protected**
* This method is defined in controllers\front\GuestTrackingController.php line 196


#### Arguments
* $delivery **[Address](AddressCore)**
* $invoice **[Address](AddressCore)**


