AuthControllerCore
===============






* Class name: AuthControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $ssl

    public mixed $ssl = true





* Visibility: **public**


### $php_self

    public mixed $php_self = 'authentication'





* Visibility: **public**


### $auth

    public mixed $auth = false





* Visibility: **public**


### $create_account

    protected boolean $create_account





* Visibility: **protected**


### $id_country

    protected mixed $id_country





* Visibility: **protected**


Methods
-------


### init

    mixed AuthControllerCore::init()

Initialize auth controller



* Visibility: **public**




### setMedia

    mixed AuthControllerCore::setMedia()

Set default medias for this controller



* Visibility: **public**




### displayAjax

    mixed AuthControllerCore::displayAjax()

Run ajax process



* Visibility: **public**




### initContent

    mixed AuthControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**




### assignDate

    mixed AuthControllerCore::assignDate()

Assign date var to smarty



* Visibility: **protected**




### assignCountries

    mixed AuthControllerCore::assignCountries()

Assign countries var to smarty



* Visibility: **protected**




### assignAddressFormat

    mixed AuthControllerCore::assignAddressFormat()

Assign address var to smarty



* Visibility: **protected**




### postProcess

    mixed AuthControllerCore::postProcess()

Start forms process



* Visibility: **public**




### processSubmitLogin

    mixed AuthControllerCore::processSubmitLogin()

Process login



* Visibility: **protected**




### processCustomerNewsletter

    mixed AuthControllerCore::processCustomerNewsletter(\Customer $customer)

Process the newsletter settings and set the customer infos.



* Visibility: **protected**


#### Arguments
* $customer **Customer** - &lt;p&gt;Reference on the customer Object.&lt;/p&gt;



### processSubmitAccount

    mixed AuthControllerCore::processSubmitAccount()

Process submit on an account



* Visibility: **protected**




### processSubmitCreate

    mixed AuthControllerCore::processSubmitCreate()

Process submit on a creation



* Visibility: **protected**




### updateContext

    mixed AuthControllerCore::updateContext(\Customer $customer)

Update context after customer creation



* Visibility: **protected**


#### Arguments
* $customer **Customer** - &lt;p&gt;Created customer&lt;/p&gt;



### sendConfirmationMail

    boolean AuthControllerCore::sendConfirmationMail(\Customer $customer)

sendConfirmationMail



* Visibility: **protected**


#### Arguments
* $customer **Customer**


