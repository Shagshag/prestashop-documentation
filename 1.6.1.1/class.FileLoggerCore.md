Class FileLoggerCore
=====================





* Class name: FileLoggerCore
* Parent class: [AbstractLogger](class.AbstractLoggerCore.md)
* Source: [classes/log/FileLogger.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L27)



Properties
----------

* [$filename](#property-$filename)

Methods
-------
* [getFilename](#method-getFilename)
* [logMessage](#method-logMessage)
* [setFilename](#method-setFilename)




Properties
----------


### <a name="property-$filename"></a>$filename

    protected mixed $filename = ''





* Visibility: **protected**
* Source: [classes/log/FileLogger.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L29)


Methods
-------


### <a name="method-getFilename"></a>getFilename

    mixed FileLoggerCore::getFilename()

Log the message



* Visibility: **public**
* Source: [classes/log/FileLogger.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L66)




### <a name="method-logMessage"></a>logMessage

    mixed FileLoggerCore::logMessage($message, $level)

Write the message in the log file



* Visibility: **protected**
* Source: [classes/log/FileLogger.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L37)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-setFilename"></a>setFilename

    mixed FileLoggerCore::setFilename(string $filename)

Check if the specified filename is writable and set the filename



* Visibility: **public**
* Source: [classes/log/FileLogger.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L51)


#### Arguments
* $filename **string**


