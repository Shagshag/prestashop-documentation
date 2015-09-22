Class ModuleCore
=====================





* Class name: ModuleCore
* This is an **abstract** class
* Source: [classes/module/Module.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L27)

Constants
----------

* [CACHE_FILE_ALL_COUNTRY_MODULES_LIST](#constant-CACHE_FILE_ALL_COUNTRY_MODULES_LIST)
* [CACHE_FILE_CUSTOMER_MODULES_LIST](#constant-CACHE_FILE_CUSTOMER_MODULES_LIST)
* [CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST](#constant-CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST)
* [CACHE_FILE_MODULES_LIST](#constant-CACHE_FILE_MODULES_LIST)
* [CACHE_FILE_MUST_HAVE_MODULES_LIST](#constant-CACHE_FILE_MUST_HAVE_MODULES_LIST)
* [CACHE_FILE_TAB_MODULES_LIST](#constant-CACHE_FILE_TAB_MODULES_LIST)
* [CACHE_FILE_TRUSTED_MODULES_LIST](#constant-CACHE_FILE_TRUSTED_MODULES_LIST)
* [CACHE_FILE_UNTRUSTED_MODULES_LIST](#constant-CACHE_FILE_UNTRUSTED_MODULES_LIST)

Properties
----------

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

Methods
-------
* [__construct](#method-__construct)
* [_clearCache](#method-_clearCache)
* [_deferedClearCache](#method-_deferedClearCache)
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
* [findTranslation](#method-findTranslation)
* [generateTrustedXml](#method-generateTrustedXml)
* [getAuthorizedModules](#method-getAuthorizedModules)
* [getBatchMode](#method-getBatchMode)
* [getCacheId](#method-getCacheId)
* [getConfirmations](#method-getConfirmations)
* [getCurrentSubTemplate](#method-getCurrentSubTemplate)
* [getErrors](#method-getErrors)
* [getExceptions](#method-getExceptions)
* [getExceptionsStatic](#method-getExceptionsStatic)
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
* [resetCurrentSubTemplate](#method-resetCurrentSubTemplate)
* [runUpgradeModule](#method-runUpgradeModule)
* [setBatchMode](#method-setBatchMode)
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


Constants
----------


### <a name="constant-CACHE_FILE_ALL_COUNTRY_MODULES_LIST"></a>CACHE_FILE_ALL_COUNTRY_MODULES_LIST

    const CACHE_FILE_ALL_COUNTRY_MODULES_LIST = '/config/xml/modules_native_addons.xml'



* Source: [classes/module/Module.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L171)


### <a name="constant-CACHE_FILE_CUSTOMER_MODULES_LIST"></a>CACHE_FILE_CUSTOMER_MODULES_LIST

    const CACHE_FILE_CUSTOMER_MODULES_LIST = '/config/xml/customer_modules_list.xml'



* Source: [classes/module/Module.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L174)


### <a name="constant-CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST"></a>CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST

    const CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST = '/config/xml/default_country_modules_list.xml'



* Source: [classes/module/Module.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L172)


### <a name="constant-CACHE_FILE_MODULES_LIST"></a>CACHE_FILE_MODULES_LIST

    const CACHE_FILE_MODULES_LIST = '/config/xml/modules_list.xml'



* Source: [classes/module/Module.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L167)


### <a name="constant-CACHE_FILE_MUST_HAVE_MODULES_LIST"></a>CACHE_FILE_MUST_HAVE_MODULES_LIST

    const CACHE_FILE_MUST_HAVE_MODULES_LIST = '/config/xml/must_have_modules_list.xml'



* Source: [classes/module/Module.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L176)


### <a name="constant-CACHE_FILE_TAB_MODULES_LIST"></a>CACHE_FILE_TAB_MODULES_LIST

    const CACHE_FILE_TAB_MODULES_LIST = '/config/xml/tab_modules_list.xml'



* Source: [classes/module/Module.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L169)


### <a name="constant-CACHE_FILE_TRUSTED_MODULES_LIST"></a>CACHE_FILE_TRUSTED_MODULES_LIST

    const CACHE_FILE_TRUSTED_MODULES_LIST = '/config/xml/trusted_modules_list.xml'



* Source: [classes/module/Module.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L178)


### <a name="constant-CACHE_FILE_UNTRUSTED_MODULES_LIST"></a>CACHE_FILE_UNTRUSTED_MODULES_LIST

    const CACHE_FILE_UNTRUSTED_MODULES_LIST = '/config/xml/untrusted_modules_list.xml'



* Source: [classes/module/Module.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L179)


Properties
----------


### <a name="property-$_INSTANCE"></a>$_INSTANCE

    protected array $_INSTANCE = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L131)


### <a name="property-$_batch_mode"></a>$_batch_mode

    protected mixed $_batch_mode = false





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L153)


### <a name="property-$_confirmations"></a>$_confirmations

    protected array $_confirmations = array()





* Visibility: **protected**
* Source: [classes/module/Module.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L119)


### <a name="property-$_defered_clearCache"></a>$_defered_clearCache

    protected mixed $_defered_clearCache = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L154)


### <a name="property-$_defered_func_call"></a>$_defered_func_call

    protected mixed $_defered_func_call = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L155)


### <a name="property-$_errors"></a>$_errors

    protected array $_errors = array()





* Visibility: **protected**
* Source: [classes/module/Module.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L116)


### <a name="property-$_generate_config_xml_mode"></a>$_generate_config_xml_mode

    protected boolean $_generate_config_xml_mode = false





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L134)


### <a name="property-$_lang"></a>$_lang

    protected array $_lang = array()





* Visibility: **protected**
* Source: [classes/module/Module.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L105)


### <a name="property-$_log_modules_perfs"></a>$_log_modules_perfs

    public boolean $_log_modules_perfs = null





* Visibility: **public**
* This property is **static**.
* Source: [classes/module/Module.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L163)


### <a name="property-$_log_modules_perfs_session"></a>$_log_modules_perfs_session

    public boolean $_log_modules_perfs_session = null





* Visibility: **public**
* This property is **static**.
* Source: [classes/module/Module.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L165)


### <a name="property-$_path"></a>$_path

    protected string $_path = null





* Visibility: **protected**
* Source: [classes/module/Module.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L108)


### <a name="property-$active"></a>$active

    public boolean $active = false





* Visibility: **public**
* Source: [classes/module/Module.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L85)


### <a name="property-$additional_description"></a>$additional_description

    public mixed $additional_description





* Visibility: **public**
* Source: [classes/module/Module.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L68)


### <a name="property-$allow_push"></a>$allow_push

    public boolean $allow_push





* Visibility: **public**
* Source: [classes/module/Module.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L158)


### <a name="property-$author"></a>$author

    public string $author





* Visibility: **public**
* Source: [classes/module/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L58)


### <a name="property-$author_uri"></a>$author_uri

    public string $author_uri = ''





* Visibility: **public**
* Source: [classes/module/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L61)


### <a name="property-$avg_rate"></a>$avg_rate

    public mixed $avg_rate





* Visibility: **public**
* Source: [classes/module/Module.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L74)


### <a name="property-$badges"></a>$badges

    public mixed $badges





* Visibility: **public**
* Source: [classes/module/Module.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L76)


### <a name="property-$cache_permissions"></a>$cache_permissions

    protected array $cache_permissions = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L140)


### <a name="property-$classInModule"></a>$classInModule

    public array $classInModule = array()





* Visibility: **public**
* This property is **static**.
* Source: [classes/module/Module.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L102)


### <a name="property-$compatibility"></a>$compatibility

    public mixed $compatibility





* Visibility: **public**
* Source: [classes/module/Module.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L70)


### <a name="property-$context"></a>$context

    protected \Context $context





* Visibility: **protected**
* Source: [classes/module/Module.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L143)


### <a name="property-$controllers"></a>$controllers

    public array $controllers = array()





* Visibility: **public**
* Source: [classes/module/Module.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L99)


### <a name="property-$current_subtemplate"></a>$current_subtemplate

    protected \Smarty_Internal_Template $current_subtemplate = null





* Visibility: **protected**
* Source: [classes/module/Module.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L149)


### <a name="property-$database_version"></a>$database_version

    public mixed $database_version





* Visibility: **public**
* Source: [classes/module/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L34)


### <a name="property-$dependencies"></a>$dependencies

    public array $dependencies = array()





* Visibility: **public**
* Source: [classes/module/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L46)


### <a name="property-$description"></a>$description

    public string $description





* Visibility: **public**
* Source: [classes/module/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L55)


### <a name="property-$description_full"></a>$description_full

    public mixed $description_full





* Visibility: **public**
* Source: [classes/module/Module.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L66)


### <a name="property-$displayName"></a>$displayName

    public string $displayName





* Visibility: **public**
* Source: [classes/module/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L52)


### <a name="property-$enable_device"></a>$enable_device

    public mixed $enable_device = 7





* Visibility: **public**
* Source: [classes/module/Module.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L93)


### <a name="property-$hosted_modules_blacklist"></a>$hosted_modules_blacklist

    public mixed $hosted_modules_blacklist = array('autoupgrade')





* Visibility: **public**
* This property is **static**.
* Source: [classes/module/Module.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L181)


### <a name="property-$id"></a>$id

    public integer $id = null





* Visibility: **public**
* Source: [classes/module/Module.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L30)


### <a name="property-$identifier"></a>$identifier

    protected string $identifier = 'id_module'





* Visibility: **protected**
* Source: [classes/module/Module.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L125)


### <a name="property-$l_cache"></a>$l_cache

    protected array $l_cache = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L137)


### <a name="property-$limited_countries"></a>$limited_countries

    public array $limited_countries = array()





* Visibility: **public**
* Source: [classes/module/Module.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L96)


### <a name="property-$local_path"></a>$local_path

    protected string $local_path = null





* Visibility: **protected**
* Source: [classes/module/Module.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L113)


### <a name="property-$module_key"></a>$module_key

    public string $module_key = ''





* Visibility: **public**
* Source: [classes/module/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L64)


### <a name="property-$modules_cache"></a>$modules_cache

    protected array $modules_cache





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L128)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/module/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L49)


### <a name="property-$nb_rates"></a>$nb_rates

    public mixed $nb_rates





* Visibility: **public**
* Source: [classes/module/Module.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L72)


### <a name="property-$need_instance"></a>$need_instance

    public integer $need_instance = 1





* Visibility: **public**
* Source: [classes/module/Module.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L79)


### <a name="property-$ps_versions_compliancy"></a>$ps_versions_compliancy

    public array $ps_versions_compliancy = array()





* Visibility: **public**
* Source: [classes/module/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L43)


### <a name="property-$push_time_limit"></a>$push_time_limit

    public mixed $push_time_limit = 180





* Visibility: **public**
* Source: [classes/module/Module.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L160)


### <a name="property-$registered_version"></a>$registered_version

    public string $registered_version





* Visibility: **public**
* Source: [classes/module/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L40)


### <a name="property-$smarty"></a>$smarty

    protected \Smarty_Data $smarty





* Visibility: **protected**
* Source: [classes/module/Module.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L146)


### <a name="property-$tab"></a>$tab

    public string $tab = null





* Visibility: **public**
* Source: [classes/module/Module.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L82)


### <a name="property-$table"></a>$table

    protected string $table = 'module'





* Visibility: **protected**
* Source: [classes/module/Module.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L122)


### <a name="property-$trusted"></a>$trusted

    public boolean $trusted = false





* Visibility: **public**
* Source: [classes/module/Module.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L88)


### <a name="property-$update_translations_after_install"></a>$update_translations_after_install

    protected mixed $update_translations_after_install = true





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L151)


### <a name="property-$version"></a>$version

    public float $version





* Visibility: **public**
* Source: [classes/module/Module.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L33)


### <a name="property-$warning"></a>$warning

    public string $warning





* Visibility: **public**
* Source: [classes/module/Module.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L91)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ModuleCore::__construct(string $name, \Context $context)

Constructor



* Visibility: **public**
* Source: [classes/module/Module.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L232)


#### Arguments
* $name **string** - Module unique name
* $context **[Context](class.ContextCore.md)**



### <a name="method-_clearCache"></a>_clearCache

    mixed ModuleCore::_clearCache($template, $cache_id, $compile_id)





* Visibility: **protected**
* Source: [classes/module/Module.php line 2399](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2399)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-_deferedClearCache"></a>_deferedClearCache

    mixed ModuleCore::_deferedClearCache($template_path, $cache_id, $compile_id)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 2444](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2444)


#### Arguments
* $template_path **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-_generateConfigXml"></a>_generateConfigXml

    mixed ModuleCore::_generateConfigXml()





* Visibility: **protected**
* Source: [classes/module/Module.php line 2453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2453)




### <a name="method-_getApplicableTemplateDir"></a>_getApplicableTemplateDir

    mixed ModuleCore::_getApplicableTemplateDir($template)





* Visibility: **protected**
* Source: [classes/module/Module.php line 2373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2373)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloaded"></a>_isTemplateOverloaded

    mixed ModuleCore::_isTemplateOverloaded($template)





* Visibility: **protected**
* Source: [classes/module/Module.php line 2262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2262)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloadedStatic"></a>_isTemplateOverloadedStatic

    mixed ModuleCore::_isTemplateOverloadedStatic($module_name, $template)





* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 2244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2244)


#### Arguments
* $module_name **mixed**
* $template **mixed**



### <a name="method-addOverride"></a>addOverride

    boolean ModuleCore::addOverride(string $classname)

Add all methods in a module override to the override class



* Visibility: **public**
* Source: [classes/module/Module.php line 2763](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2763)


#### Arguments
* $classname **string**



### <a name="method-adminDisplayInformation"></a>adminDisplayInformation

    mixed ModuleCore::adminDisplayInformation(string $msg)

add a info message to display at the top of the admin page



* Visibility: **protected**
* Source: [classes/module/Module.php line 2665](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2665)


#### Arguments
* $msg **string**



### <a name="method-adminDisplayWarning"></a>adminDisplayWarning

    mixed ModuleCore::adminDisplayWarning(string $msg)

add a warning message to display at the top of the admin page



* Visibility: **public**
* Source: [classes/module/Module.php line 2652](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2652)


#### Arguments
* $msg **string**



### <a name="method-checkCompliancy"></a>checkCompliancy

    mixed ModuleCore::checkCompliancy()





* Visibility: **public**
* Source: [classes/module/Module.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L398)




### <a name="method-checkModuleFromAddonsApi"></a>checkModuleFromAddonsApi

    boolean ModuleCore::checkModuleFromAddonsApi($module_name)

Create the Addons API call from the module name only



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1840](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1840)


#### Arguments
* $module_name **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

    mixed ModuleCore::cleanPositions($id_hook, $shop_list)





* Visibility: **public**
* Source: [classes/module/Module.php line 2033](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2033)


#### Arguments
* $id_hook **mixed**
* $shop_list **mixed**



### <a name="method-configXmlStringFormat"></a>configXmlStringFormat

    mixed ModuleCore::configXmlStringFormat($string)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1185)


#### Arguments
* $string **mixed**



### <a name="method-coreLoadModule"></a>coreLoadModule

    mixed ModuleCore::coreLoadModule($module_name)





* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1113)


#### Arguments
* $module_name **mixed**



### <a name="method-disable"></a>disable

    mixed ModuleCore::disable(boolean $force_all)

Desactivate current module.



* Visibility: **public**
* Source: [classes/module/Module.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L802)


#### Arguments
* $force_all **boolean** - If true, disable module for all shop



### <a name="method-disableByName"></a>disableByName

    true ModuleCore::disableByName(array|string $name)

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L781)


#### Arguments
* $name **array|string**



### <a name="method-disableDevice"></a>disableDevice

    mixed ModuleCore::disableDevice($device)





* Visibility: **public**
* Source: [classes/module/Module.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L761)


#### Arguments
* $device **mixed**



### <a name="method-display"></a>display

    mixed ModuleCore::display($file, $template, $cache_id, $compile_id)





* Visibility: **public**
* Source: [classes/module/Module.php line 2291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2291)


#### Arguments
* $file **mixed**
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-displayConfirmation"></a>displayConfirmation

    mixed ModuleCore::displayConfirmation($string)





* Visibility: **public**
* Source: [classes/module/Module.php line 2115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2115)


#### Arguments
* $string **mixed**



### <a name="method-displayError"></a>displayError

    string ModuleCore::displayError(string|array $error)

Helper displaying error message(s)



* Visibility: **public**
* Source: [classes/module/Module.php line 2063](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2063)


#### Arguments
* $error **string|array**



### <a name="method-displayFlags"></a>displayFlags

    mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)

Display flags in forms for translations



* Visibility: **public**
* Source: [classes/module/Module.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L820)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-displayWarning"></a>displayWarning

    string ModuleCore::displayWarning($warning)

Helper displaying warning message(s)



* Visibility: **public**
* Source: [classes/module/Module.php line 2092](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2092)


#### Arguments
* $warning **mixed**



### <a name="method-editExceptions"></a>editExceptions

    boolean ModuleCore::editExceptions($id_hook, array $excepts)

Edit exceptions for module->Hook



* Visibility: **public**
* Source: [classes/module/Module.php line 1036](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1036)


#### Arguments
* $id_hook **mixed**
* $excepts **array** - List of shopID and file name



### <a name="method-enable"></a>enable

    mixed ModuleCore::enable(boolean $force_all)

Activate current module.



* Visibility: **public**
* Source: [classes/module/Module.php line 717](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L717)


#### Arguments
* $force_all **boolean** - If true, enable module for all shop



### <a name="method-enableByName"></a>enableByName

    true ModuleCore::enableByName(array|string $name)

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L696)


#### Arguments
* $name **array|string**



### <a name="method-enableDevice"></a>enableDevice

    mixed ModuleCore::enableDevice($device)





* Visibility: **public**
* Source: [classes/module/Module.php line 749](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L749)


#### Arguments
* $device **mixed**



### <a name="method-findTranslation"></a>findTranslation

    mixed ModuleCore::findTranslation($name, $string, $source)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1948](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1948)


#### Arguments
* $name **mixed**
* $string **mixed**
* $source **mixed**



### <a name="method-generateTrustedXml"></a>generateTrustedXml

    mixed ModuleCore::generateTrustedXml()

Generate XML files for trusted and untrusted modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1752](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1752)




### <a name="method-getAuthorizedModules"></a>getAuthorizedModules

    array|null ModuleCore::getAuthorizedModules(integer $group_id)

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 2551](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2551)


#### Arguments
* $group_id **integer**



### <a name="method-getBatchMode"></a>getBatchMode

    boolean ModuleCore::getBatchMode()





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L196)




### <a name="method-getCacheId"></a>getCacheId

    mixed ModuleCore::getCacheId($name)





* Visibility: **protected**
* Source: [classes/module/Module.php line 2267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2267)


#### Arguments
* $name **mixed**



### <a name="method-getConfirmations"></a>getConfirmations

    array ModuleCore::getConfirmations()

Get module messages confirmation



* Visibility: **public**
* Source: [classes/module/Module.php line 2593](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2593)




### <a name="method-getCurrentSubTemplate"></a>getCurrentSubTemplate

    \Smarty_Internal_Template ModuleCore::getCurrentSubTemplate(string $template, string|null $cache_id, string|null $compile_id)





* Visibility: **protected**
* Source: [classes/module/Module.php line 2328](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2328)


#### Arguments
* $template **string**
* $cache_id **string|null**
* $compile_id **string|null**



### <a name="method-getErrors"></a>getErrors

    array ModuleCore::getErrors()

Get module errors



* Visibility: **public**
* Source: [classes/module/Module.php line 2582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2582)




### <a name="method-getExceptions"></a>getExceptions

    mixed ModuleCore::getExceptions($id_hook, $dispatch)





* Visibility: **public**
* Source: [classes/module/Module.php line 2188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2188)


#### Arguments
* $id_hook **mixed**
* $dispatch **mixed**



### <a name="method-getExceptionsStatic"></a>getExceptionsStatic

    mixed ModuleCore::getExceptionsStatic($id_module, $id_hook, $dispatch)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 2134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2134)


#### Arguments
* $id_module **mixed**
* $id_hook **mixed**
* $dispatch **mixed**



### <a name="method-getInstanceById"></a>getInstanceById

    \Module ModuleCore::getInstanceById(integer $id_module)

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1164)


