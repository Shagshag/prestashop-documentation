AdminCategoriesControllerCore
===============






* Class name: AdminCategoriesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminCategoriesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L30)





Properties
----------

* [$_category](#property-$_category)
* [$position_identifier](#property-$position_identifier)
* [$remove_products](#property-$remove_products)
* [$disable_products](#property-$disable_products)
* [$original_filter](#property-$original_filter)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [init](#method-init)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initContent](#method-initContent)
* [setMedia](#method-setMedia)
* [renderList](#method-renderList)
* [getList](#method-getList)
* [renderView](#method-renderView)
* [initToolbar](#method-initToolbar)
* [initProcess](#method-initProcess)
* [renderKpis](#method-renderKpis)
* [renderForm](#method-renderForm)
* [postProcess](#method-postProcess)
* [processForceDeleteImage](#method-processForceDeleteImage)
* [processAdd](#method-processAdd)
* [setDeleteMode](#method-setDeleteMode)
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processFatherlessProducts](#method-processFatherlessProducts)
* [processPosition](#method-processPosition)
* [postImage](#method-postImage)
* [getDescriptionClean](#method-getDescriptionClean)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [ajaxProcessStatusCategory](#method-ajaxProcessStatusCategory)




Properties
----------


### <a name="property-$_category"></a>$_category

    protected object $_category = null





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCategoriesController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L35)


### <a name="property-$position_identifier"></a>$position_identifier

    protected mixed $position_identifier = 'id_category_to_move'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCategoriesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L36)


### <a name="property-$remove_products"></a>$remove_products

    public boolean $remove_products = true





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCategoriesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L39)


### <a name="property-$disable_products"></a>$disable_products

    public boolean $disable_products = false





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCategoriesController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L42)


### <a name="property-$original_filter"></a>$original_filter

    private mixed $original_filter = ''





* Visibility: **private**
* This property is defined in [controllers/admin/AdminCategoriesController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L44)


### <a name="property-$object"></a>$object

    public \Category $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCategoriesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCategoriesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L46)




### <a name="method-init"></a>init

    mixed AdminCategoriesControllerCore::init()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L107)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCategoriesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L168)




### <a name="method-initContent"></a>initContent

    mixed AdminCategoriesControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L189)




### <a name="method-setMedia"></a>setMedia

    mixed AdminCategoriesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L202)




### <a name="method-renderList"></a>renderList

    mixed AdminCategoriesControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L209)




### <a name="method-getList"></a>getList

    mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L251)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-renderView"></a>renderView

    mixed AdminCategoriesControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L266)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminCategoriesControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L272)




### <a name="method-initProcess"></a>initProcess

    mixed AdminCategoriesControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L333)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminCategoriesControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L362)




### <a name="method-renderForm"></a>renderForm

    mixed AdminCategoriesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L424)




### <a name="method-postProcess"></a>postProcess

    mixed AdminCategoriesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L639)




### <a name="method-processForceDeleteImage"></a>processForceDeleteImage

    mixed AdminCategoriesControllerCore::processForceDeleteImage()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 654](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L654)




### <a name="method-processAdd"></a>processAdd

    mixed AdminCategoriesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L662)




### <a name="method-setDeleteMode"></a>setDeleteMode

    mixed AdminCategoriesControllerCore::setDeleteMode()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L691)




### <a name="method-processBulkDelete"></a>processBulkDelete

    mixed AdminCategoriesControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L703)




### <a name="method-processDelete"></a>processDelete

    mixed AdminCategoriesControllerCore::processDelete()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 728](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L728)




### <a name="method-processFatherlessProducts"></a>processFatherlessProducts

    mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L746)


#### Arguments
* $id_parent **mixed**



### <a name="method-processPosition"></a>processPosition

    mixed AdminCategoriesControllerCore::processPosition()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 771](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L771)




### <a name="method-postImage"></a>postImage

    mixed AdminCategoriesControllerCore::postImage($id)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L787)


#### Arguments
* $id **mixed**



### <a name="method-getDescriptionClean"></a>getDescriptionClean

    mixed AdminCategoriesControllerCore::getDescriptionClean($description)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminCategoriesController.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L816)


#### Arguments
* $description **mixed**



### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

    mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 821](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L821)




### <a name="method-ajaxProcessStatusCategory"></a>ajaxProcessStatusCategory

    mixed AdminCategoriesControllerCore::ajaxProcessStatusCategory()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCategoriesController.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L857)



