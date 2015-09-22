Class TabCore
=====================





* Class name: TabCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/Tab.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L27)

Constants
----------

* [TAB_MODULE_LIST_URL](#constant-TAB_MODULE_LIST_URL)

Properties
----------

* [$_cache_tabs](#property-$_cache_tabs)
* [$_getIdFromClassName](#property-$_getIdFromClassName)
* [$active](#property-$active)
* [$class_name](#property-$class_name)
* [$definition](#property-$definition)
* [$hide_host_mode](#property-$hide_host_mode)
* [$id_parent](#property-$id_parent)
* [$module](#property-$module)
* [$name](#property-$name)
* [$position](#property-$position)

Methods
-------
* [add](#method-add)
* [checkTabRights](#method-checkTabRights)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [disablingForModule](#method-disablingForModule)
* [enablingForModule](#method-enablingForModule)
* [getClassNameById](#method-getClassNameById)
* [getCollectionFromModule](#method-getCollectionFromModule)
* [getCurrentParentId](#method-getCurrentParentId)
* [getCurrentTabId](#method-getCurrentTabId)
* [getIdFromClassName](#method-getIdFromClassName)
* [getInstanceFromClassName](#method-getInstanceFromClassName)
* [getModuleTabList](#method-getModuleTabList)
* [getNbTabs](#method-getNbTabs)
* [getNewLastPosition](#method-getNewLastPosition)
* [getTab](#method-getTab)
* [getTabByIdProfile](#method-getTabByIdProfile)
* [getTabModulesList](#method-getTabModulesList)
* [getTabs](#method-getTabs)
* [initAccess](#method-initAccess)
* [move](#method-move)
* [recursiveTab](#method-recursiveTab)
* [save](#method-save)
* [update](#method-update)
* [updatePosition](#method-updatePosition)


Constants
----------


### <a name="constant-TAB_MODULE_LIST_URL"></a>TAB_MODULE_LIST_URL

    const TAB_MODULE_LIST_URL = _PS_TAB_MODULE_LIST_URL_



* Source: [classes/Tab.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L49)


Properties
----------


### <a name="property-$_cache_tabs"></a>$_cache_tabs

    protected mixed $_cache_tabs = array()

Get tabs



* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tab.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L251)


### <a name="property-$_getIdFromClassName"></a>$_getIdFromClassName

    protected mixed $_getIdFromClassName = null





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tab.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L70)


### <a name="property-$active"></a>$active

    public boolean $active = true





* Visibility: **public**
* Source: [classes/Tab.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L44)


### <a name="property-$class_name"></a>$class_name

    public string $class_name





* Visibility: **public**
* Source: [classes/Tab.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L33)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'tab', 'primary' => 'id_tab', 'multilang' => true, 'fields' => array('id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isTabName', 'size' => 64), 'class_name' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'hide_host_mode' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'validate' => 'isTabName', 'size' => 64)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Tab.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L54)


### <a name="property-$hide_host_mode"></a>$hide_host_mode

    public integer $hide_host_mode = false





* Visibility: **public**
* Source: [classes/Tab.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L47)


### <a name="property-$id_parent"></a>$id_parent

    public integer $id_parent





* Visibility: **public**
* Source: [classes/Tab.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L38)


### <a name="property-$module"></a>$module

    public mixed $module





* Visibility: **public**
* Source: [classes/Tab.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L35)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Tab.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L30)


### <a name="property-$position"></a>$position

    public integer $position





* Visibility: **public**
* Source: [classes/Tab.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L41)


Methods
-------


### <a name="method-add"></a>add

    integer TabCore::add(boolean $autodate, boolean $null_values)

additionnal treatments for Tab when creating new one :
- generate a new position
- add access for admin profile



* Visibility: **public**
* Source: [classes/Tab.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L81)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-checkTabRights"></a>checkTabRights

    mixed TabCore::checkTabRights($id_tab)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L488)


#### Arguments
* $id_tab **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

    mixed TabCore::cleanPositions($id_parent)





* Visibility: **public**
* Source: [classes/Tab.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L431)


#### Arguments
* $id_parent **mixed**



### <a name="method-delete"></a>delete

    mixed TabCore::delete()





* Visibility: **public**
* Source: [classes/Tab.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L153)




### <a name="method-disablingForModule"></a>disablingForModule

    boolean TabCore::disablingForModule($module)

Disabling tabs for module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L354)


#### Arguments
* $module **mixed** - string Module name



### <a name="method-enablingForModule"></a>enablingForModule

    boolean TabCore::enablingForModule($module)

Enabling tabs for module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L335)


#### Arguments
* $module **mixed** - string Module Name



### <a name="method-getClassNameById"></a>getClassNameById

    mixed TabCore::getClassNameById($id_tab)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L558)


#### Arguments
* $id_tab **mixed**



### <a name="method-getCollectionFromModule"></a>getCollectionFromModule

    array|\PrestaShopCollection TabCore::getCollectionFromModule($module, null $id_lang)

Get collection from module name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L314)


#### Arguments
* $module **mixed** - string Module name
* $id_lang **null** - integer Language ID



### <a name="method-getCurrentParentId"></a>getCurrentParentId

    integer TabCore::getCurrentParentId()

Get tab parent id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L184)




### <a name="method-getCurrentTabId"></a>getCurrentTabId

    integer TabCore::getCurrentTabId()

Get tab id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L169)




### <a name="method-getIdFromClassName"></a>getIdFromClassName

    integer TabCore::getIdFromClassName(string $class_name)

Get tab id from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L291)


#### Arguments
* $class_name **string**



### <a name="method-getInstanceFromClassName"></a>getInstanceFromClassName

    \Tab TabCore::getInstanceFromClassName($class_name, $id_lang)

Get Instance from tab class name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L374)


#### Arguments
* $class_name **mixed** - string Name of tab class
* $id_lang **mixed** - integer id_lang



### <a name="method-getModuleTabList"></a>getModuleTabList

    array TabCore::getModuleTabList()

Return the list of tab used by a module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L229)




### <a name="method-getNbTabs"></a>getNbTabs

    mixed TabCore::getNbTabs($id_parent)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L380)


#### Arguments
* $id_parent **mixed**



### <a name="method-getNewLastPosition"></a>getNewLastPosition

    integer TabCore::getNewLastPosition(mixed $id_parent)

return an available position in subtab for parent $id_parent



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L395)


#### Arguments
* $id_parent **mixed**



### <a name="method-getTab"></a>getTab

    array TabCore::getTab($id_lang, $id_tab)

Get tab



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L206)


#### Arguments
* $id_lang **mixed**
* $id_tab **mixed**



### <a name="method-getTabByIdProfile"></a>getTabByIdProfile

    mixed TabCore::getTabByIdProfile($id_parent, $id_profile)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L534)


#### Arguments
* $id_parent **mixed**
* $id_profile **mixed**



### <a name="method-getTabModulesList"></a>getTabModulesList

    mixed TabCore::getTabModulesList($id_tab)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L563)


#### Arguments
* $id_tab **mixed**



### <a name="method-getTabs"></a>getTabs

    mixed TabCore::getTabs($id_lang, $id_parent)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L252)


#### Arguments
* $id_lang **mixed**
* $id_parent **mixed**



### <a name="method-initAccess"></a>initAccess

    boolean TabCore::initAccess(integer $id_tab, \Context $context)

When creating a new tab $id_tab, this add default rights to the table access



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L126)


#### Arguments
* $id_tab **integer**
* $context **[Context](class.ContextCore)**



### <a name="method-move"></a>move

    mixed TabCore::move($direction)





* Visibility: **public**
* Source: [classes/Tab.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L404)


#### Arguments
* $direction **mixed**



### <a name="method-recursiveTab"></a>recursiveTab

    mixed TabCore::recursiveTab($id_tab, $tabs)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L506)


#### Arguments
* $id_tab **mixed**
* $tabs **mixed**



### <a name="method-save"></a>save

    mixed TabCore::save($null_values, $autodate)





* Visibility: **public**
* Source: [classes/Tab.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L113)


#### Arguments
* $null_values **mixed**
* $autodate **mixed**



### <a name="method-update"></a>update

    boolean TabCore::update(boolean $null_values)

Overrides update to set position to last when changing parent tab



* Visibility: **public**
* Source: [classes/Tab.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L523)


#### Arguments
* $null_values **boolean**



### <a name="method-updatePosition"></a>updatePosition

    mixed TabCore::updatePosition($way, $position)





* Visibility: **public**
* Source: [classes/Tab.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#L450)


#### Arguments
* $way **mixed**
* $position **mixed**


