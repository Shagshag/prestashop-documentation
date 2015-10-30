Class ValidateCore
=====================





* Class name: ValidateCore
* Source: [classes/Validate.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L27)


Contents
--------

### Constants

* [ADMIN_PASSWORD_LENGTH](#constant-ADMIN_PASSWORD_LENGTH)
* [PASSWORD_LENGTH](#constant-PASSWORD_LENGTH)


### Methods

* [isAbsoluteUrl](#method-isAbsoluteUrl)
* [isAddress](#method-isAddress)
* [isAnything](#method-isAnything)
* [isApe](#method-isApe)
* [isArrayWithIds](#method-isArrayWithIds)
* [isBirthDate](#method-isBirthDate)
* [isBool](#method-isBool)
* [isBoolId](#method-isBoolId)
* [isBool_Id](#method-isBool_Id)
* [isCarrierName](#method-isCarrierName)
* [isCatalogName](#method-isCatalogName)
* [isCityName](#method-isCityName)
* [isCleanHtml](#method-isCleanHtml)
* [isColor](#method-isColor)
* [isConfigName](#method-isConfigName)
* [isControllerName](#method-isControllerName)
* [isCookie](#method-isCookie)
* [isCoordinate](#method-isCoordinate)
* [isCountryName](#method-isCountryName)
* [isDate](#method-isDate)
* [isDateFormat](#method-isDateFormat)
* [isDirName](#method-isDirName)
* [isDiscountName](#method-isDiscountName)
* [isDistanceUnit](#method-isDistanceUnit)
* [isDniLite](#method-isDniLite)
* [isEan13](#method-isEan13)
* [isEmail](#method-isEmail)
* [isFileName](#method-isFileName)
* [isFloat](#method-isFloat)
* [isGenericName](#method-isGenericName)
* [isHookName](#method-isHookName)
* [isImageSize](#method-isImageSize)
* [isImageTypeName](#method-isImageTypeName)
* [isInt](#method-isInt)
* [isIp2Long](#method-isIp2Long)
* [isLabel](#method-isLabel)
* [isLangIsoCode](#method-isLangIsoCode)
* [isLanguageCode](#method-isLanguageCode)
* [isLanguageFileName](#method-isLanguageFileName)
* [isLanguageIsoCode](#method-isLanguageIsoCode)
* [isLinkRewrite](#method-isLinkRewrite)
* [isLoadedObject](#method-isLoadedObject)
* [isLocalizationPackSelection](#method-isLocalizationPackSelection)
* [isMailName](#method-isMailName)
* [isMailSubject](#method-isMailSubject)
* [isMd5](#method-isMd5)
* [isMessage](#method-isMessage)
* [isModuleName](#method-isModuleName)
* [isModuleUrl](#method-isModuleUrl)
* [isMySQLEngine](#method-isMySQLEngine)
* [isName](#method-isName)
* [isNegativePrice](#method-isNegativePrice)
* [isNullOrUnsignedId](#method-isNullOrUnsignedId)
* [isNumericIsoCode](#method-isNumericIsoCode)
* [isOptFloat](#method-isOptFloat)
* [isOrderBy](#method-isOrderBy)
* [isOrderInvoiceNumber](#method-isOrderInvoiceNumber)
* [isOrderWay](#method-isOrderWay)
* [isPasswd](#method-isPasswd)
* [isPasswdAdmin](#method-isPasswdAdmin)
* [isPercentage](#method-isPercentage)
* [isPhoneNumber](#method-isPhoneNumber)
* [isPhpDateFormat](#method-isPhpDateFormat)
* [isPostCode](#method-isPostCode)
* [isPrestaShopVersion](#method-isPrestaShopVersion)
* [isPrice](#method-isPrice)
* [isPriceDisplayMethod](#method-isPriceDisplayMethod)
* [isProductVisibility](#method-isProductVisibility)
* [isReductionType](#method-isReductionType)
* [isReference](#method-isReference)
* [isRoutePattern](#method-isRoutePattern)
* [isSceneZones](#method-isSceneZones)
* [isSerializedArray](#method-isSerializedArray)
* [isSha1](#method-isSha1)
* [isSiret](#method-isSiret)
* [isSortDirection](#method-isSortDirection)
* [isStateIsoCode](#method-isStateIsoCode)
* [isStockManagement](#method-isStockManagement)
* [isString](#method-isString)
* [isSubDomainName](#method-isSubDomainName)
* [isTabName](#method-isTabName)
* [isTableOrIdentifier](#method-isTableOrIdentifier)
* [isTablePrefix](#method-isTablePrefix)
* [isTagsList](#method-isTagsList)
* [isTplName](#method-isTplName)
* [isTrackingNumber](#method-isTrackingNumber)
* [isUnixName](#method-isUnixName)
* [isUnsignedFloat](#method-isUnsignedFloat)
* [isUnsignedId](#method-isUnsignedId)
* [isUnsignedInt](#method-isUnsignedInt)
* [isUpc](#method-isUpc)
* [isUrl](#method-isUrl)
* [isUrlOrEmpty](#method-isUrlOrEmpty)
* [isValidSearch](#method-isValidSearch)
* [isValuesList](#method-isValuesList)
* [isVoucherDescription](#method-isVoucherDescription)
* [isWeightUnit](#method-isWeightUnit)
* [isZipCodeFormat](#method-isZipCodeFormat)


Constants
----------


### <a name="constant-ADMIN_PASSWORD_LENGTH"></a>ADMIN_PASSWORD_LENGTH

```php
const ADMIN_PASSWORD_LENGTH = 8
```





* Source: [classes/Validate.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L29).


### <a name="constant-PASSWORD_LENGTH"></a>PASSWORD_LENGTH

```php
const PASSWORD_LENGTH = 5
```





* Source: [classes/Validate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L30).




Methods
-------


### <a name="method-isAbsoluteUrl"></a>isAbsoluteUrl

```php
boolean ValidateCore::isAbsoluteUrl(string $url)
```

Check if URL is absolute



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L767)


#### Arguments
* $url **string** - URL to validate



### <a name="method-isAddress"></a>isAddress

```php
boolean ValidateCore::isAddress(string $address)
```

Check for a postal address validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L354)


#### Arguments
* $address **string** - Address to validate



### <a name="method-isAnything"></a>isAnything

```php
mixed ValidateCore::isAnything()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L37)




### <a name="method-isApe"></a>isApe

```php
boolean ValidateCore::isApe(string $ape)
```

Validate APE Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L1079)


#### Arguments
* $ape **string** - APE Code



### <a name="method-isArrayWithIds"></a>isArrayWithIds

```php
boolean ValidateCore::isArrayWithIds(array $ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 999](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L999)


#### Arguments
* $ids **array**



### <a name="method-isBirthDate"></a>isBirthDate

```php
boolean ValidateCore::isBirthDate(string $date)
```

Check for birthDate validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L502)


#### Arguments
* $date **string** - birthdate to validate



### <a name="method-isBool"></a>isBool

```php
boolean ValidateCore::isBool(boolean $bool)
```

Check for boolean validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L524)


#### Arguments
* $bool **boolean** - Boolean to validate



### <a name="method-isBoolId"></a>isBoolId

```php
boolean ValidateCore::isBoolId(string $ids)
```

Check for bool_id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L925)


#### Arguments
* $ids **string**



### <a name="method-isBool_Id"></a>isBool_Id

```php
mixed ValidateCore::isBool_Id($ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L933)


#### Arguments
* $ids **mixed**



### <a name="method-isCarrierName"></a>isCarrierName

```php
boolean ValidateCore::isCarrierName(string $name)
```

Check for a carrier name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L135)


#### Arguments
* $name **string** - Carrier name to validate



### <a name="method-isCatalogName"></a>isCatalogName

```php
boolean ValidateCore::isCatalogName(string $name)
```

Check for product or category name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L293)


#### Arguments
* $name **string** - Product or category name to validate



### <a name="method-isCityName"></a>isCityName

```php
boolean ValidateCore::isCityName(string $city)
```

Check for city name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L365)


#### Arguments
* $city **string** - City name to validate



### <a name="method-isCleanHtml"></a>isCleanHtml

```php
boolean ValidateCore::isCleanHtml(string $html, $allow_iframe)
```

Check for HTML field validity (no XSS please !)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L398)


#### Arguments
* $html **string** - HTML field to validate
* $allow_iframe **mixed**



### <a name="method-isColor"></a>isColor

```php
boolean ValidateCore::isColor($color)
```

Check object validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L723)


#### Arguments
* $color **mixed**



### <a name="method-isConfigName"></a>isConfigName

```php
boolean ValidateCore::isConfigName(string $config_name)
```

Check for configuration key validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L453)


#### Arguments
* $config_name **string** - Configuration key to validate



### <a name="method-isControllerName"></a>isControllerName

```php
mixed ValidateCore::isControllerName($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1084](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L1084)


#### Arguments
* $name **mixed**



### <a name="method-isCookie"></a>isCookie

```php
boolean ValidateCore::isCookie(mixed $data)
```

Check if $data is a PrestaShop cookie object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 892](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L892)


#### Arguments
* $data **mixed** - to validate



### <a name="method-isCoordinate"></a>isCoordinate

```php
boolean ValidateCore::isCoordinate(string $data)
```

Check for Latitude/Longitude



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 967](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L967)


#### Arguments
* $data **string** - Coordinate to validate



### <a name="method-isCountryName"></a>isCountryName

```php
boolean ValidateCore::isCountryName(string $name)
```

Check for a country name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L315)


#### Arguments
* $name **string** - Country name to validate



### <a name="method-isDate"></a>isDate

```php
boolean ValidateCore::isDate(string $date)
```

Check for date validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L488)


#### Arguments
* $date **string** - Date to validate



### <a name="method-isDateFormat"></a>isDateFormat

```php
boolean ValidateCore::isDateFormat(string $date)
```

Check for date format



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L477)


#### Arguments
* $date **string** - Date to validate



### <a name="method-isDirName"></a>isDirName

```php
boolean ValidateCore::isDirName(string $dir)
```

Check for standard name directory validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L808)


#### Arguments
* $dir **string** - Directory to validate



### <a name="method-isDiscountName"></a>isDiscountName

```php
boolean ValidateCore::isDiscountName(string $voucher)
```

Check for voucher name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L282)


#### Arguments
* $voucher **string** - voucher to validate



### <a name="method-isDistanceUnit"></a>isDistanceUnit

```php
mixed ValidateCore::isDistanceUnit($unit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L829)


#### Arguments
* $unit **mixed**



### <a name="method-isDniLite"></a>isDniLite

```php
boolean ValidateCore::isDniLite(string $dni)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 881](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L881)


#### Arguments
* $dni **string** - to validate



### <a name="method-isEan13"></a>isEan13

```php
boolean ValidateCore::isEan13(string $ean13)
```

Check for barcode validity (EAN-13)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L546)


#### Arguments
* $ean13 **string** - Barcode to validate



### <a name="method-isEmail"></a>isEmail

```php
boolean ValidateCore::isEmail(string $email)
```

Check for e-mail validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L48)


#### Arguments
* $email **string** - e-mail address to validate



### <a name="method-isFileName"></a>isFileName

```php
boolean ValidateCore::isFileName(string $name)
```

Check for standard name file validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L797)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isFloat"></a>isFloat

```php
boolean ValidateCore::isFloat(float $float)
```

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L108)


#### Arguments
* $float **float** - Float number to validate



### <a name="method-isGenericName"></a>isGenericName

```php
boolean ValidateCore::isGenericName(string $name)
```

Check for standard name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L387)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isHookName"></a>isHookName

```php
boolean ValidateCore::isHookName(string $hook)
```

Check for hook name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L168)


#### Arguments
* $hook **string** - Hook name to validate



### <a name="method-isImageSize"></a>isImageSize

```php
boolean ValidateCore::isImageSize(string $size)
```

Check for an image size validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L146)


#### Arguments
* $size **string** - Image size to validate



### <a name="method-isImageTypeName"></a>isImageTypeName

```php
boolean ValidateCore::isImageTypeName(string $type)
```

Check for image type name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L223)


#### Arguments
* $type **string** - Image type name to validate



### <a name="method-isInt"></a>isInt

```php
boolean ValidateCore::isInt(integer $value)
```

Check for an integer validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L662)


#### Arguments
* $value **integer** - Integer to validate



### <a name="method-isIp2Long"></a>isIp2Long

```php
mixed ValidateCore::isIp2Long($ip)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L32)


#### Arguments
* $ip **mixed**



### <a name="method-isLabel"></a>isLabel

```php
boolean ValidateCore::isLabel(string $label)
```

Customization fields' label validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 861](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L861)


#### Arguments
* $label **string**



### <a name="method-isLangIsoCode"></a>isLangIsoCode

```php
boolean ValidateCore::isLangIsoCode(string $iso_code)
```

Check for Language Iso Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 978](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L978)


#### Arguments
* $iso_code **string**



### <a name="method-isLanguageCode"></a>isLanguageCode

```php
mixed ValidateCore::isLanguageCode($s)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L261)


#### Arguments
* $s **mixed**



### <a name="method-isLanguageFileName"></a>isLanguageFileName

```php
boolean ValidateCore::isLanguageFileName(string $file_name)
```

Check for Language File Name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 989](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L989)


#### Arguments
* $file_name **string**



### <a name="method-isLanguageIsoCode"></a>isLanguageIsoCode

```php
boolean ValidateCore::isLanguageIsoCode(string $iso_code)
```

Check for language code (ISO) validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L256)


#### Arguments
* $iso_code **string** - Language code (ISO) to validate



### <a name="method-isLinkRewrite"></a>isLinkRewrite

```php
boolean ValidateCore::isLinkRewrite(string $link)
```

Check for a link (url-rewriting only) validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L326)


#### Arguments
* $link **string** - Link to validate



### <a name="method-isLoadedObject"></a>isLoadedObject

```php
boolean ValidateCore::isLoadedObject(object $object)
```

Check object validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L712)


#### Arguments
* $object **object** - Object to validate



### <a name="method-isLocalizationPackSelection"></a>isLocalizationPackSelection

```php
boolean ValidateCore::isLocalizationPackSelection(string $data)
```

Check the localization pack part selected



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 945](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L945)


#### Arguments
* $data **string** - Localization pack to check



### <a name="method-isMailName"></a>isMailName

```php
boolean ValidateCore::isMailName(string $mail_name)
```

Check for sender name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L179)


#### Arguments
* $mail_name **string** - Sender name to validate



### <a name="method-isMailSubject"></a>isMailSubject

```php
boolean ValidateCore::isMailSubject(string $mail_subject)
```

Check for e-mail subject validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L190)


#### Arguments
* $mail_subject **string** - e-mail subject to validate



### <a name="method-isMd5"></a>isMd5

```php
boolean ValidateCore::isMd5(string $md5)
```

Check for MD5 string validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L86)


#### Arguments
* $md5 **string** - MD5 string to validate



### <a name="method-isMessage"></a>isMessage

```php
boolean ValidateCore::isMessage(string $message)
```

Check for a message validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L304)


#### Arguments
* $message **string** - Message to validate



### <a name="method-isModuleName"></a>isModuleName

```php
boolean ValidateCore::isModuleName(string $module_name)
```

Check for module name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L201)


#### Arguments
* $module_name **string** - Module name to validate



### <a name="method-isModuleUrl"></a>isModuleUrl

```php
boolean ValidateCore::isModuleUrl(string $url, array $errors)
```

Check for module URL validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L60)


#### Arguments
* $url **string** - module URL to validate
* $errors **array** - Reference array for catching errors



### <a name="method-isMySQLEngine"></a>isMySQLEngine

```php
mixed ValidateCore::isMySQLEngine($engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 775](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L775)


#### Arguments
* $engine **mixed**



### <a name="method-isName"></a>isName

```php
boolean ValidateCore::isName(string $name)
```

Check for name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L157)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isNegativePrice"></a>isNegativePrice

```php
boolean ValidateCore::isNegativePrice(string $price)
```

Check for price validity (including negative price)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L245)


#### Arguments
* $price **string** - Price to validate



### <a name="method-isNullOrUnsignedId"></a>isNullOrUnsignedId

```php
mixed ValidateCore::isNullOrUnsignedId($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 701](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L701)


#### Arguments
* $id **mixed**



### <a name="method-isNumericIsoCode"></a>isNumericIsoCode

```php
mixed ValidateCore::isNumericIsoCode($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L271)


#### Arguments
* $iso_code **mixed**



### <a name="method-isOptFloat"></a>isOptFloat

```php
boolean ValidateCore::isOptFloat(float $float)
```

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L124)


#### Arguments
* $float **float** - Float number to validate



### <a name="method-isOrderBy"></a>isOrderBy

```php
boolean ValidateCore::isOrderBy(string $order)
```

Check for table or identifier validity
Mostly used in database for ordering : ORDER BY field



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L606)


#### Arguments
* $order **string** - Field to validate



### <a name="method-isOrderInvoiceNumber"></a>isOrderInvoiceNumber

```php
mixed ValidateCore::isOrderInvoiceNumber($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1094](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L1094)


#### Arguments
* $id **mixed**



### <a name="method-isOrderWay"></a>isOrderWay

```php
boolean ValidateCore::isOrderWay(string $way)
```

Check for table or identifier validity
Mostly used in database for ordering : ASC / DESC



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L594)


#### Arguments
* $way **string** - Keyword to validate



### <a name="method-isPasswd"></a>isPasswd

```php
boolean ValidateCore::isPasswd(string $passwd, integer $size)
```

Check for password validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L437)


#### Arguments
* $passwd **string** - Password to validate
* $size **integer**



### <a name="method-isPasswdAdmin"></a>isPasswdAdmin

```php
mixed ValidateCore::isPasswdAdmin($passwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L442)


#### Arguments
* $passwd **mixed**



### <a name="method-isPercentage"></a>isPercentage

```php
boolean ValidateCore::isPercentage(float $value)
```

Check for an percentage validity (between 0 and 100)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 684](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L684)


#### Arguments
* $value **float** - Float to validate



### <a name="method-isPhoneNumber"></a>isPhoneNumber

```php
boolean ValidateCore::isPhoneNumber(string $number)
```

Check for phone number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L535)


#### Arguments
* $number **string** - Phone number to validate



### <a name="method-isPhpDateFormat"></a>isPhpDateFormat

```php
boolean ValidateCore::isPhpDateFormat(string $date_format)
```

Check date formats like http://php.net/manual/en/function.date.php



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L464)


#### Arguments
* $date_format **string** - date format to check



### <a name="method-isPostCode"></a>isPostCode

```php
boolean ValidateCore::isPostCode(string $postcode)
```

Check for postal code validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 568](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L568)


#### Arguments
* $postcode **string** - Postal code to validate



### <a name="method-isPrestaShopVersion"></a>isPrestaShopVersion

```php
mixed ValidateCore::isPrestaShopVersion($version)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L1089)


#### Arguments
* $version **mixed**



### <a name="method-isPrice"></a>isPrice

```php
boolean ValidateCore::isPrice(string $price)
```

Check for price validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L234)


#### Arguments
* $price **string** - Price to validate



### <a name="method-isPriceDisplayMethod"></a>isPriceDisplayMethod

```php
boolean ValidateCore::isPriceDisplayMethod(integer $data)
```

Price display method validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 872](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L872)


#### Arguments
* $data **integer** - Data to validate



### <a name="method-isProductVisibility"></a>isProductVisibility

```php
boolean ValidateCore::isProductVisibility(string $s)
```

Check for product visibility



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L651)


#### Arguments
* $s **string** - visibility to check



### <a name="method-isReductionType"></a>isReductionType

```php
boolean ValidateCore::isReductionType(string $data)
```

Check if the data is a reduction type (amout or percentage)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 914](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L914)


#### Arguments
* $data **string** - Data to validate



### <a name="method-isReference"></a>isReference

```php
boolean ValidateCore::isReference(string $reference)
```

Check for product reference validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L425)


#### Arguments
* $reference **string** - Product reference to validate



### <a name="method-isRoutePattern"></a>isRoutePattern

```php
boolean ValidateCore::isRoutePattern(string $pattern)
```

Check for a route pattern validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L340)


#### Arguments
* $pattern **string** - to validate



### <a name="method-isSceneZones"></a>isSceneZones

```php
boolean ValidateCore::isSceneZones(array $zones)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1016](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L1016)


#### Arguments
* $zones **array**



### <a name="method-isSerializedArray"></a>isSerializedArray

```php
boolean ValidateCore::isSerializedArray(string $data)
```

Check for PHP serialized data



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 956](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L956)


#### Arguments
* $data **string** - Serialized data to validate



### <a name="method-isSha1"></a>isSha1

```php
boolean ValidateCore::isSha1(string $sha1)
```

Check for SHA1 string validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L97)


#### Arguments
* $sha1 **string** - SHA1 string to validate



### <a name="method-isSiret"></a>isSiret

```php
boolean ValidateCore::isSiret(string $siret)
```

Validate SIRET Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1057](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L1057)


#### Arguments
* $siret **string** - SIRET Code



### <a name="method-isSortDirection"></a>isSortDirection

```php
boolean ValidateCore::isSortDirection(string $value)
```

Check if the value is a sort direction value (DESC/ASC)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 850](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L850)


#### Arguments
* $value **string**



### <a name="method-isStateIsoCode"></a>isStateIsoCode

```php
mixed ValidateCore::isStateIsoCode($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L266)


#### Arguments
* $iso_code **mixed**



### <a name="method-isStockManagement"></a>isStockManagement

```php
boolean ValidateCore::isStockManagement(array $stock_management)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1043](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L1043)


#### Arguments
* $stock_management **array**



### <a name="method-isString"></a>isString

```php
boolean ValidateCore::isString(string $data)
```

Price display method validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 903](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L903)


#### Arguments
* $data **string** - Data to validate



### <a name="method-isSubDomainName"></a>isSubDomainName

```php
mixed ValidateCore::isSubDomainName($domain)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 834](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L834)


#### Arguments
* $domain **mixed**



### <a name="method-isTabName"></a>isTabName

```php
boolean ValidateCore::isTabName(string $name)
```

Check for admin panel tab name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 819](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L819)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isTableOrIdentifier"></a>isTableOrIdentifier

```php
boolean ValidateCore::isTableOrIdentifier(string $table)
```

Check for table or identifier validity
Mostly used in database for table names and id_table



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L618)


#### Arguments
* $table **string** - Table/identifier to validate



### <a name="method-isTablePrefix"></a>isTablePrefix

```php
mixed ValidateCore::isTablePrefix($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L785)


#### Arguments
* $data **mixed**



### <a name="method-isTagsList"></a>isTagsList

```php
boolean ValidateCore::isTagsList(string $list)
```

Check for tags list validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L640)


#### Arguments
* $list **string** - List to validate



### <a name="method-isTplName"></a>isTplName

```php
boolean ValidateCore::isTplName(string $tpl_name)
```

Check for template name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L212)


#### Arguments
* $tpl_name **string** - Template name to validate



### <a name="method-isTrackingNumber"></a>isTrackingNumber

```php
boolean ValidateCore::isTrackingNumber(string $tracking_number)
```

Check tracking number validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L745)


#### Arguments
* $tracking_number **string** - Tracking number to validate



### <a name="method-isUnixName"></a>isUnixName

```php
mixed ValidateCore::isUnixName($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L780)


#### Arguments
* $data **mixed**



### <a name="method-isUnsignedFloat"></a>isUnsignedFloat

```php
mixed ValidateCore::isUnsignedFloat($float)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L113)


#### Arguments
* $float **mixed**



### <a name="method-isUnsignedId"></a>isUnsignedId

```php
boolean ValidateCore::isUnsignedId(integer $id)
```

Check for an integer validity (unsigned)
Mostly used in database for auto-increment



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L696)


#### Arguments
* $id **integer** - Integer to validate



### <a name="method-isUnsignedInt"></a>isUnsignedInt

```php
boolean ValidateCore::isUnsignedInt(integer $value)
```

Check for an integer validity (unsigned)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 673](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L673)


#### Arguments
* $value **integer** - Integer to validate



### <a name="method-isUpc"></a>isUpc

```php
boolean ValidateCore::isUpc(string $upc)
```

Check for barcode validity (UPC)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L557)


#### Arguments
* $upc **string** - Barcode to validate



### <a name="method-isUrl"></a>isUrl

```php
boolean ValidateCore::isUrl(string $url)
```

Check url validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 734](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L734)


#### Arguments
* $url **string** - Url to validate



### <a name="method-isUrlOrEmpty"></a>isUrlOrEmpty

```php
boolean ValidateCore::isUrlOrEmpty(string $url)
```

Check url validity (allowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 756](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L756)


#### Arguments
* $url **string** - Url to validate



### <a name="method-isValidSearch"></a>isValidSearch

```php
boolean ValidateCore::isValidSearch(string $search)
```

Check for search query validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L376)


#### Arguments
* $search **string** - Query to validate



### <a name="method-isValuesList"></a>isValuesList

```php
mixed ValidateCore::isValuesList()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L626)




### <a name="method-isVoucherDescription"></a>isVoucherDescription

```php
mixed ValidateCore::isVoucherDescription($text)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L839)


#### Arguments
* $text **mixed**



### <a name="method-isWeightUnit"></a>isWeightUnit

```php
mixed ValidateCore::isWeightUnit($unit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 824](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L824)


#### Arguments
* $unit **mixed**



### <a name="method-isZipCodeFormat"></a>isZipCodeFormat

```php
boolean ValidateCore::isZipCodeFormat(string $zip_code)
```

Check for zip code format validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Validate.php#L579)


#### Arguments
* $zip_code **string** - zip code format to validate


