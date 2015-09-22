Class ToolsCore
=====================





* Class name: ToolsCore
* Source: [classes/Tools.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L27)


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
* [arrayUnique](#method-arrayUnique)
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
* [getBrightness](#method-getBrightness)
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
* [safeOutput](#method-safeOutput)
* [safePostVars](#method-safePostVars)
* [scandir](#method-scandir)
* [secureReferrer](#method-secureReferrer)
* [setCookieLanguage](#method-setCookieLanguage)
* [setCurrency](#method-setCurrency)
* [simplexml_load_file](#method-simplexml_load_file)
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
* Source: [classes/Tools.php line 1988](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1988).


### <a name="property-$_caching"></a>$_caching

```php
protected mixed $_caching
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L31).


### <a name="property-$_forceCompile"></a>$_forceCompile

```php
protected mixed $_forceCompile
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L30).


### <a name="property-$_user_browser"></a>$_user_browser

```php
protected mixed $_user_browser
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L33).


### <a name="property-$_user_plateform"></a>$_user_plateform

```php
protected mixed $_user_plateform
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L32).


### <a name="property-$file_exists_cache"></a>$file_exists_cache

```php
protected mixed $file_exists_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L29).


### <a name="property-$is_addons_up"></a>$is_addons_up

```php
protected mixed $is_addons_up = true
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 3033](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3033).


### <a name="property-$round_mode"></a>$round_mode

```php
public mixed $round_mode = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Tools.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L35).


Methods
-------


### <a name="method-ZipExtract"></a>ZipExtract

```php
boolean ToolsCore::ZipExtract($from_file, $to_dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2541)


#### Arguments
* $from_file **mixed**
* $to_dir **mixed**



### <a name="method-ZipTest"></a>ZipTest

```php
boolean ToolsCore::ZipTest($from_file)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2515](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2515)


#### Arguments
* $from_file **mixed**



### <a name="method-addCSS"></a>addCSS

```php
mixed ToolsCore::addCSS($css_uri, $css_media_type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1962](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1962)


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
* Source: [classes/Tools.php line 1952](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1952)


#### Arguments
* $js_uri **mixed**



### <a name="method-addonsRequest"></a>addonsRequest

```php
mixed ToolsCore::addonsRequest($request, $params)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3034](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3034)


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
* Source: [classes/Tools.php line 2969](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2969)


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
* Source: [classes/Tools.php line 2857](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2857)


#### Arguments
* $name **string** - module name



### <a name="method-argvToGET"></a>argvToGET

```php
mixed ToolsCore::argvToGET($argc, $argv)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2816](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2816)


#### Arguments
* $argc **mixed**
* $argv **mixed**



### <a name="method-arrayUnique"></a>arrayUnique

```php
array ToolsCore::arrayUnique(array $array)
```

Reproduce array_unique working before php version 5.2.9



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3013](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3013)


#### Arguments
* $array **array**



### <a name="method-boolVal"></a>boolVal

```php
mixed ToolsCore::boolVal($value)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3193](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3193)


#### Arguments
* $value **mixed**



### <a name="method-cccCss"></a>cccCss

```php
mixed ToolsCore::cccCss($css_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1972](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1972)


#### Arguments
* $css_files **mixed**



### <a name="method-cccJS"></a>cccJS

```php
mixed ToolsCore::cccJS($js_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1982](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1982)


#### Arguments
* $js_files **mixed**



### <a name="method-ceilf"></a>ceilf

```php
float ToolsCore::ceilf(float $value, integer $precision)
```

returns the rounded value down of $value to specified precision



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1722](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1722)


#### Arguments
* $value **float**
* $precision **integer**



### <a name="method-changeFileMTime"></a>changeFileMTime

```php
mixed ToolsCore::changeFileMTime($file_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3137)


#### Arguments
* $file_name **mixed**



### <a name="method-checkPhpVersion"></a>checkPhpVersion

```php
string ToolsCore::checkPhpVersion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2495)




### <a name="method-chmodr"></a>chmodr

```php
mixed ToolsCore::chmodr($path, $filemode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2564](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2564)


#### Arguments
* $path **mixed**
* $filemode **mixed**



### <a name="method-cleanNonUnicodeSupport"></a>cleanNonUnicodeSupport

```php
\pattern ToolsCore::cleanNonUnicodeSupport(string $pattern)
```

Delete unicode class from regular expression patterns



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3026](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3026)


#### Arguments
* $pattern **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ToolsCore::clearCache(\Smarty $smarty, $tpl, $cache_id, $compile_id)
```

Clear cache for Smarty



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2717](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2717)


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
* Source: [classes/Tools.php line 2755](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2755)


#### Arguments
* $id_product **mixed**



### <a name="method-clearCompile"></a>clearCompile

```php
mixed ToolsCore::clearCompile($smarty)
```

Clear compile for Smarty



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2734](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2734)


#### Arguments
* $smarty **mixed**



### <a name="method-clearSmartyCache"></a>clearSmartyCache

```php
mixed ToolsCore::clearSmartyCache()
```

Clear Smarty cache and compile folders



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2748](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2748)




### <a name="method-clearXMLCache"></a>clearXMLCache

```php
mixed ToolsCore::clearXMLCache()
```

Clear XML cache folder



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L790)




### <a name="method-completeMetaTags"></a>completeMetaTags

```php
mixed ToolsCore::completeMetaTags($meta_tags, $default_value, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 947](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L947)


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
* Source: [classes/Tools.php line 2638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2638)


#### Arguments
* $value **string** - value to convert



### <a name="method-convertPrice"></a>convertPrice

```php
float ToolsCore::convertPrice(float $price, object|array $currency, boolean $to_currency, \Context $context)
```

Return price converted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L595)


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
* Source: [classes/Tools.php line 630](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L630)


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
* Source: [classes/Tools.php line 1819](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1819)


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
* Source: [classes/Tools.php line 871](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L871)


#### Arguments
* $object **object** - Object to display
* $kill **mixed**



### <a name="method-dateDays"></a>dateDays

```php
mixed ToolsCore::dateDays()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1470)




### <a name="method-dateFormat"></a>dateFormat

```php
string ToolsCore::dateFormat(array $params, object $smarty)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L661)


#### Arguments
* $params **array** - Date, format...
* $smarty **object** - Smarty object for language preferences



### <a name="method-dateFrom"></a>dateFrom

```php
mixed ToolsCore::dateFrom($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1491](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1491)


#### Arguments
* $date **mixed**



### <a name="method-dateMonths"></a>dateMonths

```php
mixed ToolsCore::dateMonths()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1478](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1478)




