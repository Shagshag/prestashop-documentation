ImageManagerCore
===============

This class includes functions for image manipulation




* Class name: ImageManagerCore
* This class is defined in [classes/ImageManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L32)



Constants
----------

* [ERROR_FILE_NOT_EXIST](#constant-ERROR_FILE_NOT_EXIST)
* [ERROR_FILE_WIDTH](#constant-ERROR_FILE_WIDTH)
* [ERROR_MEMORY_LIMIT](#constant-ERROR_MEMORY_LIMIT)



Methods
-------
* [thumbnail](#method-thumbnail)
* [checkImageMemoryLimit](#method-checkImageMemoryLimit)
* [resize](#method-resize)
* [imagecopyresampled](#method-imagecopyresampled)
* [isRealImage](#method-isRealImage)
* [isCorrectImageFileExt](#method-isCorrectImageFileExt)
* [validateUpload](#method-validateUpload)
* [validateIconUpload](#method-validateIconUpload)
* [cut](#method-cut)
* [create](#method-create)
* [createWhiteImage](#method-createWhiteImage)
* [write](#method-write)
* [getMimeTypeByExtension](#method-getMimeTypeByExtension)


Constants
----------


### <a name="constant-ERROR_FILE_NOT_EXIST"></a>ERROR_FILE_NOT_EXIST

    const ERROR_FILE_NOT_EXIST = 1



* This constant is defined in [classes/ImageManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L34)


### <a name="constant-ERROR_FILE_WIDTH"></a>ERROR_FILE_WIDTH

    const ERROR_FILE_WIDTH = 2



* This constant is defined in [classes/ImageManager.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L35)


### <a name="constant-ERROR_MEMORY_LIMIT"></a>ERROR_MEMORY_LIMIT

    const ERROR_MEMORY_LIMIT = 3



* This constant is defined in [classes/ImageManager.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L36)




Methods
-------


### <a name="method-thumbnail"></a>thumbnail

    string ImageManagerCore::thumbnail(string $image, string $cache_image, integer $size, string $image_type, boolean $disable_cache, boolean $regenerate)

Generate a cached thumbnail for object lists (eg. carrier, order statuses.

..etc)

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L49)


#### Arguments
* $image **string** - &lt;p&gt;Real image filename&lt;/p&gt;
* $cache_image **string** - &lt;p&gt;Cached filename&lt;/p&gt;
* $size **integer** - &lt;p&gt;Desired size&lt;/p&gt;
* $image_type **string** - &lt;p&gt;Image type&lt;/p&gt;
* $disable_cache **boolean** - &lt;p&gt;When turned on a timestamp will be added to the image URI to disable the HTTP cache&lt;/p&gt;
* $regenerate **boolean** - &lt;p&gt;When turned on and the file already exist, the file will be regenerated&lt;/p&gt;



### <a name="method-checkImageMemoryLimit"></a>checkImageMemoryLimit

    boolean ImageManagerCore::checkImageMemoryLimit($image)

Check if memory limit is too long or not



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L100)


#### Arguments
* $image **mixed**



### <a name="method-resize"></a>resize

    boolean ImageManagerCore::resize(string $src_file, string $dst_file, integer $dst_width, integer $dst_height, string $file_type, boolean $force_type, integer $error, integer $tgt_width, integer $tgt_height, integer $quality, integer $src_width, integer $src_height)

Resize, cut and optimize image



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L141)


#### Arguments
* $src_file **string** - &lt;p&gt;Image object from $_FILE&lt;/p&gt;
* $dst_file **string** - &lt;p&gt;Destination filename&lt;/p&gt;
* $dst_width **integer** - &lt;p&gt;Desired width (optional)&lt;/p&gt;
* $dst_height **integer** - &lt;p&gt;Desired height (optional)&lt;/p&gt;
* $file_type **string**
* $force_type **boolean**
* $error **integer**
* $tgt_width **integer**
* $tgt_height **integer**
* $quality **integer**
* $src_width **integer**
* $src_height **integer**



### <a name="method-imagecopyresampled"></a>imagecopyresampled

    mixed ImageManagerCore::imagecopyresampled($dst_image, $src_image, $dst_x, $dst_y, $src_x, $src_y, $dst_w, $dst_h, $src_w, $src_h, $quality)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L265)


#### Arguments
* $dst_image **mixed**
* $src_image **mixed**
* $dst_x **mixed**
* $dst_y **mixed**
* $src_x **mixed**
* $src_y **mixed**
* $dst_w **mixed**
* $dst_h **mixed**
* $src_w **mixed**
* $src_h **mixed**
* $quality **mixed**



### <a name="method-isRealImage"></a>isRealImage

    boolean ImageManagerCore::isRealImage(string $filename, string $file_mime_type, array $mime_type_list)

Check if file is a real image



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L302)


#### Arguments
* $filename **string** - &lt;p&gt;File path to check&lt;/p&gt;
* $file_mime_type **string** - &lt;p&gt;File known mime type (generally from $_FILES)&lt;/p&gt;
* $mime_type_list **array** - &lt;p&gt;Allowed MIME types&lt;/p&gt;



### <a name="method-isCorrectImageFileExt"></a>isCorrectImageFileExt

    boolean ImageManagerCore::isCorrectImageFileExt(string $filename, array|null $authorized_extensions)

Check if image file extension is correct



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L357)


#### Arguments
* $filename **string** - &lt;p&gt;Real filename&lt;/p&gt;
* $authorized_extensions **array|null**



### <a name="method-validateUpload"></a>validateUpload

    boolean|string ImageManagerCore::validateUpload(array $file, integer $max_file_size, $types)

Validate image upload (check image type and weight)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L383)


#### Arguments
* $file **array** - &lt;p&gt;Upload $_FILE value&lt;/p&gt;
* $max_file_size **integer** - &lt;p&gt;Maximum upload size&lt;/p&gt;
* $types **mixed**



### <a name="method-validateIconUpload"></a>validateIconUpload

    boolean|string ImageManagerCore::validateIconUpload(array $file, integer $max_file_size)

Validate icon upload



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L404)


#### Arguments
* $file **array** - &lt;p&gt;Upload $_FILE value&lt;/p&gt;
* $max_file_size **integer** - &lt;p&gt;Maximum upload size&lt;/p&gt;



### <a name="method-cut"></a>cut

    boolean ImageManagerCore::cut(array $src_file, string $dst_file, integer $dst_width, integer $dst_height, string $file_type, integer $dst_x, integer $dst_y)

Cut image



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L435)


#### Arguments
* $src_file **array** - &lt;p&gt;Origin filename&lt;/p&gt;
* $dst_file **string** - &lt;p&gt;Destination filename&lt;/p&gt;
* $dst_width **integer** - &lt;p&gt;Desired width&lt;/p&gt;
* $dst_height **integer** - &lt;p&gt;Desired height&lt;/p&gt;
* $file_type **string**
* $dst_x **integer**
* $dst_y **integer**



### <a name="method-create"></a>create

    resource ImageManagerCore::create(string $type, string $filename)

Create an image with GD extension from a given type



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L472)


#### Arguments
* $type **string**
* $filename **string**



### <a name="method-createWhiteImage"></a>createWhiteImage

    resource ImageManagerCore::createWhiteImage(integer $width, integer $height)

Create an empty image with white background



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 497](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L497)


#### Arguments
* $width **integer**
* $height **integer**



### <a name="method-write"></a>write

    boolean ImageManagerCore::write(string $type, resource $resource, string $filename)

Generate and write image



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L513)


#### Arguments
* $type **string**
* $resource **resource**
* $filename **string**



### <a name="method-getMimeTypeByExtension"></a>getMimeTypeByExtension

    string ImageManagerCore::getMimeTypeByExtension(string $file_name)

Return the mime type by the file extension



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageManager.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageManager.php#L555)


#### Arguments
* $file_name **string**


