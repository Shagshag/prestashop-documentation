ModuleGridEngineCore
===============






* Class name: ModuleGridEngineCore
* This is an **abstract** class
* Parent class: [Module](ModuleCore)
* This class is defined in [classes/module/ModuleGridEngine.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L27)





Properties
----------

* [$_type](#property-$_type)

Methods
-------
* [__construct](#method-__construct)
* [install](#method-install)
* [getGridEngines](#method-getGridEngines)
* [setValues](#method-setValues)
* [setTitle](#method-setTitle)
* [setSize](#method-setSize)
* [setTotalCount](#method-setTotalCount)
* [setLimit](#method-setLimit)
* [render](#method-render)




Properties
----------


### <a name="property-$_type"></a>$_type

    protected mixed $_type





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGridEngine.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L29)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ModuleGridEngineCore::__construct($type)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGridEngine.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L31)


#### Arguments
* $type **mixed**



### <a name="method-install"></a>install

    mixed ModuleGridEngineCore::install()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGridEngine.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L36)




### <a name="method-getGridEngines"></a>getGridEngines

    mixed ModuleGridEngineCore::getGridEngines()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/ModuleGridEngine.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L44)




### <a name="method-setValues"></a>setValues

    mixed ModuleGridEngineCore::setValues($values)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L66)


#### Arguments
* $values **mixed**



### <a name="method-setTitle"></a>setTitle

    mixed ModuleGridEngineCore::setTitle($title)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L67)


#### Arguments
* $title **mixed**



### <a name="method-setSize"></a>setSize

    mixed ModuleGridEngineCore::setSize($width, $height)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L68)


#### Arguments
* $width **mixed**
* $height **mixed**



### <a name="method-setTotalCount"></a>setTotalCount

    mixed ModuleGridEngineCore::setTotalCount($total_count)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L69)


#### Arguments
* $total_count **mixed**



### <a name="method-setLimit"></a>setLimit

    mixed ModuleGridEngineCore::setLimit($start, $limit)





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L70)


#### Arguments
* $start **mixed**
* $limit **mixed**



### <a name="method-render"></a>render

    mixed ModuleGridEngineCore::render()





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGridEngine.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGridEngine.php#L71)



