ValidateCore
===============






* Class name: ValidateCore
* Namespace: 



Constants
----------


### ADMIN_PASSWORD_LENGTH

    const ADMIN_PASSWORD_LENGTH = 8





### PASSWORD_LENGTH

    const PASSWORD_LENGTH = 5







Methods
-------


### isIp2Long

    mixed ValidateCore::isIp2Long($ip)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $ip **mixed**



### isAnything

    mixed ValidateCore::isAnything()





* Visibility: **public**
* This method is **static**.




### isEmail

    boolean ValidateCore::isEmail(string $email)

Check for e-mail validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $email **string** - &lt;p&gt;e-mail address to validate&lt;/p&gt;



### isModuleUrl

    boolean ValidateCore::isModuleUrl(string $url, array $errors)

Check for module URL validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;module URL to validate&lt;/p&gt;
* $errors **array** - &lt;p&gt;Reference array for catching errors&lt;/p&gt;



### isMd5

    boolean ValidateCore::isMd5(string $md5)

Check for MD5 string validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $md5 **string** - &lt;p&gt;MD5 string to validate&lt;/p&gt;



### isSha1

    boolean ValidateCore::isSha1(string $sha1)

Check for SHA1 string validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $sha1 **string** - &lt;p&gt;SHA1 string to validate&lt;/p&gt;



### isFloat

    boolean ValidateCore::isFloat(float $float)

Check for a float number validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $float **float** - &lt;p&gt;Float number to validate&lt;/p&gt;



### isUnsignedFloat

    mixed ValidateCore::isUnsignedFloat($float)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $float **mixed**



### isOptFloat

    boolean ValidateCore::isOptFloat(float $float)

Check for a float number validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $float **float** - &lt;p&gt;Float number to validate&lt;/p&gt;



### isCarrierName

    boolean ValidateCore::isCarrierName(string $name)

Check for a carrier name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Carrier name to validate&lt;/p&gt;



### isImageSize

    boolean ValidateCore::isImageSize(string $size)

Check for an image size validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $size **string** - &lt;p&gt;Image size to validate&lt;/p&gt;



### isName

    boolean ValidateCore::isName(string $name)

Check for name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### isHookName

    boolean ValidateCore::isHookName(string $hook)

Check for hook name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $hook **string** - &lt;p&gt;Hook name to validate&lt;/p&gt;



### isMailName

    boolean ValidateCore::isMailName(string $mail_name)

Check for sender name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $mail_name **string** - &lt;p&gt;Sender name to validate&lt;/p&gt;



### isMailSubject

    boolean ValidateCore::isMailSubject(string $mail_subject)

Check for e-mail subject validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $mail_subject **string** - &lt;p&gt;e-mail subject to validate&lt;/p&gt;



### isModuleName

    boolean ValidateCore::isModuleName(string $module_name)

Check for module name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **string** - &lt;p&gt;Module name to validate&lt;/p&gt;



### isTplName

    boolean ValidateCore::isTplName(string $tpl_name)

Check for template name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $tpl_name **string** - &lt;p&gt;Template name to validate&lt;/p&gt;



### isImageTypeName

    boolean ValidateCore::isImageTypeName(string $type)

Check for image type name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $type **string** - &lt;p&gt;Image type name to validate&lt;/p&gt;



### isPrice

    boolean ValidateCore::isPrice(string $price)

Check for price validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $price **string** - &lt;p&gt;Price to validate&lt;/p&gt;



### isNegativePrice

    boolean ValidateCore::isNegativePrice(string $price)

Check for price validity (including negative price)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $price **string** - &lt;p&gt;Price to validate&lt;/p&gt;



### isLanguageIsoCode

    boolean ValidateCore::isLanguageIsoCode(string $iso_code)

Check for language code (ISO) validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **string** - &lt;p&gt;Language code (ISO) to validate&lt;/p&gt;



### isLanguageCode

    mixed ValidateCore::isLanguageCode($s)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $s **mixed**



### isStateIsoCode

    mixed ValidateCore::isStateIsoCode($iso_code)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **mixed**