#### Arguments
* $id_module **integer** - Module ID



### <a name="method-getInstanceByName"></a>getInstanceByName

    \Module ModuleCore::getInstanceByName(string $module_name)

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1095](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1095)


#### Arguments
* $module_name **string** - Module name



### <a name="method-getLocalPath"></a>getLocalPath

    string ModuleCore::getLocalPath()

Get local path for module



* Visibility: **public**
* Source: [classes/module/Module.php line 2604](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2604)




### <a name="method-getModuleIdByName"></a>getModuleIdByName

    integer ModuleCore::getModuleIdByName(string $name)

Get ID module by name



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 2565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2565)


#### Arguments
* $name **string**



### <a name="method-getModuleName"></a>getModuleName

    mixed ModuleCore::getModuleName($module)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1191)


#### Arguments
* $module **mixed**



### <a name="method-getModuleNameFromClass"></a>getModuleNameFromClass

    boolean|string ModuleCore::getModuleNameFromClass(mixed $current_class)

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1057](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1057)


#### Arguments
* $current_class **mixed** - the



### <a name="method-getModulesDirOnDisk"></a>getModulesDirOnDisk

    array ModuleCore::getModulesDirOnDisk()

Return modules directory list



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1578](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1578)




### <a name="method-getModulesInstalled"></a>getModulesInstalled

    array ModuleCore::getModulesInstalled(integer $position)

