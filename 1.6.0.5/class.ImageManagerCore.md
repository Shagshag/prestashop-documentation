Class ImageManagerCore
=====================

This class includes functions for image manipulation



* Class name: ImageManagerCore
* Source: [classes/ImageManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L32)


Contents
--------

### Constants

* [ERROR_FILE_NOT_EXIST](#constant-ERROR_FILE_NOT_EXIST)
* [ERROR_FILE_WIDTH](#constant-ERROR_FILE_WIDTH)
* [ERROR_MEMORY_LIMIT](#constant-ERROR_MEMORY_LIMIT)


### Methods

* [checkImageMemoryLimit](#method-checkImageMemoryLimit)
* [create](#method-create)
* [createWhiteImage](#method-createWhiteImage)
* [cut](#method-cut)
* [getMimeTypeByExtension](#method-getMimeTypeByExtension)
* [isCorrectImageFileExt](#method-isCorrectImageFileExt)
* [isRealImage](#method-isRealImage)
* [resize](#method-resize)
* [thumbnail](#method-thumbnail)
* [validateIconUpload](#method-validateIconUpload)
* [validateUpload](#method-validateUpload)
* [write](#method-write)


Constants
----------


### <a name="constant-ERROR_FILE_NOT_EXIST"></a>ERROR_FILE_NOT_EXIST

```php
const ERROR_FILE_NOT_EXIST = 1
```





* Source: [classes/ImageManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L34).


### <a name="constant-ERROR_FILE_WIDTH"></a>ERROR_FILE_WIDTH

```php
const ERROR_FILE_WIDTH = 2
```





* Source: [classes/ImageManager.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L35).


### <a name="constant-ERROR_MEMORY_LIMIT"></a>ERROR_MEMORY_LIMIT

```php
const ERROR_MEMORY_LIMIT = 3
```





* Source: [classes/ImageManager.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L36).




Methods
-------


### <a name="method-checkImageMemoryLimit"></a>checkImageMemoryLimit

```php
boolean ImageManagerCore::checkImageMemoryLimit($image)
```

Check if memory limit is too long or not



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L99)


#### Arguments
* $image **mixed**



### <a name="method-create"></a>create

```php
resource ImageManagerCore::create(string $type, string $filename)
```

Create an image with GD extension from a given type



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L361)


#### Arguments
* $type **string**
* $filename **string**



### <a name="method-createWhiteImage"></a>createWhiteImage

```php
resource ImageManagerCore::createWhiteImage(integer $width, integer $height)
```

Create an empty image with white background



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L387)


#### Arguments
* $width **integer**
* $height **integer**



### <a name="method-cut"></a>cut

```php
boolean ImageManagerCore::cut(array $src_file, string $dst_file, integer $dst_width, integer $dst_height, string $file_type, integer $dst_x, integer $dst_y)
```

Cut image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L326)


#### Arguments
* $src_file **array** - Origin filename
* $dst_file **string** - Destination filename
* $dst_width **integer** - Desired width
* $dst_height **integer** - Desired height
* $file_type **string**
* $dst_x **integer**
* $dst_y **integer**



### <a name="method-getMimeTypeByExtension"></a>getMimeTypeByExtension

```php
string ImageManagerCore::getMimeTypeByExtension(string $file_name)
```

Return the mime type by the file extension



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L435)


#### Arguments
* $file_name **string**



### <a name="method-isCorrectImageFileExt"></a>isCorrectImageFileExt

```php
boolean ImageManagerCore::isCorrectImageFileExt($filename, $authorized_extensions)
```

Check if image file extension is correct



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L255)


#### Arguments
* $filename **mixed** - real filename
* $authorized_extensions **mixed**



### <a name="method-isRealImage"></a>isRealImage

```php
boolean ImageManagerCore::isRealImage(string $filename, string $file_mime_type, array $mime_type_list)
```

Check if file is a real image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L211)


#### Arguments
* $filename **string** - File path to check
* $file_mime_type **string** - File known mime type (generally from $_FILES)
* $mime_type_list **array** - Allowed MIME types



### <a name="method-resize"></a>resize

```php
boolean ImageManagerCore::resize(string $src_file, string $dst_file, integer $dst_width, integer $dst_height, string $file_type, $force_type, $error)
```

Resize, cut and optimize image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L128)


#### Arguments
* $src_file **string** - Image object from $_FILE
* $dst_file **string** - Destination filename
* $dst_width **integer** - Desired width (optional)
* $dst_height **integer** - Desired height (optional)
* $file_type **string**
* $force_type **mixed**
* $error **mixed**



### <a name="method-thumbnail"></a>thumbnail

```php
string ImageManagerCore::thumbnail(string $image, string $cache_image, integer $size, string $image_type, boolean $disable_cache, boolean $regenerate)
```

Generate a cached thumbnail for object lists (eg. carrier, order states.

..etc)

* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L49)


#### Arguments
* $image **string** - Real image filename
* $cache_image **string** - Cached filename
* $size **integer** - Desired size
* $image_type **string** - Image type
* $disable_cache **boolean** - When turned on a timestamp will be added to the image URI to disable the HTTP cache
* $regenerate **boolean** - When turned on and the file already exist, the file will be regenerated



### <a name="method-validateIconUpload"></a>validateIconUpload

```php
boolean|string ImageManagerCore::validateIconUpload(array $file, integer $max_file_size)
```

Validate icon upload



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L298)


#### Arguments
* $file **array** - Upload $_FILE value
* $max_file_size **integer** - Maximum upload size



### <a name="method-validateUpload"></a>validateUpload

```php
boolean|string ImageManagerCore::validateUpload(array $file, integer $max_file_size, $types)
```

Validate image upload (check image type and weight)



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L280)


#### Arguments
* $file **array** - Upload $_FILE value
* $max_file_size **integer** - Maximum upload size
* $types **mixed**



### <a name="method-write"></a>write

```php
boolean ImageManagerCore::write(string $type, resource $resource, string $filename)
```

Generate and write image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/ImageManager.php#L403)


#### Arguments
* $type **string**
* $resource **resource**
* $filename **string**