### isNumericIsoCode

    mixed ValidateCore::isNumericIsoCode($iso_code)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **mixed**



### isDiscountName

    boolean ValidateCore::isDiscountName(string $voucher)

Check for voucher name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $voucher **string** - &lt;p&gt;voucher to validate&lt;/p&gt;



### isCatalogName

    boolean ValidateCore::isCatalogName(string $name)

Check for product or category name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Product or category name to validate&lt;/p&gt;



### isMessage

    boolean ValidateCore::isMessage(string $message)

Check for a message validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $message **string** - &lt;p&gt;Message to validate&lt;/p&gt;



### isCountryName

    boolean ValidateCore::isCountryName(string $name)

Check for a country name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Country name to validate&lt;/p&gt;



### isLinkRewrite

    boolean ValidateCore::isLinkRewrite(string $link)

Check for a link (url-rewriting only) validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $link **string** - &lt;p&gt;Link to validate&lt;/p&gt;



### isRoutePattern

    boolean ValidateCore::isRoutePattern(string $pattern)

Check for a route pattern validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $pattern **string** - &lt;p&gt;to validate&lt;/p&gt;



### isAddress

    boolean ValidateCore::isAddress(string $address)

Check for a postal address validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **string** - &lt;p&gt;Address to validate&lt;/p&gt;



### isCityName

    boolean ValidateCore::isCityName(string $city)

Check for city name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $city **string** - &lt;p&gt;City name to validate&lt;/p&gt;



### isValidSearch

    boolean ValidateCore::isValidSearch(string $search)

Check for search query validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $search **string** - &lt;p&gt;Query to validate&lt;/p&gt;



### isGenericName

    boolean ValidateCore::isGenericName(string $name)

Check for standard name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### isCleanHtml

    boolean ValidateCore::isCleanHtml(string $html, $allow_iframe)

Check for HTML field validity (no XSS please !)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $html **string** - &lt;p&gt;HTML field to validate&lt;/p&gt;
* $allow_iframe **mixed**



### isReference

    boolean ValidateCore::isReference(string $reference)

Check for product reference validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $reference **string** - &lt;p&gt;Product reference to validate&lt;/p&gt;



### isPasswd

    boolean ValidateCore::isPasswd(string $passwd, integer $size)

Check for password validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $passwd **string** - &lt;p&gt;Password to validate&lt;/p&gt;
* $size **integer**



### isPasswdAdmin

    mixed ValidateCore::isPasswdAdmin($passwd)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $passwd **mixed**



### isConfigName

    boolean ValidateCore::isConfigName(string $config_name)

Check for configuration key validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $config_name **string** - &lt;p&gt;Configuration key to validate&lt;/p&gt;



### isPhpDateFormat

    boolean ValidateCore::isPhpDateFormat(string $date_format)

Check date formats like http://php.net/manual/en/function.date.php



* Visibility: **public**
* This method is **static**.


#### Arguments
* $date_format **string** - &lt;p&gt;date format to check&lt;/p&gt;



### isDateFormat

    boolean ValidateCore::isDateFormat(string $date)

Check for date format



* Visibility: **public**
* This method is **static**.


#### Arguments
* $date **string** - &lt;p&gt;Date to validate&lt;/p&gt;



### isDate

    boolean ValidateCore::isDate(string $date)

Check for date validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $date **string** - &lt;p&gt;Date to validate&lt;/p&gt;



### isBirthDate

    boolean ValidateCore::isBirthDate(string $date)

Check for birthDate validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $date **string** - &lt;p&gt;birthdate to validate&lt;/p&gt;



### isBool

    boolean ValidateCore::isBool(boolean $bool)

Check for boolean validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $bool **boolean** - &lt;p&gt;Boolean to validate&lt;/p&gt;



### isPhoneNumber

    boolean ValidateCore::isPhoneNumber(string $number)

Check for phone number validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $number **string** - &lt;p&gt;Phone number to validate&lt;/p&gt;



### isEan13

    boolean ValidateCore::isEan13(string $ean13)

