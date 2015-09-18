TabCore
===============






* Class name: TabCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### TAB_MODULE_LIST_URL

    const TAB_MODULE_LIST_URL = _PS_TAB_MODULE_LIST_URL_





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $class_name

    public string $class_name





* Visibility: **public**


### $module

    public mixed $module





* Visibility: **public**


### $id_parent

    public integer $id_parent





* Visibility: **public**


### $position

    public integer $position





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $hide_host_mode

    public integer $hide_host_mode = false





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'tab', 'primary' => 'id_tab', 'multilang' => true, 'fields' => array('id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isTabName', 'size' => 64), 'class_name' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'hide_host_mode' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'validate' => 'isTabName', 'size' => 64)))





* Visibility: **public**
* This property is **static**.


### $_getIdFromClassName

    protected mixed $_getIdFromClassName = null





* Visibility: **protected**
* This property is **static**.


### $_cache_tabs

    protected mixed $_cache_tabs = array()

Get tabs



* Visibility: **protected**
* This property is **static**.


Methods
-------


### add

    integer TabCore::add(boolean $autodate, boolean $null_values)

additionnal treatments for Tab when creating new one :
- generate a new position
- add access for admin profile



* Visibility: **public**


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### save

    mixed TabCore::save($null_values, $autodate)





* Visibility: **public**


#### Arguments
* $null_values **mixed**
* $autodate **mixed**



### initAccess

    boolean TabCore::initAccess(integer $id_tab, \Context $context)

When creating a new tab $id_tab, this add default rights to the table access



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tab **integer**
* $context **Context**



### delete

    mixed TabCore::delete()





* Visibility: **public**




### getCurrentTabId

    integer TabCore::getCurrentTabId()

Get tab id



* Visibility: **public**
* This method is **static**.




### getCurrentParentId

    integer TabCore::getCurrentParentId()

Get tab parent id



* Visibility: **public**
* This method is **static**.




### getTab

    array TabCore::getTab($id_lang, $id_tab)

Get tab



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_tab **mixed**



### getModuleTabList

    array TabCore::getModuleTabList()

Return the list of tab used by a module



* Visibility: **public**
* This method is **static**.




### getTabs

    mixed TabCore::getTabs($id_lang, $id_parent)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_parent **mixed**



### getIdFromClassName

    integer TabCore::getIdFromClassName(string $class_name)

Get tab id from name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $class_name **string**



### getCollectionFromModule

    array|\PrestaShopCollection TabCore::getCollectionFromModule($module, null $id_lang)

Get collection from module name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module **mixed** - &lt;p&gt;string Module name&lt;/p&gt;
* $id_lang **null** - &lt;p&gt;integer Language ID&lt;/p&gt;



### enablingForModule

    boolean TabCore::enablingForModule($module)

Enabling tabs for module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module **mixed** - &lt;p&gt;string Module Name&lt;/p&gt;



### disablingForModule

    boolean TabCore::disablingForModule($module)

Disabling tabs for module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $module **mixed** - &lt;p&gt;string Module name&lt;/p&gt;



### getInstanceFromClassName

    \Tab TabCore::getInstanceFromClassName($class_name, $id_lang)

Get Instance from tab class name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $class_name **mixed** - &lt;p&gt;string Name of tab class&lt;/p&gt;
* $id_lang **mixed** - &lt;p&gt;integer id_lang&lt;/p&gt;



### getNbTabs

    mixed TabCore::getNbTabs($id_parent)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_parent **mixed**



### getNewLastPosition

    integer TabCore::getNewLastPosition(mixed $id_parent)

return an available position in subtab for parent $id_parent



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_parent **mixed**



### move

    mixed TabCore::move($direction)





* Visibility: **public**


#### Arguments
* $direction **mixed**



### cleanPositions

    mixed TabCore::cleanPositions($id_parent)





* Visibility: **public**


#### Arguments
* $id_parent **mixed**



### updatePosition

    mixed TabCore::updatePosition($way, $position)





* Visibility: **public**


#### Arguments
* $way **mixed**
* $position **mixed**



### checkTabRights

    mixed TabCore::checkTabRights($id_tab)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tab **mixed**



### recursiveTab

    mixed TabCore::recursiveTab($id_tab, $tabs)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tab **mixed**
* $tabs **mixed**



### update

    boolean TabCore::update(boolean $null_values)

Overrides update to set position to last when changing parent tab



* Visibility: **public**


#### Arguments
* $null_values **boolean**



### getTabByIdProfile

    mixed TabCore::getTabByIdProfile($id_parent, $id_profile)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_parent **mixed**
* $id_profile **mixed**



### getClassNameById

    mixed TabCore::getClassNameById($id_tab)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tab **mixed**



### getTabModulesList

    mixed TabCore::getTabModulesList($id_tab)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tab **mixed**


