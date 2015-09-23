Class AbstractLoggerCore
=====================





* Class name: AbstractLoggerCore
* This is an **abstract** class
* Source: [classes/log/AbstractLogger.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L28)


Contents
--------

### Constants

* [DEBUG](#constant-DEBUG)
* [ERROR](#constant-ERROR)
* [INFO](#constant-INFO)
* [WARNING](#constant-WARNING)

### Properties

* [$level](#property-$level)
* [$level_value](#property-$level_value)

### Methods

* [__construct](#method-__construct)
* [log](#method-log)
* [logDebug](#method-logDebug)
* [logError](#method-logError)
* [logInfo](#method-logInfo)
* [logMessage](#method-logMessage)
* [logWarning](#method-logWarning)


Constants
----------


### <a name="constant-DEBUG"></a>DEBUG

```php
const DEBUG = 0
```





* Source: [classes/log/AbstractLogger.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L38).


### <a name="constant-ERROR"></a>ERROR

```php
const ERROR = 3
```





* Source: [classes/log/AbstractLogger.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L41).


### <a name="constant-INFO"></a>INFO

```php
const INFO = 1
```





* Source: [classes/log/AbstractLogger.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L39).


### <a name="constant-WARNING"></a>WARNING

```php
const WARNING = 2
```





* Source: [classes/log/AbstractLogger.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L40).


Properties
----------


### <a name="property-$level"></a>$level

```php
public mixed $level
```





* Visibility: **public**
* Source: [classes/log/AbstractLogger.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L30).


### <a name="property-$level_value"></a>$level_value

```php
protected mixed $level_value = array(0 => 'DEBUG', 1 => 'INFO', 2 => 'WARNING', 3 => 'ERROR')
```





* Visibility: **protected**
* Source: [classes/log/AbstractLogger.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AbstractLoggerCore::__construct($level)
```





* Visibility: **public**
* Source: [classes/log/AbstractLogger.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L43)


#### Arguments
* $level **mixed**



### <a name="method-log"></a>log

```php
mixed AbstractLoggerCore::log($message, $level)
```

Check the level and log the message if needed



* Visibility: **public**
* Source: [classes/log/AbstractLogger.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L65)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-logDebug"></a>logDebug

```php
mixed AbstractLoggerCore::logDebug($message)
```

Log a debug message



* Visibility: **public**
* Source: [classes/log/AbstractLogger.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L76)


#### Arguments
* $message **mixed**



### <a name="method-logError"></a>logError

```php
mixed AbstractLoggerCore::logError($message)
```

Log an error message



* Visibility: **public**
* Source: [classes/log/AbstractLogger.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L106)


#### Arguments
* $message **mixed**



### <a name="method-logInfo"></a>logInfo

```php
mixed AbstractLoggerCore::logInfo($message)
```

Log an info message



* Visibility: **public**
* Source: [classes/log/AbstractLogger.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L86)


#### Arguments
* $message **mixed**



### <a name="method-logMessage"></a>logMessage

```php
mixed AbstractLoggerCore::logMessage($message, $level)
```

Log the message



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/log/AbstractLogger.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L57)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-logWarning"></a>logWarning

```php
mixed AbstractLoggerCore::logWarning($message)
```

Log a warning message



* Visibility: **public**
* Source: [classes/log/AbstractLogger.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/log/AbstractLogger.php#L96)


#### Arguments
* $message **mixed**


