Class AdminThemesControllerCore
=====================





* Class name: AdminThemesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminThemesController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L28)


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
* [extractTheme](#method-extractTheme)
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
* [isThemeInstalled](#method-isThemeInstalled)
* [postProcess](#method-postProcess)
* [printResponsiveIcon](#method-printResponsiveIcon)
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





* Source: [controllers/admin/AdminThemesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L30).


Properties
----------


### <a name="property-$check_features"></a>$check_features

```php
public mixed $check_features = array('ccc' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_CSS_THEME_CACHE' => 0, 'PS_JS_THEME_CACHE' => 0, 'PS_HTML_THEME_COMPRESSION' => 0, 'PS_JS_HTML_THEME_COMPRESSION' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "combine, compress and cache" options.', 'tab' => 'AdminPerformance'), 'guest_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_GUEST_CHECKOUT_ENABLED' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "guest checkout" feature.', 'tab' => 'AdminPreferences'), 'one_page_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_ORDER_PROCESS_TYPE' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "one-page checkout" feature.', 'tab' => 'AdminPreferences'), 'store_locator' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_STORES_SIMPLIFIED' => 0, 'PS_STORES_DISPLAY_FOOTER' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "store locator" feature.', 'tab' => 'AdminStores'))
```

$check_features is a multidimensional array used to check [theme]/config.xml values,
and also checks prestashop current configuration if not match.



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L49).


### <a name="property-$check_features_version"></a>$check_features_version

```php
public mixed $check_features_version = '1.4'
```

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L43).


### <a name="property-$className"></a>$className

```php
public mixed $className = 'Theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L103).


### <a name="property-$img_error"></a>$img_error

```php
private mixed $img_error
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L106).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L104).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L105).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminThemesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L32)




### <a name="method-_checkConfigForFeatures"></a>_checkConfigForFeatures

```php
\error AdminThemesControllerCore::_checkConfigForFeatures($arrFeatures, mixed $configItem)
```

_checkConfigForFeatures



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1974](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1974)


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
* Source: [controllers/admin/AdminThemesController.php line 1918](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1918)


#### Arguments
* $theme_dir **string** - theme directory



### <a name="method-ajaxProcessGetAddonsThemes"></a>ajaxProcessGetAddonsThemes

```php
mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1895](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1895)




### <a name="method-ajaxProcessLeftMeta"></a>ajaxProcessLeftMeta

```php
mixed AdminThemesControllerCore::ajaxProcessLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2873](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2873)




### <a name="method-ajaxProcessRightMeta"></a>ajaxProcessRightMeta

```php
mixed AdminThemesControllerCore::ajaxProcessRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2911](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2911)




### <a name="method-archiveThisFile"></a>archiveThisFile

```php
mixed AdminThemesControllerCore::archiveThisFile($obj, $file, $server_path, $archive_path)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 910](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L910)


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
* Source: [controllers/admin/AdminThemesController.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L851)




### <a name="method-checkNames"></a>checkNames

```php
mixed AdminThemesControllerCore::checkNames()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L835)




### <a name="method-checkParentClass"></a>checkParentClass

```php
mixed AdminThemesControllerCore::checkParentClass($name)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 797](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L797)


#### Arguments
* $name **mixed**



### <a name="method-checkPostedDatas"></a>checkPostedDatas

```php
mixed AdminThemesControllerCore::checkPostedDatas()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 893](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L893)




### <a name="method-checkVersionsAndCompatibility"></a>checkVersionsAndCompatibility

```php
mixed AdminThemesControllerCore::checkVersionsAndCompatibility()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 877](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L877)




### <a name="method-checkXmlFields"></a>checkXmlFields

```php
mixed AdminThemesControllerCore::checkXmlFields($sandbox)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1470)


#### Arguments
* $sandbox **mixed**



### <a name="method-copyTheme"></a>copyTheme

```php
boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)
```

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminThemesController.php line 587](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L587)


#### Arguments
* $base_theme_dir **string** - relative path to base dir
* $target_theme_dir **string** - relative path to target dir



### <a name="method-extractTheme"></a>extractTheme

```php
mixed AdminThemesControllerCore::extractTheme($theme_zip_file, $sandbox)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1582](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1582)


#### Arguments
* $theme_zip_file **mixed**
* $sandbox **mixed**



### <a name="method-formatHelperArray"></a>formatHelperArray

```php
mixed AdminThemesControllerCore::formatHelperArray($origin_arr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2184)


#### Arguments
* $origin_arr **mixed**



### <a name="method-formatHelperValuesArray"></a>formatHelperValuesArray

```php
mixed AdminThemesControllerCore::formatHelperValuesArray($originArr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2205)


#### Arguments
* $originArr **mixed**



### <a name="method-generateArchive"></a>generateArchive

```php
mixed AdminThemesControllerCore::generateArchive()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L925)




### <a name="method-generateXML"></a>generateXML

```php
mixed AdminThemesControllerCore::generateXML($theme_to_export, $metas)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L987)


#### Arguments
* $theme_to_export **mixed**
* $metas **mixed**



### <a name="method-getModules"></a>getModules

```php
mixed AdminThemesControllerCore::getModules($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2163)


#### Arguments
* $xml **mixed**



### <a name="method-getNativeModule"></a>getNativeModule

```php
array AdminThemesControllerCore::getNativeModule(integer $type)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2032)


#### Arguments
* $type **integer** - $type = 0 both native &amp; partner (default)
$type = 1 native
$type = 2 partner



### <a name="method-hookModule"></a>hookModule

