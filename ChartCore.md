ChartCore
===============






* Class name: ChartCore
* Namespace: 
* This class is defined in classes\Chart.php line 27





Properties
----------


### $poolId

    protected mixed $poolId





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Chart.php line 29


### $width

    protected mixed $width = 600





* Visibility: **protected**
* This property is defined in classes\Chart.php line 31


### $height

    protected mixed $height = 300





* Visibility: **protected**
* This property is defined in classes\Chart.php line 32


### $timeMode

    protected mixed $timeMode = false





* Visibility: **protected**
* This property is defined in classes\Chart.php line 35


### $from

    protected mixed $from





* Visibility: **protected**
* This property is defined in classes\Chart.php line 36


### $to

    protected mixed $to





* Visibility: **protected**
* This property is defined in classes\Chart.php line 37


### $format

    protected mixed $format





* Visibility: **protected**
* This property is defined in classes\Chart.php line 38


### $granularity

    protected mixed $granularity





* Visibility: **protected**
* This property is defined in classes\Chart.php line 39


### $curves

    protected mixed $curves = array()





* Visibility: **protected**
* This property is defined in classes\Chart.php line 41


Methods
-------


### init

    mixed ChartCore::init()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Chart.php line 44




### __construct

    mixed ChartCore::__construct()





* Visibility: **public**
* This method is defined in classes\Chart.php line 53




### setSize

    mixed ChartCore::setSize($width, $height)





* Visibility: **public**
* This method is defined in classes\Chart.php line 59


#### Arguments
* $width **mixed**
* $height **mixed**



### setTimeMode

    mixed ChartCore::setTimeMode($from, $to, $granularity)





* Visibility: **public**
* This method is defined in classes\Chart.php line 66


#### Arguments
* $from **mixed**
* $to **mixed**
* $granularity **mixed**



### getCurve

    mixed ChartCore::getCurve($i)





* Visibility: **public**
* This method is defined in classes\Chart.php line 95


#### Arguments
* $i **mixed**



### display

    mixed ChartCore::display()





* Visibility: **public**
* This method is defined in classes\Chart.php line 104




### fetch

    mixed ChartCore::fetch()





* Visibility: **public**
* This method is defined in classes\Chart.php line 109