Check for barcode validity (EAN-13)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $ean13 **string** - &lt;p&gt;Barcode to validate&lt;/p&gt;



### isUpc

    boolean ValidateCore::isUpc(string $upc)

Check for barcode validity (UPC)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $upc **string** - &lt;p&gt;Barcode to validate&lt;/p&gt;



### isPostCode

    boolean ValidateCore::isPostCode(string $postcode)

Check for postal code validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $postcode **string** - &lt;p&gt;Postal code to validate&lt;/p&gt;



### isZipCodeFormat

    boolean ValidateCore::isZipCodeFormat(string $zip_code)

Check for zip code format validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $zip_code **string** - &lt;p&gt;zip code format to validate&lt;/p&gt;



### isOrderWay

    boolean ValidateCore::isOrderWay(string $way)

Check for table or identifier validity
Mostly used in database for ordering : ASC / DESC



* Visibility: **public**
* This method is **static**.


#### Arguments
* $way **string** - &lt;p&gt;Keyword to validate&lt;/p&gt;



### isOrderBy

    boolean ValidateCore::isOrderBy(string $order)

Check for table or identifier validity
Mostly used in database for ordering : ORDER BY field



* Visibility: **public**
* This method is **static**.


#### Arguments
* $order **string** - &lt;p&gt;Field to validate&lt;/p&gt;



### isTableOrIdentifier

    boolean ValidateCore::isTableOrIdentifier(string $table)

Check for table or identifier validity
Mostly used in database for table names and id_table



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **string** - &lt;p&gt;Table/identifier to validate&lt;/p&gt;



### isValuesList

    mixed ValidateCore::isValuesList()





* Visibility: **public**
* This method is **static**.




### isTagsList

    boolean ValidateCore::isTagsList(string $list)

Check for tags list validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $list **string** - &lt;p&gt;List to validate&lt;/p&gt;



### isProductVisibility

    boolean ValidateCore::isProductVisibility(string $s)

Check for product visibility



* Visibility: **public**
* This method is **static**.


#### Arguments
* $s **string** - &lt;p&gt;visibility to check&lt;/p&gt;



### isInt

    boolean ValidateCore::isInt(integer $value)

Check for an integer validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **integer** - &lt;p&gt;Integer to validate&lt;/p&gt;



### isUnsignedInt

    boolean ValidateCore::isUnsignedInt(integer $value)

Check for an integer validity (unsigned)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **integer** - &lt;p&gt;Integer to validate&lt;/p&gt;



### isPercentage

    boolean ValidateCore::isPercentage(float $value)

Check for an percentage validity (between 0 and 100)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **float** - &lt;p&gt;Float to validate&lt;/p&gt;



### isUnsignedId

    boolean ValidateCore::isUnsignedId(integer $id)

Check for an integer validity (unsigned)
Mostly used in database for auto-increment



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **integer** - &lt;p&gt;Integer to validate&lt;/p&gt;



