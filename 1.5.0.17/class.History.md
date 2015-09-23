Class History
=====================

class history
this class used to keep records of any changed to uploaded images under a session



* Class name: History
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 10](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L10)


Contents
--------


### Properties

* [$history](#property-$history)
* [$path](#property-$path)
* [$session](#property-$session)

### Methods

* [History](#method-History)
* [__construct](#method-__construct)
* [add](#method-add)
* [getLastestRestorable](#method-getLastestRestorable)
* [getNumRestorable](#method-getNumRestorable)
* [getOriginalImage](#method-getOriginalImage)
* [restore](#method-restore)




Properties
----------


### <a name="property-$history"></a>$history

```php
public mixed $history = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L12).


### <a name="property-$path"></a>$path

```php
public mixed $path = ''
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 13](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L13).


### <a name="property-$session"></a>$session

```php
public mixed $session = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L14).


Methods
-------


### <a name="method-History"></a>History

```php
mixed History::History(string $path, object $session)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L37)


#### Arguments
* $path **string** - the path to the image
* $session **object** - an instance of session class



### <a name="method-__construct"></a>__construct

```php
mixed History::__construct(string $path, object $session)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 21](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L21)


#### Arguments
* $path **string** - the path to the image
* $session **object** - an instance of session class



### <a name="method-add"></a>add

```php
mixed History::add(string $info)
```

keep tracks of each changes made to an image



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L48)


#### Arguments
* $info **string** - array(&#039;name&#039;, &#039;restorable&#039;, &#039;is_original&#039;)



### <a name="method-getLastestRestorable"></a>getLastestRestorable

```php
\return History::getLastestRestorable()
```

get the path of image which keep the lastest changes



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L85)




### <a name="method-getNumRestorable"></a>getNumRestorable

```php
array History::getNumRestorable()
```

get the lastest changes for restore



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L57)




### <a name="method-getOriginalImage"></a>getOriginalImage

```php
array History::getOriginalImage()
```

get the original image which is kept in the session folder



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L108)




### <a name="method-restore"></a>restore

```php
boolean History::restore()
```

remove the lastest restorable state



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.history.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/admin-dev/ajaxfilemanager/inc/class.history.php#L134)



