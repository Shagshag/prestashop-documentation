TreeCore
===============






* Class name: TreeCore
* Namespace: 

* This class is defined in [classes/tree/Tree.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#27)



Constants
----------


### DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* This constant is defined in [classes/tree/Tree.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#29)


### DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'tree.tpl'



* This constant is defined in [classes/tree/Tree.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#30)


### DEFAULT_HEADER_TEMPLATE

    const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'



* This constant is defined in [classes/tree/Tree.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#31)


### DEFAULT_NODE_FOLDER_TEMPLATE

    const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'



* This constant is defined in [classes/tree/Tree.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#32)


### DEFAULT_NODE_ITEM_TEMPLATE

    const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'



* This constant is defined in [classes/tree/Tree.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#33)


Properties
----------


### $_attributes

    protected mixed $_attributes





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#35)


### $_context

    private mixed $_context





* Visibility: **private**
* This property is defined in [classes/tree/Tree.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#36)


### $_data

    protected mixed $_data





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#37)


### $_data_search

    protected mixed $_data_search





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#38)


### $_headerTemplate

    protected mixed $_headerTemplate





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#39)


### $_id_tree

    protected mixed $_id_tree





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#40)


### $_id

    private mixed $_id





* Visibility: **private**
* This property is defined in [classes/tree/Tree.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#41)


### $_node_folder_template

    protected mixed $_node_folder_template





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#42)


### $_node_item_template

    protected mixed $_node_item_template





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#43)


### $_template

    protected mixed $_template





* Visibility: **protected**
* This property is defined in [classes/tree/Tree.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#44)


### $_template_directory

    private string $_template_directory





* Visibility: **private**
* This property is defined in [classes/tree/Tree.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#47)


### $_title

    private mixed $_title





* Visibility: **private**
* This property is defined in [classes/tree/Tree.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#48)


### $_no_js

    private mixed $_no_js





* Visibility: **private**
* This property is defined in [classes/tree/Tree.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#49)


### $_toolbar

    private \TreeToolbar $_toolbar





* Visibility: **private**
* This property is defined in [classes/tree/Tree.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#52)


Methods
-------


### __construct

    mixed TreeCore::__construct($id, $data)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#54)


#### Arguments
* $id **mixed**
* $data **mixed**



### __toString

    mixed TreeCore::__toString()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#63)




### setActions

    mixed TreeCore::setActions($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#68)


#### Arguments
* $value **mixed**



### getActions

    mixed TreeCore::getActions()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#78)




### setAttribute

    mixed TreeCore::setAttribute($name, $value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#87)


#### Arguments
* $name **mixed**
* $value **mixed**



### getAttribute

    mixed TreeCore::getAttribute($name)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#97)


#### Arguments
* $name **mixed**



### setAttributes

    mixed TreeCore::setAttributes($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#102)


#### Arguments
* $value **mixed**



### setIdTree

    mixed TreeCore::setIdTree($id_tree)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#112)


#### Arguments
* $id_tree **mixed**



### getIdTree

    mixed TreeCore::getIdTree()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#118)




### getAttributes

    mixed TreeCore::getAttributes()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#123)




### setContext

    mixed TreeCore::setContext($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#132)


#### Arguments
* $value **mixed**



### getContext

    mixed TreeCore::getContext()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#138)




### setDataSearch

    mixed TreeCore::setDataSearch($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#147)


#### Arguments
* $value **mixed**



### getDataSearch

    mixed TreeCore::getDataSearch()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#157)




### setData

    mixed TreeCore::setData($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#166)


#### Arguments
* $value **mixed**



### getData

    mixed TreeCore::getData()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#176)




### setHeaderTemplate

    mixed TreeCore::setHeaderTemplate($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#185)


#### Arguments
* $value **mixed**



### getHeaderTemplate

    mixed TreeCore::getHeaderTemplate()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#191)




### setId

    mixed TreeCore::setId($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#200)


#### Arguments
* $value **mixed**



### getId

    mixed TreeCore::getId()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#206)




### setNodeFolderTemplate

    mixed TreeCore::setNodeFolderTemplate($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#211)


#### Arguments
* $value **mixed**



### getNodeFolderTemplate

    mixed TreeCore::getNodeFolderTemplate()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#217)




### setNodeItemTemplate

    mixed TreeCore::setNodeItemTemplate($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#226)


#### Arguments
* $value **mixed**



### getNodeItemTemplate

    mixed TreeCore::getNodeItemTemplate()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#232)




### setTemplate

    mixed TreeCore::setTemplate($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#241)


#### Arguments
* $value **mixed**



### getTemplate

    mixed TreeCore::getTemplate()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#247)




### setTemplateDirectory

    \Tree TreeCore::setTemplateDirectory($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#261)


#### Arguments
* $value **mixed**



### getTemplateDirectory

    string TreeCore::getTemplateDirectory()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#270)




### getTemplateFile

    mixed TreeCore::getTemplateFile($template)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#280)


#### Arguments
* $template **mixed**



### setNoJS

    mixed TreeCore::setNoJS($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#312)


#### Arguments
* $value **mixed**



### setTitle

    mixed TreeCore::setTitle($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#318)


#### Arguments
* $value **mixed**



### getTitle

    mixed TreeCore::getTitle()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#324)




### setToolbar

    mixed TreeCore::setToolbar($value)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#329)


#### Arguments
* $value **mixed**



### getToolbar

    mixed TreeCore::getToolbar()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#345)




### addAction

    mixed TreeCore::addAction($action)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#358)


#### Arguments
* $action **mixed**



### removeActions

    mixed TreeCore::removeActions()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#368)




### render

    mixed TreeCore::render($data)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#378)


#### Arguments
* $data **mixed**



### renderNodes

    mixed TreeCore::renderNodes($data)





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#429)


#### Arguments
* $data **mixed**



### renderToolbar

    mixed TreeCore::renderToolbar()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#464)




### useInput

    mixed TreeCore::useInput()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#469)




### useToolbar

    mixed TreeCore::useToolbar()





* Visibility: **public**
* This method is defined in [classes/tree/Tree.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#474)




### _normalizeDirectory

    mixed TreeCore::_normalizeDirectory($directory)





* Visibility: **private**
* This method is defined in [classes/tree/Tree.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/Tree.php#479)


#### Arguments
* $directory **mixed**


