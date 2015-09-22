FileUploaderCore
===============






* Class name: FileUploaderCore
* This class is defined in [classes/FileUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#L27)





Properties
----------


### $allowedExtensions

    protected mixed $allowedExtensions = array()





* Visibility: **protected**
* This property is defined in [classes/FileUploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#29)


### $file

    protected \QqUploadedFileXhr $file





* Visibility: **protected**
* This property is defined in [classes/FileUploader.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#32)


### $sizeLimit

    protected mixed $sizeLimit





* Visibility: **protected**
* This property is defined in [classes/FileUploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#33)


Methods
-------


### __construct

    mixed FileUploaderCore::__construct(array $allowedExtensions, $sizeLimit)





* Visibility: **public**
* This method is defined in [classes/FileUploader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#35)


#### Arguments
* $allowedExtensions **array**
* $sizeLimit **mixed**



### toBytes

    mixed FileUploaderCore::toBytes($str)





* Visibility: **protected**
* This method is defined in [classes/FileUploader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#51)


#### Arguments
* $str **mixed**



### handleUpload

    mixed FileUploaderCore::handleUpload()

Returns array('success'=>true) or array('error'=>'error message')



* Visibility: **public**
* This method is defined in [classes/FileUploader.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/FileUploader.php#66)



