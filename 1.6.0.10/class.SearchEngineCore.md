Class SearchEngineCore
=====================





* Class name: SearchEngineCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/SearchEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/SearchEngine.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$getvar](#property-$getvar)
* [$server](#property-$server)

### Methods

* [getKeywords](#method-getKeywords)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'search_engine', 'primary' => 'id_search_engine', 'fields' => array('server' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl', 'required' => true), 'getvar' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/SearchEngine.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/SearchEngine.php#L35).


### <a name="property-$getvar"></a>$getvar

```php
public mixed $getvar
```





* Visibility: **public**
* Source: [classes/SearchEngine.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/SearchEngine.php#L30).


### <a name="property-$server"></a>$server

```php
public mixed $server
```





* Visibility: **public**
* Source: [classes/SearchEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/SearchEngine.php#L29).


Methods
-------


### <a name="method-getKeywords"></a>getKeywords

```php
mixed SearchEngineCore::getKeywords($url)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/SearchEngine.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/SearchEngine.php#L44)


#### Arguments
* $url **mixed**


