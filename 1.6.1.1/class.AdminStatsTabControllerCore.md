Class AdminStatsTabControllerCore
=====================





* Class name: AdminStatsTabControllerCore
* This is an **abstract** class
* Parent class: [AdminPreferencesControllerCore](class.AdminPreferencesControllerCore.md)
* Source: [controllers/admin/AdminStatsTabController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L27)


Contents
--------


### Properties

* [$object](#property-$object)

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




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Configuration $object
```





* Visibility: **public**
* This property is defined by [AdminPreferencesControllerCore](class.AdminPreferencesControllerCore.md).
* Source: [controllers/admin/AdminPreferencesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPreferencesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStatsTabControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L32)




### <a name="method-ajaxProcessSetDashboardDateRange"></a>ajaxProcessSetDashboardDateRange

```php
mixed AdminStatsTabControllerCore::ajaxProcessSetDashboardDateRange()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L285)




### <a name="method-checkModulesNames"></a>checkModulesNames

```php
mixed AdminStatsTabControllerCore::checkModulesNames($a, $b)
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L176)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-displayCalendar"></a>displayCalendar

```php
mixed AdminStatsTabControllerCore::displayCalendar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L75)




### <a name="method-displayCalendarForm"></a>displayCalendarForm

```php
mixed AdminStatsTabControllerCore::displayCalendarForm($translations, $token, $action, $table, $identifier, $id)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminStatsTabController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L88)


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
* Source: [controllers/admin/AdminStatsTabController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L123)




### <a name="method-displayMenu"></a>displayMenu

```php
mixed AdminStatsTabControllerCore::displayMenu()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L148)




### <a name="method-displayStats"></a>displayStats

```php
mixed AdminStatsTabControllerCore::displayStats()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L194)




### <a name="method-getDate"></a>getDate

```php
mixed AdminStatsTabControllerCore::getDate()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatsTabController.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L307)




### <a name="method-getModules"></a>getModules

```php
mixed AdminStatsTabControllerCore::getModules()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminStatsTabController.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L181)




### <a name="method-init"></a>init

```php
mixed AdminStatsTabControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L29)




### <a name="method-initContent"></a>initContent

```php
mixed AdminStatsTabControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L37)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStatsTabControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L69)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminStatsTabControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L223)




### <a name="method-processDateRange"></a>processDateRange

```php
mixed AdminStatsTabControllerCore::processDateRange()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L241)




### <a name="method-updateOptionPsMultishopFeatureActive"></a>updateOptionPsMultishopFeatureActive

```php
mixed AdminStatsTabControllerCore::updateOptionPsMultishopFeatureActive(string $value)
```

Enable / disable multishop menu if multishop feature is activated



* Visibility: **public**
* Source: [controllers/admin/AdminStatsTabController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminStatsTabController.php#L238)


#### Arguments
* $value **string**


