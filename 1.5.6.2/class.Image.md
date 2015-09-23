Class Image
=====================

this class provide functions to edit an image, e.g. resize, rotate, flip, crop



* Class name: Image
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 15](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L15)


Contents
--------


### Properties

* [$_debug](#property-$_debug)
* [$_errors](#property-$_errors)
* [$_imgFinal](#property-$_imgFinal)
* [$_imgInfoFinal](#property-$_imgInfoFinal)
* [$_imgInfoOrig](#property-$_imgInfoOrig)
* [$_imgOrig](#property-$_imgOrig)
* [$_imgQuality](#property-$_imgQuality)
* [$chmod](#property-$chmod)
* [$gdInfo](#property-$gdInfo)
* [$imageFile](#property-$imageFile)
* [$transparentColorBlue](#property-$transparentColorBlue)
* [$transparentColorGreen](#property-$transparentColorGreen)
* [$transparentColorRed](#property-$transparentColorRed)

### Methods

* [DestroyImages](#method-DestroyImages)
* [Image](#method-Image)
* [__construct](#method-__construct)
* [_createFinalImageHandler](#method-_createFinalImageHandler)
* [_debug](#method-_debug)
* [_getExtension](#method-_getExtension)
* [_getImageInfo](#method-_getImageInfo)
* [_isDebugEnable](#method-_isDebugEnable)
* [_isSupported](#method-_isSupported)
* [_resize](#method-_resize)
* [crop](#method-crop)
* [enableDebug](#method-enableDebug)
* [flip](#method-flip)
* [flipHorizontal](#method-flipHorizontal)
* [flipVertical](#method-flipVertical)
* [getFinalImageInfo](#method-getFinalImageInfo)
* [getGDInfo](#method-getGDInfo)
* [getImageInfo](#method-getImageInfo)
* [getOriginalImageInfo](#method-getOriginalImageInfo)
* [loadImage](#method-loadImage)
* [loadImageFromString](#method-loadImageFromString)
* [resize](#method-resize)
* [rotate](#method-rotate)
* [saveImage](#method-saveImage)
* [showErrors](#method-showErrors)
* [showImage](#method-showImage)




Properties
----------


### <a name="property-$_debug"></a>$_debug

```php
public mixed $_debug = false
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 17](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L17).


### <a name="property-$_errors"></a>$_errors

```php
public mixed $_errors = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 18](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L18).


### <a name="property-$_imgFinal"></a>$_imgFinal

```php
public mixed $_imgFinal = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 21](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L21).


### <a name="property-$_imgInfoFinal"></a>$_imgInfoFinal

```php
public mixed $_imgInfoFinal = array('name' => '', 'ext' => '', 'size' => '', 'width' => '', 'height' => '', 'type' => '', 'path' => '')
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L36).


### <a name="property-$_imgInfoOrig"></a>$_imgInfoOrig

```php
public mixed $_imgInfoOrig = array('name' => '', 'ext' => '', 'size' => '', 'width' => '', 'height' => '', 'type' => '', 'path' => '')
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L27).


### <a name="property-$_imgOrig"></a>$_imgOrig

```php
public mixed $_imgOrig = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 20](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L20).


### <a name="property-$_imgQuality"></a>$_imgQuality

```php
public mixed $_imgQuality = 90
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L45).


### <a name="property-$chmod"></a>$chmod

```php
public mixed $chmod = 493
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 26](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L26).


### <a name="property-$gdInfo"></a>$gdInfo

```php
public mixed $gdInfo = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 19](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L19).


### <a name="property-$imageFile"></a>$imageFile

```php
public mixed $imageFile = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 22](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L22).


### <a name="property-$transparentColorBlue"></a>$transparentColorBlue

```php
public mixed $transparentColorBlue = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 25](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L25).


### <a name="property-$transparentColorGreen"></a>$transparentColorGreen

```php
public mixed $transparentColorGreen = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 24](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L24).


### <a name="property-$transparentColorRed"></a>$transparentColorRed

```php
public mixed $transparentColorRed = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 23](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L23).


Methods
-------


### <a name="method-DestroyImages"></a>DestroyImages

```php
void Image::DestroyImages(boolean $original)
```

Destroy the resources used by the images.



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 653](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L653)


#### Arguments
* $original **boolean**



### <a name="method-Image"></a>Image

```php
mixed Image::Image($debug)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L58)


#### Arguments
* $debug **mixed**



### <a name="method-__construct"></a>__construct

```php
\Image Image::__construct(boolean $debug)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L53)


#### Arguments
* $debug **boolean**



### <a name="method-_createFinalImageHandler"></a>_createFinalImageHandler

```php
mixed Image::_createFinalImageHandler($dst_w, $dst_h)
```

create final image handler

@access private

* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L772)


#### Arguments
* $dst_w **mixed** - width
@param $dst_h height
@return boolean
@copyright original from noname at nivelzero dot ro
* $dst_h **mixed**



### <a name="method-_debug"></a>_debug

```php
void Image::_debug($value)
```

append to errors array and shown the each error when the debug turned on



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L88)


#### Arguments
* $value **mixed**



### <a name="method-_getExtension"></a>_getExtension

```php
string Image::_getExtension(string $file)
```

Get the extension of a file name



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L465)


#### Arguments
* $file **string**



### <a name="method-_getImageInfo"></a>_getImageInfo

```php
array Image::_getImageInfo($imagePath)
```

get image information, e.g. width, height, type



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L675)


#### Arguments
* $imagePath **mixed**



### <a name="method-_isDebugEnable"></a>_isDebugEnable

```php
boolean Image::_isDebugEnable()
```

check if debug enable



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L75)




### <a name="method-_isSupported"></a>_isSupported

```php
boolean Image::_isSupported(string $filename, string $extension, string $function, boolean $write)
```

Validate whether image reading/writing routines are valid.



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L485)


#### Arguments
* $filename **string**
* $extension **string**
* $function **string**
* $write **boolean**



### <a name="method-_resize"></a>_resize

```php
\unknown Image::_resize(integer $new_x, integer $new_y)
```

resize the image and return the thumbnail image  details array("width"=>, "height"=>, "name")



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L417)


#### Arguments
* $new_x **integer** - the thumbnail width
* $new_y **integer** - the thumbnail height



### <a name="method-crop"></a>crop

```php
boolean Image::crop(integer $dst_x, integer $dst_y, integer $dst_w, integer $dst_h)
```

Used for cropping image



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L297)


#### Arguments
* $dst_x **integer**
* $dst_y **integer**
* $dst_w **integer**
* $dst_h **integer**



### <a name="method-enableDebug"></a>enableDebug

```php
mixed Image::enableDebug(boolean $value)
```

enable to debug



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L67)


#### Arguments
* $value **boolean**



### <a name="method-flip"></a>flip

```php
boolean Image::flip(string $direction)
```

flip image horizotally or vertically



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 510](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L510)


#### Arguments
* $direction **string**



### <a name="method-flipHorizontal"></a>flipHorizontal

```php
string Image::flipHorizontal()
```

flip horizontal



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 568](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L568)




### <a name="method-flipVertical"></a>flipVertical

```php
boolean Image::flipVertical()
```

flip vertically



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L559)




### <a name="method-getFinalImageInfo"></a>getFinalImageInfo

```php
array Image::getFinalImageInfo()
```

return the final image info



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L747)




### <a name="method-getGDInfo"></a>getGDInfo

```php
array Image::getGDInfo(boolean $versionOnly)
```

get the GD version information



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L582)


#### Arguments
* $versionOnly **boolean**



### <a name="method-getImageInfo"></a>getImageInfo

```php
mixed Image::getImageInfo($imagePath)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 666](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L666)


#### Arguments
* $imagePath **mixed**



### <a name="method-getOriginalImageInfo"></a>getOriginalImageInfo

```php
array Image::getOriginalImageInfo()
```

get the original image info



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L738)




### <a name="method-loadImage"></a>loadImage

```php
boolean Image::loadImage(string $filename)
```

Load an image from the file system.



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L118)


#### Arguments
* $filename **string**



### <a name="method-loadImageFromString"></a>loadImageFromString

```php
boolean Image::loadImageFromString(string $string)
```

Load an image from a string (eg. from a database table)



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L179)


#### Arguments
* $string **string**



### <a name="method-resize"></a>resize

```php
mixed Image::resize(mixed $new_x, mixed $new_y, boolean $constraint, boolean $unchangeIfsmaller)
```

Resize the Image in the X and/or Y direction
If either is 0 it will be scaled proportionally



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L348)


#### Arguments
* $new_x **mixed**
* $new_y **mixed**
* $constraint **boolean** - keep to resize the image proportionally
* $unchangeIfsmaller **boolean** - keep the orignial size if the orignial smaller than the new size



### <a name="method-rotate"></a>rotate

```php
mixed Image::rotate($angle, $bgColor)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L714)


#### Arguments
* $angle **mixed**
* $bgColor **mixed**



### <a name="method-saveImage"></a>saveImage

```php
boolean Image::saveImage(string $filename, integer $quality, string $forcetype)
```

Save the modified image



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L201)


#### Arguments
* $filename **string**
* $quality **integer**
* $forcetype **string**



### <a name="method-showErrors"></a>showErrors

```php
mixed Image::showErrors()
```

show erros



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L100)




### <a name="method-showImage"></a>showImage

```php
boolean Image::showImage(string $type, integer $quality)
```

Shows the masked image without any saving



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.image.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/admin-dev/ajaxfilemanager/inc/class.image.php#L251)


#### Arguments
* $type **string**
* $quality **integer**


