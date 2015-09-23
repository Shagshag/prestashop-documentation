Class ToolsCore
=====================





* Class name: ToolsCore
* Source: [classes/Tools.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L28)


Contents
--------


### Properties

* [$_cache_nb_media_servers](#property-$_cache_nb_media_servers)
* [$_caching](#property-$_caching)
* [$_forceCompile](#property-$_forceCompile)
* [$a](#property-$a)
* [$file_exists_cache](#property-$file_exists_cache)

### Methods

* [ZipExtract](#method-ZipExtract)
* [ZipTest](#method-ZipTest)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [apacheModExists](#method-apacheModExists)
* [cccCss](#method-cccCss)
* [cccJS](#method-cccJS)
* [ceilf](#method-ceilf)
* [checkPhpVersion](#method-checkPhpVersion)
* [clearCache](#method-clearCache)
* [completeMetaTags](#method-completeMetaTags)
* [convertBytes](#method-convertBytes)
* [convertPrice](#method-convertPrice)
* [convertPriceFull](#method-convertPriceFull)
* [d](#method-d)
* [dateDays](#method-dateDays)
* [dateFormat](#method-dateFormat)
* [dateFrom](#method-dateFrom)
* [dateMonths](#method-dateMonths)
* [dateTo](#method-dateTo)
* [dateYears](#method-dateYears)
* [deleteDirectory](#method-deleteDirectory)
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
* [file_exists_cache](#method-file_exists_cache)
* [file_get_contents](#method-file_get_contents)
* [floorf](#method-floorf)
* [generateHtaccess](#method-generateHtaccess)
* [getAdminToken](#method-getAdminToken)
* [getAdminTokenLite](#method-getAdminTokenLite)
* [getAdminTokenLiteSmarty](#method-getAdminTokenLiteSmarty)
* [getBrightness](#method-getBrightness)
* [getCurrentUrlProtocolPrefix](#method-getCurrentUrlProtocolPrefix)
* [getFullPath](#method-getFullPath)
* [getHomeMetaTags](#method-getHomeMetaTags)
* [getHttpHost](#method-getHttpHost)
* [getIsset](#method-getIsset)
* [getMaxUploadSize](#method-getMaxUploadSize)
* [getMediaServer](#method-getMediaServer)
* [getMemoryLimit](#method-getMemoryLimit)
* [getMetaTags](#method-getMetaTags)
* [getPath](#method-getPath)
* [getProductsOrder](#method-getProductsOrder)
* [getProtocol](#method-getProtocol)
* [getRemoteAddr](#method-getRemoteAddr)
* [getServerName](#method-getServerName)
* [getShopDomain](#method-getShopDomain)
* [getShopDomainSsl](#method-getShopDomainSsl)
* [getToken](#method-getToken)
* [getValue](#method-getValue)
* [hourGenerate](#method-hourGenerate)
* [htmlentitiesDecodeUTF8](#method-htmlentitiesDecodeUTF8)
* [htmlentitiesUTF8](#method-htmlentitiesUTF8)
* [iconv](#method-iconv)
* [isCallable](#method-isCallable)
* [isEmpty](#method-isEmpty)
* [isSubmit](#method-isSubmit)
* [isX86_64arch](#method-isX86_64arch)
* [jsonDecode](#method-jsonDecode)
* [jsonEncode](#method-jsonEncode)
* [link_rewrite](#method-link_rewrite)
* [minifyCSS](#method-minifyCSS)
* [minifyHTML](#method-minifyHTML)
* [minifyHTMLpregCallback](#method-minifyHTMLpregCallback)
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
* [url](#method-url)
* [usingSecureMode](#method-usingSecureMode)




Properties
----------


### <a name="property-$_cache_nb_media_servers"></a>$_cache_nb_media_servers

```php
private mixed $_cache_nb_media_servers = null
```





* Visibility: **private**
* This property is **static**.
* Source: [classes/Tools.php line 1437](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1437).


### <a name="property-$_caching"></a>$_caching

```php
protected mixed $_caching
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L32).


### <a name="property-$_forceCompile"></a>$_forceCompile

```php
protected mixed $_forceCompile
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L31).


### <a name="property-$a"></a>$a

```php
public mixed $a
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Tools.php line 1273](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1273).


### <a name="property-$file_exists_cache"></a>$file_exists_cache

```php
protected mixed $file_exists_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tools.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L30).


Methods
-------


### <a name="method-ZipExtract"></a>ZipExtract

```php
boolean ToolsCore::ZipExtract($fromFile, $toDir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1803](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1803)


#### Arguments
* $fromFile **mixed**
* $toDir **mixed**



### <a name="method-ZipTest"></a>ZipTest

```php
boolean ToolsCore::ZipTest($fromFile)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1784](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1784)


#### Arguments
* $fromFile **mixed**



### <a name="method-addCSS"></a>addCSS

```php
true ToolsCore::addCSS(mixed $css_uri, string $css_media_type)
```

addCSS allows you to add stylesheet at any time.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1411](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1411)


#### Arguments
* $css_uri **mixed**
* $css_media_type **string**



### <a name="method-addJS"></a>addJS

```php
void ToolsCore::addJS(mixed $js_uri)
```

addJS load a javascript file in the header



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1396](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1396)


#### Arguments
* $js_uri **mixed**



### <a name="method-apacheModExists"></a>apacheModExists

```php
boolean ToolsCore::apacheModExists(string $name)
```

apacheModExists return true if the apache module $name is loaded



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 2008](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L2008)


#### Arguments
* $name **string** - module name



### <a name="method-cccCss"></a>cccCss

```php
mixed ToolsCore::cccCss($css_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1421](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1421)


#### Arguments
* $css_files **mixed**



### <a name="method-cccJS"></a>cccJS

```php
mixed ToolsCore::cccJS($js_files)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1431](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1431)


#### Arguments
* $js_files **mixed**



### <a name="method-ceilf"></a>ceilf

```php
mixed ToolsCore::ceilf($value, $precision)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1203](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1203)


#### Arguments
* $value **mixed**
* $precision **mixed**



### <a name="method-checkPhpVersion"></a>checkPhpVersion

```php
string ToolsCore::checkPhpVersion()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1764](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1764)




### <a name="method-clearCache"></a>clearCache

```php
mixed ToolsCore::clearCache(\objet $smarty)
```

Clear cache for Smarty



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1947](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1947)


#### Arguments
* $smarty **objet**



### <a name="method-completeMetaTags"></a>completeMetaTags

```php
mixed ToolsCore::completeMetaTags($metaTags, $defaultValue, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L823)


#### Arguments
* $metaTags **mixed**
* $defaultValue **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-convertBytes"></a>convertBytes

```php
integer ToolsCore::convertBytes(string $value)
```

Convert a shorthand byte value from a PHP configuration directive to an integer value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1869](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1869)


#### Arguments
* $value **string** - value to convert



### <a name="method-convertPrice"></a>convertPrice

```php
mixed ToolsCore::convertPrice(float $price, object $currency, boolean $to_currency, \Context $context)
```

Return price converted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L443)


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
* Source: [classes/Tools.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L473)


#### Arguments
* $amount **float**
* $currency_from **[Currency](class.CurrencyCore.md)** - if null we used the default currency
* $currency_to **[Currency](class.CurrencyCore.md)** - if null we used the default currency



### <a name="method-d"></a>d

```php
mixed ToolsCore::d(object $object, $kill)
```

ALIAS OF dieObject() - Display an error with detailed object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L649)


#### Arguments
* $object **object** - Object to display
* $kill **mixed**



### <a name="method-dateDays"></a>dateDays

```php
mixed ToolsCore::dateDays()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1085](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1085)




### <a name="method-dateFormat"></a>dateFormat

```php
string ToolsCore::dateFormat(array $params, object $smarty)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 512](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L512)


#### Arguments
* $params **array** - Date, format...
* $smarty **object** - Smarty object for language preferences



### <a name="method-dateFrom"></a>dateFrom

```php
mixed ToolsCore::dateFrom($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1104)


#### Arguments
* $date **mixed**



### <a name="method-dateMonths"></a>dateMonths

```php
mixed ToolsCore::dateMonths()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1092](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1092)




### <a name="method-dateTo"></a>dateTo

```php
mixed ToolsCore::dateTo($date)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1112)


#### Arguments
* $date **mixed**



### <a name="method-dateYears"></a>dateYears

```php
array ToolsCore::dateYears()
```

Generate date form



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1078](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1078)




### <a name="method-deleteDirectory"></a>deleteDirectory

```php
mixed ToolsCore::deleteDirectory(string $dirname, $delete_self)
```

Delete directory and subdirectories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L576)


#### Arguments
* $dirname **string** - Directory name
* $delete_self **mixed**



### <a name="method-dieObject"></a>dieObject

```php
\$object ToolsCore::dieObject(mixed $object, boolean $kill)
```

Display an error with detailed object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 620](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L620)


#### Arguments
* $object **mixed**
* $kill **boolean**



### <a name="method-dieOrLog"></a>dieOrLog

```php
\success ToolsCore::dieOrLog(string $msg, boolean $die)
```

Display error and dies or silently log the error.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1924](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1924)


#### Arguments
* $msg **string**
* $die **boolean**



### <a name="method-display404Error"></a>display404Error

```php
mixed ToolsCore::display404Error()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1896](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1896)




### <a name="method-displayAsDeprecated"></a>displayAsDeprecated

```php
mixed ToolsCore::displayAsDeprecated($message)
```

Display a warning message indicating that the method is deprecated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1636](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1636)


#### Arguments
* $message **mixed**



### <a name="method-displayDate"></a>displayDate

```php
string ToolsCore::displayDate(string $date, integer $id_lang, boolean $full, string $separator)
```

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L526)


#### Arguments
* $date **string** - Date to display format UNIX
* $id_lang **integer** - Language id
* $full **boolean** - With time or not (optional)
* $separator **string** - DEPRECATED



### <a name="method-displayError"></a>displayError

```php
mixed ToolsCore::displayError(string $string, boolean $htmlentities, \Context $context)
```

Display an error according to an error code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L598)


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
* Source: [classes/Tools.php line 1668](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1668)




### <a name="method-displayParameterAsDeprecated"></a>displayParameterAsDeprecated

```php
mixed ToolsCore::displayParameterAsDeprecated($parameter)
```

Display a warning message indicating that the parameter is deprecated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1657](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1657)


#### Arguments
* $parameter **mixed**



### <a name="method-displayPrice"></a>displayPrice

```php
string ToolsCore::displayPrice(float $price, object $currency, $no_utf8, \Context $context)
```

Return price with currency sign for a given product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L379)


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
* Source: [classes/Tools.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L425)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ToolsCore::enableCache($level, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1688](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1688)


#### Arguments
* $level **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-encrypt"></a>encrypt

```php
mixed ToolsCore::encrypt($passwd)
```

Encrypt password



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 842](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L842)


#### Arguments
* $passwd **mixed**



### <a name="method-fd"></a>fd

```php
mixed ToolsCore::fd(object $object)
```

Display a var dump in firebug console



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 635](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L635)


#### Arguments
* $object **object** - Object to display



### <a name="method-file_exists_cache"></a>file_exists_cache

```php
boolean ToolsCore::file_exists_cache(string $filename)
```

file_exists() wrapper with cache to speedup performance



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1235](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1235)


#### Arguments
* $filename **string** - File name



### <a name="method-file_get_contents"></a>file_get_contents

```php
mixed ToolsCore::file_get_contents($url, $useIncludePath, $streamContext, $curlTimeOut)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1242](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1242)


#### Arguments
* $url **mixed**
* $useIncludePath **mixed**
* $streamContext **mixed**
* $curlTimeOut **mixed**



### <a name="method-floorf"></a>floorf

```php
mixed ToolsCore::floorf($value, $precision)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1216)


#### Arguments
* $value **mixed**
* $precision **mixed**



### <a name="method-generateHtaccess"></a>generateHtaccess

```php
mixed ToolsCore::generateHtaccess($path, $rewrite_settings, $cache_control, $specific, $disable_multiviews)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1458](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1458)


#### Arguments
* $path **mixed**
* $rewrite_settings **mixed**
* $cache_control **mixed**
* $specific **mixed**
* $disable_multiviews **mixed**



### <a name="method-getAdminToken"></a>getAdminToken

```php
mixed ToolsCore::getAdminToken($string)
```

Encrypt password



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 867](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L867)


#### Arguments
* $string **mixed**



### <a name="method-getAdminTokenLite"></a>getAdminTokenLite

```php
mixed ToolsCore::getAdminTokenLite($tab, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 872](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L872)


#### Arguments
* $tab **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAdminTokenLiteSmarty"></a>getAdminTokenLiteSmarty

```php
mixed ToolsCore::getAdminTokenLiteSmarty($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 879](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L879)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-getBrightness"></a>getBrightness

```php
mixed ToolsCore::getBrightness($hex)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1309](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1309)


#### Arguments
* $hex **mixed**



### <a name="method-getCurrentUrlProtocolPrefix"></a>getCurrentUrlProtocolPrefix

```php
string ToolsCore::getCurrentUrlProtocolPrefix()
```

Get the current url prefix protocol (https/http)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L241)




### <a name="method-getFullPath"></a>getFullPath

```php
mixed ToolsCore::getFullPath($id_category, $end, $type_cat, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L958)


#### Arguments
* $id_category **mixed**
* $end **mixed**
* $type_cat **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getHomeMetaTags"></a>getHomeMetaTags

```php
array ToolsCore::getHomeMetaTags(integer $id_lang, $page_name)
```

Get meta tags for a given page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L812)


#### Arguments
* $id_lang **integer** - Language id
* $page_name **mixed**



### <a name="method-getHttpHost"></a>getHttpHost

```php
string ToolsCore::getHttpHost(boolean $http, boolean $entities)
```

getHttpHost return the <b>current</b> host used, with the protocol (http or https) if $http is true
This function should not be used to choose http or https domain name.

Use Tools::getShopDomain() or Tools::getShopDomainSsl instead

* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L141)


#### Arguments
* $http **boolean**
* $entities **boolean**



### <a name="method-getIsset"></a>getIsset

```php
mixed ToolsCore::getIsset($key)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L281)


#### Arguments
* $key **mixed**



### <a name="method-getMaxUploadSize"></a>getMaxUploadSize

```php
integer ToolsCore::getMaxUploadSize(integer $max_size)
```

Get max file upload size considering server settings and optional max value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1989](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1989)


#### Arguments
* $max_size **integer** - optional max file size



### <a name="method-getMediaServer"></a>getMediaServer

```php
mixed ToolsCore::getMediaServer($filename)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1439](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1439)


#### Arguments
* $filename **mixed**



### <a name="method-getMemoryLimit"></a>getMemoryLimit

```php
integer ToolsCore::getMemoryLimit()
```

getMemoryLimit allow to get the memory limit in octet



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1958](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1958)




### <a name="method-getMetaTags"></a>getMetaTags

```php
array ToolsCore::getMetaTags(integer $id_lang, $page_name, $title)
```

Get meta tages for a given page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L683)


#### Arguments
* $id_lang **integer** - Language id
* $page_name **mixed**
* $title **mixed**



### <a name="method-getPath"></a>getPath

```php
mixed ToolsCore::getPath(integer $id_category, string $path, boolean $linkOntheLastItem, $categoryType, \Context $context)
```

Get the user's journey



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 893](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L893)


#### Arguments
* $id_category **integer** - Category ID
* $path **string** - Path end
* $linkOntheLastItem **boolean** - Put or not a link on the current category
* $categoryType **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductsOrder"></a>getProductsOrder

```php
mixed ToolsCore::getProductsOrder(string $type, string $value, $prefix)
```

Get products order field name for queries.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1832](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1832)


#### Arguments
* $type **string** - by|way
* $value **string** - If no index given, use default order from admin -&gt; pref -&gt; products
* $prefix **mixed**



### <a name="method-getProtocol"></a>getProtocol

```php
String ToolsCore::getProtocol($use_ssl)
```

getProtocol return the set protocol according to configuration (http[s])



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L127)


#### Arguments
* $use_ssl **mixed**



### <a name="method-getRemoteAddr"></a>getRemoteAddr

```php
string ToolsCore::getRemoteAddr()
```

Get the server variable REMOTE_ADDR, or the first ip of HTTP_X_FORWARDED_FOR (when using proxy)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L204)




### <a name="method-getServerName"></a>getServerName

```php
string ToolsCore::getServerName()
```

Get the server variable SERVER_NAME



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L192)




### <a name="method-getShopDomain"></a>getShopDomain

```php
string ToolsCore::getShopDomain(boolean $http, boolean $entities)
```

getShopDomain returns domain name according to configuration and ignoring ssl



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L158)


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
* Source: [classes/Tools.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L176)


#### Arguments
* $http **boolean** - if true, return domain name with protocol
* $entities **boolean** - if true,



### <a name="method-getToken"></a>getToken

```php
mixed ToolsCore::getToken($page, \Context $context)
```

Get token to prevent CSRF



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L852)


#### Arguments
* $page **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getValue"></a>getValue

```php
mixed ToolsCore::getValue(string $key, mixed $defaultValue)
```

Get a value from $_POST / $_GET
if unavailable, take a default value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L270)


#### Arguments
* $key **string** - Value key
* $defaultValue **mixed** - (optional)



### <a name="method-hourGenerate"></a>hourGenerate

```php
mixed ToolsCore::hourGenerate($hours, $minutes, $seconds)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1099)


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
* Source: [classes/Tools.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L559)


#### Arguments
* $string **mixed**



### <a name="method-htmlentitiesUTF8"></a>htmlentitiesUTF8

```php
mixed ToolsCore::htmlentitiesUTF8($string, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L552)


#### Arguments
* $string **mixed**
* $type **mixed**



### <a name="method-iconv"></a>iconv

```php
mixed ToolsCore::iconv($from, $to, $string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1181)


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
* Source: [classes/Tools.php line 1714](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1714)


#### Arguments
* $function **mixed**



### <a name="method-isEmpty"></a>isEmpty

```php
mixed ToolsCore::isEmpty($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1188](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1188)


#### Arguments
* $field **mixed**



### <a name="method-isSubmit"></a>isSubmit

```php
mixed ToolsCore::isSubmit(string $submit)
```

Check if submit has been posted



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L669)


#### Arguments
* $submit **string** - submit name



### <a name="method-isX86_64arch"></a>isX86_64arch

```php
boolean ToolsCore::isX86_64arch()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1978](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1978)




### <a name="method-jsonDecode"></a>jsonDecode

```php
array ToolsCore::jsonDecode(string $json, boolean $assoc)
```

jsonDecode convert json string to php array / object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1603](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1603)


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
* Source: [classes/Tools.php line 1621](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1621)


#### Arguments
* $data **array**



### <a name="method-link_rewrite"></a>link_rewrite

```php
string ToolsCore::link_rewrite(string $str, boolean $utf8_decode)
```

Return the friendly url from the provided string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L990)


#### Arguments
* $str **string**
* $utf8_decode **boolean** - =&gt; needs to be marked as deprecated



### <a name="method-minifyCSS"></a>minifyCSS

```php
mixed ToolsCore::minifyCSS($css_content, $fileuri)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1369](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1369)


#### Arguments
* $css_content **mixed**
* $fileuri **mixed**



### <a name="method-minifyHTML"></a>minifyHTML

```php
mixed ToolsCore::minifyHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1278](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1278)


#### Arguments
* $html_content **mixed**



### <a name="method-minifyHTMLpregCallback"></a>minifyHTMLpregCallback

```php
mixed ToolsCore::minifyHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1321](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1321)


#### Arguments
* $preg_matches **mixed**



### <a name="method-nl2br"></a>nl2br

```php
string ToolsCore::nl2br($str)
```

Convert \n and \r\n and \r to <br />



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1937](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1937)


#### Arguments
* $str **mixed**



### <a name="method-orderbyPrice"></a>orderbyPrice

```php
mixed ToolsCore::orderbyPrice($array, $orderWay)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1169](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1169)


#### Arguments
* $array **mixed**
* $orderWay **mixed**



### <a name="method-p"></a>p

```php
mixed ToolsCore::p(object $object)
```

ALIAS OF dieObject() - Display an error with detailed object but don't stop the execution



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 659](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L659)


#### Arguments
* $object **object** - Object to display



### <a name="method-pRegexp"></a>pRegexp

```php
mixed ToolsCore::pRegexp($s, $delim)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1720](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1720)


#### Arguments
* $s **mixed**
* $delim **mixed**



### <a name="method-packJS"></a>packJS

```php
mixed ToolsCore::packJS($js_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1348](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1348)


#### Arguments
* $js_content **mixed**



### <a name="method-packJSinHTML"></a>packJSinHTML

```php
mixed ToolsCore::packJSinHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1330](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1330)


#### Arguments
* $html_content **mixed**



### <a name="method-packJSinHTMLpregCallback"></a>packJSinHTMLpregCallback

```php
mixed ToolsCore::packJSinHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1339](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1339)


#### Arguments
* $preg_matches **mixed**



### <a name="method-parserSQL"></a>parserSQL

```php
mixed ToolsCore::parserSQL($sql)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1355)


#### Arguments
* $sql **mixed**



### <a name="method-passwdGen"></a>passwdGen

```php
string ToolsCore::passwdGen(integer $length)
```

Random password generator



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L40)


#### Arguments
* $length **integer** - Desired length (optional)



### <a name="method-property_exists"></a>property_exists

```php
boolean ToolsCore::property_exists($class, string $property)
```

Function property_exists does not exist in PHP < 5.1



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1745](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1745)


#### Arguments
* $class **mixed**
* $property **string**



### <a name="method-ps_round"></a>ps_round

```php
mixed ToolsCore::ps_round($value, $precision)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1193](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1193)


#### Arguments
* $value **mixed**
* $precision **mixed**



### <a name="method-redirect"></a>redirect

```php
mixed ToolsCore::redirect(string $url, string $baseUri, \Link $link)
```

Redirect user to another page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L58)


#### Arguments
* $url **string** - Desired URL
* $baseUri **string** - Base URI (optional)
* $link **[Link](class.LinkCore.md)**



### <a name="method-redirectAdmin"></a>redirectAdmin

```php
mixed ToolsCore::redirectAdmin(string $url)
```

Redirect user to another admin page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L116)


#### Arguments
* $url **string** - Desired URL



### <a name="method-redirectLink"></a>redirectLink

```php
mixed ToolsCore::redirectLink(string $url)
```

Redirect url wich allready PS_BASE_URI



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L94)


#### Arguments
* $url **string** - Desired URL



### <a name="method-replaceAccentedChars"></a>replaceAccentedChars

```php
string ToolsCore::replaceAccentedChars(string $str)
```

Replace all accented chars by their equivalent non accented chars.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1029](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1029)


#### Arguments
* $str **string**



### <a name="method-replaceByAbsoluteURL"></a>replaceByAbsoluteURL

```php
mixed ToolsCore::replaceByAbsoluteURL($matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1375](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1375)


#### Arguments
* $matches **mixed**



### <a name="method-restoreCacheSettings"></a>restoreCacheSettings

```php
mixed ToolsCore::restoreCacheSettings(\Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1703](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1703)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-safeOutput"></a>safeOutput

```php
string ToolsCore::safeOutput(string $string, $html)
```

Sanitize a string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L545)


#### Arguments
* $string **string** - String to sanitize
* $html **mixed**



### <a name="method-safePostVars"></a>safePostVars

```php
mixed ToolsCore::safePostVars()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L566)




### <a name="method-secureReferrer"></a>secureReferrer

```php
\secured ToolsCore::secureReferrer(string $referrer)
```

Secure an URL referrer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L255)


#### Arguments
* $referrer **string** - URL referrer



### <a name="method-setCookieLanguage"></a>setCookieLanguage

```php
string ToolsCore::setCookieLanguage($cookie)
```

Change language in cookie while clicking on a flag



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L293)


#### Arguments
* $cookie **mixed**



### <a name="method-setCurrency"></a>setCurrency

```php
\Currency ToolsCore::setCurrency($cookie)
```

Set cookie currency from POST or default currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L350)


#### Arguments
* $cookie **mixed**



### <a name="method-simplexml_load_file"></a>simplexml_load_file

```php
mixed ToolsCore::simplexml_load_file($url, $class_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1264](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1264)


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
* Source: [classes/Tools.php line 1002](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1002)


#### Arguments
* $str **string**



### <a name="method-strReplaceFirst"></a>strReplaceFirst

```php
mixed ToolsCore::strReplaceFirst($search, $replace, $subject, $cur)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L48)


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
* Source: [classes/Tools.php line 1728](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1728)


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
* Source: [classes/Tools.php line 1139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1139)


#### Arguments
* $string **mixed**



### <a name="method-strlen"></a>strlen

```php
mixed ToolsCore::strlen($str, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1129)


#### Arguments
* $str **mixed**
* $encoding **mixed**



### <a name="method-strtolower"></a>strtolower

```php
mixed ToolsCore::strtolower($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1120)


#### Arguments
* $str **mixed**



### <a name="method-strtoupper"></a>strtoupper

```php
mixed ToolsCore::strtoupper($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1146)


#### Arguments
* $str **mixed**



### <a name="method-substr"></a>substr

```php
mixed ToolsCore::substr($str, $start, $length, $encoding)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1155)


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
* Source: [classes/Tools.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L337)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-throwDeprecated"></a>throwDeprecated

```php
mixed ToolsCore::throwDeprecated($error, $message, $class)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Tools.php line 1679](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1679)


#### Arguments
* $error **mixed**
* $message **mixed**
* $class **mixed**



### <a name="method-toCamelCase"></a>toCamelCase

```php
mixed ToolsCore::toCamelCase($str, $capitaliseFirstChar)
```

Translates a string with underscores into camel case (e.g. first_name -> firstName)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1288](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1288)


#### Arguments
* $str **mixed**
* $capitaliseFirstChar **mixed**



### <a name="method-toUnderscoreCase"></a>toUnderscoreCase

```php
string ToolsCore::toUnderscoreCase(string $string)
```

Transform a CamelCase string to underscore_case string



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1302](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1302)


#### Arguments
* $string **string**



### <a name="method-truncate"></a>truncate

```php
mixed ToolsCore::truncate($str, $maxLen, $suffix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1061](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1061)


#### Arguments
* $str **mixed**
* $maxLen **mixed**
* $suffix **mixed**



### <a name="method-ucfirst"></a>ucfirst

```php
mixed ToolsCore::ucfirst($str)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1164)


#### Arguments
* $str **mixed**



### <a name="method-url"></a>url

```php
string ToolsCore::url(string $begin, string $end)
```

Concat $begin and $end, add ? or & between strings



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tools.php line 1912](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L1912)


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
* Source: [classes/Tools.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Tools.php#L225)



