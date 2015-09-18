UploaderCore
===============






* Class name: UploaderCore
* Namespace: 



Constants
----------


### DEFAULT_MAX_SIZE

    const DEFAULT_MAX_SIZE = 10485760





Properties
----------


### $_check_file_size

    private mixed $_check_file_size





* Visibility: **private**


### $_accept_types

    private mixed $_accept_types





* Visibility: **private**


### $_files

    private mixed $_files





* Visibility: **private**


### $_max_size

    private mixed $_max_size





* Visibility: **private**


### $_name

    private mixed $_name





* Visibility: **private**


### $_save_path

    private mixed $_save_path





* Visibility: **private**


Methods
-------


### __construct

    mixed UploaderCore::__construct($name)





* Visibility: **public**


#### Arguments
* $name **mixed**



### setAcceptTypes

    mixed UploaderCore::setAcceptTypes($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getAcceptTypes

    mixed UploaderCore::getAcceptTypes()





* Visibility: **public**




### setCheckFileSize

    mixed UploaderCore::setCheckFileSize($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getFilePath

    mixed UploaderCore::getFilePath($file_name)





* Visibility: **public**


#### Arguments
* $file_name **mixed**



### getFiles

    mixed UploaderCore::getFiles()





* Visibility: **public**




### setMaxSize

    mixed UploaderCore::setMaxSize($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getMaxSize

    mixed UploaderCore::getMaxSize()





* Visibility: **public**




### setName

    mixed UploaderCore::setName($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getName

    mixed UploaderCore::getName()





* Visibility: **public**




### setSavePath

    mixed UploaderCore::setSavePath($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getPostMaxSizeBytes

    mixed UploaderCore::getPostMaxSizeBytes()





* Visibility: **public**




### getSavePath

    mixed UploaderCore::getSavePath()





* Visibility: **public**




### getUniqueFileName

    mixed UploaderCore::getUniqueFileName($prefix)





* Visibility: **public**


#### Arguments
* $prefix **mixed**



### checkFileSize

    mixed UploaderCore::checkFileSize()





* Visibility: **public**




### process

    mixed UploaderCore::process($dest)





* Visibility: **public**


#### Arguments
* $dest **mixed**



### upload

    mixed UploaderCore::upload($file, $dest)





* Visibility: **public**


#### Arguments
* $file **mixed**
* $dest **mixed**



### checkUploadError

    mixed UploaderCore::checkUploadError($error_code)





* Visibility: **protected**


#### Arguments
* $error_code **mixed**



### validate

    mixed UploaderCore::validate($file)





* Visibility: **protected**


#### Arguments
* $file **mixed**



### _getFileSize

    mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)





* Visibility: **protected**


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### _getServerVars

    mixed UploaderCore::_getServerVars($var)





* Visibility: **protected**


#### Arguments
* $var **mixed**



### _normalizeDirectory

    mixed UploaderCore::_normalizeDirectory($directory)





* Visibility: **protected**


#### Arguments
* $directory **mixed**


