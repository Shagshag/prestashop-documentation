Class TabCore
=====================





* Class name: TabCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Tab.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L27)


Contents
--------

### Constants

* [TAB_MODULE_LIST_URL](#constant-TAB_MODULE_LIST_URL)

### Properties

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

### Methods

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

```php
const TAB_MODULE_LIST_URL = 'api.prestashop.com/xml/tab_modules_list.xml'
```





* Source: [classes/Tab.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L49).


Properties
----------


### <a name="property-$_cache_tabs"></a>$_cache_tabs

```php
protected mixed $_cache_tabs = array()
```

Get tabs



* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tab.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L244).


### <a name="property-$_getIdFromClassName"></a>$_getIdFromClassName

```php
protected mixed $_getIdFromClassName = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Tab.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L71).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Tab.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L44).


### <a name="property-$class_name"></a>$class_name

```php
public string $class_name
```





* Visibility: **public**
* Source: [classes/Tab.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'tab', 'primary' => 'id_tab', 'multilang' => true, 'fields' => array('id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isTabName', 'size' => 64), 'class_name' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'hide_host_mode' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'validate' => 'isTabName', 'size' => 64)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Tab.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L54).


### <a name="property-$hide_host_mode"></a>$hide_host_mode

```php
public integer $hide_host_mode = false
```





* Visibility: **public**
* Source: [classes/Tab.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L47).


### <a name="property-$id_parent"></a>$id_parent

```php
public integer $id_parent
```





* Visibility: **public**
* Source: [classes/Tab.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L38).


### <a name="property-$module"></a>$module

```php
public mixed $module
```





* Visibility: **public**
* Source: [classes/Tab.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L35).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Tab.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L30).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Tab.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L41).


Methods
-------


### <a name="method-add"></a>add

```php
integer TabCore::add(boolean $autodate, boolean $null_values)
```

additionnal treatments for Tab when creating new one :
- generate a new position
- add access for admin profile



* Visibility: **public**
* Source: [classes/Tab.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L82)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-checkTabRights"></a>checkTabRights

```php
mixed TabCore::checkTabRights($id_tab)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L468)


#### Arguments
* $id_tab **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed TabCore::cleanPositions($id_parent)
```





* Visibility: **public**
* Source: [classes/Tab.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L416)


#### Arguments
* $id_parent **mixed**



### <a name="method-delete"></a>delete

```php
mixed TabCore::delete()
```





* Visibility: **public**
* Source: [classes/Tab.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L150)




### <a name="method-disablingForModule"></a>disablingForModule

```php
boolean TabCore::disablingForModule($module)
```

Disabling tabs for module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L341)


#### Arguments
* $module **mixed** - string Module name



### <a name="method-enablingForModule"></a>enablingForModule

```php
boolean TabCore::enablingForModule($module)
```

Enabling tabs for module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L320)


#### Arguments
* $module **mixed** - string Module Name



### <a name="method-getClassNameById"></a>getClassNameById

```php
mixed TabCore::getClassNameById($id_tab)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L533)


#### Arguments
* $id_tab **mixed**



### <a name="method-getCollectionFromModule"></a>getCollectionFromModule

```php
array|\PrestaShopCollection TabCore::getCollectionFromModule($module, null $id_lang)
```

Get collection from module name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L301)


#### Arguments
* $module **mixed** - string Module name
* $id_lang **null** - integer Language ID



### <a name="method-getCurrentParentId"></a>getCurrentParentId

```php
integer TabCore::getCurrentParentId()
```

Get tab parent id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L180)




### <a name="method-getCurrentTabId"></a>getCurrentTabId

```php
integer TabCore::getCurrentTabId()
```

Get tab id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L166)




### <a name="method-getIdFromClassName"></a>getIdFromClassName

```php
integer TabCore::getIdFromClassName($class_name)
```

Get tab id from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L281)


#### Arguments
* $class_name **mixed**



### <a name="method-getInstanceFromClassName"></a>getInstanceFromClassName

```php
\Tab TabCore::getInstanceFromClassName($class_name, $id_lang)
```

Get Instance from tab class name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L363)


#### Arguments
* $class_name **mixed** - string Name of tab class
* $id_lang **mixed** - integer id_lang



### <a name="method-getModuleTabList"></a>getModuleTabList

```php
array TabCore::getModuleTabList()
```

Return the list of tab used by a module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L225)




### <a name="method-getNbTabs"></a>getNbTabs

```php
mixed TabCore::getNbTabs($id_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L369)


#### Arguments
* $id_parent **mixed**



### <a name="method-getNewLastPosition"></a>getNewLastPosition

```php
integer TabCore::getNewLastPosition(mixed $id_parent)
```

return an available position in subtab for parent $id_parent



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L384)


#### Arguments
* $id_parent **mixed**



### <a name="method-getTab"></a>getTab

```php
array TabCore::getTab($id_lang, $id_tab)
```

Get tab



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L201)


#### Arguments
* $id_lang **mixed**
* $id_tab **mixed**



### <a name="method-getTabByIdProfile"></a>getTabByIdProfile

```php
mixed TabCore::getTabByIdProfile($id_parent, $id_profile)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L509)


#### Arguments
* $id_parent **mixed**
* $id_profile **mixed**



### <a name="method-getTabModulesList"></a>getTabModulesList

```php
mixed TabCore::getTabModulesList($id_tab)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L538)


#### Arguments
* $id_tab **mixed**



### <a name="method-getTabs"></a>getTabs

```php
mixed TabCore::getTabs($id_lang, $id_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L245)


#### Arguments
* $id_lang **mixed**
* $id_parent **mixed**



### <a name="method-initAccess"></a>initAccess

```php
boolean TabCore::initAccess(integer $id_tab, \Context $context)
```

When creating a new tab $id_tab, this add default rights to the table access



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L125)


#### Arguments
* $id_tab **integer**
* $context **[Context](class.ContextCore.md)**



### <a name="method-move"></a>move

```php
mixed TabCore::move($direction)
```





* Visibility: **public**
* Source: [classes/Tab.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L393)


#### Arguments
* $direction **mixed**



### <a name="method-recursiveTab"></a>recursiveTab

```php
mixed TabCore::recursiveTab($id_tab, $tabs)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tab.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L483)


#### Arguments
* $id_tab **mixed**
* $tabs **mixed**



### <a name="method-save"></a>save

```php
mixed TabCore::save($null_values, $autodate)
```





* Visibility: **public**
* Source: [classes/Tab.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L112)


#### Arguments
* $null_values **mixed**
* $autodate **mixed**



### <a name="method-update"></a>update

```php
boolean TabCore::update(boolean $null_values)
```

Overrides update to set position to last when changing parent tab



* Visibility: **public**
* Source: [classes/Tab.php line 499](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L499)


#### Arguments
* $null_values **boolean**



### <a name="method-updatePosition"></a>updatePosition

```php
mixed TabCore::updatePosition($way, $position)
```





* Visibility: **public**
* Source: [classes/Tab.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Tab.php#L434)


#### Arguments
* $way **mixed**
* $position **mixed**


