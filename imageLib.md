imageLib
===============






* Class name: imageLib
* Namespace: 





Properties
----------


### $fileName

    private mixed $fileName





* Visibility: **private**


### $image

    private mixed $image





* Visibility: **private**


### $imageResized

    protected mixed $imageResized





* Visibility: **protected**


### $widthOriginal

    private mixed $widthOriginal





* Visibility: **private**


### $heightOriginal

    private mixed $heightOriginal





* Visibility: **private**


### $width

    private mixed $width





* Visibility: **private**


### $height

    private mixed $height





* Visibility: **private**


### $imageSize

    private mixed $imageSize





* Visibility: **private**


### $fileExtension

    private mixed $fileExtension





* Visibility: **private**


### $debug

    private mixed $debug = true





* Visibility: **private**


### $errorArray

    private mixed $errorArray = array()





* Visibility: **private**


### $forceStretch

    private mixed $forceStretch = true





* Visibility: **private**


### $aggresiveSharpening

    private mixed $aggresiveSharpening = false





* Visibility: **private**


### $transparentArray

    private mixed $transparentArray = array('.png', '.gif')





* Visibility: **private**


### $keepTransparency

    private mixed $keepTransparency = true





* Visibility: **private**


### $fillColorArray

    private mixed $fillColorArray = array('r' => 255, 'g' => 255, 'b' => 255)





* Visibility: **private**


### $sharpenArray

    private mixed $sharpenArray = array('jpg')





* Visibility: **private**


### $psdReaderPath

    private mixed $psdReaderPath





* Visibility: **private**


### $filterOverlayPath

    private mixed $filterOverlayPath





* Visibility: **private**


### $isInterlace

    private mixed $isInterlace





* Visibility: **private**


### $captionBoxPositionArray

    private mixed $captionBoxPositionArray = array()





* Visibility: **private**


### $fontDir

    private mixed $fontDir = 'fonts'





* Visibility: **private**


### $cropFromTopPercent

    private mixed $cropFromTopPercent = 10





* Visibility: **private**


Methods
-------


### __construct

    mixed imageLib::__construct($fileName)





* Visibility: **public**


#### Arguments
* $fileName **mixed**



### initialise

    mixed imageLib::initialise()





* Visibility: **private**




### resizeImage

    mixed imageLib::resizeImage($newWidth, $newHeight, $option, $sharpen, $autoRotate)





* Visibility: **public**


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**
* $sharpen **mixed**
* $autoRotate **mixed**



### cropImage

    mixed imageLib::cropImage($newWidth, $newHeight, $cropPos)





* Visibility: **public**


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### keepTransparancy

    mixed imageLib::keepTransparancy($width, $height, $im)





* Visibility: **private**


#### Arguments
* $width **mixed**
* $height **mixed**
* $im **mixed**



### crop

    mixed imageLib::crop($optimalWidth, $optimalHeight, $newWidth, $newHeight, $cropPos)





* Visibility: **private**


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### getCropPlacing

    mixed imageLib::getCropPlacing($optimalWidth, $optimalHeight, $newWidth, $newHeight, $pos)





* Visibility: **private**


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $pos **mixed**



### getDimensions

    mixed imageLib::getDimensions($newWidth, $newHeight, $option)





* Visibility: **private**


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**



### getSizeByFixedHeight

    mixed imageLib::getSizeByFixedHeight($newWidth, $newHeight)





* Visibility: **private**


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### getSizeByFixedWidth

    mixed imageLib::getSizeByFixedWidth($newWidth, $newHeight)





* Visibility: **private**


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### getSizeByAuto

    mixed imageLib::getSizeByAuto($newWidth, $newHeight)





* Visibility: **private**


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### getOptimalCrop

    mixed imageLib::getOptimalCrop($newWidth, $newHeight)





* Visibility: **private**


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### sharpen

    mixed imageLib::sharpen()





* Visibility: **private**




### sharpen2

    mixed imageLib::sharpen2($level)





* Visibility: **private**


#### Arguments
* $level **mixed**



### findSharp

    mixed imageLib::findSharp($orig, $final)





* Visibility: **private**


#### Arguments
* $orig **mixed**
* $final **mixed**



### prepOption

    mixed imageLib::prepOption($option)





* Visibility: **private**


#### Arguments
* $option **mixed**



### borderPreset

    mixed imageLib::borderPreset($preset)





* Visibility: **public**


#### Arguments
* $preset **mixed**



### addBorder

    mixed imageLib::addBorder($thickness, $rgbArray)





* Visibility: **public**


#### Arguments
* $thickness **mixed**
* $rgbArray **mixed**



### greyScale

    mixed imageLib::greyScale()





* Visibility: **public**




### greyScaleEnhanced

    mixed imageLib::greyScaleEnhanced()





