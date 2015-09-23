Class ImageManagerCore
=====================

This class includes functions for image manipulation



* Class name: ImageManagerCore
* Source: [classes/ImageManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L32)


Contents
--------



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






Methods
-------


### <a name="method-checkImageMemoryLimit"></a>checkImageMemoryLimit

```php
boolean ImageManagerCore::checkImageMemoryLimit($image)
```

Check if memory limit is too long or not



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L91)


#### Arguments
* $image **mixed**



### <a name="method-create"></a>create

```php
resource ImageManagerCore::create(string $type, string $filename)
```

Create an image with GD extension from a given type



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L351)


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
* Source: [classes/ImageManager.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L377)


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
* Source: [classes/ImageManager.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L316)


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
* Source: [classes/ImageManager.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L425)


#### Arguments
* $file_name **string**



### <a name="method-isCorrectImageFileExt"></a>isCorrectImageFileExt

```php
boolean ImageManagerCore::isCorrectImageFileExt($filename)
```

Check if image file extension is correct



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L246)


#### Arguments
* $filename **mixed** - real filename



### <a name="method-isRealImage"></a>isRealImage

```php
boolean ImageManagerCore::isRealImage(string $filename, string $file_mime_type, array $mime_type_list)
```

Check if file is a real image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L202)


#### Arguments
* $filename **string** - File path to check
* $file_mime_type **string** - File known mime type (generally from $_FILES)
* $mime_type_list **array** - Allowed MIME types



### <a name="method-resize"></a>resize

```php
boolean ImageManagerCore::resize(string $src_file, string $dst_file, integer $dst_width, integer $dst_height, string $file_type, $force_type)
```

Resize, cut and optimize image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L120)


#### Arguments
* $src_file **string** - Image object from $_FILE
* $dst_file **string** - Destination filename
* $dst_width **integer** - Desired width (optional)
* $dst_height **integer** - Desired height (optional)
* $file_type **string**
* $force_type **mixed**



### <a name="method-thumbnail"></a>thumbnail

```php
string ImageManagerCore::thumbnail(string $image, string $cache_image, integer $size, string $image_type, boolean $disable_cache)
```

Generate a cached thumbnail for object lists (eg. carrier, order states.

..etc)

* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L44)


#### Arguments
* $image **string** - Real image filename
* $cache_image **string** - Cached filename
* $size **integer** - Desired size
* $image_type **string** - Image type
* $disable_cache **boolean** - When turned on a timestamp will be added to the image URI to disable the HTTP cache



### <a name="method-validateIconUpload"></a>validateIconUpload

```php
boolean|string ImageManagerCore::validateIconUpload(array $file, integer $max_file_size)
```

Validate icon upload



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L288)


#### Arguments
* $file **array** - Upload $_FILE value
* $max_file_size **integer** - Maximum upload size



### <a name="method-validateUpload"></a>validateUpload

```php
boolean|string ImageManagerCore::validateUpload(array $file, integer $max_file_size)
```

Validate image upload (check image type and weight)



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L270)


#### Arguments
* $file **array** - Upload $_FILE value
* $max_file_size **integer** - Maximum upload size



### <a name="method-write"></a>write

```php
boolean ImageManagerCore::write(string $type, resource $resource, string $filename)
```

Generate and write image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/ImageManager.php#L393)


#### Arguments
* $type **string**
* $resource **resource**
* $filename **string**


