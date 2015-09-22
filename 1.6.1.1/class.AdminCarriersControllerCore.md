Class AdminCarriersControllerCore
=====================





* Class name: AdminCarriersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarriersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L30)



Properties
----------

* [$object](#property-$object)
* [$position_identifier](#property-$position_identifier)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [beforeDelete](#method-beforeDelete)
* [changeGroups](#method-changeGroups)
* [changeZones](#method-changeZones)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayEditLink](#method-displayEditLink)
* [getFieldsValues](#method-getFieldsValues)
* [getList](#method-getList)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initTabModuleList](#method-initTabModuleList)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [processIsFree](#method-processIsFree)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$object"></a>$object

    public \Carrier $object





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

    protected mixed $position_identifier = 'id_carrier'





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCarriersControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L34)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

    mixed AdminCarriersControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L669)




### <a name="method-beforeDelete"></a>beforeDelete

    integer AdminCarriersControllerCore::beforeDelete(\Carrier $object)





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L606)


#### Arguments
* $object **[Carrier](class.CarrierCore.md)**



### <a name="method-changeGroups"></a>changeGroups

    mixed AdminCarriersControllerCore::changeGroups($id_carrier, $delete)





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L611)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

    mixed AdminCarriersControllerCore::changeZones($id)





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L627)


#### Arguments
* $id **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

    mixed AdminCarriersControllerCore::displayDeleteLink($token, $id, $name)





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L714)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

    mixed AdminCarriersControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L694)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-getFieldsValues"></a>getFieldsValues

    mixed AdminCarriersControllerCore::getFieldsValues(object $obj)

Overload the property $fields_value



* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L557)


#### Arguments
* $obj **object**



### <a name="method-getList"></a>getList

    mixed AdminCarriersControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

Modifying initial getList method to display position feature (drag and drop)



* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L658)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCarriersControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L127)




### <a name="method-initTabModuleList"></a>initTabModuleList

    mixed AdminCarriersControllerCore::initTabModuleList()





* Visibility: **protected**
* Source: [controllers/admin/AdminCarriersController.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L753)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminCarriersControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L118)




### <a name="method-postProcess"></a>postProcess

    mixed AdminCarriersControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L412)




### <a name="method-processIsFree"></a>processIsFree

    mixed AdminCarriersControllerCore::processIsFree()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L539)




### <a name="method-renderForm"></a>renderForm

    mixed AdminCarriersControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L159)




### <a name="method-renderList"></a>renderList

    mixed AdminCarriersControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L151)




### <a name="method-renderView"></a>renderView

    mixed AdminCarriersControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminCarriersController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarriersController.php#L141)



