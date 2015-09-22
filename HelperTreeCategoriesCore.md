HelperTreeCategoriesCore
===============






* Class name: HelperTreeCategoriesCore
* Namespace: 
* Parent class: [TreeCore](TreeCore)
* This class is defined in classes\helper\HelperTreeCategories.php line 27



Constants
----------


### DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'tree.tpl'



* This constant is defined in classes\helper\HelperTreeCategories.php line 30


### DEFAULT_NODE_FOLDER_TEMPLATE

    const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'



* This constant is defined in classes\helper\HelperTreeCategories.php line 32


### DEFAULT_NODE_ITEM_TEMPLATE

    const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'



* This constant is defined in classes\helper\HelperTreeCategories.php line 33


### DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* This constant is defined in classes\helper\HelperTreeCategories.php line 29


### DEFAULT_HEADER_TEMPLATE

    const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'



* This constant is defined in classes\helper\HelperTreeCategories.php line 31


Properties
----------


### $_disabled_categories

    private mixed $_disabled_categories





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 33


### $_input_name

    private mixed $_input_name





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 34


### $_lang

    private mixed $_lang





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 35


### $_root_category

    private mixed $_root_category





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 36


### $_selected_categories

    private mixed $_selected_categories





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 37


### $_full_tree

    private mixed $_full_tree = false





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 38


### $_shop

    private mixed $_shop





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 39


### $_use_checkbox

    private mixed $_use_checkbox





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 40


### $_use_search

    private mixed $_use_search





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 41


### $_use_shop_restriction

    private mixed $_use_shop_restriction





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 42


### $_children_only

    private mixed $_children_only = false





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 43


### $_attributes

    protected mixed $_attributes





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 35


### $_context

    private mixed $_context





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 36


### $_data

    protected mixed $_data





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 37


### $_data_search

    protected mixed $_data_search





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 38


### $_headerTemplate

    protected mixed $_headerTemplate





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 39


### $_id_tree

    protected mixed $_id_tree





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 40


### $_id

    private mixed $_id





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 41


### $_node_folder_template

    protected mixed $_node_folder_template





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 42


### $_node_item_template

    protected mixed $_node_item_template





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 43


### $_template

    protected mixed $_template





* Visibility: **protected**
* This property is defined in classes\helper\HelperTreeCategories.php line 44


### $_template_directory

    private string $_template_directory





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 47


### $_title

    private mixed $_title





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 48


### $_no_js

    private mixed $_no_js





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 49


### $_toolbar

    private \TreeToolbar $_toolbar





* Visibility: **private**
* This property is defined in classes\helper\HelperTreeCategories.php line 52


Methods
-------


### __construct

    mixed TreeCore::__construct($id, $data)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 54


#### Arguments
* $id **mixed**
* $data **mixed**



### fillTree

    mixed HelperTreeCategoriesCore::fillTree($categories, $id_category)





* Visibility: **private**
* This method is defined in classes\helper\HelperTreeCategories.php line 62


#### Arguments
* $categories **mixed**
* $id_category **mixed**



### getData

    mixed TreeCore::getData()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 176




