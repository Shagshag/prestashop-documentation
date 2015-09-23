Class Upload
=====================

This class provide all file upload functionalities



* Class name: Upload
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 9](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L9)


Contents
--------


### Properties

* [$_value](#property-$_value)
* [$dirPath](#property-$dirPath)
* [$errCode](#property-$errCode)
* [$errorCodes](#property-$errorCodes)
* [$errors](#property-$errors)
* [$fileBaseName](#property-$fileBaseName)
* [$fileExtension](#property-$fileExtension)
* [$fileName](#property-$fileName)
* [$filePath](#property-$filePath)
* [$fileSize](#property-$fileSize)
* [$fileType](#property-$fileType)
* [$imgHandler](#property-$imgHandler)
* [$img_new_x](#property-$img_new_x)
* [$img_new_y](#property-$img_new_y)
* [$img_x](#property-$img_x)
* [$img_y](#property-$img_y)
* [$invalidFileExt](#property-$invalidFileExt)
* [$originalFileName](#property-$originalFileName)
* [$safeMode](#property-$safeMode)
* [$uploadFileMode](#property-$uploadFileMode)
* [$validImageExts](#property-$validImageExts)

### Methods

* [Upload](#method-Upload)
* [_get_image_details](#method-_get_image_details)
* [_imageSave](#method-_imageSave)
* [_resize](#method-_resize)
* [deleteFileAndThumbs](#method-deleteFileAndThumbs)
* [deleteUploadedFile](#method-deleteUploadedFile)
* [displayError](#method-displayError)
* [finish](#method-finish)
* [getDirPath](#method-getDirPath)
* [getErrorCodeMsg](#method-getErrorCodeMsg)
* [getFileBaseName](#method-getFileBaseName)
* [getFileExt](#method-getFileExt)
* [getFileName](#method-getFileName)
* [getFilePath](#method-getFilePath)
* [getFileSize](#method-getFileSize)
* [getFileType](#method-getFileType)
* [getImageHeight](#method-getImageHeight)
* [getImageWidth](#method-getImageWidth)
* [getThumbInfo](#method-getThumbInfo)
* [isFileUploaded](#method-isFileUploaded)
* [isImage](#method-isImage)
* [isPermittedFileExt](#method-isPermittedFileExt)
* [isSizeTooBig](#method-isSizeTooBig)
* [moveUploadedFile](#method-moveUploadedFile)
* [resize](#method-resize)
* [setInvalidFileExt](#method-setInvalidFileExt)




Properties
----------


### <a name="property-$_value"></a>$_value

```php
public mixed $_value = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 25](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L25).


### <a name="property-$dirPath"></a>$dirPath

```php
public mixed $dirPath = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 26](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L26).


### <a name="property-$errCode"></a>$errCode

```php
public mixed $errCode = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L28).


### <a name="property-$errorCodes"></a>$errorCodes

```php
public mixed $errorCodes = array(0 => 'the file uploaded with success', 1 => 'The uploaded file exceeds the upload_max_filesize directive in php.ini', 2 => 'The uploaded file exceeds the MAX_FILE_SIZE directive that was specified in the HTML form', 3 => 'The uploaded file was only partially uploaded', 4 => 'No file was uploaded.', 6 => 'Missing a temporary folder', 7 => 'Failed to write file to disk', 8 => 'File upload stopped by extension', 999 => 'No error code avaiable')
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L31).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 24](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L24).


### <a name="property-$fileBaseName"></a>$fileBaseName

```php
public mixed $fileBaseName = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 20](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L20).


### <a name="property-$fileExtension"></a>$fileExtension

```php
public mixed $fileExtension = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L14).


### <a name="property-$fileName"></a>$fileName

```php
public mixed $fileName = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 13](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L13).


### <a name="property-$filePath"></a>$filePath

```php
public mixed $filePath = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 21](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L21).


### <a name="property-$fileSize"></a>$fileSize

```php
public mixed $fileSize
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 22](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L22).


### <a name="property-$fileType"></a>$fileType

```php
public mixed $fileType = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 11](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L11).


### <a name="property-$imgHandler"></a>$imgHandler

```php
public mixed $imgHandler = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 19](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L19).


### <a name="property-$img_new_x"></a>$img_new_x

```php
public mixed $img_new_x
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 17](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L17).


### <a name="property-$img_new_y"></a>$img_new_y

```php
public mixed $img_new_y
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 18](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L18).


### <a name="property-$img_x"></a>$img_x

```php
public mixed $img_x
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 15](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L15).


### <a name="property-$img_y"></a>$img_y

```php
public mixed $img_y
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L16).


### <a name="property-$invalidFileExt"></a>$invalidFileExt

```php
public mixed $invalidFileExt = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L27).


### <a name="property-$originalFileName"></a>$originalFileName

```php
public mixed $originalFileName = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L12).


### <a name="property-$safeMode"></a>$safeMode

```php
public mixed $safeMode
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L29).


### <a name="property-$uploadFileMode"></a>$uploadFileMode

```php
public mixed $uploadFileMode = 493
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L30).


### <a name="property-$validImageExts"></a>$validImageExts

```php
public mixed $validImageExts = array("gif", "jpg", "png")
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 23](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L23).


Methods
-------


### <a name="method-Upload"></a>Upload

```php
mixed Upload::Upload()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L44)




### <a name="method-_get_image_details"></a>_get_image_details

```php
void Upload::_get_image_details($image)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L380)


#### Arguments
* $image **mixed**



### <a name="method-_imageSave"></a>_imageSave

```php
boolean Upload::_imageSave(resource $newImageHandler, string $fileName, integer $quality)
```

save the thumbnail file and destroy the opened image



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L360)


#### Arguments
* $newImageHandler **resource**
* $fileName **string**
* $quality **integer**



### <a name="method-_resize"></a>_resize

```php
\unknown Upload::_resize(string $fileName, integer $new_x, integer $new_y)
```

resize the image and return the thumbnail image  details array("width"=>, "height"=>, "name")



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L318)


#### Arguments
* $fileName **string**
* $new_x **integer** - the thumbnail width
* $new_y **integer** - the thumbnail height



### <a name="method-deleteFileAndThumbs"></a>deleteFileAndThumbs

```php
mixed Upload::deleteFileAndThumbs(string $dirPath, string $originalImageName, string $arrayThumbnailSuffix)
```

delete the uploaded image file & associated thumnails



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L562)


#### Arguments
* $dirPath **string**
* $originalImageName **string**
* $arrayThumbnailSuffix **string**



### <a name="method-deleteUploadedFile"></a>deleteUploadedFile

```php
mixed Upload::deleteUploadedFile()
```

get the uploaded file



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L479)




### <a name="method-displayError"></a>displayError

```php
mixed Upload::displayError()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L492)




### <a name="method-finish"></a>finish

```php
mixed Upload::finish()
```

destroy the tmp file



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L487)




### <a name="method-getDirPath"></a>getDirPath

```php
\unknown Upload::getDirPath()
```

return the directory path witch the file uploaded to



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L514)




### <a name="method-getErrorCodeMsg"></a>getErrorCodeMsg

```php
mixed Upload::getErrorCodeMsg()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L71)




### <a name="method-getFileBaseName"></a>getFileBaseName

```php
mixed Upload::getFileBaseName()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L519)




### <a name="method-getFileExt"></a>getFileExt

```php
mixed Upload::getFileExt()
```

get a file extension



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L173)




### <a name="method-getFileName"></a>getFileName

```php
mixed Upload::getFileName()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L524)




### <a name="method-getFilePath"></a>getFilePath

```php
mixed Upload::getFilePath()
```

get the path which the file uploaded to



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 505](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L505)




### <a name="method-getFileSize"></a>getFileSize

```php
string Upload::getFileSize()
```

get uploaded file size



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 551](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L551)




### <a name="method-getFileType"></a>getFileType

```php
string Upload::getFileType()
```

get file type



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L164)




### <a name="method-getImageHeight"></a>getImageHeight

```php
integer Upload::getImageHeight()
```

get image height



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L542)




### <a name="method-getImageWidth"></a>getImageWidth

```php
integer Upload::getImageWidth()
```

get image width



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L533)




### <a name="method-getThumbInfo"></a>getThumbInfo

```php
array Upload::getThumbInfo(string $originalImageName, integer $originaleImageWidth, integer $originalImageHeight, string $thumbnailSuffix, integer $thumbnailWidth, integer $thumbnailHeight)
```

caculate the thumbnail details from the original image file



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L433)


#### Arguments
* $originalImageName **string**
* $originaleImageWidth **integer**
* $originalImageHeight **integer**
* $thumbnailSuffix **string**
* $thumbnailWidth **integer**
* $thumbnailHeight **integer**



### <a name="method-isFileUploaded"></a>isFileUploaded

```php
mixed Upload::isFileUploaded($indexInPost)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L49)


#### Arguments
* $indexInPost **mixed**



### <a name="method-isImage"></a>isImage

```php
mixed Upload::isImage(mixed $invalidImageExts, boolean $delete)
```

check if the uploaded is permitted to upload



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L239)


#### Arguments
* $invalidImageExts **mixed** - invalid image extension
* $delete **boolean** - force to delete the uploaded file



### <a name="method-isPermittedFileExt"></a>isPermittedFileExt

```php
boolean Upload::isPermittedFileExt(array $validFileExt)
```

check if the uploaded file extension is allowed against the validFile Extension
or against the invalid extension list when the list of valid file extension is not set



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L82)


#### Arguments
* $validFileExt **array**



### <a name="method-isSizeTooBig"></a>isSizeTooBig

```php
mixed Upload::isSizeTooBig(integer $maxSize)
```

check if the uploaded file size is too big



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L130)


#### Arguments
* $maxSize **integer**



### <a name="method-moveUploadedFile"></a>moveUploadedFile

```php
\unknown Upload::moveUploadedFile(string $dest, string $fileBaseName, \unknown_type $overwrite)
```

move the uploaded file to a specific location



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L186)


#### Arguments
* $dest **string** - the path to the directory which the uploaded file will be moved to
* $fileBaseName **string** - the base name which the uploaded file will be renamed to
* $overwrite **unknown_type**



### <a name="method-resize"></a>resize

```php
mixed Upload::resize($filePath, string $thumb_suffix, mixed $new_x, mixed $new_y)
```

Resize the Image in the X and/or Y direction
If either is 0 it will be scaled proportionally



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L294)


#### Arguments
* $filePath **mixed**
* $thumb_suffix **string**
* $new_x **mixed**
* $new_y **mixed**



### <a name="method-setInvalidFileExt"></a>setInvalidFileExt

```php
mixed Upload::setInvalidFileExt(array $invalidFileExt)
```

set the invali file extensions



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.upload.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/admin-dev/ajaxfilemanager/inc/class.upload.php#L146)


#### Arguments
* $invalidFileExt **array**


