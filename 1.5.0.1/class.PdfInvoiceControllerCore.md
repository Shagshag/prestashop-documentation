Class PdfInvoiceControllerCore
=====================





* Class name: PdfInvoiceControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/PdfInvoiceController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L30)


Contents
--------


### Properties

* [$content_only](#property-$content_only)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$filename](#property-$filename)
* [$template](#property-$template)
* [$auth](#property-$auth)
* [$authRedirection](#property-$authRedirection)
* [$cart](#property-$cart)
* [$cookie](#property-$cookie)
* [$currentCustomerGroups](#property-$currentCustomerGroups)
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
* [$context](#property-$context)
* [$css_files](#property-$css_files)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)

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
* [getTemplate](#method-getTemplate)
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
* [productSort](#method-productSort)
* [recoverCart](#method-recoverCart)
* [redirect](#method-redirect)
* [run](#method-run)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)




Properties
----------


### <a name="property-$content_only"></a>$content_only

```php
public mixed $content_only = true
```





* Visibility: **public**
* Source: [controllers/front/PdfInvoiceController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L35).


### <a name="property-$display_footer"></a>$display_footer

```php
protected mixed $display_footer = false
```





* Visibility: **protected**
* Source: [controllers/front/PdfInvoiceController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L33).


### <a name="property-$display_header"></a>$display_header

```php
protected mixed $display_header = false
```





* Visibility: **protected**
* Source: [controllers/front/PdfInvoiceController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L32).


### <a name="property-$filename"></a>$filename

```php
public mixed $filename
```





* Visibility: **public**
* Source: [controllers/front/PdfInvoiceController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L38).


### <a name="property-$template"></a>$template

```php
protected mixed $template
```





* Visibility: **protected**
* Source: [controllers/front/PdfInvoiceController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L37).


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L44).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public mixed $authRedirection = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L46).


### <a name="property-$cart"></a>$cart

```php
protected mixed $cart
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L35).


### <a name="property-$cookie"></a>$cookie

```php
protected mixed $cookie
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L35).


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

```php
protected mixed $currentCustomerGroups
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L54).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L30).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public mixed $guestAllowed = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L45).


### <a name="property-$initialized"></a>$initialized

```php
public mixed $initialized = false
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L52).


### <a name="property-$iso"></a>$iso

```php
public mixed $iso
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L37).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L35).


### <a name="property-$maintenance"></a>$maintenance

```php
protected mixed $maintenance = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L50).


### <a name="property-$n"></a>$n

```php
public mixed $n
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L42).


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

```php
public mixed $nb_items_per_page
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L56).


### <a name="property-$orderBy"></a>$orderBy

```php
public mixed $orderBy
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L39).


### <a name="property-$orderWay"></a>$orderWay

```php
public mixed $orderWay
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L40).


### <a name="property-$p"></a>$p

```php
public mixed $p
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L41).


### <a name="property-$restrictedCountry"></a>$restrictedCountry

```php
protected mixed $restrictedCountry = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L49).


### <a name="property-$smarty"></a>$smarty

```php
protected mixed $smarty
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L35).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L47).


### <a name="property-$ajax"></a>$ajax

```php
protected boolean $ajax = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L71).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L36).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L41).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FrontControllerCore::__construct()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L58)




### <a name="method-addCSS"></a>addCSS

```php
mixed FrontControllerCore::addCSS($css_uri, $css_media_type)
```

Add one or several CSS for front, checking if css files are overriden in theme/css/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 706](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L706)


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
* Source: [classes/FrontController.php line 729](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L729)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L274)


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
* Source: [classes/Controller.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L304)


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
* Source: [classes/Controller.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L285)


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
* Source: [classes/FrontController.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L437)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-checkAccess"></a>checkAccess

```php
void FrontControllerCore::checkAccess()
```

checkAccess



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L71)




### <a name="method-display"></a>display

```php
mixed PdfInvoiceControllerCore::display()
```





* Visibility: **public**
* Source: [controllers/front/PdfInvoiceController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L68)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L182)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L177)


#### Arguments
* $display **mixed**



### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

```php
mixed FrontControllerCore::displayMaintenancePage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L419)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

```php
mixed FrontControllerCore::displayRestrictedCountryPage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L430)




### <a name="method-geolocationManagement"></a>geolocationManagement

```php
mixed FrontControllerCore::geolocationManagement($defaultCountry)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L462)


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
* Source: [classes/Controller.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L113)


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
* Source: [classes/FrontController.php line 660](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L660)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed PdfInvoiceControllerCore::getTemplate($iso_country)
```

Returns the invoice template associated to the country iso_code



* Visibility: **public**
* Source: [controllers/front/PdfInvoiceController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L79)


#### Arguments
* $iso_country **mixed**



### <a name="method-init"></a>init

```php
mixed FrontControllerCore::init()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L76)




### <a name="method-initContent"></a>initContent

```php
mixed FrontControllerCore::initContent()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L377)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed FrontControllerCore::initCursedPage()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L382)




### <a name="method-initFooter"></a>initFooter

```php
mixed FrontControllerCore::initFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L574)




### <a name="method-initHeader"></a>initHeader

```php
mixed FrontControllerCore::initHeader()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L539)




### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

```php
mixed FrontControllerCore::isInWhitelistForGeolocation()
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 678](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L678)




### <a name="method-isTokenValid"></a>isTokenValid

```php
boolean FrontControllerCore::isTokenValid()
```

Check if token is valid



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L696)




### <a name="method-pagination"></a>pagination

```php
mixed FrontControllerCore::pagination($nbProducts)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L609)


#### Arguments
* $nbProducts **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed PdfInvoiceControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/PdfInvoiceController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/controllers/front/PdfInvoiceController.php#L40)




### <a name="method-preProcess"></a>preProcess

```php
mixed FrontControllerCore::preProcess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L373)




### <a name="method-process"></a>process

```php
mixed FrontControllerCore::process()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L387)




### <a name="method-productSort"></a>productSort

```php
mixed FrontControllerCore::productSort()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L582)




### <a name="method-recoverCart"></a>recoverCart

```php
mixed FrontControllerCore::recoverCart()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 748](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L748)




### <a name="method-redirect"></a>redirect

```php
mixed FrontControllerCore::redirect()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L391)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L134)




### <a name="method-setMedia"></a>setMedia

```php
mixed FrontControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/FrontController.php#L521)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Controller.php#L187)


#### Arguments
* $template **mixed**


