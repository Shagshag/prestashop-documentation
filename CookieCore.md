CookieCore
===============






* Class name: CookieCore
* This class is defined in [classes/Cookie.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L27)





Properties
----------

* [$_content](#property-$_content)
* [$_name](#property-$_name)
* [$_expire](#property-$_expire)
* [$_domain](#property-$_domain)
* [$_path](#property-$_path)
* [$_cipherTool](#property-$_cipherTool)
* [$_modified](#property-$_modified)
* [$_allow_writing](#property-$_allow_writing)
* [$_salt](#property-$_salt)
* [$_standalone](#property-$_standalone)
* [$_secure](#property-$_secure)

Methods
-------
* [__construct](#method-__construct)
* [disallowWriting](#method-disallowWriting)
* [getDomain](#method-getDomain)
* [setExpire](#method-setExpire)
* [__get](#method-__get)
* [__isset](#method-__isset)
* [__set](#method-__set)
* [__unset](#method-__unset)
* [isLogged](#method-isLogged)
* [isLoggedBack](#method-isLoggedBack)
* [logout](#method-logout)
* [mylogout](#method-mylogout)
* [makeNewLog](#method-makeNewLog)
* [update](#method-update)
* [_setcookie](#method-_setcookie)
* [__destruct](#method-__destruct)
* [write](#method-write)
* [getFamily](#method-getFamily)
* [unsetFamily](#method-unsetFamily)
* [getAll](#method-getAll)
* [getName](#method-getName)
* [exists](#method-exists)




Properties
----------


### <a name="property-$_content"></a>$_content

    protected array $_content





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L30)


### <a name="property-$_name"></a>$_name

    protected array $_name





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L33)


### <a name="property-$_expire"></a>$_expire

    protected array $_expire





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L36)


### <a name="property-$_domain"></a>$_domain

    protected array $_domain





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L39)


### <a name="property-$_path"></a>$_path

    protected array $_path





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L42)


### <a name="property-$_cipherTool"></a>$_cipherTool

    protected array $_cipherTool





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L45)


### <a name="property-$_modified"></a>$_modified

    protected mixed $_modified = false





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L47)


### <a name="property-$_allow_writing"></a>$_allow_writing

    protected mixed $_allow_writing





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L49)


### <a name="property-$_salt"></a>$_salt

    protected mixed $_salt





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L51)


### <a name="property-$_standalone"></a>$_standalone

    protected mixed $_standalone





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L53)


### <a name="property-$_secure"></a>$_secure

    protected mixed $_secure = false





* Visibility: **protected**
* This property is defined in [classes/Cookie.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L55)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed CookieCore::__construct($name, $path, $expire, $shared_urls, $standalone, $secure)

Get data if the cookie exists and else initialize an new one



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L63)


#### Arguments
* $name **mixed** - &lt;p&gt;string Cookie name before encrypting&lt;/p&gt;
* $path **mixed** - &lt;p&gt;string&lt;/p&gt;
* $expire **mixed**
* $shared_urls **mixed**
* $standalone **mixed**
* $secure **mixed**



### <a name="method-disallowWriting"></a>disallowWriting

    mixed CookieCore::disallowWriting()





* Visibility: **public**
* This method is defined in [classes/Cookie.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L91)




### <a name="method-getDomain"></a>getDomain

    mixed CookieCore::getDomain($shared_urls)





* Visibility: **protected**
* This method is defined in [classes/Cookie.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L96)


#### Arguments
* $shared_urls **mixed**



### <a name="method-setExpire"></a>setExpire

    mixed CookieCore::setExpire(integer $expire)

Set expiration date



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L136)


#### Arguments
* $expire **integer** - &lt;p&gt;Expiration time from now&lt;/p&gt;



### <a name="method-__get"></a>__get

    string CookieCore::__get(string $key)

Magic method wich return cookie data from _content array



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L147)


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### <a name="method-__isset"></a>__isset

    boolean CookieCore::__isset(string $key)

Magic method which check if key exists in the cookie



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L158)


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### <a name="method-__set"></a>__set

    mixed CookieCore::__set(string $key, mixed $value)

Magic method which adds data into _content array



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L170)


#### Arguments
* $key **string** - &lt;p&gt;Access key for the value&lt;/p&gt;
* $value **mixed** - &lt;p&gt;Value corresponding to the key&lt;/p&gt;



### <a name="method-__unset"></a>__unset

    mixed CookieCore::__unset(string $key)

Magic method wich delete data into _content array



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L189)


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### <a name="method-isLogged"></a>isLogged

    boolean CookieCore::isLogged($withGuest)

Check customer informations saved into cookie and return customer validity



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L203)


#### Arguments
* $withGuest **mixed**



### <a name="method-isLoggedBack"></a>isLoggedBack

    boolean CookieCore::isLoggedBack()

Check employee informations saved into cookie and return employee validity



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L223)




### <a name="method-logout"></a>logout

    mixed CookieCore::logout()

Delete cookie
As of version 1.5 don't call this function, use Customer::logout() or Employee::logout() instead;



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L238)




### <a name="method-mylogout"></a>mylogout

    mixed CookieCore::mylogout()

Soft logout, delete everything links to the customer
but leave there affiliate's informations.

As of version 1.5 don't call this function, use Customer::mylogout() instead;

* Visibility: **public**
* This method is defined in [classes/Cookie.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L251)




### <a name="method-makeNewLog"></a>makeNewLog

    mixed CookieCore::makeNewLog()





* Visibility: **public**
* This method is defined in [classes/Cookie.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L269)




### <a name="method-update"></a>update

    mixed CookieCore::update($nullValues)

Get cookie content



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L280)


#### Arguments
* $nullValues **mixed**



### <a name="method-_setcookie"></a>_setcookie

    mixed CookieCore::_setcookie($cookie)

Setcookie according to php version



* Visibility: **protected**
* This method is defined in [classes/Cookie.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L331)


#### Arguments
* $cookie **mixed**



### <a name="method-__destruct"></a>__destruct

    mixed CookieCore::__destruct()





* Visibility: **public**
* This method is defined in [classes/Cookie.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L347)




### <a name="method-write"></a>write

    mixed CookieCore::write()

Save cookie with setcookie()



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L355)




### <a name="method-getFamily"></a>getFamily

    mixed CookieCore::getFamily($origin)

Get a family of variables (e.g. "filter_")



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L381)


#### Arguments
* $origin **mixed**



### <a name="method-unsetFamily"></a>unsetFamily

    mixed CookieCore::unsetFamily($origin)





* Visibility: **public**
* This method is defined in [classes/Cookie.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L398)


#### Arguments
* $origin **mixed**



### <a name="method-getAll"></a>getAll

    mixed CookieCore::getAll()





* Visibility: **public**
* This method is defined in [classes/Cookie.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L406)




### <a name="method-getName"></a>getName

    String CookieCore::getName()





* Visibility: **public**
* This method is defined in [classes/Cookie.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L414)




### <a name="method-exists"></a>exists

    boolean CookieCore::exists()

Check if the cookie exists



* Visibility: **public**
* This method is defined in [classes/Cookie.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cookie.php#L425)



