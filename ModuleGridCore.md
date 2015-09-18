ModuleGridCore
===============






* Class name: ModuleGridCore
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


### $_totalCount

    protected integer $_totalCount





* Visibility: **protected**


### $_title

    protected mixed $_title





* Visibility: **protected**


### $_start

    protected mixed $_start





* Visibility: **protected**


### $_limit

    protected mixed $_limit





* Visibility: **protected**


### $_sort

    protected mixed $_sort = null





* Visibility: **protected**


### $_direction

    protected mixed $_direction = null





* Visibility: **protected**


### $_render

    protected \ModuleGridEngine $_render





* Visibility: **protected**


Methods
-------


### getData

    mixed ModuleGridCore::getData()





* Visibility: **protected**
* This method is **abstract**.




### setEmployee

    mixed ModuleGridCore::setEmployee($id_employee)





* Visibility: **public**


#### Arguments
* $id_employee **mixed**



### setLang

    mixed ModuleGridCore::setLang($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### create

    mixed ModuleGridCore::create($render, $type, $width, $height, $start, $limit, $sort, $dir)





* Visibility: **public**


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $start **mixed**
* $limit **mixed**
* $sort **mixed**
* $dir **mixed**



### render

    mixed ModuleGridCore::render()





* Visibility: **public**




### engine

    mixed ModuleGridCore::engine($params)





* Visibility: **public**


#### Arguments
* $params **mixed**



### csvExport

    mixed ModuleGridCore::csvExport($datas)





* Visibility: **protected**


#### Arguments
* $datas **mixed**



### _displayCsv

    mixed ModuleGridCore::_displayCsv()





* Visibility: **protected**




### getDate

    mixed ModuleGridCore::getDate()





* Visibility: **public**




### getLang

    mixed ModuleGridCore::getLang()





* Visibility: **public**



