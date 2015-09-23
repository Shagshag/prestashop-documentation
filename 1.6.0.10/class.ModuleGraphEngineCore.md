Class ModuleGraphEngineCore
=====================





* Class name: ModuleGraphEngineCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ModuleGraphEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L27)


Contents
--------


### Properties

* [$_type](#property-$_type)

### Methods

* [__construct](#method-__construct)
* [createValues](#method-createValues)
* [draw](#method-draw)
* [getGraphEngines](#method-getGraphEngines)
* [install](#method-install)
* [setLegend](#method-setLegend)
* [setSize](#method-setSize)
* [setTitles](#method-setTitles)




Properties
----------


### <a name="property-$_type"></a>$_type

```php
protected mixed $_type
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraphEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleGraphEngineCore::__construct($type)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraphEngine.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L31)


#### Arguments
* $type **mixed**



### <a name="method-createValues"></a>createValues

```php
mixed ModuleGraphEngineCore::createValues($values)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGraphEngine.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L65)


#### Arguments
* $values **mixed**



### <a name="method-draw"></a>draw

```php
mixed ModuleGraphEngineCore::draw()
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGraphEngine.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L69)




### <a name="method-getGraphEngines"></a>getGraphEngines

```php
mixed ModuleGraphEngineCore::getGraphEngines()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/ModuleGraphEngine.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L43)




### <a name="method-install"></a>install

```php
mixed ModuleGraphEngineCore::install()
```





* Visibility: **public**
* Source: [classes/module/ModuleGraphEngine.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L36)




### <a name="method-setLegend"></a>setLegend

```php
mixed ModuleGraphEngineCore::setLegend($legend)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGraphEngine.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L67)


#### Arguments
* $legend **mixed**



### <a name="method-setSize"></a>setSize

```php
mixed ModuleGraphEngineCore::setSize($width, $height)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGraphEngine.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L66)


#### Arguments
* $width **mixed**
* $height **mixed**



### <a name="method-setTitles"></a>setTitles

```php
mixed ModuleGraphEngineCore::setTitles($titles)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGraphEngine.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/module/ModuleGraphEngine.php#L68)


#### Arguments
* $titles **mixed**


