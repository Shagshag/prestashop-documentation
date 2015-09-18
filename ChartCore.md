ChartCore
===============






* Class name: ChartCore
* Namespace: 





Properties
----------


### $poolId

    protected mixed $poolId





* Visibility: **protected**
* This property is **static**.


### $width

    protected mixed $width = 600





* Visibility: **protected**


### $height

    protected mixed $height = 300





* Visibility: **protected**


### $timeMode

    protected mixed $timeMode = false





* Visibility: **protected**


### $from

    protected mixed $from





* Visibility: **protected**


### $to

    protected mixed $to





* Visibility: **protected**


### $format

    protected mixed $format





* Visibility: **protected**


### $granularity

    protected mixed $granularity





* Visibility: **protected**


### $curves

    protected mixed $curves = array()





* Visibility: **protected**


Methods
-------


### init

    mixed ChartCore::init()





* Visibility: **public**
* This method is **static**.




### __construct

    mixed ChartCore::__construct()





* Visibility: **public**




### setSize

    mixed ChartCore::setSize($width, $height)





* Visibility: **public**


#### Arguments
* $width **mixed**
* $height **mixed**



### setTimeMode

    mixed ChartCore::setTimeMode($from, $to, $granularity)





* Visibility: **public**


#### Arguments
* $from **mixed**
* $to **mixed**
* $granularity **mixed**



### getCurve

    mixed ChartCore::getCurve($i)





* Visibility: **public**


#### Arguments
* $i **mixed**



### display

    mixed ChartCore::display()





* Visibility: **public**




### fetch

    mixed ChartCore::fetch()





* Visibility: **public**