### <a name="method-dateTo"></a>dateTo

```php
mixed ToolsCore::dateTo($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1499)


#### Arguments
* $date **mixed**



### <a name="method-dateYears"></a>dateYears

```php
array ToolsCore::dateYears()
```

Generate date form



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1462)




### <a name="method-debug_backtrace"></a>debug_backtrace

```php
mixed ToolsCore::debug_backtrace($start, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L876)


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
* Source: [classes/Tools.php line 741](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L741)


#### Arguments
* $dirname **string** - Directory name
* $delete_self **mixed**



### <a name="method-deleteFile"></a>deleteFile

```php
mixed ToolsCore::deleteFile($file, $exclude_files)
```

Delete file



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 775](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L775)


#### Arguments
* $file **mixed**
* $exclude_files **mixed**



### <a name="method-dieObject"></a>dieObject

```php
\$object ToolsCore::dieObject(mixed $object, boolean $kill)
```

Display an error with detailed object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L835)


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
* Source: [classes/Tools.php line 2694](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2694)


#### Arguments
* $msg **string**
* $die **boolean**



### <a name="method-display404Error"></a>display404Error

```php
mixed ToolsCore::display404Error()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2666](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2666)




### <a name="method-displayAsDeprecated"></a>displayAsDeprecated

```php
mixed ToolsCore::displayAsDeprecated($message)
```

Display a warning message indicating that the method is deprecated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2371)


#### Arguments
* $message **mixed**



### <a name="method-displayDate"></a>displayDate

```php
string ToolsCore::displayDate(string $date, integer $id_lang, boolean $full, string $separator)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L675)


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
* Source: [classes/Tools.php line 810](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L810)


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
* Source: [classes/Tools.php line 2397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2397)