### isNullOrUnsignedId

    mixed ValidateCore::isNullOrUnsignedId($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### isLoadedObject

    boolean ValidateCore::isLoadedObject(object $object)

Check object validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $object **object** - &lt;p&gt;Object to validate&lt;/p&gt;



### isColor

    boolean ValidateCore::isColor($color)

Check object validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $color **mixed**



### isUrl

    boolean ValidateCore::isUrl(string $url)

Check url validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;Url to validate&lt;/p&gt;



### isTrackingNumber

    boolean ValidateCore::isTrackingNumber(string $tracking_number)

Check tracking number validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $tracking_number **string** - &lt;p&gt;Tracking number to validate&lt;/p&gt;



### isUrlOrEmpty

    boolean ValidateCore::isUrlOrEmpty(string $url)

Check url validity (allowed empty string)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;Url to validate&lt;/p&gt;



### isAbsoluteUrl

    boolean ValidateCore::isAbsoluteUrl(string $url)

Check if URL is absolute



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;URL to validate&lt;/p&gt;



### isMySQLEngine

    mixed ValidateCore::isMySQLEngine($engine)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $engine **mixed**



### isUnixName

    mixed ValidateCore::isUnixName($data)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **mixed**



### isTablePrefix

    mixed ValidateCore::isTablePrefix($data)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **mixed**



### isFileName

    boolean ValidateCore::isFileName(string $name)

Check for standard name file validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### isDirName

    boolean ValidateCore::isDirName(string $dir)

Check for standard name directory validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $dir **string** - &lt;p&gt;Directory to validate&lt;/p&gt;



### isTabName

    boolean ValidateCore::isTabName(string $name)

Check for admin panel tab name validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Name to validate&lt;/p&gt;



### isWeightUnit

    mixed ValidateCore::isWeightUnit($unit)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $unit **mixed**



### isDistanceUnit

    mixed ValidateCore::isDistanceUnit($unit)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $unit **mixed**



### isSubDomainName

    mixed ValidateCore::isSubDomainName($domain)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $domain **mixed**



### isVoucherDescription

    mixed ValidateCore::isVoucherDescription($text)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $text **mixed**



### isSortDirection

    boolean ValidateCore::isSortDirection(string $value)

Check if the value is a sort direction value (DESC/ASC)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **string**



### isLabel

    boolean ValidateCore::isLabel(string $label)

Customization fields' label validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $label **string**



### isPriceDisplayMethod

    boolean ValidateCore::isPriceDisplayMethod(integer $data)

Price display method validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **integer** - &lt;p&gt;Data to validate&lt;/p&gt;



### isDniLite

    boolean ValidateCore::isDniLite(string $dni)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dni **string** - &lt;p&gt;to validate&lt;/p&gt;



### isCookie

    boolean ValidateCore::isCookie(mixed $data)

Check if $data is a PrestaShop cookie object



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **mixed** - &lt;p&gt;to validate&lt;/p&gt;



### isString

    boolean ValidateCore::isString(string $data)

Price display method validity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **string** - &lt;p&gt;Data to validate&lt;/p&gt;



### isReductionType

    boolean ValidateCore::isReductionType(string $data)

Check if the data is a reduction type (amout or percentage)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **string** - &lt;p&gt;Data to validate&lt;/p&gt;



### isBoolId

    boolean ValidateCore::isBoolId(string $ids)

Check for bool_id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $ids **string**



### isBool_Id

    mixed ValidateCore::isBool_Id($ids)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $ids **mixed**



### isLocalizationPackSelection

    boolean ValidateCore::isLocalizationPackSelection(string $data)

Check the localization pack part selected



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **string** - &lt;p&gt;Localization pack to check&lt;/p&gt;



### isSerializedArray

    boolean ValidateCore::isSerializedArray(string $data)

Check for PHP serialized data



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **string** - &lt;p&gt;Serialized data to validate&lt;/p&gt;



### isCoordinate

    boolean ValidateCore::isCoordinate(string $data)

Check for Latitude/Longitude



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **string** - &lt;p&gt;Coordinate to validate&lt;/p&gt;



### isLangIsoCode

    boolean ValidateCore::isLangIsoCode(string $iso_code)

Check for Language Iso Code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **string**



### isLanguageFileName

    boolean ValidateCore::isLanguageFileName(string $file_name)

Check for Language File Name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $file_name **string**



### isArrayWithIds

    boolean ValidateCore::isArrayWithIds(array $ids)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $ids **array**



### isSceneZones

    boolean ValidateCore::isSceneZones(array $zones)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $zones **array**



### isStockManagement

    boolean ValidateCore::isStockManagement(array $stock_management)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $stock_management **array**



### isSiret

    boolean ValidateCore::isSiret(string $siret)

Validate SIRET Code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $siret **string** - &lt;p&gt;SIRET Code&lt;/p&gt;



### isApe

    boolean ValidateCore::isApe(string $ape)

Validate APE Code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $ape **string** - &lt;p&gt;APE Code&lt;/p&gt;



### isControllerName

    mixed ValidateCore::isControllerName($name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**



### isPrestaShopVersion

    mixed ValidateCore::isPrestaShopVersion($version)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $version **mixed**



### isOrderInvoiceNumber

    mixed ValidateCore::isOrderInvoiceNumber($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**


