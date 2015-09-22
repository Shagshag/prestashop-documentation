CookieCore
===============






* Class name: CookieCore
* Namespace: 
* This class is defined in classes\Cookie.php line 27





Properties
----------


### $_content

    protected array $_content





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 30


### $_name

    protected array $_name





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 33


### $_expire

    protected array $_expire





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 36


### $_domain

    protected array $_domain





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 39


### $_path

    protected array $_path





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 42


### $_cipherTool

    protected array $_cipherTool





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 45


### $_modified

    protected mixed $_modified = false





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 47


### $_allow_writing

    protected mixed $_allow_writing





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 49


### $_salt

    protected mixed $_salt





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 51


### $_standalone

    protected mixed $_standalone





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 53


### $_secure

    protected mixed $_secure = false





* Visibility: **protected**
* This property is defined in classes\Cookie.php line 55


Methods
-------


### __construct

    mixed CookieCore::__construct($name, $path, $expire, $shared_urls, $standalone, $secure)

Get data if the cookie exists and else initialize an new one



* Visibility: **public**
* This method is defined in classes\Cookie.php line 63


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
* This method is defined in classes\Cookie.php line 91




### getDomain

    mixed CookieCore::getDomain($shared_urls)





* Visibility: **protected**
* This method is defined in classes\Cookie.php line 96


#### Arguments
* $shared_urls **mixed**



### setExpire

    mixed CookieCore::setExpire(integer $expire)

Set expiration date



* Visibility: **public**
* This method is defined in classes\Cookie.php line 136


#### Arguments
* $expire **integer** - &lt;p&gt;Expiration time from now&lt;/p&gt;



### __get

    string CookieCore::__get(string $key)

Magic method wich return cookie data from _content array



* Visibility: **public**
* This method is defined in classes\Cookie.php line 147


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### __isset

    boolean CookieCore::__isset(string $key)

Magic method which check if key exists in the cookie



* Visibility: **public**
* This method is defined in classes\Cookie.php line 158


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### __set

    mixed CookieCore::__set(string $key, mixed $value)

Magic method which adds data into _content array



* Visibility: **public**
* This method is defined in classes\Cookie.php line 170


#### Arguments
* $key **string** - &lt;p&gt;Access key for the value&lt;/p&gt;
* $value **mixed** - &lt;p&gt;Value corresponding to the key&lt;/p&gt;



### __unset

    mixed CookieCore::__unset(string $key)

Magic method wich delete data into _content array



* Visibility: **public**
* This method is defined in classes\Cookie.php line 189


#### Arguments
* $key **string** - &lt;p&gt;key wanted&lt;/p&gt;



### isLogged

    boolean CookieCore::isLogged($withGuest)

Check customer informations saved into cookie and return customer validity



* Visibility: **public**
* This method is defined in classes\Cookie.php line 203


#### Arguments
* $withGuest **mixed**



### isLoggedBack

    boolean CookieCore::isLoggedBack()

Check employee informations saved into cookie and return employee validity



* Visibility: **public**
* This method is defined in classes\Cookie.php line 223




### logout

    mixed CookieCore::logout()

Delete cookie
As of version 1.5 don't call this function, use Customer::logout() or Employee::logout() instead;



* Visibility: **public**
* This method is defined in classes\Cookie.php line 238




### mylogout

    mixed CookieCore::mylogout()

Soft logout, delete everything links to the customer
but leave there affiliate's informations.

As of version 1.5 don't call this function, use Customer::mylogout() instead;

* Visibility: **public**
* This method is defined in classes\Cookie.php line 251




### makeNewLog

    mixed CookieCore::makeNewLog()





* Visibility: **public**
* This method is defined in classes\Cookie.php line 269




### update

    mixed CookieCore::update($nullValues)

Get cookie content



* Visibility: **public**
* This method is defined in classes\Cookie.php line 280


#### Arguments
* $nullValues **mixed**



### _setcookie

    mixed CookieCore::_setcookie($cookie)

Setcookie according to php version



* Visibility: **protected**
* This method is defined in classes\Cookie.php line 331


#### Arguments
* $cookie **mixed**



### __destruct

    mixed CookieCore::__destruct()





* Visibility: **public**
* This method is defined in classes\Cookie.php line 347




### write

    mixed CookieCore::write()

Save cookie with setcookie()



* Visibility: **public**
* This method is defined in classes\Cookie.php line 355




### getFamily

    mixed CookieCore::getFamily($origin)

Get a family of variables (e.g. "filter_")



* Visibility: **public**
* This method is defined in classes\Cookie.php line 381


#### Arguments
* $origin **mixed**



### unsetFamily

    mixed CookieCore::unsetFamily($origin)





* Visibility: **public**
* This method is defined in classes\Cookie.php line 398


#### Arguments
* $origin **mixed**



### getAll

    mixed CookieCore::getAll()





* Visibility: **public**
* This method is defined in classes\Cookie.php line 406




### getName

    String CookieCore::getName()





* Visibility: **public**
* This method is defined in classes\Cookie.php line 414




### exists

    boolean CookieCore::exists()

Check if the cookie exists



* Visibility: **public**
* This method is defined in classes\Cookie.php line 425