### <a name="method-displayNumber"></a>displayNumber

```php
mixed ToolsCore::displayNumber($number, $currency)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L565)


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
* Source: [classes/Tools.php line 2386](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2386)


#### Arguments
* $parameter **mixed**



### <a name="method-displayPrice"></a>displayPrice

```php
string ToolsCore::displayPrice(float $price, object|array $currency, $no_utf8, \Context $context)
```

Return price with currency sign for a given product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L486)


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
* Source: [classes/Tools.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L575)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ToolsCore::enableCache($level, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2417](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2417)


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
* Source: [classes/Tools.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L958)


#### Arguments
* $passwd **string** - String to encrypt



### <a name="method-encryptIV"></a>encryptIV

```php
mixed ToolsCore::encryptIV(string $data)
```

Encrypt data string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 968](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L968)


#### Arguments
* $data **string** - String to encrypt



### <a name="method-fd"></a>fd

```php
mixed ToolsCore::fd(object $object, $type)
```

Display a var dump in firebug console



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L852)


#### Arguments
* $object **object** - Object to display
* $type **mixed**



### <a name="method-fileAttachment"></a>fileAttachment

```php
mixed ToolsCore::fileAttachment($input)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3121)


#### Arguments
* $input **mixed**



### <a name="method-file_exists_cache"></a>file_exists_cache

```php
boolean ToolsCore::file_exists_cache(string $filename)
```

file_exists() wrapper with cache to speedup performance



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1761](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1761)


#### Arguments
* $filename **string** - File name



### <a name="method-file_exists_no_cache"></a>file_exists_no_cache

```php
boolean ToolsCore::file_exists_no_cache(string $filename)
```

file_exists() wrapper with a call to clearstatcache prior



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1774](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1774)


#### Arguments
* $filename **string** - File name



### <a name="method-file_get_contents"></a>file_get_contents

```php
mixed ToolsCore::file_get_contents($url, $use_include_path, $stream_context, $curl_timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1780](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1780)


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
* Source: [classes/Tools.php line 1742](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1742)


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
* Source: [classes/Tools.php line 3183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3183)


#### Arguments
* $size **mixed**
* $precision **integer**



### <a name="method-generateHtaccess"></a>generateHtaccess

```php
mixed ToolsCore::generateHtaccess($path, $rewrite_settings, $cache_control, $specific, $disable_multiviews, $medias, $disable_modsec)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2010](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2010)


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
* Source: [classes/Tools.php line 2284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2284)




### <a name="method-getAdminImageUrl"></a>getAdminImageUrl

```php
mixed ToolsCore::getAdminImageUrl(string $image, $entities)
```

Get a valid image URL to use from BackOffice



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1033](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1033)


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
* Source: [classes/Tools.php line 993](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L993)


#### Arguments
* $string **string** - string to encript



### <a name="method-getAdminTokenLite"></a>getAdminTokenLite

```php
mixed ToolsCore::getAdminTokenLite($tab, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 998](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L998)


#### Arguments
* $tab **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAdminTokenLiteSmarty"></a>getAdminTokenLiteSmarty

```php
mixed ToolsCore::getAdminTokenLiteSmarty($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1005](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1005)


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
* Source: [classes/Tools.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1017)


#### Arguments
* $url **string** - An URL to use in BackOffice
* $entities **mixed**



### <a name="method-getBrightness"></a>getBrightness

```php
mixed ToolsCore::getBrightness($hex)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1860](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1860)


#### Arguments
* $hex **mixed**



### <a name="method-getCountry"></a>getCountry

```php
mixed ToolsCore::getCountry($address)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L426)


