FileLoggerCore
===============






* Class name: FileLoggerCore
* Parent class: [AbstractLogger](AbstractLoggerCore)
* This class is defined in [classes/log/FileLogger.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L27)





Properties
----------

* [$filename](#property-$filename)

Methods
-------
* [logMessage](#method-logMessage)
* [setFilename](#method-setFilename)
* [getFilename](#method-getFilename)




Properties
----------


### <a name="property-$filename"></a>$filename

    protected mixed $filename = ''





* Visibility: **protected**
* This property is defined in [classes/log/FileLogger.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L29)


Methods
-------


### <a name="method-logMessage"></a>logMessage

    mixed FileLoggerCore::logMessage($message, $level)

Write the message in the log file



* Visibility: **protected**
* This method is defined in [classes/log/FileLogger.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L37)


#### Arguments
* $message **mixed**
* $level **mixed**



### <a name="method-setFilename"></a>setFilename

    mixed FileLoggerCore::setFilename(string $filename)

Check if the specified filename is writable and set the filename



* Visibility: **public**
* This method is defined in [classes/log/FileLogger.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L51)


#### Arguments
* $filename **string**



### <a name="method-getFilename"></a>getFilename

    mixed FileLoggerCore::getFilename()

Log the message



* Visibility: **public**
* This method is defined in [classes/log/FileLogger.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/log/FileLogger.php#L66)



