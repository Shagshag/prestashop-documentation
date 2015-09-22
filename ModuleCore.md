ModuleCore
===============






* Class name: ModuleCore
* Namespace: 
* This is an **abstract** class

* This class is defined in [classes/module/Module.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#27)



Constants
----------


### CACHE_FILE_MODULES_LIST

    const CACHE_FILE_MODULES_LIST = '/config/xml/modules_list.xml'



* This constant is defined in [classes/module/Module.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#167)


### CACHE_FILE_TAB_MODULES_LIST

    const CACHE_FILE_TAB_MODULES_LIST = '/config/xml/tab_modules_list.xml'



* This constant is defined in [classes/module/Module.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#169)


### CACHE_FILE_ALL_COUNTRY_MODULES_LIST

    const CACHE_FILE_ALL_COUNTRY_MODULES_LIST = '/config/xml/modules_native_addons.xml'



* This constant is defined in [classes/module/Module.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#171)


### CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST

    const CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST = '/config/xml/default_country_modules_list.xml'



* This constant is defined in [classes/module/Module.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#172)


### CACHE_FILE_CUSTOMER_MODULES_LIST

    const CACHE_FILE_CUSTOMER_MODULES_LIST = '/config/xml/customer_modules_list.xml'



* This constant is defined in [classes/module/Module.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#174)


### CACHE_FILE_MUST_HAVE_MODULES_LIST

    const CACHE_FILE_MUST_HAVE_MODULES_LIST = '/config/xml/must_have_modules_list.xml'



* This constant is defined in [classes/module/Module.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#176)


### CACHE_FILE_TRUSTED_MODULES_LIST

    const CACHE_FILE_TRUSTED_MODULES_LIST = '/config/xml/trusted_modules_list.xml'



* This constant is defined in [classes/module/Module.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#178)


### CACHE_FILE_UNTRUSTED_MODULES_LIST

    const CACHE_FILE_UNTRUSTED_MODULES_LIST = '/config/xml/untrusted_modules_list.xml'



* This constant is defined in [classes/module/Module.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#179)


Properties
----------


### $id

    public integer $id = null





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#30)


### $version

    public float $version





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#33)


### $database_version

    public mixed $database_version





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#34)


### $registered_version

    public string $registered_version





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#40)


### $ps_versions_compliancy

    public array $ps_versions_compliancy = array()





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#43)


### $dependencies

    public array $dependencies = array()





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#46)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#49)


### $displayName

    public string $displayName





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#52)


### $description

    public string $description





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#55)


### $author

    public string $author





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#58)


### $author_uri

    public string $author_uri = ''





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#61)


### $module_key

    public string $module_key = ''





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#64)


### $description_full

    public mixed $description_full





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#66)


### $additional_description

    public mixed $additional_description





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#68)


### $compatibility

    public mixed $compatibility





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#70)


### $nb_rates

    public mixed $nb_rates





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#72)


### $avg_rate

    public mixed $avg_rate





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#74)


### $badges

    public mixed $badges





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#76)


### $need_instance

    public integer $need_instance = 1





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#79)


### $tab

    public string $tab = null





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#82)


### $active

    public boolean $active = false





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#85)


### $trusted

    public boolean $trusted = false





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#88)


### $warning

    public string $warning





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#91)


### $enable_device

    public mixed $enable_device = 7





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#93)


### $limited_countries

    public array $limited_countries = array()





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#96)


### $controllers

    public array $controllers = array()





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#99)


### $classInModule

    public array $classInModule = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#102)


### $_lang

    protected array $_lang = array()





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#105)


### $_path

    protected string $_path = null





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#108)


### $local_path

    protected string $local_path = null





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#113)


### $_errors

    protected array $_errors = array()





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#116)


### $_confirmations

    protected array $_confirmations = array()





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#119)


### $table

    protected string $table = 'module'





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#122)


### $identifier

    protected string $identifier = 'id_module'





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#125)


### $modules_cache

    protected array $modules_cache





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#128)


### $_INSTANCE

    protected array $_INSTANCE = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#131)


### $_generate_config_xml_mode

    protected boolean $_generate_config_xml_mode = false





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#134)


### $l_cache

    protected array $l_cache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#137)


### $cache_permissions

    protected array $cache_permissions = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#140)


### $context

    protected \Context $context





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#143)


### $smarty

    protected \Smarty_Data $smarty





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#146)


### $current_subtemplate

    protected \Smarty_Internal_Template $current_subtemplate = null





* Visibility: **protected**
* This property is defined in [classes/module/Module.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#149)


### $update_translations_after_install

    protected mixed $update_translations_after_install = true





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#151)


### $_batch_mode

    protected mixed $_batch_mode = false





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#153)


### $_defered_clearCache

    protected mixed $_defered_clearCache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#154)


### $_defered_func_call

    protected mixed $_defered_func_call = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#155)


### $allow_push

    public boolean $allow_push





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#158)


### $push_time_limit

    public mixed $push_time_limit = 180





* Visibility: **public**
* This property is defined in [classes/module/Module.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#160)


### $_log_modules_perfs

    public boolean $_log_modules_perfs = null





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#163)


### $_log_modules_perfs_session

    public boolean $_log_modules_perfs_session = null





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#165)


### $hosted_modules_blacklist

    public mixed $hosted_modules_blacklist = array('autoupgrade')





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/module/Module.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#181)


Methods
-------


### setBatchMode

    mixed ModuleCore::setBatchMode(boolean $value)

Set the flag to indicate we are doing an import



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#188)


#### Arguments
* $value **boolean**



### getBatchMode

    boolean ModuleCore::getBatchMode()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#196)




### processDeferedFuncCall

    mixed ModuleCore::processDeferedFuncCall()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#201)




### processDeferedClearCache

    mixed ModuleCore::processDeferedClearCache()

Clear the caches stored in $_defered_clearCache



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#215)




### __construct

    mixed ModuleCore::__construct(string $name, \Context $context)

Constructor



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#232)


#### Arguments
* $name **string** - &lt;p&gt;Module unique name&lt;/p&gt;
* $context **[Context](ContextCore)**



### install

    mixed ModuleCore::install()

Insert module into datable



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#306)




### checkCompliancy

    mixed ModuleCore::checkCompliancy()





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#398)




### updateTranslationsAfterInstall

    mixed ModuleCore::updateTranslationsAfterInstall($update)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#407)


#### Arguments
* $update **mixed**



### updateModuleTranslations

    mixed ModuleCore::updateModuleTranslations()





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#412)




### setUpgradeMessage

    mixed ModuleCore::setUpgradeMessage($upgrade_detail)

Set errors, warning or success message of a module upgrade



* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#422)


#### Arguments
* $upgrade_detail **mixed**



### initUpgradeModule

    boolean ModuleCore::initUpgradeModule($module)

Init the upgrade module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#452)


#### Arguments
* $module **mixed**



### runUpgradeModule

    array ModuleCore::runUpgradeModule()

Run the upgrade for a given module name and version



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#481)




### upgradeModuleVersion

    boolean ModuleCore::upgradeModuleVersion($name, $version)

Upgrade the registered version to a new one



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#535)


#### Arguments
* $name **mixed**
* $version **mixed**



### needUpgrade

    boolean ModuleCore::needUpgrade($module)

Check if a module need to be upgraded.

This method modify the module_cache adding an upgrade list file

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#550)


#### Arguments
* $module **mixed**



### loadUpgradeVersionList

    boolean ModuleCore::loadUpgradeVersionList($module_name, $module_version, $registered_version)

Load the available list of upgrade of a specified module
with an associated version



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#573)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**
* $registered_version **mixed**



### getUpgradeStatus

    boolean ModuleCore::getUpgradeStatus($module_name)

Return the status of the upgraded module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#627)


#### Arguments
* $module_name **mixed**



### uninstall

    boolean ModuleCore::uninstall()

Delete module from datable



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#638)




### enableByName

    true ModuleCore::enableByName(array|string $name)

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#696)


#### Arguments
* $name **array|string**



### enable

    mixed ModuleCore::enable(boolean $force_all)

Activate current module.



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 717](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#717)


#### Arguments
* $force_all **boolean** - &lt;p&gt;If true, enable module for all shop&lt;/p&gt;



### enableDevice

    mixed ModuleCore::enableDevice($device)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 749](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#749)


#### Arguments
* $device **mixed**



### disableDevice

    mixed ModuleCore::disableDevice($device)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#761)


#### Arguments
* $device **mixed**



### disableByName

    true ModuleCore::disableByName(array|string $name)

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#781)


#### Arguments
* $name **array|string**



### disable

    mixed ModuleCore::disable(boolean $force_all)

Desactivate current module.



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#802)


#### Arguments
* $force_all **boolean** - &lt;p&gt;If true, disable module for all shop&lt;/p&gt;



### displayFlags

    mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)

Display flags in forms for translations



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#820)


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
* This method is defined in [classes/module/Module.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#854)


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook name&lt;/p&gt;
* $shop_list **array** - &lt;p&gt;List of shop linked to the hook (if null, link hook to all shops)&lt;/p&gt;



### unregisterHook

    boolean ModuleCore::unregisterHook($hook_id, array $shop_list)

Unregister module from hook



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#948)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - &lt;p&gt;List of shop&lt;/p&gt;



### unregisterExceptions

    boolean ModuleCore::unregisterExceptions($hook_id, array $shop_list)

Unregister exceptions linked to module



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 985](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#985)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - &lt;p&gt;List of shop&lt;/p&gt;



### registerExceptions

    boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shop_list)

Add exceptions for module->Hook



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 1001](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1001)


#### Arguments
* $id_hook **integer** - &lt;p&gt;Hook id&lt;/p&gt;
* $excepts **array** - &lt;p&gt;List of file name&lt;/p&gt;
* $shop_list **array** - &lt;p&gt;List of shop&lt;/p&gt;



### editExceptions

    boolean ModuleCore::editExceptions($id_hook, array $excepts)

Edit exceptions for module->Hook



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 1036](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1036)


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
* This method is defined in [classes/module/Module.php line 1057](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1057)


#### Arguments
* $current_class **mixed** - &lt;p&gt;the&lt;/p&gt;



### getInstanceByName

    \Module ModuleCore::getInstanceByName(string $module_name)

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1095](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1095)


#### Arguments
* $module_name **string** - &lt;p&gt;Module name&lt;/p&gt;



### coreLoadModule

    mixed ModuleCore::coreLoadModule($module_name)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1113)


#### Arguments
* $module_name **mixed**



### getInstanceById

    \Module ModuleCore::getInstanceById(integer $id_module)

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1164)


#### Arguments
* $id_module **integer** - &lt;p&gt;Module ID&lt;/p&gt;



### configXmlStringFormat

    mixed ModuleCore::configXmlStringFormat($string)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1185)


#### Arguments
* $string **mixed**



### getModuleName

    mixed ModuleCore::getModuleName($module)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1191)


#### Arguments
* $module **mixed**



### useTooMuchMemory

    mixed ModuleCore::useTooMuchMemory()





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1230)




### getModulesOnDisk

    array ModuleCore::getModulesOnDisk(boolean $use_config, $logged_on_addons, $id_employee)

Return available modules



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1251)


#### Arguments
* $use_config **boolean** - &lt;p&gt;in order to use config.xml file in module dir&lt;/p&gt;
* $logged_on_addons **mixed**
* $id_employee **mixed**



### getModulesDirOnDisk

    array ModuleCore::getModulesDirOnDisk()

Return modules directory list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1578](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1578)




