Class HelperUploaderCore
=====================





* Class name: HelperUploaderCore
* Parent class: [Uploader](class.UploaderCore.md)
* Source: [classes/helper/HelperUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L27)


Contents
--------

### Constants

* [DEFAULT_AJAX_TEMPLATE](#constant-DEFAULT_AJAX_TEMPLATE)
* [DEFAULT_TEMPLATE](#constant-DEFAULT_TEMPLATE)
* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)
* [TYPE_FILE](#constant-TYPE_FILE)
* [TYPE_IMAGE](#constant-TYPE_IMAGE)

### Properties

* [$_context](#property-$_context)
* [$_drop_zone](#property-$_drop_zone)
* [$_files](#property-$_files)
* [$_id](#property-$_id)
* [$_max_files](#property-$_max_files)
* [$_multiple](#property-$_multiple)
* [$_name](#property-$_name)
* [$_post_max_size](#property-$_post_max_size)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)
* [$_title](#property-$_title)
* [$_url](#property-$_url)
* [$_use_ajax](#property-$_use_ajax)

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


Constants
----------


### <a name="constant-DEFAULT_AJAX_TEMPLATE"></a>DEFAULT_AJAX_TEMPLATE

```php
const DEFAULT_AJAX_TEMPLATE = 'ajax.tpl'
```





* Source: [classes/helper/HelperUploader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L31).


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'simple.tpl'
```





* Source: [classes/helper/HelperUploader.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/uploader'
```





* Source: [classes/helper/HelperUploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L29).


### <a name="constant-TYPE_FILE"></a>TYPE_FILE

```php
const TYPE_FILE = 'file'
```





* Source: [classes/helper/HelperUploader.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L34).


### <a name="constant-TYPE_IMAGE"></a>TYPE_IMAGE

```php
const TYPE_IMAGE = 'image'
```





* Source: [classes/helper/HelperUploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L33).


Properties
----------


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L36).


### <a name="property-$_drop_zone"></a>$_drop_zone

```php
private mixed $_drop_zone
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L37).


### <a name="property-$_files"></a>$_files

```php
private mixed $_files
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L39).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L38).


### <a name="property-$_max_files"></a>$_max_files

```php
private mixed $_max_files
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L41).


### <a name="property-$_multiple"></a>$_multiple

```php
private mixed $_multiple
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L42).


### <a name="property-$_name"></a>$_name

```php
private mixed $_name
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L40).


### <a name="property-$_post_max_size"></a>$_post_max_size

```php
private mixed $_post_max_size
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L43).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperUploader.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L44).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private mixed $_template_directory
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L45).


### <a name="property-$_title"></a>$_title

```php
private mixed $_title
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L46).


### <a name="property-$_url"></a>$_url

```php
private mixed $_url
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L47).


### <a name="property-$_use_ajax"></a>$_use_ajax

```php
private mixed $_use_ajax
```





* Visibility: **private**
* Source: [classes/helper/HelperUploader.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L48).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed UploaderCore::__construct($name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L38)


#### Arguments
* $name **mixed**



### <a name="method-_getFileSize"></a>_getFileSize

```php
mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L266)


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### <a name="method-_getServerVars"></a>_getServerVars

```php
mixed UploaderCore::_getServerVars($var)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L275)


#### Arguments
* $var **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed UploaderCore::_normalizeDirectory($directory)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L280)


#### Arguments
* $directory **mixed**



### <a name="method-checkFileSize"></a>checkFileSize

```php
mixed UploaderCore::checkFileSize()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L144)




### <a name="method-checkUploadError"></a>checkUploadError

```php
mixed UploaderCore::checkUploadError($error_code)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L203)


#### Arguments
* $error_code **mixed**



### <a name="method-getAcceptTypes"></a>getAcceptTypes

```php
mixed UploaderCore::getAcceptTypes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L51)




### <a name="method-getContext"></a>getContext

```php
mixed HelperUploaderCore::getContext()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L56)




### <a name="method-getDropZone"></a>getDropZone

```php
mixed HelperUploaderCore::getDropZone()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L71)




### <a name="method-getFilePath"></a>getFilePath

```php
mixed UploaderCore::getFilePath($file_name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L62)


#### Arguments
* $file_name **mixed**



### <a name="method-getFiles"></a>getFiles

```php
mixed HelperUploaderCore::getFiles()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L101)




### <a name="method-getId"></a>getId

```php
mixed HelperUploaderCore::getId()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L86)




### <a name="method-getMaxFiles"></a>getMaxFiles

```php
mixed HelperUploaderCore::getMaxFiles()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L116)




### <a name="method-getMaxSize"></a>getMaxSize

```php
mixed UploaderCore::getMaxSize()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L86)




