AdminAttributesGroupsControllerCore
===============






* Class name: AdminAttributesGroupsControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminAttributesGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L30)





Properties
----------

* [$bootstrap](#property-$bootstrap)
* [$id_attribute](#property-$id_attribute)
* [$position_identifier](#property-$position_identifier)
* [$attribute_name](#property-$attribute_name)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [renderForm](#method-renderForm)
* [renderFormAttributes](#method-renderFormAttributes)
* [init](#method-init)
* [processAdd](#method-processAdd)
* [processUpdate](#method-processUpdate)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [initProcess](#method-initProcess)
* [setTypeAttribute](#method-setTypeAttribute)
* [processPosition](#method-processPosition)
* [processSave](#method-processSave)
* [postProcess](#method-postProcess)
* [getList](#method-getList)
* [processBulkDelete](#method-processBulkDelete)
* [ajaxProcessUpdateGroupsPositions](#method-ajaxProcessUpdateGroupsPositions)
* [ajaxProcessUpdateAttributesPositions](#method-ajaxProcessUpdateAttributesPositions)




Properties
----------


### <a name="property-$bootstrap"></a>$bootstrap

    public mixed $bootstrap = true





* Visibility: **public**
* This property is defined in [controllers/admin/AdminAttributesGroupsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L32)


### <a name="property-$id_attribute"></a>$id_attribute

    protected mixed $id_attribute





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminAttributesGroupsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L33)


### <a name="property-$position_identifier"></a>$position_identifier

    protected mixed $position_identifier = 'id_attribute_group'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminAttributesGroupsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L34)


### <a name="property-$attribute_name"></a>$attribute_name

    protected mixed $attribute_name





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminAttributesGroupsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L35)


### <a name="property-$object"></a>$object

    public \AttributeGroup $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminAttributesGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminAttributesGroupsControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L37)




### <a name="method-renderList"></a>renderList

    mixed AdminAttributesGroupsControllerCore::renderList()

AdminController::renderList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L91)




### <a name="method-renderView"></a>renderView

    mixed AdminAttributesGroupsControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L101)




### <a name="method-renderForm"></a>renderForm

    mixed AdminAttributesGroupsControllerCore::renderForm()

AdminController::renderForm() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L165)




### <a name="method-renderFormAttributes"></a>renderFormAttributes

    mixed AdminAttributesGroupsControllerCore::renderFormAttributes()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L244)




### <a name="method-init"></a>init

    mixed AdminAttributesGroupsControllerCore::init()

AdminController::init() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L380)




### <a name="method-processAdd"></a>processAdd

    mixed AdminAttributesGroupsControllerCore::processAdd()

Override processAdd to change SaveAndStay button action



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L397)




### <a name="method-processUpdate"></a>processUpdate

    mixed AdminAttributesGroupsControllerCore::processUpdate()

Override processUpdate to change SaveAndStay button action



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L437)




### <a name="method-initContent"></a>initContent

    mixed AdminAttributesGroupsControllerCore::initContent()

AdminController::initContent() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L464)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminAttributesGroupsControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L507)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminAttributesGroupsControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L533)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

    mixed AdminAttributesGroupsControllerCore::initToolbarTitle()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L586)




### <a name="method-initProcess"></a>initProcess

    mixed AdminAttributesGroupsControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L636)




### <a name="method-setTypeAttribute"></a>setTypeAttribute

    mixed AdminAttributesGroupsControllerCore::setTypeAttribute()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L658)




### <a name="method-processPosition"></a>processPosition

    mixed AdminAttributesGroupsControllerCore::processPosition()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L671)




### <a name="method-processSave"></a>processSave

    mixed AdminAttributesGroupsControllerCore::processSave()

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 698](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L698)




### <a name="method-postProcess"></a>postProcess

    mixed AdminAttributesGroupsControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L711)




### <a name="method-getList"></a>getList

    mixed AdminAttributesGroupsControllerCore::getList(integer $id_lang, string|null $order_by, string|null $order_way, integer $start, integer|null $limit, integer|boolean $id_lang_shop)

AdminController::getList() override



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L827)


#### Arguments
* $id_lang **integer**
* $order_by **string|null**
* $order_way **string|null**
* $start **integer**
* $limit **integer|null**
* $id_lang_shop **integer|boolean**



### <a name="method-processBulkDelete"></a>processBulkDelete

    mixed AdminAttributesGroupsControllerCore::processBulkDelete()

Overrides parent to delete items from sublist



* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 863](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L863)




### <a name="method-ajaxProcessUpdateGroupsPositions"></a>ajaxProcessUpdateGroupsPositions

    mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateGroupsPositions()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 881](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L881)




### <a name="method-ajaxProcessUpdateAttributesPositions"></a>ajaxProcessUpdateAttributesPositions

    mixed AdminAttributesGroupsControllerCore::ajaxProcessUpdateAttributesPositions()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminAttributesGroupsController.php line 914](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributesGroupsController.php#L914)



