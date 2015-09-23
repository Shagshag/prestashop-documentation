Class StatisticsControllerCore
=====================





* Class name: StatisticsControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/StatisticsController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/front/StatisticsController.php#L28)


Contents
--------


### Properties

* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$param_token](#property-$param_token)
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
* [$ssl](#property-$ssl)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$css_files](#property-$css_files)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)
* [$template](#property-$template)

### Methods

* [__construct](#method-__construct)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [canonicalRedirection](#method-canonicalRedirection)
* [checkAccess](#method-checkAccess)
* [display](#method-display)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayMaintenancePage](#method-displayMaintenancePage)
* [displayRestrictedCountryPage](#method-displayRestrictedCountryPage)
* [geolocationManagement](#method-geolocationManagement)
* [getController](#method-getController)
* [getCurrentCustomerGroups](#method-getCurrentCustomerGroups)
* [getLiveEditFooter](#method-getLiveEditFooter)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [isInWhitelistForGeolocation](#method-isInWhitelistForGeolocation)
* [isTokenValid](#method-isTokenValid)
* [pagination](#method-pagination)
* [postProcess](#method-postProcess)
* [preProcess](#method-preProcess)
* [process](#method-process)
* [processNavigationStats](#method-processNavigationStats)
* [processPageTime](#method-processPageTime)
* [productSort](#method-productSort)
* [recoverCart](#method-recoverCart)
* [redirect](#method-redirect)
* [run](#method-run)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$display_footer"></a>$display_footer

```php
public mixed $display_footer = false
```





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/front/StatisticsController.php#L31).


### <a name="property-$display_header"></a>$display_header

```php
public mixed $display_header = false
```





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/front/StatisticsController.php#L30).


### <a name="property-$param_token"></a>$param_token

```php
protected mixed $param_token
```





* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/front/StatisticsController.php#L33).


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L44).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public mixed $authRedirection = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L46).


### <a name="property-$cart"></a>$cart

```php
protected mixed $cart
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L35).


### <a name="property-$cookie"></a>$cookie

```php
protected mixed $cookie
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L35).


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

```php
protected mixed $currentCustomerGroups
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L57).


### <a name="property-$display_column_left"></a>$display_column_left

```php
public mixed $display_column_left = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L52).


### <a name="property-$display_column_right"></a>$display_column_right

```php
public mixed $display_column_right = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L53).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L30).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public mixed $guestAllowed = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L45).


### <a name="property-$initialized"></a>$initialized

```php
public mixed $initialized = false
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L55).


### <a name="property-$iso"></a>$iso

```php
public mixed $iso
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L37).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L35).


### <a name="property-$maintenance"></a>$maintenance

```php
protected mixed $maintenance = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L50).


### <a name="property-$n"></a>$n

```php
public mixed $n
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L42).


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

```php
public mixed $nb_items_per_page
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L59).


### <a name="property-$orderBy"></a>$orderBy

```php
public mixed $orderBy
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L39).


### <a name="property-$orderWay"></a>$orderWay

```php
public mixed $orderWay
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L40).


### <a name="property-$p"></a>$p

```php
public mixed $p
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L41).


### <a name="property-$restrictedCountry"></a>$restrictedCountry

```php
protected mixed $restrictedCountry = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L49).


### <a name="property-$smarty"></a>$smarty

```php
protected mixed $smarty
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L35).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L47).


### <a name="property-$ajax"></a>$ajax

```php
protected boolean $ajax = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L36).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L41).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L73).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L56).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FrontControllerCore::__construct()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L61)




### <a name="method-addCSS"></a>addCSS

```php
mixed FrontControllerCore::addCSS($css_uri, $css_media_type)
```

Add one or several CSS for front, checking if css files are overriden in theme/css/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L820)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### <a name="method-addJS"></a>addJS

```php
mixed FrontControllerCore::addJS($js_uri)
```

Add one or several JS files for front, checking if js files are overriden in theme/js/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L843)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L288)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
void ControllerCore::addJqueryPlugin($name, $folder)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L318)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L299)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed FrontControllerCore::canonicalRedirection($canonicalURL)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L546)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-checkAccess"></a>checkAccess

```php
boolean FrontControllerCore::checkAccess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L74)




### <a name="method-display"></a>display

```php
mixed FrontControllerCore::display()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 467](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L467)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed FrontControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L442)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed FrontControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L410)


#### Arguments
* $display **mixed**



### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

```php
mixed FrontControllerCore::displayMaintenancePage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L526)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

```php
mixed FrontControllerCore::displayRestrictedCountryPage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L538)




### <a name="method-geolocationManagement"></a>geolocationManagement

```php
mixed FrontControllerCore::geolocationManagement($defaultCountry)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L572)


#### Arguments
* $defaultCountry **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L125)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getCurrentCustomerGroups"></a>getCurrentCustomerGroups

```php
mixed FrontControllerCore::getCurrentCustomerGroups()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L774)




### <a name="method-getLiveEditFooter"></a>getLiveEditFooter

```php
mixed FrontControllerCore::getLiveEditFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 677](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L677)




### <a name="method-init"></a>init

```php
mixed FrontControllerCore::init()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L89)




### <a name="method-initContent"></a>initContent

```php
mixed FrontControllerCore::initContent()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L395)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed FrontControllerCore::initCursedPage()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L453)




### <a name="method-initFooter"></a>initFooter

```php
mixed FrontControllerCore::initFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L669)




### <a name="method-initHeader"></a>initHeader

```php
mixed FrontControllerCore::initHeader()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L649)




### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

```php
mixed FrontControllerCore::isInWhitelistForGeolocation()
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 792](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L792)




### <a name="method-isTokenValid"></a>isTokenValid

```php
boolean FrontControllerCore::isTokenValid()
```

Check if token is valid



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 810](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L810)




### <a name="method-pagination"></a>pagination

```php
mixed FrontControllerCore::pagination($nbProducts)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L723)


#### Arguments
* $nbProducts **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed StatisticsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/front/StatisticsController.php#L35)




### <a name="method-preProcess"></a>preProcess

```php
mixed FrontControllerCore::preProcess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L391)




### <a name="method-process"></a>process

```php
mixed FrontControllerCore::process()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L458)




### <a name="method-processNavigationStats"></a>processNavigationStats

```php
mixed StatisticsControllerCore::processNavigationStats()
```

Log statistics on navigation (resolution, plugins, etc.)



* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/front/StatisticsController.php#L52)




### <a name="method-processPageTime"></a>processPageTime

```php
mixed StatisticsControllerCore::processPageTime()
```

Log statistics on time spend on pages



* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/controllers/front/StatisticsController.php#L75)




### <a name="method-productSort"></a>productSort

```php
mixed FrontControllerCore::productSort()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L696)




### <a name="method-recoverCart"></a>recoverCart

```php
mixed FrontControllerCore::recoverCart()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 862](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L862)




### <a name="method-redirect"></a>redirect

```php
mixed FrontControllerCore::redirect()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L462)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L146)




### <a name="method-setMedia"></a>setMedia

```php
mixed FrontControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L631)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/Controller.php#L201)


#### Arguments
* $template **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean FrontControllerCore::viewAccess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/controller/FrontController.php#L84)



