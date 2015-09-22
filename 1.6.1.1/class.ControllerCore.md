Class ControllerCore
=====================





* Class name: ControllerCore
* This is an **abstract** class
* Source: [classes/controller/Controller.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L31)



Properties
----------

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
* [$php_self](#property-$php_self)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)
* [$template](#property-$template)

Methods
-------
* [__construct](#method-__construct)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [ajaxDie](#method-ajaxDie)
* [checkAccess](#method-checkAccess)
* [display](#method-display)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayHeaderJavaScript](#method-displayHeaderJavaScript)
* [getController](#method-getController)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [isCached](#method-isCached)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [myErrorHandler](#method-myErrorHandler)
* [postProcess](#method-postProcess)
* [redirect](#method-redirect)
* [removeCSS](#method-removeCSS)
* [removeJS](#method-removeJS)
* [run](#method-run)
* [setMedia](#method-setMedia)
* [setRedirectAfter](#method-setRedirectAfter)
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$ajax"></a>$ajax

    public boolean $ajax = false





* Visibility: **public**
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L61).


### <a name="property-$content_only"></a>$content_only

    protected boolean $content_only = false





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L58).


### <a name="property-$context"></a>$context

    protected \Context $context





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L34).


### <a name="property-$controller_type"></a>$controller_type

    public string $controller_type





* Visibility: **public**
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L76).


### <a name="property-$css_files"></a>$css_files

    public array $css_files = array()





* Visibility: **public**
* Source: [classes/controller/Controller.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L37).


### <a name="property-$display_footer"></a>$display_footer

    protected string $display_footer





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L55).


### <a name="property-$display_header"></a>$display_header

    protected boolean $display_header





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L46).


### <a name="property-$display_header_javascript"></a>$display_header_javascript

    protected boolean $display_header_javascript





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L49).


### <a name="property-$js_files"></a>$js_files

    public array $js_files = array()





* Visibility: **public**
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L40).


### <a name="property-$json"></a>$json

    protected boolean $json = false





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L64).


### <a name="property-$php_errors"></a>$php_errors

    public array $php_errors = array()





* Visibility: **public**
* This property is **static**.
* Source: [classes/controller/Controller.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L43).


### <a name="property-$php_self"></a>$php_self

    public string $php_self





* Visibility: **public**
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L79).


### <a name="property-$redirect_after"></a>$redirect_after

    protected string $redirect_after = null





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L73).


### <a name="property-$status"></a>$status

    protected string $status = ''





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L67).


### <a name="property-$template"></a>$template

    protected string $template





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L52).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ControllerCore::__construct()





* Visibility: **public**
* Source: [classes/controller/Controller.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L137)




### <a name="method-addCSS"></a>addCSS

    true ControllerCore::addCSS(string|array $css_uri, string $css_media_type, integer|null $offset, boolean $check_path)

Adds a new stylesheet(s) to the page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L299)


#### Arguments
* $css_uri **string|array** - Path to CSS file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $offset **integer|null**
* $check_path **boolean**



### <a name="method-addJS"></a>addJS

    void ControllerCore::addJS(string|array $js_uri, boolean $check_path)

Adds a new JavaScript file(s) to the page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L373)


#### Arguments
* $js_uri **string|array** - Path to JS file or an array like: array(uri, ...)
* $check_path **boolean**



### <a name="method-addJquery"></a>addJquery

    mixed ControllerCore::addJquery(string|null $version, string|null $folder, boolean $minifier)

Adds jQuery library file to queued JS file list



* Visibility: **public**
* Source: [classes/controller/Controller.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L437)


#### Arguments
* $version **string|null** - jQuery library version
* $folder **string|null** - jQuery file folder
* $minifier **boolean** - If set tot true, a minified version will be included.



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

    mixed ControllerCore::addJqueryPlugin(string|array $name, $folder, boolean $css)

Adds jQuery plugin(s) to queued JS file list



* Visibility: **public**
* Source: [classes/controller/Controller.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L469)


#### Arguments
* $name **string|array**
* $folder **mixed**
* $css **boolean**



### <a name="method-addJqueryUI"></a>addJqueryUI

    mixed ControllerCore::addJqueryUI(string|array $component, string $theme, boolean $check_dependencies)

Adds jQuery UI component(s) to queued JS file list



* Visibility: **public**
* Source: [classes/controller/Controller.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L449)


#### Arguments
* $component **string|array**
* $theme **string**
* $check_dependencies **boolean**



### <a name="method-ajaxDie"></a>ajaxDie

    mixed ControllerCore::ajaxDie(string|null $value, string|null $controller, string|null $method)

Dies and echoes output value



* Visibility: **protected**
* Source: [classes/controller/Controller.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L626)


#### Arguments
* $value **string|null**
* $controller **string|null**
* $method **string|null**



### <a name="method-checkAccess"></a>checkAccess

    mixed ControllerCore::checkAccess()

Check if the controller is available for the current user/visitor



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L84)




### <a name="method-display"></a>display

    mixed ControllerCore::display()

