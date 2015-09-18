AdminCategoriesControllerCore
===============






* Class name: AdminCategoriesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $_category

    protected object $_category = null





* Visibility: **protected**


### $position_identifier

    protected mixed $position_identifier = 'id_category_to_move'





* Visibility: **protected**


### $remove_products

    public boolean $remove_products = true





* Visibility: **public**


### $disable_products

    public boolean $disable_products = false





* Visibility: **public**


### $original_filter

    private mixed $original_filter = ''





* Visibility: **private**


### $object

    public \Category $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminCategoriesControllerCore::__construct()





* Visibility: **public**




### init

    mixed AdminCategoriesControllerCore::init()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminCategoriesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initContent

    mixed AdminCategoriesControllerCore::initContent()





* Visibility: **public**




### setMedia

    mixed AdminCategoriesControllerCore::setMedia()





* Visibility: **public**




### renderList

    mixed AdminCategoriesControllerCore::renderList()





* Visibility: **public**




### getList

    mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### renderView

    mixed AdminCategoriesControllerCore::renderView()





* Visibility: **public**




### initToolbar

    mixed AdminCategoriesControllerCore::initToolbar()





* Visibility: **public**




### initProcess

    mixed AdminCategoriesControllerCore::initProcess()





* Visibility: **public**




### renderKpis

    mixed AdminCategoriesControllerCore::renderKpis()





* Visibility: **public**




### renderForm

    mixed AdminCategoriesControllerCore::renderForm()





* Visibility: **public**




### postProcess

    mixed AdminCategoriesControllerCore::postProcess()





* Visibility: **public**




### processForceDeleteImage

    mixed AdminCategoriesControllerCore::processForceDeleteImage()





* Visibility: **public**




### processAdd

    mixed AdminCategoriesControllerCore::processAdd()





* Visibility: **public**




### setDeleteMode

    mixed AdminCategoriesControllerCore::setDeleteMode()





* Visibility: **protected**




### processBulkDelete

    mixed AdminCategoriesControllerCore::processBulkDelete()





* Visibility: **protected**




### processDelete

    mixed AdminCategoriesControllerCore::processDelete()





* Visibility: **public**




### processFatherlessProducts

    mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)





* Visibility: **public**


#### Arguments
* $id_parent **mixed**



### processPosition

    mixed AdminCategoriesControllerCore::processPosition()





* Visibility: **public**




### postImage

    mixed AdminCategoriesControllerCore::postImage($id)





* Visibility: **protected**


#### Arguments
* $id **mixed**



### getDescriptionClean

    mixed AdminCategoriesControllerCore::getDescriptionClean($description)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $description **mixed**



### ajaxProcessUpdatePositions

    mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**




### ajaxProcessStatusCategory

    mixed AdminCategoriesControllerCore::ajaxProcessStatusCategory()





* Visibility: **public**