#### Arguments
* $address **mixed**



### <a name="method-getCurrentUrlProtocolPrefix"></a>getCurrentUrlProtocolPrefix

```php
string ToolsCore::getCurrentUrlProtocolPrefix()
```

Get the current url prefix protocol (https/http)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L292)




### <a name="method-getDefaultIndexContent"></a>getDefaultIndexContent

```php
mixed ToolsCore::getDefaultIndexContent()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2291](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2291)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

```php
string ToolsCore::getDescriptionClean($description)
```

Allows to display the category description without HTML tags and slashes



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3247)


#### Arguments
* $description **mixed**



### <a name="method-getFullPath"></a>getFullPath

```php
mixed ToolsCore::getFullPath($id_category, $end, $type_cat, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1114)


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
* Source: [classes/Tools.php line 938](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L938)


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
* Source: [classes/Tools.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L181)


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
* Source: [classes/Tools.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L334)


#### Arguments
* $key **mixed**



### <a name="method-getMaxUploadSize"></a>getMaxUploadSize

```php
integer ToolsCore::getMaxUploadSize(integer $max_size)
```

Get max file upload size considering server settings and optional max value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2835)


#### Arguments
* $max_size **integer** - optional max file size



### <a name="method-getMediaServer"></a>getMediaServer

```php
mixed ToolsCore::getMediaServer($filename)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1990](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1990)


#### Arguments
* $filename **mixed**



### <a name="method-getMemoryLimit"></a>getMemoryLimit

```php
integer ToolsCore::getMemoryLimit()
```

getMemoryLimit allow to get the memory limit in octet



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2771](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2771)




### <a name="method-getMetaTags"></a>getMetaTags

```php
mixed ToolsCore::getMetaTags($id_lang, $page_name, $title)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L929)


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
* Source: [classes/Tools.php line 2784](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2784)


#### Arguments
* $option **mixed**



### <a name="method-getPath"></a>getPath

```php
mixed ToolsCore::getPath(integer $id_category, string $path, $link_on_the_item, $category_type, \Context $context)
```

Get the user's journey



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1046](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1046)


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
* Source: [classes/Tools.php line 2598](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2598)


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
* Source: [classes/Tools.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L167)


#### Arguments
* $use_ssl **boolean** - true if require ssl



### <a name="method-getRemoteAddr"></a>getRemoteAddr

```php
string ToolsCore::getRemoteAddr()
```

Get the server variable REMOTE_ADDR, or the first ip of HTTP_X_FORWARDED_FOR (when using proxy)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L246)




### <a name="method-getSafeModeStatus"></a>getSafeModeStatus

```php
mixed ToolsCore::getSafeModeStatus()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2530)




### <a name="method-getServerName"></a>getServerName

```php
string ToolsCore::getServerName()
```

Get the server variable SERVER_NAME



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L234)




### <a name="method-getShopDomain"></a>getShopDomain

```php
string ToolsCore::getShopDomain(boolean $http, boolean $entities)
```

getShopDomain returns domain name according to configuration and ignoring ssl



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L200)


#### Arguments
* $http **boolean** - if true, return domain name with protocol
* $entities **boolean** - if true,



### <a name="method-getShopDomainSsl"></a>getShopDomainSsl

```php
string ToolsCore::getShopDomainSsl(boolean $http, boolean $entities)
```

getShopDomainSsl returns domain name according to configuration and depending on ssl activation



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L218)


#### Arguments
* $http **boolean** - if true, return domain name with protocol
* $entities **boolean** - if true,



### <a name="method-getShopProtocol"></a>getShopProtocol

```php
String ToolsCore::getShopProtocol()
```

getShopProtocol return the available protocol for the current shop in use
SSL if Configuration is set on and available for the server



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L155)




### <a name="method-getToken"></a>getToken

```php
mixed ToolsCore::getToken($page, \Context $context)
```

Get token to prevent CSRF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 978](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L978)


#### Arguments
* $page **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getUserBrowser"></a>getUserBrowser

```php
mixed ToolsCore::getUserBrowser()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3218)




