AbstractLoggerCore
===============






* Class name: AbstractLoggerCore
* Namespace: 
* This is an **abstract** class



Constants
----------


### DEBUG

    const DEBUG = 0





### INFO

    const INFO = 1





### WARNING

    const WARNING = 2





### ERROR

    const ERROR = 3





Properties
----------


### $level

    public mixed $level





* Visibility: **public**


### $level_value

    protected mixed $level_value = array(0 => 'DEBUG', 1 => 'INFO', 2 => 'WARNING', 3 => 'ERROR')





* Visibility: **protected**


Methods
-------


### __construct

    mixed AbstractLoggerCore::__construct($level)





* Visibility: **public**


#### Arguments
* $level **mixed**



### logMessage

    mixed AbstractLoggerCore::logMessage($message, $level)

Log the message



* Visibility: **protected**
* This method is **abstract**.


#### Arguments
* $message **mixed**
* $level **mixed**



### log

    mixed AbstractLoggerCore::log($message, $level)

Check the level and log the message if needed



* Visibility: **public**


#### Arguments
* $message **mixed**
* $level **mixed**



### logDebug

    mixed AbstractLoggerCore::logDebug($message)

Log a debug message



* Visibility: **public**


#### Arguments
* $message **mixed**



### logInfo

    mixed AbstractLoggerCore::logInfo($message)

Log an info message



* Visibility: **public**


#### Arguments
* $message **mixed**



### logWarning

    mixed AbstractLoggerCore::logWarning($message)

Log a warning message



* Visibility: **public**


#### Arguments
* $message **mixed**



### logError

    mixed AbstractLoggerCore::logError($message)

Log an error message



* Visibility: **public**


#### Arguments
* $message **mixed**


