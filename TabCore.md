TabCore
===============






* Class name: TabCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Tab.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#27)



Constants
----------


### TAB_MODULE_LIST_URL

    const TAB_MODULE_LIST_URL = _PS_TAB_MODULE_LIST_URL_



* This constant is defined in [classes/Tab.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#49)


Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Tab.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#30)


### $class_name

    public string $class_name





* Visibility: **public**
* This property is defined in [classes/Tab.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#33)


### $module

    public mixed $module





* Visibility: **public**
* This property is defined in [classes/Tab.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#35)


### $id_parent

    public integer $id_parent





* Visibility: **public**
* This property is defined in [classes/Tab.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#38)


### $position

    public integer $position





* Visibility: **public**
* This property is defined in [classes/Tab.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#41)


### $active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Tab.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#44)


### $hide_host_mode

    public integer $hide_host_mode = false





* Visibility: **public**
* This property is defined in [classes/Tab.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#47)


### $definition

    public mixed $definition = array('table' => 'tab', 'primary' => 'id_tab', 'multilang' => true, 'fields' => array('id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isTabName', 'size' => 64), 'class_name' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'hide_host_mode' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'validate' => 'isTabName', 'size' => 64)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Tab.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#54)


### $_getIdFromClassName

    protected mixed $_getIdFromClassName = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Tab.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#70)


### $_cache_tabs

    protected mixed $_cache_tabs = array()

Get tabs



* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Tab.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#251)


Methods
-------


### add

    integer TabCore::add(boolean $autodate, boolean $null_values)

additionnal treatments for Tab when creating new one :
- generate a new position
- add access for admin profile



* Visibility: **public**
* This method is defined in [classes/Tab.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#81)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### save

    mixed TabCore::save($null_values, $autodate)





* Visibility: **public**
* This method is defined in [classes/Tab.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#113)


#### Arguments
* $null_values **mixed**
* $autodate **mixed**



### initAccess

    boolean TabCore::initAccess(integer $id_tab, \Context $context)

When creating a new tab $id_tab, this add default rights to the table access



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#126)


#### Arguments
* $id_tab **integer**
* $context **[Context](ContextCore)**



### delete

    mixed TabCore::delete()





* Visibility: **public**
* This method is defined in [classes/Tab.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#153)




### getCurrentTabId

    integer TabCore::getCurrentTabId()

Get tab id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#169)




### getCurrentParentId

    integer TabCore::getCurrentParentId()

Get tab parent id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#184)




### getTab

    array TabCore::getTab($id_lang, $id_tab)

Get tab



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#206)


#### Arguments
* $id_lang **mixed**
* $id_tab **mixed**



### getModuleTabList

    array TabCore::getModuleTabList()

Return the list of tab used by a module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#229)




### getTabs

    mixed TabCore::getTabs($id_lang, $id_parent)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#252)


#### Arguments
* $id_lang **mixed**
* $id_parent **mixed**



### getIdFromClassName

    integer TabCore::getIdFromClassName(string $class_name)

Get tab id from name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#291)


#### Arguments
* $class_name **string**



### getCollectionFromModule

    array|\PrestaShopCollection TabCore::getCollectionFromModule($module, null $id_lang)

Get collection from module name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#314)


#### Arguments
* $module **mixed** - &lt;p&gt;string Module name&lt;/p&gt;
* $id_lang **null** - &lt;p&gt;integer Language ID&lt;/p&gt;



### enablingForModule

    boolean TabCore::enablingForModule($module)

Enabling tabs for module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#335)


#### Arguments
* $module **mixed** - &lt;p&gt;string Module Name&lt;/p&gt;



### disablingForModule

    boolean TabCore::disablingForModule($module)

Disabling tabs for module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#354)


#### Arguments
* $module **mixed** - &lt;p&gt;string Module name&lt;/p&gt;



### getInstanceFromClassName

    \Tab TabCore::getInstanceFromClassName($class_name, $id_lang)

Get Instance from tab class name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#374)


#### Arguments
* $class_name **mixed** - &lt;p&gt;string Name of tab class&lt;/p&gt;
* $id_lang **mixed** - &lt;p&gt;integer id_lang&lt;/p&gt;



### getNbTabs

    mixed TabCore::getNbTabs($id_parent)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#380)


#### Arguments
* $id_parent **mixed**



### getNewLastPosition

    integer TabCore::getNewLastPosition(mixed $id_parent)

return an available position in subtab for parent $id_parent



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#395)


#### Arguments
* $id_parent **mixed**



### move

    mixed TabCore::move($direction)





* Visibility: **public**
* This method is defined in [classes/Tab.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#404)


#### Arguments
* $direction **mixed**



### cleanPositions

    mixed TabCore::cleanPositions($id_parent)





* Visibility: **public**
* This method is defined in [classes/Tab.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#431)


#### Arguments
* $id_parent **mixed**



### updatePosition

    mixed TabCore::updatePosition($way, $position)





* Visibility: **public**
* This method is defined in [classes/Tab.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#450)


#### Arguments
* $way **mixed**
* $position **mixed**



### checkTabRights

    mixed TabCore::checkTabRights($id_tab)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#488)


#### Arguments
* $id_tab **mixed**



### recursiveTab

    mixed TabCore::recursiveTab($id_tab, $tabs)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#506)


#### Arguments
* $id_tab **mixed**
* $tabs **mixed**



### update

    boolean TabCore::update(boolean $null_values)

Overrides update to set position to last when changing parent tab



* Visibility: **public**
* This method is defined in [classes/Tab.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#523)


#### Arguments
* $null_values **boolean**



### getTabByIdProfile

    mixed TabCore::getTabByIdProfile($id_parent, $id_profile)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#534)


#### Arguments
* $id_parent **mixed**
* $id_profile **mixed**



### getClassNameById

    mixed TabCore::getClassNameById($id_tab)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#558)


#### Arguments
* $id_tab **mixed**



### getTabModulesList

    mixed TabCore::getTabModulesList($id_tab)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Tab.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Tab.php#563)


#### Arguments
* $id_tab **mixed**


