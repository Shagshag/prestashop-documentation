ModuleGraphCore
===============






* Class name: ModuleGraphCore
* This is an **abstract** class
* Parent class: [Module](ModuleCore)
* This class is defined in [classes/module/ModuleGraph.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L27)





Properties
----------

* [$_employee](#property-$_employee)
* [$_values](#property-$_values)
* [$_legend](#property-$_legend)
* [$_titles](#property-$_titles)
* [$_render](#property-$_render)

Methods
-------
* [getData](#method-getData)
* [setEmployee](#method-setEmployee)
* [setLang](#method-setLang)
* [setDateGraph](#method-setDateGraph)
* [csvExport](#method-csvExport)
* [_displayCsv](#method-_displayCsv)
* [create](#method-create)
* [draw](#method-draw)
* [setOption](#method-setOption)
* [engine](#method-engine)
* [getEmployee](#method-getEmployee)
* [getDate](#method-getDate)
* [getDateBetween](#method-getDateBetween)
* [getLang](#method-getLang)




Properties
----------


### <a name="property-$_employee"></a>$_employee

    protected mixed $_employee





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L29)


### <a name="property-$_values"></a>$_values

    protected array $_values = array()





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L32)


### <a name="property-$_legend"></a>$_legend

    protected array $_legend = array()





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L35)


### <a name="property-$_titles"></a>$_titles

    protected mixed $_titles = array('main' => null, 'x' => null, 'y' => null)





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L38)


### <a name="property-$_render"></a>$_render

    protected \ModuleGraphEngine $_render





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L41)


Methods
-------


### <a name="method-getData"></a>getData

    mixed ModuleGraphCore::getData($layers)





* Visibility: **protected**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGraph.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L43)


#### Arguments
* $layers **mixed**



### <a name="method-setEmployee"></a>setEmployee

    mixed ModuleGraphCore::setEmployee($id_employee)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L45)


#### Arguments
* $id_employee **mixed**



### <a name="method-setLang"></a>setLang

    mixed ModuleGraphCore::setLang($id_lang)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L50)


#### Arguments
* $id_lang **mixed**



### <a name="method-setDateGraph"></a>setDateGraph

    mixed ModuleGraphCore::setDateGraph($layers, $legend)





* Visibility: **protected**
* This method is defined in [classes/module/ModuleGraph.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L55)


#### Arguments
* $layers **mixed**
* $legend **mixed**



### <a name="method-csvExport"></a>csvExport

    mixed ModuleGraphCore::csvExport($datas)





* Visibility: **protected**
* This method is defined in [classes/module/ModuleGraph.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L167)


#### Arguments
* $datas **mixed**



### <a name="method-_displayCsv"></a>_displayCsv

    mixed ModuleGraphCore::_displayCsv()





* Visibility: **protected**
* This method is defined in [classes/module/ModuleGraph.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L234)




### <a name="method-create"></a>create

    mixed ModuleGraphCore::create($render, $type, $width, $height, $layers)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L245)


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $layers **mixed**



### <a name="method-draw"></a>draw

    mixed ModuleGraphCore::draw()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L263)




### <a name="method-setOption"></a>setOption

    mixed ModuleGraphCore::setOption($option, $layers)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L271)


#### Arguments
* $option **mixed**
* $layers **mixed**



### <a name="method-engine"></a>engine

    mixed ModuleGraphCore::engine($params)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L275)


#### Arguments
* $params **mixed**



### <a name="method-getEmployee"></a>getEmployee

    mixed ModuleGraphCore::getEmployee($employee, \Context $context)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/module/ModuleGraph.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L315)


#### Arguments
* $employee **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getDate"></a>getDate

    mixed ModuleGraphCore::getDate()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L340)




### <a name="method-getDateBetween"></a>getDateBetween

    mixed ModuleGraphCore::getDateBetween($employee)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/ModuleGraph.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L345)


#### Arguments
* $employee **mixed**



### <a name="method-getLang"></a>getLang

    mixed ModuleGraphCore::getLang()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#L353)



