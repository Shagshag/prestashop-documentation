Class ControllerCore
=====================





* Class name: ControllerCore
* This is an **abstract** class
* Source: [classes/controller/Controller.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L30)


Contents
--------


### Properties

* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$controller_type](#property-$controller_type)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$php_errors](#property-$php_errors)
* [$php_self](#property-$php_self)
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
* [checkAccess](#method-checkAccess)
* [display](#method-display)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
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
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L75).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L70).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L35).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L81).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L40).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L65).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L55).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L45).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L76).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/controller/Controller.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L50).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L82).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L79).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L77).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L60).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ControllerCore::__construct()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L138)




### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type, $offset)
```

Add a new stylesheet in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L249)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $offset **mixed**



### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L295)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L336)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
mixed ControllerCore::addJqueryPlugin($name, null $folder, boolean $css)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L368)


#### Arguments
* $name **mixed**
* $folder **null**
* $css **boolean**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L347)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-checkAccess"></a>checkAccess

```php
mixed ControllerCore::checkAccess()
```

check that the controller is available for the current user/visitor



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L86)




### <a name="method-display"></a>display

```php
mixed ControllerCore::display()
```

Display page view



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L114)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L212)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L207)


#### Arguments
* $display **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/Controller.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L133)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-init"></a>init

```php
mixed ControllerCore::init()
```

Initialize the page



* Visibility: **public**
* Source: [classes/controller/Controller.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L96)




### <a name="method-initContent"></a>initContent

```php
mixed ControllerCore::initContent()
```

Assign smarty variables for the page main content



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L230)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed ControllerCore::initCursedPage()
```

Assign smarty variables when access is forbidden



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L235)




### <a name="method-initFooter"></a>initFooter

```php
mixed ControllerCore::initFooter()
```

Assign smarty variables for the page footer



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L240)




### <a name="method-initHeader"></a>initHeader

```php
mixed ControllerCore::initHeader()
```

Assign smarty variables for the page header



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L225)




### <a name="method-isCached"></a>isCached

```php
mixed ControllerCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L436)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L390)




### <a name="method-myErrorHandler"></a>myErrorHandler

```php
mixed ControllerCore::myErrorHandler($errno, $errstr, $errfile, $errline)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/Controller.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L444)


#### Arguments
* $errno **mixed**
* $errstr **mixed**
* $errfile **mixed**
* $errline **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed ControllerCore::postProcess()
```

Do the page treatment : post process, ajax process, etc.



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L109)




### <a name="method-redirect"></a>redirect

```php
mixed ControllerCore::redirect()
```

Redirect after process if no error



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L119)




### <a name="method-removeCSS"></a>removeCSS

```php
mixed ControllerCore::removeCSS($css_uri, $css_media_type)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L273)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### <a name="method-removeJS"></a>removeJS

```php
mixed ControllerCore::removeJS($js_uri)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L313)


#### Arguments
* $js_uri **mixed**



### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* Source: [classes/controller/Controller.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L161)




### <a name="method-setMedia"></a>setMedia

```php
mixed ControllerCore::setMedia()
```

Set default media list for controller



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L124)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L217)


#### Arguments
* $template **mixed**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent($content)
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L395)


#### Arguments
* $content **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
mixed ControllerCore::viewAccess()
```

check that the current user/visitor has valid view permissions



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/controller/Controller.php#L91)



