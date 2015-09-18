FileUploaderCore
===============






* Class name: FileUploaderCore
* Namespace: 





Properties
----------


### $allowedExtensions

    protected mixed $allowedExtensions = array()





* Visibility: **protected**


### $file

    protected \QqUploadedFileXhr $file





* Visibility: **protected**


### $sizeLimit

    protected mixed $sizeLimit





* Visibility: **protected**


Methods
-------


### __construct

    mixed FileUploaderCore::__construct(array $allowedExtensions, $sizeLimit)





* Visibility: **public**


#### Arguments
* $allowedExtensions **array**
* $sizeLimit **mixed**



### toBytes

    mixed FileUploaderCore::toBytes($str)





* Visibility: **protected**


#### Arguments
* $str **mixed**



### handleUpload

    mixed FileUploaderCore::handleUpload()

Returns array('success'=>true) or array('error'=>'error message')



* Visibility: **public**



