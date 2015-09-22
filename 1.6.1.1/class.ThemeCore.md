Class ThemeCore
=====================





* Class name: ThemeCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Theme.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L27)


Contents
--------

### Constants

* [CACHE_FILE_CUSTOMER_THEMES_LIST](#constant-CACHE_FILE_CUSTOMER_THEMES_LIST)
* [CACHE_FILE_MUST_HAVE_THEMES_LIST](#constant-CACHE_FILE_MUST_HAVE_THEMES_LIST)
* [UPLOADED_THEME_DIR_NAME](#constant-UPLOADED_THEME_DIR_NAME)

### Properties

* [$access_rights](#property-$access_rights)
* [$default_left_column](#property-$default_left_column)
* [$default_right_column](#property-$default_right_column)
* [$definition](#property-$definition)
* [$directory](#property-$directory)
* [$name](#property-$name)
* [$product_per_page](#property-$product_per_page)
* [$responsive](#property-$responsive)

### Methods

* [add](#method-add)
* [getAllThemes](#method-getAllThemes)
* [getAvailable](#method-getAvailable)
* [getByDirectory](#method-getByDirectory)
* [getInstalledThemeDirectories](#method-getInstalledThemeDirectories)
* [getMetas](#method-getMetas)
* [getNonInstalledTheme](#method-getNonInstalledTheme)
* [getThemeInfo](#method-getThemeInfo)
* [getThemes](#method-getThemes)
* [hasColumns](#method-hasColumns)
* [hasColumnsSettings](#method-hasColumnsSettings)
* [hasLeftColumn](#method-hasLeftColumn)
* [hasRightColumn](#method-hasRightColumn)
* [isUsed](#method-isUsed)
* [removeMetas](#method-removeMetas)
* [toggleDefaultLeftColumn](#method-toggleDefaultLeftColumn)
* [toggleDefaultRightColumn](#method-toggleDefaultRightColumn)
* [toggleResponsive](#method-toggleResponsive)
* [updateMetas](#method-updateMetas)


Constants
----------


### <a name="constant-CACHE_FILE_CUSTOMER_THEMES_LIST"></a>CACHE_FILE_CUSTOMER_THEMES_LIST

```php
const CACHE_FILE_CUSTOMER_THEMES_LIST = '/config/xml/customer_themes_list.xml'
```





* Source: [classes/Theme.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L36).


### <a name="constant-CACHE_FILE_MUST_HAVE_THEMES_LIST"></a>CACHE_FILE_MUST_HAVE_THEMES_LIST

```php
const CACHE_FILE_MUST_HAVE_THEMES_LIST = '/config/xml/must_have_themes_list.xml'
```





* Source: [classes/Theme.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L38).


### <a name="constant-UPLOADED_THEME_DIR_NAME"></a>UPLOADED_THEME_DIR_NAME

```php
const UPLOADED_THEME_DIR_NAME = 'uploaded'
```





* Source: [classes/Theme.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L40).


Properties
----------


### <a name="property-$access_rights"></a>$access_rights

```php
public integer $access_rights = 509
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Theme.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L43).


### <a name="property-$default_left_column"></a>$default_left_column

```php
public mixed $default_left_column
```





* Visibility: **public**
* Source: [classes/Theme.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L32).


### <a name="property-$default_right_column"></a>$default_right_column

```php
public mixed $default_right_column
```





* Visibility: **public**
* Source: [classes/Theme.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'theme', 'primary' => 'id_theme', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64, 'required' => true), 'directory' => array('type' => self::TYPE_STRING, 'validate' => 'isDirName', 'size' => 64, 'required' => true), 'responsive' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_left_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_right_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_per_page' => array('type' => self::TYPE_INT, 'validate' => 'isInt')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Theme.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L47).


### <a name="property-$directory"></a>$directory

```php
public mixed $directory
```





* Visibility: **public**
* Source: [classes/Theme.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L30).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Theme.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L29).


### <a name="property-$product_per_page"></a>$product_per_page

```php
public mixed $product_per_page
```





* Visibility: **public**
* Source: [classes/Theme.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L34).


### <a name="property-$responsive"></a>$responsive

```php
public mixed $responsive
```





* Visibility: **public**
* Source: [classes/Theme.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L31).


Methods
-------


### <a name="method-add"></a>add

```php
boolean ThemeCore::add(boolean $autodate, boolean $null_values)
```

add only theme if the directory exists



* Visibility: **public**
* Source: [classes/Theme.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L136)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-getAllThemes"></a>getAllThemes

```php
mixed ThemeCore::getAllThemes($excluded_ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L67)


#### Arguments
* $excluded_ids **mixed**



### <a name="method-getAvailable"></a>getAvailable

```php
array ThemeCore::getAvailable(boolean $installed_only)
```

return an array of all available theme (installed or not)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L85)


#### Arguments
* $installed_only **boolean**



### <a name="method-getByDirectory"></a>getByDirectory

```php
boolean|\Theme ThemeCore::getByDirectory(string $directory)
```

Checks if theme exists (by folder) and returns Theme object.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L152)


#### Arguments
* $directory **string**



### <a name="method-getInstalledThemeDirectories"></a>getInstalledThemeDirectories

```php
mixed ThemeCore::getInstalledThemeDirectories()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L163)




### <a name="method-getMetas"></a>getMetas

```php
array|boolean ThemeCore::getMetas()
```





* Visibility: **public**
* Source: [classes/Theme.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L324)




### <a name="method-getNonInstalledTheme"></a>getNonInstalledTheme

```php
mixed ThemeCore::getNonInstalledTheme()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L214)




### <a name="method-getThemeInfo"></a>getThemeInfo

```php
mixed ThemeCore::getThemeInfo($id_theme)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L174)


#### Arguments
* $id_theme **mixed**



### <a name="method-getThemes"></a>getThemes

```php
mixed ThemeCore::getThemes()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L60)




### <a name="method-hasColumns"></a>hasColumns

```php
mixed ThemeCore::hasColumns($page)
```





* Visibility: **public**
* Source: [classes/Theme.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L268)


#### Arguments
* $page **mixed**



### <a name="method-hasColumnsSettings"></a>hasColumnsSettings

```php
mixed ThemeCore::hasColumnsSettings($page)
```





* Visibility: **public**
* Source: [classes/Theme.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L278)


#### Arguments
* $page **mixed**



### <a name="method-hasLeftColumn"></a>hasLeftColumn

```php
mixed ThemeCore::hasLeftColumn($page)
```





* Visibility: **public**
* Source: [classes/Theme.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L288)


#### Arguments
* $page **mixed**



### <a name="method-hasRightColumn"></a>hasRightColumn

```php
mixed ThemeCore::hasRightColumn($page)
```





* Visibility: **public**
* Source: [classes/Theme.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L305)


#### Arguments
* $page **mixed**



### <a name="method-isUsed"></a>isUsed

```php
boolean ThemeCore::isUsed()
```

check if a theme is used by a shop



* Visibility: **public**
* Source: [classes/Theme.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L123)




### <a name="method-removeMetas"></a>removeMetas

```php
boolean ThemeCore::removeMetas()
```





* Visibility: **public**
* Source: [classes/Theme.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L336)




### <a name="method-toggleDefaultLeftColumn"></a>toggleDefaultLeftColumn

```php
mixed ThemeCore::toggleDefaultLeftColumn()
```





* Visibility: **public**
* Source: [classes/Theme.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L362)




### <a name="method-toggleDefaultRightColumn"></a>toggleDefaultRightColumn

```php
mixed ThemeCore::toggleDefaultRightColumn()
```





* Visibility: **public**
* Source: [classes/Theme.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L375)




### <a name="method-toggleResponsive"></a>toggleResponsive

```php
mixed ThemeCore::toggleResponsive()
```





* Visibility: **public**
* Source: [classes/Theme.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L345)




### <a name="method-updateMetas"></a>updateMetas

```php
mixed ThemeCore::updateMetas(array $metas, boolean $full_update)
```

update the table PREFIX_theme_meta for the current theme



* Visibility: **public**
* Source: [classes/Theme.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Theme.php#L244)


#### Arguments
* $metas **array**
* $full_update **boolean** - If true, all the meta of the theme will be deleted prior the insert, otherwise only the current $metas will be deleted


