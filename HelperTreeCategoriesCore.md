HelperTreeCategoriesCore
===============






* Class name: HelperTreeCategoriesCore
* Namespace: 
* Parent class: [TreeCore](TreeCore.md)



Constants
----------


### DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'tree.tpl'





### DEFAULT_NODE_FOLDER_TEMPLATE

    const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'





### DEFAULT_NODE_ITEM_TEMPLATE

    const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'





### DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'





### DEFAULT_HEADER_TEMPLATE

    const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'





Properties
----------


### $_disabled_categories

    private mixed $_disabled_categories





* Visibility: **private**


### $_input_name

    private mixed $_input_name





* Visibility: **private**


### $_lang

    private mixed $_lang





* Visibility: **private**


### $_root_category

    private mixed $_root_category





* Visibility: **private**


### $_selected_categories

    private mixed $_selected_categories





* Visibility: **private**


### $_full_tree

    private mixed $_full_tree = false





* Visibility: **private**


### $_shop

    private mixed $_shop





* Visibility: **private**


### $_use_checkbox

    private mixed $_use_checkbox





* Visibility: **private**


### $_use_search

    private mixed $_use_search





* Visibility: **private**


### $_use_shop_restriction

    private mixed $_use_shop_restriction





* Visibility: **private**


### $_children_only

    private mixed $_children_only = false





* Visibility: **private**


### $_attributes

    protected mixed $_attributes





* Visibility: **protected**


### $_context

    private mixed $_context





* Visibility: **private**


### $_data

    protected mixed $_data





* Visibility: **protected**


### $_data_search

    protected mixed $_data_search





* Visibility: **protected**


### $_headerTemplate

    protected mixed $_headerTemplate





* Visibility: **protected**


### $_id_tree

    protected mixed $_id_tree





* Visibility: **protected**


### $_id

    private mixed $_id





* Visibility: **private**


### $_node_folder_template

    protected mixed $_node_folder_template





* Visibility: **protected**


### $_node_item_template

    protected mixed $_node_item_template





* Visibility: **protected**


### $_template

    protected mixed $_template





* Visibility: **protected**


### $_template_directory

    private string $_template_directory





* Visibility: **private**


### $_title

    private mixed $_title





* Visibility: **private**


### $_no_js

    private mixed $_no_js





* Visibility: **private**


### $_toolbar

    private \TreeToolbar $_toolbar





* Visibility: **private**


Methods
-------


### __construct

    mixed TreeCore::__construct($id, $data)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $id **mixed**
* $data **mixed**



### fillTree

    mixed HelperTreeCategoriesCore::fillTree($categories, $id_category)





* Visibility: **private**


#### Arguments
* $categories **mixed**
* $id_category **mixed**



