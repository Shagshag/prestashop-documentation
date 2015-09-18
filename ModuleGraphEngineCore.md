ModuleGraphEngineCore
===============






* Class name: ModuleGraphEngineCore
* Namespace: 
* This is an **abstract** class
* Parent class: Module





Properties
----------


### $_type

    protected mixed $_type





* Visibility: **protected**


Methods
-------


### __construct

    mixed ModuleGraphEngineCore::__construct($type)





* Visibility: **public**


#### Arguments
* $type **mixed**



### install

    mixed ModuleGraphEngineCore::install()





* Visibility: **public**




### getGraphEngines

    mixed ModuleGraphEngineCore::getGraphEngines()





* Visibility: **public**
* This method is **static**.




### createValues

    mixed ModuleGraphEngineCore::createValues($values)





* Visibility: **public**
* This method is **abstract**.


#### Arguments
* $values **mixed**



### setSize

    mixed ModuleGraphEngineCore::setSize($width, $height)





* Visibility: **public**
* This method is **abstract**.


#### Arguments
* $width **mixed**
* $height **mixed**



### setLegend

    mixed ModuleGraphEngineCore::setLegend($legend)





* Visibility: **public**
* This method is **abstract**.


#### Arguments
* $legend **mixed**



### setTitles

    mixed ModuleGraphEngineCore::setTitles($titles)





* Visibility: **public**
* This method is **abstract**.


#### Arguments
* $titles **mixed**



### draw

    mixed ModuleGraphEngineCore::draw()





* Visibility: **public**
* This method is **abstract**.



