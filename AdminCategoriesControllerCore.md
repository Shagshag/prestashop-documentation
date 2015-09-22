AdminCategoriesControllerCore
===============






* Class name: AdminCategoriesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminCategoriesController.php line 30





Properties
----------


### $_category

    protected object $_category = null





* Visibility: **protected**
* This property is defined in controllers\admin\AdminCategoriesController.php line 35


### $position_identifier

    protected mixed $position_identifier = 'id_category_to_move'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminCategoriesController.php line 36


### $remove_products

    public boolean $remove_products = true





* Visibility: **public**
* This property is defined in controllers\admin\AdminCategoriesController.php line 39


### $disable_products

    public boolean $disable_products = false





* Visibility: **public**
* This property is defined in controllers\admin\AdminCategoriesController.php line 42


### $original_filter

    private mixed $original_filter = ''





* Visibility: **private**
* This property is defined in controllers\admin\AdminCategoriesController.php line 44


### $object

    public \Category $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminCategoriesController.php line 30


Methods
-------


### __construct

    mixed AdminCategoriesControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 46




### init

    mixed AdminCategoriesControllerCore::init()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 107




### initPageHeaderToolbar

    mixed AdminCategoriesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 168




### initContent

    mixed AdminCategoriesControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 189




### setMedia

    mixed AdminCategoriesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 202




### renderList

    mixed AdminCategoriesControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 209




### getList

    mixed AdminCategoriesControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 251


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
* This method is defined in controllers\admin\AdminCategoriesController.php line 266




### initToolbar

    mixed AdminCategoriesControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 272




### initProcess

    mixed AdminCategoriesControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 333




### renderKpis

    mixed AdminCategoriesControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 362




### renderForm

    mixed AdminCategoriesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 424




### postProcess

    mixed AdminCategoriesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 639




### processForceDeleteImage

    mixed AdminCategoriesControllerCore::processForceDeleteImage()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 654




### processAdd

    mixed AdminCategoriesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 662




### setDeleteMode

    mixed AdminCategoriesControllerCore::setDeleteMode()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCategoriesController.php line 691




### processBulkDelete

    mixed AdminCategoriesControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCategoriesController.php line 703




### processDelete

    mixed AdminCategoriesControllerCore::processDelete()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 728




### processFatherlessProducts

    mixed AdminCategoriesControllerCore::processFatherlessProducts($id_parent)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 746


#### Arguments
* $id_parent **mixed**



### processPosition

    mixed AdminCategoriesControllerCore::processPosition()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 771




### postImage

    mixed AdminCategoriesControllerCore::postImage($id)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCategoriesController.php line 787


#### Arguments
* $id **mixed**



### getDescriptionClean

    mixed AdminCategoriesControllerCore::getDescriptionClean($description)





* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminCategoriesController.php line 816


#### Arguments
* $description **mixed**



### ajaxProcessUpdatePositions

    mixed AdminCategoriesControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 821




### ajaxProcessStatusCategory

    mixed AdminCategoriesControllerCore::ajaxProcessStatusCategory()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCategoriesController.php line 857



