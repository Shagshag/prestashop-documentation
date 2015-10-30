Class imageLib
=====================





* Class name: imageLib
* Source: [admin-dev/filemanager/include/php_image_magician.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L163)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L179).


### <a name="property-$captionBoxPositionArray"></a>$captionBoxPositionArray

```php
private mixed $captionBoxPositionArray = array()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L192).


### <a name="property-$cropFromTopPercent"></a>$cropFromTopPercent

```php
private mixed $cropFromTopPercent = 10
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L196).


### <a name="property-$debug"></a>$debug

```php
private mixed $debug = true
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L175).


### <a name="property-$errorArray"></a>$errorArray

```php
private mixed $errorArray = array()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L176).


### <a name="property-$fileExtension"></a>$fileExtension

```php
private mixed $fileExtension
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L173).


### <a name="property-$fileName"></a>$fileName

```php
private mixed $fileName
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L165).


### <a name="property-$fillColorArray"></a>$fillColorArray

```php
private mixed $fillColorArray = array('r' => 255, 'g' => 255, 'b' => 255)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L183).


### <a name="property-$filterOverlayPath"></a>$filterOverlayPath

```php
private mixed $filterOverlayPath
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L188).


### <a name="property-$fontDir"></a>$fontDir

```php
private mixed $fontDir = 'fonts'
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L194).


### <a name="property-$forceStretch"></a>$forceStretch

```php
private mixed $forceStretch = true
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L178).


### <a name="property-$height"></a>$height

```php
private mixed $height
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L171).


### <a name="property-$heightOriginal"></a>$heightOriginal

```php
private mixed $heightOriginal
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L169).


### <a name="property-$image"></a>$image

```php
private mixed $image
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L166).


### <a name="property-$imageResized"></a>$imageResized

```php
protected mixed $imageResized
```





* Visibility: **protected**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L167).


### <a name="property-$imageSize"></a>$imageSize

```php
private mixed $imageSize
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L172).


### <a name="property-$isInterlace"></a>$isInterlace

```php
private mixed $isInterlace
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L190).


### <a name="property-$keepTransparency"></a>$keepTransparency

```php
private mixed $keepTransparency = true
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L182).


### <a name="property-$psdReaderPath"></a>$psdReaderPath

```php
private mixed $psdReaderPath
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L187).


### <a name="property-$sharpenArray"></a>$sharpenArray

```php
private mixed $sharpenArray = array('jpg')
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L185).


### <a name="property-$transparentArray"></a>$transparentArray

```php
private mixed $transparentArray = array('.png', '.gif')
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L181).


### <a name="property-$width"></a>$width

```php
private mixed $width
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L170).


### <a name="property-$widthOriginal"></a>$widthOriginal

```php
private mixed $widthOriginal
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L168).


Methods
-------


### <a name="method-GD2BMPstring"></a>GD2BMPstring

```php
mixed imageLib::GD2BMPstring($gd_image)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3060](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3060)


#### Arguments
* $gd_image **mixed**



### <a name="method-GetPixelColor"></a>GetPixelColor

```php
mixed imageLib::GetPixelColor($img, $x, $y)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3113)


#### Arguments
* $img **mixed**
* $x **mixed**
* $y **mixed**



### <a name="method-ImageCreateFromBMP"></a>ImageCreateFromBMP

```php
mixed imageLib::ImageCreateFromBMP($filename)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3152)


#### Arguments
* $filename **mixed**



### <a name="method-LittleEndian2String"></a>LittleEndian2String

```php
mixed imageLib::LittleEndian2String($number, $minbytes)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3130)


#### Arguments
* $number **mixed**
* $minbytes **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed imageLib::__construct($fileName)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L201)


#### Arguments
* $fileName **mixed**



### <a name="method-__destruct"></a>__destruct

```php
mixed imageLib::__destruct()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3320)




### <a name="method-addBorder"></a>addBorder

