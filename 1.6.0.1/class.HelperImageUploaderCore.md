Class HelperImageUploaderCore
=====================





* Class name: HelperImageUploaderCore
* Parent class: [HelperUploader](class.HelperUploaderCore.md)
* Source: [classes/helper/HelperImageUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperImageUploader.php#L27)


Contents
--------


### Properties

* [$_template](#property-$_template)

### Methods

* [__construct](#method-__construct)
* [_getFileSize](#method-_getFileSize)
* [_getServerVars](#method-_getServerVars)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [getAcceptTypes](#method-getAcceptTypes)
* [getContext](#method-getContext)
* [getFilePath](#method-getFilePath)
* [getFiles](#method-getFiles)
* [getId](#method-getId)
* [getMaxFiles](#method-getMaxFiles)
* [getMaxSize](#method-getMaxSize)
* [getName](#method-getName)
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
* [setContext](#method-setContext)
* [setFiles](#method-setFiles)
* [setId](#method-setId)
* [setMaxFiles](#method-setMaxFiles)
* [setMaxSize](#method-setMaxSize)
* [setMultiple](#method-setMultiple)
* [setName](#method-setName)
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
* Source: [classes/helper/HelperUploader.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L42).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed UploaderCore::__construct($name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L37)


#### Arguments
* $name **mixed**



### <a name="method-_getFileSize"></a>_getFileSize

```php
mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L217)


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### <a name="method-_getServerVars"></a>_getServerVars

```php
mixed UploaderCore::_getServerVars($var)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L224)


#### Arguments
* $var **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed UploaderCore::_normalizeDirectory($directory)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L229)


#### Arguments
* $directory **mixed**



### <a name="method-getAcceptTypes"></a>getAcceptTypes

```php
mixed UploaderCore::getAcceptTypes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L49)




### <a name="method-getContext"></a>getContext

```php
mixed HelperUploaderCore::getContext()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L54)




### <a name="method-getFilePath"></a>getFilePath

```php
mixed UploaderCore::getFilePath($file_name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L54)


#### Arguments
* $file_name **mixed**



### <a name="method-getFiles"></a>getFiles

```php
mixed HelperUploaderCore::getFiles()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L82)




### <a name="method-getId"></a>getId

```php
mixed HelperUploaderCore::getId()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L68)




### <a name="method-getMaxFiles"></a>getMaxFiles

```php
mixed HelperUploaderCore::getMaxFiles()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L96)




### <a name="method-getMaxSize"></a>getMaxSize

```php
mixed UploaderCore::getMaxSize()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L76)




### <a name="method-getName"></a>getName

```php
mixed HelperUploaderCore::getName()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L119)




### <a name="method-getPostMaxSizeBytes"></a>getPostMaxSizeBytes

```php
mixed UploaderCore::getPostMaxSizeBytes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L101)




### <a name="method-getSavePath"></a>getSavePath

```php
mixed UploaderCore::getSavePath()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L116)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperUploaderCore::getTemplate()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L124)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed HelperUploaderCore::getTemplateDirectory()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L138)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperUploaderCore::getTemplateFile($template)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L146)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperUploaderCore::getTitle()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L190)




### <a name="method-getUniqueFileName"></a>getUniqueFileName

```php
mixed UploaderCore::getUniqueFileName($prefix)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L124)


#### Arguments
* $prefix **mixed**



### <a name="method-getUrl"></a>getUrl

```php
mixed HelperUploaderCore::getUrl()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L201)




### <a name="method-isMultiple"></a>isMultiple

```php
mixed HelperUploaderCore::isMultiple()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L212)




### <a name="method-process"></a>process

```php
mixed UploaderCore::process()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L129)




### <a name="method-render"></a>render

```php
mixed HelperUploaderCore::render()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L217)




### <a name="method-setAcceptTypes"></a>setAcceptTypes

```php
mixed UploaderCore::setAcceptTypes($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L43)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperUploaderCore::setContext($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L48)


#### Arguments
* $value **mixed**



### <a name="method-setFiles"></a>setFiles

```php
mixed HelperUploaderCore::setFiles($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L76)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperUploaderCore::setId($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L62)


#### Arguments
* $value **mixed**



### <a name="method-setMaxFiles"></a>setMaxFiles

```php
mixed HelperUploaderCore::setMaxFiles($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L90)


#### Arguments
* $value **mixed**



### <a name="method-setMaxSize"></a>setMaxSize

```php
mixed UploaderCore::setMaxSize($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L70)


#### Arguments
* $value **mixed**



### <a name="method-setMultiple"></a>setMultiple

```php
mixed HelperUploaderCore::setMultiple($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L101)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed HelperUploaderCore::setName($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L113)


#### Arguments
* $value **mixed**



### <a name="method-setSavePath"></a>setSavePath

```php
mixed UploaderCore::setSavePath($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L95)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperUploaderCore::setTemplate($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L107)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed HelperUploaderCore::setTemplateDirectory($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperUploaderCore::setTitle($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L184)


#### Arguments
* $value **mixed**



### <a name="method-setUrl"></a>setUrl

```php
mixed HelperUploaderCore::setUrl($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L195)


#### Arguments
* $value **mixed**



### <a name="method-setUseAjax"></a>setUseAjax

```php
mixed HelperUploaderCore::setUseAjax($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L206)


#### Arguments
* $value **mixed**



### <a name="method-upload"></a>upload

```php
mixed UploaderCore::upload($file)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L158)


#### Arguments
* $file **mixed**



### <a name="method-useAjax"></a>useAjax

```php
mixed HelperUploaderCore::useAjax()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperUploader.php#L280)




### <a name="method-validate"></a>validate

```php
mixed UploaderCore::validate($file)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Uploader.php#L189)


#### Arguments
* $file **mixed**


