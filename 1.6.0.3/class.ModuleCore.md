Class ModuleCore
=====================





* Class name: ModuleCore
* This is an **abstract** class
* Source: [classes/module/Module.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L27)


Contents
--------

### Constants

* [CACHE_FILE_CUSTOMER_MODULES_LIST](#constant-CACHE_FILE_CUSTOMER_MODULES_LIST)
* [CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST](#constant-CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST)
* [CACHE_FILE_MODULES_LIST](#constant-CACHE_FILE_MODULES_LIST)
* [CACHE_FILE_MUST_HAVE_MODULES_LIST](#constant-CACHE_FILE_MUST_HAVE_MODULES_LIST)
* [CACHE_FILE_TAB_MODULES_LIST](#constant-CACHE_FILE_TAB_MODULES_LIST)

### Properties

* [$_INSTANCE](#property-$_INSTANCE)
* [$_confirmations](#property-$_confirmations)
* [$_errors](#property-$_errors)
* [$_generate_config_xml_mode](#property-$_generate_config_xml_mode)
* [$_lang](#property-$_lang)
* [$_path](#property-$_path)
* [$active](#property-$active)
* [$allow_push](#property-$allow_push)
* [$author](#property-$author)
* [$cache_permissions](#property-$cache_permissions)
* [$classInModule](#property-$classInModule)
* [$context](#property-$context)
* [$current_subtemplate](#property-$current_subtemplate)
* [$database_version](#property-$database_version)
* [$dependencies](#property-$dependencies)
* [$description](#property-$description)
* [$displayName](#property-$displayName)
* [$enable_device](#property-$enable_device)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$l_cache](#property-$l_cache)
* [$limited_countries](#property-$limited_countries)
* [$local_path](#property-$local_path)
* [$modules_cache](#property-$modules_cache)
* [$name](#property-$name)
* [$need_instance](#property-$need_instance)
* [$ps_versions_compliancy](#property-$ps_versions_compliancy)
* [$push_time_limit](#property-$push_time_limit)
* [$registered_version](#property-$registered_version)
* [$smarty](#property-$smarty)
* [$tab](#property-$tab)
* [$table](#property-$table)
* [$update_translations_after_install](#property-$update_translations_after_install)
* [$version](#property-$version)
* [$warning](#property-$warning)

### Methods

* [__construct](#method-__construct)
* [_clearCache](#method-_clearCache)
* [_generateConfigXml](#method-_generateConfigXml)
* [_getApplicableTemplateDir](#method-_getApplicableTemplateDir)
* [_isTemplateOverloaded](#method-_isTemplateOverloaded)
* [_isTemplateOverloadedStatic](#method-_isTemplateOverloadedStatic)
* [addOverride](#method-addOverride)
* [adminDisplayInformation](#method-adminDisplayInformation)
* [adminDisplayWarning](#method-adminDisplayWarning)
* [cleanPositions](#method-cleanPositions)
* [configXmlStringFormat](#method-configXmlStringFormat)
* [disable](#method-disable)
* [disableByName](#method-disableByName)
* [disableDevice](#method-disableDevice)
* [display](#method-display)
* [displayConfirmation](#method-displayConfirmation)
* [displayError](#method-displayError)
* [displayFlags](#method-displayFlags)
* [editExceptions](#method-editExceptions)
* [enable](#method-enable)
* [enableByName](#method-enableByName)
* [enableDevice](#method-enableDevice)
* [findTranslation](#method-findTranslation)
* [getAuthorizedModules](#method-getAuthorizedModules)
* [getCacheId](#method-getCacheId)
* [getConfirmations](#method-getConfirmations)
* [getCurrentSubTemplate](#method-getCurrentSubTemplate)
* [getErrors](#method-getErrors)
* [getExceptions](#method-getExceptions)
* [getInstanceById](#method-getInstanceById)
* [getInstanceByName](#method-getInstanceByName)
* [getLocalPath](#method-getLocalPath)
* [getModuleIdByName](#method-getModuleIdByName)
* [getModuleName](#method-getModuleName)
* [getModuleNameFromClass](#method-getModuleNameFromClass)
* [getModulesDirOnDisk](#method-getModulesDirOnDisk)
* [getModulesInstalled](#method-getModulesInstalled)
* [getModulesOnDisk](#method-getModulesOnDisk)
* [getNativeModuleList](#method-getNativeModuleList)
* [getNonNativeModuleList](#method-getNonNativeModuleList)
* [getPathUri](#method-getPathUri)
* [getPaymentModules](#method-getPaymentModules)
* [getPaypalIgnore](#method-getPaypalIgnore)
* [getPermission](#method-getPermission)
* [getPermissionStatic](#method-getPermissionStatic)
* [getPosition](#method-getPosition)
* [getTemplatePath](#method-getTemplatePath)
* [getUpgradeStatus](#method-getUpgradeStatus)
* [hookExec](#method-hookExec)
* [hookExecPayment](#method-hookExecPayment)
* [initUpgradeModule](#method-initUpgradeModule)
* [install](#method-install)
* [installOverrides](#method-installOverrides)
* [isCached](#method-isCached)
* [isEnabled](#method-isEnabled)
* [isEnabledForShopContext](#method-isEnabledForShopContext)
* [isHookableOn](#method-isHookableOn)
* [isInstalled](#method-isInstalled)
* [isRegisteredInHook](#method-isRegisteredInHook)
* [l](#method-l)
* [loadUpgradeVersionList](#method-loadUpgradeVersionList)
* [needUpgrade](#method-needUpgrade)
* [preCall](#method-preCall)
* [registerExceptions](#method-registerExceptions)
* [registerHook](#method-registerHook)
* [removeOverride](#method-removeOverride)
* [resetCurrentSubTemplate](#method-resetCurrentSubTemplate)
* [runUpgradeModule](#method-runUpgradeModule)
* [setUpgradeMessage](#method-setUpgradeMessage)
* [uninstall](#method-uninstall)
* [uninstallOverrides](#method-uninstallOverrides)
* [unregisterExceptions](#method-unregisterExceptions)
* [unregisterHook](#method-unregisterHook)
* [updateModuleTranslations](#method-updateModuleTranslations)
* [updatePosition](#method-updatePosition)
* [updateTranslationsAfterInstall](#method-updateTranslationsAfterInstall)
* [upgradeModuleVersion](#method-upgradeModuleVersion)


Constants
----------


### <a name="constant-CACHE_FILE_CUSTOMER_MODULES_LIST"></a>CACHE_FILE_CUSTOMER_MODULES_LIST

```php
const CACHE_FILE_CUSTOMER_MODULES_LIST = '/config/xml/customer_modules_list.xml'
```





* Source: [classes/module/Module.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L140).


### <a name="constant-CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST"></a>CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST

```php
const CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST = '/config/xml/default_country_modules_list.xml'
```





* Source: [classes/module/Module.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L138).


### <a name="constant-CACHE_FILE_MODULES_LIST"></a>CACHE_FILE_MODULES_LIST

```php
const CACHE_FILE_MODULES_LIST = '/config/xml/modules_list.xml'
```





* Source: [classes/module/Module.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L134).


### <a name="constant-CACHE_FILE_MUST_HAVE_MODULES_LIST"></a>CACHE_FILE_MUST_HAVE_MODULES_LIST

```php
const CACHE_FILE_MUST_HAVE_MODULES_LIST = '/config/xml/must_have_modules_list.xml'
```





* Source: [classes/module/Module.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L142).


### <a name="constant-CACHE_FILE_TAB_MODULES_LIST"></a>CACHE_FILE_TAB_MODULES_LIST

```php
const CACHE_FILE_TAB_MODULES_LIST = '/config/xml/tab_modules_list.xml'
```





* Source: [classes/module/Module.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L136).


Properties
----------


### <a name="property-$_INSTANCE"></a>$_INSTANCE

```php
protected \protected $_INSTANCE = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L107).


### <a name="property-$_confirmations"></a>$_confirmations

```php
protected \protected $_confirmations = array()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L95).


### <a name="property-$_errors"></a>$_errors

```php
protected \protected $_errors = array()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L92).


### <a name="property-$_generate_config_xml_mode"></a>$_generate_config_xml_mode

```php
protected \protected $_generate_config_xml_mode = false
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L110).


### <a name="property-$_lang"></a>$_lang

```php
protected array $_lang = array()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L81).


### <a name="property-$_path"></a>$_path

```php
protected string $_path = null
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L84).


### <a name="property-$active"></a>$active

```php
public boolean $active = false
```





* Visibility: **public**
* Source: [classes/module/Module.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L67).


### <a name="property-$allow_push"></a>$allow_push

```php
public \allow $allow_push
```





* Visibility: **public**
* Source: [classes/module/Module.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L130).


### <a name="property-$author"></a>$author

```php
public string $author
```





* Visibility: **public**
* Source: [classes/module/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L58).


### <a name="property-$cache_permissions"></a>$cache_permissions

```php
protected \protected $cache_permissions = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L116).


### <a name="property-$classInModule"></a>$classInModule

```php
public array $classInModule = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/module/Module.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L78).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L119).


### <a name="property-$current_subtemplate"></a>$current_subtemplate

```php
protected \currentSmartySubTemplate $current_subtemplate = null
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L125).


### <a name="property-$database_version"></a>$database_version

```php
public mixed $database_version
```





* Visibility: **public**
* Source: [classes/module/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L34).


### <a name="property-$dependencies"></a>$dependencies

```php
public array $dependencies = array()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L46).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/module/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L55).


### <a name="property-$displayName"></a>$displayName

```php
public string $displayName
```





* Visibility: **public**
* Source: [classes/module/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L52).


### <a name="property-$enable_device"></a>$enable_device

```php
public mixed $enable_device = 7
```





* Visibility: **public**
* Source: [classes/module/Module.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L72).


### <a name="property-$id"></a>$id

```php
public integer $id = null
```





* Visibility: **public**
* Source: [classes/module/Module.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L30).


### <a name="property-$identifier"></a>$identifier

```php
protected \protected $identifier = 'id_module'
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L101).


### <a name="property-$l_cache"></a>$l_cache

```php
protected \protected $l_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L113).


### <a name="property-$limited_countries"></a>$limited_countries

```php
public array $limited_countries = array()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L75).


### <a name="property-$local_path"></a>$local_path

```php
protected string $local_path = null
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L89).


### <a name="property-$modules_cache"></a>$modules_cache

```php
protected \protected $modules_cache
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L104).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/module/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L49).


### <a name="property-$need_instance"></a>$need_instance

```php
public integer $need_instance = 1
```





* Visibility: **public**
* Source: [classes/module/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L61).


### <a name="property-$ps_versions_compliancy"></a>$ps_versions_compliancy

```php
public array $ps_versions_compliancy = array()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L43).


### <a name="property-$push_time_limit"></a>$push_time_limit

```php
public mixed $push_time_limit = 180
```





* Visibility: **public**
* Source: [classes/module/Module.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L132).


### <a name="property-$registered_version"></a>$registered_version

```php
public string $registered_version
```





* Visibility: **public**
* Source: [classes/module/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L40).


### <a name="property-$smarty"></a>$smarty

```php
protected \Smarty_Data $smarty
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L122).


### <a name="property-$tab"></a>$tab

```php
public string $tab = null
```





* Visibility: **public**
* Source: [classes/module/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L64).


### <a name="property-$table"></a>$table

```php
protected \protected $table = 'module'
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L98).


### <a name="property-$update_translations_after_install"></a>$update_translations_after_install

```php
protected mixed $update_translations_after_install = true
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L127).


### <a name="property-$version"></a>$version

```php
public float $version
```





* Visibility: **public**
* Source: [classes/module/Module.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L33).


### <a name="property-$warning"></a>$warning

```php
public string $warning
```





* Visibility: **public**
* Source: [classes/module/Module.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L70).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleCore::__construct(string $name, \Context $context)
```

Constructor



* Visibility: **public**
* Source: [classes/module/Module.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L150)


#### Arguments
* $name **string** - Module unique name
* $context **[Context](class.ContextCore.md)**



### <a name="method-_clearCache"></a>_clearCache

```php
mixed ModuleCore::_clearCache($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1835)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-_generateConfigXml"></a>_generateConfigXml

```php
mixed ModuleCore::_generateConfigXml()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1844](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1844)




### <a name="method-_getApplicableTemplateDir"></a>_getApplicableTemplateDir

```php
mixed ModuleCore::_getApplicableTemplateDir($template)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1821](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1821)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloaded"></a>_isTemplateOverloaded

```php
mixed ModuleCore::_isTemplateOverloaded($template)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1730)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloadedStatic"></a>_isTemplateOverloadedStatic

```php
mixed ModuleCore::_isTemplateOverloadedStatic($module_name, $template)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 1715](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1715)


#### Arguments
* $module_name **mixed**
* $template **mixed**



### <a name="method-addOverride"></a>addOverride

```php
boolean ModuleCore::addOverride(string $classname)
```

Add all methods in a module override to the override class



* Visibility: **public**
* Source: [classes/module/Module.php line 2095](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L2095)


#### Arguments
* $classname **string**



### <a name="method-adminDisplayInformation"></a>adminDisplayInformation

```php
mixed ModuleCore::adminDisplayInformation(string $msg)
```

add a info message to display at the top of the admin page



* Visibility: **protected**
* Source: [classes/module/Module.php line 2040](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L2040)


#### Arguments
* $msg **string**



### <a name="method-adminDisplayWarning"></a>adminDisplayWarning

```php
mixed ModuleCore::adminDisplayWarning(string $msg)
```

add a warning message to display at the top of the admin page



* Visibility: **public**
* Source: [classes/module/Module.php line 2028](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L2028)


#### Arguments
* $msg **string**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ModuleCore::cleanPositions($id_hook, $shop_list)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1566](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1566)


#### Arguments
* $id_hook **mixed**
* $shop_list **mixed**



### <a name="method-configXmlStringFormat"></a>configXmlStringFormat

```php
mixed ModuleCore::configXmlStringFormat($string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 994](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L994)


#### Arguments
* $string **mixed**



### <a name="method-disable"></a>disable

```php
mixed ModuleCore::disable(boolean $forceAll)
```

Desactivate current module.



* Visibility: **public**
* Source: [classes/module/Module.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L671)


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
* Source: [classes/module/Module.php line 653](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L653)


#### Arguments
* $name **array|string**



### <a name="method-disableDevice"></a>disableDevice

```php
mixed ModuleCore::disableDevice($device)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L633)


#### Arguments
* $device **mixed**



### <a name="method-display"></a>display

```php
mixed ModuleCore::display($file, $template, $cacheId, $compileId)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1753](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1753)


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
* Source: [classes/module/Module.php line 1603](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1603)


#### Arguments
* $string **mixed**



### <a name="method-displayError"></a>displayError

```php
mixed ModuleCore::displayError($error)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1591](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1591)


#### Arguments
* $error **mixed**



### <a name="method-displayFlags"></a>displayFlags

```php
mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* Source: [classes/module/Module.php line 688](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L688)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-editExceptions"></a>editExceptions

```php
boolean ModuleCore::editExceptions($id_hook, array $excepts)
```

Edit exceptions for module->Hook



* Visibility: **public**
* Source: [classes/module/Module.php line 886](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L886)


#### Arguments
* $id_hook **mixed**
* $excepts **array** - List of shopID and file name



### <a name="method-enable"></a>enable

```php
mixed ModuleCore::enable(boolean $forceAll)
```

Activate current module.



* Visibility: **public**
* Source: [classes/module/Module.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L596)


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
* Source: [classes/module/Module.php line 578](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L578)


#### Arguments
* $name **array|string**



### <a name="method-enableDevice"></a>enableDevice

```php
mixed ModuleCore::enableDevice($device)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L621)


#### Arguments
* $device **mixed**



### <a name="method-findTranslation"></a>findTranslation

```php
mixed ModuleCore::findTranslation($name, $string, $source)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1486)


#### Arguments
* $name **mixed**
* $string **mixed**
* $source **mixed**



### <a name="method-getAuthorizedModules"></a>getAuthorizedModules

```php
mixed ModuleCore::getAuthorizedModules($group_id)
```

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1931](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1931)


#### Arguments
* $group_id **mixed**



### <a name="method-getCacheId"></a>getCacheId

```php
mixed ModuleCore::getCacheId($name)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1735](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1735)


#### Arguments
* $name **mixed**



### <a name="method-getConfirmations"></a>getConfirmations

```php
array ModuleCore::getConfirmations()
```

Get module messages confirmation



* Visibility: **public**
* Source: [classes/module/Module.php line 1972](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1972)




### <a name="method-getCurrentSubTemplate"></a>getCurrentSubTemplate

```php
mixed ModuleCore::getCurrentSubTemplate($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1779](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1779)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-getErrors"></a>getErrors

```php
array ModuleCore::getErrors()
```

Get module errors



* Visibility: **public**
* Source: [classes/module/Module.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1961)




### <a name="method-getExceptions"></a>getExceptions

```php
mixed ModuleCore::getExceptions($id_hook, $dispatch)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1620)


#### Arguments
* $id_hook **mixed**
* $dispatch **mixed**



### <a name="method-getInstanceById"></a>getInstanceById

```php
\Module ModuleCore::getInstanceById(integer $id_module)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L975)


#### Arguments
* $id_module **integer** - Module ID



### <a name="method-getInstanceByName"></a>getInstanceByName

```php
\Module ModuleCore::getInstanceByName(string $module_name)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L946)


#### Arguments
* $module_name **string** - Module name



### <a name="method-getLocalPath"></a>getLocalPath

```php
string ModuleCore::getLocalPath()
```

Get local path for module



* Visibility: **public**
* Source: [classes/module/Module.php line 1983](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1983)




### <a name="method-getModuleIdByName"></a>getModuleIdByName

```php
integer ModuleCore::getModuleIdByName($name)
```

Get id module by name



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1944](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1944)


#### Arguments
* $name **mixed**



### <a name="method-getModuleName"></a>getModuleName

```php
mixed ModuleCore::getModuleName($module)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1000](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1000)


#### Arguments
* $module **mixed**



### <a name="method-getModuleNameFromClass"></a>getModuleNameFromClass

```php
boolean|string ModuleCore::getModuleNameFromClass(mixed $currentClass)
```

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L908)


#### Arguments
* $currentClass **mixed** - the



### <a name="method-getModulesDirOnDisk"></a>getModulesDirOnDisk

```php
array ModuleCore::getModulesDirOnDisk()
```

Return modules directory list



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1324](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1324)




### <a name="method-getModulesInstalled"></a>getModulesInstalled

```php
array ModuleCore::getModulesInstalled(integer $position)
```

Return installed modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1393](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1393)


#### Arguments
* $position **integer** - Take only positionnables modules



### <a name="method-getModulesOnDisk"></a>getModulesOnDisk

```php
array ModuleCore::getModulesOnDisk(boolean $useConfig, $loggedOnAddons, $id_employee)
```

Return available modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1042](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1042)


#### Arguments
* $useConfig **boolean** - in order to use config.xml file in module dir
* $loggedOnAddons **mixed**
* $id_employee **mixed**



### <a name="method-getNativeModuleList"></a>getNativeModuleList

```php
mixed ModuleCore::getNativeModuleList()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1367](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1367)




### <a name="method-getNonNativeModuleList"></a>getNonNativeModuleList

```php
array ModuleCore::getNonNativeModuleList()
```

Return non native module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1349)




### <a name="method-getPathUri"></a>getPathUri

```php
string ModuleCore::getPathUri()
```

Get uri path for module



* Visibility: **public**
* Source: [classes/module/Module.php line 1994](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1994)




### <a name="method-getPaymentModules"></a>getPaymentModules

```php
array ModuleCore::getPaymentModules()
```

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1442](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1442)




### <a name="method-getPaypalIgnore"></a>getPaypalIgnore

```php
mixed ModuleCore::getPaypalIgnore()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1431](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1431)




### <a name="method-getPermission"></a>getPermission

```php
boolean ModuleCore::getPermission(array $variable, object $employee)
```

Check employee permission for module



* Visibility: **public**
* Source: [classes/module/Module.php line 1888](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1888)


#### Arguments
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPermissionStatic"></a>getPermissionStatic

```php
boolean ModuleCore::getPermissionStatic(integer $id_module, array $variable, object $employee)
```

Check employee permission for module (static method)



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1900](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1900)


#### Arguments
* $id_module **integer**
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPosition"></a>getPosition

```php
mixed ModuleCore::getPosition($id_hook)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 2005](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L2005)


#### Arguments
* $id_hook **mixed**



### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string ModuleCore::getTemplatePath(string $template)
```

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* Source: [classes/module/Module.php line 1805](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1805)


#### Arguments
* $template **string**



### <a name="method-getUpgradeStatus"></a>getUpgradeStatus

```php
boolean ModuleCore::getUpgradeStatus($module_name)
```

Return the status of the upgraded module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L518)


#### Arguments
* $module_name **mixed**



### <a name="method-hookExec"></a>hookExec

```php
string ModuleCore::hookExec(string $hook_name, array $hookArgs, $id_module)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1411](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1411)


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
* Source: [classes/module/Module.php line 1417](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1417)




### <a name="method-initUpgradeModule"></a>initUpgradeModule

```php
boolean ModuleCore::initUpgradeModule($module)
```

Init the upgrade module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L344)


#### Arguments
* $module **mixed**



### <a name="method-install"></a>install

```php
mixed ModuleCore::install()
```

Insert module into datable



* Visibility: **public**
* Source: [classes/module/Module.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L204)




### <a name="method-installOverrides"></a>installOverrides

```php
boolean ModuleCore::installOverrides()
```

Install overrides files for the module



* Visibility: **public**
* Source: [classes/module/Module.php line 2052](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L2052)




### <a name="method-isCached"></a>isCached

```php
mixed ModuleCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1826](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1826)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isEnabled"></a>isEnabled

```php
mixed ModuleCore::isEnabled($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1687](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1687)


#### Arguments
* $module_name **mixed**



### <a name="method-isEnabledForShopContext"></a>isEnabledForShopContext

```php
mixed ModuleCore::isEnabledForShopContext()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1675](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1675)




### <a name="method-isHookableOn"></a>isHookableOn

```php
boolean ModuleCore::isHookableOn(string $hook_name)
```

Check if the module is transplantable on the hook in parameter



* Visibility: **public**
* Source: [classes/module/Module.php line 1876](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1876)


#### Arguments
* $hook_name **string**



### <a name="method-isInstalled"></a>isInstalled

```php
mixed ModuleCore::isInstalled($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1665](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1665)


#### Arguments
* $module_name **mixed**



### <a name="method-isRegisteredInHook"></a>isRegisteredInHook

```php
mixed ModuleCore::isRegisteredInHook($hook)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1700](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1700)


#### Arguments
* $hook **mixed**



### <a name="method-l"></a>l

```php
string ModuleCore::l(string $string, boolean|string $specific)
```

Get translation for a given module text

Note: $specific parameter is mandatory for library files.
Otherwise, translation key will not match for Module library
when module is loaded with eval() Module::getModulesOnDisk()

* Visibility: **public**
* Source: [classes/module/Module.php line 1502](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1502)


#### Arguments
* $string **string** - String to translate
* $specific **boolean|string** - filename to use in translation key



### <a name="method-loadUpgradeVersionList"></a>loadUpgradeVersionList

```php
boolean ModuleCore::loadUpgradeVersionList($module_name, $module_version, $registered_version)
```

Load the available list of upgrade of a specified module
with an associated version



* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L468)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**
* $registered_version **mixed**



### <a name="method-needUpgrade"></a>needUpgrade

```php
boolean ModuleCore::needUpgrade($module)
```

Check if a module need to be upgraded.

This method modify the module_cache adding an upgrade list file

* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L444)


#### Arguments
* $module **mixed**



### <a name="method-preCall"></a>preCall

```php
mixed ModuleCore::preCall($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1423](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1423)


#### Arguments
* $module_name **mixed**



### <a name="method-registerExceptions"></a>registerExceptions

```php
boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shop_list)
```

Add exceptions for module->Hook



* Visibility: **public**
* Source: [classes/module/Module.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L852)


#### Arguments
* $id_hook **integer** - Hook id
* $excepts **array** - List of file name
* $shop_list **array** - List of shop



### <a name="method-registerHook"></a>registerHook

```php
boolean ModuleCore::registerHook(string $hook_name, array $shop_list)
```

Connect module to a hook



* Visibility: **public**
* Source: [classes/module/Module.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L718)


#### Arguments
* $hook_name **string** - Hook name
* $shop_list **array** - List of shop linked to the hook (if null, link hook to all shops)



### <a name="method-removeOverride"></a>removeOverride

```php
boolean ModuleCore::removeOverride(string $classname)
```

Remove all methods in a module override from the override class



* Visibility: **public**
* Source: [classes/module/Module.php line 2155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L2155)


#### Arguments
* $classname **string**



### <a name="method-resetCurrentSubTemplate"></a>resetCurrentSubTemplate

```php
mixed ModuleCore::resetCurrentSubTemplate($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1793](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1793)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-runUpgradeModule"></a>runUpgradeModule

```php
array ModuleCore::runUpgradeModule()
```

Run the upgrade for a given module name and version



* Visibility: **public**
* Source: [classes/module/Module.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L374)




### <a name="method-setUpgradeMessage"></a>setUpgradeMessage

```php
mixed ModuleCore::setUpgradeMessage($upgrade_detail)
```

Set errors, warning or success message of a module upgrade



* Visibility: **protected**
* Source: [classes/module/Module.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L308)


#### Arguments
* $upgrade_detail **mixed**



### <a name="method-uninstall"></a>uninstall

```php
boolean ModuleCore::uninstall()
```

Delete module from datable



* Visibility: **public**
* Source: [classes/module/Module.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L529)




### <a name="method-uninstallOverrides"></a>uninstallOverrides

```php
boolean ModuleCore::uninstallOverrides()
```

Uninstall overrides files for the module



* Visibility: **public**
* Source: [classes/module/Module.php line 2073](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L2073)




### <a name="method-unregisterExceptions"></a>unregisterExceptions

```php
boolean ModuleCore::unregisterExceptions($hook_id, array $shop_list)
```

Unregister exceptions linked to module



* Visibility: **public**
* Source: [classes/module/Module.php line 836](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L836)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-unregisterHook"></a>unregisterHook

```php
boolean ModuleCore::unregisterHook($hook_id, array $shop_list)
```

Unregister module from hook



* Visibility: **public**
* Source: [classes/module/Module.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L799)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-updateModuleTranslations"></a>updateModuleTranslations

```php
mixed ModuleCore::updateModuleTranslations()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L298)




### <a name="method-updatePosition"></a>updatePosition

```php
mixed ModuleCore::updatePosition($id_hook, $way, $position)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1517](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L1517)


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**



### <a name="method-updateTranslationsAfterInstall"></a>updateTranslationsAfterInstall

```php
mixed ModuleCore::updateTranslationsAfterInstall($update)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L293)


#### Arguments
* $update **mixed**



### <a name="method-upgradeModuleVersion"></a>upgradeModuleVersion

```php
boolean ModuleCore::upgradeModuleVersion($name, $version)
```

Upgrade the registered version to a new one



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/module/Module.php#L427)


#### Arguments
* $name **mixed**
* $version **mixed**


