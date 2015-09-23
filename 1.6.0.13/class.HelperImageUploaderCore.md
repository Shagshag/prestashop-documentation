Class HelperImageUploaderCore
=====================





* Class name: HelperImageUploaderCore
* Parent class: [HelperUploader](class.HelperUploaderCore.md)
* Source: [classes/helper/HelperImageUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperImageUploader.php#L27)


Contents
--------


### Properties

* [$_template](#property-$_template)

### Methods

* [__construct](#method-__construct)
* [_getFileSize](#method-_getFileSize)
* [_getServerVars](#method-_getServerVars)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [checkFileSize](#method-checkFileSize)
* [checkUploadError](#method-checkUploadError)
* [getAcceptTypes](#method-getAcceptTypes)
* [getContext](#method-getContext)
* [getDropZone](#method-getDropZone)
* [getFilePath](#method-getFilePath)
* [getFiles](#method-getFiles)
* [getId](#method-getId)
* [getMaxFiles](#method-getMaxFiles)
* [getMaxSize](#method-getMaxSize)
* [getName](#method-getName)
* [getPostMaxSize](#method-getPostMaxSize)
* [getPostMaxSizeBytes](#method-getPostMaxSizeBytes)
* [getSavePath](#method-getSavePath)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [getTitle](#method-getTitle)
* [getUniqueFileName](#method-getUniqueFileName)
* [getUrl](#method-getUrl)
* [isMultiple](#method-isMultiple)
* [process](#method-process)
* [render](#method-render)
* [setAcceptTypes](#method-setAcceptTypes)
* [setCheckFileSize](#method-setCheckFileSize)
* [setContext](#method-setContext)
* [setDropZone](#method-setDropZone)
* [setFiles](#method-setFiles)
* [setId](#method-setId)
* [setMaxFiles](#method-setMaxFiles)
* [setMaxSize](#method-setMaxSize)
* [setMultiple](#method-setMultiple)
* [setName](#method-setName)
* [setPostMaxSize](#method-setPostMaxSize)
* [setSavePath](#method-setSavePath)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)
* [setTitle](#method-setTitle)
* [setUrl](#method-setUrl)
* [setUseAjax](#method-setUseAjax)
* [upload](#method-upload)
* [useAjax](#method-useAjax)
* [validate](#method-validate)




Properties
----------


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* This property is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L44).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed UploaderCore::__construct($name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L38)


#### Arguments
* $name **mixed**



### <a name="method-_getFileSize"></a>_getFileSize

```php
mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L272)


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### <a name="method-_getServerVars"></a>_getServerVars

```php
mixed UploaderCore::_getServerVars($var)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L279)


#### Arguments
* $var **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed UploaderCore::_normalizeDirectory($directory)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L284)


#### Arguments
* $directory **mixed**



### <a name="method-checkFileSize"></a>checkFileSize

```php
mixed UploaderCore::checkFileSize()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L140)




### <a name="method-checkUploadError"></a>checkUploadError

```php
mixed UploaderCore::checkUploadError($error_code)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L204)


#### Arguments
* $error_code **mixed**



### <a name="method-getAcceptTypes"></a>getAcceptTypes

```php
mixed UploaderCore::getAcceptTypes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L51)




### <a name="method-getContext"></a>getContext

```php
mixed HelperUploaderCore::getContext()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L56)




### <a name="method-getDropZone"></a>getDropZone

```php
mixed HelperUploaderCore::getDropZone()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L70)




### <a name="method-getFilePath"></a>getFilePath

```php
mixed UploaderCore::getFilePath($file_name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L62)


#### Arguments
* $file_name **mixed**



### <a name="method-getFiles"></a>getFiles

```php
mixed HelperUploaderCore::getFiles()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L98)




### <a name="method-getId"></a>getId

```php
mixed HelperUploaderCore::getId()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L84)




### <a name="method-getMaxFiles"></a>getMaxFiles

```php
mixed HelperUploaderCore::getMaxFiles()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L112)




### <a name="method-getMaxSize"></a>getMaxSize

```php
mixed UploaderCore::getMaxSize()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L84)




### <a name="method-getName"></a>getName

```php
mixed HelperUploaderCore::getName()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L129)




### <a name="method-getPostMaxSize"></a>getPostMaxSize

```php
mixed HelperUploaderCore::getPostMaxSize()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L141)




### <a name="method-getPostMaxSizeBytes"></a>getPostMaxSizeBytes

```php
mixed UploaderCore::getPostMaxSizeBytes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L109)




### <a name="method-getSavePath"></a>getSavePath

```php
mixed UploaderCore::getSavePath()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L127)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperUploaderCore::getTemplate()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L155)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed HelperUploaderCore::getTemplateDirectory()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L169)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperUploaderCore::getTemplateFile($template)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L177)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperUploaderCore::getTitle()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L209)




### <a name="method-getUniqueFileName"></a>getUniqueFileName

```php
mixed UploaderCore::getUniqueFileName($prefix)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L135)


#### Arguments
* $prefix **mixed**



### <a name="method-getUrl"></a>getUrl

```php
mixed HelperUploaderCore::getUrl()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L220)




### <a name="method-isMultiple"></a>isMultiple

```php
mixed HelperUploaderCore::isMultiple()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L231)




### <a name="method-process"></a>process

```php
mixed UploaderCore::process($dest)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L145)


#### Arguments
* $dest **mixed**



### <a name="method-render"></a>render

```php
mixed HelperUploaderCore::render()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L236)




### <a name="method-setAcceptTypes"></a>setAcceptTypes

```php
mixed UploaderCore::setAcceptTypes($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L45)


#### Arguments
* $value **mixed**



### <a name="method-setCheckFileSize"></a>setCheckFileSize

```php
mixed UploaderCore::setCheckFileSize($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L56)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperUploaderCore::setContext($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L50)


#### Arguments
* $value **mixed**



### <a name="method-setDropZone"></a>setDropZone

```php
mixed HelperUploaderCore::setDropZone($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L64)


#### Arguments
* $value **mixed**



### <a name="method-setFiles"></a>setFiles

```php
mixed HelperUploaderCore::setFiles($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L92)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperUploaderCore::setId($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L78)


#### Arguments
* $value **mixed**



### <a name="method-setMaxFiles"></a>setMaxFiles

```php
mixed HelperUploaderCore::setMaxFiles($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L106)


#### Arguments
* $value **mixed**



### <a name="method-setMaxSize"></a>setMaxSize

```php
mixed UploaderCore::setMaxSize($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L78)


#### Arguments
* $value **mixed**



### <a name="method-setMultiple"></a>setMultiple

```php
mixed HelperUploaderCore::setMultiple($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L117)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed HelperUploaderCore::setName($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L123)


#### Arguments
* $value **mixed**



### <a name="method-setPostMaxSize"></a>setPostMaxSize

```php
mixed HelperUploaderCore::setPostMaxSize($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L134)


#### Arguments
* $value **mixed**



### <a name="method-setSavePath"></a>setSavePath

```php
mixed UploaderCore::setSavePath($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L103)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperUploaderCore::setTemplate($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L149)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed HelperUploaderCore::setTemplateDirectory($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L163)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperUploaderCore::setTitle($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L203)


#### Arguments
* $value **mixed**



### <a name="method-setUrl"></a>setUrl

```php
mixed HelperUploaderCore::setUrl($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L214)


#### Arguments
* $value **mixed**



### <a name="method-setUseAjax"></a>setUseAjax

```php
mixed HelperUploaderCore::setUseAjax($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L225)


#### Arguments
* $value **mixed**



### <a name="method-upload"></a>upload

```php
mixed UploaderCore::upload($file, $dest)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L172)


#### Arguments
* $file **mixed**
* $dest **mixed**



### <a name="method-useAjax"></a>useAjax

```php
mixed HelperUploaderCore::useAjax()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperUploader.php#L280)




### <a name="method-validate"></a>validate

```php
mixed UploaderCore::validate($file)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/Uploader.php#L236)


#### Arguments
* $file **mixed**


