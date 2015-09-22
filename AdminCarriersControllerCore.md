AdminCarriersControllerCore
===============






* Class name: AdminCarriersControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)

* This class is defined in [controllers/admin/AdminCarriersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#30)





Properties
----------


### $position_identifier

    protected mixed $position_identifier = 'id_carrier'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCarriersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#32)


### $object

    public \Carrier $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCarriersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#30)


Methods
-------


### __construct

    mixed AdminCarriersControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#34)




### initToolbar

    mixed AdminCarriersControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#118)




### initPageHeaderToolbar

    mixed AdminCarriersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#127)




### renderView

    mixed AdminCarriersControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#141)




### renderList

    mixed AdminCarriersControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#151)




### renderForm

    mixed AdminCarriersControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#159)




### postProcess

    mixed AdminCarriersControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#412)




### processIsFree

    mixed AdminCarriersControllerCore::processIsFree()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#539)




### getFieldsValues

    mixed AdminCarriersControllerCore::getFieldsValues(object $obj)

Overload the property $fields_value



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#557)


#### Arguments
* $obj **object**



### beforeDelete

    integer AdminCarriersControllerCore::beforeDelete(\Carrier $object)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarriersController.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#606)


#### Arguments
* $object **[Carrier](CarrierCore)**



### changeGroups

    mixed AdminCarriersControllerCore::changeGroups($id_carrier, $delete)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarriersController.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#611)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### changeZones

    mixed AdminCarriersControllerCore::changeZones($id)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#627)


#### Arguments
* $id **mixed**



### getList

    mixed AdminCarriersControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

Modifying initial getList method to display position feature (drag and drop)



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#658)


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
* This method is defined in [controllers/admin/AdminCarriersController.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#669)




### displayEditLink

    mixed AdminCarriersControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#694)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayDeleteLink

    mixed AdminCarriersControllerCore::displayDeleteLink($token, $id, $name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarriersController.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#714)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### initTabModuleList

    mixed AdminCarriersControllerCore::initTabModuleList()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarriersController.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#753)



