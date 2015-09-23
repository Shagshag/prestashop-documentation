Class UploaderCore
=====================





* Class name: UploaderCore
* Source: [classes/Uploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L27)


Contents
--------

### Constants

* [DEFAULT_MAX_SIZE](#constant-DEFAULT_MAX_SIZE)

### Properties

* [$_accept_types](#property-$_accept_types)
* [$_files](#property-$_files)
* [$_max_size](#property-$_max_size)
* [$_name](#property-$_name)
* [$_save_path](#property-$_save_path)

### Methods

* [__construct](#method-__construct)
* [_getFileSize](#method-_getFileSize)
* [_getServerVars](#method-_getServerVars)
* [_normalizeDirectory](#method-_normalizeDirectory)
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





* Source: [classes/Uploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L29).


Properties
----------


### <a name="property-$_accept_types"></a>$_accept_types

```php
private mixed $_accept_types
```





* Visibility: **private**
* Source: [classes/Uploader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L31).


### <a name="property-$_files"></a>$_files

```php
private mixed $_files
```





* Visibility: **private**
* Source: [classes/Uploader.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L32).


### <a name="property-$_max_size"></a>$_max_size

```php
private mixed $_max_size
```





* Visibility: **private**
* Source: [classes/Uploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L33).


### <a name="property-$_name"></a>$_name

```php
private mixed $_name
```





* Visibility: **private**
* Source: [classes/Uploader.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L34).


### <a name="property-$_save_path"></a>$_save_path

```php
private mixed $_save_path
```





* Visibility: **private**
* Source: [classes/Uploader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L35).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed UploaderCore::__construct($name)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L37)


#### Arguments
* $name **mixed**



### <a name="method-_getFileSize"></a>_getFileSize

```php
mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L259)


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### <a name="method-_getServerVars"></a>_getServerVars

```php
mixed UploaderCore::_getServerVars($var)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L266)


#### Arguments
* $var **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed UploaderCore::_normalizeDirectory($directory)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L271)


#### Arguments
* $directory **mixed**



### <a name="method-checkUploadError"></a>checkUploadError

```php
mixed UploaderCore::checkUploadError($error_code)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L191)


#### Arguments
* $error_code **mixed**



### <a name="method-getAcceptTypes"></a>getAcceptTypes

```php
mixed UploaderCore::getAcceptTypes()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L49)




### <a name="method-getFilePath"></a>getFilePath

```php
mixed UploaderCore::getFilePath($file_name)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L54)


#### Arguments
* $file_name **mixed**



### <a name="method-getFiles"></a>getFiles

```php
mixed UploaderCore::getFiles()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L62)




### <a name="method-getMaxSize"></a>getMaxSize

```php
mixed UploaderCore::getMaxSize()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L76)




### <a name="method-getName"></a>getName

```php
mixed UploaderCore::getName()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L90)




### <a name="method-getPostMaxSizeBytes"></a>getPostMaxSizeBytes

```php
mixed UploaderCore::getPostMaxSizeBytes()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L101)




### <a name="method-getSavePath"></a>getSavePath

```php
mixed UploaderCore::getSavePath()
```





* Visibility: **public**
* Source: [classes/Uploader.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L119)




### <a name="method-getUniqueFileName"></a>getUniqueFileName

```php
mixed UploaderCore::getUniqueFileName($prefix)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L127)


#### Arguments
* $prefix **mixed**



### <a name="method-process"></a>process

```php
mixed UploaderCore::process($dest)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L132)


#### Arguments
* $dest **mixed**



### <a name="method-setAcceptTypes"></a>setAcceptTypes

```php
mixed UploaderCore::setAcceptTypes($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L43)


#### Arguments
* $value **mixed**



### <a name="method-setMaxSize"></a>setMaxSize

```php
mixed UploaderCore::setMaxSize($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L70)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed UploaderCore::setName($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L84)


#### Arguments
* $value **mixed**



### <a name="method-setSavePath"></a>setSavePath

```php
mixed UploaderCore::setSavePath($value)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L95)


#### Arguments
* $value **mixed**



### <a name="method-upload"></a>upload

```php
mixed UploaderCore::upload($file, $dest)
```





* Visibility: **public**
* Source: [classes/Uploader.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L159)


#### Arguments
* $file **mixed**
* $dest **mixed**



### <a name="method-validate"></a>validate

```php
mixed UploaderCore::validate($file)
```





* Visibility: **protected**
* Source: [classes/Uploader.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Uploader.php#L223)


#### Arguments
* $file **mixed**


