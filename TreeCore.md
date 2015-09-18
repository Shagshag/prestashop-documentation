TreeCore
===============






* Class name: TreeCore
* Namespace: 



Constants
----------


### DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'





### DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'tree.tpl'





### DEFAULT_HEADER_TEMPLATE

    const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'





### DEFAULT_NODE_FOLDER_TEMPLATE

    const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'





### DEFAULT_NODE_ITEM_TEMPLATE

    const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'





Properties
----------


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


#### Arguments
* $id **mixed**
* $data **mixed**



### __toString

    mixed TreeCore::__toString()





* Visibility: **public**




### setActions

    mixed TreeCore::setActions($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getActions

    mixed TreeCore::getActions()





* Visibility: **public**




### setAttribute

    mixed TreeCore::setAttribute($name, $value)





* Visibility: **public**


#### Arguments
* $name **mixed**
* $value **mixed**



### getAttribute

    mixed TreeCore::getAttribute($name)





* Visibility: **public**


#### Arguments
* $name **mixed**



### setAttributes

    mixed TreeCore::setAttributes($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### setIdTree

    mixed TreeCore::setIdTree($id_tree)





* Visibility: **public**


#### Arguments
* $id_tree **mixed**



### getIdTree

    mixed TreeCore::getIdTree()





* Visibility: **public**




### getAttributes

    mixed TreeCore::getAttributes()





* Visibility: **public**




### setContext

    mixed TreeCore::setContext($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getContext

    mixed TreeCore::getContext()





* Visibility: **public**




### setDataSearch

    mixed TreeCore::setDataSearch($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getDataSearch

    mixed TreeCore::getDataSearch()





* Visibility: **public**




### setData

    mixed TreeCore::setData($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getData

    mixed TreeCore::getData()





* Visibility: **public**




### setHeaderTemplate

    mixed TreeCore::setHeaderTemplate($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getHeaderTemplate

    mixed TreeCore::getHeaderTemplate()





* Visibility: **public**




### setId

    mixed TreeCore::setId($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getId

    mixed TreeCore::getId()





* Visibility: **public**




### setNodeFolderTemplate

    mixed TreeCore::setNodeFolderTemplate($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getNodeFolderTemplate

    mixed TreeCore::getNodeFolderTemplate()





* Visibility: **public**




### setNodeItemTemplate

    mixed TreeCore::setNodeItemTemplate($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getNodeItemTemplate

    mixed TreeCore::getNodeItemTemplate()





* Visibility: **public**




### setTemplate

    mixed TreeCore::setTemplate($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getTemplate

    mixed TreeCore::getTemplate()





* Visibility: **public**




### setTemplateDirectory

    \Tree TreeCore::setTemplateDirectory($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getTemplateDirectory

    string TreeCore::getTemplateDirectory()





* Visibility: **public**




### getTemplateFile

    mixed TreeCore::getTemplateFile($template)





* Visibility: **public**


#### Arguments
* $template **mixed**



### setNoJS

    mixed TreeCore::setNoJS($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### setTitle

    mixed TreeCore::setTitle($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getTitle

    mixed TreeCore::getTitle()





* Visibility: **public**




### setToolbar

    mixed TreeCore::setToolbar($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getToolbar

    mixed TreeCore::getToolbar()





* Visibility: **public**




### addAction

    mixed TreeCore::addAction($action)





* Visibility: **public**


#### Arguments
* $action **mixed**



### removeActions

    mixed TreeCore::removeActions()





* Visibility: **public**




### render

    mixed TreeCore::render($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### renderNodes

    mixed TreeCore::renderNodes($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### renderToolbar

    mixed TreeCore::renderToolbar()





* Visibility: **public**




### useInput

    mixed TreeCore::useInput()





* Visibility: **public**




### useToolbar

    mixed TreeCore::useToolbar()





* Visibility: **public**




### _normalizeDirectory

    mixed TreeCore::_normalizeDirectory($directory)





* Visibility: **private**


#### Arguments
* $directory **mixed**


