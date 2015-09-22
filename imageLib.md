imageLib
===============






* Class name: imageLib
* Namespace: 
* This class is defined in admin\filemanager\include\php_image_magician.php line 163





Properties
----------


### $fileName

    private mixed $fileName





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 165


### $image

    private mixed $image





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 166


### $imageResized

    protected mixed $imageResized





* Visibility: **protected**
* This property is defined in admin\filemanager\include\php_image_magician.php line 167


### $widthOriginal

    private mixed $widthOriginal





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 168


### $heightOriginal

    private mixed $heightOriginal





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 169


### $width

    private mixed $width





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 170


### $height

    private mixed $height





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 171


### $imageSize

    private mixed $imageSize





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 172


### $fileExtension

    private mixed $fileExtension





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 173


### $debug

    private mixed $debug = true





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 175


### $errorArray

    private mixed $errorArray = array()





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 176


### $forceStretch

    private mixed $forceStretch = true





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 178


### $aggresiveSharpening

    private mixed $aggresiveSharpening = false





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 179


### $transparentArray

    private mixed $transparentArray = array('.png', '.gif')





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 181


### $keepTransparency

    private mixed $keepTransparency = true





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 182


### $fillColorArray

    private mixed $fillColorArray = array('r' => 255, 'g' => 255, 'b' => 255)





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 183


### $sharpenArray

    private mixed $sharpenArray = array('jpg')





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 185


### $psdReaderPath

    private mixed $psdReaderPath





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 187


### $filterOverlayPath

    private mixed $filterOverlayPath





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 188


### $isInterlace

    private mixed $isInterlace





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 190


### $captionBoxPositionArray

    private mixed $captionBoxPositionArray = array()





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 192


### $fontDir

    private mixed $fontDir = 'fonts'





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 194


### $cropFromTopPercent

    private mixed $cropFromTopPercent = 10





* Visibility: **private**
* This property is defined in admin\filemanager\include\php_image_magician.php line 196


Methods
-------


### __construct

    mixed imageLib::__construct($fileName)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 201


#### Arguments
* $fileName **mixed**



### initialise

    mixed imageLib::initialise()





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 258




### resizeImage

    mixed imageLib::resizeImage($newWidth, $newHeight, $option, $sharpen, $autoRotate)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 274


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**
* $sharpen **mixed**
* $autoRotate **mixed**



### cropImage

    mixed imageLib::cropImage($newWidth, $newHeight, $cropPos)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 383


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### keepTransparancy

    mixed imageLib::keepTransparancy($width, $height, $im)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 414


#### Arguments
* $width **mixed**
* $height **mixed**
* $im **mixed**



### crop

    mixed imageLib::crop($optimalWidth, $optimalHeight, $newWidth, $newHeight, $cropPos)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 438


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $cropPos **mixed**



### getCropPlacing

    mixed imageLib::getCropPlacing($optimalWidth, $optimalHeight, $newWidth, $newHeight, $pos)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 469


#### Arguments
* $optimalWidth **mixed**
* $optimalHeight **mixed**
* $newWidth **mixed**
* $newHeight **mixed**
* $pos **mixed**



### getDimensions

    mixed imageLib::getDimensions($newWidth, $newHeight, $option)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 562


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**
* $option **mixed**



