Class ModuleGraphCore
=====================





* Class name: ModuleGraphCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ModuleGraph.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L27)


Contents
--------


### Properties

* [$_employee](#property-$_employee)
* [$_legend](#property-$_legend)
* [$_render](#property-$_render)
* [$_titles](#property-$_titles)
* [$_values](#property-$_values)

### Methods

* [_displayCsv](#method-_displayCsv)
* [create](#method-create)
* [csvExport](#method-csvExport)
* [draw](#method-draw)
* [engine](#method-engine)
* [getData](#method-getData)
* [getDate](#method-getDate)
* [getDateBetween](#method-getDateBetween)
* [getEmployee](#method-getEmployee)
* [getLang](#method-getLang)
* [setDateGraph](#method-setDateGraph)
* [setEmployee](#method-setEmployee)
* [setLang](#method-setLang)
* [setOption](#method-setOption)




Properties
----------


### <a name="property-$_employee"></a>$_employee

```php
protected mixed $_employee
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L29).


### <a name="property-$_legend"></a>$_legend

```php
protected array $_legend = array()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L35).


### <a name="property-$_render"></a>$_render

```php
protected \ModuleGraphEngine $_render
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L41).


### <a name="property-$_titles"></a>$_titles

```php
protected mixed $_titles = array('main' => null, 'x' => null, 'y' => null)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L38).


### <a name="property-$_values"></a>$_values

```php
protected array $_values = array()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L32).


Methods
-------


### <a name="method-_displayCsv"></a>_displayCsv

```php
mixed ModuleGraphCore::_displayCsv()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L224)




### <a name="method-create"></a>create

```php
mixed ModuleGraphCore::create($render, $type, $width, $height, $layers)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L234)


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $layers **mixed**



### <a name="method-csvExport"></a>csvExport

```php
mixed ModuleGraphCore::csvExport($datas)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L160)


#### Arguments
* $datas **mixed**



### <a name="method-draw"></a>draw

```php
mixed ModuleGraphCore::draw()
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L250)




### <a name="method-engine"></a>engine

```php
mixed ModuleGraphCore::engine($params)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L262)


#### Arguments
* $params **mixed**



### <a name="method-getData"></a>getData

```php
mixed ModuleGraphCore::getData($layers)
```





* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/module/ModuleGraph.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L43)


#### Arguments
* $layers **mixed**



### <a name="method-getDate"></a>getDate

```php
mixed ModuleGraphCore::getDate()
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L318)




### <a name="method-getDateBetween"></a>getDateBetween

```php
mixed ModuleGraphCore::getDateBetween($employee)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/ModuleGraph.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L323)


#### Arguments
* $employee **mixed**



### <a name="method-getEmployee"></a>getEmployee

```php
mixed ModuleGraphCore::getEmployee($employee, \Context $context)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/ModuleGraph.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L295)


#### Arguments
* $employee **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getLang"></a>getLang

```php
mixed ModuleGraphCore::getLang()
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L330)




### <a name="method-setDateGraph"></a>setDateGraph

```php
mixed ModuleGraphCore::setDateGraph($layers, $legend)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L55)


#### Arguments
* $layers **mixed**
* $legend **mixed**



### <a name="method-setEmployee"></a>setEmployee

```php
mixed ModuleGraphCore::setEmployee($id_employee)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L45)


#### Arguments
* $id_employee **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed ModuleGraphCore::setLang($id_lang)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L50)


#### Arguments
* $id_lang **mixed**



### <a name="method-setOption"></a>setOption

```php
mixed ModuleGraphCore::setOption($option, $layers)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/module/ModuleGraph.php#L258)


#### Arguments
* $option **mixed**
* $layers **mixed**


