Class AddressControllerCore
=====================





* Class name: AddressControllerCore
* Parent class: [FrontController](class.FrontControllerCore)
* Source: [controllers/front/AddressController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L27)



Properties
----------

* [$_address](#property-$_address)
* [$auth](#property-$auth)
* [$authRedirection](#property-$authRedirection)
* [$guestAllowed](#property-$guestAllowed)
* [$id_country](#property-$id_country)
* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)

Methods
-------
* [assignAddressFormat](#method-assignAddressFormat)
* [assignCountries](#method-assignCountries)
* [assignVatNumber](#method-assignVatNumber)
* [displayAjax](#method-displayAjax)
* [init](#method-init)
* [initContent](#method-initContent)
* [postProcess](#method-postProcess)
* [processSubmitAddress](#method-processSubmitAddress)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$_address"></a>$_address

    protected \Address $_address





* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L38)


### <a name="property-$auth"></a>$auth

    public mixed $auth = true





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L29)


### <a name="property-$authRedirection"></a>$authRedirection

    public mixed $authRedirection = 'addresses'





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L32)


### <a name="property-$guestAllowed"></a>$guestAllowed

    public mixed $guestAllowed = true





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L30)


### <a name="property-$id_country"></a>$id_country

    protected mixed $id_country





* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L39)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'address'





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L31)


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L33)


Methods
-------


### <a name="method-assignAddressFormat"></a>assignAddressFormat

    mixed AddressControllerCore::assignAddressFormat()

Assign template vars related to address format



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L321)




### <a name="method-assignCountries"></a>assignCountries

    mixed AddressControllerCore::assignCountries()

Assign template vars related to countries display



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L293)




### <a name="method-assignVatNumber"></a>assignVatNumber

    mixed AddressControllerCore::assignVatNumber()

Assign template vars related to vat number



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L338)




### <a name="method-displayAjax"></a>displayAjax

    mixed AddressControllerCore::displayAjax()





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L360)




### <a name="method-init"></a>init

    mixed AddressControllerCore::init()

Initialize address controller



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L58)




### <a name="method-initContent"></a>initContent

    mixed AddressControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L255)




### <a name="method-postProcess"></a>postProcess

    mixed AddressControllerCore::postProcess()

Start forms process



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L104)




### <a name="method-processSubmitAddress"></a>processSubmitAddress

    mixed AddressControllerCore::processSubmitAddress()

Process changes on an address



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L118)




### <a name="method-setMedia"></a>setMedia

    mixed AddressControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AddressController.php#L44)