### getSizeByFixedHeight

    mixed imageLib::getSizeByFixedHeight($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 621


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### getSizeByFixedWidth

    mixed imageLib::getSizeByFixedWidth($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 642


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### getSizeByAuto

    mixed imageLib::getSizeByAuto($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 663


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### getOptimalCrop

    mixed imageLib::getOptimalCrop($newWidth, $newHeight)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 726


#### Arguments
* $newWidth **mixed**
* $newHeight **mixed**



### sharpen

    mixed imageLib::sharpen()





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 784




### sharpen2

    mixed imageLib::sharpen2($level)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 829


#### Arguments
* $level **mixed**



### findSharp

    mixed imageLib::findSharp($orig, $final)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 840


#### Arguments
* $orig **mixed**
* $final **mixed**



### prepOption

    mixed imageLib::prepOption($option)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 861


#### Arguments
* $option **mixed**



### borderPreset

    mixed imageLib::borderPreset($preset)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 899


#### Arguments
* $preset **mixed**



### addBorder

    mixed imageLib::addBorder($thickness, $rgbArray)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 919


#### Arguments
* $thickness **mixed**
* $rgbArray **mixed**



### greyScale

    mixed imageLib::greyScale()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 955




### greyScaleEnhanced

    mixed imageLib::greyScaleEnhanced()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 972




### greyScaleDramatic

    mixed imageLib::greyScaleDramatic()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 992




### blackAndWhite

    mixed imageLib::blackAndWhite()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1003




### negative

    mixed imageLib::negative()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1024




### sepia

    mixed imageLib::sepia()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1044




### sepia2

    mixed imageLib::sepia2()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1064




### vintage

    mixed imageLib::vintage()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1083




### gd_filter_monopin

    mixed imageLib::gd_filter_monopin()

Apply 'Monopin' preset



* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1095




### gd_filter_vintage

    mixed imageLib::gd_filter_vintage()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1107




### gd_apply_overlay

    mixed imageLib::gd_apply_overlay($im, $type, $amount)

Apply a PNG overlay



* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1122


#### Arguments
* $im **mixed**
* $type **mixed**
* $amount **mixed**



### image_colorize

    mixed imageLib::image_colorize($rgb)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1161


#### Arguments
* $rgb **mixed**



### addReflection

    mixed imageLib::addReflection($reflectionHeight, $startingTransparency, $inside, $bgColor, $stretch, $divider)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1187


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
* This method is defined in admin\filemanager\include\php_image_magician.php line 1274


#### Arguments
* $value **mixed**
* $bgColor **mixed**



### roundCorners

    mixed imageLib::roundCorners($radius, $bgColor)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1342


#### Arguments
* $radius **mixed**
* $bgColor **mixed**



### addShadow

    mixed imageLib::addShadow($shadowAngle, $blur, $bgColor)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1438


#### Arguments
* $shadowAngle **mixed**
* $blur **mixed**
* $bgColor **mixed**



### addCaptionBox

    mixed imageLib::addCaptionBox($side, $thickness, $padding, $bgColor, $transparencyAmount)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1585


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**
* $bgColor **mixed**
* $transparencyAmount **mixed**



### addTextToCaptionBox

    mixed imageLib::addTextToCaptionBox($text, $fontColor, $fontSize, $angle, $font)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1620


#### Arguments
* $text **mixed**
* $fontColor **mixed**
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**



### calculateCaptionBoxPosition

    mixed imageLib::calculateCaptionBoxPosition($side, $thickness, $padding)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1670


#### Arguments
* $side **mixed**
* $thickness **mixed**
* $padding **mixed**



### getExif

    mixed imageLib::getExif($debug)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1711


#### Arguments
* $debug **mixed**



### resolveExposureProgram

    mixed imageLib::resolveExposureProgram($ep)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1897


#### Arguments
* $ep **mixed**



### resolveMeteringMode

    mixed imageLib::resolveMeteringMode($mm)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1937


#### Arguments
* $mm **mixed**



### resolveFlash

    mixed imageLib::resolveFlash($flash)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 1974


#### Arguments
* $flash **mixed**



### writeIPTCcaption

    mixed imageLib::writeIPTCcaption($value)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2061


#### Arguments
* $value **mixed**



### writeIPTCwriter

    mixed imageLib::writeIPTCwriter($value)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2069


#### Arguments
* $value **mixed**



### writeIPTC

    mixed imageLib::writeIPTC($dat, $value)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2076


#### Arguments
* $dat **mixed**
* $value **mixed**



### iptc_maketag

    mixed imageLib::iptc_maketag($rec, $dat, $val)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2088


#### Arguments
* $rec **mixed**
* $dat **mixed**
* $val **mixed**



### addText

    mixed imageLib::addText($text, $pos, $padding, $fontColor, $fontSize, $angle, $font)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2131


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
* This method is defined in admin\filemanager\include\php_image_magician.php line 2169


#### Arguments
* $font **mixed**



### getTextSize

    mixed imageLib::getTextSize($fontSize, $angle, $font, $text)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2201


#### Arguments
* $fontSize **mixed**
* $angle **mixed**
* $font **mixed**
* $text **mixed**



### addWatermark

    mixed imageLib::addWatermark($watermarkImage, $pos, $padding, $opacity)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2221


#### Arguments
* $watermarkImage **mixed**
* $pos **mixed**
* $padding **mixed**
* $opacity **mixed**



### calculatePosition

    mixed imageLib::calculatePosition($pos, $padding, $assetWidth, $assetHeight, $upperLeft)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2273


#### Arguments
* $pos **mixed**
* $padding **mixed**
* $assetWidth **mixed**
* $assetHeight **mixed**
* $upperLeft **mixed**



### filterOpacity

    mixed imageLib::filterOpacity($img, $opacity)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2366


#### Arguments
* $img **mixed**
* $opacity **mixed**



### openImage

    mixed imageLib::openImage($file)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2433


#### Arguments
* $file **mixed**



### reset

    mixed imageLib::reset()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2485




### saveImage

    mixed imageLib::saveImage($savePath, $imageQuality)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2500


#### Arguments
* $savePath **mixed**
* $imageQuality **mixed**



### displayImage

    mixed imageLib::displayImage($fileType, $imageQuality)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2598


#### Arguments
* $fileType **mixed**
* $imageQuality **mixed**



### setTransparency

    mixed imageLib::setTransparency($bool)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2654


#### Arguments
* $bool **mixed**



### setFillColor

    mixed imageLib::setFillColor($value)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2662


#### Arguments
* $value **mixed**



### setCropFromTop

    mixed imageLib::setCropFromTop($value)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2680


#### Arguments
* $value **mixed**



### testGDInstalled

    mixed imageLib::testGDInstalled()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2688




### testEXIFInstalled

    mixed imageLib::testEXIFInstalled()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2709




### testIsImage

    mixed imageLib::testIsImage($image)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2730


#### Arguments
* $image **mixed**



### testFunct

    mixed imageLib::testFunct()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2751




### setForceStretch

    mixed imageLib::setForceStretch($value)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2766


#### Arguments
* $value **mixed**



### setFile

    mixed imageLib::setFile($fileName)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2781


#### Arguments
* $fileName **mixed**



### getFileName

    mixed imageLib::getFileName()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2796




### getHeight

    mixed imageLib::getHeight()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2811




### getWidth

    mixed imageLib::getWidth()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2818




### getOriginalHeight

    mixed imageLib::getOriginalHeight()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2825




### getOriginalWidth

    mixed imageLib::getOriginalWidth()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2832




### getErrors

    mixed imageLib::getErrors()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2839




### checkInterlaceImage

    mixed imageLib::checkInterlaceImage($isEnabled)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2854


#### Arguments
* $isEnabled **mixed**



### formatColor

    mixed imageLib::formatColor($value)





* Visibility: **protected**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2864


#### Arguments
* $value **mixed**



### hex2dec

    mixed imageLib::hex2dec($hex)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2904


#### Arguments
* $hex **mixed**



### createImageColor

    mixed imageLib::createImageColor($colorArray)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2924


#### Arguments
* $colorArray **mixed**



### testColorExists

    mixed imageLib::testColorExists($colorArray)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2935


#### Arguments
* $colorArray **mixed**



### findUnusedGreen

    mixed imageLib::findUnusedGreen()





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2950




### findUnusedBlue

    mixed imageLib::findUnusedBlue()





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2973




### invertTransparency

    mixed imageLib::invertTransparency($value, $originalMax, $invert)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 2996


#### Arguments
* $value **mixed**
* $originalMax **mixed**
* $invert **mixed**



### transparentImage

    mixed imageLib::transparentImage($src)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3021


#### Arguments
* $src **mixed**



### checkStringStartsWith

    mixed imageLib::checkStringStartsWith($needle, $haystack)





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3049


#### Arguments
* $needle **mixed**
* $haystack **mixed**



### GD2BMPstring

    mixed imageLib::GD2BMPstring($gd_image)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3060


#### Arguments
* $gd_image **mixed**



### GetPixelColor

    mixed imageLib::GetPixelColor($img, $x, $y)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3113


#### Arguments
* $img **mixed**
* $x **mixed**
* $y **mixed**



### LittleEndian2String

    mixed imageLib::LittleEndian2String($number, $minbytes)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3130


#### Arguments
* $number **mixed**
* $minbytes **mixed**



### ImageCreateFromBMP

    mixed imageLib::ImageCreateFromBMP($filename)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3152


#### Arguments
* $filename **mixed**



### imagecreatefrompsd

    mixed imageLib::imagecreatefrompsd($fileName)





* Visibility: **private**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3293


#### Arguments
* $fileName **mixed**



### __destruct

    mixed imageLib::__destruct()





* Visibility: **public**
* This method is defined in admin\filemanager\include\php_image_magician.php line 3320



