CookieCore
===============






* Class name: CookieCore
* Namespace: 





Properties
----------


### $_content

    protected array $_content





* Visibility: **protected**


### $_name

    protected array $_name





* Visibility: **protected**


### $_expire

    protected array $_expire





* Visibility: **protected**


### $_domain

    protected array $_domain





* Visibility: **protected**


### $_path

    protected array $_path





* Visibility: **protected**


### $_cipherTool

    protected array $_cipherTool





* Visibility: **protected**


### $_modified

    protected mixed $_modified = false





* Visibility: **protected**


### $_allow_writing

    protected mixed $_allow_writing





* Visibility: **protected**


### $_salt

    protected mixed $_salt





* Visibility: **protected**


### $_standalone

    protected mixed $_standalone





* Visibility: **protected**


### $_secure

    protected mixed $_secure = false





* Visibility: **protected**


Methods
-------


### __construct

    mixed CookieCore::__construct($name, $path, $expire, $shared_urls, $standalone, $secure)

Get data if the cookie exists and else initialize an new one



* Visibility: **public**


#### Arguments
* $name **mixed** - &lt;p&gt;string Cookie name before encrypting&lt;/p&gt;
* $path **mixed** - &lt;p&gt;string&lt;/p&gt;
* $expire **mixed**
* $shared_urls **mixed**
* $standalone **mixed**
* $secure **mixed**



### disallowWriting

    mixed CookieCore::disallowWriting()





* Visibility: **public**




### getDomain

    mixed CookieCore::getDomain($shared_urls)





* Visibility: **protected**


#### Arguments
* $shared_urls **mixed**



### setExpire

    mixed CookieCore::setExpire(integer $expire)

Set expiration date



* Visibility: **public**


#### Arguments
* $expire **integer** - &lt;p&gt;Expiration time from now&lt;/p&gt;



### __get

    string CookieCore::__get(string $key)

Magic method wich return cookie data from _content array



* Visibility: **public**


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### __isset

    boolean CookieCore::__isset(string $key)

Magic method which check if key exists in the cookie



* Visibility: **public**


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### __set

    mixed CookieCore::__set(string $key, mixed $value)

Magic method which adds data into _content array



* Visibility: **public**


#### Arguments
* $key **string** - &lt;p&gt;Access key for the value&lt;/p&gt;
* $value **mixed** - &lt;p&gt;Value corresponding to the key&lt;/p&gt;



### __unset

    mixed CookieCore::__unset(string $key)

Magic method wich delete data into _content array



* Visibility: **public**


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### isLogged

    boolean CookieCore::isLogged($withGuest)

Check customer informations saved into cookie and return customer validity



* Visibility: **public**


#### Arguments
* $withGuest **mixed**



### isLoggedBack

    boolean CookieCore::isLoggedBack()

Check employee informations saved into cookie and return employee validity



* Visibility: **public**




### logout

    mixed CookieCore::logout()

Delete cookie
As of version 1.5 don't call this function, use Customer::logout() or Employee::logout() instead;



* Visibility: **public**




### mylogout

    mixed CookieCore::mylogout()

Soft logout, delete everything links to the customer
but leave there affiliate's informations.

As of version 1.5 don't call this function, use Customer::mylogout() instead;

* Visibility: **public**




### makeNewLog

    mixed CookieCore::makeNewLog()





* Visibility: **public**




### update

    mixed CookieCore::update($nullValues)

Get cookie content



* Visibility: **public**


#### Arguments
* $nullValues **mixed**



### _setcookie

    mixed CookieCore::_setcookie($cookie)

Setcookie according to php version



* Visibility: **protected**


#### Arguments
* $cookie **mixed**



### __destruct

    mixed CookieCore::__destruct()





* Visibility: **public**




### write

    mixed CookieCore::write()

Save cookie with setcookie()



* Visibility: **public**




### getFamily

    mixed CookieCore::getFamily($origin)

Get a family of variables (e.g. "filter_")



* Visibility: **public**


#### Arguments
* $origin **mixed**



### unsetFamily

    mixed CookieCore::unsetFamily($origin)





* Visibility: **public**


#### Arguments
* $origin **mixed**



### getAll

    mixed CookieCore::getAll()





* Visibility: **public**




### getName

    String CookieCore::getName()





* Visibility: **public**




### exists

    boolean CookieCore::exists()

Check if the cookie exists



* Visibility: **public**



