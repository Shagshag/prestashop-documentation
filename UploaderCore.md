UploaderCore
===============






* Class name: UploaderCore
* Namespace: 

* This class is defined in [classes/Uploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#27)



Constants
----------


### DEFAULT_MAX_SIZE

    const DEFAULT_MAX_SIZE = 10485760



* This constant is defined in [classes/Uploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#29)


Properties
----------


### $_check_file_size

    private mixed $_check_file_size





* Visibility: **private**
* This property is defined in [classes/Uploader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#31)


### $_accept_types

    private mixed $_accept_types





* Visibility: **private**
* This property is defined in [classes/Uploader.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#32)


### $_files

    private mixed $_files





* Visibility: **private**
* This property is defined in [classes/Uploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#33)


### $_max_size

    private mixed $_max_size





* Visibility: **private**
* This property is defined in [classes/Uploader.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#34)


### $_name

    private mixed $_name





* Visibility: **private**
* This property is defined in [classes/Uploader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#35)


### $_save_path

    private mixed $_save_path





* Visibility: **private**
* This property is defined in [classes/Uploader.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#36)


Methods
-------


### __construct

    mixed UploaderCore::__construct($name)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#38)


#### Arguments
* $name **mixed**



### setAcceptTypes

    mixed UploaderCore::setAcceptTypes($value)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#45)


#### Arguments
* $value **mixed**



### getAcceptTypes

    mixed UploaderCore::getAcceptTypes()





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#51)




### setCheckFileSize

    mixed UploaderCore::setCheckFileSize($value)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#56)


#### Arguments
* $value **mixed**



### getFilePath

    mixed UploaderCore::getFilePath($file_name)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#62)


#### Arguments
* $file_name **mixed**



### getFiles

    mixed UploaderCore::getFiles()





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#71)




### setMaxSize

    mixed UploaderCore::setMaxSize($value)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#80)


#### Arguments
* $value **mixed**



### getMaxSize

    mixed UploaderCore::getMaxSize()





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#86)




### setName

    mixed UploaderCore::setName($value)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#95)


#### Arguments
* $value **mixed**



### getName

    mixed UploaderCore::getName()





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#101)




### setSavePath

    mixed UploaderCore::setSavePath($value)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#106)


#### Arguments
* $value **mixed**



### getPostMaxSizeBytes

    mixed UploaderCore::getPostMaxSizeBytes()





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#112)




### getSavePath

    mixed UploaderCore::getSavePath()





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#130)




### getUniqueFileName

    mixed UploaderCore::getUniqueFileName($prefix)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#139)


#### Arguments
* $prefix **mixed**



### checkFileSize

    mixed UploaderCore::checkFileSize()





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#144)




### process

    mixed UploaderCore::process($dest)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#149)


#### Arguments
* $dest **mixed**



### upload

    mixed UploaderCore::upload($file, $dest)





* Visibility: **public**
* This method is defined in [classes/Uploader.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#173)


#### Arguments
* $file **mixed**
* $dest **mixed**



### checkUploadError

    mixed UploaderCore::checkUploadError($error_code)





* Visibility: **protected**
* This method is defined in [classes/Uploader.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#203)


#### Arguments
* $error_code **mixed**



### validate

    mixed UploaderCore::validate($file)





* Visibility: **protected**
* This method is defined in [classes/Uploader.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#234)


#### Arguments
* $file **mixed**



### _getFileSize

    mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)





* Visibility: **protected**
* This method is defined in [classes/Uploader.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#266)


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### _getServerVars

    mixed UploaderCore::_getServerVars($var)





* Visibility: **protected**
* This method is defined in [classes/Uploader.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#275)


#### Arguments
* $var **mixed**



### _normalizeDirectory

    mixed UploaderCore::_normalizeDirectory($directory)





* Visibility: **protected**
* This method is defined in [classes/Uploader.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#280)


#### Arguments
* $directory **mixed**


