Class AdminThemesControllerCore
=====================





* Class name: AdminThemesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminThemesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L30)


Contents
--------

### Constants

* [MAX_NAME_LENGTH](#constant-MAX_NAME_LENGTH)

### Properties

* [$check_features](#property-$check_features)
* [$check_features_version](#property-$check_features_version)
* [$className](#property-$className)
* [$img_error](#property-$img_error)
* [$object](#property-$object)
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
* [downloadAddonsThemes](#method-downloadAddonsThemes)
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
* [installTheme](#method-installTheme)
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
* [setMedia](#method-setMedia)
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





* Source: [controllers/admin/AdminThemesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L32).


Properties
----------


### <a name="property-$check_features"></a>$check_features

```php
public array $check_features = array('ccc' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_CSS_THEME_CACHE' => 0, 'PS_JS_THEME_CACHE' => 0, 'PS_HTML_THEME_COMPRESSION' => 0, 'PS_JS_HTML_THEME_COMPRESSION' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "combine, compress and cache" options.', 'tab' => 'AdminPerformance'), 'guest_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_GUEST_CHECKOUT_ENABLED' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "guest checkout" feature.', 'tab' => 'AdminPreferences'), 'one_page_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_ORDER_PROCESS_TYPE' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "one-page checkout" feature.', 'tab' => 'AdminPreferences'), 'store_locator' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_STORES_SIMPLIFIED' => 0, 'PS_STORES_DISPLAY_FOOTER' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "store locator" feature.', 'tab' => 'AdminStores'))
```

Multidimensional array used to check [theme]/config.xml values,
and also checks prestashop current configuration if not match.



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L55).


### <a name="property-$check_features_version"></a>$check_features_version

```php
public string $check_features_version = '1.4'
```

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L47).


### <a name="property-$className"></a>$className

```php
public mixed $className = 'Theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L109).


### <a name="property-$img_error"></a>$img_error

```php
private mixed $img_error
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L112).


### <a name="property-$object"></a>$object

```php
public \Theme $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L30).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L110).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L111).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminThemesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L34)




### <a name="method-_checkConfigForFeatures"></a>_checkConfigForFeatures

```php
boolean AdminThemesControllerCore::_checkConfigForFeatures(array $arrFeatures, mixed $configItem)
```

_checkConfigForFeatures



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1943](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1943)


#### Arguments
* $arrFeatures **array** - array of feature code to check
* $configItem **mixed** - will precise the attribute which not matches. If empty, will check every attributes



### <a name="method-_isThemeCompatible"></a>_isThemeCompatible

```php
boolean AdminThemesControllerCore::_isThemeCompatible(string $theme_dir)
```

This function checks if the theme designer has thunk to make his theme compatible 1.4,
and noticed it on the $theme_dir/config.xml file. If not, some new functionnalities has
to be desactivated



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1887](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1887)


#### Arguments
* $theme_dir **string** - theme directory



### <a name="method-ajaxProcessGetAddonsThemes"></a>ajaxProcessGetAddonsThemes

```php
mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1864)




### <a name="method-ajaxProcessLeftMeta"></a>ajaxProcessLeftMeta

```php
mixed AdminThemesControllerCore::ajaxProcessLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2880](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2880)




### <a name="method-ajaxProcessRightMeta"></a>ajaxProcessRightMeta

```php
mixed AdminThemesControllerCore::ajaxProcessRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2918](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2918)




### <a name="method-archiveThisFile"></a>archiveThisFile

```php
mixed AdminThemesControllerCore::archiveThisFile(\ZipArchive $obj, string $file, string $server_path, string $archive_path)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 847](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L847)


#### Arguments
* $obj **ZipArchive**
* $file **string**
* $server_path **string**
* $archive_path **string**



### <a name="method-checkDocumentation"></a>checkDocumentation

```php
mixed AdminThemesControllerCore::checkDocumentation()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L780)




### <a name="method-checkNames"></a>checkNames

```php
mixed AdminThemesControllerCore::checkNames()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 764](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L764)




### <a name="method-checkParentClass"></a>checkParentClass

```php
mixed AdminThemesControllerCore::checkParentClass($name)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L746)


#### Arguments
* $name **mixed**



### <a name="method-checkPostedDatas"></a>checkPostedDatas

```php
mixed AdminThemesControllerCore::checkPostedDatas()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 824](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L824)




### <a name="method-checkVersionsAndCompatibility"></a>checkVersionsAndCompatibility

```php
mixed AdminThemesControllerCore::checkVersionsAndCompatibility()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L808)




### <a name="method-checkXmlFields"></a>checkXmlFields

```php
mixed AdminThemesControllerCore::checkXmlFields($xml_file)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1400](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1400)


#### Arguments
* $xml_file **mixed**



### <a name="method-copyTheme"></a>copyTheme

```php
boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)
```

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminThemesController.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L487)


#### Arguments
* $base_theme_dir **string** - relative path to base dir
* $target_theme_dir **string** - relative path to target dir



### <a name="method-downloadAddonsThemes"></a>downloadAddonsThemes

```php
mixed AdminThemesControllerCore::downloadAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 515](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L515)




