ModuleCore
===============






* Class name: ModuleCore
* Namespace: 
* This is an **abstract** class



Constants
----------


### CACHE_FILE_MODULES_LIST

    const CACHE_FILE_MODULES_LIST = '/config/xml/modules_list.xml'





### CACHE_FILE_TAB_MODULES_LIST

    const CACHE_FILE_TAB_MODULES_LIST = '/config/xml/tab_modules_list.xml'





### CACHE_FILE_ALL_COUNTRY_MODULES_LIST

    const CACHE_FILE_ALL_COUNTRY_MODULES_LIST = '/config/xml/modules_native_addons.xml'





### CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST

    const CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST = '/config/xml/default_country_modules_list.xml'





### CACHE_FILE_CUSTOMER_MODULES_LIST

    const CACHE_FILE_CUSTOMER_MODULES_LIST = '/config/xml/customer_modules_list.xml'





### CACHE_FILE_MUST_HAVE_MODULES_LIST

    const CACHE_FILE_MUST_HAVE_MODULES_LIST = '/config/xml/must_have_modules_list.xml'





### CACHE_FILE_TRUSTED_MODULES_LIST

    const CACHE_FILE_TRUSTED_MODULES_LIST = '/config/xml/trusted_modules_list.xml'





### CACHE_FILE_UNTRUSTED_MODULES_LIST

    const CACHE_FILE_UNTRUSTED_MODULES_LIST = '/config/xml/untrusted_modules_list.xml'





Properties
----------


### $id

    public integer $id = null





* Visibility: **public**


### $version

    public float $version





* Visibility: **public**


### $database_version

    public mixed $database_version





* Visibility: **public**


### $registered_version

    public string $registered_version





* Visibility: **public**


### $ps_versions_compliancy

    public array $ps_versions_compliancy = array()





* Visibility: **public**


### $dependencies

    public array $dependencies = array()





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $displayName

    public string $displayName





* Visibility: **public**


### $description

    public string $description





* Visibility: **public**


### $author

    public string $author





* Visibility: **public**


### $author_uri

    public string $author_uri = ''





* Visibility: **public**


### $module_key

    public string $module_key = ''





* Visibility: **public**


### $description_full

    public mixed $description_full





* Visibility: **public**


### $additional_description

    public mixed $additional_description





* Visibility: **public**


### $compatibility

    public mixed $compatibility





* Visibility: **public**


### $nb_rates

    public mixed $nb_rates





* Visibility: **public**


### $avg_rate

    public mixed $avg_rate





* Visibility: **public**


### $badges

    public mixed $badges





* Visibility: **public**


### $need_instance

    public integer $need_instance = 1





* Visibility: **public**


### $tab

    public string $tab = null





* Visibility: **public**


### $active

    public boolean $active = false





* Visibility: **public**


### $trusted

    public boolean $trusted = false





* Visibility: **public**


### $warning

    public string $warning





* Visibility: **public**


### $enable_device

    public mixed $enable_device = 7





* Visibility: **public**


### $limited_countries

    public array $limited_countries = array()





* Visibility: **public**


### $controllers

    public array $controllers = array()





* Visibility: **public**


### $classInModule

    public array $classInModule = array()





* Visibility: **public**
* This property is **static**.


### $_lang

    protected array $_lang = array()





* Visibility: **protected**


### $_path

    protected string $_path = null





* Visibility: **protected**


### $local_path

    protected string $local_path = null





* Visibility: **protected**


### $_errors

    protected array $_errors = array()





* Visibility: **protected**


### $_confirmations

    protected array $_confirmations = array()





* Visibility: **protected**


### $table

    protected string $table = 'module'





* Visibility: **protected**


### $identifier

    protected string $identifier = 'id_module'





* Visibility: **protected**


### $modules_cache

    protected array $modules_cache





* Visibility: **protected**
* This property is **static**.


### $_INSTANCE

    protected array $_INSTANCE = array()





* Visibility: **protected**
* This property is **static**.


### $_generate_config_xml_mode

    protected boolean $_generate_config_xml_mode = false





* Visibility: **protected**
* This property is **static**.


### $l_cache

    protected array $l_cache = array()





* Visibility: **protected**
* This property is **static**.


### $cache_permissions

    protected array $cache_permissions = array()