Return installed modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1665](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1665)


#### Arguments
* $position **integer** - Take only positionnables modules



### <a name="method-getModulesOnDisk"></a>getModulesOnDisk

    array ModuleCore::getModulesOnDisk(boolean $use_config, $logged_on_addons, $id_employee)

Return available modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1251)


#### Arguments
* $use_config **boolean** - in order to use config.xml file in module dir
* $logged_on_addons **mixed**
* $id_employee **mixed**



### <a name="method-getNativeModuleList"></a>getNativeModuleList

    mixed ModuleCore::getNativeModuleList()





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1630](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1630)




### <a name="method-getNonNativeModuleList"></a>getNonNativeModuleList

    array ModuleCore::getNonNativeModuleList()

Return non native module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1603)




### <a name="method-getPathUri"></a>getPathUri

    string ModuleCore::getPathUri()

Get uri path for module



* Visibility: **public**
* Source: [classes/module/Module.php line 2615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2615)




### <a name="method-getPaymentModules"></a>getPaymentModules

    array ModuleCore::getPaymentModules()

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1902](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1902)




### <a name="method-getPaypalIgnore"></a>getPaypalIgnore

    mixed ModuleCore::getPaypalIgnore()





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1891](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1891)




### <a name="method-getPermission"></a>getPermission

    boolean ModuleCore::getPermission(array $variable, object $employee)

