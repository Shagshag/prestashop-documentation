ChartCore
===============






* Class name: ChartCore
* This class is defined in [classes/Chart.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L27)





Properties
----------

* [$poolId](#property-$poolId)
* [$width](#property-$width)
* [$height](#property-$height)
* [$timeMode](#property-$timeMode)
* [$from](#property-$from)
* [$to](#property-$to)
* [$format](#property-$format)
* [$granularity](#property-$granularity)
* [$curves](#property-$curves)

Methods
-------
* [init](#method-init)
* [__construct](#method-__construct)
* [setSize](#method-setSize)
* [setTimeMode](#method-setTimeMode)
* [getCurve](#method-getCurve)
* [display](#method-display)
* [fetch](#method-fetch)




Properties
----------


### <a name="property-$poolId"></a>$poolId

    protected mixed $poolId





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Chart.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L29)


### <a name="property-$width"></a>$width

    protected mixed $width = 600





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L31)


### <a name="property-$height"></a>$height

    protected mixed $height = 300





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L32)


### <a name="property-$timeMode"></a>$timeMode

    protected mixed $timeMode = false





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L35)


### <a name="property-$from"></a>$from

    protected mixed $from





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L36)


### <a name="property-$to"></a>$to

    protected mixed $to





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L37)


### <a name="property-$format"></a>$format

    protected mixed $format





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L38)


### <a name="property-$granularity"></a>$granularity

    protected mixed $granularity





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L39)


### <a name="property-$curves"></a>$curves

    protected mixed $curves = array()





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L41)


Methods
-------


### <a name="method-init"></a>init

    mixed ChartCore::init()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Chart.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L44)




### <a name="method-__construct"></a>__construct

    mixed ChartCore::__construct()





* Visibility: **public**
* This method is defined in [classes/Chart.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L53)




### <a name="method-setSize"></a>setSize

    mixed ChartCore::setSize($width, $height)





* Visibility: **public**
* This method is defined in [classes/Chart.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L59)


#### Arguments
* $width **mixed**
* $height **mixed**



### <a name="method-setTimeMode"></a>setTimeMode

    mixed ChartCore::setTimeMode($from, $to, $granularity)





* Visibility: **public**
* This method is defined in [classes/Chart.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L66)


#### Arguments
* $from **mixed**
* $to **mixed**
* $granularity **mixed**



### <a name="method-getCurve"></a>getCurve

    mixed ChartCore::getCurve($i)





* Visibility: **public**
* This method is defined in [classes/Chart.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L95)


#### Arguments
* $i **mixed**



### <a name="method-display"></a>display

    mixed ChartCore::display()





* Visibility: **public**
* This method is defined in [classes/Chart.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L104)




### <a name="method-fetch"></a>fetch

    mixed ChartCore::fetch()





* Visibility: **public**
* This method is defined in [classes/Chart.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#L109)