### getNonNativeModuleList

    array ModuleCore::getNonNativeModuleList()

Return non native module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1603)




### getNativeModuleList

    mixed ModuleCore::getNativeModuleList()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1630](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1630)




### getModulesInstalled

    array ModuleCore::getModulesInstalled(integer $position)

Return installed modules



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1665](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1665)


#### Arguments
* $position **integer** - &lt;p&gt;Take only positionnables modules&lt;/p&gt;



### isModuleTrusted

    integer ModuleCore::isModuleTrusted($module_name)

Return if the module is provided by addons.prestashop.com or not



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1684](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1684)


#### Arguments
* $module_name **mixed**



### generateTrustedXml

    mixed ModuleCore::generateTrustedXml()

Generate XML files for trusted and untrusted modules



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1752](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1752)




### checkModuleFromAddonsApi

    boolean ModuleCore::checkModuleFromAddonsApi($module_name)

Create the Addons API call from the module name only



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1840](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1840)


#### Arguments
* $module_name **mixed**



### hookExec

    string ModuleCore::hookExec(string $hook_name, array $hook_args, $id_module)

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1866](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1866)


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook Name&lt;/p&gt;
* $hook_args **array** - &lt;p&gt;Parameters for the functions&lt;/p&gt;
* $id_module **mixed**



