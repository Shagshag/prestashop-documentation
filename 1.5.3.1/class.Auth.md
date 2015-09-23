Class Auth
=====================

the purpose I added this class is to make the file system much flexible
for customization.

Actually,  this is a kind of interface and you should modify it to fit your system

* Class name: Auth
* Source: [admin-dev/ajaxfilemanager/inc/class.auth.php line 10](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/admin-dev/ajaxfilemanager/inc/class.auth.php#L10)


Contents
--------


### Properties

* [$__loginIndexInSession](#property-$__loginIndexInSession)

### Methods

* [Auth](#method-Auth)
* [__construct](#method-__construct)
* [isLoggedIn](#method-isLoggedIn)
* [login](#method-login)




Properties
----------


### <a name="property-$__loginIndexInSession"></a>$__loginIndexInSession

```php
public mixed $__loginIndexInSession = 'ajax_user'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.auth.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/admin-dev/ajaxfilemanager/inc/class.auth.php#L12).


Methods
-------


### <a name="method-Auth"></a>Auth

```php
mixed Auth::Auth()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.auth.php line 18](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/admin-dev/ajaxfilemanager/inc/class.auth.php#L18)




### <a name="method-__construct"></a>__construct

```php
mixed Auth::__construct()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.auth.php line 13](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/admin-dev/ajaxfilemanager/inc/class.auth.php#L13)




### <a name="method-isLoggedIn"></a>isLoggedIn

```php
boolean Auth::isLoggedIn()
```

check if the user has logged



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.auth.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/admin-dev/ajaxfilemanager/inc/class.auth.php#L27)




### <a name="method-login"></a>login

```php
boolean Auth::login()
```

validate the username & password



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.auth.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/admin-dev/ajaxfilemanager/inc/class.auth.php#L36)



