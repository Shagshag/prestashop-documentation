AddressControllerCore
===============






* Class name: AddressControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/AddressController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L27)





Properties
----------


### $auth

    public mixed $auth = true





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#29)


### $guestAllowed

    public mixed $guestAllowed = true





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#30)


### $php_self

    public mixed $php_self = 'address'





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#31)


### $authRedirection

    public mixed $authRedirection = 'addresses'





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#32)


### $ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#33)


### $_address

    protected \Address $_address





* Visibility: **protected**
* This property is defined in [controllers/front/AddressController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#38)


### $id_country

    protected mixed $id_country





* Visibility: **protected**
* This property is defined in [controllers/front/AddressController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#39)


Methods
-------


### setMedia

    mixed AddressControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#44)




### init

    mixed AddressControllerCore::init()

Initialize address controller



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#58)




### postProcess

    mixed AddressControllerCore::postProcess()

Start forms process



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#104)




### processSubmitAddress

    mixed AddressControllerCore::processSubmitAddress()

Process changes on an address



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#118)




### initContent

    mixed AddressControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#255)




### assignCountries

    mixed AddressControllerCore::assignCountries()

Assign template vars related to countries display



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#293)




### assignAddressFormat

    mixed AddressControllerCore::assignAddressFormat()

Assign template vars related to address format



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#321)




### assignVatNumber

    mixed AddressControllerCore::assignVatNumber()

Assign template vars related to vat number



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#338)




### displayAjax

    mixed AddressControllerCore::displayAjax()





* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#360)



