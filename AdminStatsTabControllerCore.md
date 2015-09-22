AdminStatsTabControllerCore
===============






* Class name: AdminStatsTabControllerCore
* This is an **abstract** class
* Parent class: [AdminPreferencesControllerCore](AdminPreferencesControllerCore)
* This class is defined in [controllers/admin/AdminStatsTabController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L27)





Properties
----------

* [$object](#property-$object)

Methods
-------
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [displayCalendar](#method-displayCalendar)
* [displayCalendarForm](#method-displayCalendarForm)
* [displayEngines](#method-displayEngines)
* [displayMenu](#method-displayMenu)
* [checkModulesNames](#method-checkModulesNames)
* [getModules](#method-getModules)
* [displayStats](#method-displayStats)
* [postProcess](#method-postProcess)
* [processDateRange](#method-processDateRange)
* [ajaxProcessSetDashboardDateRange](#method-ajaxProcessSetDashboardDateRange)
* [getDate](#method-getDate)
* [__construct](#method-__construct)
* [updateOptionPsMultishopFeatureActive](#method-updateOptionPsMultishopFeatureActive)




Properties
----------


### <a name="property-$object"></a>$object

    public \Configuration $object





* Visibility: **public**
* This property is defined by [AdminPreferencesControllerCore](AdminPreferencesControllerCore)
* This property is defined in [controllers/admin/AdminStatsTabController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L30)


Methods
-------


### <a name="method-init"></a>init

    mixed AdminStatsTabControllerCore::init()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L29)




### <a name="method-initContent"></a>initContent

    mixed AdminStatsTabControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L37)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminStatsTabControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L69)




### <a name="method-displayCalendar"></a>displayCalendar

    mixed AdminStatsTabControllerCore::displayCalendar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L75)




### <a name="method-displayCalendarForm"></a>displayCalendarForm

    mixed AdminStatsTabControllerCore::displayCalendarForm($translations, $token, $action, $table, $identifier, $id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminStatsTabController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L88)


#### Arguments
* $translations **mixed**
* $token **mixed**
* $action **mixed**
* $table **mixed**
* $identifier **mixed**
* $id **mixed**



### <a name="method-displayEngines"></a>displayEngines

    mixed AdminStatsTabControllerCore::displayEngines()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L123)




### <a name="method-displayMenu"></a>displayMenu

    mixed AdminStatsTabControllerCore::displayMenu()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L148)




### <a name="method-checkModulesNames"></a>checkModulesNames

    mixed AdminStatsTabControllerCore::checkModulesNames($a, $b)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L176)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-getModules"></a>getModules

    mixed AdminStatsTabControllerCore::getModules()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L181)




### <a name="method-displayStats"></a>displayStats

    mixed AdminStatsTabControllerCore::displayStats()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L194)




### <a name="method-postProcess"></a>postProcess

    mixed AdminStatsTabControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L223)




### <a name="method-processDateRange"></a>processDateRange

    mixed AdminStatsTabControllerCore::processDateRange()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L241)




### <a name="method-ajaxProcessSetDashboardDateRange"></a>ajaxProcessSetDashboardDateRange

    mixed AdminStatsTabControllerCore::ajaxProcessSetDashboardDateRange()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L285)




### <a name="method-getDate"></a>getDate

    mixed AdminStatsTabControllerCore::getDate()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminStatsTabController.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L307)




### <a name="method-__construct"></a>__construct

    mixed AdminPreferencesControllerCore::__construct()





* Visibility: **public**
* This method is defined by [AdminPreferencesControllerCore](AdminPreferencesControllerCore)
* This method is defined in [controllers/admin/AdminStatsTabController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L32)




### <a name="method-updateOptionPsMultishopFeatureActive"></a>updateOptionPsMultishopFeatureActive

    mixed AdminPreferencesControllerCore::updateOptionPsMultishopFeatureActive(string $value)

Enable / disable multishop menu if multishop feature is activated



* Visibility: **public**
* This method is defined by [AdminPreferencesControllerCore](AdminPreferencesControllerCore)
* This method is defined in [controllers/admin/AdminStatsTabController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L238)


#### Arguments
* $value **string**