* Visibility: **public**




### greyScaleDramatic

    mixed imageLib::greyScaleDramatic()





* Visibility: **public**




### blackAndWhite

    mixed imageLib::blackAndWhite()





* Visibility: **public**




### negative

    mixed imageLib::negative()





* Visibility: **public**




### sepia

    mixed imageLib::sepia()





* Visibility: **public**




### sepia2

    mixed imageLib::sepia2()





* Visibility: **public**




### vintage

    mixed imageLib::vintage()





* Visibility: **public**




### gd_filter_monopin

    mixed imageLib::gd_filter_monopin()

Apply 'Monopin' preset



* Visibility: **public**




### gd_filter_vintage

    mixed imageLib::gd_filter_vintage()





* Visibility: **public**




### gd_apply_overlay

    mixed imageLib::gd_apply_overlay($im, $type, $amount)

Apply a PNG overlay



* Visibility: **private**


#### Arguments
* $im **mixed**
* $type **mixed**
* $amount **mixed**



### image_colorize

    mixed imageLib::image_colorize($rgb)





* Visibility: **public**


#### Arguments
* $rgb **mixed**



### addReflection

    mixed imageLib::addReflection($reflectionHeight, $startingTransparency, $inside, $bgColor, $stretch, $divider)





* Visibility: **public**


#### Arguments
* $reflectionHeight **mixed**
* $startingTransparency **mixed**
* $inside **mixed**
* $bgColor **mixed**
* $stretch **mixed**
* $divider **mixed**



### rotate

    mixed imageLib::rotate($value, $bgColor)





* Visibility: **public**


#### Arguments
* $value **mixed**
* $bgColor **mixed**



### roundCorners

    mixed imageLib::roundCorners($radius, $bgColor)





* Visibility: **public**


#### Arguments
* $radius **mixed**
* $bgColor **mixed**



### addShadow

    mixed imageLib::addShadow($shadowAngle, $blur, $bgColor)





* Visibility: **public**


#### Arguments
* $shadowAngle **mixed**
* $blur **mixed**
* $bgColor **mixed**



### addCaptionBox

    mixed imageLib::addCaptionBox($side, $thickness, $padding, $bgColor, $transparencyAmount)





* Visibility: **public**


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**
* $bgColor **mixed**
* $transparencyAmount **mixed**



### addTextToCaptionBox

    mixed imageLib::addTextToCaptionBox($text, $fontColor, $fontSize, $angle, $font)





* Visibility: **public**


#### Arguments
* $text **mixed**
* $fontColor **mixed**
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**



### calculateCaptionBoxPosition

    mixed imageLib::calculateCaptionBoxPosition($side, $thickness, $padding)





* Visibility: **private**


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**



### getExif

    mixed imageLib::getExif($debug)





* Visibility: **public**


#### Arguments
* $debug **mixed**



### resolveExposureProgram

    mixed imageLib::resolveExposureProgram($ep)





* Visibility: **private**


#### Arguments
* $ep **mixed**



### resolveMeteringMode

    mixed imageLib::resolveMeteringMode($mm)





* Visibility: **private**


#### Arguments
* $mm **mixed**



### resolveFlash

    mixed imageLib::resolveFlash($flash)





* Visibility: **private**


#### Arguments
* $flash **mixed**



