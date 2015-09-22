FrontControllerCore
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


* Class name: FrontControllerCore
* Parent class: [Controller](ControllerCore)
* This class is defined in [classes/controller/FrontController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L27)





Properties
----------

* [$smarty](#property-$smarty)
* [$cookie](#property-$cookie)
* [$link](#property-$link)
* [$cart](#property-$cart)
* [$errors](#property-$errors)
* [$iso](#property-$iso)
* [$orderBy](#property-$orderBy)
* [$orderWay](#property-$orderWay)
* [$p](#property-$p)
* [$n](#property-$n)
* [$auth](#property-$auth)
* [$guestAllowed](#property-$guestAllowed)
* [$authRedirection](#property-$authRedirection)
* [$ssl](#property-$ssl)
* [$restrictedCountry](#property-$restrictedCountry)
* [$maintenance](#property-$maintenance)
* [$display_column_left](#property-$display_column_left)
* [$display_column_right](#property-$display_column_right)
* [$initialized](#property-$initialized)
* [$currentCustomerGroups](#property-$currentCustomerGroups)
* [$nb_items_per_page](#property-$nb_items_per_page)

Methods
-------
* [__construct](#method-__construct)
* [checkAccess](#method-checkAccess)
* [viewAccess](#method-viewAccess)
* [init](#method-init)
* [postProcess](#method-postProcess)
* [initContent](#method-initContent)
* [displayHeader](#method-displayHeader)
* [displayFooter](#method-displayFooter)
* [initCursedPage](#method-initCursedPage)
* [process](#method-process)
* [redirect](#method-redirect)
* [displayContent](#method-displayContent)
* [display](#method-display)
* [displayMaintenancePage](#method-displayMaintenancePage)
* [displayRestrictedCountryPage](#method-displayRestrictedCountryPage)
* [sslRedirection](#method-sslRedirection)
* [canonicalRedirection](#method-canonicalRedirection)
* [geolocationManagement](#method-geolocationManagement)
* [setMobileMedia](#method-setMobileMedia)
* [setMedia](#method-setMedia)
* [initHeader](#method-initHeader)
* [initFooter](#method-initFooter)
* [checkLiveEditAccess](#method-checkLiveEditAccess)
* [getLiveEditFooter](#method-getLiveEditFooter)
* [productSort](#method-productSort)
* [pagination](#method-pagination)
* [getCurrentCustomerGroups](#method-getCurrentCustomerGroups)
* [isInWhitelistForGeolocation](#method-isInWhitelistForGeolocation)
* [isTokenValid](#method-isTokenValid)
* [addMedia](#method-addMedia)
* [removeMedia](#method-removeMedia)
* [addCSS](#method-addCSS)
* [removeCSS](#method-removeCSS)
* [addJS](#method-addJS)
* [removeJS](#method-removeJS)
* [recoverCart](#method-recoverCart)
* [setTemplate](#method-setTemplate)
* [getOverrideTemplate](#method-getOverrideTemplate)
* [useMobileTheme](#method-useMobileTheme)
* [getThemeDir](#method-getThemeDir)
* [getOverrideThemeDir](#method-getOverrideThemeDir)
* [getLayout](#method-getLayout)
* [getTemplatePath](#method-getTemplatePath)
* [setMobileTemplate](#method-setMobileTemplate)
* [initLogoAndFavicon](#method-initLogoAndFavicon)
* [addColorsToProductList](#method-addColorsToProductList)
* [getColorsListCacheId](#method-getColorsListCacheId)




Properties
----------


### <a name="property-$smarty"></a>$smarty

    protected  $smarty





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/controller/FrontController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L33)


### <a name="property-$cookie"></a>$cookie

    protected  $cookie





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/controller/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L39)


### <a name="property-$link"></a>$link

    protected  $link





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/controller/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L45)


### <a name="property-$cart"></a>$cart

    protected  $cart





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/controller/FrontController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L51)


### <a name="property-$errors"></a>$errors

    public array $errors = array()





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L54)


### <a name="property-$iso"></a>$iso

    public string $iso





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L57)


### <a name="property-$orderBy"></a>$orderBy

    public string $orderBy





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L60)


### <a name="property-$orderWay"></a>$orderWay

    public string $orderWay





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L63)


### <a name="property-$p"></a>$p

    public integer $p





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L66)


### <a name="property-$n"></a>$n

    public integer $n





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L69)


### <a name="property-$auth"></a>$auth

    public boolean $auth = false





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L72)


### <a name="property-$guestAllowed"></a>$guestAllowed

    public boolean $guestAllowed = false

If set to true, user can be logged in as guest when checking if logged in.



* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L80)


### <a name="property-$authRedirection"></a>$authRedirection

    public boolean $authRedirection = false

Route of PrestaShop page to redirect to after forced login.



* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L88)


### <a name="property-$ssl"></a>$ssl

    public boolean $ssl = false





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L91)


### <a name="property-$restrictedCountry"></a>$restrictedCountry

    protected boolean $restrictedCountry = false





* Visibility: **protected**
* This property is defined in [classes/controller/FrontController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L94)


### <a name="property-$maintenance"></a>$maintenance

    protected boolean $maintenance = false





* Visibility: **protected**
* This property is defined in [classes/controller/FrontController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L97)


### <a name="property-$display_column_left"></a>$display_column_left

    public boolean $display_column_left = true





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L100)


### <a name="property-$display_column_right"></a>$display_column_right

    public boolean $display_column_right = true





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L103)


### <a name="property-$initialized"></a>$initialized

    public boolean $initialized = false

True if controller has already been initialized.

Prevents initializing controller more than once.

* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/controller/FrontController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L111)


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

    protected array $currentCustomerGroups





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/controller/FrontController.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L116)


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

    public integer $nb_items_per_page





* Visibility: **public**
* This property is defined in [classes/controller/FrontController.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L121)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed FrontControllerCore::__construct()

Controller constructor



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L128)




### <a name="method-checkAccess"></a>checkAccess

    boolean FrontControllerCore::checkAccess()

Check if the controller is available for the current user/visitor



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L163)




### <a name="method-viewAccess"></a>viewAccess

    boolean FrontControllerCore::viewAccess()

Check if the current user/visitor has valid view permissions



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L174)




### <a name="method-init"></a>init

    mixed FrontControllerCore::init()

Initializes front controller: sets smarty variables,
class properties, redirects depending on context, etc.



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L198)




### <a name="method-postProcess"></a>postProcess

    mixed FrontControllerCore::postProcess()

Method that is executed after init() and checkAccess().

Used to process user input.

* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L560)




### <a name="method-initContent"></a>initContent

    mixed FrontControllerCore::initContent()

Initializes common front page content: header, footer and side columns



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L567)




### <a name="method-displayHeader"></a>displayHeader

    mixed FrontControllerCore::displayHeader(boolean $display)

Compiles and outputs page header section (including HTML <head>)



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L595)


#### Arguments
* $display **boolean** - &lt;p&gt;If true, renders visual page header section&lt;/p&gt;



### <a name="method-displayFooter"></a>displayFooter

    mixed FrontControllerCore::displayFooter($display)

Compiles and outputs page footer section



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L636)


#### Arguments
* $display **mixed**



### <a name="method-initCursedPage"></a>initCursedPage

    mixed FrontControllerCore::initCursedPage()

Renders and outputs maintenance page and ends controller process.



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 645](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L645)




### <a name="method-process"></a>process

    mixed FrontControllerCore::process()

Called before compiling common page sections (header, footer, columns).

Good place to modify smarty variables.

* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L656)




### <a name="method-redirect"></a>redirect

    mixed FrontControllerCore::redirect()

Redirects to redirect_after link



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 665](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L665)




### <a name="method-displayContent"></a>displayContent

    mixed FrontControllerCore::displayContent()

Renders page content.

Used for retrocompatibility with PS 1.4

* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L674)




### <a name="method-display"></a>display

    boolean FrontControllerCore::display()

Compiles and outputs full page content



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L685)




### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

    mixed FrontControllerCore::displayMaintenancePage()

Displays maintenance page if shop is closed.



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L747)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

    mixed FrontControllerCore::displayRestrictedCountryPage()

Displays 'country restricted' page if user's country is not allowed.



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 770](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L770)




### <a name="method-sslRedirection"></a>sslRedirection

    mixed FrontControllerCore::sslRedirection()

Redirects to correct protocol if settings and request methods don't match.



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L785)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

    mixed FrontControllerCore::canonicalRedirection(string $canonical_url)

Redirects to canonical URL



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L806)


#### Arguments
* $canonical_url **string**



### <a name="method-geolocationManagement"></a>geolocationManagement

    \Country|false FrontControllerCore::geolocationManagement(\Country $default_country)

Geolocation management



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L857)


#### Arguments
* $default_country **[Country](CountryCore)**



### <a name="method-setMobileMedia"></a>setMobileMedia

    mixed FrontControllerCore::setMobileMedia()

Specific medias for mobile device.

If autoload directory is present in the mobile theme, these files will not be loaded

* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 915](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L915)




### <a name="method-setMedia"></a>setMedia

    boolean FrontControllerCore::setMedia()

Sets controller CSS and JS files.



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L939)




### <a name="method-initHeader"></a>initHeader

    mixed FrontControllerCore::initHeader()

Initializes page header variables



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 997](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L997)




### <a name="method-initFooter"></a>initFooter

    mixed FrontControllerCore::initFooter()

Initializes page footer variables



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1019](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1019)




### <a name="method-checkLiveEditAccess"></a>checkLiveEditAccess

    boolean FrontControllerCore::checkLiveEditAccess()

Checks if the user can use Live Edit feature



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1045](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1045)




### <a name="method-getLiveEditFooter"></a>getLiveEditFooter

    string FrontControllerCore::getLiveEditFooter()

Renders Live Edit widget



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1063](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1063)




### <a name="method-productSort"></a>productSort

    mixed FrontControllerCore::productSort()

Assigns product list page sorting variables



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1082](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1082)




### <a name="method-pagination"></a>pagination

    mixed FrontControllerCore::pagination(integer|null $total_products)

Assigns product list page pagination variables



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1121)


#### Arguments
* $total_products **integer|null**



### <a name="method-getCurrentCustomerGroups"></a>getCurrentCustomerGroups

    array FrontControllerCore::getCurrentCustomerGroups()

Sets and returns customer groups that the current customer(visitor) belongs to.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/controller/FrontController.php line 1196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1196)




### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

    boolean FrontControllerCore::isInWhitelistForGeolocation()

Checks if user's location is whitelisted.



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/controller/FrontController.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1224)




### <a name="method-isTokenValid"></a>isTokenValid

    boolean FrontControllerCore::isTokenValid()

Checks if token is valid



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1262)




### <a name="method-addMedia"></a>addMedia

    true|void FrontControllerCore::addMedia(string|array $media_uri, string|null $css_media_type, integer|null $offset, boolean $remove, boolean $check_path)

Adds a media file(s) (CSS, JS) to page header



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1281)


#### Arguments
* $media_uri **string|array** - &lt;p&gt;Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string|null** - &lt;p&gt;CSS media type&lt;/p&gt;
* $offset **integer|null**
* $remove **boolean** - &lt;p&gt;If True, removes media files&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### <a name="method-removeMedia"></a>removeMedia

    mixed FrontControllerCore::removeMedia(string|array $media_uri, string|null $css_media_type, boolean $check_path)

Removes media file(s) from page header



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1346](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1346)


#### Arguments
* $media_uri **string|array** - &lt;p&gt;Path to file, or an array paths of like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string|null** - &lt;p&gt;CSS media type&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### <a name="method-addCSS"></a>addCSS

    true|void FrontControllerCore::addCSS(array|string $css_uri, string $css_media_type, integer|null $offset, boolean $check_path)

Add one or several CSS for front, checking if css files are overridden in theme/css/modules/ directory



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1361)


#### Arguments
* $css_uri **array|string** - &lt;p&gt;$media_uri Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string** - &lt;p&gt;CSS media type&lt;/p&gt;
* $offset **integer|null**
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### <a name="method-removeCSS"></a>removeCSS

    mixed FrontControllerCore::removeCSS(array|string $css_uri, string $css_media_type, boolean $check_path)

Removes CSS file(s) from page header



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1373)


#### Arguments
* $css_uri **array|string** - &lt;p&gt;$media_uri Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string** - &lt;p&gt;CSS media type&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### <a name="method-addJS"></a>addJS

    true|void FrontControllerCore::addJS(array|string $js_uri, boolean $check_path)

Add one or several JS files for front, checking if js files are overridden in theme/js/modules/ directory



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1386](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1386)


#### Arguments
* $js_uri **array|string** - &lt;p&gt;Path to file, or an array of paths&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### <a name="method-removeJS"></a>removeJS

    mixed FrontControllerCore::removeJS(array|string $js_uri, boolean $check_path)

Removes JS file(s) from page header



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1397](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1397)


#### Arguments
* $js_uri **array|string** - &lt;p&gt;Path to file, or an array of paths&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### <a name="method-recoverCart"></a>recoverCart

    integer|false FrontControllerCore::recoverCart()

Recovers cart information



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 1407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1407)




### <a name="method-setTemplate"></a>setTemplate

    mixed FrontControllerCore::setTemplate(string $default_template)

Sets template file for page content output



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1437)


#### Arguments
* $default_template **string**



### <a name="method-getOverrideTemplate"></a>getOverrideTemplate

    string|boolean FrontControllerCore::getOverrideTemplate()

Returns an overridden template path (if any) for this controller.

If not overridden, will return false. This method can be easily overriden in a
specific controller.

* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1459](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1459)




### <a name="method-useMobileTheme"></a>useMobileTheme

    boolean FrontControllerCore::useMobileTheme()

Checks if mobile theme is active and in use.



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 1470](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1470)




### <a name="method-getThemeDir"></a>getThemeDir

    string FrontControllerCore::getThemeDir()

Returns theme directory (regular or mobile)



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 1487](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1487)




### <a name="method-getOverrideThemeDir"></a>getOverrideThemeDir

    string FrontControllerCore::getOverrideThemeDir()

Returns theme override directory (regular or mobile)



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 1498](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1498)




### <a name="method-getLayout"></a>getLayout

    boolean|string FrontControllerCore::getLayout()

Returns the layout corresponding to the current page by using the override system
Ex:
On the url: http://localhost/index.php?id_product=1&controller=product, this method will
check if the layout exists in the following files (in that order), and return the first found:
- /themes/default/override/layout-product-1.tpl
- /themes/default/override/layout-product.tpl
- /themes/default/layout.tpl



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1515](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1515)




### <a name="method-getTemplatePath"></a>getTemplatePath

    string FrontControllerCore::getTemplatePath(string $template)

Returns template path



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1545](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1545)


#### Arguments
* $template **string**



### <a name="method-setMobileTemplate"></a>setMobileTemplate

    mixed FrontControllerCore::setMobileTemplate(string $template)

Checks if the template set is available for mobile themes,
otherwise front template is chosen.



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1573)


#### Arguments
* $template **string**



### <a name="method-initLogoAndFavicon"></a>initLogoAndFavicon

    array FrontControllerCore::initLogoAndFavicon()

Returns logo and favicon variables, depending
on active theme type (regular or mobile)



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1612](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1612)




### <a name="method-addColorsToProductList"></a>addColorsToProductList

    mixed FrontControllerCore::addColorsToProductList(array $products)

Renders and adds color list HTML for each product in a list



* Visibility: **public**
* This method is defined in [classes/controller/FrontController.php line 1635](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1635)


#### Arguments
* $products **array**



### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

    string FrontControllerCore::getColorsListCacheId(integer $id_product)

Returns cache ID for product color list



* Visibility: **protected**
* This method is defined in [classes/controller/FrontController.php line 1683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/FrontController.php#L1683)


#### Arguments
* $id_product **integer**


