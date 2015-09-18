ToolsCore
===============

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
* Namespace: 





Properties
----------


### $file_exists_cache

    protected mixed $file_exists_cache = array()





* Visibility: **protected**
* This property is **static**.


### $_forceCompile

    protected mixed $_forceCompile





* Visibility: **protected**
* This property is **static**.


### $_caching

    protected mixed $_caching





* Visibility: **protected**
* This property is **static**.


### $_user_plateform

    protected mixed $_user_plateform





* Visibility: **protected**
* This property is **static**.


### $_user_browser

    protected mixed $_user_browser





* Visibility: **protected**
* This property is **static**.


### $round_mode

    public mixed $round_mode = null





* Visibility: **public**
* This property is **static**.


### $_cache_nb_media_servers

    protected mixed $_cache_nb_media_servers = null





* Visibility: **protected**
* This property is **static**.


### $is_addons_up

    protected mixed $is_addons_up = true





* Visibility: **protected**
* This property is **static**.


Methods
-------


### passwdGen

    boolean|string ToolsCore::passwdGen(integer $length, string $flag)

Random password generator



* Visibility: **public**
* This method is **static**.


#### Arguments
* $length **integer** - &lt;p&gt;Desired length (optional)&lt;/p&gt;
* $flag **string** - &lt;p&gt;Output type (NUMERIC, ALPHANUMERIC, NO_NUMERIC, RANDOM)&lt;/p&gt;



### getBytes

    boolean|string ToolsCore::getBytes($length)

Random bytes generator

Thanks to Zend for entropy

* Visibility: **public**
* This method is **static**.


#### Arguments
* $length **mixed** - &lt;p&gt;Desired length of random bytes&lt;/p&gt;



### strReplaceFirst

    mixed ToolsCore::strReplaceFirst($search, $replace, $subject, $cur)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $search **mixed**
* $replace **mixed**
* $subject **mixed**
* $cur **mixed**



### redirect

    mixed ToolsCore::redirect(string $url, string $base_uri, \Link $link, string|array $headers)

Redirect user to another page



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;Desired URL&lt;/p&gt;
* $base_uri **string** - &lt;p&gt;Base URI (optional)&lt;/p&gt;
* $link **Link**
* $headers **string|array** - &lt;p&gt;A list of headers to send before redirection&lt;/p&gt;



### redirectLink

    mixed ToolsCore::redirectLink(string $url)

Redirect URLs already containing PS_BASE_URI



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;Desired URL&lt;/p&gt;



### redirectAdmin

    mixed ToolsCore::redirectAdmin(string $url)

Redirect user to another admin page



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;Desired URL&lt;/p&gt;



### getShopProtocol

    String ToolsCore::getShopProtocol()

getShopProtocol return the available protocol for the current shop in use
SSL if Configuration is set on and available for the server



* Visibility: **public**
* This method is **static**.




### getProtocol

    String ToolsCore::getProtocol(boolean $use_ssl)

getProtocol return the set protocol according to configuration (http[s])



* Visibility: **public**
* This method is **static**.


#### Arguments
* $use_ssl **boolean** - &lt;p&gt;true if require ssl&lt;/p&gt;



### getHttpHost

    string ToolsCore::getHttpHost(boolean $http, boolean $entities, $ignore_port)

getHttpHost return the <b>current</b> host used, with the protocol (http or https) if $http is true
This function should not be used to choose http or https domain name.

Use Tools::getShopDomain() or Tools::getShopDomainSsl instead

* Visibility: **public**
* This method is **static**.


#### Arguments
* $http **boolean**
* $entities **boolean**
* $ignore_port **mixed**



### getShopDomain

    string ToolsCore::getShopDomain(boolean $http, boolean $entities)

getShopDomain returns domain name according to configuration and ignoring ssl



* Visibility: **public**
* This method is **static**.


#### Arguments
* $http **boolean** - &lt;p&gt;if true, return domain name with protocol&lt;/p&gt;
* $entities **boolean** - &lt;p&gt;if true, convert special chars to HTML entities&lt;/p&gt;



### getShopDomainSsl

    string ToolsCore::getShopDomainSsl(boolean $http, boolean $entities)

getShopDomainSsl returns domain name according to configuration and depending on ssl activation



* Visibility: **public**
* This method is **static**.


