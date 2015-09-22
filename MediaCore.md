MediaCore
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


* Class name: MediaCore
* Namespace: 
* This class is defined in classes\Media.php line 27





Properties
----------


### $jquery_ui_dependencies

    public mixed $jquery_ui_dependencies = array('ui.core' => array('fileName' => 'jquery.ui.core.min.js', 'dependencies' => array(), 'theme' => true), 'ui.widget' => array('fileName' => 'jquery.ui.widget.min.js', 'dependencies' => array(), 'theme' => false), 'ui.mouse' => array('fileName' => 'jquery.ui.mouse.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => false), 'ui.position' => array('fileName' => 'jquery.ui.position.min.js', 'dependencies' => array(), 'theme' => false), 'ui.draggable' => array('fileName' => 'jquery.ui.draggable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => false), 'ui.droppable' => array('fileName' => 'jquery.ui.droppable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse', 'ui.draggable'), 'theme' => false), 'ui.resizable' => array('fileName' => 'jquery.ui.resizable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.selectable' => array('fileName' => 'jquery.ui.selectable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.sortable' => array('fileName' => 'jquery.ui.sortable.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.autocomplete' => array('fileName' => 'jquery.ui.autocomplete.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'ui.menu'), 'theme' => true), 'ui.button' => array('fileName' => 'jquery.ui.button.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.dialog' => array('fileName' => 'jquery.ui.dialog.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'ui.button'), 'theme' => true), 'ui.menu' => array('fileName' => 'jquery.ui.menu.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position'), 'theme' => true), 'ui.slider' => array('fileName' => 'jquery.ui.slider.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.mouse'), 'theme' => true), 'ui.spinner' => array('fileName' => 'jquery.ui.spinner.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.button'), 'theme' => true), 'ui.tabs' => array('fileName' => 'jquery.ui.tabs.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.datepicker' => array('fileName' => 'jquery.ui.datepicker.min.js', 'dependencies' => array('ui.core'), 'theme' => true), 'ui.progressbar' => array('fileName' => 'jquery.ui.progressbar.min.js', 'dependencies' => array('ui.core', 'ui.widget'), 'theme' => true), 'ui.tooltip' => array('fileName' => 'jquery.ui.tooltip.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'ui.position', 'effects.core'), 'theme' => true), 'ui.accordion' => array('fileName' => 'jquery.ui.accordion.min.js', 'dependencies' => array('ui.core', 'ui.widget', 'effects.core'), 'theme' => true), 'effects.core' => array('fileName' => 'jquery.effects.core.min.js', 'dependencies' => array(), 'theme' => false), 'effects.blind' => array('fileName' => 'jquery.effects.blind.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.bounce' => array('fileName' => 'jquery.effects.bounce.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.clip' => array('fileName' => 'jquery.effects.clip.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.drop' => array('fileName' => 'jquery.effects.drop.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.explode' => array('fileName' => 'jquery.effects.explode.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.fade' => array('fileName' => 'jquery.effects.fade.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.fold' => array('fileName' => 'jquery.effects.fold.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.highlight' => array('fileName' => 'jquery.effects.highlight.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.pulsate' => array('fileName' => 'jquery.effects.pulsate.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.scale' => array('fileName' => 'jquery.effects.scale.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.shake' => array('fileName' => 'jquery.effects.shake.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.slide' => array('fileName' => 'jquery.effects.slide.min.js', 'dependencies' => array('effects.core'), 'theme' => false), 'effects.transfer' => array('fileName' => 'jquery.effects.transfer.min.js', 'dependencies' => array('effects.core'), 'theme' => false))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Media.php line 29


### $js_def

    protected array $js_def = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Media.php line 69


### $inline_script

    protected array $inline_script = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Media.php line 74


### $inline_script_src

    protected array $inline_script_src = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Media.php line 79


### $pattern_callback

    public string $pattern_callback = '#(url\((?![\'"]?(?:data:|//|https?:))(?:\'|")?)([^\)\'"]*)(?=[\'"]?\))#s'





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Media.php line 84


### $current_css_file

    protected string $current_css_file





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Media.php line 89


### $pattern_js

    public string $pattern_js = '#\s*(<\s*script(?:\s[^>]*(?:javascript)[^>]*|)+>)(.*)(<\s*/script\s*[^>]*>)\s*#Uims'





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Media.php line 94


Methods
-------


### minifyHTML

    mixed MediaCore::minifyHTML($html_content)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 96


#### Arguments
* $html_content **mixed**



### minifyHTMLpregCallback

    mixed MediaCore::minifyHTMLpregCallback($preg_matches)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 117


#### Arguments
* $preg_matches **mixed**



### packJSinHTML

    mixed MediaCore::packJSinHTML($html_content)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 132


#### Arguments
* $html_content **mixed**



### packJSinHTMLpregCallback

    mixed MediaCore::packJSinHTMLpregCallback($preg_matches)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 155


#### Arguments
* $preg_matches **mixed**



### packJS

    mixed MediaCore::packJS($js_content)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 168


#### Arguments
* $js_content **mixed**



### minifyCSS

    mixed MediaCore::minifyCSS($css_content, $fileuri, $import_url)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 184


#### Arguments
* $css_content **mixed**
* $fileuri **mixed**
* $import_url **mixed**



### replaceByAbsoluteURL

    mixed MediaCore::replaceByAbsoluteURL($matches)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 216


#### Arguments
* $matches **mixed**



### getJSPath

    string MediaCore::getJSPath(mixed $js_uri)

addJS return javascript path



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 239


#### Arguments
* $js_uri **mixed**



### getCSSPath

    string MediaCore::getCSSPath(mixed $css_uri, string $css_media_type, boolean $need_rtl)

addCSS return stylesheet path.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 253


#### Arguments
* $css_uri **mixed**
* $css_media_type **string**
* $need_rtl **boolean**



### getMediaPath

    mixed MediaCore::getMediaPath($media_uri, $css_media_type)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 267


#### Arguments
* $media_uri **mixed**
* $css_media_type **mixed**



### getJqueryPath

    string MediaCore::getJqueryPath(mixed $version, $folder, $minifier)

return jquery path.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 319


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### getJqueryUIPath

    string MediaCore::getJqueryUIPath(mixed $component, $theme, $check_dependencies)

return jqueryUI component path.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 370


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### getJqueryPluginPath

    string|boolean MediaCore::getJqueryPluginPath(mixed $name, $folder)

return jquery plugin path.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 438


#### Arguments
* $name **mixed**
* $folder **mixed**



### getJqueryPluginCSSPath

    string|boolean MediaCore::getJqueryPluginCSSPath(mixed $name, $folder)

return jquery plugin css path if exist.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 469


#### Arguments
* $name **mixed**
* $folder **mixed**



### cccCss

    array MediaCore::cccCss(array $css_files)

Combine Compress and Cache CSS (ccc) calls



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 495


#### Arguments
* $css_files **array**



### getBackTrackLimit

    mixed MediaCore::getBackTrackLimit()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 602




### cccJS

    array MediaCore::cccJS(array $js_files)

Combine Compress and Cache (ccc) JS calls



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 622


#### Arguments
* $js_files **array**



### clearCache

    void MediaCore::clearCache()

Clear theme cache



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 711




### getJsDef

    array MediaCore::getJsDef()

Get JS definitions



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 734




### getInlineScript

    array MediaCore::getInlineScript()

Get JS inline script



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 745




### addJsDef

    void MediaCore::addJsDef(mixed $js_def)

Add a new javascript definition at bottom of page



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 757


#### Arguments
* $js_def **mixed**



### addJsDefL

    void MediaCore::addJsDefL(mixed $params, string $content, \Smarty $smarty, boolean $repeat)

Add a new javascript definition from a capture at bottom of page



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 778


#### Arguments
* $params **mixed**
* $content **string**
* $smarty **Smarty**
* $repeat **boolean**



### deferInlineScripts

    mixed MediaCore::deferInlineScripts($output)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 791


#### Arguments
* $output **mixed**



### deferScript

    boolean|string MediaCore::deferScript(array $matches)

Get all JS scripts and place it to bottom
To be used in callback with deferInlineScripts



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Media.php line 851


#### Arguments
* $matches **array**


