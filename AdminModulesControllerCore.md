AdminModulesControllerCore
===============






* Class name: AdminModulesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminModulesController.php line 27





Properties
----------


### $_modules_ad

    private mixed $_modules_ad = array('blockcart' => array('cartabandonmentpro'), 'blocklayered' => array('pm_advancedsearch4'))





* Visibility: **private**
* This property is defined in controllers\admin\AdminModulesController.php line 29


### $map

    protected mixed $map = array('check' => 'check', 'install' => 'install', 'uninstall' => 'uninstall', 'configure' => 'getContent', 'update' => 'update', 'delete' => 'delete', 'checkAndUpdate' => 'checkAndUpdate', 'updateAll' => 'updateAll')





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 37


### $list_modules_categories

    protected mixed $list_modules_categories = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 48


### $list_partners_modules

    protected mixed $list_partners_modules = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 49


### $list_natives_modules

    protected mixed $list_natives_modules = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 50


### $nb_modules_total

    protected mixed $nb_modules_total





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 52


### $nb_modules_installed

    protected mixed $nb_modules_installed





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 53


### $nb_modules_activated

    protected mixed $nb_modules_activated





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 54


### $serial_modules

    protected mixed $serial_modules = ''





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 56


### $modules_authors

    protected mixed $modules_authors = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 57


### $id_employee

    protected mixed $id_employee





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 59


### $iso_default_country

    protected mixed $iso_default_country





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 60


### $filter_configuration

    protected mixed $filter_configuration = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 61


### $xml_modules_list

    protected mixed $xml_modules_list = _PS_API_MODULES_LIST_16_





* Visibility: **protected**
* This property is defined in controllers\admin\AdminModulesController.php line 63


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
* This method is defined in controllers\admin\AdminModulesController.php line 73




### checkCategoriesNames

    mixed AdminModulesControllerCore::checkCategoriesNames($a, $b)





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 148


#### Arguments
* $a **mixed**
* $b **mixed**



### setMedia

    mixed AdminModulesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 157




### ajaxProcessRefreshModuleList

    mixed AdminModulesControllerCore::ajaxProcessRefreshModuleList($force_reload_cache)





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 167


#### Arguments
* $force_reload_cache **mixed**



### displayAjaxRefreshModuleList

    mixed AdminModulesControllerCore::displayAjaxRefreshModuleList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 219




### ajaxProcessLogOnAddonsWebservices

    mixed AdminModulesControllerCore::ajaxProcessLogOnAddonsWebservices()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 225




### ajaxProcessLogOutAddonsWebservices

    mixed AdminModulesControllerCore::ajaxProcessLogOutAddonsWebservices()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 247




### ajaxProcessReloadModulesList

    mixed AdminModulesControllerCore::ajaxProcessReloadModulesList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 256




### ajaxProcessGetTabModulesList

    mixed AdminModulesControllerCore::ajaxProcessGetTabModulesList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 270




### ajaxProcessSetFilter

    mixed AdminModulesControllerCore::ajaxProcessSetFilter()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 316




### ajaxProcessSaveFavoritePreferences

    mixed AdminModulesControllerCore::ajaxProcessSaveFavoritePreferences()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 322




### ajaxProcessSaveTabModulePreferences

    mixed AdminModulesControllerCore::ajaxProcessSaveTabModulePreferences()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 349




### getCurrentUrl

    mixed AdminModulesControllerCore::getCurrentUrl($remove)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminModulesController.php line 372


#### Arguments
* $remove **mixed**



### extractArchive

    mixed AdminModulesControllerCore::extractArchive($file, $redirect)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminModulesController.php line 391


#### Arguments
* $file **mixed**
* $redirect **mixed**



### recursiveDeleteOnDisk

    mixed AdminModulesControllerCore::recursiveDeleteOnDisk($dir)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminModulesController.php line 437


#### Arguments
* $dir **mixed**



### setFilterModules

    mixed AdminModulesControllerCore::setFilterModules($module_type, $country_module_value, $module_install, $module_status)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminModulesController.php line 463


#### Arguments
* $module_type **mixed**
* $country_module_value **mixed**
* $module_install **mixed**
* $module_status **mixed**



### resetFilterModules

    mixed AdminModulesControllerCore::resetFilterModules()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminModulesController.php line 471




### postProcessFilterModules

    mixed AdminModulesControllerCore::postProcessFilterModules()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 485




### postProcessResetFilterModules

    mixed AdminModulesControllerCore::postProcessResetFilterModules()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 491




### postProcessFilterCategory

    mixed AdminModulesControllerCore::postProcessFilterCategory()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 497




### postProcessUnfilterCategory

    mixed AdminModulesControllerCore::postProcessUnfilterCategory()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 504




### postProcessReset

    mixed AdminModulesControllerCore::postProcessReset()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 516




### postProcessDownload

    mixed AdminModulesControllerCore::postProcessDownload()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 554




### postProcessEnable

    mixed AdminModulesControllerCore::postProcessEnable()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 603




### postProcessEnable_Device

    mixed AdminModulesControllerCore::postProcessEnable_Device()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 626




### postProcessDisable_Device

    mixed AdminModulesControllerCore::postProcessDisable_Device()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 645




### postProcessDelete

    mixed AdminModulesControllerCore::postProcessDelete()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 664




### postProcessCallback

    mixed AdminModulesControllerCore::postProcessCallback()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 696




### getModulesByInstallation

    mixed AdminModulesControllerCore::getModulesByInstallation($tab_modules_list)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminModulesController.php line 1040


#### Arguments
* $tab_modules_list **mixed**



### postProcess

    mixed AdminModulesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1085




### generateHtmlMessage

    string AdminModulesControllerCore::generateHtmlMessage($module_errors)

Generate html errors for a module process



* Visibility: **protected**
* This method is defined in controllers\admin\AdminModulesController.php line 1129


#### Arguments
* $module_errors **mixed**



### initModulesList

    mixed AdminModulesControllerCore::initModulesList($modules)





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1149


#### Arguments
* $modules **mixed**



### makeModulesStats

    mixed AdminModulesControllerCore::makeModulesStats($module)





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1173


#### Arguments
* $module **mixed**



### isModuleFiltered

    mixed AdminModulesControllerCore::isModuleFiltered($module)





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1193


#### Arguments
* $module **mixed**



### renderKpis

    mixed AdminModulesControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1296




### initModal

    mixed AdminModulesControllerCore::initModal()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1344




### initContent

    mixed AdminModulesControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1379




### ajaxProcessGetModuleQuickView

    mixed AdminModulesControllerCore::ajaxProcessGetModuleQuickView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminModulesController.php line 1634