#### Arguments
* $http **boolean** - &lt;p&gt;if true, return domain name with protocol&lt;/p&gt;
* $entities **boolean** - &lt;p&gt;if true, convert special chars to HTML entities&lt;/p&gt;



### getServerName

    string ToolsCore::getServerName()

Get the server variable SERVER_NAME



* Visibility: **public**
* This method is **static**.




### getRemoteAddr

    string ToolsCore::getRemoteAddr()

Get the server variable REMOTE_ADDR, or the first ip of HTTP_X_FORWARDED_FOR (when using proxy)



* Visibility: **public**
* This method is **static**.




### usingSecureMode

    boolean ToolsCore::usingSecureMode()

Check if the current page use SSL connection on not



* Visibility: **public**
* This method is **static**.




### getCurrentUrlProtocolPrefix

    string ToolsCore::getCurrentUrlProtocolPrefix()

Get the current url prefix protocol (https/http)



* Visibility: **public**
* This method is **static**.




### secureReferrer

    string ToolsCore::secureReferrer(string $referrer)

Secure an URL referrer



* Visibility: **public**
* This method is **static**.


#### Arguments
* $referrer **string** - &lt;p&gt;URL referrer&lt;/p&gt;



### getValue

    mixed ToolsCore::getValue(string $key, mixed $default_value)

Get a value from $_POST / $_GET
if unavailable, take a default value



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string** - &lt;p&gt;Value key&lt;/p&gt;
* $default_value **mixed** - &lt;p&gt;(optional)&lt;/p&gt;



### getAllValues

    mixed ToolsCore::getAllValues()

Get all values from $_POST/$_GET



* Visibility: **public**
* This method is **static**.