```php
mixed imageLib::addBorder($thickness, $rgbArray)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 919](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L919)


#### Arguments
* $thickness **mixed**
* $rgbArray **mixed**



### <a name="method-addCaptionBox"></a>addCaptionBox

```php
mixed imageLib::addCaptionBox($side, $thickness, $padding, $bgColor, $transparencyAmount)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1585)


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**
* $bgColor **mixed**
* $transparencyAmount **mixed**



### <a name="method-addReflection"></a>addReflection

```php
mixed imageLib::addReflection($reflectionHeight, $startingTransparency, $inside, $bgColor, $stretch, $divider)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1187)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1438)


#### Arguments
* $shadowAngle **mixed**
* $blur **mixed**
* $bgColor **mixed**



### <a name="method-addText"></a>addText

```php
mixed imageLib::addText($text, $pos, $padding, $fontColor, $fontSize, $angle, $font)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2131)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1620](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1620)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2221)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1003)




### <a name="method-borderPreset"></a>borderPreset

```php
mixed imageLib::borderPreset($preset)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L899)


#### Arguments
* $preset **mixed**



### <a name="method-calculateCaptionBoxPosition"></a>calculateCaptionBoxPosition

```php
mixed imageLib::calculateCaptionBoxPosition($side, $thickness, $padding)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1670)


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**



### <a name="method-calculatePosition"></a>calculatePosition

```php
mixed imageLib::calculatePosition($pos, $padding, $assetWidth, $assetHeight, $upperLeft)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2273)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2854)


#### Arguments
* $isEnabled **mixed**



### <a name="method-checkStringStartsWith"></a>checkStringStartsWith

```php
mixed imageLib::checkStringStartsWith($needle, $haystack)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3049](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3049)


#### Arguments
* $needle **mixed**
* $haystack **mixed**



### <a name="method-createImageColor"></a>createImageColor

```php
mixed imageLib::createImageColor($colorArray)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2924](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2924)


#### Arguments
* $colorArray **mixed**



### <a name="method-crop"></a>crop

```php
mixed imageLib::crop($optimalWidth, $optimalHeight, $newWidth, $newHeight, $cropPos)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L438)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L383)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### <a name="method-displayImage"></a>displayImage

```php
mixed imageLib::displayImage($fileType, $imageQuality)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2598](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2598)


#### Arguments
* $fileType **mixed**
* $imageQuality **mixed**



### <a name="method-filterOpacity"></a>filterOpacity

```php
mixed imageLib::filterOpacity($img, $opacity)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2366)


#### Arguments
* $img **mixed**
* $opacity **mixed**



### <a name="method-findSharp"></a>findSharp

```php
mixed imageLib::findSharp($orig, $final)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 840](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L840)


#### Arguments
* $orig **mixed**
* $final **mixed**



### <a name="method-findUnusedBlue"></a>findUnusedBlue

```php
mixed imageLib::findUnusedBlue()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2973](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2973)




### <a name="method-findUnusedGreen"></a>findUnusedGreen

```php
mixed imageLib::findUnusedGreen()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2950](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2950)




### <a name="method-formatColor"></a>formatColor

```php
mixed imageLib::formatColor($value)
```





* Visibility: **protected**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2864)


#### Arguments
* $value **mixed**



### <a name="method-gd_apply_overlay"></a>gd_apply_overlay

```php
mixed imageLib::gd_apply_overlay($im, $type, $amount)
```

Apply a PNG overlay



* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1122)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1095](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1095)




### <a name="method-gd_filter_vintage"></a>gd_filter_vintage

```php
mixed imageLib::gd_filter_vintage()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1107)




### <a name="method-getCropPlacing"></a>getCropPlacing

```php
mixed imageLib::getCropPlacing($optimalWidth, $optimalHeight, $newWidth, $newHeight, $pos)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L469)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L562)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**



### <a name="method-getErrors"></a>getErrors

```php
mixed imageLib::getErrors()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2839)




### <a name="method-getExif"></a>getExif

```php
mixed imageLib::getExif($debug)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1711](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1711)


#### Arguments
* $debug **mixed**



### <a name="method-getFileName"></a>getFileName

```php
mixed imageLib::getFileName()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2796](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2796)




