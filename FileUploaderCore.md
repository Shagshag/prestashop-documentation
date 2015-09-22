FileUploaderCore
===============






* Class name: FileUploaderCore
* This class is defined in [classes/FileUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L27)





Properties
----------

* [$allowedExtensions](#property-$allowedExtensions)
* [$file](#property-$file)
* [$sizeLimit](#property-$sizeLimit)

Methods
-------
* [__construct](#method-__construct)
* [toBytes](#method-toBytes)
* [handleUpload](#method-handleUpload)




Properties
----------


### <a name="property-$allowedExtensions"></a>$allowedExtensions

    protected mixed $allowedExtensions = array()





* Visibility: **protected**
* This property is defined in [classes/FileUploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L29)


### <a name="property-$file"></a>$file

    protected \QqUploadedFileXhr $file





* Visibility: **protected**
* This property is defined in [classes/FileUploader.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L32)


### <a name="property-$sizeLimit"></a>$sizeLimit

    protected mixed $sizeLimit





* Visibility: **protected**
* This property is defined in [classes/FileUploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed FileUploaderCore::__construct(array $allowedExtensions, $sizeLimit)





* Visibility: **public**
* This method is defined in [classes/FileUploader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L35)


#### Arguments
* $allowedExtensions **array**
* $sizeLimit **mixed**



### <a name="method-toBytes"></a>toBytes

    mixed FileUploaderCore::toBytes($str)





* Visibility: **protected**
* This method is defined in [classes/FileUploader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L51)


#### Arguments
* $str **mixed**



### <a name="method-handleUpload"></a>handleUpload

    mixed FileUploaderCore::handleUpload()

Returns array('success'=>true) or array('error'=>'error message')



* Visibility: **public**
* This method is defined in [classes/FileUploader.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L66)



