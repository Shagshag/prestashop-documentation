Class AdminThemesControllerCore
=====================





* Class name: AdminThemesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminThemesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L27)


Contents
--------


### Properties

* [$check_features](#property-$check_features)
* [$check_features_version](#property-$check_features_version)
* [$className](#property-$className)
* [$img_error](#property-$img_error)
* [$max_name_length](#property-$max_name_length)
* [$table](#property-$table)
* [$toolbar_scroll](#property-$toolbar_scroll)

### Methods

* [__construct](#method-__construct)
* [_checkConfigForFeatures](#method-_checkConfigForFeatures)
* [_isThemeCompatible](#method-_isThemeCompatible)
* [ajaxProcessGetAddonsThemes](#method-ajaxProcessGetAddonsThemes)
* [archiveThisFile](#method-archiveThisFile)
* [checkDocumentation](#method-checkDocumentation)
* [checkMobileNeeds](#method-checkMobileNeeds)
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
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processDelete](#method-processDelete)
* [processExportTheme](#method-processExportTheme)
* [processImportTheme](#method-processImportTheme)
* [processThemeInstall](#method-processThemeInstall)
* [processUpdate](#method-processUpdate)
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
* [updateThemeMetas](#method-updateThemeMetas)
* [uploadIco](#method-uploadIco)




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
* Source: [controllers/admin/AdminThemesController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L47).


### <a name="property-$check_features_version"></a>$check_features_version

```php
public mixed $check_features_version = '1.4'
```

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L40).


### <a name="property-$className"></a>$className

```php
public mixed $className = 'Theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L98).


### <a name="property-$img_error"></a>$img_error

```php
private mixed $img_error
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L101).


### <a name="property-$max_name_length"></a>$max_name_length

```php
public mixed $max_name_length = 128
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L41).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L99).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L100).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminThemesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L29)




### <a name="method-_checkConfigForFeatures"></a>_checkConfigForFeatures

```php
\error AdminThemesControllerCore::_checkConfigForFeatures($arrFeatures, mixed $configItem)
```

_checkConfigForFeatures



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1610](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1610)


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
* Source: [controllers/admin/AdminThemesController.php line 1560](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1560)


#### Arguments
* $theme_dir **string** - theme directory



### <a name="method-ajaxProcessGetAddonsThemes"></a>ajaxProcessGetAddonsThemes

```php
mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1542)




### <a name="method-archiveThisFile"></a>archiveThisFile

```php
mixed AdminThemesControllerCore::archiveThisFile($obj, $file, $server_path, $archive_path)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L702)


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
* Source: [controllers/admin/AdminThemesController.php line 650](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L650)




### <a name="method-checkMobileNeeds"></a>checkMobileNeeds

```php
mixed AdminThemesControllerCore::checkMobileNeeds()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L243)




### <a name="method-checkNames"></a>checkNames

```php
mixed AdminThemesControllerCore::checkNames()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 635](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L635)




### <a name="method-checkParentClass"></a>checkParentClass

```php
mixed AdminThemesControllerCore::checkParentClass($name)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 616](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L616)


#### Arguments
* $name **mixed**



### <a name="method-checkPostedDatas"></a>checkPostedDatas

```php
mixed AdminThemesControllerCore::checkPostedDatas()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 686](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L686)




### <a name="method-checkVersionsAndCompatibility"></a>checkVersionsAndCompatibility

```php
mixed AdminThemesControllerCore::checkVersionsAndCompatibility()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L672)




### <a name="method-checkXmlFields"></a>checkXmlFields

```php
mixed AdminThemesControllerCore::checkXmlFields($sandbox)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1212)


#### Arguments
* $sandbox **mixed**



### <a name="method-copyTheme"></a>copyTheme

```php
boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)
```

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminThemesController.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L474)


#### Arguments
* $base_theme_dir **string** - relative path to base dir
* $target_theme_dir **string** - relative path to target dir



### <a name="method-formatHelperArray"></a>formatHelperArray

```php
mixed AdminThemesControllerCore::formatHelperArray($origin_arr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1709](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1709)


#### Arguments
* $origin_arr **mixed**



### <a name="method-formatHelperValuesArray"></a>formatHelperValuesArray

```php
mixed AdminThemesControllerCore::formatHelperValuesArray($originArr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1734](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1734)


#### Arguments
* $originArr **mixed**



### <a name="method-generateArchive"></a>generateArchive

```php
mixed AdminThemesControllerCore::generateArchive()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 715](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L715)




### <a name="method-generateXML"></a>generateXML

```php
mixed AdminThemesControllerCore::generateXML($theme_to_export, $metas)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 762](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L762)


#### Arguments
* $theme_to_export **mixed**
* $metas **mixed**



### <a name="method-getModules"></a>getModules

```php
mixed AdminThemesControllerCore::getModules($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1693](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1693)


#### Arguments
* $xml **mixed**



### <a name="method-getNativeModule"></a>getNativeModule

```php
mixed AdminThemesControllerCore::getNativeModule()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1654](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1654)




### <a name="method-hookModule"></a>hookModule

```php
mixed AdminThemesControllerCore::hookModule($id_module, $module_hooks, $shop)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1925](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1925)


#### Arguments
* $id_module **mixed**
* $module_hooks **mixed**
* $shop **mixed**



### <a name="method-init"></a>init

```php
mixed AdminThemesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L103)




### <a name="method-initContent"></a>initContent

```php
mixed AdminThemesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1492](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1492)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminThemesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 593](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L593)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminThemesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2254](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2254)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminThemesControllerCore::postProcess()
```

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2106)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminThemesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L522)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminThemesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L574)




### <a name="method-processExportTheme"></a>processExportTheme

```php
mixed AdminThemesControllerCore::processExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 866](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L866)




### <a name="method-processImportTheme"></a>processImportTheme

```php
mixed AdminThemesControllerCore::processImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1247)




### <a name="method-processThemeInstall"></a>processThemeInstall

```php
mixed AdminThemesControllerCore::processThemeInstall()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1956](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1956)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminThemesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L555)




### <a name="method-recurseCopy"></a>recurseCopy

```php
mixed AdminThemesControllerCore::recurseCopy($src, $dst)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1230)


#### Arguments
* $src **mixed**
* $dst **mixed**



### <a name="method-renderChooseThemeModule"></a>renderChooseThemeModule

```php
mixed AdminThemesControllerCore::renderChooseThemeModule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1745](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1745)




### <a name="method-renderExportTheme"></a>renderExportTheme

```php
mixed AdminThemesControllerCore::renderExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1163)




### <a name="method-renderExportTheme1"></a>renderExportTheme1

```php
mixed AdminThemesControllerCore::renderExportTheme1()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 980](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L980)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminThemesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L262)




### <a name="method-renderImportTheme"></a>renderImportTheme

```php
mixed AdminThemesControllerCore::renderImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1391)




### <a name="method-renderList"></a>renderList

```php
mixed AdminThemesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L459)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminThemesControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2265)




