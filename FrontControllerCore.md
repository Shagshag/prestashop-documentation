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
* Namespace: 
* Parent class: Controller





Properties
----------


### $smarty

    protected  $smarty





* Visibility: **protected**
* This property is **static**.


### $cookie

    protected  $cookie





* Visibility: **protected**
* This property is **static**.


### $link

    protected  $link





* Visibility: **protected**
* This property is **static**.


### $cart

    protected  $cart





* Visibility: **protected**
* This property is **static**.


### $errors

    public array $errors = array()





* Visibility: **public**


### $iso

    public string $iso





* Visibility: **public**


### $orderBy

    public string $orderBy





* Visibility: **public**


### $orderWay

    public string $orderWay





* Visibility: **public**


### $p

    public integer $p





* Visibility: **public**


### $n

    public integer $n





* Visibility: **public**


### $auth

    public boolean $auth = false





* Visibility: **public**


### $guestAllowed

    public boolean $guestAllowed = false

If set to true, user can be logged in as guest when checking if logged in.



* Visibility: **public**


### $authRedirection

    public boolean $authRedirection = false

Route of PrestaShop page to redirect to after forced login.



* Visibility: **public**


### $ssl

    public boolean $ssl = false





* Visibility: **public**


### $restrictedCountry

    protected boolean $restrictedCountry = false





* Visibility: **protected**


### $maintenance

    protected boolean $maintenance = false





* Visibility: **protected**


### $display_column_left

    public boolean $display_column_left = true





* Visibility: **public**


### $display_column_right

    public boolean $display_column_right = true





* Visibility: **public**


### $initialized

    public boolean $initialized = false

True if controller has already been initialized.

Prevents initializing controller more than once.

* Visibility: **public**
* This property is **static**.


### $currentCustomerGroups

    protected array $currentCustomerGroups





* Visibility: **protected**
* This property is **static**.


### $nb_items_per_page

    public integer $nb_items_per_page





* Visibility: **public**


Methods
-------


### __construct

    mixed FrontControllerCore::__construct()

Controller constructor



* Visibility: **public**




### checkAccess

    boolean FrontControllerCore::checkAccess()

Check if the controller is available for the current user/visitor



* Visibility: **public**




### viewAccess

    boolean FrontControllerCore::viewAccess()

Check if the current user/visitor has valid view permissions



* Visibility: **public**




### init

    mixed FrontControllerCore::init()

Initializes front controller: sets smarty variables,
class properties, redirects depending on context, etc.



* Visibility: **public**




### postProcess

    mixed FrontControllerCore::postProcess()

Method that is executed after init() and checkAccess().

Used to process user input.

* Visibility: **public**




### initContent

    mixed FrontControllerCore::initContent()

Initializes common front page content: header, footer and side columns



* Visibility: **public**




### displayHeader

    mixed FrontControllerCore::displayHeader(boolean $display)

Compiles and outputs page header section (including HTML <head>)



* Visibility: **public**


#### Arguments
* $display **boolean** - &lt;p&gt;If true, renders visual page header section&lt;/p&gt;



### displayFooter

    mixed FrontControllerCore::displayFooter($display)

Compiles and outputs page footer section



* Visibility: **public**


#### Arguments
* $display **mixed**



### initCursedPage

    mixed FrontControllerCore::initCursedPage()

Renders and outputs maintenance page and ends controller process.



* Visibility: **public**




### process

    mixed FrontControllerCore::process()

Called before compiling common page sections (header, footer, columns).

Good place to modify smarty variables.

* Visibility: **public**




### redirect

    mixed FrontControllerCore::redirect()

Redirects to redirect_after link



* Visibility: **protected**




### displayContent

    mixed FrontControllerCore::displayContent()

Renders page content.

Used for retrocompatibility with PS 1.4

* Visibility: **public**




### display

    boolean FrontControllerCore::display()

Compiles and outputs full page content



* Visibility: **public**




### displayMaintenancePage

    mixed FrontControllerCore::displayMaintenancePage()

Displays maintenance page if shop is closed.



* Visibility: **protected**




### displayRestrictedCountryPage

    mixed FrontControllerCore::displayRestrictedCountryPage()

Displays 'country restricted' page if user's country is not allowed.



* Visibility: **protected**




### sslRedirection

    mixed FrontControllerCore::sslRedirection()

Redirects to correct protocol if settings and request methods don't match.



* Visibility: **protected**




### canonicalRedirection

    mixed FrontControllerCore::canonicalRedirection(string $canonical_url)

Redirects to canonical URL



* Visibility: **protected**


#### Arguments
* $canonical_url **string**



### geolocationManagement

    \Country|false FrontControllerCore::geolocationManagement(\Country $default_country)

Geolocation management



* Visibility: **protected**


#### Arguments
* $default_country **Country**



### setMobileMedia

    mixed FrontControllerCore::setMobileMedia()

Specific medias for mobile device.

If autoload directory is present in the mobile theme, these files will not be loaded

* Visibility: **public**




### setMedia

    boolean FrontControllerCore::setMedia()

Sets controller CSS and JS files.



* Visibility: **public**




### initHeader

    mixed FrontControllerCore::initHeader()

Initializes page header variables



* Visibility: **public**




### initFooter

    mixed FrontControllerCore::initFooter()

Initializes page footer variables



* Visibility: **public**




### checkLiveEditAccess

    boolean FrontControllerCore::checkLiveEditAccess()

Checks if the user can use Live Edit feature



* Visibility: **public**




### getLiveEditFooter

    string FrontControllerCore::getLiveEditFooter()