### setChildrenOnly

    mixed HelperTreeCategoriesCore::setChildrenOnly($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 132


#### Arguments
* $value **mixed**



### setFullTree

    mixed HelperTreeCategoriesCore::setFullTree($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 138


#### Arguments
* $value **mixed**



### getFullTree

    mixed HelperTreeCategoriesCore::getFullTree()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 144




### setDisabledCategories

    mixed HelperTreeCategoriesCore::setDisabledCategories($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 150


#### Arguments
* $value **mixed**



### getDisabledCategories

    mixed HelperTreeCategoriesCore::getDisabledCategories()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 156




### setInputName

    mixed HelperTreeCategoriesCore::setInputName($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 161


#### Arguments
* $value **mixed**



### getInputName

    mixed HelperTreeCategoriesCore::getInputName()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 167




### setLang

    mixed HelperTreeCategoriesCore::setLang($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 176


#### Arguments
* $value **mixed**



### getLang

    mixed HelperTreeCategoriesCore::getLang()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 182




### getNodeFolderTemplate

    mixed TreeCore::getNodeFolderTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 217




### getNodeItemTemplate

    mixed TreeCore::getNodeItemTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 232




### setRootCategory

    mixed HelperTreeCategoriesCore::setRootCategory($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 209


#### Arguments
* $value **mixed**



### getRootCategory

    mixed HelperTreeCategoriesCore::getRootCategory()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 219




### setSelectedCategories

    mixed HelperTreeCategoriesCore::setSelectedCategories($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 224


#### Arguments
* $value **mixed**



### getSelectedCategories

    mixed HelperTreeCategoriesCore::getSelectedCategories()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 234




### setShop

    mixed HelperTreeCategoriesCore::setShop($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 243


#### Arguments
* $value **mixed**



### getShop

    mixed HelperTreeCategoriesCore::getShop()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 249




### getTemplate

    mixed TreeCore::getTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 247




### setUseCheckBox

    mixed HelperTreeCategoriesCore::setUseCheckBox($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 275


#### Arguments
* $value **mixed**



### setUseSearch

    mixed HelperTreeCategoriesCore::setUseSearch($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 281


#### Arguments
* $value **mixed**



### setUseShopRestriction

    mixed HelperTreeCategoriesCore::setUseShopRestriction($value)





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 287


#### Arguments
* $value **mixed**



### useCheckBox

    mixed HelperTreeCategoriesCore::useCheckBox()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 293




### useSearch

    mixed HelperTreeCategoriesCore::useSearch()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 298




### useShopRestriction

    mixed HelperTreeCategoriesCore::useShopRestriction()





* Visibility: **public**
* This method is defined in classes\helper\HelperTreeCategories.php line 303




### render

    mixed TreeCore::render($data)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 378


#### Arguments
* $data **mixed**



### renderNodes

    mixed TreeCore::renderNodes($data)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 429


#### Arguments
* $data **mixed**



### _disableCategories

    mixed HelperTreeCategoriesCore::_disableCategories($categories, $disabled_categories)





* Visibility: **private**
* This method is defined in classes\helper\HelperTreeCategories.php line 411


#### Arguments
* $categories **mixed**
* $disabled_categories **mixed**



### _getSelectedChildNumbers

    mixed HelperTreeCategoriesCore::_getSelectedChildNumbers($categories, $selected, $parent)





* Visibility: **private**
* This method is defined in classes\helper\HelperTreeCategories.php line 425


#### Arguments
* $categories **mixed**
* $selected **mixed**
* $parent **mixed**



### __toString

    mixed TreeCore::__toString()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 63




### setActions

    mixed TreeCore::setActions($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 68


#### Arguments
* $value **mixed**



### getActions

    mixed TreeCore::getActions()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 78




### setAttribute

    mixed TreeCore::setAttribute($name, $value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 87


#### Arguments
* $name **mixed**
* $value **mixed**



### getAttribute

    mixed TreeCore::getAttribute($name)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 97


#### Arguments
* $name **mixed**



### setAttributes

    mixed TreeCore::setAttributes($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 102


#### Arguments
* $value **mixed**



### setIdTree

    mixed TreeCore::setIdTree($id_tree)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 112


#### Arguments
* $id_tree **mixed**



### getIdTree

    mixed TreeCore::getIdTree()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 118




### getAttributes

    mixed TreeCore::getAttributes()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 123




### setContext

    mixed TreeCore::setContext($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 132


#### Arguments
* $value **mixed**



### getContext

    mixed TreeCore::getContext()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 138




### setDataSearch

    mixed TreeCore::setDataSearch($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 147


#### Arguments
* $value **mixed**



### getDataSearch

    mixed TreeCore::getDataSearch()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 157




### setData

    mixed TreeCore::setData($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 166


#### Arguments
* $value **mixed**



### setHeaderTemplate

    mixed TreeCore::setHeaderTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 185


#### Arguments
* $value **mixed**



### getHeaderTemplate

    mixed TreeCore::getHeaderTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 191




### setId

    mixed TreeCore::setId($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 200


#### Arguments
* $value **mixed**



### getId

    mixed TreeCore::getId()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 206




### setNodeFolderTemplate

    mixed TreeCore::setNodeFolderTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 211


#### Arguments
* $value **mixed**



### setNodeItemTemplate

    mixed TreeCore::setNodeItemTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 226


#### Arguments
* $value **mixed**



### setTemplate

    mixed TreeCore::setTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 241


#### Arguments
* $value **mixed**



### setTemplateDirectory

    \Tree TreeCore::setTemplateDirectory($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 261


#### Arguments
* $value **mixed**



### getTemplateDirectory

    string TreeCore::getTemplateDirectory()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 270




### getTemplateFile

    mixed TreeCore::getTemplateFile($template)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 280


#### Arguments
* $template **mixed**



### setNoJS

    mixed TreeCore::setNoJS($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 312


#### Arguments
* $value **mixed**



### setTitle

    mixed TreeCore::setTitle($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 318


#### Arguments
* $value **mixed**



### getTitle

    mixed TreeCore::getTitle()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 324




### setToolbar

    mixed TreeCore::setToolbar($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 329


#### Arguments
* $value **mixed**



### getToolbar

    mixed TreeCore::getToolbar()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 345




### addAction

    mixed TreeCore::addAction($action)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 358


#### Arguments
* $action **mixed**



### removeActions

    mixed TreeCore::removeActions()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 368




### renderToolbar

    mixed TreeCore::renderToolbar()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 464




### useInput

    mixed TreeCore::useInput()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 469




### useToolbar

    mixed TreeCore::useToolbar()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 474




### _normalizeDirectory

    mixed TreeCore::_normalizeDirectory($directory)





* Visibility: **private**
* This method is defined by [TreeCore](TreeCore)
* This method is defined in classes\helper\HelperTreeCategories.php line 479


#### Arguments
* $directory **mixed**


