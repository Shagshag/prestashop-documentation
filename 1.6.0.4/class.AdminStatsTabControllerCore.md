Class AdminStatsTabControllerCore
=====================





* Class name: AdminStatsTabControllerCore
* This is an **abstract** class
* Parent class: [AdminPreferencesControllerCore](class.AdminPreferencesControllerCore.md)
* Source: [controllers/admin/AdminStatsTabController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L27)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [ajaxProcessSetDashboardDateRange](#method-ajaxProcessSetDashboardDateRange)
* [checkModulesNames](#method-checkModulesNames)
* [displayCalendar](#method-displayCalendar)
* [displayCalendarForm](#method-displayCalendarForm)
* [displayEngines](#method-displayEngines)
* [displayMenu](#method-displayMenu)
* [displayStats](#method-displayStats)
* [getDate](#method-getDate)
* [getModules](#method-getModules)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [processDateRange](#method-processDateRange)
* [updateOptionPsMultishopFeatureActive](#method-updateOptionPsMultishopFeatureActive)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStatsTabControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L30)




### <a name="method-ajaxProcessSetDashboardDateRange"></a>ajaxProcessSetDashboardDateRange

```php
mixed AdminStatsTabControllerCore::ajaxProcessSetDashboardDateRange()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L293)




### <a name="method-checkModulesNames"></a>checkModulesNames

```php
mixed AdminStatsTabControllerCore::checkModulesNames($a, $b)
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L178)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-displayCalendar"></a>displayCalendar

```php
mixed AdminStatsTabControllerCore::displayCalendar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L74)




### <a name="method-displayCalendarForm"></a>displayCalendarForm

```php
mixed AdminStatsTabControllerCore::displayCalendarForm($translations, $token, $action, $table, $identifier, $id)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminStatsTabController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L87)


#### Arguments
* $translations **mixed**
* $token **mixed**
* $action **mixed**
* $table **mixed**
* $identifier **mixed**
* $id **mixed**



### <a name="method-displayEngines"></a>displayEngines

```php
mixed AdminStatsTabControllerCore::displayEngines()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatsTabController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L123)




### <a name="method-displayMenu"></a>displayMenu

```php
mixed AdminStatsTabControllerCore::displayMenu()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L148)




### <a name="method-displayStats"></a>displayStats

```php
mixed AdminStatsTabControllerCore::displayStats()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L196)




### <a name="method-getDate"></a>getDate

```php
mixed AdminStatsTabControllerCore::getDate()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatsTabController.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L315)




### <a name="method-getModules"></a>getModules

```php
mixed AdminStatsTabControllerCore::getModules()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatsTabController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L183)




### <a name="method-init"></a>init

```php
mixed AdminStatsTabControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L29)




### <a name="method-initContent"></a>initContent

```php
mixed AdminStatsTabControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L37)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStatsTabControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L68)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminStatsTabControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L223)




### <a name="method-processDateRange"></a>processDateRange

```php
mixed AdminStatsTabControllerCore::processDateRange()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L243)




### <a name="method-updateOptionPsMultishopFeatureActive"></a>updateOptionPsMultishopFeatureActive

```php
mixed AdminStatsTabControllerCore::updateOptionPsMultishopFeatureActive(string $value)
```

Enable / disable multishop menu if multishop feature is activated



* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminStatsTabController.php#L180)


#### Arguments
* $value **string**