### hookExecPayment

    string ModuleCore::hookExecPayment()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1877](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1877)




### preCall

    mixed ModuleCore::preCall($module_name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1883)


#### Arguments
* $module_name **mixed**



### getPaypalIgnore

    mixed ModuleCore::getPaypalIgnore()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1891](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1891)




### getPaymentModules

    array ModuleCore::getPaymentModules()

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1902](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1902)




### findTranslation

    mixed ModuleCore::findTranslation($name, $string, $source)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 1948](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1948)


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
* This method is defined in [classes/module/Module.php line 1964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1964)


#### Arguments
* $string **string** - &lt;p&gt;String to translate&lt;/p&gt;
* $specific **boolean|string** - &lt;p&gt;filename to use in translation key&lt;/p&gt;



### updatePosition

    mixed ModuleCore::updatePosition($id_hook, $way, $position)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 1980](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#1980)


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**



### cleanPositions

    mixed ModuleCore::cleanPositions($id_hook, $shop_list)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2033](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2033)


#### Arguments
* $id_hook **mixed**
* $shop_list **mixed**



### displayError

    string ModuleCore::displayError(string|array $error)

Helper displaying error message(s)



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2063](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2063)


#### Arguments
* $error **string|array**



### displayWarning

    string ModuleCore::displayWarning($warning)