Check employee permission for module



* Visibility: **public**
* Source: [classes/module/Module.php line 2502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2502)


#### Arguments
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPermissionStatic"></a>getPermissionStatic

    boolean ModuleCore::getPermissionStatic(integer $id_module, array $variable, object $employee)

Check employee permission for module (static method)



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 2514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2514)


#### Arguments
* $id_module **integer**
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPosition"></a>getPosition

    mixed ModuleCore::getPosition($id_hook)





* Visibility: **public**
* Source: [classes/module/Module.php line 2626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2626)


#### Arguments
* $id_hook **mixed**



### <a name="method-getPossibleHooksList"></a>getPossibleHooksList

    array ModuleCore::getPossibleHooksList()

Return the hooks list where this module can be hooked.



* Visibility: **public**
* Source: [classes/module/Module.php line 3062](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L3062)




### <a name="method-getTemplatePath"></a>getTemplatePath

    string ModuleCore::getTemplatePath(string $template)

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* Source: [classes/module/Module.php line 2353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2353)


#### Arguments
* $template **string**



### <a name="method-getUpgradeStatus"></a>getUpgradeStatus

    boolean ModuleCore::getUpgradeStatus($module_name)

Return the status of the upgraded module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L627)


#### Arguments
* $module_name **mixed**



### <a name="method-hookExec"></a>hookExec

    string ModuleCore::hookExec(string $hook_name, array $hook_args, $id_module)

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1866](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1866)


