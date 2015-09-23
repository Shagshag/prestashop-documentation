Class ModuleGridCore
=====================





* Class name: ModuleGridCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ModuleGrid.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L27)


Contents
--------


### Properties

* [$_direction](#property-$_direction)
* [$_employee](#property-$_employee)
* [$_limit](#property-$_limit)
* [$_render](#property-$_render)
* [$_sort](#property-$_sort)
* [$_start](#property-$_start)
* [$_title](#property-$_title)
* [$_totalCount](#property-$_totalCount)
* [$_values](#property-$_values)

### Methods

* [_displayCsv](#method-_displayCsv)
* [create](#method-create)
* [csvExport](#method-csvExport)
* [engine](#method-engine)
* [getData](#method-getData)
* [getDate](#method-getDate)
* [getLang](#method-getLang)
* [render](#method-render)
* [setEmployee](#method-setEmployee)
* [setLang](#method-setLang)




Properties
----------


### <a name="property-$_direction"></a>$_direction

```php
protected mixed $_direction = null
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L50).


### <a name="property-$_employee"></a>$_employee

```php
protected mixed $_employee
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L29).


### <a name="property-$_limit"></a>$_limit

```php
protected mixed $_limit
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L44).


### <a name="property-$_render"></a>$_render

```php
protected \ModuleGridEngine $_render
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L53).


### <a name="property-$_sort"></a>$_sort

```php
protected mixed $_sort = null
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L47).


### <a name="property-$_start"></a>$_start

```php
protected mixed $_start
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L41).


### <a name="property-$_title"></a>$_title

```php
protected mixed $_title
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L38).


### <a name="property-$_totalCount"></a>$_totalCount

```php
protected integer $_totalCount
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L35).


### <a name="property-$_values"></a>$_values

```php
protected array $_values = array()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L32).


Methods
-------


### <a name="method-_displayCsv"></a>_displayCsv

```php
mixed ModuleGridCore::_displayCsv()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L165)




### <a name="method-create"></a>create

```php
mixed ModuleGridCore::create($render, $type, $width, $height, $start, $limit, $sort, $dir)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L67)


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $start **mixed**
* $limit **mixed**
* $sort **mixed**
* $dir **mixed**



### <a name="method-csvExport"></a>csvExport

```php
mixed ModuleGridCore::csvExport($datas)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L138)


#### Arguments
* $datas **mixed**



### <a name="method-engine"></a>engine

```php
mixed ModuleGridCore::engine($params)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L95)


#### Arguments
* $params **mixed**



### <a name="method-getData"></a>getData

```php
mixed ModuleGridCore::getData()
```





* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/module/ModuleGrid.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L55)




### <a name="method-getDate"></a>getDate

```php
mixed ModuleGridCore::getDate()
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L175)




### <a name="method-getLang"></a>getLang

```php
mixed ModuleGridCore::getLang()
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L180)




### <a name="method-render"></a>render

```php
mixed ModuleGridCore::render()
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L90)




### <a name="method-setEmployee"></a>setEmployee

```php
mixed ModuleGridCore::setEmployee($id_employee)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L57)


#### Arguments
* $id_employee **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed ModuleGridCore::setLang($id_lang)
```





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/module/ModuleGrid.php#L62)


#### Arguments
* $id_lang **mixed**


