Class ThemeCore
=====================





* Class name: ThemeCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Theme.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L27)


Contents
--------


### Properties

* [$access_rights](#property-$access_rights)
* [$definition](#property-$definition)
* [$directory](#property-$directory)
* [$name](#property-$name)

### Methods

* [add](#method-add)
* [getAvailable](#method-getAvailable)
* [getThemes](#method-getThemes)
* [isUsed](#method-isUsed)




Properties
----------


### <a name="property-$access_rights"></a>$access_rights

```php
public integer $access_rights = 509
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Theme.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'theme', 'primary' => 'id_theme', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64, 'required' => true), 'directory' => array('type' => self::TYPE_STRING, 'validate' => 'isDirName', 'size' => 64, 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Theme.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L37).


### <a name="property-$directory"></a>$directory

```php
public mixed $directory
```





* Visibility: **public**
* Source: [classes/Theme.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L30).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Theme.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L29).


Methods
-------


### <a name="method-add"></a>add

```php
boolean ThemeCore::add(boolean $autodate, boolean $null_values)
```

add only theme if the directory exists



* Visibility: **public**
* Source: [classes/Theme.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L106)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-getAvailable"></a>getAvailable

```php
array ThemeCore::getAvailable(boolean $installed_only)
```

return an array of all available theme (installed or not)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L59)


#### Arguments
* $installed_only **boolean**



### <a name="method-getThemes"></a>getThemes

```php
mixed ThemeCore::getThemes()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L46)




### <a name="method-isUsed"></a>isUsed

```php
boolean ThemeCore::isUsed()
```

check if a theme is used by a shop



* Visibility: **public**
* Source: [classes/Theme.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Theme.php#L93)



