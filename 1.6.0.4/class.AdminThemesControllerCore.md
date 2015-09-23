Class AdminThemesControllerCore
=====================





* Class name: AdminThemesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminThemesController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L28)


Contents
--------

### Constants

* [MAX_NAME_LENGTH](#constant-MAX_NAME_LENGTH)

### Properties

* [$check_features](#property-$check_features)
* [$check_features_version](#property-$check_features_version)
* [$className](#property-$className)
* [$img_error](#property-$img_error)
* [$table](#property-$table)
* [$toolbar_scroll](#property-$toolbar_scroll)

### Methods

* [__construct](#method-__construct)
* [_checkConfigForFeatures](#method-_checkConfigForFeatures)
* [_isThemeCompatible](#method-_isThemeCompatible)
* [ajaxProcessGetAddonsThemes](#method-ajaxProcessGetAddonsThemes)
* [ajaxProcessLeftMeta](#method-ajaxProcessLeftMeta)
* [ajaxProcessRightMeta](#method-ajaxProcessRightMeta)
* [archiveThisFile](#method-archiveThisFile)
* [checkDocumentation](#method-checkDocumentation)
* [checkNames](#method-checkNames)
* [checkParentClass](#method-checkParentClass)
* [checkPostedDatas](#method-checkPostedDatas)
* [checkVersionsAndCompatibility](#method-checkVersionsAndCompatibility)
* [checkXmlFields](#method-checkXmlFields)
* [copyTheme](#method-copyTheme)
* [formatHelperArray](#method-formatHelperArray)
* [formatHelperValuesArray](#method-formatHelperValuesArray)
* [generateArchive](#method-generateArchive)
* [generateXML](#method-generateXML)
* [getModules](#method-getModules)
* [getNativeModule](#method-getNativeModule)
* [hookModule](#method-hookModule)
* [importThemeXmlConfig](#method-importThemeXmlConfig)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processDefaultLeftColumn](#method-processDefaultLeftColumn)
* [processDefaultRightColumn](#method-processDefaultRightColumn)
* [processDelete](#method-processDelete)
* [processExportTheme](#method-processExportTheme)
* [processImportTheme](#method-processImportTheme)
* [processLeftMeta](#method-processLeftMeta)
* [processResponsive](#method-processResponsive)
* [processRightMeta](#method-processRightMeta)
* [processThemeInstall](#method-processThemeInstall)
* [processUpdate](#method-processUpdate)
* [processUpdateOptions](#method-processUpdateOptions)
* [recurseCopy](#method-recurseCopy)
* [renderChooseThemeModule](#method-renderChooseThemeModule)
* [renderExportTheme](#method-renderExportTheme)
* [renderExportTheme1](#method-renderExportTheme1)
* [renderForm](#method-renderForm)
* [renderImportTheme](#method-renderImportTheme)
* [renderList](#method-renderList)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)
* [updateImages](#method-updateImages)
* [updateLogo](#method-updateLogo)
* [updateOptionPsFavicon](#method-updateOptionPsFavicon)
* [updateOptionPsLogo](#method-updateOptionPsLogo)
* [updateOptionPsLogoInvoice](#method-updateOptionPsLogoInvoice)
* [updateOptionPsLogoMail](#method-updateOptionPsLogoMail)
* [updateOptionPsLogoMobile](#method-updateOptionPsLogoMobile)
* [updateOptionPsStoresIcon](#method-updateOptionPsStoresIcon)
* [updateOptionThemeForShop](#method-updateOptionThemeForShop)
* [uploadIco](#method-uploadIco)


Constants
----------


### <a name="constant-MAX_NAME_LENGTH"></a>MAX_NAME_LENGTH

```php
const MAX_NAME_LENGTH = 128
```





* Source: [controllers/admin/AdminThemesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L30).


Properties
----------


### <a name="property-$check_features"></a>$check_features

```php
public mixed $check_features = array('ccc' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_CSS_THEME_CACHE' => 0, 'PS_JS_THEME_CACHE' => 0, 'PS_HTML_THEME_COMPRESSION' => 0, 'PS_JS_HTML_THEME_COMPRESSION' => 0))), 'error' => 'This theme may not correctly use "combine, compress and cache"', 'tab' => 'AdminPerformance'), 'guest_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_GUEST_CHECKOUT_ENABLED' => 0))), 'error' => 'This theme may not correctly use "guest checkout"', 'tab' => 'AdminPreferences'), 'one_page_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_ORDER_PROCESS_TYPE' => 0))), 'error' => 'This theme may not correctly use "one page checkout"', 'tab' => 'AdminPreferences'), 'store_locator' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_STORES_SIMPLIFIED' => 0, 'PS_STORES_DISPLAY_FOOTER' => 0))), 'error' => 'This theme may not correctly use "display store location"', 'tab' => 'AdminStores'))
```

$check_features is a multidimensional array used to check [theme]/config.xml values,
and also checks prestashop current configuration if not match.



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L49).


### <a name="property-$check_features_version"></a>$check_features_version

```php
public mixed $check_features_version = '1.4'
```

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L43).


### <a name="property-$className"></a>$className

```php
public mixed $className = 'Theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L103).


### <a name="property-$img_error"></a>$img_error

```php
private mixed $img_error
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L106).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L104).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L105).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminThemesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L32)




### <a name="method-_checkConfigForFeatures"></a>_checkConfigForFeatures

```php
\error AdminThemesControllerCore::_checkConfigForFeatures($arrFeatures, mixed $configItem)
```

_checkConfigForFeatures



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1838](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1838)


#### Arguments
* $arrFeatures **mixed**
* $configItem **mixed** - will precise the attribute which not matches. If empty, will check every attributes



### <a name="method-_isThemeCompatible"></a>_isThemeCompatible

```php
boolean AdminThemesControllerCore::_isThemeCompatible(string $theme_dir)
```

This function checks if the theme designer has thunk to make his theme compatible 1.4,
and noticed it on the $theme_dir/config.xml file. If not, some new functionnalities has
to be desactivated



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1782](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1782)


#### Arguments
* $theme_dir **string** - theme directory



### <a name="method-ajaxProcessGetAddonsThemes"></a>ajaxProcessGetAddonsThemes

```php
mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1760](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1760)




### <a name="method-ajaxProcessLeftMeta"></a>ajaxProcessLeftMeta

```php
mixed AdminThemesControllerCore::ajaxProcessLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2731](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2731)




### <a name="method-ajaxProcessRightMeta"></a>ajaxProcessRightMeta

```php
mixed AdminThemesControllerCore::ajaxProcessRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2769](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2769)




### <a name="method-archiveThisFile"></a>archiveThisFile

```php
mixed AdminThemesControllerCore::archiveThisFile($obj, $file, $server_path, $archive_path)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 810](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L810)


#### Arguments
* $obj **mixed**
* $file **mixed**
* $server_path **mixed**
* $archive_path **mixed**



### <a name="method-checkDocumentation"></a>checkDocumentation

```php
mixed AdminThemesControllerCore::checkDocumentation()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 751](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L751)




### <a name="method-checkNames"></a>checkNames

```php
mixed AdminThemesControllerCore::checkNames()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L735)




### <a name="method-checkParentClass"></a>checkParentClass

```php
mixed AdminThemesControllerCore::checkParentClass($name)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L697)


#### Arguments
* $name **mixed**



### <a name="method-checkPostedDatas"></a>checkPostedDatas

```php
mixed AdminThemesControllerCore::checkPostedDatas()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 793](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L793)




### <a name="method-checkVersionsAndCompatibility"></a>checkVersionsAndCompatibility

```php
mixed AdminThemesControllerCore::checkVersionsAndCompatibility()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 777](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L777)




### <a name="method-checkXmlFields"></a>checkXmlFields

```php
mixed AdminThemesControllerCore::checkXmlFields($sandbox)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1355)


#### Arguments
* $sandbox **mixed**



### <a name="method-copyTheme"></a>copyTheme

```php
boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)
```

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminThemesController.php line 503](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L503)


#### Arguments
* $base_theme_dir **string** - relative path to base dir
* $target_theme_dir **string** - relative path to target dir



### <a name="method-formatHelperArray"></a>formatHelperArray

```php
mixed AdminThemesControllerCore::formatHelperArray($origin_arr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2048](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2048)


#### Arguments
* $origin_arr **mixed**



### <a name="method-formatHelperValuesArray"></a>formatHelperValuesArray

```php
mixed AdminThemesControllerCore::formatHelperValuesArray($originArr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2069](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2069)


#### Arguments
* $originArr **mixed**



### <a name="method-generateArchive"></a>generateArchive

```php
mixed AdminThemesControllerCore::generateArchive()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 825](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L825)




### <a name="method-generateXML"></a>generateXML

```php
mixed AdminThemesControllerCore::generateXML($theme_to_export, $metas)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 872](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L872)


#### Arguments
* $theme_to_export **mixed**
* $metas **mixed**



### <a name="method-getModules"></a>getModules

```php
mixed AdminThemesControllerCore::getModules($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2027](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2027)


#### Arguments
* $xml **mixed**



### <a name="method-getNativeModule"></a>getNativeModule

```php
array AdminThemesControllerCore::getNativeModule(integer $type)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1896](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1896)


#### Arguments
* $type **integer** - $type = 0 both native &amp; partner (default)
$type = 1 native
$type = 2 partner



### <a name="method-hookModule"></a>hookModule

```php
mixed AdminThemesControllerCore::hookModule($id_module, $module_hooks, $shop)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2300](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2300)


#### Arguments
* $id_module **mixed**
* $module_hooks **mixed**
* $shop **mixed**



### <a name="method-importThemeXmlConfig"></a>importThemeXmlConfig

```php
string|\Theme AdminThemesControllerCore::importThemeXmlConfig(\SimpleXMLElement $xml, boolean $theme_dir)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1499)


#### Arguments
* $xml **SimpleXMLElement**
* $theme_dir **boolean** - only used if the theme directory to import is already located on the shop



### <a name="method-init"></a>init

```php
mixed AdminThemesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L108)




### <a name="method-initContent"></a>initContent

```php
mixed AdminThemesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1695](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1695)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminThemesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L668)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminThemesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2636](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2636)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminThemesControllerCore::postProcess()
```

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2480](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2480)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminThemesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 531](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L531)




### <a name="method-processDefaultLeftColumn"></a>processDefaultLeftColumn

```php
mixed AdminThemesControllerCore::processDefaultLeftColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2697)




### <a name="method-processDefaultRightColumn"></a>processDefaultRightColumn

```php
mixed AdminThemesControllerCore::processDefaultRightColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2714](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2714)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminThemesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 641](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L641)




### <a name="method-processExportTheme"></a>processExportTheme

```php
mixed AdminThemesControllerCore::processExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 979](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L979)




### <a name="method-processImportTheme"></a>processImportTheme

```php
mixed AdminThemesControllerCore::processImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1399](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1399)




### <a name="method-processLeftMeta"></a>processLeftMeta

```php
mixed AdminThemesControllerCore::processLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2750](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2750)




### <a name="method-processResponsive"></a>processResponsive

```php
mixed AdminThemesControllerCore::processResponsive()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2680](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2680)




### <a name="method-processRightMeta"></a>processRightMeta

```php
mixed AdminThemesControllerCore::processRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2788](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2788)




### <a name="method-processThemeInstall"></a>processThemeInstall

```php
mixed AdminThemesControllerCore::processThemeInstall()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2328](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2328)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminThemesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L597)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminThemesControllerCore::processUpdateOptions()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L633)




### <a name="method-recurseCopy"></a>recurseCopy

```php
mixed AdminThemesControllerCore::recurseCopy($src, $dst)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1380](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1380)


#### Arguments
* $src **mixed**
* $dst **mixed**



### <a name="method-renderChooseThemeModule"></a>renderChooseThemeModule

```php
mixed AdminThemesControllerCore::renderChooseThemeModule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2079](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2079)




### <a name="method-renderExportTheme"></a>renderExportTheme

```php
mixed AdminThemesControllerCore::renderExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1305)




### <a name="method-renderExportTheme1"></a>renderExportTheme1

```php
mixed AdminThemesControllerCore::renderExportTheme1()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1109)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminThemesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L261)




### <a name="method-renderImportTheme"></a>renderImportTheme

```php
mixed AdminThemesControllerCore::renderImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1581](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L1581)




### <a name="method-renderList"></a>renderList

```php
mixed AdminThemesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L487)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminThemesControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2811](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2811)




### <a name="method-renderView"></a>renderView

```php
mixed AdminThemesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2461)




### <a name="method-updateImages"></a>updateImages

```php
mixed AdminThemesControllerCore::updateImages($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2271)


#### Arguments
* $xml **mixed**



### <a name="method-updateLogo"></a>updateLogo

```php
boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)
```

Generic function which allows logo upload



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2545](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2545)


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### <a name="method-updateOptionPsFavicon"></a>updateOptionPsFavicon

```php
mixed AdminThemesControllerCore::updateOptionPsFavicon()
```

Update PS_FAVICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2591](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2591)




### <a name="method-updateOptionPsLogo"></a>updateOptionPsLogo

```php
mixed AdminThemesControllerCore::updateOptionPsLogo()
```

Update PS_LOGO



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2500](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2500)




### <a name="method-updateOptionPsLogoInvoice"></a>updateOptionPsLogoInvoice

```php
mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()
```

Update PS_LOGO_INVOICE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2524](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2524)




### <a name="method-updateOptionPsLogoMail"></a>updateOptionPsLogoMail

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMail()
```

Update PS_LOGO_MAIL



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2516](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2516)




### <a name="method-updateOptionPsLogoMobile"></a>updateOptionPsLogoMobile

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMobile()
```

Update PS_LOGO_MOBILE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2508](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2508)




### <a name="method-updateOptionPsStoresIcon"></a>updateOptionPsStoresIcon

```php
mixed AdminThemesControllerCore::updateOptionPsStoresIcon()
```

Update PS_STORES_ICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2532](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2532)




### <a name="method-updateOptionThemeForShop"></a>updateOptionThemeForShop

```php
mixed AdminThemesControllerCore::updateOptionThemeForShop()
```

Update theme for current shop



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2606)




### <a name="method-uploadIco"></a>uploadIco

```php
mixed AdminThemesControllerCore::uploadIco($name, $dest)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminThemesController.php#L2620)


#### Arguments
* $name **mixed**
* $dest **mixed**


