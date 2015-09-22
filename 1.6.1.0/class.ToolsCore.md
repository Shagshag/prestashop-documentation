Class ToolsCore
=====================

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.

* Class name: ToolsCore
* Source: [classes/Tools.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L27)


Contents
--------


### Properties

* [$_cache_nb_media_servers](#property-$_cache_nb_media_servers)
* [$_caching](#property-$_caching)
* [$_forceCompile](#property-$_forceCompile)
* [$_user_browser](#property-$_user_browser)
* [$_user_plateform](#property-$_user_plateform)
* [$file_exists_cache](#property-$file_exists_cache)
* [$is_addons_up](#property-$is_addons_up)
* [$round_mode](#property-$round_mode)

### Methods

* [ZipExtract](#method-ZipExtract)
* [ZipTest](#method-ZipTest)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [addonsRequest](#method-addonsRequest)
* [alignVersionNumber](#method-alignVersionNumber)
* [apacheModExists](#method-apacheModExists)
* [argvToGET](#method-argvToGET)
* [arrayReplaceRecursive](#method-arrayReplaceRecursive)
* [arrayUnique](#method-arrayUnique)
* [array_replace](#method-array_replace)
* [boolVal](#method-boolVal)
* [cccCss](#method-cccCss)
* [cccJS](#method-cccJS)
* [ceilf](#method-ceilf)
* [changeFileMTime](#method-changeFileMTime)
* [checkPhpVersion](#method-checkPhpVersion)
* [chmodr](#method-chmodr)
* [cleanNonUnicodeSupport](#method-cleanNonUnicodeSupport)
* [clearCache](#method-clearCache)
* [clearColorListCache](#method-clearColorListCache)
* [clearCompile](#method-clearCompile)
* [clearSmartyCache](#method-clearSmartyCache)
* [clearXMLCache](#method-clearXMLCache)
* [completeMetaTags](#method-completeMetaTags)
* [convertBytes](#method-convertBytes)
* [convertPrice](#method-convertPrice)
* [convertPriceFull](#method-convertPriceFull)
* [copy](#method-copy)
* [d](#method-d)
* [dateDays](#method-dateDays)
* [dateFormat](#method-dateFormat)
* [dateFrom](#method-dateFrom)
* [dateMonths](#method-dateMonths)
* [dateTo](#method-dateTo)
* [dateYears](#method-dateYears)
* [debug_backtrace](#method-debug_backtrace)
* [deleteDirectory](#method-deleteDirectory)
* [deleteFile](#method-deleteFile)
* [dieObject](#method-dieObject)
* [dieOrLog](#method-dieOrLog)
* [display404Error](#method-display404Error)
* [displayAsDeprecated](#method-displayAsDeprecated)
* [displayDate](#method-displayDate)
* [displayError](#method-displayError)
* [displayFileAsDeprecated](#method-displayFileAsDeprecated)
* [displayNumber](#method-displayNumber)
* [displayParameterAsDeprecated](#method-displayParameterAsDeprecated)
* [displayPrice](#method-displayPrice)
* [displayPriceSmarty](#method-displayPriceSmarty)
* [enableCache](#method-enableCache)
* [encrypt](#method-encrypt)
* [encryptIV](#method-encryptIV)
* [error_log](#method-error_log)
* [fd](#method-fd)
* [fileAttachment](#method-fileAttachment)
* [file_exists_cache](#method-file_exists_cache)
* [file_exists_no_cache](#method-file_exists_no_cache)
* [file_get_contents](#method-file_get_contents)
* [floorf](#method-floorf)
* [formatBytes](#method-formatBytes)
* [generateHtaccess](#method-generateHtaccess)
* [generateIndex](#method-generateIndex)
* [getAdminImageUrl](#method-getAdminImageUrl)
* [getAdminToken](#method-getAdminToken)
* [getAdminTokenLite](#method-getAdminTokenLite)
* [getAdminTokenLiteSmarty](#method-getAdminTokenLiteSmarty)
* [getAdminUrl](#method-getAdminUrl)
* [getAllValues](#method-getAllValues)
* [getBrightness](#method-getBrightness)
* [getBytes](#method-getBytes)
* [getCountry](#method-getCountry)
* [getCurrentUrlProtocolPrefix](#method-getCurrentUrlProtocolPrefix)
* [getDefaultIndexContent](#method-getDefaultIndexContent)
* [getDescriptionClean](#method-getDescriptionClean)
* [getFullPath](#method-getFullPath)
* [getHomeMetaTags](#method-getHomeMetaTags)
* [getHttpHost](#method-getHttpHost)
* [getIsset](#method-getIsset)
* [getMaxUploadSize](#method-getMaxUploadSize)
* [getMediaServer](#method-getMediaServer)
* [getMemoryLimit](#method-getMemoryLimit)
* [getMetaTags](#method-getMetaTags)
* [getOctets](#method-getOctets)
* [getPath](#method-getPath)
* [getProductsOrder](#method-getProductsOrder)
* [getProtocol](#method-getProtocol)
* [getRemoteAddr](#method-getRemoteAddr)
* [getSafeModeStatus](#method-getSafeModeStatus)
* [getServerName](#method-getServerName)
* [getShopDomain](#method-getShopDomain)
* [getShopDomainSsl](#method-getShopDomainSsl)
* [getShopProtocol](#method-getShopProtocol)
* [getToken](#method-getToken)
* [getUserBrowser](#method-getUserBrowser)
* [getUserPlatform](#method-getUserPlatform)
* [getValue](#method-getValue)
* [hourGenerate](#method-hourGenerate)
* [htmlentitiesDecodeUTF8](#method-htmlentitiesDecodeUTF8)
* [htmlentitiesUTF8](#method-htmlentitiesUTF8)
* [iconv](#method-iconv)
* [isCallable](#method-isCallable)
* [isEmpty](#method-isEmpty)
* [isPHPCLI](#method-isPHPCLI)
* [isSubmit](#method-isSubmit)
* [isX86_64arch](#method-isX86_64arch)
* [jsonDecode](#method-jsonDecode)
* [jsonEncode](#method-jsonEncode)
* [link_rewrite](#method-link_rewrite)
* [math_round](#method-math_round)
* [minifyCSS](#method-minifyCSS)
* [minifyHTML](#method-minifyHTML)
* [minifyHTMLpregCallback](#method-minifyHTMLpregCallback)
* [modRewriteActive](#method-modRewriteActive)
* [nl2br](#method-nl2br)
* [normalizeDirectory](#method-normalizeDirectory)
* [orderbyPrice](#method-orderbyPrice)
* [p](#method-p)
* [pRegexp](#method-pRegexp)
* [packJS](#method-packJS)
* [packJSinHTML](#method-packJSinHTML)
* [packJSinHTMLpregCallback](#method-packJSinHTMLpregCallback)
* [parserSQL](#method-parserSQL)
* [passwdGen](#method-passwdGen)
* [property_exists](#method-property_exists)
* [ps_round](#method-ps_round)
* [purifyHTML](#method-purifyHTML)
* [recurseCopy](#method-recurseCopy)
* [redirect](#method-redirect)
* [redirectAdmin](#method-redirectAdmin)
* [redirectLink](#method-redirectLink)
* [replaceAccentedChars](#method-replaceAccentedChars)
* [replaceByAbsoluteURL](#method-replaceByAbsoluteURL)
* [restoreCacheSettings](#method-restoreCacheSettings)
* [round_helper](#method-round_helper)
* [rtrimString](#method-rtrimString)
* [safeDefine](#method-safeDefine)
* [safeOutput](#method-safeOutput)
* [safePostVars](#method-safePostVars)
* [scandir](#method-scandir)
* [secureReferrer](#method-secureReferrer)
* [setCookieLanguage](#method-setCookieLanguage)
* [setCurrency](#method-setCurrency)
* [simplexml_load_file](#method-simplexml_load_file)
* [spreadAmount](#method-spreadAmount)
* [str2url](#method-str2url)
* [strReplaceFirst](#method-strReplaceFirst)
* [str_replace_once](#method-str_replace_once)
* [stripslashes](#method-stripslashes)
* [strlen](#method-strlen)
* [strpos](#method-strpos)
* [strrpos](#method-strrpos)
* [strtolower](#method-strtolower)
* [strtoupper](#method-strtoupper)
* [substr](#method-substr)
* [switchLanguage](#method-switchLanguage)
* [throwDeprecated](#method-throwDeprecated)
* [toCamelCase](#method-toCamelCase)
* [toUnderscoreCase](#method-toUnderscoreCase)
* [truncate](#method-truncate)
* [truncateString](#method-truncateString)
* [ucfirst](#method-ucfirst)
* [ucwords](#method-ucwords)
* [unSerialize](#method-unSerialize)
* [url](#method-url)
* [usingSecureMode](#method-usingSecureMode)
* [version_compare](#method-version_compare)
* [waitUntilFileIsModified](#method-waitUntilFileIsModified)




Properties
----------


### <a name="property-$_cache_nb_media_servers"></a>$_cache_nb_media_servers

```php
protected mixed $_cache_nb_media_servers = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 2185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2185).


### <a name="property-$_caching"></a>$_caching

```php
protected mixed $_caching
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L31).


### <a name="property-$_forceCompile"></a>$_forceCompile

```php
protected mixed $_forceCompile
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L30).


### <a name="property-$_user_browser"></a>$_user_browser

```php
protected mixed $_user_browser
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L33).


### <a name="property-$_user_plateform"></a>$_user_plateform

```php
protected mixed $_user_plateform
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L32).


### <a name="property-$file_exists_cache"></a>$file_exists_cache

```php
protected mixed $file_exists_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L29).


### <a name="property-$is_addons_up"></a>$is_addons_up

```php
protected mixed $is_addons_up = true
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 3231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3231).


### <a name="property-$round_mode"></a>$round_mode

```php
public mixed $round_mode = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Tools.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L35).


Methods
-------


### <a name="method-ZipExtract"></a>ZipExtract

```php
boolean ToolsCore::ZipExtract($from_file, $to_dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2740](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2740)


#### Arguments
* $from_file **mixed**
* $to_dir **mixed**



### <a name="method-ZipTest"></a>ZipTest

```php
boolean ToolsCore::ZipTest($from_file)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2714](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2714)


#### Arguments
* $from_file **mixed**



### <a name="method-addCSS"></a>addCSS

```php
mixed ToolsCore::addCSS($css_uri, $css_media_type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2159)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### <a name="method-addJS"></a>addJS

```php
void ToolsCore::addJS(mixed $js_uri)
```

addJS load a javascript file in the header



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2149)


#### Arguments
* $js_uri **mixed**



### <a name="method-addonsRequest"></a>addonsRequest

```php
mixed ToolsCore::addonsRequest($request, $params)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3232)


#### Arguments
* $request **mixed**
* $params **mixed**



### <a name="method-alignVersionNumber"></a>alignVersionNumber

```php
mixed ToolsCore::alignVersionNumber($v1, $v2)
```

Align 2 version with the same number of sub version
version_compare will work better for its comparison :)
(Means: '1.8' to '1.9.3' will change '1.8' to '1.8.0')



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3167)


#### Arguments
* $v1 **mixed**
* $v2 **mixed**



### <a name="method-apacheModExists"></a>apacheModExists

```php
boolean ToolsCore::apacheModExists(string $name)
```

apacheModExists return true if the apache module $name is loaded



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3056](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3056)


#### Arguments
* $name **string** - module name



### <a name="method-argvToGET"></a>argvToGET

```php
mixed ToolsCore::argvToGET($argc, $argv)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3015](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3015)


#### Arguments
* $argc **mixed**
* $argv **mixed**



### <a name="method-arrayReplaceRecursive"></a>arrayReplaceRecursive

```php
mixed ToolsCore::arrayReplaceRecursive(array $base, array $replacements)
```

Replaces elements from passed arrays into the first array recursively



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3601](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3601)


#### Arguments
* $base **array** - The array in which elements are replaced.
* $replacements **array** - The array from which elements will be extracted.



### <a name="method-arrayUnique"></a>arrayUnique

```php
array ToolsCore::arrayUnique(array $array)
```

Reproduce array_unique working before php version 5.2.9



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3211)


#### Arguments
* $array **array**



### <a name="method-array_replace"></a>array_replace

```php
array|mixed|null ToolsCore::array_replace()
```

Implement array_replace for PHP <= 5.2



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 749](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L749)




### <a name="method-boolVal"></a>boolVal

```php
mixed ToolsCore::boolVal($value)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3403)


#### Arguments
* $value **mixed**



### <a name="method-cccCss"></a>cccCss

```php
mixed ToolsCore::cccCss($css_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2169)


#### Arguments
* $css_files **mixed**



### <a name="method-cccJS"></a>cccJS

```php
mixed ToolsCore::cccJS($js_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2179)


#### Arguments
* $js_files **mixed**



### <a name="method-ceilf"></a>ceilf

```php
float ToolsCore::ceilf(float $value, integer $precision)
```

returns the rounded value down of $value to specified precision



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1907](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1907)


#### Arguments
* $value **float**
* $precision **integer**



### <a name="method-changeFileMTime"></a>changeFileMTime

```php
mixed ToolsCore::changeFileMTime($file_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3347)


#### Arguments
* $file_name **mixed**



### <a name="method-checkPhpVersion"></a>checkPhpVersion

```php
string ToolsCore::checkPhpVersion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2694](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2694)




### <a name="method-chmodr"></a>chmodr

```php
mixed ToolsCore::chmodr($path, $filemode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2763](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2763)


#### Arguments
* $path **mixed**
* $filemode **mixed**



### <a name="method-cleanNonUnicodeSupport"></a>cleanNonUnicodeSupport

```php
string ToolsCore::cleanNonUnicodeSupport(string $pattern)
```

Delete unicode class from regular expression patterns



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3224)


#### Arguments
* $pattern **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ToolsCore::clearCache(\Smarty $smarty, $tpl, $cache_id, $compile_id)
```

Clear cache for Smarty



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2916](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2916)


#### Arguments
* $smarty **Smarty**
* $tpl **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-clearColorListCache"></a>clearColorListCache

```php
mixed ToolsCore::clearColorListCache($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2954](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2954)


#### Arguments
* $id_product **mixed**



### <a name="method-clearCompile"></a>clearCompile

```php
mixed ToolsCore::clearCompile($smarty)
```

Clear compile for Smarty



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2933)


#### Arguments
* $smarty **mixed**



### <a name="method-clearSmartyCache"></a>clearSmartyCache

```php
mixed ToolsCore::clearSmartyCache()
```

Clear Smarty cache and compile folders



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2947](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2947)




### <a name="method-clearXMLCache"></a>clearXMLCache

```php
mixed ToolsCore::clearXMLCache()
```

Clear XML cache folder



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 944](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L944)




### <a name="method-completeMetaTags"></a>completeMetaTags

```php
mixed ToolsCore::completeMetaTags($meta_tags, $default_value, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1119)


#### Arguments
* $meta_tags **mixed**
* $default_value **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-convertBytes"></a>convertBytes

```php
integer ToolsCore::convertBytes(string $value)
```

Convert a shorthand byte value from a PHP configuration directive to an integer value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2837](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2837)


#### Arguments
* $value **string** - value to convert



### <a name="method-convertPrice"></a>convertPrice

```php
float ToolsCore::convertPrice(float $price, object|array $currency, boolean $to_currency, \Context $context)
```

Return price converted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 716](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L716)


#### Arguments
* $price **float** - Product price
* $currency **object|array** - Current currency object
* $to_currency **boolean** - convert to currency or from currency to default currency
* $context **[Context](class.ContextCore.md)**



### <a name="method-convertPriceFull"></a>convertPriceFull

```php
mixed ToolsCore::convertPriceFull(float $amount, \Currency $currency_from, \Currency $currency_to)
```

Convert amount from a currency to an other currency automatically



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 784](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L784)


#### Arguments
* $amount **float**
* $currency_from **[Currency](class.CurrencyCore.md)** - if null we used the default currency
* $currency_to **[Currency](class.CurrencyCore.md)** - if null we used the default currency



### <a name="method-copy"></a>copy

```php
mixed ToolsCore::copy($source, $destination, $stream_context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2012](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2012)


#### Arguments
* $source **mixed**
* $destination **mixed**
* $stream_context **mixed**



### <a name="method-d"></a>d

```php
mixed ToolsCore::d(object $object, $kill)
```

ALIAS OF dieObject() - Display an error with detailed object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1028)


#### Arguments
* $object **object** - Object to display
* $kill **mixed**



### <a name="method-dateDays"></a>dateDays

```php
mixed ToolsCore::dateDays()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1650](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1650)




### <a name="method-dateFormat"></a>dateFormat

```php
string ToolsCore::dateFormat(array $params, object $smarty)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L815)


#### Arguments
* $params **array** - Date, format...
* $smarty **object** - Smarty object for language preferences



### <a name="method-dateFrom"></a>dateFrom

```php
mixed ToolsCore::dateFrom($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1671](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1671)


#### Arguments
* $date **mixed**



### <a name="method-dateMonths"></a>dateMonths

```php
mixed ToolsCore::dateMonths()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1658](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1658)




### <a name="method-dateTo"></a>dateTo

```php
mixed ToolsCore::dateTo($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1679](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1679)


#### Arguments
* $date **mixed**



### <a name="method-dateYears"></a>dateYears

```php
array ToolsCore::dateYears()
```

Generate date form



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1642)




### <a name="method-debug_backtrace"></a>debug_backtrace

```php
mixed ToolsCore::debug_backtrace($start, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1033](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1033)


#### Arguments
* $start **mixed**
* $limit **mixed**



### <a name="method-deleteDirectory"></a>deleteDirectory

```php
mixed ToolsCore::deleteDirectory(string $dirname, $delete_self)
```

Delete directory and subdirectories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L895)


#### Arguments
* $dirname **string** - Directory name
* $delete_self **mixed**



### <a name="method-deleteFile"></a>deleteFile

```php
mixed ToolsCore::deleteFile(string $file, array $exclude_files)
```

Delete file



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L929)


#### Arguments
* $file **string** - File path
* $exclude_files **array** - Excluded files



### <a name="method-dieObject"></a>dieObject

```php
\$object ToolsCore::dieObject(mixed $object, boolean $kill)
```

Display an error with detailed object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 992](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L992)


#### Arguments
* $object **mixed**
* $kill **boolean**



### <a name="method-dieOrLog"></a>dieOrLog

```php
boolean ToolsCore::dieOrLog(string $msg, boolean $die)
```

Display error and dies or silently log the error.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2893](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2893)


#### Arguments
* $msg **string**
* $die **boolean**



### <a name="method-display404Error"></a>display404Error

```php
mixed ToolsCore::display404Error()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2865](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2865)




### <a name="method-displayAsDeprecated"></a>displayAsDeprecated

```php
mixed ToolsCore::displayAsDeprecated($message)
```

Display a warning message indicating that the method is deprecated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2570](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2570)


#### Arguments
* $message **mixed**



### <a name="method-displayDate"></a>displayDate

```php
string ToolsCore::displayDate(string $date, integer $id_lang, boolean $full, string $separator)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L829)


#### Arguments
* $date **string** - Date to display format UNIX
* $id_lang **integer** - Language id DEPRECATED
* $full **boolean** - With time or not (optional)
* $separator **string** - DEPRECATED



### <a name="method-displayError"></a>displayError

```php
mixed ToolsCore::displayError(string $string, boolean $htmlentities, \Context $context)
```

Display an error according to an error code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 967](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L967)


#### Arguments
* $string **string** - Error message
* $htmlentities **boolean** - By default at true for parsing error message with htmlentities
* $context **[Context](class.ContextCore.md)**



### <a name="method-displayFileAsDeprecated"></a>displayFileAsDeprecated

```php
mixed ToolsCore::displayFileAsDeprecated()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2596](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2596)




### <a name="method-displayNumber"></a>displayNumber

```php
mixed ToolsCore::displayNumber($number, $currency)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L686)


#### Arguments
* $number **mixed**
* $currency **mixed**



### <a name="method-displayParameterAsDeprecated"></a>displayParameterAsDeprecated

```php
mixed ToolsCore::displayParameterAsDeprecated($parameter)
```

Display a warning message indicating that the parameter is deprecated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2585)


#### Arguments
* $parameter **mixed**



### <a name="method-displayPrice"></a>displayPrice

```php
string ToolsCore::displayPrice(float $price, object|array $currency, $no_utf8, \Context $context)
```

Return price with currency sign for a given product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 607](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L607)


#### Arguments
* $price **float** - Product price
* $currency **object|array** - Current currency (object, id_currency, NULL =&gt; context currency)
* $no_utf8 **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-displayPriceSmarty"></a>displayPriceSmarty

```php
mixed ToolsCore::displayPriceSmarty($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L696)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ToolsCore::enableCache($level, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2616](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2616)


#### Arguments
* $level **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-encrypt"></a>encrypt

```php
mixed ToolsCore::encrypt(string $passwd)
```

Encrypt password



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1130)


#### Arguments
* $passwd **string** - String to encrypt



### <a name="method-encryptIV"></a>encryptIV

```php
mixed ToolsCore::encryptIV(string $data)
```

Encrypt data string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1140)


#### Arguments
* $data **string** - String to encrypt



### <a name="method-error_log"></a>error_log

```php
boolean ToolsCore::error_log(mixed $object, integer|null $message_type, string|null $destination, string|null $extra_headers)
```

Prints object information into error log



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1080](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1080)


#### Arguments
* $object **mixed**
* $message_type **integer|null**
* $destination **string|null**
* $extra_headers **string|null**



### <a name="method-fd"></a>fd

```php
mixed ToolsCore::fd(object $object, $type)
```

Display a var dump in firebug console



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1009)


#### Arguments
* $object **object** - Object to display
* $type **mixed**



### <a name="method-fileAttachment"></a>fileAttachment

```php
array|null ToolsCore::fileAttachment(string $input, boolean $return_content)
```

Returns an array containing information about
HTTP file upload variable ($_FILES)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3329)


#### Arguments
* $input **string** - File upload field name
* $return_content **boolean** - If true, returns uploaded file contents



### <a name="method-file_exists_cache"></a>file_exists_cache

```php
boolean ToolsCore::file_exists_cache(string $filename)
```

file_exists() wrapper with cache to speedup performance



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1946](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1946)


#### Arguments
* $filename **string** - File name



### <a name="method-file_exists_no_cache"></a>file_exists_no_cache

```php
boolean ToolsCore::file_exists_no_cache(string $filename)
```

file_exists() wrapper with a call to clearstatcache prior



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1959](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1959)


#### Arguments
* $filename **string** - File name



### <a name="method-file_get_contents"></a>file_get_contents

```php
mixed ToolsCore::file_get_contents($url, $use_include_path, $stream_context, $curl_timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1965](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1965)


#### Arguments
* $url **mixed**
* $use_include_path **mixed**
* $stream_context **mixed**
* $curl_timeout **mixed**



### <a name="method-floorf"></a>floorf

```php
float ToolsCore::floorf(float $value, integer $precision)
```

returns the rounded value up of $value to specified precision



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1927)


#### Arguments
* $value **float**
* $precision **integer**



### <a name="method-formatBytes"></a>formatBytes

```php
string ToolsCore::formatBytes($size, integer $precision)
```

Format a number into a human readable format
e.g. 24962496 => 23.81M



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3393](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3393)


#### Arguments
* $size **mixed**
* $precision **integer**



### <a name="method-generateHtaccess"></a>generateHtaccess

```php
mixed ToolsCore::generateHtaccess($path, $rewrite_settings, $cache_control, $specific, $disable_multiviews, $medias, $disable_modsec)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2207)


#### Arguments
* $path **mixed**
* $rewrite_settings **mixed**
* $cache_control **mixed**
* $specific **mixed**
* $disable_multiviews **mixed**
* $medias **mixed**
* $disable_modsec **mixed**



### <a name="method-generateIndex"></a>generateIndex

```php
mixed ToolsCore::generateIndex()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2483](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2483)




### <a name="method-getAdminImageUrl"></a>getAdminImageUrl

```php
mixed ToolsCore::getAdminImageUrl(string $image, $entities)
```

Get a valid image URL to use from BackOffice



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1205)


#### Arguments
* $image **string** - Image name
* $entities **mixed**



### <a name="method-getAdminToken"></a>getAdminToken

```php
mixed ToolsCore::getAdminToken(string $string)
```

Tokenize a string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1165)


#### Arguments
* $string **string** - string to encript



### <a name="method-getAdminTokenLite"></a>getAdminTokenLite

```php
mixed ToolsCore::getAdminTokenLite($tab, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1170)


#### Arguments
* $tab **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAdminTokenLiteSmarty"></a>getAdminTokenLiteSmarty

```php
mixed ToolsCore::getAdminTokenLiteSmarty($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1177)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-getAdminUrl"></a>getAdminUrl

```php
mixed ToolsCore::getAdminUrl(string $url, $entities)
```

Get a valid URL to use from BackOffice



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1189)


#### Arguments
* $url **string** - An URL to use in BackOffice
* $entities **mixed**



### <a name="method-getAllValues"></a>getAllValues

```php
mixed ToolsCore::getAllValues()
```

Get all values from $_POST/$_GET



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L449)




### <a name="method-getBrightness"></a>getBrightness

```php
mixed ToolsCore::getBrightness($hex)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2053](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2053)


#### Arguments
* $hex **mixed**



### <a name="method-getBytes"></a>getBytes

```php
boolean|string ToolsCore::getBytes($length)
```

Random bytes generator

Thanks to Zend for entropy

* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L90)


#### Arguments
* $length **mixed** - Desired length of random bytes



### <a name="method-getCountry"></a>getCountry

```php
mixed ToolsCore::getCountry($address)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L546)


#### Arguments
* $address **mixed**



### <a name="method-getCurrentUrlProtocolPrefix"></a>getCurrentUrlProtocolPrefix

```php
string ToolsCore::getCurrentUrlProtocolPrefix()
```

Get the current url prefix protocol (https/http)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L402)




### <a name="method-getDefaultIndexContent"></a>getDefaultIndexContent

```php
mixed ToolsCore::getDefaultIndexContent()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2490)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
string ToolsCore::getDescriptionClean($description)
```

Allows to display the category description without HTML tags and slashes



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3456)


#### Arguments
* $description **mixed**



### <a name="method-getFullPath"></a>getFullPath

```php
mixed ToolsCore::getFullPath($id_category, $end, $type_cat, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1286)


#### Arguments
* $id_category **mixed**
* $end **mixed**
* $type_cat **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getHomeMetaTags"></a>getHomeMetaTags

```php
mixed ToolsCore::getHomeMetaTags($id_lang, $page_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1110)


#### Arguments
* $id_lang **mixed**
* $page_name **mixed**



### <a name="method-getHttpHost"></a>getHttpHost

```php
string ToolsCore::getHttpHost(boolean $http, boolean $entities, $ignore_port)
```

getHttpHost return the <b>current</b> host used, with the protocol (http or https) if $http is true
This function should not be used to choose http or https domain name.

Use Tools::getShopDomain() or Tools::getShopDomainSsl instead

* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L283)


#### Arguments
* $http **boolean**
* $entities **boolean**
* $ignore_port **mixed**



### <a name="method-getIsset"></a>getIsset

```php
mixed ToolsCore::getIsset($key)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 454](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L454)


#### Arguments
* $key **mixed**



### <a name="method-getMaxUploadSize"></a>getMaxUploadSize

```php
integer ToolsCore::getMaxUploadSize(integer $max_size)
```

Get max file upload size considering server settings and optional max value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3034](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3034)


#### Arguments
* $max_size **integer** - optional max file size



### <a name="method-getMediaServer"></a>getMediaServer

```php
mixed ToolsCore::getMediaServer($filename)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2187)


#### Arguments
* $filename **mixed**



### <a name="method-getMemoryLimit"></a>getMemoryLimit

```php
integer ToolsCore::getMemoryLimit()
```

getMemoryLimit allow to get the memory limit in octet



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2970](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2970)




### <a name="method-getMetaTags"></a>getMetaTags

```php
mixed ToolsCore::getMetaTags($id_lang, $page_name, $title)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1101)


#### Arguments
* $id_lang **mixed**
* $page_name **mixed**
* $title **mixed**



### <a name="method-getOctets"></a>getOctets

```php
integer ToolsCore::getOctets($option)
```

getOctet allow to gets the value of a configuration option in octet



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2983](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2983)


#### Arguments
* $option **mixed**



### <a name="method-getPath"></a>getPath

```php
mixed ToolsCore::getPath(integer $id_category, string $path, $link_on_the_item, $category_type, \Context $context)
```

Get the user's journey



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1218)


#### Arguments
* $id_category **integer** - Category ID
* $path **string** - Path end
* $link_on_the_item **mixed**
* $category_type **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductsOrder"></a>getProductsOrder

```php
string ToolsCore::getProductsOrder(string $type, string $value, boolean|\bool(false)|string $prefix)
```

Get products order field name for queries.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2797)


#### Arguments
* $type **string** - by|way
* $value **string** - If no index given, use default order from admin -&gt; pref -&gt; products
* $prefix **boolean|bool(false)|string**



### <a name="method-getProtocol"></a>getProtocol

```php
String ToolsCore::getProtocol(boolean $use_ssl)
```

getProtocol return the set protocol according to configuration (http[s])



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L269)


#### Arguments
* $use_ssl **boolean** - true if require ssl



### <a name="method-getRemoteAddr"></a>getRemoteAddr

```php
string ToolsCore::getRemoteAddr()
```

Get the server variable REMOTE_ADDR, or the first ip of HTTP_X_FORWARDED_FOR (when using proxy)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L348)




### <a name="method-getSafeModeStatus"></a>getSafeModeStatus

```php
mixed ToolsCore::getSafeModeStatus()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2729](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2729)




### <a name="method-getServerName"></a>getServerName

```php
string ToolsCore::getServerName()
```

Get the server variable SERVER_NAME



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L336)




### <a name="method-getShopDomain"></a>getShopDomain

```php
string ToolsCore::getShopDomain(boolean $http, boolean $entities)
```

getShopDomain returns domain name according to configuration and ignoring ssl



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L302)


#### Arguments
* $http **boolean** - if true, return domain name with protocol
* $entities **boolean** - if true, convert special chars to HTML entities



### <a name="method-getShopDomainSsl"></a>getShopDomainSsl

```php
string ToolsCore::getShopDomainSsl(boolean $http, boolean $entities)
```

getShopDomainSsl returns domain name according to configuration and depending on ssl activation



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L320)


#### Arguments
* $http **boolean** - if true, return domain name with protocol
* $entities **boolean** - if true, convert special chars to HTML entities



### <a name="method-getShopProtocol"></a>getShopProtocol

```php
String ToolsCore::getShopProtocol()
```

getShopProtocol return the available protocol for the current shop in use
SSL if Configuration is set on and available for the server



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L257)




### <a name="method-getToken"></a>getToken

```php
mixed ToolsCore::getToken($page, \Context $context)
```

Get token to prevent CSRF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1150)


#### Arguments
* $page **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getUserBrowser"></a>getUserBrowser

```php
mixed ToolsCore::getUserBrowser()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3428](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3428)




### <a name="method-getUserPlatform"></a>getUserPlatform

```php
mixed ToolsCore::getUserPlatform()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3410)




### <a name="method-getValue"></a>getValue

```php
mixed ToolsCore::getValue(string $key, mixed $default_value)
```

Get a value from $_POST / $_GET
if unavailable, take a default value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L431)


#### Arguments
* $key **string** - Value key
* $default_value **mixed** - (optional)



### <a name="method-hourGenerate"></a>hourGenerate

```php
mixed ToolsCore::hourGenerate($hours, $minutes, $seconds)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1666](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1666)


#### Arguments
* $hours **mixed**
* $minutes **mixed**
* $seconds **mixed**



### <a name="method-htmlentitiesDecodeUTF8"></a>htmlentitiesDecodeUTF8

```php
mixed ToolsCore::htmlentitiesDecodeUTF8($string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 872](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L872)


#### Arguments
* $string **mixed**



### <a name="method-htmlentitiesUTF8"></a>htmlentitiesUTF8

```php
mixed ToolsCore::htmlentitiesUTF8($string, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L864)


#### Arguments
* $string **mixed**
* $type **mixed**



### <a name="method-iconv"></a>iconv

```php
mixed ToolsCore::iconv($from, $to, $string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1772](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1772)


#### Arguments
* $from **mixed**
* $to **mixed**
* $string **mixed**



### <a name="method-isCallable"></a>isCallable

```php
mixed ToolsCore::isCallable($function)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2643)


#### Arguments
* $function **mixed**



### <a name="method-isEmpty"></a>isEmpty

```php
mixed ToolsCore::isEmpty($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1779](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1779)


#### Arguments
* $field **mixed**



### <a name="method-isPHPCLI"></a>isPHPCLI

```php
boolean ToolsCore::isPHPCLI()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3010](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3010)




### <a name="method-isSubmit"></a>isSubmit

```php
mixed ToolsCore::isSubmit(string $submit)
```

Check if submit has been posted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1090](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1090)


#### Arguments
* $submit **string** - submit name



### <a name="method-isX86_64arch"></a>isX86_64arch

```php
boolean ToolsCore::isX86_64arch()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3001](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3001)




### <a name="method-jsonDecode"></a>jsonDecode

```php
array ToolsCore::jsonDecode(string $json, boolean $assoc)
```

jsonDecode convert json string to php array / object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2537](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2537)


#### Arguments
* $json **string**
* $assoc **boolean** - (since 1.4.2.4) if true, convert to associativ array



### <a name="method-jsonEncode"></a>jsonEncode

```php
string ToolsCore::jsonEncode(array $data)
```

Convert an array to json string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2555](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2555)


#### Arguments
* $data **array**



### <a name="method-link_rewrite"></a>link_rewrite

```php
string ToolsCore::link_rewrite(string $str, boolean $utf8_decode)
```

Return the friendly url from the provided string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1318)


#### Arguments
* $str **string**
* $utf8_decode **boolean** - (deprecated)



### <a name="method-math_round"></a>math_round

```php
mixed ToolsCore::math_round($value, $places, $mode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1819](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1819)


#### Arguments
* $value **mixed**
* $places **mixed**
* $mode **mixed**



### <a name="method-minifyCSS"></a>minifyCSS

```php
mixed ToolsCore::minifyCSS($css_content, $fileuri)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2116)


#### Arguments
* $css_content **mixed**
* $fileuri **mixed**



### <a name="method-minifyHTML"></a>minifyHTML

```php
mixed ToolsCore::minifyHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2022](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2022)


#### Arguments
* $html_content **mixed**



### <a name="method-minifyHTMLpregCallback"></a>minifyHTMLpregCallback

```php
mixed ToolsCore::minifyHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2068](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2068)


#### Arguments
* $preg_matches **mixed**



### <a name="method-modRewriteActive"></a>modRewriteActive

```php
mixed ToolsCore::modRewriteActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3189)




### <a name="method-nl2br"></a>nl2br

```php
string ToolsCore::nl2br($str)
```

Convert \n and \r\n and \r to <br />



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2906](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2906)


#### Arguments
* $str **mixed**



### <a name="method-normalizeDirectory"></a>normalizeDirectory

```php
mixed ToolsCore::normalizeDirectory($directory)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1628](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1628)


#### Arguments
* $directory **mixed**



### <a name="method-orderbyPrice"></a>orderbyPrice

```php
mixed ToolsCore::orderbyPrice($array, $order_way)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1757](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1757)


#### Arguments
* $array **mixed**
* $order_way **mixed**



### <a name="method-p"></a>p

```php
mixed ToolsCore::p(object $object)
```

ALIAS OF dieObject() - Display an error with detailed object but don't stop the execution



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1065](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1065)


#### Arguments
* $object **object** - Object to display



### <a name="method-pRegexp"></a>pRegexp

```php
mixed ToolsCore::pRegexp($s, $delim)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2649](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2649)


#### Arguments
* $s **mixed**
* $delim **mixed**



### <a name="method-packJS"></a>packJS

```php
mixed ToolsCore::packJS($js_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2095](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2095)


#### Arguments
* $js_content **mixed**



### <a name="method-packJSinHTML"></a>packJSinHTML

```php
mixed ToolsCore::packJSinHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2077](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2077)


#### Arguments
* $html_content **mixed**



### <a name="method-packJSinHTMLpregCallback"></a>packJSinHTMLpregCallback

```php
mixed ToolsCore::packJSinHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2086](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2086)


#### Arguments
* $preg_matches **mixed**



### <a name="method-parserSQL"></a>parserSQL

```php
mixed ToolsCore::parserSQL($sql)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2102)


#### Arguments
* $sql **mixed**



### <a name="method-passwdGen"></a>passwdGen

```php
boolean|string ToolsCore::passwdGen(integer $length, string $flag)
```

Random password generator



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L44)


#### Arguments
* $length **integer** - Desired length (optional)
* $flag **string** - Output type (NUMERIC, ALPHANUMERIC, NO_NUMERIC, RANDOM)



### <a name="method-property_exists"></a>property_exists

```php
boolean ToolsCore::property_exists(object $class, string $property)
```

Function property_exists does not exist in PHP < 5.1



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2675](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2675)


#### Arguments
* $class **object**
* $property **string**



### <a name="method-ps_round"></a>ps_round

```php
float ToolsCore::ps_round(float $value, integer $precision, $round_mode)
```

returns the rounded value of $value to specified precision, according to your configuration;



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1793](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1793)


#### Arguments
* $value **float**
* $precision **integer**
* $round_mode **mixed**



### <a name="method-purifyHTML"></a>purifyHTML

```php
mixed ToolsCore::purifyHTML($html, $uri_unescape, $allow_style)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3461)


#### Arguments
* $html **mixed**
* $uri_unescape **mixed**
* $allow_style **mixed**



### <a name="method-recurseCopy"></a>recurseCopy

```php
mixed ToolsCore::recurseCopy($src, $dst, boolean $del)
```

Copy the folder $src into $dst, $dst is created if it do not exist



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3081](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3081)


#### Arguments
* $src **mixed**
* $dst **mixed**
* $del **boolean** - if true, delete the file after copy



### <a name="method-redirect"></a>redirect

```php
mixed ToolsCore::redirect(string $url, string $base_uri, \Link $link, string|array $headers)
```

Redirect user to another page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L179)


#### Arguments
* $url **string** - Desired URL
* $base_uri **string** - Base URI (optional)
* $link **[Link](class.LinkCore.md)**
* $headers **string|array** - A list of headers to send before redirection



### <a name="method-redirectAdmin"></a>redirectAdmin

```php
mixed ToolsCore::redirectAdmin(string $url)
```

Redirect user to another admin page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L245)


#### Arguments
* $url **string** - Desired URL



### <a name="method-redirectLink"></a>redirectLink

```php
mixed ToolsCore::redirectLink(string $url)
```

Redirect URLs already containing PS_BASE_URI



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L223)


#### Arguments
* $url **string** - Desired URL



### <a name="method-replaceAccentedChars"></a>replaceAccentedChars

```php
string ToolsCore::replaceAccentedChars(string $str)
```

Replace all accented chars by their equivalent non accented chars.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1384)


#### Arguments
* $str **string**



### <a name="method-replaceByAbsoluteURL"></a>replaceByAbsoluteURL

```php
mixed ToolsCore::replaceByAbsoluteURL($matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2122)


#### Arguments
* $matches **mixed**



### <a name="method-restoreCacheSettings"></a>restoreCacheSettings

```php
mixed ToolsCore::restoreCacheSettings(\Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2632](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2632)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-round_helper"></a>round_helper

```php
mixed ToolsCore::round_helper($value, $mode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1876)


#### Arguments
* $value **mixed**
* $mode **mixed**



### <a name="method-rtrimString"></a>rtrimString

```php
string ToolsCore::rtrimString(string $str, string $str_search)
```

Delete a substring from another one starting from the right



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3377](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3377)


#### Arguments
* $str **string**
* $str_search **string**



### <a name="method-safeDefine"></a>safeDefine

```php
mixed ToolsCore::safeDefine(string $constant, mixed $value)
```

Check if a constant was already defined



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3537](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3537)


#### Arguments
* $constant **string** - Constant name
* $value **mixed** - Default value to set if not defined



### <a name="method-safeOutput"></a>safeOutput

```php
string ToolsCore::safeOutput(string $string, $html)
```

Sanitize a string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L857)


#### Arguments
* $string **string** - String to sanitize
* $html **mixed**



### <a name="method-safePostVars"></a>safePostVars

```php
mixed ToolsCore::safePostVars()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L882)




### <a name="method-scandir"></a>scandir

```php
array ToolsCore::scandir($path, $ext, $dir, $recursive)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3116)


#### Arguments
* $path **mixed**
* $ext **mixed**
* $dir **mixed**
* $recursive **mixed**



### <a name="method-secureReferrer"></a>secureReferrer

```php
string ToolsCore::secureReferrer(string $referrer)
```

Secure an URL referrer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L416)


#### Arguments
* $referrer **string** - URL referrer



### <a name="method-setCookieLanguage"></a>setCookieLanguage

```php
string ToolsCore::setCookieLanguage($cookie)
```

Change language in cookie while clicking on a flag



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 466](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L466)


#### Arguments
* $cookie **mixed**



### <a name="method-setCurrency"></a>setCurrency

```php
\Currency ToolsCore::setCurrency($cookie)
```

Set cookie currency from POST or default currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L567)


#### Arguments
* $cookie **mixed**



### <a name="method-simplexml_load_file"></a>simplexml_load_file

```php
mixed ToolsCore::simplexml_load_file($url, $class_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2000](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2000)


#### Arguments
* $url **mixed**
* $class_name **mixed**



### <a name="method-spreadAmount"></a>spreadAmount

```php
mixed ToolsCore::spreadAmount($amount, $precision, $rows, $column)
```

Spread an amount on lines, adjusting the $column field,
with the biggest adjustments going to the rows having the
highest $sort_column.

E.g.:

$rows = [['a' => 5.1], ['a' => 8.2]];

spreadAmount(0.3, 1, $rows, 'a');

=> $rows is [['a' => 8.4], ['a' => 5.2]]

* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3564)


#### Arguments
* $amount **mixed** - float  The amount to spread across the rows
* $precision **mixed** - int Rounding precision
                  e.g. if $amount is 1, $precision is 0 and $rows = [[&#039;a&#039; =&gt; 2], [&#039;a&#039; =&gt; 1]]
                  then the resulting $rows will be [[&#039;a&#039; =&gt; 3], [&#039;a&#039; =&gt; 1]]
                  But if $precision were 1, then the resulting $rows would be [[&#039;a&#039; =&gt; 2.5], [&#039;a&#039; =&gt; 1.5]]
* $rows **mixed**
* $column **mixed** - string The column on which to perform adjustments



### <a name="method-str2url"></a>str2url

```php
string ToolsCore::str2url(string $str)
```

Return a friendly url made from the provided string
If the mbstring library is available, the output is the same as the js function of the same name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1332](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1332)


#### Arguments
* $str **string**



### <a name="method-strReplaceFirst"></a>strReplaceFirst

```php
mixed ToolsCore::strReplaceFirst($search, $replace, $subject, $cur)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L166)


#### Arguments
* $search **mixed**
* $replace **mixed**
* $subject **mixed**
* $cur **mixed**



### <a name="method-str_replace_once"></a>str_replace_once

```php
mixed ToolsCore::str_replace_once($needle, $replace, $haystack)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2657)


#### Arguments
* $needle **mixed**
* $replace **mixed**
* $haystack **mixed**



### <a name="method-stripslashes"></a>stripslashes

```php
mixed ToolsCore::stripslashes($string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1706)


#### Arguments
* $string **mixed**



### <a name="method-strlen"></a>strlen

```php
mixed ToolsCore::strlen($str, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1696)


#### Arguments
* $str **mixed**
* $encoding **mixed**



### <a name="method-strpos"></a>strpos

```php
mixed ToolsCore::strpos($str, $find, $offset, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1731](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1731)


#### Arguments
* $str **mixed**
* $find **mixed**
* $offset **mixed**
* $encoding **mixed**



### <a name="method-strrpos"></a>strrpos

```php
mixed ToolsCore::strrpos($str, $find, $offset, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1738)


#### Arguments
* $str **mixed**
* $find **mixed**
* $offset **mixed**
* $encoding **mixed**



### <a name="method-strtolower"></a>strtolower

```php
mixed ToolsCore::strtolower($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1687](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1687)


#### Arguments
* $str **mixed**



### <a name="method-strtoupper"></a>strtoupper

```php
mixed ToolsCore::strtoupper($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1713](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1713)


#### Arguments
* $str **mixed**



### <a name="method-substr"></a>substr

```php
mixed ToolsCore::substr($str, $start, $length, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1722](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1722)


#### Arguments
* $str **mixed**
* $start **mixed**
* $length **mixed**
* $encoding **mixed**



### <a name="method-switchLanguage"></a>switchLanguage

```php
mixed ToolsCore::switchLanguage(\Context $context)
```

Set cookie id_lang



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 515](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L515)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-throwDeprecated"></a>throwDeprecated

```php
mixed ToolsCore::throwDeprecated($error, $message, $class)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Tools.php line 2607](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2607)


#### Arguments
* $error **mixed**
* $message **mixed**
* $class **mixed**



### <a name="method-toCamelCase"></a>toCamelCase

```php
mixed ToolsCore::toCamelCase($str, $catapitalise_first_char)
```

Translates a string with underscores into camel case (e.g. first_name -> firstName)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2032](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2032)


#### Arguments
* $str **mixed**
* $catapitalise_first_char **mixed**



### <a name="method-toUnderscoreCase"></a>toUnderscoreCase

```php
string ToolsCore::toUnderscoreCase(string $string)
```

Transform a CamelCase string to underscore_case string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2046](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2046)


#### Arguments
* $string **string**



### <a name="method-truncate"></a>truncate

```php
mixed ToolsCore::truncate($str, $max_length, $suffix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1492](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1492)


#### Arguments
* $str **mixed**
* $max_length **mixed**
* $suffix **mixed**



### <a name="method-truncateString"></a>truncateString

```php
mixed ToolsCore::truncateString($text, $length, $options)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1501)


#### Arguments
* $text **mixed**
* $length **mixed**
* $options **mixed**



### <a name="method-ucfirst"></a>ucfirst

```php
mixed ToolsCore::ucfirst($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1745)


#### Arguments
* $str **mixed**



### <a name="method-ucwords"></a>ucwords

```php
mixed ToolsCore::ucwords($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1750](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L1750)


#### Arguments
* $str **mixed**



### <a name="method-unSerialize"></a>unSerialize

```php
mixed ToolsCore::unSerialize($serialized, $object)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3198)


#### Arguments
* $serialized **mixed**
* $object **mixed**



### <a name="method-url"></a>url

```php
string ToolsCore::url(string $begin, string $end)
```

Concat $begin and $end, add ? or & between strings



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2881](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L2881)


#### Arguments
* $begin **string**
* $end **string**



### <a name="method-usingSecureMode"></a>usingSecureMode

```php
boolean ToolsCore::usingSecureMode()
```

Check if the current page use SSL connection on not



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L379)




### <a name="method-version_compare"></a>version_compare

```php
mixed ToolsCore::version_compare($v1, $v2, string $operator)
```

Align version sent and use internal function



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3153)


#### Arguments
* $v1 **mixed**
* $v2 **mixed**
* $operator **string**



### <a name="method-waitUntilFileIsModified"></a>waitUntilFileIsModified

```php
mixed ToolsCore::waitUntilFileIsModified($file_name, $timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3352](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Tools.php#L3352)


#### Arguments
* $file_name **mixed**
* $timeout **mixed**


