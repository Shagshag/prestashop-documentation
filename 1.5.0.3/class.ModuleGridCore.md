Class ModuleGridCore
=====================





* Class name: ModuleGridCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/ModuleGrid.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L28)


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
* [$_confirmations](#property-$_confirmations)
* [$_errors](#property-$_errors)
* [$_generate_config_xml_mode](#property-$_generate_config_xml_mode)
* [$_lang](#property-$_lang)
* [$_path](#property-$_path)
* [$active](#property-$active)
* [$author](#property-$author)
* [$cache_permissions](#property-$cache_permissions)
* [$classInModule](#property-$classInModule)
* [$context](#property-$context)
* [$dependencies](#property-$dependencies)
* [$description](#property-$description)
* [$displayName](#property-$displayName)
* [$exceptionsCache](#property-$exceptionsCache)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$l_cache](#property-$l_cache)
* [$limited_countries](#property-$limited_countries)
* [$local_path](#property-$local_path)
* [$modules_cache](#property-$modules_cache)
* [$name](#property-$name)
* [$need_instance](#property-$need_instance)
* [$ps_versions_compliancy](#property-$ps_versions_compliancy)
* [$registered_version](#property-$registered_version)
* [$smarty](#property-$smarty)
* [$tab](#property-$tab)
* [$table](#property-$table)
* [$version](#property-$version)
* [$warning](#property-$warning)

### Methods

* [__construct](#method-__construct)
* [_clearCache](#method-_clearCache)
* [_displayCsv](#method-_displayCsv)
* [_generateConfigXml](#method-_generateConfigXml)
* [_getApplicableTemplateDir](#method-_getApplicableTemplateDir)
* [_isTemplateOverloaded](#method-_isTemplateOverloaded)
* [_isTemplateOverloadedStatic](#method-_isTemplateOverloadedStatic)
* [cleanPositions](#method-cleanPositions)
* [configXmlStringFormat](#method-configXmlStringFormat)
* [create](#method-create)
* [csvExport](#method-csvExport)
* [disable](#method-disable)
* [disableByName](#method-disableByName)
* [display](#method-display)
* [displayConfirmation](#method-displayConfirmation)
* [displayError](#method-displayError)
* [displayFlags](#method-displayFlags)
* [editExceptions](#method-editExceptions)
* [enable](#method-enable)
* [enableByName](#method-enableByName)
* [engine](#method-engine)
* [findTranslation](#method-findTranslation)
* [getAuthorizedModules](#method-getAuthorizedModules)
* [getConfirmations](#method-getConfirmations)
* [getData](#method-getData)
* [getDate](#method-getDate)
* [getErrors](#method-getErrors)
* [getExceptions](#method-getExceptions)
* [getInstanceById](#method-getInstanceById)
* [getInstanceByName](#method-getInstanceByName)
* [getLang](#method-getLang)
* [getModuleIdByName](#method-getModuleIdByName)
* [getModuleNameFromClass](#method-getModuleNameFromClass)
* [getModulesDirOnDisk](#method-getModulesDirOnDisk)
* [getModulesInstalled](#method-getModulesInstalled)
* [getModulesOnDisk](#method-getModulesOnDisk)
* [getNonNativeModuleList](#method-getNonNativeModuleList)
* [getPathUri](#method-getPathUri)
* [getPaymentModules](#method-getPaymentModules)
* [getPermission](#method-getPermission)
* [getPermissionStatic](#method-getPermissionStatic)
* [getTemplatePath](#method-getTemplatePath)
* [hookExec](#method-hookExec)
* [hookExecPayment](#method-hookExecPayment)
* [initUpgradeModule](#method-initUpgradeModule)
* [install](#method-install)
* [isCached](#method-isCached)
* [isHookableOn](#method-isHookableOn)
* [isInstalled](#method-isInstalled)
* [isRegisteredInHook](#method-isRegisteredInHook)
* [l](#method-l)
* [loadUpgradeVersionList](#method-loadUpgradeVersionList)
* [needUpgrade](#method-needUpgrade)
* [preCall](#method-preCall)
* [registerExceptions](#method-registerExceptions)
* [registerHook](#method-registerHook)
* [render](#method-render)
* [runUpgradeModule](#method-runUpgradeModule)
* [setEmployee](#method-setEmployee)
* [setLang](#method-setLang)
* [setUpgradeMessage](#method-setUpgradeMessage)
* [sqlShopRestriction](#method-sqlShopRestriction)
* [uninstall](#method-uninstall)
* [unregisterExceptions](#method-unregisterExceptions)
* [unregisterHook](#method-unregisterHook)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$_direction"></a>$_direction

```php
protected mixed $_direction = null
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L51).


### <a name="property-$_employee"></a>$_employee

```php
protected mixed $_employee
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L30).


### <a name="property-$_limit"></a>$_limit

```php
protected mixed $_limit
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L45).


### <a name="property-$_render"></a>$_render

```php
protected \ModuleGridEngine $_render
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L54).


### <a name="property-$_sort"></a>$_sort

```php
protected mixed $_sort = null
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L48).


### <a name="property-$_start"></a>$_start

```php
protected mixed $_start
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L42).


### <a name="property-$_title"></a>$_title

```php
protected mixed $_title
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L39).


### <a name="property-$_totalCount"></a>$_totalCount

```php
protected integer $_totalCount
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L36).


### <a name="property-$_values"></a>$_values

```php
protected string $_values = array()
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L33).


### <a name="property-$_INSTANCE"></a>$_INSTANCE

```php
protected \protected $_INSTANCE = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L105).


### <a name="property-$_confirmations"></a>$_confirmations

```php
protected \protected $_confirmations = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L93).


### <a name="property-$_errors"></a>$_errors

```php
protected \protected $_errors = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L90).


### <a name="property-$_generate_config_xml_mode"></a>$_generate_config_xml_mode

```php
protected \protected $_generate_config_xml_mode = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L108).


### <a name="property-$_lang"></a>$_lang

```php
protected array $_lang = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L79).


### <a name="property-$_path"></a>$_path

```php
protected string $_path = NULL
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L82).


### <a name="property-$active"></a>$active

```php
public boolean $active = false
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L67).


### <a name="property-$author"></a>$author

```php
public string $author
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L58).


### <a name="property-$cache_permissions"></a>$cache_permissions

```php
protected \protected $cache_permissions = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L114).


### <a name="property-$classInModule"></a>$classInModule

```php
public array $classInModule = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L76).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L117).


### <a name="property-$dependencies"></a>$dependencies

```php
public array $dependencies = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L46).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L55).


### <a name="property-$displayName"></a>$displayName

```php
public string $displayName
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L52).


### <a name="property-$exceptionsCache"></a>$exceptionsCache

```php
protected mixed $exceptionsCache = NULL
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1378](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1378).


### <a name="property-$id"></a>$id

```php
public integer $id = NULL
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L31).


### <a name="property-$identifier"></a>$identifier

```php
protected \protected $identifier = 'id_module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L99).


### <a name="property-$l_cache"></a>$l_cache

```php
protected \protected $l_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L111).


### <a name="property-$limited_countries"></a>$limited_countries

```php
public array $limited_countries = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L73).


### <a name="property-$local_path"></a>$local_path

```php
protected string $local_path = NULL
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L87).


### <a name="property-$modules_cache"></a>$modules_cache

```php
protected \protected $modules_cache
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L102).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L49).


### <a name="property-$need_instance"></a>$need_instance

```php
public integer $need_instance = 1
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L61).


### <a name="property-$ps_versions_compliancy"></a>$ps_versions_compliancy

```php
public array $ps_versions_compliancy = array('min' => '1.4', 'max' => '1.6')
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L43).


### <a name="property-$registered_version"></a>$registered_version

```php
public string $registered_version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L40).


### <a name="property-$smarty"></a>$smarty

```php
protected \Smarty_Data $smarty
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L120).


### <a name="property-$tab"></a>$tab

```php
public string $tab = NULL
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L64).


### <a name="property-$table"></a>$table

```php
protected \protected $table = 'module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L96).


### <a name="property-$version"></a>$version

```php
public float $version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L34).


### <a name="property-$warning"></a>$warning

```php
public string $warning
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L70).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleCore::__construct(string $name, \Context $context)
```

Constructor



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L128)


#### Arguments
* $name **string** - Module unique name
* $context **[Context](class.ContextCore.md)**



### <a name="method-_clearCache"></a>_clearCache

```php
mixed ModuleCore::_clearCache($template, $cacheId, $compileId)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1506](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1506)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-_displayCsv"></a>_displayCsv

```php
mixed ModuleGridCore::_displayCsv()
```





* Visibility: **protected**
* Source: [classes/ModuleGrid.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L164)




### <a name="method-_generateConfigXml"></a>_generateConfigXml

```php
mixed ModuleCore::_generateConfigXml()
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1511](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1511)




### <a name="method-_getApplicableTemplateDir"></a>_getApplicableTemplateDir

```php
mixed ModuleCore::_getApplicableTemplateDir($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1494](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1494)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloaded"></a>_isTemplateOverloaded

```php
mixed ModuleCore::_isTemplateOverloaded($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1451](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1451)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloadedStatic"></a>_isTemplateOverloadedStatic

```php
mixed ModuleCore::_isTemplateOverloadedStatic($moduleName, $template)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1442](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1442)


#### Arguments
* $moduleName **mixed**
* $template **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ModuleCore::cleanPositions($id_hook, $shopList)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1328](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1328)


#### Arguments
* $id_hook **mixed**
* $shopList **mixed**



### <a name="method-configXmlStringFormat"></a>configXmlStringFormat

```php
mixed ModuleCore::configXmlStringFormat($string)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 837](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L837)


#### Arguments
* $string **mixed**



### <a name="method-create"></a>create

```php
mixed ModuleGridCore::create($render, $type, $width, $height, $start, $limit, $sort, $dir)
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L70)


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
* Source: [classes/ModuleGrid.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L137)


#### Arguments
* $datas **mixed**



### <a name="method-disable"></a>disable

```php
mixed ModuleCore::disable(boolean $forceAll)
```

Desactivate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 537](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L537)


#### Arguments
* $forceAll **boolean** - If true, disable module for all shop



### <a name="method-disableByName"></a>disableByName

```php
true ModuleCore::disableByName(array|string $name)
```

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L519)


#### Arguments
* $name **array|string**



### <a name="method-display"></a>display

```php
mixed ModuleCore::display($file, $template, $cacheId, $compileId)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1456](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1456)


#### Arguments
* $file **mixed**
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-displayConfirmation"></a>displayConfirmation

```php
mixed ModuleCore::displayConfirmation($string)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1363](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1363)


#### Arguments
* $string **mixed**



### <a name="method-displayError"></a>displayError

```php
mixed ModuleCore::displayError($error)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1353](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1353)


#### Arguments
* $error **mixed**



### <a name="method-displayFlags"></a>displayFlags

```php
mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L554)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-editExceptions"></a>editExceptions

```php
boolean ModuleCore::editExceptions(integer $hookID, array $excepts)
```

Edit exceptions for module->Hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L746)


#### Arguments
* $hookID **integer** - Hook id
* $excepts **array** - List of shopID and file name



### <a name="method-enable"></a>enable

```php
mixed ModuleCore::enable(boolean $forceAll)
```

Activate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L488)


#### Arguments
* $forceAll **boolean** - If true, enable module for all shop



### <a name="method-enableByName"></a>enableByName

```php
true ModuleCore::enableByName(array|string $name)
```

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L472)


#### Arguments
* $name **array|string**



### <a name="method-engine"></a>engine

```php
mixed ModuleGridCore::engine($params)
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L96)


#### Arguments
* $params **mixed**



### <a name="method-findTranslation"></a>findTranslation

```php
string ModuleCore::findTranslation(string $name, string $string, string $source)
```

find translation from $_MODULES and put it in self::$l_cache if not already exist
and return it.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1213)


#### Arguments
* $name **string** - name of the module
* $string **string** - term to find
* $source **string** - additional param for building translation key



### <a name="method-getAuthorizedModules"></a>getAuthorizedModules

```php
mixed ModuleCore::getAuthorizedModules($group_id)
```

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1580](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1580)


#### Arguments
* $group_id **mixed**



### <a name="method-getConfirmations"></a>getConfirmations

```php
array ModuleCore::getConfirmations()
```

Get module messages confirmation



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1615](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1615)




### <a name="method-getData"></a>getData

```php
mixed ModuleGridCore::getData()
```





* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/ModuleGrid.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L173)




### <a name="method-getDate"></a>getDate

```php
mixed ModuleGridCore::getDate()
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L175)




### <a name="method-getErrors"></a>getErrors

```php
array ModuleCore::getErrors()
```

Get module errors



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1604](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1604)




### <a name="method-getExceptions"></a>getExceptions

```php
mixed ModuleCore::getExceptions($hookID, $dispatch)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1379](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1379)


#### Arguments
* $hookID **mixed**
* $dispatch **mixed**



### <a name="method-getInstanceById"></a>getInstanceById

```php
\Module ModuleCore::getInstanceById($moduleID)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 818](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L818)


#### Arguments
* $moduleID **mixed**



### <a name="method-getInstanceByName"></a>getInstanceByName

```php
\Module ModuleCore::getInstanceByName(string $moduleName)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L799)


#### Arguments
* $moduleName **string** - Module name



### <a name="method-getLang"></a>getLang

```php
mixed ModuleGridCore::getLang()
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L179)




### <a name="method-getModuleIdByName"></a>getModuleIdByName

```php
integer ModuleCore::getModuleIdByName($name)
```

Get id module by name



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1593](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1593)


#### Arguments
* $name **mixed**



### <a name="method-getModuleNameFromClass"></a>getModuleNameFromClass

```php
boolean|string ModuleCore::getModuleNameFromClass(mixed $currentClass)
```

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 768](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L768)


#### Arguments
* $currentClass **mixed** - the



### <a name="method-getModulesDirOnDisk"></a>getModulesDirOnDisk

```php
array ModuleCore::getModulesDirOnDisk()
```

Return modules directory list



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1079)




### <a name="method-getModulesInstalled"></a>getModulesInstalled

```php
array ModuleCore::getModulesInstalled(integer $position)
```

Return installed modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1126)


#### Arguments
* $position **integer** - Take only positionnables modules



### <a name="method-getModulesOnDisk"></a>getModulesOnDisk

```php
array ModuleCore::getModulesOnDisk(boolean $useConfig, $loggedOnAddons)
```

Return available modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 848](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L848)


#### Arguments
* $useConfig **boolean** - in order to use config.xml file in module dir
* $loggedOnAddons **mixed**



### <a name="method-getNonNativeModuleList"></a>getNonNativeModuleList

```php
array ModuleCore::getNonNativeModuleList()
```

Return non native module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1102)




### <a name="method-getPathUri"></a>getPathUri

```php
string ModuleCore::getPathUri()
```

Get uri path for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1626](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1626)




### <a name="method-getPaymentModules"></a>getPaymentModules

```php
array ModuleCore::getPaymentModules()
```

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1170](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1170)




### <a name="method-getPermission"></a>getPermission

```php
boolean ModuleCore::getPermission(array $variable, object $employee)
```

Check employee permission for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1545](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1545)


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
* Source: [classes/Module.php line 1557](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1557)


#### Arguments
* $id_module **integer**
* $variable **array** - (action)
* $employee **object**



### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string ModuleCore::getTemplatePath(string $template)
```

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1486](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1486)


#### Arguments
* $template **string**



### <a name="method-hookExec"></a>hookExec

```php
string ModuleCore::hookExec(string $hook_name, array $hookArgs, $id_module)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1144)


#### Arguments
* $hook_name **string** - Hook Name
* $hookArgs **array** - Parameters for the functions
* $id_module **mixed**



### <a name="method-hookExecPayment"></a>hookExecPayment

```php
mixed ModuleCore::hookExecPayment()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1150)




### <a name="method-initUpgradeModule"></a>initUpgradeModule

```php
boolean ModuleCore::initUpgradeModule($module_name, $module_version)
```

Init the upgrade module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L293)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**



### <a name="method-install"></a>install

```php
mixed ModuleGridCore::install()
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L56)




### <a name="method-isCached"></a>isCached

```php
mixed ModuleCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1499)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isHookableOn"></a>isHookableOn

```php
boolean ModuleCore::isHookableOn(string $hook_name)
```

Check if the module is transplantable on the hook in parameter



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1533](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1533)


#### Arguments
* $hook_name **string**



### <a name="method-isInstalled"></a>isInstalled

```php
mixed ModuleCore::isInstalled($moduleName)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1421](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1421)


#### Arguments
* $moduleName **mixed**



### <a name="method-isRegisteredInHook"></a>isRegisteredInHook

```php
mixed ModuleCore::isRegisteredInHook($hook)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1427](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1427)


#### Arguments
* $hook **mixed**



### <a name="method-l"></a>l

```php
string ModuleCore::l(string $string, boolean|string $specific, $id_lang)
```

Get translation for a given module text

Note: $specific parameter is mandatory for library files.
Otherwise, translation key will not match for Module library
when module is loaded with eval() Module::getModulesOnDisk()

* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1254](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1254)


#### Arguments
* $string **string** - String to translate
* $specific **boolean|string** - filename to use in translation key
* $id_lang **mixed**



### <a name="method-loadUpgradeVersionList"></a>loadUpgradeVersionList

```php
boolean ModuleCore::loadUpgradeVersionList($module_name, $module_version, $registered_version)
```

Load the available list of upgrade of a specified module
with an associated version



* Visibility: **private**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L393)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**
* $registered_version **mixed**



### <a name="method-needUpgrade"></a>needUpgrade

```php
boolean ModuleCore::needUpgrade($module_name, $module_version)
```

Check if a module need to be upgraded.

This method modify the module_cache adding an upgrade list file

* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L372)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**



### <a name="method-preCall"></a>preCall

```php
mixed ModuleCore::preCall($moduleName)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1157](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1157)


#### Arguments
* $moduleName **mixed**



### <a name="method-registerExceptions"></a>registerExceptions

```php
boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shopList)
```

Add exceptions for module->Hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L712)


#### Arguments
* $id_hook **integer** - Hook id
* $excepts **array** - List of file name
* $shopList **array** - List of shop



### <a name="method-registerHook"></a>registerHook

```php
boolean ModuleCore::registerHook(string $hook_name, array $shopList)
```

Connect module to a hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L583)


#### Arguments
* $hook_name **string** - Hook name
* $shopList **array** - List of shop linked to the hook (if null, link hook to all shops)



### <a name="method-render"></a>render

```php
mixed ModuleGridCore::render()
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L91)




### <a name="method-runUpgradeModule"></a>runUpgradeModule

```php
array ModuleCore::runUpgradeModule()
```

Run the upgrade for a given module name and version



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L317)




### <a name="method-setEmployee"></a>setEmployee

```php
mixed ModuleGridCore::setEmployee($id_employee)
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L61)


#### Arguments
* $id_employee **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed ModuleGridCore::setLang($id_lang)
```





* Visibility: **public**
* Source: [classes/ModuleGrid.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ModuleGrid.php#L65)


#### Arguments
* $id_lang **mixed**



### <a name="method-setUpgradeMessage"></a>setUpgradeMessage

```php
mixed ModuleCore::setUpgradeMessage($upgrade_detail)
```

Set errors, warning or success message of a module upgrade



* Visibility: **private**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L259)


#### Arguments
* $upgrade_detail **mixed**



### <a name="method-sqlShopRestriction"></a>sqlShopRestriction

```php
mixed ModuleCore::sqlShopRestriction($share, $alias)
```

Get SQL modules restriction by shop



* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L176)


#### Arguments
* $share **mixed**
* $alias **mixed**



### <a name="method-uninstall"></a>uninstall

```php
boolean ModuleCore::uninstall()
```

Delete module from datable



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L432)




### <a name="method-unregisterExceptions"></a>unregisterExceptions

```php
boolean ModuleCore::unregisterExceptions($hook_id, array $shopList)
```

Unregister exceptions linked to module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L696)


#### Arguments
* $hook_id **mixed**
* $shopList **array** - List of shop



### <a name="method-unregisterHook"></a>unregisterHook

```php
boolean ModuleCore::unregisterHook($hook_id, array $shopList)
```

Unregister module from hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L658)


#### Arguments
* $hook_id **mixed**
* $shopList **array** - List of shop



### <a name="method-updatePosition"></a>updatePosition

```php
mixed ModuleCore::updatePosition($id_hook, $way, $position)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/Module.php line 1281](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Module.php#L1281)


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**


