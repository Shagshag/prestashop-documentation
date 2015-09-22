Class FrontControllerCore
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

* Class name: FrontControllerCore
* Parent class: [Controller](class.ControllerCore.md)
* Source: [classes/controller/FrontController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L27)


Contents
--------


### Properties

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

### Methods

* [__construct](#method-__construct)
* [addCSS](#method-addCSS)
* [addColorsToProductList](#method-addColorsToProductList)
* [addJS](#method-addJS)
* [addMedia](#method-addMedia)
* [canonicalRedirection](#method-canonicalRedirection)
* [checkAccess](#method-checkAccess)
* [checkLiveEditAccess](#method-checkLiveEditAccess)
* [display](#method-display)
* [displayContent](#method-displayContent)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayMaintenancePage](#method-displayMaintenancePage)
* [displayRestrictedCountryPage](#method-displayRestrictedCountryPage)
* [geolocationManagement](#method-geolocationManagement)
* [getColorsListCacheId](#method-getColorsListCacheId)
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
* [isInWhitelistForGeolocation](#method-isInWhitelistForGeolocation)
* [isTokenValid](#method-isTokenValid)
* [pagination](#method-pagination)
* [postProcess](#method-postProcess)
* [process](#method-process)
* [productSort](#method-productSort)
* [recoverCart](#method-recoverCart)
* [redirect](#method-redirect)
* [removeCSS](#method-removeCSS)
* [removeJS](#method-removeJS)
* [removeMedia](#method-removeMedia)
* [setMedia](#method-setMedia)
* [setMobileMedia](#method-setMobileMedia)
* [setMobileTemplate](#method-setMobileTemplate)
* [setTemplate](#method-setTemplate)
* [sslRedirection](#method-sslRedirection)
* [useMobileTheme](#method-useMobileTheme)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = false
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L43).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public mixed $authRedirection = false
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L45).


### <a name="property-$cart"></a>$cart

```php
protected mixed $cart
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L34).


### <a name="property-$cookie"></a>$cookie

```php
protected mixed $cookie
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L34).


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

```php
protected mixed $currentCustomerGroups
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/controller/FrontController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L56).


### <a name="property-$display_column_left"></a>$display_column_left

```php
public mixed $display_column_left = true
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L51).


### <a name="property-$display_column_right"></a>$display_column_right

```php
public mixed $display_column_right = true
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L52).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L29).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public mixed $guestAllowed = false
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L44).


### <a name="property-$initialized"></a>$initialized

```php
public mixed $initialized = false
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/controller/FrontController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L54).


### <a name="property-$iso"></a>$iso

```php
public mixed $iso
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L36).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L34).


### <a name="property-$maintenance"></a>$maintenance

```php
protected mixed $maintenance = false
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L49).


### <a name="property-$n"></a>$n

```php
public mixed $n
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L41).


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

```php
public mixed $nb_items_per_page
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L58).


### <a name="property-$orderBy"></a>$orderBy

```php
public mixed $orderBy
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L38).


### <a name="property-$orderWay"></a>$orderWay

```php
public mixed $orderWay
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L39).


### <a name="property-$p"></a>$p

```php
public mixed $p
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L40).


### <a name="property-$restrictedCountry"></a>$restrictedCountry

```php
protected mixed $restrictedCountry = false
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L48).


### <a name="property-$smarty"></a>$smarty

```php
protected mixed $smarty
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L34).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = false
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L46).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FrontControllerCore::__construct()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L60)




### <a name="method-addCSS"></a>addCSS

```php
mixed FrontControllerCore::addCSS($css_uri, string $css_media_type, integer $offset, boolean $check_path)
```

Add one or several CSS for front, checking if css files are overriden in theme/css/modules/ directory



* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1092](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1092)


#### Arguments
* $css_uri **mixed**
* $css_media_type **string**
* $offset **integer**
* $check_path **boolean**



### <a name="method-addColorsToProductList"></a>addColorsToProductList

```php
mixed FrontControllerCore::addColorsToProductList($products)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1310](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1310)


#### Arguments
* $products **mixed**



### <a name="method-addJS"></a>addJS

```php
mixed FrontControllerCore::addJS($js_uri, boolean $check_path)
```

Add one or several JS files for front, checking if js files are overriden in theme/js/modules/ directory



* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1108)


#### Arguments
* $js_uri **mixed**
* $check_path **boolean**



### <a name="method-addMedia"></a>addMedia

```php
mixed FrontControllerCore::addMedia($media_uri, $css_media_type, $offset, $remove, $check_path)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1022](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1022)


#### Arguments
* $media_uri **mixed**
* $css_media_type **mixed**
* $offset **mixed**
* $remove **mixed**
* $check_path **mixed**



### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed FrontControllerCore::canonicalRedirection($canonical_url)
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L643)


#### Arguments
* $canonical_url **mixed**



### <a name="method-checkAccess"></a>checkAccess

```php
boolean FrontControllerCore::checkAccess()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L93)




### <a name="method-checkLiveEditAccess"></a>checkLiveEditAccess

```php
mixed FrontControllerCore::checkLiveEditAccess()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L851)




### <a name="method-display"></a>display

```php
mixed FrontControllerCore::display()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L534)




### <a name="method-displayContent"></a>displayContent

```php
mixed FrontControllerCore::displayContent()
```

1.4 retrocompatibility



* Visibility: **public**
* Source: [classes/controller/FrontController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L530)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed FrontControllerCore::displayFooter($display)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L507)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed FrontControllerCore::displayHeader($display)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L469)


#### Arguments
* $display **mixed**



### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

```php
mixed FrontControllerCore::displayMaintenancePage()
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 592](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L592)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

```php
mixed FrontControllerCore::displayRestrictedCountryPage()
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L615)




### <a name="method-geolocationManagement"></a>geolocationManagement

```php
mixed FrontControllerCore::geolocationManagement($default_country)
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L685)


#### Arguments
* $default_country **mixed**



### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

```php
mixed FrontControllerCore::getColorsListCacheId($id_product)
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 1347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1347)


#### Arguments
* $id_product **mixed**



### <a name="method-getCurrentCustomerGroups"></a>getCurrentCustomerGroups

```php
mixed FrontControllerCore::getCurrentCustomerGroups()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/FrontController.php line 963](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L963)




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
* Source: [classes/controller/FrontController.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1209)




### <a name="method-getLiveEditFooter"></a>getLiveEditFooter

```php
mixed FrontControllerCore::getLiveEditFooter()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 860](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L860)




### <a name="method-getOverrideTemplate"></a>getOverrideTemplate

```php
boolean FrontControllerCore::getOverrideTemplate()
```

Returns the template corresponding to the current page.

By default this method return false but could easily be overridden in a specific controller

* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1171)




### <a name="method-getOverrideThemeDir"></a>getOverrideThemeDir

```php
mixed FrontControllerCore::getOverrideThemeDir()
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 1192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1192)




### <a name="method-getTemplatePath"></a>getTemplatePath

```php
mixed FrontControllerCore::getTemplatePath($template)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1232)


#### Arguments
* $template **mixed**



### <a name="method-getThemeDir"></a>getThemeDir

```php
mixed FrontControllerCore::getThemeDir()
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 1187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1187)




### <a name="method-init"></a>init

```php
mixed FrontControllerCore::init()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L108)




### <a name="method-initContent"></a>initContent

```php
mixed FrontControllerCore::initContent()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L446)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed FrontControllerCore::initCursedPage()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L513)




### <a name="method-initFooter"></a>initFooter

```php
mixed FrontControllerCore::initFooter()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L831)




### <a name="method-initHeader"></a>initHeader

```php
mixed FrontControllerCore::initHeader()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L812)




### <a name="method-initLogoAndFavicon"></a>initLogoAndFavicon

```php
array FrontControllerCore::initLogoAndFavicon()
```

Return an array with specific logo and favicon,
if mobile device



* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1293)




### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

```php
mixed FrontControllerCore::isInWhitelistForGeolocation()
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/controller/FrontController.php line 982](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L982)




### <a name="method-isTokenValid"></a>isTokenValid

```php
boolean FrontControllerCore::isTokenValid()
```

Check if token is valid



* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1014](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1014)




### <a name="method-pagination"></a>pagination

```php
mixed FrontControllerCore::pagination($total_products)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 904](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L904)


#### Arguments
* $total_products **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed FrontControllerCore::postProcess()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L442)




### <a name="method-process"></a>process

```php
mixed FrontControllerCore::process()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L518)




### <a name="method-productSort"></a>productSort

```php
mixed FrontControllerCore::productSort()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 877](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L877)




### <a name="method-recoverCart"></a>recoverCart

```php
mixed FrontControllerCore::recoverCart()
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1118)




### <a name="method-redirect"></a>redirect

```php
mixed FrontControllerCore::redirect()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L522)




### <a name="method-removeCSS"></a>removeCSS

```php
mixed FrontControllerCore::removeCSS($css_uri, $css_media_type, $check_path)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1097](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1097)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**
* $check_path **mixed**



### <a name="method-removeJS"></a>removeJS

```php
mixed FrontControllerCore::removeJS($js_uri, $check_path)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1113)


#### Arguments
* $js_uri **mixed**
* $check_path **mixed**



### <a name="method-removeMedia"></a>removeMedia

```php
mixed FrontControllerCore::removeMedia($media_uri, $css_media_type, $check_path)
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1079)


#### Arguments
* $media_uri **mixed**
* $css_media_type **mixed**
* $check_path **mixed**



### <a name="method-setMedia"></a>setMedia

```php
mixed FrontControllerCore::setMedia()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L767)




### <a name="method-setMobileMedia"></a>setMobileMedia

```php
mixed FrontControllerCore::setMobileMedia()
```

Specific medias for mobile device.

if autoload directory is present in the mobile theme, these files will not be loaded

* Visibility: **public**
* Source: [classes/controller/FrontController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L746)




### <a name="method-setMobileTemplate"></a>setMobileTemplate

```php
mixed FrontControllerCore::setMobileTemplate($template)
```

This checks if the template set is available for mobile themes,
otherwise the front template is choosen.



* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1258)


#### Arguments
* $template **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed FrontControllerCore::setTemplate($default_template)
```

This is overrided to manage is behaviour
if a customer access to the site with mobile device.



* Visibility: **public**
* Source: [classes/controller/FrontController.php line 1150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1150)


#### Arguments
* $default_template **mixed**



### <a name="method-sslRedirection"></a>sslRedirection

```php
mixed FrontControllerCore::sslRedirection()
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L627)




### <a name="method-useMobileTheme"></a>useMobileTheme

```php
mixed FrontControllerCore::useMobileTheme()
```





* Visibility: **protected**
* Source: [classes/controller/FrontController.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L1176)




### <a name="method-viewAccess"></a>viewAccess

```php
boolean FrontControllerCore::viewAccess()
```





* Visibility: **public**
* Source: [classes/controller/FrontController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/controller/FrontController.php#L103)



