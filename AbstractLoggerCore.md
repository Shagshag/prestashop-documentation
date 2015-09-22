AbstractLoggerCore
===============






* Class name: AbstractLoggerCore
* This is an **abstract** class
* This class is defined in [classes/log/AbstractLogger.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L27)



Constants
----------

* [DEBUG](#constant-DEBUG)
* [INFO](#constant-INFO)
* [WARNING](#constant-WARNING)
* [ERROR](#constant-ERROR)

Properties
----------

* [$level](#property-$level)
* [$level_value](#property-$level_value)

Methods
-------
* [__construct](#method-__construct)
* [logMessage](#method-logMessage)
* [log](#method-log)
* [logDebug](#method-logDebug)
* [logInfo](#method-logInfo)
* [logWarning](#method-logWarning)
* [logError](#method-logError)


Constants
----------


### <a name="constant-DEBUG"></a>DEBUG

    const DEBUG = 0



* This constant is defined in [classes/log/AbstractLogger.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L37)


### <a name="constant-INFO"></a>INFO

    const INFO = 1



* This constant is defined in [classes/log/AbstractLogger.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L38)


### <a name="constant-WARNING"></a>WARNING

    const WARNING = 2



* This constant is defined in [classes/log/AbstractLogger.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L39)


### <a name="constant-ERROR"></a>ERROR

    const ERROR = 3



* This constant is defined in [classes/log/AbstractLogger.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L40)


Properties
----------


### <a name="property-$level"></a>$level

    public mixed $level





* Visibility: **public**
* This property is defined in [classes/log/AbstractLogger.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L29)


### <a name="property-$level_value"></a>$level_value

    protected mixed $level_value = array(0 => 'DEBUG', 1 => 'INFO', 2 => 'WARNING', 3 => 'ERROR')





* Visibility: **protected**
* This property is defined in [classes/log/AbstractLogger.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AbstractLoggerCore::__construct($level)





* Visibility: **public**
* This method is defined in [classes/log/AbstractLogger.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L42)


#### Arguments
* $level **mixed**



### <a name="method-logMessage"></a>logMessage

    mixed AbstractLoggerCore::logMessage($message, $level)

Log the message



* Visibility: **protected**
* This method is **abstract**.
* This method is defined in [classes/log/AbstractLogger.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L57)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-log"></a>log

    mixed AbstractLoggerCore::log($message, $level)

Check the level and log the message if needed



* Visibility: **public**
* This method is defined in [classes/log/AbstractLogger.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L65)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-logDebug"></a>logDebug

    mixed AbstractLoggerCore::logDebug($message)

Log a debug message



* Visibility: **public**
* This method is defined in [classes/log/AbstractLogger.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L77)


#### Arguments
* $message **mixed**



### <a name="method-logInfo"></a>logInfo

    mixed AbstractLoggerCore::logInfo($message)

Log an info message



* Visibility: **public**
* This method is defined in [classes/log/AbstractLogger.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L87)


#### Arguments
* $message **mixed**



### <a name="method-logWarning"></a>logWarning

    mixed AbstractLoggerCore::logWarning($message)

Log a warning message



* Visibility: **public**
* This method is defined in [classes/log/AbstractLogger.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L97)


#### Arguments
* $message **mixed**



### <a name="method-logError"></a>logError

    mixed AbstractLoggerCore::logError($message)

Log an error message



* Visibility: **public**
* This method is defined in [classes/log/AbstractLogger.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/AbstractLogger.php#L107)


#### Arguments
* $message **mixed**


