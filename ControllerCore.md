ControllerCore
===============






* Class name: ControllerCore
* Namespace: 
* This is an **abstract** class

* This class is defined in [classes/controller/Controller.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#31)





Properties
----------


### $context

    protected \Context $context





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#34)


### $css_files

    public array $css_files = array()





* Visibility: **public**
* This property is defined in [classes/controller/Controller.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#37)


### $js_files

    public array $js_files = array()





* Visibility: **public**
* This property is defined in [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#40)


### $php_errors

    public array $php_errors = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/controller/Controller.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#43)


### $display_header

    protected boolean $display_header





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#46)


### $display_header_javascript

    protected boolean $display_header_javascript





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#49)


### $template

    protected string $template





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#52)


### $display_footer

    protected string $display_footer





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#55)


### $content_only

    protected boolean $content_only = false





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#58)


### $ajax

    public boolean $ajax = false





* Visibility: **public**
* This property is defined in [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#61)


### $json

    protected boolean $json = false





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#64)


### $status

    protected string $status = ''





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#67)


### $redirect_after

    protected string $redirect_after = null





* Visibility: **protected**
* This property is defined in [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#73)


### $controller_type

    public string $controller_type





* Visibility: **public**
* This property is defined in [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#76)


### $php_self

    public string $php_self





* Visibility: **public**
* This property is defined in [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#79)


Methods
-------


### checkAccess

    mixed ControllerCore::checkAccess()

Check if the controller is available for the current user/visitor



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#84)




### viewAccess

    mixed ControllerCore::viewAccess()

Check if the current user/visitor has valid view permissions



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#89)




### init

    mixed ControllerCore::init()

Initialize the page



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#94)




### postProcess

    mixed ControllerCore::postProcess()

Do the page treatment: process input, process AJAX, etc.



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#112)




### display

    mixed ControllerCore::display()

Displays page view



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#117)




### setMedia

    mixed ControllerCore::setMedia()

Sets default media list for this controller



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#122)




### getController

    \Controller ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)

returns a new instance of this controller



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/controller/Controller.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#132)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### __construct

    mixed ControllerCore::__construct()





* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#137)




### run

    mixed ControllerCore::run()

Starts the controller process (this method should not be overridden!)



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#168)




### displayHeader

    mixed ControllerCore::displayHeader(boolean $display)

Sets page header display



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#222)


#### Arguments
* $display **boolean**



### displayHeaderJavaScript

    mixed ControllerCore::displayHeaderJavaScript(boolean $display)

Sets page header javascript display



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#232)


#### Arguments
* $display **boolean**



### displayFooter

    mixed ControllerCore::displayFooter(boolean $display)

Sets page header display



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#242)


#### Arguments
* $display **boolean**



### setTemplate

    mixed ControllerCore::setTemplate(string $template)

Sets template file for page content output



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#252)


#### Arguments
* $template **string**



### initHeader

    mixed ControllerCore::initHeader()

Assigns Smarty variables for the page header



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#260)




### initContent

    mixed ControllerCore::initContent()

Assigns Smarty variables for the page main content



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#265)




### initCursedPage

    mixed ControllerCore::initCursedPage()

Assigns Smarty variables when access is forbidden



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#270)




### initFooter

    mixed ControllerCore::initFooter()

Assigns Smarty variables for the page footer



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#275)




### redirect

    mixed ControllerCore::redirect()

Redirects to $this->redirect_after after the process if there is no error



* Visibility: **protected**
* This method is **abstract**.
* This method is defined in [classes/controller/Controller.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#280)




### setRedirectAfter

    mixed ControllerCore::setRedirectAfter($url)

Set $this->redirect_after that will be used by redirect() after the process



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#285)


#### Arguments
* $url **mixed**



### addCSS

    true ControllerCore::addCSS(string|array $css_uri, string $css_media_type, integer|null $offset, boolean $check_path)

Adds a new stylesheet(s) to the page header.



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#299)


#### Arguments
* $css_uri **string|array** - &lt;p&gt;Path to CSS file, or list of css files like this : array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string**
* $offset **integer|null**
* $check_path **boolean**



### removeCSS

    mixed ControllerCore::removeCSS(string|array $css_uri, string $css_media_type, boolean $check_path)

Removes CSS stylesheet(s) from the queued stylesheet list



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#339)


#### Arguments
* $css_uri **string|array** - &lt;p&gt;Path to CSS file or an array like: array(array(uri =&gt; media_type), ...)&lt;/p&gt;
* $css_media_type **string**
* $check_path **boolean**



### addJS

    void ControllerCore::addJS(string|array $js_uri, boolean $check_path)

Adds a new JavaScript file(s) to the page header.



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#373)


#### Arguments
* $js_uri **string|array** - &lt;p&gt;Path to JS file or an array like: array(uri, ...)&lt;/p&gt;
* $check_path **boolean**



### removeJS

    mixed ControllerCore::removeJS(string|array $js_uri, boolean $check_path)

Removes JS file(s) from the queued JS file list



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#405)


#### Arguments
* $js_uri **string|array** - &lt;p&gt;Path to JS file or an array like: array(uri, ...)&lt;/p&gt;
* $check_path **boolean**



### addJquery

    mixed ControllerCore::addJquery(string|null $version, string|null $folder, boolean $minifier)

Adds jQuery library file to queued JS file list



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#437)


#### Arguments
* $version **string|null** - &lt;p&gt;jQuery library version&lt;/p&gt;
* $folder **string|null** - &lt;p&gt;jQuery file folder&lt;/p&gt;
* $minifier **boolean** - &lt;p&gt;If set tot true, a minified version will be included.&lt;/p&gt;



### addJqueryUI

    mixed ControllerCore::addJqueryUI(string|array $component, string $theme, boolean $check_dependencies)

Adds jQuery UI component(s) to queued JS file list



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#449)


#### Arguments
* $component **string|array**
* $theme **string**
* $check_dependencies **boolean**



### addJqueryPlugin

    mixed ControllerCore::addJqueryPlugin(string|array $name, $folder, boolean $css)

Adds jQuery plugin(s) to queued JS file list



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#469)


#### Arguments
* $name **string|array**
* $folder **mixed**
* $css **boolean**



### isXmlHttpRequest

    boolean ControllerCore::isXmlHttpRequest()

Checks if the controller has been called from XmlHttpRequest (AJAX)



* Visibility: **public**
* This method is defined in [classes/controller/Controller.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#494)




### smartyOutputContent

    mixed ControllerCore::smartyOutputContent(array|string $content)

Renders controller templates and generates page content



* Visibility: **protected**
* This method is defined in [classes/controller/Controller.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#506)


#### Arguments
* $content **array|string** - &lt;p&gt;Template file(s) to be rendered&lt;/p&gt;



### isCached

    boolean ControllerCore::isCached(string $template, string|null $cache_id, string|null $compile_id)

Checks if a template is cached



* Visibility: **protected**
* This method is defined in [classes/controller/Controller.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#565)


#### Arguments
* $template **string**
* $cache_id **string|null** - &lt;p&gt;Cache item ID&lt;/p&gt;
* $compile_id **string|null**



### myErrorHandler

    boolean ControllerCore::myErrorHandler(string $errno, string $errstr, string $errfile, integer $errline)

Custom error handler



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/controller/Controller.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#583)


#### Arguments
* $errno **string**
* $errstr **string**
* $errfile **string**
* $errline **integer**



### ajaxDie

    mixed ControllerCore::ajaxDie(string|null $value, string|null $controller, string|null $method)

Dies and echoes output value



* Visibility: **protected**
* This method is defined in [classes/controller/Controller.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/Controller.php#626)


#### Arguments
* $value **string|null**
* $controller **string|null**
* $method **string|null**


