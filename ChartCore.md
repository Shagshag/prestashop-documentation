ChartCore
===============






* Class name: ChartCore
* Namespace: 

* This class is defined in [classes/Chart.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#27)





Properties
----------


### $poolId

    protected mixed $poolId





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Chart.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#29)


### $width

    protected mixed $width = 600





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#31)


### $height

    protected mixed $height = 300





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#32)


### $timeMode

    protected mixed $timeMode = false





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#35)


### $from

    protected mixed $from





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#36)


### $to

    protected mixed $to





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#37)


### $format

    protected mixed $format





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#38)


### $granularity

    protected mixed $granularity





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#39)


### $curves

    protected mixed $curves = array()





* Visibility: **protected**
* This property is defined in [classes/Chart.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#41)


Methods
-------


### init

    mixed ChartCore::init()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Chart.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#44)




### __construct

    mixed ChartCore::__construct()





* Visibility: **public**
* This method is defined in [classes/Chart.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#53)




### setSize

    mixed ChartCore::setSize($width, $height)





* Visibility: **public**
* This method is defined in [classes/Chart.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#59)


#### Arguments
* $width **mixed**
* $height **mixed**



### setTimeMode

    mixed ChartCore::setTimeMode($from, $to, $granularity)





* Visibility: **public**
* This method is defined in [classes/Chart.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#66)


#### Arguments
* $from **mixed**
* $to **mixed**
* $granularity **mixed**



### getCurve

    mixed ChartCore::getCurve($i)





* Visibility: **public**
* This method is defined in [classes/Chart.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#95)


#### Arguments
* $i **mixed**



### display

    mixed ChartCore::display()





* Visibility: **public**
* This method is defined in [classes/Chart.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#104)




### fetch

    mixed ChartCore::fetch()





* Visibility: **public**
* This method is defined in [classes/Chart.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Chart.php#109)



