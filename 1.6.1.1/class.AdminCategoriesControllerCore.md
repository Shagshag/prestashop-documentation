Class AdminCategoriesControllerCore
=====================





* Class name: AdminCategoriesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCategoriesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L30)



Properties
----------

* [$_category](#property-$_category)
* [$disable_products](#property-$disable_products)
* [$object](#property-$object)
* [$original_filter](#property-$original_filter)
* [$position_identifier](#property-$position_identifier)
* [$remove_products](#property-$remove_products)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessStatusCategory](#method-ajaxProcessStatusCategory)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [getDescriptionClean](#method-getDescriptionClean)
* [getList](#method-getList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processFatherlessProducts](#method-processFatherlessProducts)
* [processForceDeleteImage](#method-processForceDeleteImage)
* [processPosition](#method-processPosition)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [setDeleteMode](#method-setDeleteMode)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$_category"></a>$_category

    protected object $_category = null





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L35)


### <a name="property-$disable_products"></a>$disable_products

    public boolean $disable_products = false





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L42)


### <a name="property-$object"></a>$object

    public \Category $object





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L30)


### <a name="property-$original_filter"></a>$original_filter

    private mixed $original_filter = ''





* Visibility: **private**
* Source: [controllers/admin/AdminCategoriesController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L44)


### <a name="property-$position_identifier"></a>$position_identifier

    protected mixed $position_identifier = 'id_category_to_move'





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L36)


### <a name="property-$remove_products"></a>$remove_products

    public boolean $remove_products = true





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L39)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCategoriesControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L46)




### <a name="method-ajaxProcessStatusCategory"></a>ajaxProcessStatusCategory

    mixed AdminCategoriesControllerCore::ajaxProcessStatusCategory()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L857)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

    mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 821](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L821)




### <a name="method-getDescriptionClean"></a>getDescriptionClean

    mixed AdminCategoriesControllerCore::getDescriptionClean($description)





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCategoriesController.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L816)


#### Arguments
* $description **mixed**



### <a name="method-getList"></a>getList

    mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L251)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-init"></a>init

    mixed AdminCategoriesControllerCore::init()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L107)




### <a name="method-initContent"></a>initContent

    mixed AdminCategoriesControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L189)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCategoriesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L168)




### <a name="method-initProcess"></a>initProcess

    mixed AdminCategoriesControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L333)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminCategoriesControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L272)




### <a name="method-postImage"></a>postImage

    mixed AdminCategoriesControllerCore::postImage($id)





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L787)


#### Arguments
* $id **mixed**



### <a name="method-postProcess"></a>postProcess

    mixed AdminCategoriesControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L639)




### <a name="method-processAdd"></a>processAdd

    mixed AdminCategoriesControllerCore::processAdd()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L662)




### <a name="method-processBulkDelete"></a>processBulkDelete

    mixed AdminCategoriesControllerCore::processBulkDelete()





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L703)




### <a name="method-processDelete"></a>processDelete

    mixed AdminCategoriesControllerCore::processDelete()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 728](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L728)




### <a name="method-processFatherlessProducts"></a>processFatherlessProducts

    mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L746)


#### Arguments
* $id_parent **mixed**



### <a name="method-processForceDeleteImage"></a>processForceDeleteImage

    mixed AdminCategoriesControllerCore::processForceDeleteImage()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 654](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L654)




### <a name="method-processPosition"></a>processPosition

    mixed AdminCategoriesControllerCore::processPosition()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 771](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L771)




### <a name="method-renderForm"></a>renderForm

    mixed AdminCategoriesControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L424)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminCategoriesControllerCore::renderKpis()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L362)




### <a name="method-renderList"></a>renderList

    mixed AdminCategoriesControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L209)




### <a name="method-renderView"></a>renderView

    mixed AdminCategoriesControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L266)




### <a name="method-setDeleteMode"></a>setDeleteMode

    mixed AdminCategoriesControllerCore::setDeleteMode()





* Visibility: **protected**
* Source: [controllers/admin/AdminCategoriesController.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L691)




### <a name="method-setMedia"></a>setMedia

    mixed AdminCategoriesControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/admin/AdminCategoriesController.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCategoriesController.php#L202)



