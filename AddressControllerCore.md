AddressControllerCore
===============






* Class name: AddressControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $auth

    public mixed $auth = true





* Visibility: **public**


### $guestAllowed

    public mixed $guestAllowed = true





* Visibility: **public**


### $php_self

    public mixed $php_self = 'address'





* Visibility: **public**


### $authRedirection

    public mixed $authRedirection = 'addresses'





* Visibility: **public**


### $ssl

    public mixed $ssl = true





* Visibility: **public**


### $_address

    protected \Address $_address





* Visibility: **protected**


### $id_country

    protected mixed $id_country





* Visibility: **protected**


Methods
-------


### setMedia

    mixed AddressControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**




### init

    mixed AddressControllerCore::init()

Initialize address controller



* Visibility: **public**




### postProcess

    mixed AddressControllerCore::postProcess()

Start forms process



* Visibility: **public**




### processSubmitAddress

    mixed AddressControllerCore::processSubmitAddress()

Process changes on an address



* Visibility: **protected**




### initContent

    mixed AddressControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**




### assignCountries

    mixed AddressControllerCore::assignCountries()

Assign template vars related to countries display



* Visibility: **protected**




### assignAddressFormat

    mixed AddressControllerCore::assignAddressFormat()

Assign template vars related to address format



* Visibility: **protected**




### assignVatNumber

    mixed AddressControllerCore::assignVatNumber()

Assign template vars related to vat number



* Visibility: **protected**




### displayAjax

    mixed AddressControllerCore::displayAjax()





* Visibility: **public**