Helper displaying warning message(s)



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2092](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2092)


#### Arguments
* $warning **mixed**



### displayConfirmation

    mixed ModuleCore::displayConfirmation($string)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2115)


#### Arguments
* $string **mixed**



### getExceptionsStatic

    mixed ModuleCore::getExceptionsStatic($id_module, $id_hook, $dispatch)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2134)


#### Arguments
* $id_module **mixed**
* $id_hook **mixed**
* $dispatch **mixed**



### getExceptions

    mixed ModuleCore::getExceptions($id_hook, $dispatch)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2188)


#### Arguments
* $id_hook **mixed**
* $dispatch **mixed**



### isInstalled

    mixed ModuleCore::isInstalled($module_name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2193)


#### Arguments
* $module_name **mixed**



### isEnabledForShopContext

    mixed ModuleCore::isEnabledForShopContext()





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2203)




### isEnabled

    mixed ModuleCore::isEnabled($module_name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2214)


#### Arguments
* $module_name **mixed**



### isRegisteredInHook

    mixed ModuleCore::isRegisteredInHook($hook)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2228)


#### Arguments
* $hook **mixed**



### _isTemplateOverloadedStatic

    mixed ModuleCore::_isTemplateOverloadedStatic($module_name, $template)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2244)


#### Arguments
* $module_name **mixed**
* $template **mixed**



### _isTemplateOverloaded

    mixed ModuleCore::_isTemplateOverloaded($template)





* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2262)


#### Arguments
* $template **mixed**



### getCacheId

    mixed ModuleCore::getCacheId($name)





* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2267)


#### Arguments
* $name **mixed**



### display

    mixed ModuleCore::display($file, $template, $cache_id, $compile_id)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2291)


#### Arguments
* $file **mixed**
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### getCurrentSubTemplate

    \Smarty_Internal_Template ModuleCore::getCurrentSubTemplate(string $template, string|null $cache_id, string|null $compile_id)





* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2328](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2328)