### <a name="method-extractTheme"></a>extractTheme

```php
mixed AdminThemesControllerCore::extractTheme($theme_zip_file, $sandbox)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1516](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1516)


#### Arguments
* $theme_zip_file **mixed**
* $sandbox **mixed**



### <a name="method-formatHelperArray"></a>formatHelperArray

```php
mixed AdminThemesControllerCore::formatHelperArray($origin_arr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2153)


#### Arguments
* $origin_arr **mixed**



### <a name="method-formatHelperValuesArray"></a>formatHelperValuesArray

```php
mixed AdminThemesControllerCore::formatHelperValuesArray($originArr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2174)


#### Arguments
* $originArr **mixed**



### <a name="method-generateArchive"></a>generateArchive

```php
mixed AdminThemesControllerCore::generateArchive()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 862](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L862)




### <a name="method-generateXML"></a>generateXML

```php
mixed AdminThemesControllerCore::generateXML($theme_to_export, $metas)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 924](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L924)


#### Arguments
* $theme_to_export **mixed**
* $metas **mixed**



### <a name="method-getModules"></a>getModules

```php
mixed AdminThemesControllerCore::getModules($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2132)


#### Arguments
* $xml **mixed**



### <a name="method-getNativeModule"></a>getNativeModule

```php
array AdminThemesControllerCore::getNativeModule(integer $type)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2001](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2001)


#### Arguments
* $type **integer** - $type = 0 both native &amp; partner (default)
$type = 1 native
$type = 2 partner



### <a name="method-hookModule"></a>hookModule

```php
mixed AdminThemesControllerCore::hookModule($id_module, $module_hooks, $shop)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2404)


#### Arguments
* $id_module **mixed**
* $module_hooks **mixed**
* $shop **mixed**



### <a name="method-importThemeXmlConfig"></a>importThemeXmlConfig

```php
array|string AdminThemesControllerCore::importThemeXmlConfig(\SimpleXMLElement $xml, boolean $theme_dir)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1600](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1600)


#### Arguments
* $xml **SimpleXMLElement**
* $theme_dir **boolean** - only used if the theme directory to import is already located on the shop



### <a name="method-init"></a>init

```php
mixed AdminThemesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L114)




### <a name="method-initContent"></a>initContent

```php
mixed AdminThemesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1824](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1824)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminThemesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 713](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L713)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminThemesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2777](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2777)




### <a name="method-installTheme"></a>installTheme

```php
mixed AdminThemesControllerCore::installTheme($theme_dir, $sandbox, $redirect)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1525](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1525)


#### Arguments
* $theme_dir **mixed**
* $sandbox **mixed**
* $redirect **mixed**



### <a name="method-isThemeInstalled"></a>isThemeInstalled

```php
mixed AdminThemesControllerCore::isThemeInstalled($theme_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1581](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1581)


#### Arguments
* $theme_name **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminThemesControllerCore::postProcess()
```

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2587](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2587)




### <a name="method-printResponsiveIcon"></a>printResponsiveIcon

```php
mixed AdminThemesControllerCore::printResponsiveIcon($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2821](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2821)


#### Arguments
* $value **mixed**



### <a name="method-processAdd"></a>processAdd

```php
mixed AdminThemesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 556](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L556)




### <a name="method-processDefaultLeftColumn"></a>processDefaultLeftColumn

