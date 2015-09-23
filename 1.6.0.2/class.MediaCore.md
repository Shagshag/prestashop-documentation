Class MediaCore
=====================





* Class name: MediaCore
* Source: [classes/Media.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L27)


Contents
--------


### Properties

* [$jquery_ui_dependencies](#property-$jquery_ui_dependencies)

### Methods

* [cccCss](#method-cccCss)
* [cccJS](#method-cccJS)
* [getBackTrackLimit](#method-getBackTrackLimit)
* [getCSSPath](#method-getCSSPath)
* [getJSPath](#method-getJSPath)
* [getJqueryPath](#method-getJqueryPath)
* [getJqueryPluginCSSPath](#method-getJqueryPluginCSSPath)
* [getJqueryPluginPath](#method-getJqueryPluginPath)
* [getJqueryUIPath](#method-getJqueryUIPath)
* [minifyCSS](#method-minifyCSS)
* [minifyHTML](#method-minifyHTML)
* [minifyHTMLpregCallback](#method-minifyHTMLpregCallback)
* [packJS](#method-packJS)
* [packJSinHTML](#method-packJSinHTML)
* [packJSinHTMLpregCallback](#method-packJSinHTMLpregCallback)




Properties
----------


### <a name="property-$jquery_ui_dependencies"></a>$jquery_ui_dependencies

```php
public mixed $jquery_ui_dependencies = array('ui.core' => array('fileName' => 'jquery.ui.core.min.js', 'dependencies' => array(), 'theme' => true), 'ui.widget' => array('fileName' => 'jquery.ui.widget.min.js', 'dependencies' => array(), 'theme' => false), 'ui.mouse' => array('fileName' => 'jquery.ui.mouse.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => false), 'ui.position' => array('fileName' => 'jquery.ui.position.min.js', 'dependencies' => array(), 'theme' => false), 'ui.draggable' => array('fileName' => 'jquery.ui.draggable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => false), 'ui.droppable' => array('fileName' => 'jquery.ui.droppable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse', 'ui.draggable'), 'theme' => false), 'ui.resizable' => array('fileName' => 'jquery.ui.resizable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.selectable' => array('fileName' => 'jquery.ui.selectable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.sortable' => array('fileName' => 'jquery.ui.sortable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.accordion' => array('fileName' => 'jquery.ui.accordion.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.autocomplete' => array('fileName' => 'jquery.ui.autocomplete.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'ui.menu'), 'theme' => true), 'ui.button' => array('fileName' => 'jquery.ui.button.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.dialog' => array('fileName' => 'jquery.ui.dialog.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'ui.button'), 'theme' => true), 'ui.menu' => array('fileName' => 'jquery.ui.menu.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position'), 'theme' => true), 'ui.slider' => array('fileName' => 'jquery.ui.slider.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.tabs' => array('fileName' => 'jquery.ui.tabs.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.datepicker' => array('fileName' => 'jquery.ui.datepicker.min.js', 'dependencies' => array('ui.core'), 'theme' => true), 'ui.progressbar' => array('fileName' => 'jquery.ui.progressbar.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.tooltip' => array('fileName' => 'jquery.ui.tooltip.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'effects.core'), 'theme' => true), 'effects.core' => array('fileName' => 'jquery.effects.core.min.js', 'dependencies' => array(), 'theme' => false), 'effects.blind' => array('fileName' => 'jquery.effects.blind.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.bounce' => array('fileName' => 'jquery.effects.bounce.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.clip' => array('fileName' => 'jquery.effects.clip.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.drop' => array('fileName' => 'jquery.effects.drop.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.explode' => array('fileName' => 'jquery.effects.explode.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.fade' => array('fileName' => 'jquery.effects.fade.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.fold' => array('fileName' => 'jquery.effects.fold.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.highlight' => array('fileName' => 'jquery.effects.highlight.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.pulsate' => array('fileName' => 'jquery.effects.pulsate.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.scale' => array('fileName' => 'jquery.effects.scale.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.shake' => array('fileName' => 'jquery.effects.shake.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.slide' => array('fileName' => 'jquery.effects.slide.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.transfer' => array('fileName' => 'jquery.effects.transfer.min.js', 'dependencies' => array('effects.core'), 'theme' => false))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Media.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L29).


Methods
-------


### <a name="method-cccCss"></a>cccCss

```php
array MediaCore::cccCss($css_files)
```

Combine Compress and Cache CSS (ccc) calls



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L391)


#### Arguments
* $css_files **mixed**



### <a name="method-cccJS"></a>cccJS

```php
array MediaCore::cccJS($js_files)
```

Combine Compress and Cache (ccc) JS calls



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L500)


#### Arguments
* $js_files **mixed**



### <a name="method-getBackTrackLimit"></a>getBackTrackLimit

```php
mixed MediaCore::getBackTrackLimit()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L481)




### <a name="method-getCSSPath"></a>getCSSPath

```php
string MediaCore::getCSSPath(mixed $css_uri, string $css_media_type)
```

addCSS return stylesheet path.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L222)


#### Arguments
* $css_uri **mixed**
* $css_media_type **string**



### <a name="method-getJSPath"></a>getJSPath

```php
string MediaCore::getJSPath(mixed $js_uri)
```

addJS return javascript path



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L192)


#### Arguments
* $js_uri **mixed**



### <a name="method-getJqueryPath"></a>getJqueryPath

```php
string MediaCore::getJqueryPath(mixed $version, $folder, $minifier)
```

return jquery path.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L248)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-getJqueryPluginCSSPath"></a>getJqueryPluginCSSPath

```php
void MediaCore::getJqueryPluginCSSPath(mixed $name, $folder)
```

return jquery plugin css path if exist.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L370)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-getJqueryPluginPath"></a>getJqueryPluginPath

```php
void MediaCore::getJqueryPluginPath(mixed $name, $folder)
```

return jquery plugin path.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L345)


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
* Source: [classes/Media.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L289)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-minifyCSS"></a>minifyCSS

```php
mixed MediaCore::minifyCSS($css_content, $fileuri, $import_url)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L152)


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
* Source: [classes/Media.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L66)


#### Arguments
* $html_content **mixed**



### <a name="method-minifyHTMLpregCallback"></a>minifyHTMLpregCallback

```php
mixed MediaCore::minifyHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L87)


#### Arguments
* $preg_matches **mixed**



### <a name="method-packJS"></a>packJS

```php
mixed MediaCore::packJS($js_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L136)


#### Arguments
* $js_content **mixed**



### <a name="method-packJSinHTML"></a>packJSinHTML

```php
mixed MediaCore::packJSinHTML($html_content)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L101)


#### Arguments
* $html_content **mixed**



### <a name="method-packJSinHTMLpregCallback"></a>packJSinHTMLpregCallback

```php
mixed MediaCore::packJSinHTMLpregCallback($preg_matches)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Media.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Media.php#L125)


#### Arguments
* $preg_matches **mixed**


