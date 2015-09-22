AbstractLoggerCore
===============






* Class name: AbstractLoggerCore
* Namespace: 
* This is an **abstract** class
* This class is defined in classes\log\AbstractLogger.php line 27



Constants
----------


### DEBUG

    const DEBUG = 0



* This constant is defined in classes\log\AbstractLogger.php line 37


### INFO

    const INFO = 1



* This constant is defined in classes\log\AbstractLogger.php line 38


### WARNING

    const WARNING = 2



* This constant is defined in classes\log\AbstractLogger.php line 39


### ERROR

    const ERROR = 3



* This constant is defined in classes\log\AbstractLogger.php line 40


Properties
----------


### $level

    public mixed $level





* Visibility: **public**
* This property is defined in classes\log\AbstractLogger.php line 29


### $level_value

    protected mixed $level_value = array(0 => 'DEBUG', 1 => 'INFO', 2 => 'WARNING', 3 => 'ERROR')





* Visibility: **protected**
* This property is defined in classes\log\AbstractLogger.php line 30


Methods
-------


### __construct

    mixed AbstractLoggerCore::__construct($level)





* Visibility: **public**
* This method is defined in classes\log\AbstractLogger.php line 42


#### Arguments
* $level **mixed**



### logMessage

    mixed AbstractLoggerCore::logMessage($message, $level)

Log the message



* Visibility: **protected**
* This method is **abstract**.
* This method is defined in classes\log\AbstractLogger.php line 57


#### Arguments
* $message **mixed**
* $level **mixed**



### log

    mixed AbstractLoggerCore::log($message, $level)

Check the level and log the message if needed



* Visibility: **public**
* This method is defined in classes\log\AbstractLogger.php line 65


#### Arguments
* $message **mixed**
* $level **mixed**



### logDebug

    mixed AbstractLoggerCore::logDebug($message)

Log a debug message



* Visibility: **public**
* This method is defined in classes\log\AbstractLogger.php line 77


#### Arguments
* $message **mixed**



### logInfo

    mixed AbstractLoggerCore::logInfo($message)

Log an info message



* Visibility: **public**
* This method is defined in classes\log\AbstractLogger.php line 87


#### Arguments
* $message **mixed**



### logWarning

    mixed AbstractLoggerCore::logWarning($message)

Log a warning message



* Visibility: **public**
* This method is defined in classes\log\AbstractLogger.php line 97


#### Arguments
* $message **mixed**



### logError

    mixed AbstractLoggerCore::logError($message)

Log an error message



* Visibility: **public**
* This method is defined in classes\log\AbstractLogger.php line 107


#### Arguments
* $message **mixed**