#### Arguments
* $hook_name **string** - Hook Name
* $hook_args **array** - Parameters for the functions
* $id_module **mixed**



### <a name="method-hookExecPayment"></a>hookExecPayment

    string ModuleCore::hookExecPayment()





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1877](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1877)




### <a name="method-initUpgradeModule"></a>initUpgradeModule

    boolean ModuleCore::initUpgradeModule($module)

Init the upgrade module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L452)


#### Arguments
* $module **mixed**



### <a name="method-install"></a>install

    mixed ModuleCore::install()

Insert module into datable



* Visibility: **public**
* Source: [classes/module/Module.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L306)




### <a name="method-installControllers"></a>installControllers

    boolean ModuleCore::installControllers()

Install module's controllers using public property $controllers



* Visibility: **private**
* Source: [classes/module/Module.php line 2677](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2677)




### <a name="method-installOverrides"></a>installOverrides

    boolean ModuleCore::installOverrides()

Install overrides files for the module



* Visibility: **public**
* Source: [classes/module/Module.php line 2718](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2718)




### <a name="method-isCached"></a>isCached

    mixed ModuleCore::isCached($template, $cache_id, $compile_id)





* Visibility: **public**
* Source: [classes/module/Module.php line 2378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2378)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-isEnabled"></a>isEnabled

    mixed ModuleCore::isEnabled($module_name)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 2214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2214)


