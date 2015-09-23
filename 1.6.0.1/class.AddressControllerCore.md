Class AddressControllerCore
=====================





* Class name: AddressControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/AddressController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L27)


Contents
--------


### Properties

* [$_address](#property-$_address)
* [$auth](#property-$auth)
* [$authRedirection](#property-$authRedirection)
* [$guestAllowed](#property-$guestAllowed)
* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)

### Methods

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

```php
protected \Address $_address
```





* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L38).


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = true
```





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L29).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public mixed $authRedirection = 'addresses'
```





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L32).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public mixed $guestAllowed = true
```





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L30).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'address'
```





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L31).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L33).


Methods
-------


### <a name="method-assignAddressFormat"></a>assignAddressFormat

```php
mixed AddressControllerCore::assignAddressFormat()
```

Assign template vars related to address format



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L344)




### <a name="method-assignCountries"></a>assignCountries

```php
mixed AddressControllerCore::assignCountries()
```

Assign template vars related to countries display



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L302)




### <a name="method-assignVatNumber"></a>assignVatNumber

```php
mixed AddressControllerCore::assignVatNumber()
```

Assign template vars related to vat number



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L355)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AddressControllerCore::displayAjax()
```





* Visibility: **public**
* Source: [controllers/front/AddressController.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L375)




### <a name="method-init"></a>init

```php
mixed AddressControllerCore::init()
```

Initialize address controller



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L55)




### <a name="method-initContent"></a>initContent

```php
mixed AddressControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L265)




### <a name="method-postProcess"></a>postProcess

```php
mixed AddressControllerCore::postProcess()
```

Start forms process



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L105)




### <a name="method-processSubmitAddress"></a>processSubmitAddress

```php
mixed AddressControllerCore::processSubmitAddress()
```

Process changes on an address



* Visibility: **protected**
* Source: [controllers/front/AddressController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L120)




### <a name="method-setMedia"></a>setMedia

```php
mixed AddressControllerCore::setMedia()
```

Set default medias for this controller



* Visibility: **public**
* Source: [controllers/front/AddressController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/AddressController.php#L43)



