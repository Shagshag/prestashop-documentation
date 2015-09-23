Class FileUploaderCore
=====================





* Class name: FileUploaderCore
* Source: [classes/FileUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/FileUploader.php#L27)


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
protected mixed $allowedExtensions = array()
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/FileUploader.php#L29).


### <a name="property-$file"></a>$file

```php
protected mixed $file
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/FileUploader.php#L30).


### <a name="property-$sizeLimit"></a>$sizeLimit

```php
protected mixed $sizeLimit
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/FileUploader.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FileUploaderCore::__construct(array $allowedExtensions, $sizeLimit)
```





* Visibility: **public**
* Source: [classes/FileUploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/FileUploader.php#L33)


#### Arguments
* $allowedExtensions **array**
* $sizeLimit **mixed**



### <a name="method-handleUpload"></a>handleUpload

```php
mixed FileUploaderCore::handleUpload()
```

Returns array('success'=>true) or array('error'=>'error message')



* Visibility: **public**
* Source: [classes/FileUploader.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/FileUploader.php#L64)




### <a name="method-toBytes"></a>toBytes

```php
mixed FileUploaderCore::toBytes($str)
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/FileUploader.php#L48)


#### Arguments
* $str **mixed**


