Class ValidateCore
=====================





* Class name: ValidateCore
* Source: [classes/Validate.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L27)


Contents
--------



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
* [isOrderWay](#method-isOrderWay)
* [isPasswd](#method-isPasswd)
* [isPasswdAdmin](#method-isPasswdAdmin)
* [isPercentage](#method-isPercentage)
* [isPhoneNumber](#method-isPhoneNumber)
* [isPhpDateFormat](#method-isPhpDateFormat)
* [isPostCode](#method-isPostCode)
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






Methods
-------


### <a name="method-isAbsoluteUrl"></a>isAbsoluteUrl

```php
boolean ValidateCore::isAbsoluteUrl(string $url)
```

Check if URL is absolute



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L747)


#### Arguments
* $url **string** - URL to validate



### <a name="method-isAddress"></a>isAddress

```php
boolean ValidateCore::isAddress(string $address)
```

Check for a postal address validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L348)


#### Arguments
* $address **string** - Address to validate



### <a name="method-isAnything"></a>isAnything

```php
mixed ValidateCore::isAnything()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L34)




### <a name="method-isApe"></a>isApe

```php
boolean ValidateCore::isApe($ape)
```

Validate APE Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L1049)


#### Arguments
* $ape **mixed** - APE Code



### <a name="method-isArrayWithIds"></a>isArrayWithIds

```php
boolean ValidateCore::isArrayWithIds(array $ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 978](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L978)


#### Arguments
* $ids **array**



### <a name="method-isBirthDate"></a>isBirthDate

```php
boolean ValidateCore::isBirthDate(string $date)
```

Check for birthDate validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L486)


#### Arguments
* $date **string** - birthdate to validate



### <a name="method-isBool"></a>isBool

```php
boolean ValidateCore::isBool(boolean $bool)
```

Check for boolean validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 505](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L505)


#### Arguments
* $bool **boolean** - Boolean to validate



### <a name="method-isBoolId"></a>isBoolId

```php
boolean ValidateCore::isBoolId(string $ids)
```

Check for bool_id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 904](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L904)


#### Arguments
* $ids **string**



### <a name="method-isBool_Id"></a>isBool_Id

```php
mixed ValidateCore::isBool_Id($ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 912](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L912)


#### Arguments
* $ids **mixed**



### <a name="method-isCarrierName"></a>isCarrierName

```php
boolean ValidateCore::isCarrierName(string $name)
```

Check for a carrier name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L131)


#### Arguments
* $name **string** - Carrier name to validate



### <a name="method-isCatalogName"></a>isCatalogName

```php
boolean ValidateCore::isCatalogName(string $name)
```

Check for product or category name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L289)


#### Arguments
* $name **string** - Product or category name to validate



### <a name="method-isCityName"></a>isCityName

```php
boolean ValidateCore::isCityName(string $city)
```

Check for city name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L359)


#### Arguments
* $city **string** - City name to validate



### <a name="method-isCleanHtml"></a>isCleanHtml

```php
boolean ValidateCore::isCleanHtml(string $html)
```

Check for HTML field validity (no XSS please !)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L392)


#### Arguments
* $html **string** - HTML field to validate



### <a name="method-isColor"></a>isColor

```php
boolean ValidateCore::isColor($color)
```

Check object validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L703)


#### Arguments
* $color **mixed**



### <a name="method-isConfigName"></a>isConfigName

```php
boolean ValidateCore::isConfigName(string $config_name)
```

Check for configuration key validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L438)


#### Arguments
* $config_name **string** - Configuration key to validate



### <a name="method-isControllerName"></a>isControllerName

```php
mixed ValidateCore::isControllerName($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1054](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L1054)


#### Arguments
* $name **mixed**



### <a name="method-isCookie"></a>isCookie

```php
boolean ValidateCore::isCookie(mixed $data)
```

Check if $data is a PrestaShop cookie object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 871](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L871)


#### Arguments
* $data **mixed** - to validate



### <a name="method-isCoordinate"></a>isCoordinate

```php
boolean ValidateCore::isCoordinate(string $data)
```

Check for Latitude/Longitude



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L946)