Renders Live Edit widget



* Visibility: **public**




### productSort

    mixed FrontControllerCore::productSort()

Assigns product list page sorting variables



* Visibility: **public**




### pagination

    mixed FrontControllerCore::pagination(integer|null $total_products)

Assigns product list page pagination variables



* Visibility: **public**


#### Arguments
* $total_products **integer|null**



### getCurrentCustomerGroups

    array FrontControllerCore::getCurrentCustomerGroups()

Sets and returns customer groups that the current customer(visitor) belongs to.



* Visibility: **public**
* This method is **static**.




### isInWhitelistForGeolocation

    boolean FrontControllerCore::isInWhitelistForGeolocation()

Checks if user's location is whitelisted.



* Visibility: **protected**
* This method is **static**.




### isTokenValid

    boolean FrontControllerCore::isTokenValid()

Checks if token is valid



* Visibility: **public**




### addMedia

    true|void FrontControllerCore::addMedia(string|array $media_uri, string|null $css_media_type, integer|null $offset, boolean $remove, boolean $check_path)

Adds a media file(s) (CSS, JS) to page header



* Visibility: **public**


#### Arguments
* $media_uri **string|array** - &lt;p&gt;Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string|null** - &lt;p&gt;CSS media type&lt;/p&gt;
* $offset **integer|null**
* $remove **boolean** - &lt;p&gt;If True, removes media files&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### removeMedia

    mixed FrontControllerCore::removeMedia(string|array $media_uri, string|null $css_media_type, boolean $check_path)

Removes media file(s) from page header



* Visibility: **public**


#### Arguments
* $media_uri **string|array** - &lt;p&gt;Path to file, or an array paths of like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string|null** - &lt;p&gt;CSS media type&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### addCSS

    true|void FrontControllerCore::addCSS(array|string $css_uri, string $css_media_type, integer|null $offset, boolean $check_path)

Add one or several CSS for front, checking if css files are overridden in theme/css/modules/ directory



* Visibility: **public**


#### Arguments
* $css_uri **array|string** - &lt;p&gt;$media_uri Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string** - &lt;p&gt;CSS media type&lt;/p&gt;
* $offset **integer|null**
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### removeCSS

    mixed FrontControllerCore::removeCSS(array|string $css_uri, string $css_media_type, boolean $check_path)

Removes CSS file(s) from page header



* Visibility: **public**


#### Arguments
* $css_uri **array|string** - &lt;p&gt;$media_uri Path to file, or an array of paths like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string** - &lt;p&gt;CSS media type&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### addJS

    true|void FrontControllerCore::addJS(array|string $js_uri, boolean $check_path)

Add one or several JS files for front, checking if js files are overridden in theme/js/modules/ directory



* Visibility: **public**


#### Arguments
* $js_uri **array|string** - &lt;p&gt;Path to file, or an array of paths&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### removeJS

    mixed FrontControllerCore::removeJS(array|string $js_uri, boolean $check_path)

Removes JS file(s) from page header



* Visibility: **public**


#### Arguments
* $js_uri **array|string** - &lt;p&gt;Path to file, or an array of paths&lt;/p&gt;
* $check_path **boolean** - &lt;p&gt;If true, checks if files exists&lt;/p&gt;



### recoverCart

    integer|false FrontControllerCore::recoverCart()

Recovers cart information



* Visibility: **protected**




### setTemplate

    mixed FrontControllerCore::setTemplate(string $default_template)

Sets template file for page content output



* Visibility: **public**


#### Arguments
* $default_template **string**



### getOverrideTemplate

    string|boolean FrontControllerCore::getOverrideTemplate()

Returns an overridden template path (if any) for this controller.

If not overridden, will return false. This method can be easily overriden in a
specific controller.

* Visibility: **public**




### useMobileTheme

    boolean FrontControllerCore::useMobileTheme()

Checks if mobile theme is active and in use.



* Visibility: **protected**




### getThemeDir

    string FrontControllerCore::getThemeDir()

Returns theme directory (regular or mobile)



* Visibility: **protected**




### getOverrideThemeDir

    string FrontControllerCore::getOverrideThemeDir()

Returns theme override directory (regular or mobile)



* Visibility: **protected**




### getLayout

    boolean|string FrontControllerCore::getLayout()

Returns the layout corresponding to the current page by using the override system
Ex:
On the url: http://localhost/index.php?id_product=1&controller=product, this method will
check if the layout exists in the following files (in that order), and return the first found:
- /themes/default/override/layout-product-1.tpl
- /themes/default/override/layout-product.tpl
- /themes/default/layout.tpl



* Visibility: **public**




### getTemplatePath

    string FrontControllerCore::getTemplatePath(string $template)

Returns template path



* Visibility: **public**


#### Arguments
* $template **string**



### setMobileTemplate

    mixed FrontControllerCore::setMobileTemplate(string $template)

Checks if the template set is available for mobile themes,
otherwise front template is chosen.



* Visibility: **public**


#### Arguments
* $template **string**



### initLogoAndFavicon

    array FrontControllerCore::initLogoAndFavicon()

Returns logo and favicon variables, depending
on active theme type (regular or mobile)



* Visibility: **public**




### addColorsToProductList

    mixed FrontControllerCore::addColorsToProductList(array $products)

Renders and adds color list HTML for each product in a list



* Visibility: **public**


#### Arguments
* $products **array**



### getColorsListCacheId

    string FrontControllerCore::getColorsListCacheId(integer $id_product)

Returns cache ID for product color list



* Visibility: **protected**


#### Arguments
* $id_product **integer**