* Visibility: **protected**
* This property is **static**.


### $context

    protected \Context $context





* Visibility: **protected**


### $smarty

    protected \Smarty_Data $smarty





* Visibility: **protected**


### $current_subtemplate

    protected \Smarty_Internal_Template $current_subtemplate = null





* Visibility: **protected**


### $update_translations_after_install

    protected mixed $update_translations_after_install = true





* Visibility: **protected**
* This property is **static**.


### $_batch_mode

    protected mixed $_batch_mode = false





* Visibility: **protected**
* This property is **static**.


### $_defered_clearCache

    protected mixed $_defered_clearCache = array()





* Visibility: **protected**
* This property is **static**.


### $_defered_func_call

    protected mixed $_defered_func_call = array()





* Visibility: **protected**
* This property is **static**.


### $allow_push

    public boolean $allow_push





* Visibility: **public**


### $push_time_limit

    public mixed $push_time_limit = 180





* Visibility: **public**


### $_log_modules_perfs

    public boolean $_log_modules_perfs = null





* Visibility: **public**
* This property is **static**.


### $_log_modules_perfs_session

    public boolean $_log_modules_perfs_session = null





* Visibility: **public**
* This property is **static**.


### $hosted_modules_blacklist

    public mixed $hosted_modules_blacklist = array('autoupgrade')





* Visibility: **public**
* This property is **static**.


Methods
-------


### setBatchMode

    mixed ModuleCore::setBatchMode(boolean $value)

Set the flag to indicate we are doing an import



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **boolean**



### getBatchMode

    boolean ModuleCore::getBatchMode()





* Visibility: **public**
* This method is **static**.




### processDeferedFuncCall

    mixed ModuleCore::processDeferedFuncCall()





* Visibility: **public**
* This method is **static**.




### processDeferedClearCache

    mixed ModuleCore::processDeferedClearCache()

Clear the caches stored in $_defered_clearCache



* Visibility: **public**
* This method is **static**.




### __construct

    mixed ModuleCore::__construct(string $name, \Context $context)

Constructor



* Visibility: **public**


#### Arguments
* $name **string** - &lt;p&gt;Module unique name&lt;/p&gt;
* $context **Context**



### install

    mixed ModuleCore::install()

Insert module into datable



* Visibility: **public**




### checkCompliancy

    mixed ModuleCore::checkCompliancy()





* Visibility: **public**




### updateTranslationsAfterInstall

    mixed ModuleCore::updateTranslationsAfterInstall($update)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $update **mixed**



### updateModuleTranslations

    mixed ModuleCore::updateModuleTranslations()





* Visibility: **public**




### setUpgradeMessage

    mixed ModuleCore::setUpgradeMessage($upgrade_detail)

Set errors, warning or success message of a module upgrade



* Visibility: **protected**


#### Arguments
* $upgrade_detail **mixed**



### initUpgradeModule

    boolean ModuleCore::initUpgradeModule($module)

Init the upgrade module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module **mixed**



### runUpgradeModule

    array ModuleCore::runUpgradeModule()

Run the upgrade for a given module name and version



* Visibility: **public**




### upgradeModuleVersion

    boolean ModuleCore::upgradeModuleVersion($name, $version)

Upgrade the registered version to a new one



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**
* $version **mixed**



### needUpgrade

    boolean ModuleCore::needUpgrade($module)

Check if a module need to be upgraded.

This method modify the module_cache adding an upgrade list file

* Visibility: **public**
* This method is **static**.


#### Arguments
* $module **mixed**



### loadUpgradeVersionList

    boolean ModuleCore::loadUpgradeVersionList($module_name, $module_version, $registered_version)

Load the available list of upgrade of a specified module
with an associated version



* Visibility: **protected**
* This method is **static**.


#### Arguments
* $module_name **mixed**
* $module_version **mixed**
* $registered_version **mixed**



### getUpgradeStatus

    boolean ModuleCore::getUpgradeStatus($module_name)

Return the status of the upgraded module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **mixed**



### uninstall

    boolean ModuleCore::uninstall()

Delete module from datable



* Visibility: **public**




### enableByName

    true ModuleCore::enableByName(array|string $name)

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **array|string**



### enable

    mixed ModuleCore::enable(boolean $force_all)

Activate current module.



* Visibility: **public**


