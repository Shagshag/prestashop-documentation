Class AuthControllerCore
=====================





* Class name: AuthControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/AuthController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L27)



Properties
----------

* [$auth](#property-$auth)
* [$create_account](#property-$create_account)
* [$id_country](#property-$id_country)
* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)

Methods
-------
* [assignAddressFormat](#method-assignAddressFormat)
* [assignCountries](#method-assignCountries)
* [assignDate](#method-assignDate)
* [displayAjax](#method-displayAjax)
* [init](#method-init)
* [initContent](#method-initContent)
* [postProcess](#method-postProcess)
* [processCustomerNewsletter](#method-processCustomerNewsletter)
* [processSubmitAccount](#method-processSubmitAccount)
* [processSubmitCreate](#method-processSubmitCreate)
* [processSubmitLogin](#method-processSubmitLogin)
* [sendConfirmationMail](#method-sendConfirmationMail)
* [setMedia](#method-setMedia)
* [updateContext](#method-updateContext)




Properties
----------


### <a name="property-$auth"></a>$auth

    public mixed $auth = false





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L31).


### <a name="property-$create_account"></a>$create_account

    protected boolean $create_account





* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L36).


### <a name="property-$id_country"></a>$id_country

    protected mixed $id_country





* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L37).


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'authentication'





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L30).


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L29).


Methods
-------


### <a name="method-assignAddressFormat"></a>assignAddressFormat

    mixed AuthControllerCore::assignAddressFormat()

Assign address var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L217)




### <a name="method-assignCountries"></a>assignCountries

    mixed AuthControllerCore::assignCountries()

Assign countries var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L198)




### <a name="method-assignDate"></a>assignDate

    mixed AuthControllerCore::assignDate()

Assign date var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L174)




### <a name="method-displayAjax"></a>displayAjax

    mixed AuthControllerCore::displayAjax()

Run ajax process



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L79)




### <a name="method-init"></a>init

    mixed AuthControllerCore::init()

Initialize auth controller



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L43)




### <a name="method-initContent"></a>initContent

    mixed AuthControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L88)




### <a name="method-postProcess"></a>postProcess

    mixed AuthControllerCore::postProcess()

Start forms process



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L249)




### <a name="method-processCustomerNewsletter"></a>processCustomerNewsletter

    mixed AuthControllerCore::processCustomerNewsletter(\Customer $customer)

Process the newsletter settings and set the customer infos.



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L360)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)** - Reference on the customer Object.



### <a name="method-processSubmitAccount"></a>processSubmitAccount

    mixed AuthControllerCore::processSubmitAccount()

Process submit on an account



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L378)




### <a name="method-processSubmitCreate"></a>processSubmitCreate

    mixed AuthControllerCore::processSubmitCreate()

Process submit on a creation



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L699)




### <a name="method-processSubmitLogin"></a>processSubmitLogin

    mixed AuthControllerCore::processSubmitLogin()

Process login



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L267)




### <a name="method-sendConfirmationMail"></a>sendConfirmationMail

    boolean AuthControllerCore::sendConfirmationMail(\Customer $customer)

sendConfirmationMail



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L743)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)**



### <a name="method-setMedia"></a>setMedia

    mixed AuthControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L60)




### <a name="method-updateContext"></a>updateContext

    mixed AuthControllerCore::updateContext(\Customer $customer)

Update context after customer creation



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L718)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)** - Created customer


