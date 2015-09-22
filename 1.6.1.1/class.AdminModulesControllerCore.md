Class AdminModulesControllerCore
=====================





* Class name: AdminModulesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminModulesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L27)



Properties
----------

* [$_modules_ad](#property-$_modules_ad)
* [$filter_configuration](#property-$filter_configuration)
* [$id_employee](#property-$id_employee)
* [$iso_default_country](#property-$iso_default_country)
* [$list_modules_categories](#property-$list_modules_categories)
* [$list_natives_modules](#property-$list_natives_modules)
* [$list_partners_modules](#property-$list_partners_modules)
* [$map](#property-$map)
* [$modules_authors](#property-$modules_authors)
* [$nb_modules_activated](#property-$nb_modules_activated)
* [$nb_modules_installed](#property-$nb_modules_installed)
* [$nb_modules_total](#property-$nb_modules_total)
* [$serial_modules](#property-$serial_modules)
* [$xml_modules_list](#property-$xml_modules_list)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessGetModuleQuickView](#method-ajaxProcessGetModuleQuickView)
* [ajaxProcessGetTabModulesList](#method-ajaxProcessGetTabModulesList)
* [ajaxProcessLogOnAddonsWebservices](#method-ajaxProcessLogOnAddonsWebservices)
* [ajaxProcessLogOutAddonsWebservices](#method-ajaxProcessLogOutAddonsWebservices)
* [ajaxProcessRefreshModuleList](#method-ajaxProcessRefreshModuleList)
* [ajaxProcessReloadModulesList](#method-ajaxProcessReloadModulesList)
* [ajaxProcessSaveFavoritePreferences](#method-ajaxProcessSaveFavoritePreferences)
* [ajaxProcessSaveTabModulePreferences](#method-ajaxProcessSaveTabModulePreferences)
* [ajaxProcessSetFilter](#method-ajaxProcessSetFilter)
* [checkCategoriesNames](#method-checkCategoriesNames)
* [displayAjaxRefreshModuleList](#method-displayAjaxRefreshModuleList)
* [extractArchive](#method-extractArchive)
* [generateHtmlMessage](#method-generateHtmlMessage)
* [getCurrentUrl](#method-getCurrentUrl)
* [getModulesByInstallation](#method-getModulesByInstallation)
* [initContent](#method-initContent)
* [initModal](#method-initModal)
* [initModulesList](#method-initModulesList)
* [isModuleFiltered](#method-isModuleFiltered)
* [makeModulesStats](#method-makeModulesStats)
* [postProcess](#method-postProcess)
* [postProcessCallback](#method-postProcessCallback)
* [postProcessDelete](#method-postProcessDelete)
* [postProcessDisable_Device](#method-postProcessDisable_Device)
* [postProcessDownload](#method-postProcessDownload)
* [postProcessEnable](#method-postProcessEnable)
* [postProcessEnable_Device](#method-postProcessEnable_Device)
* [postProcessFilterCategory](#method-postProcessFilterCategory)
* [postProcessFilterModules](#method-postProcessFilterModules)
* [postProcessReset](#method-postProcessReset)
* [postProcessResetFilterModules](#method-postProcessResetFilterModules)
* [postProcessUnfilterCategory](#method-postProcessUnfilterCategory)
* [recursiveDeleteOnDisk](#method-recursiveDeleteOnDisk)
* [renderKpis](#method-renderKpis)
* [resetFilterModules](#method-resetFilterModules)
* [setFilterModules](#method-setFilterModules)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$_modules_ad"></a>$_modules_ad

    private mixed $_modules_ad = array('blockcart' => array('cartabandonmentpro'), 'blocklayered' => array('pm_advancedsearch4'))





* Visibility: **private**
* Source: [controllers/admin/AdminModulesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L29)


### <a name="property-$filter_configuration"></a>$filter_configuration

    protected mixed $filter_configuration = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L61)


### <a name="property-$id_employee"></a>$id_employee

    protected mixed $id_employee





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L59)


### <a name="property-$iso_default_country"></a>$iso_default_country

    protected mixed $iso_default_country





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L60)


### <a name="property-$list_modules_categories"></a>$list_modules_categories

    protected mixed $list_modules_categories = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L48)


### <a name="property-$list_natives_modules"></a>$list_natives_modules

    protected mixed $list_natives_modules = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L50)


### <a name="property-$list_partners_modules"></a>$list_partners_modules

    protected mixed $list_partners_modules = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L49)


### <a name="property-$map"></a>$map

    protected mixed $map = array('check' => 'check', 'install' => 'install', 'uninstall' => 'uninstall', 'configure' => 'getContent', 'update' => 'update', 'delete' => 'delete', 'checkAndUpdate' => 'checkAndUpdate', 'updateAll' => 'updateAll')





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L37)


### <a name="property-$modules_authors"></a>$modules_authors

    protected mixed $modules_authors = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L57)


### <a name="property-$nb_modules_activated"></a>$nb_modules_activated

    protected mixed $nb_modules_activated





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L54)


### <a name="property-$nb_modules_installed"></a>$nb_modules_installed

    protected mixed $nb_modules_installed





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L53)


### <a name="property-$nb_modules_total"></a>$nb_modules_total

    protected mixed $nb_modules_total





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L52)


### <a name="property-$serial_modules"></a>$serial_modules

    protected mixed $serial_modules = ''





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L56)


### <a name="property-$xml_modules_list"></a>$xml_modules_list

    protected mixed $xml_modules_list = _PS_API_MODULES_LIST_16_





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L63)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminModulesControllerCore::__construct()

Admin Modules Controller Constructor
Init list modules categories
Load id employee
Load filter configuration
Load cache file



* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L73)




### <a name="method-ajaxProcessGetModuleQuickView"></a>ajaxProcessGetModuleQuickView

    mixed AdminModulesControllerCore::ajaxProcessGetModuleQuickView()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1634)




### <a name="method-ajaxProcessGetTabModulesList"></a>ajaxProcessGetTabModulesList

    mixed AdminModulesControllerCore::ajaxProcessGetTabModulesList()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L270)




### <a name="method-ajaxProcessLogOnAddonsWebservices"></a>ajaxProcessLogOnAddonsWebservices

    mixed AdminModulesControllerCore::ajaxProcessLogOnAddonsWebservices()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L225)




### <a name="method-ajaxProcessLogOutAddonsWebservices"></a>ajaxProcessLogOutAddonsWebservices

    mixed AdminModulesControllerCore::ajaxProcessLogOutAddonsWebservices()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L247)




### <a name="method-ajaxProcessRefreshModuleList"></a>ajaxProcessRefreshModuleList

    mixed AdminModulesControllerCore::ajaxProcessRefreshModuleList($force_reload_cache)





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L167)


#### Arguments
* $force_reload_cache **mixed**



### <a name="method-ajaxProcessReloadModulesList"></a>ajaxProcessReloadModulesList

    mixed AdminModulesControllerCore::ajaxProcessReloadModulesList()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L256)




### <a name="method-ajaxProcessSaveFavoritePreferences"></a>ajaxProcessSaveFavoritePreferences

    mixed AdminModulesControllerCore::ajaxProcessSaveFavoritePreferences()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L322)




### <a name="method-ajaxProcessSaveTabModulePreferences"></a>ajaxProcessSaveTabModulePreferences

    mixed AdminModulesControllerCore::ajaxProcessSaveTabModulePreferences()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L349)




### <a name="method-ajaxProcessSetFilter"></a>ajaxProcessSetFilter

    mixed AdminModulesControllerCore::ajaxProcessSetFilter()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L316)




### <a name="method-checkCategoriesNames"></a>checkCategoriesNames

    mixed AdminModulesControllerCore::checkCategoriesNames($a, $b)





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L148)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-displayAjaxRefreshModuleList"></a>displayAjaxRefreshModuleList

    mixed AdminModulesControllerCore::displayAjaxRefreshModuleList()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L219)




### <a name="method-extractArchive"></a>extractArchive

    mixed AdminModulesControllerCore::extractArchive($file, $redirect)





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L391)


#### Arguments
* $file **mixed**
* $redirect **mixed**



### <a name="method-generateHtmlMessage"></a>generateHtmlMessage

    string AdminModulesControllerCore::generateHtmlMessage($module_errors)

Generate html errors for a module process



* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 1129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1129)


#### Arguments
* $module_errors **mixed**



### <a name="method-getCurrentUrl"></a>getCurrentUrl

    mixed AdminModulesControllerCore::getCurrentUrl($remove)





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L372)


#### Arguments
* $remove **mixed**



### <a name="method-getModulesByInstallation"></a>getModulesByInstallation

    mixed AdminModulesControllerCore::getModulesByInstallation($tab_modules_list)





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 1040](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1040)


#### Arguments
* $tab_modules_list **mixed**



### <a name="method-initContent"></a>initContent

    mixed AdminModulesControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1379)




### <a name="method-initModal"></a>initModal

    mixed AdminModulesControllerCore::initModal()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1344)




### <a name="method-initModulesList"></a>initModulesList

    mixed AdminModulesControllerCore::initModulesList($modules)





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1149)


#### Arguments
* $modules **mixed**



### <a name="method-isModuleFiltered"></a>isModuleFiltered

    mixed AdminModulesControllerCore::isModuleFiltered($module)





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1193)


#### Arguments
* $module **mixed**



### <a name="method-makeModulesStats"></a>makeModulesStats

    mixed AdminModulesControllerCore::makeModulesStats($module)





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1173)


#### Arguments
* $module **mixed**



### <a name="method-postProcess"></a>postProcess

    mixed AdminModulesControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1085](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1085)




### <a name="method-postProcessCallback"></a>postProcessCallback

    mixed AdminModulesControllerCore::postProcessCallback()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L696)




### <a name="method-postProcessDelete"></a>postProcessDelete

    mixed AdminModulesControllerCore::postProcessDelete()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 664](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L664)




### <a name="method-postProcessDisable_Device"></a>postProcessDisable_Device

    mixed AdminModulesControllerCore::postProcessDisable_Device()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 645](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L645)




### <a name="method-postProcessDownload"></a>postProcessDownload

    mixed AdminModulesControllerCore::postProcessDownload()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L554)




### <a name="method-postProcessEnable"></a>postProcessEnable

    mixed AdminModulesControllerCore::postProcessEnable()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L603)




### <a name="method-postProcessEnable_Device"></a>postProcessEnable_Device

    mixed AdminModulesControllerCore::postProcessEnable_Device()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L626)




### <a name="method-postProcessFilterCategory"></a>postProcessFilterCategory

    mixed AdminModulesControllerCore::postProcessFilterCategory()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 497](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L497)




### <a name="method-postProcessFilterModules"></a>postProcessFilterModules

    mixed AdminModulesControllerCore::postProcessFilterModules()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L485)




### <a name="method-postProcessReset"></a>postProcessReset

    mixed AdminModulesControllerCore::postProcessReset()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L516)




### <a name="method-postProcessResetFilterModules"></a>postProcessResetFilterModules

    mixed AdminModulesControllerCore::postProcessResetFilterModules()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 491](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L491)




### <a name="method-postProcessUnfilterCategory"></a>postProcessUnfilterCategory

    mixed AdminModulesControllerCore::postProcessUnfilterCategory()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L504)




### <a name="method-recursiveDeleteOnDisk"></a>recursiveDeleteOnDisk

    mixed AdminModulesControllerCore::recursiveDeleteOnDisk($dir)





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L437)


#### Arguments
* $dir **mixed**



### <a name="method-renderKpis"></a>renderKpis

    mixed AdminModulesControllerCore::renderKpis()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 1296](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L1296)




### <a name="method-resetFilterModules"></a>resetFilterModules

    mixed AdminModulesControllerCore::resetFilterModules()





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 471](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L471)




### <a name="method-setFilterModules"></a>setFilterModules

    mixed AdminModulesControllerCore::setFilterModules($module_type, $country_module_value, $module_install, $module_status)





* Visibility: **protected**
* Source: [controllers/admin/AdminModulesController.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L463)


#### Arguments
* $module_type **mixed**
* $country_module_value **mixed**
* $module_install **mixed**
* $module_status **mixed**



### <a name="method-setMedia"></a>setMedia

    mixed AdminModulesControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/admin/AdminModulesController.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminModulesController.php#L157)