#### Arguments
* $force_all **boolean** - &lt;p&gt;If true, enable module for all shop&lt;/p&gt;



### enableDevice

    mixed ModuleCore::enableDevice($device)





* Visibility: **public**


#### Arguments
* $device **mixed**



### disableDevice

    mixed ModuleCore::disableDevice($device)





* Visibility: **public**


#### Arguments
* $device **mixed**



### disableByName

    true ModuleCore::disableByName(array|string $name)

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **array|string**



### disable

    mixed ModuleCore::disable(boolean $force_all)

Desactivate current module.



* Visibility: **public**


#### Arguments
* $force_all **boolean** - &lt;p&gt;If true, disable module for all shop&lt;/p&gt;



### displayFlags

    mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)

Display flags in forms for translations



* Visibility: **public**


#### Arguments
* $languages **array** - &lt;p&gt;All languages available&lt;/p&gt;
* $default_language **integer** - &lt;p&gt;Default language id&lt;/p&gt;
* $ids **string** - &lt;p&gt;Multilingual div ids in form&lt;/p&gt;
* $id **string** - &lt;p&gt;Current div id]&lt;/p&gt;
* $return **boolean** - &lt;p&gt;define the return way : false for a display, true for a return&lt;/p&gt;
* $use_vars_instead_of_ids **boolean** - &lt;p&gt;use an js vars instead of ids seperate by &quot;¤&quot;&lt;/p&gt;



### registerHook

    boolean ModuleCore::registerHook(string $hook_name, array $shop_list)

Connect module to a hook



* Visibility: **public**


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook name&lt;/p&gt;
* $shop_list **array** - &lt;p&gt;List of shop linked to the hook (if null, link hook to all shops)&lt;/p&gt;



### unregisterHook

    boolean ModuleCore::unregisterHook($hook_id, array $shop_list)

Unregister module from hook



* Visibility: **public**


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - &lt;p&gt;List of shop&lt;/p&gt;



### unregisterExceptions

    boolean ModuleCore::unregisterExceptions($hook_id, array $shop_list)

Unregister exceptions linked to module



* Visibility: **public**


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - &lt;p&gt;List of shop&lt;/p&gt;



### registerExceptions

    boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shop_list)

Add exceptions for module->Hook



* Visibility: **public**


#### Arguments
* $id_hook **integer** - &lt;p&gt;Hook id&lt;/p&gt;
* $excepts **array** - &lt;p&gt;List of file name&lt;/p&gt;
* $shop_list **array** - &lt;p&gt;List of shop&lt;/p&gt;



### editExceptions

    boolean ModuleCore::editExceptions($id_hook, array $excepts)

Edit exceptions for module->Hook



* Visibility: **public**


#### Arguments
* $id_hook **mixed**
* $excepts **array** - &lt;p&gt;List of shopID and file name&lt;/p&gt;



### getModuleNameFromClass

    boolean|string ModuleCore::getModuleNameFromClass(mixed $current_class)

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $current_class **mixed** - &lt;p&gt;the&lt;/p&gt;



### getInstanceByName

    \Module ModuleCore::getInstanceByName(string $module_name)

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **string** - &lt;p&gt;Module name&lt;/p&gt;



### coreLoadModule

    mixed ModuleCore::coreLoadModule($module_name)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $module_name **mixed**



### getInstanceById

    \Module ModuleCore::getInstanceById(integer $id_module)

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **integer** - &lt;p&gt;Module ID&lt;/p&gt;



### configXmlStringFormat

    mixed ModuleCore::configXmlStringFormat($string)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**



### getModuleName

    mixed ModuleCore::getModuleName($module)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $module **mixed**



### useTooMuchMemory

    mixed ModuleCore::useTooMuchMemory()





* Visibility: **protected**
* This method is **static**.




### getModulesOnDisk

    array ModuleCore::getModulesOnDisk(boolean $use_config, $logged_on_addons, $id_employee)

Return available modules



* Visibility: **public**
* This method is **static**.


#### Arguments
* $use_config **boolean** - &lt;p&gt;in order to use config.xml file in module dir&lt;/p&gt;
* $logged_on_addons **mixed**
* $id_employee **mixed**



### getModulesDirOnDisk

    array ModuleCore::getModulesDirOnDisk()

Return modules directory list



* Visibility: **public**
* This method is **static**.