#### Arguments
* $data **string** - Coordinate to validate



### <a name="method-isCountryName"></a>isCountryName

```php
boolean ValidateCore::isCountryName(string $name)
```

Check for a country name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L311)


#### Arguments
* $name **string** - Country name to validate



### <a name="method-isDate"></a>isDate

```php
boolean ValidateCore::isDate(string $date)
```

Check for date validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L473)


#### Arguments
* $date **string** - Date to validate



### <a name="method-isDateFormat"></a>isDateFormat

```php
boolean ValidateCore::isDateFormat(string $date)
```

Check for date format



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L462)


#### Arguments
* $date **string** - Date to validate



### <a name="method-isDirName"></a>isDirName

```php
boolean ValidateCore::isDirName(string $dir)
```

Check for standard name directory validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L787)


#### Arguments
* $dir **string** - Directory to validate



### <a name="method-isDiscountName"></a>isDiscountName

```php
boolean ValidateCore::isDiscountName(string $voucher)
```

Check for voucher name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L278)


#### Arguments
* $voucher **string** - voucher to validate



### <a name="method-isDistanceUnit"></a>isDistanceUnit

```php
mixed ValidateCore::isDistanceUnit($unit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L808)


#### Arguments
* $unit **mixed**



### <a name="method-isDniLite"></a>isDniLite

```php
boolean ValidateCore::isDniLite(string $dni)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 860](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L860)


#### Arguments
* $dni **string** - to validate



### <a name="method-isEan13"></a>isEan13

```php
boolean ValidateCore::isEan13(string $ean13)
```

Check for barcode validity (EAN-13)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L527)


#### Arguments
* $ean13 **string** - Barcode to validate



### <a name="method-isEmail"></a>isEmail

```php
boolean ValidateCore::isEmail(string $email)
```

Check for e-mail validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L45)


#### Arguments
* $email **string** - e-mail address to validate



### <a name="method-isFileName"></a>isFileName

```php
boolean ValidateCore::isFileName(string $name)
```

Check for standard name file validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L776)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isFloat"></a>isFloat

```php
boolean ValidateCore::isFloat(float $float)
```

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L104)


#### Arguments
* $float **float** - Float number to validate



### <a name="method-isGenericName"></a>isGenericName

```php
boolean ValidateCore::isGenericName(string $name)
```

Check for standard name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L381)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isHookName"></a>isHookName

```php
boolean ValidateCore::isHookName(string $hook)
```

Check for hook name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L164)


#### Arguments
* $hook **string** - Hook name to validate



### <a name="method-isImageSize"></a>isImageSize

```php
boolean ValidateCore::isImageSize(string $size)
```

Check for an image size validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L142)


#### Arguments
* $size **string** - Image size to validate



### <a name="method-isImageTypeName"></a>isImageTypeName

```php
boolean ValidateCore::isImageTypeName(string $type)
```

Check for image type name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L219)


#### Arguments
* $type **string** - Image type name to validate



### <a name="method-isInt"></a>isInt

```php
boolean ValidateCore::isInt(integer $value)
```

Check for an integer validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L642)


#### Arguments
* $value **integer** - Integer to validate



### <a name="method-isIp2Long"></a>isIp2Long

```php
mixed ValidateCore::isIp2Long($ip)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L29)


#### Arguments
* $ip **mixed**



### <a name="method-isLabel"></a>isLabel

```php
boolean ValidateCore::isLabel(string $label)
```

Customization fields' label validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 840](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L840)


#### Arguments
* $label **string**



### <a name="method-isLangIsoCode"></a>isLangIsoCode

```php
boolean ValidateCore::isLangIsoCode(string $iso_code)
```

Check for Language Iso Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L957)


#### Arguments
* $iso_code **string**



### <a name="method-isLanguageCode"></a>isLanguageCode

```php
mixed ValidateCore::isLanguageCode($s)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L257)


#### Arguments
* $s **mixed**



