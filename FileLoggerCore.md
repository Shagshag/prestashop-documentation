FileLoggerCore
===============






* Class name: FileLoggerCore
* Namespace: 
* Parent class: AbstractLogger





Properties
----------


### $filename

    protected mixed $filename = ''





* Visibility: **protected**


Methods
-------


### logMessage

    mixed FileLoggerCore::logMessage($message, $level)

Write the message in the log file



* Visibility: **protected**


#### Arguments
* $message **mixed**
* $level **mixed**



### setFilename

    mixed FileLoggerCore::setFilename(string $filename)

Check if the specified filename is writable and set the filename



* Visibility: **public**


#### Arguments
* $filename **string**



### getFilename

    mixed FileLoggerCore::getFilename()

Log the message



* Visibility: **public**