### getNonNativeModuleList

    array ModuleCore::getNonNativeModuleList()

Return non native module



* Visibility: **public**
* This method is **static**.




### getNativeModuleList

    mixed ModuleCore::getNativeModuleList()





* Visibility: **public**
* This method is **static**.




### getModulesInstalled

    array ModuleCore::getModulesInstalled(integer $position)

Return installed modules



* Visibility: **public**
* This method is **static**.


#### Arguments
* $position **integer** - &lt;p&gt;Take only positionnables modules&lt;/p&gt;



### isModuleTrusted

    integer ModuleCore::isModuleTrusted($module_name)

Return if the module is provided by addons.prestashop.com or not



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **mixed**



### generateTrustedXml

    mixed ModuleCore::generateTrustedXml()

Generate XML files for trusted and untrusted modules



* Visibility: **public**
* This method is **static**.




### checkModuleFromAddonsApi

    boolean ModuleCore::checkModuleFromAddonsApi($module_name)

Create the Addons API call from the module name only



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **mixed**



### hookExec

    string ModuleCore::hookExec(string $hook_name, array $hook_args, $id_module)

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook Name&lt;/p&gt;
* $hook_args **array** - &lt;p&gt;Parameters for the functions&lt;/p&gt;
* $id_module **mixed**



### hookExecPayment

    string ModuleCore::hookExecPayment()





* Visibility: **public**
* This method is **static**.




