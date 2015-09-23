Class FileLoggerCore
=====================





* Class name: FileLoggerCore
* Parent class: [AbstractLogger](class.AbstractLoggerCore.md)
* Source: [classes/log/FileLogger.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/FileLogger.php#L27)


Contents
--------


### Properties

* [$filename](#property-$filename)
* [$level](#property-$level)
* [$level_value](#property-$level_value)

### Methods

* [__construct](#method-__construct)
* [getFilename](#method-getFilename)
* [log](#method-log)
* [logDebug](#method-logDebug)
* [logError](#method-logError)
* [logInfo](#method-logInfo)
* [logMessage](#method-logMessage)
* [logWarning](#method-logWarning)
* [setFilename](#method-setFilename)




Properties
----------


### <a name="property-$filename"></a>$filename

```php
protected mixed $filename = ''
```





* Visibility: **protected**
* Source: [classes/log/FileLogger.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/FileLogger.php#L29).


### <a name="property-$level"></a>$level

```php
public mixed $level
```





* Visibility: **public**
* This property is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L29).


### <a name="property-$level_value"></a>$level_value

```php
protected mixed $level_value = array(0 => 'DEBUG', 1 => 'INFO', 2 => 'WARNING', 3 => 'ERROR')
```





* Visibility: **protected**
* This property is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AbstractLoggerCore::__construct($level)
```





* Visibility: **public**
* This method is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L42)


#### Arguments
* $level **mixed**



### <a name="method-getFilename"></a>getFilename

```php
mixed FileLoggerCore::getFilename()
```

Log the message



* Visibility: **public**
* Source: [classes/log/FileLogger.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/FileLogger.php#L62)




### <a name="method-log"></a>log

```php
mixed AbstractLoggerCore::log($message, $level)
```

Check the level and log the message if needed



* Visibility: **public**
* This method is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L64)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-logDebug"></a>logDebug

```php
mixed AbstractLoggerCore::logDebug($message)
```

Log a debug message



* Visibility: **public**
* This method is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L75)


#### Arguments
* $message **mixed**



### <a name="method-logError"></a>logError

```php
mixed AbstractLoggerCore::logError($message)
```

Log an error message



* Visibility: **public**
* This method is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L105)


#### Arguments
* $message **mixed**



### <a name="method-logInfo"></a>logInfo

```php
mixed AbstractLoggerCore::logInfo($message)
```

Log an info message



* Visibility: **public**
* This method is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L85)


#### Arguments
* $message **mixed**



### <a name="method-logMessage"></a>logMessage

```php
mixed FileLoggerCore::logMessage($message, $level)
```

Write the message in the log file



* Visibility: **protected**
* Source: [classes/log/FileLogger.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/FileLogger.php#L37)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-logWarning"></a>logWarning

```php
mixed AbstractLoggerCore::logWarning($message)
```

Log a warning message



* Visibility: **public**
* This method is defined by [AbstractLoggerCore](class.AbstractLoggerCore.md).
* Source: [classes/log/AbstractLogger.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/AbstractLogger.php#L95)


#### Arguments
* $message **mixed**



### <a name="method-setFilename"></a>setFilename

```php
mixed FileLoggerCore::setFilename($filename)
```

Check if the specified filename is writable and set the filename



* Visibility: **public**
* Source: [classes/log/FileLogger.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/log/FileLogger.php#L48)


#### Arguments
* $filename **mixed**


