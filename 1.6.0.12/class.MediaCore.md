Class MediaCore
=====================





* Class name: MediaCore
* Source: [classes/Media.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L27)


Contents
--------


### Properties

* [$inline_script](#property-$inline_script)
* [$inline_script_src](#property-$inline_script_src)
* [$jquery_ui_dependencies](#property-$jquery_ui_dependencies)
* [$js_def](#property-$js_def)

### Methods

* [addJsDef](#method-addJsDef)
* [addJsDefL](#method-addJsDefL)
* [cccCss](#method-cccCss)
* [cccJS](#method-cccJS)
* [clearCache](#method-clearCache)
* [deferInlineScripts](#method-deferInlineScripts)
* [deferScript](#method-deferScript)
* [getBackTrackLimit](#method-getBackTrackLimit)
* [getCSSPath](#method-getCSSPath)
* [getInlineScript](#method-getInlineScript)
* [getJSPath](#method-getJSPath)
* [getJqueryPath](#method-getJqueryPath)
* [getJqueryPluginCSSPath](#method-getJqueryPluginCSSPath)
* [getJqueryPluginPath](#method-getJqueryPluginPath)
* [getJqueryUIPath](#method-getJqueryUIPath)
* [getJsDef](#method-getJsDef)
* [getMediaPath](#method-getMediaPath)
* [minifyCSS](#method-minifyCSS)
* [minifyHTML](#method-minifyHTML)
* [minifyHTMLpregCallback](#method-minifyHTMLpregCallback)
* [packJS](#method-packJS)
* [packJSinHTML](#method-packJSinHTML)
* [packJSinHTMLpregCallback](#method-packJSinHTMLpregCallback)




Properties
----------


### <a name="property-$inline_script"></a>$inline_script

```php
protected array $inline_script = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Media.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L74).


### <a name="property-$inline_script_src"></a>$inline_script_src

```php
protected array $inline_script_src = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Media.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L79).


### <a name="property-$jquery_ui_dependencies"></a>$jquery_ui_dependencies

```php
public mixed $jquery_ui_dependencies = array('ui.core' => array('fileName' => 'jquery.ui.core.min.js', 'dependencies' => array(), 'theme' => true), 'ui.widget' => array('fileName' => 'jquery.ui.widget.min.js', 'dependencies' => array(), 'theme' => false), 'ui.mouse' => array('fileName' => 'jquery.ui.mouse.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => false), 'ui.position' => array('fileName' => 'jquery.ui.position.min.js', 'dependencies' => array(), 'theme' => false), 'ui.draggable' => array('fileName' => 'jquery.ui.draggable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => false), 'ui.droppable' => array('fileName' => 'jquery.ui.droppable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse', 'ui.draggable'), 'theme' => false), 'ui.resizable' => array('fileName' => 'jquery.ui.resizable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.selectable' => array('fileName' => 'jquery.ui.selectable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.sortable' => array('fileName' => 'jquery.ui.sortable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.autocomplete' => array('fileName' => 'jquery.ui.autocomplete.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'ui.menu'), 'theme' => true), 'ui.button' => array('fileName' => 'jquery.ui.button.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.dialog' => array('fileName' => 'jquery.ui.dialog.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'ui.button'), 'theme' => true), 'ui.menu' => array('fileName' => 'jquery.ui.menu.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position'), 'theme' => true), 'ui.slider' => array('fileName' => 'jquery.ui.slider.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.spinner' => array('fileName' => 'jquery.ui.spinner.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.button'), 'theme' => true), 'ui.tabs' => array('fileName' => 'jquery.ui.tabs.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.datepicker' => array('fileName' => 'jquery.ui.datepicker.min.js', 'dependencies' => array('ui.core'), 'theme' => true), 'ui.progressbar' => array('fileName' => 'jquery.ui.progressbar.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.tooltip' => array('fileName' => 'jquery.ui.tooltip.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'effects.core'), 'theme' => true), 'ui.accordion' => array('fileName' => 'jquery.ui.accordion.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'effects.core'), 'theme' => true), 'effects.core' => array('fileName' => 'jquery.effects.core.min.js', 'dependencies' => array(), 'theme' => false), 'effects.blind' => array('fileName' => 'jquery.effects.blind.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.bounce' => array('fileName' => 'jquery.effects.bounce.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.clip' => array('fileName' => 'jquery.effects.clip.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.drop' => array('fileName' => 'jquery.effects.drop.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.explode' => array('fileName' => 'jquery.effects.explode.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.fade' => array('fileName' => 'jquery.effects.fade.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.fold' => array('fileName' => 'jquery.effects.fold.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.highlight' => array('fileName' => 'jquery.effects.highlight.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.pulsate' => array('fileName' => 'jquery.effects.pulsate.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.scale' => array('fileName' => 'jquery.effects.scale.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.shake' => array('fileName' => 'jquery.effects.shake.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.slide' => array('fileName' => 'jquery.effects.slide.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.transfer' => array('fileName' => 'jquery.effects.transfer.min.js', 'dependencies' => array('effects.core'), 'theme' => false))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Media.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L29).


### <a name="property-$js_def"></a>$js_def

```php
protected array $js_def = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Media.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L69).


Methods
-------


### <a name="method-addJsDef"></a>addJsDef

```php
void MediaCore::addJsDef(mixed $js_def)
```

Add a new javascript definition at bottom of page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L691)


#### Arguments
* $js_def **mixed**



### <a name="method-addJsDefL"></a>addJsDefL

```php
void MediaCore::addJsDefL($params, $content, $smarty, $repeat)
```

Add a new javascript definition from a capture at bottom of page



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 706](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L706)


#### Arguments
* $params **mixed**
* $content **mixed**
* $smarty **mixed**
* $repeat **mixed**



### <a name="method-cccCss"></a>cccCss

```php
array MediaCore::cccCss($css_files)
```

Combine Compress and Cache CSS (ccc) calls



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L447)


#### Arguments
* $css_files **mixed**



### <a name="method-cccJS"></a>cccJS

```php
array MediaCore::cccJS($js_files)
```

Combine Compress and Cache (ccc) JS calls



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L577)


#### Arguments
* $js_files **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed MediaCore::clearCache()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 660](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L660)




### <a name="method-deferInlineScripts"></a>deferInlineScripts

```php
mixed MediaCore::deferInlineScripts($output)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L718)


#### Arguments
* $output **mixed**



### <a name="method-deferScript"></a>deferScript

```php
mixed MediaCore::deferScript($matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L767)


#### Arguments
* $matches **mixed**



### <a name="method-getBackTrackLimit"></a>getBackTrackLimit

```php
mixed MediaCore::getBackTrackLimit()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L558)




### <a name="method-getCSSPath"></a>getCSSPath

```php
string MediaCore::getCSSPath(mixed $css_uri, string $css_media_type, boolean $need_rtl)
```

addCSS return stylesheet path.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L221)


#### Arguments
* $css_uri **mixed**
* $css_media_type **string**
* $need_rtl **boolean**



### <a name="method-getInlineScript"></a>getInlineScript

```php
mixed MediaCore::getInlineScript()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 680](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L680)




### <a name="method-getJSPath"></a>getJSPath

```php
string MediaCore::getJSPath(mixed $js_uri)
```

addJS return javascript path



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L208)


#### Arguments
* $js_uri **mixed**



### <a name="method-getJqueryPath"></a>getJqueryPath

```php
string MediaCore::getJqueryPath(mixed $version, $folder, $minifier)
```

return jquery path.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L287)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-getJqueryPluginCSSPath"></a>getJqueryPluginCSSPath

```php
string|boolean MediaCore::getJqueryPluginCSSPath(mixed $name, $folder)
```

return jquery plugin css path if exist.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L424)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-getJqueryPluginPath"></a>getJqueryPluginPath

```php
string|boolean MediaCore::getJqueryPluginPath(mixed $name, $folder)
```

return jquery plugin path.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L396)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-getJqueryUIPath"></a>getJqueryUIPath

```php
string MediaCore::getJqueryUIPath(mixed $component, $theme, $check_dependencies)
```

return jqueryUI component path.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L329)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-getJsDef"></a>getJsDef

```php
mixed MediaCore::getJsDef()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L674)




### <a name="method-getMediaPath"></a>getMediaPath

```php
mixed MediaCore::getMediaPath($media_uri, $css_media_type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L235)


#### Arguments
* $media_uri **mixed**
* $css_media_type **mixed**



### <a name="method-minifyCSS"></a>minifyCSS

```php
mixed MediaCore::minifyCSS($css_content, $fileuri, $import_url)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L168)


#### Arguments
* $css_content **mixed**
* $fileuri **mixed**
* $import_url **mixed**



### <a name="method-minifyHTML"></a>minifyHTML

```php
mixed MediaCore::minifyHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L81)


#### Arguments
* $html_content **mixed**



### <a name="method-minifyHTMLpregCallback"></a>minifyHTMLpregCallback

```php
mixed MediaCore::minifyHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L102)


#### Arguments
* $preg_matches **mixed**



### <a name="method-packJS"></a>packJS

```php
mixed MediaCore::packJS($js_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L152)


#### Arguments
* $js_content **mixed**



### <a name="method-packJSinHTML"></a>packJSinHTML

```php
mixed MediaCore::packJSinHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L116)


#### Arguments
* $html_content **mixed**



### <a name="method-packJSinHTMLpregCallback"></a>packJSinHTMLpregCallback

```php
mixed MediaCore::packJSinHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Media.php#L140)


#### Arguments
* $preg_matches **mixed**