### <a name="method-isLanguageFileName"></a>isLanguageFileName

```php
boolean ValidateCore::isLanguageFileName(string $file_name)
```

Check for Language File Name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 968](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L968)


#### Arguments
* $file_name **string**



### <a name="method-isLanguageIsoCode"></a>isLanguageIsoCode

```php
boolean ValidateCore::isLanguageIsoCode(string $iso_code)
```

Check for language code (ISO) validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L252)


#### Arguments
* $iso_code **string** - Language code (ISO) to validate



### <a name="method-isLinkRewrite"></a>isLinkRewrite

```php
boolean ValidateCore::isLinkRewrite(string $link)
```

Check for a link (url-rewriting only) validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L322)


#### Arguments
* $link **string** - Link to validate



### <a name="method-isLoadedObject"></a>isLoadedObject

```php
boolean ValidateCore::isLoadedObject(object $object)
```

Check object validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 692](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L692)


#### Arguments
* $object **object** - Object to validate



### <a name="method-isLocalizationPackSelection"></a>isLocalizationPackSelection

```php
boolean ValidateCore::isLocalizationPackSelection(string $data)
```

Check the localization pack part selected



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 924](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L924)


#### Arguments
* $data **string** - Localization pack to check



### <a name="method-isMailName"></a>isMailName

```php
boolean ValidateCore::isMailName(string $mail_name)
```

Check for sender name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L175)


#### Arguments
* $mail_name **string** - Sender name to validate



### <a name="method-isMailSubject"></a>isMailSubject

```php
boolean ValidateCore::isMailSubject(string $mail_subject)
```

Check for e-mail subject validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L186)


#### Arguments
* $mail_subject **string** - e-mail subject to validate



### <a name="method-isMd5"></a>isMd5

```php
boolean ValidateCore::isMd5(string $md5)
```

Check for MD5 string validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L82)


#### Arguments
* $md5 **string** - MD5 string to validate



### <a name="method-isMessage"></a>isMessage

```php
boolean ValidateCore::isMessage(string $message)
```

Check for a message validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L300)


#### Arguments
* $message **string** - Message to validate



### <a name="method-isModuleName"></a>isModuleName

```php
boolean ValidateCore::isModuleName(string $module_name)
```

Check for module name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L197)


#### Arguments
* $module_name **string** - Module name to validate



### <a name="method-isModuleUrl"></a>isModuleUrl

```php
boolean ValidateCore::isModuleUrl(string $url, array $errors)
```

Check for module URL validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L57)


#### Arguments
* $url **string** - module URL to validate
* $errors **array** - Reference array for catching errors



### <a name="method-isMySQLEngine"></a>isMySQLEngine

```php
mixed ValidateCore::isMySQLEngine($engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 754](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L754)


#### Arguments
* $engine **mixed**



### <a name="method-isName"></a>isName

```php
boolean ValidateCore::isName(string $name)
```

Check for name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L153)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isNegativePrice"></a>isNegativePrice

```php
boolean ValidateCore::isNegativePrice(string $price)
```

Check for price validity (including negative price)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L241)


#### Arguments
* $price **string** - Price to validate



### <a name="method-isNullOrUnsignedId"></a>isNullOrUnsignedId

```php
mixed ValidateCore::isNullOrUnsignedId($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L681)


#### Arguments
* $id **mixed**



### <a name="method-isNumericIsoCode"></a>isNumericIsoCode

```php
mixed ValidateCore::isNumericIsoCode($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L267)


#### Arguments
* $iso_code **mixed**



### <a name="method-isOptFloat"></a>isOptFloat

```php
boolean ValidateCore::isOptFloat(float $float)
```

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L120)


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
* Source: [classes/Validate.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L586)


#### Arguments
* $order **string** - Field to validate



### <a name="method-isOrderWay"></a>isOrderWay

```php
boolean ValidateCore::isOrderWay(string $way)
```

Check for table or identifier validity
Mostly used in database for ordering : ASC / DESC



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L574)


#### Arguments
* $way **string** - Keyword to validate



### <a name="method-isPasswd"></a>isPasswd

```php
boolean ValidateCore::isPasswd(string $passwd, integer $size)
```

Check for password validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L422)


#### Arguments
* $passwd **string** - Password to validate
* $size **integer**



### <a name="method-isPasswdAdmin"></a>isPasswdAdmin

```php
mixed ValidateCore::isPasswdAdmin($passwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L427)