### <a name="method-getHeight"></a>getHeight

```php
mixed imageLib::getHeight()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2811)




### <a name="method-getOptimalCrop"></a>getOptimalCrop

```php
mixed imageLib::getOptimalCrop($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 726](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L726)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getOriginalHeight"></a>getOriginalHeight

```php
mixed imageLib::getOriginalHeight()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2825](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2825)




### <a name="method-getOriginalWidth"></a>getOriginalWidth

```php
mixed imageLib::getOriginalWidth()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2832](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2832)




### <a name="method-getSizeByAuto"></a>getSizeByAuto

```php
mixed imageLib::getSizeByAuto($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 663](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L663)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getSizeByFixedHeight"></a>getSizeByFixedHeight

```php
mixed imageLib::getSizeByFixedHeight($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L621)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getSizeByFixedWidth"></a>getSizeByFixedWidth

```php
mixed imageLib::getSizeByFixedWidth($newWidth, $newHeight)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L642)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getTextFont"></a>getTextFont

```php
mixed imageLib::getTextFont($font)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2169)


#### Arguments
* $font **mixed**



### <a name="method-getTextSize"></a>getTextSize

```php
mixed imageLib::getTextSize($fontSize, $angle, $font, $text)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2201)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2818](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2818)




### <a name="method-greyScale"></a>greyScale

```php
mixed imageLib::greyScale()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 955](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L955)




### <a name="method-greyScaleDramatic"></a>greyScaleDramatic

```php
mixed imageLib::greyScaleDramatic()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 992](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L992)




### <a name="method-greyScaleEnhanced"></a>greyScaleEnhanced

```php
mixed imageLib::greyScaleEnhanced()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 972](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L972)




### <a name="method-hex2dec"></a>hex2dec

```php
mixed imageLib::hex2dec($hex)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2904](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2904)


#### Arguments
* $hex **mixed**



### <a name="method-image_colorize"></a>image_colorize

```php
mixed imageLib::image_colorize($rgb)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1161)


#### Arguments
* $rgb **mixed**



### <a name="method-imagecreatefrompsd"></a>imagecreatefrompsd

```php
mixed imageLib::imagecreatefrompsd($fileName)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3293)


#### Arguments
* $fileName **mixed**



### <a name="method-initialise"></a>initialise

```php
mixed imageLib::initialise()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L258)




### <a name="method-invertTransparency"></a>invertTransparency

```php
mixed imageLib::invertTransparency($value, $originalMax, $invert)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2996](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2996)


#### Arguments
* $value **mixed**
* $originalMax **mixed**
* $invert **mixed**



### <a name="method-iptc_maketag"></a>iptc_maketag

```php
mixed imageLib::iptc_maketag($rec, $dat, $val)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2088](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2088)


#### Arguments
* $rec **mixed**
* $dat **mixed**
* $val **mixed**



### <a name="method-keepTransparancy"></a>keepTransparancy

```php
mixed imageLib::keepTransparancy($width, $height, $im)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L414)


#### Arguments
* $width **mixed**
* $height **mixed**
* $im **mixed**



### <a name="method-negative"></a>negative

```php
mixed imageLib::negative()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1024](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1024)




### <a name="method-openImage"></a>openImage

```php
mixed imageLib::openImage($file)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2433](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2433)


#### Arguments
* $file **mixed**



### <a name="method-prepOption"></a>prepOption

```php
mixed imageLib::prepOption($option)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 861](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L861)


#### Arguments
* $option **mixed**



### <a name="method-reset"></a>reset

```php
mixed imageLib::reset()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2485)




### <a name="method-resizeImage"></a>resizeImage

```php
mixed imageLib::resizeImage($newWidth, $newHeight, $option, $sharpen, $autoRotate)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L274)


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
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1897](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1897)


#### Arguments
* $ep **mixed**



### <a name="method-resolveFlash"></a>resolveFlash

