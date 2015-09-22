ModuleGraphEngineCore
===============






* Class name: ModuleGraphEngineCore
* This is an **abstract** class
* Parent class: [Module](ModuleCore)
* This class is defined in [classes/module/ModuleGraphEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#L27)





Properties
----------


### $_type

    protected mixed $_type





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraphEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#29)


Methods
-------


### __construct

    mixed ModuleGraphEngineCore::__construct($type)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraphEngine.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#31)


#### Arguments
* $type **mixed**



### install

    mixed ModuleGraphEngineCore::install()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraphEngine.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#36)




### getGraphEngines

    mixed ModuleGraphEngineCore::getGraphEngines()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/ModuleGraphEngine.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#44)




### createValues

    mixed ModuleGraphEngineCore::createValues($values)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGraphEngine.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#66)


#### Arguments
* $values **mixed**



### setSize

    mixed ModuleGraphEngineCore::setSize($width, $height)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGraphEngine.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#67)


#### Arguments
* $width **mixed**
* $height **mixed**



### setLegend

    mixed ModuleGraphEngineCore::setLegend($legend)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGraphEngine.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#68)


#### Arguments
* $legend **mixed**



### setTitles

    mixed ModuleGraphEngineCore::setTitles($titles)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGraphEngine.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#69)


#### Arguments
* $titles **mixed**



### draw

    mixed ModuleGraphEngineCore::draw()





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGraphEngine.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraphEngine.php#70)