### getData

    mixed TreeCore::getData()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setChildrenOnly

    mixed HelperTreeCategoriesCore::setChildrenOnly($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### setFullTree

    mixed HelperTreeCategoriesCore::setFullTree($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getFullTree

    mixed HelperTreeCategoriesCore::getFullTree()





* Visibility: **public**




### setDisabledCategories

    mixed HelperTreeCategoriesCore::setDisabledCategories($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getDisabledCategories

    mixed HelperTreeCategoriesCore::getDisabledCategories()





* Visibility: **public**




### setInputName

    mixed HelperTreeCategoriesCore::setInputName($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getInputName

    mixed HelperTreeCategoriesCore::getInputName()





* Visibility: **public**




### setLang

    mixed HelperTreeCategoriesCore::setLang($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getLang

    mixed HelperTreeCategoriesCore::getLang()





* Visibility: **public**




### getNodeFolderTemplate

    mixed TreeCore::getNodeFolderTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### getNodeItemTemplate

    mixed TreeCore::getNodeItemTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setRootCategory

    mixed HelperTreeCategoriesCore::setRootCategory($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getRootCategory

    mixed HelperTreeCategoriesCore::getRootCategory()





* Visibility: **public**




### setSelectedCategories

    mixed HelperTreeCategoriesCore::setSelectedCategories($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getSelectedCategories

    mixed HelperTreeCategoriesCore::getSelectedCategories()





* Visibility: **public**




### setShop

    mixed HelperTreeCategoriesCore::setShop($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getShop

    mixed HelperTreeCategoriesCore::getShop()





* Visibility: **public**




### getTemplate

    mixed TreeCore::getTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setUseCheckBox

    mixed HelperTreeCategoriesCore::setUseCheckBox($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### setUseSearch

    mixed HelperTreeCategoriesCore::setUseSearch($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### setUseShopRestriction

    mixed HelperTreeCategoriesCore::setUseShopRestriction($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### useCheckBox

    mixed HelperTreeCategoriesCore::useCheckBox()





* Visibility: **public**




### useSearch

    mixed HelperTreeCategoriesCore::useSearch()





* Visibility: **public**




### useShopRestriction

    mixed HelperTreeCategoriesCore::useShopRestriction()





* Visibility: **public**




### render

    mixed TreeCore::render($data)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $data **mixed**



### renderNodes

    mixed TreeCore::renderNodes($data)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $data **mixed**



### _disableCategories

    mixed HelperTreeCategoriesCore::_disableCategories($categories, $disabled_categories)





* Visibility: **private**


#### Arguments
* $categories **mixed**
* $disabled_categories **mixed**



### _getSelectedChildNumbers

    mixed HelperTreeCategoriesCore::_getSelectedChildNumbers($categories, $selected, $parent)





* Visibility: **private**


#### Arguments
* $categories **mixed**
* $selected **mixed**
* $parent **mixed**



### __toString

    mixed TreeCore::__toString()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setActions

    mixed TreeCore::setActions($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getActions

    mixed TreeCore::getActions()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setAttribute

    mixed TreeCore::setAttribute($name, $value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $name **mixed**
* $value **mixed**



### getAttribute

    mixed TreeCore::getAttribute($name)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $name **mixed**



### setAttributes

    mixed TreeCore::setAttributes($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### setIdTree

    mixed TreeCore::setIdTree($id_tree)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $id_tree **mixed**



### getIdTree

    mixed TreeCore::getIdTree()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### getAttributes

    mixed TreeCore::getAttributes()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setContext

    mixed TreeCore::setContext($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getContext

    mixed TreeCore::getContext()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setDataSearch

    mixed TreeCore::setDataSearch($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getDataSearch

    mixed TreeCore::getDataSearch()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setData

    mixed TreeCore::setData($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### setHeaderTemplate

    mixed TreeCore::setHeaderTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getHeaderTemplate

    mixed TreeCore::getHeaderTemplate()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setId

    mixed TreeCore::setId($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getId

    mixed TreeCore::getId()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setNodeFolderTemplate

    mixed TreeCore::setNodeFolderTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### setNodeItemTemplate

    mixed TreeCore::setNodeItemTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### setTemplate

    mixed TreeCore::setTemplate($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### setTemplateDirectory

    \Tree TreeCore::setTemplateDirectory($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getTemplateDirectory

    string TreeCore::getTemplateDirectory()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### getTemplateFile

    mixed TreeCore::getTemplateFile($template)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $template **mixed**



### setNoJS

    mixed TreeCore::setNoJS($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### setTitle

    mixed TreeCore::setTitle($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getTitle

    mixed TreeCore::getTitle()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### setToolbar

    mixed TreeCore::setToolbar($value)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $value **mixed**



### getToolbar

    mixed TreeCore::getToolbar()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### addAction

    mixed TreeCore::addAction($action)





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $action **mixed**



### removeActions

    mixed TreeCore::removeActions()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### renderToolbar

    mixed TreeCore::renderToolbar()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### useInput

    mixed TreeCore::useInput()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### useToolbar

    mixed TreeCore::useToolbar()





* Visibility: **public**
* This method is defined by [TreeCore](TreeCore.md)




### _normalizeDirectory

    mixed TreeCore::_normalizeDirectory($directory)





* Visibility: **private**
* This method is defined by [TreeCore](TreeCore.md)


#### Arguments
* $directory **mixed**


