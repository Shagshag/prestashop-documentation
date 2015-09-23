Class ThemeCore
=====================





* Class name: ThemeCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Theme.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L27)


Contents
--------


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
* [getAvailable](#method-getAvailable)
* [getByDirectory](#method-getByDirectory)
* [getMetas](#method-getMetas)
* [getThemes](#method-getThemes)
* [hasLeftColumn](#method-hasLeftColumn)
* [hasRightColumn](#method-hasRightColumn)
* [isUsed](#method-isUsed)
* [removeMetas](#method-removeMetas)
* [toggleDefaultLeftColumn](#method-toggleDefaultLeftColumn)
* [toggleDefaultRightColumn](#method-toggleDefaultRightColumn)
* [toggleResponsive](#method-toggleResponsive)
* [updateMetas](#method-updateMetas)




Properties
----------


### <a name="property-$access_rights"></a>$access_rights

```php
public integer $access_rights = 509
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Theme.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L37).


### <a name="property-$default_left_column"></a>$default_left_column

```php
public mixed $default_left_column
```





* Visibility: **public**
* Source: [classes/Theme.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L32).


### <a name="property-$default_right_column"></a>$default_right_column

```php
public mixed $default_right_column
```





* Visibility: **public**
* Source: [classes/Theme.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'theme', 'primary' => 'id_theme', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64, 'required' => true), 'directory' => array('type' => self::TYPE_STRING, 'validate' => 'isDirName', 'size' => 64, 'required' => true), 'responsive' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_left_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_right_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_per_page' => array('type' => self::TYPE_INT, 'validate' => 'isInt')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Theme.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L41).


### <a name="property-$directory"></a>$directory

```php
public mixed $directory
```





* Visibility: **public**
* Source: [classes/Theme.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L30).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Theme.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L29).


### <a name="property-$product_per_page"></a>$product_per_page

```php
public mixed $product_per_page
```





* Visibility: **public**
* Source: [classes/Theme.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L34).


### <a name="property-$responsive"></a>$responsive

```php
public mixed $responsive
```





* Visibility: **public**
* Source: [classes/Theme.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L31).


Methods
-------


### <a name="method-add"></a>add

```php
boolean ThemeCore::add(boolean $autodate, boolean $null_values)
```

add only theme if the directory exists



* Visibility: **public**
* Source: [classes/Theme.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L114)


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
* Source: [classes/Theme.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L67)


#### Arguments
* $installed_only **boolean**



### <a name="method-getByDirectory"></a>getByDirectory

```php
boolean|\Theme ThemeCore::getByDirectory($directory)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L127)


#### Arguments
* $directory **mixed**



### <a name="method-getMetas"></a>getMetas

```php
array|boolean ThemeCore::getMetas()
```





* Visibility: **public**
* Source: [classes/Theme.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L206)




### <a name="method-getThemes"></a>getThemes

```php
mixed ThemeCore::getThemes()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Theme.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L54)




### <a name="method-hasLeftColumn"></a>hasLeftColumn

```php
mixed ThemeCore::hasLeftColumn($page)
```





* Visibility: **public**
* Source: [classes/Theme.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L170)


#### Arguments
* $page **mixed**



### <a name="method-hasRightColumn"></a>hasRightColumn

```php
mixed ThemeCore::hasRightColumn($page)
```





* Visibility: **public**
* Source: [classes/Theme.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L187)


#### Arguments
* $page **mixed**



### <a name="method-isUsed"></a>isUsed

```php
boolean ThemeCore::isUsed()
```

check if a theme is used by a shop



* Visibility: **public**
* Source: [classes/Theme.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L101)




### <a name="method-removeMetas"></a>removeMetas

```php
boolean ThemeCore::removeMetas()
```





* Visibility: **public**
* Source: [classes/Theme.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L217)




### <a name="method-toggleDefaultLeftColumn"></a>toggleDefaultLeftColumn

```php
mixed ThemeCore::toggleDefaultLeftColumn()
```





* Visibility: **public**
* Source: [classes/Theme.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L241)




### <a name="method-toggleDefaultRightColumn"></a>toggleDefaultRightColumn

```php
mixed ThemeCore::toggleDefaultRightColumn()
```





* Visibility: **public**
* Source: [classes/Theme.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L253)




### <a name="method-toggleResponsive"></a>toggleResponsive

```php
mixed ThemeCore::toggleResponsive()
```





* Visibility: **public**
* Source: [classes/Theme.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L225)




### <a name="method-updateMetas"></a>updateMetas

```php
mixed ThemeCore::updateMetas(array $metas, boolean $full_update)
```

update the table PREFIX_theme_meta for the current theme



* Visibility: **public**
* Source: [classes/Theme.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Theme.php#L146)


#### Arguments
* $metas **array**
* $full_update **boolean** - If true, all the meta of the theme will be deleted prior the insert, otherwise only the current $metas will be deleted