### <a name="method-renderView"></a>renderView

```php
mixed AdminThemesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2089](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2089)




### <a name="method-updateImages"></a>updateImages

```php
mixed AdminThemesControllerCore::updateImages($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1886](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L1886)


#### Arguments
* $xml **mixed**



### <a name="method-updateLogo"></a>updateLogo

```php
boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)
```

Generic function which allows logo upload



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2172)


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### <a name="method-updateOptionPsFavicon"></a>updateOptionPsFavicon

```php
mixed AdminThemesControllerCore::updateOptionPsFavicon()
```

Update PS_FAVICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2210)




### <a name="method-updateOptionPsLogo"></a>updateOptionPsLogo

```php
mixed AdminThemesControllerCore::updateOptionPsLogo()
```

Update PS_LOGO



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2128)




### <a name="method-updateOptionPsLogoInvoice"></a>updateOptionPsLogoInvoice

```php
mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()
```

Update PS_LOGO_INVOICE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2152)




### <a name="method-updateOptionPsLogoMail"></a>updateOptionPsLogoMail

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMail()
```

Update PS_LOGO_MAIL



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2144)




### <a name="method-updateOptionPsLogoMobile"></a>updateOptionPsLogoMobile

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMobile()
```

Update PS_LOGO_MOBILE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2136)




### <a name="method-updateOptionPsStoresIcon"></a>updateOptionPsStoresIcon

```php
mixed AdminThemesControllerCore::updateOptionPsStoresIcon()
```

Update PS_STORES_ICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2160)




### <a name="method-updateOptionThemeForShop"></a>updateOptionThemeForShop

```php
mixed AdminThemesControllerCore::updateOptionThemeForShop()
```

Update theme for current shop



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2225)




### <a name="method-updateThemeMetas"></a>updateThemeMetas

```php
mixed AdminThemesControllerCore::updateThemeMetas(\Theme $theme)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 503](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L503)


#### Arguments
* $theme **[Theme](class.ThemeCore.md)**



### <a name="method-uploadIco"></a>uploadIco

```php
mixed AdminThemesControllerCore::uploadIco($name, $dest)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2239](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminThemesController.php#L2239)


#### Arguments
* $name **mixed**
* $dest **mixed**


