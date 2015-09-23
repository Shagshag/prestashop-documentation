Class imageLib
=====================





* Class name: imageLib
* Source: [admin-dev/filemanager/include/php_image_magician.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L163)


Contents
--------


### Properties

* [$aggresiveSharpening](#property-$aggresiveSharpening)
* [$captionBoxPositionArray](#property-$captionBoxPositionArray)
* [$cropFromTopPercent](#property-$cropFromTopPercent)
* [$debug](#property-$debug)
* [$errorArray](#property-$errorArray)
* [$fileExtension](#property-$fileExtension)
* [$fileName](#property-$fileName)
* [$fillColorArray](#property-$fillColorArray)
* [$filterOverlayPath](#property-$filterOverlayPath)
* [$fontDir](#property-$fontDir)
* [$forceStretch](#property-$forceStretch)
* [$height](#property-$height)
* [$heightOriginal](#property-$heightOriginal)
* [$image](#property-$image)
* [$imageResized](#property-$imageResized)
* [$imageSize](#property-$imageSize)
* [$isInterlace](#property-$isInterlace)
* [$keepTransparency](#property-$keepTransparency)
* [$psdReaderPath](#property-$psdReaderPath)
* [$sharpenArray](#property-$sharpenArray)
* [$transparentArray](#property-$transparentArray)
* [$width](#property-$width)
* [$widthOriginal](#property-$widthOriginal)

### Methods

* [GD2BMPstring](#method-GD2BMPstring)
* [GetPixelColor](#method-GetPixelColor)
* [ImageCreateFromBMP](#method-ImageCreateFromBMP)
* [LittleEndian2String](#method-LittleEndian2String)
* [__construct](#method-__construct)
* [__destruct](#method-__destruct)
* [addBorder](#method-addBorder)
* [addCaptionBox](#method-addCaptionBox)
* [addReflection](#method-addReflection)
* [addShadow](#method-addShadow)
* [addText](#method-addText)
* [addTextToCaptionBox](#method-addTextToCaptionBox)
* [addWatermark](#method-addWatermark)
* [blackAndWhite](#method-blackAndWhite)
* [borderPreset](#method-borderPreset)
* [calculateCaptionBoxPosition](#method-calculateCaptionBoxPosition)
* [calculatePosition](#method-calculatePosition)
* [checkInterlaceImage](#method-checkInterlaceImage)
* [checkStringStartsWith](#method-checkStringStartsWith)
* [createImageColor](#method-createImageColor)
* [crop](#method-crop)
* [cropImage](#method-cropImage)
* [displayImage](#method-displayImage)
* [filterOpacity](#method-filterOpacity)
* [findSharp](#method-findSharp)
* [findUnusedBlue](#method-findUnusedBlue)
* [findUnusedGreen](#method-findUnusedGreen)
* [formatColor](#method-formatColor)
* [gd_apply_overlay](#method-gd_apply_overlay)
* [gd_filter_monopin](#method-gd_filter_monopin)
* [gd_filter_vintage](#method-gd_filter_vintage)
* [getCropPlacing](#method-getCropPlacing)
* [getDimensions](#method-getDimensions)
* [getErrors](#method-getErrors)
* [getExif](#method-getExif)
* [getFileName](#method-getFileName)
* [getHeight](#method-getHeight)
* [getOptimalCrop](#method-getOptimalCrop)
* [getOriginalHeight](#method-getOriginalHeight)
* [getOriginalWidth](#method-getOriginalWidth)
* [getSizeByAuto](#method-getSizeByAuto)
* [getSizeByFixedHeight](#method-getSizeByFixedHeight)
* [getSizeByFixedWidth](#method-getSizeByFixedWidth)
* [getTextFont](#method-getTextFont)
* [getTextSize](#method-getTextSize)
* [getWidth](#method-getWidth)
* [greyScale](#method-greyScale)
* [greyScaleDramatic](#method-greyScaleDramatic)
* [greyScaleEnhanced](#method-greyScaleEnhanced)
* [hex2dec](#method-hex2dec)
* [image_colorize](#method-image_colorize)
* [imagecreatefrompsd](#method-imagecreatefrompsd)
* [initialise](#method-initialise)
* [invertTransparency](#method-invertTransparency)
* [iptc_maketag](#method-iptc_maketag)
* [keepTransparancy](#method-keepTransparancy)
* [negative](#method-negative)
* [openImage](#method-openImage)
* [prepOption](#method-prepOption)
* [reset](#method-reset)
* [resizeImage](#method-resizeImage)
* [resolveExposureProgram](#method-resolveExposureProgram)
* [resolveFlash](#method-resolveFlash)
* [resolveMeteringMode](#method-resolveMeteringMode)
* [rotate](#method-rotate)
* [roundCorners](#method-roundCorners)
* [saveImage](#method-saveImage)
* [sepia](#method-sepia)
* [sepia2](#method-sepia2)
* [setCropFromTop](#method-setCropFromTop)
* [setFile](#method-setFile)
* [setFillColor](#method-setFillColor)
* [setForceStretch](#method-setForceStretch)
* [setTransparency](#method-setTransparency)
* [sharpen](#method-sharpen)
* [sharpen2](#method-sharpen2)
* [testColorExists](#method-testColorExists)
* [testEXIFInstalled](#method-testEXIFInstalled)
* [testFunct](#method-testFunct)
* [testGDInstalled](#method-testGDInstalled)
* [testIsImage](#method-testIsImage)
* [transparentImage](#method-transparentImage)
* [vintage](#method-vintage)
* [writeIPTC](#method-writeIPTC)
* [writeIPTCcaption](#method-writeIPTCcaption)
* [writeIPTCwriter](#method-writeIPTCwriter)




Properties
----------


### <a name="property-$aggresiveSharpening"></a>$aggresiveSharpening

```php
private mixed $aggresiveSharpening = false
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L180).


### <a name="property-$captionBoxPositionArray"></a>$captionBoxPositionArray

```php
private mixed $captionBoxPositionArray = array()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L193).


### <a name="property-$cropFromTopPercent"></a>$cropFromTopPercent

```php
private mixed $cropFromTopPercent = 10
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L197).


### <a name="property-$debug"></a>$debug

```php
private mixed $debug = true
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L176).


### <a name="property-$errorArray"></a>$errorArray

```php
private mixed $errorArray = array()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L177).


### <a name="property-$fileExtension"></a>$fileExtension

```php
private mixed $fileExtension
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L174).


### <a name="property-$fileName"></a>$fileName

```php
private mixed $fileName
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L166).


### <a name="property-$fillColorArray"></a>$fillColorArray

```php
private mixed $fillColorArray = array('r' => 255, 'g' => 255, 'b' => 255)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L184).


### <a name="property-$filterOverlayPath"></a>$filterOverlayPath

```php
private mixed $filterOverlayPath
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L189).


### <a name="property-$fontDir"></a>$fontDir

```php
private mixed $fontDir = 'fonts'
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L195).


### <a name="property-$forceStretch"></a>$forceStretch

```php
private mixed $forceStretch = true
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L179).


### <a name="property-$height"></a>$height

```php
private mixed $height
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L172).


### <a name="property-$heightOriginal"></a>$heightOriginal

```php
private mixed $heightOriginal
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L170).


### <a name="property-$image"></a>$image

```php
private mixed $image
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L167).


### <a name="property-$imageResized"></a>$imageResized

```php
protected mixed $imageResized
```





* Visibility: **protected**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L168).


### <a name="property-$imageSize"></a>$imageSize

```php
private mixed $imageSize
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L173).


### <a name="property-$isInterlace"></a>$isInterlace

```php
private mixed $isInterlace
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L191).


### <a name="property-$keepTransparency"></a>$keepTransparency

```php
private mixed $keepTransparency = true
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L183).


### <a name="property-$psdReaderPath"></a>$psdReaderPath

```php
private mixed $psdReaderPath
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L188).


### <a name="property-$sharpenArray"></a>$sharpenArray

```php
private mixed $sharpenArray = array('jpg')
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L186).


### <a name="property-$transparentArray"></a>$transparentArray

```php
private mixed $transparentArray = array('.png', '.gif')
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L182).


### <a name="property-$width"></a>$width

```php
private mixed $width
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L171).


### <a name="property-$widthOriginal"></a>$widthOriginal

```php
private mixed $widthOriginal
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L169).


Methods
-------


### <a name="method-GD2BMPstring"></a>GD2BMPstring

```php
mixed imageLib::GD2BMPstring($gd_image)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3004](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L3004)


#### Arguments
* $gd_image **mixed**



### <a name="method-GetPixelColor"></a>GetPixelColor

```php
mixed imageLib::GetPixelColor($img, $x, $y)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3057](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L3057)


#### Arguments
* $img **mixed**
* $x **mixed**
* $y **mixed**



### <a name="method-ImageCreateFromBMP"></a>ImageCreateFromBMP

```php
mixed imageLib::ImageCreateFromBMP($filename)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3096](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L3096)


#### Arguments
* $filename **mixed**



### <a name="method-LittleEndian2String"></a>LittleEndian2String

```php
mixed imageLib::LittleEndian2String($number, $minbytes)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3074](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L3074)


#### Arguments
* $number **mixed**
* $minbytes **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed imageLib::__construct($fileName)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L202)


#### Arguments
* $fileName **mixed**



### <a name="method-__destruct"></a>__destruct

```php
mixed imageLib::__destruct()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L3253)




### <a name="method-addBorder"></a>addBorder

```php
mixed imageLib::addBorder($thickness, $rgbArray)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 919](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L919)


#### Arguments
* $thickness **mixed**
* $rgbArray **mixed**



### <a name="method-addCaptionBox"></a>addCaptionBox

```php
mixed imageLib::addCaptionBox($side, $thickness, $padding, $bgColor, $transaprencyAmount)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1597](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1597)


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**
* $bgColor **mixed**
* $transaprencyAmount **mixed**



### <a name="method-addReflection"></a>addReflection

```php
mixed imageLib::addReflection($reflectionHeight, $startingTransparency, $inside, $bgColor, $stretch, $divider)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1198)


#### Arguments
* $reflectionHeight **mixed**
* $startingTransparency **mixed**
* $inside **mixed**
* $bgColor **mixed**
* $stretch **mixed**
* $divider **mixed**



### <a name="method-addShadow"></a>addShadow

```php
mixed imageLib::addShadow($shadowAngle, $blur, $bgColor)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1448](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1448)


#### Arguments
* $shadowAngle **mixed**
* $blur **mixed**
* $bgColor **mixed**



### <a name="method-addText"></a>addText

```php
mixed imageLib::addText($text, $pos, $padding, $fontColor, $fontSize, $angle, $font)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2080](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2080)


#### Arguments
* $text **mixed**
* $pos **mixed**
* $padding **mixed**
* $fontColor **mixed**
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**



### <a name="method-addTextToCaptionBox"></a>addTextToCaptionBox

```php
mixed imageLib::addTextToCaptionBox($text, $fontColor, $fontSize, $angle, $font)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1632](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1632)


#### Arguments
* $text **mixed**
* $fontColor **mixed**
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**



### <a name="method-addWatermark"></a>addWatermark

```php
mixed imageLib::addWatermark($watermarkImage, $pos, $padding, $opacity)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2167)


#### Arguments
* $watermarkImage **mixed**
* $pos **mixed**
* $padding **mixed**
* $opacity **mixed**



### <a name="method-blackAndWhite"></a>blackAndWhite

```php
mixed imageLib::blackAndWhite()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1005](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1005)




### <a name="method-borderPreset"></a>borderPreset

```php
mixed imageLib::borderPreset($preset)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 897](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L897)


#### Arguments
* $preset **mixed**



### <a name="method-calculateCaptionBoxPosition"></a>calculateCaptionBoxPosition

```php
mixed imageLib::calculateCaptionBoxPosition($side, $thickness, $padding)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1679](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1679)


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**



### <a name="method-calculatePosition"></a>calculatePosition

```php
mixed imageLib::calculatePosition($pos, $padding, $assetWidth, $assetHeight, $upperLeft)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2221)


#### Arguments
* $pos **mixed**
* $padding **mixed**
* $assetWidth **mixed**
* $assetHeight **mixed**
* $upperLeft **mixed**



### <a name="method-checkInterlaceImage"></a>checkInterlaceImage

```php
mixed imageLib::checkInterlaceImage($isEnabled)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2789](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2789)


#### Arguments
* $isEnabled **mixed**



### <a name="method-checkStringStartsWith"></a>checkStringStartsWith

```php
mixed imageLib::checkStringStartsWith($needle, $haystack)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2993](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2993)


#### Arguments
* $needle **mixed**
* $haystack **mixed**



### <a name="method-createImageColor"></a>createImageColor

```php
mixed imageLib::createImageColor($colorArray)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2864](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2864)


#### Arguments
* $colorArray **mixed**



### <a name="method-crop"></a>crop

```php
mixed imageLib::crop($optimalWidth, $optimalHeight, $newWidth, $newHeight, $cropPos)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L427)


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### <a name="method-cropImage"></a>cropImage

```php
mixed imageLib::cropImage($newWidth, $newHeight, $cropPos)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L377)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### <a name="method-displayImage"></a>displayImage

```php
mixed imageLib::displayImage($fileType, $imageQuality)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2528](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2528)


#### Arguments
* $fileType **mixed**
* $imageQuality **mixed**



### <a name="method-filterOpacity"></a>filterOpacity

```php
mixed imageLib::filterOpacity($img, $opacity)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2316)


#### Arguments
* $img **mixed**
* $opacity **mixed**



### <a name="method-findSharp"></a>findSharp

```php
mixed imageLib::findSharp($orig, $final)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L838)


#### Arguments
* $orig **mixed**
* $final **mixed**



### <a name="method-findUnusedBlue"></a>findUnusedBlue

```php
mixed imageLib::findUnusedBlue()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2915](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2915)




### <a name="method-findUnusedGreen"></a>findUnusedGreen

```php
mixed imageLib::findUnusedGreen()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2890](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2890)




### <a name="method-formatColor"></a>formatColor

```php
mixed imageLib::formatColor($value)
```





* Visibility: **protected**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2799](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2799)


#### Arguments
* $value **mixed**



### <a name="method-gd_apply_overlay"></a>gd_apply_overlay

```php
mixed imageLib::gd_apply_overlay($im, $type, $amount)
```

Apply a PNG overlay



* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1133)


#### Arguments
* $im **mixed**
* $type **mixed**
* $amount **mixed**



### <a name="method-gd_filter_monopin"></a>gd_filter_monopin

```php
mixed imageLib::gd_filter_monopin()
```

Apply 'Monopin' preset



* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1105)




### <a name="method-gd_filter_vintage"></a>gd_filter_vintage

```php
mixed imageLib::gd_filter_vintage()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1118)




### <a name="method-getCropPlacing"></a>getCropPlacing

```php
mixed imageLib::getCropPlacing($optimalWidth, $optimalHeight, $newWidth, $newHeight, $pos)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L459)


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $pos **mixed**



### <a name="method-getDimensions"></a>getDimensions

```php
mixed imageLib::getDimensions($newWidth, $newHeight, $option)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L554)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**



### <a name="method-getErrors"></a>getErrors

```php
mixed imageLib::getErrors()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2774](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2774)




### <a name="method-getExif"></a>getExif

```php
mixed imageLib::getExif($debug)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1721](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1721)


#### Arguments
* $debug **mixed**



### <a name="method-getFileName"></a>getFileName

```php
mixed imageLib::getFileName()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2731](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2731)




### <a name="method-getHeight"></a>getHeight

```php
mixed imageLib::getHeight()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2746](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2746)




### <a name="method-getOptimalCrop"></a>getOptimalCrop

```php
mixed imageLib::getOptimalCrop($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L722)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getOriginalHeight"></a>getOriginalHeight

```php
mixed imageLib::getOriginalHeight()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2760](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2760)




### <a name="method-getOriginalWidth"></a>getOriginalWidth

```php
mixed imageLib::getOriginalWidth()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2767)




### <a name="method-getSizeByAuto"></a>getSizeByAuto

```php
mixed imageLib::getSizeByAuto($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L657)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getSizeByFixedHeight"></a>getSizeByFixedHeight

```php
mixed imageLib::getSizeByFixedHeight($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L615)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getSizeByFixedWidth"></a>getSizeByFixedWidth

```php
mixed imageLib::getSizeByFixedWidth($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L636)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getTextFont"></a>getTextFont

```php
mixed imageLib::getTextFont($font)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2118)


#### Arguments
* $font **mixed**



### <a name="method-getTextSize"></a>getTextSize

```php
mixed imageLib::getTextSize($fontSize, $angle, $font, $text)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2147)


#### Arguments
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**
* $text **mixed**



### <a name="method-getWidth"></a>getWidth

```php
mixed imageLib::getWidth()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2753](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2753)




### <a name="method-greyScale"></a>greyScale

```php
mixed imageLib::greyScale()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 956](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L956)




### <a name="method-greyScaleDramatic"></a>greyScaleDramatic

```php
mixed imageLib::greyScaleDramatic()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 994](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L994)




### <a name="method-greyScaleEnhanced"></a>greyScaleEnhanced

```php
mixed imageLib::greyScaleEnhanced()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 974](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L974)




### <a name="method-hex2dec"></a>hex2dec

```php
mixed imageLib::hex2dec($hex)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2844](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2844)


#### Arguments
* $hex **mixed**



### <a name="method-image_colorize"></a>image_colorize

```php
mixed imageLib::image_colorize($rgb)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1172)


#### Arguments
* $rgb **mixed**



### <a name="method-imagecreatefrompsd"></a>imagecreatefrompsd

```php
mixed imageLib::imagecreatefrompsd($fileName)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3227](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L3227)


#### Arguments
* $fileName **mixed**



### <a name="method-initialise"></a>initialise

```php
mixed imageLib::initialise()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L255)




### <a name="method-invertTransparency"></a>invertTransparency

```php
mixed imageLib::invertTransparency($value, $originalMax, $invert)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2940](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2940)


#### Arguments
* $value **mixed**
* $originalMax **mixed**
* $invert **mixed**



### <a name="method-iptc_maketag"></a>iptc_maketag

```php
mixed imageLib::iptc_maketag($rec, $dat, $val)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2038](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2038)


#### Arguments
* $rec **mixed**
* $dat **mixed**
* $val **mixed**



### <a name="method-keepTransparancy"></a>keepTransparancy

```php
mixed imageLib::keepTransparancy($width, $height, $im)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L403)


#### Arguments
* $width **mixed**
* $height **mixed**
* $im **mixed**



### <a name="method-negative"></a>negative

```php
mixed imageLib::negative()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1028](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1028)




### <a name="method-openImage"></a>openImage

```php
mixed imageLib::openImage($file)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2384](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2384)


#### Arguments
* $file **mixed**



### <a name="method-prepOption"></a>prepOption

```php
mixed imageLib::prepOption($option)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 859](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L859)


#### Arguments
* $option **mixed**



### <a name="method-reset"></a>reset

```php
mixed imageLib::reset()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2432](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2432)




### <a name="method-resizeImage"></a>resizeImage

```php
mixed imageLib::resizeImage($newWidth, $newHeight, $option, $sharpen, $autoRotate)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L271)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**
* $sharpen **mixed**
* $autoRotate **mixed**



### <a name="method-resolveExposureProgram"></a>resolveExposureProgram

```php
mixed imageLib::resolveExposureProgram($ep)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1846](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1846)


#### Arguments
* $ep **mixed**



### <a name="method-resolveFlash"></a>resolveFlash

```php
mixed imageLib::resolveFlash($flash)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1923](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1923)


#### Arguments
* $flash **mixed**



### <a name="method-resolveMeteringMode"></a>resolveMeteringMode

```php
mixed imageLib::resolveMeteringMode($mm)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1886](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1886)


#### Arguments
* $mm **mixed**



### <a name="method-rotate"></a>rotate

```php
mixed imageLib::rotate($value, $bgColor)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1283)


#### Arguments
* $value **mixed**
* $bgColor **mixed**



### <a name="method-roundCorners"></a>roundCorners

```php
mixed imageLib::roundCorners($radius, $bgColor)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1353](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1353)


#### Arguments
* $radius **mixed**
* $bgColor **mixed**



### <a name="method-saveImage"></a>saveImage

```php
mixed imageLib::saveImage($savePath, $imageQuality)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2447)


#### Arguments
* $savePath **mixed**
* $imageQuality **mixed**



### <a name="method-sepia"></a>sepia

```php
mixed imageLib::sepia()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1050](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1050)




### <a name="method-sepia2"></a>sepia2

```php
mixed imageLib::sepia2()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1070](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1070)




### <a name="method-setCropFromTop"></a>setCropFromTop

```php
mixed imageLib::setCropFromTop($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2606)


#### Arguments
* $value **mixed**



### <a name="method-setFile"></a>setFile

```php
mixed imageLib::setFile($fileName)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2716](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2716)


#### Arguments
* $fileName **mixed**



### <a name="method-setFillColor"></a>setFillColor

```php
mixed imageLib::setFillColor($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2588](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2588)


#### Arguments
* $value **mixed**



### <a name="method-setForceStretch"></a>setForceStretch

```php
mixed imageLib::setForceStretch($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2701](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2701)


#### Arguments
* $value **mixed**



### <a name="method-setTransparency"></a>setTransparency

```php
mixed imageLib::setTransparency($bool)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2580](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2580)


#### Arguments
* $bool **mixed**



### <a name="method-sharpen"></a>sharpen

```php
mixed imageLib::sharpen()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L780)




### <a name="method-sharpen2"></a>sharpen2

```php
mixed imageLib::sharpen2($level)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 826](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L826)


#### Arguments
* $level **mixed**



### <a name="method-testColorExists"></a>testColorExists

```php
mixed imageLib::testColorExists($colorArray)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2875](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2875)


#### Arguments
* $colorArray **mixed**



### <a name="method-testEXIFInstalled"></a>testEXIFInstalled

```php
mixed imageLib::testEXIFInstalled()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2638)




### <a name="method-testFunct"></a>testFunct

```php
mixed imageLib::testFunct()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2686](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2686)




### <a name="method-testGDInstalled"></a>testGDInstalled

```php
mixed imageLib::testGDInstalled()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2614](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2614)




### <a name="method-testIsImage"></a>testIsImage

```php
mixed imageLib::testIsImage($image)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2662](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2662)


#### Arguments
* $image **mixed**



### <a name="method-transparentImage"></a>transparentImage

```php
mixed imageLib::transparentImage($src)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2965](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2965)


#### Arguments
* $src **mixed**



### <a name="method-vintage"></a>vintage

```php
mixed imageLib::vintage()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1093](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L1093)




### <a name="method-writeIPTC"></a>writeIPTC

```php
mixed imageLib::writeIPTC($dat, $value)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2026](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2026)


#### Arguments
* $dat **mixed**
* $value **mixed**



### <a name="method-writeIPTCcaption"></a>writeIPTCcaption

```php
mixed imageLib::writeIPTCcaption($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2011](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2011)


#### Arguments
* $value **mixed**



### <a name="method-writeIPTCwriter"></a>writeIPTCwriter

```php
mixed imageLib::writeIPTCwriter($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2019](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/admin-dev/filemanager/include/php_image_magician.php#L2019)


#### Arguments
* $value **mixed**


