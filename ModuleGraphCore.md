ModuleGraphCore
===============






* Class name: ModuleGraphCore
* Namespace: 
* This is an **abstract** class
* Parent class: Module





Properties
----------


### $_employee

    protected mixed $_employee





* Visibility: **protected**


### $_values

    protected array $_values = array()





* Visibility: **protected**


### $_legend

    protected array $_legend = array()





* Visibility: **protected**


### $_titles

    protected mixed $_titles = array('main' => null, 'x' => null, 'y' => null)





* Visibility: **protected**


### $_render

    protected \ModuleGraphEngine $_render





* Visibility: **protected**


Methods
-------


### getData

    mixed ModuleGraphCore::getData($layers)





* Visibility: **protected**
* This method is **abstract**.


#### Arguments
* $layers **mixed**



### setEmployee

    mixed ModuleGraphCore::setEmployee($id_employee)





* Visibility: **public**


#### Arguments
* $id_employee **mixed**



### setLang

    mixed ModuleGraphCore::setLang($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### setDateGraph

    mixed ModuleGraphCore::setDateGraph($layers, $legend)





* Visibility: **protected**


#### Arguments
* $layers **mixed**
* $legend **mixed**



### csvExport

    mixed ModuleGraphCore::csvExport($datas)





* Visibility: **protected**


#### Arguments
* $datas **mixed**



### _displayCsv

    mixed ModuleGraphCore::_displayCsv()





* Visibility: **protected**




### create

    mixed ModuleGraphCore::create($render, $type, $width, $height, $layers)





* Visibility: **public**


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $layers **mixed**



### draw

    mixed ModuleGraphCore::draw()





* Visibility: **public**




### setOption

    mixed ModuleGraphCore::setOption($option, $layers)





* Visibility: **public**


#### Arguments
* $option **mixed**
* $layers **mixed**



### engine

    mixed ModuleGraphCore::engine($params)





* Visibility: **public**


#### Arguments
* $params **mixed**



### getEmployee

    mixed ModuleGraphCore::getEmployee($employee, \Context $context)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $employee **mixed**
* $context **Context**



### getDate

    mixed ModuleGraphCore::getDate()





* Visibility: **public**




### getDateBetween

    mixed ModuleGraphCore::getDateBetween($employee)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $employee **mixed**



### getLang

    mixed ModuleGraphCore::getLang()





* Visibility: **public**



