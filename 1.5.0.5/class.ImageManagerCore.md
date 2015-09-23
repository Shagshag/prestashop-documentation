Class ImageManagerCore
=====================

This class includes functions for image manipulation



* Class name: ImageManagerCore
* Source: [classes/ImageManager.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L33)


Contents
--------



### Methods

* [create](#method-create)
* [createWhiteImage](#method-createWhiteImage)
* [cut](#method-cut)
* [isRealImage](#method-isRealImage)
* [resize](#method-resize)
* [thumbnail](#method-thumbnail)
* [validateIconUpload](#method-validateIconUpload)
* [validateUpload](#method-validateUpload)
* [write](#method-write)






Methods
-------


### <a name="method-create"></a>create

```php
resource ImageManagerCore::create(string $type, string $filename)
```

Create an image with GD extension from a given type



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L293)


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
* Source: [classes/ImageManager.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L319)


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
* Source: [classes/ImageManager.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L258)


#### Arguments
* $src_file **array** - Origin filename
* $dst_file **string** - Destination filename
* $dst_width **integer** - Desired width
* $dst_height **integer** - Desired height
* $file_type **string**
* $dst_x **integer**
* $dst_y **integer**



### <a name="method-isRealImage"></a>isRealImage

```php
boolean ImageManagerCore::isRealImage(string $filename, string $file_mime_type, array $mime_type_list)
```

Check if file is a real image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L172)


#### Arguments
* $filename **string** - File path to check
* $file_mime_type **string** - File known mime type (generally from $_FILES)
* $mime_type_list **array** - Allowed MIME types



### <a name="method-resize"></a>resize

```php
boolean ImageManagerCore::resize(string $src_file, string $dst_file, integer $dst_width, integer $dst_height, string $file_type)
```

Resize, cut and optimize image



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L98)


#### Arguments
* $src_file **string** - Image object from $_FILE
* $dst_file **string** - Destination filename
* $dst_width **integer** - Desired width (optional)
* $dst_height **integer** - Desired height (optional)
* $file_type **string**



### <a name="method-thumbnail"></a>thumbnail

```php
string ImageManagerCore::thumbnail(string $image, string $cache_image, integer $size, string $image_type, boolean $disable_cache)
```

Generate a cached thumbnail for object lists (eg. carrier, order states.

..etc)

* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageManager.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L45)


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
* Source: [classes/ImageManager.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L234)


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
* Source: [classes/ImageManager.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L216)


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
* Source: [classes/ImageManager.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ImageManager.php#L335)


#### Arguments
* $type **string**
* $resource **resource**
* $filename **string**