```php
mixed imageLib::resolveFlash($flash)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1974](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1974)


#### Arguments
* $flash **mixed**



### <a name="method-resolveMeteringMode"></a>resolveMeteringMode

```php
mixed imageLib::resolveMeteringMode($mm)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1937)


#### Arguments
* $mm **mixed**



### <a name="method-rotate"></a>rotate

```php
mixed imageLib::rotate($value, $bgColor)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1274)


#### Arguments
* $value **mixed**
* $bgColor **mixed**



### <a name="method-roundCorners"></a>roundCorners

```php
mixed imageLib::roundCorners($radius, $bgColor)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1342)


#### Arguments
* $radius **mixed**
* $bgColor **mixed**



### <a name="method-saveImage"></a>saveImage

```php
mixed imageLib::saveImage($savePath, $imageQuality)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2500)


#### Arguments
* $savePath **mixed**
* $imageQuality **mixed**



### <a name="method-sepia"></a>sepia

```php
mixed imageLib::sepia()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1044](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1044)




### <a name="method-sepia2"></a>sepia2

```php
mixed imageLib::sepia2()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1064](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1064)




### <a name="method-setCropFromTop"></a>setCropFromTop

```php
mixed imageLib::setCropFromTop($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2680)


#### Arguments
* $value **mixed**



### <a name="method-setFile"></a>setFile

```php
mixed imageLib::setFile($fileName)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2781](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2781)


#### Arguments
* $fileName **mixed**



### <a name="method-setFillColor"></a>setFillColor

```php
mixed imageLib::setFillColor($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2662)


#### Arguments
* $value **mixed**



### <a name="method-setForceStretch"></a>setForceStretch

```php
mixed imageLib::setForceStretch($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2766](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2766)


#### Arguments
* $value **mixed**



### <a name="method-setTransparency"></a>setTransparency

```php
mixed imageLib::setTransparency($bool)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2654](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2654)


#### Arguments
* $bool **mixed**



### <a name="method-sharpen"></a>sharpen

```php
mixed imageLib::sharpen()
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 784](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L784)




### <a name="method-sharpen2"></a>sharpen2

```php
mixed imageLib::sharpen2($level)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L829)


#### Arguments
* $level **mixed**



### <a name="method-testColorExists"></a>testColorExists

```php
mixed imageLib::testColorExists($colorArray)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2935](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2935)


#### Arguments
* $colorArray **mixed**



### <a name="method-testEXIFInstalled"></a>testEXIFInstalled

```php
mixed imageLib::testEXIFInstalled()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2709](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2709)




### <a name="method-testFunct"></a>testFunct

```php
mixed imageLib::testFunct()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2751)




### <a name="method-testGDInstalled"></a>testGDInstalled

```php
mixed imageLib::testGDInstalled()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2688)




### <a name="method-testIsImage"></a>testIsImage

```php
mixed imageLib::testIsImage($image)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2730)


#### Arguments
* $image **mixed**



### <a name="method-transparentImage"></a>transparentImage

```php
mixed imageLib::transparentImage($src)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 3021](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L3021)


#### Arguments
* $src **mixed**



### <a name="method-vintage"></a>vintage

```php
mixed imageLib::vintage()
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L1083)




### <a name="method-writeIPTC"></a>writeIPTC

```php
mixed imageLib::writeIPTC($dat, $value)
```





* Visibility: **private**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2076](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2076)


#### Arguments
* $dat **mixed**
* $value **mixed**



### <a name="method-writeIPTCcaption"></a>writeIPTCcaption

```php
mixed imageLib::writeIPTCcaption($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2061](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2061)


#### Arguments
* $value **mixed**



### <a name="method-writeIPTCwriter"></a>writeIPTCwriter

```php
mixed imageLib::writeIPTCwriter($value)
```





* Visibility: **public**
* Source: [admin-dev/filemanager/include/php_image_magician.php line 2069](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/admin-dev/filemanager/include/php_image_magician.php#L2069)


#### Arguments
* $value **mixed**


