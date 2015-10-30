Class ModuleGridCore
=====================





* Class name: ModuleGridCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ModuleGrid.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L27)


Contents
--------


### Properties

* [$_direction](#property-$_direction)
* [$_employee](#property-$_employee)
* [$_limit](#property-$_limit)
* [$_render](#property-$_render)
* [$_sort](#property-$_sort)
* [$_start](#property-$_start)
* [$_title](#property-$_title)
* [$_totalCount](#property-$_totalCount)
* [$_values](#property-$_values)
* [$_INSTANCE](#property-$_INSTANCE)
* [$_batch_mode](#property-$_batch_mode)
* [$_confirmations](#property-$_confirmations)
* [$_defered_clearCache](#property-$_defered_clearCache)
* [$_defered_func_call](#property-$_defered_func_call)
* [$_errors](#property-$_errors)
* [$_generate_config_xml_mode](#property-$_generate_config_xml_mode)
* [$_lang](#property-$_lang)
* [$_log_modules_perfs](#property-$_log_modules_perfs)
* [$_log_modules_perfs_session](#property-$_log_modules_perfs_session)
* [$_path](#property-$_path)
* [$active](#property-$active)
* [$additional_description](#property-$additional_description)
* [$allow_push](#property-$allow_push)
* [$author](#property-$author)
* [$author_uri](#property-$author_uri)
* [$avg_rate](#property-$avg_rate)
* [$badges](#property-$badges)
* [$cache_permissions](#property-$cache_permissions)
* [$classInModule](#property-$classInModule)
* [$compatibility](#property-$compatibility)
* [$context](#property-$context)
* [$controllers](#property-$controllers)
* [$current_subtemplate](#property-$current_subtemplate)
* [$database_version](#property-$database_version)
* [$dependencies](#property-$dependencies)
* [$description](#property-$description)
* [$description_full](#property-$description_full)
* [$displayName](#property-$displayName)
* [$enable_device](#property-$enable_device)
* [$hosted_modules_blacklist](#property-$hosted_modules_blacklist)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$l_cache](#property-$l_cache)
* [$limited_countries](#property-$limited_countries)
* [$local_path](#property-$local_path)
* [$module_key](#property-$module_key)
* [$modules_cache](#property-$modules_cache)
* [$name](#property-$name)
* [$nb_rates](#property-$nb_rates)
* [$need_instance](#property-$need_instance)
* [$ps_versions_compliancy](#property-$ps_versions_compliancy)
* [$push_time_limit](#property-$push_time_limit)
* [$registered_version](#property-$registered_version)
* [$smarty](#property-$smarty)
* [$tab](#property-$tab)
* [$table](#property-$table)
* [$trusted](#property-$trusted)
* [$update_translations_after_install](#property-$update_translations_after_install)
* [$version](#property-$version)
* [$warning](#property-$warning)

### Methods

* [__construct](#method-__construct)
* [_clearCache](#method-_clearCache)
* [_deferedClearCache](#method-_deferedClearCache)
* [_displayCsv](#method-_displayCsv)
* [_generateConfigXml](#method-_generateConfigXml)
* [_getApplicableTemplateDir](#method-_getApplicableTemplateDir)
* [_isTemplateOverloaded](#method-_isTemplateOverloaded)
* [_isTemplateOverloadedStatic](#method-_isTemplateOverloadedStatic)
* [addOverride](#method-addOverride)
* [adminDisplayInformation](#method-adminDisplayInformation)
* [adminDisplayWarning](#method-adminDisplayWarning)
* [checkCompliancy](#method-checkCompliancy)
* [checkModuleFromAddonsApi](#method-checkModuleFromAddonsApi)
* [cleanPositions](#method-cleanPositions)
* [configXmlStringFormat](#method-configXmlStringFormat)
* [coreLoadModule](#method-coreLoadModule)
* [create](#method-create)
* [csvExport](#method-csvExport)
* [disable](#method-disable)
* [disableByName](#method-disableByName)
* [disableDevice](#method-disableDevice)
* [display](#method-display)
* [displayConfirmation](#method-displayConfirmation)
* [displayError](#method-displayError)
* [displayFlags](#method-displayFlags)
* [displayWarning](#method-displayWarning)
* [editExceptions](#method-editExceptions)
* [enable](#method-enable)
* [enableByName](#method-enableByName)
* [enableDevice](#method-enableDevice)
* [engine](#method-engine)
* [findTranslation](#method-findTranslation)
* [generateTrustedXml](#method-generateTrustedXml)
* [getAuthorizedModules](#method-getAuthorizedModules)
* [getBatchMode](#method-getBatchMode)
* [getCacheId](#method-getCacheId)
* [getConfirmations](#method-getConfirmations)
* [getCurrentSubTemplate](#method-getCurrentSubTemplate)
* [getData](#method-getData)
* [getDate](#method-getDate)
* [getErrors](#method-getErrors)
* [getExceptions](#method-getExceptions)
* [getExceptionsStatic](#method-getExceptionsStatic)
* [getInstanceById](#method-getInstanceById)
* [getInstanceByName](#method-getInstanceByName)
* [getLang](#method-getLang)
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
* [getPossibleHooksList](#method-getPossibleHooksList)
* [getTemplatePath](#method-getTemplatePath)
* [getUpgradeStatus](#method-getUpgradeStatus)
* [hookExec](#method-hookExec)
* [hookExecPayment](#method-hookExecPayment)
* [initUpgradeModule](#method-initUpgradeModule)
* [install](#method-install)
* [installControllers](#method-installControllers)
* [installOverrides](#method-installOverrides)
* [isCached](#method-isCached)
* [isEnabled](#method-isEnabled)
* [isEnabledForShopContext](#method-isEnabledForShopContext)
* [isHookableOn](#method-isHookableOn)
* [isInstalled](#method-isInstalled)
* [isModuleTrusted](#method-isModuleTrusted)
* [isRegisteredInHook](#method-isRegisteredInHook)
* [l](#method-l)
* [loadUpgradeVersionList](#method-loadUpgradeVersionList)
* [needUpgrade](#method-needUpgrade)
* [preCall](#method-preCall)
* [processDeferedClearCache](#method-processDeferedClearCache)
* [processDeferedFuncCall](#method-processDeferedFuncCall)
* [registerExceptions](#method-registerExceptions)
* [registerHook](#method-registerHook)
* [removeOverride](#method-removeOverride)
* [render](#method-render)
* [resetCurrentSubTemplate](#method-resetCurrentSubTemplate)
* [runUpgradeModule](#method-runUpgradeModule)
* [setBatchMode](#method-setBatchMode)
* [setEmployee](#method-setEmployee)
* [setLang](#method-setLang)
* [setUpgradeMessage](#method-setUpgradeMessage)
* [uninstall](#method-uninstall)
* [uninstallOverrides](#method-uninstallOverrides)
* [unregisterExceptions](#method-unregisterExceptions)
* [unregisterHook](#method-unregisterHook)
* [updateModuleTranslations](#method-updateModuleTranslations)
* [updatePosition](#method-updatePosition)
* [updateTranslationsAfterInstall](#method-updateTranslationsAfterInstall)
* [upgradeModuleVersion](#method-upgradeModuleVersion)
* [useTooMuchMemory](#method-useTooMuchMemory)




Properties
----------


### <a name="property-$_direction"></a>$_direction

```php
protected mixed $_direction = null
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L50).


### <a name="property-$_employee"></a>$_employee

```php
protected mixed $_employee
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L29).


### <a name="property-$_limit"></a>$_limit

```php
protected mixed $_limit
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L44).


### <a name="property-$_render"></a>$_render

```php
protected \ModuleGridEngine $_render
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L53).


### <a name="property-$_sort"></a>$_sort

```php
protected mixed $_sort = null
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L47).


### <a name="property-$_start"></a>$_start

```php
protected mixed $_start
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L41).


### <a name="property-$_title"></a>$_title

```php
protected mixed $_title
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L38).


### <a name="property-$_totalCount"></a>$_totalCount

```php
protected integer $_totalCount
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L35).


### <a name="property-$_values"></a>$_values

```php
protected array $_values = array()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L32).


### <a name="property-$_INSTANCE"></a>$_INSTANCE

```php
protected array $_INSTANCE = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L131).


### <a name="property-$_batch_mode"></a>$_batch_mode

```php
protected mixed $_batch_mode = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L153).


### <a name="property-$_confirmations"></a>$_confirmations

```php
protected array $_confirmations = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L119).


### <a name="property-$_defered_clearCache"></a>$_defered_clearCache

```php
protected mixed $_defered_clearCache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L154).


### <a name="property-$_defered_func_call"></a>$_defered_func_call

```php
protected mixed $_defered_func_call = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L155).


### <a name="property-$_errors"></a>$_errors

```php
protected array $_errors = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L116).


### <a name="property-$_generate_config_xml_mode"></a>$_generate_config_xml_mode

```php
protected boolean $_generate_config_xml_mode = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L134).


### <a name="property-$_lang"></a>$_lang

```php
protected array $_lang = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L105).


### <a name="property-$_log_modules_perfs"></a>$_log_modules_perfs

```php
public boolean $_log_modules_perfs = null
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L163).


### <a name="property-$_log_modules_perfs_session"></a>$_log_modules_perfs_session

```php
public boolean $_log_modules_perfs_session = null
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L165).


### <a name="property-$_path"></a>$_path

```php
protected string $_path = null
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L108).


### <a name="property-$active"></a>$active

```php
public boolean $active = false
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L85).


### <a name="property-$additional_description"></a>$additional_description

```php
public mixed $additional_description
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L68).


### <a name="property-$allow_push"></a>$allow_push

```php
public boolean $allow_push
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L158).


### <a name="property-$author"></a>$author

```php
public string $author
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L58).


### <a name="property-$author_uri"></a>$author_uri

```php
public string $author_uri = ''
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L61).


### <a name="property-$avg_rate"></a>$avg_rate

```php
public mixed $avg_rate
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L74).


### <a name="property-$badges"></a>$badges

```php
public mixed $badges
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L76).


### <a name="property-$cache_permissions"></a>$cache_permissions

```php
protected array $cache_permissions = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L140).


### <a name="property-$classInModule"></a>$classInModule

```php
public array $classInModule = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L102).


### <a name="property-$compatibility"></a>$compatibility

```php
public mixed $compatibility
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L70).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L143).


### <a name="property-$controllers"></a>$controllers

```php
public array $controllers = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L99).


### <a name="property-$current_subtemplate"></a>$current_subtemplate

```php
protected \Smarty_Internal_Template $current_subtemplate = null
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L149).


### <a name="property-$database_version"></a>$database_version

```php
public mixed $database_version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L34).


### <a name="property-$dependencies"></a>$dependencies

```php
public array $dependencies = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L46).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L55).


### <a name="property-$description_full"></a>$description_full

```php
public mixed $description_full
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L66).


### <a name="property-$displayName"></a>$displayName

```php
public string $displayName
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L52).


### <a name="property-$enable_device"></a>$enable_device

```php
public mixed $enable_device = 7
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L93).


### <a name="property-$hosted_modules_blacklist"></a>$hosted_modules_blacklist

```php
public mixed $hosted_modules_blacklist = array('autoupgrade')
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L181).


### <a name="property-$id"></a>$id

```php
public integer $id = null
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L30).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = 'id_module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L125).


### <a name="property-$l_cache"></a>$l_cache

```php
protected array $l_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L137).


### <a name="property-$limited_countries"></a>$limited_countries

```php
public array $limited_countries = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L96).


### <a name="property-$local_path"></a>$local_path

```php
protected string $local_path = null
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L113).


### <a name="property-$module_key"></a>$module_key

```php
public string $module_key = ''
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L64).


### <a name="property-$modules_cache"></a>$modules_cache

```php
protected array $modules_cache
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L128).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L49).


### <a name="property-$nb_rates"></a>$nb_rates

```php
public mixed $nb_rates
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L72).


### <a name="property-$need_instance"></a>$need_instance

```php
public integer $need_instance = 1
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L79).


### <a name="property-$ps_versions_compliancy"></a>$ps_versions_compliancy

```php
public array $ps_versions_compliancy = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L43).


### <a name="property-$push_time_limit"></a>$push_time_limit

```php
public mixed $push_time_limit = 180
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L160).


### <a name="property-$registered_version"></a>$registered_version

```php
public string $registered_version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L40).


### <a name="property-$smarty"></a>$smarty

```php
protected \Smarty_Data $smarty
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L146).


### <a name="property-$tab"></a>$tab

```php
public string $tab = null
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L82).


### <a name="property-$table"></a>$table

```php
protected string $table = 'module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L122).


### <a name="property-$trusted"></a>$trusted

```php
public boolean $trusted = false
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L88).


### <a name="property-$update_translations_after_install"></a>$update_translations_after_install

```php
protected mixed $update_translations_after_install = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L151).


### <a name="property-$version"></a>$version

```php
public float $version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L33).


### <a name="property-$warning"></a>$warning

```php
public string $warning
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L91).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleCore::__construct(string $name, \Context $context)
```

Constructor



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L232)


#### Arguments
* $name **string** - Module unique name
* $context **[Context](class.ContextCore.md)**



### <a name="method-_clearCache"></a>_clearCache

```php
mixed ModuleCore::_clearCache($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2398)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-_deferedClearCache"></a>_deferedClearCache

```php
mixed ModuleCore::_deferedClearCache($template_path, $cache_id, $compile_id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2443)


#### Arguments
* $template_path **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-_displayCsv"></a>_displayCsv

```php
mixed ModuleGridCore::_displayCsv()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L181)




### <a name="method-_generateConfigXml"></a>_generateConfigXml

```php
mixed ModuleCore::_generateConfigXml()
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2452)




### <a name="method-_getApplicableTemplateDir"></a>_getApplicableTemplateDir

```php
mixed ModuleCore::_getApplicableTemplateDir($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2372)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloaded"></a>_isTemplateOverloaded

```php
mixed ModuleCore::_isTemplateOverloaded($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2261)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloadedStatic"></a>_isTemplateOverloadedStatic

```php
mixed ModuleCore::_isTemplateOverloadedStatic($module_name, $template)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2243)


#### Arguments
* $module_name **mixed**
* $template **mixed**



### <a name="method-addOverride"></a>addOverride

```php
boolean ModuleCore::addOverride(string $classname)
```

Add all methods in a module override to the override class



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2762](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2762)


#### Arguments
* $classname **string**



### <a name="method-adminDisplayInformation"></a>adminDisplayInformation

```php
mixed ModuleCore::adminDisplayInformation(string $msg)
```

add a info message to display at the top of the admin page



* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2664](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2664)


#### Arguments
* $msg **string**



### <a name="method-adminDisplayWarning"></a>adminDisplayWarning

```php
mixed ModuleCore::adminDisplayWarning(string $msg)
```

add a warning message to display at the top of the admin page



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2651)


#### Arguments
* $msg **string**



### <a name="method-checkCompliancy"></a>checkCompliancy

```php
mixed ModuleCore::checkCompliancy()
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L398)




### <a name="method-checkModuleFromAddonsApi"></a>checkModuleFromAddonsApi

```php
boolean ModuleCore::checkModuleFromAddonsApi($module_name)
```

Create the Addons API call from the module name only



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1839)


#### Arguments
* $module_name **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ModuleCore::cleanPositions($id_hook, $shop_list)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2032](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2032)


#### Arguments
* $id_hook **mixed**
* $shop_list **mixed**



### <a name="method-configXmlStringFormat"></a>configXmlStringFormat

```php
mixed ModuleCore::configXmlStringFormat($string)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1184)


#### Arguments
* $string **mixed**



### <a name="method-coreLoadModule"></a>coreLoadModule

```php
mixed ModuleCore::coreLoadModule($module_name)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1112)


#### Arguments
* $module_name **mixed**



### <a name="method-create"></a>create

```php
mixed ModuleGridCore::create($render, $type, $width, $height, $start, $limit, $sort, $dir)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L67)


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $start **mixed**
* $limit **mixed**
* $sort **mixed**
* $dir **mixed**



### <a name="method-csvExport"></a>csvExport

```php
mixed ModuleGridCore::csvExport($datas)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L153)


#### Arguments
* $datas **mixed**



### <a name="method-disable"></a>disable

```php
mixed ModuleCore::disable(boolean $force_all)
```

Desactivate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L802)


#### Arguments
* $force_all **boolean** - If true, disable module for all shop



### <a name="method-disableByName"></a>disableByName

```php
true ModuleCore::disableByName(array|string $name)
```

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L781)


#### Arguments
* $name **array|string**



### <a name="method-disableDevice"></a>disableDevice

```php
mixed ModuleCore::disableDevice($device)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L761)


#### Arguments
* $device **mixed**



### <a name="method-display"></a>display

```php
mixed ModuleCore::display($file, $template, $cache_id, $compile_id)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2290)


#### Arguments
* $file **mixed**
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-displayConfirmation"></a>displayConfirmation

```php
mixed ModuleCore::displayConfirmation($string)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2114)


#### Arguments
* $string **mixed**



### <a name="method-displayError"></a>displayError

```php
string ModuleCore::displayError(string|array $error)
```

Helper displaying error message(s)



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2062](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2062)


#### Arguments
* $error **string|array**



### <a name="method-displayFlags"></a>displayFlags

```php
mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L820)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-displayWarning"></a>displayWarning

```php
string ModuleCore::displayWarning($warning)
```

Helper displaying warning message(s)



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2091](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2091)


#### Arguments
* $warning **mixed**



### <a name="method-editExceptions"></a>editExceptions

```php
boolean ModuleCore::editExceptions($id_hook, array $excepts)
```

Edit exceptions for module->Hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1035)


#### Arguments
* $id_hook **mixed**
* $excepts **array** - List of shopID and file name



### <a name="method-enable"></a>enable

```php
mixed ModuleCore::enable(boolean $force_all)
```

Activate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 717](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L717)


#### Arguments
* $force_all **boolean** - If true, enable module for all shop



### <a name="method-enableByName"></a>enableByName

```php
true ModuleCore::enableByName(array|string $name)
```

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L696)


#### Arguments
* $name **array|string**



### <a name="method-enableDevice"></a>enableDevice

```php
mixed ModuleCore::enableDevice($device)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 749](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L749)


#### Arguments
* $device **mixed**



### <a name="method-engine"></a>engine

```php
mixed ModuleGridCore::engine($params)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L97)


#### Arguments
* $params **mixed**



### <a name="method-findTranslation"></a>findTranslation

```php
mixed ModuleCore::findTranslation($name, $string, $source)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1947](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1947)


#### Arguments
* $name **mixed**
* $string **mixed**
* $source **mixed**



### <a name="method-generateTrustedXml"></a>generateTrustedXml

```php
mixed ModuleCore::generateTrustedXml()
```

Generate XML files for trusted and untrusted modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1751)




### <a name="method-getAuthorizedModules"></a>getAuthorizedModules

```php
array|null ModuleCore::getAuthorizedModules(integer $group_id)
```

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2550)


#### Arguments
* $group_id **integer**



### <a name="method-getBatchMode"></a>getBatchMode

```php
boolean ModuleCore::getBatchMode()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L196)




### <a name="method-getCacheId"></a>getCacheId

```php
mixed ModuleCore::getCacheId($name)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2266)


#### Arguments
* $name **mixed**



### <a name="method-getConfirmations"></a>getConfirmations

```php
array ModuleCore::getConfirmations()
```

Get module messages confirmation



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2592](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2592)




### <a name="method-getCurrentSubTemplate"></a>getCurrentSubTemplate

```php
\Smarty_Internal_Template ModuleCore::getCurrentSubTemplate(string $template, string|null $cache_id, string|null $compile_id)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2327)


#### Arguments
* $template **string**
* $cache_id **string|null**
* $compile_id **string|null**



### <a name="method-getData"></a>getData

```php
mixed ModuleGridCore::getData()
```





* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/module/ModuleGrid.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L55)




### <a name="method-getDate"></a>getDate

```php
mixed ModuleGridCore::getDate()
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L192)




### <a name="method-getErrors"></a>getErrors

```php
array ModuleCore::getErrors()
```

Get module errors



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2581](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2581)




### <a name="method-getExceptions"></a>getExceptions

```php
mixed ModuleCore::getExceptions($id_hook, $dispatch)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2187)


#### Arguments
* $id_hook **mixed**
* $dispatch **mixed**



### <a name="method-getExceptionsStatic"></a>getExceptionsStatic

```php
mixed ModuleCore::getExceptionsStatic($id_module, $id_hook, $dispatch)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2133)


#### Arguments
* $id_module **mixed**
* $id_hook **mixed**
* $dispatch **mixed**



### <a name="method-getInstanceById"></a>getInstanceById

```php
\Module ModuleCore::getInstanceById(integer $id_module)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1163)


#### Arguments
* $id_module **integer** - Module ID



### <a name="method-getInstanceByName"></a>getInstanceByName

```php
\Module ModuleCore::getInstanceByName(string $module_name)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1094](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1094)


#### Arguments
* $module_name **string** - Module name



### <a name="method-getLang"></a>getLang

```php
mixed ModuleGridCore::getLang()
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L197)




### <a name="method-getLocalPath"></a>getLocalPath

```php
string ModuleCore::getLocalPath()
```

Get local path for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2603)




### <a name="method-getModuleIdByName"></a>getModuleIdByName

```php
integer ModuleCore::getModuleIdByName(string $name)
```

Get ID module by name



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2564)


#### Arguments
* $name **string**



### <a name="method-getModuleName"></a>getModuleName

```php
mixed ModuleCore::getModuleName($module)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1190)


#### Arguments
* $module **mixed**



### <a name="method-getModuleNameFromClass"></a>getModuleNameFromClass

```php
boolean|string ModuleCore::getModuleNameFromClass(mixed $current_class)
```

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1056](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1056)


#### Arguments
* $current_class **mixed** - the



### <a name="method-getModulesDirOnDisk"></a>getModulesDirOnDisk

```php
array ModuleCore::getModulesDirOnDisk()
```

Return modules directory list



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1577)




### <a name="method-getModulesInstalled"></a>getModulesInstalled

```php
array ModuleCore::getModulesInstalled(integer $position)
```

Return installed modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1664](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1664)


#### Arguments
* $position **integer** - Take only positionnables modules



### <a name="method-getModulesOnDisk"></a>getModulesOnDisk

```php
array ModuleCore::getModulesOnDisk(boolean $use_config, $logged_on_addons, $id_employee)
```

Return available modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1250)


#### Arguments
* $use_config **boolean** - in order to use config.xml file in module dir
* $logged_on_addons **mixed**
* $id_employee **mixed**



### <a name="method-getNativeModuleList"></a>getNativeModuleList

```php
mixed ModuleCore::getNativeModuleList()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1629](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1629)




### <a name="method-getNonNativeModuleList"></a>getNonNativeModuleList

```php
array ModuleCore::getNonNativeModuleList()
```

Return non native module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1602)




### <a name="method-getPathUri"></a>getPathUri

```php
string ModuleCore::getPathUri()
```

Get uri path for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2614](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2614)




### <a name="method-getPaymentModules"></a>getPaymentModules

```php
array ModuleCore::getPaymentModules()
```

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1901](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1901)




### <a name="method-getPaypalIgnore"></a>getPaypalIgnore

```php
mixed ModuleCore::getPaypalIgnore()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1890](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1890)




### <a name="method-getPermission"></a>getPermission

```php
boolean ModuleCore::getPermission(array $variable, object $employee)
```

Check employee permission for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2501)


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
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2513](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2513)


#### Arguments
* $id_module **integer**
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPosition"></a>getPosition

```php
mixed ModuleCore::getPosition($id_hook)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2625)


#### Arguments
* $id_hook **mixed**



### <a name="method-getPossibleHooksList"></a>getPossibleHooksList

```php
array ModuleCore::getPossibleHooksList()
```

Return the hooks list where this module can be hooked.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 3061](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L3061)




### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string ModuleCore::getTemplatePath(string $template)
```

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2352](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2352)


#### Arguments
* $template **string**



### <a name="method-getUpgradeStatus"></a>getUpgradeStatus

```php
boolean ModuleCore::getUpgradeStatus($module_name)
```

Return the status of the upgraded module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L627)


#### Arguments
* $module_name **mixed**



### <a name="method-hookExec"></a>hookExec

```php
string ModuleCore::hookExec(string $hook_name, array $hook_args, $id_module)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1865](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1865)


#### Arguments
* $hook_name **string** - Hook Name
* $hook_args **array** - Parameters for the functions
* $id_module **mixed**



### <a name="method-hookExecPayment"></a>hookExecPayment

```php
string ModuleCore::hookExecPayment()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1876)




### <a name="method-initUpgradeModule"></a>initUpgradeModule

```php
boolean ModuleCore::initUpgradeModule($module)
```

Init the upgrade module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L452)


#### Arguments
* $module **mixed**



### <a name="method-install"></a>install

```php
mixed ModuleCore::install()
```

Insert module into datable



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L306)




### <a name="method-installControllers"></a>installControllers

```php
boolean ModuleCore::installControllers()
```

Install module's controllers using public property $controllers



* Visibility: **private**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2676](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2676)




### <a name="method-installOverrides"></a>installOverrides

```php
boolean ModuleCore::installOverrides()
```

Install overrides files for the module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2717](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2717)




### <a name="method-isCached"></a>isCached

```php
mixed ModuleCore::isCached($template, $cache_id, $compile_id)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2377](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2377)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-isEnabled"></a>isEnabled

```php
mixed ModuleCore::isEnabled($module_name)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2213)


#### Arguments
* $module_name **mixed**



### <a name="method-isEnabledForShopContext"></a>isEnabledForShopContext

```php
mixed ModuleCore::isEnabledForShopContext()
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2202)




### <a name="method-isHookableOn"></a>isHookableOn

```php
boolean ModuleCore::isHookableOn(string $hook_name)
```

Check if the module is transplantable on the hook in parameter



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2489](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2489)


#### Arguments
* $hook_name **string**



### <a name="method-isInstalled"></a>isInstalled

```php
mixed ModuleCore::isInstalled($module_name)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2192)


#### Arguments
* $module_name **mixed**



### <a name="method-isModuleTrusted"></a>isModuleTrusted

```php
integer ModuleCore::isModuleTrusted($module_name)
```

Return if the module is provided by addons.prestashop.com or not



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1683)


#### Arguments
* $module_name **mixed**



### <a name="method-isRegisteredInHook"></a>isRegisteredInHook

```php
mixed ModuleCore::isRegisteredInHook($hook)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2227)


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
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1963](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1963)


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
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L573)


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
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L550)


#### Arguments
* $module **mixed**



### <a name="method-preCall"></a>preCall

```php
mixed ModuleCore::preCall($module_name)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1882)


#### Arguments
* $module_name **mixed**



### <a name="method-processDeferedClearCache"></a>processDeferedClearCache

```php
mixed ModuleCore::processDeferedClearCache()
```

Clear the caches stored in $_defered_clearCache



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L215)




### <a name="method-processDeferedFuncCall"></a>processDeferedFuncCall

```php
mixed ModuleCore::processDeferedFuncCall()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L201)




### <a name="method-registerExceptions"></a>registerExceptions

```php
boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shop_list)
```

Add exceptions for module->Hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1000](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1000)


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
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L854)


#### Arguments
* $hook_name **string** - Hook name
* $shop_list **array** - List of shop linked to the hook (if null, link hook to all shops)



### <a name="method-removeOverride"></a>removeOverride

```php
boolean ModuleCore::removeOverride(string $classname)
```

Remove all methods in a module override from the override class



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2911](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2911)


#### Arguments
* $classname **string**



### <a name="method-render"></a>render

```php
mixed ModuleGridCore::render()
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L92)




### <a name="method-resetCurrentSubTemplate"></a>resetCurrentSubTemplate

```php
mixed ModuleCore::resetCurrentSubTemplate($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2340)


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
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L481)




### <a name="method-setBatchMode"></a>setBatchMode

```php
mixed ModuleCore::setBatchMode(boolean $value)
```

Set the flag to indicate we are doing an import



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L188)


#### Arguments
* $value **boolean**



### <a name="method-setEmployee"></a>setEmployee

```php
mixed ModuleGridCore::setEmployee($id_employee)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L57)


#### Arguments
* $id_employee **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed ModuleGridCore::setLang($id_lang)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/ModuleGrid.php#L62)


#### Arguments
* $id_lang **mixed**



### <a name="method-setUpgradeMessage"></a>setUpgradeMessage

```php
mixed ModuleCore::setUpgradeMessage($upgrade_detail)
```

Set errors, warning or success message of a module upgrade



* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L422)


#### Arguments
* $upgrade_detail **mixed**



### <a name="method-uninstall"></a>uninstall

```php
boolean ModuleCore::uninstall()
```

Delete module from datable



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L638)




### <a name="method-uninstallOverrides"></a>uninstallOverrides

```php
boolean ModuleCore::uninstallOverrides()
```

Uninstall overrides files for the module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2739](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L2739)




### <a name="method-unregisterExceptions"></a>unregisterExceptions

```php
boolean ModuleCore::unregisterExceptions($hook_id, array $shop_list)
```

Unregister exceptions linked to module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 984](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L984)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-unregisterHook"></a>unregisterHook

```php
boolean ModuleCore::unregisterHook($hook_id, array $shop_list)
```

Unregister module from hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 947](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L947)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-updateModuleTranslations"></a>updateModuleTranslations

```php
mixed ModuleCore::updateModuleTranslations()
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L412)




### <a name="method-updatePosition"></a>updatePosition

```php
mixed ModuleCore::updatePosition($id_hook, $way, $position)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1979](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1979)


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
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L407)


#### Arguments
* $update **mixed**



### <a name="method-upgradeModuleVersion"></a>upgradeModuleVersion

```php
boolean ModuleCore::upgradeModuleVersion($name, $version)
```

Upgrade the registered version to a new one



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L535)


#### Arguments
* $name **mixed**
* $version **mixed**



### <a name="method-useTooMuchMemory"></a>useTooMuchMemory

```php
mixed ModuleCore::useTooMuchMemory()
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/module/Module.php#L1229)