```php
mixed AdminThemesControllerCore::processDefaultLeftColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2844](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2844)




### <a name="method-processDefaultRightColumn"></a>processDefaultRightColumn

```php
mixed AdminThemesControllerCore::processDefaultRightColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2862](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2862)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminThemesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L671)




### <a name="method-processExportTheme"></a>processExportTheme

```php
mixed AdminThemesControllerCore::processExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1031](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1031)




### <a name="method-processImportTheme"></a>processImportTheme

```php
mixed AdminThemesControllerCore::processImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1444](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1444)




### <a name="method-processLeftMeta"></a>processLeftMeta

```php
mixed AdminThemesControllerCore::processLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2899)




### <a name="method-processResponsive"></a>processResponsive

```php
mixed AdminThemesControllerCore::processResponsive()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2826](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2826)




### <a name="method-processRightMeta"></a>processRightMeta

```php
mixed AdminThemesControllerCore::processRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2937)




### <a name="method-processThemeInstall"></a>processThemeInstall

```php
mixed AdminThemesControllerCore::processThemeInstall()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2430)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminThemesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L627)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminThemesControllerCore::processUpdateOptions()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 663](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L663)




### <a name="method-recurseCopy"></a>recurseCopy

```php
mixed AdminThemesControllerCore::recurseCopy($src, $dst)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1425)


#### Arguments
* $src **mixed**
* $dst **mixed**



### <a name="method-renderChooseThemeModule"></a>renderChooseThemeModule

```php
mixed AdminThemesControllerCore::renderChooseThemeModule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2184)




### <a name="method-renderExportTheme"></a>renderExportTheme

```php
mixed AdminThemesControllerCore::renderExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1350)




### <a name="method-renderExportTheme1"></a>renderExportTheme1

```php
mixed AdminThemesControllerCore::renderExportTheme1()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1155)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminThemesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L249)




### <a name="method-renderImportTheme"></a>renderImportTheme

```php
mixed AdminThemesControllerCore::renderImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1700](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L1700)




### <a name="method-renderList"></a>renderList

```php
mixed AdminThemesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L474)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminThemesControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2960](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2960)




### <a name="method-renderView"></a>renderView

```php
mixed AdminThemesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2568](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2568)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminThemesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2984](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2984)




### <a name="method-updateImages"></a>updateImages

```php
mixed AdminThemesControllerCore::updateImages($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2375)


#### Arguments
* $xml **mixed**



### <a name="method-updateLogo"></a>updateLogo

```php
boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)
```

Generic function which allows logo upload



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2658](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2658)


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### <a name="method-updateOptionPsFavicon"></a>updateOptionPsFavicon

```php
mixed AdminThemesControllerCore::updateOptionPsFavicon()
```

Update PS_FAVICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2732](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2732)




### <a name="method-updateOptionPsLogo"></a>updateOptionPsLogo

```php
mixed AdminThemesControllerCore::updateOptionPsLogo()
```

Update PS_LOGO



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2613](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2613)




### <a name="method-updateOptionPsLogoInvoice"></a>updateOptionPsLogoInvoice

```php
mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()
```

Update PS_LOGO_INVOICE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2637](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2637)




### <a name="method-updateOptionPsLogoMail"></a>updateOptionPsLogoMail

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMail()
```

Update PS_LOGO_MAIL



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2629](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2629)




### <a name="method-updateOptionPsLogoMobile"></a>updateOptionPsLogoMobile

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMobile()
```

Update PS_LOGO_MOBILE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2621](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2621)




### <a name="method-updateOptionPsStoresIcon"></a>updateOptionPsStoresIcon

```php
mixed AdminThemesControllerCore::updateOptionPsStoresIcon()
```

Update PS_STORES_ICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2645](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2645)




### <a name="method-updateOptionThemeForShop"></a>updateOptionThemeForShop

```php
mixed AdminThemesControllerCore::updateOptionThemeForShop()
```

Update theme for current shop



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2747](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2747)




### <a name="method-uploadIco"></a>uploadIco

```php
mixed AdminThemesControllerCore::uploadIco($name, $dest)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminThemesController.php#L2761)


#### Arguments
* $name **mixed**
* $dest **mixed**


