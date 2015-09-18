AdminCarriersControllerCore
===============






* Class name: AdminCarriersControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $position_identifier

    protected mixed $position_identifier = 'id_carrier'





* Visibility: **protected**


### $object

    public \Carrier $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminCarriersControllerCore::__construct()





* Visibility: **public**




### initToolbar

    mixed AdminCarriersControllerCore::initToolbar()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminCarriersControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderView

    mixed AdminCarriersControllerCore::renderView()





* Visibility: **public**




### renderList

    mixed AdminCarriersControllerCore::renderList()





* Visibility: **public**




### renderForm

    mixed AdminCarriersControllerCore::renderForm()





* Visibility: **public**




### postProcess

    mixed AdminCarriersControllerCore::postProcess()





* Visibility: **public**




### processIsFree

    mixed AdminCarriersControllerCore::processIsFree()





* Visibility: **public**




### getFieldsValues

    mixed AdminCarriersControllerCore::getFieldsValues(object $obj)

Overload the property $fields_value



* Visibility: **public**


#### Arguments
* $obj **object**



### beforeDelete

    integer AdminCarriersControllerCore::beforeDelete(\Carrier $object)





* Visibility: **protected**


#### Arguments
* $object **Carrier**



### changeGroups

    mixed AdminCarriersControllerCore::changeGroups($id_carrier, $delete)





* Visibility: **protected**


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### changeZones

    mixed AdminCarriersControllerCore::changeZones($id)





* Visibility: **public**


#### Arguments
* $id **mixed**



### getList

    mixed AdminCarriersControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

Modifying initial getList method to display position feature (drag and drop)



* Visibility: **public**


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### ajaxProcessUpdatePositions

    mixed AdminCarriersControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**




### displayEditLink

    mixed AdminCarriersControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayDeleteLink

    mixed AdminCarriersControllerCore::displayDeleteLink($token, $id, $name)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### initTabModuleList

    mixed AdminCarriersControllerCore::initTabModuleList()





* Visibility: **protected**