#### Arguments
* $module_name **mixed**



### <a name="method-isEnabledForShopContext"></a>isEnabledForShopContext

    mixed ModuleCore::isEnabledForShopContext()





* Visibility: **public**
* Source: [classes/module/Module.php line 2203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2203)




### <a name="method-isHookableOn"></a>isHookableOn

    boolean ModuleCore::isHookableOn(string $hook_name)

Check if the module is transplantable on the hook in parameter



* Visibility: **public**
* Source: [classes/module/Module.php line 2490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2490)


#### Arguments
* $hook_name **string**



### <a name="method-isInstalled"></a>isInstalled

    mixed ModuleCore::isInstalled($module_name)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 2193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2193)


#### Arguments
* $module_name **mixed**



### <a name="method-isModuleTrusted"></a>isModuleTrusted

    integer ModuleCore::isModuleTrusted($module_name)

Return if the module is provided by addons.prestashop.com or not



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1684](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1684)


#### Arguments
* $module_name **mixed**



### <a name="method-isRegisteredInHook"></a>isRegisteredInHook

    mixed ModuleCore::isRegisteredInHook($hook)





* Visibility: **public**
* Source: [classes/module/Module.php line 2228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2228)


#### Arguments
* $hook **mixed**



### <a name="method-l"></a>l

    string ModuleCore::l(string $string, boolean|string $specific)

