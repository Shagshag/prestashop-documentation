Class ParentOrderControllerCore
=====================





* Class name: ParentOrderControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/ParentOrderController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L37)


Contents
--------


### Properties

* [$nbProducts](#property-$nbProducts)
* [$php_self](#property-$php_self)
* [$ssl](#property-$ssl)
* [$auth](#property-$auth)
* [$authRedirection](#property-$authRedirection)
* [$cart](#property-$cart)
* [$cookie](#property-$cookie)
* [$currentCustomerGroups](#property-$currentCustomerGroups)
* [$display_column_left](#property-$display_column_left)
* [$display_column_right](#property-$display_column_right)
* [$errors](#property-$errors)
* [$guestAllowed](#property-$guestAllowed)
* [$initialized](#property-$initialized)
* [$iso](#property-$iso)
* [$link](#property-$link)
* [$maintenance](#property-$maintenance)
* [$n](#property-$n)
* [$nb_items_per_page](#property-$nb_items_per_page)
* [$orderBy](#property-$orderBy)
* [$orderWay](#property-$orderWay)
* [$p](#property-$p)
* [$restrictedCountry](#property-$restrictedCountry)
* [$smarty](#property-$smarty)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$controller_type](#property-$controller_type)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$display_header_javascript](#property-$display_header_javascript)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$php_errors](#property-$php_errors)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)
* [$template](#property-$template)

### Methods

* [__construct](#method-__construct)
* [_assignAddress](#method-_assignAddress)
* [_assignCarrier](#method-_assignCarrier)
* [_assignPayment](#method-_assignPayment)
* [_assignSummaryInformations](#method-_assignSummaryInformations)
* [_assignWrappingAndTOS](#method-_assignWrappingAndTOS)
* [_checkFreeOrder](#method-_checkFreeOrder)
* [_processCarrier](#method-_processCarrier)
* [_setDefaultCarrierSelection](#method-_setDefaultCarrierSelection)
* [_updateMessage](#method-_updateMessage)
* [addCSS](#method-addCSS)
* [addColorsToProductList](#method-addColorsToProductList)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addMedia](#method-addMedia)
* [ajaxDie](#method-ajaxDie)
* [canonicalRedirection](#method-canonicalRedirection)
* [checkAccess](#method-checkAccess)
* [checkLiveEditAccess](#method-checkLiveEditAccess)
* [display](#method-display)
* [displayContent](#method-displayContent)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayHeaderJavaScript](#method-displayHeaderJavaScript)
* [displayMaintenancePage](#method-displayMaintenancePage)
* [displayRestrictedCountryPage](#method-displayRestrictedCountryPage)
* [geolocationManagement](#method-geolocationManagement)
* [getColorsListCacheId](#method-getColorsListCacheId)
* [getController](#method-getController)
* [getCurrentCustomerGroups](#method-getCurrentCustomerGroups)
* [getLayout](#method-getLayout)
* [getLiveEditFooter](#method-getLiveEditFooter)
* [getOverrideTemplate](#method-getOverrideTemplate)
* [getOverrideThemeDir](#method-getOverrideThemeDir)
* [getTemplatePath](#method-getTemplatePath)
* [getThemeDir](#method-getThemeDir)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [initLogoAndFavicon](#method-initLogoAndFavicon)
* [isCached](#method-isCached)
* [isInWhitelistForGeolocation](#method-isInWhitelistForGeolocation)
* [isTokenValid](#method-isTokenValid)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [myErrorHandler](#method-myErrorHandler)
* [pagination](#method-pagination)
* [postProcess](#method-postProcess)
* [process](#method-process)
* [productSort](#method-productSort)
* [recoverCart](#method-recoverCart)
* [redirect](#method-redirect)
* [removeCSS](#method-removeCSS)
* [removeJS](#method-removeJS)
* [removeMedia](#method-removeMedia)
* [run](#method-run)
* [setDefaultCarrierSelection](#method-setDefaultCarrierSelection)
* [setMedia](#method-setMedia)
* [setMobileMedia](#method-setMobileMedia)
* [setMobileTemplate](#method-setMobileTemplate)
* [setNoCarrier](#method-setNoCarrier)
* [setRedirectAfter](#method-setRedirectAfter)
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [sslRedirection](#method-sslRedirection)
* [useMobileTheme](#method-useMobileTheme)
* [validateDeliveryOption](#method-validateDeliveryOption)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$nbProducts"></a>$nbProducts

```php
public mixed $nbProducts
```





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L42).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'order'
```





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L40).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L39).


### <a name="property-$auth"></a>$auth

```php
public boolean $auth = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L72).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public boolean $authRedirection = false
```

Route of PrestaShop page to redirect to after forced login.



* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L88).


### <a name="property-$cart"></a>$cart

```php
protected  $cart
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L51).


### <a name="property-$cookie"></a>$cookie

```php
protected  $cookie
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L39).


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

```php
protected array $currentCustomerGroups
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L116).


### <a name="property-$display_column_left"></a>$display_column_left

```php
public boolean $display_column_left = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L100).


### <a name="property-$display_column_right"></a>$display_column_right

```php
public boolean $display_column_right = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L103).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L54).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public boolean $guestAllowed = false
```

If set to true, user can be logged in as guest when checking if logged in.



* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L80).


### <a name="property-$initialized"></a>$initialized

```php
public boolean $initialized = false
```

True if controller has already been initialized.

Prevents initializing controller more than once.

* Visibility: **public**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L111).


### <a name="property-$iso"></a>$iso

```php
public string $iso
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L57).


### <a name="property-$link"></a>$link

```php
protected  $link
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L45).


### <a name="property-$maintenance"></a>$maintenance

```php
protected boolean $maintenance = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L97).


### <a name="property-$n"></a>$n

```php
public integer $n
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L69).


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

```php
public integer $nb_items_per_page
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L121).


### <a name="property-$orderBy"></a>$orderBy

```php
public string $orderBy
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L60).


### <a name="property-$orderWay"></a>$orderWay

```php
public string $orderWay
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L63).


### <a name="property-$p"></a>$p

```php
public integer $p
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L66).


### <a name="property-$restrictedCountry"></a>$restrictedCountry

```php
protected boolean $restrictedCountry = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L94).


### <a name="property-$smarty"></a>$smarty

```php
protected  $smarty
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L33).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L61).


### <a name="property-$content_only"></a>$content_only

```php
protected boolean $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L58).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L34).


### <a name="property-$controller_type"></a>$controller_type

```php
public string $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L76).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L37).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L55).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L46).


### <a name="property-$display_header_javascript"></a>$display_header_javascript

```php
protected boolean $display_header_javascript
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L49).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L40).


### <a name="property-$json"></a>$json

```php
protected boolean $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L64).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L43).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected string $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L73).


### <a name="property-$status"></a>$status

```php
protected string $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L67).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L52).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FrontControllerCore::__construct()
```

Controller constructor



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L128)




### <a name="method-_assignAddress"></a>_assignAddress

```php
mixed ParentOrderControllerCore::_assignAddress()
```





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L386)




### <a name="method-_assignCarrier"></a>_assignCarrier

```php
mixed ParentOrderControllerCore::_assignCarrier()
```





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L494)




### <a name="method-_assignPayment"></a>_assignPayment

```php
mixed ParentOrderControllerCore::_assignPayment()
```





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L572)




### <a name="method-_assignSummaryInformations"></a>_assignSummaryInformations

```php
mixed ParentOrderControllerCore::_assignSummaryInformations()
```





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L293)




### <a name="method-_assignWrappingAndTOS"></a>_assignWrappingAndTOS

```php
mixed ParentOrderControllerCore::_assignWrappingAndTOS()
```





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L529)




### <a name="method-_checkFreeOrder"></a>_checkFreeOrder

```php
boolean ParentOrderControllerCore::_checkFreeOrder()
```

Check if order is free



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L170)




### <a name="method-_processCarrier"></a>_processCarrier

```php
mixed ParentOrderControllerCore::_processCarrier()
```





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L214)




### <a name="method-_setDefaultCarrierSelection"></a>_setDefaultCarrierSelection

```php
\number ParentOrderControllerCore::_setDefaultCarrierSelection(array $carriers)
```

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 635](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L635)


#### Arguments
* $carriers **array**



### <a name="method-_updateMessage"></a>_updateMessage

```php
mixed ParentOrderControllerCore::_updateMessage($messageContent)
```





* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L182)


#### Arguments
* $messageContent **mixed**



### <a name="method-addCSS"></a>addCSS

```php
true|void FrontControllerCore::addCSS(array|string $css_uri, string $css_media_type, integer|null $offset, boolean $check_path)
```

Add one or several CSS for front, checking if css files are overridden in theme/css/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1338)


#### Arguments
* $css_uri **array|string** - $media_uri Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)
* $css_media_type **string** - CSS media type
* $offset **integer|null**
* $check_path **boolean** - If true, checks if files exists



### <a name="method-addColorsToProductList"></a>addColorsToProductList

```php
mixed FrontControllerCore::addColorsToProductList(array $products)
```

Renders and adds color list HTML for each product in a list



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1611)


#### Arguments
* $products **array**



### <a name="method-addJS"></a>addJS

```php
true|void FrontControllerCore::addJS(array|string $js_uri, boolean $check_path)
```

Add one or several JS files for front, checking if js files are overridden in theme/js/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1363](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1363)


#### Arguments
* $js_uri **array|string** - Path to file, or an array of paths
* $check_path **boolean** - If true, checks if files exists



### <a name="method-addJquery"></a>addJquery

```php
mixed ControllerCore::addJquery(string|null $version, string|null $folder, boolean $minifier)
```

Adds jQuery library file to queued JS file list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L425)


#### Arguments
* $version **string|null** - jQuery library version
* $folder **string|null** - jQuery file folder
* $minifier **boolean** - If set tot true, a minified version will be included.



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
mixed ControllerCore::addJqueryPlugin(string|array $name, $folder, boolean $css)
```

Adds jQuery plugin(s) to queued JS file list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L457)


#### Arguments
* $name **string|array**
* $folder **mixed**
* $css **boolean**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
mixed ControllerCore::addJqueryUI(string|array $component, string $theme, boolean $check_dependencies)
```

Adds jQuery UI component(s) to queued JS file list



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L437)


#### Arguments
* $component **string|array**
* $theme **string**
* $check_dependencies **boolean**



### <a name="method-addMedia"></a>addMedia

```php
true|void FrontControllerCore::addMedia(string|array $media_uri, string|null $css_media_type, integer|null $offset, boolean $remove, boolean $check_path)
```

Adds a media file(s) (CSS, JS) to page header



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1258)


#### Arguments
* $media_uri **string|array** - Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)
* $css_media_type **string|null** - CSS media type
* $offset **integer|null**
* $remove **boolean** - If True, removes media files
* $check_path **boolean** - If true, checks if files exists



### <a name="method-ajaxDie"></a>ajaxDie

```php
mixed ControllerCore::ajaxDie(string|null $value, string|null $controller, string|null $method)
```

Dies and echoes output value



* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 608](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L608)


#### Arguments
* $value **string|null**
* $controller **string|null**
* $method **string|null**



### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed FrontControllerCore::canonicalRedirection(string $canonical_url)
```

Redirects to canonical URL



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L806)


#### Arguments
* $canonical_url **string**



### <a name="method-checkAccess"></a>checkAccess

```php
boolean FrontControllerCore::checkAccess()
```

Check if the controller is available for the current user/visitor



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L163)




### <a name="method-checkLiveEditAccess"></a>checkLiveEditAccess

```php
boolean FrontControllerCore::checkLiveEditAccess()
```

Checks if the user can use Live Edit feature



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1043](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1043)




### <a name="method-display"></a>display

```php
boolean FrontControllerCore::display()
```

Compiles and outputs full page content



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 684](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L684)




### <a name="method-displayContent"></a>displayContent

```php
mixed FrontControllerCore::displayContent()
```

Renders page content.

Used for retrocompatibility with PS 1.4

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 673](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L673)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed FrontControllerCore::displayFooter($display)
```

Compiles and outputs page footer section



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 635](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L635)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed FrontControllerCore::displayHeader(boolean $display)
```

Compiles and outputs page header section (including HTML <head>)



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L595)


#### Arguments
* $display **boolean** - If true, renders visual page header section



### <a name="method-displayHeaderJavaScript"></a>displayHeaderJavaScript

```php
mixed ControllerCore::displayHeaderJavaScript(boolean $display)
```

Sets page header javascript display



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L223)


#### Arguments
* $display **boolean**



### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

```php
mixed FrontControllerCore::displayMaintenancePage()
```

Displays maintenance page if shop is closed.



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L745)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

```php
mixed FrontControllerCore::displayRestrictedCountryPage()
```

Displays 'country restricted' page if user's country is not allowed.



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 770](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L770)




### <a name="method-geolocationManagement"></a>geolocationManagement

```php
\Country|false FrontControllerCore::geolocationManagement(\Country $default_country)
```

Geolocation management



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L853)


#### Arguments
* $default_country **[Country](class.CountryCore.md)**



### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

```php
string FrontControllerCore::getColorsListCacheId(integer $id_product)
```

Returns cache ID for product color list



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1654](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1654)


#### Arguments
* $id_product **integer**



### <a name="method-getController"></a>getController

```php
\Controller ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

returns a new instance of this controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L129)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getCurrentCustomerGroups"></a>getCurrentCustomerGroups

```php
array FrontControllerCore::getCurrentCustomerGroups()
```

Sets and returns customer groups that the current customer(visitor) belongs to.



* Visibility: **public**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1182)




### <a name="method-getLayout"></a>getLayout

```php
boolean|string FrontControllerCore::getLayout()
```

Returns the layout corresponding to the current page by using the override system
Ex:
On the url: http://localhost/index.php?id_product=1&controller=product, this method will
check if the layout exists in the following files (in that order), and return the first found:
- /themes/default/override/layout-product-1.tpl
- /themes/default/override/layout-product.tpl
- /themes/default/layout.tpl



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1494)




### <a name="method-getLiveEditFooter"></a>getLiveEditFooter

```php
string FrontControllerCore::getLiveEditFooter()
```

Renders Live Edit widget



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1059](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1059)




### <a name="method-getOverrideTemplate"></a>getOverrideTemplate

```php
string|boolean FrontControllerCore::getOverrideTemplate()
```

Returns an overridden template path (if any) for this controller.

If not overridden, will return false. This method can be easily overriden in a
specific controller.

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1439](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1439)




### <a name="method-getOverrideThemeDir"></a>getOverrideThemeDir

```php
string FrontControllerCore::getOverrideThemeDir()
```

Returns theme override directory (regular or mobile)



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1477)




### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string FrontControllerCore::getTemplatePath(string $template)
```

Returns template path



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1523)


#### Arguments
* $template **string**



### <a name="method-getThemeDir"></a>getThemeDir

```php
string FrontControllerCore::getThemeDir()
```

Returns theme directory (regular or mobile)



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1466](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1466)




### <a name="method-init"></a>init

```php
mixed ParentOrderControllerCore::init()
```

Initialize parent order controller



* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L48)




### <a name="method-initContent"></a>initContent

```php
mixed FrontControllerCore::initContent()
```

Initializes common front page content: header, footer and side columns



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L567)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed FrontControllerCore::initCursedPage()
```

Renders and outputs maintenance page and ends controller process.



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L644)




### <a name="method-initFooter"></a>initFooter

```php
mixed FrontControllerCore::initFooter()
```

Initializes page footer variables



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1015](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1015)




### <a name="method-initHeader"></a>initHeader

```php
mixed FrontControllerCore::initHeader()
```

Initializes page header variables



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 993](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L993)




### <a name="method-initLogoAndFavicon"></a>initLogoAndFavicon

```php
array FrontControllerCore::initLogoAndFavicon()
```

Returns logo and favicon variables, depending
on active theme type (regular or mobile)



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1589](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1589)




### <a name="method-isCached"></a>isCached

```php
boolean ControllerCore::isCached(string $template, string|null $cache_id, string|null $compile_id)
```

Checks if a template is cached



* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 547](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L547)


#### Arguments
* $template **string**
* $cache_id **string|null** - Cache item ID
* $compile_id **string|null**



### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

```php
boolean FrontControllerCore::isInWhitelistForGeolocation()
```

Checks if user's location is whitelisted.



* Visibility: **protected**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1208)




### <a name="method-isTokenValid"></a>isTokenValid

```php
boolean FrontControllerCore::isTokenValid()
```

Checks if token is valid



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1240)




### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```

Checks if the controller has been called from XmlHttpRequest (AJAX)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L481)




### <a name="method-myErrorHandler"></a>myErrorHandler

```php
boolean ControllerCore::myErrorHandler(string $errno, string $errstr, string $errfile, integer $errline)
```

Custom error handler



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L565)


#### Arguments
* $errno **string**
* $errstr **string**
* $errfile **string**
* $errline **integer**



### <a name="method-pagination"></a>pagination

```php
mixed FrontControllerCore::pagination(integer|null $total_products)
```

Assigns product list page pagination variables



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1116)


#### Arguments
* $total_products **integer|null**



### <a name="method-postProcess"></a>postProcess

```php
mixed FrontControllerCore::postProcess()
```

Method that is executed after init() and checkAccess().

Used to process user input.

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L560)




### <a name="method-process"></a>process

```php
mixed FrontControllerCore::process()
```

Called before compiling common page sections (header, footer, columns).

Good place to modify smarty variables.

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 655](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L655)




### <a name="method-productSort"></a>productSort

```php
mixed FrontControllerCore::productSort()
```

Assigns product list page sorting variables



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1079)




### <a name="method-recoverCart"></a>recoverCart

```php
integer|false FrontControllerCore::recoverCart()
```

Recovers cart information



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1384)




### <a name="method-redirect"></a>redirect

```php
mixed FrontControllerCore::redirect()
```

Redirects to redirect_after link



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 664](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L664)




### <a name="method-removeCSS"></a>removeCSS

```php
mixed FrontControllerCore::removeCSS(array|string $css_uri, string $css_media_type, boolean $check_path)
```

Removes CSS file(s) from page header



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1350)


#### Arguments
* $css_uri **array|string** - $media_uri Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)
* $css_media_type **string** - CSS media type
* $check_path **boolean** - If true, checks if files exists



### <a name="method-removeJS"></a>removeJS

```php
mixed FrontControllerCore::removeJS(array|string $js_uri, boolean $check_path)
```

Removes JS file(s) from page header



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1374)


#### Arguments
* $js_uri **array|string** - Path to file, or an array of paths
* $check_path **boolean** - If true, checks if files exists



### <a name="method-removeMedia"></a>removeMedia

```php
mixed FrontControllerCore::removeMedia(string|array $media_uri, string|null $css_media_type, boolean $check_path)
```

Removes media file(s) from page header



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1323)


#### Arguments
* $media_uri **string|array** - Path to file, or an array paths of like: array(array(uri =&gt; media_type), ...)
* $css_media_type **string|null** - CSS media type
* $check_path **boolean** - If true, checks if files exists



### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Starts the controller process (this method should not be overridden!)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L161)




### <a name="method-setDefaultCarrierSelection"></a>setDefaultCarrierSelection

```php
\number ParentOrderControllerCore::setDefaultCarrierSelection(array $carriers)
```

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 620](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L620)


#### Arguments
* $carriers **array**



### <a name="method-setMedia"></a>setMedia

```php
mixed ParentOrderControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/ParentOrderController.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L145)




### <a name="method-setMobileMedia"></a>setMobileMedia

```php
mixed FrontControllerCore::setMobileMedia()
```

Specific medias for mobile device.

If autoload directory is present in the mobile theme, these files will not be loaded

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 915](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L915)




### <a name="method-setMobileTemplate"></a>setMobileTemplate

```php
mixed FrontControllerCore::setMobileTemplate(string $template)
```

Checks if the template set is available for mobile themes,
otherwise front template is chosen.



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1551](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1551)


#### Arguments
* $template **string**



### <a name="method-setNoCarrier"></a>setNoCarrier

```php
mixed ParentOrderControllerCore::setNoCarrier()
```

Set id_carrier to 0 (no shipping price)



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L603)




### <a name="method-setRedirectAfter"></a>setRedirectAfter

```php
mixed ControllerCore::setRedirectAfter($url)
```

Set $this->redirect_after that will be used by redirect() after the process



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L276)


#### Arguments
* $url **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed FrontControllerCore::setTemplate(string $default_template)
```

Sets template file for page content output



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1417](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1417)


#### Arguments
* $default_template **string**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent(array|string $content)
```

Renders controller templates and generates page content



* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/Controller.php#L493)


#### Arguments
* $content **array|string** - Template file(s) to be rendered



### <a name="method-sslRedirection"></a>sslRedirection

```php
mixed FrontControllerCore::sslRedirection()
```

Redirects to correct protocol if settings and request methods don't match.



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L785)




### <a name="method-useMobileTheme"></a>useMobileTheme

```php
boolean FrontControllerCore::useMobileTheme()
```

Checks if mobile theme is active and in use.



* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L1450)




### <a name="method-validateDeliveryOption"></a>validateDeliveryOption

```php
boolean ParentOrderControllerCore::validateDeliveryOption(array $delivery_option)
```

Validate get/post param delivery option



* Visibility: **protected**
* Source: [controllers/front/ParentOrderController.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/ParentOrderController.php#L281)


#### Arguments
* $delivery_option **array**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean FrontControllerCore::viewAccess()
```

Check if the current user/visitor has valid view permissions



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/controller/FrontController.php#L174)



