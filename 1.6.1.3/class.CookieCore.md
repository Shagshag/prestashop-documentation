Class CookieCore
=====================





* Class name: CookieCore
* Source: [classes/Cookie.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L27)


Contents
--------


### Properties

* [$_allow_writing](#property-$_allow_writing)
* [$_cipherTool](#property-$_cipherTool)
* [$_content](#property-$_content)
* [$_domain](#property-$_domain)
* [$_expire](#property-$_expire)
* [$_modified](#property-$_modified)
* [$_name](#property-$_name)
* [$_path](#property-$_path)
* [$_salt](#property-$_salt)
* [$_secure](#property-$_secure)
* [$_standalone](#property-$_standalone)

### Methods

* [__construct](#method-__construct)
* [__destruct](#method-__destruct)
* [__get](#method-__get)
* [__isset](#method-__isset)
* [__set](#method-__set)
* [__unset](#method-__unset)
* [_setcookie](#method-_setcookie)
* [disallowWriting](#method-disallowWriting)
* [exists](#method-exists)
* [getAll](#method-getAll)
* [getDomain](#method-getDomain)
* [getFamily](#method-getFamily)
* [getName](#method-getName)
* [isLogged](#method-isLogged)
* [isLoggedBack](#method-isLoggedBack)
* [logout](#method-logout)
* [makeNewLog](#method-makeNewLog)
* [mylogout](#method-mylogout)
* [setExpire](#method-setExpire)
* [unsetFamily](#method-unsetFamily)
* [update](#method-update)
* [write](#method-write)




Properties
----------


### <a name="property-$_allow_writing"></a>$_allow_writing

```php
protected mixed $_allow_writing
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L49).


### <a name="property-$_cipherTool"></a>$_cipherTool

```php
protected array $_cipherTool
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L45).


### <a name="property-$_content"></a>$_content

```php
protected array $_content
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L30).


### <a name="property-$_domain"></a>$_domain

```php
protected array $_domain
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L39).


### <a name="property-$_expire"></a>$_expire

```php
protected array $_expire
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L36).


### <a name="property-$_modified"></a>$_modified

```php
protected mixed $_modified = false
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L47).


### <a name="property-$_name"></a>$_name

```php
protected array $_name
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L33).


### <a name="property-$_path"></a>$_path

```php
protected array $_path
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L42).


### <a name="property-$_salt"></a>$_salt

```php
protected mixed $_salt
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L51).


### <a name="property-$_secure"></a>$_secure

```php
protected mixed $_secure = false
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L55).


### <a name="property-$_standalone"></a>$_standalone

```php
protected mixed $_standalone
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L53).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CookieCore::__construct($name, $path, $expire, $shared_urls, $standalone, $secure)
```

Get data if the cookie exists and else initialize an new one



* Visibility: **public**
* Source: [classes/Cookie.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L63)


#### Arguments
* $name **mixed** - string Cookie name before encrypting
* $path **mixed** - string
* $expire **mixed**
* $shared_urls **mixed**
* $standalone **mixed**
* $secure **mixed**



### <a name="method-__destruct"></a>__destruct

```php
mixed CookieCore::__destruct()
```





* Visibility: **public**
* Source: [classes/Cookie.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L347)




### <a name="method-__get"></a>__get

```php
string CookieCore::__get(string $key)
```

Magic method wich return cookie data from _content array



* Visibility: **public**
* Source: [classes/Cookie.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L147)


#### Arguments
* $key **string** - key wanted



### <a name="method-__isset"></a>__isset

```php
boolean CookieCore::__isset(string $key)
```

Magic method which check if key exists in the cookie



* Visibility: **public**
* Source: [classes/Cookie.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L158)


#### Arguments
* $key **string** - key wanted



### <a name="method-__set"></a>__set

```php
mixed CookieCore::__set(string $key, mixed $value)
```

Magic method which adds data into _content array



* Visibility: **public**
* Source: [classes/Cookie.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L170)


#### Arguments
* $key **string** - Access key for the value
* $value **mixed** - Value corresponding to the key



### <a name="method-__unset"></a>__unset

```php
mixed CookieCore::__unset(string $key)
```

Magic method wich delete data into _content array



* Visibility: **public**
* Source: [classes/Cookie.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L189)


#### Arguments
* $key **string** - key wanted



### <a name="method-_setcookie"></a>_setcookie

```php
mixed CookieCore::_setcookie($cookie)
```

Setcookie according to php version



* Visibility: **protected**
* Source: [classes/Cookie.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L331)


#### Arguments
* $cookie **mixed**



### <a name="method-disallowWriting"></a>disallowWriting

```php
mixed CookieCore::disallowWriting()
```





* Visibility: **public**
* Source: [classes/Cookie.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L91)




### <a name="method-exists"></a>exists

```php
boolean CookieCore::exists()
```

Check if the cookie exists



* Visibility: **public**
* Source: [classes/Cookie.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L425)




### <a name="method-getAll"></a>getAll

```php
mixed CookieCore::getAll()
```





* Visibility: **public**
* Source: [classes/Cookie.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L406)




### <a name="method-getDomain"></a>getDomain

```php
mixed CookieCore::getDomain($shared_urls)
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L96)


#### Arguments
* $shared_urls **mixed**



### <a name="method-getFamily"></a>getFamily

```php
mixed CookieCore::getFamily($origin)
```

Get a family of variables (e.g. "filter_")



* Visibility: **public**
* Source: [classes/Cookie.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L381)


#### Arguments
* $origin **mixed**



### <a name="method-getName"></a>getName

```php
String CookieCore::getName()
```





* Visibility: **public**
* Source: [classes/Cookie.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L414)




### <a name="method-isLogged"></a>isLogged

```php
boolean CookieCore::isLogged($withGuest)
```

Check customer informations saved into cookie and return customer validity



* Visibility: **public**
* Source: [classes/Cookie.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L203)


#### Arguments
* $withGuest **mixed**



### <a name="method-isLoggedBack"></a>isLoggedBack

```php
boolean CookieCore::isLoggedBack()
```

Check employee informations saved into cookie and return employee validity



* Visibility: **public**
* Source: [classes/Cookie.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L223)




### <a name="method-logout"></a>logout

```php
mixed CookieCore::logout()
```

Delete cookie
As of version 1.5 don't call this function, use Customer::logout() or Employee::logout() instead;



* Visibility: **public**
* Source: [classes/Cookie.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L238)




### <a name="method-makeNewLog"></a>makeNewLog

```php
mixed CookieCore::makeNewLog()
```





* Visibility: **public**
* Source: [classes/Cookie.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L269)




### <a name="method-mylogout"></a>mylogout

```php
mixed CookieCore::mylogout()
```

Soft logout, delete everything links to the customer
but leave there affiliate's informations.

As of version 1.5 don't call this function, use Customer::mylogout() instead;

* Visibility: **public**
* Source: [classes/Cookie.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L251)




### <a name="method-setExpire"></a>setExpire

```php
mixed CookieCore::setExpire(integer $expire)
```

Set expiration date



* Visibility: **public**
* Source: [classes/Cookie.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L136)


#### Arguments
* $expire **integer** - Expiration time from now



### <a name="method-unsetFamily"></a>unsetFamily

```php
mixed CookieCore::unsetFamily($origin)
```





* Visibility: **public**
* Source: [classes/Cookie.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L398)


#### Arguments
* $origin **mixed**



### <a name="method-update"></a>update

```php
mixed CookieCore::update($nullValues)
```

Get cookie content



* Visibility: **public**
* Source: [classes/Cookie.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L280)


#### Arguments
* $nullValues **mixed**



### <a name="method-write"></a>write

```php
mixed CookieCore::write()
```

Save cookie with setcookie()



* Visibility: **public**
* Source: [classes/Cookie.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/Cookie.php#L355)



