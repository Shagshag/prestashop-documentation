Class ControllerCore
=====================





* Class name: ControllerCore
* This is an **abstract** class
* Source: [classes/controller/Controller.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L30)


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
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L75).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L70).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L35).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L81).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L40).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L65).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L55).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L45).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L76).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/controller/Controller.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L50).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L82).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L79).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L77).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L60).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ControllerCore::__construct()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L137)




### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type, $offset)
```

Add a new stylesheet in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L242)


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
* Source: [classes/controller/Controller.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L271)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L294)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
void ControllerCore::addJqueryPlugin(mixed $name, mixed $folder)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L326)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L305)


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
* Source: [classes/controller/Controller.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L86)




### <a name="method-display"></a>display

```php
mixed ControllerCore::display()
```

Display page view



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L113)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L205)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L200)


#### Arguments
* $display **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/Controller.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L132)


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
* Source: [classes/controller/Controller.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L96)




### <a name="method-initContent"></a>initContent

```php
mixed ControllerCore::initContent()
```

Assign smarty variables for the page main content



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L223)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed ControllerCore::initCursedPage()
```

Assign smarty variables when access is forbidden



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L228)




### <a name="method-initFooter"></a>initFooter

```php
mixed ControllerCore::initFooter()
```

Assign smarty variables for the page footer



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L233)




### <a name="method-initHeader"></a>initHeader

```php
mixed ControllerCore::initHeader()
```

Assign smarty variables for the page header



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L218)




### <a name="method-isCached"></a>isCached

```php
mixed ControllerCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L369)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L354)




### <a name="method-myErrorHandler"></a>myErrorHandler

```php
mixed ControllerCore::myErrorHandler($errno, $errstr, $errfile, $errline)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/Controller.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L377)


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
* Source: [classes/controller/Controller.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L108)




### <a name="method-redirect"></a>redirect

```php
mixed ControllerCore::redirect()
```

Redirect after process if no error



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L118)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* Source: [classes/controller/Controller.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L154)




### <a name="method-setMedia"></a>setMedia

```php
mixed ControllerCore::setMedia()
```

Set default media list for controller



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L123)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L210)


#### Arguments
* $template **mixed**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent($content)
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L359)


#### Arguments
* $content **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
mixed ControllerCore::viewAccess()
```

check that the current user/visitor has valid view permissions



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/controller/Controller.php#L91)