#### Arguments
* $template **string**
* $cache_id **string|null**
* $compile_id **string|null**



### resetCurrentSubTemplate

    mixed ModuleCore::resetCurrentSubTemplate($template, $cache_id, $compile_id)





* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2341](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2341)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### getTemplatePath

    string ModuleCore::getTemplatePath(string $template)

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2353)


#### Arguments
* $template **string**



### _getApplicableTemplateDir

    mixed ModuleCore::_getApplicableTemplateDir($template)





* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2373)


#### Arguments
* $template **mixed**



### isCached

    mixed ModuleCore::isCached($template, $cache_id, $compile_id)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2378)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### _clearCache

    mixed ModuleCore::_clearCache($template, $cache_id, $compile_id)





* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2399](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2399)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### _deferedClearCache

    mixed ModuleCore::_deferedClearCache($template_path, $cache_id, $compile_id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2444](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2444)


#### Arguments
* $template_path **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### _generateConfigXml

    mixed ModuleCore::_generateConfigXml()





* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2453)




### isHookableOn

    boolean ModuleCore::isHookableOn(string $hook_name)

Check if the module is transplantable on the hook in parameter



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2490)


#### Arguments
* $hook_name **string**



### getPermission

    boolean ModuleCore::getPermission(array $variable, object $employee)

Check employee permission for module



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2502)


#### Arguments
* $variable **array** - &lt;p&gt;(action)&lt;/p&gt;
* $employee **object**



### getPermissionStatic

    boolean ModuleCore::getPermissionStatic(integer $id_module, array $variable, object $employee)

Check employee permission for module (static method)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2514)


#### Arguments
* $id_module **integer**
* $variable **array** - &lt;p&gt;(action)&lt;/p&gt;
* $employee **object**



### getAuthorizedModules

    array|null ModuleCore::getAuthorizedModules(integer $group_id)

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2551](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2551)


#### Arguments
* $group_id **integer**



### getModuleIdByName

    integer ModuleCore::getModuleIdByName(string $name)

Get ID module by name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/Module.php line 2565](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2565)


#### Arguments
* $name **string**



### getErrors

    array ModuleCore::getErrors()

Get module errors



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2582)




### getConfirmations

    array ModuleCore::getConfirmations()

Get module messages confirmation



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2593](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2593)




### getLocalPath

    string ModuleCore::getLocalPath()

Get local path for module



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2604](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2604)




### getPathUri

    string ModuleCore::getPathUri()

Get uri path for module



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2615)




### getPosition

    mixed ModuleCore::getPosition($id_hook)





* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2626)


#### Arguments
* $id_hook **mixed**



### adminDisplayWarning

    mixed ModuleCore::adminDisplayWarning(string $msg)

add a warning message to display at the top of the admin page



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2652](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2652)


#### Arguments
* $msg **string**



### adminDisplayInformation

    mixed ModuleCore::adminDisplayInformation(string $msg)

add a info message to display at the top of the admin page



* Visibility: **protected**
* This method is defined in [classes/module/Module.php line 2665](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2665)


#### Arguments
* $msg **string**



### installControllers

    boolean ModuleCore::installControllers()

Install module's controllers using public property $controllers



* Visibility: **private**
* This method is defined in [classes/module/Module.php line 2677](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2677)




### installOverrides

    boolean ModuleCore::installOverrides()

Install overrides files for the module



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2718](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2718)




### uninstallOverrides

    boolean ModuleCore::uninstallOverrides()

Uninstall overrides files for the module



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2740](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2740)




### addOverride

    boolean ModuleCore::addOverride(string $classname)

Add all methods in a module override to the override class



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2763](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2763)


#### Arguments
* $classname **string**



### removeOverride

    boolean ModuleCore::removeOverride(string $classname)

Remove all methods in a module override from the override class



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 2912](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#2912)


#### Arguments
* $classname **string**



### getPossibleHooksList

    array ModuleCore::getPossibleHooksList()

Return the hooks list where this module can be hooked.



* Visibility: **public**
* This method is defined in [classes/module/Module.php line 3062](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/Module.php#3062)