Get translation for a given module text

Note: $specific parameter is mandatory for library files.
Otherwise, translation key will not match for Module library
when module is loaded with eval() Module::getModulesOnDisk()

* Visibility: **public**
* Source: [classes/module/Module.php line 1964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1964)


#### Arguments
* $string **string** - String to translate
* $specific **boolean|string** - filename to use in translation key



### <a name="method-loadUpgradeVersionList"></a>loadUpgradeVersionList

    boolean ModuleCore::loadUpgradeVersionList($module_name, $module_version, $registered_version)

Load the available list of upgrade of a specified module
with an associated version



* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L573)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**
* $registered_version **mixed**



### <a name="method-needUpgrade"></a>needUpgrade

    boolean ModuleCore::needUpgrade($module)

Check if a module need to be upgraded.

This method modify the module_cache adding an upgrade list file

* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L550)


#### Arguments
* $module **mixed**



### <a name="method-preCall"></a>preCall

    mixed ModuleCore::preCall($module_name)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1883)


#### Arguments
* $module_name **mixed**



### <a name="method-processDeferedClearCache"></a>processDeferedClearCache

    mixed ModuleCore::processDeferedClearCache()

Clear the caches stored in $_defered_clearCache



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L215)




### <a name="method-processDeferedFuncCall"></a>processDeferedFuncCall

    mixed ModuleCore::processDeferedFuncCall()





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L201)




