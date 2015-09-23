Class ValidateCore
=====================





* Class name: ValidateCore
* Source: [classes/Validate.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L28)


Contents
--------



### Methods

* [IsSortDirection](#method-IsSortDirection)
* [isAbsoluteUrl](#method-isAbsoluteUrl)
* [isAddress](#method-isAddress)
* [isAnything](#method-isAnything)
* [isApe](#method-isApe)
* [isArrayWithIds](#method-isArrayWithIds)
* [isBirthDate](#method-isBirthDate)
* [isBool](#method-isBool)
* [isBool_Id](#method-isBool_Id)
* [isCarrierName](#method-isCarrierName)
* [isCatalogName](#method-isCatalogName)
* [isCityName](#method-isCityName)
* [isCleanHtml](#method-isCleanHtml)
* [isColor](#method-isColor)
* [isConfigName](#method-isConfigName)
* [isCookie](#method-isCookie)
* [isCoordinate](#method-isCoordinate)
* [isCountryName](#method-isCountryName)
* [isDate](#method-isDate)
* [isDateFormat](#method-isDateFormat)
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
* [isNullOrUnsignedId](#method-isNullOrUnsignedId)
* [isNumericIsoCode](#method-isNumericIsoCode)
* [isOptFloat](#method-isOptFloat)
* [isOrderBy](#method-isOrderBy)
* [isOrderWay](#method-isOrderWay)
* [isPasswd](#method-isPasswd)
* [isPasswdAdmin](#method-isPasswdAdmin)
* [isPhoneNumber](#method-isPhoneNumber)
* [isPhpDateFormat](#method-isPhpDateFormat)
* [isPostCode](#method-isPostCode)
* [isPrice](#method-isPrice)
* [isPriceDisplayMethod](#method-isPriceDisplayMethod)
* [isReductionType](#method-isReductionType)
* [isReference](#method-isReference)
* [isSceneZones](#method-isSceneZones)
* [isSerializedArray](#method-isSerializedArray)
* [isSha1](#method-isSha1)
* [isSiret](#method-isSiret)
* [isStateIsoCode](#method-isStateIsoCode)
* [isStockManagement](#method-isStockManagement)
* [isString](#method-isString)
* [isSubDomainName](#method-isSubDomainName)
* [isTabName](#method-isTabName)
* [isTableOrIdentifier](#method-isTableOrIdentifier)
* [isTablePrefix](#method-isTablePrefix)
* [isTagsList](#method-isTagsList)
* [isTplName](#method-isTplName)
* [isUnixName](#method-isUnixName)
* [isUnsignedFloat](#method-isUnsignedFloat)
* [isUnsignedId](#method-isUnsignedId)
* [isUnsignedInt](#method-isUnsignedInt)
* [isUpc](#method-isUpc)
* [isUrl](#method-isUrl)
* [isUrlOrEmpty](#method-isUrlOrEmpty)
* [isValidSearch](#method-isValidSearch)
* [isValidThemeDir](#method-isValidThemeDir)
* [isValuesList](#method-isValuesList)
* [isVoucherDescription](#method-isVoucherDescription)
* [isWeightUnit](#method-isWeightUnit)
* [isZipCodeFormat](#method-isZipCodeFormat)






Methods
-------


### <a name="method-IsSortDirection"></a>IsSortDirection

```php
boolean ValidateCore::IsSortDirection(\char $value)
```

Check if the value is a sort direction value (DESC/ASC)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 754](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L754)


#### Arguments
* $value **char**



### <a name="method-isAbsoluteUrl"></a>isAbsoluteUrl

```php
boolean ValidateCore::isAbsoluteUrl($url)
```

Check object validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L683)


#### Arguments
* $url **mixed**



### <a name="method-isAddress"></a>isAddress

```php
boolean ValidateCore::isAddress(string $address)
```

Check for a postal address validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L323)


#### Arguments
* $address **string** - Address to validate



### <a name="method-isAnything"></a>isAnything

```php
mixed ValidateCore::isAnything($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L35)


#### Arguments
* $data **mixed**



### <a name="method-isApe"></a>isApe

```php
boolean ValidateCore::isApe($ape)
```

Validate APE Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L964)


#### Arguments
* $ape **mixed** - APE Code



### <a name="method-isArrayWithIds"></a>isArrayWithIds

```php
boolean ValidateCore::isArrayWithIds(array $ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 894](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L894)


#### Arguments
* $ids **array**



### <a name="method-isBirthDate"></a>isBirthDate

```php
boolean ValidateCore::isBirthDate(string $date)
```

Check for birthDate validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L453)


#### Arguments
* $date **string** - birthdate to validate



### <a name="method-isBool"></a>isBool

```php
boolean ValidateCore::isBool(boolean $bool)
```

Check for boolean validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 471](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L471)


#### Arguments
* $bool **boolean** - Boolean to validate



### <a name="method-isBool_Id"></a>isBool_Id

```php
boolean ValidateCore::isBool_Id(string $ids)
```

Check for bool_id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L829)


#### Arguments
* $ids **string**



### <a name="method-isCarrierName"></a>isCarrierName

```php
boolean ValidateCore::isCarrierName(string $name)
```

Check for a carrier name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L132)


#### Arguments
* $name **string** - Carrier name to validate



### <a name="method-isCatalogName"></a>isCatalogName

```php
boolean ValidateCore::isCatalogName(string $name)
```

Check for product or category name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L279)


#### Arguments
* $name **string** - Product or category name to validate



### <a name="method-isCityName"></a>isCityName

```php
boolean ValidateCore::isCityName(string $city)
```

Check for city name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L334)


#### Arguments
* $city **string** - City name to validate



### <a name="method-isCleanHtml"></a>isCleanHtml

```php
boolean ValidateCore::isCleanHtml(string $html)
```

Check for HTML field validity (no XSS please !)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L367)


#### Arguments
* $html **string** - HTML field to validate



### <a name="method-isColor"></a>isColor

```php
boolean ValidateCore::isColor($color)
```

Check object validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 650](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L650)


#### Arguments
* $color **mixed**



### <a name="method-isConfigName"></a>isConfigName

```php
boolean ValidateCore::isConfigName(string $configName)
```

Check for configuration key validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L406)


#### Arguments
* $configName **string** - Configuration key to validate



### <a name="method-isCookie"></a>isCookie

```php
boolean ValidateCore::isCookie(mixed $data)
```

Check if $data is a PrestaShop cookie object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L796)


#### Arguments
* $data **mixed** - to validate



### <a name="method-isCoordinate"></a>isCoordinate

```php
boolean ValidateCore::isCoordinate(string $data)
```

Check for Latitude/Longitude



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 862](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L862)


#### Arguments
* $data **string** - Coordinate to validate



### <a name="method-isCountryName"></a>isCountryName

```php
boolean ValidateCore::isCountryName(string $name)
```

Check for a country name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L301)


#### Arguments
* $name **string** - Country name to validate



### <a name="method-isDate"></a>isDate

```php
boolean ValidateCore::isDate(string $date)
```

Check for date validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L440)


#### Arguments
* $date **string** - Date to validate



### <a name="method-isDateFormat"></a>isDateFormat

```php
boolean ValidateCore::isDateFormat(string $date)
```

Check for date format



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L429)


#### Arguments
* $date **string** - Date to validate



### <a name="method-isDiscountName"></a>isDiscountName

```php
boolean ValidateCore::isDiscountName(string $voucher)
```

Check for voucher name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L268)


#### Arguments
* $voucher **string** - voucher to validate



### <a name="method-isDistanceUnit"></a>isDistanceUnit

```php
mixed ValidateCore::isDistanceUnit($unit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L733)


#### Arguments
* $unit **mixed**



### <a name="method-isDniLite"></a>isDniLite

```php
boolean ValidateCore::isDniLite(string $dni)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L785)


#### Arguments
* $dni **string** - to validate



### <a name="method-isEan13"></a>isEan13

```php
boolean ValidateCore::isEan13(string $ean13)
```

Check for barcode validity (EAN-13)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L493)


#### Arguments
* $ean13 **string** - Barcode to validate



### <a name="method-isEmail"></a>isEmail

```php
boolean ValidateCore::isEmail(string $email, $required)
```

Check for e-mail validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L46)


#### Arguments
* $email **string** - e-mail address to validate
* $required **mixed**



### <a name="method-isFileName"></a>isFileName

```php
boolean ValidateCore::isFileName(string $name)
```

Check for standard name file validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L712)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isFloat"></a>isFloat

```php
boolean ValidateCore::isFloat(float $float)
```

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L105)


#### Arguments
* $float **float** - Float number to validate



### <a name="method-isGenericName"></a>isGenericName

```php
boolean ValidateCore::isGenericName(string $name)
```

Check for standard name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 356](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L356)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isHookName"></a>isHookName

```php
boolean ValidateCore::isHookName(string $hook)
```

Check for hook name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L165)


#### Arguments
* $hook **string** - Hook name to validate



### <a name="method-isImageSize"></a>isImageSize

```php
boolean ValidateCore::isImageSize(string $size)
```

Check for an image size validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L143)


#### Arguments
* $size **string** - Image size to validate



### <a name="method-isImageTypeName"></a>isImageTypeName

```php
boolean ValidateCore::isImageTypeName(string $type)
```

Check for image type name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L220)


#### Arguments
* $type **string** - Image type name to validate



### <a name="method-isInt"></a>isInt

```php
boolean ValidateCore::isInt($value)
```

Check for an integer validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 600](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L600)


#### Arguments
* $value **mixed**



### <a name="method-isIp2Long"></a>isIp2Long

```php
mixed ValidateCore::isIp2Long($ip)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L30)


#### Arguments
* $ip **mixed**



### <a name="method-isLabel"></a>isLabel

```php
boolean ValidateCore::isLabel($label)
```

Customization fields' label validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 765](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L765)


#### Arguments
* $label **mixed**



### <a name="method-isLangIsoCode"></a>isLangIsoCode

```php
boolean ValidateCore::isLangIsoCode(string $iso_code)
```

Check for Language Iso Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L873)


#### Arguments
* $iso_code **string**



### <a name="method-isLanguageCode"></a>isLanguageCode

```php
mixed ValidateCore::isLanguageCode($s)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L247)


#### Arguments
* $s **mixed**



### <a name="method-isLanguageFileName"></a>isLanguageFileName

```php
boolean ValidateCore::isLanguageFileName(string $file_name)
```

Check for Language File Name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 884](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L884)


#### Arguments
* $file_name **string**



### <a name="method-isLanguageIsoCode"></a>isLanguageIsoCode

```php
boolean ValidateCore::isLanguageIsoCode(string $isoCode)
```

Check for language code (ISO) validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L242)


#### Arguments
* $isoCode **string** - Language code (ISO) to validate



### <a name="method-isLinkRewrite"></a>isLinkRewrite

```php
boolean ValidateCore::isLinkRewrite(string $link)
```

Check for a link (url-rewriting only) validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L312)


#### Arguments
* $link **string** - Link to validate



### <a name="method-isLoadedObject"></a>isLoadedObject

```php
boolean ValidateCore::isLoadedObject(integer $object)
```

Check object validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L639)


#### Arguments
* $object **integer** - Object to validate



### <a name="method-isLocalizationPackSelection"></a>isLocalizationPackSelection

```php
boolean ValidateCore::isLocalizationPackSelection(string $data)
```

Check the localization pack part selected



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 840](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L840)


#### Arguments
* $data **string** - Localization pack to check



### <a name="method-isMailName"></a>isMailName

```php
boolean ValidateCore::isMailName(string $mailName)
```

Check for sender name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L176)


#### Arguments
* $mailName **string** - Sender name to validate



### <a name="method-isMailSubject"></a>isMailSubject

```php
boolean ValidateCore::isMailSubject(string $mailSubject)
```

Check for e-mail subject validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L187)


#### Arguments
* $mailSubject **string** - e-mail subject to validate



### <a name="method-isMd5"></a>isMd5

```php
boolean ValidateCore::isMd5(string $md5)
```

Check for MD5 string validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L83)


#### Arguments
* $md5 **string** - MD5 string to validate



### <a name="method-isMessage"></a>isMessage

```php
boolean ValidateCore::isMessage(string $message)
```

Check for a message validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L290)


#### Arguments
* $message **string** - Message to validate



### <a name="method-isModuleName"></a>isModuleName

```php
boolean ValidateCore::isModuleName(string $moduleName)
```

Check for module name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L198)


#### Arguments
* $moduleName **string** - Module name to validate



### <a name="method-isModuleUrl"></a>isModuleUrl

```php
boolean ValidateCore::isModuleUrl(string $url, array $errors)
```

Check for module URL validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L58)


#### Arguments
* $url **string** - module URL to validate
* $errors **array** - Reference array for catching errors



### <a name="method-isMySQLEngine"></a>isMySQLEngine

```php
mixed ValidateCore::isMySQLEngine($engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L690)


#### Arguments
* $engine **mixed**



### <a name="method-isName"></a>isName

```php
boolean ValidateCore::isName(string $name)
```

Check for name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L154)


#### Arguments
* $name **string** - Name to validate



### <a name="method-isNullOrUnsignedId"></a>isNullOrUnsignedId

```php
mixed ValidateCore::isNullOrUnsignedId($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 628](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L628)


#### Arguments
* $id **mixed**



### <a name="method-isNumericIsoCode"></a>isNumericIsoCode

```php
mixed ValidateCore::isNumericIsoCode($isoCode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L257)


#### Arguments
* $isoCode **mixed**



### <a name="method-isOptFloat"></a>isOptFloat

```php
boolean ValidateCore::isOptFloat(float $float)
```

Check for a float number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L121)


#### Arguments
* $float **float** - Float number to validate



### <a name="method-isOrderBy"></a>isOrderBy

```php
boolean ValidateCore::isOrderBy(string $orderBy)
```

Check for table or identifier validity
Mostly used in database for ordering : ORDER BY field



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L552)


#### Arguments
* $orderBy **string** - Field to validate



### <a name="method-isOrderWay"></a>isOrderWay

```php
boolean ValidateCore::isOrderWay(string $orderWay)
```

Check for table or identifier validity
Mostly used in database for ordering : ASC / DESC



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L540)


#### Arguments
* $orderWay **string** - Keyword to validate



### <a name="method-isPasswd"></a>isPasswd

```php
boolean ValidateCore::isPasswd(string $passwd, $size)
```

Check for password validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L390)


#### Arguments
* $passwd **string** - Password to validate
* $size **mixed**



### <a name="method-isPasswdAdmin"></a>isPasswdAdmin

```php
mixed ValidateCore::isPasswdAdmin($passwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L395)


#### Arguments
* $passwd **mixed**



### <a name="method-isPhoneNumber"></a>isPhoneNumber

```php
boolean ValidateCore::isPhoneNumber(string $phoneNumber)
```

Check for phone number validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 482](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L482)


#### Arguments
* $phoneNumber **string** - Phone number to validate



### <a name="method-isPhpDateFormat"></a>isPhpDateFormat

```php
boolean ValidateCore::isPhpDateFormat(string $date_format)
```

Check date formats like http://php.net/manual/en/function.date.php



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L417)


#### Arguments
* $date_format **string** - date format to check



### <a name="method-isPostCode"></a>isPostCode

```php
boolean ValidateCore::isPostCode(string $postcode)
```

Check for postal code validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 515](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L515)


#### Arguments
* $postcode **string** - Postal code to validate



### <a name="method-isPrice"></a>isPrice

```php
boolean ValidateCore::isPrice(string $price)
```

Check for price validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L231)


#### Arguments
* $price **string** - Price to validate



### <a name="method-isPriceDisplayMethod"></a>isPriceDisplayMethod

```php
boolean ValidateCore::isPriceDisplayMethod(integer $data)
```

Price display method validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L776)


#### Arguments
* $data **integer** - Data to validate



### <a name="method-isReductionType"></a>isReductionType

```php
boolean ValidateCore::isReductionType(string $data)
```

Check if the data is a reduction type (amout or percentage)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 818](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L818)


#### Arguments
* $data **string** - Data to validate



### <a name="method-isReference"></a>isReference

```php
boolean ValidateCore::isReference(string $reference)
```

Check for product reference validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L379)


#### Arguments
* $reference **string** - Product reference to validate



### <a name="method-isSceneZones"></a>isSceneZones

```php
boolean ValidateCore::isSceneZones(array $zones)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L908)


#### Arguments
* $zones **array**



### <a name="method-isSerializedArray"></a>isSerializedArray

```php
boolean ValidateCore::isSerializedArray(string $data)
```

Check for PHP serialized data



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L851)


#### Arguments
* $data **string** - Serialized data to validate



### <a name="method-isSha1"></a>isSha1

```php
boolean ValidateCore::isSha1(string $sha1)
```

Check for SHA1 string validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L94)


#### Arguments
* $sha1 **string** - SHA1 string to validate



### <a name="method-isSiret"></a>isSiret

```php
boolean ValidateCore::isSiret($siret)
```

Validate SIRET Code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 944](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L944)


#### Arguments
* $siret **mixed** - SIRET Code



### <a name="method-isStateIsoCode"></a>isStateIsoCode

```php
mixed ValidateCore::isStateIsoCode($isoCode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L252)


#### Arguments
* $isoCode **mixed**



### <a name="method-isStockManagement"></a>isStockManagement

```php
boolean ValidateCore::isStockManagement(array $stock_management)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 931](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L931)


#### Arguments
* $stock_management **array**



### <a name="method-isString"></a>isString

```php
boolean ValidateCore::isString(string $data)
```

Price display method validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L807)


#### Arguments
* $data **string** - Data to validate



### <a name="method-isSubDomainName"></a>isSubDomainName

```php
mixed ValidateCore::isSubDomainName($subDomainName)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L738)


#### Arguments
* $subDomainName **mixed**



### <a name="method-isTabName"></a>isTabName

```php
boolean ValidateCore::isTabName(string $name)
```

Check for admin panel tab name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L723)


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
* Source: [classes/Validate.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L564)


#### Arguments
* $table **string** - Table/identifier to validate



### <a name="method-isTablePrefix"></a>isTablePrefix

```php
mixed ValidateCore::isTablePrefix($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 700](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L700)


#### Arguments
* $data **mixed**



### <a name="method-isTagsList"></a>isTagsList

```php
boolean ValidateCore::isTagsList(string $list)
```

Check for tags list validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L589)


#### Arguments
* $list **string** - List to validate



### <a name="method-isTplName"></a>isTplName

```php
boolean ValidateCore::isTplName(string $tplName)
```

Check for template name validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L209)


#### Arguments
* $tplName **string** - Template name to validate



### <a name="method-isUnixName"></a>isUnixName

```php
mixed ValidateCore::isUnixName($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L695)


#### Arguments
* $data **mixed**



### <a name="method-isUnsignedFloat"></a>isUnsignedFloat

```php
mixed ValidateCore::isUnsignedFloat($float)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L110)


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
* Source: [classes/Validate.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L623)


#### Arguments
* $id **integer** - Integer to validate



### <a name="method-isUnsignedInt"></a>isUnsignedInt

```php
boolean ValidateCore::isUnsignedInt($value)
```

Check for an integer validity (unsigned)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L611)


#### Arguments
* $value **mixed**



### <a name="method-isUpc"></a>isUpc

```php
boolean ValidateCore::isUpc(string $upc)
```

Check for barcode validity (UPC)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L504)


#### Arguments
* $upc **string** - Barcode to validate



### <a name="method-isUrl"></a>isUrl

```php
boolean ValidateCore::isUrl(string $url)
```

Check url valdity (disallowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L661)


#### Arguments
* $url **string** - Url to validate



### <a name="method-isUrlOrEmpty"></a>isUrlOrEmpty

```php
boolean ValidateCore::isUrlOrEmpty(string $url)
```

Check url validity (allowed empty string)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L672)


#### Arguments
* $url **string** - Url to validate



### <a name="method-isValidSearch"></a>isValidSearch

```php
boolean ValidateCore::isValidSearch(string $search)
```

Check for search query validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L345)


#### Arguments
* $search **string** - Query to validate



### <a name="method-isValidThemeDir"></a>isValidThemeDir

```php
boolean ValidateCore::isValidThemeDir(string $dir)
```

Validate theme directory
We currently check if the item is a valid theme directory



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 976](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L976)


#### Arguments
* $dir **string**



### <a name="method-isValuesList"></a>isValuesList

```php
boolean ValidateCore::isValuesList(string $list)
```

Check for values list validity
Mostly used in database for insertions (A,B,C),(A,B,C).

..

* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L576)


#### Arguments
* $list **string** - List to validate



### <a name="method-isVoucherDescription"></a>isVoucherDescription

```php
mixed ValidateCore::isVoucherDescription($text)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L743)


#### Arguments
* $text **mixed**



### <a name="method-isWeightUnit"></a>isWeightUnit

```php
mixed ValidateCore::isWeightUnit($unit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 728](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L728)


#### Arguments
* $unit **mixed**



### <a name="method-isZipCodeFormat"></a>isZipCodeFormat

```php
boolean ValidateCore::isZipCodeFormat(string $zip_code)
```

Check for zip code format validity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Validate.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Validate.php#L526)


#### Arguments
* $zip_code **string** - zip code format to validate