### getIsset

    mixed ToolsCore::getIsset($key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**



### setCookieLanguage

    string ToolsCore::setCookieLanguage($cookie)

Change language in cookie while clicking on a flag



* Visibility: **public**
* This method is **static**.


#### Arguments
* $cookie **mixed**



### switchLanguage

    mixed ToolsCore::switchLanguage(\Context $context)

Set cookie id_lang



* Visibility: **public**
* This method is **static**.


#### Arguments
* $context **Context**



### getCountry

    mixed ToolsCore::getCountry($address)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **mixed**



### setCurrency

    \Currency ToolsCore::setCurrency($cookie)

Set cookie currency from POST or default currency



* Visibility: **public**
* This method is **static**.


#### Arguments
* $cookie **mixed**



### displayPrice

    string ToolsCore::displayPrice(float $price, object|array $currency, $no_utf8, \Context $context)

Return price with currency sign for a given product



* Visibility: **public**
* This method is **static**.


#### Arguments
* $price **float** - &lt;p&gt;Product price&lt;/p&gt;
* $currency **object|array** - &lt;p&gt;Current currency (object, id_currency, NULL =&gt; context currency)&lt;/p&gt;
* $no_utf8 **mixed**
* $context **Context**



### displayNumber

    mixed ToolsCore::displayNumber($number, $currency)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $number **mixed**
* $currency **mixed**



### displayPriceSmarty

    mixed ToolsCore::displayPriceSmarty($params, $smarty)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **mixed**
* $smarty **mixed**



### convertPrice

    float ToolsCore::convertPrice(float $price, object|array $currency, boolean $to_currency, \Context $context)

Return price converted



* Visibility: **public**
* This method is **static**.


#### Arguments
* $price **float** - &lt;p&gt;Product price&lt;/p&gt;
* $currency **object|array** - &lt;p&gt;Current currency object&lt;/p&gt;
* $to_currency **boolean** - &lt;p&gt;convert to currency or from currency to default currency&lt;/p&gt;
* $context **Context**



### array_replace

    array|mixed|null ToolsCore::array_replace()

Implement array_replace for PHP <= 5.2



* Visibility: **public**
* This method is **static**.




### convertPriceFull

    mixed ToolsCore::convertPriceFull(float $amount, \Currency $currency_from, \Currency $currency_to)

Convert amount from a currency to an other currency automatically



* Visibility: **public**
* This method is **static**.


#### Arguments
* $amount **float**
* $currency_from **Currency** - &lt;p&gt;if null we used the default currency&lt;/p&gt;
* $currency_to **Currency** - &lt;p&gt;if null we used the default currency&lt;/p&gt;



### dateFormat

    string ToolsCore::dateFormat(array $params, object $smarty)

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **array** - &lt;p&gt;Date, format...&lt;/p&gt;
* $smarty **object** - &lt;p&gt;Smarty object for language preferences&lt;/p&gt;



### displayDate

    string ToolsCore::displayDate(string $date, integer $id_lang, boolean $full, string $separator)

Display date regarding to language preferences



* Visibility: **public**
* This method is **static**.


#### Arguments
* $date **string** - &lt;p&gt;Date to display format UNIX&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Language id DEPRECATED&lt;/p&gt;
* $full **boolean** - &lt;p&gt;With time or not (optional)&lt;/p&gt;
* $separator **string** - &lt;p&gt;DEPRECATED&lt;/p&gt;



### safeOutput

    string ToolsCore::safeOutput(string $string, $html)

Sanitize a string



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **string** - &lt;p&gt;String to sanitize&lt;/p&gt;
* $html **mixed**



### htmlentitiesUTF8

    mixed ToolsCore::htmlentitiesUTF8($string, $type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**
* $type **mixed**



### htmlentitiesDecodeUTF8

    mixed ToolsCore::htmlentitiesDecodeUTF8($string)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**



### safePostVars

    mixed ToolsCore::safePostVars()





* Visibility: **public**
* This method is **static**.




### deleteDirectory

    mixed ToolsCore::deleteDirectory(string $dirname, $delete_self)

Delete directory and subdirectories



* Visibility: **public**
* This method is **static**.


#### Arguments
* $dirname **string** - &lt;p&gt;Directory name&lt;/p&gt;
* $delete_self **mixed**



### deleteFile

    mixed ToolsCore::deleteFile(string $file, array $exclude_files)

Delete file



* Visibility: **public**
* This method is **static**.


#### Arguments
* $file **string** - &lt;p&gt;File path&lt;/p&gt;
* $exclude_files **array** - &lt;p&gt;Excluded files&lt;/p&gt;



### clearXMLCache

    mixed ToolsCore::clearXMLCache()

Clear XML cache folder



* Visibility: **public**
* This method is **static**.




### displayError

    mixed ToolsCore::displayError(string $string, boolean $htmlentities, \Context $context)

Display an error according to an error code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **string** - &lt;p&gt;Error message&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;By default at true for parsing error message with htmlentities&lt;/p&gt;
* $context **Context**



### dieObject

    \$object ToolsCore::dieObject(mixed $object, boolean $kill)

Display an error with detailed object



* Visibility: **public**
* This method is **static**.


#### Arguments
* $object **mixed**
* $kill **boolean**



### fd

    mixed ToolsCore::fd(object $object, $type)

Display a var dump in firebug console



* Visibility: **public**
* This method is **static**.


#### Arguments
* $object **object** - &lt;p&gt;Object to display&lt;/p&gt;
* $type **mixed**



### d

    mixed ToolsCore::d(object $object, $kill)

ALIAS OF dieObject() - Display an error with detailed object



* Visibility: **public**
* This method is **static**.


#### Arguments
* $object **object** - &lt;p&gt;Object to display&lt;/p&gt;
* $kill **mixed**



### debug_backtrace

    mixed ToolsCore::debug_backtrace($start, $limit)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $start **mixed**
* $limit **mixed**



### p

    mixed ToolsCore::p(object $object)

ALIAS OF dieObject() - Display an error with detailed object but don't stop the execution



* Visibility: **public**
* This method is **static**.


#### Arguments
* $object **object** - &lt;p&gt;Object to display&lt;/p&gt;



### error_log

    boolean ToolsCore::error_log(mixed $object, integer|null $message_type, string|null $destination, string|null $extra_headers)

Prints object information into error log



* Visibility: **public**
* This method is **static**.


#### Arguments
* $object **mixed**
* $message_type **integer|null**
* $destination **string|null**
* $extra_headers **string|null**



### isSubmit

    mixed ToolsCore::isSubmit(string $submit)

Check if submit has been posted



* Visibility: **public**
* This method is **static**.


#### Arguments
* $submit **string** - &lt;p&gt;submit name&lt;/p&gt;



### getMetaTags

    mixed ToolsCore::getMetaTags($id_lang, $page_name, $title)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $page_name **mixed**
* $title **mixed**



### getHomeMetaTags

    mixed ToolsCore::getHomeMetaTags($id_lang, $page_name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $page_name **mixed**



### completeMetaTags

    mixed ToolsCore::completeMetaTags($meta_tags, $default_value, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $meta_tags **mixed**
* $default_value **mixed**
* $context **Context**



### encrypt

    mixed ToolsCore::encrypt(string $passwd)

Encrypt password



* Visibility: **public**
* This method is **static**.


#### Arguments
* $passwd **string** - &lt;p&gt;String to encrypt&lt;/p&gt;



### encryptIV

    mixed ToolsCore::encryptIV(string $data)

Encrypt data string



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **string** - &lt;p&gt;String to encrypt&lt;/p&gt;



### getToken

    mixed ToolsCore::getToken($page, \Context $context)

Get token to prevent CSRF



* Visibility: **public**
* This method is **static**.


#### Arguments
* $page **mixed**
* $context **Context**



### getAdminToken

    mixed ToolsCore::getAdminToken(string $string)

Tokenize a string



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **string** - &lt;p&gt;string to encript&lt;/p&gt;



### getAdminTokenLite

    mixed ToolsCore::getAdminTokenLite($tab, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $tab **mixed**
* $context **Context**



### getAdminTokenLiteSmarty

    mixed ToolsCore::getAdminTokenLiteSmarty($params, $smarty)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **mixed**
* $smarty **mixed**



### getAdminUrl

    mixed ToolsCore::getAdminUrl(string $url, $entities)

Get a valid URL to use from BackOffice



* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **string** - &lt;p&gt;An URL to use in BackOffice&lt;/p&gt;
* $entities **mixed**



### getAdminImageUrl

    mixed ToolsCore::getAdminImageUrl(string $image, $entities)

Get a valid image URL to use from BackOffice



* Visibility: **public**
* This method is **static**.


#### Arguments
* $image **string** - &lt;p&gt;Image name&lt;/p&gt;
* $entities **mixed**



### getPath

    mixed ToolsCore::getPath(integer $id_category, string $path, $link_on_the_item, $category_type, \Context $context)

Get the user's journey



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **integer** - &lt;p&gt;Category ID&lt;/p&gt;
* $path **string** - &lt;p&gt;Path end&lt;/p&gt;
* $link_on_the_item **mixed**
* $category_type **mixed**
* $context **Context**



### getFullPath

    mixed ToolsCore::getFullPath($id_category, $end, $type_cat, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **mixed**
* $end **mixed**
* $type_cat **mixed**
* $context **Context**



### link_rewrite

    string ToolsCore::link_rewrite(string $str, boolean $utf8_decode)

Return the friendly url from the provided string



* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **string**
* $utf8_decode **boolean** - &lt;p&gt;(deprecated)&lt;/p&gt;



### str2url

    string ToolsCore::str2url(string $str)

Return a friendly url made from the provided string
If the mbstring library is available, the output is the same as the js function of the same name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **string**



### replaceAccentedChars

    string ToolsCore::replaceAccentedChars(string $str)

Replace all accented chars by their equivalent non accented chars.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **string**



### truncate

    mixed ToolsCore::truncate($str, $max_length, $suffix)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**
* $max_length **mixed**
* $suffix **mixed**



### truncateString

    mixed ToolsCore::truncateString($text, $length, $options)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $text **mixed**
* $length **mixed**
* $options **mixed**



### normalizeDirectory

    mixed ToolsCore::normalizeDirectory($directory)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $directory **mixed**



### dateYears

    array ToolsCore::dateYears()

Generate date form



* Visibility: **public**
* This method is **static**.




### dateDays

    mixed ToolsCore::dateDays()





* Visibility: **public**
* This method is **static**.




### dateMonths

    mixed ToolsCore::dateMonths()





* Visibility: **public**
* This method is **static**.




### hourGenerate

    mixed ToolsCore::hourGenerate($hours, $minutes, $seconds)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $hours **mixed**
* $minutes **mixed**
* $seconds **mixed**



### dateFrom

    mixed ToolsCore::dateFrom($date)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $date **mixed**



### dateTo

    mixed ToolsCore::dateTo($date)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $date **mixed**



### strtolower

    mixed ToolsCore::strtolower($str)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**



### strlen

    mixed ToolsCore::strlen($str, $encoding)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**
* $encoding **mixed**



### stripslashes

    mixed ToolsCore::stripslashes($string)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**



### strtoupper

    mixed ToolsCore::strtoupper($str)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**



### substr

    mixed ToolsCore::substr($str, $start, $length, $encoding)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**
* $start **mixed**
* $length **mixed**
* $encoding **mixed**



### strpos

    mixed ToolsCore::strpos($str, $find, $offset, $encoding)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**
* $find **mixed**
* $offset **mixed**
* $encoding **mixed**



### strrpos

    mixed ToolsCore::strrpos($str, $find, $offset, $encoding)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**
* $find **mixed**
* $offset **mixed**
* $encoding **mixed**



### ucfirst

    mixed ToolsCore::ucfirst($str)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**



### ucwords

    mixed ToolsCore::ucwords($str)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**



### orderbyPrice

    mixed ToolsCore::orderbyPrice($array, $order_way)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $array **mixed**
* $order_way **mixed**



### iconv

    mixed ToolsCore::iconv($from, $to, $string)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $from **mixed**
* $to **mixed**
* $string **mixed**



### isEmpty

    mixed ToolsCore::isEmpty($field)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $field **mixed**



### ps_round

    float ToolsCore::ps_round(float $value, integer $precision, $round_mode)

returns the rounded value of $value to specified precision, according to your configuration;



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **float**
* $precision **integer**
* $round_mode **mixed**



### math_round

    mixed ToolsCore::math_round($value, $places, $mode)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **mixed**
* $places **mixed**
* $mode **mixed**



### round_helper

    mixed ToolsCore::round_helper($value, $mode)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **mixed**
* $mode **mixed**



### ceilf

    float ToolsCore::ceilf(float $value, integer $precision)

returns the rounded value up of $value to specified precision



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **float**
* $precision **integer**



### floorf

    float ToolsCore::floorf(float $value, integer $precision)

returns the rounded value down of $value to specified precision



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **float**
* $precision **integer**



### file_exists_cache

    boolean ToolsCore::file_exists_cache(string $filename)

file_exists() wrapper with cache to speedup performance



* Visibility: **public**
* This method is **static**.


#### Arguments
* $filename **string** - &lt;p&gt;File name&lt;/p&gt;



### file_exists_no_cache

    boolean ToolsCore::file_exists_no_cache(string $filename)

file_exists() wrapper with a call to clearstatcache prior



* Visibility: **public**
* This method is **static**.


#### Arguments
* $filename **string** - &lt;p&gt;File name&lt;/p&gt;



### file_get_contents

    mixed ToolsCore::file_get_contents($url, $use_include_path, $stream_context, $curl_timeout)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **mixed**
* $use_include_path **mixed**
* $stream_context **mixed**
* $curl_timeout **mixed**



### simplexml_load_file

    mixed ToolsCore::simplexml_load_file($url, $class_name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **mixed**
* $class_name **mixed**



### copy

    mixed ToolsCore::copy($source, $destination, $stream_context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $source **mixed**
* $destination **mixed**
* $stream_context **mixed**



### minifyHTML

    mixed ToolsCore::minifyHTML($html_content)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $html_content **mixed**



### toCamelCase

    mixed ToolsCore::toCamelCase($str, $catapitalise_first_char)

Translates a string with underscores into camel case (e.g. first_name -> firstName)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**
* $catapitalise_first_char **mixed**



### toUnderscoreCase

    string ToolsCore::toUnderscoreCase(string $string)

Transform a CamelCase string to underscore_case string



* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **string**



### getBrightness

    mixed ToolsCore::getBrightness($hex)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $hex **mixed**



### minifyHTMLpregCallback

    mixed ToolsCore::minifyHTMLpregCallback($preg_matches)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $preg_matches **mixed**



### packJSinHTML

    mixed ToolsCore::packJSinHTML($html_content)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $html_content **mixed**



### packJSinHTMLpregCallback

    mixed ToolsCore::packJSinHTMLpregCallback($preg_matches)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $preg_matches **mixed**



### packJS

    mixed ToolsCore::packJS($js_content)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $js_content **mixed**



### parserSQL

    mixed ToolsCore::parserSQL($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### minifyCSS

    mixed ToolsCore::minifyCSS($css_content, $fileuri)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $css_content **mixed**
* $fileuri **mixed**



### replaceByAbsoluteURL

    mixed ToolsCore::replaceByAbsoluteURL($matches)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $matches **mixed**



### addJS

    void ToolsCore::addJS(mixed $js_uri)

addJS load a javascript file in the header



* Visibility: **public**
* This method is **static**.


#### Arguments
* $js_uri **mixed**



### addCSS

    mixed ToolsCore::addCSS($css_uri, $css_media_type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### cccCss

    mixed ToolsCore::cccCss($css_files)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $css_files **mixed**



### cccJS

    mixed ToolsCore::cccJS($js_files)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $js_files **mixed**



### getMediaServer

    mixed ToolsCore::getMediaServer($filename)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $filename **mixed**



### generateHtaccess

    mixed ToolsCore::generateHtaccess($path, $rewrite_settings, $cache_control, $specific, $disable_multiviews, $medias, $disable_modsec)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $path **mixed**
* $rewrite_settings **mixed**
* $cache_control **mixed**
* $specific **mixed**
* $disable_multiviews **mixed**
* $medias **mixed**
* $disable_modsec **mixed**



### generateIndex

    mixed ToolsCore::generateIndex()





* Visibility: **public**
* This method is **static**.




### getDefaultIndexContent

    mixed ToolsCore::getDefaultIndexContent()





* Visibility: **public**
* This method is **static**.




### jsonDecode

    array ToolsCore::jsonDecode(string $json, boolean $assoc)

jsonDecode convert json string to php array / object



* Visibility: **public**
* This method is **static**.


#### Arguments
* $json **string**
* $assoc **boolean** - &lt;p&gt;(since 1.4.2.4) if true, convert to associativ array&lt;/p&gt;



### jsonEncode

    string ToolsCore::jsonEncode(array $data)

Convert an array to json string



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **array**



### displayAsDeprecated

    mixed ToolsCore::displayAsDeprecated($message)

Display a warning message indicating that the method is deprecated



* Visibility: **public**
* This method is **static**.


#### Arguments
* $message **mixed**



### displayParameterAsDeprecated

    mixed ToolsCore::displayParameterAsDeprecated($parameter)

Display a warning message indicating that the parameter is deprecated



* Visibility: **public**
* This method is **static**.


#### Arguments
* $parameter **mixed**



### displayFileAsDeprecated

    mixed ToolsCore::displayFileAsDeprecated()





* Visibility: **public**
* This method is **static**.




### throwDeprecated

    mixed ToolsCore::throwDeprecated($error, $message, $class)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $error **mixed**
* $message **mixed**
* $class **mixed**



### enableCache

    mixed ToolsCore::enableCache($level, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $level **mixed**
* $context **Context**



### restoreCacheSettings

    mixed ToolsCore::restoreCacheSettings(\Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $context **Context**



### isCallable

    mixed ToolsCore::isCallable($function)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $function **mixed**



### pRegexp

    mixed ToolsCore::pRegexp($s, $delim)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $s **mixed**
* $delim **mixed**



### str_replace_once

    mixed ToolsCore::str_replace_once($needle, $replace, $haystack)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $needle **mixed**
* $replace **mixed**
* $haystack **mixed**



### property_exists

    boolean ToolsCore::property_exists(object $class, string $property)

Function property_exists does not exist in PHP < 5.1



* Visibility: **public**
* This method is **static**.


#### Arguments
* $class **object**
* $property **string**



### checkPhpVersion

    string ToolsCore::checkPhpVersion()





* Visibility: **public**
* This method is **static**.




### ZipTest

    boolean ToolsCore::ZipTest($from_file)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $from_file **mixed**



### getSafeModeStatus

    mixed ToolsCore::getSafeModeStatus()





* Visibility: **public**
* This method is **static**.




### ZipExtract

    boolean ToolsCore::ZipExtract($from_file, $to_dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $from_file **mixed**
* $to_dir **mixed**



### chmodr

    mixed ToolsCore::chmodr($path, $filemode)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $path **mixed**
* $filemode **mixed**



### getProductsOrder

    string ToolsCore::getProductsOrder(string $type, string $value, boolean|\bool(false)|string $prefix)

Get products order field name for queries.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $type **string** - &lt;p&gt;by|way&lt;/p&gt;
* $value **string** - &lt;p&gt;If no index given, use default order from admin -&gt; pref -&gt; products&lt;/p&gt;
* $prefix **boolean|bool(false)|string**



### convertBytes

    integer ToolsCore::convertBytes(string $value)

Convert a shorthand byte value from a PHP configuration directive to an integer value



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **string** - &lt;p&gt;value to convert&lt;/p&gt;



### display404Error

    mixed ToolsCore::display404Error()





* Visibility: **public**
* This method is **static**.




### url

    string ToolsCore::url(string $begin, string $end)

Concat $begin and $end, add ? or & between strings



* Visibility: **public**
* This method is **static**.


#### Arguments
* $begin **string**
* $end **string**



### dieOrLog

    boolean ToolsCore::dieOrLog(string $msg, boolean $die)

Display error and dies or silently log the error.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $msg **string**
* $die **boolean**



### nl2br

    string ToolsCore::nl2br($str)

Convert \n and \r\n and \r to <br />



* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**



### clearCache

    mixed ToolsCore::clearCache(\Smarty $smarty, $tpl, $cache_id, $compile_id)

Clear cache for Smarty



* Visibility: **public**
* This method is **static**.


#### Arguments
* $smarty **Smarty**
* $tpl **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### clearCompile

    mixed ToolsCore::clearCompile($smarty)

Clear compile for Smarty



* Visibility: **public**
* This method is **static**.


#### Arguments
* $smarty **mixed**



### clearSmartyCache

    mixed ToolsCore::clearSmartyCache()

Clear Smarty cache and compile folders



* Visibility: **public**
* This method is **static**.




### clearColorListCache

    mixed ToolsCore::clearColorListCache($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### getMemoryLimit

    integer ToolsCore::getMemoryLimit()

getMemoryLimit allow to get the memory limit in octet



* Visibility: **public**
* This method is **static**.




### getOctets

    integer ToolsCore::getOctets($option)

getOctet allow to gets the value of a configuration option in octet



* Visibility: **public**
* This method is **static**.


#### Arguments
* $option **mixed**



### isX86_64arch

    boolean ToolsCore::isX86_64arch()





* Visibility: **public**
* This method is **static**.




### isPHPCLI

    boolean ToolsCore::isPHPCLI()





* Visibility: **public**
* This method is **static**.




### argvToGET

    mixed ToolsCore::argvToGET($argc, $argv)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $argc **mixed**
* $argv **mixed**



### getMaxUploadSize

    integer ToolsCore::getMaxUploadSize(integer $max_size)

Get max file upload size considering server settings and optional max value



* Visibility: **public**
* This method is **static**.


#### Arguments
* $max_size **integer** - &lt;p&gt;optional max file size&lt;/p&gt;



### apacheModExists

    boolean ToolsCore::apacheModExists(string $name)

apacheModExists return true if the apache module $name is loaded



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;module name&lt;/p&gt;



### recurseCopy

    mixed ToolsCore::recurseCopy($src, $dst, boolean $del)

Copy the folder $src into $dst, $dst is created if it do not exist



* Visibility: **public**
* This method is **static**.


#### Arguments
* $src **mixed**
* $dst **mixed**
* $del **boolean** - &lt;p&gt;if true, delete the file after copy&lt;/p&gt;



### scandir

    array ToolsCore::scandir($path, $ext, $dir, $recursive)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $path **mixed**
* $ext **mixed**
* $dir **mixed**
* $recursive **mixed**



### version_compare

    mixed ToolsCore::version_compare($v1, $v2, string $operator)

Align version sent and use internal function



* Visibility: **public**
* This method is **static**.


#### Arguments
* $v1 **mixed**
* $v2 **mixed**
* $operator **string**



### alignVersionNumber

    mixed ToolsCore::alignVersionNumber($v1, $v2)

Align 2 version with the same number of sub version
version_compare will work better for its comparison :)
(Means: '1.8' to '1.9.3' will change '1.8' to '1.8.0')



* Visibility: **public**
* This method is **static**.


#### Arguments
* $v1 **mixed**
* $v2 **mixed**



### modRewriteActive

    mixed ToolsCore::modRewriteActive()





* Visibility: **public**
* This method is **static**.




### unSerialize

    mixed ToolsCore::unSerialize($serialized, $object)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $serialized **mixed**
* $object **mixed**



### arrayUnique

    array ToolsCore::arrayUnique(array $array)

Reproduce array_unique working before php version 5.2.9



* Visibility: **public**
* This method is **static**.


#### Arguments
* $array **array**



### cleanNonUnicodeSupport

    string ToolsCore::cleanNonUnicodeSupport(string $pattern)

Delete unicode class from regular expression patterns



* Visibility: **public**
* This method is **static**.


#### Arguments
* $pattern **string**



### addonsRequest

    mixed ToolsCore::addonsRequest($request, $params)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $request **mixed**
* $params **mixed**



### fileAttachment

    array|null ToolsCore::fileAttachment(string $input, boolean $return_content)

Returns an array containing information about
HTTP file upload variable ($_FILES)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $input **string** - &lt;p&gt;File upload field name&lt;/p&gt;
* $return_content **boolean** - &lt;p&gt;If true, returns uploaded file contents&lt;/p&gt;



### changeFileMTime

    mixed ToolsCore::changeFileMTime($file_name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $file_name **mixed**



### waitUntilFileIsModified

    mixed ToolsCore::waitUntilFileIsModified($file_name, $timeout)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $file_name **mixed**
* $timeout **mixed**



### rtrimString

    string ToolsCore::rtrimString(string $str, string $str_search)

Delete a substring from another one starting from the right



* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **string**
* $str_search **string**



### formatBytes

    string ToolsCore::formatBytes($size, integer $precision)

Format a number into a human readable format
e.g. 24962496 => 23.81M



* Visibility: **public**
* This method is **static**.


#### Arguments
* $size **mixed**
* $precision **integer**



### boolVal

    mixed ToolsCore::boolVal($value)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **mixed**



### getUserPlatform

    mixed ToolsCore::getUserPlatform()





* Visibility: **public**
* This method is **static**.




### getUserBrowser

    mixed ToolsCore::getUserBrowser()





* Visibility: **public**
* This method is **static**.




### getDescriptionClean

    string ToolsCore::getDescriptionClean($description)

Allows to display the category description without HTML tags and slashes



* Visibility: **public**
* This method is **static**.


#### Arguments
* $description **mixed**



### purifyHTML

    mixed ToolsCore::purifyHTML($html, $uri_unescape, $allow_style)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $html **mixed**
* $uri_unescape **mixed**
* $allow_style **mixed**



### safeDefine

    mixed ToolsCore::safeDefine(string $constant, mixed $value)

Check if a constant was already defined



* Visibility: **public**
* This method is **static**.


#### Arguments
* $constant **string** - &lt;p&gt;Constant name&lt;/p&gt;
* $value **mixed** - &lt;p&gt;Default value to set if not defined&lt;/p&gt;



### spreadAmount

    mixed ToolsCore::spreadAmount($amount, $precision, $rows, $column)

Spread an amount on lines, adjusting the $column field,
with the biggest adjustments going to the rows having the
highest $sort_column.

E.g.:

$rows = [['a' => 5.1], ['a' => 8.2]];

spreadAmount(0.3, 1, $rows, 'a');

=> $rows is [['a' => 8.4], ['a' => 5.2]]

* Visibility: **public**
* This method is **static**.


#### Arguments
* $amount **mixed** - &lt;p&gt;float  The amount to spread across the rows&lt;/p&gt;
* $precision **mixed** - &lt;p&gt;int Rounding precision&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                  e.g. if $amount is 1, $precision is 0 and $rows = [[&#039;a&#039; =&gt; 2], [&#039;a&#039; =&gt; 1]]
                  then the resulting $rows will be [[&#039;a&#039; =&gt; 3], [&#039;a&#039; =&gt; 1]]
                  But if $precision were 1, then the resulting $rows would be [[&#039;a&#039; =&gt; 2.5], [&#039;a&#039; =&gt; 1.5]]&lt;/code&gt;&lt;/pre&gt;
* $rows **mixed**
* $column **mixed** - &lt;p&gt;string The column on which to perform adjustments&lt;/p&gt;



### arrayReplaceRecursive

    mixed ToolsCore::arrayReplaceRecursive(array $base, array $replacements)

Replaces elements from passed arrays into the first array recursively



* Visibility: **public**
* This method is **static**.


#### Arguments
* $base **array** - &lt;p&gt;The array in which elements are replaced.&lt;/p&gt;
* $replacements **array** - &lt;p&gt;The array from which elements will be extracted.&lt;/p&gt;


