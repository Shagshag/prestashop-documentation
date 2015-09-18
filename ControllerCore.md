ControllerCore
===============






* Class name: ControllerCore
* Namespace: 
* This is an **abstract** class





Properties
----------


### $context

    protected \Context $context





* Visibility: **protected**


### $css_files

    public array $css_files = array()





* Visibility: **public**


### $js_files

    public array $js_files = array()





* Visibility: **public**


### $php_errors

    public array $php_errors = array()





* Visibility: **public**
* This property is **static**.


### $display_header

    protected boolean $display_header





* Visibility: **protected**


### $display_header_javascript

    protected boolean $display_header_javascript





* Visibility: **protected**


### $template

    protected string $template





* Visibility: **protected**


### $display_footer

    protected string $display_footer





* Visibility: **protected**


### $content_only

    protected boolean $content_only = false





* Visibility: **protected**


### $ajax

    public boolean $ajax = false





* Visibility: **public**


### $json

    protected boolean $json = false





* Visibility: **protected**


### $status

    protected string $status = ''





* Visibility: **protected**


### $redirect_after

    protected string $redirect_after = null





* Visibility: **protected**


### $controller_type

    public string $controller_type





* Visibility: **public**


### $php_self

    public string $php_self





* Visibility: **public**


Methods
-------


### checkAccess

    mixed ControllerCore::checkAccess()

Check if the controller is available for the current user/visitor



* Visibility: **public**
* This method is **abstract**.




### viewAccess

    mixed ControllerCore::viewAccess()

Check if the current user/visitor has valid view permissions



* Visibility: **public**
* This method is **abstract**.




### init

    mixed ControllerCore::init()

Initialize the page



* Visibility: **public**




### postProcess

    mixed ControllerCore::postProcess()

Do the page treatment: process input, process AJAX, etc.



* Visibility: **public**
* This method is **abstract**.




### display

    mixed ControllerCore::display()

Displays page view



* Visibility: **public**
* This method is **abstract**.




### setMedia

    mixed ControllerCore::setMedia()

Sets default media list for this controller



* Visibility: **public**
* This method is **abstract**.




### getController

    \Controller ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)

returns a new instance of this controller



* Visibility: **public**
* This method is **static**.


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### __construct

    mixed ControllerCore::__construct()





* Visibility: **public**




### run

    mixed ControllerCore::run()

Starts the controller process (this method should not be overridden!)



* Visibility: **public**




### displayHeader

    mixed ControllerCore::displayHeader(boolean $display)

Sets page header display



* Visibility: **public**


#### Arguments
* $display **boolean**



### displayHeaderJavaScript

    mixed ControllerCore::displayHeaderJavaScript(boolean $display)

Sets page header javascript display



* Visibility: **public**


#### Arguments
* $display **boolean**



### displayFooter

    mixed ControllerCore::displayFooter(boolean $display)

Sets page header display



* Visibility: **public**


#### Arguments
* $display **boolean**



### setTemplate

    mixed ControllerCore::setTemplate(string $template)

Sets template file for page content output



* Visibility: **public**


#### Arguments
* $template **string**



### initHeader

    mixed ControllerCore::initHeader()

Assigns Smarty variables for the page header



* Visibility: **public**
* This method is **abstract**.




### initContent

    mixed ControllerCore::initContent()

Assigns Smarty variables for the page main content



* Visibility: **public**
* This method is **abstract**.




### initCursedPage

    mixed ControllerCore::initCursedPage()

Assigns Smarty variables when access is forbidden



* Visibility: **public**
* This method is **abstract**.




### initFooter

    mixed ControllerCore::initFooter()

Assigns Smarty variables for the page footer



* Visibility: **public**
* This method is **abstract**.




### redirect

    mixed ControllerCore::redirect()

Redirects to $this->redirect_after after the process if there is no error



* Visibility: **protected**
* This method is **abstract**.




### setRedirectAfter

    mixed ControllerCore::setRedirectAfter($url)

