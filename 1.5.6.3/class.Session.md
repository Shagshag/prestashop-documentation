Class Session
=====================





* Class name: Session
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L12)


Contents
--------


### Properties

* [$debug](#property-$debug)
* [$dir](#property-$dir)
* [$ext](#property-$ext)
* [$fp](#property-$fp)
* [$gcCounter](#property-$gcCounter)
* [$gcCounterFile](#property-$gcCounterFile)
* [$gcCounterFileName](#property-$gcCounterFileName)
* [$gcLogFile](#property-$gcLogFile)
* [$gcLogFileName](#property-$gcLogFileName)
* [$lifeTime](#property-$lifeTime)
* [$mTime](#property-$mTime)
* [$sessionDir](#property-$sessionDir)
* [$sessionFile](#property-$sessionFile)

### Methods

* [Session](#method-Session)
* [__construct](#method-__construct)
* [_gc](#method-_gc)
* [_log](#method-_log)
* [gc](#method-gc)
* [getSessionDir](#method-getSessionDir)
* [init](#method-init)




Properties
----------


### <a name="property-$debug"></a>$debug

```php
public mixed $debug = true
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 26](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L26).


### <a name="property-$dir"></a>$dir

```php
public mixed $dir = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L16).


### <a name="property-$ext"></a>$ext

```php
public mixed $ext = '.txt'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 20](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L20).


### <a name="property-$fp"></a>$fp

```php
public mixed $fp = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 15](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L15).


### <a name="property-$gcCounter"></a>$gcCounter

```php
public mixed $gcCounter = 5
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 21](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L21).


### <a name="property-$gcCounterFile"></a>$gcCounterFile

```php
public mixed $gcCounterFile = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 23](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L23).


### <a name="property-$gcCounterFileName"></a>$gcCounterFileName

```php
public mixed $gcCounterFileName = 'gc_counter.ajax.php'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 22](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L22).


### <a name="property-$gcLogFile"></a>$gcLogFile

```php
public mixed $gcLogFile = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 25](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L25).


### <a name="property-$gcLogFileName"></a>$gcLogFileName

```php
public mixed $gcLogFileName = 'gc_log.ajax.php'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 24](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L24).


### <a name="property-$lifeTime"></a>$lifeTime

```php
public mixed $lifeTime
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L14).


### <a name="property-$mTime"></a>$mTime

```php
public mixed $mTime = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 17](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L17).


### <a name="property-$sessionDir"></a>$sessionDir

```php
public mixed $sessionDir = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 18](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L18).


### <a name="property-$sessionFile"></a>$sessionFile

```php
public mixed $sessionFile = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 19](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L19).


Methods
-------


### <a name="method-Session"></a>Session

```php
mixed Session::Session()
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L65)




### <a name="method-__construct"></a>__construct

```php
mixed Session::__construct()
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L33)




### <a name="method-_gc"></a>_gc

```php
mixed Session::_gc()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L105)




### <a name="method-_log"></a>_log

```php
mixed Session::_log(\unknown_type $msg)
```

log action taken by the gc



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L189)


#### Arguments
* $msg **unknown_type**



### <a name="method-gc"></a>gc

```php
mixed Session::gc()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L80)




### <a name="method-getSessionDir"></a>getSessionDir

```php
string Session::getSessionDir()
```

get the current session directory



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L206)




### <a name="method-init"></a>init

```php
boolean Session::init()
```

session init



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.session.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/admin-dev/ajaxfilemanager/inc/class.session.php#L73)



