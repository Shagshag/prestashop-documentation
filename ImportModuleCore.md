ImportModuleCore
===============

ImportModule class, ImportModule.php
Import module management




* Class name: ImportModuleCore
* Namespace: 
* This is an **abstract** class
* Parent class: Module





Properties
----------


### $_link

    protected mixed $_link = null





* Visibility: **protected**


### $server

    public mixed $server





* Visibility: **public**


### $user

    public mixed $user





* Visibility: **public**


### $passwd

    public mixed $passwd





* Visibility: **public**


### $database

    public mixed $database





* Visibility: **public**


### $prefix

    public string $prefix





* Visibility: **public**


Methods
-------


### __destruct

    mixed ImportModuleCore::__destruct()





* Visibility: **public**




### initDatabaseConnection

    mixed ImportModuleCore::initDatabaseConnection()





* Visibility: **protected**




### ExecuteS

    mixed ImportModuleCore::ExecuteS($query)





* Visibility: **public**


#### Arguments
* $query **mixed**



### Execute

    mixed ImportModuleCore::Execute($query)





* Visibility: **public**


#### Arguments
* $query **mixed**



### getValue

    mixed ImportModuleCore::getValue($query)





* Visibility: **public**


#### Arguments
* $query **mixed**



### getImportModulesOnDisk

    mixed ImportModuleCore::getImportModulesOnDisk()





* Visibility: **public**
* This method is **static**.




### getDefaultIdLang

    mixed ImportModuleCore::getDefaultIdLang()





* Visibility: **public**
* This method is **abstract**.



