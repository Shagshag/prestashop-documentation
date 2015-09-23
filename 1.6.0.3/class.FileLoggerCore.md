Class FileLoggerCore
=====================





* Class name: FileLoggerCore
* Parent class: [AbstractLogger](class.AbstractLoggerCore.md)
* Source: [classes/log/FileLogger.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/log/FileLogger.php#L27)


Contents
--------


### Properties

* [$filename](#property-$filename)

### Methods

* [getFilename](#method-getFilename)
* [logMessage](#method-logMessage)
* [setFilename](#method-setFilename)




Properties
----------


### <a name="property-$filename"></a>$filename

```php
protected mixed $filename = ''
```





* Visibility: **protected**
* Source: [classes/log/FileLogger.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/log/FileLogger.php#L29).


Methods
-------


### <a name="method-getFilename"></a>getFilename

```php
mixed FileLoggerCore::getFilename()
```

Log the message



* Visibility: **public**
* Source: [classes/log/FileLogger.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/log/FileLogger.php#L62)




### <a name="method-logMessage"></a>logMessage

```php
mixed FileLoggerCore::logMessage($message, $level)
```

Write the message in the log file



* Visibility: **protected**
* Source: [classes/log/FileLogger.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/log/FileLogger.php#L37)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-setFilename"></a>setFilename

```php
mixed FileLoggerCore::setFilename($filename)
```

Check if the specified filename is writable and set the filename



* Visibility: **public**
* Source: [classes/log/FileLogger.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/log/FileLogger.php#L48)


#### Arguments
* $filename **mixed**