### <a name="method-getUserPlatform"></a>getUserPlatform

```php
mixed ToolsCore::getUserPlatform()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3200)




### <a name="method-getValue"></a>getValue

```php
mixed ToolsCore::getValue(string $key, mixed $default_value)
```

Get a value from $_POST / $_GET
if unavailable, take a default value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L321)


#### Arguments
* $key **string** - Value key
* $default_value **mixed** - (optional)



### <a name="method-hourGenerate"></a>hourGenerate

```php
mixed ToolsCore::hourGenerate($hours, $minutes, $seconds)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1486)


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
* Source: [classes/Tools.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L718)


#### Arguments
* $string **mixed**



### <a name="method-htmlentitiesUTF8"></a>htmlentitiesUTF8

```php
mixed ToolsCore::htmlentitiesUTF8($string, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L710)


#### Arguments
* $string **mixed**
* $type **mixed**



### <a name="method-iconv"></a>iconv

```php
mixed ToolsCore::iconv($from, $to, $string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1592](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1592)


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
* Source: [classes/Tools.php line 2444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2444)


#### Arguments
* $function **mixed**



### <a name="method-isEmpty"></a>isEmpty

```php
mixed ToolsCore::isEmpty($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1599](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1599)


#### Arguments
* $field **mixed**



### <a name="method-isPHPCLI"></a>isPHPCLI

```php
boolean ToolsCore::isPHPCLI()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2811](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2811)




### <a name="method-isSubmit"></a>isSubmit

```php
mixed ToolsCore::isSubmit(string $submit)
```

Check if submit has been posted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 918](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L918)


#### Arguments
* $submit **string** - submit name



### <a name="method-isX86_64arch"></a>isX86_64arch

```php
boolean ToolsCore::isX86_64arch()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2802](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2802)




### <a name="method-jsonDecode"></a>jsonDecode

```php
array ToolsCore::jsonDecode(string $json, boolean $assoc)
```

jsonDecode convert json string to php array / object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2338](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2338)


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
* Source: [classes/Tools.php line 2356](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2356)


#### Arguments
* $data **array**



### <a name="method-link_rewrite"></a>link_rewrite

```php
string ToolsCore::link_rewrite(string $str, boolean $utf8_decode)
```

Return the friendly url from the provided string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1146)


#### Arguments
* $str **string**
* $utf8_decode **boolean** - (deprecated)



### <a name="method-math_round"></a>math_round

```php
mixed ToolsCore::math_round($value, $places, $mode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1634](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1634)


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
* Source: [classes/Tools.php line 1920](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1920)


#### Arguments
* $css_content **mixed**
* $fileuri **mixed**



### <a name="method-minifyHTML"></a>minifyHTML

```php
mixed ToolsCore::minifyHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1829](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1829)


#### Arguments
* $html_content **mixed**



### <a name="method-minifyHTMLpregCallback"></a>minifyHTMLpregCallback

```php
mixed ToolsCore::minifyHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1872](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1872)


#### Arguments
* $preg_matches **mixed**



### <a name="method-modRewriteActive"></a>modRewriteActive

```php
mixed ToolsCore::modRewriteActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2991](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2991)




### <a name="method-nl2br"></a>nl2br

```php
string ToolsCore::nl2br($str)
```

Convert \n and \r\n and \r to <br />



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2707](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2707)


#### Arguments
* $str **mixed**



### <a name="method-normalizeDirectory"></a>normalizeDirectory

```php
mixed ToolsCore::normalizeDirectory($directory)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1439](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1439)


#### Arguments
* $directory **mixed**



### <a name="method-orderbyPrice"></a>orderbyPrice

```php
mixed ToolsCore::orderbyPrice($array, $order_way)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1577](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1577)


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
* Source: [classes/Tools.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L908)


#### Arguments
* $object **object** - Object to display



### <a name="method-pRegexp"></a>pRegexp

```php
mixed ToolsCore::pRegexp($s, $delim)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2450](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2450)