#### Arguments
* $passwd **mixed**



### <a name="method-isPercentage"></a>isPercentage

```php
boolean ValidateCore::isPercentage(float $value)
```

Check for an percentage validity (between 0 and 100)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 664](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L664)


#### Arguments
* $value **float** - Float to validate



### <a name="method-isPhoneNumber"></a>isPhoneNumber

```php
boolean ValidateCore::isPhoneNumber(string $number)
```

Check for phone number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L516)


#### Arguments
* $number **string** - Phone number to validate



### <a name="method-isPhpDateFormat"></a>isPhpDateFormat

```php
boolean ValidateCore::isPhpDateFormat(string $date_format)
```

Check date formats like http://php.net/manual/en/function.date.php



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L449)


#### Arguments
* $date_format **string** - date format to check



### <a name="method-isPostCode"></a>isPostCode

```php
boolean ValidateCore::isPostCode(string $postcode)
```

Check for postal code validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L549)


#### Arguments
* $postcode **string** - Postal code to validate



### <a name="method-isPrice"></a>isPrice

```php
boolean ValidateCore::isPrice(string $price)
```

Check for price validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L230)


#### Arguments
* $price **string** - Price to validate



### <a name="method-isPriceDisplayMethod"></a>isPriceDisplayMethod

```php
boolean ValidateCore::isPriceDisplayMethod(integer $data)
```

Price display method validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L851)


#### Arguments
* $data **integer** - Data to validate



### <a name="method-isProductVisibility"></a>isProductVisibility

```php
boolean ValidateCore::isProductVisibility(string $s)
```

Check for product visibility



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L631)


#### Arguments
* $s **string** - visibility to check



### <a name="method-isReductionType"></a>isReductionType

```php
boolean ValidateCore::isReductionType(string $data)
```

Check if the data is a reduction type (amout or percentage)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 893](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L893)


#### Arguments
* $data **string** - Data to validate



### <a name="method-isReference"></a>isReference

```php
boolean ValidateCore::isReference(string $reference)
```

Check for product reference validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L410)


#### Arguments
* $reference **string** - Product reference to validate



### <a name="method-isRoutePattern"></a>isRoutePattern

```php
boolean ValidateCore::isRoutePattern(string $pattern)
```

Check for a route pattern validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L335)


#### Arguments
* $pattern **string** - to validate



### <a name="method-isSceneZones"></a>isSceneZones

```php
boolean ValidateCore::isSceneZones(array $zones)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 992](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L992)


#### Arguments
* $zones **array**



### <a name="method-isSerializedArray"></a>isSerializedArray

```php
boolean ValidateCore::isSerializedArray(string $data)
```

Check for PHP serialized data



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 935](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L935)


#### Arguments
* $data **string** - Serialized data to validate



### <a name="method-isSha1"></a>isSha1

```php
boolean ValidateCore::isSha1(string $sha1)
```

Check for SHA1 string validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L93)


#### Arguments
* $sha1 **string** - SHA1 string to validate



### <a name="method-isSiret"></a>isSiret

```php
boolean ValidateCore::isSiret($siret)
```

Validate SIRET Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1028](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L1028)


#### Arguments
* $siret **mixed** - SIRET Code



### <a name="method-isSortDirection"></a>isSortDirection

```php
boolean ValidateCore::isSortDirection(\char $value)
```

Check if the value is a sort direction value (DESC/ASC)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L829)


#### Arguments
* $value **char**



### <a name="method-isStateIsoCode"></a>isStateIsoCode

```php
mixed ValidateCore::isStateIsoCode($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L262)


#### Arguments
* $iso_code **mixed**