Displays page view



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L117)




### <a name="method-displayFooter"></a>displayFooter

    mixed ControllerCore::displayFooter(boolean $display)

Sets page header display



* Visibility: **public**
* Source: [classes/controller/Controller.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L242)


#### Arguments
* $display **boolean**



### <a name="method-displayHeader"></a>displayHeader

    mixed ControllerCore::displayHeader(boolean $display)

Sets page header display



* Visibility: **public**
* Source: [classes/controller/Controller.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L222)


#### Arguments
* $display **boolean**



### <a name="method-displayHeaderJavaScript"></a>displayHeaderJavaScript

    mixed ControllerCore::displayHeaderJavaScript(boolean $display)

Sets page header javascript display



* Visibility: **public**
* Source: [classes/controller/Controller.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L232)


#### Arguments
* $display **boolean**



### <a name="method-getController"></a>getController

    \Controller ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)

returns a new instance of this controller



* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/Controller.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L132)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-init"></a>init

    mixed ControllerCore::init()

Initialize the page



* Visibility: **public**
* Source: [classes/controller/Controller.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L94)




### <a name="method-initContent"></a>initContent

    mixed ControllerCore::initContent()

Assigns Smarty variables for the page main content



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L265)




### <a name="method-initCursedPage"></a>initCursedPage

    mixed ControllerCore::initCursedPage()

Assigns Smarty variables when access is forbidden



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L270)




### <a name="method-initFooter"></a>initFooter

    mixed ControllerCore::initFooter()

Assigns Smarty variables for the page footer



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L275)




### <a name="method-initHeader"></a>initHeader

    mixed ControllerCore::initHeader()

Assigns Smarty variables for the page header



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L260)




### <a name="method-isCached"></a>isCached

    boolean ControllerCore::isCached(string $template, string|null $cache_id, string|null $compile_id)

Checks if a template is cached



* Visibility: **protected**
* Source: [classes/controller/Controller.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L565)


#### Arguments
* $template **string**
* $cache_id **string|null** - Cache item ID
* $compile_id **string|null**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

    boolean ControllerCore::isXmlHttpRequest()

Checks if the controller has been called from XmlHttpRequest (AJAX)



* Visibility: **public**
* Source: [classes/controller/Controller.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L494)




### <a name="method-myErrorHandler"></a>myErrorHandler

    boolean ControllerCore::myErrorHandler(string $errno, string $errstr, string $errfile, integer $errline)

Custom error handler



* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/Controller.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L583)


#### Arguments
* $errno **string**
* $errstr **string**
* $errfile **string**
* $errline **integer**



### <a name="method-postProcess"></a>postProcess

    mixed ControllerCore::postProcess()

Do the page treatment: process input, process AJAX, etc.



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L112)




### <a name="method-redirect"></a>redirect

    mixed ControllerCore::redirect()

Redirects to $this->redirect_after after the process if there is no error



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L280)




### <a name="method-removeCSS"></a>removeCSS

    mixed ControllerCore::removeCSS(string|array $css_uri, string $css_media_type, boolean $check_path)

Removes CSS stylesheet(s) from the queued stylesheet list



* Visibility: **public**
* Source: [classes/controller/Controller.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L339)


#### Arguments
* $css_uri **string|array** - Path to CSS file or an array like: array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $check_path **boolean**



### <a name="method-removeJS"></a>removeJS

    mixed ControllerCore::removeJS(string|array $js_uri, boolean $check_path)

Removes JS file(s) from the queued JS file list



* Visibility: **public**
* Source: [classes/controller/Controller.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L405)


#### Arguments
* $js_uri **string|array** - Path to JS file or an array like: array(uri, ...)
* $check_path **boolean**



### <a name="method-run"></a>run

    mixed ControllerCore::run()

Starts the controller process (this method should not be overridden!)



* Visibility: **public**
* Source: [classes/controller/Controller.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L168)




### <a name="method-setMedia"></a>setMedia

    mixed ControllerCore::setMedia()

Sets default media list for this controller



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L122)




### <a name="method-setRedirectAfter"></a>setRedirectAfter

    mixed ControllerCore::setRedirectAfter($url)

Set $this->redirect_after that will be used by redirect() after the process



* Visibility: **public**
* Source: [classes/controller/Controller.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L285)


#### Arguments
* $url **mixed**



### <a name="method-setTemplate"></a>setTemplate

    mixed ControllerCore::setTemplate(string $template)

Sets template file for page content output



* Visibility: **public**
* Source: [classes/controller/Controller.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L252)


#### Arguments
* $template **string**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

    mixed ControllerCore::smartyOutputContent(array|string $content)

Renders controller templates and generates page content



* Visibility: **protected**
* Source: [classes/controller/Controller.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L506)


#### Arguments
* $content **array|string** - Template file(s) to be rendered



### <a name="method-viewAccess"></a>viewAccess

    mixed ControllerCore::viewAccess()

Check if the current user/visitor has valid view permissions



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#L89)



