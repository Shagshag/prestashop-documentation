AuthControllerCore
===============






* Class name: AuthControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/AuthController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L27)





Properties
----------

* [$ssl](#property-$ssl)
* [$php_self](#property-$php_self)
* [$auth](#property-$auth)
* [$create_account](#property-$create_account)
* [$id_country](#property-$id_country)

Methods
-------
* [init](#method-init)
* [setMedia](#method-setMedia)
* [displayAjax](#method-displayAjax)
* [initContent](#method-initContent)
* [assignDate](#method-assignDate)
* [assignCountries](#method-assignCountries)
* [assignAddressFormat](#method-assignAddressFormat)
* [postProcess](#method-postProcess)
* [processSubmitLogin](#method-processSubmitLogin)
* [processCustomerNewsletter](#method-processCustomerNewsletter)
* [processSubmitAccount](#method-processSubmitAccount)
* [processSubmitCreate](#method-processSubmitCreate)
* [updateContext](#method-updateContext)
* [sendConfirmationMail](#method-sendConfirmationMail)




Properties
----------


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in [controllers/front/AuthController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L29)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'authentication'





* Visibility: **public**
* This property is defined in [controllers/front/AuthController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L30)


### <a name="property-$auth"></a>$auth

    public mixed $auth = false





* Visibility: **public**
* This property is defined in [controllers/front/AuthController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L31)


### <a name="property-$create_account"></a>$create_account

    protected boolean $create_account





* Visibility: **protected**
* This property is defined in [controllers/front/AuthController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L36)


### <a name="property-$id_country"></a>$id_country

    protected mixed $id_country





* Visibility: **protected**
* This property is defined in [controllers/front/AuthController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L37)


Methods
-------


### <a name="method-init"></a>init

    mixed AuthControllerCore::init()

Initialize auth controller



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L43)




### <a name="method-setMedia"></a>setMedia

    mixed AuthControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L60)




### <a name="method-displayAjax"></a>displayAjax

    mixed AuthControllerCore::displayAjax()

Run ajax process



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L79)




### <a name="method-initContent"></a>initContent

    mixed AuthControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L88)




### <a name="method-assignDate"></a>assignDate

    mixed AuthControllerCore::assignDate()

Assign date var to smarty



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L174)




### <a name="method-assignCountries"></a>assignCountries

    mixed AuthControllerCore::assignCountries()

Assign countries var to smarty



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L198)




### <a name="method-assignAddressFormat"></a>assignAddressFormat

    mixed AuthControllerCore::assignAddressFormat()

Assign address var to smarty



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L217)




### <a name="method-postProcess"></a>postProcess

    mixed AuthControllerCore::postProcess()

Start forms process



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L249)




### <a name="method-processSubmitLogin"></a>processSubmitLogin

    mixed AuthControllerCore::processSubmitLogin()

Process login



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L267)




### <a name="method-processCustomerNewsletter"></a>processCustomerNewsletter

    mixed AuthControllerCore::processCustomerNewsletter(\Customer $customer)

Process the newsletter settings and set the customer infos.



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L360)


#### Arguments
* $customer **[Customer](CustomerCore)** - &lt;p&gt;Reference on the customer Object.&lt;/p&gt;



### <a name="method-processSubmitAccount"></a>processSubmitAccount

    mixed AuthControllerCore::processSubmitAccount()

Process submit on an account



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L378)




### <a name="method-processSubmitCreate"></a>processSubmitCreate

    mixed AuthControllerCore::processSubmitCreate()

Process submit on a creation



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L699)




### <a name="method-updateContext"></a>updateContext

    mixed AuthControllerCore::updateContext(\Customer $customer)

Update context after customer creation



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L718)


#### Arguments
* $customer **[Customer](CustomerCore)** - &lt;p&gt;Created customer&lt;/p&gt;



### <a name="method-sendConfirmationMail"></a>sendConfirmationMail

    boolean AuthControllerCore::sendConfirmationMail(\Customer $customer)

sendConfirmationMail



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#L743)


#### Arguments
* $customer **[Customer](CustomerCore)**