```php
mixed AdminThemesControllerCore::hookModule($id_module, $module_hooks, $shop)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2437](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2437)


#### Arguments
* $id_module **mixed**
* $module_hooks **mixed**
* $shop **mixed**



### <a name="method-importThemeXmlConfig"></a>importThemeXmlConfig

```php
array|string AdminThemesControllerCore::importThemeXmlConfig(\SimpleXMLElement $xml, boolean $theme_dir)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1638)


#### Arguments
* $xml **SimpleXMLElement**
* $theme_dir **boolean** - only used if the theme directory to import is already located on the shop



### <a name="method-init"></a>init

```php
mixed AdminThemesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L108)




### <a name="method-initContent"></a>initContent

```php
mixed AdminThemesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1854](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1854)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminThemesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 765](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L765)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminThemesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2773](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2773)




### <a name="method-isThemeInstalled"></a>isThemeInstalled

```php
mixed AdminThemesControllerCore::isThemeInstalled($theme_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1620)


#### Arguments
* $theme_name **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminThemesControllerCore::postProcess()
```

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2617](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2617)




### <a name="method-printResponsiveIcon"></a>printResponsiveIcon

```php
mixed AdminThemesControllerCore::printResponsiveIcon($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2817](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2817)


#### Arguments
* $value **mixed**



### <a name="method-processAdd"></a>processAdd

```php
mixed AdminThemesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L615)




### <a name="method-processDefaultLeftColumn"></a>processDefaultLeftColumn

```php
mixed AdminThemesControllerCore::processDefaultLeftColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2839](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2839)




### <a name="method-processDefaultRightColumn"></a>processDefaultRightColumn

```php
mixed AdminThemesControllerCore::processDefaultRightColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2856](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2856)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminThemesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L733)




### <a name="method-processExportTheme"></a>processExportTheme

```php
mixed AdminThemesControllerCore::processExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1094](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1094)




### <a name="method-processImportTheme"></a>processImportTheme

```php
mixed AdminThemesControllerCore::processImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1514](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1514)




### <a name="method-processLeftMeta"></a>processLeftMeta

```php
mixed AdminThemesControllerCore::processLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2892](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2892)




### <a name="method-processResponsive"></a>processResponsive

```php
mixed AdminThemesControllerCore::processResponsive()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2822](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2822)




### <a name="method-processRightMeta"></a>processRightMeta

```php
mixed AdminThemesControllerCore::processRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2930](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2930)




### <a name="method-processThemeInstall"></a>processThemeInstall

```php
mixed AdminThemesControllerCore::processThemeInstall()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2465](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2465)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminThemesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 687](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L687)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminThemesControllerCore::processUpdateOptions()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 725](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L725)




### <a name="method-recurseCopy"></a>recurseCopy

```php
mixed AdminThemesControllerCore::recurseCopy($src, $dst)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1495)


#### Arguments
* $src **mixed**
* $dst **mixed**



### <a name="method-renderChooseThemeModule"></a>renderChooseThemeModule

```php
mixed AdminThemesControllerCore::renderChooseThemeModule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2215)




### <a name="method-renderExportTheme"></a>renderExportTheme

```php
mixed AdminThemesControllerCore::renderExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1420)




### <a name="method-renderExportTheme1"></a>renderExportTheme1

```php
mixed AdminThemesControllerCore::renderExportTheme1()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1224)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminThemesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L341)




### <a name="method-renderImportTheme"></a>renderImportTheme

```php
mixed AdminThemesControllerCore::renderImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1738](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L1738)




### <a name="method-renderList"></a>renderList

```php
mixed AdminThemesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L573)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminThemesControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2953](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2953)




### <a name="method-renderView"></a>renderView

```php
mixed AdminThemesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2598](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2598)




### <a name="method-updateImages"></a>updateImages

```php
mixed AdminThemesControllerCore::updateImages($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2408](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2408)


#### Arguments
* $xml **mixed**



### <a name="method-updateLogo"></a>updateLogo

```php
boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)
```

Generic function which allows logo upload



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2682](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2682)


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### <a name="method-updateOptionPsFavicon"></a>updateOptionPsFavicon

```php
mixed AdminThemesControllerCore::updateOptionPsFavicon()
```

Update PS_FAVICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2728](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2728)




### <a name="method-updateOptionPsLogo"></a>updateOptionPsLogo

```php
mixed AdminThemesControllerCore::updateOptionPsLogo()
```

Update PS_LOGO



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2637](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2637)




### <a name="method-updateOptionPsLogoInvoice"></a>updateOptionPsLogoInvoice

```php
mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()
```

Update PS_LOGO_INVOICE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2661](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2661)




### <a name="method-updateOptionPsLogoMail"></a>updateOptionPsLogoMail

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMail()
```

Update PS_LOGO_MAIL



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2653](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2653)




### <a name="method-updateOptionPsLogoMobile"></a>updateOptionPsLogoMobile

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMobile()
```

Update PS_LOGO_MOBILE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2645](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2645)




### <a name="method-updateOptionPsStoresIcon"></a>updateOptionPsStoresIcon

```php
mixed AdminThemesControllerCore::updateOptionPsStoresIcon()
```

Update PS_STORES_ICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2669](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2669)




### <a name="method-updateOptionThemeForShop"></a>updateOptionThemeForShop

```php
mixed AdminThemesControllerCore::updateOptionThemeForShop()
```

Update theme for current shop



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2743](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2743)




### <a name="method-uploadIco"></a>uploadIco

```php
mixed AdminThemesControllerCore::uploadIco($name, $dest)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2757](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminThemesController.php#L2757)


#### Arguments
* $name **mixed**
* $dest **mixed**


