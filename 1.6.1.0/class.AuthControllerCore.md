Class AuthControllerCore
=====================





* Class name: AuthControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/AuthController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L27)


Contents
--------


### Properties

* [$auth](#property-$auth)
* [$create_account](#property-$create_account)
* [$id_country](#property-$id_country)
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


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = false
```





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L31).


### <a name="property-$create_account"></a>$create_account

```php
protected boolean $create_account
```





* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L36).


### <a name="property-$id_country"></a>$id_country

```php
protected mixed $id_country
```





* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L37).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'authentication'
```





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L30).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* Source: [controllers/front/AuthController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L29).


Methods
-------


### <a name="method-assignAddressFormat"></a>assignAddressFormat

```php
mixed AuthControllerCore::assignAddressFormat()
```

Assign address var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L210)




### <a name="method-assignCountries"></a>assignCountries

```php
mixed AuthControllerCore::assignCountries()
```

Assign countries var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L192)




### <a name="method-assignDate"></a>assignDate

```php
mixed AuthControllerCore::assignDate()
```

Assign date var to smarty



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L168)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AuthControllerCore::displayAjax()
```

Run ajax process



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L76)




### <a name="method-init"></a>init

```php
mixed AuthControllerCore::init()
```

Initialize auth controller



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L43)




### <a name="method-initContent"></a>initContent

```php
mixed AuthControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L85)




### <a name="method-postProcess"></a>postProcess

```php
mixed AuthControllerCore::postProcess()
```

Start forms process



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L237)




### <a name="method-processCustomerNewsletter"></a>processCustomerNewsletter

```php
mixed AuthControllerCore::processCustomerNewsletter(\Customer $customer)
```

Process the newsletter settings and set the customer infos.



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L350)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)** - Reference on the customer Object.



### <a name="method-processSubmitAccount"></a>processSubmitAccount

```php
mixed AuthControllerCore::processSubmitAccount()
```

Process submit on an account



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L369)




### <a name="method-processSubmitCreate"></a>processSubmitCreate

```php
mixed AuthControllerCore::processSubmitCreate()
```

Process submit on a creation



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L668)




### <a name="method-processSubmitLogin"></a>processSubmitLogin

```php
mixed AuthControllerCore::processSubmitLogin()
```

Process login



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L252)




### <a name="method-sendConfirmationMail"></a>sendConfirmationMail

```php
boolean AuthControllerCore::sendConfirmationMail(\Customer $customer)
```

sendConfirmationMail



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L714)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AuthControllerCore::setMedia()
```

Set default medias for this controller



* Visibility: **public**
* Source: [controllers/front/AuthController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L58)




### <a name="method-updateContext"></a>updateContext

```php
mixed AuthControllerCore::updateContext(\Customer $customer)
```

Update context after customer creation



* Visibility: **protected**
* Source: [controllers/front/AuthController.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/AuthController.php#L690)


#### Arguments
* $customer **[Customer](class.CustomerCore.md)** - Created customer


