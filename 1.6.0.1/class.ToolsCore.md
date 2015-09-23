Class ToolsCore
=====================





* Class name: ToolsCore
* Source: [classes/Tools.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L27)


Contents
--------


### Properties

* [$_cache_nb_media_servers](#property-$_cache_nb_media_servers)
* [$_caching](#property-$_caching)
* [$_forceCompile](#property-$_forceCompile)
* [$file_exists_cache](#property-$file_exists_cache)
* [$is_addons_up](#property-$is_addons_up)

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
* [cccCss](#method-cccCss)
* [cccJS](#method-cccJS)
* [ceilf](#method-ceilf)
* [changeFileMTime](#method-changeFileMTime)
* [checkPhpVersion](#method-checkPhpVersion)
* [cleanNonUnicodeSupport](#method-cleanNonUnicodeSupport)
* [clearCache](#method-clearCache)
* [clearSmartyCache](#method-clearSmartyCache)
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
* [displayParameterAsDeprecated](#method-displayParameterAsDeprecated)
* [displayPrice](#method-displayPrice)
* [displayPriceSmarty](#method-displayPriceSmarty)
* [enableCache](#method-enableCache)
* [encrypt](#method-encrypt)
* [fd](#method-fd)
* [fileAttachment](#method-fileAttachment)
* [file_exists_cache](#method-file_exists_cache)
* [file_get_contents](#method-file_get_contents)
* [floorf](#method-floorf)
* [generateHtaccess](#method-generateHtaccess)
* [getAdminToken](#method-getAdminToken)
* [getAdminTokenLite](#method-getAdminTokenLite)
* [getAdminTokenLiteSmarty](#method-getAdminTokenLiteSmarty)
* [getBrightness](#method-getBrightness)
* [getCurrentUrlProtocolPrefix](#method-getCurrentUrlProtocolPrefix)
* [getDefaultIndexContent](#method-getDefaultIndexContent)
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
* [minifyCSS](#method-minifyCSS)
* [minifyHTML](#method-minifyHTML)
* [minifyHTMLpregCallback](#method-minifyHTMLpregCallback)
* [modRewriteActive](#method-modRewriteActive)
* [nl2br](#method-nl2br)
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
* [redirect](#method-redirect)
* [redirectAdmin](#method-redirectAdmin)
* [redirectLink](#method-redirectLink)
* [replaceAccentedChars](#method-replaceAccentedChars)
* [replaceByAbsoluteURL](#method-replaceByAbsoluteURL)
* [restoreCacheSettings](#method-restoreCacheSettings)
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
* [strtolower](#method-strtolower)
* [strtoupper](#method-strtoupper)
* [substr](#method-substr)
* [switchLanguage](#method-switchLanguage)
* [throwDeprecated](#method-throwDeprecated)
* [toCamelCase](#method-toCamelCase)
* [toUnderscoreCase](#method-toUnderscoreCase)
* [truncate](#method-truncate)
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
* Source: [classes/Tools.php line 1636](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1636).


### <a name="property-$_caching"></a>$_caching

```php
protected mixed $_caching
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L31).


### <a name="property-$_forceCompile"></a>$_forceCompile

```php
protected mixed $_forceCompile
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L30).


### <a name="property-$file_exists_cache"></a>$file_exists_cache

```php
protected mixed $file_exists_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L29).


### <a name="property-$is_addons_up"></a>$is_addons_up

```php
protected mixed $is_addons_up = true
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 2547](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2547).


Methods
-------


### <a name="method-ZipExtract"></a>ZipExtract

```php
boolean ToolsCore::ZipExtract($from_file, $to_dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2146)


#### Arguments
* $from_file **mixed**
* $to_dir **mixed**



### <a name="method-ZipTest"></a>ZipTest

```php
boolean ToolsCore::ZipTest($from_file)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2120)


#### Arguments
* $from_file **mixed**



### <a name="method-addCSS"></a>addCSS

```php
mixed ToolsCore::addCSS($css_uri, $css_media_type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1610](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1610)


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
* Source: [classes/Tools.php line 1600](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1600)


#### Arguments
* $js_uri **mixed**



### <a name="method-addonsRequest"></a>addonsRequest

```php
mixed ToolsCore::addonsRequest($request, $params)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2548)


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
* Source: [classes/Tools.php line 2483](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2483)


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
* Source: [classes/Tools.php line 2403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2403)


#### Arguments
* $name **string** - module name



### <a name="method-argvToGET"></a>argvToGET

```php
mixed ToolsCore::argvToGET($argc, $argv)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2362](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2362)


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
* Source: [classes/Tools.php line 2527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2527)


#### Arguments
* $array **array**



### <a name="method-cccCss"></a>cccCss

```php
mixed ToolsCore::cccCss($css_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1620)


#### Arguments
* $css_files **mixed**



### <a name="method-cccJS"></a>cccJS

```php
mixed ToolsCore::cccJS($js_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1630](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1630)


#### Arguments
* $js_files **mixed**



### <a name="method-ceilf"></a>ceilf

```php
float ToolsCore::ceilf(float $value, integer $precision)
```

returns the rounded value down of $value to specified precision



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1389)


#### Arguments
* $value **float**
* $precision **integer**



### <a name="method-changeFileMTime"></a>changeFileMTime

```php
mixed ToolsCore::changeFileMTime($file_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2625)


#### Arguments
* $file_name **mixed**



### <a name="method-checkPhpVersion"></a>checkPhpVersion

```php
string ToolsCore::checkPhpVersion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2100)




### <a name="method-cleanNonUnicodeSupport"></a>cleanNonUnicodeSupport

```php
\pattern ToolsCore::cleanNonUnicodeSupport(string $pattern)
```

Delete unicode class from regular expression patterns



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2540](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2540)


#### Arguments
* $pattern **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ToolsCore::clearCache(\Smarty $smarty, $tpl, $cache_id, $compile_id)
```

Clear cache for Smarty



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2297](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2297)


#### Arguments
* $smarty **Smarty**
* $tpl **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-clearSmartyCache"></a>clearSmartyCache

```php
mixed ToolsCore::clearSmartyCache()
```

Clear smarty cache folders



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L745)




### <a name="method-completeMetaTags"></a>completeMetaTags

```php
mixed ToolsCore::completeMetaTags($meta_tags, $default_value, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 897](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L897)


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
* Source: [classes/Tools.php line 2218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2218)


#### Arguments
* $value **string** - value to convert



### <a name="method-convertPrice"></a>convertPrice

```php
mixed ToolsCore::convertPrice(float $price, object $currency, boolean $to_currency, \Context $context)
```

Return price converted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L557)


#### Arguments
* $price **float** - Product price
* $currency **object** - Current currency object
* $to_currency **boolean** - convert to currency or from currency to default currency
* $context **[Context](class.ContextCore.md)**



### <a name="method-convertPriceFull"></a>convertPriceFull

```php
mixed ToolsCore::convertPriceFull(float $amount, \Currency $currency_from, \Currency $currency_to)
```

Convert amount from a currency to an other currency automatically



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 592](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L592)


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
* Source: [classes/Tools.php line 1474](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1474)


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
* Source: [classes/Tools.php line 821](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L821)


#### Arguments
* $object **object** - Object to display
* $kill **mixed**



### <a name="method-dateDays"></a>dateDays

```php
mixed ToolsCore::dateDays()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1242)




### <a name="method-dateFormat"></a>dateFormat

```php
string ToolsCore::dateFormat(array $params, object $smarty)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L623)


#### Arguments
* $params **array** - Date, format...
* $smarty **object** - Smarty object for language preferences



### <a name="method-dateFrom"></a>dateFrom

```php
mixed ToolsCore::dateFrom($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1263)


#### Arguments
* $date **mixed**



### <a name="method-dateMonths"></a>dateMonths

```php
mixed ToolsCore::dateMonths()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1250)




### <a name="method-dateTo"></a>dateTo

```php
mixed ToolsCore::dateTo($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1271)


#### Arguments
* $date **mixed**



### <a name="method-dateYears"></a>dateYears

```php
array ToolsCore::dateYears()
```

Generate date form



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1234)




### <a name="method-debug_backtrace"></a>debug_backtrace

```php
mixed ToolsCore::debug_backtrace($start, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 826](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L826)


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
* Source: [classes/Tools.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L704)


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
* Source: [classes/Tools.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L733)


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
* Source: [classes/Tools.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L785)


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
* Source: [classes/Tools.php line 2274](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2274)


#### Arguments
* $msg **string**
* $die **boolean**



### <a name="method-display404Error"></a>display404Error

```php
mixed ToolsCore::display404Error()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2246](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2246)




### <a name="method-displayAsDeprecated"></a>displayAsDeprecated

```php
mixed ToolsCore::displayAsDeprecated($message)
```

Display a warning message indicating that the method is deprecated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1978](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1978)


#### Arguments
* $message **mixed**



### <a name="method-displayDate"></a>displayDate

```php
string ToolsCore::displayDate(string $date, integer $id_lang, boolean $full, string $separator)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 637](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L637)


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
* Source: [classes/Tools.php line 760](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L760)


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
* Source: [classes/Tools.php line 2004](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2004)




### <a name="method-displayParameterAsDeprecated"></a>displayParameterAsDeprecated

```php
mixed ToolsCore::displayParameterAsDeprecated($parameter)
```

Display a warning message indicating that the parameter is deprecated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1993](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1993)


#### Arguments
* $parameter **mixed**



### <a name="method-displayPrice"></a>displayPrice

```php
string ToolsCore::displayPrice(float $price, object $currency, $no_utf8, \Context $context)
```

Return price with currency sign for a given product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L461)


#### Arguments
* $price **float** - Product price
* $currency **object** - Current currency (object, id_currency, NULL =&gt; context currency)
* $no_utf8 **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-displayPriceSmarty"></a>displayPriceSmarty

```php
mixed ToolsCore::displayPriceSmarty($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L539)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ToolsCore::enableCache($level, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2024](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2024)


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
* Source: [classes/Tools.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L908)


#### Arguments
* $passwd **string** - String to encrypt



### <a name="method-fd"></a>fd

```php
mixed ToolsCore::fd(object $object, $type)
```

Display a var dump in firebug console



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L802)


#### Arguments
* $object **object** - Object to display
* $type **mixed**



### <a name="method-fileAttachment"></a>fileAttachment

```php
mixed ToolsCore::fileAttachment($input)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2610](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2610)


#### Arguments
* $input **mixed**



### <a name="method-file_exists_cache"></a>file_exists_cache

```php
boolean ToolsCore::file_exists_cache(string $filename)
```

file_exists() wrapper with cache to speedup performance



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1428](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1428)


#### Arguments
* $filename **string** - File name



### <a name="method-file_get_contents"></a>file_get_contents

```php
mixed ToolsCore::file_get_contents($url, $use_include_path, $stream_context, $curl_timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1435](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1435)


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
* Source: [classes/Tools.php line 1409](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1409)


#### Arguments
* $value **float**
* $precision **integer**



### <a name="method-generateHtaccess"></a>generateHtaccess

```php
mixed ToolsCore::generateHtaccess($path, $rewrite_settings, $cache_control, $specific, $disable_multiviews, $medias, $disable_modsec)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1658](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1658)


#### Arguments
* $path **mixed**
* $rewrite_settings **mixed**
* $cache_control **mixed**
* $specific **mixed**
* $disable_multiviews **mixed**
* $medias **mixed**
* $disable_modsec **mixed**



### <a name="method-getAdminToken"></a>getAdminToken

```php
mixed ToolsCore::getAdminToken(string $string)
```

Tokenize a string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L933)


#### Arguments
* $string **string** - string to encript



### <a name="method-getAdminTokenLite"></a>getAdminTokenLite

```php
mixed ToolsCore::getAdminTokenLite($tab, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 938](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L938)


#### Arguments
* $tab **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAdminTokenLiteSmarty"></a>getAdminTokenLiteSmarty

```php
mixed ToolsCore::getAdminTokenLiteSmarty($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 945](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L945)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-getBrightness"></a>getBrightness

```php
mixed ToolsCore::getBrightness($hex)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1515](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1515)


#### Arguments
* $hex **mixed**



### <a name="method-getCurrentUrlProtocolPrefix"></a>getCurrentUrlProtocolPrefix

```php
string ToolsCore::getCurrentUrlProtocolPrefix()
```

Get the current url prefix protocol (https/http)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L282)




### <a name="method-getDefaultIndexContent"></a>getDefaultIndexContent

```php
mixed ToolsCore::getDefaultIndexContent()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1897](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1897)




### <a name="method-getFullPath"></a>getFullPath

```php
mixed ToolsCore::getFullPath($id_category, $end, $type_cat, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1026](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1026)


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
* Source: [classes/Tools.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L888)


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
* Source: [classes/Tools.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L177)


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
* Source: [classes/Tools.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L322)


#### Arguments
* $key **mixed**



### <a name="method-getMaxUploadSize"></a>getMaxUploadSize

```php
integer ToolsCore::getMaxUploadSize(integer $max_size)
```

Get max file upload size considering server settings and optional max value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2381](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2381)


#### Arguments
* $max_size **integer** - optional max file size



### <a name="method-getMediaServer"></a>getMediaServer

```php
mixed ToolsCore::getMediaServer($filename)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1638)


#### Arguments
* $filename **mixed**



### <a name="method-getMemoryLimit"></a>getMemoryLimit

```php
integer ToolsCore::getMemoryLimit()
```

getMemoryLimit allow to get the memory limit in octet



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2317](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2317)




### <a name="method-getMetaTags"></a>getMetaTags

```php
mixed ToolsCore::getMetaTags($id_lang, $page_name, $title)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 879](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L879)


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
* Source: [classes/Tools.php line 2330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2330)


#### Arguments
* $option **mixed**



### <a name="method-getPath"></a>getPath

```php
mixed ToolsCore::getPath(integer $id_category, string $path, $link_on_the_item, $category_type, \Context $context)
```

Get the user's journey



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 959](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L959)


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
* Source: [classes/Tools.php line 2178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2178)


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
* Source: [classes/Tools.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L163)


#### Arguments
* $use_ssl **boolean** - true if require ssl



### <a name="method-getRemoteAddr"></a>getRemoteAddr

```php
string ToolsCore::getRemoteAddr()
```

Get the server variable REMOTE_ADDR, or the first ip of HTTP_X_FORWARDED_FOR (when using proxy)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L242)




### <a name="method-getSafeModeStatus"></a>getSafeModeStatus

```php
mixed ToolsCore::getSafeModeStatus()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2135)




### <a name="method-getServerName"></a>getServerName

```php
string ToolsCore::getServerName()
```

Get the server variable SERVER_NAME



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L230)




### <a name="method-getShopDomain"></a>getShopDomain

```php
string ToolsCore::getShopDomain(boolean $http, boolean $entities)
```

getShopDomain returns domain name according to configuration and ignoring ssl



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L196)


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
* Source: [classes/Tools.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L214)


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
* Source: [classes/Tools.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L151)




### <a name="method-getToken"></a>getToken

```php
mixed ToolsCore::getToken($page, \Context $context)
```

Get token to prevent CSRF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 918](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L918)


#### Arguments
* $page **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getValue"></a>getValue

```php
mixed ToolsCore::getValue(string $key, mixed $default_value)
```

Get a value from $_POST / $_GET
if unavailable, take a default value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L311)


#### Arguments
* $key **string** - Value key
* $default_value **mixed** - (optional)



### <a name="method-hourGenerate"></a>hourGenerate

```php
mixed ToolsCore::hourGenerate($hours, $minutes, $seconds)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1258)


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
* Source: [classes/Tools.php line 682](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L682)


#### Arguments
* $string **mixed**



### <a name="method-htmlentitiesUTF8"></a>htmlentitiesUTF8

```php
mixed ToolsCore::htmlentitiesUTF8($string, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L672)


#### Arguments
* $string **mixed**
* $type **mixed**



### <a name="method-iconv"></a>iconv

```php
mixed ToolsCore::iconv($from, $to, $string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1347)


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
* Source: [classes/Tools.php line 2051](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2051)


#### Arguments
* $function **mixed**



### <a name="method-isEmpty"></a>isEmpty

```php
mixed ToolsCore::isEmpty($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1354](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1354)


#### Arguments
* $field **mixed**



### <a name="method-isPHPCLI"></a>isPHPCLI

```php
boolean ToolsCore::isPHPCLI()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2357](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2357)




### <a name="method-isSubmit"></a>isSubmit

```php
mixed ToolsCore::isSubmit(string $submit)
```

Check if submit has been posted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L868)


#### Arguments
* $submit **string** - submit name



### <a name="method-isX86_64arch"></a>isX86_64arch

```php
boolean ToolsCore::isX86_64arch()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2348](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2348)




### <a name="method-jsonDecode"></a>jsonDecode

```php
array ToolsCore::jsonDecode(string $json, boolean $assoc)
```

jsonDecode convert json string to php array / object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1945](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1945)


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
* Source: [classes/Tools.php line 1963](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1963)


#### Arguments
* $data **array**



### <a name="method-link_rewrite"></a>link_rewrite

```php
string ToolsCore::link_rewrite(string $str, boolean $utf8_decode)
```

Return the friendly url from the provided string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1058](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1058)


#### Arguments
* $str **string**
* $utf8_decode **boolean** - (deprecated)



### <a name="method-minifyCSS"></a>minifyCSS

```php
mixed ToolsCore::minifyCSS($css_content, $fileuri)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1575)


#### Arguments
* $css_content **mixed**
* $fileuri **mixed**



### <a name="method-minifyHTML"></a>minifyHTML

```php
mixed ToolsCore::minifyHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1484](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1484)


#### Arguments
* $html_content **mixed**



### <a name="method-minifyHTMLpregCallback"></a>minifyHTMLpregCallback

```php
mixed ToolsCore::minifyHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1527)


#### Arguments
* $preg_matches **mixed**



### <a name="method-modRewriteActive"></a>modRewriteActive

```php
mixed ToolsCore::modRewriteActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2505](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2505)




### <a name="method-nl2br"></a>nl2br

```php
string ToolsCore::nl2br($str)
```

Convert \n and \r\n and \r to <br />



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2287)


#### Arguments
* $str **mixed**



### <a name="method-orderbyPrice"></a>orderbyPrice

```php
mixed ToolsCore::orderbyPrice($array, $order_way)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1335](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1335)


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
* Source: [classes/Tools.php line 858](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L858)


#### Arguments
* $object **object** - Object to display



### <a name="method-pRegexp"></a>pRegexp

```php
mixed ToolsCore::pRegexp($s, $delim)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2057](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2057)


#### Arguments
* $s **mixed**
* $delim **mixed**



### <a name="method-packJS"></a>packJS

```php
mixed ToolsCore::packJS($js_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1554](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1554)


#### Arguments
* $js_content **mixed**



### <a name="method-packJSinHTML"></a>packJSinHTML

```php
mixed ToolsCore::packJSinHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1536](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1536)


#### Arguments
* $html_content **mixed**



### <a name="method-packJSinHTMLpregCallback"></a>packJSinHTMLpregCallback

```php
mixed ToolsCore::packJSinHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1545](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1545)


#### Arguments
* $preg_matches **mixed**



### <a name="method-parserSQL"></a>parserSQL

```php
mixed ToolsCore::parserSQL($sql)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1561](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1561)


#### Arguments
* $sql **mixed**



### <a name="method-passwdGen"></a>passwdGen

```php
string ToolsCore::passwdGen(integer $length, string $flag)
```

Random password generator



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L40)


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
* Source: [classes/Tools.php line 2081](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2081)


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
* Source: [classes/Tools.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1368)


#### Arguments
* $value **float**
* $precision **integer**



### <a name="method-redirect"></a>redirect

```php
mixed ToolsCore::redirect(string $url, $base_uri, \Link $link, string|array $headers)
```

Redirect user to another page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L73)


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
* Source: [classes/Tools.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L139)


#### Arguments
* $url **string** - Desired URL



### <a name="method-redirectLink"></a>redirectLink

```php
mixed ToolsCore::redirectLink(string $url)
```

Redirect URLs already containing PS_BASE_URI



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L117)


#### Arguments
* $url **string** - Desired URL



### <a name="method-replaceAccentedChars"></a>replaceAccentedChars

```php
string ToolsCore::replaceAccentedChars(string $str)
```

Replace all accented chars by their equivalent non accented chars.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1109)


#### Arguments
* $str **string**



### <a name="method-replaceByAbsoluteURL"></a>replaceByAbsoluteURL

```php
mixed ToolsCore::replaceByAbsoluteURL($matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1581](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1581)


#### Arguments
* $matches **mixed**



### <a name="method-restoreCacheSettings"></a>restoreCacheSettings

```php
mixed ToolsCore::restoreCacheSettings(\Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2040](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2040)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-safeOutput"></a>safeOutput

```php
string ToolsCore::safeOutput(string $string, $html)
```

Sanitize a string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 665](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L665)


#### Arguments
* $string **string** - String to sanitize
* $html **mixed**



### <a name="method-safePostVars"></a>safePostVars

```php
mixed ToolsCore::safePostVars()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 692](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L692)




### <a name="method-scandir"></a>scandir

```php
array ToolsCore::scandir($path, $ext, $dir, $recursive)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2431](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2431)


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
* Source: [classes/Tools.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L296)


#### Arguments
* $referrer **string** - URL referrer



### <a name="method-setCookieLanguage"></a>setCookieLanguage

```php
string ToolsCore::setCookieLanguage($cookie)
```

Change language in cookie while clicking on a flag



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L334)


#### Arguments
* $cookie **mixed**



### <a name="method-setCurrency"></a>setCurrency

```php
\Currency ToolsCore::setCurrency($cookie)
```

Set cookie currency from POST or default currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L420)


#### Arguments
* $cookie **mixed**



### <a name="method-simplexml_load_file"></a>simplexml_load_file

```php
mixed ToolsCore::simplexml_load_file($url, $class_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1469)


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
* Source: [classes/Tools.php line 1072](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1072)


#### Arguments
* $str **string**



### <a name="method-strReplaceFirst"></a>strReplaceFirst

```php
mixed ToolsCore::strReplaceFirst($search, $replace, $subject, $cur)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L60)


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
* Source: [classes/Tools.php line 2065](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2065)


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
* Source: [classes/Tools.php line 1298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1298)


#### Arguments
* $string **mixed**



### <a name="method-strlen"></a>strlen

```php
mixed ToolsCore::strlen($str, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1288](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1288)


#### Arguments
* $str **mixed**
* $encoding **mixed**



### <a name="method-strtolower"></a>strtolower

```php
mixed ToolsCore::strtolower($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1279)


#### Arguments
* $str **mixed**



### <a name="method-strtoupper"></a>strtoupper

```php
mixed ToolsCore::strtoupper($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1305)


#### Arguments
* $str **mixed**



### <a name="method-substr"></a>substr

```php
mixed ToolsCore::substr($str, $start, $length, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1314](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1314)


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
* Source: [classes/Tools.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L384)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-throwDeprecated"></a>throwDeprecated

```php
mixed ToolsCore::throwDeprecated($error, $message, $class)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Tools.php line 2015](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2015)


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
* Source: [classes/Tools.php line 1494](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1494)


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
* Source: [classes/Tools.php line 1508](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1508)


#### Arguments
* $string **string**



### <a name="method-truncate"></a>truncate

```php
mixed ToolsCore::truncate($str, $max_length, $suffix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1217)


#### Arguments
* $str **mixed**
* $max_length **mixed**
* $suffix **mixed**



### <a name="method-ucfirst"></a>ucfirst

```php
mixed ToolsCore::ucfirst($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1323)


#### Arguments
* $str **mixed**



### <a name="method-ucwords"></a>ucwords

```php
mixed ToolsCore::ucwords($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1328](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L1328)


#### Arguments
* $str **mixed**



### <a name="method-unSerialize"></a>unSerialize

```php
mixed ToolsCore::unSerialize($serialized, $object)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2514](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2514)


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
* Source: [classes/Tools.php line 2262](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2262)


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
* Source: [classes/Tools.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L263)




### <a name="method-version_compare"></a>version_compare

```php
mixed ToolsCore::version_compare($v1, $v2, string $operator)
```

Align version sent and use internal function



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2469)


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
* Source: [classes/Tools.php line 2630](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Tools.php#L2630)


#### Arguments
* $file_name **mixed**
* $timeout **mixed**


