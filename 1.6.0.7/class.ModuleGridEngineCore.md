Class ModuleGridEngineCore
=====================





* Class name: ModuleGridEngineCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ModuleGridEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L27)


Contents
--------


### Properties

* [$_type](#property-$_type)

### Methods

* [__construct](#method-__construct)
* [getGridEngines](#method-getGridEngines)
* [install](#method-install)
* [render](#method-render)
* [setLimit](#method-setLimit)
* [setSize](#method-setSize)
* [setTitle](#method-setTitle)
* [setTotalCount](#method-setTotalCount)
* [setValues](#method-setValues)




Properties
----------


### <a name="property-$_type"></a>$_type

```php
protected mixed $_type
```





* Visibility: **protected**
* Source: [classes/module/ModuleGridEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleGridEngineCore::__construct($type)
```





* Visibility: **public**
* Source: [classes/module/ModuleGridEngine.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L31)


#### Arguments
* $type **mixed**



### <a name="method-getGridEngines"></a>getGridEngines

```php
mixed ModuleGridEngineCore::getGridEngines()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/ModuleGridEngine.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L43)




### <a name="method-install"></a>install

```php
mixed ModuleGridEngineCore::install()
```





* Visibility: **public**
* Source: [classes/module/ModuleGridEngine.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L36)




### <a name="method-render"></a>render

```php
mixed ModuleGridEngineCore::render()
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGridEngine.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L70)




### <a name="method-setLimit"></a>setLimit

```php
mixed ModuleGridEngineCore::setLimit($start, $limit)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGridEngine.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L69)


#### Arguments
* $start **mixed**
* $limit **mixed**



### <a name="method-setSize"></a>setSize

```php
mixed ModuleGridEngineCore::setSize($width, $height)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGridEngine.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L67)


#### Arguments
* $width **mixed**
* $height **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed ModuleGridEngineCore::setTitle($title)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGridEngine.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L66)


#### Arguments
* $title **mixed**



### <a name="method-setTotalCount"></a>setTotalCount

```php
mixed ModuleGridEngineCore::setTotalCount($totalCount)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGridEngine.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L68)


#### Arguments
* $totalCount **mixed**



### <a name="method-setValues"></a>setValues

```php
mixed ModuleGridEngineCore::setValues($values)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ModuleGridEngine.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/module/ModuleGridEngine.php#L65)


#### Arguments
* $values **mixed**


