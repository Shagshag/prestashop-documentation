imageLib
===============






* Class name: imageLib
* This class is defined in [admin/filemanager/include/php_image_magician.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L163)





Properties
----------

* [$fileName](#property-$fileName)
* [$image](#property-$image)
* [$imageResized](#property-$imageResized)
* [$widthOriginal](#property-$widthOriginal)
* [$heightOriginal](#property-$heightOriginal)
* [$width](#property-$width)
* [$height](#property-$height)
* [$imageSize](#property-$imageSize)
* [$fileExtension](#property-$fileExtension)
* [$debug](#property-$debug)
* [$errorArray](#property-$errorArray)
* [$forceStretch](#property-$forceStretch)
* [$aggresiveSharpening](#property-$aggresiveSharpening)
* [$transparentArray](#property-$transparentArray)
* [$keepTransparency](#property-$keepTransparency)
* [$fillColorArray](#property-$fillColorArray)
* [$sharpenArray](#property-$sharpenArray)
* [$psdReaderPath](#property-$psdReaderPath)
* [$filterOverlayPath](#property-$filterOverlayPath)
* [$isInterlace](#property-$isInterlace)
* [$captionBoxPositionArray](#property-$captionBoxPositionArray)
* [$fontDir](#property-$fontDir)
* [$cropFromTopPercent](#property-$cropFromTopPercent)

Methods
-------
* [__construct](#method-__construct)
* [initialise](#method-initialise)
* [resizeImage](#method-resizeImage)
* [cropImage](#method-cropImage)
* [keepTransparancy](#method-keepTransparancy)
* [crop](#method-crop)
* [getCropPlacing](#method-getCropPlacing)
* [getDimensions](#method-getDimensions)
* [getSizeByFixedHeight](#method-getSizeByFixedHeight)
* [getSizeByFixedWidth](#method-getSizeByFixedWidth)
* [getSizeByAuto](#method-getSizeByAuto)
* [getOptimalCrop](#method-getOptimalCrop)
* [sharpen](#method-sharpen)
* [sharpen2](#method-sharpen2)
* [findSharp](#method-findSharp)
* [prepOption](#method-prepOption)
* [borderPreset](#method-borderPreset)
* [addBorder](#method-addBorder)
* [greyScale](#method-greyScale)
* [greyScaleEnhanced](#method-greyScaleEnhanced)
* [greyScaleDramatic](#method-greyScaleDramatic)
* [blackAndWhite](#method-blackAndWhite)
* [negative](#method-negative)
* [sepia](#method-sepia)
* [sepia2](#method-sepia2)
* [vintage](#method-vintage)
* [gd_filter_monopin](#method-gd_filter_monopin)
* [gd_filter_vintage](#method-gd_filter_vintage)
* [gd_apply_overlay](#method-gd_apply_overlay)
* [image_colorize](#method-image_colorize)
* [addReflection](#method-addReflection)
* [rotate](#method-rotate)
* [roundCorners](#method-roundCorners)
* [addShadow](#method-addShadow)
* [addCaptionBox](#method-addCaptionBox)
* [addTextToCaptionBox](#method-addTextToCaptionBox)
* [calculateCaptionBoxPosition](#method-calculateCaptionBoxPosition)
* [getExif](#method-getExif)
* [resolveExposureProgram](#method-resolveExposureProgram)
* [resolveMeteringMode](#method-resolveMeteringMode)
* [resolveFlash](#method-resolveFlash)
* [writeIPTCcaption](#method-writeIPTCcaption)
* [writeIPTCwriter](#method-writeIPTCwriter)
* [writeIPTC](#method-writeIPTC)
* [iptc_maketag](#method-iptc_maketag)
* [addText](#method-addText)
* [getTextFont](#method-getTextFont)
* [getTextSize](#method-getTextSize)
* [addWatermark](#method-addWatermark)
* [calculatePosition](#method-calculatePosition)
* [filterOpacity](#method-filterOpacity)
* [openImage](#method-openImage)
* [reset](#method-reset)
* [saveImage](#method-saveImage)
* [displayImage](#method-displayImage)
* [setTransparency](#method-setTransparency)
* [setFillColor](#method-setFillColor)
* [setCropFromTop](#method-setCropFromTop)
* [testGDInstalled](#method-testGDInstalled)
* [testEXIFInstalled](#method-testEXIFInstalled)
* [testIsImage](#method-testIsImage)
* [testFunct](#method-testFunct)
* [setForceStretch](#method-setForceStretch)
* [setFile](#method-setFile)
* [getFileName](#method-getFileName)
* [getHeight](#method-getHeight)
* [getWidth](#method-getWidth)
* [getOriginalHeight](#method-getOriginalHeight)
* [getOriginalWidth](#method-getOriginalWidth)
* [getErrors](#method-getErrors)
* [checkInterlaceImage](#method-checkInterlaceImage)
* [formatColor](#method-formatColor)
* [hex2dec](#method-hex2dec)
* [createImageColor](#method-createImageColor)
* [testColorExists](#method-testColorExists)
* [findUnusedGreen](#method-findUnusedGreen)
* [findUnusedBlue](#method-findUnusedBlue)
* [invertTransparency](#method-invertTransparency)
* [transparentImage](#method-transparentImage)
* [checkStringStartsWith](#method-checkStringStartsWith)
* [GD2BMPstring](#method-GD2BMPstring)
* [GetPixelColor](#method-GetPixelColor)
* [LittleEndian2String](#method-LittleEndian2String)
* [ImageCreateFromBMP](#method-ImageCreateFromBMP)
* [imagecreatefrompsd](#method-imagecreatefrompsd)
* [__destruct](#method-__destruct)




Properties
----------


### <a name="property-$fileName"></a>$fileName

    private mixed $fileName





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L165)


### <a name="property-$image"></a>$image

    private mixed $image





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L166)


### <a name="property-$imageResized"></a>$imageResized

    protected mixed $imageResized





* Visibility: **protected**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L167)


### <a name="property-$widthOriginal"></a>$widthOriginal

    private mixed $widthOriginal





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L168)


### <a name="property-$heightOriginal"></a>$heightOriginal

    private mixed $heightOriginal





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L169)


### <a name="property-$width"></a>$width

    private mixed $width





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L170)


### <a name="property-$height"></a>$height

    private mixed $height





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L171)


### <a name="property-$imageSize"></a>$imageSize

    private mixed $imageSize





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L172)


### <a name="property-$fileExtension"></a>$fileExtension

    private mixed $fileExtension





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L173)


### <a name="property-$debug"></a>$debug

    private mixed $debug = true





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L175)


### <a name="property-$errorArray"></a>$errorArray

    private mixed $errorArray = array()





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L176)


### <a name="property-$forceStretch"></a>$forceStretch

    private mixed $forceStretch = true





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L178)


### <a name="property-$aggresiveSharpening"></a>$aggresiveSharpening

    private mixed $aggresiveSharpening = false





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L179)


### <a name="property-$transparentArray"></a>$transparentArray

    private mixed $transparentArray = array('.png', '.gif')





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L181)


### <a name="property-$keepTransparency"></a>$keepTransparency

    private mixed $keepTransparency = true





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L182)


### <a name="property-$fillColorArray"></a>$fillColorArray

    private mixed $fillColorArray = array('r' => 255, 'g' => 255, 'b' => 255)





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L183)


### <a name="property-$sharpenArray"></a>$sharpenArray

    private mixed $sharpenArray = array('jpg')





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L185)


### <a name="property-$psdReaderPath"></a>$psdReaderPath

    private mixed $psdReaderPath





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L187)


### <a name="property-$filterOverlayPath"></a>$filterOverlayPath

    private mixed $filterOverlayPath





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L188)


### <a name="property-$isInterlace"></a>$isInterlace

    private mixed $isInterlace





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L190)


### <a name="property-$captionBoxPositionArray"></a>$captionBoxPositionArray

    private mixed $captionBoxPositionArray = array()





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L192)


### <a name="property-$fontDir"></a>$fontDir

    private mixed $fontDir = 'fonts'





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L194)


### <a name="property-$cropFromTopPercent"></a>$cropFromTopPercent

    private mixed $cropFromTopPercent = 10





* Visibility: **private**
* This property is defined in [admin/filemanager/include/php_image_magician.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L196)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed imageLib::__construct($fileName)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L201)


#### Arguments
* $fileName **mixed**



### <a name="method-initialise"></a>initialise

    mixed imageLib::initialise()





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L258)




### <a name="method-resizeImage"></a>resizeImage

    mixed imageLib::resizeImage($newWidth, $newHeight, $option, $sharpen, $autoRotate)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L274)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**
* $sharpen **mixed**
* $autoRotate **mixed**



### <a name="method-cropImage"></a>cropImage

    mixed imageLib::cropImage($newWidth, $newHeight, $cropPos)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L383)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### <a name="method-keepTransparancy"></a>keepTransparancy

    mixed imageLib::keepTransparancy($width, $height, $im)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L414)


#### Arguments
* $width **mixed**
* $height **mixed**
* $im **mixed**



### <a name="method-crop"></a>crop

    mixed imageLib::crop($optimalWidth, $optimalHeight, $newWidth, $newHeight, $cropPos)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L438)


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### <a name="method-getCropPlacing"></a>getCropPlacing

    mixed imageLib::getCropPlacing($optimalWidth, $optimalHeight, $newWidth, $newHeight, $pos)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L469)


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $pos **mixed**



### <a name="method-getDimensions"></a>getDimensions

    mixed imageLib::getDimensions($newWidth, $newHeight, $option)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L562)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**



### <a name="method-getSizeByFixedHeight"></a>getSizeByFixedHeight

    mixed imageLib::getSizeByFixedHeight($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L621)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getSizeByFixedWidth"></a>getSizeByFixedWidth

    mixed imageLib::getSizeByFixedWidth($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L642)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getSizeByAuto"></a>getSizeByAuto

    mixed imageLib::getSizeByAuto($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 663](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L663)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-getOptimalCrop"></a>getOptimalCrop

    mixed imageLib::getOptimalCrop($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 726](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L726)


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### <a name="method-sharpen"></a>sharpen

    mixed imageLib::sharpen()





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 784](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L784)




### <a name="method-sharpen2"></a>sharpen2

    mixed imageLib::sharpen2($level)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L829)


#### Arguments
* $level **mixed**



### <a name="method-findSharp"></a>findSharp

    mixed imageLib::findSharp($orig, $final)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 840](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L840)


#### Arguments
* $orig **mixed**
* $final **mixed**



### <a name="method-prepOption"></a>prepOption

    mixed imageLib::prepOption($option)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 861](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L861)


#### Arguments
* $option **mixed**



### <a name="method-borderPreset"></a>borderPreset

    mixed imageLib::borderPreset($preset)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L899)


#### Arguments
* $preset **mixed**



### <a name="method-addBorder"></a>addBorder

    mixed imageLib::addBorder($thickness, $rgbArray)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 919](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L919)


#### Arguments
* $thickness **mixed**
* $rgbArray **mixed**



### <a name="method-greyScale"></a>greyScale

    mixed imageLib::greyScale()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 955](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L955)




### <a name="method-greyScaleEnhanced"></a>greyScaleEnhanced

    mixed imageLib::greyScaleEnhanced()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 972](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L972)




### <a name="method-greyScaleDramatic"></a>greyScaleDramatic

    mixed imageLib::greyScaleDramatic()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 992](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L992)




### <a name="method-blackAndWhite"></a>blackAndWhite

    mixed imageLib::blackAndWhite()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1003)




### <a name="method-negative"></a>negative

    mixed imageLib::negative()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1024](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1024)




### <a name="method-sepia"></a>sepia

    mixed imageLib::sepia()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1044](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1044)




### <a name="method-sepia2"></a>sepia2

    mixed imageLib::sepia2()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1064](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1064)




### <a name="method-vintage"></a>vintage

    mixed imageLib::vintage()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1083)




### <a name="method-gd_filter_monopin"></a>gd_filter_monopin

    mixed imageLib::gd_filter_monopin()

Apply 'Monopin' preset



* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1095](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1095)




### <a name="method-gd_filter_vintage"></a>gd_filter_vintage

    mixed imageLib::gd_filter_vintage()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1107)




### <a name="method-gd_apply_overlay"></a>gd_apply_overlay

    mixed imageLib::gd_apply_overlay($im, $type, $amount)

Apply a PNG overlay



* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1122)


#### Arguments
* $im **mixed**
* $type **mixed**
* $amount **mixed**



### <a name="method-image_colorize"></a>image_colorize

    mixed imageLib::image_colorize($rgb)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1161)


#### Arguments
* $rgb **mixed**



### <a name="method-addReflection"></a>addReflection

    mixed imageLib::addReflection($reflectionHeight, $startingTransparency, $inside, $bgColor, $stretch, $divider)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1187)


#### Arguments
* $reflectionHeight **mixed**
* $startingTransparency **mixed**
* $inside **mixed**
* $bgColor **mixed**
* $stretch **mixed**
* $divider **mixed**



### <a name="method-rotate"></a>rotate

    mixed imageLib::rotate($value, $bgColor)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1274)


#### Arguments
* $value **mixed**
* $bgColor **mixed**



### <a name="method-roundCorners"></a>roundCorners

    mixed imageLib::roundCorners($radius, $bgColor)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1342)


#### Arguments
* $radius **mixed**
* $bgColor **mixed**



### <a name="method-addShadow"></a>addShadow

    mixed imageLib::addShadow($shadowAngle, $blur, $bgColor)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1438)


#### Arguments
* $shadowAngle **mixed**
* $blur **mixed**
* $bgColor **mixed**



### <a name="method-addCaptionBox"></a>addCaptionBox

    mixed imageLib::addCaptionBox($side, $thickness, $padding, $bgColor, $transparencyAmount)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1585)


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**
* $bgColor **mixed**
* $transparencyAmount **mixed**



### <a name="method-addTextToCaptionBox"></a>addTextToCaptionBox

    mixed imageLib::addTextToCaptionBox($text, $fontColor, $fontSize, $angle, $font)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1620](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1620)


#### Arguments
* $text **mixed**
* $fontColor **mixed**
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**



### <a name="method-calculateCaptionBoxPosition"></a>calculateCaptionBoxPosition

    mixed imageLib::calculateCaptionBoxPosition($side, $thickness, $padding)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1670)


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**



### <a name="method-getExif"></a>getExif

    mixed imageLib::getExif($debug)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1711](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1711)


#### Arguments
* $debug **mixed**



### <a name="method-resolveExposureProgram"></a>resolveExposureProgram

    mixed imageLib::resolveExposureProgram($ep)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1897](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1897)


#### Arguments
* $ep **mixed**



### <a name="method-resolveMeteringMode"></a>resolveMeteringMode

    mixed imageLib::resolveMeteringMode($mm)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1937)


#### Arguments
* $mm **mixed**



### <a name="method-resolveFlash"></a>resolveFlash

    mixed imageLib::resolveFlash($flash)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 1974](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L1974)


#### Arguments
* $flash **mixed**



### <a name="method-writeIPTCcaption"></a>writeIPTCcaption

    mixed imageLib::writeIPTCcaption($value)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2061](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2061)


#### Arguments
* $value **mixed**



### <a name="method-writeIPTCwriter"></a>writeIPTCwriter

    mixed imageLib::writeIPTCwriter($value)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2069](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2069)


#### Arguments
* $value **mixed**



### <a name="method-writeIPTC"></a>writeIPTC

    mixed imageLib::writeIPTC($dat, $value)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2076](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2076)


#### Arguments
* $dat **mixed**
* $value **mixed**



### <a name="method-iptc_maketag"></a>iptc_maketag

    mixed imageLib::iptc_maketag($rec, $dat, $val)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2088](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2088)


#### Arguments
* $rec **mixed**
* $dat **mixed**
* $val **mixed**



### <a name="method-addText"></a>addText

    mixed imageLib::addText($text, $pos, $padding, $fontColor, $fontSize, $angle, $font)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2131)


#### Arguments
* $text **mixed**
* $pos **mixed**
* $padding **mixed**
* $fontColor **mixed**
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**



### <a name="method-getTextFont"></a>getTextFont

    mixed imageLib::getTextFont($font)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2169)


#### Arguments
* $font **mixed**



### <a name="method-getTextSize"></a>getTextSize

    mixed imageLib::getTextSize($fontSize, $angle, $font, $text)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2201)


#### Arguments
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**
* $text **mixed**



### <a name="method-addWatermark"></a>addWatermark

    mixed imageLib::addWatermark($watermarkImage, $pos, $padding, $opacity)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2221)


#### Arguments
* $watermarkImage **mixed**
* $pos **mixed**
* $padding **mixed**
* $opacity **mixed**



### <a name="method-calculatePosition"></a>calculatePosition

    mixed imageLib::calculatePosition($pos, $padding, $assetWidth, $assetHeight, $upperLeft)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2273)


#### Arguments
* $pos **mixed**
* $padding **mixed**
* $assetWidth **mixed**
* $assetHeight **mixed**
* $upperLeft **mixed**



### <a name="method-filterOpacity"></a>filterOpacity

    mixed imageLib::filterOpacity($img, $opacity)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2366)


#### Arguments
* $img **mixed**
* $opacity **mixed**



### <a name="method-openImage"></a>openImage

    mixed imageLib::openImage($file)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2433](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2433)


#### Arguments
* $file **mixed**



### <a name="method-reset"></a>reset

    mixed imageLib::reset()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2485)




### <a name="method-saveImage"></a>saveImage

    mixed imageLib::saveImage($savePath, $imageQuality)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2500)


#### Arguments
* $savePath **mixed**
* $imageQuality **mixed**



### <a name="method-displayImage"></a>displayImage

    mixed imageLib::displayImage($fileType, $imageQuality)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2598](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2598)


#### Arguments
* $fileType **mixed**
* $imageQuality **mixed**



### <a name="method-setTransparency"></a>setTransparency

    mixed imageLib::setTransparency($bool)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2654](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2654)


#### Arguments
* $bool **mixed**



### <a name="method-setFillColor"></a>setFillColor

    mixed imageLib::setFillColor($value)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2662)


#### Arguments
* $value **mixed**



### <a name="method-setCropFromTop"></a>setCropFromTop

    mixed imageLib::setCropFromTop($value)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2680)


#### Arguments
* $value **mixed**



### <a name="method-testGDInstalled"></a>testGDInstalled

    mixed imageLib::testGDInstalled()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2688)




### <a name="method-testEXIFInstalled"></a>testEXIFInstalled

    mixed imageLib::testEXIFInstalled()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2709](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2709)




### <a name="method-testIsImage"></a>testIsImage

    mixed imageLib::testIsImage($image)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2730)


#### Arguments
* $image **mixed**



### <a name="method-testFunct"></a>testFunct

    mixed imageLib::testFunct()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2751)




### <a name="method-setForceStretch"></a>setForceStretch

    mixed imageLib::setForceStretch($value)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2766](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2766)


#### Arguments
* $value **mixed**



### <a name="method-setFile"></a>setFile

    mixed imageLib::setFile($fileName)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2781](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2781)


#### Arguments
* $fileName **mixed**



### <a name="method-getFileName"></a>getFileName

    mixed imageLib::getFileName()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2796](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2796)




### <a name="method-getHeight"></a>getHeight

    mixed imageLib::getHeight()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2811)




### <a name="method-getWidth"></a>getWidth

    mixed imageLib::getWidth()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2818](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2818)




### <a name="method-getOriginalHeight"></a>getOriginalHeight

    mixed imageLib::getOriginalHeight()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2825](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2825)




### <a name="method-getOriginalWidth"></a>getOriginalWidth

    mixed imageLib::getOriginalWidth()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2832](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2832)




### <a name="method-getErrors"></a>getErrors

    mixed imageLib::getErrors()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2839)




### <a name="method-checkInterlaceImage"></a>checkInterlaceImage

    mixed imageLib::checkInterlaceImage($isEnabled)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2854)


#### Arguments
* $isEnabled **mixed**



### <a name="method-formatColor"></a>formatColor

    mixed imageLib::formatColor($value)





* Visibility: **protected**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2864)


#### Arguments
* $value **mixed**



### <a name="method-hex2dec"></a>hex2dec

    mixed imageLib::hex2dec($hex)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2904](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2904)


#### Arguments
* $hex **mixed**



### <a name="method-createImageColor"></a>createImageColor

    mixed imageLib::createImageColor($colorArray)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2924](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2924)


#### Arguments
* $colorArray **mixed**



### <a name="method-testColorExists"></a>testColorExists

    mixed imageLib::testColorExists($colorArray)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2935](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2935)


#### Arguments
* $colorArray **mixed**



### <a name="method-findUnusedGreen"></a>findUnusedGreen

    mixed imageLib::findUnusedGreen()





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2950](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2950)




### <a name="method-findUnusedBlue"></a>findUnusedBlue

    mixed imageLib::findUnusedBlue()





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2973](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2973)




### <a name="method-invertTransparency"></a>invertTransparency

    mixed imageLib::invertTransparency($value, $originalMax, $invert)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 2996](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L2996)


#### Arguments
* $value **mixed**
* $originalMax **mixed**
* $invert **mixed**



### <a name="method-transparentImage"></a>transparentImage

    mixed imageLib::transparentImage($src)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3021](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3021)


#### Arguments
* $src **mixed**



### <a name="method-checkStringStartsWith"></a>checkStringStartsWith

    mixed imageLib::checkStringStartsWith($needle, $haystack)





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3049](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3049)


#### Arguments
* $needle **mixed**
* $haystack **mixed**



### <a name="method-GD2BMPstring"></a>GD2BMPstring

    mixed imageLib::GD2BMPstring($gd_image)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3060](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3060)


#### Arguments
* $gd_image **mixed**



### <a name="method-GetPixelColor"></a>GetPixelColor

    mixed imageLib::GetPixelColor($img, $x, $y)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3113)


#### Arguments
* $img **mixed**
* $x **mixed**
* $y **mixed**



### <a name="method-LittleEndian2String"></a>LittleEndian2String

    mixed imageLib::LittleEndian2String($number, $minbytes)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3130)


#### Arguments
* $number **mixed**
* $minbytes **mixed**



### <a name="method-ImageCreateFromBMP"></a>ImageCreateFromBMP

    mixed imageLib::ImageCreateFromBMP($filename)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3152)


#### Arguments
* $filename **mixed**



### <a name="method-imagecreatefrompsd"></a>imagecreatefrompsd

    mixed imageLib::imagecreatefrompsd($fileName)





* Visibility: **private**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3293)


#### Arguments
* $fileName **mixed**



### <a name="method-__destruct"></a>__destruct

    mixed imageLib::__destruct()





* Visibility: **public**
* This method is defined in [admin/filemanager/include/php_image_magician.php line 3320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin/filemanager/include/php_image_magician.php#L3320)