#### Arguments
* $s **mixed**
* $delim **mixed**



### <a name="method-packJS"></a>packJS

```php
mixed ToolsCore::packJS($js_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1899](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1899)


#### Arguments
* $js_content **mixed**



### <a name="method-packJSinHTML"></a>packJSinHTML

```php
mixed ToolsCore::packJSinHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1881](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1881)


#### Arguments
* $html_content **mixed**



### <a name="method-packJSinHTMLpregCallback"></a>packJSinHTMLpregCallback

```php
mixed ToolsCore::packJSinHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1890](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1890)


#### Arguments
* $preg_matches **mixed**



### <a name="method-parserSQL"></a>parserSQL

```php
mixed ToolsCore::parserSQL($sql)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1906](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1906)


#### Arguments
* $sql **mixed**



### <a name="method-passwdGen"></a>passwdGen

```php
string ToolsCore::passwdGen(integer $length, string $flag)
```

Random password generator



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L44)


#### Arguments
* $length **integer** - Desired length (optional)
* $flag **string** - Output type (NUMERIC, ALPHANUMERIC, NO_NUMERIC)



### <a name="method-property_exists"></a>property_exists

```php
boolean ToolsCore::property_exists($class, string $property)
```

Function property_exists does not exist in PHP < 5.1



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2476](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2476)


#### Arguments
* $class **mixed**
* $property **string**



### <a name="method-ps_round"></a>ps_round

```php
float ToolsCore::ps_round(float $value, integer $precision)
```

returns the rounded value of $value to specified precision, according to your configuration;



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1613](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1613)


#### Arguments
* $value **float**
* $precision **integer**



### <a name="method-purifyHTML"></a>purifyHTML

```php
mixed ToolsCore::purifyHTML($html)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3252)


#### Arguments
* $html **mixed**



### <a name="method-recurseCopy"></a>recurseCopy

```php
mixed ToolsCore::recurseCopy($src, $dst, boolean $del)
```

Copy the folder $src into $dst, $dst is created if it do not exist



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2882](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2882)


#### Arguments
* $src **mixed**
* $dst **mixed**
* $del **boolean** - if true, delete the file after copy



### <a name="method-redirect"></a>redirect

```php
mixed ToolsCore::redirect(string $url, $base_uri, \Link $link, string|array $headers)
```

Redirect user to another page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L77)


#### Arguments
* $url **string** - Desired URL
* $base_uri **mixed**
* $link **[Link](class.LinkCore.md)**
* $headers **string|array** - A list of headers to send before redirection



### <a name="method-redirectAdmin"></a>redirectAdmin

```php
mixed ToolsCore::redirectAdmin(string $url)
```

Redirect user to another admin page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L143)


#### Arguments
* $url **string** - Desired URL



### <a name="method-redirectLink"></a>redirectLink

```php
mixed ToolsCore::redirectLink(string $url)
```

Redirect URLs already containing PS_BASE_URI



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L121)


#### Arguments
* $url **string** - Desired URL



### <a name="method-replaceAccentedChars"></a>replaceAccentedChars

```php
string ToolsCore::replaceAccentedChars(string $str)
```

Replace all accented chars by their equivalent non accented chars.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1200)


#### Arguments
* $str **string**



### <a name="method-replaceByAbsoluteURL"></a>replaceByAbsoluteURL

```php
mixed ToolsCore::replaceByAbsoluteURL($matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1926](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1926)


#### Arguments
* $matches **mixed**



### <a name="method-restoreCacheSettings"></a>restoreCacheSettings

```php
mixed ToolsCore::restoreCacheSettings(\Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2433)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-round_helper"></a>round_helper

```php
mixed ToolsCore::round_helper($value, $mode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1691](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1691)


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
* Source: [classes/Tools.php line 3167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3167)


#### Arguments
* $str **string**
* $str_search **string**



### <a name="method-safeOutput"></a>safeOutput