### <a name="method-getName"></a>getName

```php
mixed HelperUploaderCore::getName()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L133)




### <a name="method-getPostMaxSize"></a>getPostMaxSize

```php
mixed HelperUploaderCore::getPostMaxSize()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L145)




### <a name="method-getPostMaxSizeBytes"></a>getPostMaxSizeBytes

```php
mixed UploaderCore::getPostMaxSizeBytes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L112)




### <a name="method-getSavePath"></a>getSavePath

```php
mixed UploaderCore::getSavePath()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L130)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperUploaderCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L160)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed HelperUploaderCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L175)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperUploaderCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L184)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperUploaderCore::getTitle()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L218)




### <a name="method-getUniqueFileName"></a>getUniqueFileName

```php
mixed UploaderCore::getUniqueFileName($prefix)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L139)


#### Arguments
* $prefix **mixed**



### <a name="method-getUrl"></a>getUrl

```php
mixed HelperUploaderCore::getUrl()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L229)




### <a name="method-isMultiple"></a>isMultiple

```php
mixed HelperUploaderCore::isMultiple()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L240)




### <a name="method-process"></a>process

```php
mixed UploaderCore::process($dest)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L149)


#### Arguments
* $dest **mixed**



### <a name="method-render"></a>render

```php
mixed HelperUploaderCore::render()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L245)




### <a name="method-setAcceptTypes"></a>setAcceptTypes

```php
mixed UploaderCore::setAcceptTypes($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L45)


#### Arguments
* $value **mixed**



### <a name="method-setCheckFileSize"></a>setCheckFileSize

```php
mixed UploaderCore::setCheckFileSize($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L56)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperUploaderCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L50)


#### Arguments
* $value **mixed**



### <a name="method-setDropZone"></a>setDropZone

```php
mixed HelperUploaderCore::setDropZone($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L65)


#### Arguments
* $value **mixed**



### <a name="method-setFiles"></a>setFiles

```php
mixed HelperUploaderCore::setFiles($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L95)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperUploaderCore::setId($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L80)


#### Arguments
* $value **mixed**



### <a name="method-setMaxFiles"></a>setMaxFiles

```php
mixed HelperUploaderCore::setMaxFiles($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L110)


#### Arguments
* $value **mixed**



### <a name="method-setMaxSize"></a>setMaxSize

```php
mixed UploaderCore::setMaxSize($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L80)


#### Arguments
* $value **mixed**



### <a name="method-setMultiple"></a>setMultiple

```php
mixed HelperUploaderCore::setMultiple($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L121)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed HelperUploaderCore::setName($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L127)


#### Arguments
* $value **mixed**



### <a name="method-setPostMaxSize"></a>setPostMaxSize

```php
mixed HelperUploaderCore::setPostMaxSize($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setSavePath"></a>setSavePath

```php
mixed UploaderCore::setSavePath($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L106)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperUploaderCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L154)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed HelperUploaderCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L169)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperUploaderCore::setTitle($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L212)


#### Arguments
* $value **mixed**



### <a name="method-setUrl"></a>setUrl

```php
mixed HelperUploaderCore::setUrl($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L223)


#### Arguments
* $value **mixed**



### <a name="method-setUseAjax"></a>setUseAjax

```php
mixed HelperUploaderCore::setUseAjax($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L234)


#### Arguments
* $value **mixed**



### <a name="method-upload"></a>upload

```php
mixed UploaderCore::upload($file, $dest)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L173)


#### Arguments
* $file **mixed**
* $dest **mixed**



### <a name="method-useAjax"></a>useAjax

```php
mixed HelperUploaderCore::useAjax()
```





* Visibility: **public**
* Source: [classes/helper/HelperUploader.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperUploader.php#L291)




### <a name="method-validate"></a>validate

```php
mixed UploaderCore::validate($file)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Uploader.php#L234)


#### Arguments
* $file **mixed**


