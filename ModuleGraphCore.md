ModuleGraphCore
===============






* Class name: ModuleGraphCore
* Namespace: 
* This is an **abstract** class
* Parent class: [Module](ModuleCore)

* This class is defined in [classes/module/ModuleGraph.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#27)





Properties
----------


### $_employee

    protected mixed $_employee





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#29)


### $_values

    protected array $_values = array()





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#32)


### $_legend

    protected array $_legend = array()





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#35)


### $_titles

    protected mixed $_titles = array('main' => null, 'x' => null, 'y' => null)





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#38)


### $_render

    protected \ModuleGraphEngine $_render





* Visibility: **protected**
* This property is defined in [classes/module/ModuleGraph.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#41)


Methods
-------


### getData

    mixed ModuleGraphCore::getData($layers)





* Visibility: **protected**
* This method is **abstract**.
* This method is defined in [classes/module/ModuleGraph.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#43)


#### Arguments
* $layers **mixed**



### setEmployee

    mixed ModuleGraphCore::setEmployee($id_employee)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#45)


#### Arguments
* $id_employee **mixed**



### setLang

    mixed ModuleGraphCore::setLang($id_lang)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#50)


#### Arguments
* $id_lang **mixed**



### setDateGraph

    mixed ModuleGraphCore::setDateGraph($layers, $legend)





* Visibility: **protected**
* This method is defined in [classes/module/ModuleGraph.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#55)


#### Arguments
* $layers **mixed**
* $legend **mixed**



### csvExport

    mixed ModuleGraphCore::csvExport($datas)





* Visibility: **protected**
* This method is defined in [classes/module/ModuleGraph.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#167)


#### Arguments
* $datas **mixed**



### _displayCsv

    mixed ModuleGraphCore::_displayCsv()





* Visibility: **protected**
* This method is defined in [classes/module/ModuleGraph.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#234)




### create

    mixed ModuleGraphCore::create($render, $type, $width, $height, $layers)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#245)


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $layers **mixed**



### draw

    mixed ModuleGraphCore::draw()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#263)




### setOption

    mixed ModuleGraphCore::setOption($option, $layers)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#271)


#### Arguments
* $option **mixed**
* $layers **mixed**



### engine

    mixed ModuleGraphCore::engine($params)





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#275)


#### Arguments
* $params **mixed**



### getEmployee

    mixed ModuleGraphCore::getEmployee($employee, \Context $context)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/module/ModuleGraph.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#315)


#### Arguments
* $employee **mixed**
* $context **[Context](ContextCore)**



### getDate

    mixed ModuleGraphCore::getDate()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#340)




### getDateBetween

    mixed ModuleGraphCore::getDateBetween($employee)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/ModuleGraph.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#345)


#### Arguments
* $employee **mixed**



### getLang

    mixed ModuleGraphCore::getLang()





* Visibility: **public**
* This method is defined in [classes/module/ModuleGraph.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGraph.php#353)



