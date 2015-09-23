Class ChartCore
=====================





* Class name: ChartCore
* Source: [classes/Chart.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L27)


Contents
--------


### Properties

* [$curves](#property-$curves)
* [$format](#property-$format)
* [$from](#property-$from)
* [$granularity](#property-$granularity)
* [$height](#property-$height)
* [$poolId](#property-$poolId)
* [$timeMode](#property-$timeMode)
* [$to](#property-$to)
* [$width](#property-$width)

### Methods

* [__construct](#method-__construct)
* [display](#method-display)
* [fetch](#method-fetch)
* [getCurve](#method-getCurve)
* [init](#method-init)
* [setSize](#method-setSize)
* [setTimeMode](#method-setTimeMode)




Properties
----------


### <a name="property-$curves"></a>$curves

```php
protected mixed $curves = array()
```





* Visibility: **protected**
* Source: [classes/Chart.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L41).


### <a name="property-$format"></a>$format

```php
protected mixed $format
```





* Visibility: **protected**
* Source: [classes/Chart.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L38).


### <a name="property-$from"></a>$from

```php
protected mixed $from
```





* Visibility: **protected**
* Source: [classes/Chart.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L36).


### <a name="property-$granularity"></a>$granularity

```php
protected mixed $granularity
```





* Visibility: **protected**
* Source: [classes/Chart.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L39).


### <a name="property-$height"></a>$height

```php
protected mixed $height = 300
```





* Visibility: **protected**
* Source: [classes/Chart.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L32).


### <a name="property-$poolId"></a>$poolId

```php
protected mixed $poolId
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Chart.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L29).


### <a name="property-$timeMode"></a>$timeMode

```php
protected mixed $timeMode = false
```





* Visibility: **protected**
* Source: [classes/Chart.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L35).


### <a name="property-$to"></a>$to

```php
protected mixed $to
```





* Visibility: **protected**
* Source: [classes/Chart.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L37).


### <a name="property-$width"></a>$width

```php
protected mixed $width = 600
```





* Visibility: **protected**
* Source: [classes/Chart.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L31).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ChartCore::__construct()
```





* Visibility: **public**
* Source: [classes/Chart.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L54)




### <a name="method-display"></a>display

```php
mixed ChartCore::display()
```





* Visibility: **public**
* Source: [classes/Chart.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L98)




### <a name="method-fetch"></a>fetch

```php
mixed ChartCore::fetch()
```





* Visibility: **public**
* Source: [classes/Chart.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L103)




### <a name="method-getCurve"></a>getCurve

```php
mixed ChartCore::getCurve($i)
```





* Visibility: **public**
* Source: [classes/Chart.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L90)


#### Arguments
* $i **mixed**



### <a name="method-init"></a>init

```php
mixed ChartCore::init()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Chart.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L44)




### <a name="method-setSize"></a>setSize

```php
mixed ChartCore::setSize($width, $height)
```





* Visibility: **public**
* Source: [classes/Chart.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L60)


#### Arguments
* $width **mixed**
* $height **mixed**



### <a name="method-setTimeMode"></a>setTimeMode

```php
mixed ChartCore::setTimeMode($from, $to, $granularity)
```





* Visibility: **public**
* Source: [classes/Chart.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/Chart.php#L67)


#### Arguments
* $from **mixed**
* $to **mixed**
* $granularity **mixed**


