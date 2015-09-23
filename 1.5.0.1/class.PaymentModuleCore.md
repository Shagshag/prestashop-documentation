Class PaymentModuleCore
=====================





* Class name: PaymentModuleCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/PaymentModule.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L28)


Contents
--------


### Properties

* [$currencies](#property-$currencies)
* [$currencies_mode](#property-$currencies_mode)
* [$currentOrder](#property-$currentOrder)
* [$_INSTANCE](#property-$_INSTANCE)
* [$_db](#property-$_db)
* [$_errors](#property-$_errors)
* [$_generateConfigXmlMode](#property-$_generateConfigXmlMode)
* [$_lang](#property-$_lang)
* [$_path](#property-$_path)
* [$active](#property-$active)
* [$author](#property-$author)
* [$beforeUninstall](#property-$beforeUninstall)
* [$cache_permissions](#property-$cache_permissions)
* [$classInModule](#property-$classInModule)
* [$context](#property-$context)
* [$description](#property-$description)
* [$displayName](#property-$displayName)
* [$exceptionsCache](#property-$exceptionsCache)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$l_cache](#property-$l_cache)
* [$limited_countries](#property-$limited_countries)
* [$modulesCache](#property-$modulesCache)
* [$name](#property-$name)
* [$need_instance](#property-$need_instance)
* [$tab](#property-$tab)
* [$table](#property-$table)
* [$version](#property-$version)
* [$warning](#property-$warning)

### Methods

* [__construct](#method-__construct)
* [_clearCache](#method-_clearCache)
* [_generateConfigXml](#method-_generateConfigXml)
* [_getApplicableTemplateDir](#method-_getApplicableTemplateDir)
* [_getFormatedAddress](#method-_getFormatedAddress)
* [_getTxtFormatedAddress](#method-_getTxtFormatedAddress)
* [_isTemplateOverloaded](#method-_isTemplateOverloaded)
* [_isTemplateOverloadedStatic](#method-_isTemplateOverloadedStatic)
* [addCurrencyPermissions](#method-addCurrencyPermissions)
* [cleanPositions](#method-cleanPositions)
* [configXmlStringFormat](#method-configXmlStringFormat)
* [disable](#method-disable)
* [disableByName](#method-disableByName)
* [display](#method-display)
* [displayConfirmation](#method-displayConfirmation)
* [displayError](#method-displayError)
* [displayFlags](#method-displayFlags)
* [editExceptions](#method-editExceptions)
* [enable](#method-enable)
* [enableByName](#method-enableByName)
* [findTranslation](#method-findTranslation)
* [getAuthorizedModules](#method-getAuthorizedModules)
* [getCurrency](#method-getCurrency)
* [getExceptions](#method-getExceptions)
* [getInstalledPaymentModules](#method-getInstalledPaymentModules)
* [getInstanceById](#method-getInstanceById)
* [getInstanceByName](#method-getInstanceByName)
* [getModuleIdByName](#method-getModuleIdByName)
* [getModuleNameFromClass](#method-getModuleNameFromClass)
* [getModulesDirOnDisk](#method-getModulesDirOnDisk)
* [getModulesInstalled](#method-getModulesInstalled)
* [getModulesOnDisk](#method-getModulesOnDisk)
* [getNonNativeModuleList](#method-getNonNativeModuleList)
* [getPaymentModules](#method-getPaymentModules)
* [getPermission](#method-getPermission)
* [getPermissionStatic](#method-getPermissionStatic)
* [getTemplatePath](#method-getTemplatePath)
* [hookExec](#method-hookExec)
* [hookExecPayment](#method-hookExecPayment)
* [install](#method-install)
* [isCached](#method-isCached)
* [isHookableOn](#method-isHookableOn)
* [isInstalled](#method-isInstalled)
* [isRegisteredInHook](#method-isRegisteredInHook)
* [l](#method-l)
* [preCall](#method-preCall)
* [registerExceptions](#method-registerExceptions)
* [registerHook](#method-registerHook)
* [sqlShopRestriction](#method-sqlShopRestriction)
* [templateAssign](#method-templateAssign)
* [uninstall](#method-uninstall)
* [unregisterExceptions](#method-unregisterExceptions)
* [unregisterHook](#method-unregisterHook)
* [updatePosition](#method-updatePosition)
* [validateOrder](#method-validateOrder)




Properties
----------


### <a name="property-$currencies"></a>$currencies

```php
public mixed $currencies = true
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L32).


### <a name="property-$currencies_mode"></a>$currencies_mode

```php
public mixed $currencies_mode = 'checkbox'
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L33).


### <a name="property-$currentOrder"></a>$currentOrder

```php
public integer $currentOrder
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L31).


### <a name="property-$_INSTANCE"></a>$_INSTANCE

```php
protected mixed $_INSTANCE = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L82).


### <a name="property-$_db"></a>$_db

```php
public mixed $_db
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L75).


### <a name="property-$_errors"></a>$_errors

```php
protected mixed $_errors = false
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L69).


### <a name="property-$_generateConfigXmlMode"></a>$_generateConfigXmlMode

```php
protected mixed $_generateConfigXmlMode = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L84).


### <a name="property-$_lang"></a>$_lang

```php
protected array $_lang = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L58).


### <a name="property-$_path"></a>$_path

```php
protected string $_path = NULL
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L61).


### <a name="property-$active"></a>$active

```php
public boolean $active = false
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L55).


### <a name="property-$author"></a>$author

```php
public string $author
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L46).


### <a name="property-$beforeUninstall"></a>$beforeUninstall

```php
public string $beforeUninstall = NULL
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L67).


### <a name="property-$cache_permissions"></a>$cache_permissions

```php
protected mixed $cache_permissions = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L88).


### <a name="property-$classInModule"></a>$classInModule

```php
public array $classInModule = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L93).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L96).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L43).


### <a name="property-$displayName"></a>$displayName

```php
public string $displayName
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L40).


### <a name="property-$exceptionsCache"></a>$exceptionsCache

```php
protected mixed $exceptionsCache = NULL
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1115).


### <a name="property-$id"></a>$id

```php
public integer $id = NULL
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L31).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L73).


### <a name="property-$l_cache"></a>$l_cache

```php
protected mixed $l_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L86).


### <a name="property-$limited_countries"></a>$limited_countries

```php
public array $limited_countries = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L78).


### <a name="property-$modulesCache"></a>$modulesCache

```php
protected mixed $modulesCache
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L80).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L37).


### <a name="property-$need_instance"></a>$need_instance

```php
public integer $need_instance = 1
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L49).


### <a name="property-$tab"></a>$tab

```php
public string $tab = NULL
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L52).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L71).


### <a name="property-$version"></a>$version

```php
public float $version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L34).


### <a name="property-$warning"></a>$warning

```php
public string $warning
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L64).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleCore::__construct(string $name, \Context $context)
```

Constructor



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L104)


#### Arguments
* $name **string** - Module unique name
* $context **[Context](class.ContextCore.md)**



### <a name="method-_clearCache"></a>_clearCache

```php
mixed ModuleCore::_clearCache($template, $cacheId, $compileId)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1255](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1255)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-_generateConfigXml"></a>_generateConfigXml

```php
mixed ModuleCore::_generateConfigXml()
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1260](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1260)




### <a name="method-_getApplicableTemplateDir"></a>_getApplicableTemplateDir

```php
mixed ModuleCore::_getApplicableTemplateDir($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1243](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1243)


#### Arguments
* $template **mixed**



### <a name="method-_getFormatedAddress"></a>_getFormatedAddress

```php
String PaymentModuleCore::_getFormatedAddress(\Address $the_address, $line_sep, $fields_style)
```





* Visibility: **private**
* Source: [classes/PaymentModule.php line 498](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L498)


#### Arguments
* $the_address **[Address](class.AddressCore.md)**
* $line_sep **mixed**
* $fields_style **mixed**



### <a name="method-_getTxtFormatedAddress"></a>_getTxtFormatedAddress

```php
String PaymentModuleCore::_getTxtFormatedAddress($the_address)
```





* Visibility: **private**
* Source: [classes/PaymentModule.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L473)


#### Arguments
* $the_address **mixed**



### <a name="method-_isTemplateOverloaded"></a>_isTemplateOverloaded

```php
mixed ModuleCore::_isTemplateOverloaded($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1190](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1190)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloadedStatic"></a>_isTemplateOverloadedStatic

```php
mixed ModuleCore::_isTemplateOverloadedStatic($moduleName, $template)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1181)


#### Arguments
* $moduleName **mixed**
* $template **mixed**



### <a name="method-addCurrencyPermissions"></a>addCurrencyPermissions

```php
boolean PaymentModuleCore::addCurrencyPermissions(integer $id_currency, array $id_module_list)
```

Allows specified payment modules to be used by a specific currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 543](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L543)


#### Arguments
* $id_currency **integer**
* $id_module_list **array**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ModuleCore::cleanPositions($id_hook, $shopList)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1064](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1064)


#### Arguments
* $id_hook **mixed**
* $shopList **mixed**



### <a name="method-configXmlStringFormat"></a>configXmlStringFormat

```php
mixed ModuleCore::configXmlStringFormat($string)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L580)


#### Arguments
* $string **mixed**



### <a name="method-disable"></a>disable

```php
mixed ModuleCore::disable(boolean $forceAll)
```

Desactivate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L291)


#### Arguments
* $forceAll **boolean** - If true, disable module for all shop



### <a name="method-disableByName"></a>disableByName

```php
true ModuleCore::disableByName(array|string $name)
```

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L275)


#### Arguments
* $name **array|string**



### <a name="method-display"></a>display

```php
mixed ModuleCore::display($file, $template, $cacheId, $compileId)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1195](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1195)


#### Arguments
* $file **mixed**
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-displayConfirmation"></a>displayConfirmation

```php
mixed ModuleCore::displayConfirmation($string)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1100)


#### Arguments
* $string **mixed**



### <a name="method-displayError"></a>displayError

```php
mixed ModuleCore::displayError($error)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1090](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1090)


#### Arguments
* $error **mixed**



### <a name="method-displayFlags"></a>displayFlags

```php
mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L309)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-editExceptions"></a>editExceptions

```php
mixed ModuleCore::editExceptions($hookID, $excepts)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 489](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L489)


#### Arguments
* $hookID **mixed**
* $excepts **mixed**



### <a name="method-enable"></a>enable

```php
mixed ModuleCore::enable(boolean $forceAll)
```

Activate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L245)


#### Arguments
* $forceAll **boolean** - If true, enable module for all shop



### <a name="method-enableByName"></a>enableByName

```php
true ModuleCore::enableByName(array|string $name)
```

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L231)


#### Arguments
* $name **array|string**



### <a name="method-findTranslation"></a>findTranslation

```php
string ModuleCore::findTranslation(string $name, string $string, string $source)
```

find translation from $_MODULES and put it in self::$l_cache if not already exist
and return it.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L946)


#### Arguments
* $name **string** - name of the module
* $string **string** - term to find
* $source **string** - additional param for building translation key



### <a name="method-getAuthorizedModules"></a>getAuthorizedModules

```php
mixed ModuleCore::getAuthorizedModules($group_id)
```

get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1314](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1314)


#### Arguments
* $group_id **mixed**



### <a name="method-getCurrency"></a>getCurrency

```php
\Currency PaymentModuleCore::getCurrency($current_id_currency)
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L507)


#### Arguments
* $current_id_currency **mixed**



### <a name="method-getExceptions"></a>getExceptions

```php
mixed ModuleCore::getExceptions($hookID, $dispatch)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1116)


#### Arguments
* $hookID **mixed**
* $dispatch **mixed**



### <a name="method-getInstalledPaymentModules"></a>getInstalledPaymentModules

```php
array PaymentModuleCore::getInstalledPaymentModules()
```

List all installed and active payment modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L575)




### <a name="method-getInstanceById"></a>getInstanceById

```php
\Module ModuleCore::getInstanceById($moduleID)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L561)


#### Arguments
* $moduleID **mixed**



### <a name="method-getInstanceByName"></a>getInstanceByName

```php
\Module ModuleCore::getInstanceByName(string $moduleName)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L542)


#### Arguments
* $moduleName **string** - Module name



### <a name="method-getModuleIdByName"></a>getModuleIdByName

```php
integer ModuleCore::getModuleIdByName($name)
```

get id module by name



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1329](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1329)


#### Arguments
* $name **mixed**



### <a name="method-getModuleNameFromClass"></a>getModuleNameFromClass

```php
boolean|string ModuleCore::getModuleNameFromClass(mixed $currentClass)
```

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 511](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L511)


#### Arguments
* $currentClass **mixed** - the



### <a name="method-getModulesDirOnDisk"></a>getModulesDirOnDisk

```php
mixed ModuleCore::getModulesDirOnDisk()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L802)




### <a name="method-getModulesInstalled"></a>getModulesInstalled

```php
array ModuleCore::getModulesInstalled(integer $position)
```

Return installed modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L851)


#### Arguments
* $position **integer** - Take only positionnables modules



### <a name="method-getModulesOnDisk"></a>getModulesOnDisk

```php
array ModuleCore::getModulesOnDisk(boolean $useConfig, $loggedOnAddons)
```

Return available modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 591](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L591)


#### Arguments
* $useConfig **boolean** - in order to use config.xml file in module dir
* $loggedOnAddons **mixed**



### <a name="method-getNonNativeModuleList"></a>getNonNativeModuleList

```php
array ModuleCore::getNonNativeModuleList()
```

Return non native module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 824](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L824)




### <a name="method-getPaymentModules"></a>getPaymentModules

```php
array ModuleCore::getPaymentModules()
```

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 896](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L896)




### <a name="method-getPermission"></a>getPermission

```php
mixed ModuleCore::getPermission($variable, $employee)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1286)


#### Arguments
* $variable **mixed**
* $employee **mixed**



### <a name="method-getPermissionStatic"></a>getPermissionStatic

```php
mixed ModuleCore::getPermissionStatic($id_module, $variable, $employee)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1291](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1291)


#### Arguments
* $id_module **mixed**
* $variable **mixed**
* $employee **mixed**



### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string ModuleCore::getTemplatePath(string $template)
```

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1217](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1217)


#### Arguments
* $template **string**



### <a name="method-hookExec"></a>hookExec

```php
string ModuleCore::hookExec(string $hook_name, array $hookArgs, $id_module)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L870)


#### Arguments
* $hook_name **string** - Hook Name
* $hookArgs **array** - Parameters for the functions
* $id_module **mixed**



### <a name="method-hookExecPayment"></a>hookExecPayment

```php
mixed ModuleCore::hookExecPayment()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L876)




### <a name="method-install"></a>install

```php
mixed PaymentModuleCore::install()
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L35)




### <a name="method-isCached"></a>isCached

```php
mixed ModuleCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1248](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1248)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isHookableOn"></a>isHookableOn

```php
boolean ModuleCore::isHookableOn(string $hook_name)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1281](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1281)


#### Arguments
* $hook_name **string**



### <a name="method-isInstalled"></a>isInstalled

```php
mixed ModuleCore::isInstalled($moduleName)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1159)


#### Arguments
* $moduleName **mixed**



### <a name="method-isRegisteredInHook"></a>isRegisteredInHook

```php
mixed ModuleCore::isRegisteredInHook($hook)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1165](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1165)


#### Arguments
* $hook **mixed**



### <a name="method-l"></a>l

```php
string ModuleCore::l(string $string, boolean|string $specific, $id_lang)
```

Get translation for a given module text

Note: $specific parameter is mandatory for library files.
Otherwise, translation key will not match for Module library
when module is loaded with eval() Module::getModulesOnDisk()

* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L987)


#### Arguments
* $string **string** - String to translate
* $specific **boolean|string** - filename to use in translation key
* $id_lang **mixed**



### <a name="method-preCall"></a>preCall

```php
mixed PaymentModuleCore::preCall($moduleName)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 592](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L592)


#### Arguments
* $moduleName **mixed**



### <a name="method-registerExceptions"></a>registerExceptions

```php
boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shopList)
```

Add exceptions for module->Hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L464)


#### Arguments
* $id_hook **integer** - Hook id
* $excepts **array** - List of file name
* $shopList **array** - List of shop



### <a name="method-registerHook"></a>registerHook

```php
boolean ModuleCore::registerHook(string $hook_name, array $shopList)
```

Connect module to a hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L338)


#### Arguments
* $hook_name **string** - Hook name
* $shopList **array** - List of shop linked to the hook (if null, link hook to all shops)



### <a name="method-sqlShopRestriction"></a>sqlShopRestriction

```php
mixed ModuleCore::sqlShopRestriction($share, $alias)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L142)


#### Arguments
* $share **mixed**
* $alias **mixed**



### <a name="method-templateAssign"></a>templateAssign

```php
mixed ModuleCore::templateAssign(string $key, mixed $value)
```

Assign a smarty vars (same syntax as smarty->assign) but prefix all keys with module name



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1232](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1232)


#### Arguments
* $key **string** - Variable key (can be an array)
* $value **mixed** - Variable value



### <a name="method-uninstall"></a>uninstall

```php
mixed PaymentModuleCore::uninstall()
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L70)




### <a name="method-unregisterExceptions"></a>unregisterExceptions

```php
boolean ModuleCore::unregisterExceptions($hook_id, array $shopList)
```

Unregister exceptions linked to module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L446)


#### Arguments
* $hook_id **mixed**
* $shopList **array** - List of shop



### <a name="method-unregisterHook"></a>unregisterHook

```php
boolean ModuleCore::unregisterHook($hook_id, array $shopList)
```

Unregister module from hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L412)


#### Arguments
* $hook_id **mixed**
* $shopList **array** - List of shop



### <a name="method-updatePosition"></a>updatePosition

```php
mixed ModuleCore::updatePosition($id_hook, $way, $position)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1014](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Module.php#L1014)


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**



### <a name="method-validateOrder"></a>validateOrder

```php
mixed PaymentModuleCore::validateOrder(integer $id_cart, integer $id_order_state, float $amountPaid, string $paymentMethod, string $message, $extraVars, $currency_special, $dont_touch_amount, $secure_key, \Shop $shop)
```

Validate an order in database
Function called from a payment module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PaymentModule.php#L89)


#### Arguments
* $id_cart **integer** - Value
* $id_order_state **integer** - Value
* $amountPaid **float** - Amount really paid by customer (in the default currency)
* $paymentMethod **string** - Payment method (eg. &#039;Credit card&#039;)
* $message **string** - Message to attach to order
* $extraVars **mixed**
* $currency_special **mixed**
* $dont_touch_amount **mixed**
* $secure_key **mixed**
* $shop **[Shop](class.ShopCore.md)**