### writeIPTCcaption

    mixed imageLib::writeIPTCcaption($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### writeIPTCwriter

    mixed imageLib::writeIPTCwriter($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### writeIPTC

    mixed imageLib::writeIPTC($dat, $value)





* Visibility: **private**


#### Arguments
* $dat **mixed**
* $value **mixed**



### iptc_maketag

    mixed imageLib::iptc_maketag($rec, $dat, $val)





* Visibility: **private**


#### Arguments
* $rec **mixed**
* $dat **mixed**
* $val **mixed**



### addText

    mixed imageLib::addText($text, $pos, $padding, $fontColor, $fontSize, $angle, $font)





* Visibility: **public**


#### Arguments
* $text **mixed**
* $pos **mixed**
* $padding **mixed**
* $fontColor **mixed**
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**



### getTextFont

    mixed imageLib::getTextFont($font)





* Visibility: **private**


#### Arguments
* $font **mixed**



### getTextSize

    mixed imageLib::getTextSize($fontSize, $angle, $font, $text)





* Visibility: **private**


#### Arguments
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**
* $text **mixed**



### addWatermark

    mixed imageLib::addWatermark($watermarkImage, $pos, $padding, $opacity)





* Visibility: **public**


#### Arguments
* $watermarkImage **mixed**
* $pos **mixed**
* $padding **mixed**
* $opacity **mixed**



### calculatePosition

    mixed imageLib::calculatePosition($pos, $padding, $assetWidth, $assetHeight, $upperLeft)





* Visibility: **private**


#### Arguments
* $pos **mixed**
* $padding **mixed**
* $assetWidth **mixed**
* $assetHeight **mixed**
* $upperLeft **mixed**



### filterOpacity

    mixed imageLib::filterOpacity($img, $opacity)





* Visibility: **private**


#### Arguments
* $img **mixed**
* $opacity **mixed**



### openImage

    mixed imageLib::openImage($file)





* Visibility: **private**


#### Arguments
* $file **mixed**



### reset

    mixed imageLib::reset()





* Visibility: **public**




### saveImage

    mixed imageLib::saveImage($savePath, $imageQuality)





* Visibility: **public**


#### Arguments
* $savePath **mixed**
* $imageQuality **mixed**



### displayImage

    mixed imageLib::displayImage($fileType, $imageQuality)





* Visibility: **public**


#### Arguments
* $fileType **mixed**
* $imageQuality **mixed**



### setTransparency

    mixed imageLib::setTransparency($bool)





* Visibility: **public**


#### Arguments
* $bool **mixed**



### setFillColor

    mixed imageLib::setFillColor($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### setCropFromTop

    mixed imageLib::setCropFromTop($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### testGDInstalled

    mixed imageLib::testGDInstalled()





* Visibility: **public**




### testEXIFInstalled

    mixed imageLib::testEXIFInstalled()





* Visibility: **public**




### testIsImage

    mixed imageLib::testIsImage($image)





* Visibility: **public**


#### Arguments
* $image **mixed**



### testFunct

    mixed imageLib::testFunct()





* Visibility: **public**




### setForceStretch

    mixed imageLib::setForceStretch($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### setFile

    mixed imageLib::setFile($fileName)





* Visibility: **public**


#### Arguments
* $fileName **mixed**



### getFileName

    mixed imageLib::getFileName()





* Visibility: **public**




### getHeight

    mixed imageLib::getHeight()





* Visibility: **public**




### getWidth

    mixed imageLib::getWidth()





* Visibility: **public**




### getOriginalHeight

    mixed imageLib::getOriginalHeight()





* Visibility: **public**




### getOriginalWidth

    mixed imageLib::getOriginalWidth()





* Visibility: **public**




### getErrors

    mixed imageLib::getErrors()





* Visibility: **public**




### checkInterlaceImage

    mixed imageLib::checkInterlaceImage($isEnabled)





* Visibility: **private**


#### Arguments
* $isEnabled **mixed**



### formatColor

    mixed imageLib::formatColor($value)





* Visibility: **protected**


#### Arguments
* $value **mixed**



### hex2dec

    mixed imageLib::hex2dec($hex)





* Visibility: **public**


#### Arguments
* $hex **mixed**



### createImageColor

    mixed imageLib::createImageColor($colorArray)





* Visibility: **private**


#### Arguments
* $colorArray **mixed**



### testColorExists

    mixed imageLib::testColorExists($colorArray)





* Visibility: **private**


#### Arguments
* $colorArray **mixed**



### findUnusedGreen

    mixed imageLib::findUnusedGreen()





* Visibility: **private**




### findUnusedBlue

    mixed imageLib::findUnusedBlue()





* Visibility: **private**




### invertTransparency

    mixed imageLib::invertTransparency($value, $originalMax, $invert)





* Visibility: **private**


#### Arguments
* $value **mixed**
* $originalMax **mixed**
* $invert **mixed**



### transparentImage

    mixed imageLib::transparentImage($src)





* Visibility: **private**


#### Arguments
* $src **mixed**



### checkStringStartsWith

    mixed imageLib::checkStringStartsWith($needle, $haystack)





* Visibility: **public**


#### Arguments
* $needle **mixed**
* $haystack **mixed**



### GD2BMPstring

    mixed imageLib::GD2BMPstring($gd_image)





* Visibility: **private**


#### Arguments
* $gd_image **mixed**



### GetPixelColor

    mixed imageLib::GetPixelColor($img, $x, $y)





* Visibility: **private**


#### Arguments
* $img **mixed**
* $x **mixed**
* $y **mixed**



### LittleEndian2String

    mixed imageLib::LittleEndian2String($number, $minbytes)





* Visibility: **private**


#### Arguments
* $number **mixed**
* $minbytes **mixed**



### ImageCreateFromBMP

    mixed imageLib::ImageCreateFromBMP($filename)





* Visibility: **private**


#### Arguments
* $filename **mixed**



### imagecreatefrompsd

    mixed imageLib::imagecreatefrompsd($fileName)





* Visibility: **private**


#### Arguments
* $fileName **mixed**



### __destruct

    mixed imageLib::__destruct()





* Visibility: **public**



