AddressControllerCore
===============






* Class name: AddressControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/AddressController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L27)





Properties
----------

* [$auth](#property-$auth)
* [$guestAllowed](#property-$guestAllowed)
* [$php_self](#property-$php_self)
* [$authRedirection](#property-$authRedirection)
* [$ssl](#property-$ssl)
* [$_address](#property-$_address)
* [$id_country](#property-$id_country)

Methods
-------
* [setMedia](#method-setMedia)
* [init](#method-init)
* [postProcess](#method-postProcess)
* [processSubmitAddress](#method-processSubmitAddress)
* [initContent](#method-initContent)
* [assignCountries](#method-assignCountries)
* [assignAddressFormat](#method-assignAddressFormat)
* [assignVatNumber](#method-assignVatNumber)
* [displayAjax](#method-displayAjax)




Properties
----------


### <a name="property-$auth"></a>$auth

    public mixed $auth = true





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L29)


### <a name="property-$guestAllowed"></a>$guestAllowed

    public mixed $guestAllowed = true





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L30)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'address'





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L31)


### <a name="property-$authRedirection"></a>$authRedirection

    public mixed $authRedirection = 'addresses'





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L32)


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in [controllers/front/AddressController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L33)


### <a name="property-$_address"></a>$_address

    protected \Address $_address





* Visibility: **protected**
* This property is defined in [controllers/front/AddressController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L38)


### <a name="property-$id_country"></a>$id_country

    protected mixed $id_country





* Visibility: **protected**
* This property is defined in [controllers/front/AddressController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L39)


Methods
-------


### <a name="method-setMedia"></a>setMedia

    mixed AddressControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L44)




### <a name="method-init"></a>init

    mixed AddressControllerCore::init()

Initialize address controller



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L58)




### <a name="method-postProcess"></a>postProcess

    mixed AddressControllerCore::postProcess()

Start forms process



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L104)




### <a name="method-processSubmitAddress"></a>processSubmitAddress

    mixed AddressControllerCore::processSubmitAddress()

Process changes on an address



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L118)




### <a name="method-initContent"></a>initContent

    mixed AddressControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L255)




### <a name="method-assignCountries"></a>assignCountries

    mixed AddressControllerCore::assignCountries()

Assign template vars related to countries display



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L293)




### <a name="method-assignAddressFormat"></a>assignAddressFormat

    mixed AddressControllerCore::assignAddressFormat()

Assign template vars related to address format



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L321)




### <a name="method-assignVatNumber"></a>assignVatNumber

    mixed AddressControllerCore::assignVatNumber()

Assign template vars related to vat number



* Visibility: **protected**
* This method is defined in [controllers/front/AddressController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L338)




### <a name="method-displayAjax"></a>displayAjax

    mixed AddressControllerCore::displayAjax()





* Visibility: **public**
* This method is defined in [controllers/front/AddressController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L360)