### preCall

    mixed ModuleCore::preCall($module_name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **mixed**



### getPaypalIgnore

    mixed ModuleCore::getPaypalIgnore()





* Visibility: **public**
* This method is **static**.




### getPaymentModules

    array ModuleCore::getPaymentModules()

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.




### findTranslation

    mixed ModuleCore::findTranslation($name, $string, $source)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**
* $string **mixed**
* $source **mixed**



### l

    string ModuleCore::l(string $string, boolean|string $specific)

Get translation for a given module text

Note: $specific parameter is mandatory for library files.
Otherwise, translation key will not match for Module library
when module is loaded with eval() Module::getModulesOnDisk()

* Visibility: **public**


#### Arguments
* $string **string** - &lt;p&gt;String to translate&lt;/p&gt;
* $specific **boolean|string** - &lt;p&gt;filename to use in translation key&lt;/p&gt;



### updatePosition

    mixed ModuleCore::updatePosition($id_hook, $way, $position)





* Visibility: **public**


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**



### cleanPositions

    mixed ModuleCore::cleanPositions($id_hook, $shop_list)





* Visibility: **public**


#### Arguments
* $id_hook **mixed**
* $shop_list **mixed**



### displayError

    string ModuleCore::displayError(string|array $error)

Helper displaying error message(s)



* Visibility: **public**


#### Arguments
* $error **string|array**



### displayWarning

    string ModuleCore::displayWarning($warning)

Helper displaying warning message(s)



* Visibility: **public**


#### Arguments
* $warning **mixed**



### displayConfirmation

    mixed ModuleCore::displayConfirmation($string)





* Visibility: **public**


#### Arguments
* $string **mixed**



### getExceptionsStatic

    mixed ModuleCore::getExceptionsStatic($id_module, $id_hook, $dispatch)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **mixed**
* $id_hook **mixed**
* $dispatch **mixed**



### getExceptions

    mixed ModuleCore::getExceptions($id_hook, $dispatch)





* Visibility: **public**


#### Arguments
* $id_hook **mixed**
* $dispatch **mixed**



### isInstalled

    mixed ModuleCore::isInstalled($module_name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **mixed**



### isEnabledForShopContext

    mixed ModuleCore::isEnabledForShopContext()





* Visibility: **public**




### isEnabled

    mixed ModuleCore::isEnabled($module_name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $module_name **mixed**



### isRegisteredInHook

    mixed ModuleCore::isRegisteredInHook($hook)





* Visibility: **public**


#### Arguments
* $hook **mixed**



### _isTemplateOverloadedStatic

    mixed ModuleCore::_isTemplateOverloadedStatic($module_name, $template)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $module_name **mixed**
* $template **mixed**



### _isTemplateOverloaded

    mixed ModuleCore::_isTemplateOverloaded($template)





* Visibility: **protected**


#### Arguments
* $template **mixed**



### getCacheId

    mixed ModuleCore::getCacheId($name)





* Visibility: **protected**


#### Arguments
* $name **mixed**



### display

    mixed ModuleCore::display($file, $template, $cache_id, $compile_id)





* Visibility: **public**


#### Arguments
* $file **mixed**
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### getCurrentSubTemplate

    \Smarty_Internal_Template ModuleCore::getCurrentSubTemplate(string $template, string|null $cache_id, string|null $compile_id)





* Visibility: **protected**


#### Arguments
* $template **string**
* $cache_id **string|null**
* $compile_id **string|null**



### resetCurrentSubTemplate

    mixed ModuleCore::resetCurrentSubTemplate($template, $cache_id, $compile_id)





* Visibility: **protected**


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### getTemplatePath

    string ModuleCore::getTemplatePath(string $template)

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**


#### Arguments
* $template **string**



### _getApplicableTemplateDir

    mixed ModuleCore::_getApplicableTemplateDir($template)





* Visibility: **protected**


#### Arguments
* $template **mixed**



### isCached

    mixed ModuleCore::isCached($template, $cache_id, $compile_id)





* Visibility: **public**


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### _clearCache

    mixed ModuleCore::_clearCache($template, $cache_id, $compile_id)





* Visibility: **protected**


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### _deferedClearCache

    mixed ModuleCore::_deferedClearCache($template_path, $cache_id, $compile_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $template_path **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### _generateConfigXml

    mixed ModuleCore::_generateConfigXml()





* Visibility: **protected**




### isHookableOn

    boolean ModuleCore::isHookableOn(string $hook_name)

Check if the module is transplantable on the hook in parameter



* Visibility: **public**


#### Arguments
* $hook_name **string**



### getPermission

    boolean ModuleCore::getPermission(array $variable, object $employee)

Check employee permission for module



* Visibility: **public**


#### Arguments
* $variable **array** - &lt;p&gt;(action)&lt;/p&gt;
* $employee **object**



### getPermissionStatic

    boolean ModuleCore::getPermissionStatic(integer $id_module, array $variable, object $employee)

Check employee permission for module (static method)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **integer**
* $variable **array** - &lt;p&gt;(action)&lt;/p&gt;
* $employee **object**



### getAuthorizedModules

    array|null ModuleCore::getAuthorizedModules(integer $group_id)

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.


#### Arguments
* $group_id **integer**



### getModuleIdByName

    integer ModuleCore::getModuleIdByName(string $name)

Get ID module by name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string**



### getErrors

    array ModuleCore::getErrors()

Get module errors



* Visibility: **public**




### getConfirmations

    array ModuleCore::getConfirmations()

Get module messages confirmation



* Visibility: **public**




### getLocalPath

    string ModuleCore::getLocalPath()

Get local path for module



* Visibility: **public**




### getPathUri

    string ModuleCore::getPathUri()

Get uri path for module



* Visibility: **public**




### getPosition

    mixed ModuleCore::getPosition($id_hook)





* Visibility: **public**


#### Arguments
* $id_hook **mixed**



### adminDisplayWarning

    mixed ModuleCore::adminDisplayWarning(string $msg)

add a warning message to display at the top of the admin page



* Visibility: **public**


#### Arguments
* $msg **string**



### adminDisplayInformation

    mixed ModuleCore::adminDisplayInformation(string $msg)

add a info message to display at the top of the admin page



* Visibility: **protected**


#### Arguments
* $msg **string**



### installControllers

    boolean ModuleCore::installControllers()

Install module's controllers using public property $controllers



* Visibility: **private**




### installOverrides

    boolean ModuleCore::installOverrides()

Install overrides files for the module



* Visibility: **public**




### uninstallOverrides

    boolean ModuleCore::uninstallOverrides()

Uninstall overrides files for the module



* Visibility: **public**




### addOverride

    boolean ModuleCore::addOverride(string $classname)

Add all methods in a module override to the override class



* Visibility: **public**


#### Arguments
* $classname **string**



### removeOverride

    boolean ModuleCore::removeOverride(string $classname)

Remove all methods in a module override from the override class



* Visibility: **public**


#### Arguments
* $classname **string**



### getPossibleHooksList

    array ModuleCore::getPossibleHooksList()

Return the hooks list where this module can be hooked.



* Visibility: **public**



