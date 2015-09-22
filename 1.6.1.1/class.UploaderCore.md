Class UploaderCore
=====================





* Class name: UploaderCore
* Source: [classes/Uploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L27)


Contents
--------

### Constants

* [DEFAULT_MAX_SIZE](#constant-DEFAULT_MAX_SIZE)

### Properties

* [$_accept_types](#property-$_accept_types)
* [$_check_file_size](#property-$_check_file_size)
* [$_files](#property-$_files)
* [$_max_size](#property-$_max_size)
* [$_name](#property-$_name)
* [$_save_path](#property-$_save_path)

### Methods

* [__construct](#method-__construct)
* [_getFileSize](#method-_getFileSize)
* [_getServerVars](#method-_getServerVars)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [checkFileSize](#method-checkFileSize)
* [checkUploadError](#method-checkUploadError)
* [getAcceptTypes](#method-getAcceptTypes)
* [getFilePath](#method-getFilePath)
* [getFiles](#method-getFiles)
* [getMaxSize](#method-getMaxSize)
* [getName](#method-getName)
* [getPostMaxSizeBytes](#method-getPostMaxSizeBytes)
* [getSavePath](#method-getSavePath)
* [getUniqueFileName](#method-getUniqueFileName)
* [process](#method-process)
* [setAcceptTypes](#method-setAcceptTypes)
* [setCheckFileSize](#method-setCheckFileSize)
* [setMaxSize](#method-setMaxSize)
* [setName](#method-setName)
* [setSavePath](#method-setSavePath)
* [upload](#method-upload)
* [validate](#method-validate)


Constants
----------


### <a name="constant-DEFAULT_MAX_SIZE"></a>DEFAULT_MAX_SIZE

```php
const DEFAULT_MAX_SIZE = 10485760
```





* Source: [classes/Uploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L29).


Properties
----------


### <a name="property-$_accept_types"></a>$_accept_types

```php
private mixed $_accept_types
```





* Visibility: **private**
* Source: [classes/Uploader.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L32).


### <a name="property-$_check_file_size"></a>$_check_file_size

```php
private mixed $_check_file_size
```





* Visibility: **private**
* Source: [classes/Uploader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L31).


### <a name="property-$_files"></a>$_files

```php
private mixed $_files
```





* Visibility: **private**
* Source: [classes/Uploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L33).


### <a name="property-$_max_size"></a>$_max_size

```php
private mixed $_max_size
```





* Visibility: **private**
* Source: [classes/Uploader.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L34).


### <a name="property-$_name"></a>$_name

```php
private mixed $_name
```





* Visibility: **private**
* Source: [classes/Uploader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L35).


### <a name="property-$_save_path"></a>$_save_path

```php
private mixed $_save_path
```





* Visibility: **private**
* Source: [classes/Uploader.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed UploaderCore::__construct($name)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L38)


#### Arguments
* $name **mixed**



### <a name="method-_getFileSize"></a>_getFileSize

```php
mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L266)


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### <a name="method-_getServerVars"></a>_getServerVars

```php
mixed UploaderCore::_getServerVars($var)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L275)


#### Arguments
* $var **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed UploaderCore::_normalizeDirectory($directory)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L280)


#### Arguments
* $directory **mixed**



### <a name="method-checkFileSize"></a>checkFileSize

```php
mixed UploaderCore::checkFileSize()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L144)




### <a name="method-checkUploadError"></a>checkUploadError

```php
mixed UploaderCore::checkUploadError($error_code)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L203)


#### Arguments
* $error_code **mixed**



### <a name="method-getAcceptTypes"></a>getAcceptTypes

```php
mixed UploaderCore::getAcceptTypes()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L51)




### <a name="method-getFilePath"></a>getFilePath

```php
mixed UploaderCore::getFilePath($file_name)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L62)


#### Arguments
* $file_name **mixed**



### <a name="method-getFiles"></a>getFiles

```php
mixed UploaderCore::getFiles()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L71)




### <a name="method-getMaxSize"></a>getMaxSize

```php
mixed UploaderCore::getMaxSize()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L86)




### <a name="method-getName"></a>getName

```php
mixed UploaderCore::getName()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L101)




### <a name="method-getPostMaxSizeBytes"></a>getPostMaxSizeBytes

```php
mixed UploaderCore::getPostMaxSizeBytes()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L112)




### <a name="method-getSavePath"></a>getSavePath

```php
mixed UploaderCore::getSavePath()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L130)




### <a name="method-getUniqueFileName"></a>getUniqueFileName

```php
mixed UploaderCore::getUniqueFileName($prefix)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L139)


#### Arguments
* $prefix **mixed**



### <a name="method-process"></a>process

```php
mixed UploaderCore::process($dest)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L149)


#### Arguments
* $dest **mixed**



### <a name="method-setAcceptTypes"></a>setAcceptTypes

```php
mixed UploaderCore::setAcceptTypes($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L45)


#### Arguments
* $value **mixed**



### <a name="method-setCheckFileSize"></a>setCheckFileSize

```php
mixed UploaderCore::setCheckFileSize($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L56)


#### Arguments
* $value **mixed**



### <a name="method-setMaxSize"></a>setMaxSize

```php
mixed UploaderCore::setMaxSize($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L80)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed UploaderCore::setName($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L95)


#### Arguments
* $value **mixed**



### <a name="method-setSavePath"></a>setSavePath

```php
mixed UploaderCore::setSavePath($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L106)


#### Arguments
* $value **mixed**



### <a name="method-upload"></a>upload

```php
mixed UploaderCore::upload($file, $dest)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L173)


#### Arguments
* $file **mixed**
* $dest **mixed**



### <a name="method-validate"></a>validate

```php
mixed UploaderCore::validate($file)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Uploader.php#L234)


#### Arguments
* $file **mixed**


