Class FileUploaderCore
=====================





* Class name: FileUploaderCore
* Source: [classes/FileUploader.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FileUploader.php#L118)


Contents
--------


### Properties

* [$allowedExtensions](#property-$allowedExtensions)
* [$file](#property-$file)
* [$sizeLimit](#property-$sizeLimit)

### Methods

* [__construct](#method-__construct)
* [handleUpload](#method-handleUpload)
* [toBytes](#method-toBytes)




Properties
----------


### <a name="property-$allowedExtensions"></a>$allowedExtensions

```php
private mixed $allowedExtensions = array()
```





* Visibility: **private**
* Source: [classes/FileUploader.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FileUploader.php#L121).


### <a name="property-$file"></a>$file

```php
private mixed $file
```





* Visibility: **private**
* Source: [classes/FileUploader.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FileUploader.php#L123).


### <a name="property-$sizeLimit"></a>$sizeLimit

```php
private mixed $sizeLimit = 10485760
```





* Visibility: **private**
* Source: [classes/FileUploader.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FileUploader.php#L122).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FileUploaderCore::__construct(array $allowedExtensions, $sizeLimit)
```





* Visibility: **public**
* Source: [classes/FileUploader.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FileUploader.php#L125)


#### Arguments
* $allowedExtensions **array**
* $sizeLimit **mixed**



### <a name="method-handleUpload"></a>handleUpload

```php
mixed FileUploaderCore::handleUpload()
```

Returns array('success'=>true) or array('error'=>'error message')



* Visibility: **public**
* Source: [classes/FileUploader.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FileUploader.php#L154)




### <a name="method-toBytes"></a>toBytes

```php
mixed FileUploaderCore::toBytes($str)
```





* Visibility: **private**
* Source: [classes/FileUploader.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FileUploader.php#L139)


#### Arguments
* $str **mixed**


