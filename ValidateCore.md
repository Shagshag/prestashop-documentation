ValidateCore
===============






* Class name: ValidateCore
* This class is defined in [classes/Validate.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L27)



Constants
----------

* [ADMIN_PASSWORD_LENGTH](#constant-ADMIN_PASSWORD_LENGTH)
* [PASSWORD_LENGTH](#constant-PASSWORD_LENGTH)



Methods
-------
* [isIp2Long](#method-isIp2Long)
* [isAnything](#method-isAnything)
* [isEmail](#method-isEmail)
* [isModuleUrl](#method-isModuleUrl)
* [isMd5](#method-isMd5)
* [isSha1](#method-isSha1)
* [isFloat](#method-isFloat)
* [isUnsignedFloat](#method-isUnsignedFloat)
* [isOptFloat](#method-isOptFloat)
* [isCarrierName](#method-isCarrierName)
* [isImageSize](#method-isImageSize)
* [isName](#method-isName)
* [isHookName](#method-isHookName)
* [isMailName](#method-isMailName)
* [isMailSubject](#method-isMailSubject)
* [isModuleName](#method-isModuleName)
* [isTplName](#method-isTplName)
* [isImageTypeName](#method-isImageTypeName)
* [isPrice](#method-isPrice)
* [isNegativePrice](#method-isNegativePrice)
* [isLanguageIsoCode](#method-isLanguageIsoCode)
* [isLanguageCode](#method-isLanguageCode)
* [isStateIsoCode](#method-isStateIsoCode)
* [isNumericIsoCode](#method-isNumericIsoCode)
* [isDiscountName](#method-isDiscountName)
* [isCatalogName](#method-isCatalogName)
* [isMessage](#method-isMessage)
* [isCountryName](#method-isCountryName)
* [isLinkRewrite](#method-isLinkRewrite)
* [isRoutePattern](#method-isRoutePattern)
* [isAddress](#method-isAddress)
* [isCityName](#method-isCityName)
* [isValidSearch](#method-isValidSearch)
* [isGenericName](#method-isGenericName)
* [isCleanHtml](#method-isCleanHtml)
* [isReference](#method-isReference)
* [isPasswd](#method-isPasswd)
* [isPasswdAdmin](#method-isPasswdAdmin)
* [isConfigName](#method-isConfigName)
* [isPhpDateFormat](#method-isPhpDateFormat)
* [isDateFormat](#method-isDateFormat)
* [isDate](#method-isDate)
* [isBirthDate](#method-isBirthDate)
* [isBool](#method-isBool)
* [isPhoneNumber](#method-isPhoneNumber)
* [isEan13](#method-isEan13)
* [isUpc](#method-isUpc)
* [isPostCode](#method-isPostCode)
* [isZipCodeFormat](#method-isZipCodeFormat)
* [isOrderWay](#method-isOrderWay)
* [isOrderBy](#method-isOrderBy)
* [isTableOrIdentifier](#method-isTableOrIdentifier)
* [isValuesList](#method-isValuesList)
* [isTagsList](#method-isTagsList)
* [isProductVisibility](#method-isProductVisibility)
* [isInt](#method-isInt)
* [isUnsignedInt](#method-isUnsignedInt)
* [isPercentage](#method-isPercentage)
* [isUnsignedId](#method-isUnsignedId)
* [isNullOrUnsignedId](#method-isNullOrUnsignedId)
* [isLoadedObject](#method-isLoadedObject)
* [isColor](#method-isColor)
* [isUrl](#method-isUrl)
* [isTrackingNumber](#method-isTrackingNumber)
* [isUrlOrEmpty](#method-isUrlOrEmpty)
* [isAbsoluteUrl](#method-isAbsoluteUrl)
* [isMySQLEngine](#method-isMySQLEngine)
* [isUnixName](#method-isUnixName)
* [isTablePrefix](#method-isTablePrefix)
* [isFileName](#method-isFileName)
* [isDirName](#method-isDirName)
* [isTabName](#method-isTabName)
* [isWeightUnit](#method-isWeightUnit)
* [isDistanceUnit](#method-isDistanceUnit)
* [isSubDomainName](#method-isSubDomainName)
* [isVoucherDescription](#method-isVoucherDescription)
* [isSortDirection](#method-isSortDirection)
* [isLabel](#method-isLabel)
* [isPriceDisplayMethod](#method-isPriceDisplayMethod)
* [isDniLite](#method-isDniLite)
* [isCookie](#method-isCookie)
* [isString](#method-isString)
* [isReductionType](#method-isReductionType)
* [isBoolId](#method-isBoolId)
* [isBool_Id](#method-isBool_Id)
* [isLocalizationPackSelection](#method-isLocalizationPackSelection)
* [isSerializedArray](#method-isSerializedArray)
* [isCoordinate](#method-isCoordinate)
* [isLangIsoCode](#method-isLangIsoCode)
* [isLanguageFileName](#method-isLanguageFileName)
* [isArrayWithIds](#method-isArrayWithIds)
* [isSceneZones](#method-isSceneZones)
* [isStockManagement](#method-isStockManagement)
* [isSiret](#method-isSiret)
* [isApe](#method-isApe)
* [isControllerName](#method-isControllerName)
* [isPrestaShopVersion](#method-isPrestaShopVersion)
* [isOrderInvoiceNumber](#method-isOrderInvoiceNumber)


Constants
----------


### <a name="constant-ADMIN_PASSWORD_LENGTH"></a>ADMIN_PASSWORD_LENGTH

    const ADMIN_PASSWORD_LENGTH = 8



* This constant is defined in [classes/Validate.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L29)


### <a name="constant-PASSWORD_LENGTH"></a>PASSWORD_LENGTH

    const PASSWORD_LENGTH = 5



* This constant is defined in [classes/Validate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L30)




Methods
-------


### <a name="method-isIp2Long"></a>isIp2Long

    mixed ValidateCore::isIp2Long($ip)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L32)


#### Arguments
* $ip **mixed**



### <a name="method-isAnything"></a>isAnything

    mixed ValidateCore::isAnything()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L37)




### <a name="method-isEmail"></a>isEmail

    boolean ValidateCore::isEmail(string $email)

Check for e-mail validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L48)


#### Arguments
* $email **string** - &lt;p&gt;e-mail address to validate&lt;/p&gt;



### <a name="method-isModuleUrl"></a>isModuleUrl

    boolean ValidateCore::isModuleUrl(string $url, array $errors)

Check for module URL validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L60)


#### Arguments
* $url **string** - &lt;p&gt;module URL to validate&lt;/p&gt;
* $errors **array** - &lt;p&gt;Reference array for catching errors&lt;/p&gt;



### <a name="method-isMd5"></a>isMd5

    boolean ValidateCore::isMd5(string $md5)

Check for MD5 string validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L86)


#### Arguments
* $md5 **string** - &lt;p&gt;MD5 string to validate&lt;/p&gt;



### <a name="method-isSha1"></a>isSha1

    boolean ValidateCore::isSha1(string $sha1)

Check for SHA1 string validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L97)


#### Arguments
* $sha1 **string** - &lt;p&gt;SHA1 string to validate&lt;/p&gt;



### <a name="method-isFloat"></a>isFloat

    boolean ValidateCore::isFloat(float $float)

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L108)


#### Arguments
* $float **float** - &lt;p&gt;Float number to validate&lt;/p&gt;



### <a name="method-isUnsignedFloat"></a>isUnsignedFloat

    mixed ValidateCore::isUnsignedFloat($float)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L113)


#### Arguments
* $float **mixed**



### <a name="method-isOptFloat"></a>isOptFloat

    boolean ValidateCore::isOptFloat(float $float)

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L124)


#### Arguments
* $float **float** - &lt;p&gt;Float number to validate&lt;/p&gt;



### <a name="method-isCarrierName"></a>isCarrierName

    boolean ValidateCore::isCarrierName(string $name)

Check for a carrier name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L135)


#### Arguments
* $name **string** - &lt;p&gt;Carrier name to validate&lt;/p&gt;



### <a name="method-isImageSize"></a>isImageSize

    boolean ValidateCore::isImageSize(string $size)

Check for an image size validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L146)


#### Arguments
* $size **string** - &lt;p&gt;Image size to validate&lt;/p&gt;



### <a name="method-isName"></a>isName

    boolean ValidateCore::isName(string $name)

Check for name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L157)


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### <a name="method-isHookName"></a>isHookName

    boolean ValidateCore::isHookName(string $hook)

Check for hook name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L168)


#### Arguments
* $hook **string** - &lt;p&gt;Hook name to validate&lt;/p&gt;



### <a name="method-isMailName"></a>isMailName

    boolean ValidateCore::isMailName(string $mail_name)

Check for sender name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L179)


#### Arguments
* $mail_name **string** - &lt;p&gt;Sender name to validate&lt;/p&gt;



### <a name="method-isMailSubject"></a>isMailSubject

    boolean ValidateCore::isMailSubject(string $mail_subject)

Check for e-mail subject validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L190)


#### Arguments
* $mail_subject **string** - &lt;p&gt;e-mail subject to validate&lt;/p&gt;



### <a name="method-isModuleName"></a>isModuleName

    boolean ValidateCore::isModuleName(string $module_name)

Check for module name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L201)


#### Arguments
* $module_name **string** - &lt;p&gt;Module name to validate&lt;/p&gt;



### <a name="method-isTplName"></a>isTplName

    boolean ValidateCore::isTplName(string $tpl_name)

Check for template name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L212)


#### Arguments
* $tpl_name **string** - &lt;p&gt;Template name to validate&lt;/p&gt;



### <a name="method-isImageTypeName"></a>isImageTypeName

    boolean ValidateCore::isImageTypeName(string $type)

Check for image type name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L223)


#### Arguments
* $type **string** - &lt;p&gt;Image type name to validate&lt;/p&gt;



### <a name="method-isPrice"></a>isPrice

    boolean ValidateCore::isPrice(string $price)

Check for price validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L234)


#### Arguments
* $price **string** - &lt;p&gt;Price to validate&lt;/p&gt;



### <a name="method-isNegativePrice"></a>isNegativePrice

    boolean ValidateCore::isNegativePrice(string $price)

Check for price validity (including negative price)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L245)


#### Arguments
* $price **string** - &lt;p&gt;Price to validate&lt;/p&gt;



### <a name="method-isLanguageIsoCode"></a>isLanguageIsoCode

    boolean ValidateCore::isLanguageIsoCode(string $iso_code)

Check for language code (ISO) validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L256)


#### Arguments
* $iso_code **string** - &lt;p&gt;Language code (ISO) to validate&lt;/p&gt;



### <a name="method-isLanguageCode"></a>isLanguageCode

    mixed ValidateCore::isLanguageCode($s)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L261)


#### Arguments
* $s **mixed**



### <a name="method-isStateIsoCode"></a>isStateIsoCode

    mixed ValidateCore::isStateIsoCode($iso_code)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L266)


#### Arguments
* $iso_code **mixed**



### <a name="method-isNumericIsoCode"></a>isNumericIsoCode

    mixed ValidateCore::isNumericIsoCode($iso_code)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L271)


#### Arguments
* $iso_code **mixed**



### <a name="method-isDiscountName"></a>isDiscountName

    boolean ValidateCore::isDiscountName(string $voucher)

Check for voucher name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L282)


#### Arguments
* $voucher **string** - &lt;p&gt;voucher to validate&lt;/p&gt;



### <a name="method-isCatalogName"></a>isCatalogName

    boolean ValidateCore::isCatalogName(string $name)

Check for product or category name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L293)


#### Arguments
* $name **string** - &lt;p&gt;Product or category name to validate&lt;/p&gt;



### <a name="method-isMessage"></a>isMessage

    boolean ValidateCore::isMessage(string $message)

Check for a message validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L304)


#### Arguments
* $message **string** - &lt;p&gt;Message to validate&lt;/p&gt;



### <a name="method-isCountryName"></a>isCountryName

    boolean ValidateCore::isCountryName(string $name)

Check for a country name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L315)


#### Arguments
* $name **string** - &lt;p&gt;Country name to validate&lt;/p&gt;



### <a name="method-isLinkRewrite"></a>isLinkRewrite

    boolean ValidateCore::isLinkRewrite(string $link)

Check for a link (url-rewriting only) validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L326)


#### Arguments
* $link **string** - &lt;p&gt;Link to validate&lt;/p&gt;



### <a name="method-isRoutePattern"></a>isRoutePattern

    boolean ValidateCore::isRoutePattern(string $pattern)

Check for a route pattern validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L340)


#### Arguments
* $pattern **string** - &lt;p&gt;to validate&lt;/p&gt;



### <a name="method-isAddress"></a>isAddress

    boolean ValidateCore::isAddress(string $address)

Check for a postal address validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L354)


#### Arguments
* $address **string** - &lt;p&gt;Address to validate&lt;/p&gt;



### <a name="method-isCityName"></a>isCityName

    boolean ValidateCore::isCityName(string $city)

Check for city name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L365)


#### Arguments
* $city **string** - &lt;p&gt;City name to validate&lt;/p&gt;



### <a name="method-isValidSearch"></a>isValidSearch

    boolean ValidateCore::isValidSearch(string $search)

Check for search query validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L376)


#### Arguments
* $search **string** - &lt;p&gt;Query to validate&lt;/p&gt;



### <a name="method-isGenericName"></a>isGenericName

    boolean ValidateCore::isGenericName(string $name)

Check for standard name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L387)


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### <a name="method-isCleanHtml"></a>isCleanHtml

    boolean ValidateCore::isCleanHtml(string $html, $allow_iframe)

Check for HTML field validity (no XSS please !)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L398)


#### Arguments
* $html **string** - &lt;p&gt;HTML field to validate&lt;/p&gt;
* $allow_iframe **mixed**



### <a name="method-isReference"></a>isReference

    boolean ValidateCore::isReference(string $reference)

Check for product reference validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L425)


#### Arguments
* $reference **string** - &lt;p&gt;Product reference to validate&lt;/p&gt;



### <a name="method-isPasswd"></a>isPasswd

    boolean ValidateCore::isPasswd(string $passwd, integer $size)

Check for password validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L437)


#### Arguments
* $passwd **string** - &lt;p&gt;Password to validate&lt;/p&gt;
* $size **integer**



### <a name="method-isPasswdAdmin"></a>isPasswdAdmin

    mixed ValidateCore::isPasswdAdmin($passwd)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L442)


#### Arguments
* $passwd **mixed**



### <a name="method-isConfigName"></a>isConfigName

    boolean ValidateCore::isConfigName(string $config_name)

Check for configuration key validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L453)


#### Arguments
* $config_name **string** - &lt;p&gt;Configuration key to validate&lt;/p&gt;



### <a name="method-isPhpDateFormat"></a>isPhpDateFormat

    boolean ValidateCore::isPhpDateFormat(string $date_format)

Check date formats like http://php.net/manual/en/function.date.php



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L464)


#### Arguments
* $date_format **string** - &lt;p&gt;date format to check&lt;/p&gt;



### <a name="method-isDateFormat"></a>isDateFormat

    boolean ValidateCore::isDateFormat(string $date)

Check for date format



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L477)


#### Arguments
* $date **string** - &lt;p&gt;Date to validate&lt;/p&gt;



### <a name="method-isDate"></a>isDate

    boolean ValidateCore::isDate(string $date)

Check for date validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L488)


#### Arguments
* $date **string** - &lt;p&gt;Date to validate&lt;/p&gt;



### <a name="method-isBirthDate"></a>isBirthDate

    boolean ValidateCore::isBirthDate(string $date)

Check for birthDate validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L502)


#### Arguments
* $date **string** - &lt;p&gt;birthdate to validate&lt;/p&gt;



### <a name="method-isBool"></a>isBool

    boolean ValidateCore::isBool(boolean $bool)

Check for boolean validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L524)


#### Arguments
* $bool **boolean** - &lt;p&gt;Boolean to validate&lt;/p&gt;



### <a name="method-isPhoneNumber"></a>isPhoneNumber

    boolean ValidateCore::isPhoneNumber(string $number)

Check for phone number validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L535)


#### Arguments
* $number **string** - &lt;p&gt;Phone number to validate&lt;/p&gt;



### <a name="method-isEan13"></a>isEan13

    boolean ValidateCore::isEan13(string $ean13)

Check for barcode validity (EAN-13)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L546)


#### Arguments
* $ean13 **string** - &lt;p&gt;Barcode to validate&lt;/p&gt;



### <a name="method-isUpc"></a>isUpc

    boolean ValidateCore::isUpc(string $upc)

Check for barcode validity (UPC)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L557)


#### Arguments
* $upc **string** - &lt;p&gt;Barcode to validate&lt;/p&gt;



### <a name="method-isPostCode"></a>isPostCode

    boolean ValidateCore::isPostCode(string $postcode)

Check for postal code validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 568](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L568)


#### Arguments
* $postcode **string** - &lt;p&gt;Postal code to validate&lt;/p&gt;



### <a name="method-isZipCodeFormat"></a>isZipCodeFormat

    boolean ValidateCore::isZipCodeFormat(string $zip_code)

Check for zip code format validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L579)


#### Arguments
* $zip_code **string** - &lt;p&gt;zip code format to validate&lt;/p&gt;



### <a name="method-isOrderWay"></a>isOrderWay

    boolean ValidateCore::isOrderWay(string $way)

Check for table or identifier validity
Mostly used in database for ordering : ASC / DESC



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L594)


#### Arguments
* $way **string** - &lt;p&gt;Keyword to validate&lt;/p&gt;



### <a name="method-isOrderBy"></a>isOrderBy

    boolean ValidateCore::isOrderBy(string $order)

Check for table or identifier validity
Mostly used in database for ordering : ORDER BY field



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L606)


#### Arguments
* $order **string** - &lt;p&gt;Field to validate&lt;/p&gt;



### <a name="method-isTableOrIdentifier"></a>isTableOrIdentifier

    boolean ValidateCore::isTableOrIdentifier(string $table)

Check for table or identifier validity
Mostly used in database for table names and id_table



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L618)


#### Arguments
* $table **string** - &lt;p&gt;Table/identifier to validate&lt;/p&gt;



### <a name="method-isValuesList"></a>isValuesList

    mixed ValidateCore::isValuesList()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L626)




### <a name="method-isTagsList"></a>isTagsList

    boolean ValidateCore::isTagsList(string $list)

Check for tags list validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L640)


#### Arguments
* $list **string** - &lt;p&gt;List to validate&lt;/p&gt;



### <a name="method-isProductVisibility"></a>isProductVisibility

    boolean ValidateCore::isProductVisibility(string $s)

Check for product visibility



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L651)


#### Arguments
* $s **string** - &lt;p&gt;visibility to check&lt;/p&gt;



### <a name="method-isInt"></a>isInt

    boolean ValidateCore::isInt(integer $value)

Check for an integer validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L662)


#### Arguments
* $value **integer** - &lt;p&gt;Integer to validate&lt;/p&gt;



### <a name="method-isUnsignedInt"></a>isUnsignedInt

    boolean ValidateCore::isUnsignedInt(integer $value)

Check for an integer validity (unsigned)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 673](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L673)


#### Arguments
* $value **integer** - &lt;p&gt;Integer to validate&lt;/p&gt;



### <a name="method-isPercentage"></a>isPercentage

    boolean ValidateCore::isPercentage(float $value)

Check for an percentage validity (between 0 and 100)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 684](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L684)


#### Arguments
* $value **float** - &lt;p&gt;Float to validate&lt;/p&gt;



### <a name="method-isUnsignedId"></a>isUnsignedId

    boolean ValidateCore::isUnsignedId(integer $id)

Check for an integer validity (unsigned)
Mostly used in database for auto-increment



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L696)


#### Arguments
* $id **integer** - &lt;p&gt;Integer to validate&lt;/p&gt;



### <a name="method-isNullOrUnsignedId"></a>isNullOrUnsignedId

    mixed ValidateCore::isNullOrUnsignedId($id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 701](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L701)


#### Arguments
* $id **mixed**



### <a name="method-isLoadedObject"></a>isLoadedObject

    boolean ValidateCore::isLoadedObject(object $object)

Check object validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L712)


#### Arguments
* $object **object** - &lt;p&gt;Object to validate&lt;/p&gt;



### <a name="method-isColor"></a>isColor

    boolean ValidateCore::isColor($color)

Check object validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L723)


#### Arguments
* $color **mixed**



### <a name="method-isUrl"></a>isUrl

    boolean ValidateCore::isUrl(string $url)

Check url validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 734](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L734)


#### Arguments
* $url **string** - &lt;p&gt;Url to validate&lt;/p&gt;



### <a name="method-isTrackingNumber"></a>isTrackingNumber

    boolean ValidateCore::isTrackingNumber(string $tracking_number)

Check tracking number validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L745)


#### Arguments
* $tracking_number **string** - &lt;p&gt;Tracking number to validate&lt;/p&gt;



### <a name="method-isUrlOrEmpty"></a>isUrlOrEmpty

    boolean ValidateCore::isUrlOrEmpty(string $url)

Check url validity (allowed empty string)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 756](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L756)


#### Arguments
* $url **string** - &lt;p&gt;Url to validate&lt;/p&gt;



### <a name="method-isAbsoluteUrl"></a>isAbsoluteUrl

    boolean ValidateCore::isAbsoluteUrl(string $url)

Check if URL is absolute



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L767)


#### Arguments
* $url **string** - &lt;p&gt;URL to validate&lt;/p&gt;



### <a name="method-isMySQLEngine"></a>isMySQLEngine

    mixed ValidateCore::isMySQLEngine($engine)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 775](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L775)


#### Arguments
* $engine **mixed**



### <a name="method-isUnixName"></a>isUnixName

    mixed ValidateCore::isUnixName($data)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L780)


#### Arguments
* $data **mixed**



### <a name="method-isTablePrefix"></a>isTablePrefix

    mixed ValidateCore::isTablePrefix($data)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L785)


#### Arguments
* $data **mixed**



### <a name="method-isFileName"></a>isFileName

    boolean ValidateCore::isFileName(string $name)

Check for standard name file validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L797)


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### <a name="method-isDirName"></a>isDirName

    boolean ValidateCore::isDirName(string $dir)

Check for standard name directory validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L808)


#### Arguments
* $dir **string** - &lt;p&gt;Directory to validate&lt;/p&gt;



### <a name="method-isTabName"></a>isTabName

    boolean ValidateCore::isTabName(string $name)

Check for admin panel tab name validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 819](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L819)


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### <a name="method-isWeightUnit"></a>isWeightUnit

    mixed ValidateCore::isWeightUnit($unit)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 824](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L824)


#### Arguments
* $unit **mixed**



### <a name="method-isDistanceUnit"></a>isDistanceUnit

    mixed ValidateCore::isDistanceUnit($unit)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L829)


#### Arguments
* $unit **mixed**



### <a name="method-isSubDomainName"></a>isSubDomainName

    mixed ValidateCore::isSubDomainName($domain)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 834](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L834)


#### Arguments
* $domain **mixed**



### <a name="method-isVoucherDescription"></a>isVoucherDescription

    mixed ValidateCore::isVoucherDescription($text)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L839)


#### Arguments
* $text **mixed**



### <a name="method-isSortDirection"></a>isSortDirection

    boolean ValidateCore::isSortDirection(string $value)

Check if the value is a sort direction value (DESC/ASC)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 850](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L850)


#### Arguments
* $value **string**



### <a name="method-isLabel"></a>isLabel

    boolean ValidateCore::isLabel(string $label)

Customization fields' label validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 861](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L861)


#### Arguments
* $label **string**



### <a name="method-isPriceDisplayMethod"></a>isPriceDisplayMethod

    boolean ValidateCore::isPriceDisplayMethod(integer $data)

Price display method validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 872](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L872)


#### Arguments
* $data **integer** - &lt;p&gt;Data to validate&lt;/p&gt;



### <a name="method-isDniLite"></a>isDniLite

    boolean ValidateCore::isDniLite(string $dni)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 881](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L881)


#### Arguments
* $dni **string** - &lt;p&gt;to validate&lt;/p&gt;



### <a name="method-isCookie"></a>isCookie

    boolean ValidateCore::isCookie(mixed $data)

Check if $data is a PrestaShop cookie object



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 892](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L892)


#### Arguments
* $data **mixed** - &lt;p&gt;to validate&lt;/p&gt;



### <a name="method-isString"></a>isString

    boolean ValidateCore::isString(string $data)

Price display method validity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 903](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L903)


#### Arguments
* $data **string** - &lt;p&gt;Data to validate&lt;/p&gt;



### <a name="method-isReductionType"></a>isReductionType

    boolean ValidateCore::isReductionType(string $data)

Check if the data is a reduction type (amout or percentage)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 914](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L914)


#### Arguments
* $data **string** - &lt;p&gt;Data to validate&lt;/p&gt;



### <a name="method-isBoolId"></a>isBoolId

    boolean ValidateCore::isBoolId(string $ids)

Check for bool_id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L925)


#### Arguments
* $ids **string**



### <a name="method-isBool_Id"></a>isBool_Id

    mixed ValidateCore::isBool_Id($ids)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L933)


#### Arguments
* $ids **mixed**



### <a name="method-isLocalizationPackSelection"></a>isLocalizationPackSelection

    boolean ValidateCore::isLocalizationPackSelection(string $data)

Check the localization pack part selected



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 945](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L945)


#### Arguments
* $data **string** - &lt;p&gt;Localization pack to check&lt;/p&gt;



### <a name="method-isSerializedArray"></a>isSerializedArray

    boolean ValidateCore::isSerializedArray(string $data)

Check for PHP serialized data



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 956](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L956)


#### Arguments
* $data **string** - &lt;p&gt;Serialized data to validate&lt;/p&gt;



### <a name="method-isCoordinate"></a>isCoordinate

    boolean ValidateCore::isCoordinate(string $data)

Check for Latitude/Longitude



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 967](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L967)


#### Arguments
* $data **string** - &lt;p&gt;Coordinate to validate&lt;/p&gt;



### <a name="method-isLangIsoCode"></a>isLangIsoCode

    boolean ValidateCore::isLangIsoCode(string $iso_code)

Check for Language Iso Code



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 978](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L978)


#### Arguments
* $iso_code **string**



### <a name="method-isLanguageFileName"></a>isLanguageFileName

    boolean ValidateCore::isLanguageFileName(string $file_name)

Check for Language File Name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 989](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L989)


#### Arguments
* $file_name **string**



### <a name="method-isArrayWithIds"></a>isArrayWithIds

    boolean ValidateCore::isArrayWithIds(array $ids)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 999](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L999)


#### Arguments
* $ids **array**



### <a name="method-isSceneZones"></a>isSceneZones

    boolean ValidateCore::isSceneZones(array $zones)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 1016](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L1016)


#### Arguments
* $zones **array**



### <a name="method-isStockManagement"></a>isStockManagement

    boolean ValidateCore::isStockManagement(array $stock_management)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 1043](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L1043)


#### Arguments
* $stock_management **array**



### <a name="method-isSiret"></a>isSiret

    boolean ValidateCore::isSiret(string $siret)

Validate SIRET Code



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 1057](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L1057)


#### Arguments
* $siret **string** - &lt;p&gt;SIRET Code&lt;/p&gt;



### <a name="method-isApe"></a>isApe

    boolean ValidateCore::isApe(string $ape)

Validate APE Code



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L1079)


#### Arguments
* $ape **string** - &lt;p&gt;APE Code&lt;/p&gt;



### <a name="method-isControllerName"></a>isControllerName

    mixed ValidateCore::isControllerName($name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 1084](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L1084)


#### Arguments
* $name **mixed**



### <a name="method-isPrestaShopVersion"></a>isPrestaShopVersion

    mixed ValidateCore::isPrestaShopVersion($version)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L1089)


#### Arguments
* $version **mixed**



### <a name="method-isOrderInvoiceNumber"></a>isOrderInvoiceNumber

    mixed ValidateCore::isOrderInvoiceNumber($id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Validate.php line 1094](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Validate.php#L1094)


#### Arguments
* $id **mixed**