```php
string ToolsCore::safeOutput(string $string, $html)
```

Sanitize a string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L703)


#### Arguments
* $string **string** - String to sanitize
* $html **mixed**



### <a name="method-safePostVars"></a>safePostVars

```php
mixed ToolsCore::safePostVars()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 728](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L728)




### <a name="method-scandir"></a>scandir

```php
array ToolsCore::scandir($path, $ext, $dir, $recursive)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2917](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2917)


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
* Source: [classes/Tools.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L306)


#### Arguments
* $referrer **string** - URL referrer



### <a name="method-setCookieLanguage"></a>setCookieLanguage

```php
string ToolsCore::setCookieLanguage($cookie)
```

Change language in cookie while clicking on a flag



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L346)


#### Arguments
* $cookie **mixed**



### <a name="method-setCurrency"></a>setCurrency

```php
\Currency ToolsCore::setCurrency($cookie)
```

Set cookie currency from POST or default currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L447)


#### Arguments
* $cookie **mixed**



### <a name="method-simplexml_load_file"></a>simplexml_load_file

```php
mixed ToolsCore::simplexml_load_file($url, $class_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1814](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1814)


#### Arguments
* $url **mixed**
* $class_name **mixed**



### <a name="method-str2url"></a>str2url

```php
string ToolsCore::str2url(string $str)
```

Return a friendly url made from the provided string
If the mbstring library is available, the output is the same as the js function of the same name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1160)


#### Arguments
* $str **string**



### <a name="method-strReplaceFirst"></a>strReplaceFirst

```php
mixed ToolsCore::strReplaceFirst($search, $replace, $subject, $cur)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L64)


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
* Source: [classes/Tools.php line 2458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2458)


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
* Source: [classes/Tools.php line 1526](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1526)


#### Arguments
* $string **mixed**



### <a name="method-strlen"></a>strlen

```php
mixed ToolsCore::strlen($str, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1516](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1516)


#### Arguments
* $str **mixed**
* $encoding **mixed**



### <a name="method-strpos"></a>strpos

```php
mixed ToolsCore::strpos($str, $find, $offset, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1551](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1551)


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
* Source: [classes/Tools.php line 1558](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1558)


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
* Source: [classes/Tools.php line 1507](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1507)


#### Arguments
* $str **mixed**



### <a name="method-strtoupper"></a>strtoupper

```php
mixed ToolsCore::strtoupper($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1533)


#### Arguments
* $str **mixed**



### <a name="method-substr"></a>substr

```php
mixed ToolsCore::substr($str, $start, $length, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1542)


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
* Source: [classes/Tools.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L395)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-throwDeprecated"></a>throwDeprecated

```php
mixed ToolsCore::throwDeprecated($error, $message, $class)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Tools.php line 2408](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2408)


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
* Source: [classes/Tools.php line 1839](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1839)


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
* Source: [classes/Tools.php line 1853](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1853)


#### Arguments
* $string **string**



### <a name="method-truncate"></a>truncate

```php
mixed ToolsCore::truncate($str, $max_length, $suffix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1308](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1308)


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
* Source: [classes/Tools.php line 1317](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1317)


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
* Source: [classes/Tools.php line 1565](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1565)


#### Arguments
* $str **mixed**



### <a name="method-ucwords"></a>ucwords

```php
mixed ToolsCore::ucwords($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1570](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L1570)


#### Arguments
* $str **mixed**



### <a name="method-unSerialize"></a>unSerialize

```php
mixed ToolsCore::unSerialize($serialized, $object)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 3000](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3000)


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
* Source: [classes/Tools.php line 2682](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2682)


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
* Source: [classes/Tools.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L269)




### <a name="method-version_compare"></a>version_compare

```php
mixed ToolsCore::version_compare($v1, $v2, string $operator)
```

Align version sent and use internal function



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2955](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L2955)


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
* Source: [classes/Tools.php line 3142](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Tools.php#L3142)


#### Arguments
* $file_name **mixed**
* $timeout **mixed**


