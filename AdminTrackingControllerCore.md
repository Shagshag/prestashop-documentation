AdminTrackingControllerCore
===============






* Class name: AdminTrackingControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminTrackingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L30)





Properties
----------

* [$bootstrap](#property-$bootstrap)
* [$_helper_list](#property-$_helper_list)
* [$object](#property-$object)

Methods
-------
* [postprocess](#method-postprocess)
* [initContent](#method-initContent)
* [getCustomListCategoriesEmpty](#method-getCustomListCategoriesEmpty)
* [getCustomListProductsAttributesNoStock](#method-getCustomListProductsAttributesNoStock)
* [getCustomListProductsNoStock](#method-getCustomListProductsNoStock)
* [getCustomListProductsDisabled](#method-getCustomListProductsDisabled)
* [renderList](#method-renderList)
* [displayEnableLink](#method-displayEnableLink)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayEditLink](#method-displayEditLink)
* [clearFilters](#method-clearFilters)
* [clearListOptions](#method-clearListOptions)
* [getList](#method-getList)
* [getDescriptionClean](#method-getDescriptionClean)




Properties
----------


### <a name="property-$bootstrap"></a>$bootstrap

    public mixed $bootstrap = true





* Visibility: **public**
* This property is defined in [controllers/admin/AdminTrackingController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L32)


### <a name="property-$_helper_list"></a>$_helper_list

    protected \HelperList $_helper_list





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminTrackingController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L35)


### <a name="property-$object"></a>$object

    public \Product|\Category $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminTrackingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L30)


Methods
-------


### <a name="method-postprocess"></a>postprocess

    mixed AdminTrackingControllerCore::postprocess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L37)




### <a name="method-initContent"></a>initContent

    mixed AdminTrackingControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L56)




### <a name="method-getCustomListCategoriesEmpty"></a>getCustomListCategoriesEmpty

    mixed AdminTrackingControllerCore::getCustomListCategoriesEmpty()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L88)




### <a name="method-getCustomListProductsAttributesNoStock"></a>getCustomListProductsAttributesNoStock

    mixed AdminTrackingControllerCore::getCustomListProductsAttributesNoStock()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L125)




### <a name="method-getCustomListProductsNoStock"></a>getCustomListProductsNoStock

    mixed AdminTrackingControllerCore::getCustomListProductsNoStock()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L169)




### <a name="method-getCustomListProductsDisabled"></a>getCustomListProductsDisabled

    mixed AdminTrackingControllerCore::getCustomListProductsDisabled()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L213)




### <a name="method-renderList"></a>renderList

    mixed AdminTrackingControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L244)




### <a name="method-displayEnableLink"></a>displayEnableLink

    mixed AdminTrackingControllerCore::displayEnableLink($token, $id, $value, $active, $id_category, $id_product)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L277)


#### Arguments
* $token **mixed**
* $id **mixed**
* $value **mixed**
* $active **mixed**
* $id_category **mixed**
* $id_product **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

    mixed AdminTrackingControllerCore::displayDeleteLink($token, $id, $name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L286)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

    mixed AdminTrackingControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L295)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-clearFilters"></a>clearFilters

    mixed AdminTrackingControllerCore::clearFilters()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTrackingController.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L304)




### <a name="method-clearListOptions"></a>clearListOptions

    mixed AdminTrackingControllerCore::clearListOptions()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L323)




### <a name="method-getList"></a>getList

    mixed AdminTrackingControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTrackingController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L338)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getDescriptionClean"></a>getDescriptionClean

    mixed AdminTrackingControllerCore::getDescriptionClean($description)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminTrackingController.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTrackingController.php#L343)


#### Arguments
* $description **mixed**


