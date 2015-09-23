Class ControllerCore
=====================





* Class name: ControllerCore
* This is an **abstract** class
* Source: [classes/controller/Controller.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L31)


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
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [postProcess](#method-postProcess)
* [redirect](#method-redirect)
* [run](#method-run)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L36).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L77).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L51).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L73).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* Source: [classes/controller/Controller.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L56).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ControllerCore::__construct()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L132)




### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type)
```

Add a new stylesheet in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L237)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**



### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L269)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L292)


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
* Source: [classes/controller/Controller.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L323)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* Source: [classes/controller/Controller.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L303)


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
* Source: [classes/controller/Controller.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L82)




### <a name="method-display"></a>display

```php
mixed ControllerCore::display()
```

Display page view



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L108)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L200)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L195)


#### Arguments
* $display **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* Source: [classes/controller/Controller.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L127)


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
* Source: [classes/controller/Controller.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L92)




### <a name="method-initContent"></a>initContent

```php
mixed ControllerCore::initContent()
```

Assign smarty variables for the page main content



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L218)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed ControllerCore::initCursedPage()
```

Assign smarty variables when access is forbidden



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L223)




### <a name="method-initFooter"></a>initFooter

```php
mixed ControllerCore::initFooter()
```

Assign smarty variables for the page footer



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L228)




### <a name="method-initHeader"></a>initHeader

```php
mixed ControllerCore::initHeader()
```

Assign smarty variables for the page header



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L213)




### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L346)




### <a name="method-postProcess"></a>postProcess

```php
mixed ControllerCore::postProcess()
```

Do the page treatment : post process, ajax process, etc.



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L103)




### <a name="method-redirect"></a>redirect

```php
mixed ControllerCore::redirect()
```

Redirect after process if no error



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L113)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* Source: [classes/controller/Controller.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L149)




### <a name="method-setMedia"></a>setMedia

```php
mixed ControllerCore::setMedia()
```

Set default media list for controller



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L118)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* Source: [classes/controller/Controller.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L205)


#### Arguments
* $template **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
mixed ControllerCore::viewAccess()
```

check that the current user/visitor has valid view permissions



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/controller/Controller.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L87)



