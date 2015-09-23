Class ChartCore
=====================





* Class name: ChartCore
* Source: [classes/Chart.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L28)


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
* Source: [classes/Chart.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L42).


### <a name="property-$format"></a>$format

```php
protected mixed $format
```





* Visibility: **protected**
* Source: [classes/Chart.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L39).


### <a name="property-$from"></a>$from

```php
protected mixed $from
```





* Visibility: **protected**
* Source: [classes/Chart.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L37).


### <a name="property-$granularity"></a>$granularity

```php
protected mixed $granularity
```





* Visibility: **protected**
* Source: [classes/Chart.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L40).


### <a name="property-$height"></a>$height

```php
protected mixed $height = 300
```





* Visibility: **protected**
* Source: [classes/Chart.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L33).


### <a name="property-$poolId"></a>$poolId

```php
protected mixed $poolId
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Chart.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L30).


### <a name="property-$timeMode"></a>$timeMode

```php
protected mixed $timeMode = false
```





* Visibility: **protected**
* Source: [classes/Chart.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L36).


### <a name="property-$to"></a>$to

```php
protected mixed $to
```





* Visibility: **protected**
* Source: [classes/Chart.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L38).


### <a name="property-$width"></a>$width

```php
protected mixed $width = 600
```





* Visibility: **protected**
* Source: [classes/Chart.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ChartCore::__construct()
```





* Visibility: **public**
* Source: [classes/Chart.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L55)




### <a name="method-display"></a>display

```php
mixed ChartCore::display()
```





* Visibility: **public**
* Source: [classes/Chart.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L99)




### <a name="method-fetch"></a>fetch

```php
mixed ChartCore::fetch()
```





* Visibility: **public**
* Source: [classes/Chart.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L104)




### <a name="method-getCurve"></a>getCurve

```php
mixed ChartCore::getCurve($i)
```





* Visibility: **public**
* Source: [classes/Chart.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L91)


#### Arguments
* $i **mixed**



### <a name="method-init"></a>init

```php
mixed ChartCore::init()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Chart.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L45)




### <a name="method-setSize"></a>setSize

```php
mixed ChartCore::setSize($width, $height)
```





* Visibility: **public**
* Source: [classes/Chart.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L61)


#### Arguments
* $width **mixed**
* $height **mixed**



### <a name="method-setTimeMode"></a>setTimeMode

```php
mixed ChartCore::setTimeMode($from, $to, $granularity)
```





* Visibility: **public**
* Source: [classes/Chart.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Chart.php#L68)


#### Arguments
* $from **mixed**
* $to **mixed**
* $granularity **mixed**


