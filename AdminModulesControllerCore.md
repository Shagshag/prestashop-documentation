AdminModulesControllerCore
===============






* Class name: AdminModulesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $_modules_ad

    private mixed $_modules_ad = array('blockcart' => array('cartabandonmentpro'), 'blocklayered' => array('pm_advancedsearch4'))





* Visibility: **private**


### $map

    protected mixed $map = array('check' => 'check', 'install' => 'install', 'uninstall' => 'uninstall', 'configure' => 'getContent', 'update' => 'update', 'delete' => 'delete', 'checkAndUpdate' => 'checkAndUpdate', 'updateAll' => 'updateAll')





* Visibility: **protected**


### $list_modules_categories

    protected mixed $list_modules_categories = array()





* Visibility: **protected**


### $list_partners_modules

    protected mixed $list_partners_modules = array()





* Visibility: **protected**


### $list_natives_modules

    protected mixed $list_natives_modules = array()





* Visibility: **protected**


### $nb_modules_total

    protected mixed $nb_modules_total





* Visibility: **protected**


### $nb_modules_installed

    protected mixed $nb_modules_installed





* Visibility: **protected**


### $nb_modules_activated

    protected mixed $nb_modules_activated





* Visibility: **protected**


### $serial_modules

    protected mixed $serial_modules = ''





* Visibility: **protected**


### $modules_authors

    protected mixed $modules_authors = array()





* Visibility: **protected**


### $id_employee

    protected mixed $id_employee





* Visibility: **protected**


### $iso_default_country

    protected mixed $iso_default_country





* Visibility: **protected**


### $filter_configuration

    protected mixed $filter_configuration = array()





* Visibility: **protected**


### $xml_modules_list

    protected mixed $xml_modules_list = _PS_API_MODULES_LIST_16_





* Visibility: **protected**


Methods
-------


### __construct

    mixed AdminModulesControllerCore::__construct()

Admin Modules Controller Constructor
Init list modules categories
Load id employee
Load filter configuration
Load cache file



* Visibility: **public**




### checkCategoriesNames

    mixed AdminModulesControllerCore::checkCategoriesNames($a, $b)





* Visibility: **public**


#### Arguments
* $a **mixed**
* $b **mixed**



### setMedia

    mixed AdminModulesControllerCore::setMedia()





* Visibility: **public**




### ajaxProcessRefreshModuleList

    mixed AdminModulesControllerCore::ajaxProcessRefreshModuleList($force_reload_cache)





* Visibility: **public**


#### Arguments
* $force_reload_cache **mixed**



### displayAjaxRefreshModuleList

    mixed AdminModulesControllerCore::displayAjaxRefreshModuleList()





* Visibility: **public**




### ajaxProcessLogOnAddonsWebservices

    mixed AdminModulesControllerCore::ajaxProcessLogOnAddonsWebservices()





* Visibility: **public**




### ajaxProcessLogOutAddonsWebservices

    mixed AdminModulesControllerCore::ajaxProcessLogOutAddonsWebservices()





* Visibility: **public**




### ajaxProcessReloadModulesList

    mixed AdminModulesControllerCore::ajaxProcessReloadModulesList()





* Visibility: **public**




### ajaxProcessGetTabModulesList

    mixed AdminModulesControllerCore::ajaxProcessGetTabModulesList()





* Visibility: **public**




### ajaxProcessSetFilter

    mixed AdminModulesControllerCore::ajaxProcessSetFilter()





* Visibility: **public**




### ajaxProcessSaveFavoritePreferences

    mixed AdminModulesControllerCore::ajaxProcessSaveFavoritePreferences()





* Visibility: **public**




### ajaxProcessSaveTabModulePreferences

    mixed AdminModulesControllerCore::ajaxProcessSaveTabModulePreferences()





* Visibility: **public**




### getCurrentUrl

    mixed AdminModulesControllerCore::getCurrentUrl($remove)





* Visibility: **protected**


#### Arguments
* $remove **mixed**



### extractArchive

    mixed AdminModulesControllerCore::extractArchive($file, $redirect)





* Visibility: **protected**


#### Arguments
* $file **mixed**
* $redirect **mixed**



### recursiveDeleteOnDisk

    mixed AdminModulesControllerCore::recursiveDeleteOnDisk($dir)





* Visibility: **protected**


#### Arguments
* $dir **mixed**



### setFilterModules

    mixed AdminModulesControllerCore::setFilterModules($module_type, $country_module_value, $module_install, $module_status)





* Visibility: **protected**


#### Arguments
* $module_type **mixed**
* $country_module_value **mixed**
* $module_install **mixed**
* $module_status **mixed**



### resetFilterModules

    mixed AdminModulesControllerCore::resetFilterModules()





* Visibility: **protected**




### postProcessFilterModules

    mixed AdminModulesControllerCore::postProcessFilterModules()





* Visibility: **public**




### postProcessResetFilterModules

    mixed AdminModulesControllerCore::postProcessResetFilterModules()





* Visibility: **public**




### postProcessFilterCategory

    mixed AdminModulesControllerCore::postProcessFilterCategory()





* Visibility: **public**




### postProcessUnfilterCategory

    mixed AdminModulesControllerCore::postProcessUnfilterCategory()





* Visibility: **public**




### postProcessReset

    mixed AdminModulesControllerCore::postProcessReset()





* Visibility: **public**




### postProcessDownload

    mixed AdminModulesControllerCore::postProcessDownload()





* Visibility: **public**




### postProcessEnable

    mixed AdminModulesControllerCore::postProcessEnable()





* Visibility: **public**




### postProcessEnable_Device

    mixed AdminModulesControllerCore::postProcessEnable_Device()





* Visibility: **public**




### postProcessDisable_Device

    mixed AdminModulesControllerCore::postProcessDisable_Device()





* Visibility: **public**




### postProcessDelete

    mixed AdminModulesControllerCore::postProcessDelete()





* Visibility: **public**




### postProcessCallback

    mixed AdminModulesControllerCore::postProcessCallback()





* Visibility: **public**




### getModulesByInstallation

    mixed AdminModulesControllerCore::getModulesByInstallation($tab_modules_list)





* Visibility: **protected**


#### Arguments
* $tab_modules_list **mixed**



### postProcess

    mixed AdminModulesControllerCore::postProcess()





* Visibility: **public**




### generateHtmlMessage

    string AdminModulesControllerCore::generateHtmlMessage($module_errors)

Generate html errors for a module process



* Visibility: **protected**


#### Arguments
* $module_errors **mixed**



### initModulesList

    mixed AdminModulesControllerCore::initModulesList($modules)





* Visibility: **public**


#### Arguments
* $modules **mixed**



### makeModulesStats

    mixed AdminModulesControllerCore::makeModulesStats($module)





* Visibility: **public**


#### Arguments
* $module **mixed**



### isModuleFiltered

    mixed AdminModulesControllerCore::isModuleFiltered($module)





* Visibility: **public**


#### Arguments
* $module **mixed**



### renderKpis

    mixed AdminModulesControllerCore::renderKpis()





* Visibility: **public**




### initModal

    mixed AdminModulesControllerCore::initModal()





* Visibility: **public**




### initContent

    mixed AdminModulesControllerCore::initContent()





* Visibility: **public**




### ajaxProcessGetModuleQuickView

    mixed AdminModulesControllerCore::ajaxProcessGetModuleQuickView()





* Visibility: **public**



