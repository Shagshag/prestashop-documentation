Class AdminThemesControllerCore
=====================





* Class name: AdminThemesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminThemesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L27)


Contents
--------


### Properties

* [$check_features](#property-$check_features)
* [$check_features_version](#property-$check_features_version)
* [$className](#property-$className)
* [$table](#property-$table)
* [$toolbar_scroll](#property-$toolbar_scroll)

### Methods

* [__construct](#method-__construct)
* [_checkConfigForFeatures](#method-_checkConfigForFeatures)
* [_isThemeCompatible](#method-_isThemeCompatible)
* [ajaxProcessGetAddonsThemes](#method-ajaxProcessGetAddonsThemes)
* [checkMobileNeeds](#method-checkMobileNeeds)
* [copyTheme](#method-copyTheme)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processDelete](#method-processDelete)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderOptions](#method-renderOptions)
* [updateLogo](#method-updateLogo)
* [updateOptionPsFavicon](#method-updateOptionPsFavicon)
* [updateOptionPsLogo](#method-updateOptionPsLogo)
* [updateOptionPsLogoInvoice](#method-updateOptionPsLogoInvoice)
* [updateOptionPsLogoMail](#method-updateOptionPsLogoMail)
* [updateOptionPsLogoMobile](#method-updateOptionPsLogoMobile)
* [updateOptionPsStoresIcon](#method-updateOptionPsStoresIcon)
* [updateOptionThemeForShop](#method-updateOptionThemeForShop)
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
* Source: [controllers/admin/AdminThemesController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L47).


### <a name="property-$check_features_version"></a>$check_features_version

```php
public mixed $check_features_version = '1.4'
```

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L41).


### <a name="property-$className"></a>$className

```php
public mixed $className = 'Theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L98).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L99).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L100).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminThemesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L29)




### <a name="method-_checkConfigForFeatures"></a>_checkConfigForFeatures

```php
\error AdminThemesControllerCore::_checkConfigForFeatures($arrFeatures, mixed $configItem)
```

_checkConfigForFeatures



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 520](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L520)


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
* Source: [controllers/admin/AdminThemesController.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L470)


#### Arguments
* $theme_dir **string** - theme directory



### <a name="method-ajaxProcessGetAddonsThemes"></a>ajaxProcessGetAddonsThemes

```php
mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L452)




### <a name="method-checkMobileNeeds"></a>checkMobileNeeds

```php
mixed AdminThemesControllerCore::checkMobileNeeds()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L230)




### <a name="method-copyTheme"></a>copyTheme

```php
boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)
```

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminThemesController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L338)


#### Arguments
* $base_theme_dir **string** - relative path to base dir
* $target_theme_dir **string** - relative path to target dir



### <a name="method-init"></a>init

```php
mixed AdminThemesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L102)




### <a name="method-initContent"></a>initContent

```php
mixed AdminThemesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L417)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminThemesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L405)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminThemesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 709](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L709)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminThemesControllerCore::postProcess()
```

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L569)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminThemesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L364)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminThemesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L389)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminThemesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L249)




### <a name="method-renderList"></a>renderList

```php
mixed AdminThemesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L323)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminThemesControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 720](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L720)




### <a name="method-updateLogo"></a>updateLogo

```php
boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)
```

Generic function which allows logo upload



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 628](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L628)


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### <a name="method-updateOptionPsFavicon"></a>updateOptionPsFavicon

```php
mixed AdminThemesControllerCore::updateOptionPsFavicon()
```

Update PS_FAVICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 666](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L666)




### <a name="method-updateOptionPsLogo"></a>updateOptionPsLogo

```php
mixed AdminThemesControllerCore::updateOptionPsLogo()
```

Update PS_LOGO



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 584](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L584)




### <a name="method-updateOptionPsLogoInvoice"></a>updateOptionPsLogoInvoice

```php
mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()
```

Update PS_LOGO_INVOICE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 608](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L608)




### <a name="method-updateOptionPsLogoMail"></a>updateOptionPsLogoMail

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMail()
```

Update PS_LOGO_MAIL



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 600](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L600)




### <a name="method-updateOptionPsLogoMobile"></a>updateOptionPsLogoMobile

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMobile()
```

Update PS_LOGO_MOBILE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 592](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L592)




### <a name="method-updateOptionPsStoresIcon"></a>updateOptionPsStoresIcon

```php
mixed AdminThemesControllerCore::updateOptionPsStoresIcon()
```

Update PS_STORES_ICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 616](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L616)




### <a name="method-updateOptionThemeForShop"></a>updateOptionThemeForShop

```php
mixed AdminThemesControllerCore::updateOptionThemeForShop()
```

Update theme for current shop



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 680](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L680)




### <a name="method-uploadIco"></a>uploadIco

```php
mixed AdminThemesControllerCore::uploadIco($name, $dest)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminThemesController.php#L694)


#### Arguments
* $name **mixed**
* $dest **mixed**


