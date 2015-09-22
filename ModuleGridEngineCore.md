ModuleGridEngineCore
===============






* Class name: ModuleGridEngineCore
* This is an **abstract** class
* Parent class: [Module](ModuleCore)
* This class is defined in [classes/module/ModuleGridEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L27)





Properties
----------


### $_type

    protected mixed $_type





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGridEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#29)


Methods
-------


### __construct

    mixed ModuleGridEngineCore::__construct($type)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGridEngine.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#31)


#### Arguments
* $type **mixed**



### install

    mixed ModuleGridEngineCore::install()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGridEngine.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#36)




### getGridEngines

    mixed ModuleGridEngineCore::getGridEngines()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/ModuleGridEngine.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#44)




### setValues

    mixed ModuleGridEngineCore::setValues($values)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#66)


#### Arguments
* $values **mixed**



### setTitle

    mixed ModuleGridEngineCore::setTitle($title)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#67)


#### Arguments
* $title **mixed**



### setSize

    mixed ModuleGridEngineCore::setSize($width, $height)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#68)


#### Arguments
* $width **mixed**
* $height **mixed**



### setTotalCount

    mixed ModuleGridEngineCore::setTotalCount($total_count)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#69)


#### Arguments
* $total_count **mixed**



### setLimit

    mixed ModuleGridEngineCore::setLimit($start, $limit)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#70)


#### Arguments
* $start **mixed**
* $limit **mixed**



### render

    mixed ModuleGridEngineCore::render()





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#71)