### <a name="method-isStockManagement"></a>isStockManagement

```php
boolean ValidateCore::isStockManagement(array $stock_management)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 1015](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L1015)


#### Arguments
* $stock_management **array**



### <a name="method-isString"></a>isString

```php
boolean ValidateCore::isString(string $data)
```

Price display method validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L882)


#### Arguments
* $data **string** - Data to validate



### <a name="method-isSubDomainName"></a>isSubDomainName

```php
mixed ValidateCore::isSubDomainName($domain)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 813](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L813)


#### Arguments
* $domain **mixed**



### <a name="method-isTabName"></a>isTabName

```php
boolean ValidateCore::isTabName(string $name)
```

Check for admin panel tab name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 798](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L798)


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
* Source: [classes/Validate.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L598)


#### Arguments
* $table **string** - Table/identifier to validate



### <a name="method-isTablePrefix"></a>isTablePrefix

```php
mixed ValidateCore::isTablePrefix($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 764](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L764)


#### Arguments
* $data **mixed**



### <a name="method-isTagsList"></a>isTagsList

```php
boolean ValidateCore::isTagsList(string $list)
```

Check for tags list validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 620](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L620)


#### Arguments
* $list **string** - List to validate



### <a name="method-isTplName"></a>isTplName

```php
boolean ValidateCore::isTplName(string $tpl_name)
```

Check for template name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L208)


#### Arguments
* $tpl_name **string** - Template name to validate



### <a name="method-isTrackingNumber"></a>isTrackingNumber

```php
boolean ValidateCore::isTrackingNumber(string $tracking_number)
```

Check tracking number validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 725](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L725)


#### Arguments
* $tracking_number **string** - Tracking number to validate



### <a name="method-isUnixName"></a>isUnixName

```php
mixed ValidateCore::isUnixName($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L759)


#### Arguments
* $data **mixed**



### <a name="method-isUnsignedFloat"></a>isUnsignedFloat

```php
mixed ValidateCore::isUnsignedFloat($float)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L109)


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
* Source: [classes/Validate.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L676)


#### Arguments
* $id **integer** - Integer to validate



### <a name="method-isUnsignedInt"></a>isUnsignedInt

```php
boolean ValidateCore::isUnsignedInt(integer $value)
```

Check for an integer validity (unsigned)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 653](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L653)


#### Arguments
* $value **integer** - Integer to validate



### <a name="method-isUpc"></a>isUpc

```php
boolean ValidateCore::isUpc(string $upc)
```

Check for barcode validity (UPC)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L538)


#### Arguments
* $upc **string** - Barcode to validate



### <a name="method-isUrl"></a>isUrl

```php
boolean ValidateCore::isUrl(string $url)
```

Check url validity (disallowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L714)


#### Arguments
* $url **string** - Url to validate



### <a name="method-isUrlOrEmpty"></a>isUrlOrEmpty

```php
boolean ValidateCore::isUrlOrEmpty(string $url)
```

Check url validity (allowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 736](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L736)


#### Arguments
* $url **string** - Url to validate



### <a name="method-isValidSearch"></a>isValidSearch

```php
boolean ValidateCore::isValidSearch(string $search)
```

Check for search query validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L370)


#### Arguments
* $search **string** - Query to validate



### <a name="method-isValuesList"></a>isValuesList

```php
mixed ValidateCore::isValuesList()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L606)




### <a name="method-isVoucherDescription"></a>isVoucherDescription

```php
mixed ValidateCore::isVoucherDescription($text)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 818](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L818)


#### Arguments
* $text **mixed**



### <a name="method-isWeightUnit"></a>isWeightUnit

```php
mixed ValidateCore::isWeightUnit($unit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 803](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L803)


#### Arguments
* $unit **mixed**



### <a name="method-isZipCodeFormat"></a>isZipCodeFormat

```php
boolean ValidateCore::isZipCodeFormat(string $zip_code)
```

Check for zip code format validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Validate.php#L560)


#### Arguments
* $zip_code **string** - zip code format to validate


