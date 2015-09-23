Class AuthControllerCore
=====================





* Class name: AuthControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/AuthController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L27)


Contents
--------


### Properties

* [$create_account](#property-$create_account)
* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)

### Methods

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


### <a name="property-$create_account"></a>$create_account

```php
protected boolean $create_account
```





* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L35).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'authentication'
```





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L30).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L29).


Methods
-------


### <a name="method-assignAddressFormat"></a>assignAddressFormat

```php
mixed AuthControllerCore::assignAddressFormat()
```

Assign address var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L223)




### <a name="method-assignCountries"></a>assignCountries

```php
mixed AuthControllerCore::assignCountries()
```

Assign countries var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L200)




### <a name="method-assignDate"></a>assignDate

```php
mixed AuthControllerCore::assignDate()
```

Assign date var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L171)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AuthControllerCore::displayAjax()
```

Run ajax process



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L74)




### <a name="method-init"></a>init

```php
mixed AuthControllerCore::init()
```

Initialize auth controller



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L41)




### <a name="method-initContent"></a>initContent

```php
mixed AuthControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L83)




### <a name="method-postProcess"></a>postProcess

```php
mixed AuthControllerCore::postProcess()
```

Start forms process



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L246)




### <a name="method-processCustomerNewsletter"></a>processCustomerNewsletter

```php
mixed AuthControllerCore::processCustomerNewsletter(\Customer $customer)
```

Process the newsletter settings and set the customer infos.



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L345)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)** - Reference on the customer Object.



### <a name="method-processSubmitAccount"></a>processSubmitAccount

```php
mixed AuthControllerCore::processSubmitAccount()
```

Process submit on an account



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L361)




### <a name="method-processSubmitCreate"></a>processSubmitCreate

```php
mixed AuthControllerCore::processSubmitCreate()
```

Process submit on a creation



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 646](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L646)




### <a name="method-processSubmitLogin"></a>processSubmitLogin

```php
mixed AuthControllerCore::processSubmitLogin()
```

Process login



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L261)




### <a name="method-sendConfirmationMail"></a>sendConfirmationMail

```php
boolean AuthControllerCore::sendConfirmationMail(\Customer $customer)
```

sendConfirmationMail



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 692](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L692)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AuthControllerCore::setMedia()
```

Set default medias for this controller



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L56)




### <a name="method-updateContext"></a>updateContext

```php
mixed AuthControllerCore::updateContext(\Customer $customer)
```

Update context after customer creation



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/front/AuthController.php#L668)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)** - Created customer