Set $this->redirect_after that will be used by redirect() after the process



* Visibility: **public**


#### Arguments
* $url **mixed**



### addCSS

    true ControllerCore::addCSS(string|array $css_uri, string $css_media_type, integer|null $offset, boolean $check_path)

Adds a new stylesheet(s) to the page header.



* Visibility: **public**


#### Arguments
* $css_uri **string|array** - &lt;p&gt;Path to CSS file, or list of css files like this : array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string**
* $offset **integer|null**
* $check_path **boolean**



### removeCSS

    mixed ControllerCore::removeCSS(string|array $css_uri, string $css_media_type, boolean $check_path)

Removes CSS stylesheet(s) from the queued stylesheet list



* Visibility: **public**


#### Arguments
* $css_uri **string|array** - &lt;p&gt;Path to CSS file or an array like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string**
* $check_path **boolean**



### addJS

    void ControllerCore::addJS(string|array $js_uri, boolean $check_path)

Adds a new JavaScript file(s) to the page header.



* Visibility: **public**


#### Arguments
* $js_uri **string|array** - &lt;p&gt;Path to JS file or an array like: array(uri, ...)&lt;/p&gt;
* $check_path **boolean**



### removeJS

    mixed ControllerCore::removeJS(string|array $js_uri, boolean $check_path)

Removes JS file(s) from the queued JS file list



* Visibility: **public**


#### Arguments
* $js_uri **string|array** - &lt;p&gt;Path to JS file or an array like: array(uri, ...)&lt;/p&gt;
* $check_path **boolean**



### addJquery

    mixed ControllerCore::addJquery(string|null $version, string|null $folder, boolean $minifier)

Adds jQuery library file to queued JS file list



* Visibility: **public**


#### Arguments
* $version **string|null** - &lt;p&gt;jQuery library version&lt;/p&gt;
* $folder **string|null** - &lt;p&gt;jQuery file folder&lt;/p&gt;
* $minifier **boolean** - &lt;p&gt;If set tot true, a minified version will be included.&lt;/p&gt;



### addJqueryUI

    mixed ControllerCore::addJqueryUI(string|array $component, string $theme, boolean $check_dependencies)

Adds jQuery UI component(s) to queued JS file list



* Visibility: **public**


#### Arguments
* $component **string|array**
* $theme **string**
* $check_dependencies **boolean**



### addJqueryPlugin

    mixed ControllerCore::addJqueryPlugin(string|array $name, $folder, boolean $css)

Adds jQuery plugin(s) to queued JS file list



* Visibility: **public**


#### Arguments
* $name **string|array**
* $folder **mixed**
* $css **boolean**



### isXmlHttpRequest

    boolean ControllerCore::isXmlHttpRequest()

Checks if the controller has been called from XmlHttpRequest (AJAX)



* Visibility: **public**




### smartyOutputContent

    mixed ControllerCore::smartyOutputContent(array|string $content)

Renders controller templates and generates page content



* Visibility: **protected**


#### Arguments
* $content **array|string** - &lt;p&gt;Template file(s) to be rendered&lt;/p&gt;



### isCached

    boolean ControllerCore::isCached(string $template, string|null $cache_id, string|null $compile_id)

Checks if a template is cached



* Visibility: **protected**


#### Arguments
* $template **string**
* $cache_id **string|null** - &lt;p&gt;Cache item ID&lt;/p&gt;
* $compile_id **string|null**



### myErrorHandler

    boolean ControllerCore::myErrorHandler(string $errno, string $errstr, string $errfile, integer $errline)

Custom error handler



* Visibility: **public**
* This method is **static**.


#### Arguments
* $errno **string**
* $errstr **string**
* $errfile **string**
* $errline **integer**



### ajaxDie

    mixed ControllerCore::ajaxDie(string|null $value, string|null $controller, string|null $method)

Dies and echoes output value



* Visibility: **protected**


#### Arguments
* $value **string|null**
* $controller **string|null**
* $method **string|null**