### <a name="method-registerExceptions"></a>registerExceptions

    boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shop_list)

Add exceptions for module->Hook



* Visibility: **public**
* Source: [classes/module/Module.php line 1001](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1001)


#### Arguments
* $id_hook **integer** - Hook id
* $excepts **array** - List of file name
* $shop_list **array** - List of shop



### <a name="method-registerHook"></a>registerHook

    boolean ModuleCore::registerHook(string $hook_name, array $shop_list)

Connect module to a hook



* Visibility: **public**
* Source: [classes/module/Module.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L854)


#### Arguments
* $hook_name **string** - Hook name
* $shop_list **array** - List of shop linked to the hook (if null, link hook to all shops)



### <a name="method-removeOverride"></a>removeOverride

    boolean ModuleCore::removeOverride(string $classname)

Remove all methods in a module override from the override class



* Visibility: **public**
* Source: [classes/module/Module.php line 2912](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2912)


#### Arguments
* $classname **string**



### <a name="method-resetCurrentSubTemplate"></a>resetCurrentSubTemplate

    mixed ModuleCore::resetCurrentSubTemplate($template, $cache_id, $compile_id)





* Visibility: **protected**
* Source: [classes/module/Module.php line 2341](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2341)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-runUpgradeModule"></a>runUpgradeModule

    array ModuleCore::runUpgradeModule()

Run the upgrade for a given module name and version



* Visibility: **public**
* Source: [classes/module/Module.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L481)




### <a name="method-setBatchMode"></a>setBatchMode

    mixed ModuleCore::setBatchMode(boolean $value)

Set the flag to indicate we are doing an import



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L188)


#### Arguments
* $value **boolean**



### <a name="method-setUpgradeMessage"></a>setUpgradeMessage

    mixed ModuleCore::setUpgradeMessage($upgrade_detail)

Set errors, warning or success message of a module upgrade



* Visibility: **protected**
* Source: [classes/module/Module.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L422)


#### Arguments
* $upgrade_detail **mixed**



### <a name="method-uninstall"></a>uninstall

    boolean ModuleCore::uninstall()

Delete module from datable



* Visibility: **public**
* Source: [classes/module/Module.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L638)




### <a name="method-uninstallOverrides"></a>uninstallOverrides

    boolean ModuleCore::uninstallOverrides()

Uninstall overrides files for the module



* Visibility: **public**
* Source: [classes/module/Module.php line 2740](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L2740)




### <a name="method-unregisterExceptions"></a>unregisterExceptions

    boolean ModuleCore::unregisterExceptions($hook_id, array $shop_list)

Unregister exceptions linked to module



* Visibility: **public**
* Source: [classes/module/Module.php line 985](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L985)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-unregisterHook"></a>unregisterHook

    boolean ModuleCore::unregisterHook($hook_id, array $shop_list)

Unregister module from hook



* Visibility: **public**
* Source: [classes/module/Module.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L948)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-updateModuleTranslations"></a>updateModuleTranslations

    mixed ModuleCore::updateModuleTranslations()





* Visibility: **public**
* Source: [classes/module/Module.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L412)




### <a name="method-updatePosition"></a>updatePosition

    mixed ModuleCore::updatePosition($id_hook, $way, $position)





* Visibility: **public**
* Source: [classes/module/Module.php line 1980](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1980)


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**



### <a name="method-updateTranslationsAfterInstall"></a>updateTranslationsAfterInstall

    mixed ModuleCore::updateTranslationsAfterInstall($update)





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L407)


#### Arguments
* $update **mixed**



### <a name="method-upgradeModuleVersion"></a>upgradeModuleVersion

    boolean ModuleCore::upgradeModuleVersion($name, $version)

Upgrade the registered version to a new one



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L535)


#### Arguments
* $name **mixed**
* $version **mixed**



### <a name="method-useTooMuchMemory"></a>useTooMuchMemory

    mixed ModuleCore::useTooMuchMemory()





* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 1230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#L1230)



