AuthControllerCore
===============






* Class name: AuthControllerCore
* Namespace: 
* Parent class: [FrontController](FrontControllerCore)

* This class is defined in [controllers/front/AuthController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#27)





Properties
----------


### $ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in [controllers/front/AuthController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#29)


### $php_self

    public mixed $php_self = 'authentication'





* Visibility: **public**
* This property is defined in [controllers/front/AuthController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#30)


### $auth

    public mixed $auth = false





* Visibility: **public**
* This property is defined in [controllers/front/AuthController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#31)


### $create_account

    protected boolean $create_account





* Visibility: **protected**
* This property is defined in [controllers/front/AuthController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#36)


### $id_country

    protected mixed $id_country





* Visibility: **protected**
* This property is defined in [controllers/front/AuthController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#37)


Methods
-------


### init

    mixed AuthControllerCore::init()

Initialize auth controller



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#43)




### setMedia

    mixed AuthControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#60)




### displayAjax

    mixed AuthControllerCore::displayAjax()

Run ajax process



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#79)




### initContent

    mixed AuthControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#88)




### assignDate

    mixed AuthControllerCore::assignDate()

Assign date var to smarty



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#174)




### assignCountries

    mixed AuthControllerCore::assignCountries()

Assign countries var to smarty



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#198)




### assignAddressFormat

    mixed AuthControllerCore::assignAddressFormat()

Assign address var to smarty



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#217)




### postProcess

    mixed AuthControllerCore::postProcess()

Start forms process



* Visibility: **public**
* This method is defined in [controllers/front/AuthController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#249)




### processSubmitLogin

    mixed AuthControllerCore::processSubmitLogin()

Process login



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#267)




### processCustomerNewsletter

    mixed AuthControllerCore::processCustomerNewsletter(\Customer $customer)

Process the newsletter settings and set the customer infos.



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#360)


#### Arguments
* $customer **[Customer](CustomerCore)** - &lt;p&gt;Reference on the customer Object.&lt;/p&gt;



### processSubmitAccount

    mixed AuthControllerCore::processSubmitAccount()

Process submit on an account



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#378)




### processSubmitCreate

    mixed AuthControllerCore::processSubmitCreate()

Process submit on a creation



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#699)




### updateContext

    mixed AuthControllerCore::updateContext(\Customer $customer)

Update context after customer creation



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#718)


#### Arguments
* $customer **[Customer](CustomerCore)** - &lt;p&gt;Created customer&lt;/p&gt;



### sendConfirmationMail

    boolean AuthControllerCore::sendConfirmationMail(\Customer $customer)

sendConfirmationMail



* Visibility: **protected**
* This method is defined in [controllers/front/AuthController.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/AuthController.php#743)


#### Arguments
* $customer **[Customer](CustomerCore)**


